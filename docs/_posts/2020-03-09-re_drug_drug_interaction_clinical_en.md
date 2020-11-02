---
layout: model
title: Relation Extraction Model Clinical
author: John Snow Labs
name: re_drug_drug_interaction_clinical
class: RelationExtractionModel
language: en
repository: clinical/models
date: 2020-03-09
tags: [clinical,relation_extraction]
article_header:
   type: cover
use_language_switcher: "Python-Scala-Java"
---

{:.h2_title}
## Description 




{:.btn-box}
<button class="button button-orange" disabled>Live Demo</button><br/>[Open in Colab](https://colab.research.google.com/github/JohnSnowLabs/spark-nlp-workshop/blob/master/tutorials/Certification_Trainings/Healthcare/10.Clinical_Relation_Extraction.ipynb){:.button.button-orange.button-orange-trans.co.button-icon}<br/>[Download](https://s3.amazonaws.com/auxdata.johnsnowlabs.com/clinical/models/re_drug_drug_interaction_clinical_en_2.5.5_2.4_1599156924424.zip){:.button.button-orange.button-orange-trans.arr.button-icon}<br/>

## How to use 
<div class="tabs-box" markdown="1">

{% include programmingLanguageSelectScalaPython.html %}

```python
model = RelationExtractionModel.pretrained("re_drug_drug_interaction_clinical","en","clinical/models")\
	.setInputCols("word_embeddings","chunk","pos","dependency")\
	.setOutputCol("category")
```

```scala
val model = RelationExtractionModel.pretrained("re_drug_drug_interaction_clinical","en","clinical/models")
	.setInputCols("word_embeddings","chunk","pos","dependency")
	.setOutputCol("category")
```
</div>



{:.model-param}
## Model Information
{:.table-model}
|----------------|-----------------------------------------|
| Model Name     | re_drug_drug_interaction_clinical       |
| Model Class    | RelationExtractionModel                 |
| Dimension      | 2.4                                     |
| Compatibility  | 2.5.5                                   |
| License        | Licensed                                |
| Edition        | Healthcare                              |
| Inputs         | word_embeddings, chunk, pos, dependency |
| Output         | category                                |
| Language       | en                                      |
| Case Sensitive | False                                   |
| Dependencies   | embeddings_clinical                     |




{:.h2_title}
## Data Source
Trained on data gathered and manually annotated by John Snow Labs  
Visit [this]() link to get more information

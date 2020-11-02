---
layout: model
title: 
author: John Snow Labs
name: sent_covidbert_large_uncased
class: BertSentenceEmbeddings
language: en
repository: public/models
date: 2020-08-27
tags: [embeddings]
article_header:
   type: cover
use_language_switcher: "Python-Scala-Java"
---

{:.h2_title}
## Description 




{:.btn-box}
<button class="button button-orange" disabled>Live Demo</button><br/><button class="button button-orange" disabled>Open in Colab</button><br/>[Download](https://s3.amazonaws.com/auxdata.johnsnowlabs.com/public/models/sent_covidbert_large_uncased_en_2.6.0_2.4_1598488155401.zip){:.button.button-orange.button-orange-trans.arr.button-icon}<br/>

## How to use 
<div class="tabs-box" markdown="1">

{% include programmingLanguageSelectScalaPython.html %}

```python
model = BertSentenceEmbeddings.pretrained("sent_covidbert_large_uncased","en","public/models")\
	.setInputCols("document")\
	.setOutputCol("bert_sentence_embeddings")
```

```scala
val model = BertSentenceEmbeddings.pretrained("sent_covidbert_large_uncased","en","public/models")
	.setInputCols("document")
	.setOutputCol("bert_sentence_embeddings")
```
</div>



{:.model-param}
## Model Information
{:.table-model}
|----------------|------------------------------|
| Model Name     | sent_covidbert_large_uncased |
| Model Class    | BertSentenceEmbeddings       |
| Dimension      | 2.4                          |
| Compatibility  | 2.6.0                        |
| License        | open source                  |
| Edition        | public                       |
| Inputs         | document                     |
| Output         | bert_sentence_embeddings     |
| Language       | en                           |
| Case Sensitive | True                         |
| Dependencies   |                              |




{:.h2_title}
## Data Source
  
Visit [this](https://github.com/JohnSnowLabs/spark-nlp/blob/master/src/main/scala/com/johnsnowlabs/nlp/embeddings/BertSentenceEmbeddings.scala) link to get more information

---
layout: model
title: Explain Document DL
author: John Snow Labs
name: explain_document_dl
class: Pipeline
language: 
repository: public/models
date: 2020-03-19
tags: [pipeline]
article_header:
   type: cover
use_language_switcher: "Python-Scala-Java"
---

{:.h2_title}
## Description 




{:.btn-box}
<button class="button button-orange" disabled>Live Demo</button><br/><button class="button button-orange" disabled>Open in Colab</button><br/>[Download](https://s3.amazonaws.com/auxdata.johnsnowlabs.com/public/models/explain_document_dl_en_2.0.0_2.4_1584626657780.zip){:.button.button-orange.button-orange-trans.arr.button-icon}<br/>

## How to use 
<div class="tabs-box" markdown="1">

{% include programmingLanguageSelectScalaPython.html %}

```python
model = PretrainedPipeline.downloadPipeline("explain_document_dl","","public/models")

model.annotate("The patient had stomach pain and high fever")
```

```scala
val model = PretrainedPipeline.downloadPipeline("explain_document_dl","","public/models")

model.annotate("The patient had stomach pain and high fever")
```
</div>



{:.model-param}
## Model Information
{:.table-model}
|----------------|---------------------|
| Model Name     | explain_document_dl |
| Model Class    | Pipeline            |
| Dimension      | 2.4                 |
| Compatibility  | 2.0.0               |
| License        | open source         |
| Edition        | public              |
| Inputs         |                     |
| Output         |                     |
| Language       |                     |
| Case Sensitive | False               |
| Dpendencies    |                     |




{:.h2_title}
## Data Source
  
Visit [this]() link to get more information

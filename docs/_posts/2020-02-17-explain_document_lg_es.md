---
layout: model
title: Explain Document Large
author: John Snow Labs
name: explain_document_lg
class: PipelineModel
language: es
repository: public/models
date: 2020-02-17
tags: [pipeline]
article_header:
   type: cover
use_language_switcher: "Python-Scala-Java"
---

{:.h2_title}
## Description 




{:.btn-box}
<button class="button button-orange" disabled>Live Demo</button><br/><button class="button button-orange" disabled>Open in Colab</button><br/>[Download](https://s3.amazonaws.com/auxdata.johnsnowlabs.com/public/models/explain_document_lg_es_2.4.0_2.4_1581975536033.zip){:.button.button-orange.button-orange-trans.arr.button-icon}<br/>

## How to use 
<div class="tabs-box" markdown="1">

{% include programmingLanguageSelectScalaPython.html %}

```python
model = PretrainedPipeline("explain_document_lg","es","public/models")

model.annotate("The patient had stomach pain and high fever")
```

```scala
val model = PretrainedPipeline("explain_document_lg","es","public/models")

model.annotate("The patient had stomach pain and high fever")
```
</div>



{:.model-param}
## Model Information
{:.table-model}
|----------------|---------------------|
| Model Name     | explain_document_lg |
| Model Class    | PipelineModel       |
| Dimension      | 2.4                 |
| Compatibility  | 2.4.0               |
| License        | open source         |
| Edition        | public              |
| Inputs         |                     |
| Output         |                     |
| Language       | es                  |
| Case Sensitive | True                |
| Dependencies   |                     |




{:.h2_title}
## Data Source
  
Visit [this]() link to get more information

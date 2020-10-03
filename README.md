# hindi-nli-data
A repository containing the details of natural language inference dataset in Hindi developed by

<br>
<p align="center">
  <img src="https://github.com/midas-research/bhaav/blob/master/MIDAS-logo.jpg" alt="MIDAS lab at IIIT-Delhi"  width="60%"/>
  <br>
</p>
<br>

**hindi-nli-data** is the first recasted dataset for natural language inference in Hindi. Evaluating the learning capabilities of deep learning models in the field of Natural Language Processing has always been challenging. The task of Natural Language Inference (NLI) have been the touchstone in measuring their performance. 
However, there is complete absence of labeled NLI datasets in a low-resource language like Hindi. To address this, we performed automated recasting of three existing text classification datasets related to affective content analysis in Hindi language to Natural Language Inference datasets. This resulted in four NLI datasets with 21K, 26K, 55K and 105K premise-hypothesis pairs. The dataset along with its details is shared in this repo.

## Dataset Overview

Four different datasets belonging to the semantic phenomenon: **Sentiment Analysis**, **Emotion Analysis**, **Discourse Analysis** and **Topic-Modelling** in Hindi language are recasted. For the sentiment analysis domain - Product Review dataset **PR** developed by [Akhtar et al](http://iitp.ac.in/~ai-nlp-ml/resources.html) is utlilized. For emotion analysis, we consider the largest emotion analysis dataset in Hindi - [BHAAV](https://github.com/midas-research/bhaav) **BH** developed by Kumar et al and hindi-discourse (https://github.com/midas-research/hindi-discourse) for the discourse analysis dataset. We use the BBC News dataset for the classification over topic modelling (https://tinyurl.com/y8hxtbn8).

The data for all four phenomenon is shared as tsv files over [here](https://github.com/midas-research/hindi-nli-data/tree/master/Classification) for the Classification task and [here](https://github.com/midas-research/hindi-nli-data/tree/master/Textual_Entailment) for the task of Natural Language Inference.

### Recasting Process

<br>
<p align="center">
  <img src="https://github.com/midas-research/hindi-nli-data/blob/master/recasting-template.png" alt="recasting-process"  width="60%"/>
  <br>
</p>
<br>

### Samples from Original Sources

<br>
<p align="center">
  <img src="https://github.com/midas-research/hindi-nli-data/blob/master/source-data-sample.png" alt="original-samples"  width="95%"/>
  <br>
</p>
<br>

### Approach

<br>
<p align="center">
  <img src="https://github.com/midas-research/hindi-nli-data/blob/master/approach.png" alt="recasted-samples"  width="95%"/>
  <br>
</p>
<br>

### Distribution of Train and Test samples in the Recasted Dataset

<br>
<p align="center">
  <img src="https://github.com/midas-research/hindi-nli-data/blob/master/recasted-data-distribution.png" alt="train-test-distribution"  width="40%"/>
  <br>
</p>
<br>

### Inconsistency in premise-hypothesis pairs

<br>
<p align="center">
  <img src="https://github.com/midas-research/hindi-nli-data/blob/master/consistency-example.PNG" alt="consistency-example"  width="70%"/>
  <br>
</p>
<br>

## Terms of Use

1. This corpus can be used freely for research purposes.
2. The paper listed below provide details of the creation and use of the corpus. If you use the corpus, then please cite the     paper.
3. If interested in commercial use of the corpus, send email to midas@iiitd.ac.in.
4. If you use the corpus in a product or application, then please credit the authors and [Multimodal Digital Media Analysis Lab - Indraprastha Institute of Information Technology, New Delhi](http://midas.iiitd.edu.in) appropriately. Also, if you send us an email, we will be thrilled to know about how you have used the corpus.
5. Multimodal Digital Media Analysis Lab - Indraprastha Institute of Information Technology, New Delhi, India disclaims any responsibility for the use of the corpus and does not provide technical support. However, the contact listed above will be happy to respond to queries and clarifications.
6. Rather than redistributing the corpus, please direct interested parties to this [page](https://github.com/midas-research/hindi-nli-data)

Please feel free to send us an email:
- with feedback regarding the corpus.
- with information on how you have used the corpus.
- if interested in having us analyze your data for natural language inference.
- if interested in a collaborative research project.

Copyright (C) 2019 Multimodal Digital Media Analysis Lab - Indraprastha Institute of Information Technology, New Delhi (MIDAS, IIIT-Delhi)

## References

Paper under review. Please check back soon.


```
```



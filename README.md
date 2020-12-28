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

```
@inproceedings{uppal-etal-2020-two,
    title = "Two-Step Classification using Recasted Data for Low Resource Settings",
    author = "Uppal, Shagun  and
      Gupta, Vivek  and
      Swaminathan, Avinash  and
      Zhang, Haimin  and
      Mahata, Debanjan  and
      Gosangi, Rakesh  and
      Shah, Rajiv Ratn  and
      Stent, Amanda",
    booktitle = "Proceedings of the 1st Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 10th International Joint Conference on Natural Language Processing",
    month = dec,
    year = "2020",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.aacl-main.71",
    pages = "706--719",
    abstract = "An NLP model{'}s ability to reason should be independent of language. Previous works utilize Natural Language Inference (NLI) to understand the reasoning ability of models, mostly focusing on high resource languages like English. To address scarcity of data in low-resource languages such as Hindi, we use data recasting to create NLI datasets for four existing text classification datasets. Through experiments, we show that our recasted dataset is devoid of statistical irregularities and spurious patterns. We further study the consistency in predictions of the textual entailment models and propose a consistency regulariser to remove pairwise-inconsistencies in predictions. We propose a novel two-step classification method which uses textual-entailment predictions for classification task. We further improve the performance by using a joint-objective for classification and textual entailment. We therefore highlight the benefits of data recasting and improvements on classification performance using our approach with supporting experimental results.",
}
```



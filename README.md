# hindi-nli-data
a repository containing the details of natural language inference dataset in Hindi developed by

<br>
<p align="center">
  <img src="https://github.com/midas-research/bhaav/blob/master/MIDAS-logo.jpg" alt="MIDAS lab at IIIT-Delhi"  width="60%"/>
  <br>
</p>
<br>

**hindi-nli-data** is the first recasted dataset for natural language inference in Hindi. Evaluating the learning capabilities of deep learning models in the field of Natural Language Processing has always been 
challenging. The task of Natural Language Inference (NLI) have been the touchstone in measuring their performance. 
However, there is complete absence of labeled NLI datasets in a low-resource language like Hindi. To address this, 
we performed automated recasting of three existing text classification datasets related to affective content analysis in 
Hindi language to Natural Language Inference datasets. This resulted in three NLI datasets with 43K, 17K, and 203K 
premise hypothesis pairs. The dataset along with its details is shared in this repo.

## Dataset Overview

Three different affective content datasets in Hindi language is recasted. Two of them are in the domain of sentiment analysis - Product Review dataset **PR** and Movie Review **MR** dataset developed by [Akhtar et al](http://iitp.ac.in/~ai-nlp-ml/resources.html). The third one is the largest emotion analysis dataset in Hindi - [BHAAV](https://github.com/midas-research/bhaav) BH developed by Kumar et al.

The data is shared as tsv files overe [here](https://github.com/midas-research/hindi-nli-data/blob/master/recasted-hindi-nli-data.zip).

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

### Recasted Samples

<br>
<p align="center">
  <img src="https://github.com/midas-research/hindi-nli-data/blob/master/recasted-data-samples.png" alt="recasted-samples"  width="95%"/>
  <br>
</p>
<br>

### Distribution of Train and Test samples in the Recasted Dataset

<br>
<p align="center">
  <img src="https://github.com/midas-research/hindi-nli-data/blob/master/recasted-data-distribution.png" alt="train-test-distribution"  width="60%"/>
  <br>
</p>
<br>

### Accuracies of different Sentence Embeddings on Textual Entailment Task

<br>
<p align="center">
  <img src="https://github.com/midas-research/hindi-nli-data/blob/master/te-accuracy.png" alt="te-accuracies"  width="60%"/>
  <br>
</p>
<br>



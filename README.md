# Ben-Sarc

This repository contains the dataset of the paper titled [**"Ben-Sarc: A Self-Annotated Corpus for Sarcasm Detection from Bengali Social Media Comments and Its Baseline Evaluation"**](https://engrxiv.org/index.php/engrxiv/preprint/view/2102) accepted in [*Natural Language Engineering*](https://www.cambridge.org/core/journals/natural-language-engineering) journal.

## Table of Contents

- [Ben-Sarc](#ben-sarc)
  - [Dataset Details](#dataset-details)
  - [Authors](#authors)
  - [Citation](#citation)

## Dataset Details

We are releasing a large-scale self-annotated Bengali corpus for sarcasm detection research problem in the Bengali language named `Ben-Sarc` containing 25,636 comments, manually collected from different public Facebook pages and evaluated by external evaluators. 

### Data Instances
The `Ben-Sarc` dataset is in `.xlsx` format. One example from the `Ben-Sarc` dataset is given below:
```
|----|------------------------------------------------------------------------------------------------------------|----------|
| id |                                           Text                                                             | Polarity |
|----|------------------------------------------------------------------------------------------------------------|----------|
| 589|তোমারে ভাবিয়া সারারাত জাগিয়া ঘুম মোর হয়েছে নষ্ট বুকের বামপাশে চিনচিন ব্যাথা করে একি গ্যাস্ট্রিক না প্রেম হচ্ছে না স্পষ্ট ।  |    1     |
|----|------------------------------------------------------------------------------------------------------------|----------|
```
### Data Fields
-  `id`: A string representing the text ID.
-  `Text`: A string containing the text.
-  `Polarity` : A number containing the polarity of the text

`Polarity` of the `Ben-Sarc` is defined as follows:
```
            `0` indicates *Non-Sarcastic Text* 
            
            `1` indicates *Sarcastic Text*
```

## Authors
- Sanzana Karim Lora
- G. M. Shahariar
- Tamanna Nazmin
- Noor Nafeur Rahman
- Rafsan Rahman
- Miyad Bhuiyan
- Faisal Muhammad Shah

## Citation
If you use our dataset, please cite the following paper:
```
citation
```

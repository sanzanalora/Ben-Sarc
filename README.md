# Ben-Sarc

This repository contains the dataset of the paper titled [**"Ben-Sarc: A Self-Annotated Corpus for Sarcasm Detection from Bengali Social Media Comments and Its Baseline Evaluation"**]( https://doi.org/10.1017/nlp.2024.11) published in [***Natural Language Processing**(formerly known as Natural Language Engineering)*](https://www.cambridge.org/core/journals/natural-language-engineering) journal by [*Cambridge University Press*](https://www.cambridge.org/). The **Ben-Sarc** is also available at [***HuggingFace***](https://huggingface.co/datasets/sanzanalora/Ben-Sarc)(https://huggingface.co/datasets/sanzanalora/Ben-Sarc).

## Table of Contents

- [Ben-Sarc](#ben-sarc)
  - [Dataset Details](#dataset-details)
  - [Authors](#authors)
  - [License](#license)
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

## License
Contents of this repository are restricted to only non-commercial research purposes under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Citation
If you use our dataset, please cite the following paper:
```
@article{Lora_Shahariar_Nazmin_Rahman_Rahman_Bhuiyan_Shah_2024,
  title={Ben-Sarc: A self-annotated corpus for sarcasm detection from Bengali social media comments and its baseline evaluation},
  DOI={10.1017/nlp.2024.11},
  journal={Natural Language Processing},
  author={Lora, Sanzana Karim and Shahariar, G. M. and Nazmin, Tamanna and Rahman, Noor Nafeur and Rahman, Rafsan and Bhuiyan, Miyad and Shah, Faisal Muhammad},
  year={2024},
  pages={1–26}} 
```

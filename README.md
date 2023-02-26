# Dialect and Sentiment-Identification-in-Nuanced-Arabic-Tweets
This Repository contains work done in NADI shared task 2022.  We achieved first place in both NADI 2022 subtasks by ensembling a set of models built on top Arabic-bert-based models in three settings: (1) prompt-based, (2) single fine-tuning, and multitask fine-tuning.


## Overview
This github is an implementation for accepted manuscript titled `Dialect & Sentiment Identification in Nuanced Arabic Tweets Using an Ensemble of Prompt-based, Fine-tuned, and Multitask BERT-Based Models`.


[Publised paper](https://aclanthology.org/2022.wanlp-1.48.pdf).



If you find code/work useful, please consider citing
```
@inproceedings{abdel-salam-2022-dialect,
    title = "Dialect {\&} Sentiment Identification in Nuanced {A}rabic Tweets Using an Ensemble of Prompt-based, Fine-tuned, and Multitask {BERT}-Based Models",
    author = "Abdel-Salam, Reem",
    booktitle = "Proceedings of the The Seventh Arabic Natural Language Processing Workshop (WANLP)",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates (Hybrid)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.wanlp-1.48",
    pages = "452--457",
    abstract = "Dialect Identification is important to improve the performance of various application as translation, speech recognition, etc. In this paper, we present our findings and results in the Nuanced Arabic Dialect Identification Shared Task (NADI 2022) for country-level dialect identification and sentiment identification for dialectical Arabic. The proposed model is an ensemble between fine-tuned BERT-based models and various approaches of prompt-tuning. Our model secured first place on the leaderboard for subtask 1 with an 27.06 F1-macro score, and subtask 2 secured first place with 75.15 F1-PN score. Our findings show that prompt-tuning-based models achieved better performance when compared to fine-tuning and Multi-task based methods. Moreover, using an ensemble of different loss functions might improve model performance.",
}
```

## Abstract

Dialect Identification is important to improve the performance of various application as translation, speech recognition, etc. In this paper, we present our findings and results in the Nuanced Arabic Dialect Identification Shared Task (NADI 2022) for country-level dialect identification and sentiment identification for dialectical Arabic. The proposed model is an ensemble between fine-tuned BERT-based models and various approaches of prompt-tuning.
Our model secured first place on the leaderboard for subtask 1 with an 27.06 F1-macro
score, and subtask 2 secured first place with 75.15 F1-PN score. Our findings show that
prompt-tuning-based models achieved better performance when compared to fine-tuning and
Multi-task based methods. Moreover, using an ensemble of different loss functions might improve model performance.

## Results
1. `Official Results from website shared task 1`
![Alt text](Results/task_1.png?raw=true "Title")
2. `Official Results from website shared task 2`
![Alt text](Results/task_2.png?raw=true "Title")


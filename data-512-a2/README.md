# A2: Bias in Data

The goal of this assignment is to identify potential sources of bias in the Wikipedia Talk corpus of data annotated by annotators from Crowdflower, and describe some implications of those biases.

## Data Source

The data for the analysis has been collected from [Figshare](https://figshare.com/projects/Wikipedia_Talk/16731)  and the data schema can be found [here](https://meta.wikimedia.org/wiki/Research:Detox/Data_Release).  
The analysis focuses on two datasets- [Toxicity](https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Toxicity/4563973) and [Personal Attacks](https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Personal_Attacks/4054689)



## Directory Structure

```
.
├── data
│   ├── attack_annotated_comments.tsv
|   ├── attack_annotations.tsv
│   ├── attack_worker_demographics.tsv
│   ├── toxicity_annotated_comments.tsv
│   ├── toxicity_annotations.tsv
│   └── toxicity_worker_demographics.tsv
├── images
│   ├── hostile_comments_by_age.png
|   ├── hostile_comments_by_education.png
│   ├── hostile_comments_by_gender.png
│   ├── hostile_comments_by_language.png
│   ├── label_disagreement_attack.png
│   ├── label_disagreement_toxic_vs_attack.png
│   └── label_disagreement_toxicity.png
├── README.md
├── LICENCE
└── data512-a2-bias-in-data.ipynb

```

## Analysis Questions

## Results


## License

This code is available under the [MIT License](LICENSE)

Wulczyn, Ellery; Thain, Nithum; Dixon, Lucas (2017): Wikipedia Talk Labels: Personal Attacks. figshare. Dataset. https://doi.org/10.6084/m9.figshare.4054689.v6

Thain, Nithum; Dixon, Lucas; Wulczyn, Ellery (2017): Wikipedia Talk Labels: Toxicity. figshare. Dataset. https://doi.org/10.6084/m9.figshare.4563973.v2

Text is available under the [Creative Commons Attribution-ShareAlike License](https://creativecommons.org/licenses/by-sa/3.0/); additional terms may apply. See [Terms of Use](https://foundation.wikimedia.org/wiki/Terms_of_Use/en) for details.

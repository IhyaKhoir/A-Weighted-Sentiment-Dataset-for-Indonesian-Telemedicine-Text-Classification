# A-Weighted-Sentiment-Dataset-for-Indonesian-Telemedicine-Text-Classification
This repository contains datasets related to our paper [A-Weighted-Sentiment-Dataset-for-Indonesian-Telemedicine-Text-Classification](https://doi.org/10.1016/j.dib.2026.113172). This dataset is also available on the [Mendeley Data website](https://doi.org/10.17632/rmmmf2dp8d.2)

## Value of the Data
- The Weighted Indonesian Telemedicine Sentiment Dataset contains 19,680 manually annotated Indonesian-language user reviews from three telemedicine applications, labeled with three sentiment classes (Positive, Neutral, Negative) and a weight attribute (Uninformative, Informative, Complex) indicating review informativeness.
- Two annotators followed documented guidelines created by a psychology expert, and inter-annotator agreement was measured using Cohen's Kappa (κ = 0.752), enabling other researchers to assess label reliability.
- This dataset introduces a weight attribute (Uninformative, Informative, Complex), which adds a crucial secondary dimension. This enables researchers to analyze not only what the user feels but also the substantive value of the review, thereby supporting more advanced tasks such as Aspect-Based Sentiment Analysis (ABSA). For example, analyze reviews with mixed emotions. On the other hand, this label can be used to curate data, such as filtering uninformative reviews or studying the characteristics of complex user feedback.
- This dataset facilitates and supports experiments in advanced NLP technologies, including BERT, LSTM, and LLMs, such as the user review sentiment classification task.

## Data Annotation
- Each review in the dataset was manually annotated with a primary sentiment label: Positive, Neutral, or Negative, and a secondary weight label: Uninformative, Informative, or Complex.
- The annotation process was based on clearly defined criteria (e.g., satisfaction/appreciation for positive; factual health questions for neutral; disappointment/complaints for negative) developed by the authors and reviewed by an expert in clinical psychology to ensure clinical and contextual relevance.
- Two independent annotators labeled the reviews. In cases of disagreement, discussions were held to reach a consensus. If consensus could not be reached, the disagreement was resolved through consultation with a Psychology expert.
- A Cohen’s Kappa score (κ = 0.752) was calculated to verify inter-annotator reliability, indicating substantial agreement.
- Anonymization was strictly applied during the preprocessing stage. All attributes containing Personally Identifiable Information (PII), such as usernames, were removed to guarantee user privacy and confidentiality.

## List of Attributes

| Attribute      | Description                                  |
| -------------- | -------------------------------------------- |
| Platform     | Application distributor platform (e.g., Google Play Store) |
| App_name      | Name of the telemedicine application (Alodokter, Halodoc, KlikDokter)      |
| rating    | Application user satisfaction score (numeric)    |
| Review    | The complete text content of the user review     |
| sentiment  | Sentiment data label (Positive, Neutral, Negative) |
| weight | User review complexity/informativeness label (Uninformative, Informative, Complex)     |

## Citation
If you use this dataset in a scientific publication, we would appreciate using the following citations:

### Plain Text
Athallah, F. W., Ulumudin, I. C., Sutoyo, R., & Andangsari, E. W. (2026). A weighted sentiment dataset for Indonesian telemedicine text classification. Data in Brief, 68, 113172.

### Bibtex
```
@article{ATHALLAH2026113172,
title = {A weighted sentiment dataset for Indonesian telemedicine text classification},
journal = {Data in Brief},
volume = {68},
pages = {113172},
year = {2026},
issn = {2352-3409},
doi = {https://doi.org/10.1016/j.dib.2026.113172},
url = {https://www.sciencedirect.com/science/article/pii/S2352340926007195},
author = {Fakhri Wahid Athallah and Ihya Choerul Ulumudin and Rhio Sutoyo and Esther Widhi Andangsari},
keywords = {Indonesian telemedicine, Weighted sentiment analysis, Text classification, Telemedicine user review, Natural language processing, Indonesian language corpus, Health informatics},
abstract = {The digital era has fundamentally transformed the global healthcare paradigm. Consequently, Indonesia’s e-health market is projected to reach US$ 3.6 billion by 2031, generating a massive volume of user review data. This paper introduces a novel dataset, named the Indonesian Telemedicine User Review Dataset for Sentiment Analysis. The dataset comprises over 19,680 rows of user reviews sourced from the three most prominent telemedicine applications in Indonesia (Alodokter, Halodoc, KlikDokter). Two human annotators annotated the dataset, strictly adhering to guidelines rigorously validated by domain experts in Psychology, yielding a Cohen’s Kappa score of 0.752. The dataset contains 14,748 positive, 711 neutral, and 4,221 negative reviews. Uniquely, it introduces a weight attribute (Uninformative, Informative, Complex), adding a crucial secondary dimension that enables researchers to analyze not only what the user feels but also the substantive value of the review, supporting advanced tasks such as Aspect-Based Sentiment Analysis (ABSA).}
}
```

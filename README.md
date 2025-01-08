# IC-CQRD-Dataset-
IC-CQRD-Dataset 
Intention Classification of Chinese Questions on Respiratory Diseases (IC-CQRD) Dataset

In the Dataset, 0 represents HT, 1 represents WWH, 2 represents WD, 3 represents WHY, and 4 represents PRE.

The experimental data is sourced from mainstream Chinese Q\&A platforms such as Baidu Know, 360Q\&A, and Sogou Ask. The CQRD data were collected through web crawlers on these platforms. Approximately 40,000 CQRD data were successively gathered in the experiment. After removing duplicates and filtering out CQRD that did not meet the requirements, a subset of the corpus was selected for labeling. The initial batch of manual labeling consisted of 8,926 CQRD, with 8,056 questions used for training and 870 questions used for testing. During this labeling process, keywords in each CQRD were manually summarized and applied to the classification task. However, later on it was decided to remove the non-medical problems category due to its broad scope across various fields. This version of the data was named CQRD\_8000.

The CQRD corpus was expanded to include 28,521 samples based on the first batch of annotations. The training corpus included 21610 CQRD and the test corpus included 6263 CQRD. In addition, it contains 648 CQRD of multi-category. The name of this dataset version is CQRD\_28000.

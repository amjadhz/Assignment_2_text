Research Question 1:
How do linguistic and contextual features in emails contribute to identifying phishing attempts?


Methodology
- preprocess
- clean data tokonize
- divide test and train data
- TF-IDF and Word Frequency (KNN?) => https://www.sciencedirect.com/science/article/pii/S0747563224001420 => Amjad
- or bert? classification labeling => https://www.splunk.com/en_us/blog/security/deep-learning-in-security-text-based-phishing-email-detection-with-bert-model.html => Sara
  literature on Bert; https://ceur-ws.org/Vol-3575/Paper4.pdf
- POS (Part of speech) Husam
- train models
- test models
- visualize results

tasks
- literature review
- description dataset and methodology
- discussion results


Literature review for chosen dataset:

Dataset 1: Phishing Attempts.
- https://www.sciencedirect.com/science/article/pii/S0747563224001420
- https://ceur-ws.org/Vol-2940/paper10.pdf
- https://www.phishing.org/what-is-phishing

Dataset 2: Fake News.
- https://www.mdpi.com/2227-7390/9/22/2988
- https://ieeexplore.ieee.org/abstract/document/9709267


# For working localy:

create venv for python on your device use these commands: 
 - Create Venv :

```
py -m venv .venv
```

 - Activate Venv:

```
.venv\Scripts\activate
```

Install Libraries from requirements.txt

```
pip install -r requirements.txt
```


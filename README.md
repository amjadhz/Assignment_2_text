Research Question 1:
How do linguistic and contextual features in emails contribute to identifying phishing attempts?


Methodology
- preprocess
- clean data tokonize
- divide test and train data
- address class imbalance?
- TF-IDF and Word Frequency? => https://www.sciencedirect.com/science/article/pii/S0747563224001420
- or bert? classification labeling => https://www.splunk.com/en_us/blog/security/deep-learning-in-security-text-based-phishing-email-detection-with-bert-model.html
- Extract certain features as word count, whether there is an URL
- train models
- test models
- visualize results

tasks
- literature review
- description dataset and methodology
- discussion results


Research Question 2: Can topic modeling combined with engagement metrics (e.g., retweets) predict the likelihood of news being fake across different source domains?

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


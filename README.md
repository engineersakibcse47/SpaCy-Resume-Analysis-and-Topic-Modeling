# SpaCy-Resume-Analysis-and-Topic-Modeling

## Introduction
In this project, going to use spacy for entity recognition on 200 Resume and experiment around various NLP tools for text analysis. The main purpose of this project is to help recruiters go throwing hundreds of applications within a few minutes. We have also added skills match feature so that hiring managers can follow a metric that will help them to decide whether they should move to the interview stage or not. We will be using two datasets; the first contains resume texts and the second contains skills that we will use to create an entity ruler.

## Dataset
livecareer.com resume Dataset A collection of 2400+ Resume Examples taken from livecareer.com for categorizing a given resume into any of the labels defined in the dataset: Resume Dataset

## Inside the CSV
ID: Unique identifier and file name for the respective pdf. Resume_str : Contains the resume text only in string format. Resume_html : Contains the resume data in html format as present while web scrapping. Category : Category of the job the resume was used to apply.

## Present categories
HR, Designer, Information-Technology, Teacher, Advocate, Business-Development, Healthcare, Fitness, Agriculture, BPO, Sales, Consultant, Digital-Media, Automobile, Chef, Finance, Apparel, Engineering, Accountant, Construction, Public-Relations, Banking, Arts, Aviation

## Acknowledgements
Data was obtained by scrapping individual resume examples from www.livecareer.com website. Web Scrapping code present in my Github Repo.

## Jobzilla skill patterns
The jobzilla skill dataset is jsonl file containing different skills that can be used to create spaCy entity_ruler. The data set contains label and pattern-> diferent words used to descibe skills in various resume.

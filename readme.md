# Autism Screening using Machine Learning

## Abstract

The project aims to improve autism screening by creating a machine learning model that predicts the likelihood of an individual having autism spectrum disorder (ASD) based on survey data. Autism is a complex condition characterized by challenges in social skills, repetitive behaviors, speech, and nonverbal communication. Early diagnosis and intervention can significantly impact an individual's learning, communication, and social skills. The machine learning model developed in this project helps healthcare professionals prioritize their resources by identifying individuals who may require further evaluation for ASD.

## About Autism

Autism, also known as autism spectrum disorder (ASD), encompasses a wide range of conditions that vary from person to person. It is influenced by a combination of genetic and environmental factors. People with autism may have different strengths and challenges in learning, thinking, and problem-solving. The severity of the disorder can range from highly skilled individuals to those facing significant challenges.

## Dataset Description

The dataset used in this project consists of survey results from more than 700 individuals who filled out an app form. The dataset includes the following columns:

- ID: ID of the patient
- A1_Score to A10_Score: Scores based on Autism Spectrum Quotient (AQ) 10-item screening tool
- age: Age of the patient in years
- gender: Gender of the patient
- ethnicity: Ethnicity of the patient
- jaundice: Whether the patient had jaundice at the time of birth
- autism: Whether an immediate family member has been diagnosed with autism
- country_of_res: Country of residence of the patient
- used_app_before: Whether the patient has undergone a screening test before
- result: Score for AQ1-10 screening test
- age_desc: Age description of the patient
- relation: Relation of the patient who completed the test
- Class/ASD: Target column, where 0 represents "No" and 1 represents "Yes" for ASD diagnosis.

## The Role of Machine Learning

Machine learning plays a crucial role in this project as it enables the development of a predictive model that can assess the likelihood of an individual having autism. By training on the provided dataset, the model can learn patterns and associations between various features and the target variable (ASD diagnosis). The high accuracy, F1 score, precision, and recall achieved (99.9%) indicate that the model is performing exceptionally well in distinguishing between individuals with and without ASD.

## Directory Structure

The project directory structure is as follows:

- Autism-Adult-Data.csv: CSV file containing survey data for adult individuals.
- Autism-Child-Data.csv: CSV file containing survey data for child individuals.
- final-data.csv: CSV file with cleaned and preprocessed data used for model training.
- main.ipynb: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- README.md: The current file, which serves as a project readme written in Markdown format.

## Conclusion

The project has successfully demonstrated the potential of machine learning in improving autism screening by predicting the likelihood of an individual having autism spectrum disorder. The highly accurate model can assist healthcare professionals in prioritizing their resources for early intervention, thereby positively impacting the learning, communication, and social skills of individuals with ASD. As with any machine learning application in a healthcare context, it is essential to continue refining and validating the model using diverse and representative datasets to ensure its reliability and generalizability.

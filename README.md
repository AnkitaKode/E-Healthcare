# E-Health-Care

The web application aims to minimize reliance on doctors, support underserved communities with essential medical checkups, and help individuals avoid unnecessary healthcare costs. It is developed using Django, machine learning techniques and deep learning models.

## Overview

In many areas, there is a severe shortage of doctors, limiting access to proper medical checkups. As a result, many cases escalate to critical conditions due to delayed medical intervention. This app offers an accessible solution, enabling individuals to perform basic health checkups and receive timely guidance.


## Application

- Reduce dependence on doctors.
- Assist underserved individuals with essential medical checkups.
- Minimize unnecessary medical expenses.
- Promote technology’s role in healthcare.

## Models

The project includes several models for disease prediction:

- **Pneumonia model**: `pickle_model_pneumonia.pkl`
- **Diabetes model**: `pickle_model_diabetes.pkl`
- **Heart model**: `pickle_model_heart.pkl`
- **Disease model**: `pickle_model_disease.pkl`

- ## Datasets Used for Model Development

- **Heart**: `heart.csv` [In the repository]
- **Diabetes**: `diabetes.csv` [In the repository]
- **Disease**: `disease.csv` [In the repository]
- **Pneumonia**: [Link](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

- ## Tools Used for Project Development

- **Python**
- **Django**
- **HTML**
- **CSS**
- **JavaScript**
- **Pandas**
- **NumPy**


- ## Features

### Patient

- Register and sign in
- Update and edit profile
- View and search specialist doctors
- Predict diseases based on symptoms or x-ray images
- Book, cancel, view, and download appointments
- Provide feedback to the system

### Admin

- View and manage total patients, predictions, doctors, and feedback
- Add, edit, delete, and assign doctors to respective diseases

### Doctor

- Register via provided username and password from the admin
- Manage appointments and view patient records
- Send disease precautions to patients via email

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss proposed changes.


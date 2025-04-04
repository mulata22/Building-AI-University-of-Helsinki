# Herbal AI: Intelligent Herbal Detection
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->


Final project for the Building AI course

## Summary

SmartHerbal AI is an intelligent solution designed to detect crop herbals early using image recognition and machine learning, empowering farmers with timely insights to take preventive action and increase yield.


## Background

Crop disease is a major cause of agricultural loss globally. Many farmers, especially in rural or underserved areas, lack access to agricultural experts who can diagnose plant diseases. Early detection is critical, but current methods are either manual or inaccessible to smallholder farmers.

This project aims to:

Reduce crop losses by detecting diseases early
Empower smallholder farmers with AI-assisted decision making
Improve food security in regions dependent on agriculture
My personal motivation comes from growing up in a farming community and seeing first-hand the losses due to undiagnosed plant issues. Making AI accessible to farmers can significantly improve livelihoods.


## How is it used?

Farmers can take a photo of the affected plant using a mobile app or upload it to a web portal. The AI model analyzes the image, detects the presence and type of disease, and provides:

Diagnosis of the issue
Confidence score
Suggested actions or treatments
Users: Farmers, agricultural extension officers, NGOs, and agri-tech companies.

Environment: Rural/remote areas with limited access to agronomists but with smartphones or internet cafés.

## Data sources and AI methods
Data sources:

PlantVillage dataset (public dataset of labeled crop disease images)
Local agricultural extension data (if available)
Crowdsourced farmer image submissions
AI methods:

Convolutional Neural Networks (CNNs) for image classification
TensorFlow/Keras or PyTorch frameworks
Mobile optimization using TensorFlow Lite
[Twitter API](https://developer.twitter.com/en/docs)

| Component      | Description |
| ----------- | ----------- |
| Dataset      | PlantVillage, custom annotated images       |
| AI Framework   | TensorFlow, Keras        |
| Model Architecture      | CNN with image preprocessing       |
| Output   | Disease label + confidence score        |

## Challenges

Limited internet access may hinder image upload from remote areas
Model accuracy may vary with image quality or unusual crop conditions
Not a replacement for expert diagnosis in rare or complex cases
Ethical concern: misuse of data, ensuring farmer data privacy
## What next?

Improve model accuracy by including more localized disease images
Add multilingual support for app instructions and diagnosis
Partner with agriculture NGOs for deployment and farmer training
Develop an offline model version for areas with no internet

## Acknowledgments

* Inspired by various real-world applications such as Plantix and Nuru AI
Thanks to Reaktor & University of Helsinki for the Building AI course
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)

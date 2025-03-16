<div id="top"></div>

# AgriTech


---

## Introduction

Agriculture faces a host of challenges, from unpredictable weather conditions to soil degradation and plant diseases. These issues can reduce crop yields, increase costs, and impact food security. **AgriTech** is a web application designed to bridge the gap between modern agricultural practices and advanced technologies like machine learning and deep learning. By providing tools for crop disease detection, fertilizer recommendations, and crop selection advice, AgriGo empowers farmers to make data-driven decisions and optimize their farming processes.

---

## The Problem

Farming is becoming increasingly complex due to:
- **Limited access to expert advice** for small-scale farmers.
- **Inefficiency in crop selection** based on soil and environmental conditions.
- **Lack of knowledge about fertilizers** to use for specific soil and crop types.
- **Crop diseases going undetected**, leading to reduced productivity.

AgriTech addresses these challenges with an easy-to-use platform that integrates scientific analysis into daily agricultural practices.

---

## Features



### 1. Crop Recommendation  
AgriTech analyzes soil properties like nitrogen, phosphorus, potassium (NPK) levels, moisture, temperature, and rainfall to suggest the most suitable crops for your farm. This ensures optimized crop selection tailored to your unique environmental conditions.

### 2. Fertilizer Suggestions  
Using data such as soil type, pH, temperature, and the selected crop, AgriTech provides precise fertilizer recommendations. These suggestions help maintain soil health, improve crop growth, and maximize overall yield efficiency.

### 3. Crop Disease Detection  
With just an uploaded image of your crop, AgriTech’s AI-powered image recognition system identifies diseases and evaluates plant health. This allows for quick interventions to protect your crops and prevent widespread damage.


---

## How to Use

```


### Run with Docker

1. **Build the Docker image**:
   ```bash
   docker build -t agriTech-webapp .
   ```

2. **Run the container**:
   ```bash
   docker run -p 5000:5000 agriTech-webapp
   ```

Visit the app at [http://localhost:5000](http://localhost:5000).

---

## Dataset

The datasets used for this project are sourced from Kaggle:

- [Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
- [Fertilizer Recommendation Dataset](https://www.kaggle.com/datasets/gdabhishek/fertilizer-prediction)
- [Crop Disease Image Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)

---

## Built With

- [Flask](https://flask.palletsprojects.com/en/2.0.x/)
- [TensorFlow](https://www.tensorflow.org)
- [scikit-learn](https://scikit-learn.org/stable/)
- [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/)

---



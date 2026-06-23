# 💊 Insurance Premium Predictor

![Python](https://img.shields.io/badge/Python-3.11-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)
![Streamlit](https://img.shields.io/badge/Streamlit-Frontend-red)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)

### 🚀 End-to-End Machine Learning Prediction API

A production-style Insurance Premium Prediction System that combines **Machine Learning**, **FastAPI**, **Streamlit**, and **Docker** to deliver real-time insurance premium category predictions based on user demographics, lifestyle, and financial information.

---

## ✨ Project Highlights

🔹 Machine Learning model integration using Scikit-Learn

🔹 FastAPI-powered REST API backend

🔹 Interactive Streamlit frontend

🔹 Pydantic-based request and response validation

🔹 Robust HTTP exception handling

🔹 Modular project architecture

🔹 Query parameter and path parameter implementation

🔹 Confidence score generation

🔹 Class probability prediction

🔹 Dockerized deployment

🔹 📊 API Workflow: User Input → Streamlit Frontend → FastAPI API → ML Model Prediction → JSON Response → Streamlit Display

---

## 🎯 Problem Statement

Insurance providers assess multiple factors such as age, income, smoking habits, occupation, and city before determining premium categories.

This application automates that process by leveraging Machine Learning to predict whether a customer falls into a:

* 🟢 Low Premium Category
* 🟡 Medium Premium Category
* 🔴 High Premium Category

along with prediction confidence and probability distribution.

---

## 🛠️ Tech Stack

### Backend

* FastAPI
* Pydantic
* Uvicorn

### Frontend

* Streamlit

### Machine Learning

* Scikit-Learn
* Pandas
* NumPy

### DevOps

* Docker
* Git
* GitHub

---

## 🏗️ Software Engineering Concepts Implemented

### API Development

✔ RESTful API Design

✔ Request Validation

✔ Response Validation

✔ HTTP Exception Handling

✔ Structured API Endpoints

✔ Query Parameters

✔ Path Parameters

### Machine Learning Deployment

✔ Model Serialization

✔ Real-Time Inference

✔ Probability Prediction

✔ Confidence Score Calculation

### Project Structure

✔ Modular Folder Organization

✔ Configuration Management

✔ Schema Separation

✔ Model Separation

✔ Frontend-Backend Decoupling

---

## 📂 Project Structure

```text
Insurance-Premium-Prediction
│
├── app.py
├── frontend.py
├── requirements.txt
├── dockerfile
│
├── config/
├── schema/
└── model/
```

---

## 📊 Sample Prediction

### Input

| Feature | Value |
|----------|--------|
| Age | 30 |
| Weight | 65 kg |
| Height | 1.70 m |
| Annual Income | 10 LPA |
| Smoker | True |
| City | Mumbai |
| Occupation | Retired |

### Output

**Predicted Insurance Premium Category:** 🟢 Low

**Confidence Score:** 0.47

**Class Probabilities**

```json
{
  "High": 0.08,
  "Low": 0.47,
  "Medium": 0.45
}
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone <repository-url>
cd Insurance-Premium-Prediction
```

### Create Virtual Environment

```bash
py -3.11 -m venv myenv311
```

### Activate Environment

```bash
myenv311\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Backend

```bash
uvicorn app:app --reload
```

---

## ▶️ Run Frontend

```bash
streamlit run frontend.py
```

---

## 🐳 Docker Support

Build Docker Image

```bash
docker build -t insurance-premium-api .
```

Run Docker Container

```bash
docker run -p 8000:8000 insurance-premium-api
```

---

## 🎓 Skills Demonstrated

* FastAPI Development
* Machine Learning Deployment
* Pydantic Validation
* API Design
* Error Handling
* Streamlit Development
* Docker Containerization
* Software Architecture
* Git & GitHub
* End-to-End ML Application Development

---

## 🌟 Key Learning Outcomes

This project demonstrates practical experience in building and deploying Machine Learning-powered APIs, integrating frontend and backend systems, implementing data validation using Pydantic, handling exceptions, and containerizing applications using Docker.

---

## 👨‍💻 Author

**Md Amaan Sadat**

Built as a full-stack Machine Learning project integrating Data Science, Backend Development, Frontend Development, and DevOps practices.
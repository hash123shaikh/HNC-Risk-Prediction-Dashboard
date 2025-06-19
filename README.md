# 🧠 HNC-Risk-Prediction-Dashboard

A lightweight, in-house web dashboard for **Head and Neck Cancer (HNC)** risk prediction using radiomics and clinical data. This tool enables clinicians and researchers to visualize top-5 radiomics features, explore patient-level clinical data, and obtain real-time risk scores from a trained machine learning model—all securely hosted within institutional infrastructure.

---

## 📌 Project Overview

This dashboard bridges radiomics research with clinical utility. It offers:

- A **patient lookup** system by ID
- A **tabular view of clinical features**
- A **visual representation of radiomics features**
- A **real-time risk score** for recurrence prediction

All operations run locally within a Dockerized environment to ensure compliance with data privacy policies.

---

## 🚀 Key Features

- 🔍 **Patient Lookup** – Quickly search by ID
- 📋 **Clinical Data Table** – View demographics & treatment summary
- 📊 **Radiomics Visualization** – Horizontal bar chart of top-5 features
- 🧠 **Risk Score** – Real-time recurrence prediction via scikit-learn
- 🌐 **RESTful API** – Built with FastAPI, supports health checks and prediction endpoints
- 🧪 **Modular ETL Pipeline** – Merge & validate clinical + radiomics data nightly
- 🖥️ **React Frontend** – Responsive UI styled with Tailwind CSS
- 🐳 **Docker-First Architecture** – Reproducible deployment using Docker Compose

---

## 🧱 Tech Stack

| Layer      | Technology              |
|------------|--------------------------|
| Frontend   | React, Axios, Chart.js, React Router, Tailwind CSS |
| Backend    | FastAPI, Uvicorn, Pandas, scikit-learn |
| ETL        | Python, Pandas, JSON Schema |
| Deployment | Docker, Docker Compose, NGINX (production) |
| CI/CD      | GitHub Actions (optional) |

---

## 📁 Repository Structure


# Personalized Learning Pathway Platform

A scalable, AI-driven educational platform that curates personalized learning journeys using adaptive algorithms to tailor content and pacing to each user's unique learning style and progress.

## 🚀 Overview

This platform empowers learners to reach their educational goals by delivering customized content paths. Leveraging AI and real-time feedback, it dynamically adjusts to users’ evolving needs, providing a deeply engaging and effective learning experience.

## ✨ Features

- 🎯 **Adaptive Learning Engine**: AI/ML algorithms built with PyTorch to personalize content based on learner behavior, performance, and preferences.
- 📊 **Real-Time Progress Tracking**: Dashboards for learners and educators to monitor growth and engagement.
- 🔗 **External Resource Integration**: Seamless integration with third-party educational APIs (e.g., Open Educational Resources, YouTube Edu, etc.).
- ⚙️ **Scalable Architecture**: Deployed with Kubernetes on Google Cloud Platform (GCP) for robust performance and scalability.
- 📚 **Modular Content System**: Easily configurable lessons, quizzes, and assessments.

## 🧱 Tech Stack

| Layer       | Technology            |
|-------------|------------------------|
| Frontend    | Angular                |
| Backend     | Ruby on Rails          |
| Database    | MySQL                  |
| AI/ML       | PyTorch                |
| Deployment  | Kubernetes on GCP      |

## 📦 Project Structure

personalized-learning-platform/
├── frontend/                   # Angular frontend application
│   ├── src/                   # Angular source files
│   ├── angular.json           # Angular workspace config
│   └── package.json           # Frontend dependencies
│
├── backend/                   # Ruby on Rails API backend
│   ├── app/                   # MVC structure: models, controllers, views
│   ├── config/                # Rails configuration
│   ├── db/                    # Database migrations and seeds
│   └── Gemfile                # Backend dependencies
│
├── ml-engine/                 # AI/ML logic using PyTorch
│   ├── models/                # Model definitions
│   ├── training/              # Training scripts
│   ├── inference/             # Inference and serving scripts
│   └── requirements.txt       # Python dependencies
│
├── k8s/                       # Kubernetes deployment manifests
│   ├── frontend-deployment.yaml
│   ├── backend-deployment.yaml
│   ├── ml-engine-deployment.yaml
│   └── services.yaml
│
├── docs/                      # Documentation, architecture diagrams, API specs
│
├── .gitignore
├── README.md
└── LICENSE

## 🧠 AI/ML Overview

The adaptive learning system uses reinforcement learning and learner analytics to:

- Analyze performance across assessments
- Adjust difficulty and content sequencing
- Recommend supplementary materials in real-time

## 🛠️ Installation

### Prerequisites

- Node.js & Angular CLI
- Ruby 3.x & Rails 7.x
- MySQL 8+
- Python 3.9+ with PyTorch
- Docker & Kubernetes CLI
- GCP CLI (optional for deployment)

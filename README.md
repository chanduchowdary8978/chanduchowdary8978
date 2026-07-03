<div align="center">

# Bondu Chandu
<div align="center">

# Bondu Chandu

### Machine Learning Engineer • Distributed ML • ML Systems • Optimization • M.Tech @ NIT Jalandhar

<p>

<a href="https://chanduchowdary8978.github.io/Chandu_Portfolio/">
<img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/chandu-chowdary-bondu/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:chanduchowdary8978@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</p>

<img src="https://komarev.com/ghpvc/?username=chanduchowdary8978&style=flat-square&color=blue" />

</div>

---

# Engineering Summary

I build **production-oriented machine learning systems** that combine statistical modeling, deep learning, and scalable software engineering. My work focuses on designing end-to-end ML pipelines, optimizing distributed training, deploying inference services, and evaluating models under realistic operating conditions.

Current areas of work include:

- Communication-efficient Distributed Training (LocalSGD)
- Fraud Detection for High-Volume Payment Systems
- Time-Series Forecasting
- ML System Design
- Optimization Algorithms
- Data Engineering Pipelines
- Mathematical Modeling for Machine Learning

Alongside engineering projects, I study optimization theory and distributed learning to better understand the mathematical foundations behind modern machine learning systems. :contentReference[oaicite:0]{index=0}

---

# Core Expertise

<table>

<tr>

<td width="50%">

## Machine Learning

- Classical Machine Learning
- Deep Learning
- Supervised Learning
- Feature Engineering
- Model Evaluation
- Hyperparameter Optimization
- Time-Series Forecasting
- Fraud & Anomaly Detection

</td>

<td width="50%">

## Distributed ML

- LocalSGD
- Non-IID Training
- Distributed Optimization
- Communication-Efficient Learning
- Multi-worker Simulation
- Training Stability
- Gradient Synchronization

</td>

</tr>

<tr>

<td>

## ML Systems

- End-to-End ML Pipelines
- Real-Time Inference
- FastAPI Services
- Docker Deployment
- Experimentation
- Model Benchmarking
- Monitoring Pipelines

</td>

<td>

## Mathematical Foundations

- Convex Optimization
- Gradient-Based Optimization
- Linear Algebra
- Probability & Statistics
- Numerical Optimization
- Mathematical Modeling

</td>

</tr>

</table>

---

# Engineering Focus

| Domain | Focus |
|---------|-------|
| **Machine Learning** | Building production-ready ML pipelines |
| **Deep Learning** | PyTorch-based model development and optimization |
| **Distributed Training** | Communication-efficient LocalSGD and scalable training strategies |
| **MLOps** | FastAPI deployment, Docker containerization and reproducible workflows |
| **Optimization** | Gradient methods, training stability and convergence analysis |
| **Data Engineering** | Large-scale preprocessing, feature engineering and pipeline automation |
| **Research** | Distributed optimization, ML systems and mathematical modeling |

---

# Technology Stack

## Programming

<p>

<img src="https://skillicons.dev/icons?i=python,cpp,c,r,postgres,mongodb"/>

</p>

---

## Machine Learning

<p>

<img src="https://skillicons.dev/icons?i=pytorch"/>

<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>

<img src="https://img.shields.io/badge/XGBoost-EC6B23?style=for-the-badge"/>

<img src="https://img.shields.io/badge/LightGBM-7CB342?style=for-the-badge"/>

</p>

---

## ML Systems & Deployment

<p>

<img src="https://skillicons.dev/icons?i=docker,git,linux,fastapi"/>

</p>

---

## Databases

<p>

<img src="https://skillicons.dev/icons?i=postgres,mongodb"/>

</p>

---

## Visualization

<p>

<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge"/>

</p>

---

## Deep Learning Optimization

<table>

<tr>

<td>Automatic Mixed Precision (AMP)</td>
<td>Gradient Clipping</td>
<td>Learning Rate Scheduling</td>

</tr>

<tr>

<td>Cosine Annealing</td>
<td>Training Stability</td>
<td>Distributed Optimization</td>

</tr>

</table>

---

# Engineering Interests

Rather than focusing on individual models, I enjoy building complete machine learning systems that can be trained, evaluated, deployed, and monitored efficiently.

Current engineering interests include:

- Distributed Machine Learning
- Communication-Efficient Training
- Fraud Detection Systems
- High-Volume Transaction Analytics
- Time-Series Forecasting
- ML Infrastructure
- Real-Time Inference
- Optimization Algorithms
- Simulation-Based Machine Learning
- Data-Centric AI
- Mathematical Modeling for ML

---# Featured Engineering Projects

---

## Distributed Fraud Detection for Payment Systems using LocalSGD

> **Communication-efficient distributed fraud detection system designed for large-scale payment networks using LocalSGD, real-time inference, and containerized deployment.**

| Category | Details |
|----------|----------|
| **Domain** | Distributed Machine Learning |
| **Dataset** | 6.36 Million Payment Transactions |
| **Framework** | PyTorch |
| **Deployment** | FastAPI + Docker |
| **Training Strategy** | LocalSGD with Non-IID Workers |

### Problem

Modern payment systems process millions of transactions across geographically distributed data centers. Centralized training introduces significant communication overhead while fraud detection suffers from extreme class imbalance.

### Engineering Approach

- Simulated **5 distributed worker nodes** using Non-IID data partitions
- Implemented communication-efficient **LocalSGD** synchronization
- Built an end-to-end distributed training pipeline using PyTorch
- Deployed the trained model through **FastAPI**
- Containerized the inference service using Docker

### Engineering Highlights

- Distributed LocalSGD Training
- Automatic Mixed Precision (AMP)
- Gradient Clipping
- Learning Rate Scheduling
- Network Communication Simulation
- Monitoring Dashboard
- Real-Time Fraud Inference API

### Performance

| Metric | Value |
|---------|--------|
| Accuracy | **99.94%** |
| ROC-AUC | **0.9906** |
| Fraud F1 Score | **0.680** |
| Dataset Size | **6.36M Transactions** |

### Technology Stack

`Python` • `PyTorch` • `FastAPI` • `Docker` • `LocalSGD`

**Repository →** *(Add Repository Link)*

---

## RapidoSim — Multi-Agent Ride-Hailing Simulation

> **Simulation framework for modeling ride-hailing ecosystems using reinforcement learning and stochastic optimization.**

| Category | Details |
|----------|----------|
| **Domain** | Reinforcement Learning |
| **Environment** | Multi-Agent Simulation |
| **Optimization** | Dynamic Pricing |

### Problem

Ride-hailing platforms continuously balance rider demand, driver availability, and pricing under uncertain environments.

### Engineering Approach

- Modeled dispatch as a **Markov Decision Process (MDP)**
- Designed a modular multi-agent simulation
- Compared adaptive pricing strategies with static and surge pricing baselines
- Built an experimentation framework for evaluating policy performance

### Engineering Highlights

- Reinforcement Learning Environment
- Dynamic Pricing Engine
- Modular Simulation Design
- Benchmarking Framework
- Policy Evaluation Pipeline

### Technology Stack

`Python` • `Reinforcement Learning` • `Stochastic Optimization`

**Repository →** *(Add Repository Link)*

---

## Thermal Throttling Prediction via System Telemetry

> **Machine learning pipeline for predicting CPU thermal behavior from hardware telemetry to support proactive performance management.**

| Category | Details |
|----------|----------|
| **Domain** | Predictive Analytics |
| **Model** | XGBoost |
| **Objective** | Early Thermal Throttling Detection |

### Problem

CPU thermal throttling reduces system performance. Predicting thermal behavior before throttling enables proactive resource management.

### Engineering Approach

- Built an end-to-end ML pipeline
- Engineered temporal telemetry features
- Trained XGBoost regression models
- Evaluated prediction quality for proactive intervention

### Engineering Highlights

- Feature Engineering
- Data Preprocessing Pipeline
- Regression Modeling
- Model Evaluation
- Performance Analysis

### Performance

| Metric | Value |
|---------|--------|
| R² Score | **0.355** |
| MAE | **≈ 0.73°C** |

### Technology Stack

`Python` • `XGBoost` • `Scikit-learn`

**Repository →** *(Add Repository Link)*

---

## Convex Optimization Essentials for Linear Models

> **Implementation and benchmarking of optimization algorithms from first principles for supervised learning.**

| Category | Details |
|----------|----------|
| **Domain** | Optimization |
| **Implementation** | From Scratch |
| **Frameworks** | NumPy + PyTorch |

### Problem

Understanding optimization algorithms requires more than using library implementations. This project benchmarks optimization strategies under identical training conditions.

### Engineering Approach

- Implemented optimization algorithms from scratch
- Compared convergence characteristics
- Visualized optimization trajectories
- Evaluated optimizer efficiency using cross-validation

### Implemented Algorithms

- Gradient Descent
- Mini-Batch Gradient Descent
- Stochastic Gradient Descent
- SAGA

### Performance

| Metric | Value |
|---------|--------|
| Cross Validation Accuracy | **96.5%** |

### Engineering Highlights

- Mathematical Implementation
- Convergence Visualization
- Optimizer Benchmarking
- Performance Comparison

### Technology Stack

`Python` • `NumPy` • `PyTorch` • `Matplotlib`

**Repository →** *(Add Repository Link)*

---

## ISRO Weather Forecasting using LSTM

> **End-to-end multivariate time-series forecasting pipeline developed during the Machine Learning Internship at ISRO SDSC SHAR.**

| Category | Details |
|----------|----------|
| **Domain** | Time-Series Forecasting |
| **Framework** | PyTorch |
| **Dataset** | 420K+ Observations |

### Problem

Operational weather forecasting requires robust sequence models capable of learning temporal dependencies across multiple atmospheric variables.

### Engineering Approach

- Built reusable preprocessing and sequence generation pipelines
- Applied feature engineering for multivariate atmospheric data
- Encoded wind direction using circular transformations
- Evaluated forecasting performance across multiple configurations

### Engineering Highlights

- Multivariate LSTM Pipeline
- Feature Engineering
- Circular Encoding
- Hyperparameter Optimization
- End-to-End Evaluation Pipeline

### Performance

| Metric | Value |
|---------|--------|
| Dataset | **420K+ Observations** |
| Variables | **7 Weather Features** |
| Best R² | **0.9998** |

### Technology Stack

`Python` • `PyTorch` • `LSTM`

**Repository →** *(Add Repository Link)*

---

# Research & Technical Writing

## Research

| Status | Research | Area |
|---------|----------|------|
| 📝 Under Review | **Communication-Efficient Distributed Learning using LocalSGD** | Distributed Machine Learning |
| 🚧 In Preparation | **Spatial Dispatch Networks** | Mathematical Modeling · Stochastic Systems |

---

## Technical Writing

I regularly publish engineering notes covering optimization, machine learning, and distributed training.

**Learning Optimization Newsletter**

- 26+ technical editions
- Mathematical optimization
- Gradient-based methods
- Distributed learning
- ML engineering concepts

> **Read on LinkedIn:**  
> https://www.linkedin.com/in/chandu-chowdary-bondu/

---

# GitHub Analytics

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=chanduchowdary8978&show_icons=true&hide_border=true&rank_icon=github"/>

<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chanduchowdary8978&layout=compact&hide_border=true"/>

</div>

---

<div align="center">

<img src="https://streak-stats.demolab.com?user=chanduchowdary8978&hide_border=true"/>

</div>

---

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=chanduchowdary8978&hide_border=true"/>

</div>

---

# Current Engineering Focus

| Building | Optimizing | Research |
|-----------|------------|----------|
| Communication-Efficient ML Systems | Distributed Training | LocalSGD |
| Production ML Pipelines | Training Stability | Distributed Optimization |
| Real-Time Inference APIs | Automatic Mixed Precision | Mathematical Modeling |
| Fraud Detection Systems | Gradient-Based Optimization | Large-Scale ML Systems |

---

# Engineering Principles

- Design machine learning systems that are reproducible, scalable, and measurable.
- Benchmark models using appropriate evaluation metrics rather than relying solely on accuracy.
- Treat optimization as both a mathematical problem and a systems engineering challenge.
- Prioritize production readiness through deployment, monitoring, and reproducible workflows.
- Build solutions that balance model performance with computational efficiency.

---

# Education

| Degree | Institution | Duration |
|----------|-------------|----------|
| **M.Tech — Mathematics & Computing** | Dr. B. R. Ambedkar National Institute of Technology, Jalandhar | 2025 – 2027 |
| **B.Tech — Computer Science & Engineering** | JNTUA College of Engineering, Kalikiri | 2020 – 2024 |

---

# Professional Experience

## Machine Learning Intern

**Indian Space Research Organisation (ISRO) – SDSC SHAR**

**Feb 2024 – May 2024**

Worked on an end-to-end multivariate weather forecasting pipeline using LSTM models over large-scale atmospheric datasets.

Key contributions included:

- Data preprocessing pipeline
- Sequence generation
- Feature engineering
- Circular encoding
- Model evaluation
- Hyperparameter optimization
- Forecast accuracy analysis

---

# Open Source Goals

Current long-term engineering priorities include:

- Building production-quality ML systems
- Contributing reusable ML infrastructure
- Publishing reproducible research
- Developing scalable distributed learning frameworks
- Improving model deployment workflows

---

# Connect

<div align="center">

<a href="https://chanduchowdary8978.github.io/Chandu_Portfolio/">
<img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>

<a href="https://github.com/chanduchowdary8978">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/>
</a>

<a href="https://www.linkedin.com/in/chandu-chowdary-bondu/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:chanduchowdary8978@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

---

<div align="center">

### Thanks for visiting.

Machine Learning • Distributed Systems • Optimization • ML Infrastructure

</div>


### Machine Learning Engineer · Math-First Thinker · NIT Jalandhar

*"I trust an ML model only after reducing it to math."*

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logoColor=white)](https://chanduchowdary8978.github.io/Chandu_Portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chandu-chowdary-bondu/)

</div>

---

## About Me

I am a **Machine Learning Engineer** pursuing M.Tech in Mathematics & Computing at **NIT Jalandhar**, with a strong focus on understanding *why* models work — not just how to use them.

My work sits at the intersection of **mathematical rigor** and **practical ML systems**:

- I study gradient-based optimization, convergence theory, and loss landscapes from first principles
- I build end-to-end ML pipelines — from data ingestion to training, evaluation, and deployment
- I have applied these skills in a real-world research environment at **ISRO – SDSC SHAR**
- I write about optimization and ML engineering — [read my notes on LinkedIn](https://www.linkedin.com/in/chandu-chowdary-bondu/)

> My long-term goal: become an AI engineer who combines **mathematical depth** with **strong systems thinking** — building models that are accurate, stable, interpretable, and deployable.

---

## Currently

- Working on: **Core Gradients — Optimization from Scratch** (convergence analysis, gradient-based methods)
- Learning: **Statistical Learning Theory · Proximal and Second-Order Methods · MLOps Architecture**
- Open to collaborate on: **Math-heavy ML / AI research projects**
- Exploring: **Quantitative Finance applications of ML**
- Ask me about: **ML, Linear Algebra, Probability, Convex Optimization, Gradient Descent**

---

## Featured Projects

### [Core Gradients: Optimization from Scratch](https://github.com/chanduchowdary8978) &nbsp;·&nbsp; NIT Jalandhar &nbsp;·&nbsp; Nov 2025 – Jan 2026

> A deep, from-scratch exploration of gradient-based optimization methods with mathematical intuition and convergence analysis.

- Implemented **linear and logistic regression** from scratch on real datasets
- Studied convex sets, convex functions, and optimality conditions rigorously
- Applied **GD / SGD / Mini-batch** variants with gradient, subgradient, and proximal methods
- Analyzed **KKT conditions** to understand constrained optimization and regularization effects

---

### [Performance-Aware Thermal Throttling Prediction](https://github.com/chanduchowdary8978) &nbsp;·&nbsp; Self Project &nbsp;·&nbsp; Sep – Nov 2025

> An ML system to predict CPU thermal throttling events from system telemetry — combining classification and regression in a unified pipeline.

- Formulated throttling detection as a **classification problem** with advance prediction
- Built a **regression model** to forecast future CPU temperature at the predicted event time
- Performed time-aligned **feature engineering** and preprocessing for prediction stability

---

### [Time-Series Forecasting with LSTM — ISRO Internship](https://github.com/chanduchowdary8978) &nbsp;·&nbsp; ISRO SDSC SHAR &nbsp;·&nbsp; Feb – May 2024

> End-to-end LSTM forecasting on real operational weather data in a constrained research environment.

- Developed **LSTM-based** time-series models on live operational weather datasets from ISRO
- Built a complete **training and evaluation pipeline** for sequence modeling
- Analyzed model behavior: error patterns, stability, and generalization under real constraints

---

### [Hyperparameter Optimization Tool](https://github.com/chanduchowdary8978) &nbsp;·&nbsp; Self Project &nbsp;·&nbsp; Nov 2023 – Jan 2024

> A Streamlit-based GUI tool to explore and compare hyperparameter tuning strategies interactively.

- Explored **grid search and random search** strategies with efficiency trade-off analysis
- Built a full **Streamlit GUI** for uploading datasets, tuning parameters, and evaluating models

---

### [Titanic Survival Prediction](https://github.com/chanduchowdary8978) &nbsp;·&nbsp; Self Project &nbsp;·&nbsp; Sep – Nov 2023

> A tabular ML classification project focused on deep feature engineering and model comparison.

- Engineered features and preprocessed data for robust tabular classification
- Compared multiple classifiers; achieved **0.825 accuracy** with ensemble methods

---

## Mathematical Foundations

```
Linear Algebra          ->  Foundations of every model I build
Probability Theory      ->  Distributions, expectations, and inference
Convex Optimization     ->  Optimality, duality, KKT conditions
Gradient-Based Methods  ->  GD, SGD, Proximal, Subgradient, Adam variants
Convergence Theory      ->  Smoothness, Lipschitz constants, conditioning
Statistical Learning    ->  Bias-variance, regularization, generalization bounds
```

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**ML and Math**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

**MLOps and Systems**

![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Tools**

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![pgAdmin](https://img.shields.io/badge/pgAdmin4-336791?style=flat-square&logo=postgresql&logoColor=white)

---

## Education

| Degree | Institution | CGPA | Year |
|---|---|---|---|
| **M.Tech** – Mathematics & Computing | NIT Jalandhar | 7.77 *(1st Sem)* | 2025 – 2027 |
| **B.Tech** – Computer Science & Engineering | JNTU College of Engineering, Kalikiri | 7.66 | 2020 – 2024 |

---

## Experience

**Machine Learning Intern — Indian Space Research Organisation (ISRO), SDSC SHAR**
`Feb 2024 – May 2024`

Worked on LSTM-based time-series forecasting with real operational weather data in a constrained, research-grade environment. Built an end-to-end pipeline covering training, evaluation, error analysis, and deployment considerations.

---

## Ongoing Self-Study

I maintain an active study practice outside coursework. Currently focused on:

- **Gradient-based optimization** — both mathematical derivations and application trade-offs
- **Convergence and stability analysis** — across GD, SGD, proximal, and second-order methods
- **Constrained optimization** — KKT theory, dual problems, and regularization connections
- **Modern deep learning optimizers** — Adam, AdaGrad, RMSProp and their practical behavior
- **MLOps architecture** — Kafka pipelines, MLflow tracking, and deployment workflows

---

## Latest Writing

I publish notes and articles on ML engineering and optimization on LinkedIn:

- **[Core Gradients: Batch Gradient Descent](https://www.linkedin.com/in/chandu-chowdary-bondu/)** — Geometric and optimization perspective, smoothness and convergence behavior *(Feb 2026)*
- **[Learning Rates, Lipschitz Constants, and Convergence](https://www.linkedin.com/in/chandu-chowdary-bondu/)** — Why step size matters and what goes wrong with bad conditioning *(Feb 2026)*

---

<div align="center">

### Let's Connect

*I am always open to discussing ML research, optimization theory, or interesting engineering problems.*

[![Portfolio](https://img.shields.io/badge/Visit_Portfolio-000000?style=for-the-badge)](https://chanduchowdary8978.github.io/Chandu_Portfolio/)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chandu-chowdary-bondu/)

---

![Profile Views](https://komarev.com/ghpvc/?username=chanduchowdary8978&color=blue&style=flat-square&label=Profile+Views)

*"Mathematics is the language in which the universe is written — and gradient descent is how we read it."*

</div>

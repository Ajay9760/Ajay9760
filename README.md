# Hi, I'm Ajay Adire 👋

**CSE-DS Graduate** · Full-Stack Engineer · Data Science Practitioner  
📍 Hyderabad, India · 🔗 [LinkedIn](https://www.linkedin.com/in/ajay-adire-a03868309/) · 🐙 [GitHub](https://github.com/Ajay9760)

---

## 💼 Professional Summary

I'm a Computer Science & Data Science graduate who bridges backend engineering and machine learning. I design and build production-grade systems across three key areas:

1. **Full-Stack Systems**: Distributed microservices, secure APIs, scalable web apps
2. **Machine Learning**: Real-world predictive models for healthcare, deployed as interactive applications
3. **Product Engineering**: From concept to live deployment with clean architecture and rigorous testing

I approach every project with a data-driven mindset—whether that means optimizing distributed systems, tuning ML model thresholds against business constraints, or designing databases that scale. My work spans React/React Native frontends, Spring Boot/Node.js backends, PostgreSQL/Redis infrastructure, and ML pipelines with scikit-learn.

- 🏗️ I design full-stack systems with complex business logic: microservices, auth flows, payments, and cloud deployments
- 🤖 I build ML models that solve real problems: feature engineering, model comparison, threshold tuning, and actionable insights
- 📊 My CSE-DS foundation helps me think holistically about data modeling, scalability, performance, and system trade-offs
- 🔒 I prioritize engineering discipline: security, testing, CI/CD automation, and code quality across all domains
- 🌱 I'm exploring AI/ML integrations that enhance product experiences and drive data-informed decisions

---

## 🛠️ Tech Stack

**Languages**  
`Java` · `Python` · `JavaScript` · `TypeScript` · `SQL`

**Backend & APIs**  
`Spring Boot` · `Node.js` · `Express` · `RESTful APIs` · `JWT Authentication`

**Frontend**  
`React` · `React Native` · `Redux Toolkit` · `Tailwind CSS` · `Streamlit`

**Data Science & ML**  
`Scikit-learn` · `Pandas` · `NumPy` · `Jupyter` · `Feature Engineering` · `Model Evaluation`

**Databases & Messaging**  
`PostgreSQL` · `Redis` · `RabbitMQ` · `Quartz Scheduler`

**Cloud / DevOps**  
`Docker` · `Docker Compose` · `GitHub Actions` · `Nginx` · `CI/CD`

**Testing & Quality**  
`Jest` · `Playwright` · `JUnit 5` · `Mockito` · `CodeQL` · `Snyk`

---

## 🚀 Featured Projects

### **Backend & Systems Engineering**

#### [Chronos — Distributed Job Scheduler](https://github.com/Ajay9760/Job-Scheduler)
> Enterprise-grade distributed job scheduling system built with a three-service microservices architecture

A scalable scheduling platform built with Spring Boot, PostgreSQL, RabbitMQ, and Quartz. Demonstrates distributed system design with independent API, scheduler, and worker services handling asynchronous job execution, retries, cron-based scheduling, and execution history tracking.

`Java 21` · `Spring Boot 3.2` · `PostgreSQL` · `RabbitMQ` · `Quartz Scheduler` · `Docker` · `Flyway`

---

#### [NanoInfluencer Marketplace](https://github.com/Ajay9760/nanoinfluencer-marketplace) · [Live Site](https://ajay9760.github.io/nanoinfluencer-marketplace)
> A two-sided marketplace connecting brands with nano-influencers for performance-driven marketing

Combines a secure full-stack architecture with business-focused product logic. Includes JWT-based authentication with short-lived access tokens, refresh token rotation, 2FA with TOTP, role-based access, Stripe test-mode payments, file validation, and deployment automation with GitHub Actions.

`React 18` · `TypeScript` · `Node.js` · `Express` · `PostgreSQL` · `Redis` · `Docker` · `Nginx`

---

#### [CalorieFitnessTracker](https://github.com/Ajay9760/CalorieFitnessTracker)
> Cross-platform fitness and nutrition tracking application with React Native mobile and React web dashboard

A complete health-tracking product with a custom Indian food database of 1,000+ items, calorie logging, workout tracking, and visual analytics. Demonstrates full-stack product design with clean architecture and state management across platforms.

`React Native` · `React` · `TypeScript` · `Node.js` · `Express` · `Redux Toolkit` · `Recharts`

---

### **Machine Learning & Data Science**

#### [Hospital Readmission Risk Predictor](https://github.com/Ajay9760/Hospital-Readmission-RIsk) · [Live App](https://hospital-readmission-risk-auyqrxqyrqfaywmh3rrgmn.streamlit.app/)
> Real-world ML model predicting which diabetic inpatients are at high risk of 30-day readmission

This project demonstrates end-to-end data science workflow with real clinical data:

**Data Engineering**:
- Cleaned and handled missing values across 101,766 inpatient encounters (0.2% to 96.9% missingness)
- Made principled decisions: dropped low-signal features (weight at 96.9% missing), retained clinically meaningful missing values (unmeasured labs as signal, not noise)
- Avoided patient-level data leakage by splitting on encounter ID, not random rows

**Feature Engineering**:
- Bucketed raw ICD-9 diagnosis codes (hundreds of values) into 8 clinically meaningful categories
- Engineered time-based features, categorical encodings, and handled class imbalance

**Modeling & Threshold Tuning**:
- Compared Logistic Regression (interpretable baseline) vs. Random Forest (non-linear capture)
- Tuned decision threshold (0.521 = top 20%) against realistic operational constraint: hospital care teams can manage ~1 in 5 patients
- Identified consensus risk drivers: prior visits, age 70–90, diabetes meds, absent A1C testing

**Results**: ROC-AUC 0.63 (consistent with published research); precision/recall tuned for operational deployment, not raw accuracy

**Deployment**: Live Streamlit app with risk calculator, model explainability (top drivers), and threshold adjustment

`Python` · `Scikit-learn` · `Pandas` · `Streamlit` · `Jupyter` · `Random Forest` · `Logistic Regression`

---

#### [Diabetes Risk Prediction](https://github.com/Ajay9760/Diabetes-Prediction-Model) · [Live App](https://diabetes-prediction-model-xv.streamlit.app/)
> Interactive ML dashboard for diabetes risk prediction from patient health measurements

A streamlined classification model built with scikit-learn and deployed as an interactive Streamlit app. Demonstrates model training, serialization, and real-time inference on 8-feature patient data.

**Features**:
- Logistic Regression model with feature scaling
- Real-time prediction interface with sidebar input controls
- Model analytics dashboard: evaluation metrics, confusion matrix, feature coefficients
- Probability output for risk stratification

**Metrics**: 73.38% test accuracy, ROC-AUC 0.79, precision/recall tradeoff analysis

`Python` · `Scikit-learn` · `Streamlit` · `Pandas` · `Joblib`

---

#### [Breast Cancer Prediction](https://github.com/Ajay9760/Breast-Cancer-Prediction) · [Live App](https://breast-cancer-prediction-zihlnsndewsl4skz8km4p7.streamlit.app/)
> ML classification model for predicting breast cancer diagnosis from tumor characteristics

A clinical prediction model deployed as a live, interactive Streamlit application for real-time risk assessment.

`Python` · `Scikit-learn` · `Streamlit` · `Pandas` · `Joblib`

---

### **Other Projects**

#### [NewsAggregator](https://github.com/Ajay9760/NewsAggregator)
> Personalized news API backend using Spring Boot and JWT-based authentication

Demonstrates secure API design with user personalization, external data integration, and role-aware access patterns.

`Java` · `Spring Boot` · `JWT` · `Spring Security` · `REST API`

---

#### [Library Management System](https://github.com/Ajay9760/Library-Management-System)
> Backend system for managing books, members, and borrowing records

`Java` · `Spring Boot` · `SQL`

---

#### [BookMyShow DB Design](https://github.com/Ajay9760/BookMyShow-)
> Fully normalized relational database schema for a ticket booking platform

Demonstrates advanced SQL design with normalization through BCNF for complex business domains.

`SQL` · `Database Design` · `Normalization (1NF → BCNF)`

---

## 📊 Technical Strengths by Domain

### **Full-Stack Engineering**
✅ Microservices architecture with service isolation and async communication  
✅ RESTful API design with JWT authentication, role-based access, token rotation  
✅ React/React Native for responsive, state-managed frontends  
✅ Spring Boot and Node.js for scalable backends  
✅ PostgreSQL with normalization, Redis caching, RabbitMQ messaging  
✅ Docker containerization and GitHub Actions CI/CD  

### **Machine Learning & Data Science**
✅ End-to-end ML pipelines: EDA → cleaning → engineering → training → evaluation → deployment  
✅ Feature engineering: categorical encoding, bucketing, handling missing data with domain knowledge  
✅ Model selection: Logistic Regression for interpretability, Random Forest for non-linear capture  
✅ Threshold tuning: Optimizing for business constraints, not just raw accuracy  
✅ Deployment: Streamlit for interactive dashboards, real-time inference, explainability  
✅ Handling real-world messiness: class imbalance, data leakage, sparse features, clinical domain knowledge

### **Engineering Discipline**
✅ Security: 2FA, token rotation, HTTPS, input validation, automated scanning  
✅ Testing: Unit tests, E2E tests, 80%+ code coverage, security scanning  
✅ Code quality: TypeScript, Lombok, MapStruct, linting, formatting  
✅ Observability: Logging, health checks, metrics, error tracking  

---

## 📈 GitHub Stats

![Ajay's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Ajay9760&show_icons=true&theme=default&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Ajay9760&layout=compact&hide_border=true)

---

## 📫 Connect

- 💼 [LinkedIn — Ajay Adire](https://www.linkedin.com/in/ajay-adire-a03868309/)
- 🐙 [GitHub — @Ajay9760](https://github.com/Ajay9760)

---

_Open to full-stack engineering, backend roles, and data science positions. I'm passionate about building systems that work reliably and models that drive real business decisions._

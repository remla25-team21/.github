# REMLA25 Team 21 - Sentiment Analysis Project

Welcome to REMLA25 Team 21's project! 🚀

This organization contains a complete **Development Operations (DevOps)** and **Machine Learning Operations (MLOps)** project that demonstrates sentiment analysis using modern software engineering practices, containerization, and cloud-native technologies.

## 🎯 Project Overview

Our sentiment analysis application performs real-time sentiment classification on user feedback using a machine learning model. The project showcases a complete MLOps pipeline with microservices architecture, monitoring, testing, and deployment automation.

**🌐 Live Demo**: Access our application through the deployment instructions below!

## 🏗️ Architecture & Repository Structure

The project is organized into **6 specialized repositories**, each serving a specific purpose in our DevOps and MLOps pipeline:

### 📊 Core Repositories

| Repository | Purpose | Tech Stack |
|------------|---------|------------|
| **[operation](https://github.com/remla25-team21/operation)** | 🚀 **Main entry point** - Orchestration & deployment | Kubernetes, Helm, Docker Compose, Istio |
| **[app](https://github.com/remla25-team21/app)** | 🖥️ Frontend UI & backend service | Flask, HTML/CSS/JS, Prometheus metrics |
| **[model-service](https://github.com/remla25-team21/model-service)** | 🤖 ML model serving API | Flask, REST API |
| **[model-training](https://github.com/remla25-team21/model-training)** | 🧠 ML training pipeline | Python, scikit-learn, DVC |

### 📚 Shared Libraries

| Repository | Purpose | Usage |
|------------|---------|-------|
| **[lib-ml](https://github.com/remla25-team21/lib-ml)** | 🔧 Data preprocessing utilities | Shared across training & serving |
| **[lib-version](https://github.com/remla25-team21/lib-version)** | 📋 Version management | System versioning & metadata |

## 📈 Features & Capabilities

### 🎯 Machine Learning

- **Sentiment Classification**: Restaurant review sentiment analysis
- **Model Versioning**: DVC-based data and model versioning
- **A/B Testing**: Multiple model variants with traffic splitting
- **ML Testing**: Comprehensive test suite for model quality

### 🏗️ Infrastructure

- **Containerization**: Docker containers for all services
- **Orchestration**: Kubernetes deployment with Helm charts
- **Service Mesh**: Istio for traffic management and observability
- **Monitoring**: Prometheus metrics with Grafana dashboards

### 🔍 Observability

- **Metrics Collection**: Custom Prometheus metrics for ML operations
- **Session Tracking**: User behavior and satisfaction monitoring
- **Performance Monitoring**: Response time and throughput metrics
- **Sticky Sessions**: User-consistent A/B testing experience

### 🔧 DevOps & Quality

- **CI/CD**: Automated testing and deployment pipelines
- **Code Quality**: Pylint, Flake8, and Bandit for code analysis
- **Security Scanning**: Automated vulnerability detection
- **Documentation**: Comprehensive API documentation with Swagger

## 📊 Monitoring & Metrics

Our application includes comprehensive monitoring:

- **Business Metrics**: Sentiment prediction distribution, user satisfaction
- **Technical Metrics**: Response times, error rates, resource usage
- **User Metrics**: Session duration, rating distribution
- **Model Metrics**: Prediction accuracy, model usage by variant

Access monitoring dashboards through the Kubernetes deployment options above.

## 🤝 Contributing

This project was developed as part of the REMLA (Release Engineering for Machine Learning Applications) course. Each repository contains detailed contribution guidelines and development setup instructions.

## 📄 License

This project is developed for educational purposes as part of REMLA25 coursework.

---

**🚀 Ready to get started?** Head to the **[operation repository](https://github.com/remla25-team21/operation)** for detailed deployment instructions!

For questions or issues, please check the individual repository README files or create an issue in the relevant repository.

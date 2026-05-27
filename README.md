# 100 Days of MLOps Challenge [KodeKloud]

This repository contains the code and resources for the **100 Days of MLOps** challenge by KodeKloud. The course is designed to help you learn and practice MLOps concepts and techniques over a span of 100 days.

---
[![GitHub stars](https://img.shields.io/github/stars/imshakil/100-days-mlops-kodekloud?style=social)](https://github.com/imshakil/100-days-mlops-kodekloud/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/imshakil/100-days-mlops-kodekloud?style=social)](https://github.com/imshakil/100-days-mlops-kodekloud/network/members)
[![GitHub issues](https://img.shields.io/github/issues/imshakil/100-days-mlops-kodekloud)](https://github.com/imshakil/100-days-mlops-kodekloud/issues)
![Badge](https://hitscounter.dev/api/hit?url=https%3A%2F%2Fgithub.com%2FimShakil%2F100-days-mlops-kodekloud&label=&icon=github&color=%23198754&message=&style=flat&tz=UTC)

## Course Overview

This challenge walks through core MLOps practice end to end. You start with local Python setup, project structure, and code quality, then move through data versioning, experiment tracking, model registry, training pipelines, serving, monitoring, CI/CD, and Kubernetes-based deployment.

## Prerequisite

Before starting, you should know basic Python, Git, command-line work, and simple machine learning workflows. Helpful extras: Docker, YAML, and comfort editing files in a terminal. I would recommend finishing this [100 days of DevOps challenge](https://linkly.link/2CeGc) before starting here.

## What You'll Learn

By the end of the 100 days, you should be able to:

- Set up reproducible Python environments and standard ML project layouts
- Use DVC and MLflow for data, experiments, metrics, and model lifecycle tracking
- Package, test, lint, and automate ML workflows with modern Python tooling
- Build and containerize model serving APIs with Flask, FastAPI, BentoML, and Docker
- Add monitoring, drift detection, reporting, and retraining workflows
- Build CI/CD pipelines for model validation, registration, deployment, and rollback
- Orchestrate ML workloads on Kubernetes with Argo, Prefect, KServe, and Kubeflow Pipelines

## Quick Start

1. **Star this repository** ⭐ to keep track of your progress
2. **Fork the repo** to create your own copy
3. Start with [Day 001](days/001.md) - Create a Python Virtual Environment for ML
4. Follow the daily challenges in order
5. Share your progress using `#100DaysOfMLOps`

> **Want to start the official challenge?** Use this [KodeKloud link](https://linkly.link/2CeSH) - it helps support this project!

## Challenge Progress

![14%](https://progress-bar.xyz/14)

## Daily Challenges

| Day | Challenge | Topics | Solution |
| --- | --------- | ------ | -------- |
| 01 | Create a Python Virtual Environment for ML | Python, virtual environments, project setup | [Solved](days/001.md) |
| 02 | Set Up and Configure Jupyter Notebook Server | Jupyter, notebooks, local dev setup | [Solved](days/002.md) |
| 03 | Fix a Broken uv Lockfile Specification | uv, dependency locking, package resolution | [Solved](days/003.md) |
| 04 | Create a Standard ML Project Structure | repository structure, packaging, conventions | [Solved](days/004.md) |
| 05 | Create a Makefile for ML Workflow Automation | Makefile, task automation, developer workflow | [Solved](days/005.md) |
| 06 | Set Up Code Quality Tools for ML Code | linting, formatting, static analysis | [Solved](days/006.md) |
| 07 | Package an ML Project as Installable Python Package | packaging, setuptools, installation | [Solved](days/007.md) |
| 08 | Configure Pre-Commit Hooks for ML Repository | pre-commit, git hooks, code quality | [Solved](days/008.md) |
| 09 | Create a Custom ML Project Template with Cookiecutter | Cookiecutter, templates, scaffolding | [Solved](days/009.md) |
| 10 | Install and Initialize DVC in an ML Project | DVC, data versioning, initialization | [Solved](days/010.md) |
| 11 | Track a Dataset with DVC | DVC, dataset tracking, reproducibility | [Solved](days/011.md) |
| 12 | Configure a DVC Remote Storage | DVC, remote storage, artifact sync | [Solved](days/012.md) |
| 13 | Pull DVC-Tracked Data from Remote | DVC, pull, data restore | [Solved](days/013.md) |
| 14 | Create a DVC Pipeline for Data Processing | DVC pipelines, data processing, stages | [Solved](days/014.md) |
| 15 | Parameterize a DVC Pipeline | DVC, parameters, pipeline configuration | Pending |
| 16 | Track ML Metrics with DVC | DVC, metrics, experiment tracking | Pending |
| 17 | Run and Compare DVC Experiments | DVC, experiments, comparison | Pending |
| 18 | Version Datasets and Models Across Git Branches | Git branches, model versioning, datasets | Pending |
| 19 | Build Complete DVC ML Pipeline with Remote Storage and Experiments | DVC, remote storage, full pipeline | Pending |
| 20 | Install and Start the MLflow Tracking Server | MLflow, tracking server, setup | Pending |
| 21 | Log an ML Experiment to MLflow | MLflow, experiment logging, runs | Pending |
| 22 | Create and Organize MLflow Experiments | MLflow, experiment management, organization | Pending |
| 23 | Search and Query MLflow Runs | MLflow, search, querying runs | Pending |
| 24 | Enable MLflow Autologging | MLflow, autologging, instrumentation | Pending |
| 25 | Register, Version, and Manage Model Lifecycle | MLflow, model registry, lifecycle | Pending |
| 26 | Compare Model Runs and Select the Best | MLflow, model comparison, selection | Pending |
| 27 | Load Model from Registry with Custom Preprocessing | MLflow, registry, preprocessing | Pending |
| 28 | Fix a Broken MLflow Project and Re-Run It | MLflow, debugging, project recovery | Pending |
| 29 | Configure MLflow with Remote Tracking Server and Artifact Store | MLflow, remote tracking, artifacts | Pending |
| 30 | End-to-End MLflow Lifecycle: Train, Register, Serve, Monitor | MLflow, lifecycle, deployment, monitoring | Pending |
| 31 | Train a Scikit-Learn Model with Reproducible Script | scikit-learn, training script, reproducibility | Pending |
| 32 | Manage Training Configuration with YAML | YAML, configuration, training params | Pending |
| 33 | Evaluate a Trained Model and Generate Classification Report | evaluation, metrics, classification report | Pending |
| 34 | Implement Cross-Validation for Model Selection | cross-validation, model selection, evaluation | Pending |
| 35 | Hyperparameter Tuning with Optuna | Optuna, hyperparameter tuning, optimization | Pending |
| 36 | Automated Model Selection with FLAML AutoML | FLAML, AutoML, model selection | Pending |
| 37 | Distributed Model Training with Joblib Parallelization | joblib, parallelization, distributed training | Pending |
| 38 | Build Modular Training Pipeline with Config-Driven Stages | modular design, config-driven pipeline, training | Pending |
| 39 | Train a PyTorch Model with GPU Support and Checkpointing | PyTorch, GPU, checkpointing | Pending |
| 40 | Production Training System: Tracking, Tuning, and Model Selection | production training, tracking, tuning | Pending |
| 41 | Install and Initialize a Feast Feature Store | Feast, feature store, initialization | Pending |
| 42 | Define Feature Views in Feast | Feast, feature views, feature engineering | Pending |
| 43 | Materialize Features to the Online Store | Feast, online store, materialization | Pending |
| 44 | Store MLflow's Admin Password in HashiCorp Vault | Vault, secrets, MLflow integration | Pending |
| 45 | Fix a Broken Vault KV Policy for the MLflow Reader | Vault, policies, access control | Pending |
| 46 | Author Data-Quality Expectations with Great Expectations | Great Expectations, data quality, expectations | Pending |
| 47 | Debug a Failing Great Expectations Checkpoint | Great Expectations, checkpoints, debugging | Pending |
| 48 | Publish Great Expectations Data Docs as a CI Artefact | Great Expectations, CI, documentation | Pending |
| 49 | Secrets + Data-Quality Integration Capstone | secrets management, data quality, capstone | Pending |
| 50 | Create Docker Image for ML Training Environment | Docker, containerization, training env | Pending |
| 51 | Create Multi-Stage Docker Build for ML Serving | Docker, multi-stage builds, serving | Pending |
| 52 | Set Up Local ML Dev Environment with Docker Compose | Docker Compose, local dev, services | Pending |
| 53 | Create GPU-Enabled Docker Image for Deep Learning | Docker, GPU, deep learning | Pending |
| 54 | Push ML Model Images to Container Registry | container registry, image push, Docker | Pending |
| 55 | Add Health Checks and Graceful Shutdown to ML Containers | health checks, shutdown, reliability | Pending |
| 56 | Automate ML Docker Image Building in CI Pipeline | CI, Docker build, automation | Pending |
| 57 | Serve an ML Model with Flask | Flask, serving, API | Pending |
| 58 | Serve an ML Model with FastAPI | FastAPI, serving, API | Pending |
| 59 | Run Batch Predictions on a Dataset | batch inference, predictions, dataset processing | Pending |
| 60 | Package a Model as a BentoML Service | BentoML, packaging, model service | Pending |
| 61 | Containerize an ML Model API with Docker | Docker, API containerization, serving | Pending |
| 62 | Implement A/B Testing for Model Deployment | A/B testing, deployment, experimentation | Pending |
| 63 | Implement Async Batch Prediction with Task Queue | async jobs, task queues, batch prediction | Pending |
| 64 | Serve Multiple Models Behind Unified API Gateway | API gateway, multi-model serving, routing | Pending |
| 65 | Implement Canary Deployment for Model Updates | canary deployment, rollout, release strategy | Pending |
| 66 | Production Model Serving with Docker Compose | Docker Compose, production serving, orchestration | Pending |
| 67 | Add Prometheus as a Grafana Data Source | Prometheus, Grafana, observability | Pending |
| 68 | Generate a Model Performance Report | model performance, reporting, metrics | Pending |
| 69 | Generate a Data Quality Report | data quality, reporting, validation | Pending |
| 70 | Create Automated Tests with Evidently Test Suites | Evidently, testing, monitoring | Pending |
| 71 | Set Up Evidently Monitoring Dashboard | Evidently, dashboard, monitoring | Pending |
| 72 | Set Up Drift Detection Alerts | drift detection, alerts, monitoring | Pending |
| 73 | Automatic Retraining Triggered by Drift Detection | drift detection, retraining, automation | Pending |
| 74 | Monitor Custom Business Metrics Alongside ML Metrics | business metrics, ML metrics, monitoring | Pending |
| 75 | End-to-End Monitoring: Prometheus, Grafana, Evidently | monitoring stack, observability, ML metrics | Pending |
| 76 | Create CI Pipeline for ML Code Linting and Testing | CI, linting, testing | Pending |
| 77 | Add Data Validation to CI Pipeline | CI, data validation, quality gates | Pending |
| 78 | Add Model Validation Tests to CI | CI, model validation, testing | Pending |
| 79 | Generate Model Performance Reports in CI with CML | CML, CI, reporting | Pending |
| 80 | Automate Model Registration in CI/CD | CI/CD, model registry, automation | Pending |
| 81 | Automate Model Deployment with CD Pipeline | CD, deployment, automation | Pending |
| 82 | End-to-End ML CI/CD Pipeline | CI/CD, automation, deployment | Pending |
| 83 | Automated Model Rollback with Health Checks | rollback, health checks, deployment safety | Pending |
| 84 | Production ML CI/CD with Multi-Environment Promotion | CI/CD, promotion, environments | Pending |
| 85 | Install Argo Workflows on Kubernetes | Argo Workflows, Kubernetes, installation | Pending |
| 86 | Create a Basic ML Training Workflow in Argo | Argo Workflows, training workflow, Kubernetes | Pending |
| 87 | Pass Data Between Argo Steps with Output Parameters and Branching | Argo, parameters, branching | Pending |
| 88 | Create an ML Pipeline with Prefect | Prefect, workflow orchestration, pipelines | Pending |
| 89 | Parallel Model Training with Argo withItems Fan-Out | Argo, parallelism, fan-out | Pending |
| 90 | Automated Retraining with Argo CronWorkflow | Argo, CronWorkflow, scheduled retraining | Pending |
| 91 | Production ML Pipeline: Argo Workflows + MLflow on Kubernetes | Argo, MLflow, Kubernetes pipeline | Pending |
| 92 | Deploy an ML Model on Kubernetes | Kubernetes, deployment, serving | Pending |
| 93 | Configure HPA for ML Serving Deployment | Kubernetes, HPA, autoscaling | Pending |
| 94 | Deploy a Model with KServe InferenceService | KServe, inference service, Kubernetes | Pending |
| 95 | Kubeflow Pipelines - Install and Run a Basic KFP Pipeline | Kubeflow Pipelines, installation, orchestration | Pending |
| 96 | GitOps Model Deployment with ArgoCD | GitOps, ArgoCD, deployment | Pending |
| 97 | Capstone (1/4): End-to-End ML System - Train, Register, Serve | capstone, training, registry, serving | Pending |
| 98 | Capstone (2/4): Monitoring and Automated Retraining | capstone, monitoring, retraining | Pending |
| 99 | Capstone (3/4): Orchestrate the Full MLOps Loop with Argo Workflows | capstone, orchestration, Argo Workflows | Pending |
| 100 | Capstone (4/4): Close the Loop with Prometheus + Grafana Observability | capstone, Prometheus, Grafana, observability | Pending |

## 🤝 Contributing

Contributions are welcome! If you think any solution steps would be better, Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/improvement-day-number`)
3. **Commit** your changes (`git commit -am 'Add new solution for days-number'`)
4. **Push** to the branch (`git push origin feature/improvement-day-number`)
5. **Create** a Pull Request

## ⭐ Show Your Support

If this repository helped you in your DevOps journey:

- **Star** this repository ⭐
- **Fork** it to create your own version
- **Share** it with fellow developers
- **Follow me** for more DevOps content

## 📄 License

This project is licensed under the GPL License - see the [LICENSE](LICENSE) file for details.

## 🔗 Connect With Me

- **GitHub**: [@imshakil](https://github.com/imshakil)
- **LinkedIn**: [Connect with me](https://linkedin.com/in/imshakil)
- **Medium**: [@imshakil](https://medium.com/@imshakil)

---

**Happy Learning!**

> Remember: Start with Day 1 and build your skills progressively!

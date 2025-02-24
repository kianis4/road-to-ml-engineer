Week 5: MLOps, Cloud, and Productionization
## Goal
Learn how to package models (Docker), serve them (FastAPI), deploy to the cloud (AWS, GCP), and monitor in production. Understand the lifecycle of ML in a real industry setting.

## Monday: Containerization with Docker
**Notebook**: `05_mlops_cloud_deployment.ipynb`
- Create a Dockerfile for a trained scikit-learn or TF/PyTorch model.
- Test locally.

## Tuesday: Model Serving & APIs
**Topics**:
- FastAPI or Flask microservice exposing a `/predict` endpoint.

**Notebook Tasks**:
- Write the API, containerize it, test with `curl` or `requests`.
- Add basic request logging.

## Wednesday: CI/CD for ML
**Topics**:
- GitHub Actions or GitLab CI (building & testing Docker images).
- Unit tests for your model code.

**Notebook Tasks**:
- Set up a pipeline that runs tests and builds images automatically on push.

## Thursday: Cloud Deployment
**Topics**:
- AWS ECS/EKS, AWS Elastic Beanstalk, or GCP Cloud Run.

**Notebook Tasks**:
- Push your Docker image to a registry.
- Deploy to the cloud, test your public endpoint.

## Friday: Monitoring & Logging
**Topics**:
- AWS CloudWatch, GCP Stackdriver.
- Basic metrics for inference latency, memory usage, error rates.

**Notebook Tasks**:
- Set up logs and demonstrate how to retrieve them.
- Simulate traffic, track metrics.

## Weekend: Consolidation
- Document your MLOps pipeline thoroughly in the notebook & repo README.

**ADHD Tip**: Schedule short daily tasks (deploy, verify logs, update docs) to avoid overload.
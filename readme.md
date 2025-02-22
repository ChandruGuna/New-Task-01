# Python Flask App - AWS EKS Deployment

This project demonstrates how to containerize a Python Flask application, push the Docker image to AWS Elastic Container Registry (ECR), and deploy it on AWS Elastic Kubernetes Service (EKS).

---

## Project Workflow

1. *Push Python code to GitHub*  
2. *Clone the repo and build a Docker image*  
3. *Create AWS ECR and push the image*  
4. *Deploy the container to AWS EKS*  

---

## Prerequisites

Before proceeding, ensure you have the following installed:

- *Git* → [Download Git](https://git-scm.com/downloads)
- *Docker* → [Download Docker](https://www.docker.com/products/docker-desktop)
- *Python 3.9+* → [Download Python](https://www.python.org/downloads/)
- *AWS CLI* → [Install AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)
- *kubectl* → [Install kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- *eksctl* → [Install eksctl](https://eksctl.io/introduction/installation/)

---

## *1. Clone the GitHub Repository*

```sh
git clone <GITHUB_REPO_URL>
cd my-python-app
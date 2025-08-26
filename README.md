# ci-cd_workflow-using-github_Action
CI/CD Pipeline with GitHub Actions & Docker
📌 Objective

Set up a complete CI/CD pipeline that:

Builds a Docker image of a sample Flask app

Runs basic tests

Pushes the image to DockerHub

Deploys the app locally on Minikube

This shows how DevOps engineers automate the build → test → release → deploy cycle using GitHub Actions.

⚙️ Tech Stack

Flask (Python) → Simple demo application

Docker → Containerization

GitHub Actions → CI/CD pipeline automation

DockerHub → Container registry

Minikube + kubectl → Local Kubernetes deployment

📂 Project Structure
.
├── app.py               # Simple Flask app
├── Dockerfile           # Docker build instructions
├── requirements.txt     # Python dependencies (Flask)
└── .github/
    └── workflows/
        └── ci-cd.yml    # GitHub Actions workflow
Deliverables

✅ GitHub repo with code + workflow

✅ DockerHub image → akki5175/ci-cd-demo:latest

✅ Minikube deployment screenshot

<img width="1249" height="853" alt="Screenshot from 2025-08-25 15-29-04" src="https://github.com/user-attachments/assets/1a28176f-244c-4239-ad3c-ba1d034286ca" />
<img width="1888" height="1003" alt="Screenshot from 2025-08-26 08-28-53" src="https://github.com/user-attachments/assets/ae712eb0-ec1d-448d-96b3-adf3720f2d5b" />



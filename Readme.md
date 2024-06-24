# 📋KubeTaskManager📋

TaskMaster Pro is a full-stack task management application built with Flask, React, and Kubernetes.
![Task_manager_UI](https://github.com/bharath-manjunath/Kube-Task-Manager/blob/master/Assets/Task_manager_UI.jpeg)

## Getting Started

### Prerequisites

Make sure you have the following tools installed on your machine:

- [Docker](https://www.docker.com/get-started)
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [Minikube](https://minikube.sigs.k8s.io/docs/start/)

## Local Development 👨‍💻

### 👨‍💻 Backend 👨‍💻 (Flask)

1. Navigate to the `backend` directory:
   ```bash
   cd backend

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
  

3. Run the Flask application:
   ```bash
    python app.py
   ``` 
### 👨‍💻 Fronted 👨‍💻 (React)

1. Navigate to the frontend directory:
   ```bash
   cd frontend
2. Install dependencies:
   ```bash
   npm install
3. Run the React application:
   ```bash
   npm start
   ```
The frontend should now be accessible at http://localhost:3000.

### 🚢 Deployment 🚢(k8's)

1. Start Minikube cluster:
   ```bash
   minikube start
2. Deploy the application:
   ```bash
   kubectl apply -f fontend.yaml 
   kubectl apply -f backend.yaml

3. Access the application:
   ```bash
   minikube service frontend-service
   kubectl port-forward backend-pod name 5000:5000
   ```
😀The application should be accessible in your web browser😀.


## Contribute to 📋KubeTaskManager📋

We welcome contributions from the community to enhance KubeTaskManager. If you'd like to contribute, please follow these guidelines:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Ensure your code follows the project's coding standards.
- Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---


 
   

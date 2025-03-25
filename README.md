# Weather App

## 🌍 About the Project

This is a simple weather web application. I created it as part of my **project training**, and I will make future modifications such as **using Terraform and Jenkins**. The app is containerized using **Docker** and deployed on **AWS EC2** with **NGINX**.

---

## 📌 Prerequisites

Before running the project, make sure you have the following installed:

- **Docker**
- **AWS EC2 Instance (Ubuntu)**

---

## 🚀 Setup & Deployment

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/EslamMOsman/weather-app.git
cd weather-app
```

### 2️⃣ Build the Docker Image

```bash
docker build -t weather-app .
```

### 3️⃣ Run the Container

```bash
docker run -d -p 80:80 weather-app
```

### 4️⃣ Access the App

- If running **locally**, open:
  ```
  http://localhost
  ```
- If deployed on **AWS EC2**, use the public IP:
  ```
  http://<your-ec2-public-ip>
  ```

---

## 🛠️ Troubleshooting

### Check Running Containers

```bash
docker ps
```

### View Logs

```bash
docker logs <container_id>
```

### Stop a Running Container

```bash
docker stop <container_id>
```

### Restart the Container

```bash
docker start <container_id>
```

---

## 📜 License

This project is open-source and available for use and modification.

---

## 📩 Contact Me

If you encounter any issues or have any suggestions, feel free to reach out to me!


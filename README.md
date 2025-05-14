
# 🚀 Docker Python App

This project demonstrates how to set up and run a Python application inside a Docker container.

---

## 📥 Clone the Repository

```bash
git clone "https://github.com/perumandlahemakumari/docker-python-app.git"
cd docker-python-app
```

---

## 🛠️ Docker Compose Installation

If Docker Compose is not installed, follow these steps:

```bash
DOCKER_CONFIG=${DOCKER_CONFIG:-$HOME/.docker}
mkdir -p $DOCKER_CONFIG/cli-plugins
curl -SL https://github.com/docker/compose/releases/download/v2.36.0/docker-compose-linux-x86_64 -o $DOCKER_CONFIG/cli-plugins/docker-compose
chmod +x $DOCKER_CONFIG/cli-plugins/docker-compose
sudo chmod +x /usr/local/lib/docker/cli-plugins/docker-compose
docker compose version
```

---

## 📦 Run the Application

Start the containers:

```bash
docker compose up -d
```

Check running containers:

```bash
docker ps
```

Visit your app in the browser:

🌐 **http://IP:8000**

---

## 📁 Project Structure

```
docker-python-app/
├── Dockerfile
├── docker-compose.yml
├── app/
│   └── main.py
└── requirements.txt
```

---

## 🧾 License

This project is licensed under the MIT License.

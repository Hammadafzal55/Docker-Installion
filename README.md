# 🐳 Docker Installation & Hello World Guide (Windows)

This repository documents the **complete process of installing Docker Desktop on Windows**, verifying the installation, and successfully running the **hello-world** container.  
It is intended for **beginners and students** getting started with Docker and DevOps tools.

---

## 📌 Prerequisites
Before installing Docker, make sure you have:

- Windows 10 / 11 (64-bit)
- Stable internet connection
- Virtualization enabled in BIOS
- Administrator access on your system

---

## 🚀 Step 1: Download Docker Desktop

Download Docker Desktop for Windows from the official Docker website:

🔗 https://docs.docker.com/desktop/setup/install/windows-install/

📺 Video Tutorial (Optional):  
https://youtu.be/R4uy6Oqiy5I

---

## 🛠 Step 2: Install Docker Desktop

1. Run the downloaded installer
2. Keep default options selected
3. Make sure **WSL 2** option is enabled
4. Complete the installation
5. **Restart your system** when prompted

---

## ▶️ Step 3: Start Docker Desktop

1. Open **Docker Desktop** from the Start Menu
2. Wait until Docker finishes starting
3. You should see the status:

Docker Desktop is running

yaml
Copy code

🐳 A whale icon will appear in the system tray, indicating Docker is active.

---

## 🧪 Step 4: Verify Docker Installation

Open **Command Prompt** or **PowerShell** and run:

```bash
docker --version
```

### ✅ Expected Output
```bash
Docker version 29.x.x, build xxxxx
```

If the version is displayed, Docker is installed correctly.

## 🌍 Step 5: Run the Hello World Container
Run the following command:
```bash
docker run hello-world
```
🔍 What Docker Does Internally

Checks if the hello-world image exists locally

Downloads the image from Docker Hub (if not found)

Creates a container from the image

Runs the container

Displays output in the terminal

### ✅ Successful Output
If Docker is working correctly, you will see:
```bash
Hello from Docker!
```
This message shows that your installation appears to be working correctly.
🎉 This confirms Docker is fully functional.

## 🔁 Step 6: Run Hello World Again (Optional)
Run the same command again:

```bash
docker run hello-world
```
This time, Docker will use the local image instead of downloading it again.

## 📦 Step 7: View Docker Images
To list all Docker images on your system:

```bash
docker images
```
You should see:

```text
hello-world
```
## 🧹 (Optional) Cleanup
To see all containers (including stopped ones):

```bash
docker ps -a
```
To remove a container:

```bash
docker rm <container_id>
```
## ✅ Final Checklist

 ✅ Docker Desktop installed

 ✅ Docker running successfully

 ✅ Docker version verified

 ✅ Hello World container executed

## 🎯 Conclusion
Docker has been successfully installed and verified on your system.
You are now ready to work with:

- Docker images

- Containers

- Real-world DevOps and cloud-native tools

### Happy Containerizing! 🐳🚀

## 🔗 Useful Resources
Docker Documentation: https://docs.docker.com/

Docker Hub: https://hub.docker.com/

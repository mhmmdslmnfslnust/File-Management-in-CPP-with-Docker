# File-Management-in-C++ (Dockerized)

This is a **C++-based command-line file system simulator**, now with a **Docker container** for easy execution — no setup or compilation required! It mimics a basic file system with commands like creating files and directories, reading/writing files, navigating, and saving/loading persistent structure.

---

## 🚀 Running with Docker (No Compilation Required)

### 🐳 For First-Time Docker Users

> 🧠 Docker allows you to run this project **without installing C++** or setting up dependencies. Think of it as "plug and play."

---

### ✅ Steps to Use (Two Options)

#### Option 1: You Have the Docker Image (`file-management-in-cpp-deployed-using-docker.tar`)

1. **Install Docker Desktop**  
   - [Download for Windows/Mac/Linux](https://www.docker.com/products/docker-desktop/)

2. **Load the image**:
   ```bash
   docker load -i file-management-in-cpp-deployed-using-docker.tar
   ```
3. **Run the container**:
   ```bash
   docker run -it file-management-in-cpp-deployed-using-docker
   ```

---
#### Option 2: You Only Have the Source Code
Install Docker Desktop
1. **Install Docker Desktop**  
   - [Download for Windows/Mac/Linux](https://www.docker.com/products/docker-desktop/)
2. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/File-Management-in-CPP-with-Docker.git
   cd File-Management-in-CPP-with-Docker
   ```
3. **Build the Docker image**:
   ```bash
   docker build -t file-management-in-cpp-deployed-using-docker .
   ```
4. **Run the container:**
   ```bash
   docker run -it file-management-in-cpp-deployed-using-docker
   ```
## 📦 What's Inside the Image?

This Docker image contains everything needed to run the modular file system without compiling:

### 🔹 Included Files:

| File Name        | Description |
|------------------|-------------|
| `main.cpp`       | Entry point for the file system program |
| `File.h`         | Class definitions for file objects |
| `Directory.h`    | Class definitions for directories |
| `FileSystem.h`   | Core file system logic – manages files & directories |
| `CommandUtils.h` | Helper functions for command parsing and suggestions |
| `sample.dat`     | Data file to initialize directory structure (load/save) |
| `Dockerfile`     | Instructions for building the Docker image |

---

## 📁 About the Original Project

For full documentation, modular class breakdown, CLI usage, and examples:  
👉 **[File-Management-in-C++](https://github.com/mhmmdslmnfslnust/File-Management-in-CPP)**

This container is simply a wrapper around that core logic for easier deployment and testing.

   

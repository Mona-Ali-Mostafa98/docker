# ITI - Docker Lab 🐋

## Task 1: Working with Docker Hello-world Image
### Objective
Learn how to run a container using the hello-world image and manage containers and images.

### Steps
#### 1. Run a Container with hello-world Image
```bash
docker pull hello-world
docker run hello-world
```
#### 2. Check Container Status and Explain
```bash
docker ps -a
- output : 
CONTAINER ID   IMAGE         COMMAND    CREATED              STATUS                          PORTS     NAMES
e08daeaae1ad   hello-world   "/hello"   About a minute ago   Exited (0) About a minute ago             charming_elbakyan
```
#### 3. Start the Stopped Container
```bash
docker start charming_elbakyan   or   docker start e08daeaae1ad
```
#### 4. Remove the Container
```bash
docker rm charming_elbakyan
```
#### 5. Remove the Image
```bash
docker rmi hello-world 
```
---

## Task 2: Running Container with Ubuntu Image
### Objective
Run an Ubuntu container in interactive mode, create a file inside it, and manage containers.

### Steps
#### 1. Run Ubuntu Container in Interactive Mode
```bash
```
#### 2. Create a File inside the Container
```bash
```
#### 3. Stop and Remove the Container
```bash
```
#### 4. Check File Status
```bash
```
#### 5. What happened to hello-docker file?
```bash
```
#### 6. Remove All Stopped Containers
```bash
```
#### 7. Bonus: Remove All Containers in One Command
```bash
```

---
## Task 3: Creating a Custom Nginx Docker Image
### Objective
Create a custom Docker image using Nginx and a local HTML file.

### Steps
#### 1. Create a Local HTML File
```bash
```
#### 2. Write Dockerfile and Copy the HTML file to the Docker Image
```bash
```
#### 3. Run Container with New Image
```bash
```

#### 4. Test the Container, open your browser and navigate to http://localhost:8088 to check if everything is okay
```bash
```


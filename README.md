## Building-and-pushing-a-Docker-image-to-Docker-Hub-with-GitHub-Actions

### :point_right: **In this project, I used the GitHub Actions workflow (CI/CD pipeline) to build and push a Docker image to Docker Hub.** :point_left:

### **Steps:**

- [x] I **create**d the Node.js **app files** and the **Dockerfile**. (app.js, package.json, package-lock.json, Dockerfile)
    
- [x] I **create**d this **remote repository** and **repository Secrets** for **DOCKERHUB_USERNAME** and **DOCKERHUB_PASSWORD**.

- [x] I **push**ed my **files** from my local machine to this remote repository.
      
- [x] I used **Actions -> "set up a workflow yourself"** to create my _build_and_push_docker_image.yml_ file.
      
- [x] I used the _"Build and push Docker images"_ from **Marketplace/Actions**.
      
- [x] After creating and **push**ing the **workflow file** to the **main branch** and waiting for the run, I could see my newly created **Docker image** on **Docker Hub**.

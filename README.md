# build-and-push-Docker-image-to-Docker-Hub-with-GitHub-Actions

In this project, I used the GitHub Actions workflow (CI/CD pipeline) to build and push a Docker image to Docker Hub.

Steps:

1. I created the Node.js app files and the Dockerfile. (app.js, package.json, package-lock.json, Dockerfile)
2. I created this remote repository and repository Secrets for DOCKERHUB_USERNAME and DOCKERHUB_PASSWORD.
3. I pushed my files from my local machine to this remote repository.
4. I used Actions -> "set up a workflow yourself" to create my build_and_push_docker_image.yaml file.
5. I used the "Build and push Docker images" from Marketplace/Actions.
6. After creating and pushing the workflow file to the main branch and waiting for the run, I could see my newly created Docker image on Docker Hub.

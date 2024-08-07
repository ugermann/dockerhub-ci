# dockerhub-ci
Building Docker images and pushing them to dockerhub via github CI

Requirements:
- You need a dockerhub account.

How to use:
- Fork this repo.
- Clone it to your local machine.
- Create your Docker context in ./docker.
- Create a repo on Dockerhub for your image.
- Create a Docker access token in your dockerhub account.
- Replace the docker tag in .github/workflows/dockerhub-ci.yml
- Push to your fork of this repo.
  

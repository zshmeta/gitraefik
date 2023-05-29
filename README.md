# Gitraefik

## Introduction
Gitraefik is a project that combines Gitea and Traefik using Docker Compose. The purpose of this project is to provide a simple and efficient way to host a private Git repository using Gitea, while also having a reverse proxy and load balancer using Traefik. This allows for easy access to the Git repository from anywhere, while also ensuring security and scalability.

## Getting Started
To get started, make sure you have Docker and Docker Compose installed on your system. Then, clone the Gitraefik repository and navigate to the directory in your terminal.

```
git clone https://github.com/username/Gitraefik.git
cd Gitraefik
```

Next, open the `docker-compose.yml` file and edit the environment variables for Gitea to your desired settings. You can also edit the Traefik configuration if needed.

```
nano docker-compose.yml
```

Once you have made your changes, run the command `docker-compose up -d` to start the containers in the background. You can then access Gitea by navigating to http://localhost:3000 in your web browser.

## External Access
If you want to access Gitea from a different device on your network, you will need to edit the Traefik configuration to allow external access. This can be done by adding a rule to the Traefik configuration file.

## Conclusion
Overall, Gitraefik provides a simple and efficient way to host a private Git repository with added security and scalability. Happy coding!

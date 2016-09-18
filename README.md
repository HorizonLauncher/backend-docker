# backend-docker
Docker tools to quickly deploy the Horizon backend

Dependencies:
====
- [Docker](https://docs.docker.com/engine/installation/linux/)
- [Docker compose](https://docs.docker.com/compose/install/)

How to deploy
====
1. Clone this repository recursively: `git clone --recursive https://github.com/HorizonLauncher/backend-docker.git`
2. Change directory into the repository: `cd backend-docker`
3. Build the docker images:  `docker-compose build`
4. Start the docker images: `docker-compose up` (add `-d` to run them in the background)

The `src` directory contains the backend source code and is a [Git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules) 
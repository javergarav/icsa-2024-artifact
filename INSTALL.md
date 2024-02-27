# INSTALL

## Requirements

[Docker](https://www.docker.com/) installed. If not, do the installation according to the following information:

* For a **Linux**-based operating system: [Docker Engine](https://docs.docker.com/engine/install/).
* For **MacOS** operating system: [Docker Desktop](https://www.docker.com/products/docker-desktop/).
* For **Windows** operating system: [Docker Desktop](https://www.docker.com/products/docker-desktop/).

## Execution

**1.** In the operation system **Terminal**: execute the following command:

> docker run --name neo4j-client -p 7474:7474 -p 7687:7687 -d neo4j

**2.** In a **web browser**: open the following URL:

> [http://localhost:7474/](http://localhost:7474/)

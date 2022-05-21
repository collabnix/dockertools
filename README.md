



![stars](https://img.shields.io/github/stars/collabnix/dockertools)
![forks](https://img.shields.io/github/forks/collabnix/dockertools)
![issues](https://img.shields.io/github/issues/collabnix/dockertools)
![Twitter](https://img.shields.io/twitter/follow/collabnix?style=social)

Developers love Docker. Docker is a suite of software development tools for creating, sharing and running containers. Developers use Docker to accelerate how they build, share, and run modern applications. This repository was built with a purpose. It is being used by Collabnix community internally to target the most popular developer tools and technique and coming up with the best practices around these tools. 


Follow [the Collabnix Twitter account](https://twitter.com/collabnix) to keep track of the latest developer tools.

Have Questions? Join us over [Slack](https://launchpass.com/collabnix) and get chance to be a part of 6400+ DevOps enthusiasts.<br>


# Types of Docker Developer Tools

- [Docker Integrated Developer Tools](https://github.com/collabnix/dockertools#docker-integrated-developer-tools)
- [Open Source Developer Tools](https://github.com/collabnix/dockertools#open-source-developer-tools)

## Docker Integrated Developer Tools

<img width="1072" alt="image" src="https://user-images.githubusercontent.com/34368930/169660363-17e48331-660b-4f87-acd6-eaea195f25fe.png">



docker build - [Easily create and share portable Docker container images using open standards](https://docs.docker.com/engine/reference/commandline/build/)<br>
docker buildx - [Extended build capabilities with Buildkit](https://docs.docker.com/engine/reference/commandline/buildx/)<br>
docker compose - [Build and Manage multiple services in Docker containers](https://docs.docker.com/engine/reference/commandline/compose/)<br>
docker scan - [Quickly detect and learn how to remediate CVEs in your Docker image](https://docs.docker.com/engine/scan/)<br>
docker context - [Manages multiple Swarm clusters, Kubernetes clusters and Docker nodes](https://docs.docker.com/engine/context/working-with-contexts/)<br>
docker sbom - [Generate the Software Bill of Materials (SBOM) of a container image](https://docs.docker.com/engine/sbom/)<br>
docker extensions - [Use 3rd party tools within Docker Desktop to extend its functionality](https://docs.docker.com/desktop/extensions/)<br>
docker trust - [Manage trust on Docker Images](https://docs.docker.com/engine/reference/commandline/trust/)<br>

## Open Source Developer Tools

## Image Slim

DockerSlim - [Minify and Secure Docker containers](https://github.com/docker-slim/docker-slim)  ![Docker Pulls](https://img.shields.io/docker/pulls/dslim/docker-slim) <br>
Minicon - [Minimization of the filesystem for containers](https://github.com/grycap/minicon)<br>
Watchtower - [A process for automating Docker container base image updates](https://github.com/containrrr/watchtower) ![Docker Pulls](https://img.shields.io/docker/pulls/containrrr/watchtower)  <br>
Syft - [CLI tool and library for generating a Software Bill of Materials from container images and filesystems](https://github.com/anchore/syft) ![Docker Pulls](https://img.shields.io/docker/pulls/anchore/syft) <br>


## Image Build Toolkit

BuildKit - [Toolkit for converting source code to build artifacts in an efficient, expressive and repeatable manner](https://github.com/moby/buildkit)<br>
Dive - [Tool for exploring each layer in a docker image](https://github.com/wagoodman/dive)<br>
Docker-Squash - [Squashing helps with organizing images in logical layers.](https://github.com/goldmann/docker-squash)<br>
Docker-Diun - [ Docker image update notifier](https://github.com/crazy-max/diun)
Trivy - [Trivy is a container image scanner which uncovers known vulnerabilities.](https://www.cloudsavvyit.com/12027/how-to-use-trivy-to-find-vulnerabilities-in-docker-containers)br<>
vbaksa/promoter - [Docker Image promotion tool](https://github.com/vbaksa/promoter)<br>
Argo Watcher - [A small tool that will wait for the specific docker image to be rolled out](https://github.com/shini4i/argo-watcher)<br>
Terrier - [Terrier is a Image and Container analysis tool that can be used to scan Images and Containers to identify and verify the presence of specific files according to their hashes](https://github.com/heroku/terrier)<br>
PHPQA - [Docker image that provides static analysis tools for PHP](https://github.com/jakzal/phpqa)<br>
Docker Registry Pruner - [Tool to apply retention logic to docker images in a Docker Registry](https://github.com/tumblr/docker-registry-pruner)<br>







## Image Security

TerraScan -[Detect compliance and security violations across Infrastructure as Code to mitigate risk before provisioning cloud native infrastructure. ](https://github.com/accurics/terrascan)<br>
Clair - [Vulnerability Static Analysis for Containers](https://github.com/quay/clair)<br>
Trivy - [Vulnerability Scanner for Containers and other Artifacts, Suitable for CI - Aqua Security](https://github.com/aquasecurity/trivy)<br>
DeepSource - [Static Analysis for DockerFiles](https://deepsource.io/)<br>
DockerScan - [A Docker analysis & hacking tools](https://github.com/cr0hn/dockerscan)<br>
Container-diff - [container-diff is a tool for analyzing and comparing container images. container-diff can examine images along several different criteria.](https://github.com/GoogleContainerTools/container-diff)<br>

## Docker CLI

Docker Buildx - [a CLI plugin that extends the docker command with the full support of the features provided by Moby BuildKit builder toolkit.](https://docs.docker.com/buildx/working-with-buildx/)<br>

## DockerHub

DockerHub Scraper - [Scraping DockerHub](https://github.com/itamarhaber/dockerhub-scraper)<br>

## Docker Volume

Flocker - [Data Volume Manager for your Dockerized applications.](https://github.com/ClusterHQ/flocker)<br>
offen/docker-volume-backup - [Backup Docker volumes locally or to any S3 or WebDAV compatible storage](https://github.com/offen/docker-volume-backup)<br>

## Cloud-Job

 Launcha - [Launcha is a docker-based cloud job launcher.](https://github.com/vwxyzjn/launcha)<br>
 
## Runtime Security

Tracee - [Linux Runtime Security and Forensics using eBPF](https://github.com/aquasecurity/tracee)<br>

## Container Orchestration

Miniboss - [Manages container locally](https://github.com/afroisalreadyinu/miniboss)<br>
Portainer - [Making Docker management easy. https://www.portainer.io](https://github.com/portainer/portainer)<br>
Drone - [continuous delivery system built on container technology](https://github.com/harness/drone)<br>
Kubernetes - [most popular container orchestration engine](https://kubernetes.io)<br>
Amazon ECS - [highly scalable management service which allows developers to run containerized applications on EC2 instances.](https://aws.amazon.com/ecs/)<br>
Ryuk - [Remove containers/networks/volumes/images by given filter after specified delay.](https://hub.docker.com/r/testcontainers/ryuk)<br>
Traefik - [Traefik is an HTTP reverse proxy that’s easy to integrate with container workloads.](https://github.com/traefik/traefik)<br>
Docker Context - [Makes it easy to switch between multiple Docker and Kubernetes environments.](https://docs.docker.com/engine/context/working-with-contexts/)<br>



## Cluster Management

Nebula - [designed to manage massive clusters at scale.](http://nebula.readthedocs.io/en/latest/)<br>

## Machine Learning

Paddle Serving - [A flexible, high-performance carrier for machine learning models](https://github.com/PaddlePaddle/Serving)<br>

## Android app
Android-Docker - [A Docker image for building and testing Android apps.](https://github.com/randr0id/android-docker)<br>

## Development

Konveyor Move2Kube - [Automatically create Dockerfiles, Kubernetes Yamls, Helm charts and other Infrastructure as Code Artifacts for your application.](https://move2kube.konveyor.io/)<br>
Docksal - [tool for defining and managing web development environments.](https://github.com/docksal/docksal)<br>
Chartbrew - [Chartbrew is an open-source web application that can connect directly to databases and APIs and use the data to create beautiful charts.](https://github.com/chartbrew/chartbrew)<br>
Conan Docker - [accelerating the development and Continuous Integration of C and C++ projects.](https://github.com/conan-io/conan-docker-tools)<br>


## Workflow
Open Policy Registry - [A Docker-inspired workflow for OPA policies](https://www.openpolicyregistry.io/)<br>

## Networking

Libnetwork - [Docker libnetwork plugin for Calico http://www.projectcalico.org](https://github.com/projectcalico/libnetwork-plugin)<br>
Libnetwork - [networking for containers](https://github.com/moby/libnetwork)<br>
Caddy Gen - [Automated Caddy reverse proxy for docker containers](https://github.com/wemake-services/caddy-gen)<br>

## Swarm

Orbiter - [Autoscaler for Docker Swarm](https://github.com/gianarb/orbiter)

## Maintainer

- [Apurva Bhandari](https://www.linkedin.com/in/apurvabhandari-linux/)
- [Ajeet S Raina](https://www.linkedin.com/in/ajeetsraina)

## Contributor
- [Mansi Mishra](https://github.com/0904-mansi)


Last Updated: 19 April 2022


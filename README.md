# PiTasks

## Description

**PiTasks** is a Raspberry Pi-based home lab for learning and experimenting with modern infrastructure, containerization, and DevOps. It serves as the deployment platform for personal projects while providing hands-on experience with Docker, Kubernetes, networking, and automation.

The long-term goal is to build a highly available Raspberry Pi cluster capable of hosting multiple self-developed applications and services.

[![Java](https://img.shields.io/badge/Language-Java%2021+-orange.svg)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Framework-Spring%20Boot%203.x-green.svg)](https://spring.io/projects/spring-boot)
[![Raspberry Pi](https://img.shields.io/badge/Hardware-Raspberry%20Pi-C51A4A.svg)](https://www.raspberrypi.com/)
[![Docker](https://img.shields.io/badge/Container-Docker-2496ED.svg)](https://www.docker.com/)

## Key Features

* **Self-Hosted Infrastructure:** Run personal applications on a Raspberry Pi cluster.
* **Containerized Workloads:** Deploy applications using Docker containers.
* **Kubernetes Learning Platform:** Experiment with orchestration, scaling, and service management.
* **Infrastructure Automation:** Use Python and Bash scripts to simplify deployment and maintenance.
* **Expandable Architecture:** Continuously extend the infrastructure with new services, monitoring, and networking components.

## Tech Stack

* **Hardware:** Raspberry Pi
* **Containerization:** Docker
* **Orchestration:** Kubernetes
* **Automation:** Python, Bash
* **Monitoring (planned):** Prometheus, Grafana

---

## Table of Contents

* [Project Structure](#project-structure)
* [Roadmap](#roadmap)
* [Hosted Projects](#hosted-projects)
* [Credits](#credits)

## Project Structure

```text
docker/             # Dockerfiles and compose files
kubernetes/         # Kubernetes manifests
scripts/            # Automation scripts
docs/               # Documentation
```

## Roadmap

### Phase 1

* Initial Raspberry Pi setup
* Docker installation
* Deploy first containerized application

### Phase 2

* Build Kubernetes cluster
* Configure networking and ingress
* Persistent storage
* Internal DNS

### Phase 3

* Automated deployments
* Monitoring and logging
* CI/CD
* High availability
* Backup strategy

## Hosted Projects

### TaskForge

A full-stack ToDo Manager built with:

* Spring Boot
* Flutter
* PostgreSQL
* Docker
* Kubernetes

Additional applications and services will be deployed as the infrastructure evolves.

## Credits

**Developer:**

* [Reiterer Julian](https://github.com/ReitererJulian)

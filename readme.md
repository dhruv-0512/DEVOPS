# DevOps Lab

This repository contains my implementations and documentation for the **DevOps Lab exercises** completed as part of my coursework.

The exercises cover Kubernetes and Minikube, Docker networking and security, monitoring with Grafana, and CI/CD with Jenkins. Each exercise is documented separately with the commands, configurations, implementation details, verification steps, and screenshots of successful execution.

## Repository Purpose

The purpose of this repository is to maintain a record of the practical work completed throughout the DevOps Lab.

For each exercise, I document:

- The objective of the exercise
- Tools and technologies used
- Commands or configurations implemented
- Important implementation steps
- Verification of the expected result
- Screenshots and evidence of execution
- Final outcome

The repository serves as both a **record of completed coursework** and a reference for the concepts and tools used during the lab.

## Project Structure

All exercises are maintained directly in the root directory of the repository. Each exercise has its own folder containing its README, implementation files, configurations, and screenshots where applicable.

```text
DEVOPS/
├── Exercise-1/
├── Exercise-2/
├── Exercise-3/
├── Exercise-4/
├── Exercise-5/
├── Exercise-6/
├── Exercise-7/
├── Exercise-8/
├── Exercise-9/
├── Exercise-10/
├── .gitignore
└── readme.md
```

Each exercise has its own README and supporting files. Screenshots are stored in the corresponding screenshot directory and named sequentially (`first.png`, `second.png`, `third.png`, and so on) in the order they appear in that exercise's README. Existing capitalization exceptions are preserved: Exercises 4, 5, and 6 use `Screenshots/`, while Exercise 1 keeps its two legacy images at the exercise root.

## Exercises and Progress

| # | Exercise | Focus Area | Status |
|---|---|---|---|
| 1 | [Kubernetes Getting Started](./Exercise-1/) | Kubernetes fundamentals | Completed |
| 2 | [Minikube, kubectl and Flask](./Exercise-2/) | Deploying a Flask application using Minikube and kubectl | Completed |
| 3 | [Scaling a Flask App with ReplicaSets](./Exercise-3/) | ReplicaSets and application scaling | Completed |
| 4 | [Docker Networking](./Exercise-4/) | Docker networking and container communication | Completed |
| 5 | [Docker Security with AppArmor](./Exercise-5/) | Flask, custom AppArmor profiles and Docker security | Completed |
| 6 | [Grafana Real-time Monitoring](./Exercise-6/) | Application monitoring and Grafana dashboards | Completed |
| 7 | [Jenkins CI Automation](./Exercise-7/) | Jenkins running in Docker and CI automation | Completed |
| 8 | [Jenkins Hello World Job](./Exercise-8/) | GitHub integration and Freestyle jobs | Completed |
| 9 | [Jenkins Multi-Stage Pipeline](./Exercise-9/) | Automated multi-stage CI/CD pipeline | Completed |
| 10 | [Multi-Node, Multi-App Minikube Deployment](./Exercise-10/) | Multi-node Kubernetes cluster and multiple applications | Completed |

**Summary:** 10 of 10 exercises completed.

## How to Use This Repository

1. Open the relevant `Exercise-*` folder.
2. Read its `README.md` for the objective and implementation details.
3. Review the commands, configurations, and source files.
4. Follow the screenshots in the order they are referenced in the README. The filenames (`first.png`, `second.png`, `third.png`, and so on) correspond to their order of appearance.
5. Check the verification steps and execution results.

## Documentation Approach

The documentation focuses on my completed implementations rather than reproducing the original lab instructions. Each exercise includes relevant implementation details, verification steps, and screenshots to demonstrate the results.

Screenshots are stored in the corresponding exercise's screenshot directory and named sequentially according to their order in the README. See the capitalization and Exercise 1 exceptions described above.

## Technologies

- **Containerization and Security:** Docker, Docker Networking, AppArmor
- **Programming:** Python, Flask, Docker SDK for Python
- **Orchestration:** Kubernetes, Minikube, kubectl
- **Monitoring:** Grafana, Prometheus
- **CI/CD:** Jenkins, Freestyle jobs, multi-stage pipelines
- **Version Control:** Git and GitHub

The specific technologies and implementation details for each exercise are documented in its respective folder.

## Note

This repository is maintained as part of my **DevOps Lab coursework**. Each `Exercise-*` directory contains an individual practical exercise, while this README provides an overview of the repository, progress tracking, and navigation to the completed work.
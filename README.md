# Flask App with CI/CD

## Overview

This repository contains a simple Flask web application and a GitHub Actions CI pipeline.

### Features

- Dockerized Flask app
- CI pipeline includes:
  - Build Docker image
  - Run app in a container
  - Run tests
  - Push to Docker Hub
  - Notify via Slack/Email
  - Update CD repo to trigger ArgoCD deployment

## Tech Stack

- Flask
- GitHub Actions
- Docker
- Docker Hub
- ArgoCD (via separate repo)


---
title: "Research Infrastructure & APIs"
description: "REST APIs, web interfaces, and deployment infrastructure built to expose research models to end users at CERIST."
tags:
  - "Full Stack"
  - "FastAPI"
  - "React"
  - "Docker"
  - "Infrastructure"
image: "/images/placeholder.svg"
---

## Overview

Built the bridge between research models and end users at CERIST: APIs to serve trained NLP models, interfaces to visualize and interact with results, and the deployment infrastructure to run all of it reliably.

## Engineering Stack

- **Backend**: FastAPI, Django REST Framework, exposing model inference as REST endpoints.
- **Frontend**: React, TypeScript, for interactive result visualization and internal tooling.
- **Infrastructure**: Docker for containerized, reproducible deployment; PostgreSQL and MongoDB for structured and semi-structured data management.
- **DevOps**: Administration of Linux servers and GPU workstations, including environment setup for training and inference workloads.

## Why this matters

A recurring gap between NLP research and usable systems is deployment: a model that only runs in a notebook has no value to end users. This project's goal was to make every research model in the group usable as a real, queryable service, not just a checkpoint file.

## My Role

Owned the infrastructure end to end: API design, containerization, deployment, and the Linux/GPU environment the models actually train and run on.

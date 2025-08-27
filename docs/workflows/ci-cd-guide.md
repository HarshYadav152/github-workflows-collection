# CI/CD Workflow Guide

This guide provides a quick overview of how to use CI/CD workflows in this repo.

## Workflows Included

- `node-ci.yml`: Basic Node.js CI
- `python-ci.yml`: Basic Python CI
- `docker-build.yml`: Build a Docker image
- `deploy-prod.yml`: Deploy to production (dummy example)

## Usage

You can trigger any workflow manually via the **Actions** tab or by referencing them in your own project via `workflow_call` if marked as reusable.

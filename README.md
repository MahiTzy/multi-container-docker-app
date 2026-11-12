# Multi-Container Docker Application

A starter project for learning how to run a multi-container application with Docker Compose.

## Overview
This repository demonstrates a containerized application environment. Compose configuration defines the services, networks, ports, and volumes used by the stack.

## Prerequisites
- Docker Engine
- Docker Compose plugin

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/MahiTzy/multi-container-docker-app.git
   cd multi-container-docker-app
   ```
2. Start the services:
   ```bash
   docker compose up -d
   ```
3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Useful Commands
- View running containers: `docker compose ps`
- Follow service logs: `docker compose logs -f`
- Stop the stack: `docker compose down`
- Rebuild images: `docker compose up -d --build`

## Configuration
Review the Compose file before changing service names, ports, environment variables, or volumes. Do not commit secrets.

## Learning Goals
Understand service orchestration, container networking, port mapping, and the lifecycle of a Compose application.

## License
No license terms are specified here. Refer to the repository's LICENSE file, if present, before reuse.
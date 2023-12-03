# # Pac-Man Deployment on Akash Network

## Overview
This repository contains the code for deploying Pac-Man on the Akash network.

## Features
Pac-Man is a classic arcade game known for its simple yet engaging gameplay. Some of the key features of Pac-Man include:

Gameplay Mechanics: Players control Pac-Man, a character navigating through a maze filled with dots while avoiding ghosts. The goal is to eat all the dots and fruits while avoiding or strategically outmaneuvering the ghosts.

Power-Ups: Pac-Man can consume power pellets, temporarily allowing him to turn the tables on the ghosts. After eating a power pellet, the ghosts turn blue, becoming vulnerable, and Pac-Man can eat them for extra points.

Ghosts AI: Each ghost has its unique behavior pattern, creating diverse challenges for players. Some ghosts may chase Pac-Man directly, while others might try to ambush or cut off his path.

Mazes and Levels: As players progress, the mazes become more intricate, with different layouts and additional challenges. Advancing through levels increases difficulty and introduces new elements.

Fruits and Bonus Items: Periodically, bonus fruits appear in the maze, providing extra points when eaten. These fruits often appear at specific intervals or after reaching certain score thresholds.

potential modifications or enhancements for this deployment:

Containerization: Adapting Pac-Man to run within a Docker container, ensuring portability and easy deployment on Akash or any Docker-compatible platform.

Decentralized Deployment: Optimizing the game to leverage Akash's decentralized cloud infrastructure, utilizing multiple nodes for hosting game instances, which could enhance availability and fault tolerance.

Load Balancing: Implementing load balancing strategies to distribute game instances across Akash nodes, ensuring even resource utilization and efficient gameplay experience for users.

Scalability: Designing the game architecture to scale seamlessly with varying user demand, allowing for dynamic resource allocation on Akash's decentralized network during peak usage periods.

Network Latency Management: Implementing techniques to mitigate network latency issues inherent in decentralized deployments, ensuring smooth gameplay experiences across distributed nodes.

Persistent Storage Handling: Managing game state and data persistence across distributed nodes, ensuring continuity and consistency for players even with dynamic deployment and node changes.

## Deployment Steps
### Prerequisites
 deploying Pac-Man on the Akash networ
- An Akash account
- Docker installed
- Akash CLI configured

### Deployment Process

1. Clone this repository: `git clone https://github.com/your-username/pac-man-akash.git`
2. Change directory: `cd pac-man-akash`
3. Build the Docker image: `docker build -t pac-man .`
4. Push the image to Docker Hub or an Akash-compatible registry.
5. Create the deployment manifest for Akash.
6. Deploy on Akash using the manifest: `akash deploy manifest.yml`

### Active Deployments
My active deployments of Pac-Man on the Akash network:
(http://o719jsrq4pdn90mu4g1ir2da9g.ingress.provider-02.sandbox-01.aksh.pw/)




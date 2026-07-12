# Personal DevOps Project - Monitoring System
 
## What it does
Flask app deployed on AWS EC2, containerized with Docker, 
auto-built via GitHub Actions CI/CD, monitored real-time 
using Prometheus + Grafana with Node Exporter metrics.
 
## Tech Stack
AWS EC2, Docker, Docker Compose, GitHub Actions, 
Prometheus, Grafana, Node Exporter, Python/Flask, Linux
 
## Challenges Faced & Fixed
- Fixed CI/CD pipeline path issue (requirements.txt location)
- Debugged Prometheus target DNS resolution failure caused 
  by service naming mismatch in docker-compose.yml
- Configured security groups for multi-port access (Flask, 
  Prometheus, Grafana, Node Exporter)
 
## Screenshots
<img width="800" height="330" alt="image" src="https://github.com/user-attachments/assets/7b6bfd00-d995-485a-a724-7855ee05422e" />

<img width="3149" height="781" alt="image" src="https://github.com/user-attachments/assets/b42ebb14-d6ab-4d4f-977f-350a0b3b2863" />

<img width="1722" height="751" alt="image" src="https://github.com/user-attachments/assets/a03576ab-21db-452e-b717-31328ff6526a" />



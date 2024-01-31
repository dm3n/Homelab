---

# My HomeLab Setup

## Overview
This repository documents my personal homelab setup, consisting of a 2-computer cluster with a focus on various technologies for home and personal cloud computing.

## System Specifications
Each node in the cluster has the following specifications:
- **OS**: Proxmox VE 8.1.3 x86_64
- **Host**: MS-7522 3.0
- **CPU**: Intel i7 950 (8) @ 3.068GHz
- **GPU**: AMD ATI Radeon HD 5000/6000/7350 & AMD ATI Radeon HD 6950
- **Memory**: 24GB RAM per node (48GB total)
- **Storage**: 8.2 TB total storage across the cluster

## Technologies Hosted

### CasaOS
- **Description**: A simple, home cloud OS for personal servers.
- **Purpose**: CasaOS provides an easy interface to manage my homelab services.

### Docker
- **Description**: An open platform for developing, shipping, and running applications.
- **Purpose**: Docker is used to containerize and manage applications, ensuring isolation and scalability. Everything is inside my CasaOS LXC container, and then each service containerized with docker individually.

### Tailscale
- **Description**: A secure network tunneling solution.
- **Purpose**: Tailscale is used to create secure tunnels to my server over the internet, providing remote access from anywhere in the world while maintaining security.

### Kasm Workspaces
- **Description**: Delivers containerized virtual desktops and applications.
- **Purpose**: I use Kasm for cloud-based virtual machines, allowing remote work and computing.

### Nextcloud
- **Description**: A suite of client-server software for creating and using file hosting services.
- **Purpose**: Nextcloud is my solution for file hosting and sharing, personal cloud storage.

### Vaultwarden
- **Description**: An open-source password management solution.
- **Purpose**: Vaultwarden is used for securely storing and managing passwords and sensitive information.

### ChatbotUI
- **Description**: A custom interface for interacting with Local Large Language Models (LLMs).
- **Purpose**: ChatbotUI is developed to upload local LLMs and interact with them via APIs. It's used for processing various data types like PDFs, Word documents, etc.

## Network Diagram
https://github.com/dm3n/Homelab/files/14107451/Visual.Paradigm.Online.pdf


---

## Future Plans

### Building a Self-Hosted Custom Large Language Model (LLM)

#### Objective
My next ambitious project is to develop and host my own custom version of a Large Language Model (LLM) similar to ChatGPT, tailored specifically to my personal data and interests.

#### Key Features
1. **Data Integration**: Implement a Dropbox-like feature for easy and seamless upload of my datasets. This will allow me to continuously feed new data into the model, enhancing its learning and accuracy over time.

2. **Automatic Data Processing**: Once data is uploaded, it will be automatically processed and integrated into the LLM. This automation will ensure the model is consistently fine-tuned with the latest information without manual intervention.

3. **Real-Time Updates**: The LLM will be designed to update its knowledge base in real-time as new data is ingested. This ensures that the model remains current and increasingly reflective of my specific use cases and interests.

4. **Self-Hosted on Homelab**: The entire LLM will be hosted and run on my homelab servers. This approach not only ensures full control over the model and its data but also serves as a testbed for scaling and managing advanced AI applications in a home environment.

5. **Custom Interaction Interface**: Develop a user-friendly interface to interact with the LLM. This interface will be tailored to my preferences, offering an intuitive and personalized experience.

#### Challenges and Learning
- **Technical Challenges**: Tackling the complexities of training and maintaining a large-scale AI model in a home server environment.
- **Continuous Learning**: Keeping abreast with the latest advancements in AI and machine learning to incorporate state-of-the-art features in my custom LLM.

#### Long-Term Vision
This project is not just about building a tool but also about deepening my understanding of AI and machine learning. It's a journey towards creating a personalized AI assistant that grows and evolves with my personal and professional needs.

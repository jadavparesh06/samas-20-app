# SAMAS 2.0 - Video Management System

## Overview

SAMAS 2.0 is an advanced **Video Management System (VMS)** designed for enterprise-grade installations. It enables efficient video stream management, intelligent video analytics (IVA), and real-time playback from a scalable architecture. Optimized for high camera density, it is suitable for both cloud and on-premise environments. SAMAS 2.0 supports flexible deployment and high performance while providing features like multi-tenancy and intelligent analytics.

## Key Features

- **Multi-Tenant Support**: Enable deployment across multiple sites, with centralized control.
- **High Scalability**: Capable of managing up to 1000 cameras in a single system.
- **Intelligent Video Analytics (IVA)**: Provides real-time insights for smarter security management.
- **Flexible Deployment**: Supports both containerized solutions for cloud and hybrid environments or direct host-based deployment.
- **Advanced Recording and Playback**: Live streaming and playback from recorded streams using HLS and WebRTC protocols.

## Technologies

- **Backend**: .NET Core Web API, microservices architecture
- **Frontend**: Angular SPA
- **Storage**: PostgreSQL, SQL Server
- **Streaming Protocols**: HLS, WebRTC
- **Media Processing**: GStreamer pipelines
- **Cloud/On-Premise**: Kubernetes, Docker
- **Video Analytics**: Intelligent Video Analytics (IVA)

## Architecture Overview

SAMAS 2.0 follows a **microservices architecture** that separates core functionalities like recording, playback, metadata management, and device control. Services communicate via HTTP, WebRTC, and RTSP protocols. The system is designed for scalability and reliability, using Kubernetes for container orchestration and deployment.

## Installation

### Prerequisites

1. **Docker**: Ensure Docker is installed for containerized deployment.
2. **Kubernetes**: Required for orchestrating and deploying the microservices.
3. **Database**: PostgreSQL or SQL Server as the backend database for metadata and recording information.
4. **Media Libraries**: GStreamer for media streaming and processing.

### Setting Up the Repository

1. Clone the repository:
    ```bash
    git clone [https://github.com/yourusername/samas-20.git](https://github.com/jadavparesh06/samas-20)
  ```

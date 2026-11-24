# Cloud_Project


PROJECT OVERVIEW

This repository contains the complete implementation of a Distributed Visitor Counter Web Application developed for the 3rd-Year B.Tech Computer Science and Engineering Cloud Computing curriculum.

The application demonstrates real-world enterprise cloud architecture principles across 5 progressive phases:

Containerization & Local Orchestration: Modular Python Flask application integrated with an atomic in-memory Redis key-value store, containerized using an optimized multi-layer Dockerfile and orchestrated locally with Docker Compose.
Kubernetes Deployment & Self-Healing: Highly available deployment with exactly 2 initial replicas, health probes, resource requests/limits, and automated ReplicaSet self-healing upon pod termination.
Horizontal Pod Autoscaling (HPA): Dynamic scaling between 2 and 6 replicas based on empirical CPU metrics collected by the Kubernetes Metrics Server, validated under multi-threaded concurrency loads.
Hybrid Multi-Cloud Architecture: Dual-cluster simulation separating On-Premises Private Cloud from Public Cloud (AWS/GCP), backed by an intelligent reverse proxy that executes automatic traffic failover upon private cluster failure.
Cost Optimization: Measurable multi-dimensional cost reductions achieving an 83.4% infrastructure savings across image compression, resource right-sizing, and elastic scaling.
System Architecture

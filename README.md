# Kubernetes-Enabled-Cloud-Disaster-Recovery-K8s-ECDR-
K8s-ECDR is a disaster recovery solution for cloud-native applications that leverages the power of Kubernetes and other cloud-based tools for failover and redundancy management.

## Features
* Provides automatic failover for cloud-native applications
* Utilizes Kubernetes for container orchestration and management
* Incorporates cloud-based tools for redundancy and disaster recovery
* Easy to set up and configure
## Requirements
* A Kubernetes cluster
* A cloud provider account (AWS, Azure, or Google Cloud)
## Installation
* Clone the repository
* Run `kubectl apply -f k8s-ecdr.yaml`
* Configure the cloud provider credentials in the `k8s-ecdr-config.yaml` file

## Usage
* Deploy your cloud-native application on the Kubernetes cluster
* Apply the K8s-ECDR configuration using kubectl apply -f k8s-ecdr-config.yaml
* Test the disaster recovery functionality by simulating a failure
## Contributions
Feel free to contribute to this project by opening a pull request or an issue.

## License
This project is licensed under the MIT License.

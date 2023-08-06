# Moringa Ansible Project

This repository contains Ansible playbooks and configuration files for deploying an e-commerce platform and provisioning infrastructure using Terraform.

## Playbooks

### main.yaml

Initializes the environment for deploying the e-commerce platform.

### playbook.yaml

Deploys the "YOLO Project" application and sets up MongoDB, Node.js, and npm.

### stage2_playbook.yaml

Deploys the second stage of the project, provisioning infrastructure using Terraform.

## Variables

The `project_vars.yml` file contains variables used in the playbooks:

- `mongodb_service_name`: Name of the MongoDB service.
- `github_repo_url`: Git repository URL for the "YOLO Project" application.
- `client_app_directory`: Path to the client application directory.
- `backend_app_directory`: Path to the backend application directory.
- `client_port`: Port number for the client application.
- `backend_port`: Port number for the backend application.
- `product_api_url`: URL for adding products to the API.
- `sample_product`: Details of a sample product to be added.

## Usage

1. Clone this repository.
2. Update the `project_vars.yml` file with your specific values.
3. Install Ansible and Terraform on your local machine.
4. Run the playbooks using the `ansible-playbook` command, e.g., `ansible-playbook main.yaml`.

Please customize the playbooks and variables to match your environment and project specifications.

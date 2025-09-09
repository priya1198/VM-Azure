📘 Azure Virtual Machine Deployment Documentation
📌 Overview

This document outlines the steps and configuration details for deploying a Virtual Machine (VM) in the Azure portal. The deployment includes the creation of a Resource Group, configuration of authentication, network settings (inbound ports), and tagging for resource management.
🚀 Steps to Create the VM in Azure Portal
1. Login to Azure Portal

Navigate to https://portal.azure.com
 and log in with your credentials.

📸 Screenshot:

2. Create a Resource Group

Resource Group Name: <your-resource-group-name>

Region: <region-name> (e.g., East US)

The Resource Group is a logical container that holds the related resources for the VM.

📸 Screenshot:

3. Create a Virtual Machine

VM Name: <your-vm-name>

Region: Same as the Resource Group

Image: Ubuntu Server / Windows Server (your choice)

Size: Standard B1s (or as needed)

Authentication Type: Password

Username: <your-username>

Password: <your-password>

Inbound Ports:

Port 22 (SSH) – for remote terminal access (Linux)

Port 80 (HTTP) – for web server access

Tags:

Environment = Development

Owner = <your-name>

(You can customize tags as needed)

📸 Screenshots:

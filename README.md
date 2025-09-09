📘 Azure Virtual Machine Deployment Documentation
📌 Overview

This document outlines the steps and configuration details for deploying a Virtual Machine (VM) in the Azure portal. The deployment includes the creation of a Resource Group, configuration of authentication, network settings (inbound ports), and tagging for resource management.

🚀 Steps to Create the VM in Azure Portal
1. Login to Azure Portal

Navigate to https://portal.azure.com
 and log in with your credentials.

📸 Screenshot:

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/3edf097a-232e-4ecd-ae3c-fabe7b7a5e2e" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/8af9102c-a7aa-451c-9407-af3102f0ce35" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/0a9faa38-c300-4d0e-82f7-b52eacfc4898" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/2ef98317-2a44-4310-8e26-1cc368f2b0c7" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/72979f7f-12aa-41de-95ee-80c1e5e2bfe1" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/6aab9af0-a08b-4410-92ba-a3ec563528d6" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/56e65ba7-847b-49d3-903a-6fa860a1ded0" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/45b54211-ab9f-4045-b31a-6a1b255bf334" />

2. Create a Resource Group

Resource Group Name: <your-resource-group-name>

Region: <region-name> (e.g., East US)

The Resource Group is a logical container that holds the related resources for the VM.

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

Owner = your name

(You can customize tags as needed)

📸 Screenshots:

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/71a2283c-8553-4f17-89d9-6e966f63a794" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/6ef9a816-da7f-4d09-a84a-a43e6542b661" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/79953a2d-271c-47d1-a0b7-daac4fe1c6ee" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4f8d4b20-7fd8-4661-8f96-8b87d1faf590" />

# AWS EC2 Windows Server Deployment Project

## Project Overview

This project demonstrates the deployment and configuration of a Windows Server virtual machine using Amazon Web Services (AWS) EC2.

The project includes launching a Windows EC2 instance, configuring security settings, obtaining the administrator password, and connecting remotely using Remote Desktop Protocol (RDP).

## Technologies Used

* Amazon Web Services (AWS)
* Amazon EC2
* Windows Server
* Remote Desktop Protocol (RDP)
* Security Groups

---

## Project Objectives

* Create a Windows EC2 instance
* Configure inbound security rules
* Retrieve Windows administrator credentials
* Connect using Remote Desktop
* Verify successful deployment

---

## Step 1: Create EC2 Windows Instance

Created a new Windows Server EC2 instance from the AWS Management Console.

![Windows Instance Creation](screenshots/01-instance-created.png)

---

## Step 2: Configure Security Group

Configured inbound rules to allow RDP access on port 3389.

![Security Group Configuration](screenshots/02-security-group.png)

---

## Step 3: Retrieve Administrator Password

Obtained the Windows Administrator password using the EC2 key pair.

![Administrator Password](screenshots/03-password-retrieval.png)

---

## Step 4: Connect Using Remote Desktop

Connected to the Windows EC2 instance using Microsoft Remote Desktop.

![Remote Desktop Connection](screenshots/04-rdp-connection.png)

---

## Step 5: Verify Windows Server Access

Successfully logged into the Windows Server desktop environment.

![Windows Desktop](screenshots/05-windows-server.png)

---

## Skills Demonstrated

* AWS EC2 Administration
* Windows Server Management
* Cloud Computing Fundamentals
* Remote Desktop Configuration
* Security Group Management
* Basic Cloud Security Practices

---

## Security Considerations

* Restricted RDP access through Security Groups
* Used key-pair encryption for password retrieval
* Followed least-privilege access principles
* Protected administrator credentials

---

## Learning Outcomes

Through this project, I learned:

* How to deploy a Windows EC2 instance
* How to configure AWS Security Groups
* How to connect securely using RDP
* Basic Windows Server administration
* Cloud infrastructure fundamentals

---

## Author

**Obinna (HappyTech1)**

Aspiring Cybersecurity Professional | AWS Learner | Cloud Security Enthusiast

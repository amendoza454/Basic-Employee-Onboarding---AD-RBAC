# Basic Employee Onboarding (AD)(RBAC)

## Project Overview
* This project simulates an IT admin environment for Northstar Medical Group (NMG), a fictional healthcare organization. The objective was to establish a structure Active Directory environment, implement a department based user management with Organizational Units (OUs) and corresponding Security Groups, and finally troubleshoot an employee access issue using Role-Based Access Control (RBAC) principles. The motive behind this project is to create a practical scenario where I would be tackling a common issue faced by IT Support and Identity and Access Management (IAM) professionals in a real-world workplace. 

* The lab was completed using Windows Server 2019, Active Directory Domain Services (AD DS), and Oracle VirtualBox.

## Problem Statement
* Northstar Medical Group experienced management challenges resulting from poorly structured Active Directory administration by its previous Managed Service Provider (MSP). The environment lacked consistent organizational structures, standardized security group assignments, and efficient employee onboarding procedures. Manual user deployment increased the likelihood of employees being assigned to incorrect departments or receiving inappropriate access permissions. In a healthcare environment, these weaknesses could create unauthorized access risks involving sensitive patient information and potentially affect HIPAA compliance.

## Solution Overview
* In order to solve this problem first I built a new Active Directory domain, NMG.com, using Windows Server 2019 and configured NMG-DC01 as the domain controller. I created four Organizational Units (OUs) and categorized them as; Finance, HR, IT, and Operations as seen in screenshots. Each these units/departments received a corresponding security group to lay a foundation for simple RBAC model. I then added 15 employee accounts to the OUs and organized them to their respective security groups. After this was completed I worked on a simulated high-priority ticket involving an HR employee who was incorrectly assigned to the Operations OU and Security Group. By correcting the employee's OU placement and group membership, I demonstrated user account administration, identity troubleshooting, and access management principles. 

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server 2019 - Server Operating System
* Active Directory Domain Services - Domain Administration and Identity Management
* Oracle VirtualBox - Virtualized Lab Environment 
* Active Directory Users and Computers - User, OU, and Security Group Admin
* Role-Based Access Control (RBAC) - Department Based Management Design
* GitHub - Project Documentation and Evidence 

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Created 4 OUs, 4 security groups, and 15 employee accounts
* Resolved an employee access Ticket by correcting OU placement and security group membership


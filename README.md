# Basic Employee Onboarding (AD)(RBAC)

## Project Overview
* Built a simulated Active Directory environment for Northstar Medical Group (NMG), a fictional healthcare organization, to practice employee onboarding, identity management, and access troubleshooting. 

* The project demonstrates hands-on experience with Windows Server 2019, Active Directory Domain Services (AD DS), and Role-Based Access Control (RBAC) principles.

## Problem Statement
* NMG's fictional IT environment lacked a standardized Active Directory structure due to poor administration by a previous Managed Service Provider (MSP). Inconsistent user provisioning and security group assignments increased the risk of incorrect employee access and potential HIPAA compliance concerns.

## Solution Overview
* I built the NMG.com Active Directory domain using Windows Server 2019, with NMG-DC01 serving as the domain controller. To organize employee accounts, I created 4 departmental OUs (Finance, HR, IT, and Operations) and 4 corresponding security groups to support Role-Based Access Control (RBAC). I then provisioned 15 employee accounts, assigning each to the appropriate department and security group. To put these skills into practice, I resolved a simulated high-priority support ticket (NMG-0047) involving an employee assigned to the wrong department and security group. This demonstrated my ability to identify and correct common Active Directory account management issues.

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


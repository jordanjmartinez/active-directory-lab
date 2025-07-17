# Active Directory Lab 

A hands-on Windows Server lab simulating a real-world enterprise network environemnt using Active Directory, GPOs, and role-based access controls. 

This lab was designed to practice domain management, security policies, and multi-user workflows.

## Table of Contents

### 1. [Objectives](#objectives)
### 2. [Lab Overview](#lab-overview)
### 3. [Technologies Used](#technologies-used)

# 1. Objectives

This lab simulates a real-world Windows enterprise environment to practice Active Directory administration, GPO enforcement, user management, and secure network design. The objectives below cover both foundational setup and advanced tasks to reinforce practical IT skills.

- Build an enterprise domain controller and network from scratch
- Practice user/group administration, GPO deployment, and access control
- Configure OU structured based on departments for scalable management
- Implement folder redirection to centralize user data
- Set up drive mapping via GPO for shared network access
- Enforce desktop restrictions based on department or role
- Simulate least privilege access using nested security groups
- Join client machines to the domain and validate policy enforcment
- Create and enforce password policies and screen lock timers
- Test user isolation, ensuring department users cannot access unauthorized shares
- Practice delegated admin tasks using scope group permisions
- Design and document group naming conventions for clairty and consistency
- Simulate basic IT support tasks (resetting passwords, unlocking accounts)
- Test real-world workflows like onboaring, offboarding, and user role changes
- Integrate Active Directory Certificate Services (AD CS)
- Configure DNS zones and records manually
- Practice writing PowerShell scripts for AD user management

# 2. Lab Overview

| Component              | Description                                 |
|------------------------|---------------------------------------------|
| Domain Controller      | Windows Server 2022                         |
| Domain Name            | robinhood.lab                               |
| Client Machines        | Windows 10/11 VMs                           |
| Organizational Units   | HR, IT, Finance, Sales                      |
| Security Groups        | HR_Group, IT_Group                          |
| Key Features           | GPOs, Folder Redirection, Drive Mapping, Role-Based Device Control   |

# 3. Technologies Used

- Windows Server 2022 VM
- Windows 10/11 VM
- Active Directory Domain Services  
- Group Policy Management  
- Oracle VirtualBox

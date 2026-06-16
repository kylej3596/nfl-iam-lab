# NFL Identity and Access Management Lab

## Project Overview

This project simulates an enterprise Identity and Access Management (IAM) environment using Microsoft Entra ID.

The environment was designed around an NFL organization structure and demonstrates key IAM concepts including:

- User Provisioning
- Security Group Management
- Role-Based Access Control (RBAC)
- Identity Lifecycle Management
- Access Governance
- Least Privilege Principles

---

## Environment

- Microsoft Entra ID
- Azure Portal
- Security Groups
- Cloud-Based Identity Management

---

## Organizational Structure

NFL
├── League Administrators
├── Eagles Management
├── Eagles Coaches
├── Eagles Offensive Players
└── Eagles Defensive Players




---

## Security Groups Created

### NFL-League-Admins

Responsible for overall administration.

### Eagles-Management

Contains executive leadership and management.

### Eagles-Coaches

Contains coaching staff.

### Eagles-Offensive Players

Contains offensive team members.

<img width="1896" height="1056" alt="Offensive players group" src="https://github.com/user-attachments/assets/87897c61-6edc-419f-bc7b-0bc55edf68db" />

### Eagles-Defensive Players

Contains defensive team members.

<img width="1897" height="1067" alt="Defensive player group" src="https://github.com/user-attachments/assets/ceed7e87-af41-4e79-ac1e-f3ad7a73a42f" />

---

## IAM Processes Demonstrated

### Joiner

Created new user accounts and assigned appropriate group memberships.

### Mover

Simulated role changes by modifying group memberships.

### Leaver

Simulated account deprovisioning and removal of access.

---

## Access Review Scenario

A user was identified with excessive privileges outside of their assigned role.

<img width="1855" height="976" alt="user added to group they should not be in" src="https://github.com/user-attachments/assets/76afc15c-4ef3-4a8d-8967-869850ebce67" />

### Remediation

- Reviewed permissions
- Removed unnecessary access
- Revalidated group memberships

  <img width="1887" height="1017" alt="removing user from group" src="https://github.com/user-attachments/assets/0eade3c6-1749-4782-8bb7-46bc6d8d1e9e" />

This demonstrates least privilege and access governance principles.

---

## Skills Demonstrated

- Microsoft Entra ID
- Identity Governance
- Access Management
- RBAC
- User Administration
- Security Groups
- Access Reviews
- IAM Documentation

---

## Author

Kyle Jones

Aspiring IAM Engineer focused on Identity Governance, Access Management, and Cloud Security.

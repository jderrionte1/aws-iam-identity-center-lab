# AWS IAM Identity Center Lab

## Project Objective

Demonstrate centralized identity management using AWS IAM Identity Center (SSO), groups, permission sets, and account assignments.

## Services Used

- AWS IAM Identity Center
- AWS IAM
- AWS Organizations

## Concepts Demonstrated

- Single Sign-On (SSO)
- Identity Management
- Groups
- Permission Sets
- Account Assignments
- Centralized Access Control

## Architecture

Identity Center User
↓
Developers Group
↓
ReadOnlyAccess Permission Set
↓
AWS Account

## Screenshots

### IAM Identity Center Enabled

![Identity Center Enabled](screenshots/identity-center-enabled.png)

### User Created

![User Created](screenshots/user-created.png)

### Group Created

![Group Created](screenshots/group-created.png)

### Permission Set Created

![Permission Set](screenshots/permission-set-created.png)

### Account Assignment Created

![Account Assignment](screenshots/account-assignment-created.png)

## Lessons Learned

This project demonstrated how AWS IAM Identity Center provides centralized access management using users, groups, permission sets, and account assignments.

Unlike traditional IAM users and policies, IAM Identity Center enables scalable access management through Single Sign-On (SSO) and centralized permission management.

Key concepts learned:

- Creating Identity Center users
- Managing groups
- Assigning permission sets
- Linking permissions to AWS accounts
- Implementing centralized access control

## Skills Demonstrated

- AWS IAM Identity Center
- Identity Governance
- Role-Based Access Control (RBAC)
- Permission Management
- AWS Security Best Practices
- Cloud Identity Administration

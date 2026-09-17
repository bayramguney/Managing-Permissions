# Managing-Permissions

# CompTIA Assisted Live Lab: Managing Permissions

## Overview

This lab focuses on understanding and managing file and folder permissions in a Windows operating system environment. Permission management is a fundamental cybersecurity skill used to control access to resources, protect sensitive information, and reduce security risks.

In this lab, I practiced reviewing existing permissions, assigning appropriate access levels, modifying user and group permissions, and validating access after changes were applied.

Proper permission management supports important cybersecurity principles including **Identity and Access Management (IAM)**, **Access Control**, and the **Principle of Least Privilege (PoLP)**.

---

# Lab Objectives

The objectives of this lab were to:

- Understand the purpose of file and folder permissions
- Identify different permission levels and access rights
- Review permissions assigned to users and groups
- Modify permissions according to security requirements
- Apply the principle of least privilege
- Control access to files and folders
- Verify permissions after configuration changes
- Troubleshoot permission-related access issues

---

# Lab Environment

**Lab Type:** CompTIA Assisted Live Lab  
**Topic:** Managing Permissions  
**Category:** Access Control / Identity and Access Management (IAM)

## Operating System

- Windows

## Tools Used

- Windows File Explorer
- File and Folder Security Properties
- User and Group Permission Settings

---

# Background Knowledge

## What Are Permissions?

Permissions define what actions a user, group, or system account can perform on a resource.

Examples of resources that require permissions:

- Files
- Folders
- Applications
- Network shares
- Databases
- System settings

By controlling permissions, organizations can ensure that only authorized users can access sensitive resources.

---

# Types of Windows Permissions

| Permission | Description |
|------------|-------------|
| Full Control | Provides complete access, including reading, writing, deleting files, and changing permissions |
| Modify | Allows users to read, write, modify, and delete files |
| Read & Execute | Allows users to view files and execute applications |
| Read | Allows users to view file contents |
| Write | Allows users to create or modify files |

---

# Principle of Least Privilege (PoLP)

The **Principle of Least Privilege** is a security practice where users are granted only the minimum permissions necessary to perform their assigned responsibilities.

For example:

```
Employee:
Needs access to view reports

Correct Permission:
Read Access
```

Instead of:

```
Full Control Access
```

Providing excessive permissions creates unnecessary security risks, including:

- Unauthorized access
- Accidental data modification
- Data exposure
- Privilege escalation

---

# Lab Tasks Performed

## 1. Reviewing Existing Permissions

The first step was reviewing current permissions assigned to files and folders.

Steps performed:

1. Selected a file or folder.
2. Opened the security settings:

```
Properties → Security
```

3. Reviewed:

- Users with access
- Groups with access
- Permission levels
- Inherited permissions

This helped identify who had access and what actions they were allowed to perform.

---

# 2. Understanding Users and Groups

Windows permissions can be assigned to individual users or groups.

Examples:

```
User:
John Smith

Permission:
Read and Modify
```

```
Group:
Security Analysts

Permission:
Read and Execute
```

Using groups makes permission management easier because administrators can assign access based on job responsibilities rather than managing every user individually.

---

# 3. Modifying Permissions

During this activity, permissions were adjusted based on security requirements.

Tasks included:

- Adding users
- Removing unnecessary permissions
- Changing permission levels
- Assigning appropriate access rights

Example:

Before:

```
Temporary Employee:
Full Control
```

After:

```
Temporary Employee:
Read Only
```

This follows the least privilege security model.

---

# 4. Testing Permission Changes

After modifying permissions, access was tested to confirm that security settings worked correctly.

Validation steps included:

- Confirming authorized users could access resources
- Confirming unauthorized users were restricted
- Checking that assigned permissions matched requirements

Testing permissions is important because incorrect configurations can either block legitimate users or expose sensitive resources.

---

# Security Importance

Incorrect permission configurations can create serious security vulnerabilities.

Common risks include:

## Unauthorized Data Access

Users may access confidential files without proper authorization.

## Data Modification

Users with excessive permissions may accidentally or intentionally change important information.

## Privilege Escalation

Attackers may take advantage of weak permissions to gain higher access levels.

## Compliance Issues

Organizations must maintain proper access controls to meet security and regulatory requirements.

---

# Relationship to the CIA Triad

Permission management supports the three principles of information security:

## Confidentiality

Ensures sensitive information is accessible only to authorized users.

Example:

```
Only HR employees can access employee records.
```

## Integrity

Prevents unauthorized users from modifying important data.

Example:

```
Only administrators can change system configuration files.
```

## Availability

Ensures authorized users can access resources when needed.

Example:

```
Employees can access required applications and documents.
```

---

# Real-World Cybersecurity Applications

Security professionals use permission management in many areas:

## Identity and Access Management (IAM)

IAM controls:

- User identities
- Authentication
- Authorization
- Access permissions

## Access Reviews

Security teams regularly review permissions to identify:

- Excessive privileges
- Unused accounts
- Incorrect access assignments

## Security Auditing

Auditors examine permissions to verify that organizations follow security policies.

## Incident Response

Security analysts investigate permissions when determining how unauthorized access occurred.

---

# CompTIA Security+ Connections

This lab relates to several CompTIA Security+ SY0-701 concepts.

## Domain 1: General Security Concepts

Topics covered:

- Security controls
- Access control principles
- Least privilege
- Defense-in-depth

## Domain 4: Security Operations

Topics covered:

- Account management
- Permission auditing
- Security monitoring
- Access reviews

## Domain 5: Security Program Management

Topics covered:

- Security policies
- Governance
- Compliance requirements

---

# Skills Demonstrated

Through this lab, I demonstrated the following cybersecurity skills:

✅ File and folder permission management  
✅ Windows access control administration  
✅ User and group permission configuration  
✅ Identity and Access Management fundamentals  
✅ Least privilege implementation  
✅ Permission troubleshooting  
✅ Security best practices  
✅ Access control auditing  

---

# Key Takeaways

- Permissions control who can access resources and what actions they can perform.
- Least privilege is essential for reducing security risks.
- User and group permissions must be reviewed regularly.
- Proper access control protects confidentiality, integrity, and availability.
- Permission management is an important responsibility for cybersecurity professionals and SOC analysts.

---

# Career Relevance

As a cybersecurity professional and SOC Analyst candidate, understanding permissions is essential because analysts frequently investigate:

- Unauthorized access attempts
- Account privilege issues
- Suspicious user activity
- Misconfigured access controls
- Security policy violations

Managing permissions correctly helps organizations reduce attack surfaces and maintain a secure environment.

---



GitHub Portfolio:

https://github.com/bayramguney

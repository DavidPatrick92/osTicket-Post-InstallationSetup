# osTicket-Post-InstallationSetup

## Project Overview

## Acknowledge Agent Panel vs Admin Panel

### Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin

📸 Screenshot:
Terminal output showing the resolved IP addresses:
<img width="1000" alt="image" src="images/Screenshot 2026-08-04 202333.png">


### Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

### Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

## Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 

### Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)

### Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken

### Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)

### Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other

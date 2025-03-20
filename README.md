# HackArmory DevSecOps Course Plan (5 Weeks)

## Week 1: Introduction to DevSecOps & Azure Cloud Fundamentals

### Day 1: Introduction to DevSecOps and Azure Cloud
* What is DevSecOps?
* The DevSecOps lifecycle (Plan → Develop → Build → Test → Release → Deploy → Operate → Monitor)
* Security challenges in traditional DevOps vs. DevSecOps

**DIY Project:** Create a DevSecOps roadmap tailored to different roles (Dev, Sec, Ops).

* Overview of Azure services & architecture
* Resource Groups, Availability Zones, and Subscriptions
* Using Azure Portal, CLI, and PowerShell

**DIY Project:** Set up an Azure account and deploy a Resource Group.

### Day 2: Identity & Access Management (IAM), Management Groups & Hierarchies and Provisioning
* Azure Active Directory (AAD) and authentication methods
* IAM roles, RBAC policies, and least privilege access

**DIY Project:** Create users, groups, and assign IAM roles in Azure.

* Billing and cost management with subscriptions
* Implementing Azure Management Groups for multi-account structures
* Setting policies for management groups

**DIY Project:** Set up a Management Group hierarchy and assign policies.

* Deploying VMs using Azure Portal & CLI
* Networking basics (VNETs, NSGs, Public/Private IPs)
* Secure Shell (SSH) and Remote Desktop (RDP)

**DIY Project:** Deploy a Linux/Windows VM and configure security groups.

## Week 2: Networking & Security Essentials

### Day 3: Networking Fundamentals, Secure Access & Zero Trust Architecture

* What is a VNET (Virtual Network)?
* Subnets, DNS, Public vs. Private IPs
* Network Security Groups (NSG) and Firewalls

**DIY Project:** Deploy a VNET with two subnets and configure an NSG to restrict access.

### Day 4: Secure Access, Zero Trust Architecture, Cloud Security and Compliance

* Role of VPNs, Bastion Hosts, and Jump Servers
* Zero Trust Architecture principles
* Just-in-Time (JIT) Access in Azure

**DIY Project:** Set up Azure Bastion for secure remote VM access.

* Azure Security Center & Defender
* Governance (Azure Policy, Blueprints)
* Compliance frameworks (SOC2, NIST, CIS)

**DIY Project:** Apply an Azure Policy to enforce governance rules on resources.

* Azure Monitor, Log Analytics, Application Insights
* Implementing alerts and dashboards

**DIY Project:** Create an Azure Monitor dashboard tracking VM performance.

## Week 3: Agile, Scrum, and Sprint Planning
### Day 5: Agile & Scrum Basics

* What is Agile?
* Scrum framework: roles, ceremonies, artifacts
* Story points and backlog prioritization

**DIY Project:** Create a Scrum workflow in Azure DevOps and define a sample backlog.

### Day 6: Sprint Planning and Task Management

* Creating epics, stories, and tasks
* Using Kanban and Scrum boards
* Sprint reviews and retrospectives

**DIY Project:** Set up a Kanban board and assign work items.

## Week 4: Git & CI/CD Pipelines
### Day 7: Git & Version Control

* Git fundamentals (clone, commit, push, pull, branch, merge)
* Feature branches vs. trunk-based development
* GitHub/GitLab/Azure Repos basics

**DIY Project:** Set up a Git repository, create branches, and push code.

### Day 8: CI/CD Pipeline Basics and Security

* Understanding Continuous Integration & Deployment
* CI/CD tools: GitHub Actions, Azure DevOps Pipelines

**DIY Project:** Create a basic CI pipeline in GitHub Actions or Azure DevOps.

* Security scanning in pipelines (SAST, DAST, dependency checks)
* Secrets management (Azure Key Vault)

**DIY Project:** Build a CI/CD Pipeline that connects to your Azure Account

## Week 5: Infrastructure as Code (IaC) with Terraform
### Day 9 Introduction to Infrastructure as Code (IaC)

* What is IaC? Terraform vs. ARM templates vs. Bicep
* Setting up Terraform CLI

**DIY Project:** Install Terraform and configure Azure as a provider.

* Terraform providers, variables, modules
* Managing state and locking

**DIY Project:** Write a Terraform script to deploy a Resource Group and Storage Account.

### Day 10: Terraform for Infrastructure Automation

* Terraform best practices (remote state, workspaces)
* Integrating Terraform with CI/CD

**DIY Project:** Use Terraform to deploy a VM and configure networking.
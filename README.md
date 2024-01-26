# DEVOPS

## 1. Overview of DevOps

## 2. Version Control with Git

## 3. Build and Deployment tools (Jenkins)

## 4. Infrastructure Automation (Ansible)

## 5. Microservices (Docker)

## 6. Orchestration using Kubernetes

## 7. Monitoring tools

## 8. Terraform - Infrastructure Management

## 9. Live examples

## 1. Module - Overview of DevOps

### Definition of DevOps

#### DevOps is nothing but a practice/methodology to work developers and operations working together

### Roles and Responsibilities

1. Build and Deployment Automation
2. CICD Workflows
3. System Admin
4. Monitoring, Logging and Reporting
5. Integrations

### Version Control Systems

#### VCS is an application which tracks every change

1. Centralized Version Control System (SVN)
2. Distributed Version Control System (GIT - v2.43.0)

### GIT

- Working directory is also knows as untracked area.

- Version - git --version
- git config --global user.name "Anil Simha"
- git config --global user.email "<tanilsimha@gmail.com>"
- git config --global --list
- git init : To initialize the empty repository
- git add -A : To add all the untracked files
- git status : To see what all files are committed and not
- git rm --cached fileName : To unstage
- git commit -m "commit message" : To commit the files
- git ls-files: To view the list of committed files in local repo
- git log : To view the change log in detailed
- git log --oneline : High level view
- git show "commitID" : To view details from that particular commitID

# Project List

## Training Scheduler

**Role:** Developer

**Tasks:** 

* Enables the staff to manage the application of tutors.
* Includes scheduling function as the name denotes, and enables the applicants to proceed to the next step of application.

## Scheduling Pages

**Role:** Developer

**Tasks:** 

* Created new interactive systems that enable tutors to manage their schedules, which is considered one of the most critical functions for the main company website.

## Migration from native PHP to Yii Framework of Main Website

**Role:** Senior Developer

**Tasks:** 

* Work with a junior developer to transfer/translate all functions given the limited timeframe.

## Development Environment

**Role:** Sysad

**Tasks:** 

* Previous development environment just used XAMPP on Windows workstations while production used Centos VMs.
* Created development environment using KVM and OpenVZ to closely replicate the production environment.
* Instructed the users on how to use the new environment as the new main dev environment to help lessen cross-environment errors.

## Migration from Subversion to Git

**Role:** Ops

**Tasks:**

* Migrate old SVN repositories to Git.
* Help familiarize users in using Git to maximize its features like powerful branching. It is quite difficult to visualize branching especially when migrating from SVN where we never used the merging feature.
* Used Git Flow (slightly modified) as the new development flow.

## Unit Testing

**Role:** Developer

**Tasks:**

* Initiated the creation/usage of unit tests for the main website.
* Created initial tests and also created guides/tips for other developers.
* Taught other developers on how to create tests and how make testable code.

## Capistrano deployer

**Role:** Ops

**Tasks:**

* Create recipes for new systems and modify existing recipes to enable new features.
* Created recipes that use git as the source.

## Jenkins

**Role:** Ops, Release Manager

**Tasks:**

* Set-up Jenkins for running various tests so it will be part of the deployment process.
* Integrated capistrano deployment so developers can take control of the deployment process.

## Redmine

## Development environment using VMWare

**Role:** Ops, Release Manager

**Tasks:**

* Set-up Jenkins for running various tests so it will be part of the deployment process.

## Percona + Syncthing for local development database

**Role:** Sysad

**Tasks:**

* Used Percona Xtrabackup to make faster and more efficient backup of the large database for use in the development environment.
* Used Syncthing to enable faster (P2P) transfer of DB data to multiple development DB VMs.
* JP Side adopted this method later for use in the Production environment.

## Puppet

**Role:** Sysad

**Tasks:**

* Set up puppet to manage the main website development VMs.
* It is ideal for this purpose since we don't want the devs to make permanent configuration modifications to the dev VMs, in order to prevent cross-environment errors. 

## Readthedocs

**Role:** Sysad

**Tasks:**

* Set up readthedocs in the office network to host docs/guides by the IT/System Departments
* Taught the users on how to create and deploy documents to the system

## ELK Stack

**Role:** Sysad

**Tasks:**

* Set up ELK in office network to monitor network traffic and usage.
* Helped set up ELK in AWS to monitor access logs from the main company websites.
* Created new metrics/graphs based on the currently available data.

## Jenkins Blue Ocean

**Role:** Ops

**Tasks:**

* Updated Jenkins to newest version and then installed the Blue Ocean plugin.
* Created new pipelines for the main projects. (Build, Test, Merge, Approval, Deploy, Notifications)

## Sakura Cloud to AWS Migration

## Ansible

**Role:** Sysad

**Tasks:**

* Created ansible configurations to provision the PH-side websites during AWS migration and also for new projects.
* Ran the scripts for both the Staging and Production environments.

## Docker

## Kubernetes


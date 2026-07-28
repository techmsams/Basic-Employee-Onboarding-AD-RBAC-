# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
The problem in this project was related to a fictional company I was working for called Northstar Medical Group. They are considered a fast-growing company that delegates their Identity Lifecycle workflow to a third-party MSP. In the beginning, this was good, but as they grew, issues began to show. They had no RBAC policy in place. Their users were assigned access AD-HOC. There were no audit trails and HIPAA risks.

## Solution Overview
The solution was to build out a basic employee onboarding pipeline in Active Directory. I set up an RBAC matrix and ensured that the users were given access to ONLY the things required for the role. I also simulated a mock ticket where a user was provisioned the incorrect level of access.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Solved a mock ticket where a user was given the incorrect access!
* I fully documented my steps end-to-end

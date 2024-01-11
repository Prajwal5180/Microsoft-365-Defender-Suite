# Microsoft 365 Defender Suite

## Overview

Microsoft 365 Defender is an integrated security suite that offers comprehensive protection across various Microsoft 365 services. It combines multiple security solutions to provide advanced threat protection, detection, and response capabilities.


### Key features of Microsoft Defender

- Microsoft Defender for Office 365: Defender for Office 365 safeguards your organization against malicious threats posed by email messages, links (URLs) and collaboration tools.

- Microsoft Defender for Cloud Apps: Microsoft Defender for Cloud Apps is a Cloud Access Security Broker (CASB) that operates on multiple clouds. This provides full visibility and in-depth data to identify and protect all of your Microsoft and third-party cloud services from cyberthreats. With security professionals in mind, Microsoft Defender for Cloud Apps incorporates innovative automation along with centralized management and simple deployment.

- Microsoft Defender for Identity: Microsoft 365 Defender for Identity is a cloud-based service designed to help protect on-premise, cloud and hybrid environments from various types of internal threats and targeted cyber-attacks. This is accomplished by leveraging your on-premise Active Directory signals to detect advanced threats early and identify malicious insider actions directed at your organization.

## Sandbox Scenario
Contoso Corporation, strategically implements the Microsoft 365 Defender Suite to fortify its cybersecurity posture. The corporation, operating in a dynamic and interconnected digital landscape, recognizes the critical importance of comprehensive security solutions. Contoso initiates the implementation of Microsoft Defender for Office 365, Microsoft Defender for Cloud Apps, and Microsoft Defender for Identity to integrate security and designed to offer comprehensive protection across various Microsoft 365 services. It combines multiple security solutions to provide advanced threat protection, detection, and response capabilities.

## About the Sandbox

Using this environment, You'll be able to explore features and offerings offered by Microsoft Defender. Please find the detailed overview of the sandbox environment below.

### Pre-provisioned resources

#### **Virtual Machines**: 

- 2 *Windows Server 2019 Datacenter* Virtual machines, virtual machine-related resources like Virtual networks, Network security groups, managed disks, Network interface cards, and IP addresses are deployed as part of the automation.

  These virtual machines are tailored and configured to the sandbox's specifications. Files, applications, packages, and OS configurations are all pre-configured. It is recommended that you use the same virtual machine throughout the lab for the best experience.

#### **License and subscription**: 

- You'll have access to a pre-configured Microsoft user account with an active Azure subscription, a tenant, and a Microsoft 365 E5 license assigned to the user. 
   
  User account has been assigned as Owner at subscription and Global administrator at the tenant level. You need to use the same user account throughout the lab to get the most out of the lab. 

#### **Azure Credits**: 

- You have been given a quota of **$83 USD** which includes the running cost of Pre-deployed resources, license cost, and other resources deployed while running through the lab.

  You will receive **cost alerts** to your registered email address at **50%/75%/90%/95%/100%** of the allotted Azure Credit is spent.

  You can visit the Azure Subscription page to check the current Azure credit spend and Analysis on **Cost analysis** tab under the Cost Management option.

  ![Picture 1](../Media/o1.jpg)

#### **Duration and Deletion of sandbox**:  

- The sandbox environment will be active for **30 days/730** hours from the time of registration. 
- The maximum allowed virtual machine uptime is only **40 hours**. It is recommended to deallocate the virtual machine when not in use.
- The virtual machine is set up with a custom feature called Idle start/stop. This custom package will check the virtual machine's idleness every **2 hours/120 minutes**. If the virtual machine is left idle for over 2 hours, a pop-up window will appear, prompting you to respond. If you do not take action within 10 minutes, the virtual machine will shut down automatically. This feature is enabled in virtual machines to optimize Azure costs.
- when 100% of Azure credits are spent, the sandbox environment will get automatically deleted without any prior notification. To retain the environment for a longer period and to get the most out of the environment, please follow the best practices mentioned below.

#### **Best practices**: 

- **Resources usage**: Please stop the virtual machines and other resources when not in use to minimize the Azure spend.

- **Azure Cost Analysis**: Maintain a practice of checking the Cost Analysis report of the assigned Azure subscription often in check the Azure spending so that the environment can be retained for a longer duration of time.

- **Alert notifications**: Make sure to check your registered email's inbox for any alert-related mails. Alerts give you a head start to keep your Azure spending in control and to plan out the remaining credits in the best way possible.

## Lab Guide Contents:
You will have access to a lab guide which is a reference material to assist you in getting started with the exploration.

Based on your interests, you can use this lab guide as a reference to learn and test any Microsoft Defender feature. You are also encouraged to explore additional features of Microsoft Defender based on your interests and preferences.

- Lab 01 - Explore Microsoft Defender Portal 
- Lab 02 - Configure Email authentication
- Lab 03 - Configure Protection Policies 
- Lab 04 - Configure Priority accounts 
- Lab 05 - Configure block/allow lists
- Lab 06 - Launch phishing simulation campaigns
- Lab 07 - Create Incidents 
- Lab 08 - Detect & Investigate threats
- Lab 09 - Discover Apps 
- Lab 10 - Configure App Access Policies 
- Lab 11 - Setup Alerts & App Governance 
- Lab 12 - Investigate Alerts and activities
- Lab 13 - Deploy Domain Controller 
- Lab 14 - Setup Defender for Identity Sensors 
- Lab 15 - Download and schedule defender for identity reports

### Azure services and related products

- Microsoft Defender for Office 365
- Microsoft Defender for Cloud Apps
- Microsoft Defender for Identity
- Microsoft Entra ID

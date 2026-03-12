# Azure SOC Lab – Security Monitoring Project

This project demonstrates a home Security Operations Center (SOC) lab built using Microsoft Azure and Microsoft Sentinel.

The purpose of this lab is to simulate cyber attacks, collect security logs and detect malicious behaviour using SIEM detection rules.

## Technologies Used

• Microsoft Sentinel (SIEM)

• Azure Virtual Machine

• Log Analytics Workspace

• KQL (Kusto Query Language)

• Windows Event Logs

## Lab Capabilities

• Log ingestion from Windows VM

• Detection of brute-force login attempts

• Security alert investigation

• Mapping attacker behaviour using MITRE ATT&CK


## Architecture

The SOC lab environment was built in Microsoft Azure and consists of a monitored Windows virtual machine sending security logs to Microsoft Sentinel.

The diagram below illustrates the data flow within the SOC lab environment.

<p align="center">  
<img width="650"  alt="image" src="https://github.com/user-attachments/assets/0bdbd002-cdea-4f66-9b08-5bdbdcb9e298" />

</p>

## Lab Setup

The SOC lab environment was deployed in Microsoft Azure using the following components:

### Resource Group

A dedicated resource group was created to manage all resources related to the SOC lab environment.

<img width="3507" alt="image" src="https://github.com/user-attachments/assets/48b33477-8d89-443f-983f-e8c5a4c15bcf" />




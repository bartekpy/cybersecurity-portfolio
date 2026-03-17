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
<br>
<br>
<br>

### Resource Group

A dedicated resource group was created to manage all resources related to the SOC lab environment.
<p align="centre">
<img width="900"  src="https://github.com/user-attachments/assets/48b33477-8d89-443f-983f-e8c5a4c15bcf" />
</p>  
<br>
<br>
<br>

### Log Analytics Workspace

Log Analytics Workspace was deployed to store and analyse security logs collected from the monitored virtual machine.

<p align="centre">
<img width="900" alt="image" src="https://github.com/user-attachments/assets/42d60a17-bc67-4e2e-b13d-e7d9971126ea" />
</p>
<br>
<br>
<br>

### Microsoft Sentinel

Microsoft Sentinel was enabled on top of the Log Analytics Workspace to analyse collected security logs and detect suspicious activity.

<p align="center">
<img width="900"  alt="image" src="https://github.com/user-attachments/assets/0cb6338c-bd8c-46fe-a2c0-7cbcd2608888" />
</p>






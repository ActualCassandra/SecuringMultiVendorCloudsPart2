
# Securing Multivendor Clouds Part 2 - Microsoft Event for Partners

Welcome to the Securing Multivendor Clouds Part 2 repository.

***Part 2 will be on March 17 2022 from 1400-1730 GMT!***

## Registration Link
https://aka.ms/securingmvc-regp2

## Event Presentation PDF
A PDF version of the presentation from the event will be made available within a week of the event finishing.

*Link coming soon*

### Part 1
If you want to know more about securing multivendor clouds from an identity perspective, please check out the [github repo for Part 1](https://github.com/LuciBlanchardMSFT/SecuringMultiVendorClouds). However, it is not a requirement for Part 2.

## Badges and how to claim
Silver – Complete cloud skills challenge **and** be registered for the event.

Gold – Completed cloud Skills Challenge **+** registered for the event **+** pass the SC-200 exam.

To claim a badge, send an email to:

 > Email: ProtectandDefend@microsoft.com
 > 
 > Subject: Securing Multivendor Clouds Badge Claim
 > 
 > Body: Provide proof of completing the skills challenge https://aka.ms/SecuringMVC2-CSC, along with proof that it’s you, and proof of SC-200 certification for gold(screenshot will suffice).

Qualified submissions will receive a Badge via email.

## Agenda

**Azure Arc:**
 - Overview
 - Hybrid Scenarios

**Defender for Cloud:**
 - Overview
 - Learn how to get a single view showing Defender for Cloud recommendations for AWS and GCP
 - Integrate GCP and AWS resources into Defender for Cloud's secure score calculations
 - Use Defender for Cloud to show the Integration of GCP Security Command Center recommendations based on the CIS standard into the Defender for Cloud's regulatory compliance dashboard
 - Use Defender for Cloud's CSPM features to manage your AWS resources
 - Use Microsoft Defender for Containers for threat detection and advanced defenses to your Amazon EKS clusters

**Microsoft Sentinel:**
 - Overview
 - Data Connectors
 - Sentinel Solutions
 - Content Management

## Following along in the demo / labs
Access to an Azure tenant is required to follow along, as is access to a GCP and AWS Tenant. Not all of these will be free, although the costs should be minimal. 

### Labs
#### Part 1 Labs - IAM
These labs are not required, but they will show you to leverage Azure AD in a multi-cloud environment. 
- [Part 1 Labs](http://aka.ms/securingmvc-repo)

#### Part 2 Labs and Docs
[Main labs folder of this repo](/Labs) for the initial setup of AWS and GCP.

Additionally, the demos will go through connecting AWS and GCP to Microsoft Defender for Cloud, as per these Microsoft documentation pages:
- [Connecting AWS to MDfC](https://docs.microsoft.com/en-us/azure/defender-for-cloud/quickstart-onboard-aws)
    - [AWS prerequisites for ARC, etc.](https://techcommunity.microsoft.com/t5/itops-talk-blog/step-by-step-how-to-connect-aws-machines-to-microsoft-defender/ba-p/3251096)
- [Connecting GCP to MDfC](https://docs.microsoft.com/en-us/azure/defender-for-cloud/quickstart-onboard-gcp)
- [Custom Standards and Assessments](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/custom-assessments-and-standards-in-microsoft-defender-for-cloud/ba-p/3251252)
- [Connecting non-Azure virtual machines](https://docs.microsoft.com/en-us/azure/defender-for-cloud/quickstart-onboard-machines?pivots=azure-arc)

Our Microsoft Sentinel demo is narrower in scope than the MDfC demo and focuses on some new AWS S3 functionality:
- [Connect Microsoft Sentinel to Amazon Web Services to ingest AWS service log data](https://docs.microsoft.com/en-us/azure/sentinel/connect-aws?tabs=s3)
- [PowerShell scripts for AWS S3 Data Connector](https://github.com/Azure/Azure-Sentinel/tree/master/DataConnectors/AWS-S3)

Finally, Azure Arc is a very broad topic. [Azure Arc Jumpstart](https://azurearcjumpstart.io/azure_arc_jumpstart/) has labs for a wide range of scenarios and is recommended to learn more, hands-on.
- [Connect Azure Arc-enabled servers to Microsoft Defender for Cloud](https://azurearcjumpstart.io/azure_arc_jumpstart/azure_arc_servers/day2/arc_defender/#azure-arc-and-microsoft-defender-for-cloud-integration)
- [Connect Azure Arc-enabled servers to Azure Sentinel](https://azurearcjumpstart.io/azure_arc_jumpstart/azure_arc_servers/day2/arc_azuresentinel/#connect-azure-arc-enabled-servers-to-azure-sentinel)

*More tbc*

## Learning and Training Resources
 - [Microsoft Defender for Cloud Ninja Training](http://aka.ms/ascninja)
 - [Microsoft Defender for Cloud Community Repository](https://github.com/Azure/Microsoft-Defender-for-Cloud)
 - [Microsoft Sentinel Ninja Training](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/become-a-microsoft-sentinel-ninja-the-complete-level-400/ba-p/1246310)
 - [Defender for Cloud 'In the Field' Youtube series](https://www.youtube.com/hashtag/mdfcinthefield)
 - [Cloud Skills Challenge for this event - SC-200 learning path excerpts relevant to this event](https://aka.ms/SecuringMVC2-CSC)
 - [Azure Arc Jumpstart](https://azurearcjumpstart.io/overview/)

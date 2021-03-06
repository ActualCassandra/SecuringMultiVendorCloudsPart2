# Overview
These labs require:
 - An Azure tenant
 - An Amazon Web Services (AWS) tenant
 - A Google Cloud Platform (GCP) tenant


## Potential costs
 Costs should be minimal and you should use trial accounts where possible. Ensure that any resources such as containers or VMs are shutdown when not using and once you have completed the labs delete any created resources.

 Microsoft Defender for Cloud (MDfC) costs are only incurred when specific services are being used, but you are still encouraged to use the trial. See the [pricing page for details](https://azure.microsoft.com/en-gb/pricing/details/defender-for-cloud/).
 
 ## Other details
 - Use a modern browser such a Edge. Recommended to use an 'InPrivate' window or similar when creating accounts so that you don't accidentally used a logged in account unless you really wish.
 - If you follow along during the event, you will probably not see any resources from AWS or GCP show up in MDfC as the onboarding process can take several hours once a connector has been configured.

 # AWS
 You should create a trial account (if you do not already have an account) 24 hours prior to doing the labs.
 
 You can skip most of the next section if you want to use an existing account, skip to Step 10 if this is the case.
## Steps to create your AWS trial account
1. Go to https://aws.amazon.com/free/. Click 'Create a a Free Account'. [Screenshot](../Images/AWS-1-create%20a%20free%20account.png)
2. Type the email address you would like to use for the trial as well as a unique AWS account name, and click 'Verify email address'. You'll be sent an email to the same address containing a verification code. Enter the code and select verify. Double check your spam folder if you do not see the AWS email verification email. [Screenshot](../Images/AWS-2-sign%20up%20for%20AWS.png)
3. Once you have entered your verification code, you'll be prompted to create a password for your root account. Choose a secure password. [Screenshot](../Images/AWS-3-email%20verification%20code.png)
4. You'll now need to provide additional details for your account. Make sure you select 'Personal - for your own projects'. Tick your agreement at the bottom and click Continue. [Screenshot](../Images/AWS-4-Account%20details.png)
5. You'll now need to enter in your billing details. Ensure that you terminate the trial immediately once the labs are completed so you do not incur additional charges. [Screenshot](../Images/AWS-5-Billing%20details.png)
6. Confirm your identity. Choose whichever option you prefer, enter the captcha, and select the option at the bottom. SMS works well for most people. [Screenshot](../Images/AWS-6-Confirm%identity.png)
7. Enter the code you received to your phone. [Screenshot](../Images/AWS-7-Enter%20code.png)
8. You'll now be asked to select a support plan. For these labs and your trial account, select 'Basic support - Free' and Click 'Complete sign up' at the bottom to finish the AWS trial sign up process. [Screenshot](../Images/AWS-8-Support%20Plan.png)
9. You've completed signing up for your AWS trial account. Click 'Go to the AWS Management Console' to start your labs. *You may want to get a cup of tea before clicking, since occasionally it takes a few minutes before your account is ready to use. You'll receive an email titled 'Your AWS Account is Ready - Get Started Now' once it is ready.* We will not go through securing your AWS account, but please enable MFA on this account. [Screenshot](../Images/AWS-9-Complete%20trial%20sign%20up.png)
10. You'll need your AWS account ID for any labs. Whilst in the AWS console, click on your account name in the top right and the account ID will be shown in the dropdown menu. Alternatively you can run the command 'aws sts get-caller-identity' from the AWS CLI which will show the ID for your currently logged-in account. [Screenshot](../Images/AWS-10-Account-ID.png)
11. If you need to return to the AWS console, go to https://console.aws.amazon.com.


 ## Connecting your AWS account to your Azure subscription
https://docs.microsoft.com/en-us/azure/defender-for-cloud/quickstart-onboard-aws?pivots=env-settings#connect-your-aws-account

 # GCP
 You should create a trial account (if you do not already have an account) 24 hours prior to doing the labs.

 You can skip most of the next section if you want to use an existing account, **skip to Step 9 if this is the case**.
## Steps to create your GCP trial account
1. Go to https://cloud.google.com/free/. Click 'Get started for free'. [Screenshot](../Images/GCP-1-get%20started%20for%20free.png)
2. This page will probably show your currently logged-in google account. But, feel free to create a separate account and 'switch account' if you want to use a different one. You'll need to do this if you've already tried GCP for free on a specific account in the past. *We will not walk through setting up a base google account*. Select the appropriate country and 'Personal project', accept the Terms of service, and click 'Continue'. [Screenshot](../Images/GCP-2-Account%201%20of%203.png)
3. Enter your mobile phone number and click 'Send Code'. [Screenshot](../Images/GCP-3-Send%20Code.png)
4. Enter the verification code and click 'Verify'. [Screenshot](../Images/GCP-4-Verify.png)
5. You'll now need to enter in  your billing details. You can selecet an existing payments profile or create a new one, and note the $300 credit as well as no autocharge after your free trial ends. Once you have completed this page, click 'Start my Free Trial' at the bottom. [Screenshot](../Images/GCP-5-Billing%20details.png)
6. A popup window will appear on your screen, on top of the existing window which will be darkened. Verify that it's you. Click 'Continue' and a new browser window will open. **this experience may vary depending on your credit card provider's security** If verification is successful you'll be sent to a welcome screen.
7. At the welcome screen fill in what best describes you and click 'Done'. [Screenshot](../Images/GCP-7-Welcome-Done.png)
8. You've completed creating your free account and are now ready to start the labs. We will not go through securing your GCP account, but please enable MFA.
9. It's recommended that you create a new project for the lab and maybe a new Organization 'above' the project. **You'll need to know the project number and project ID later when connecting your project to Microsoft Defender for Cloud.** You can search for a project by typing its name into the top search bar, or typing *project* and seeing if it is on the list, or you can also search for 'Create a Project. Find your project and you will see the required details. [Screenshot](../Images/GCP-9-Project-details.png)
10. If you need to return to the GCP console, go to https://console.cloud.google.com.


## Connecting your GCP project to your Azure subscription
https://docs.microsoft.com/en-us/azure/defender-for-cloud/quickstart-onboard-gcp?pivots=env-settings#connect-your-gcp-projects

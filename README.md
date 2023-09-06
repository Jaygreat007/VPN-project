# VPN-project


 

<h2>Description</h2>
Creating a Virtual Private Network (VPN) on the Amazon Web Services (AWS) cloud is a valuable addition to your cybersecurity portfolio. A VPN enhances data security and privacy by establishing an encrypted communication channel between your network and AWS resources.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Aws cloud</b> 
- <b>Virtual Machine</b>

<h2>Environments Used </h2>

- <b>Mac ios </b> 

<h2>Program walk-through:</h2>
Step 1: AWS Account Setup

Sign Up for AWS: If you don't already have an AWS account, sign up for one on the AWS website.

Access AWS Console: Log in to the AWS Management Console using your account credentials.

Step 2: Launching a Virtual Private Server (VPS)

Choose a Region: Select the AWS region where you want to deploy your VPS. Consider factors like latency and data residency requirements.

Launch an EC2 Instance: Launch an Amazon Elastic Compute Cloud (EC2) instance, which will act as your VPN server. Choose an appropriate instance type and configure security group rules to allow VPN traffic.

Create and Associate a Key Pair: To secure remote access to the VPS, create an SSH key pair and associate it with the instance.

Step 3: VPN Server Configuration

Connect to the VPS: Use SSH to connect to your VPS. Install and configure the VPN server software of your choice. Common choices include OpenVPN, IPsec, or AWS Client VPN.

Generate Certificates and Keys: Create the necessary certificates and keys for the VPN server and clients. Ensure that you follow best practices for certificate management.

<h2>Screenshots of Project </h2>


<p align="center">
Launch the Aws cloud VPN: <br/>
<img src="https://imgur.com/Wtsa4Nx.jpeg" height="80%" width="80%" alt=/>
<br />
<br />
Select the platforms you're connecting to:  <br/>
<img src="https://imgur.com/3VqNSkV.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install the OpenVPN connect app: <br/>
<img src="https://imgur.com/hADf8t3.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the username and passcode to your OpenVPN:  <br/>
<img src="https://imgur.com/nAYTVTW.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Your vpn connection stats:  <br/>
<img src="https://imgur.com/2oIq2WS.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
This screenshot basically confirms that my VPN is working correctly. As you can see my ip address says that I am located in Columbus, Ohio. When I am currently in Charlotte, North Carolina:  <br/>
<img src="https://imgur.com/Ey8caOR.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

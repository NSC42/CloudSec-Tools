# Cloud-Security-Resources- NEW REPO
List of cloud Security Resources and tools

Disclaimer:
This is a group of tools references and resources put together for AWS, Azure and GCP.
Feel free to reference it and use it.

Please quote the author :) be kind

#####
# AWS 
####


# Name - CloudSplaining 
Resource - IAM
Platform - AWS

Cloudsplaining is an AWS IAM Security Assessment tool that identifies violations of least privilege and generates a risk-prioritized HTML report with a triage worksheet. https://cloudsplaining.readthedocs.io/

Link: https://github.com/salesforce/cloudsplaining.git
----

# Name - Sentinel Hashicoper Terraform Template 
Resource - Terraform, CIS
Platform - AWS

Sentinel is a language and framework for policy built to be embedded in existing software to enable fine-grained, logic-based policy decisions. This repository contains a library of Sentinel policies, developed by HashiCorp, that can be consumed directly within the Terraform Cloud platform.

Link: https://github.com/salesforce/cloudsplaining
---

# PROWLER - Tool based on AWS-CLI commands 
1. prowler - Tool based on AWS-CLI commands for AWS account hardening, following guidelines of the CIS Amazon Web Services Foundations Benchmark 
# Link: https://github.com/toniblyx/prowler 
---

# CIS - CIS Compliance for AWS
# Link: https://d0.awsstatic.com/whitepapers/compliance/AWS_CIS_Foundations_Benchmark.pdf)

---

# SCOUT2 - Security auditing tool for AWS environments 
nccgroup/Scout2 - Security auditing tool for AWS environments 
# Link: https://github.com/nccgroup/Scout2 

---

# CloudSploit scan - AWS security scanning checks
nccgroup/Scout2 - Security auditing tool for AWS environments 
# Link: https://github.com/cloudsploit/scans

--
# Amazon Inspector Official

# Link https://aws.amazon.com/inspector/
 
 ---
 
 # Netflix Security Monkey 
 Netflix/security_monkey - Security Monkey monitors your AWS and GCP accounts for policy changes and alerts on insecure configurations
# Link https://github.com/Netflix/security_monkey
 
 ---
 
 # Netflix - Aardvark
 
6. Aardvark - Aardvark is a multi-account AWS IAM Access Advisor API
# Link: https://github.com/Netflix-Skunkworks/aardvark

 # Netflix - RepoKid
  Repokid - AWS Least Privilege for Distributed, High-Velocity Deployment
  
 # Link: https://github.com/Netflix/repokid 
  
  ---
 # AWS Zeus - by Deniz
  
8. DenizParlak/Zeus - AWS Auditing & Hardening Tool 

# Link http://www.denizparlak.com/?p=386
----

# Nimbostratus Fingerprinting and Exploiting Cloud infra 

9. Nimbostratus - Tools for fingerprinting and exploiting Amazon cloud infrastructures + video presentation and intro blog post
# Instruction Link: https://andresriancho.github.io/nimbostratus/
# GIT: https://github.com/andresriancho/nimbostratus
----

# Bitbucket Finder 

10. Bucket finder - This is a fairly simple tool to run, all it requires is a wordlist and it will go off and check each word to see if that bucket name exists in the Amazon's S3 system. Any that it finds it will check to see if the bucket is public, private or a redirect.

# link -  TBD

--

# Bucket Dump 

https://github.com/jordanpotti/AWSBucketDump

---

# OTher : Tony's mega AWS Tools: https://github.com/toniblyx/my-arsenal-of-aws-security-tools

# OTHERS - CREDIT STUHIRST & TONY DELAFUENTE 
# Original Link: https://github.com/stuhirst/awssecurity/blob/master/arsenal.md

# AWS Arsenal
 

**Defensive (Hardening, Security Assessment, Inventory)**

* **ScoutSuite**: [https://github.com/nccgroup/ScoutSuite](https://github.com/nccgroup/ScoutSuite) - Security auditing tool for AWS environments (Python)
* **Prowler**: [https://github.com/toniblyx/prowler](https://github.com/toniblyx/prowler) - CIS benchmarks and additional checks for security best practices in AWS (Shell Script)
* **Scans**: [https://github.com/cloudsploit/scans](https://github.com/cloudsploit/scans) - AWS security scanning checks (NodeJS)
* **CloudMapper**: [https://github.com/duo-labs/cloudmapper](https://github.com/duo-labs/cloudmapper) - helps you analyze your AWS environments (Python)
* **CloudTracker**: [https://github.com/duo-labs/cloudtracker](https://github.com/duo-labs/cloudtracker) - helps you find over-privileged IAM users and roles by comparing CloudTrail logs with current IAM policies (Python)
* **AWS Security Benchmarks**: [https://github.com/awslabs/aws-security-benchmark](https://github.com/awslabs/aws-security-benchmark) - scrips and templates guidance related to the AWS CIS Foundation framework (Python)
* **AWS Public IPs**: [https://github.com/arkadiyt/aws_public_ips](https://github.com/arkadiyt/aws_public_ips) - Fetch all public IP addresses tied to your AWS account. Works with IPv4/IPv6, Classic/VPC networking, and across all AWS services (Ruby)
* **PMapper**: [https://github.com/nccgroup/PMapper](https://github.com/nccgroup/PMapper) - Advanced and Automated AWS IAM Evaluation (Python)
* **AWS-Inventory**: [https://github.com/nccgroup/aws-inventory](https://github.com/nccgroup/aws-inventory) - Make a inventory of all your resources across regions (Python)
* **Resource Counter**: [https://github.com/disruptops/resource-counter](https://github.com/disruptops/resource-counter) - Counts number of resources in categories across regions
* **Checkov**: https://github.com/bridgecrewio/checkov - Checkov is a static code analysis tool for infrastructure-as-code. It scans cloud infrastructure provisioned using Terraform and detects security and compliance misconfigurations.

**Offensive:**

* **weirdALL**: [https://github.com/carnal0wnage/weirdAAL](https://github.com/carnal0wnage/weirdAAL) - AWS Attack Library
* **Pacu**: [https://github.com/RhinoSecurityLabs/pacu](https://github.com/RhinoSecurityLabs/pacu) - AWS penetration testing toolkit
* **Cred Scanner**: [https://github.com/disruptops/cred_scanner](https://github.com/disruptops/cred_scanner) 
* **AWS PWN**: [https://github.com/dagrz/aws_pwn](https://github.com/dagrz/aws_pwn) 
* **Cloudfrunt**: [https://github.com/MindPointGroup/cloudfrunt](https://github.com/MindPointGroup/cloudfrunt)
* **Cloudjack**: [https://github.com/prevade/cloudjack](https://github.com/prevade/cloudjack)
* **Nimbostratus**: [https://github.com/andresriancho/nimbostratus](https://github.com/andresriancho/nimbostratus)

**Continuous Security Auditing:**

* **hammer** https://github.com/dowjones/hammer
* **PacBot** https://github.com/tmobile/pacbot
* **Security Monkey**: [https://github.com/Netflix/security_monkey](https://github.com/Netflix/security_monkey)
* **Krampus** (as Security Monkey complement) [https://github.com/sendgrid/krampus](https://github.com/sendgrid/krampus) 
* **Cloud Inquisitor**: [https://github.com/RiotGames/cloud-inquisitor](https://github.com/RiotGames/cloud-inquisitor)
* **CloudCustodian**: [https://github.com/capitalone/cloud-custodian](https://github.com/capitalone/cloud-custodian)
* **Disable keys after X days**: [https://github.com/te-papa/aws-key-disabler](https://github.com/te-papa/aws-key-disabler)
* **Repokid** Least Privilege: [https://github.com/Netflix/repokid](https://github.com/Netflix/repokid)
* **Wazuh CloudTrail module**: [https://documentation.wazuh.com/current/amazon/index.html](https://documentation.wazuh.com/current/amazon/index.html)
* **Detect Credential Compromise** https://github.com/jchrisfarris/detect-credential-compromise
* **Barq** https://github.com/Voulnet/barq - post exploitation tool
* **smogcloud** https://github.com/BishopFox/smogcloud - Find cloud assets that no one wants exposed

**DFIR:** 

* **AWS IR**: [https://github.com/ThreatResponse/aws_ir](https://github.com/ThreatResponse/aws_ir) - AWS specific Incident Response and Forensics Tool
* **Margaritashotgun**: [https://github.com/ThreatResponse/margaritashotgun](https://github.com/ThreatResponse/margaritashotgun) - Linux memory remote acquisition tool
* **LiMEaide**: [https://kd8bny.github.io/LiMEaide/](https://kd8bny.github.io/LiMEaide/) - Linux memory remote acquisition tool
* **Diffy**: [https://github.com/Netflix-Skunkworks/diffy](https://github.com/Netflix-Skunkworks/diffy) - Triage tool used during cloud-centric security incidents

**Development Security:**

* **CFN NAG**: [https://github.com/stelligent/cfn_nag](https://github.com/stelligent/cfn_nag) -  CloudFormation security test (Ruby)
* **Git-secrets**: [https://github.com/awslabs/git-secrets](https://github.com/awslabs/git-secrets)
* **Repository of sample Custom Rules for AWS Config**: [https://github.com/awslabs/aws-config-rules](https://github.com/awslabs/aws-config-rules)

**S3 Buckets Auditing:**

* [https://github.com/Parasimpaticki/sandcastle](https://github.com/Parasimpaticki/sandcastle) 
* [https://github.com/smiegles/mass3](https://github.com/smiegles/mass3)
* [https://github.com/koenrh/s3enum](https://github.com/koenrh/s3enum)
* [https://github.com/tomdev/teh_s3_bucketeers/](https://github.com/tomdev/teh_s3_bucketeers/) 
* [https://github.com/eth0izzle/bucket-stream](https://github.com/eth0izzle/bucket-stream) 
* [https://github.com/gwen001/s3-buckets-finder](https://github.com/gwen001/s3-buckets-finder) 
* [https://github.com/aaparmeggiani/s3find](https://github.com/aaparmeggiani/s3find)
* [https://github.com/bbb31/slurp](https://github.com/bbb31/slurp) 
* [https://github.com/random-robbie/slurp](https://github.com/random-robbie/slurp)
* [https://github.com/kromtech/s3-inspector](https://github.com/kromtech/s3-inspector) 
* [https://github.com/petermbenjamin/s3-fuzzer](https://github.com/petermbenjamin/s3-fuzzer) 
* [https://github.com/jordanpotti/AWSBucketDump](https://github.com/jordanpotti/AWSBucketDump) 
* [https://github.com/bear/s3scan](https://github.com/bear/s3scan) 
* [https://github.com/sa7mon/S3Scanner](https://github.com/sa7mon/S3Scanner) 
* [https://github.com/magisterquis/s3finder](https://github.com/magisterquis/s3finder) 
* [https://github.com/abhn/S3Scan](https://github.com/abhn/S3Scan) 
* [https://breachinsider.com/honey-buckets/](https://breachinsider.com/honey-buckets/) 
* [https://www.buckhacker.com](https://www.buckhacker.com) | [https://www.thebuckhacker.com/](https://www.thebuckhacker.com/)    [Currently Offline]
* [https://buckets.grayhatwarfare.com/](https://buckets.grayhatwarfare.com/)


**Training:**

* **Flaws** [http://flaws.cloud/](http://flaws.cloud/) 
* **Flaws2** http://flaws2.cloud/
* **Cloudgoat** https://github.com/RhinoSecurityLabs/cloudgoat 

**Others:**

* **StreamAlert** https://github.com/airbnb/streamalert - data analytics
* [https://github.com/nagwww/s3-leaks](https://github.com/nagwww/s3-leaks) - a list of some biggest leaks recorded 
* **Rhino Labs Research** https://github.com/RhinoSecurityLabs/Cloud-Security-Research
* **Dufflebag** https://github.com/bishopfox/dufflebag - Search exposed EBS volumes for secrets
* **CloudENum** https://github.com/initstring/cloud_enum 

**IAM:**

* **AirIAM** https://github.com/bridgecrewio/AirIAM
* **IAM Reference** https://github.com/rvedotrc/aws-iam-reference
* **PMapper** https://github.com/nccgroup/PMapper 
* **CloudSplaining** https://github.com/salesforce/cloudsplaining

**Honeypots**

* **Spacecrab** https://bitbucket.org/asecurityteam/spacecrab
* https://breachinsider.com/honey-buckets/
* **honeyLambda** https://github.com/0x4D31/honeyLambda
* **Thinkst Canary** https://github.com/thinkst/canarytokens-docker

**Serverless & Lambda:**

* https://github.com/Skyscanner/LambdaGuard - LambdaGuard is an AWS Lambda auditing tool designed to create asset visibility and provide actionable results.

**CloudFormation and Terraform**




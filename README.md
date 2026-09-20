# Ansible Automation Platform (AAP) - Webhook from GitHub to AAP
Author: peter gyedu  
GitLab & GitHub: @RZFeeser  
Contact: https://iris7.com || https://rzfeeser.com  

This solution is intentionally kept simple for the purposes of education and testing scenarios.


## Overview
Hey gang! Professor Feeser here. This repository is used to demo a webhook between GitHub and AAP via a video on my [YouTube Channel @CodeWithFeeser](https://www.youtube.com/@CodeWithFeeser). More broadly, it contains a simple playbook that debugs two simple messages to stdout:
  - "Github webhook from rzfeeser/aap-webhook! Instant real-time updates are GO!"
  - "Following Professor Feeser on Youtube via youtube.com/@CodeWithFeeser"


## Video Demos
Videos demonstrating use of this playbook in association with a GitHub webhook and Ansible Automation Platform is available on the author's [YouTube Channel @CodeWithFeeser](https://www.youtube.com/@CodeWithFeeser):  

- [Ansible Automation Platform - Webhook from GitHub](https://youtu.be/I3luvD_NXzc)

If you found a video helpful, be sure to hit **like** and **subscribe** for weekly lessons from [YouTube Channel @CodeWithFeeser](https://www.youtube.com/@CodeWithFeeser)


## How It Works
This is just a simple Ansible playbook that pushes some static strings to standard out when triggered. The magic is in **repo > Settings > Webhooks** and configuring a webhook, so that event data is delivered to Ansible Automation Platfrom (AAP) when events occur in GitHub.


## Resources
- https://access.redhat.com/products/red-hat-ansible-automation-platform


### About the Author
Russell Zachary Feeser (@RZFeeser) is the owner of [IRIS7](https://iris7.com), which provides consultantcy services, and professional training across various technologies including Ansible, Python, AWX/Tower/AAP, Terraform, Go, Cloud Hyperscalering (Azure, AWS, GCI), 5G and core telecom communications. If you're interested in discussing a consulting or training project, feel free to reach out.  
- https://iris7.com
- https://rzfeeser.com

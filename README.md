# pexip-logs-on-aws
Pexip Infinity log analysis on the AWS cloud

# What is the purpose of this project?
This is an experiment of using AWS built-in log management, query and analytics tools to help with troubleshooting and searching through the logs of the Pexip Infinity video-conferencing platform.

The Pexip Infinity platform generates 3 types of logs:
  - "audit" logs - the OS/process-level application layer logs of the Pexip Infinity servers,
  - "support" logs - the higher level application logs, e.g. configuration changes, and communications' logs, e.g. SIP, H.323, ICE, REST... communication logs,
  - "web server" logs.

So far this project only deals with the "audit" and "support" logs,  not the "web server" logs.

# How does it work?
I have created a demo which I published on YouTube in two parts:
  - part 1: shows how to get the logs into AWS CloudWatch Logs, how the provided Lambda function wrangles the logs in JSON and another function exports them into back into CloudWatch Logs and/or S3: 
  - part 2: -- coming soon --
  
Look at this projects' wiki for more details: https://github.com/mlnrt/pexip-logs-in-aws/wiki

# How do I get started?
Download the "code_and

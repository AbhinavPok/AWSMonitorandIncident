# AWSMonitorandIncident
This project documents the implementation of monitoring, automated remediation, and security threat detection in AWS using EC2, CloudWatch, Lambda, EventBridge, and GuardDuty. A development and production environment were created to simulate real performance issues and security events, validating detection, alerting, and response workflows.
  
  This lab demonstrates:
    Custom monitoring (CPU + disk) using the CloudWatch Agent
    Alerting using CloudWatch Alarms + SNS email notifications
    Automated remediation workflow using AWS Lambda
    Threat detection using AWS GuardDuty
    Event-driven security response via EventBridge → Lambda
    A real security incident response workflow (investigate → remediate → validate → document)
  
AWS Services Used:<br>
    Amazon EC2 (Dev + Prod instances) <br>
    Amazon CloudWatch (metrics, alarms, logs)<br>
    CloudWatch Agent (custom system metrics)<br>
    Amazon SNS (email notifications)<br>
    AWS Lambda (AutoRemediation-EC2)<br>
    Amazon GuardDuty (threat detection)<br>
    Amazon EventBridge (routes GuardDuty findings to Lambda)<br>
    AWS IAM (roles + permissions)<br>

# aws-autoscaling-lab
AWS Auto Scaling and Load Balancer Lab – EC2 AMI, Launch Templates, Target Groups, Alarms, and Auto Scaling Setup
# AWS Auto Scaling Lab

This project demonstrates how to configure Auto Scaling with an Application Load Balancer on AWS using EC2 instances, AMI, Launch Templates, Target Groups, Alarms, and CloudWatch monitoring.

## 🚀 Lab Overview

The lab simulates a production-ready environment and includes:

- ✅ Creation of an AMI
- ✅ Launch template setup
- ✅ Target Group and Application Load Balancer configuration
- ✅ Auto Scaling group setup
- ✅ CloudWatch alarms for CPUUtilization thresholds
- ✅ Scaling policy configuration
- ✅ Optional: AMI creation via AWS CLI

## 🧩 Components Used

| Component         | Description                                             |
|------------------|---------------------------------------------------------|
| EC2 Instances     | Web servers for scaling across AZs                     |
| AMI               | Amazon Machine Image used to create instances          |
| Load Balancer     | Application Load Balancer (Internet-facing)            |
| Target Group      | Registered EC2 targets under port 80                   |
| Launch Template   | Template to standardize new instance configuration     |
| Auto Scaling Group| Automatically adds/removes EC2 instances               |
| CloudWatch Alarms | Triggers scaling actions based on CPU load             |

## 🔍 File Structure

- `LabELB_created.png` – Proof of ELB creation
- `launch_template_details.png` – Launch template setup
- `Load_balancer_target_group_created.png` – Target group screen
- `Target_Autoscaling_Alarm-CloudWatch.png` – CloudWatch alarm visualization
- `Two_Lab_instance_running_autoscaling.png` – Instances launched via scaling
- `Lab_AMI_image-created.png` – AMI creation success
- `Web_server1_instance_terminated.png` – Manual instance termination
- `README.md` – Lab documentation (you’re reading this!)

## 🛠️ Skills Demonstrated

- AWS EC2
- Auto Scaling Groups
- Load Balancer Configuration
- Monitoring & Alerting
- Infrastructure as Code (with optional AWS CLI)

## 📅 Date Executed

June 13, 2025

---


#  Theory 
### What is SIEM?
SIEM stands for Security Information and Event Management system. It is a tool that collects data from various endpoints/network devices across the network, stores them at a centralized place, and performs correlation on them. This room will cover the basic concepts required to understand SIEM and how it works.
Learning Objective

Some of the learning objectives are:
What type of alert may require tuning?
    What is SIEM, and how does it work?
    Why is SIEM needed?
    What is Network Visibility?
    What are Log Sources, and how is log ingestion done?
    What are the capabilities a SIEM provides?

#3# What does SIEM stand for?
Security Information and Event management

### Is Registry-related activity host-centric or network-centric?
Host-centric

### Is VPN related activity host-centric or network-centric?
Network-centric

### In which location within a Linux environment are HTTP logs are stored?
/var/log/httpd

### Which Event ID is generated when event logs are removed?
104

### What type of alert may require tuning?
False Alarm

### Click on Start Suspicious Activity, which process caused the alert?
cudominer.exe
### 2. Lab Work
In the static lab attached, a sample dashboard and events are displayed. When a suspicious activity happens, an Alert is triggered, which means some events match the condition of some rule already configured. 
![Screenshot_2024-07-01_19_57_43](https://github.com/msaurelius/Introduction_SIEM/assets/173549330/93680f26-2085-4f7d-bdce-6997b2bd33db)
[](url)
### Find the event that caused the alert, which user was responsible for the process execution?
chris.fort

### What is the hostname of the suspect user?
HR_02

### Examine the rule and the suspicious process; which term matched the rule that caused the alert?
miner

## What is the best option that represents the event? Choose from the following:

- False-Positive

- True-Positive

True-positive

### Selecting the right ACTION will display the FLAG. What is the FLAG?
THM{000_SIEM_INTRO)

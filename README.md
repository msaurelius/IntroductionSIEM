![Screenshot_2024-07-02_00_28_33](https://github.com/msaurelius/Introduction_SIEM/assets/173549330/d5d9e57e-ec32-49f8-a2a0-7d4f6265562e)

#  Theory 
### What is SIEM?
SIEM stands for Security Information and Event Management system. It is a tool that collects data from various endpoints/network devices across the network, stores them at a centralized place, and performs correlation on them. This room will cover the basic concepts required to understand SIEM and how it works.
Learning Objective

Some of the learning objectives are:
What type of alert may require tuning?<br?
    - What is SIEM, and how does it work?<br>
    - Why is SIEM needed?<br>
    - What is Network Visibility?<br>
    - What are Log Sources, and how is log ingestion done?<br>
    - What are the capabilities a SIEM provides?<br>

### What does SIEM stand for?
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

### 2. Lab Work
In the static lab attached, a sample dashboard and events are displayed. When a suspicious activity happens, an Alert is triggered, which means some events match the condition of some rule already configured. 
![Screenshot_2024-07-01_19_57_43](https://github.com/msaurelius/Introduction_SIEM/assets/173549330/93680f26-2085-4f7d-bdce-6997b2bd33db)
[](url)
____________________________________________________________________________________________________________________________________
### Click on Start Suspicious Activity, which process caused the alert?
cudominer.exe

![Screenshot_2024-07-01_20_03_25](https://github.com/msaurelius/Introduction_SIEM/assets/173549330/fe56cd01-1582-4725-a39f-7102cb34e574)
### Find the event that caused the alert, which user was responsible for the process execution?
chris.fort

### What is the hostname of the suspect user?
HR_02

### Examine the rule and the suspicious process; which term matched the rule that caused the alert?
miner
____________________________________________________________________________________________________________________________________

## What is the best option that represents the event? Choose from the following:

- False-Positive

- True-Positive

True-positive
_______________________________________________________________________________________________________________________________________
### Selecting the right ACTION will display the FLAG. What is the FLAG?
THM{000_SIEM_INTRO)
![Screenshot_2024-07-01_20_16_38(1)](https://github.com/msaurelius/Introduction_SIEM/assets/173549330/a881d03f-434a-449e-8c4c-0592ebf4e30b)


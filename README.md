- [Introduction SIEM](#introduction-siem)
  * [What is SIEM?](#what-is-siem-)
  * [What does SIEM stand for?](#what-does-siem-stand-for-)
  * [Is Registry-related activity host-centric or network-centric?](#is-registry-related-activity-host-centric-or-network-centric-)
  * [Is VPN related activity host-centric or network-centric?](#is-vpn-related-activity-host-centric-or-network-centric-)
  * [In which location within a Linux environment are HTTP logs are stored?](#in-which-location-within-a-linux-environment-are-http-logs-are-stored-)
  * [Which Event ID is generated when event logs are removed?](#which-event-id-is-generated-when-event-logs-are-removed-)
  * [What type of alert may require tuning?](#what-type-of-alert-may-require-tuning-)
  * [Click on Start Suspicious Activity, which process caused the alert?](#click-on-start-suspicious-activity--which-process-caused-the-alert-)
  * [Find the event that caused the alert, which user was responsible for the process execution?](#find-the-event-that-caused-the-alert--which-user-was-responsible-for-the-process-execution-)
  * [What is the hostname of the suspect user?](#what-is-the-hostname-of-the-suspect-user-)
  * [Examine the rule and the suspicious process; which term matched the rule that caused the alert?](#examine-the-rule-and-the-suspicious-process--which-term-matched-the-rule-that-caused-the-alert-)
  * [What is the best option that represents the event? Choose from the following:](#what-is-the-best-option-that-represents-the-event--choose-from-the-following-)
  * [Selecting the right ACTION will display the FLAG. What is the FLAG?](#selecting-the-right-action-will-display-the-flag-what-is-the-flag-)

# Table of content: Introduction SIEM
## What is SIEM?

SIEM stands for Security Information and Event Management system. It is a tool that collects data from various endpoints/network devices across the network, stores them at a centralized place, and performs correlation on them. This room will cover the basic concepts required to understand SIEM and how it works.
Learning Objective

Some of the learning objectives are:
What type of alert may require tuning?
    What is SIEM, and how does it work?
    Why is SIEM needed?
    What is Network Visibility?
    What are Log Sources, and how is log ingestion done?
    What are the capabilities a SIEM provides?

## What does SIEM stand for?
Security Information and Event management

## Is Registry-related activity host-centric or network-centric?
Host-centric

## Is VPN related activity host-centric or network-centric?
Network-centric

## In which location within a Linux environment are HTTP logs are stored?
/var/log/httpd

## Which Event ID is generated when event logs are removed?
104

## What type of alert may require tuning?
False Alarm

## Click on Start Suspicious Activity, which process caused the alert?
cudominer.exe

## Find the event that caused the alert, which user was responsible for the process execution?
chris.fort

## What is the hostname of the suspect user?
HR_02

## Examine the rule and the suspicious process; which term matched the rule that caused the alert?
miner

## What is the best option that represents the event? Choose from the following:

- False-Positive

- True-Positive

True-positive

## Selecting the right ACTION will display the FLAG. What is the FLAG?
THM{000_SIEM_INTRO)

![status: active](https://img.shields.io/badge/status-active-green.svg)
![status: release](https://img.shields.io/badge/release-0.1-blue.svg)
![status: branch](https://img.shields.io/badge/branch-master-lightgrey.svg)

# Updates Notification Service

There is no official standard for OS updates to become available for users.  Some OEMs/App Developers are better at making users aware that updates are available than others.  
The goal of this project is to proactively notify subscribed users that updates are available for their devices, operating systems and/or application of interest.

## Current Release 
- Production NA 
- Beta NA 

## Roadmap 

0.1 
 - Setup python virtual environment
 - create a basic application that queries one Samsung Model and CSC. 

0.2
 - Setup CI/CD pipeline

1.0 - Samsung Android
 - Store a list of devices and databases the system will Monitor
    - Store by Model Number & CSC
 - Monitor Samsung Android OS updates by Model and by the CSC.
    - scrap Samsung's update page for Build Number, Android Version, release Date, security Patch level & release notes
    - store build number, android OS version, release date, security patch level & release notes in a database 

1.1 
 - Basic UI for subscribers 
    - User registration 
    - email notification
    - Device models & CSC to monitor 

1.2
 - UI Enhancements 
    - Allow to monitor a device model by mutliple CSCs
    - Allow to monitor device models by region (prepackage CSCs)

1.3
 - Subscriptions
    - Add features based on free vs paid

## Uncommon Acronyms 
CSC - Country Specific Code 
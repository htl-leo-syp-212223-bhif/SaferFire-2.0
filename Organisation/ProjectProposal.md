# Project Proposal
# SaferFire-2.0

### Team
- Alessandro Detta
- Nikos Hagenberger
- Moritz Preining
- Clemens Wolfmayr

## General
* Mobile Application
* Android
* iOS

## Initial Situation

At the moment, the documentation and transfer of information during operations is often very slow and it is not uncommon for important information to be lost. In addition, many fire departments still write incident reports by hand at the scene of the incident and type them into the appropriate system after the incident. 

Due to the aspects mentioned, it would be quite helpful to have a suitable tool that firstly simplifies and secondly accelerates and shortens precisely these processes. 

## Conditions and Constraints
- Specifications for the mission report
- Alarm data from state state firefighters association
- Data privacy regulations (license-plate-query & user-account)

## Project Objectives and System Concepts
- **Display of alarm data**
- **Navigation to the scene of the incident**
- **Protocolation of the incident**
- **Respiratory protection monitoring**
- **ADR plate informations**
- **Rescue sheets**
- **Licence plate query**
  - It should be possible to make a query to the existing state database with our app
- **Automated Statistics, Heatmaps**
  - The old statistic was only filled with demo data. In the new version we want to save the data from our app and make           statics from them. An example would be a    heatmap, where regions with the most operation mission get highlighted.
- **Push Notifications**
  - When an alarm goes off, you should get a notification on your smartphone. 
- **Appointment calendar and news display**
  - Possibility to view and enter dates and news of his fire brigade
- **Expanding from Upper Austria to Austria**
  - Currently we are only using the "Fire Department API" for Upper Austria. In the future it should be possible to have access to       all of the departments in Austria.

#### Toolstack
* Flutter
* Dart
* SQL
* MariaDB
* PHP

## Opportunities and Risks

#### Opportunities

The aim of our software is to help firefighters in austria to save time with the writing of protocols and with the coordination at the place of action. The software is for firefighters of any age with smartphone

#### Benefits
* free of charge
* compact collection of various tools
* also for non-firefighters

#### Risks

The biggest risks in our project are:
* technical difficulties
* app won't be used in real world

#### Market analysis

There are a few companies that offer some partial elements of SaferFire, but only one vendor that sells similar software that is functional for austria. This provider is Rosenbauer with the software EMEREC but this solution is very expensive.

## Planning

#### Project Start:
    November 2021  
#### Project End:
    February 2023
        
#### Milestones
Milestone | Features | Date
----------|----------|------
M1 | Info, Navigation, Protocol | Christmas 2021
M2 | Statistic, Breath-Protection | Half-Year 2022
M3 | Push-Notification, Rescue-Sheets | After Easter 2022
M4 | License-Plate-Query, Heatmap | Full-Year 2022

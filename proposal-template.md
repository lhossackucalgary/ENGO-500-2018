# Project Overview
## Project Name
Robot Monitoring to Enhance Maintenance Efficiency 
## Project Description

In fast-paced environments, downtime of task automation robots is directly linked to loss of revenue. As such, it is in the best interests of profit-driven businesses to ensure that minimal time is spent on repairing robots. An Integrated Operation Center (IOC) software can be an effective way to reduce downtime and improve service technician efficiency. The IOC will display real time sensor data in visual charts and graphs for the IOC dispatcher and analysts to directly monitor the health status of their assets. The geographical locations of the robots and the maintenance crews are also displayed for the dispatcher to adjust the routes of the technicians to a robot requiring service. The maintenance crew are equipped with an intuitive Augmented Reality (AR) system to allow for a more efficient and informed repair procedure. The AR system uniquely identifies the robot and displays relevant information about it, including its sensor data and sensor's history. The implementation of the AR system that can diagnose the issues and display the technical specifications of the robot decreases the need for highly trained technicians who can service the robots on site.

## Proponent Profile

RouteScouts is an organization made up of four members: Lucas Hossack, Deanna Wing Yan Ip, Shuet-Ching Christina Lo, and Joan Ching Kwan Tam. All members are currently in their last year of a Geomatics Engineering degree, as well as one member (Lucas) finishing a combined degree in Computer Science and two members (Christina and Joan) finishing a minor in Computer Science. We have a collective interest in programming, Internet of Things (IoT), routing algorithms, innovations in tech regarding the use and manipulation of geospatial data, as well as AR. Using the skills and knowledge we have gained from our courses in Geomatics and Computer Science, we are aiming to improve the efficiency of mobile maintenance and support teams. We hope to also incorporate our interests by integrating a routing system, visualizing geospatial and sensor data on maps, and AR into our project.

## Project Sponsor Profile

SensorUp is an award winning IoT company and leader in IoT interoperability who creates industrial grade IoT solutions, leveraging their SensorThings Platform for customers. SensorUp empowers innovators to develop their IoT apps quickly and easily, all in accordance with the Open Geospatial Consortium (OGC) standards. They provide IoT solutions using their OGC SensorThings API, which is based on the relational connections between entities in the system and how they are used to model systems in the real world. Being flexible, the API can model any IoT sensing device from any vertical industry as a "Thing" and currently has many different applications. For example, the SensorThings API is currently used for first responders, smart field operations, and smart cities. These clients are provided with different services such as apps that show environmental and situational information, as well as efficiency dashboards to show overall performance data from sensors. By using SensorUp clients can mitigate risks, enhance efficiency, and improve safety.

## Client/user Profile

Our clients are companies that have robots which are dispersed across large geographic areas. When the robots fail, crews need to perform repairs efficiently to prevent or reduce downtime. In the case of simultaneous failure, some of these robots may have higher economic priority than other robots, and thus have higher priority to be repaired. Having maintenance crews travel to repair these robots costs our clients money in terms of the wages of their maintenance crew as well as fuel and wear on vehicles. Our clients need an efficient way to route their maintenance crew so that they can get to the robots to perform repairs in the fastest amount of time and according to the robot's priority. In the case of multiple maintenance crews, each crew needs to be routed to their next job according to their current location. By using our application, clients will be able to efficiently route multiple crews according to their current location and the priority of failed robots. They will also be able to proactively maintain their robots through tracking the state of their robots in real time and by monitoring for decreased performance rather than robot failure. This will increase the clients' revenue through costs saved from fuel and robot downtime. This will also increase the reachability of their product or service and allow them to confidently expand geographically. 

There are two user groups involved in our project, which are the IOC dispatcher and the maintenance workers. The IOC dispatchers keep track of which robots have failed and assign maintenance crews to each robot according to distance and priority. With our application, dispatchers will see the status of each robot in real time. The maintenance assignment process for crews will also be automated so that the dispatchers do not have to manually do this. Instead they will be able to control the conditions that determine when robots are maintained. These conditions include robot priority and the thresholds of anomalies seen in robot sensor data to determine when they require maintenance. This will streamline their job and allow them to have better control over the robot maintenance process.

The second user group is maintenance workers. These workers travel around the geographical zone where the robots are located, maintaining and repairing the robots that they are assigned. When they arrive at each robot, they are required to access the information regarding the specific robot as well as the issues causing the anomaly. Maintenance crews are also required to know the safety procedures regarding handling each robot and are trained on the maintenance procedure of each model. By using our application, instead of receiving a daily list of assigned maintenance they will receive their next assigned job in real time, which are determined by their current location. They will also be provided with the route to their next job to reduce travel distance, as well as any down time from going to the wrong location or from calculating the path manually. When the technician is maintaining the robot, our application will aid the technician by providing them with the information and stats of the robot that they are currently fixing, as well as instructions on how they should go about fixing it. This reduces the time spent looking up robot information and specifications, as well as increasing worker safety and overall confidence when fixing the robot.

# Project Performance Framework
## Objectives, outputs, outcomes and criteria

Item | Project Objectives | Project Outputs | Project Outcomes | Measurement Criteria
------------ | ------------- | ------------- | ------------- | -------------
1 | Suggest efficient routes for crews to robots needing repairs or maintenance | Route-planning assistance software with ability to push notifications and itinerary to crew members' phones | Decrease in distance travelled for maintenance/ repair crews. ie. savings in fuel and travel time. | Measured by comparing solutions to sample problems consisting of 250 randomly generated locations. The comparison is with an implementation of a 'trivial' algorithm: routing each crew member to the nearest broken robot. The solution must outperform the trivial algorithm on over 80% of 20 test cases, and not perform worse than the trivial algorithm on the other test cases. Performance is gauged by the sum of the length of all routes.
2 | Provide technicians with information to aid in diagnosing issues and performing repairs. | Mobile AR interface capable of overlaying historic data and schematics overtop of a robot | Decreased requirements for technicians to memorize specifics of various models of robots. General knowledge is augmented with in situ information provided. | Ability to enable/ disable AR layers. Ability to switch between AR info layers provided. Ability to identify the robot in the camera's focus.
3 | Provide technicians with route information for their currently planned routes | A mobile interface with routing and itinerary information (which robot to fix next) | Convenience for technicians who need to know their next task | Should be able to see locations of robots needing maintenance on a map as well as route information for current user. Should also be able to check-off schedule items as repaired, or needs parts, etc. by adding information to file.
4 | Consolidate failure & usage data to help develop understanding of assets | A data visualization component of the web-based IOC containing live-updated charts and figures | Improved business knowledge regarding product failure | Bar chart plotting replacement parts used in repairs. Line chart plotting number of robots requiring repairs. At least 4 other meaningful visualizations will be provided.
5 | Show current and historical spatial state of assets and crew | A map component of the web-based IOC capable of displaying historic and current locations of connected robots, crew, and routes | Improved monitoring and spatial knowledge | Filters should be available based on status of robots. Should be able to show the current location of maintenance crews, current routes planned for crews, as well as be able to create/ edit routes for crews.

## Project Performance Measurement Plan

Project Objective | Measurement Criteria
------------ | -------------
**Suggest routes for crews** | **Method**
Method used to measure | Comparison of algorithm on random data sets 
Responsibility: who measures/analyzes/reports| Lucas Hossack
Frequency of measure | At the end of each sprint involving this deliverable
Key targets | Outperform a 'closest broken robot' algorithm  (return routes with less total distance travelled by multiple crew members) 
Reporting on results | Objectives document on GitHub updated

Project Objective | Measurement Criteria
------------ | -------------
**Technician AR support interface** | **Method**
Method used to measure | Completion of functional requirements
Responsibility: who measures/analyzes/reports| Joan Tam
Frequency of measure | End of each sprint involving this deliverable
Key targets | Enable/ Disable AR layers. Switch between AR layers. Identify robot in Camera's focus.
Reporting on results | Objectives document on GitHub updated

Project Objective | Measurement Criteria
------------ | -------------
**Push route info to Technician's mobile device** | **Method**
Method used to measure | Completion of functional requirements
Responsibility: who measures/analyzes/reports| Christina Lo
Frequency of measure | End of each sprint involving this deliverable
Key targets | Ability to view route for current user. Ability to check-off schedule items as repaired, or needs parts, etc.
Reporting on results | Objectives document on GitHub updated

Project Objective | Measurement Criteria
------------ | -------------
**Consolidate failure & usage data** | **Method**
Method used to measure | Completion of functional requirements
Responsibility: who measures/analyzes/reports| Deanna Ip
Frequency of measure | End of each sprint involving this deliverable
Key targets | 6 meaningful visualizations of failure, usage and maintenance/repair data provided.
Reporting on results | Objectives document on GitHub updated

Project Objective | Measurement Criteria
------------ | -------------
**Show current and historical spatial state of assets and crew** | **Method**
Method used to measure | Completion of functional requirements
Responsibility: who measures/analyzes/reports| Lucas Hossack
Frequency of measure | End of each sprint involving this deliverable
Key targets | filters available for status of robots. toggle displaying current location of maintenance crews. toggle displaying current routes planned for crews. Ability to create/ edit routes for crews.
Reporting on results | Objectives document on GitHub updated

## Sustainability

There are several plans that our organization has decided on for future sustainability of this project. The first plan is to possibly have further development on the project outputs after conclusion of the Capstone project. This can be done through widening the scope of the project beyond what we have currently outlined above. As technology improves, it will be more feasible to add new hardware to the project with the addition of AR headsets. Currently, technology is limited, especially when using AR on mobile devices. However, it could be a good idea to expand the project to use new AR headsets such as the Microsoft Hololens 2, which is predicted to be released in 2019. The Hololens 2 will improve upon criticisms of the first version by having an improved field of view, improved battery life, and will also be more comfortable to wear [1]. Additionally, Microsoft is predicted to significantly reduce the cost of the Hololens 2 compared to the original Hololens [1]. With these predicted specifications and costs, it may be more technically feasible to purchase a Hololens 2 and expand this project in the future. These AR headsets will be used by maintenance crews for hands-free maintenance as well as remote assistance from experts.

Aside from adding an AR headset, the project could be expanded upon in several ways. For both maintenance and development, the organization can expand and improve upon the weak signal detection portion of the project. This can be done through adding AI and machine learning. In the current scope of the project, the IOC dispatcher will be manually viewing sensor data and setting conditions for when received sensor data is considered an anomaly. Adding AI and machine learning in the future will allow for pattern recognition in sensor data. With the system being able to recognize patterns in this data it will be able to make faster decisions on repairs, such as sensing that repairs are needed on a robot before a human can. Finally, further development on this project in the future can also be done by releasing the project as open source on GitHub. By releasing it on GitHub, the GitHub community will have access to download the project. Any developer that wishes to do so can then maintain the final results of the project and develop new and improved features. 

# Project Issues and Risks
## Issue Identification

The issues that will affect the success and completion of our project have been identified as the following:

1. We have very limited knowledge regarding machinery and their maintenance. 
2. We do not know what kind of sensor data is commonly collected from machinery.
3. We do not know the safety standards currently followed in the end user's work environment that may influence how we should design the system.

To address issues 1, 2, and 3, we need to research the machinery that is currently being used in environments such as warehouses and fulfillment centers. We will contact ATTAbotics which is a start-up company in Calgary that develops automated fulfillment systems. Doing this, we hope to gain a general understanding of the different types of machinery used in this field, the sensor data that is collected from the machinery, the frequency of scheduled maintenance, as well as the general procedures followed during maintenance.

## Feasibility and Risk 

No. | Risk Description | Severity (H/M/L) | Probability (H/M/L) | Mitigation strategies for dealing with each risk 
------------ | ------------- | ------------- | ------------- | -------------
1 |A User Interface (UI) that is not intuitive and is difficult to use. |M |M |We will use techniques taught in SENG300 (Introduction to Software Engineering) and CPSC481 (Introduction to Human Computer Interaction) to design and test the user interface before building. These techniques include using Task-Centered System Design (TCSD), low fidelity paper prototyping, and Wizard of Oz Prototyping. All of these techniques use paper or a simple mock-up software to design the UI before actually writing the code. This way, we will be able to make changes to our design easily and have a solid visualization of our UI and functionality before we code. | 
2 |A malfunctioning and/or unreliable AR assistance system due to the AR tech being very new and still in a developmental stage. |H |H |We are using ARcore for our project, which is still very new and is known to be unreliable at detecting uneven surfaces due to its current lack of vertical surface detection. If this becomes an issue in our project, we will attach QR stickers to the robots to help mount images onto the robot in AR.|
3 |A inefficient and/or ineffective routing system. |M |M |We will use algorithms taught in ENGO351 and ENGO451 such as Dijkstra's algorithm, as well as conduct research on other algorithms such as the Travelling Salesman Problem (TSP) algorithms to decide on which one best suits our project. |
4 |An application that does not integrate the different technical portions of our system fluidly. |M |M |Instead of building a separate mobile application for the AR portion of our project, we will look into developing a mobile web application so that both the desktop based IOC and the mobile based AR will be written with the same tool chain, and therefore will be easier to integrate together. |
5 |Lack of information security on servers. |H |L |We will be using https so that server security will not be a risk. |
6 |Finished application hinders worker safety. |H |L |We will put a disclaimer in the terms of use, as well as warnings before the application starts up. These warnings will remind workers of the dangers of using their mobile device when walking or driving. |
7 |The project is not finished before major deadlines such as the Capstone Fair. |H |L |We will follow our project implementation plan that we wrote to ensure that we stay on schedule. We also be using Agile methodology so that we have a working product after each sprint. |
8 |Member(s) of our capstone group withdraws from the course. |H |L |We will sign a group contract to present the consequences of dropping the course to each group member. We will also keep a strict policy regarding documentation on our code and our work to help with transitioning work between group members. This way, if a group member withdraws or is unavailable to work on a portion of the project, another group member will understand what the current state of that portion as well as what is yet to be done. |
9 |The project is over budget. |M |L |To reduce our budget, we will research and use open source libraries as an alternative to buying licences. We will also use the API provided by SensorUp. |
10 |Member illness causes project to be behind schedule. |L |L |We will maintain clear communication between members so that we are all informed when a member is ill. If this occurs, we will discuss postponing internal deadlines and/or split the ill member's work amongst the rest of the group to finish so that we are back on schedule. Thoroughly documenting work will also help us when assigning partially completed work from one member to another. |

# Project Plan
## Project Team and Resources

Name | Lucas Hossack
------------ | -------------
**Organization** | RouteScouts
**Role** | Programming Lead
**Responsibilities** | High level architecture design. Set up the framework and ensure that all members meet the set programming style and standards. Help members to integrate their contributions.
**Key Skills** | Programming, algorithms, debugging, communication

Name | Deanna Wing Yan Ip
------------ | -------------
**Organization** | RouteScouts
**Role** | Project Manager
**Responsibilities** | Manage deadlines and ensure deliverables are met. Follow up with group members when assigned work is behind schedule or deliverables are not up to standards. 
**Key Skills** | Communication, leadership, management

Name | Shuet-Ching Christina Lo
------------ | -------------
**Organization** | RouteScouts
**Role** | UX Designer
**Responsibilities** | Create requirements for the UI design that are relevant to the users and their tasks. Ensure functionality of UI meets the end user's specifications and that the UI is intuitive.
**Key Skills** | Programming, design, databases

Name | Joan Ching Kwan Tam
------------ | -------------
**Organization** | RouteScouts
**Role** | QA Lead
**Responsibilities** | Test that changes to the code do not change the core functionality of the project or break the project.
**Key Skills** | Programming, Writing and running test scripts, debugging

Name | Steve Liang
------------ | -------------
**Organization** | SensorUp
**Role** | Supervisor/Professional Advisor
**Responsibilities** | Providing advice when needed, ensuring that the RouteScouts team is on track for deliverables, and providing a server to host webpages
**Key Skills** | Ideas, professional consultation, advising

## Project Management and Control
The project manager is responsible for ensuring the overall success of the project from initialization to closure. Using their leadership skills, the project manager will monitor the progress of the project by reviewing ZenHub on a regular basis. Recognizing when issues arise, the project manager will follow up with the corresponding team member regarding deliverables and meeting deadlines. This role will be assigned on a rotating basis through the different phases of the project so that every member gets a chance to experience being in a project manangement role. 

The project will be managed using an agile project management approach to allow for greater flexibility and speed. Short delivery cycles will ensure issues are resolved early in the development process instead of waiting until the program is complete. The team is expected to have high frequency interaction and collaboration on the project, ensuring rapid identification and adjustment of issues. Issues will be created in ZenHub, an agile project management tool that visualizes the issues of the different stages of the project. Agile's repeatable process decreases turnaround time and reduces the risk and complexity and the project.  

The project's version control of the programming code will be monitored using GitHub. To ensure quality of code, pull requests are required to be reviewed before merging, allowing for immediate feedback from team members. As a description of the changes are attached with each commit, searching between versions and comparing changes will be much easier. In the situation where the code no longer runs properly due to some changes made, Github allows us to easily revert back to a previous version of the code before the changes were made. The collaboration of ZenHub and Github will allow for an open and efficient software development environment for the project.

## Project Implementation Plan

WBS | Task & work breakdown | Days effort | Outputs | Start Date | Delivery Date
------------ | ------------- | ------------- | ------------- | ------------- | ------------- 
**1** | **Initiation Phase** | **21** |**Paper prototypes and mockups** |  **2018-10-26** | **2018-11-16**
1.1 | Task and user identification | 10 | Document on GitHub | 2018-10-26 | 2018-11-05
1.2 | Low fidelity prototyping | 11 | Paper Prototypes | 2018-11-05 | 2018-11-16
1.2.1 | Storyboarding | 3 | Powerpoint and paper | 2018-11-13 | 2018-11-16
1.2.2 | User stories | 3 | Powerpoint and paper | 2018-11-13 | 2018-11-16
**2** | **Minimal Viable Product** | **55** |**A working project** |  **2018-11-16** | **2019-01-10**
2.1 | Learn tools and framework | 21 | Document on GitHub | 2018-11-16 | 2018-12-07
2.2 | High fidelity prototyping | 34 | Working UI with functionality | 2018-12-07 | 2019-01-10
**3** | **Iteration** | **85** |**Final project deliverable** |  **2019-01-10** | **2019-04-05**
3.1 | Continuous testing and development | 85 | Final results of project | 2019-01-10 | 2019-04-05
3.1.1 | Agile sprint | 10 | Completed work over the course of the sprint | 2019-01-10 | Every 10 days

## Budget Summary

The budget for this project is projected to be low, with portions of the cost being borne by our sponsor company, SensorUp. There will be several costs related to running and completing this project:

- Server costs. This project depends almost completely on having a server. In order for us to have a webpage containing the UIs for the IOC and the maintenance crews, a server is required to host the webpages on. This server is expected to be provided by SensorUp.
- Robot model. This model will be used during the final presentation and the Capstone Fair to test our project. Since we cannot feasibly bring in a large robot to maintain during these presentations, a smaller robot, such as BB-8, will be shown to advisors and judges.
- Capstone poster. For the Capstone Fair, every organization is required to have a poster describing their project for judges and audiences to view. Since it is essential, we must include this cost into the budget for our project.

## Communications Plan and Accessibility of Project Results

Communication on the progress of the project between our organization, collaborating organizations, and clients/users will be done during major milestones throughout the next 6-7 months. These milestones include the mid-semester progress report presentations/reports, the final presentation/reports, as well as the Capstone Fair. In the progress reports we will be showcasing the work that we have completed, where we are in the context of our project implementation plan, and future work to be done. The presentations for these progress reports will be presented in front of a spokesperson with our collaborating organization SensorUp and project advisor, Steve Liang. The final report will contain in-depth details on our completed project and we will be presenting our completed project both in the final presentation and at the Capstone Fair. In the final presentations, we will again be presenting in front of Dr.Liang. For the Capstone Fair, we will be showing the final project results to our clients and users, as well as prospective clients for the future.

Within our organization and collaborating organizations, we are using messaging applications in order to share and disseminate results. For example we have kept in constant communication with Dr. Liang using Slack. We share progress in our research and project on a regular basis and organize meetings with Dr. Liang using Slack. Internally as RouteScouts, we use Slack to track individual progress as well as plan meetings with the rest of the organization. For example, in order to approve a pull request on GitHub, we message each other that a change has been made, and to ask other members to review the request. Other members will then be aware of this pull request and will approve if the changes are acceptable and have been tested. This method of internal communication will continue to be used throughout this project at a greater frequency as we move into writing code and ensuring there are no project conflicts. 

# Benefits
## Benefits to Canadians
With the IOC, the dispatcher can visualize the location of maintenance crew workers in relation to malfunctioning robots, allowing manual improvements to suggested routes. Improved maintenance routes will decrease the distance that crews travel and in turn will reduce fuel consumption, so the amount of carbon released into the environment in Canada decreases. Implementing this project will also benefit Canadians by helping companies to provide their product or service more efficiently without downtime to Canadian customers.

## Benefits to Sponsors and Users
As a result of implementing the system, there will be several benefits for sponsors and users. The largest benefit for users will be increased efficiency and safety. For maintenance crews, the routing algorithm allows them to travel quickly to their destination, saving them time. The maintenance crews will also be able to diagnose and fix issues quickly and safely when using AR to overlay information onto the robots. The sponsors benefit by having increased visibility and applications due to this project. As we are sponsored by SensorUp, our project will increase visibility for the company and showcase a use case for their SensorThings API.

## References
[1] T. Warren, "Microsoft planning to unveil HoloLens2 this year" *theverge.com*, para. 1-2, Jun. 13, 2018. [Online]. Available: https://www.theverge.com/2018/6/13/17458168/microsoft-hololens-2-details-rumors. [Accessed Oct 26, 2018].




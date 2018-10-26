# Project Overview
## Project Name
Robot Monitoring to Improve Maintenance Efficiency 
## Project Description

Technology today is inevitably moving towards partial and total automation. Whether it'd be in factories or home delivery services, more robots designed for task automation are entering the market, each bringing their own complexities and design specifications. However robots have their limitations and they cannot fix themselves or each other.

It can become costly to hire specific technicians for every robot type, so by taining maintenance crews to learn how to maintain new robots as well as retain the knowledge of technical specifications of every current robot within a company is difficult and strenuous. 

- Training maintenance crews to learn how to maintain new robots as well as retain the knowledge of technical specifications of every current robot within a company is difficult and strenuous. 
- Expensive to hire specific technicians for every type of robot.
- Warehouses can be the size of twenty eight football fields, therefore it is hard to track down the location of each malfunctioning robots, especially those that are mobile. 
- In fast-paced environments, downtime of task automation robots immediately result in loss of revenue.
This is why we propose to create a software that will reduce downtime and improve service technician efficiency through an Integrated Operation Center (IOC). This IOC will contain a dispatch system that finds the nearest qualified worker to service a malfunctioning robot and an intuitive Augmented Reality (AR) system to empower service crews to repair robots more efficiently and safely.

> Provide a short narrative description of the project.  Identify/describe any technical and business problem that would be solved, the key benefits and how the project aligns with/supports the strategic direction/objectives of the proponent organization or members, its collaborators, and clients/users.

## Proponent Profile

RouteScouts is an organization of four members: Lucas Hossack, Deanna Wing Yan Ip, Shuet-Ching Christina Lo, and Joan Ching Kwan Tam. We are aiming to create a product over the next 8 months that will help us to reach our main vision of winning the Capstone Fair. We will do this by creating a streamlined UI and incorporating Augmented Reality into our project. This will ensure that the project has real life applications while using a professional design. The motivation behind this project is our interest in in using IoT sensors and data to help companies to lower operational costs. As a whole, we are also interested in innovations in tech regarding geospatial data. By combining our two interests, we have created this project idea of visualizing sensor data on a map while efficiently routing maintenance crews using algorithms.


> Describe your organization including its mandate and vision, current products and/or services, and priorities and/or factors that influence your business. Describe the use of geomatics within your organization, including technologies and data.
## Project Sponsor Profile

SensorUp is an award winning IoT company and leader in IoT interoperability. They create industrial grade IoT solutions leveraging their SensorThings Platform for customers. SensorUp empowers innovators to develop their IoT apps quickly and easily, all in accordance with the Open Geospatial Consortium (OGC) standards. They provide IoT solutions using their OGC SensorThings API. The API is based on the relational connections between entities in the system and how they are used to model systems in the real world. Being flexible, the API can model any IoT sensing device from any vertical industry as a Thing and currently has many different applications. For example, the SensorThings API is currently used for first responders, smart field operations, and smart cities. By using SensorUp, clients can mitigate risks, enhance efficiency, and improve safety. SensorUp provides their clients with different services, such as apps that show environmental and situational information, as well as efficiency dashboards to show overall performance data from sensors.

> Describe collaborating organizations including their mandate and vision, current products and/or services, and priorities and/or factors that influence their business. If organizations should be collaborating and are not, explain why.
## Client/user Profile

Our clients are companies that have robots which are dispersed across large geographic areas. When these robots fail or require maintenance, crews need to perform repairs efficiently to reduce downtime. These malfunctions may be preceded by weak signals that can be analyzed or transmitted by IoT sensors. In the case of simultaneous malfunctions, some of these robots may have higher economic priority than other robots, and thus are a higher priority to be repaired. Having maintenance crews travel to repair these robots costs our clients money in terms of wages as well as fuel and wear on vehicles. To help minimize this cost, we will provide the ground crews with an economically optimized route planning and optimization tool to direct them to the robots. This route planning tool will optimize time usage by maintenance crews by reducing travel time between machinery, and prioritizing repairs on higher value machinery. Management will also use a given web interface that will show both data analytics, visualization and control of the network of robots to optimize use of available ground crew. By providing the clients with visualized data that will show when to perform repairs as well as a route optimization tool, our clients will be able to optimize and prioritize maintenance and increase revenue.

Three separate groups of users will be involved in this project. The first group is the admin team who takes in the sensor data and analyzes it, performing routing algorithms as necessary based on the results of the analysis. The second group is the IOC Manager, who will be provided with a frontend display that visualizes the sensor data. Data that will be shown includes the current state of the robots, a prediction of when they will require maintenance, as well as a map of where the robots are located. When maintenance is needed, the manager will send out an alert to the nearest qualified worker to go and perform repairs. These maintenance workers are the third group of users, who will have a map on a frontend display showing the most efficient route to the robot. When they arrive at the location, the workers will then use a mobile app involving Augmented Reality that will show them relevant data needed for efficient maintenance and repairs.

> Describe the needs of the clients/users and how they will benefit from the results of this project. Describe what they do and how they will be impacted by the results and how it may influence their future business direction. Describe how clients/users will be engaged in the project.

# Project Performance Framework
## Objectives, outputs, outcomes and criteria

> Identify and define project objectives, outputs and outcomes as well as a measurement criteria. 
> -	Objectives: Define what the project is trying to achieve.
> -	Outputs: Deliverables and products produced by the project.
> -	Outcomes: Impact you are working to realize such as behaviours and practices that results from the outputs. They can be short, medium or long term.

Item | Project Objectives | Project Outputs | Project Outcomes | Measurement Criteria
------------ | ------------- | ------------- | ------------- | -------------
1 | Suggest routes for crews to robots needing repairs or maintenance more optimal than appending each newly reported broken robot to the end of a crew's itinerary | Route-planning assistance software with ability to push notifications and itinerary to crew members' phones | Decrease in distance travelled for maintenance/ repair crews. ie. savings in fuel and travel time. | Measured by comparing solutions to sample problems consisting of 250 randomly generated locations. The solution must outperform the trivial algorithm on over 95% of 20 test cases. Performance is gauged by the sum of the length of all routes.
2 | Provide technicians with information to aid in diagnosing issues and performing repairs. | Mobile AR interface capable of overlaying historic data and schematics overtop of a robot | Decreased requirements for technicians to memorize specifics of various models of robots. General knowledge is augmented with in situ information provided. | Ability to enable/ disable AR layers. Ability to switch between AR info layers provided. Ability to identify the robot in the camera's focus.
3 | Provide technicians with route information for their currently planned routes | A mobile interface with routing and itinerary information (which robot to fix next) | Convenience for technicians who need to know their next task | should be able to see locations of robots needing maintenance on a map. should be able to see route information for current user. should be able to check-off schedule items as repaired, or needs parts, etc. (add information to file).
4 | Consolidate failure & usage data to help develop understanding of assets | A data visualization component of the web-based IOC containing live-updated charts and figures | Improved business knowledge regarding product failure | Bar chart plotting replacement parts used in repairs. Line chart plotting number of robots requiring repairs. At least 4 other meaningful visualizations must be available.
5 | Show current and historical spatial state of assets and crew | A map component of the web-based IOC capable of displaying historic and current locations of connected robots, crew, and routes | Improved monitoring and spatial knowledge | filters should be available based on status of robots. should be able to show the current location of maintenance crews. should be able to show current routes planned for crews. should be able to create/ edit routes for crews.


> For the measurement criteria provide a statement that describes what the project will accomplish and the performance measure. The project objectives whenever possible should be written to be specific, measurable, achievable, realistic and timely (SMART). The measurement criteria specifies a metric(s) that will measure success.  

## Project Performance Measurement Plan
> For each project objective and measurement criteria identified in the above table, indicate the methods used to measure, who is responsible, frequency of measurement, key targets and reporting on results. For example, if there are three(3) project objectives, fill out a performance measurement plan for each objective.

Project Objective | Measurement Criteria
------------ | -------------
**Description of Measure** | **Method**
Method used to measure |
Responsibility: who measures/analyses/reports|
Frequency of measure |
Key targets |
Reporting on results |

## Sustainability

There are several plans that our organization has decided on for future sustainability of this project. The first plan is to possibly have further development on the project outputs after conclusion of the Capstone project. This can be done through widening the scope of the project beyond what we have currently outlined above. As technology improves, it will be more feasible to add new hardware to the project with the addition of AR headsets. Currently, technology is limited, especially when using AR on mobile devices. However it could be a good idea to expand the project to use new AR headsets such as the Microsoft Hololens 2, which is predicted to be released in 2019. The Hololens 2 will improve upon criticisms of the first version by having an improved field of view, improved battery life, and will also be more comfortable to wear. Additionally, Microsoft is predicted to significantly reduce the cost of the Hololens 2 compared to the Hololens. With these predicted specifications and costs, it may be more technically feasible to purchase a Hololens 2 and expand this project. These AR headsets will be used by maintenance crews for hands-free maintenance as well as remote assistance from experts.

Aside from adding an AR headset, the project could be expanded upon in several ways. For both maintenance and development, the organization can expand and improve upon the weak signal detection portion of the project. This can be done through adding AI and machine learning. In the current scope of the project, the IOC will be manually viewing sensor data, alerting, and routing maintenance crews to fix a robot when repairs are needed. Adding AI and machine learning in the future will allow for pattern recognition in sensor data. With the system being able to recognize patterns in this data it will be able to make faster decisions on repairs, such as sensing that repairs are needed on a robot before a human can. Finally, further development on this project in the future can also be done by releasing the project as open source on GitHub. By releasing it on GitHub, the GitHub community will have access to download the project. Any developer that wishes to do so can then maintain the final results of the project and develop new and improved features. 

--> ADD REFERENCE IN THIS SECTION FOR HOLOLENS INFORMATION

> Describe plans for maintenance and/or further development of the project outputs.  Demonstrate that the organization sustaining the project results has a structure in place to do so.  
Describe plans for the maintenance and/or further development of the project outputs for the immediate years following the GeoConnections’ funded project.  Identify as specifically as possible the organization and sector or division that will be responsible for maintaining the results.  

> Describe the role of your collaborators in sustaining your project.

# Project Issues and Risks
## Issue Identification
> Specify any major policy, standards, data, technical, partnership and/or client engagement issues that need to be addressed in order for the project to be successful. 

## Feasibility and Risk 

-Technical Risk
-Safety Risk
-Deadlines
-Losing people/knowledge

Risk mitigation
-prototyping
-evaluate scope frequency
-insurance

commitment risks, organization risks, contracting risks, technical risks, financial risks, human resources risks (such as the availability of qualified personnel or experienced personnel), project dependencies and/or policy issues related to data access (i.e. licensing, intellectual property, copyright, security, privacy etc). 




> Identify and evaluate potential challenges or risks in completing and/or sustaining the project.  Please fill out the table and add any other applicable risks.  Examples of risks include: commitment risks, organization risks, contracting risks, technical risks, financial risks, human resources risks (such as the availability of qualified personnel or experienced personnel), project dependencies and/or policy issues related to data access (i.e. licensing, intellectual property, copyright, security, privacy etc). 

No. | Risk Description | Severity (H/M/L) | Probability (H/M/L) | Mitigation strategies for dealing with each risk 
------------ | ------------- | ------------- | ------------- | -------------
1 | | | |
2 | | | |

> To demonstrate feasibility, make reference to past research, pilot projects, demonstrations, previous experience, and reports. Evaluate the mitigation statements against the Project Implementation Plan for availability of resources and flexibility to address potential risks.  If no mitigation is planned, indicate “none”.

# Project Plan
## Project Team and Resources
> Identify the resource name, organization, role and responsibilities of the resource. Note any unique competencies that are required to deliver on the project. If the resource name is unknown note this in the resource name field but complete the role, and unique competencies fields. Collaborating organizations resources also need to be included in this table. 

Name | Lucas Hossack
------------ | -------------
**Organization** | RouteScouts
**Role** | Programming Lead
**Responsibilities** | High level architecture design
**Key Skills** | Programming, algorithms, debugging

Name | Deanna Wing Yan Ip
------------ | -------------
**Organization** | RouteScouts
**Role** | Project Manager
**Responsibilities** | Manage deadlines, ensure deliverables are met
**Key Skills** | Communication, leadership, management

Name | Shuet-Ching Christina Lo
------------ | -------------
**Organization** | RouteScouts
**Role** | UX Designer
**Responsibilities** | Ensure functionality of UI meets the end user's specifications
**Key Skills** | Programming, design, databases

Name | Joan Ching Kwan Tam
------------ | -------------
**Organization** | RouteScouts
**Role** | QA Lead
**Responsibilities** | Test changes to the code
**Key Skills** | Writing tests, testing tests, running tests

Name | Steve Liang
------------ | -------------
**Organization** | SensorUp
**Role** | Supervisor/Professional Advisor
**Responsibilities** | Providing advice when needed
**Key Skills** | Ideas, professional consultation, advising

## Project Management and Control
The project manager is responsible for ensuring the overall success of the project from initialization to closure. Using their leadership skills, the project manager will monitor the progress of the project by reviewing Zenhub on a regular basis. Recognizing when issues arise, the project manager will follow up with the corresponding team member regarding deliverables and meeting deadlines. This role will be assigned on a rotating basis through the different phases of the project. 

The project will be managed using an agile project management approach to allow for greater flexibility and speed. Short delivery cycles will ensure issues are resolved early in the development process instead of waiting until the program is complete. The team is expected to have high frequency interaction and collaboration on the project, ensuring rapid identification and adjustment of issues. Issues will be created in Zenhub, an agile project management tool that visualizes the issues of the different stages of the project. Agile's repeatable process decreases turnaround time and reduces the risk and complexity and the project.  

The project's version control of the programming code will be monitored using Github. To ensure quality of code, pull requests are required to be reviewed before mergering, allowing for immediate feedback from team members. As a description of the changes are attached with each commit, searching between versions and comparing changes will be much easier. In the situation where the code no longer runs properly due to some changes made, Github allows us to easily revert back to a previous version of the code before the changes were made. The collaboration of Zenhub and Github will allow for an open and efficient software development environment for the project.

> Describe mechanisms in place to ensure effective management and control of the proposed project.

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
3.1.1 | Agile sprint | Periodic | Completed work over the course of the sprint | 2019-01-10 | Variable dates

> Include a thorough project implementation plan, and clearly indicate the following elements:

> Project phases with well-defined activities or tasks for each stage and calendar-based schedule
> Project control and tracking methods 
> Communication and feedback mechanisms
> Milestones and deliverables (below)

> The project should be divided into phases, with a series of milestones at critical points in the work. Each milestone should be qualified with associated tasks to be completed. Deliverables are to be linked to these milestones. 

> Complete the table below. The schedule of work is left to the discretion of the project proponent. 

> •	Column 1 “WBS” – identifies a number for each task and sub-task and milestones. 
> •	Column 2 “Task and work breakdown” – describes each task and sub-task and milestone. Sub-tasks must be defined to a maximum of ten days. As a guideline, it is advisable to provide a breakdown / detail on any activity with a total effort of more than 10 days
> •	Column 3 “Duration (days)”is the total length of time in working days that the activity will take.
> •	Column 4 “Organization” – indicates the name of the organization responsible for the task. 
> •	Column 5 “Team Members Name” – identifies the actual personnel assigned to carry out the described task. 
> •	Column 6 “Days effort/person” – indicates the level of work effort in days for each team member. 
> •	Column 7 “Outputs” – indicates all the outputs to be delivered at the milestone. 
> •	Column 8 “Start Date” – indicates the date at which the first activity begins.
> •	Column 9 “Delivery Date” – indicates the date for delivery of the final deliverable of a particular milestone. 

WBS | Task & work breakdown | Days effort | Outputs | Start Date | Delivery Date
------------ | ------------- | ------------- | ------------- | ------------- | ------------- 
**1** | **Initiation Phase** | **14** |** ** |  **20xx-xx-xx** | ** **
1.1 | Kick-off meeting, including preperation | 2 | Meeting minutes document on GitHub | 2014-03-14 | 
1.2 | some tasks here | 5 |  | 20xx-xx-xx | 
1.3 | some taks here | 5 |  | 20xx-xx-xx | 
**2** | **Phase 2** | **15** |** ** |  **20xx-xx-xx** | ** **
2.1 | some tasks here | 5 |  | 20xx-xx-xx | 
2.2 | some tasks here | 5 |  | 20xx-xx-xx | 
**3** | **Phase 3** | **20** |** ** |  **20xx-xx-xx** | ** **
3.1 | some tasks here | 10 |  | 20xx-xx-xx | 
3.2 | some tasks here | 5 |  | 20xx-xx-xx | 

## Budget Summary

There will be several costs related to running and completing this project:

- Server costs. This project depends almost completely on having a server. In order for us to have a webpage containing the UIs for the IOC and the maintenance crews, a server is required to host the webpages on. 
- Robot model. This model will be used during the final presentation and the Capstone Fair to test our project. Since we cannot feasibly bring in a large robot to maintain during these presentations, a smaller robot, such as BB-8, will be shown to advisors and judges.
- Capstone poster. For the Capstone Fair, every organization is required to have a poster describing their project for judges and audiences to view. Since it is essential, we must include this cost into the budget for our project.

> Briefly describe the budget required for this project. Itemize and justify the expenses.


## Communications Plan and Accessibility of Project Results

Communication on the progress of the project between our organization, collaborating organizations, and clients/users will be done during major milestones throughout the next 6-7 months. These milestones include the mid-semester progress report presentations/reports, the final presentation/reports, as well as the Capstone Fair. In the progress reports we will be showing the work that we have done up to that point, where we are in the context of our project implementation plan, and future work to be done. The presentations for these progress reports will be presented in front of a spokesperson with our collaborating organization SensorUp and project advisor, Steve Liang. The final report will contain in-depth details on our completed project and we will be presenting our completed project both in the final presentation and at the Capstone Fair. In the final presentations, we will again be presenting in front of Dr.Liang. For the Capstone Fair, we will be showing the final project results to our clients and users, as well as prospective clients for the future.

Within our organization and collaborating organizations, we are using messaging applications in order to share and disseminate results. For example we have kept in constant communication with Dr.Liang using Slack. With Slack, we are sharing the progress we have made in our research and project on a nearly weekly basis through messages. As well, we have been using Slack to set up  physical or video meetings with Dr. Liang to have him check upon our progress and see if he has any concerns. Internally as RouteScouts, we have been using both Slack and Facebook Messenger to share our individual progress as well as plan meetings with the rest of the organization. For example, in order to approve a pull request on GitHub, we have messaged each other that a change has been made, and to ask other members to review the request. Other members will then know of this pull request and approve if the changes made are acceptable. This method of internal communication will continue to be used throughout this project at a greater frequency as we move into writing code and ensuring there are no project conflicts. 

> Describe how you will share and disseminate results of your project amongst your organization, the collaborating organizations as well and clients/users (i.e., presentations, post on the web, conferences, demonstrations, press releases etc.).

# Benefits
## Benefits to Canadians
By having an Integrated Operation Center, the dispatcher can visualize the location of maintenance crew workers in relation to malfunctioned robots, allowing for route optimization. Improved maintenance routes will decrease fuel comsumption, so the amount of carbon released into the environment would also significantly decrease. 

With a 
may indirectly result in reduced prices in the products. 
The development of this new technology 


-decreased price in products (indirect)
-new technology


## Benefits to Sponsors and Users
As a result of implementing the system, there will be increased safety for 
users
-increased safety
-diagnose issues quickly
-time saved

sponsor
-have fun
-increase visbility of his API




## References
https://www.thebalancesmb.com/route-planning-2221322
https://www.supplychaindive.com/news/4-types-of-autonomous-mobile-robots-and-their-warehouse-use-cases/529548/
https://www.theverge.com/2018/6/13/17458168/microsoft-hololens-2-details-rumors




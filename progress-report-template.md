# Introduction
## Milestone Summary
> Template Instruction: The planned delivery date is outlined in the propsosal whereas the actual delivery date is when the milestone components are completed. If the planned date falls in next reporting period, enter the proposed completion date.  “In-progress”, or “ongoing”, can be entered, as required. If the planned and actual delivery dates are different please explain why the dates have changed in section 2.1 or 2.3, as appropriate.  

Milestone | Components | Planned Delivery Date | Actual Delivery Date
------------ | ------------- | ------------- | ------------- 
Low/Medium Fidelity Prototypes completed | Paper prototypes, IOC/Mobile app PowerPoint mockups, Mobile AR storyboard, Video of AR experimentation | 2018-11-16 |  2018-11-26
Minimal Viable Product | Working interfaces and database (In-progress) | 2019-01-10 | In-progress
Final Result | Complete working project (In-progress) | 2019-04-05 | In-progress

# Milestone Overview
## Summary of Work Accomplished During this Period

Over the past few weeks, we have completed work largely based upon the schedule we set in our project proposal. The deliverables expected to be completed by this point in time include identifying tasks and users, as well as creating prototypes of our interfaces. The interfaces that we have decided on creating are for the two users, the IOC and the maintenance crews. The IOC interface will include a map of robot and maintenance crew, as well as statistics for each robot. Maintenance crews will be able to see details regarding their current and next job requests and an AR overlay for the robot they are repairing. We have created a document containing tasks that the interfaces should be able to perform. These tasks are split up into 4 separate categories: must have tasks, should have tasks, could have tasks, as well as tasks that can be excluded. Must have tasks are tasks that the interface requires to function based upon our project specifications. Should have tasks are ones that are not essential to the function of the interface, but should be included. Could have tasks are tasks that we can implement if time permits, but are largely unnecessary. Finally, excluded tasks are ones that are not required for the interface and are not tasks that the user should be able to perform.

After completing the list of tasks, each member was required to submit a paper prototype of the interface. By having each member brainstorm and contribute their own ideas, we were able to look at and discuss different ideas and pros and cons for the final low-fidelity prototype. Once having decided on a general layout, work began on creating a mockup of the interface using Microsoft PowerPoint. This PowerPoint shows our interfaces and the interactions between different buttons. For example, clicking on one of the robots on the map in the IOC interface brings up its information. !!!Insert maintenance crew example here.!!! The PowerPoint forces us to think of interactions within the interface and whether or not it is intuitive for users to use. !!!Maybe add more stuff here later about the PowerPoint, or we can just leave it if we good!!!

Finally, we have begun researching different technologies to use for the AR portion of our project. AR applications, while not new, are beginning to gain popularity. Thus, many APIs and software development kits, or SDKs, are being released and updated for development of both web and mobile applications. One API we researched was WebXR, which is an open web API for AR that hopes to bring mixed reality to the web [1]. WebXR is developed by Mozilla and is expected to provide a foundation to develop AR experiences within browsers. This is done by enabling the integration of the real world with contextual overlays [1]. We have also looked into building a mobile AR application through the use of ARCore, which is a SDKs that is used to build AR experiences. ARCore uses several APIs to enable mobile devices to sense its environment through motion tracking, environmental understanding, and light estimation [2]. Within ARCore, developers can build AR apps that can respond to 2D images. This is called an augmented image, and is something that we have researched for our project. Tracking within ARCore tells the device where the images are physically located, once it has been detected by the camera [3]. 

An additional option which we are investigating is the use of object recognition libraries. These utilize various underlying technologies, but we need an option which can perform well on a mobile device, consistently, and track the object sufficiently well for AR. JeelizAR [4] is an example of such a library in JavaScript for WebXR. For ARCore, we may be able to utilize TensorFlow [5]. While object and orientation recognition provides some benefits of robustness and not requiring high-contrast images to be attached to our robots, it is not yet supported natively in ARCore, though this was proposed earlier in 2018 [6].

> Template Instructions: Describe the work accomplished in this phase. Include a brief summary of the work accomplished in comparison to the work plan. Provide relevant samples of the work progress, that is useful for evaluating the progress, such as URLs of prototype, operational results, pictures of field work, sample data collected, URL of code repository, etc.

## Lessons Learned

With the research we have done on APIs and SDKs for AR applications, we have run into a number of issues. WebXR was the first API we researched, to use AR within a web browser. There are some issues with implementation in WebXR however, such that it does not support augmented images, which makes it a higher risk to develop with than AR Core. We were unable to investigate object detection libraries further due to not having access to a web server with ssl - WebXR requires https.

Next, we looked into using ARCore to build a mobile application instead, using Android Studio as the integrated development environment, or IDE. More research needs to be done into using ARCore and augmented images, but we are confident that we can use this for our project (please reword this sentence). One problem with using Android Studio to develop a mobile application is that the official language is Java, which no members of our group has used in several years. As a result, we must add re-learning Java into our schedule if we stick with the plan to develop a mobile application on Android Studio. Another issue with Android Studio is that some of the group member's laptops cannot efficiently run programs on it as it is a fairly resource heavy program. This would force group members to work on the application either on the laptops that can handle the load, or at home on their desktop, which is very inefficient. One solution that has been proposed for this issue is to ask the IT department at the university to install Android Studio in the Geomatics Engineering department's computer lab. This would allow us to work on it together as a group, allowing for easier communication and help when required.

> Template Instruction: Insert in this section, an explanation of significant problems encountered and their solutions.

## Changes to the Work Plan

Based upon the work we have completed up to this point, there will be no changes to the work plan for the next milestone. As a large majority of our group members have used Java and Android Studio before, we believe that developing a mobile application on Android Studio will not hinder our plans. We are confident that we will be able to complete our next milestone on time.

> Template Instruction: If applicable to the project situation, describe here any changes to the work plan for the next milestone.

## List of Attachments
> Template Instruction: Insert the list of documents that are attached such as milestone components  that were listed in the milestone summary table.

Milestone | Document | Link
------------ | ------------- | -------------  
1 | Augmented image testing | https://github.com/lhossackucalgary/ENGO500-2018-group3/blob/master/AugmentedImageVideo.mp4
1 | AR Prototype/Storyboard | https://github.com/lhossackucalgary/ENGO500-2018-group3/blob/master/AR%20Prototype%20Storyboard.pdf
1 | IOC Prototype | nolink
1 | Paper prototypes | nolink


## References

[1] https://www.infoq.com/news/2018/09/mozilla-webxr-spec
[2] https://developers.google.com/ar/discover/
[3] https://developers.google.com/ar/develop/java/augmented-images/
[4] https://github.com/jeeliz/jeelizAR
[5] https://www.tensorflow.org/lite/
[6] https://github.com/google-ar/arcore-android-sdk/issues/418

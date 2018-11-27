# Introduction
## Milestone Summary
> Template Instruction: The planned delivery date is outlined in the proposal whereas the actual delivery date is when the milestone components are completed. If the planned date falls in next reporting period, enter the proposed completion date.  “In-progress”, or “ongoing”, can be entered, as required. If the planned and actual delivery dates are different please explain why the dates have changed in section 2.1 or 2.3, as appropriate.  

Milestone | Components | Planned Delivery Date | Actual Delivery Date
------------ | ------------- | ------------- | ------------- 
Low/Medium Fidelity Prototypes completed | Paper prototypes, IOC/Mobile app PowerPoint mockups, Mobile AR storyboard, Video of AR experimentation | 2018-11-16 |  2018-11-26
Minimal Viable Product | Working interfaces and database (In-progress) | 2019-01-10 | In-progress
Final Result | Complete working project (In-progress) | 2019-04-05 | In-progress

# Milestone Overview
## Summary of Work Accomplished During this Period

Over the past weeks, we produced low and medium fidelity prototypes of the application. These tasks were completed within a time frame which aligned closely to the defined schedule in our project proposal. Our current expected deliverables include identifying tasks and users, and creating prototypes of our interfaces. The interfaces will be created for two users groups, the IOC and the maintenance crews. The IOC interface will include a map displaying the location of the robots and maintenance crews, as well as real-time statistics for each robot. Maintenance crews will be able to view details regarding their current and next job requests from the IOC Mobile Application and an AR overlay for the robot requiring repair. The *Application Tasks* document describes and categorizes the importance of tasks the interfaces should perform. The tasks are split up into 4 separate categories: must have tasks, should have tasks, could have tasks, and tasks that can be excluded. Must have tasks are necessary for the interface to function based on our project specifications. Should have tasks are not essential to interface functionality, but should be included. Could have tasks are tasks that can be implemented if time permits, but are not required. Excluded tasks does not interfere with the fuctionality of the interface but would be nice to have.

After completing the task list, each member was asked to submit a paper prototype of the interface, viewable at the *Paper Prototype* link below. By having each member brainstorm and contribute their own ideas, it resulted in a diverse range of designs. Following a discussion of the pros and cons of each design, we took the best features to produce the final low-fidelity prototype. Once having decided on a general layout, we began creating a mockup of the interface using Microsoft PowerPoint, this is the *IOC Prototype* document attached. The PowerPoint provides visualization of our interfaces and the interactions between buttons. For example, clicking on one of the robots on the map in the IOC interface brings up its information. By creating the PowerPoint, we were able to see the interactions within the interface and whether or not it is intuitive for users to use.

Moreover, we began researching current available technologies for our AR interface. With the growing popularity of AR applications, several APIs and software development kits are being released and updated for development in both web and mobile applications. One API we researched was WebXR, an open web API for AR that hopes to bring mixed reality to the web [1]. WebXR is expected to provide a foundation to develop AR experiences within browsers. This is done by enabling the integration of the real world with contextual overlays [1]. We also looked into building a mobile AR application using ARCore, an SDK used to build AR experiences. ARCore utilizes several APIs to enable mobile devices to sense their environment through motion tracking, environmental understanding, and light estimation [2]. Within ARCore, developers can build AR apps that can respond to 2D images. This is called an augmented image, which we have researched for our project. Tracking within ARCore tells the device where the images are physically located, once it has been detected by the camera [3]. The *Augmented Image Testing* video displays some of our investigations into AR Core.

An additional option we are investigating into is the use of object recognition libraries. These libraries utilize various technologies, but we need an option which can perform consistently on mobile devices, and track objects sufficiently well. JeelizAR [4] is an example of such a library in JavaScript for WebXR. Similarly, we may be able to utilize TensorFlow [5] for ARCore. While object and orientation recognition provides some benefits of robustness and omits the need for high-contrast images to be attached, it is not yet supported natively in ARCore, though it was proposed earlier in 2018 [6]. In addition to the AR research, we also have created an *AR Prototype/Storyboard* available from the List of Attachments.

> Template Instructions: Describe the work accomplished in this phase. Include a brief summary of the work accomplished in comparison to the work plan. Provide relevant samples of the work progress, that is useful for evaluating the progress, such as URLs of prototype, operational results, pictures of field work, sample data collected, URL of code repository, etc.

## Lessons Learned

With the intensive research on APIs and SDKs for AR applications, we came upon several issues. We initially looked into using WebXR for AR development within a web browser. However, an issue we encountered with the implementation of WebXR was that it did not support augmented images. Therefore, development using WebXR comes with a higher risk in comparison to ARCore. We were also unable to further investigate object detection libraries as we did not have access to a web server with ssl - WebXR requires https.

Instead, we looked into using ARCore to build a mobile application with Android Studio as the integrated development environment. Further investigation in ARCore and augmented images are still needed, but ARCore seems to be the most feasible option. One challenge with using Android Studio to develop our mobile application is programming in Java. As none of us use Java often, we will need to add re-learning Java into our schedule if we decide on using Android Studio. With Android Studio being a resource heavy application, group members who can't run the program on their laptops would be forced to work on at home on their desktop. One solution that has been proposed for this issue is to ask the IT department at the university to install Android Studio in the Geomatics Engineering department's computer lab. This would allow our group to work together on campus, resulting in easier communication and assistance between group members when required.

> Template Instruction: Insert in this section, an explanation of significant problems encountered and their solutions.

## Changes to the Work Plan

Based on the work completed up to this point, there will be no changes to the work plan for our next milestone. As most of our group members have used Java and Android Studio before, we believe that developing a mobile application on Android Studio will not hinder our plans. We are confident that we will be able to complete our next milestone on schedule.

> Template Instruction: If applicable to the project situation, describe here any changes to the work plan for the next milestone.

## List of Attachments
> Template Instruction: Insert the list of documents that are attached such as milestone components  that were listed in the milestone summary table.

Milestone | Document | Link
------------ | ------------- | -------------  
1 | Application tasks | https://github.com/lhossackucalgary/ENGO500-2018-group3/blob/master/ApplicationTasks.md
1 | Paper prototypes | https://github.com/lhossackucalgary/ENGO500-2018-group3/blob/master/Low-Fi-PaperPrototypes.pdf
1 | IOC Prototype | https://github.com/lhossackucalgary/ENGO500-2018-group3/blob/master/RMEME%20Prototyping.pptx
1 | IOC Prototype Video | https://www.youtube.com/watch?v=RB1N0FBRyeo&feature=youtu.be
1 | Mobile App Prototype | https://github.com/lhossackucalgary/ENGO500-2018-group3/blob/master/MobileAppProto_Capstone.pptx
1 | AR Storyboard | https://github.com/lhossackucalgary/ENGO500-2018-group3/blob/master/AR%20Prototype%20Storyboard.pdf
1 | Augmented image testing | https://github.com/lhossackucalgary/ENGO500-2018-group3/blob/master/AugmentedImageVideo.mp4


## References

[1] Sergio. D. S, "Mozilla Pushes WebXR as New Open Web API for Augmented Reality," *infoq.com*, para. 1-2, Sep. 16, 2018. [Online]. Available: https://www.infoq.com/news/2018/09/mozilla-webxr-spec. [Accessed Nov. 26, 2018].

[2] "ARCore Overview", *developers.google.com*, para. 1. [Online]. Available: https://developers.google.com/ar/discover/. [Accessed Nov. 26, 2018].

[3] "Recognize and Augment Images", *developers.google.com*. [Online]. Available: https://developers.google.com/ar/develop/java/augmented-images/. [Accessed Nov. 26, 2018].

[4] B. Xavier, "JeelizAR" [online]. Available: https://github.com/jeeliz/jeelizAR [Accessed: Nov 26, 2018].

[5] TensorFlow, "TensorFlow" [online]. Available: https://www.tensorflow.org/lite/ [Accessed: Nov 26, 2018].

[6] B. Nasser, "Feature request : 3D Object Detection" [online]. Available: https://github.com/google-ar/arcore-android-sdk/issues/418 [Accessed: Nov 26, 2018].


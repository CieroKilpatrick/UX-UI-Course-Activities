## 20.1 Lesson Plan - Web Prototyping and Web Performance (6:30 PM)

- Today's class will be an continuing Bootstrap components and introducing web performance.

### Instructor Notes

- Use the [20.1-Advanced-Web-Prototyping-1.pptx](https://drive.google.com/open?id=18jmeqMzYhHo1Y4tqMBYy2fU67eqcb7Ww) slide show provided as an initial guide for today's class. Feel free to modify the slides slightly to fit your own style, but be sure to cover the same concepts and activities.

- Slack out a .pdf of the days slideshow to students at the beginning of class. 

- Have your TAs reference [TimeTracker](TimeTracker.md) to help keep track of time during class.

---

### Class Objectives

- - Students will gain an understanding of the power of jQuery and how behavior is a key component of creating web experiences.

- Student will explore jQuery options showcase.

- Students will be able to review common jQuery interactions through jQuery Plugins.

  - More Modals
  - Alerts.
  - Form helpers.
    - Currency picker.
    - Slider.
    - Country Picker.
    - Date & Time Picker.

- Students will be able to be plugin jQuery.

- To introduce students to working through problems via prototyping.

- Discuss RAD development. 

- Explore Bootstrap Alerts. 

- Review and test website performance.

- Students will be introduced to web performance as a UX issue.

- Students will test web speeds.

##### Instructor Priorities

- Students should be growing their use of web behaviors. Jquery is a very challenging and confusing aspect of web development.

- Update students that the goal is not to become worldclass Jquery or Bootstrap developers or even code from scratch right away. They might get there but no one starts out at that place. However they will experiment and use code effectively and get ideas across even it is not their final UI vision.

- Share a bunch of resources at will and make sure to encourage students to lean on each other, on tutoring, and to experiment with more prototyping with Bootstrap.

---

### Class Materials

- Computer & VS Code.

- Post-it Notes.

- Sharpies / Dry Erase Markers.

---

### 1. Instructor Do: SLIDES - Intro + Review (10 mins) (Critical)

- Open up the [20.1-Advanced-Web-Prototyping-1.pptx](https://drive.google.com/open?id=18jmeqMzYhHo1Y4tqMBYy2fU67eqcb7Ww) or your modified file and present each of the slides. Use the `Teams` slide as a cue for breaking students up into teams.

- Review. 

  - Ask Which Bootstrap components rely on jQuery?

- Get a class temperature on how they are feeling about Bootstrap 4. 

  - Ask: By show of hands. How many of you you are finding Bootstrap freeing?

  - Ask: By show of hands. How many of you you are finding Bootstrap restrictive?

- Remind students that Bootstrap is tons of free lines of code but you have to dig in under the hood and understand the fundamentals of how they write the CSS to really unlock its potential.

  - Ask: Do any of you want to right your own Framework?

- Next...Standardization vs. Customization.

  - Ask: What does Bootstrap help with? Standardization or customization?

    - Answer: Standardization - they define the CSS & HTML classes you have to play by bootstraps rules.

  - Have a short conversation about the why Code would want to Standardize rather than customize.

### 2. Instructor Do: SLIDES - Prototype Management (10 mins) (Critical)

- Next...Prototyping can be Totally RAD.

- Next...Play the .gif.

  - A Strong 1980's reference anyone know it?

- Next...RAD Method (Rapid Application Development).

  - Review the method. It Relies on prototyping and rapid cycles of iterative development to speed up development and elicit early feedback from business users.

- Ask: Does this look familiar to anyone else?

  - It should as Developers have visualized the design process their own way.

  - Not every company you come across will be versed in the design process but might have analogous processes.

  - Being able to adapt the Design Thinking process inside these development methodologies will help you be more employable.

- Next...When developing prototypes we need to consider a few factors.

  - Review the Degree of difficulty vs. Time.

  - Using Bootstrap at first might have a high level of difficulty? Yes?. 

  - However over time it should decrease uncertainty and decrease costs.

  - UX is inherently strategic as is development.

- Next... UX / UI Development and paradox of customerization. 

  - Customerization is the customization of products or services through personal interaction between a company and its customers.

### 3. Instructor Do: DISCUSSION - Customerization (10 mins) (Critical)

- Next...Customization Post-it.

- **Instructions**

  - **1.** Take a moment and complete 1 Post-it note of a company / website that you believe lives in the Customerization zone.

  - **2.** Come and add your PostIts to the whiteboard.

- Have a short conversation about the companies / websites that made it into the list.

  - Review the big players. Ask: based on these is it only possible to achieve this status if you are big?

  - Keep conversation short and call out Post-it notes and ask students to answer why they chose it.

### 4. Instructor Do: SLIDES - Prototype Management cont'd (5 mins) (Critical)

- Next...Fail Fast, Fail Hard, Fail Often.

  - If you are not failing you are not taking risks if you are not taking risks with your solutions you probably aren’t learning anything.

### 5. Students Do: DISCUSSION - Coding Fail (5 mins) (Critical)

- Raise your hand if you have failed at coding.

  - (keep your hand up as long as remains true).

  - In the past week? 
  - In the past couple of days?  
  - In past 24 hours? 
  - In the past hour? 

- Your hand should have been up until the past hour!

  - Empathize with students that we understand this stuff is very hard and we are throwing it at them incredible fast.

  - Coding is not for everyone but if you want to build digital solutions you need to have some grasp on how it works.

- Next...Play the .gif.

  - Prototyping can feel like this!

  - Keep at it and you will get better I promise. 

### 6. Instructor Do: SLIDES - Interface Customization (10 mins) (Critical)

- Next...Custom UI.

  - Customization lets users make their own selections about what they want to see, or set preferences for how information is organized or displayed.

- Next...Play the .gif. of custom Nike ID shoe.

  - Giving users control is more the just the UI it is about them engaging in the entire system.

- Next...Interface Personalization.

  - Personalization is done by the application being used. Apps tries to deliver user the content, experience, or functionality that matches their needs. 

  - Ask: What is the difference between customization & personalization. 

    - Call on a student to answer.

- Next... Personalization can be achieved through communications.

  - The main goal of personalization is to deliver content and functionality that matches specific user needs or interests, with no effort from the users. 

  - Netflix, 75 percent of their views come from personalized recommendations.

- Next...Review Nike ID systems.

### 7. Instructor Do: Bootstrap DEMO - Interface Customization (10 mins) (Critical)

- Once time's up call on a few students to share a few JavaScript components they've identified and their behavior.

- Below are some examples, briefly go through any unfamiliar components together as a class and discuss.

  - [**Dismissible Alerts**](https://getbootstrap.com/docs/4.1/components/alerts/#dismissing): Bootstrap alert components which can be "dismissed" or made to fade away by clicking a button within the alert.

  - [**Carousel**](https://getbootstrap.com/docs/4.1/components/carousel/): A slideshow component for cycling through elements — images or slides of text — like a carousel.

  - [**Collapse**](https://getbootstrap.com/docs/4.1/components/collapse/): Used to toggle the visibility of content by shrinking or expanding it in and out of view.

  - [**Dropdowns**](https://getbootstrap.com/docs/4.1/components/dropdowns/): Used to toggle contextual overlays for displaying links

  - [**Modals**](https://getbootstrap.com/docs/4.1/components/modal/): Used to add pop-up dialogs to your site which can contain virtually any content.

  - [**Popovers**](https://getbootstrap.com/docs/4.1/components/popovers/): Can be added to any element to toggle tiny overlays that contain text when clicked — similar to those found in iOS.

  - [**Scrollspy**](https://getbootstrap.com/docs/4.1/components/scrollspy): Used to automatically update a Bootstrap navigation or list group component to indicate the link that's currently active in the viewport as the user scrolls.

  - [**Tooltips**](https://getbootstrap.com/docs/4.1/components/tooltips/): Similar to popovers, tooltips can be added to any element to toggle even smaller overlays containing text.

### 8. Instructor Do: SLIDES Interface Communications (slides 20-26) (10 mins) (Critical)

- Next...Let's talk about Interface Communications: Alerts, Indicators, Validations, and Notifications.

- Next...Alerts.

  - Provide contextual feedback messages for typical user actions with the handful of available and flexible alert messages.

  - Ask: Why would we we want to alert our users?

  - keep conversation short.

- Next...Indicators.

  - User Interface element that stand out to inform the user that there is something special about it that warrants the user’s attention. 

- Next...Validations. 

  - Messages are error messages related to users’ inputs: they communicate whether the data just entered was incomplete or incorrect. 

  - User must take action.
  - User must have context to fix error.

- Next... Notifications.

  - Informational messages that alert the user of general occurrences within a system. 

- Next...Review Usage Table. 

  - Understanding when and how to use UI feedback tools is important in order to build consistency in the communication to users. 

- Next...Review Good Notification Tips. 

  - **Non-Interfering > Small in size > contextual > Serve warning only** 

### 9. Everyone Do: BREAK (15 mins)

- Let's take a break.

### 10. Students Do: ACTIVITY - Interface Communications samples (10 mins) (Critical)

- Next...Let's practice with alerts.

- **Instructions**

  - **1.** Find UI Code inspiration for Alerts, Notifications, Indicators, and validations.

  - **2.** Share sample in #dev-resources.

### 11. Students Do: ACTIVITY - Practice Bootstrap Alerts etc. (45 mins) (Critical)

- Next...Let's practice with alerts.

  - In this activity we will update a static landing page to make use of some of Bootstrap's Interactive JavaScript components.

- **Instructions**

  - **1.** Open TODO: Link in your web browser and take a moment to examine the page.

  - Now refer back to the last of Bootstrap JavaScript components discussed in the previous activity and update the page to implement a few of those. 

  - At a minimum, attempt to include:

    - A Carousel
    - A Scrollspy
    - A Modal
    - A Dismissible Alert
    - A Collapse Element

  - Feel free to modify, add, or remove any part of the existing web page you'd like in order to achieve this.

  - While the goal of this activity is to use as many Bootstrap JavaScript components as possible, attempt to do so in a meaningful way.

- **Bonus**

- Once you've added the required components, attempt to add the rest of Bootstrap's JavaScript components.

### 12. Instructor Do: SLIDES Web Performance Intro (slides 32-39) (15 mins) (Critical)

- Next...Play gif.

  - Ask: When you solve a code problem does it make you feel like this?

  - Its better! 

- Next...Let's Talk Web Performance and UX.

  - Provide that building prototypes is all good but eventually they also need to be websites that work.

- Next...User Experience is impacted by technology performance.

  - Review second delay.

  - Can you imagine any other profession that has a second time constraint.

  - A doctor diagnosis: not back in a second bad! 
  - A sandwich shop not completed in a second bad review! 

- Next...Review the Web Performance is User Experience.

  - **Poor performance damages findability**
  - **Poor performance increases the time to complete a task**
  - **Poor performance reduces user satisfaction**

- Next...Continued.

  - **Poor performance endangers accessibility**
  - **Undermines understanding**
  - **Associated with poor usability**

- Next...The fact is Time matters to your user.

  - slack out [Google - Why Performance Matters](https://developers.google.com/web/fundamentals/performance/why-performance-matters/)

- Next... Review Time and Conversion rate.

### 13. Students Do: ACTIVITY - Web Performance Analysis (30 mins) (Critical)

- Next...Let's practice with alerts.

- **Instructions**

  - **1.** Run Speed tests on 5 of your favorite websites.

    - Do not repeat websites of your fellow students.

    - [Google Speed test](https://developers.google.com/speed/pagespeed/insights/)

  - **2.** Take screen shots of Desktop & Mobile. Add images to gDrive to copy links.

  - **3.** Add speed analysis to the google sheet.

  - [Web Performance Analysis Google Sheet](https://docs.google.com/spreadsheets/d/1NgHWM2KTtzxZu5WfoWYCfGMTIpglZ00mrQscFncMvRg/edit?usp=sharing)

### 14. Everyone Do: End (5 mins)

- Go home.

---

# LessonPlan & Slideshow Instructor Feedback

- Please click the link which best represents your overall feeling regarding today's class. It will link you to a form which allows you to submit additional (optional) feedback.

- [:heart_eyes: Great](https://www.surveygizmo.com/s3/4346059/UX-UI-Instructor-Feedback?section=20.1&lp_useful=great)

- [:grinning: Like](https://www.surveygizmo.com/s3/4346059/UX-UI-Instructor-Feedback?section=20.1&lp_useful=like)

- [:neutral_face: Neutral](https://www.surveygizmo.com/s3/4346059/UX-UI-Instructor-Feedback?section=20.1&lp_useful=neutral)

- [:confounded: Dislike](https://www.surveygizmo.com/s3/4346059/UX-UI-Instructor-Feedback?section=20.1&lp_useful=dislike)

- [:triumph: Not Great](https://www.surveygizmo.com/s3/4346059/UX-UI-Instructor-Feedback?section=20.1&lp_useful=not%great)

---

### Copyright

Trilogy Education Services © 2018. All Rights Reserved.

# SEG4105 - Tutorial 3

| Outline | Value |
| --- | --- |
| Course | SEG 4105 |
| Date | Fall 2023 |
| Student | Michael Bosciglio, mbosc084@uottawa.ca, 300135179 |
| TA | Shabnam Hassaniahari, shass126@uottawa.ca <br> Ali Mirferdos , smirf045@uottawa.ca| 
| Professor | Andrew Forward, aforward@hey.com |  
| Team | https://github.com/MichaelBosciglio/seg4105_playground/blob/main/lab03/README.md https://github.com/ChetanMandur/seg4105_playground/blob/main/lab03/README.md https://github.com/Macomatic/seg4105_playground/blob/main/lab03/README.md https://github.com/hongyuewang/seg4105_playground/tree/main/lab03  https://github.com/SunnyD01/seg4105_playground/blob/master/lab03/readme.md|


### Breadboarding
![image](https://github.com/MichaelBosciglio/seg4105_playground/assets/55165965/5ef8b89f-5870-438a-b3bd-e432dd55d381)

### Problem
Our application's main functionality involves having a user be able to swap between their saved profiles on their mouse attachment. In order to do so, one must be able to create and delete a profile as well. In our MVP at the end of the first semester of our capstone project, all of the profile related functionality was hard coded so that we could give a proper demonstration of our projects intended functionality. Now we need to give the user the ability to create, swap between, edit/save and delete profiles.

### Appetite
Given a 6 week time frame, this feature will be able to be implemented given the complexity of the issue. Splitting the problem into three main parts will allow for enough time to complete the feature. Having ~2 weeks per main issue allows for better time allocation throughout the 6 weeks. If creating new profiles takes longer than switching profiles, I can allocate three weeks for this part of the feature to ensure that all parts are completed after the 6 weeks. 

### Solution
The solution to this feature is to update the current Profiles page in our react web application. We are going to need to first introduce the Create Profile screen which will pop up if the user's JSON file does not currently contain a profile. This new profile will be added to the user's profile list and show on the Profiles Page, from here the user will be able to Delete, Edit/Save and Swap between profiles. This will be done by updating the users JSON file based on which button the user selects.

### Rabbit Holes
One rabbit hole that needs to be avoided is to not be too focused on improving the UI of the profiles page while working on the core functionality. Since many new features are being added, it is important to ensure that we are maintaining the current UI elements that work well within the web application. Another rabbit hole that should be avoided is to include new features on to the profiles page without having client feedback. When creating this page, we are attempting to implement the core functionality of our application. If this is not done and other features are added, it can stray away from what the client needs. Once the page is complete, new features can be added based on the clients requests. 

### No Go's
We should not be adding any more new features on to the profiles page as the current feature includes the core requirements that the client requested. We should not change the UI and UX of the Profiles page. 




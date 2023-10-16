# SEG4105 - Tut06

| Outline | Value |
| --- | --- |
| Course | SEG 4105 |
| Date | Fall 2023 |
| Student | Michael Bosciglio, mbosc084@uottawa.ca, 300135179 |
| TA | Shabnam Hassaniahari, shass126@uottawa.ca <br> Ali Mirferdos , smirf045@uottawa.ca| 
| Professor | Andrew Forward, aforward@hey.com |  

## Betting Table Notes

### Chetan
- Problem
  - Is something that needs to be done for the final product
  - Essentially needs to connect to the application on the web
- Appetite
  - Acknowledges that the 6 week time frame is longer than needed
  - Important for the UX of the application
  - Allows for some testing after the feature is implemented
- Solution
  - Has proof of what APIs can be used to connect the device and application
  - Simplifies the code base and keeps it all connected
- Rabbit Holes
  - Try to avoid APIs that may change or harm our software in the future
  - Essentially want to make sure that the choice is future proof so do the research a head of time
- No Gos
  - Avoid the user's error from hindering the UX of our project

### Marco

- Problem
  - There is no current way for the product to be mounted to a mouse
  - Would help with the accessibility of our product
- Appetite
  - States that this would take 6 weeks which is fair
  - Simply a hardware feature (no software)
- Solution
  - Create a housing and attachment for the Pico Pi
  - Can use PLA casing
- Rabbit Holes
  - PLA casing should be good enough for this project
  - Avoid things such as glue as it would be permanant (need modularity)
- No Gos
  - Avoid new inputs and Raspberry Pi boards

### Hong Yue

- Problem
  - Important issue that needs to be solved
  - Need an application that can be downloaded to connect directly to the device (similar to Logitech GHUB software)
  - Web app is missing key functionality that can be solved with a desktop app
- Appetite
  - Recreate the web-app in 6 weeks within a desktop application
  - Should be enough things for multiple group members to work on
- Solution
  - Electron will be good for importing the web app code into the desktop app
  - Javascript and Typescript
  - Can be used on Windows, macOS, and Linux
  - Signin, Account and Overlay features
- Rabbit Holes
  - Use Typescript as it will be easier to import (same as web app)
  - Keeps the same UI and UX
- No Gos
  - No novel pages

### Dennis (Separate Project)

- Problem
  - Making a game more complex with a heirarchy of attacks and defences.
  - Create priority between attacks and statuses
- Appetite
  - Takes 6 weeks which makes sense
  - Since he is a solo developer, should fit in time frame
- Solution
  - Create a class that takes in all information for each unit
  - Save priorities and statuses
- Rabbit Holes
  - N/A
- No Gos
  - Do not update the actual effects and attacks, just the classes.

### The Bet
- We did not choose Dennis' pitch as he was not a part of our capstone presentation but we did listen to his pitch about his game creation.
- We did not choose my pitch because the time allocated for the feature would not make sense if we are going to implement it as a team of 4. The feature is mandatory for the application to function but having 4 people to work on it would be overkill.
- We did not choose Marco's pitch because the 3D modeling would be hard to separate into a 4 person workflow. This is something that needs to be implemnted as a ticket but should be done by one person who is the most knowledgable about 3D modeling and design.
- We did not choose Chetan's pitch because having all four of our developers to work on a hardware solution would limit the progress of our web and desktop application. This would be unnecessary work for the developers to complete when they have not worked on hardware throughout the projects lifecycle. We deemed it more beneficial for Chetan to continue to implement this feature in the future.
- The winner of the Betting table was Hong Yue's pitch (Electron Desktop App). This pitch was the most ideal for us to complete within the 6 weeks because it allows for enough content to be split up amongst our 4 team members. This idea also was solving one of the more important problems that needs multiple people to assist with which is the desktop to Raspberry Pi direct connection on multiple operating systems. With all of our expertist thus far, we should be able to complete this feature in the 6 weeks.
  
Tracking Meeting Minutes: https://github.com/Macomatic/T40-Mouse-Accessibility-Attachment/blob/main/Minutes.md#october-10-2023-400---500-pm <br>


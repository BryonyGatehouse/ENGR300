# ENGR300 : Mission Control Project

Completed in a team of 6.

### Introduction

For 2020, the ENGR300 class worked with a single client to create software and hardware for a hobby rocket. The roles were separated over the teams, a third of the teams working on creating a rocket with gimble and minimal onboard software, a third working on simulating the flight of the rocket given certain inputs (like wind, etc), and the final third working on a Mission Control Software which helps with the communication between the rocket, simulation and the user. 

This required all teams to share their communication protocols so that any set of teams' software can communicate between each other. 

### Paperwork

The paperwork was discussed as a team than written up by each member chosing sections to focus on. 

For this project, it was required that we wrote up a Project Proposal which included:
- A product perspective detailing what the product needs to do, what it needs to complete these requirements, and what limitations will be faced.
- How to verify the ability of the program, including the readability of the code and the types of tests.
- The development schedule including the budget and risks to team members, the project and users. 

For this project, it was required that we wrote up an Architecture Design which included:
- The Stakeholders and their concerns.
- The Architectural Viewpoints using Kruchten's 4+1 architecture view model.

### Coding

The coding was often done during lab times when we could work in the same room discussing any problems or choices we needed to solve. The work was separated between the team so that each had their own part to work on.

I worked on:
- The flight simulator which displayed the rocket's location and any data from the rocket while it's in flight and afterwards. This feature allowed the user to track the rocket during flight and find it afterwards. The programming was focused on calculating the area of map required to display the rocket in, resizing the map image to zoom in on the rocket's location, and mapping the journey travelled by the rocket. 
- The controller for the GUI. This feature allowed the user to access the other features offered by the program. The programming focused on mapping a path between the various pages, adding required links in the menu bar, and making the appearance acceptable to a user (colour scheme, readable, etc).
- Code quality. This is the quality of the code, along with the testing of the components. The programming focused on fixing bugs, adding documentation, correcting coding style, and creating tests to ensure coverage. 

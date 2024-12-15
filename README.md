
# Software Requirements Specification (SRS)

Project Name: Real Track Website


1. Introduction
1.1 Purpose
The purpose of this document is to define the software requirements for the Real Track Website. This system enables real-time tracking of up to two users simultaneously, displaying their location and providing directions for the path between them.
1.2 Scope
The Real Track Website is a web-based application designed to provide users with real-time location tracking and navigation capabilities. The system supports the following key features:
•	Real-time tracking of up to two users.
•	Display of user locations on an interactive map.
•	Calculation and display of the shortest path with turn-by-turn directions.
•	Secure and user-friendly interface for location sharing and navigation.
1.3 Definitions, Acronyms, and Abbreviations
•	SRS: Software Requirements Specification
•	API: Application Programming Interface
1.4 References
•	Leaflet Documentation
•	1.5 Overview
•	This document describes the functional and non-functional requirements, design constraints, and system models for the Real Track Website.
2.1 Product Perspective
The Real Track Website will leverage technologies such as Node.js, Express.js, Socket.IO, and the Leaflet.js library for its backend and frontend functionalities. The system will be deployed as a responsive web application compatible with modern browsers and mobile devices.
2.2 Product Features
1.	Real-Time Location Tracking:
o	Track up to two users simultaneously.
o	Update user locations every 5 seconds.
2.	Path Direction Display:
o	Show the shortest path between two users.
o	Provide turn-by-turn directions and estimated time of arrival.
3.	Interactive Map:
o	Display user locations on an interactive map.
o	Allow zooming, panning, and changing map views.
2.3 User Characteristics
•	Users are expected to have basic familiarity with web applications and navigation tools.
•	Targeted primarily at individuals or small groups needing location tracking in real-time.
2.4 Constraints
•	The system can only track a maximum of two users at a time.
•	Internet connection is required for real-time updates.
•	Accuracy depends on the user’s GPS device and network connectivity.
3. Functional Requirements
 Real-Time Tracking
•	The system shall update the location of each user every 5 seconds using Socket.IO for real-time communication.
•	Display both users’ locations on the same map view.
4. Non-Functional Requirements
Compatibility
•	Compatible with modern browsers which supports geolocation (Chrome, Firefox, Safari, Edge).


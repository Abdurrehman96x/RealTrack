
# Software Requirements Specification (SRS)

**Project Name: Real Track Website**

![Image Alt](https://github.com/Abdurrehman96x/RealTrack/blob/4cc9651b3ddc80f84a44bf4392a6713b901ea139/image.png)

1. Introduction <br />
1.1 Purpose <br />
The purpose of this document is to define the software requirements for the Real Track Website. This system enables real-time tracking of up to two users simultaneously, displaying their location and providing directions for the path between them.
1.2 Scope <br /><br />
The Real Track Website is a web-based application designed to provide users with real-time location tracking and navigation capabilities. The system supports the following key features: <br /> <br />
•	Real-time tracking of up to two users.<br />
•	Display of user locations on an interactive map.<br />
•	Calculation and display of the shortest path with turn-by-turn directions.<br />
•	Secure and user-friendly interface for location sharing and navigation.<br /><br />
1.3 Definitions, Acronyms, and Abbreviations<br /><br />
•	SRS: Software Requirements Specification<br />
•	API: Application Programming Interface<br /><br />
1.4 References <br /><br />
•	Leaflet Documentation <br />
•	1.5 Overview<br /><br />
•	This document describes the functional and non-functional requirements, design constraints, and system models for the Real Track Website. <br /><br />
2. Overall Description  ><br /><br />
2.1 Product Perspective<br /><br />
The Real Track Website will leverage technologies such as Node.js, Express.js, Socket.IO, and the Leaflet.js library for its backend and frontend functionalities. The system will be deployed as a responsive web application compatible with modern browsers and mobile devices.<br />
2.2 Product Features<br />
.	Real-Time Location Tracking:<br /><br />
o	Track up to two users simultaneously.<br />
o	Update user locations every 5 seconds.<br />
.	Path Direction Display:<br /><br />
o	Show the shortest path between two users.<br />
o	Provide turn-by-turn directions and estimated time of arrival.<br />
.	Interactive Map:<br /><br />
o	Display user locations on an interactive map.<br />
o	Allow zooming, panning, and changing map views.<br /><br />
2.3 User Characteristics<br />
•	Users are expected to have basic familiarity with web applications and navigation tools.<br />
•	Targeted primarily at individuals or small groups needing location tracking in real-time.<br /><br />
2.4 Constraints<br />
•	The system can only track a maximum of two users at a time.<br />
•	Internet connection is required for real-time updates.<br />
•	Accuracy depends on the user’s GPS device and network connectivity.<br /><br />
3. Functional Requirements<br /><br />
 Real-Time Tracking<br />
•	The system shall update the location of each user every 5 seconds using Socket.IO for real-time communication.<br />
•	Display both users’ locations on the same map view.<br />
4. Non-Functional Requirements<br /><br />
Compatibility<br />
•	Compatible with modern browsers which supports geolocation (Chrome, Firefox, Safari, Edge).<br />


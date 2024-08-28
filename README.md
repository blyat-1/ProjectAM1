# ProjectAM1
Requirements

-Prevent installation of unauthorized applicatations 
-Monitor activity
-Determine and suspicious acts
-create user permissions 


Platfroms
Andriod and windows

DESIGN

Client-Server Model: Often, such applications work on a client-server model where the server manages policies and the client enforces them on individual devices.


Components
Agent: Runs on the client device and enforces policies.
Server: Central management console for monitoring and policy configuration.
Database: Stores information about policies, logs, user data, etc.



Software
Environment Setup

Stack:
Programming 
Set up version control (e.g., Git).
Client Application:

Prevent Unauthorized Apps:
Windows: You might use Group Policy or Windows Defender Application Control.

Monitor Suspicious Activity:
Implement behavior monitoring, which might involve hooking into system APIs or using existing monitoring tools.


Server Application:

Policy Management: Create a web interface for admins to configure policies.
Data Handling: Implement data collection and reporting features.
Communication: Set up secure communication channels (e.g., HTTPS, SSL/TLS) between the server and clients.

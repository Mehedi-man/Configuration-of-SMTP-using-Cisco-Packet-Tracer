Configuration of SMTP and FTP Server using Cisco Packet Tracer
Introduction
This guide walks you through the steps to configure an SMTP (Simple Mail Transfer Protocol) server and an FTP (File Transfer Protocol) server using Cisco Packet Tracer. These services are essential for email communication and file transfer in a network.

Prerequisites
Cisco Packet Tracer installed on your machine.
Basic understanding of networking and TCP/IP protocols.
A basic Packet Tracer project with a network topology.
Table of Contents
Setting up the SMTP Server
Setting up the FTP Server
Configuring Clients
Testing the Configuration
Conclusion
1. Setting up the SMTP Server
To configure the SMTP server on Cisco Packet Tracer, follow these steps:

Step 1: Add SMTP Server
Open Cisco Packet Tracer.
Drag and drop a Server from the End Devices category onto the workspace.
Click on the server to open the device configuration window.
Click on the Config tab.
In the Global Settings, choose SMTP from the services list.
Enter the SMTP server settings, including the server name (e.g., smtp-server.com).
Step 2: Enable SMTP Service
Go to the SMTP tab.
Check the Enabled box to activate the SMTP service on the server.
You can configure additional options like mail queues or logging if necessary.
2. Setting up the FTP Server
Step 1: Add FTP Server
Drag and drop another Server from the End Devices category onto the workspace.
Click on the server to open the configuration window.
Select the Config tab.
In the Global Settings, choose FTP from the services list.
Step 2: Enable FTP Service
Go to the FTP tab.
Check the Enabled box to turn on the FTP service.
You can set a username and password for the FTP server for added security.
Configure the directory structure for files to be uploaded/downloaded.
Step 3: Configure FTP Directories
Under the FTP settings, specify the Directory location for storing files.
Optionally, create directories such as /upload/ or /shared/ for organizational purposes.
3. Configuring Clients
Step 1: Configure Client IP Addresses
On the client computers (PCs or laptops), go to the Desktop tab.
Open IP Configuration and set a static IP address, subnet mask, and gateway for each device. Ensure the gateway matches the router IP.
Step 2: Connect Clients to the SMTP and FTP Servers
Open Command Prompt on the clients.
Test the connection to the servers using the ping command (e.g., ping 192.168.1.1 for the SMTP server IP).
If the ping test is successful, clients should be able to connect to the SMTP and FTP servers.
4. Testing the Configuration
Testing SMTP:
On the client, open the Desktop tab.
Open the Email application.
Configure the email client with the SMTP server settings (e.g., smtp-server.com as the SMTP server).
Send an email from the client to another client or server.
Verify that the email is sent successfully.
Testing FTP:
On the client, open the FTP application from the Desktop tab.
Enter the FTP server's IP address, username, and password.
Browse the directories, upload files, and download files.
Verify that files can be successfully transferred between clients and the FTP server.
5. Conclusion
The SMTP and FTP servers have been successfully configured in Cisco Packet Tracer. By following the above steps, you can send emails using the SMTP protocol and transfer files using FTP within your network.

SMTP allows email communication between clients and servers.
FTP allows the transfer of files between clients and servers, providing an efficient way to manage and share files in a network.
If you encounter any issues during configuration, double-check the server settings, IP configurations, and ensure proper connectivity between devices.

License
This project is licensed under the MIT License.


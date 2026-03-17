📍 GPS Tracking Server

A Java and MongoDB-based GPS tracking server that processes TCP requests from GPS devices compatible with the TK103 protocol.

🚀 Features

📡 Read and parse incoming GPS data streams

🔄 Handle handshake signals and continuous feedback requests

📍 Process real-time location data

⏱️ Track last known location within a 30-second interval

📏 Calculate distance between coordinates

💾 Store processed data in MongoDB

📢 Publish coordinates to messaging topics

📊 Send analytics and system status updates

📧 Email notifications for:

System status reports

Offline devices alerts

🧰 Tech Stack

☕ Java

🍃 MongoDB (v3.6)

⚡ Netty (v4.0)

📩 Apache ActiveMQ (v5.14.5)

📡 Messaging System

The server uses messaging queues for real-time communication:

Topic: COO
Publishes processed GPS coordinates for live tracking

Topic: REQSTATUS
Used for analytics and request status monitoring

➡️ External services can subscribe to:

/topic/COO

to receive live GPS updates.

⚙️ Installation & Setup
🔹 Step 1: Build Project
mvn clean install
🔹 Step 2: Setup Directory

Copy the gps folder to:

/opt
🔹 Step 3: Configuration

Update the configuration file:

system.yml

⚠️ Enable:

ActiveMQ messaging

Email service

🔹 Step 4: Run Server
java -jar GpsServer2-2.0.0.jar
🔄 Run as Background Service (Optional)
Steps:

Rename JAR file:

GpsServer2-2.0.0-jar-with-dependencies.jar → GpsServer.jar

Move file to:

/opt

Copy config file:

gpsserver.conf → /etc/init

Start service:

service gpsserver start
📌 Supported Protocol

✅ TK103 GPS Data Communication Protocol

📊 Functionality Overview

Accepts TCP connections from GPS devices

Parses incoming raw data

Processes and validates location information

Stores coordinates in database

Publishes data for real-time consumption

Generates reports and alerts

📬 Notifications

📧 Periodic system health reports

⚠️ Alerts for inactive/offline GPS devices

📌 Conclusion

This GPS tracking server provides a scalable and real-time solution for tracking GPS devices using TCP protocol, with support for messaging systems and monitoring capabilities.

👩‍💻 Author

Sandhya Patel
🔗 GitHub: https://github.com/Sandhyapatel-24

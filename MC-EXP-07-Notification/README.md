📘 Experiment No. 07 – Message Alert Application

📌 Aim

To implement an Android application that creates an alert upon receiving a message.

🧠 Theory

In Android applications, alerts are used to notify users when a message is received. This is useful in applications such as messaging apps, email apps, banking systems, and reminder services.

Android provides several components to detect incoming messages and notify users. One important component is the Broadcast Receiver, which listens for system events such as receiving an SMS. When a message arrives, the system sends a broadcast signal, and the Broadcast Receiver captures it to trigger an action.

After detecting the message, alerts can be generated using:

Alert Dialogs – Displays a pop-up message on the screen

Notification Manager – Shows notifications in the notification bar

The Notification Manager allows alerts with sound, vibration, and icons, ensuring users do not miss important messages. It also enables users to open the app directly from the notification.

Thus, Android provides powerful tools like Broadcast Receivers, Notifications, and Alert Dialogs for real-time user alerts.

🛠️ Tools & Technologies

Android Studio

Java

XML

Broadcast Receiver

Notification Manager

📂 GitHub Repository

🔗 https://github.com/Sandhyapatel-24/MC_Lab_Sandhya/tree/main/MC-EXP-07-Notification

📊 Output

Application successfully detects incoming messages

Alert is generated using notification or dialog

User is notified instantly upon message reception

📌 Conclusion

In this experiment, an Android application was implemented to generate alerts when a message is received. This helps notify users instantly and improves real-time communication within applications.

# ExcelBulkMailer-Effortless-Email-Distribution-to-Multiple-Recipients
ExcelBulkMailer simplifies mass email distribution by seamlessly sending messages to multiple recipients from an Excel file. Efficient and convenient
ExcelBulkMailer is a Python script designed to simplify the process of sending bulk emails to multiple recipients using an Excel file as the source of recipient email addresses. This script leverages the smtplib library to handle the email sending process and supports Gmail as the SMTP server.

Features
Send bulk emails to multiple recipients listed in an Excel file.
Customizable email subject and message content.
Easy-to-use interface for sending emails in batches.
Usage
Clone the repository to your local machine.
Ensure you have Python installed on your system.
Install the required libraries by running pip install -r requirements.txt.
Replace the placeholders in the script with your sender email, sender password, Excel file path, subject, and message.
Run the script and watch as emails are sent to each recipient listed in the Excel file.
Dependencies
smtplib: For handling the SMTP connection and sending emails.
pandas: For reading data from the Excel file.
Note
Ensure that you have enabled less secure apps access in your Gmail account settings if you are using Gmail as the SMTP server.
Use this script responsibly and ensure compliance with anti-spam regulations and email etiquette guidelines.

How to use this bulkemail,
first type your email and then inplace of password write the app password.
how to get the app password:
To use the email sending functionality, provide your Gmail email address and generate an "App Password" for secure access. To generate an App Password:

Go to your Google Account settings.
Click on "Security" in the left navigation panel.
Under "Signing in to Google," select "App passwords."
If prompted, sign in to your Google Account.
Select "Mail" from the drop-down list and "Other" from the second drop-down list.
Enter a name for the application (e.g., "ExcelBulkMailer") and click "Generate."
Follow the instructions to enter the App Password (16 characters) into the script where "sender_password" is mentioned.
Ensure the Excel file contains a column labeled "Email" with the recipients' email addresses. Customize the "subject" and "message" variables as needed. Run the script to send emails to all recipients listed in the Excel file.
thank you! 




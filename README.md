**Professional Personal Portfolio Website**

A responsive, high-performance personal portfolio website built with vanilla web technologies. This project showcases academic achievements, professional skills, and projects while featuring a serverless contact system integrated with Google Sheets and Gmail.


🚀 **Key Features**

Responsive Design: Optimized for mobile, tablet, and desktop viewing.

Project Showcase: Interactive gallery of development work.

Serverless Contact Form: Uses Google Apps Script to handle submissions without a traditional backend.

Real-time Notifications: Automated email alerts and spreadsheet logging for every inquiry.

Blog Integration: Includes dedicated pages for sharing insights and updates.


🛠️ **Technology Stack**

Frontend: HTML5, CSS3, JavaScript (ES6+)

Middleware: Google Apps Script (JavaScript)

Database/Storage: Google Sheets API

Deployment: Vercel


⚙️ **How the Contact Form Works**

This project implements a bridge between the static frontend and Google Services:

The frontend fetch API sends data to a Google Apps Script Web App.

The script validates the data (with fallbacks for empty subjects).

The message is appended as a new row in a private Google Sheet.

An automated email is sent to the developer via Gmail API.


🚀 **Deployment**

The site is hosted on Vercel. You can view the live version at: https://www.rasib.com.bd/


👨‍💻 **Author**

Mohammad Rasib Iftekhar Nabil
Student ID: C243116
International Islamic University Chittagong (IIUC)


📄 **License**

This project was developed as part of the Software Development I (CSE 2340) course.

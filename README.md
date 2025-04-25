# Chrome-extension-for-time-tracking-and-productivity-analytics
COMPANY: CODTECH IT SOLUTIONS
NAME: MUSTAFIZ AHMED
INTERN ID: CT04WR245
DOMAIN: FULL STACK WEB DEVELOPMENT
DURATION: 4 WEEKS
MENTOR: NEELA SANTHOSH KUMAR

This project is a simple yet powerful Chrome Extension designed to help users track how much time they spend on various websites and analyze their productivity patterns. It automatically logs the duration of each website visit and classifies the sites as either productive (e.g., coding platforms, educational resources) or unproductive (e.g., social media, entertainment).

The extension includes:

A background script that detects active tabs and tracks time spent on each website.

A popup interface that displays a quick summary of productive and unproductive minutes.

A Node.js backend server that stores the data, categorizes the websites, and provides usage summaries.

Whenever a user switches tabs or interacts with the browser, the extension logs the previous tab’s URL and time duration, then sends this data to the backend. The server maintains a simple in-memory database to store this information, classifies URLs based on predefined keywords, and returns analytics when requested.

The system provides:

Real-time tracking of website usage

Simple productivity reports (e.g., total productive vs. unproductive time)

Weekly analytics (easily extendable)

This tool is especially useful for students, professionals, and remote workers looking to become more aware of their online habits and manage their time better.

# HCI_Fedex_Project
MSSTATE Human Computer Interaction Class - Fedex Alert Management Dashboard 


### Team : On Site
### Team Members
Alief Twumasi - Employee Page, Routes Page, Weather Widget
Brisa Chora - Login page, Homepage, Routes Page 
Brandon Marks - Routes Page
Michael Gonzales - Urgent Alerts
Zoe McGee - Homepage
Ladarius Course - Routes Page 

### Overview
Convey alerts to location management
in a hierarchical order

### Assumptions:
- All Divisions
- Alerts affecting the specific FedEx location
- Real-time and historical data available to user
- Reveals critical alerts that will impact operations
- All levels of management will have access to alerts generated for their locations

### Feedback
The user feedback that we got weren't for major changes to our application. We learned that we were moving the right direction with how it looked because most people thought it was easy to navigate and understand. Most critiques were about small little things like the color, how things weren't lined up properly, and that our weather icon was too simple. ​

So, in the end we kept to a similar design for the final prototype changed a lot of the color that we had before, lined up our widgets better when you click on them, and adding a better weather icon that sures more information. ​

​### Development Challenges:
Beginners to HTML, CSS, and JavaScript, so we had to learn it on top of developing this application.



Getting started #
Flowbite can be easily integrated into your project through NPM. It functions as a plugin for Tailwind CSS and offers both a data attributes interface and a JavaScript API for powering interactive UI components.

Require via NPM #
Make sure that you have Node.js and Tailwind CSS installed.

Install Flowbite as a dependency using NPM by running the following command:
npm install flowbite
Require Flowbite as a plugin inside the tailwind.config.js file:
module.exports = {

    plugins: [
        require('flowbite/plugin')
    ]

}
Additionally to your own content data you should add flowbite to apply the classes from the interactive elements in the tailwind.config.js file:
module.exports = {

    content: [
        "./node_modules/flowbite/**/*.js"
    ]

}
Require the JavaScript code that powers the interactive elements before the end of your <body> tag:
<script src="../path/to/flowbite/dist/flowbite.min.js"></script>
Learn more about the Flowbite JavaScript API and functionalities in the JavaScript section.

### INSTALL Chart.JS for graphs

npm install chart.js

# HCI_Fedex_Project
MSSTATE Human Computer Interaction Class - Fedex Alert Management Dashboard 


### Team : On Site
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

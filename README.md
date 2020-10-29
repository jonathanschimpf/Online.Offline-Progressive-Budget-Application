# Online/Offline Budget Tool
‎
‎‎![License](https://img.shields.io/static/v1?label=License&message=MIT&color=brightgreen) 
![License](https://img.shields.io/static/v1?label=Language&message=JavaScript&color=yellow)
![License](https://img.shields.io/static/v1?label=Language&message=Chart.js&color=red) 
![License](https://img.shields.io/static/v1?label=Language&message=Node.js&color=green)


![License](https://img.shields.io/static/v1?label=Language&message=MongoDB&color=blueviolet)
![License](https://img.shields.io/static/v1?label=Language&message=Mongoose&color=blue)
![License](https://img.shields.io/static/v1?label=Language&message=Express.js&color=yellowgreen)    ![License](https://img.shields.io/static/v1?label=Language&message=HTML5&color=orange) ![License](https://img.shields.io/static/v1?label=Language&message=CSS3&color=blue) 
  

  ---
  
  <p>&nbsp;<p>
    

## Description 

<p>&nbsp;<p>

<strong><em>What is this project? Why did you make this project? How did you make this project?</strong></em>

<p>&nbsp;<p>

This project is an intuitive budgeting tool that allows a user to keep track of their deposits and expenses. These entries are stored in a table format with their provided description and amount, and visualized over time in a date stamped line chart as well (Thanks to `Chart.js`). This is a progressive web application that can be used both online, and offline if necessary. In the event that a connection is lost during use, transaction entries will be stored temporarily in `IndexedDB` "pending" storage, and then permanently added to the `MongoDB` database once a connection can be established again. A `Service Worker` file provides a cached version of the website when using offline so the user interface can continue to be utilized during an outage. This provides reliability at all times, specifically during moments of unpredictable connectivity or during travel when data/wifi might not necessarily be available in the moment. This responsive application is optimized for all screen sizes and it's capabilities can be enjoyed in both a mobile or desktop setting.

<p>&nbsp;<p>


View the application here =>‏‏‎ ‎‏‏‎ ‎‏‏‎ ‎‏‏[`Online/Offline Budget Tool`](https://onlineoffline-budget-app.herokuapp.com/)


<p>&nbsp;<p>


---

<p>&nbsp;<p>


## Table of Contents: 

<p>&nbsp;<p>

* [Usage](#usage)
* [License](#license)
* [Credits](#credits)
* [Questions](#questions)

<p>&nbsp;<p>

---


<p>&nbsp;<p>


## Usage


<p>&nbsp;<p>


<strong><em>Instructions and examples for usage + development details:</strong></em>

<p>&nbsp;<p>


Log on to:‏‏‎ ‎‏‏‎ ‎‎‏‏[`Online/Offline Budget Tool`](https://onlineoffline-budget-app.herokuapp.com/). Get started by simply adding a description of your budgetary item and the value associated. If this is an expense then select the "- Reduce Funds" submit button, and use the "+ Add Funds" submit button for all deposits. After submitting you'll see a live update of your entry populate on a table directly below, and the line chart will update displaying the visualization for said entry as well. The application will scroll into view below automatically upon submit, giving you the exact view of this data. Feel free to add more entries when neeeded. 

<p>&nbsp;<p>



<p>&nbsp;<p>


[![IMAGE](public/assets/images/screengrab.jpg)](https://onlineoffline-budget-app.herokuapp.com/) 


<p>&nbsp;<p>


--- 


<p>&nbsp;<p>



[![IMAGE](public/assets/images/screengrab_2.jpg)](https://onlineoffline-budget-app.herokuapp.com/) 


<p>&nbsp;<p>
 


---

<p>&nbsp;</p>

<p align= "center"><img src="public/assets/images/Online_Offline_Budget_Tool_Final.gif" alt="animated" href="https://onlineoffline-budget-app.herokuapp.com/" /></p>

<p>&nbsp;</p>  


---



<p>&nbsp;<p>


## License


<p>&nbsp;<p>


This project is covered under the MIT license. 


<p>&nbsp;<p>


---


<p>&nbsp;<p>


## Credits


<p>&nbsp;<p>


<strong><em>Third party assets:</strong></em>


<p>&nbsp;<p>

`Node.js` =>‏‏‎ ‎ ‏‏‎ ‎[An asynchronous event-driven runtime built on Chrome's V8 JavaScript engine.](https://nodejs.org/en/)


<p>&nbsp;‏‏‎‏‏‎ ‎<strong>+</strong></p>


`Express.js` =>‏‏‎ ‎ ‏‏‎ ‎[A fast, unopinionated, minimalist web framework for Node.js.](https://expressjs.com/)


<p>&nbsp;‏‏‎‏‏‎ ‎<strong>+</strong></p>



`MongoDB` =>‏‏‎ ‎ ‏‏‎ ‎[The most popular databse for modern apps.](https://www.mongodb.com/)


<p>&nbsp;‏‏‎‏‏‎ ‎<strong>+</strong></p>


`Mongoose npm` =>‏‏‎ ‎ ‏‏‎ ‎[A MongoDB object modeling tool designed to work in an asynchronous environment. ](https://www.npmjs.com/package/mongoose)


<p>&nbsp;‏‏‎‏‏‎ ‎<strong>+</strong></p>


`Chart.js` =>‏‏‎ ‎ ‏‏‎ ‎[Simple yet flexible JavaScript charting for designers & developers.](https://www.chartjs.org/)



<p>&nbsp;‏‏‎‏‏‎ ‎<strong>+</strong></p>


`Bootstrap CDN` =>‏‏‎ ‎ ‏‏‎ ‎[An pen-source CSS framework directed at responsive, mobile-first front-end web development.](https://getbootstrap.com/)



<p>&nbsp;‏‏‎‏‏‎ ‎<strong>+</strong></p>



`Heroku` =>‏‏‎ ‎ ‏‏‎ ‎[A platform that enables developers to build, run, & operate applications entirely in the cloud.](https://www.heroku.com)



<p>&nbsp;‏‏‎‏‏‎ ‎<strong>+</strong></p>


`Compression npm` =>‏‏‎ ‎ ‏‏‎ ‎[Node.js compression middleware.](https://www.npmjs.com/package/compression)



<p>&nbsp;‏‏‎‏‏‎ ‎<strong>+</strong></p>


`JSCompress` =>‏‏‎ ‎ ‏‏‎ ‎[An online JavaScript compressor that allows you to minify files by up to 80%.](https://jscompress.com/)


<p>&nbsp;‏‏‎‏‏‎ ‎<strong>+</strong></p>


`Morgan npm` =>‏‏‎ ‎ ‏‏‎ ‎[HTTP request logger middleware for node.js that is named after Dexter.](https://www.npmjs.com/package/morgan)

<p>&nbsp;<p>

---


<p>&nbsp;<p>


## Questions?


<p>&nbsp;<p>


Shoot me an e-mail! => jonathan@jonathanschimpf.com

<p>&nbsp;<p>


Check out more of my work here on =>
[GitHub](http://github.com/jonathanschimpf)

<p>&nbsp;<p>






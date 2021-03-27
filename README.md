<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <nav>
   <ul>
    <li><a href="home.html">Home</a></li>
    <li><a href="Services.html">Services</a></li>
    <li><a href="About.html">About us</a></li>
    <li><a href="Portfolio.html">Portfolio</a></li>
    <li><a href="contact.html">Contact us</a></li>
  </ul>
</nav>
<meta charset="utf-8">
<title>thewebsite.sol</title>
<link rel="stylesheet" href="Style.css">

  </head>
  <body>
<h1>Home</h1>
  </body>
   <footer>
    @copyright AP 2021, All rights Reserved
   </footer>
</html>

h1 {
  text-align: center;
}
body{
  margin: 0;
  padding: 0;
}
/*footer*/
footer {
  background-color: #F1F1F1;
  text-align: center;
  padding: 10px;
}
ul {
  text-align: center;
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
  position: -webkit-sticky; /* Safari */
  position: sticky;
  top: 0;
}

li {
  display: inline-block;
}

li a {
  display: inline-block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change the link color to #111 (black) on hover */
li a:hover {
  background-color: #111;
}

h4 {
  text-align: center;
  padding: 5%;
  margin: 0;
  font-size: 20px;
}
.column {
  float: left;
  width: 30%;
  padding: 10px;
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
screen and (max-width:600px) {
  .column {
    width: 100%;
  }
}

* {
  box-sizing: border-box;
}
/* Contact us page */
/* Style inputs */
input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #4CAF50;
  color: white;
  padding: 12px 20px;
  border: none;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

/* Style the container/contact section */
.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 10px;
}

/* Create two columns that float next to eachother */
.column {
  float: left;
  width: 50%;
  margin-top: 6px;
  padding: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}

---
title: Contact || Kellie Ortiz's Portfolio
layout: base.njk
tags: navItem
---

<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="x-ua-compatible" content="ie=edge">
        <title>Kellie Ortiz's Portfolio</title>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="css/style.css">
    </head>
<body>
  <div class="main-box">
<header>
  <img src="logo.png" alt="banner" class="banner" width="800" height="250">
  <nav id="main-nav">
  <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="art.html">Art</a></li>
      <li><a href="design.html">Design</a></li>
      <li>Contact</li>
  </ul>
  </nav>
</header>
<h2>Keep In Touch!</h2>
<div class="container">
    <form action="action_page.php">
  
      <label for="fname">First Name</label>
      <input type="text" id="fname" name="firstname" placeholder="Your name..">
  
      <label for="lname">Last Name</label>
      <input type="text" id="lname" name="lastname" placeholder="Your last name..">
  
      <label for="country">Country</label>
      <select id="country" name="country">
        <option value="australia">Australia</option>
        <option value="canada">Canada</option>
        <option value="usa">USA</option>
      </select>
  
      <label for="subject">Subject</label>
      <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
  
      <input type="submit" value="Submit">
  
    </form>
  </div>
  </div>
</body>
</html> 
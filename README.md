# nodejs-assignment

This repository contains a Simple Blog Website. Developed using Nodejs and MongoDB.<br>
This is a Voosh's Backend Assingnment.<br>
This Assignment contains functionalities.<br>
User Registration: Users can create a new account by providing necessary details.<br>
User Login: Registered users can log in to their accounts.<br>
User Logout: Users can securely log out of their accounts.<br>
Profile Viewing: Users can view their profile details.<br>
Profile Editing: Users can edit their profile information including photo, name, bio, phone, email, and password.<br>
Photo Upload: Users can upload a new photo or provide an image URL for their profile picture.<br>
Profile Privacy: Users can choose to make their profiles either public or private.<br>
Admin Access: Admin users have access to both public and private user profiles.<br>
User Access: Normal users can only view public user profiles.<br>
Thank You !!!<br>
Here is a working copy of Website:  <br>
<h1>Steps to start Working</h1>
<ol>
  <li><h3>Setup Node on your Machine</h3>
    <h4>Installing Node and NPM</h4>
    <code>sudo apt-get install nodejs</code><br>
    <code>sudo apt-get install npm</code>
  </li>
  <li><h3>Setup MongoDB</h3>
    <p>Totally optional if you don't want any database but it won't hurt to have some content in your mind to style better.</p>
    <h4>if mongo in not installed then type this command</h4>
    <code>sudo apt-get install mongodb</code><br>
    <ul>
      <li>Make a folder with name <b>data</b> in your home directory.<br>
        <code>mkdir data</code>
      </li>
      <li>Then create a file with name <b>mongod</b> in your home directory.<br>
      <code>touch mongod</code><br>
      <code>sudo chmod +777 mongod</code>
      </li>
      <li>finally open up file with gedit type following code<br>
        <h4>type in terminal</h4>
        <code>echo "mongod --dbpath=data">mongod</code>
      </li>
    </ul> 
  </li>
  <li><h3>Finally running locally app</h3>
  <ul>
    <li>Run the Mongo Configuration File you Created above</li>
    <code>./mongod</code>
  <li>navigate to the main folder where app.js is located and type</li>
      <code>npm install</code>
      <code>node app.js</code>
    </ul>
    </li>
</ol>
<br><br>
<h4>==================================</h4>
<h3>If your mongod service is giving you some error</h3>
<h4>try these commands</h4><br>
<code>mongo</code><br>
<code>use admin</code><br>
<code>db.shutdowmServer()</code><br>
<code>db.shutdowmServer()</code><br>
this error is commonly due to some other service running on the port which mongo service listen is preoccupied by some other service

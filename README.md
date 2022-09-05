# Greenwiz-Assignment

   Assignment

##Overview:
Write a code which will take a website link as an input and download images of that.


##I have done it in four steps:-
Step 1:- In step 1, I have imported all the modules which are used in our project.
Step 2:- Here we write the logic where we found a url of images from websites.
Step 3:- Here we write the logic where we downloaded the file from the url of images of websites.
Step 4:-  Once the url file is downloaded after that we write the logic where we have to store the images in our local folders.

##Modules Used:-
1.cheerio:- Cheerio is a tool for parsing HTML and XML in Node. js, and is very popular with over 23k stars on GitHub. It is fast, flexible, and easy to use.
Know more → https://www.npmjs.com/package/cheerio

2.axios:- Axios is a promise-based HTTP Client for node. js and the browser. It is isomorphic (= it can run in the browser and nodejs with the same codebase). On the server-side it uses the native node. js http module, while on the client (browser) it uses XMLHttpRequests
Know more → https://www.npmjs.com/package/axios

3.https:- The HTTPS module provides a way of making Node. js transfer data over HTTP TLS/SSL protocol, which is the secure HTTP protocol.
Know more → https://www.npmjs.com/package/https

4.fs:- The Node.js file system module allows you to work with the file system on your computer. To include the File System module, use the require() method: var fs = require('fs');
Know more → https://www.npmjs.com/package/fs

5.mime-types:- MIME types—also sometimes called Internet media types or Content-types—describe the media type of content either contained in email or served by web servers or web applications, and are intended to help guide a web browser to correctly process and display the content.
Know more →https://www.npmjs.com/package/mime-types 


##Why we used this module in this assignment:-
1.With the help of cheerio we are parsing the html document of the websites for getting all the url which is written in the program and also we are finding the location of the url of  images with this module.
2.With the help of axios library we are sending the request of our domain and we get the response from the  domain which is what we want so that's why we use this module.
3.After that we are using fs module for the read of file and write in our directory 
4.And with the help of https module we are getting the url and after that we are downloaded the images in our local folders 
5.And finally we are using mime-types to handle the media types or content-types.


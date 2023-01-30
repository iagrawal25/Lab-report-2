# Lab Report 2
## Part 1: Creating a Web Server
* We will be creating a web server called 'StringServer' which will take incoming requests and print the same string on the screen.
* Strings can be added by using the following request:

> /add-message?s=<string> 
* Each new string will be added to a new line ("/n").
* For example, if I enter 'https://localhost:4000/add-message?s=hey_there' the webpage will look like this:  

![Image](ss2.png)

  

* Now, if I enter 'add-message?s=whats_up' the webpage will add this new string in a new line and display the message.

![Image](ss3.png)

# Step 1- Installing Apache and Updating the Firewall
## The following Command updates a list of packages in package manner.

`sudo apt update`

![Image1](./Images/Image1.PNG)

## The following Command runs Apache2 Package Installation(This was a redo so the result was showing it was indstalled already)

`sudo apt install apache2`

![Image2](./Images/Image2.PNG)

### This code verifies that Apache 2 is running in my server.

`sudo systemctl status apache2`

![Image3](./Images/Image3.PNG)

### Opened TCP port 80 in the EC2 Instance which is the default port that web browsers use to access web pages on the Internet

![Image4](./Images/Image4.PNG)

### This output confirms access to Apache2 Locally

![Image5](./Images/Image5.PNG)

### Test page showing Apache server is running over the browser.

![Image6](./Images/Image6.PNG)
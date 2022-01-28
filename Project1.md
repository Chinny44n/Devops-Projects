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

# Step 2-Installing MySQL
### The following command installs the MySQL in the server. (The result shows it has already beem installed as this is a rework of Project 1)

`$ sudo apt install mysql-server`

![Image7](./Images/Image7.PNG)

### The following command runs a security script that removes sime insecure default settings and lock down access to the database system

`$ sudo mysql_secure_installation`

![Image8](./Images/Image8.PNG)
![Image9](./Images/Image9.PNG)

### This code verifies that we can log in to the MySQL server

`$ sudo mysql`

![Image10](./Images/Image10.PNG)

# Step 3-Installing PHP

### The following command installs php , libapache2-mod-php and php-mysql

`$ sudo apt install php libapache2-mod-php php-mysql`

![Image11](./Images/image11.PNG)

### The following command confirms the PHP Version

`$ php -v`

![Image12](./Images/Image12.PNG)
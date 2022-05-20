
## Understanding LAMP stack implementation
### Setting up an EC2 instance 
An EC2 instance is created and connected through a local host.
![ec2_instance](./img/1%20connecting%20to%20ec2.png)
The package is updated so as to get it up and running.
![udating_package](./img/2%20updating%20package.png)
### Step one(Installing apache2)
Apache2 server is installed in the virtual machine.
![installing_apache2](./img/3%20install%20apache2.png)
Result indicating that apache2 server is up.
![apache2_server_up](./img/4%20apache2%20server%20up.png)
Communicating to server locally through powershell.
![connecting_to_server_locally](./img/5%20connecting%20to%20server%20locally.png)
Communicating to server via the web.
![connecting_to_server_via_web](./img/6%20connecting%20to%20server%20via%20web.png)
### Step two(Installing mysql)
Mysql is installed in the instance.
![mysql_installed](./img/7%20mysql%20installed.png)
Then secured installation is set. A password is also set, then mysql prompts to enter login details. Access is granted into mysql space.
![login_to_mysql](./img/8%20login%20to%20mysql.png)
### Step three(Installing php)
php is installed into the EC2 instance.
![installing_php](./img/9%20installing%20php.png)
### Step four(Creating a virtual host)
First a host is created in apache2 to server this EC2 instance personally.
![creating_a_host](./img/10%20creating%20a%20host.png)
A virtual web host is created.
![creating_a_web_host](./img/11%20creating%20a%20virtual%20web%20host.png)
A message is composed and sent to the server in order to verify that it can be seen through the web.
![message_sent_to_the_server](./img/12%20message%20sent%20to%20the%20server.png)
The server is reloaded and apache2 is ran.
![reload_server](./img/13%20reload%20and%20run%20apache2.png)
### Step five(Enable php on the website)
Then apache2 server is removed as the default path in order to give php presedence.
![removing_apache_as_default](./img/14%20removing%20apache%20as%20default.png)
The public key is used to access the website attaching /info.php
![php_enabled](./img/15%20accessing%20the%20server%20via%20web.png)

# CLIENT/SERVER ARCHITECTURE USING A MYSQL RELATIONAL DATABASE MANAGEMENT SYSTEM

## Client-server architecture with mysql


Create and configure two Linux-based virtual servers (EC2 instances in AWS).
Server A name - `mysql server`
Server B name - `mysql client`

On mysql server Linux Server install MySQL Server software

![server](./Images/my-server.PNG)

On mysql client Linux Server install MySQL Client software

![client](./Images/client.PNG)

`sudo vi /etc/mysql/mysql.conf.d/mysqld.cnf`

![bind](./Images/bind-address.PNG)

From mysql client Linux Server, connect remotely to mysql server Database Engine without using SSH.

## Server configuration 

![localhost](./Images/Local-host.PNG)

New database

![new-database](./Images/Created-new-database.PNG)

New user

![new-user](./Images/created-new-user.PNG)

Connection from client side

![Access](./Images/Accessed-new-user.PNG)

Show databases


![database](./Images/Show-databases.PNG)
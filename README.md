# Supporting_System 

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/Django.svg)


This is Supporting system using Tornado Web server.

Version : 1.0

Build : Passing

Author : Maryam Saeedmehr

Language : Python Both 2.7 - 3.6.5




# **PreRequirements**

For This Project You Need below Requirements :
- pyhon
- mysql

```shell
$ apt install python mysql
```

# **Requirement**

For runnig code.py file You Need to install below pakcage for python  :

- tornado 
- MySQLdb


```shell
$ pip install 
$ pip install MySQL-python
```

# **install**
## Step0 : Cloning

First of All Clone the Project : 

```shell
$ git clone https://github.com/MaryamSaeedmehr/Supporting_System
```

## Step1 : Connect to MySQL and create a database

Connect to MySQL as a user that can create databases and users:

```shell
$ mysql -u root
```
    
Create a database named "tickets":
    
```shell
mysql> CREATE DATABASE tickets;
```
    
Allow the "maryam" user to connect with the password "7731":
    
```shell
mysql> GRANT ALL PRIVILEGES ON tickets.* TO 'maryam'@'localhost' IDENTIFIED BY '7731';
```

## Step2 : Create the tables in your new database

You can use the provided bankdb.sql file by running this command:

```shell
$ mysql --user=maryam --password=7731 --database=tickets < dataBase.sql
```

You can run the above command again later if you want to delete the
contents of the tickets and start over after testing.

Then now you Must Put Database information in code.py from line 13 - 16

## Step3 : Run the Supporting_System project


With the default user, password, and database you can just run:

```shell
$ python code.py
```

# **Usage**

Now For Sending Requests You Have 2 Options :
1. Postman
2. Our Client Code

## POSTMAN :
Download and install <a href="https://www.getpostman.com/apps" target="_blank">**Postman**</a>. 

In our Project We Support Both POST & GET Method for Requesting

You Can See Example Below : 

### GET :


![GET GIF](https://highhost.org/gif-video/bank-project-Server-GET.gif)



### POST :


![POST GIF](https://highhost.org/gif-video/bank-project-Server-POST.gif)

## OUR CLIENT CODE:

Just Go To Client Folders and Run Below Code : 

```shell 
$ pip3 install requests
$ python3 client-[METHOD].py
```

### GET :


![GET GIF](https://highhost.org/gif-video/bank-project-Client-GET.gif)



### POST :


This section has not been completed yet


# **Support**

Reach out to me at one of the following places!

- Telegram at <a href="https://t.me/msaeedmehr" target="_blank">@msaeedmehr</a>
- Gmail at <a href="mailto:maryamsaeedmehr@gmail.com" target="_blank">maryamsaeedmehr@gmail.com</a>

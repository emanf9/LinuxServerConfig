# Linux Server Configuration for the Item Catalog Project by Ethan Falck

IP Address of Server: 18.217.170.155
SSH Port: 2200
Complete URL for Application: http://18.217.170.155/

The software installed onto the standard Ubuntu server is as follows: Apache, WSGI, Virtual Enviornment, Pip, Flask, HTTPlib, OAuth2, Psycopg, SQL Alchemy, PostgreSQL, and Requests.
The sudoers file was edited to include the user grader. The firewall was configured to only accept NTP, HTTP, and SSH from 2200. The sshd_config file was edited to disable root login.

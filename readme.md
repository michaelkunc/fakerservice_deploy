# Airflow Deploy

An Ansible playbook for installing and configuring Apache Airflow. 
This playbook will override the standard SQLite installation and provide a MySQL instance to hold metadata.

# Assumptions
A non-root user with sudo rights.
Python 2.7 
Ubuntu 17.04

# Other notes
I use fabric to perform some basic bootstrapping of the server. The fabric script creates a user called data_engineer and gives the role sudo rights.

 
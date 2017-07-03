# Udacity Nanodegree 

# Build an Item Catelog Application

> Scot Pfleghaar

## About
Developed an application that provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items.

## Programming Languages, Technologies, and Framworks Used
  * Python
  * Flask
  * JSON
  * HTTP
  * HTML5
  * CSS3
  * SQLalchemy
  * Ajax

## To Run

### You will need the following:
  * [Python3](https://www.python.org/)
  * [Vagrant](https://www.vagrantup.com/)
  * [VirtualBox](https://www.virtualbox.org/)
  * [Google Developer Account](https://developers.google.com/)
### Setup

First, you'll need all the related dependacies:
```
  $ pip install -r setup.txt
```
Next, you'll need to load the information from the database:
```
  $ python database_setup.py
```
```
  $ python lotsofmenus.py
```



### To Run

Launch the Vagrant VM inside Vagrant sub-directory using the following command:
  
  ```
    $ vagrant up
  ```
Then Log into this using command:
  
  ```
    $ vagrant ssh
  ```
  Next, Change directory to vagrant:
  ```
    $ cd /vagrant
  ```
  Run 
  ```
  python main_catalog.py
  ```
  Finally, in your browser go to [http://localhost:8000](http://localhost:8000)
  
  ## To Close

To close the application enter CTRL-C in the terminal

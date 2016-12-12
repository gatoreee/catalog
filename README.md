# catalog
Project: Catalog - [Enrique B]
================================

Required Libraries and Dependencies
-----------------------------------
The project presents an online guitar catalog. It uses SQLite, Python and Bootstap and allows users to log-in with their fb or google+ accounts. Development was done using a Vagrant VM provided by the Udacity team. In order to replicate the development and test environment, this Vagrant VM should be installed.

How to Run Project
------------------
The project repository can be found at https://github.com/gatoreee/catalog. Save all files to a local folder named 'catalog' inside the Vagrant VM folder. In order to run the application, open a command prompt and follow the instructions below: 
1) From the command prompt, run the 'vagrant up' command. This should launch the Vagrant VM
2) From the command prompt, run the 'vagrant ssh' command. This will connect and log you into the Vagrant VM
3) From the vagrant command prompt, run the command 'cd /vagrant/catalog' to take you to the folder where the files are saved
4) Add your app_id and app_secret to the fb_client_secrets.json file in order to support fb login 
5) Add your client_id and client_secret to the client_secrets.json file in order to support google+ login 
6) From the vagrant command line, run the 'python catalog.py' command
7) Open browser and go to http://localhost:8000/; to view json endpoints go to http://localhost:8000/catalog/json or http://localhost:8000/category/json (categories are: Electrics, Acoustics, Basses, Classicals, Amplifiers, Effects) or http://localhost:8000/category/item/json

Extra Credit Description
------------------------
I added support for retrieving and displaying the user's profile picture from fb or google+. I also introduced Bootstrap for a more responsive application.

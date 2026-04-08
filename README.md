[Webserver-Commands.txt](https://github.com/user-attachments/files/26571491/Webserver-Commands.txt)# 🚀 LAMP Stack Deployment on AWS EC2

This project demonstrates the deployment of a LAMP (Linux, Apache, MySQL, PHP) stack on an AWS EC2 instance with a working web application.

---

## 📌 Project Overview

* Deployed Apache Web Server on Ubuntu EC2
* Configured PHP for dynamic web pages
* Installed and secured MySQL database
* Connected PHP with MySQL
* Built a feedback form storing user input

---

## 🛠️ Tech Stack

* AWS EC2 (Ubuntu)
* Apache2
* PHP
* MySQL
* Linux

---

## ⚙️ Setup Process

1. Launch EC2 instance
2. Configure Security Group (Allow HTTP - Port 80)
3. Install Apache Web Server
4. Install PHP and modules
5. Install MySQL server
6. Connect PHP with MySQL
7. Deploy application in `/var/www/html`

---

## 💻 Features

* Custom Apache Web Page
* PHP Server Running Successfully
* Database Connection Working
* Feedback Form with Data Storage

---

## 📸 Screenshots
 
 <img width="960" height="1020" alt="01-apache-default" src="https://github.com/user-attachments/assets/0f0bb03c-e60d-4727-a11f-57ba7da10ddb" />

---<img width="960" height="1020" alt="02-custom-page" src="https://github.com/user-attachments/assets/071eb0b8-d963-4350-bf75-cfb1d518970b" />

<img width="960" height="1020" alt="03-php-working" src="https://github.com/user-attachments/assets/7f6c1739-742d-47a4-b7ef-68303a50f21a" />

<img width="960" height="1020" alt="04-db-connected" src="https://github.com/user-attachments/assets/1162cf25-be11-4e84-9e40-0768521cd60f" />

<img width="960" height="1020" alt="05-feedback-form" src="https://github.com/user-attachments/assets/3a96208f-c853-43f9-aabc-101e1e1cbca6" />


## 📂 Commands Used


See full setup commands:
[Uploading Webserver-Command    2  apt update
    3  apt upgrade -y
    4  apt install apache2 -y
    5  systemctl start apache2
    6  systemctl enable apache2
    7  systemctl status apache2
    8  systemctl restart apache2
    9  systemctl status apache2
   10  curl http://100.53.249.35
   11  cd /var/www/html
   12  ls
   13  sudo rmindex.html
   14  sudo rm index.html
   15  nano index.html
   16  apt install php libapache2-mod-php -y
   17  php -v
   18  cd /var/www/html
   19  sudo nano index.php
   20  sudo rm index.html
   21  sudo systemctl restart apache2
   22  apt install mysql-server -y
   23  systemctl status mysql
   24  mysql_secure_installation
   25  mysql
   26  mysql_secure_installation
   27  mysql
   28  cd /var/www/html
   29  nano db.php
   30  sudo systemctl restart apache2
   31  systemctl restart apache2
   32  systemctl enable apache2
   33  systemctl status apache2
   34  curl http://100.53.249.35
   35  curl http://100.53.249.35/db.php
   36  cd ..
   37  apt install php-mysql -y
   38  systemctl restart apache2
   39  systemctl enable apache2
   40  systemctl status apache2
   41  sudo tail -n 20 /var/log/apache2/error.log
   42  sudo mysql
   43  mysql
   44  cd /var/www/html
   45  nano index.php
   46  systemctl restart apache2
   47  nano index.php
   48  systemctl restart apache2
   49  cd ..s.txt…]()


---

## 🎯 What I Learned

* AWS EC2 deployment
* Security Groups & Networking
* Apache Web Server setup
* PHP & MySQL integration
* Debugging real-world deployment issues

---

## 🚀 Future Improvements

* Automate using Ansible
* Dockerize application
* Add CI/CD pipeline

---

## 👩‍💻 Author

Priyanshi Kothari

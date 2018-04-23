# Ansible role – Snipe-IT (Docker)

Ansible role for setting up and configuring [Snipe-IT](https://snipeitapp.com/) using Docker.


## Variables

* **nginx\_proxy\_version** – Nginx proxy docker container version [latest]

* **snipeit\_debug\_mode** – Snipe-IT debug mode enabled [false]

* **snipeit\_directory** – Snipe-IT data and database directory [/srv/snipeit]

* **snipeit\_domain\_name** – Snipe-IT url

* **snipeit\_mail\_encryption** – Mail encryption protocol [tls]

* **snipeit\_mail\_from\_name** – "Mail from" name [Snipe-IT]

* **snipeit\_mail\_port** – Snipe-IT mail port [587]

* **snipeit\_mysql\_version** – MySQL docker container version [5.6]

* **snipeit\_version** – Snipe-IT docker container version

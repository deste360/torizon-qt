# Simple app
Simple Qt app test running on **Toradex Colibri iMX7** with Torizon

Recreate the example on Toradex documentation [here](https://developer.toradex.com/knowledge-base/debian-container-for-torizon) using docker-compose, for start up calculator Qt application on power on.

Based on *torizon/arm32v7-debian-weston:latest* and *torizon/arm32v7-debian-qt5-wayland:latest*


## How to run this test

* Install Torizon with Docker support on Colibri iMX7 using **Toradex Easy Installer**
* Login to Torizon (initial username and password: *torizon*, password must be change at first login)
* Git clone repository **deste360/torizon-qt** on your development machine by `git clone https://github.com/deste360/torizon-qt`
* Copy **simple-app** directory to Torizon (you can use WinSCP by SSH)
* Using Torizon console enter to **simple-app** directory and launch `docker-compose up`
* You should see the Qt calculator example application; it should start automatically when reboot

---
layout: post
title:  "Raspberry Pi Development Notes"
date:   2018-10-02 17:54:49 +0800
categories: article researchnotes raspberrypi
---

How to ssh to a Raspberry Pi

~~~
# password: raspberry
$> ssh pi@192.168.2.173
~~~

~~~

$> sudo apt-get update

$> sudo apt-get install -y git curl zlib1g-dev subversion
$> sudo apt-get install -y openssl libreadline6-dev git-core zlib1g libssl-dev
$> sudo apt-get install -y libyaml-dev libsqlite3-dev sqlite3
$> sudo apt-get install -y libxml2-dev libxslt-dev
$> sudo apt-get install -y autoconf automake libtool bison
sudo apt-get install nodejs

$> curl -sSL https://rvm.io/mpapis.asc | gpg --import -
$> curl -sSL https://get.rvm.io | bash -s stable --rails

$> source /home/pi/.rvm/scripts/rvm
~~~

To run a Jekyll enabled site on RPi 
~~~
$> jekyll serve --host 0.0.0.0
~~~



To generate a API only rails application
~~~
$> rails new <rails app name> --api --skip-action-cable --skip-active-storage
~~~



### Notable Articles
- [How to Install Ruby on Rails on Raspberry Pi 3`](https://parsun.com/2017/09/23/how-to-install-ruby-on-rails-on-raspberry-pi-3/)
- [Fixing Rails 5.2 Bus Error on ARMv7/Raspberry Pi](https://romkey.com/2018/05/14/fixing-rails-5-2-bus-error-on-armv7-raspberry-pi/)
- [REST Service For The Udoo Neo Gpios and Sensors](https://www.udoo.org/rest-service-for-the-udoo-neo-gpios-and-sensors/)
- REST service for the UDOO NEO GPIO's and sensors. [GitHub, marksull/udooneorest](https://github.com/marksull/udooneorest)
- [How to Clone Raspberry Pi SD Cards Using the Command Line in OS X](https://computers.tutsplus.com/articles/how-to-clone-raspberry-pi-sd-cards-using-the-command-line-in-os-x--mac-59911)
- [artoo.io, Next generation robotic framework](http://artoo.io/)
- [artoo connecting to Raspberry Pi through artoo-raspi gem](http://artoo.io/documentation/platforms/raspberry-pi/)
- [Evented GPIO on Raspberry PI with Ruby](https://tenderlovemaking.com/2017/01/17/evented-gpio-on-raspberry-pi-with-ruby.html)
- [Calling C/C++ from Ruby](https://www.amberbit.com/blog/2014/6/12/calling-c-cpp-from-ruby/)
- [Stackoverflow, How do I install crystal-lang on rapsberry pi?](https://stackoverflow.com/questions/42796143/how-do-i-install-crystal-lang-on-rapsberry-pi/42796648#42796648)
- [Install Crystal on Raspbian](http://public.portalier.com/raspbian/)


### Ruby Gems and libraries
- The simple way to control your Raspberry Pi's GPIO pins, with Ruby! 
  - [github, MainShayne233/ruby_pins](https://github.com/MainShayne233/ruby_pins)
- A ruby gem allows for ruby code running on devices such as raspberry pi or systems with 1wire usb adapters to speak to the system's input/output pins. the end goal is for people to contribute code for specific devices, sensors and outputs. 
  - [GitHub, klappy/gpio](https://github.com/klappy/gpio)
- Event driven Raspberry Pi GPIO programming in Ruby. 
  - [GitHub, jwhitehorn/pi_piper](https://github.com/jwhitehorn/pi_piper)
- Ruby conversion of RPi.GPIO Python module.
  - [GitHub, ClockVapor/rpi_gpio](https://github.com/ClockVapor/rpi_gpio)



### Security and Pentesting

- [Wi-fi Hacking with Raspberry Pi 3 - WPA/WPA2](https://www.youtube.com/watch?v=RZEZp8fqn_0)
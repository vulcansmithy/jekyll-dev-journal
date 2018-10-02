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


## Link References:
* [How to Install Ruby on Rails on Raspberry Pi 3](https://parsun.com/2017/09/23/how-to-install-ruby-on-rails-on-raspberry-pi-3/)
* [Fixing Rails 5.2 Bus Error on ARMv7/Raspberry Pi](https://romkey.com/2018/05/14/fixing-rails-5-2-bus-error-on-armv7-raspberry-pi/)
* [Stackoverflow, How do I install crystal-lang on rapsberry pi?](https://stackoverflow.com/questions/42796143/how-do-i-install-crystal-lang-on-rapsberry-pi/42796648#42796648)
* [Install Crystal on Raspbian](http://public.portalier.com/raspbian/)
* [Calling C/C++ from Ruby](https://www.amberbit.com/blog/2014/6/12/calling-c-cpp-from-ruby/)
* [Ruby conversion of RPi.GPIO Python module](https://github.com/ClockVapor/rpi_gpio)
* [github.com, jwhitehorn/pi_piper](https://github.com/jwhitehorn/pi_piper)
* ["I need to know when my cats are pooping..."](https://tenderlovemaking.com/2017/01/17/evented-gpio-on-raspberry-pi-with-ruby.html)
* [RPi Ruby on Rails](https://tenderlovemaking.com/2017/01/17/evented-gpio-on-raspberry-pi-with-ruby.html)
* [...](http://artoo.io/documentation/platforms/raspberry-pi/)
* [Wi-fi Hacking with Raspberry Pi 3 - WPA/WPA2](https://www.youtube.com/watch?v=RZEZp8fqn_0)
* [github, ruby_pints](https://github.com/MainShayne233/ruby_pins)
* [RubyPins: Control Raspberry Pi GPIO pins with Ruby!](https://www.reddit.com/r/raspberry_pi/comments/4td2r2/rubypins_control_raspberry_pi_gpio_pins_with_ruby/)
* [lappy/gpio](https://github.com/klappy/gpio)
* [jwhitehorn/pi_piper](https://github.com/jwhitehorn/pi_piper)
* [https://github.com/marksull/udooneorest](https://github.com/marksull/udooneorest)
* [REST SERVICE FOR THE UDOO NEO GPIOS AND SENSORS](https://www.udoo.org/rest-service-for-the-udoo-neo-gpios-and-sensors/)
* [How to Clone Raspberry Pi SD Cards Using the Command Line in OS X](https://computers.tutsplus.com/articles/how-to-clone-raspberry-pi-sd-cards-using-the-command-line-in-os-x--mac-59911)

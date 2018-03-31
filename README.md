# northern-aura-linux-welcome
This is a fork of Ubuntu Budgie's welcome screen. This fork is designed for Northern Aura Linux 0.7 Development.
To install this on your system:

sudo apt install gir1.2-webkit2-4.0 python3-notify2 node-uglify.

git clone https://github.com/na12345678910/northern-aura-linux-welcome.git

uglifyjs -o data/js/bootstrap.min.js data/js/bootstrap.js

uglifyjs -o data/js/ekko-lightbox.min.js data/js/ekko-lightbox.js

To test without installing:

sudo chmod +x ./budgie-welcome && sudo chmod +x ./budgie-welcome-privileged-actions && sudo ./budgie-welcome -d

To force a live-session test:

sudo chmod +x ./budgie-welcome && sudo chmod +x ./budgie-welcome-privileged-actions && sudo ./budgie-welcome --force-session=live -d

This is work in development!

This work is licenced under GPL v3+
# Installing The IonQT Wallet On Linux.

This install will detect your linux distro and install the QT wallet if it is supported. If your distro is not suported do not worry, I am working on more distros all the time.

# Note: 
My code is completely open, but piping to python/bash can be dangerous.  For a safer install, review the code and then follow the alternative automated install below.

curl -s https://gist.githubusercontent.com/sk00t3r/ff9b32c5f06bf289a54b794a97469cf8/raw/331a434ae9010c1bcfaa3cbeae7f5abfff964dc9/installQT.py | python

# Alternative Automated Install:

cd /opt

sudo apt-get install git -y

sudo wget https://raw.githubusercontent.com/sk00t3r/debian-install-ionqt/master/installQT.py

sudo chmod 755 installQT.py

sudo ./installQT.py

# For Low RAM VPS Installs:

This install will detect your linux distro and install the QT wallet if it is supported. If your distro is not suported do not worry, I am working on more distros all the time.

Special thanks to bige for letting me use his VPS' and his time in troubleshooting.

# Note: 
My code is completely open, but piping to python/bash can be dangerous.  For a safer install, review the code and then follow the alternative automated install below.

curl -s https://gist.githubusercontent.com/sk00t3r/90ba3cef5e959dd581b562db8673ad8a/raw/ad6c5a4c1ebf1a37adbf3071a6588c0c474d72c1/installQTvps.py | python

# Alternative Low Ram VPS Automated Install:

cd /opt

sudo apt-get install git -y

sudo wget https://raw.githubusercontent.com/sk00t3r/debian-install-ionqt/master/installQTvps.py

sudo chmod 755 installQTvps.py

sudo ./installQTvps.py

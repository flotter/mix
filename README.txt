Usage:

The installer and setup scripts will create a folder 'mix' in the current directory. Call this script from your Linux home directory. The script is intended for 64-bit Ubuntu and will not work on 32-bit machines, parcially because OpenEmebedded is configured for 64bit native libraries only.

INSTALL:
---------------------------------------

(Install OpenEmbedded) 

cd ~/

sudo apt-get install git

git clone https://github.com/flotter/mix

cd ~/mix

source ./install-mix6000-linux


SETUP:
----------------------------------------

(Setup the environment)

cd ~/mix

source ./setup-mix6000-linux


BUILD:
----------------------------------------

(Build root filesystem)

cd ~/mix/oe

bitbake mix6000-image



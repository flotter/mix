Usage:

The installer and setup scripts will create a folder 'mix' in the current directory. Call this script from your Linux home directory. The script is intended for 64-bit Ubuntu and will not work on 32-bit machines, parcially because OpenEmebedded is configured for 64bit native libraries only.

INSTALL:
---------------------------------------

(Install OpenEmbedded - This takes several hours) 

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


BUILD/RUN:
----------------------------------------

(Build root filesystem - This takes some hours)

cd ~/mix/

source start-build

OR:

(Develop/Debug using Eclipse)

cd ~/mix/

source start-eclipse

LICENSE:
-----------------------------------------

You need to register on the ARM website here:  https://login.arm.com/register.php

Then get the activation code here: http://ds.arm.com/ds-5-community-edition/getting-started/

Finally, in Eclipse under Help go to ARM License Manager and enter the activation code and login details.

# DeSo Node Install Script



# Usage 

sudo wget https://raw.githubusercontent.com/seanslater/bitclout-launch-node/main/bitclout-node.sh

sudo chmod 777 ./bitclout-node.sh

sudo ./bitclout-node.sh

sudo reboot



# Description

Download script to execute the installation script, Docker, and additional packages.

Nano text editor will open to edit dev.env and edit ADMIN_PUBLIC_KEYS to lock admin access. 

Once installation has completed the server needs to be rebooted (to allow the open file limits to be refreshed).

Once rebooted, after a couple of minutes the node will start automatically. 

The node will then start to sync the blockchain - this will take a bit of time to complete. 

You can now open the IP address assigned to your server in your web browser and you should have a working read-only BitClout node online! Enjoy!


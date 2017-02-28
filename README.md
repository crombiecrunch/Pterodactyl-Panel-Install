# Pterodactyl-Panel-Install

This script will install Pterodactyl-Panel for minecraft on your Ubuntu 16.x system. You have the choice to either install with Nginx or Apache.

This script should be ran on a properly setup server not under root. 

curl -Lo install.sh https://raw.githubusercontent.com/crombiecrunch/Pterodactyl-Panel-Install/master/install.sh <br>
bash install.sh -i [nginx] [apache] <br>
  i.e. bash install.sh -i nginx<br>
  
  You will be prompted for email, FDQN, time zone, and portal password. 
  
 This will install all of the necesary files and update the system including SSL.
 
 You will not be prompted again until you need to copy and paste the core code from your node. As shown here, https://daemon.pterodactyl.io/docs/configuration
 

1. Install Ubuntu Server 26.04 with OpenSSH 
2. Install wazuh as per the quickstart guide with the `-i` flag to install on the latest Ubuntu LTS (which is not yet supported) `curl -sO https://packages.wazuh.com/4.14/wazuh-install.sh && sudo bash ./wazuh-install.sh -a -i`
3. Note down the admin password supplied by the program
4. Get VM IP via `prlctl list -f` if installed via Parallels
5. Access the console via the host machine - visit https://(IP):443
6. Connect as "admin" with the password from step 3

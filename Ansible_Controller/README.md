# Homework 7
For this assignment we must create an Ansible controller that can spin up 4 web servers using 4 blank-state VMs. According to the assignment description we need to  

We will be executing a couple of files for this assignment:
* Script: hw7.sh
* Playbook: webserver.yaml

In order to run this you need these files/programs:
* Oracle Virtual Box 5.2.26
* CentOS_Reference
* Alpine_Reference
* pfSense_Reference
* Ansible

**Instructions:** 
1. Start pfSense Router. **Wait until router VM is up**
2. Start the CentOS CLI VM up  **Wait until CentOS VM is up**. 
3. Start up the 4 Alpine_Reference VM's.
4. Log in and in each Alpine_Reference VM, use the command ``` ip addr ``` to retrieve the IP addresses of the 4 machines. Make sure the IP address of the first one booted ends with a .20 and the following go up by one.
5. Download the files needed for this assignemnt:
* curl https://raw.githubusercontent.com/Ryanwall15/CS312/master/Ansible_Controller/ansible-index.html > ~/ansible-index.html
* curl https://raw.githubusercontent.com/Ryanwall15/CS312/master/Ansible_Controller/hosts.ini > ~/hosts.ini
* curl https://raw.githubusercontent.com/Ryanwall15/CS312/master/Ansible_Controller/hw7.sh > ~/hw7.sh
* curl https://raw.githubusercontent.com/Ryanwall15/CS312/master/Ansible_Controller/webserver.yaml > ~/webserver.yaml
6. Run the shell script by running the command ``` sh hw7.sh ```


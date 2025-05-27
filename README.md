**1. Clone the repo**
    https://github.com/soujnar/Ansible-Docker-installation.git

**2. Add your VMs in to the inventory file (ie. hosts.ini)**

**3. Add credentials to your VMs in the inventory file**

**4. Make sure that the OS is CentOS or change the download link in the playbook(ie. Docker_installation.yml)**

**5. Run the playbook:**
     ansible-playbook -i hosts.ini Docker_installation.yml
     

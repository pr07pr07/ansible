### How to configure OCI Collection for Ansible

  ```bash
  # Install the oci-cli
  $ bash -c "$(curl -L https://raw.githubusercontent.com/oracle/oci-cli/master/scripts/install/install.sh)"
  $ exec -l $SHELL

 # Configure config file 
  $ oci setup config
  
 # Install pip
  $ sudo apt install pip
 
 # Install the Python OCI module
  $ python3 -m pip install oci

 # Install the Ansible OCI collection 
  $ ansible-galaxy collection install oracle.oci


  ```
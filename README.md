# lab-1-Ansible
1)What inventory parameters can be used to establish a local connection instead of ssh in Ansible?
To establish a local connection in Ansible, set ansible_connection=local in the inventory for localhost. Optionally, configure ansible_python_interpreter to specify the Python path if needed.

2) What value we must set for ansible_connection parameter to connect to a Windows server?
[windows]
windows_host ansible_connection=winrm

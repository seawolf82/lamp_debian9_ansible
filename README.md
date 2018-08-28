# lamp_debian9_ansible

To install lamp on debian 9 run:

ansible-playbook -i hosts site.yaml

To uninstall lamp on debian9 run:

ansible-playbook -i hosts deprovision.yaml

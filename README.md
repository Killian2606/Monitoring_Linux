# Monitoring_Linux
prerequis :

machine 
debian
40go
4go ram 
8 CPU

créer un utilisateur nommé "ansible" sans mot de passe

unzip monitoring_linux 

cd monitoring_linux 

 pour lancer le projet complet
ansible-playbook -i inventory.ini site.yml -v



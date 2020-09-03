# nginx-docker-install-ubuntu
Install nginx and docker,create nginx.conf,script cold docker restart and add task crontab,create swap,configure ufw. OS - Ubuntu
2.9 start playbook:

add ip - hosts
ansible-playbook -i hosts SetupWebServerOneContainerStage.yml --private-key=your_key.pem
enter host,port,name domain, name nginx.conf

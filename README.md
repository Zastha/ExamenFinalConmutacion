# ExamenFinalConmutacion

### Configuracion SSH
ip domain-name juanmark.com
crypto key generate rsa
1024
username juan secret mark

line vty 0 15
transport input ssh
login local
exit
ip ssh version 2


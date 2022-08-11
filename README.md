# Group4
lab3-mininet-topo.py: Mininet topo file, it should run on Mininet host. 

#sudo python3 lab3-mininet-topo.py 

Lab3-ryu-app.py: ryu application, insert initial flow table to switches,  

note that it should run along with ofctl_rest.py on Mininet host. 

#ryu-manager lab3-ryu-app.py ofctl_rest.py 

rest-addon.py: run on a host that could reach ryu controller, which could change the flow table on the fly. 

#python3 rest-addon.py 

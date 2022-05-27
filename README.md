# ping
unlimited pinging on server
import os
var = True
zahl = 0
while var:
    zahl += 1
    ip = input("Which IP-Address do you want to constantly ping: ")
    os.system("ping -n 4 {}".format(ip))
    if zahl == 1:
        while var:
            os.system("ping -n 4 {}".format(ip))

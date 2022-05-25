# ping
unlimited pinging on server
import os
var = True
while var:
    ip = "192.168.0.1"
    os.system("ping -n 4 {}".format(ip))

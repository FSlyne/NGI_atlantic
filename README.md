# NGI_atlantic 2021

Generate traffic function
python3 udp_server_function.py

Monitor traffic at egress interface
bash interface_monitor.sh
which calls
python3 change_bandwidth.py

Display graph of traffic at ingress
python graph_interface.py vxlan100 interface


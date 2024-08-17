
MANAGEMENT PORT CONFIGURATION

# configure terminal
# ip address 192.168.115.85 (IP Address) 255.255.255.0 (Subnet Mask)
# ip gateway 192.168.115.3
# exit


PORT SPEED CONFIGURATION

# configure terminal
# interface fx ethernet 0/10 (As Example)
# no fec-mode
# no negotiation
# speed 1000 (In Mbps)
# exit


LINK AGGREGATION

# configure terminal
# interface port channel 10
# exit
# int range fx 0/22-25
# channel-group 10 mode active
# end

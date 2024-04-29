# ingryd-linux-ansible-group-6

## This is a project which enables configuration management using ansible on three host machines with the following configuration information for their static ip addreses and hostnames

| Static ip | hostname |
| --------- |:--------:|
| 192.168.100.10 | control |
| 192.168.100.20 | node1 |
| 192.168.100.30 | node2 |

## The respective static ip on the three machines as illustrated in the table above can all ping each other using the hostname or static ip

## The control machine can ssh into both node1 and node2 (a) securely and (b) without using password. (SSH Key-gen type is ed25519)

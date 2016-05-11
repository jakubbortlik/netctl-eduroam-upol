netctl-eduroam profile for Palacký University network
=====================================================
this is the netctl profile for Palacký University, Olomouc that works on my Dell Latitude E6400 running Arch Linux

##How to get it working
```
# Find/create a directory to save the files, mine is ~/code/netctl-eduroam-upol:
cd ~/code/netctl-eduroam-upol
git clone git://github.com/jakubbortlik/netctl-eduroam-upol.git

# Copy the profile to /etc/netctl/. You may need to do that with sudo:
cp eduroam-upol /etc/netctl/

# Edit the device and user specific parts:
sudo -e /etc/netctl/eduroam-upol
# Substitute:
#<NETWORK INTERFACE> with your wireless interface, e.g. wlp12s0 (find out with "ip link")
#<YOUR-PORTAL-LOGIN>
#<YOUR-SECRET>
```

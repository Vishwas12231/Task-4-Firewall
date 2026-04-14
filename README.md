# Task 4 - Setup and Use Firewall on Linux

## Objective
Configured and tested firewall rules using UFW.

## Commands Used

### Install UFW
sudo apt install ufw -y

### Enable Firewall
sudo ufw enable

### Check Status
sudo ufw status numbered

### Block Port 23
sudo ufw deny 23

### Allow Port 22
sudo ufw allow 22

### Remove Block Rule
sudo ufw delete deny 23

## Outcome
Learned basic firewall management, inbound traffic blocking, and allowing secure ports.

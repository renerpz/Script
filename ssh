#!/bin/bash

# Update package lists
echo "Updating package lists..."
sudo apt update

# Install OpenSSH server
echo "Installing OpenSSH server..."
sudo apt install -y openssh-server

# Enable SSH service to start on boot
echo "Enabling SSH service to start on boot..."
sudo systemctl enable ssh

# Start SSH service
echo "Starting SSH service..."
sudo systemctl start ssh

# Check the status of the SSH service
echo "Checking SSH service status..."
sudo systemctl status ssh

echo "OpenSSH installation and setup complete."

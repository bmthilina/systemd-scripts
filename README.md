
# systemd-scripts
systemd startup scripts for common applications

# Installation instructions

 - Copy the script file to "/etc/systemd/system/" 
 - Reload the systemd: "sudo systemctl daemon-reload"
 - Enable the service (auto start at boot): "sudo systemctl enable <service-name>"
 - Start the service: "sudo systemctl start <service-name>"

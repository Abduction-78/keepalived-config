# Keepalived Config with Nginx Monitoring

This is a Keepalived configuration for high availability with Nginx monitoring. The configuration uses VRRP to manage a virtual IP and ensures that Nginx stays up and running. If Nginx fails, the backup node will take over.

## How to Use

1. Install Keepalived on your Linux machines.
2. Copy the `keepalived.conf` file to `/etc/keepalived/keepalived.conf`.
3. Adjust network settings (interface, IPs, etc.) as per your setup.
4. Start Keepalived.

# Firewall Configuration

## Allow SSH
`sudo ufw allow ssh`

## Default Deny Policy
* `sudo ufw default deny incoming`
* `sudo ufw default allow outgoing`

## Allow Port 8080
`sudo ufw allow 8080/tcp`

## What happens if you run sudo ufw enable before sudo ufw allow ssh?

If I enable UFW before allowing SSH, I might lose remote access to the server because incoming SSH connections could be blocked by the firewall.

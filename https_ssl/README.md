 SSL

Bash scripts for the HTTPS and SSL project.

## Tasks

| File | Description |
|------|-------------|
| `0-world_wide_web` | Displays the record type and destination of the www, lb-01, web-01 and web-02 subdomains of a domain, or of one specific subdomain |

## Usage
# Installs nginx on port 80 and serves a page containing Holberton School
apt-get update -y
apt-get install -y nginx
echo "Holberton School for the win!" > /var/www/html/index.html
service nginx restart || { pkill nginx; nginx; }


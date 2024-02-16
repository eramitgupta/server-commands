# Server Commands

Certainly! Here's a concise list of server commands
A few examples of useful commands and/or tasks.

## Getting Started 

update system 
```bash
 sudo apt update && sudo apt  upgrade
 ```
rmdir Remove Directory
```bash
rmdir directory_name
```
chmod permissions file_or_directory
```bash
sudo chmod -R 777 xy.com/ or directory_name
```
kill 
```bash
kill process_id
```
tar Tape Archive
```bash
tar options archive_file files_or_directories
```
tar Tape Archive
```bash
tar options archive_file files_or_directories
```
gzip GNU Zip
```bash
gzip file
```
unzip 
```bash
unzip archive_file
```
sudo dpkg -i 
```bash
sudo dpkg -i package_file.deb
```

## Nginx

Provides the current status and information about Nginx.
```bash
sudo systemctl status nginx
```
Monitors real-time error logs for Nginx.
```bash
sudo tail -f /var/log/nginx/error.log
```
Monitors real-time access logs for Nginx.
```bash
sudo tail -f /var/log/nginx/access.log
```
Initiates the Nginx web server stop or start
```bash
sudo systemctl start nginx
```
Restarts Nginx to apply configuration changes without stopping the service
```bash
sudo systemctl restart nginx
```
Reloads the Nginx configuration, preserving active connections.
```bash
sudo systemctl reload nginx
```
Verifies the syntax of the Nginx configuration files.
```bash
sudo nginx -t
```
Opens the main Nginx configuration file for editing.
```bash
sudo nano /etc/nginx/nginx.conf
```
Checks the configuration syntax and reloads Nginx if the syntax is correct.
```bash
sudo nginx -t && sudo systemctl reload nginx
```
Opens the default site configuration file for editing.
```bash
sudo nano /etc/nginx/sites-available/default
```
Opens the default site configuration file for editing.
```bash
sudo nano /etc/nginx/sites-available/default
```

php.ini
```bash
sudo nano /etc/php/8.2/fpm/php.ini
```
memory_limit:
upload_max_filesize:
post_max_size:
max_execution_time:
Restart PHP-FPM:

```bash
sudo systemctl restart php7.4-fpm
sudo systemctl restart nginx
```

## Database

Initiates a MySQL session, prompting for the password of the specified user.
```bash
mysql -u root -p
```
Selects a specific database for subsequent SQL queries.
```bash
USE your_database;
```
Executes SQL statements from the specified script file in the currently selected database.
```bash
SOURCE /path/to/your/abc.sql;
```

### laravel valet 
change php v one domain 

```bash
 valet isolate php@8.2 --site "domainName" --secure
```

## Configure Git user name:

Sets your Git user name to 'eramitgupta'. Replace 'eramitgupta' with your actual Git user name
```bash
git config user.name 'eramitgupta'
```
Sets your Git user email to 'info.eramitgupta@gmail.com'. Replace 'info.eramitgupta@gmail.com' with your actual Git email address.
```bash
git config user.email 'info.eramitgupta@gmail.com'
```

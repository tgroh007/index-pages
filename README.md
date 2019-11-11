# Index Pages
Assign pages as the index page for WordPress custom post types, similar to the Posts Page.

Nginx users, don't forget to add autoindex on; to your example.com.conf file Or you it will throw a 403 nginx forbidden error. 
File is located:

cd /etc/nginx/sites-available,

Example:
**root /var/www/mywebsite.com;
  autoindex on;**

After you modify your mywebsite.com file, restart nginx,
**sudo service nginx restart**

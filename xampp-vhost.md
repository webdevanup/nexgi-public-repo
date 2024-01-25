# Setup Vhost

1. Start Your XAMPP
2. Check your localhost & IP 127.0.0.1 should be working 


## For Mac Users

**Files locations**
hosts file - /etc/hosts
httpd.conf file - /Applications/XAMPP/xamppfiles/etc/httpd.conf
httpd-vhosts.conf - /Applications/XAMPP/xamppfiles/etc/extra/httpd-vhosts.conf

**httpd-vhosts block sample**
```
<VirtualHost *:80>
    ServerName localhost 
    DocumentRoot "C:/xampp/htdocs"  
    <Directory "C:/xampp/htdocs">  
        Options Indexes FollowSymLinks MultiViews
        AllowOverride all
        Order Deny,Allow
        Allow from all
        Require all granted
    </Directory>
</VirtualHost>
```

## For Window Users

**Files locations**
hosts file - C:\Windows\System32\drivers\etc\hosts
httpd.conf file - C:\xampp\apache\conf\httpd.conf
httpd-vhosts.conf - C:\xampp\apache\conf\extra\httpd-vhosts.conf

**httpd-vhosts block sample**
```
<VirtualHost *:80>
    ServerName localhost 
    DocumentRoot "C:/xampp/htdocs" 
    <Directory "C:/xampp/htdocs"> 
        Options Indexes FollowSymLinks MultiViews
        AllowOverride all
        Order Deny,Allow
        Allow from all
        Require all granted
    </Directory>
</VirtualHost>
```




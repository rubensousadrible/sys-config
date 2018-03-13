## Edit the vhosts.conf file

Open this file to add in the virtual host.

`sudo nano /etc/apache2/extra/httpd-vhosts.conf`

An example domain in the file is given of the format required to add in additional domains, just follow this to create your new virtual host:

```
<VirtualHost *:80>
ServerAdmin webmaster@dummy-host2.example.com
DocumentRoot "/usr/docs/dummy-host2.example.com"
ServerName dummy-host2.example.com
ErrorLog "/private/var/log/apache2/dummy-host2.example.com-error_log"
CustomLog "/private/var/log/apache2/dummy-host2.example.com-access_log" common
</VirtualHost>
```

We can take this example and extend on it, if you wanted a domain named **apple.com** for example, you can copy the existing text block and edit to suit:

```
<VirtualHost *:80>
    ServerName apple.com
    ServerAlias www.apple.com
    DocumentRoot "/Users/USERNAME/Sites/apple"
    ErrorLog "/private/var/log/apache2/apple.com-error_log"
    CustomLog "/private/var/log/apache2/apple.com-access_log" common
    ServerAdmin web@coolestguidesontheplanet.com
</VirtualHost>
``` 

So in the example above a vhost for **apple.com** is created and the document root is in the **Sites** folder, in the text block above I have also added in some log files, what you need to change is the document root location username and domain name to suit your needs. Finish and save the file.

Now also you need to map the IP address to be the localhost.

## Map Your IP address to localhost

`sudo nano /etc/hosts`

Add the Domain and ‘**www**‘ alias to resolve to the localhost address

`127.0.0.1 apple.com www.apple.com`

## Restart Apache

`sudo apachectl restart`

Check out your local **vhost** domain in the browser

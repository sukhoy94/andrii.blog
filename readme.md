# INIT

1. Get last version of wp-cli
````
curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
````
   
2. Download wordpress core
````
php wp-cli.phar core download
````   

3. Map your virtual host to project directory (xampp example)
````
<VirtualHost *:80>
DocumentRoot "/xampp/htdocs/blog"
ServerName blog.loc
</VirtualHost>
````
and add in hosts file: 
```
127.0.0.1 blog.loc
```

4. Now project should be available under http://blog.loc/ on your local machine

# To read

https://make.wordpress.org/core/handbook/best-practices/coding-standards/php/ - coding standards

# bWAPP

 bWAPP compatible for PHP7 or higher
 
 bWAPP compatible for PHP8 or higher



--------------
bWAPP - README
--------------

bWAPP, or a buggy web application, is a deliberately insecure web application.
bWAPP helps security enthusiasts, developers and students to discover and to prevent web vulnerabilities.
It prepares one to conduct successful penetration testing and ethical hacking projects.
What makes bWAPP so unique? Well, it has over 100 web bugs!
bWAPP covers all major known web vulnerabilities, including all risks from the OWASP Top 10 project!
It is for security-testing and educational purposes only.




# How to FIx it for PHP7 and Higher :
Download bWAPP package and set config for your system and install database.after that following steps:

1 . Copy **fix_mysql.php** to root bWAPP directory 

2 . add following code into **security.php** in root directory after first line ( <?php ) 

```php
    include("fix_mysql.php");
```
best regards.

# Nikto

```
nikto -h vulnerable_ip
```

This scan type will retrieve the headers advertised by the webserver or application (I.e. Apache2, Apache Tomcat, Jenkins or JBoss) and will look for any sensitive files or directories (i.e. login.php, /admin/, etc)



## PLUGINS

| Plugin Name    | Description                                                                                                                                                                            |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| apacheusers    | Attempt to enumerate Apache HTTP Authentication Users                                                                                                                                  |
| cgi            | Look for CGI scripts that we may be able to exploit                                                                                                                                    |
| robots         | Analyse the robots.txt file which dictates what files/folders we are able to navigate to                                                                                               |
| dir\_traversal | Attempt to use a directory traversal attack (i.e. LFI) to look for system files such as /etc/passwd on Linux (http://ip\_address/application.php?view=../../../../../../../etc/passwd) |

Example:

```
nikto -h 10.10.10.1 -Plugin apacheuser
```

##

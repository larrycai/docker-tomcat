## Introduction ##

It is a simple ubuntu:14.04 based tomcat7 using openjdk7

tomcat manager gui interface is available (`tomcat7-admin` is installed) with user/passwd `admin\admin`

    $ docker run -d -p 8080:8080 larrycai/tomcat


The volumn is `var/lib/tomcat7/webapps`, which can be used to deploy and shared with other containers
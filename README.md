# auth-spring-security-3


Simple use of spring boot security with role based login.

This is similar to auth-spring-security-1 but here i used manual login instead of using spring security automatic login

### Defference

 Login logic is written by us

### Instructions

- simple role based login system
- when user register | we allocate a user role to him 
- we have a single ADMIN which we created manually [By changing the role of USER to ADMIN through database]
- if the user is not logged in he is not able to visit some pages

### Permitted URL'S

- localhost:8080/admin/** = for ADMIN ONLY
 
- localhost:8080/user/**	 = for USER , ADMIN
 
- localhost:8080/**       = for everyone


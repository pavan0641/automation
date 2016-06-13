# automation
1. Download authentication-app.zip and extact . This having authentication using angularjs  Rest end point framewrok  with mysql database
2. Download Apache , and configure http like 
  DocumentRoot "C:\authentication-app"
<Directory "C:\authentication-app">
Options Indexes FollowSymLinks
AllowOverride None
Require all granted
</Directory>
 
3. execute auth.sql in my Sql 

Note : i used for mysql db username as  : root & passowrd :my_password , incase you want to change , after extraction authentication-app.zip goto api/config.php provide details accordingly 

4. Jmeter scripts attached Note: used json plguin to validate json response



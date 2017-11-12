# Divi Requirements
-------------------

PHP and MySQL Requirements 
--------------------------
PHP 7 or greater
MySQL 5.6 or greater
The mod_rewrite Apache module must be enabled


PHP variables need to be >= to the values below
-----------------------------------------------
post_max_size 128M
max_execution_time 300
upload_max_filesize 256M
max_input_time 600
max_input_vars 5000


If you get builder timeout errors you need to add the follwing to the end of you .htaccess file 
------------------------------------------------------------------------------------------------
<IfModule mod_substitute.c>
SubstituteMaxLineLength 20M
</IfModule>
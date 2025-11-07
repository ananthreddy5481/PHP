# PHP

<?php -- the staring of the code block.
?>   -- the ending of the code.

ECHO -- PRINTING FUNCTION.
$ -- this indicates that the following is a varible.(ex: $age this means age is a varible).
"  " -- in php the text in the double qutoes treated as the interpolation(inputing form the above code itself) and 
'  ' -- in the single quotes it is treated as the plain text.
in php it will delete the assinged varibles after the task is done to avoid that we use 
static - it will make sure that the previous input is remembered.

requesting methods : GET and POST

GET   :  the requesting method that will transfer the user input through the url that is it is visible in the url.
POST  : the requesting method that will transfer in the backend through the HTTP request.[HTTP - set of rules for transfering the data on internet]
the GET and POST request is made by the html code and the php will verify the request weather it is a POST or GET.

PDO - php data objects it will help to establish a connection between mysql and the php files.this line will tell the username that should be 


require -- it is used to include the previously made files in this code.

register.php:
we will include the previous db.php for establishing the connection b/w the mysql and the php server.

in the register php we will declare the "message" and giving it empty value in the starting so that when the file is executed the php will have no inputs to send to the html so that we need an empty value so that there will no error for not declaring the message.

in this two scripts: html and php  : trim - will delete the left space while inputing the information.
html - the interface and taking input from the user and sending to the php { the line form method="POST" will make it send the info in the POST "
php - take the input in the POST method and store it in the respective varible.




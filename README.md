# PHP

<?php -- the staring of the code block.
?>   -- the ending of the code.

ECHO -- PRINTING FUNCTION.
$ -- this indicates that the following is a varible.(ex: $age this means age is a varible).
"  " -- in php the text in the double qutoes treated as the interpolation(inputing form the above code itself) and 
'  ' -- in the single quotes it is treated as the plain text.
in php it will delete the assinged varibles after the task is done to avoid that we use 
static - it will make sure that the previous input is remembered.

$_SERVER - IT WILL COINTAIN THE INFORMATION ABOUT THE SERVER LIKE THE REQUEST METHOD AND ETC--[super global varible].

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

in this the line  $stmt = $pdo->prepare("INSERT INTO users (username, email, password) VALUES (?, ?, ?)"); it will prepare a sql query to input in the database.
this line             $stmt->execute([$username, $email, $hashedPassword]); will enter the above values into the database server.

CATCH - this block is executed when the TRY is failed , in that catch PDOException(error that causes when connecting to the database) then it is stored in the $e varible.

HTML:
in the HTML the part in the head is not seen in the webpage (seen like in the tabname etc).

LOGIN :

password_verify -- built in function to compare the hashed and plaintext.

$_SESSION - it will store the user data that is needed to execute the sessions .
session_start(); - it will call the data that is stored by $_SESSION in every page where ever we include .


isset - it will check the varible is assaigned some value or not.

upload_err_ok - it is an error value of '0' which means the file uploaded correctly.

pathinfo - it is used to extract the info of the file from its name or address.
pathinfo_extention - it will tell about the what info should be extractes in this case it is 'extention'.

<a href="<?php echo htmlspecialchars($current_user['file']); ?>" target="_blank">
    View / Download      IN THIS THE TARGET=BLANK HELP TO OPEN THE FILE IN A NEW TAB. AND THE ECHO OPENS THE FILE THAT IS SAVED.
</a>



enctype="multipart/form-data" --> ENCTYPE - ENCRYPTION TYPE - MULTIPART MEAN SPLIT THE FILE INTO MULTIPLE PARTS AND TRANSFER THE DATA FROM THE FORM.

BUTTON TYPE - SUBMIT TELLS THE BROWSER TO SUBMIT THE FORM. BUTTON NAME IS THE NAME OF THE BUTTON VISIBLE TO USER.

WHILE ENTERING THE USER DETAILS IN THE ADMIN DASHBOARD WE WILL USE THE FOREACH LOOP FOR ENTERING THE EACH DETAIL OF EACH USER.






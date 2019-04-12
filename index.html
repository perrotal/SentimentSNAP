<body>
    
</body>
</html>
</doctype>

<?php

session_start();
require_once('dbconnect.php');
if(isset($_SESSION['user'])){
  header('Location: home.php');
}
if(isset( $_POST['username'] ) && isset( $_POST['password'])){
  $username = $_POST['username'];
  $password = hash('sha256', $_POST['password']);
  $result = $db->users->findOne(array( 'username'=>$username, 'password'=>$password));
  if($result) {
    $_SESSION['user'] = $result->_id;
    header('Location: home.php');
  }
}
?>
<html>
<head>

    <link rel="stylesheet" type="text/css" href="style.css">
    

<title>Finsta</title>
</head>
<body>	
    
  <?php include('header.php'); ?>
  <form method="post" action="indexss.php">
    <fieldset>
        <h3>Login</h3>
      <label for="username">Username: </label><input type="text" name="username" /><br>
      <label for="password" >Password: </label><input type="password" name="password" /><br>
      <input type= "submit" value="Log in">
    </fieldset>
       <a href= "register.php" style="position: absolute; text-align:center;" >No account? Register here. </a>
  </form>
 
<!--===============================================================================================-->
	<script src="mainj.js"></script>

    
</body>
</html>

<?php include 'config.php';?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form method="post">
  <table>
    <tr>
    <td><label for="Name">Name</label></td>
        <td><input type="text" name="name" placeholder="Enter Name"/></td>
    </tr>
    <tr>
    <td><label for="age">Age</label></td>
        <td><input type="text" name="age" placeholder="Enter Age"/></td>
    </tr>
    <tr>
        <td><input type="submit" name="submit" value="Save"/></td>
    </tr>
  </table>  
    </form>
</body>
</html>
<?php
if(isset($_POST['submit']))
{
    $name=$_POST['name'];
    echo "sdf".$name;

}

?>

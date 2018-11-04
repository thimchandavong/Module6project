<?php 
//Allow Headers 
header('Access-Control-Allow-Origin: *');
//$servername = "localhost:3306"; 
$servername = "jamsa02.centralus.cloudapp.azure.com:3306";
$username = "Learner"; 
$password = "Rasmussen"; 
$dbname = "demo";
// Create connection 
$conn = new mysqli($servername, $username, $password, $dbname);
// Check connection 
 if ($conn->connect_error) 
     echo "Error: Unexpected connection error. Please retry the operation."; 
 else 
  { 
     $result = $conn->query("SELECT * FROM test");
     if (($result != 0) && ($result->num_rows > 0)) 
       { 
          $row = $result->fetch_assoc();
          $AdressID = $row['AdressID']; 
          $AddressLine1 = $row['AddressLine1']; 
          $AddressLine2 = $row['AddressLine2']; 
          $City = $row['City'];
          
          $StateProvinceID = $row['StateProvinceID']; 
          $PostalCode = $row['PostalCode']; 
          $rowguid = $row['rowguid']; 
          $ModifiedDate = $row['ModifiedDate'];
          echo $AdressID; 
          echo $AddressLine1; 
          echo $AddressLine2; 
	echo $City; 
          echo $StateProvinceID; 
          echo $PostalCode; 
  echo $rowguid; 
          echo $ModifiedDate; 
       } 
     $conn->close(); 
} 
?>

# Login-System
A simple login system in using php and mysql in html

While learning backend, I started with php, (FACEBOOK is on php)...
I came through some of the functions of php which can provide functionality to interact with mysql database(the procedural way).

For example : 1. mysqli_connect(DB_SERVER, DB_USERNAME, DB_PASSWORD, DB_NAME)
              2. mysqli_prepare($link, $sql)
              3. mysqli_stmt_execute($stmt)
              4. mysqli_stmt_store_result($stmt)
              5. mysqli_stmt_num_rows($stmt)
              6. mysqli_stmt_close($stmt)
              7. mysqli_stmt_bind_param($stmt, "ss", $param_username, $param_password)
              8. mysqli_close($link)
              9. mysqli_stmt_fetch($stmt)
              10. password_verify($password, $hashed_password)
              11. session_start()
              12. session_destroy()
              13. header("location: login.php")
              14. isset($_SESSION["loggedin"])
              15. trim($_POST["new_password"])
              16. htmlspecialchars($_SERVER["PHP_SELF"])
              
              and much more...
             
I've also applied validation on forms, like username, password, etc.

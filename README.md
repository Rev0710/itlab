<!DOCTYPE html>
<html lang="">
<head>
    <title>Login Form</title>
    <style>
        body {
          font-family: sans-serif;
        }
       
        }
        label {
          display: block;
          margin-bottom: 5px;
        }
        input[type="text"],
        input[type="password"] {
          width: 100%;
          padding: 10px;
          margin-bottom: 10px;
          border: 1px solid #ccc;
          border-radius: 3px;
          box-sizing: border-box;
        }
       
        }
    </style>
</head>
<body>

<form action="" method="post">
    <label for="username">Username:</label>
    <input type="text" id="username" name="username" required>

    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required>

    <input type="submit" value="Login">
</form>

</body>
</html>

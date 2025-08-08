<!DOCTYPE html>
<html lang="">
<head>
    <title>Login Form</title>
    <style>
        body {
          font-family: sans-serif;
        }
        form {
          width: 300px;
          margin: 0 auto;
          padding: 20px;
          border: 1px solid #ccc;
          border-radius: 5px;
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
        input[type=""] {
          background-color: #4CAF50;
          color: white;
          padding: 100px 150px;
          border: none;
          border-radius: 3px;
          cursor: pointer;
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

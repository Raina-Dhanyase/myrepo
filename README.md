# myrepo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>loginpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #585353;
        }
        .login-container {
            height: 450px;
            width: 350px;
            margin: 0 auto;
            margin-top: 100px;
            margin-bottom: 100px;
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.5);
        }
        .logo {
            text-align:center;
            margin-bottom: 20px;
        }
        .logo img {
            width: 100px;
            height: auto;
        }
        h4 {
            text-align: center;
            margin-bottom: 10px;
        }
        
        input[type="text"],
        input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            display: inline-block;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            width: 100%;
            background-color: #ec7a0f;
            color: white;
            padding: 14px 20px;
            margin: 8px 0;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: rgb(216, 144, 11);
        }
    </style>
</head>
<body>
    <div class="login-container">
        <div class="logo">
            <img src="img3.jpg" alt="Logo">
            
        </div>
       <h4>Login/Sign in</h4>
        <form action="/login" method="post">
            <label for="email">Email Address</label>
            <input type="text" id="email" name="email" placeholder="Enter your mail id ">
            <label for="Contact no">Contact no.</label>
            <input type="text" id="contact no" name="Contact no." placeholder="Enter your number">


            <label for="password">Password</label>
            <input type="password" id="password" name="password" placeholder="Enter your password">

            <input type="submit" value="Login">
           
        </form>
      
    </div>
</body>
</html>

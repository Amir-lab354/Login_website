# Login_website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login</title>
    <link rel="stylesheet" href="style-sheet.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    <div class="wrapper">
        <form action="">
            <h1>Login</h1>
            <div class="input-box">
                <input type="text" placeholder="Username" 
                required>
                <img class="i" src="bxs-user.svg">
            </div>
            <div class="input-box">
                <input type="assword" placeholder="Password" 
                required>
                <img class="i" src="bxs-lock-alt.svg">
            </div>

            <div class="remember-forgot">
                <label><input type="checkbox">Remember me
                </label>
                <a href="#">Forgot password?</a>
            </div>
            <button type="submit" class="btn">Login</button>

            <div class="register-link">
                <p>Don't have an account? <a href="register.html">Register</a></p>
            </div>
        </form>
    </div>
</body>
</html>

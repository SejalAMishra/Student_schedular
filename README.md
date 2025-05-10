<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Time Mastery - Manage Your Time Effectively</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #f7f7f7, #e2e2e2);
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .header {
            width: 100%;
            padding: 20px;
            background: linear-gradient(90deg, #FF8C00, #FF6347);
            color: white;
            text-align: center;
            position: relative;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .header img {
            width: 60px;
            position: absolute;
            top: 10px;
            left: 20px;
        }
        .header h1 {
            margin: 0;
            font-size: 2.5em;
            animation: fadeInDown 1s ease-in-out;
        }
        .header p {
            margin-top: 5px;
            font-size: 1.2em;
            animation: fadeInUp 1s ease-in-out;
        }
        .main-content {
            text-align: center;
            padding: 50px 20px;
            background-color: white;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            border-radius: 15px;
            margin: 30px 0;
            max-width: 900px;
            width: 100%;
        }
        .main-content h2 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #FF6347;
        }
        .main-content p {
            font-size: 1.2em;
            margin-bottom: 30px;
            line-height: 1.5;
        }
        .login-container, .signup-container {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(251, 17, 17, 0.3);
            width: 300px;
            margin: 20px auto;
        }
        .login-container h3, .signup-container h3 {
            margin-bottom: 20px;
            color: #FF6347;
        }
        input[type="text"], input[type="password"], input[type="email"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 10px;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #FF8C00;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #FF6347;
        }
        .footer {
            width: 100%;
            padding: 20px;
            background-color: #333;
            color: rgb(239, 235, 235);
            text-align: center;
            position: fixed;
            bottom: 0;
        }
        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

    
    <div class="header">
        <img src=<!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Time Management Logo</title>
            <style>
                .logo {
                    width: 100px;
                    height: 100px;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    background-color: #f0f0f0;
                    border-radius: 50%;
                    position: relative;
                    margin: 0.05px auto;
                    text-decoration: none; /* Removes underline from link */
                }
                .clock-face {
                    fill: #ffffff;
                    stroke: #070404;
                    stroke-width: 2px;
                }
                .hour-hand, .minute-hand {
                    stroke: #333333;
                    stroke-width: 4px;
                    stroke-linecap: round;
                }
                .hour-hand {
                    transform-origin: center;
                    transform: rotate(45deg);
                }
                .minute-hand {
                    transform-origin: center;
                    transform: rotate(90deg);
                }
                .bracket {
                    fill: none;
                    stroke: #ff6600;
                    stroke-width: 4px;
                    stroke-linecap: round;
                }
            </style>
        </head>
        <body>
            <a href="https://yourwebsite.com" class="logo">
                <div class="logo">
                    <svg viewBox="0 0 100 100" width="80%" height="80%">
                        <!-- Clock Face -->
                        <circle class="clock-face" cx="50" cy="50" r="48"/>
                        
                        <!-- Hour Hand -->
                        <line class="hour-hand" x1="50" y1="50" x2="50" y2="30"/>
                        
                        <!-- Minute Hand -->
                        <line class="minute-hand" x1="50" y1="50" x2="50" y2="20"/>
                        
                        <!-- Brackets (Code Symbols) -->
                        <path class="bracket" d="M20 40 Q10 50 20 60"/>
                        <path class="bracket" d="M80 40 Q90 50 80 60"/>
                    </svg>
                </div>
            </a>
        </body>
        </html> "Time Mastery " <!-- Replace with your logo image -->
        <h1>Time Mastery</h1>
        <p>Master Your Time, Achieve Your Goals</p>
    </div>
    <div class="main-content">
        <h2>Welcome to Time Mastery</h2>
        <p>Your journey to better time management starts here. Join us to unlock your full potential by managing your time effectively and reaching your goals effortlessly.</p>


        <div class="signup-container">
            <h3>Sign Up for a New Account</h3>
            <form action="/submit-signup" method="post">
                <input type="text" placeholder="Full Name" name="fullname" required>
                <input type="email" placeholder="Email" name="email" required>
                <input type="password" placeholder="Password" name="password" required>
                <button type="submit">Sign Up</button>
            </form>
        </div>
    </div>

</body>
</html>

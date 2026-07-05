<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krishna Rajput Website</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial,sans-serif;
        }

        body{
            display:flex;
            justify-content:center;
            align-items:center;
            height:100vh;
            background:linear-gradient(135deg,#0f2027,#203a43,#2c5364);
            color:white;
            text-align:center;
        }

        h1{
            font-size:45px;
            text-transform:uppercase;
            animation:glow 2s infinite alternate;
        }

        p{
            margin-top:20px;
            font-size:20px;
        }

        @keyframes glow{
            from{
                text-shadow:0 0 10px #00e5ff;
            }
            to{
                text-shadow:0 0 25px #00e5ff,0 0 40px #00e5ff;
            }
        }
    </style>
</head>
<body>

<div>
    <h1>WELCOME TO<br>KRISHNA RAJPUT WEBSITE</h1>
    <p>Created using Termux 🚀</p>
</div>

</body>
</html>

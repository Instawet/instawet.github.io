<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            background-color: black;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        #centered-image {
            width: 500px;
            height: 500px;
        }
        #top-banner {
            background-color: red;
            color: white;
            text-align: center;
            padding: 10px;
            width: 100%;
        }
        #bottom-left {
            color: white;
            text-align: left;
            padding: 10px;
            position: absolute;
            bottom: 0;
            left: 0;
        }
        #bottom-right {
            color: white;
            text-align: right;
            padding: 10px;
            position: absolute;
            bottom: 0;
            right: 0;
        }
    </style>
</head>
<body>
    <div id="top-banner">
        Coming soon...
    </div>
    <img id="centered-image" src="Instawet.jpg" alt="Centered Image">
    <div id="bottom-left">
        Copyright 2023 instawet Inc
    </div>
    <div id="bottom-right">
        <a href="mailto:info@instawet.nl">Contact</a>
    </div>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <title>Two Equal Sections</title>

    <!-- Internal CSS -->
    <style>
        body {
            margin: 0;
        }

        .container {
            display: flex;
            height: 100vh;
        }

        .left, .right {
            width: 50%;
            text-align: center;
            padding-top: 100px;
            font-size: 20px;
            color: white;
        }

        .left {
            background-color: blue;
        }

        .right {
            background-color: green;
        }
    </style>
</head>

<body>

<div class="container">
    <div class="left">
        <h2>Left Section</h2>
    </div>

    <div class="right">
        <h2>Right Section</h2>
    </div>
</div>

</body>
</html>

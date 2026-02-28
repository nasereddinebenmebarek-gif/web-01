<!DOCTYPE html>
<html>

<head>
    <title>Lab 01</title>

    <style>
        body {
            font-family: Cambria;
        }

        .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .style1 {
            color: red;
        }

        .style2 {
            color: green;
            font-size: 16px;
            font-weight: bold;
        }

        .style3 {
            font-size: 14px;
        }

        .style4 {
            width: 250px;
            height: 250px;
        }
    </style>
</head>

<body>

    <h1>Welcome to my Web Site</h1>
    <h2 class="style1">Web Development (Lab1)</h2>

    <div class="container">

        <p class="style2">
            Full name: <span class="style3">Naserdden ben mbarek</span><br>
            Age: <span class="style3">21 years old</span><br>
            Class: <span class="style3">2nd LMD Computer Science</span><br>
            University: <span class="style3">University of EL OUED</span>
        </p>

        <img src="photo.png" class="style4">

    </div>

</body>
</html>

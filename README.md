<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>University Navigation Menu</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            background-color: #f5f5f5;
        }

        .navbar {
            background-color: #04203f;
            padding: 0;
        }

        .navbar ul {
            list-style: none;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .navbar li {
            display: inline-block;
        }

        .navbar a {
            display: block;
            color: #ffffff;
            text-decoration: none;
            font-weight: bold;
            padding: 15px 25px;
            transition: background 0.3s, color 0.3s;
        }

        .navbar a.active {
            background-color: #F9A825;
            color: #000;
        }

        .navbar a:hover {
            background-color: #F9A825;
            color: #000000;
        }

        .welcome {
            background-color: #98f0c2;
            padding: 10px;
            margin-top: 25px;
        }

        h2 {
            color: black;
            font-size: 1.2rem;
            font-weight: bold;
        }

        p {
            margin-top: 25px;
            color: #a33a3a;
            font-size: 0.9rem;
            margin-left: 5px;
        }
    </style>
</head>

<body>
    <header>
        <nav class="navbar">
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ACADEMICS</a></li>
                <li><a href="#">ADMISSIONS</a></li>
                <li><a href="#">RESEARCH</a></li>
                <li><a href="#">CONTACT</a></li>
            </ul>
        </nav>
    </header>

    <section class="welcome">
        <h2>Welcome to Lovely Professional University</h2>
    </section>
    <p>To Explore our programs, admissions, and research opportunities available in LPU Campus</p>
</body>

</html>

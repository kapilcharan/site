<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>gym fitness</title>
    <style>
        body {
            background-image: url("https://previews.123rf.com/images/artyme83/artyme831711/artyme83171100020/89531978-athletic-young-woman-after-hard-workout-at-gym-fitness-girl-holds-shaker-with-sportive-nutrition.jpg");
            background-position: top center;
            
        }

        h2 {
            color: white;
        }
        form{
            border: 4px solid white;
            border-radius: 15px;
            position:absolute;
            top: 200px; right: 250px;
            padding: 40px;
            margin: 0px;
        }
        .hello{
            padding: 8px;
            width: 300px;
            margin: 2px;
            text-align: center;
            font-family: 'Baloo Bhai', cursive;
            border: 2px solid white;
            border-radius: 10px;
        }
        #sb{
            width: 320px;
            background-color: black;
            color: white;
            text-align: center;
            border: 2px solid white;
            padding: 8px;
            margin: 4px;
            border-radius: 10px;

        }
        #div1{
            position: absolute;
            top: 32px; left: 12px;
            background-color: black;
            color: white;
            font-family: 'Baloo Bhai', cursive;
            border: 2px solid white;
            border-radius: 11px;
            padding: 10px;
        }
        #div2{
            position: absolute;
            top: 32px;left: 116px;
            background-color: black;
            color: white;
            font-family: 'Baloo Bhai', cursive;
            border: 2px solid white;
            border-radius: 11px;
            padding: 10px;

        }
        .nav ul{
            overflow: auto;
            list-style: none;
        }
        .nav li{
            float: right;
            list-style: none;
            color: white;
            margin: 12px;
        }
        .nav a{
            list-style: none;
            color: white;
        }

        

    </style>
</head>

<body>
        <form action="backend.php">
            <h2>Join the best gym of Delhi now</h2>
            <input type="text" name="name" class="hello" placeholder="Enter your Name"><br>
            <input type="number" name="name" class="hello" placeholder="Enter your Age"><br>
            <input type="text" name="name" class="hello" placeholder="Enter your Gender"><br>
            <input type="text" name="name" class="hello" placeholder="Enter your Locality"><br>
            <input type="email" name="name" class="hello" placeholder="Enter your Email Id"><br>
            <input type="text" name="name" class="hello" placeholder="Enter your Phone Number"><br>
            <button type="submit" name="submit" id="sb">Submit</button>
        </form>
    <header>
        <nav class="nav">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <div>
        <button type="submit" id="div1"> call us now</button>
    </div>
    <div>
        <button type="submit" id="div2">email us</button>
    </div>

</body>

</html>

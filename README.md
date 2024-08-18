<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

    
    <title>Document</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background: rgb(112, 112, 247);
        }

        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            background: white;
            width: 600px;
            margin: auto;
            margin-top: 250px;
            border-radius: 15px;

        }

        .d {
            display: flex;
            width: 100%;
        }

        .color {
            background-color: rgb(102, 5, 68);
            border-radius: 15px;
            padding: 3px;
            color: white;
            padding: 8px 20px;
            display: flex;
            gap: 30px;
        }

        a{
            text-decoration: none;
            color: white;

        }

        input {
            text-align: center;
            border: none;
            outline: none;
        }

      

        .selec {
            background-color: white;
            width: 150px;
            display: flex;
            justify-content: center;
            margin-top: 10px;
            position: relative;
            left: 24%;
            border-radius: 10px;
            padding-top: 8px;
            padding-bottom: 8px;

        }

        .selecthere {
            display: flex;
            flex-direction: column;
            gap: 10px;

        }

        .selecthere a {
            color: black;
        }
        input::placeholder{
            font-weight: 400;
            color: rgb(102, 5, 68);
        }
        .k{
        display: flex;
        justify-content:space-between;
        margin: auto;
        width: 100%;
        padding-right: 10px;
        }
        i{
            color: white;
        }
        p i{
            color: rgb(102, 5, 68);
            font-size: 20px;
            font-weight: 800;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="d">
            <div class="color">
                <a href="">Everything</a>
                <button onclick="toggleClass()"><i class="fas fa-angle-up search-icon"></i><button>
            </div>
<div class="k">
            <input type="text" placeholder="Search Anything">

            <p><i class="fas fa-search search-icon"></i></p>
        </div>
        </div>

    </div>


    <div class="hidden" id="l">
        <div class="selec">
            <div class="selecthere">
                <a href="">Everything</a>
                <a href="">Sotware developer</a>
                <a href="">Web developer</a>
                <a href="">Data Analyst</a>
                <a href=""> IT consulte</a>
                <a href="">Network cyfcghvj</a>
            </div>
        </div>
    </div>
    <script src="m.js"></script>
</body>

</html>

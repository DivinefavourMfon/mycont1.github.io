<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            padding: 0;
            margin: 0;
            background-color: orange;
        }
        #container{
            display: grid;
            place-items: center;
            margin-top: 100px;
        }
        form{
            width: 400px;
            height: fit-content;
            border-radius: 10px;
            padding: 30px;
            text-align: center;
            background-color: white;
        }
        input{
            width: 100%;
            font-weight: bold;
            border-radius: 5px;
            border: 3px solid grey;
            font-size: 15px;
            height: 30px;
        }
        textarea{
            width: 100%;
            font-weight: bold;
            border-radius: 5px;
            border: 3px solid grey;
            height: 80px;
            font-size: 15px;
            font-family: arial;
            resize: none;
        }
        button{
            font-size: 20px;
            width: 102%;
            height: 35px;
            font-weight: bold;
            background-color: orange;
            color: white;
            border: none;
            border-radius: 5px;
            font-family: segoe ui;
        }
        #vip{
            width: 100%;
            height: 20px;
            background-color: #fe8b8e;
            text-align: center;
            margin-bottom: 20px;
            padding: 10px;
            font-size: 14px;
            transition: all 0.5s ease;
        }
    </style>
</head>
<body>
    <div id="container">
        <form>
            <a style=" font-size: 33px; font-family: verdana; font-weight: bold;">CONTACT US</a><br>
            <div id="vip"></div>
            <br>
            <input type="text" placeholder="Name" required><br><br>
            <input type="text" placeholder="Subject" required><br><br>
            <input type="text" placeholder="Phone" required><br><br>
            <input type="email" placeholder="Email" required><br><br>
            <textarea placeholder="Message" required></textarea><br><br>
            <button>SUBMIT</button>
        </form>
    </div>
</body>
</html>

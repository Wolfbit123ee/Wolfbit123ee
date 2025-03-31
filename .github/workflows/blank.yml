<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Auto Decrease Counter</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: white;
            color: black;
        }
        h1 {
            color: orange;
            font-weight: bold;
        }
        .counter {
            font-size: 50px;
            font-weight: bold;
            color: black;
        }
        .info-box {
            display: inline-block;
            background-color: rgba(211, 211, 211, 0.5);
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }
        .buttons {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin-top: 20px;
        }
        button {
            font-size: 18px;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            width: 200px;
            font-weight: bold;
        }
        .blue { color: blue; }
        .red { color: red; }
        .yellow { color: yellow; }
        .green { color: green; }
        .pink { color: pink; }
        .bold { font-weight: bold; }
        .black-btn { background-color: black; color: white; }
    </style>
</head>
<body>

    <h1><span class="bold yellow">!RESET</span> = <span class="bold">-1</span></h1>
    <h2>
        <span class="bold blue">LIKE = -3</span> 
        <span class="bold red">SUB = -3</span>
    </h2>

    <div class="info-box">
        <h2><span class="bold blue">$2 = -500</span></h2>
        <h2><span class="bold green">$5 = -1000</span></h2>
        <h2><span class="bold yellow">$20 = help me</span></h2>
        <h2><span class="bold pink">$50 = break mouse</span></h2>
        <h2><span class="bold red">$100 = face reveal</span></h2>
        <h2><span class="bold red">$300 = restart</span></h2>
    </div>

    <h1 class="counter" id="counter">99999998957</h1>

    <div class="buttons">
        <button class="black-btn" onclick="updateCounter(-1)">RESET (-1)</button>
        <button class="black-btn" onclick="updateCounter(+2)">Plus (+2)</button>
        <button class="black-btn" onclick="updateCounter(-3)">SUB (-3)</button>
        <button class="black-btn" onclick="updateCounter(-500)">$2 (-500)</button>
        <button class="black-btn" onclick="updateCounter(-1000)">$5 (-1000)</button>
        <button class="black-btn" onclick="updateCounter(+99999999000)">RESET</button>
    </div>

    <script>
        let count = 99999998957;
        function updateCounter(value) {
            count += value;
            document.getElementById("counter").innerText = count;
        }

        // Auto decrease counter every 2 seconds (-3)
        setInterval(() => {
            updateCounter(-3);
        }, 2000);
    </script>

</body>
</html>

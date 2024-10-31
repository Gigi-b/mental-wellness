<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mental Wellness Quotes</title>
    <style>
        body {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            text-align: center;
            padding: 20px;
        }
        #quote-box {
            max-width: 600px;
            padding: 20px;
            border-radius: 8px;
            background-color: #ffffff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        #quote {
            font-size: 1.5em;
            margin-bottom: 15px;
        }
    </style>
</head>
<body>
    <div id="quote-box">
        <div id="quote"></div>
        <p>- Stay Positive, Stay Healthy -</p>
    </div>

    <script>
        const quotes = [
            "Happiness is not by chance, but by choice.",
            "The only way to be truly happy is to love what you do.",
            "Positive thinking leads to positive outcomes.",
            "Mental wellness is the key to a fulfilling life.",
            "Surround yourself with people who uplift you.",
            "Your mind is a powerful thing. When you fill it with positive thoughts, your life will start to change.",
            "Take time for self-care and recharge your soul."
        ];

        function getRandomQuote() {
            const randomIndex = Math.floor(Math.random() * quotes.length);
            return quotes[randomIndex];
        }

        document.getElementById("quote").textContent = getRandomQuote();
    </script>
</body>
</html>

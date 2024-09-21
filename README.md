<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SAMAYSBD Vegetarian Diet Plans</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background-color: #000000;
            color: #ffffff;
        }
        .container {
            text-align: center;
            background-color: #1a1a1a;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(255,255,255,0.1);
            max-width: 600px;
            width: 90%;
        }
        h1, h2 {
            color: #ffff00;
            margin-bottom: 1rem;
        }
        select {
            margin-top: 1rem;
            padding: 0.5rem;
            font-size: 1rem;
            background-color: #ffff00;
            color: #000000;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        #packageInfo {
            margin-top: 2rem;
            display: none;
        }
        .price {
            font-size: 1.5rem;
            margin: 1rem 0;
        }
        .original-price {
            text-decoration: line-through;
            color: #888;
        }
        .current-price {
            color: #ffff00;
            font-weight: bold;
        }
        .veg-info {
            font-style: italic;
            color: #00ff00;
        }
        .contact-info {
            margin-top: 1rem;
            text-align: left;
        }
        .contact-item {
            display: flex;
            align-items: center;
            margin: 0.5rem 0;
        }
        .contact-item img {
            width: 24px;
            height: 24px;
            margin-right: 0.5rem;
        }
        .qr-code {
            margin-top: 1rem;
            text-align: center;
        }
        .qr-code img {
            width: 150px;
            height: 150px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>SAMAYSBD</h1>
        <h2>Transform Yourself with Our Vegetarian Diet Plans</h2>
        <p class="veg-info">All our diet plans are pure vegetarian</p>
        <select id="goalSelect" onchange="showPackage()">
            <option value="">Choose your package</option>
            <option value="Muscle Gain Diet Plan">Muscle Gain Diet Plan Package</option>
            <option value="Weight Loss Diet Plan">Weight Loss Diet Plan Package</option>
        </select>
        <div id="packageInfo">
            <h3 id="packageTitle"></h3>
            <div class="price">
                <span class="original-price">₹200</span>
                <span class="current-price">₹149 only</span>
            </div>
            <p>To get started, please reply with the following information:</p>
            <ul style="text-align: left;">
                <li>Age</li>
                <li>Gender</li>
                <li>Current Body Weight</li>
                <li>Height</li>
                <li>Activity Level (No activity, Moderate Activity, Heavy Activity)</li>
                <li>Any medical conditions or allergies</li>
                <li>Dietary preferences or restrictions (besides being vegetarian)</li>
                <li>Specific fitness goals (e.g., weight loss target, muscle gain target)</li>
                <li>Current diet overview</li>
                <li>Any supplements you're currently taking</li>
            </ul>
            <p>To:</p>
            <div class="contact-info">
                <div class="contact-item">
                    <img src="/api/placeholder/24/24" alt="Gmail logo" /> samaysbd@gmail.com
                </div>
                <div class="contact-item">
                    <img src="/api/placeholder/24/24" alt="Instagram logo" /> @samaysbd
                </div>
            </div>
            <div class="qr-code">
                <a href="https://www.instagram.com/samaysbd?igsh=a2R0NTJ4cmJnZ2N1" target="_blank">
                    <img src="/api/placeholder/150/150" alt="Instagram QR Code" />
                </a>
            </div>
        </div>
    </div>

    <script>
        function showPackage() {
            const goal = document.getElementById('goalSelect').value;
            const packageInfo = document.getElementById('packageInfo');
            const packageTitle = document.getElementById('packageTitle');
            
            if (goal) {
                packageTitle.textContent = goal + " Package";
                packageInfo.style.display = 'block';
            } else {
                packageInfo.style.display = 'none';
            }
        }
    </script>
</body>
</html>

<!--
**samaysbd/samaysbd** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

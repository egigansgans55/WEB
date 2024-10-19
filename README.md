<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Painel XIT</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        body {
            background-color: #212121;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
            padding: 20px;
        }
        .container {
            background-color: #333;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
            width: 100%;
            max-width: 400px; /* Kontainer lurus ke bawah */
        }
        h1, h2 {
            color: #fff;
            text-align: center;
            margin-bottom: 15px;
        }
        h1 {
            font-size: 1.6em;
        }
        h2 {
            font-size: 1.3em;
        }
        ul.feature-list {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        .feature-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin: 10px 0;
            padding: 10px;
            background-color: #444;
            border-radius: 8px;
            transition: background-color 0.3s ease;
        }
        .feature-item:hover {
            background-color: #555;
        }
        .feature-item label {
            font-weight: bold;
            color: #fff;
        }
        .buttons {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
            flex-direction: column;
        }
        .btn {
            width: 100%;
            padding: 12px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.2s ease;
            margin-bottom: 10px; /* Agar tombol tidak terlalu berdempetan */
        }
        .btn:active {
            transform: scale(0.98);
        }
        .btn-inject {
            background-color: #4CAF50;
            color: white;
        }
        .btn-inject:hover {
            background-color: #43a047;
        }
        .btn-clean {
            background-color: #f44336;
            color: white;
        }
        .btn-clean:hover {
            background-color: #d32f2f;
        }
        .slider-container {
            margin: 20px 0;
        }
        .slider-container h3 {
            margin-bottom: 10px;
            color: #fff;
        }
        .slider {
            width: 100%;
        }
        #save-settings {
            width: 100%;
            background-color: #2196F3;
            color: white;
            padding: 12px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 20px;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }
        #save-settings:hover {
            background-color: #1976D2;
        }
        #save-settings:active {
            transform: scale(0.98);
        }
        .credits {
            text-align: center;
            color: #bbb;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1><b>RICO TRICK ⚙️🩸</b></h1>
        <h2><b>PAINEL XIT ☠️✅</b></h2>
        <ul class="feature-list">
            <li class="feature-item"><label>ELITE AIMBOT</label><input type="checkbox"></li>
            <li class="feature-item"><label>AIMBT 2X</label><input type="checkbox"></li>
            <li class="feature-item"><label>AUTO HEAD</label><input type="checkbox"></li>
            <li class="feature-item"><label>SUPRESOR</label><input type="checkbox"></li>
            <li class="feature-item"><label>REGEDIT</label><input type="checkbox"></li>
        </ul>
        <div class="buttons">
            <button id="injectBtn" class="btn btn-inject">ACTIVATE</button>
            <button class="btn btn-clean">RESET</button>
        </div>
        <h2>AIM CALIBRADOR</h2>
        <div class="slider-container">
            <h3><strong>AIMBOT :</strong></h3>
            <input id="headshot-assertiveness" class="slider" type="range" min="0" max="100" value="50">
            <p id="headshot-assertiveness-value" style="color: #fff;">50</p>
        </div>
        <div class="slider-container">
            <h3><strong>SENSIBILIDAD:</strong></h3>
            <input id="sensitivity" class="slider" type="range" min="0" max="100" value="50">
            <p id="sensitivity-value" style="color: #fff;">50</p>
        </div>
        <button id="save-settings">GUARDAR</button>
        <p class="credits">@Riquinho iOS</p>
    </div>

    <script>
        const aimbotSlider = document.getElementById('headshot-assertiveness');
        const aimbotValue = document.getElementById('headshot-assertiveness-value');
        const sensitivitySlider = document.getElementById('sensitivity');
        const sensitivityValue = document.getElementById('sensitivity-value');

        // Update AIMBOT value dynamically
        aimbotSlider.oninput = function() {
            aimbotValue.textContent = this.value;
        }

        // Update SENSIBILIDAD value dynamically
        sensitivitySlider.oninput = function() {
            sensitivityValue.textContent = this.value;
        }
    </script>
</body>
</html> <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Painel XIT</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        body {
            background-color: #212121;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
            padding: 20px;
        }
        .container {
            background-color: #333;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
            width: 100%;
            max-width: 400px; /* Kontainer lurus ke bawah */
        }
        h1, h2 {
            color: #fff;
            text-align: center;
            margin-bottom: 15px;
        }
        h1 {
            font-size: 1.6em;
        }
        h2 {
            font-size: 1.3em;
        }
        ul.feature-list {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        .feature-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin: 10px 0;
            padding: 10px;
            background-color: #444;
            border-radius: 8px;
            transition: background-color 0.3s ease;
        }
        .feature-item:hover {
            background-color: #555;
        }
        .feature-item label {
            font-weight: bold;
            color: #fff;
        }
        .buttons {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
            flex-direction: column;
        }
        .btn {
            width: 100%;
            padding: 12px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.2s ease;
            margin-bottom: 10px; /* Agar tombol tidak terlalu berdempetan */
        }
        .btn:active {
            transform: scale(0.98);
        }
        .btn-inject {
            background-color: #4CAF50;
            color: white;
        }
        .btn-inject:hover {
            background-color: #43a047;
        }
        .btn-clean {
            background-color: #f44336;
            color: white;
        }
        .btn-clean:hover {
            background-color: #d32f2f;
        }
        .slider-container {
            margin: 20px 0;
        }
        .slider-container h3 {
            margin-bottom: 10px;
            color: #fff;
        }
        .slider {
            width: 100%;
        }
        #save-settings {
            width: 100%;
            background-color: #2196F3;
            color: white;
            padding: 12px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 20px;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }
        #save-settings:hover {
            background-color: #1976D2;
        }
        #save-settings:active {
            transform: scale(0.98);
        }
        .credits {
            text-align: center;
            color: #bbb;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1><b>RICO TRICK ⚙️🩸</b></h1>
        <h2><b>PAINEL XIT ☠️✅</b></h2>
        <ul class="feature-list">
            <li class="feature-item"><label>ELITE AIMBOT</label><input type="checkbox"></li>
            <li class="feature-item"><label>AIMBT 2X</label><input type="checkbox"></li>
            <li class="feature-item"><label>AUTO HEAD</label><input type="checkbox"></li>
            <li class="feature-item"><label>SUPRESOR</label><input type="checkbox"></li>
            <li class="feature-item"><label>REGEDIT</label><input type="checkbox"></li>
        </ul>
        <div class="buttons">
            <button id="injectBtn" class="btn btn-inject">ACTIVATE</button>
            <button class="btn btn-clean">RESET</button>
        </div>
        <h2>AIM CALIBRADOR</h2>
        <div class="slider-container">
            <h3><strong>AIMBOT :</strong></h3>
            <input id="headshot-assertiveness" class="slider" type="range" min="0" max="100" value="50">
            <p id="headshot-assertiveness-value" style="color: #fff;">50</p>
        </div>
        <div class="slider-container">
            <h3><strong>SENSIBILIDAD:</strong></h3>
            <input id="sensitivity" class="slider" type="range" min="0" max="100" value="50">
            <p id="sensitivity-value" style="color: #fff;">50</p>
        </div>
        <button id="save-settings">GUARDAR</button>
        <p class="credits">@Riquinho iOS</p>
    </div>

    <script>
        const aimbotSlider = document.getElementById('headshot-assertiveness');
        const aimbotValue = document.getElementById('headshot-assertiveness-value');
        const sensitivitySlider = document.getElementById('sensitivity');
        const sensitivityValue = document.getElementById('sensitivity-value');

        // Update AIMBOT value dynamically
        aimbotSlider.oninput = function() {
            aimbotValue.textContent = this.value;
        }

        // Update SENSIBILIDAD value dynamically
        sensitivitySlider.oninput = function() {
            sensitivityValue.textContent = this.value;
        }
    </script>
</body>
</html>

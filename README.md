## Hi there 👋
I'm Sotimboyev Sadulla

<p align="center">
  

 <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="3px">
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:000000,50:4CAF50,100:000000&text=Hii%20I'm%20Sotimboyev%20Sadulla%20Welcome%20to%20my%20GitHub%20profile!&fontSize=30&fontColor=39FF14&animation=twinkling&fontAlignY=38"/>
</p>

 <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="3px">
<h1 align="center" style="color:#39FF14; text-shadow: 0 0 8px #39FF14, 0 0 20px #39FF14;">


<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&duration=2800&pause=900&color=00F260&center=true&vCenter=true&width=820&lines=;I'm%20Al-xorazmiy+vorislari+IT+Student" />
</p>
### 🌐 Men bilan bog'lanish:

<p align="center">
  <a href="https://t.me/Sotimboyev_7" target="_blank">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SOTIMBOYEV - Neon Glitch Effect</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #0b0f19;
            color: #ffffff;
            font-family: 'Courier New', Courier, monospace;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
            flex-direction: column;
        }

        /* Yuqori va pastdagi neon chiziqlar */
        .neon-line-top, .neon-line-bottom {
            position: absolute;
            width: 100%;
            height: 3px;
            background: linear-gradient(90deg, #ff0055, #00ffff, #ff00ff, #00ff66, #ff0055);
            background-size: 400% 400%;
            animation: gradientBorder 4s linear infinite;
        }

        .neon-line-top {
            top: 20px;
        }

        .neon-line-bottom {
            bottom: 20px;
        }

        @keyframes gradientBorder {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* Asosiy konteyner */
        .glitch-container {
            position: relative;
            background-color: #121826;
            padding: 40px 50px;
            border: 2px solid #1f293d;
            border-radius: 8px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.8), inset 0 0 15px rgba(0, 255, 255, 0.05);
        }

        /* Matn dizayni (Grid-block uslubi) */
        .glitch-text {
            font-size: 3.5rem;
            font-weight: 900;
            letter-spacing: 8px;
            text-transform: uppercase;
            position: relative;
            color: #ffffff;
            text-shadow: 
                2px 0 #00ffff, 
                -2px 0 #ff0055,
                0 0 10px rgba(255, 255, 255, 0.8);
            animation: glitchAnim 2.5s infinite linear alternate-reverse;
        }

        /* Har bir harf va blok simulyatsiyasi uchun katakcha chiziqlari */
        .glitch-text span {
            display: inline-block;
            position: relative;
            border: 1px solid rgba(255, 255, 255, 0.4);
            background: rgba(255, 255, 255, 0.03);
            padding: 2px 8px;
            margin: 0 2px;
            box-shadow: inset 0 0 8px rgba(0, 255, 255, 0.2);
        }

        /* Glitch animatsiyasi */
        @keyframes glitchAnim {
            0% {
                text-shadow: 2px 0 #00ffff, -2px 0 #ff0055;
                transform: translate(0);
            }
            20% {
                text-shadow: -3px 0 #00ffff, 3px 0 #ff0055;
                transform: translate(-2px, 2px);
            }
            40% {
                text-shadow: 3px 0 #00ff66, -3px 0 #00ffff;
                transform: translate(2px, -1px);
            }
            60% {
                text-shadow: 1px 0 #ff0055, -1px 0 #00ff66;
                transform: translate(-1px, -2px);
            }
            80% {
                text-shadow: -2px 0 #ff00ff, 2px 0 #00ffff;
                transform: translate(1px, 2px);
            }
            100% {
                text-shadow: 2px 0 #00ffff, -2px 0 #ff0055;
                transform: translate(0);
            }
        }
    </style>
</head>
<body>

    <div class="neon-line-top"></div>

    <div class="glitch-container">
        <h1 class="glitch-text">
            <span>S</span><span>O</span><span>T</span><span>I</span><span>M</span><span>B</span><span>O</span><span>Y</span><span>E</span><span>V</span>
        </h1>
    </div>

    <div class="neon-line-bottom"></div>

</body>
</html>


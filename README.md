<!DOCTYPE html>
<html lang="am">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ንጋት የዜማ መሳሪያዎች | Nigat Melody</title>
    <style>
        :root {
            --primary-gradient: linear-gradient(135deg, #ff8c00 0%, #ee0979 100%);
            --glass: rgba(255, 255, 255, 0.1);
            --gold: #ffd700;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background: #0a0a0a;
            color: white;
            overflow: hidden; /* Prevents scroll during transition */
        }

        /* Full Screen Background with Animated Gradient */
        .main-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            background: linear-gradient(45deg, #0f0c29, #302b63, #24243e);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* PAGE 1: THE WELCOME */
        .page {
            height: 100vh;
            width: 100%;
            position: absolute;
            transition: transform 0.8s cubic-bezier(0.7, 0, 0.3,

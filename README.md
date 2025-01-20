# vert_ws
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Vertical Scroll Website</title>
    <link rel="stylesheet" href="styles.css">
    <script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_GA_TRACKING_ID"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag() { dataLayer.push(arguments); }
        gtag('js', new Date());
        gtag('config', 'YOUR_GA_TRACKING_ID');
    </script>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }

        .slides {
            display: flex;
            flex-direction: column;
            width: 100%;
        }

        .slide {
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #f0f0f0;
            border-bottom: 1px solid #ccc;
        }

        .slide iframe {
            width: 90%;
            height: 90%;
            border: none;
        }

        /* Optional: Add custom styles for smooth scrolling indicators */
        .scroll-indicator {
            position: fixed;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            color: #555;
            font-size: 14px;
            text-align: center;
        }

        .scroll-indicator span {
            display: block;
        }
    </style>
</head>

<body>

    <div class="slides">
        <div class="slide">
            <iframe loading="lazy" src="https://www.canva.com/design/DAGcpgRQm5g/m5X6n6fgsvno_HztzdGBHw/view?embed" allowfullscreen="allowfullscreen" allow="fullscreen"></iframe>
        </div>
        <div class="slide">
            <iframe loading="lazy" src="https://www.canva.com/design/DAGcpgRQm5g/m5X6n6fgsvno_HztzdGBHw/view?embed" allowfullscreen="allowfullscreen" allow="fullscreen"></iframe>
        </div>
        <!-- Add more slides as needed -->
    </div>

    <div class="scroll-indicator">
        <span>&darr; Scroll Down &darr;</span>
    </div>

</body>

</html>

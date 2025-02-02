
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I Love You</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            background: radial-gradient(circle, #ff99cc, #ffccdd); /* Gradient background */
            color: #000;
            margin: 0;
            padding: 20px;
            overflow-x: hidden; /* Prevent horizontal scrolling */
            display: flex; /* Use flexbox */
            flex-direction: column; /* Column layout */
            align-items: center; /* Center horizontally */
            justify-content: flex-start; /* Align items at the start */
            min-height: 100vh; /* Minimum height for scrolling */
        }
        .container {
            background: rgba(255, 228, 225, 0.9); /* Soft pastel pink with transparency */
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.5); /* Enhanced shadow for floating effect */
            width: 100%; /* Full width */
            max-width: 800px; /* Increased max-width */
            margin: 20px auto; /* Center the container */
            animation: float 3s ease-in-out infinite; /* Floating animation */
            text-align: center; /* Center text and heart */
        }
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
        h1 {
            font-size: 3em; /* Increased font size */
            margin-bottom: 20px;
            color: #d5006d; /* Darker pink for contrast */
        }
        p {
            font-size: 1.2em;
            margin: 15px 0;
            line-height: 1.5;
            color: #333; /* Darker text for better readability */
        }
        .heart {
            font-size: 60px;
            margin: 20px 0;
            color: #ff69b4; /* Pink heart */
        }
        .heart-background {
            position: absolute;
            width: 100%;
            height: 100%;
            pointer-events: none; /* Allow clicks to go through */
            z-index: 0; /* Ensure it is behind the container */
        }
        .heart-background span {
            position: absolute;
            font-size: 20px; /* Size of the hearts */
            opacity: 0.1; /* Light opacity for subtlety */
            animation: float 5s infinite; /* Floating animation */
        }
        .spacer {
            height: 100vh; /* Spacer height */
        }
    </style>
</head>
<body>
    <div class="heart-background">
        <span style="top: 3%; left: 10%;">❤️</span>
        <span style="top: 10%; left: 70%;">❤️</span>
        <span style="top: 20%; left: 30%;">❤️</span>
        <span style="top: 15%; left: 50%;">❤️</span>
        <span style="top: 25%; left: 80%;">❤️</span>
        <span style="top: 30%; left: 20%;">❤️</span>
        <span style="top: 40%; left: 60%;">❤️</span>
        <span style="top: 12%; left: 85%;">❤️</span>
        <span style="top: 55%; left: 5%;">❤️</span>
        <span style="top: 65%; left: 40%;">❤️</span>
        <span style="top: 70%; left: 90%;">❤️</span>
        <span style="top: 75%; left: 15%;">❤️</span>
        <span style="top: 85%; left: 35%;">❤️</span>
        <span style="top: 30%; left: 75%;">❤️</span>
        <span style="top: 45%; left: 50%;">❤️</span>
        <span style="top: 65%; left: 20%;">❤️</span>
        <span style="top: 50%; left: 80%;">❤️</span>
        <span style="top: 90%; left: 60%;">❤️</span>
        <span style="top: 80%; left: 10%;">❤️</span>
        <span style="top: 55%; left: 90%;">❤️</span>
        <span style="top: 40%; left: 15%;">❤️</span>
        <span style="top: 25%; left: 65%;">❤️</span>
        <span style="top: 10%; left: 25%;">❤️</span>
        <span style="top: 75%; left: 50%;">❤️</span>
    </div>
    <div class="container">
        <h1>Happy Valentine's Day, Athira!</h1>
        <div class="heart">❤️</div>
        <p>
            I don’t even know how to put this into words, but I love you, Athira. You’ve been there for me when I was at my lowest, and I honestly don’t know what I would have done without you.
        </p>
        <p>
            I’m so grateful for you—for your kindness, your patience, and for just being there when I needed someone the most. You’ve made my life so much better just by being in it.
        </p>
        <p>
            I hope you know how much I love you, Athira, and how much I appreciate everything you’ve done for me. I’ll always do my best to make you as happy as you’ve made me.
        </p>
    </div>
    <div class="spacer"></div> <!-- Spacer to enable scrolling -->
</body>
</html>

# codsoft_taskno2
Landing page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4, #fad0c4, #fbc2eb);
            text-align: center;
            color: white;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            overflow: hidden;
        }
        h1 {
            font-size: 3rem;
            animation: fadeIn 2s ease-in-out;
        }
        p {
            font-size: 1.5rem;
            margin: 20px;
        }
        .btn {
            background: #ff6b6b;
            padding: 15px 30px;
            border: none;
            border-radius: 30px;
            color: white;
            font-size: 1.2rem;
            cursor: pointer;
            transition: 0.3s;
        }
        .btn:hover {
            background: #ff4757;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-100px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <h1>Welcome to web World!</h1>
    <p>Discover amazing experiences with us.</p>
    <button class="btn" onclick="showMessage()">Get Started</button>
    
    <script>
        function showMessage() {
            alert("Thanks for visiting! Stay tuned for more.");
        }
    </script>
</body>
</html>

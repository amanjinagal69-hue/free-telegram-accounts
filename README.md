<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Telegram Premium Access</title>
</head>
<body style="margin: 0; padding: 0; font-family: sans-serif; background: url('43841e28ad24c45c4869ce51f342316e.jpg') no-repeat center center fixed; background-size: cover; display: flex; justify-content: center; align-items: center; height: 100vh;">

    <div style="background: rgba(255, 255, 255, 0.9); padding: 30px; border-radius: 20px; box-shadow: 0 8px 16px rgba(0,0,0,0.3); text-align: center; width: 85%; max-width: 400px;">
        <h1 style="color: #0088cc; margin-top: 0;">Telegram Premium</h1>
        <p style="margin-bottom: 25px; color: #333;">अपना फ्री अकाउंट क्लेम करने के लिए पहले शेयर करें!</p>
        
        <button onclick="sharePage()" style="display: block; width: 100%; padding: 15px; margin-bottom: 15px; background: #25D366; color: white; border: none; border-radius: 10px; font-size: 16px; font-weight: bold; cursor: pointer;">SHARE WITH FRIENDS</button>
        
        <button onclick="claimAccess()" style="display: block; width: 100%; padding: 15px; background: #0088cc; color: white; border: none; border-radius: 10px; font-size: 16px; font-weight: bold; cursor: pointer;">CLAIM ACCESS NOW</button>
    </div>

    <script>
        function sharePage() {
            if (navigator.share) {
                navigator.share({
                    title: 'Free Telegram Premium',
                    text: 'Check this out! Get free premium here:',
                    url: window.location.href
                });
            } else {
                alert('लिंक कॉपी हो गया, इसे दोस्तों को शेयर करें!');
            }
        }

        function claimAccess() {
            alert('चेकिंग हो रही है... कृपया पहले 5 अलग-अलग ग्रुप्स में शेयर करें!');
        }
    </script>
</body>
</html>

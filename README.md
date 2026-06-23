<!DOCTYPE html>
<html>
<head>
    <title>Get Free Telegram Access</title>
</head>
<body style="text-align: center; padding: 40px; font-family: sans-serif; background-color: #f0f2f5;">
    <div style="background: white; padding: 30px; border-radius: 15px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
        <h1>Telegram Premium Access</h1>
        <p>अपना फ्री अकाउंट क्लेम करने के लिए पहले शेयर करें!</p>
        
        <button onclick="sharePage()" style="display: block; width: 100%; padding: 15px; margin-bottom: 10px; background: #25D366; color: white; border: none; border-radius: 8px; font-size: 16px; font-weight: bold;">SHARE WITH FRIENDS</button>
        
        <button onclick="claimAccess()" style="display: block; width: 100%; padding: 15px; background: #0088cc; color: white; border: none; border-radius: 8px; font-size: 16px; font-weight: bold;">CLAIM ACCESS NOW</button>
    </div>

    <script>
        function sharePage() {
            if (navigator.share) {
                navigator.share({
                    title: 'Free Telegram Accounts',
                    text: 'Check this out! Get free access here:',
                    url: window.location.href
                });
            } else {
                alert('लिंक कॉपी हो गया, दोस्तों को शेयर करें!');
            }
        }

        function claimAccess() {
            alert('शेयरिंग चेक की जा रही है... कृपया 5 ग्रुप्स में शेयर करें!');
        }
    </script>
</body>
</html>

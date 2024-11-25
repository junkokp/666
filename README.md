<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>按鈕計數器</title>
    <script>
        let count = 0;
        function buttonClicked() {
            count++;
            if (count >= 1000) {
                document.getElementById("message").innerText = "easy HTML";
            }
        }
    </script>
</head>
<body>
    <h1>按下按鈕1000次來揭曉秘密訊息</h1>
    <button onclick="buttonClicked()">點我！</button>
    <p id="message"></p>
</body>
</html>

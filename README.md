<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>رسالة لشوشو</title>
    <style>
        body {
            background-color: #f3f4f6;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        h1 {
            color: #ff69b4;
            font-size: 3em;
        }
        p {
            color: #333;
            font-size: 1.5em;
        }
        .message {
            margin-top: 20px;
            font-style: italic;
            font-size: 1.2em;
            color: #555;
        }
    </style>
</head>
<body>

    <h1 id="greeting">ازيك يا شوشو!</h1>
    <p id="message">الرسالة الرومانسية بتاعتك النهاردة:</p>

    <div class="message" id="romanticMessage">
        <script>
            // وظيفة لعرض رسالة رومانسية
            function displayMessage() {
                const messages = [
                    "شوشو، إنتي النور اللي بينور حياتي!",
                    "يا شيماء، حبك أكبر من أي كلام.",
                    "كل لحظة بفتكر فيها اسمك بتفرحني يا شوشو.",
                    "شيماء، إنتي حلمي اللي تحقق.",
                    "شوشو، ضحكتك هي سبب سعادتي!"
                ];

                const randomMessage = messages[Math.floor(Math.random() * messages.length)];
                document.getElementById('romanticMessage').textContent = randomMessage;
            }

            // التحقق من عدد مرات الاستخدام
            let visitCount = localStorage.getItem('visitCount') || 0;

            if (visitCount < 2) {
                displayMessage();
                visitCount++;
                localStorage.setItem('visitCount', visitCount);
            } else {
                document.getElementById('greeting').textContent = "الصفحة انتهت صلاحيتها!";
                document.getElementById('message').textContent = "الرسالة مش متاحة لأنك استخدمتها مرتين.";
                document.getElementById('romanticMessage').textContent = "";
            }
        </script>
    </div>

</body>
</html>

<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>رسالة حب لشيماء</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #fff0f5;
            text-align: center;
            padding: 50px;
            background-image: url('image-url.jpg');
            background-size: cover;
            background-position: center;
            color: #4b0082; /* لون النص */
        }
        .message {
            background-color: rgba(255, 255, 255, 0.8);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            display: inline-block;
            max-width: 600px;
            font-size: 20px;
            color: #4b0082; /* لون النص داخل الرسالة */
        }
    </style>
</head>
<body>
    <h1>عامله اي يا طفلتي ❤️</h1>
    <div class="message">
        <p id="love-message"></p>
    </div>

    <script>
        const messages = [
            "إنتي كل حاجة ليا يا حبيبتي 🌹",
            "بحبك يا نور عيني 🌟، إنتي حياتي كلها",
            "إنتي اللي ماليتي قلبي بالحب يا شوشو 💖",
            "قلبي بيطير لما بشوفك، بحبك يا بنوتي 😘",
            "شيماء، إنتي كل دنيتي ❤️",
            "يا نور عيني، بحس إن حياتي جميلة بيكي 🌸",
            "شوشو، إنتي كل حاجة بحلم بيها 💕",
            "أنا محظوظ إني معاكي، يا طفلتي 💖",
            "شيماء، حبك مالي قلبي وعقلي 💘",
            "بحبك يا حياتي، مفيش زيك في الدنيا 💖",
            "إنتي حبيبتي وأميرة قلبي 💕",
            "كل يوم بحبك أكتر يا نور عيني 🌹",
            "إنتي فرحتي يا شوشو 💖",
            "بشكر ربنا كل يوم عشان إنتي في حياتي يا قلبي ❤️",
            "شيماء، إنتي أحلى هدية في حياتي 🎁",
            "إنتي طفلتي الجميله وملاكي يا حبيبتي 💖",
            "إنتي بتضحكي، وأنا بتعذب بحبك 😘",
            "يا شيماء، إنتي الأمان بتاعي 🛡️",
            "كل يوم بحس إني بحبك أكتر يا شوشو 💘",
            "إنتي ملاكي اللي دايمًا في قلبي ❤️"
        ];

        // اختار رسالة عشوائية
        function getRandomMessage() {
            const randomIndex = Math.floor(Math.random() * messages.length);
            return messages[randomIndex];
        }

        // عرض الرسالة العشوائية
        document.getElementById('love-message').textContent = getRandomMessage();
    </script>
</body>
</html>![-background](https://github.com/user-attachments/assets/e1403950-d551-40d8-ab8e-a978ad508093)

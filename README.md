<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Thu Thập Thông Tin</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .form-container {
            background: #ffffff;
            padding: 20px 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            width: 100%;
        }
        .form-container h2 {
            margin-bottom: 20px;
            color: #6200ea;
        }
        .form-container label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .form-container input, .form-container textarea, .form-container button {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        .form-container button {
            background-color: #6200ea;
            color: #ffffff;
            border: none;
            cursor: pointer;
        }
        .form-container button:hover {
            background-color: #4500b5;
        }
    </style>
</head>
<body>
    <div class="form-container">
        <h2>Form Thu Thập Thông Tin</h2>
        <form action="/submit" method="POST">
            <!-- Họ và tên -->
            <label for="name">Họ và Tên</label>
            <input type="text" id="name" name="name" placeholder="Nhập họ và tên của bạn" required>
            
            <!-- Email -->
            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="Nhập email của bạn" required>
            
            <!-- Số điện thoại -->
            <label for="phone">Số Điện Thoại</label>
            <input type="tel" id="phone" name="phone" placeholder="Nhập số điện thoại" required>
            
            <!-- Tin nhắn -->
            <label for="message">Tin nhắn</label>
            <textarea id="message" name="message" rows="4" placeholder="Nhập tin nhắn hoặc yêu cầu của bạn"></textarea>
            
            <!-- Nút gửi -->
            <button type="submit">Gửi Thông Tin</button>
        </form>
    </div>
</body>
</html>

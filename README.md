<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>روابطي الشخصية</title>
    <style>
        :root {
            --primary: #25D366; /* لون واتساب */
            --bg: #f5f5f5;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: var(--bg);
            text-align: center;
            padding: 20px;
        }
        .profile {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid white;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .link {
            display: block;
            background: white;
            color: #333;
            padding: 15px;
            margin: 15px auto;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            max-width: 400px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: all 0.3s ease;
        }
        .link:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.1);
        }
        .social-icons {
            margin: 20px 0;
        }
        .social-icon {
            margin: 0 10px;
            width: 24px;
        }
    </style>
</head>
<body>
    <img src="https://via.placeholder.com/120" alt="Profile" class="profile">
    <h1>@اسم_المستخدم</h1>
    <p>مرحبًا بكم في روابطي المهمة</p>
    
    <div class="links">
        <a href="#" class="link">💼 الملف الشخصي</a>
        <a href="#" class="link">🛒 متجري الإلكتروني</a>
        <a href="#" class="link">📸 إنستجرام</a>
        <a href="#" class="link">🎬 يوتيوب</a>
        <a href="#" class="link" style="background: var(--primary); color: white;">📱 تواصل عبر واتساب</a>
    </div>
    
    <div class="social-icons">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" class="social-icon" alt="Instagram">
        <img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" class="social-icon" alt="Twitter">
    </div>
</body>
</html>

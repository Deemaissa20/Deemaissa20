<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحة فريق IoTeam</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #121212;
            color: #e0e0e0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1c1c1c;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            color: #ff5722;
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        h2 {
            color: #ff5722;
        }
        form {
            background-color: #1c1c1c;
            padding: 20px;
            border-radius: 5px;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: none;
            border-radius: 5px;
            background-color: #2b2b2b;
            color: #e0e0e0;
        }
        input[type="submit"] {
            background-color: #ff5722;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        input[type="submit"]:hover {
            background-color: #e64a19;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #1c1c1c;
            margin-top: 20px;
        }
        footer a {
            color: #ff5722;
            text-decoration: none;
            margin: 0 10px;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <h1>فريق IoTeam</h1>
    </header>

    <section>
        <h2>نبذة عن الفريق</h2>
        <p>فريق IoTeam هو مجموعة من المتخصصين والمهتمين بتكنولوجيا إنترنت الأشياء (IoT). نسعى إلى تطوير حلول مبتكرة وتحسين تجربة المستخدم في هذا المجال المتنامي.</p>

        <h2>تخصص إنترنت الأشياء</h2>
        <p>تخصص إنترنت الأشياء هو مجال دراسي وتقني يركز على ربط الأجهزة الإلكترونية بالشبكات لتبادل البيانات وتحقيق التفاعل الذكي. يعد هذا التخصص أحد أكثر المجالات تأثيرًا في المستقبل القريب، حيث يساهم في تحسين حياة الناس وجعل الأجهزة أكثر ذكاءً وكفاءة.</p>

        <h2>إرسال اقتراحاتك</h2>
        <form action="#" method="post">
            <input type="text" name="name" placeholder="اسمك" required>
            <input type="email" name="email" placeholder="بريدك الإلكتروني" required>
            <textarea name="suggestion" rows="5" placeholder="أدخل اقتراحك هنا" required></textarea>
            <input type="submit" value="إرسال">
        </form>
    </section>

    <footer>
        <p>تابعنا على وسائل التواصل الاجتماعي:</p>
        <a href="#">فيسبوك</a> | <a href="#">واتساب</a> | <a href="#">إنستقرام</a>
    </footer>

</body>
</html>

# Create an HTML file named "knoz_al_lughah.html"
with open("knoz_al_lughah.html", "w", encoding="utf-8") as f:
    f.write("""
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>كنوز اللغة العربية</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #333;
            text-align: center;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>كنوز اللغة العربية</h1>
        <p>اللغة العربية هي إحدى أجمل اللغات في العالم. إنها لغة القرآن الكريم ولها تاريخ طويل في الأدب والشعر والفلسفة.</p>
        <p>تعتبر اللغة العربية من أغنى اللغات من حيث الكلمات والمفردات، وهي مصدر إلهام للكتّاب والشعراء.</p>
        <p>في هذه الصفحة، سنستكشف بعضًا من كنوز اللغة العربية ونتعرف على جمالها وعمقها.</p>
    </div>
</body>
</html>
""")
print("The webpage 'knoz_al_lughah.html' has been created successfully.")

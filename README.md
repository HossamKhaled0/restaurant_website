/* === style.css === */ body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f8f8f8; }

header { background-color: #d35400; color: white; padding: 15px; text-align: center; }

nav { background-color: #333; text-align: center; padding: 10px 0; }

nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }

main { padding: 20px; max-width: 800px; margin: auto; }

.menu-item { background-color: white; margin: 10px 0; padding: 15px; border-radius: 5px; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); }

form { background-color: white; padding: 20px; border-radius: 5px; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); max-width: 400px; margin: auto; }

input[type="text"], input[type="password"] { width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 4px; }

input[type="submit"] { background-color: #d35400; color: white; border: none; padding: 10px 15px; border-radius: 4px; cursor: pointer; }

/* === index.html === */

<!DOCTYPE html><html>
<head>
  <title>مطعم الذوق الرفيع</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>مطعم الذوق الرفيع</h1>
  </header>
  <nav>
    <a href="index.html">الرئيسية</a>
    <a href="menu.html">القائمة</a>
    <a href="login.html">تسجيل الدخول</a>
  </nav>
  <main>
    <h2>مرحبا بكم في مطعمنا!</h2>
    <p>نقدم أشهى الأطباق الشرقية والغربية بجودة عالية وخدمة مميزة.</p>
  </main>
</body>
</html>/* === menu.html === */

<!DOCTYPE html><html>
<head>
  <title>قائمة الطعام</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>قائمة الطعام</h1>
  </header>
  <nav>
    <a href="index.html">الرئيسية</a>
    <a href="menu.html">القائمة</a>
    <a href="login.html">تسجيل الدخول</a>
  </nav>
  <main>
    <div class="menu-item">
      <h3>مشاوي مشكلة</h3>
      <p>قطع لحم ودجاج مشوي، تقدم مع أرز وسلطة - 45 ريال</p>
    </div>
    <div class="menu-item">
      <h3>بيتزا مارجريتا</h3>
      <p>بيتزا تقليدية مع جبن موزاريلا وطماطم طازجة - 30 ريال</p>
    </div>
    <div class="menu-item">
      <h3>عصير مانجو طازج</h3>
      <p>عصير طبيعي بدون سكر مضاف - 12 ريال</p>
    </div>
  </main>
</body>
</html>/* === login.html === */

<!DOCTYPE html><html>
<head>
  <title>تسجيل الدخول</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>تسجيل الدخول</h1>
  </header>
  <nav>
    <a href="index.html">الرئيسية</a>
    <a href="menu.html">القائمة</a>
    <a href="login.html">تسجيل الدخول</a>
  </nav>
  <main>
    <form>
      <label for="username">اسم المستخدم:</label>
      <input type="text" id="username" name="username" required><label for="password">كلمة المرور:</label>
  <input type="password" id="password" name="password" required>

  <input type="submit" value="دخول">
</form>

  </main>
</body>
</html>

<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>العبها صح</title>
  <link rel="stylesheet" href="style.css">
  <script defer src="script.js"></script>
</head>
<body>
  <!-- الصفحة الرئيسية -->
  <div id="start-screen" class="screen">
    <img src="SXB (1).png" alt="العبها صح" class="start-image">
    <button id="start-button" class="main-button">اختار الفئات</button>
  </div>

  <!-- اختيار الفئات -->
  <div id="category-selection" class="screen hidden">
    <h2>اختر 5 فئات</h2>
    <div class="category-pages">
      <div class="category-page active" id="page1">
        <!-- الصفحة 1 -->
        <div class="category" data-category="شعارات دول">شعارات دول</div>
        <div class="category" data-category="اسم المسلسل">اسم المسلسل</div>
        <div class="category" data-category="خمن الشخصية">خمن الشخصية</div>
        <div class="category" data-category="شعارات السعودية">شعارات السعودية</div>
        <div class="category" data-category="شعارات مطاعم">شعارات مطاعم</div>
        <div class="category" data-category="سوبرماركت">سوبرماركت</div>
        <div class="category" data-category="نوروتو">نوروتو</div>
        <div class="category" data-category="هجوم العمالقة">هجوم العمالقة</div>
      </div>
      <div class="category-page" id="page2">
        <!-- الصفحة 2 -->
        <div class="category" data-category="شارع الأعشى">شارع الأعشى</div>
        <div class="category" data-category="شباب البومب">شباب البومب</div>
        <div class="category" data-category="خريف القلب">خريف القلب</div>
        <div class="category" data-category="خمس نجوم">خمس نجوم</div>
        <div class="category" data-category="إسلامي">إسلامي</div>
        <div class="category" data-category="قرآن">قرآن</div>
        <div class="category" data-category="قصص الأنبياء">قصص الأنبياء</div>
        <div class="category" data-category="من القارئ">من القارئ</div>
      </div>
    </div>
    <div class="pagination">
      <button id="prev-page">‹</button>
      <button id="next-page">›</button>
    </div>
    <button id="confirm-categories" class="main-button">التالي</button>
  </div>

  <!-- إدخال أسماء الفرق -->
  <div id="team-names" class="screen hidden">
    <h2>اكتب أسماء الفرق</h2>
    <input type="text" id="team1-name" placeholder="اسم الفريق الأول">
    <input type="text" id="team2-name" placeholder="اسم الفريق الثاني">
    <button id="start-game" class="main-button">ابدأ اللعبة</button>
  </div>

  <!-- لوحة الأسئلة -->
  <div id="game-board" class="screen hidden">
    <div class="scoreboard">
      <div id="team1-display"></div>
      <div id="team2-display"></div>
    </div>
    <div id="questions-grid"></div>
    <div class="helpers">
      <button id="double-points">دبل النقاط</button>
      <button id="call-friend">اتصال بصديق</button>
    </div>
  </div>
</body>
</html>

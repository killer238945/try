<!DOCTYPE html>
<html lang="ar">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>يوسف ماركت</title>
 <link rel="stylesheet" href="styles.css">
</head>
<body>
 <header>
   <h1>مرحبًا بكم في يوسف ماركت</h1>
   <h2>أفضل المنتجات والخدمات بأفضل الأسعار</h2>
 </header>

 <nav>
   <ul>
      <li><a href="https://www.instagram.com/dominant18o?igsh=MXA5MjVkYjEyNTE3eQ==">انستغرام</a></li>
     <li><a href="#">منتجاتنا</a></li>
     <li><a href="#">من نحن</a></li>
     <li><a href="#">اتصل بنا</a></li>
   </ul>
 </nav>

 <main>
   <section class="products">
     <h2>منتجاتنا</h2>
     <div class="product">
       <img src="product1.jpg" alt="منتج 1">
       <h3>مؤمل  1</h3>
       <p>للمص 1</p>
       <p>السعر: 10000 دينار عراقي</p>
       <button>أضف إلى السلة</button>
     </div>
     <div class="product">
       <img src="product2.jpg" alt="منتج 2">
       <h3>مؤمل</h3>
       <p>للنيج 2</p>
       <p>السعر: 15000 دينار عراقي</p>
       <button>أضف إلى السلة</button>
     </div>
     <!-• يمكنك إضافة المزيد من المنتجات هنا -->
   </section>

   <section class="services">
     <h2>خدماتنا</h2>
     <table>
       <tr>
         <th>امؤمل</th>
         <th>خدامة</th>
         <th>مجاني</th>
       </tr>
       <tr>
         <td>خدمة التوصيل</td>
         <td>توصيل سريع وآمن</td>
         <td>5000 دينار</td>
       </tr>
       <tr>
         <td>خدمة توصلي القحبة</td>
         <td>خدمة احترافي للتوصيل</td>
         <td>10000 دينار</td>
       </tr>
       <!-• يمكنك إضافة المزيد من الخدمات هنا -->
     </table>
   </section>

   <section class="contact">
     <h2>تواصل معنا</h2>
     <form action="submit_form.php" method="post">
       <label for="الاسم">الاسم:</label>
       <input type="text" id="الاسم" name="الاسم" required><br><br>

       <label for="البريد الإلكتروني">البريد الإلكتروني:</label>
       <input type="email" id="البريد الإلكتروني" name="البريد الإلكتروني" required><br><br>

       <label for="رسالة">رسالة:</label>
       <textarea id="رسالة" name="رسالة" required></textarea><br><br>

       <button type="submit">إرسال</button>
     </form>
   </section>
 </main>

 <footer>
   <p>&copy; 2024 يوسف ماركت. جميع الحقوق محفوظة.</p>
 </footer>
</body>
</html>

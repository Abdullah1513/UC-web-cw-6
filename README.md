<p dir="rtl">
<h3><a href="https://github.com/kuwaitcodes/UC-web-cw-5">تمرين </a></h3></p>


<p dir="rtl">
اليوم راح راح نحسب مؤشر وزن الجسم ⚖️!</p>
<h1></h1>
<p dir="rtl">
 <strong><a href="https://docs.google.com/document/d/1x_uAIiWvD_XAvQauaqAsBJpRtgbctJ50kOZBFgnF6-8/edit">الجزء الاول</a></strong></p>




1. قم بعمل fork للـ repository
2. افتح الـ repository باستخدام github desktop
3. افتح ملف script.js وابدأ الحل
4. عرف دالة BMI تستقبل معاملين (weight, height)
    - استخدم المعادلة التالية لحساب مؤشر وزن الجسم:
    <br><code>الوزن / (الطول * الطول)</code>
    - ارجع ناتج المعادلة بإستخدام كلمة return
5. قم بمناداة الدالة داخل console.log ولا تنسى كتابة معاملات
6. احفظ التغييرات وارفع الكود إلى github

<p dir="rtl">
<strong>بونص! ✨</strong></p>

- قم بكتابة معاملات افتراضية للدالة، وكرر الخطوة 5 بدون معاملات!


<h1></h1>

<p dir="rtl">
 <strong><a href="https://docs.google.com/document/d/1ySzER3_FO-PkOdqFfrcQHRU2gVjuXfTMPQ6mt2aoUtE/edit">الجزء الثاني</a></strong></p>

  1. اكمل الخطوات في ملف script.js
  2. عرف دالة Status تستقبل معامل bmi, وترجع لنا قيمة على المقياس التالي:
<div dir="rtl">
  <table>
    <tr><td>return</td><td>bmi</td></tr>
    <tr><td>"لديك نقص في الوزن"</td><td>< 18.5</td></tr>
    <tr><td>"وزنك صحي"</td><td>>= 18.5 && < 25</td></tr>
    <tr><td>"لديك زيادة في الوزن"</td><td>>= 25</td></tr>
  </table>
</div>

3. إذهب إلى وسم h2 في صفحة HTML واستخدم حدث onclick وقم بإستدعاء الدوال التالية:
    <br> <code>alert(Status(BMI(80, 1.8)))</code>
4. احفظ اتغيرات وارفع الكود إلى github
      


 <p dir="rtl">
<strong>بونص! ✨</strong></p>

- قم بإستخدام  حدث onmouseover بدلاً من onclick في الخطوة 5


<h1></h1>

<p dir="rtl">
 <strong><a href="https://docs.google.com/document/d/1Dnjdo8myU3RORp1kgF3O0k_6s2GmYLklxRTS6aSxqZg/edit">الجزء الثالث</a></strong></p>

1. اكمل الخطوات في ملف script.js
2. عرف دالة calculate لتعمل الخطوات التالية عند مناداتها:
    - احفظ قيمة الوزن التي في حقل الإدخال في متغير weight
    - احفظ قيمة الطول التي في حقل الادخال في متغير height
    - احسب المؤشر عن طريق دالة BMI واحفظه في متغير bmi
    - مرر قيمة المؤشر إلى دالة Status واحفظ المرجع في متغير  desc
    - اعرض قيمة متغير bmi ومتغير desc داخل الوسم الذي يحمل هوية result
4. اضف حدث onclick إلى الزر ليستدعي دالة calculate
5. احفظ اتغيرات وارفع الكود إلى github
6. قم بتسليم التمرين على موقع Mentorly


 <p dir="rtl">
<strong>بونص! ✨</strong></p>

- قم بالتعبير عن كل حالة من الحالات بتغيير لون النص، مثلا: 
    - لديك نقص في الوزن  <- باللون البرتقالي
    - وزنك صحي <- باللون الاخضر
    - لديك زيادة في الوزن <- باللون الاحمر

 <p dir="rtl">
آخر موعد لرفع الكود هو نهاية المحاضرة "لا تترددون أنكم تسألون المدرسين 👌"
</p>

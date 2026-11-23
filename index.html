<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>دفتري الرقمي | 15 خدمة</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: system-ui, Tahoma, sans-serif; }
    body { background: #081222; color: #f8fafc; padding: 12px; display: flex; justify-content: center; min-height: 100vh; }
    .app { width: 100%; max-width: 490px; }
    .hidden { display: none !important; }
    .card { background: #10203a; border: 1px solid #22395e; border-radius: 16px; padding: 14px; margin-bottom: 11px; }
    h1, h2, h3 { margin-bottom: 6px; }
    .muted { color: #94a3b8; font-size: 0.8rem; line-height: 1.5; }
    .row { display: flex; gap: 7px; flex-wrap: wrap; }
    input, select { width: 100%; padding: 10px; border-radius: 10px; border: 1px solid #2b4775; background: #091426; color: #fff; margin: 7px 0; font-size: 0.88rem; }
    button { padding: 9px 11px; border-radius: 10px; border: none; font-weight: bold; cursor: pointer; font-size: 0.8rem; }
    .btn-blue { background: #2563eb; color: #fff; }
    .btn-gold { background: #eab308; color: #081222; }
    .btn-green { background: #16a34a; color: #fff; }
    .btn-red { background: #dc2626; color: #fff; }
    .btn-gray { background: #1a2c47; color: #e2e8f0; border: 1px solid #2d466e; }
    .tabs { display: grid; grid-template-columns: repeat(4, 1fr); gap: 5px; margin-bottom: 10px; }
    .tab { background: #10203a; color: #94a3b8; border: 1px solid #22395e; padding: 8px 4px; border-radius: 10px; font-size: 0.75rem; }
    .tab.active { background: #2563eb; color: #fff; }
    .doc { background: #091426; border: 1px solid #1e3559; border-radius: 12px; padding: 11px; margin-bottom: 9px; }
    .doc-title { font-weight: bold; font-size: 0.9rem; }
    .doc-sub { color: #94a3b8; font-size: 0.74rem; margin: 3px 0 8px; }
    .badge { display: inline-block; background: rgba(34,197,94,0.15); color: #86efac; padding: 2px 7px; border-radius: 999px; font-size: 0.7rem; }
    .badge-w { background: rgba(245,158,11,0.18); color: #fcd34d; }
    .link-row { display: flex; justify-content: space-between; align-items: center; gap: 8px; background: #091426; border: 1px solid #1e3559; border-radius: 11px; padding: 10px; margin-bottom: 8px; }
    .link-row a { text-decoration: none; }
    .paper { background: #fffef9; color: #111; border: 4px double #7f1d1d; padding: 15px; border-radius: 6px; line-height: 1.7; font-size: 0.86rem; }
    .modal { position: fixed; inset: 0; background: rgba(0,0,0,0.82); display: flex; align-items: center; justify-content: center; padding: 12px; z-index: 60; }
    .modal-box { background: #10203a; border: 1px solid #2b4775; border-radius: 16px; padding: 14px; width: 100%; max-width: 480px; max-height: 90vh; overflow-y: auto; }
    @media print {
      body * { visibility: hidden; }
      #printArea, #printArea * { visibility: visible; }
      #printArea { position: fixed; inset: 0; background: #fff; padding: 15mm; }
      .no-print { display: none !important; }
    }
  </style>
</head>
<body>
  <div class="app">

    <!-- شاشة الدخول والاختيار بين المواطن والموظف -->
    <div id="authScreen" class="card" style="text-align:center; margin-top:20px;">
      <h1>دفتري الرقمي</h1>
      <p class="muted">محفظة رقمية وبطاقة ذكية بـ 15 خدمة — فضاء مستقل للمواطن وفضاء للموظف</p>

      <div class="row" style="margin:12px 0;">
        <button id="roleUser" class="btn-blue" style="flex:1;">👤 فضاء المواطن (1234)</button>
        <button id="roleStaff" class="btn-gray" style="flex:1;">🏛️ فضاء الموظف (0000)</button>
      </div>

      <input id="pinInput" type="password" value="1234" style="text-align:center; letter-spacing:4px;" />
      <button id="loginBtn" class="btn-blue" style="width:100%; padding:11px;">دخول</button>
    </div>

    <!-- واجهة المواطن / الشعب -->
    <div id="userScreen" class="hidden">
      <div class="card">
        <div class="row" style="justify-content:space-between; align-items:center;">
          <div>
            <h2 id="uTitle">👤 فضاء المواطن</h2>
            <div class="muted">دهانة أسامة • هوية رقمية موحدة • وضع بدون إنترنت نشط</div>
          </div>
          <div class="row">
            <button id="langBtn" class="btn-gray">AR / FR</button>
            <button class="btn-red logout-btn">خروج</button>
          </div>
        </div>
        <div class="row" style="margin-top:10px; justify-content:space-between; align-items:center;">
          <span id="cardStatus" class="badge">البطاقة نشطة (G-74129)</span>
          <button id="freezeBtn" class="btn-red">🚨 إيقاف فوري (فقدان)</button>
        </div>
      </div>

      <div class="tabs">
        <button class="tab active" data-t="tDocs">📁 الوثائق</button>
        <button class="tab" data-t="tShare">🔐 المشاركة</button>
        <button class="tab" data-t="tGov">🌐 روابط الدولة</button>
        <button class="tab" data-t="tLog">📜 السجل والهوية</button>
      </div>

      <!-- تبويب الوثائق (تصنيف + صلاحية + قفل خصوصية + طباعة) -->
      <div id="tDocs" class="card u-pane">
        <div class="row" style="justify-content:space-between; align-items:center; margin-bottom:8px;">
          <h3 style="margin:0;">محفظة الوثائق</h3>
          <button id="openAdd" class="btn-blue">+ إضافة</button>
        </div>
        <div class="row" style="margin-bottom:10px;">
          <button class="btn-blue cat-b" data-c="all">الكل</button>
          <button class="btn-gray cat-b" data-c="شخصية">شخصية</button>
          <button class="btn-gray cat-b" data-c="جامعية">جامعية</button>
          <button class="btn-gray cat-b" data-c="إدارية">إدارية</button>
        </div>
        <div id="docsBox"></div>
      </div>

      <!-- تبويب المشاركة المحدودة والملخص السريع -->
      <div id="tShare" class="card u-pane hidden">
        <h3>مشاركة آمنة ومؤقتة وملخص سريع</h3>
        <p class="muted">شارك ملخصاً أو رمزاً صالحاً لمرة واحدة لمدة 5 دقائق (عرض فقط دون نسخ أو حفظ خارجي)</p>
        <select id="shareSelect"></select>
        <div class="row" style="margin-top:6px;">
          <button id="genTempBtn" class="btn-gold" style="flex:1;">⏳ إنشاء رمز مؤقت (لمرة واحدة)</button>
          <button id="copySummaryBtn" class="btn-blue">📋 تصدير ملخص</button>
        </div>
        <div id="tempOut" class="doc" style="margin-top:10px; font-family:monospace; color:#fde047;">
          لم يتم إنشاء رمز مشاركة بعد.
        </div>
      </div>

      <!-- تبويب روابط الدولة الرسمية لاستخراج الوثائق -->
      <div id="tGov" class="card u-pane hidden">
        <h3>🌐 روابط رسمية لاستخراج وثائق الدولة</h3>
        <p class="muted">استخرج وثيقتك من الموقع الرسمي للدولة ثم أضفها في محفظتك</p>

        <div class="link-row">
          <div>
            <strong>الحالة المدنية (S12 / الإقامة)</strong>
            <div class="muted">وزارة الداخلية</div>
          </div>
          <a href="https://etatcivil.interieur.gov.dz" target="_blank" class="btn-blue">فتح الموقع</a>
        </div>

        <div class="link-row">
          <div>
            <strong>صحيفة السوابق العدلية (رقم 3)</strong>
            <div class="muted">وزارة العدل</div>
          </div>
          <a href="https://portail.mjustice.dz" target="_blank" class="btn-blue">فتح الموقع</a>
        </div>

        <div class="link-row">
          <div>
            <strong>فضاء الهناء (الضمان الاجتماعي / الشفاء)</strong>
            <div class="muted">CNAS</div>
          </div>
          <a href="https://elhanaa.cnas.dz" target="_blank" class="btn-blue">فتح الموقع</a>
        </div>

        <div class="link-row">
          <div>
            <strong>الخدمات الجامعية (PROGRES)</strong>
            <div class="muted">التعليم العالي</div>
          </div>
          <a href="https://progres.mesrs.dz" target="_blank" class="btn-blue">فتح الموقع</a>
        </div>
      </div>

      <!-- تبويب الهوية الموحدة وسجل التحقق والمعاملات -->
      <div id="tLog" class="card u-pane hidden">
        <h3>🪪 الهوية الرقمية الموحدة</h3>
        <p class="muted" style="margin-bottom:10px;">
          الاسم: دهانة أسامة • الميلاد: 24 جوان 2004 (باتنة) • الصفة: طالب ماستر 2 قانون أعمال ومسيّر مؤسسة • المعرّف: DZ-BATNA-74129
        </p>
        <h3>📜 سجل التحقق والمعاملات</h3>
        <div id="logsBox" class="muted"></div>
      </div>
    </div>

    <!-- واجهة الموظف / الإدارة -->
    <div id="staffScreen" class="hidden">
      <div class="card">
        <div class="row" style="justify-content:space-between; align-items:center;">
          <div>
            <h2>🏛️ فضاء الموظف</h2>
            <div class="muted">فحص الوثائق والبطاقات وطباعة نسخة للأرشيف</div>
          </div>
          <button class="btn-red logout-btn">خروج</button>
        </div>
      </div>

      <div class="card">
        <h3>التحقق الفوري</h3>
        <input id="staffCode" type="text" placeholder="اكتب: DOC-BAC-2021 أو DOC-204 أو G-74129" />
        <div class="row">
          <button id="verifyBtn" class="btn-gold" style="flex:1;">🔍 تحقق</button>
          <button id="nfcBtn" class="btn-blue">📶 تمرير بطاقة NFC</button>
        </div>
        <div class="row" style="margin-top:8px;">
          <button class="btn-gray q-btn" data-q="DOC-BAC-2021">البكالوريا</button>
          <button class="btn-gray q-btn" data-q="DOC-204">الماستر</button>
          <button class="btn-gray q-btn" data-q="DOC-101">الميلاد</button>
        </div>
        <div id="staffResult" style="margin-top:12px; font-size:0.86rem; line-height:1.6;"></div>
      </div>
    </div>

  </div>

  <!-- نافذة إضافة وثيقة -->
  <div id="addModal" class="modal hidden">
    <div class="modal-box">
      <h3>إضافة وثيقة للمحفظة</h3>
      <input id="inTitle" type="text" placeholder="عنوان الوثيقة" />
      <input id="inIssuer" type="text" placeholder="الجهة المصدرة" />
      <select id="inCat">
        <option value="شخصية">شخصية</option>
        

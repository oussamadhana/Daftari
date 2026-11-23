<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>دفتري الرقمي | Daftari Digital</title>
  <script src="https://cdn.jsdelivr.net/npm/qrcodejs@1.0.0/qrcode.min.js"></script>
  <style>
    :root {
      --bg: #08101e;
      --surface: #111c30;
      --surface-2: #0b1526;
      --border: #223554;
      --text: #f8fafc;
      --muted: #94a3b8;
      --primary: #2563eb;
      --gold: #d4af37;
      --success: #22c55e;
      --danger: #ef4444;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: system-ui, -apple-system, "Segoe UI", Tahoma, sans-serif;
    }

    body {
      background: radial-gradient(circle at top, #132544 0%, var(--bg) 65%);
      color: var(--text);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      padding: 14px;
    }

    .app-shell {
      width: 100%;
      max-width: 480px;
      display: flex;
      flex-direction: column;
      gap: 14px;
    }

    .hidden { display: none !important; }

    /* شاشة اختيار الواجهة والدخول */
    .portal-screen {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 22px;
      padding: 24px 18px;
      margin-top: 24px;
      box-shadow: 0 20px 45px rgba(0,0,0,0.45);
      text-align: center;
    }

    .brand-badge {
      width: 64px;
      height: 64px;
      border-radius: 18px;
      background: linear-gradient(135deg, #1d4ed8, #0f294a);
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 0 auto 12px;
      font-size: 28px;
      border: 1px solid rgba(255,255,255,0.2);
    }

    .role-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
      margin: 18px 0;
    }

    .role-card {
      background: var(--surface-2);
      border: 2px solid var(--border);
      border-radius: 16px;
      padding: 16px 10px;
      cursor: pointer;
      transition: 0.2s;
      text-align: center;
    }

    .role-card.active {
      border-color: #3b82f6;
      background: #152847;
    }

    .role-card.staff-role.active {
      border-color: var(--gold);
      background: #23221a;
    }

    .role-icon { font-size: 26px; margin-bottom: 6px; }
    .role-title { font-weight: bold; font-size: 0.92rem; }
    .role-sub { font-size: 0.74rem; color: var(--muted); margin-top: 4px; }

    .pin-input {
      width: 100%;
      padding: 12px;
      border-radius: 12px;
      border: 1px solid var(--border);
      background: var(--surface-2);
      color: #fff;
      text-align: center;
      font-size: 1.2rem;
      letter-spacing: 6px;
      margin-bottom: 12px;
    }

    /* الرأس العام */
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: var(--surface);
      border: 1px solid var(--border);
      padding: 12px 15px;
      border-radius: 16px;
    }

    .header h2 { font-size: 1.08rem; }
    .header span { font-size: 0.74rem; color: var(--muted); }

    .switch-btn {
      background: rgba(239, 68, 68, 0.14);
      color: #fca5a5;
      border: 1px solid rgba(239, 68, 68, 0.35);
      padding: 6px 10px;
      border-radius: 10px;
      font-size: 0.76rem;
      cursor: pointer;
    }

    /* التبويبات */
    .tabs {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 8px;
      background: var(--surface);
      padding: 6px;
      border-radius: 14px;
      border: 1px solid var(--border);
    }

    .tab-btn {
      background: transparent;
      border: none;
      color: var(--muted);
      padding: 9px 6px;
      border-radius: 10px;
      font-size: 0.84rem;
      font-weight: 600;
      cursor: pointer;
    }

    .tab-btn.active {
      background: #1d4ed8;
      color: #fff;
    }

    /* البطاقة الذكية */
    .tier-switcher {
      display: flex;
      gap: 6px;
      margin-bottom: 10px;
    }

    .tier-btn {
      flex: 1;
      padding: 7px;
      border-radius: 10px;
      border: 1px solid var(--border);
      background: var(--surface);
      color: var(--muted);
      font-size: 0.76rem;
      cursor: pointer;
    }

    .tier-btn.active {
      color: #fff;
      border-color: #60a5fa;
      background: #172a4a;
      font-weight: bold;
    }

    .smart-card {
      border-radius: 20px;
      padding: 20px;
      min-height: 170px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      border: 1px solid rgba(255,255,255,0.2);
      box-shadow: 0 14px 32px rgba(0,0,0,0.45);
    }

    .tier-silver { background: linear-gradient(135deg, #0f294a 0%, #1e3a5f 60%, #94a3b8 100%); }
    .tier-gold { background: linear-gradient(135deg, #0c2240 0%, #163763 58%, #b8891e 100%); }
    .tier-platinum { background: linear-gradient(135deg, #071224 0%, #132542 55%, #cbd5e1 100%); }

    .card-row {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .chip {
      width: 38px;
      height: 28px;
      border-radius: 6px;
      background: linear-gradient(135deg, #e2e8f0, #94a3b8);
    }

    .card-serial {
      font-family: monospace;
      font-size: 0.98rem;
      font-weight: bold;
      background: rgba(0,0,0,0.35);
      padding: 4px 10px;
      border-radius: 8px;
    }

    /* اللوحات والأزرار */
    .panel {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 15px;
    }

    .panel-top {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 12px;
    }

    .btn-primary {
      background: #2563eb;
      color: #fff;
      border: none;
      padding: 9px 13px;
      border-radius: 10px;
      font-size: 0.82rem;
      font-weight: 600;
      cursor: pointer;
    }

    .btn-gold {
      background: var(--gold);
      color: #08101e;
      border: none;
      padding: 8px 11px;
      border-radius: 9px;
      font-size: 0.78rem;
      font-weight: bold;
      cursor: pointer;
    }

    .btn-green {
      background: #16a34a;
      color: #fff;
      border: none;
      padding: 8px 11px;
      border-radius: 9px;
      font-size: 0.78rem;
      font-weight: bold;
      cursor: pointer;
    }

    .btn-outline {
      background: transparent;
      color: #cbd5e1;
      border: 1px solid var(--border);
      padding: 8px 10px;
      border-radius: 9px;
      font-size: 0.78rem;
      cursor: pointer;
    }

    .doc-card {
      background: var(--surface-2);
      border: 1px solid var(--border);
      border-radius: 13px;
      padding: 13px;
      margin-bottom: 10px;
    }

    .doc-card.featured {
      border-color: rgba(212, 175, 55, 0.55);
      background: linear-gradient(180deg, #101d35 0%, #0b1526 100%);
    }

    .doc-header {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      gap: 8px;
    }

    .doc-title { font-weight: 700; font-size: 0.94rem; }
    .doc-sub { font-size: 0.76rem; color: var(--muted); margin-top: 3px; }

    .status-pill {
      background: rgba(34, 197, 94, 0.14);
      color: #86efac;
      border: 1px solid rgba(34, 197, 94, 0.35);
      padding: 3px 8px;
      border-radius: 999px;
      font-size: 0.7rem;
      white-space: nowrap;
    }

    .doc-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 7px;
      margin-top: 10px;
    }

    .qr-wrapper {
      background: #fff;
      padding: 12px;
      border-radius: 14px;
      width: fit-content;
      margin: 12px auto;
    }

    .verify-input {
      width: 100%;
      padding: 11px;
      border-radius: 10px;
      border: 1px solid var(--border);
      background: var(--surface-2);
      color: #fff;
      margin: 8px 0;
      font-size: 0.86rem;
    }

    .staff-banner {
      background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%);
      border: 1px solid rgba(212, 175, 55, 0.45);
      border-radius: 16px;
      padding: 14px;
    }

    .result-box {
      border-radius: 14px;
      padding: 14px;
      margin-top: 12px;
      font-size: 0.85rem;
      line-height: 1.7;
    }

    .result-ok {
      background: rgba(34, 197, 94, 0.12);
      border: 1px solid rgba(34, 197, 94, 0.45);
      color: #dcfce7;
    }

    .result-err {
      background: rgba(239, 68, 68, 0.12);
      border: 1px solid rgba(239, 68, 68, 0.45);
      color: #fecaca;
    }

    /* نافذة معاينة وطباعة الوثيقة الرسمية */
    .modal-backdrop {
      position: fixed;
      inset: 0;
      background: rgba(0,0,0,0.8);
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 12px;
      z-index: 100;
      overflow-y: auto;
    }

    .modal-box {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 16px;
      width: 100%;
      max-width: 520px;
      max-height: 92vh;
      overflow-y: auto;
    }

    /* تصميم الوثيقة الورقية المطابقة للأصل عند الطباعة */
    .official-paper {
      background: #fdfbf4;
      color: #111827;
      border: 6px double #7f1d1d;
      outline: 2px solid #14532d;
      outline-offset: -11px;
      padding: 20px 18px;
      border-radius: 4px;
      position: relative;
      text-align: right;
      line-height: 1.75;
      font-size: 0.86rem;
      box-shadow: 0 8px 24px rgba(0,0,0,0.35);
    }

    .paper-header {
      text-align: center;
      border-bottom: 1px solid #cbd5e1;
      padding-bottom: 8px;
      margin-bottom: 10px;
    }

    .paper-header h4 { font-size: 0.92rem; color: #111827; }
    .paper-title {
      text-align: center;
      color: #991b1b;
      font-size: 1.35rem;
      font-weight: 900;
      margin: 8px 0;
      letter-spacing: 0.5px;
    }

    .paper-meta {
      display: flex;
      justify-content: space-between;
      font-size: 0.78rem;
      font-weight: bold;
      color: #374151;
      margin-bottom: 8px;
    }

    .paper-footer {
      display: flex;
      justify-content: space-between;
      align-items: flex-end;
      margin-top: 14px;
      padding-top: 10px;
      border-top: 1px dashed #9ca3af;
      font-size: 0.76rem;
    }

    .digital-stamp {
      border: 2px solid #15803d;
      color: #15803d;
      padding: 6px 10px;
      border-radius: 8px;
      font-weight: bold;
      font-size: 0.72rem;
      background: rgba(22, 163, 74, 0.06);
    }

    /* إعدادات الطباعة الحقيقية (تطبع الورقة فقط بدون خلفية التطبيق) */
    @media print {
      body * { visibility: hidden; }
      #printableArea, #printableArea * { visibility: visible; }
      #printableArea {
        position: fixed;
        inset: 0;
        width: 100%;
        background: #fff;
        padding: 15mm;
      }
      .no-print { display: none !important; }
    }
  </style>
</head>
<body>
  <div class="app-shell">

    <!-- 1. شاشة اختيار الواجهة (مستخدم أو موظف) -->
    <div id="portalScreen" class="portal-screen">
      <div class="brand-badge">🛡️</div>
      <h1 style="font-size:1.4rem;">دفتري الرقمي • Daftari Digital</h1>
      <p style="color:var(--muted); font-size:0.84rem; margin-top:4px;">اختر نوع الواجهة للدخول إلى المنظومة</p>

      <div class="role-grid">
        <div id="selectUserRole" class="role-card active">
          <div class="role-icon">👤</div>
          <div class="role-title">واجهة المستخدم</div>
          <div class="role-sub">المواطن / الطالب (PIN: 1234)</div>
        </div>
        <div id="selectStaffRole" class="role-card staff-role">
          <div class="role-icon">🏛️</div>
          <div class="role-title">واجهة الموظف</div>
          <div class="role-sub">الإدارة / الجامعة (PIN: 0000)</div>
        </div>
      </div>

      <input id="pinInput" class="pin-input" type="password" maxlength="4" value="1234" />
      <button id="loginBtn" class="btn-primary" style="width:100%; padding:13px; font-size:0.95rem;">
        دخول إلى واجهة المستخدم
      </button>
    </div>

    <!-- 2. واجهة المستخدم (المواطن / الطالب) -->
    <div id="userApp" class="hidden" style="display:flex; flex-direction:column; gap:14px;">
      <header class="header">
        <div>
          <h2>👤 فضاء المواطن • دفتري الرقمي</h2>
          <span>المستخدم: دهانة أسامة • محفظة مؤمنة</span>
        </div>
        <button class="switch-btn logout-trigger">تبديل الواجهة 🔄</button>
      </header>

      <nav class="tabs">
        <button class="tab-btn active" data-utab="uWallet">📁 وثائقي والطباعة</button>
        <button class="tab-btn" data-utab="uCard">💳 البطاقة و QR</button>
      </nav>

      <!-- تبويب وثائق المستخدم -->
      <section id="uWallet" class="u-tab-content">
        <div class="panel">
          <div class="panel-top">
            <div>
              <h3 style="font-size:0.96rem;">محفظة الوثائق الرسمية (<span id="docCount">0</span>)</h3>
              <p style="font-size:0.74rem; color:var(--muted);">اضغط "نسخة رسمية / طباعة" لإخراج الوثيقة ورقياً عند الطلب</p>
            </div>
            <button id="openAddModalBtn" class="btn-primary">+ إضافة</button>
          </div>
          <div id="docsContainer"></div>
        </div>
      </section>

      <!-- تبويب البطاقة الذكية و QR -->
      <section id="uCard" class="u-tab-content hidden">
        <div class="tier-switcher">
          <button class="tier-btn" data-tier="silver">الفضية</button>
          <button class="tier-btn active" data-tier="gold">الذهبية</button>
          <button class="tier-btn" data-tier="platinum">البلاتينية</button>
        </div>

        <div id="smartCardBox" class="smart-card tier-gold">
          <div class="card-row">
            <div>
              <strong>دفتري الرقمي</strong>
              <div style="font-size:0.74rem; opacity:0.85;">Daftari Digital</div>
            </div>
            <span id="cardSerial" class="card-serial">G-74129</span>
          </div>
          <div class="card-row" style="margin:12px 0;">
            <div class="chip"></div>
            <div style="font-size:0.78rem;">NFC • SMART ID 📶</div>
          </div>
          <div>
            <strong style="display:block; font-size:1.05rem;">دهانة أسامة</strong>
            <small id="cardEditionLabel" style="font-size:0.76rem; opacity:0.9;">GOLD EDITION • الباقة الاحترافية</small>
          </div>
        </div>

        <div class="panel" style="margin-top:12px; text-align:center;">
          <h3 style="font-size:0.94rem;">رمز التحقق الديناميكي المؤقت</h3>
          <p style="font-size:0.76rem; color:var(--muted); margin-top:4px;">أظهر هذا الرمز للموظف لمسحه والتحقق من وثائقك</p>
          <div id="qrBox" class="qr-wrapper"></div>
          <div id="qrTimer" style="font-size:0.8rem; color:#fde047;">صالح لمدة: 30 ثانية</div>
          <div id="activeQrText" style="font-family:monospace; font-size:0.72rem; color:#93c5fd; margin-top:6px;"></div>
        </div>
      </section>
    </div>

    <!-- 3. واجهة الموظف (الإدارة / المؤسسة المستقبِلة) -->
    <div id="staffApp" class="hidden" style="display:flex; flex-direction:column; gap:14px;">
      <header class="header" style="border-color: rgba(212, 175, 55, 0.45);">
        <div>
          <h2>🏛️ فضاء الموظف • بوابة التحقق</h2>
          <span>مصلحة استقبال الملفات والتحقق الإلكتروني</span>
        </div>
        <button class="switch-btn logout-trigger">تبديل الواجهة 🔄</button>
      </header>

      <div class="staff-banner">
        <h3 style="font-size:0.96rem; color:#fde047;">فحص وثيقة أو بطاقة مواطن</h3>
        <p style="font-size:0.78rem; color:#cbd5e1; margin-top:4px;">
          أدخل معرّف الوثيقة أو رقم البطاقة الذكية (أو اختر فحصاً سريعاً) للتحقق من المطابقة للأصل أو طباعة نسخة للأرشيف:
        </p>

        <input id="staffSearchInput" class="verify-input" type="text" placeholder="مثال: DOC-BAC-2021 أو 35003472 أو G-74129" />

        <div style="display:flex; flex-wrap:wrap; gap:6px; margin-top:6px;">
          <button id="staffVerifyBtn" class="btn-gold" style="flex:1;">🔍 تحقق الآن</button>
          <button class="btn-outline quick-check" data-code="DOC-BAC-2021">فحص البكالوريا</button>
          <button class="btn-outline quick-check" data-code="DOC-204">فحص شهادة جامعية</button>
          <button class="btn-outline quick-check" data-code="G-74129">فحص البطاقة</button>
        </div>
      </div>

      <div id="staffResultContainer" class="panel">
        <p style="font-size:0.84rem; color:var(--muted); text-align:center;">
          في انتظار مسح رمز QR أو إدخال معرّف الوثيقة للتحقق...
        </p>
      </div>
    </div>
  </div>

  <!-- نافذة معاينة وطباعة الوثيقة الرسمية -->
  <div id="docModal" class="modal-backdrop hidden">
    <div class="modal-box">
      <div class="no-print" style="display:flex; justify-content:space-between; align-items:center; margin-bottom:10px;">
        <strong style="font-size:0.92rem;">معاينة النسخة الرسمية القابلة للطباعة</strong>
        <button id="closeDocModalBtn" class="btn-outline">إغلاق ✕</button>
      </div>

      <div id="printableArea"></div>

      <div class="no-print" style="display:flex; gap:8px; margin-top:12px;">
        <button onclick="window.print()" class="btn-green" style="flex:1; padding:11px;">🖨️ طباعة الورقة / حفظ PDF</button>
        <button id="closeDocModalBtn2" class="btn-outline">رجوع</button>
      </div>
    </div>
  </div>

  <!-- نافذة إضافة وثيقة جديدة -->
  <div id="addModal" class="modal-backdrop hidden">
    <div class="modal-box">
      <h3 style="margin-bottom:10px; font-size:1rem;">إضافة وثيقة جديدة للمحفظة</h3>
      <input id="newTitle" class="verify-input" type="text" placeholder="عنوان الوثيقة (مثلاً: شهادة الإقامة)" />
      <input id="newIssuer" class="verify-input" type="text" placeholder="الجهة المصدرة (مثلاً: بلدية باتنة)" />
      <input id="newDetails" class="verify-input" type="text" placeholder="بيانات إضافية (مثلاً: رقم الوثيقة أو الملاحظة)" />
      <div style="display:flex; gap:8px; margin-top:8px;">
        <button id="saveDocBtn" class="btn-primary" style="flex:1;">حفظ في المحفظة</button>
        <button id="closeAddBtn" class="btn-outline">إلغاء</button>
      </div>
    </div>
  </div>

  <script>
    const tiers = {
      silver: { serial: "S-35684", label: "ESSENTIAL EDITION • الباقة الأساسية", cls: "smart-card tier-silver" },
      gold: { serial: "G-74129", label: "GOLD EDITION • الباقة الاحترافية", cls: "smart-card tier-gold" },
      platinum: { serial: "E-99999", label: "ELITE ENTERPRISE • باقة النخبة", cls: "smart-card tier-platinum" }
    };

    const initialDocs = [
      {
        id: "DOC-BAC-2021",
        isBac: true,
        title: "شهادة البكالوريا للتعليم الثانوي - دورة 2021",
        issuer: "وزارة التربية الوطنية - الديوان الوطني للامتحانات والمسابقات",
        date: "2021-07-17",
        examNumber: "35003472",
        serialNumber: "515368152330019265",
        branch: "لغات أجنبية",
        grade: "مقبول",
        holder: "دهانة أسامة",
        birthInfo: "24 جوان 2004 بـ باتنة - باتنة",
        hash: "SHA256:BAC2021-35003472-515368152330019265"
      },
      {
        id: "DOC-204",
        isBac: false,
        title: "شهادة التسجيل الجامعي - ماستر 2 قانون أعمال",
        issuer: "وزارة التعليم العالي والبحث العلمي - جامعة باتنة 1",
        date: "2026-10-15",
        holder: "دهانة أسامة",
        details: "السنة الجامعية 2026/2027 - كلية الحقوق والعلوم السياسية",
        hash: "SHA256:UNIV-BATNA1-M2-DROIT-2026"
      },
      {
        id: "DOC-101",
        isBac: false,
        title: "مستخرج شهادة الميلاد الرقمية (S12)",
        issuer: "وزارة الداخلية والجماعات المحلية - بلدية باتنة",
        date: "2026-11-01",
        holder: "دهانة أسامة",
        details: "تاريخ ومكان الميلاد: 24 جوان 2004 بـ باتنة",
        hash: "SHA256:CIV-BATNA-S12-20040624"
      }
    ];

    let docs = JSON.parse(localStorage.getItem("daftari_v3_docs")) || initialDocs;
    let selectedRole = "user";
    let currentTier = "gold";
    let activeQrDoc = docs[0];
    let secondsLeft = 30;

    // اختيار الواجهة من الشاشة الرئيسية
    const selectUserRole = document.getElementById("selectUserRole");
    const selectStaffRole = document.getElementById("selectStaffRole");
    const pinInput = document.getElementById("pinInput");
    const loginBtn = document.getElementById("loginBtn");

    selectUserRole.addEventListener("click", () => {
      selectedRole = "user";
      selectUserRole.classList.add("active");
      selectStaffRole.classList.remove("active");
      pinInput.value = "1234";
      loginBtn.textContent = "دخول إلى واجهة المستخدم";
      loginBtn.className = "btn-primary";
    });

    selectStaffRole.addEventListener("click", () => {
      selectedRole = "staff";
      selectStaffRole.classList.add("active");
      selectUserRole.classList.remove("active");
      pinInput.value = "0000";
      loginBtn.textContent = "دخول إلى واجهة الموظف";
      loginBtn.className = "btn-gold";
    });

    loginBtn.addEventListener("click", () => {
      const pin = pinInput.value.trim();
      if (selectedRole === "user") {
        if (pin !== "1234") return alert("رمز واجهة المستخدم التجريبي هو 1234");
        document.getElementById("portalScreen").classList.add("hidden");
        document.getElementById("staffApp").classList.add("hidden");
        document.getElementById("userApp").classList.remove("hidden");
        renderUserDocs();
        updateQR(activeQrDoc);
      } else {
        if (pin !== "0000") return alert("رمز واجهة الموظف التجريبي هو 0000");
        document.getElementById("portalScreen").classList.add("hidden");
        document.getElementById("userApp").classList.add("hidden");
        document.getElementById("staffApp").classList.remove("hidden");
      }
    });

    document.querySelectorAll(".logout-trigger").forEach(btn => {
      btn.addEventListener("click", () => {
        document.getElementById("userApp").classList.add("hidden");
        document.getElementById("staffApp").classList.add("hidden");
        document.getElementById("portalScreen").classList.remove("hidden");
      });
    });

    // تبويبات المستخدم
    document.querySelectorAll(".tab-btn").forEach(btn => {
      btn.addEventListener("click", () => {
        document.querySelectorAll(".tab-btn").forEach(b => b.classList.remove("active"));
        document.querySelectorAll(".u-tab-content").forEach(c => c.classList.add("hidden"));
        btn.classList.add("active");
        document.getElementById(btn.dataset.utab).classList.remove("hidden");
      });
    });

    // تبديل باقات البطاقة
    document.querySelectorAll(".tier-btn").forEach(btn => {
      btn.addEventListener("click", () => {
        document.querySelectorAll(".tier-btn").forEach(b => b.classList.remove("active"));
        btn.classList.add("active");
        currentTier = btn.dataset.tier;
        document.getElementById("smartCardBox").className = tiers[currentTier].cls;
        document.getElementById("cardSerial").textContent = tiers[currentTier].serial;
        document.getElementById("cardEditionLabel").textContent = tiers[currentTier].label;
        updateQR(activeQrDoc);
      });
    });

    // توليد QR
    function updateQR(doc) {
      activeQrDoc = doc || docs[0];
      const qrBox = document.getElementById("qrBox");
      qrBox.innerHTML = "";
      const token = Math.random().toString(36).substring(2, 7).toUpperCase();
      new QRCode(qrBox, {
        text: `DAFTARI|${tiers[currentTier].serial}|${activeQrDoc.id}|${token}`,
        width: 140,
        height: 140
      });
      document.getElementById("activeQrText").textContent = `الوثيقة النشطة: ${activeQrDoc.id} • رمز الجلسة: ${token}`;
      secondsLeft = 30;
    }

    setInterval(() => {
      if (document.getElementById("userApp").classList.contains("hidden")) return;
      secondsLeft--;
      if (secondsLeft <= 0) updateQR(activeQrDoc);
      document.getElementById("qrTimer").textContent = `صالح لمدة: ${secondsLeft} ثانية (يتجدد تلقائياً)`;
    }, 1000);

    // بناء القالب الرسمي المطابق للأصل للطباعة
    function openOfficialDocument(doc) {
      const area = document.getElementById("printableArea");
      if (doc.isBac) {
        area.innerHTML = `
          <div class="official-paper">
            <div class="paper-meta">
              <span>الرقم: ${doc.examNumber}</span>
              <span>الرقم التسلسلي: ${doc.serialNumber}</span>
            </div>
            <div class="paper-header">
              <h4>الجمهورية الجزائرية الديمقراطية الشعبية</h4>
              <div style="font-weight:bold; font-size:0.84rem;">وزارة التربية الوطنية • الديوان الوطني للامتحانات والمسابقات</div>
            </div>
            <div class="paper-title">شهادة البكالوريا للتعليم الثانوي</div>
            <p style="margin-top:8px;">
              بناءً على محضر لجنة المداولات لدورة <strong>2021</strong>،<br>
              تمنح شهادة البكالوريا للتعليم الثانوي<br>
              للسيد: <strong>${doc.holder}</strong><br>
              المولود في: <strong>${doc.birthInfo}</strong><br>
              شعبة: <strong>${doc.branch}</strong> • بتقدير: <strong>${doc.grade}</strong>
            </p>
            <p style="margin-top:8px; font-size:0.8rem;">
              حُرّر بالجزائر في: <strong>17 جويلية 2021</strong> — مُمضى: عن وزير التربية الوطنية، مدير الديوان الوطني للامتحانات والمسابقات.
            </p>
            <div class="paper-footer">
              <div class="digital-stamp">
                ✓ مستخرج رقمي موثق — دفتري الرقمي<br>
                المعرّف: ${doc.id}<br>
                مطابق للأصل وقابل للتحقق الفوري
              </div>
              <div id="paperQr"></div>
            </div>
          </div>
        `;
      } else {
        area.innerHTML = `
          <div class="official-paper" style="border-color:#1e3a8a;">
            <div class="paper-meta">
              <span>المعرّف: ${doc.id}</span>
              <span>التاريخ: ${doc.date}</span>
            </div>
            <div class="paper-header">
              <h4>الجمهورية الجزائرية الديمقراطية الشعبية</h4>
              <div style="font-weight:bold; font-size:0.84rem;">${doc.issuer}</div>
            </div>
            <div class="paper-title" style="color:#1e3a8a; font-size:1.15rem;">${doc.title}</div>
            <p style="margin-top:10px;">
              تشهد الجهة المصدرة المذكورة أعلاه بصحة بيانات هذه الوثيقة الخاصة بـ:<br>
              السيد: <strong>${doc.holder}</strong><br>
              التفاصيل: <strong>${doc.details || "وثيقة رسمية سارية المفعول"}</strong>
            </p>
            <div class="paper-footer">
              <div class="digital-stamp">
                ✓ نسخة رقمية موثقة — دفتري الرقمي<br>
                البصمة: ${doc.hash.substring(0, 22)}...
              </div>
              <div id="paperQr"></div>
            </div>
          </div>
        `;
      }

      document.getElementById("docModal").classList.remove("hidden");
      new QRCode(document.getElementById("paperQr"), {
        text: `VERIFY|${doc.id}|${doc.holder}`,
        width: 64,
        height: 64
      });
    }

    document.getElementById("closeDocModalBtn").addEventListener("click", () => {
      document.getElementById("docModal").classList.add("hidden");
    });
    document.getElementById("closeDocModalBtn2").addEventListener("click", () => {
      document.getElementById("docModal").classList.add("hidden");
    });

    // عرض وثائق المستخدم
    function renderUserDocs() {
      const container = document.getElementById("docsContainer");
      container.innerHTML = "";
      document.getElementById("docCount").textContent = docs.length;

      docs.forEach(doc => {
        const card = document.createElement("div");
        card.className = doc.isBac ? "doc-card featured" : "doc-card";
        card.innerHTML = `
          <div class="doc-header">
            <div>
              <div class="doc-title">${doc.title}</div>
              <div class="doc-sub">${doc.issuer} • (${doc.id})</div>
            </div>
            <span class="status-pill">موثقة ✓</span>
          </div>
          <div class="doc-actions">
            <button class="btn-green print-btn">🖨️ نسخة رسمية / طباعة</button>
            <button class="btn-gold qr-btn">رمز QR</button>
          </div>
        `;
        card.querySelector(".print-btn").addEventListener("click", () => openOfficialDocument(doc));
        card.querySelector(".qr-btn").addEventListener("click", () => {
          updateQR(doc);
          document.querySelector('[data-utab="uCard"]').click();
        });
        container.appendChild(card);
      });
    }

    // إضافة وثيقة جديدة
    const addModal = document.getElementById("addModal");
    document.getElementById("openAddModalBtn").addEventListener("click", () => addModal.classList.remove("hidden"));
    document.getElementById("closeAddBtn").addEventListener("click", () => addModal.classList.add("hidden"));
    document.getElementById("saveDocBtn").addEventListener("click", () => {
      const title = document.getElementById("newTitle").value.trim();
      if (!title) return;
      const newDoc = {
        id: "DOC-" + Math.floor(300 + Math.random() * 699),
        isBac: false,
        title,
        issuer: document.getElementById("newIssuer").value.trim() || "جهة رسمية معتمدة",
        date: new Date().toISOString().split("T")[0],
        holder: "دهانة أسامة",
        details: document.getElementById("newDetails").value.trim() || "وثيقة مضافة وموثقة رقمياً",
        hash: "SHA256:" + Math.random().toString(16).substring(2, 16).toUpperCase()
      };
      docs.unshift(newDoc);
      localStorage.setItem("daftari_v3_docs", JSON.stringify(docs));
      renderUserDocs();
      addModal.classList.add("hidden");
      document.getElementById("newTitle").value = "";
      document.getElementById("newIssuer").value = "";
      document.getElementById("newDetails").value = "";
    });

    // منطق التحقق في واجهة الموظف
    function runStaffCheck(raw) {
      const q = raw.trim().toUpperCase();
      const box = document.getElementById("staffResultContainer");
      const matchedDoc = docs.find(d =>
        d.id.toUpperCase() === q ||
        (d.examNumber && d.examNumber === q) ||
        q.includes(d.id.toUpperCase())
      );
      const matchedCard = Object.values(tiers).find(t => t.serial === q || q.includes(t.serial));

      if (matchedDoc) {
        box.innerHTML = `
          <div class="result-box result-ok">
            <div style="font-size:1rem; font-weight:bold; margin-bottom:6px;">✅ تم التحقق: الوثيقة أصلية ومطابقة للسجل</div>
            <div>• <strong>صاحب الوثيقة:</strong> ${matchedDoc.holder}</div>
            <div>• <strong>نوع الوثيقة:</strong> ${matchedDoc.title}</div>
            <div>• <strong>الجهة المصدرة:</strong> ${matchedDoc.issuer}</div>
            <div>• <strong>معرّف التوثيق:</strong> ${matchedDoc.id}</div>
            <div style="margin-top:12px;">
              <button id="staffOpenPaperBtn" class="btn-green" style="width:100%; padding:10px;">
                📄 معاينة النسخة الرسمية أو طباعتها للأرشيف
              </button>
            </div>
          </div>
        `;
        document.getElementById("staffOpenPaperBtn").addEventListener("click", () => openOfficialDocument(matchedDoc));
      } else if (matchedCard) {
        box.innerHTML = `
          <div class="result-box result-ok">
            <div style="font-size:1rem; font-weight:bold; margin-bottom:6px;">✅ بطاقة ذكية صالحة ونشطة</div>
            <div>• <strong>حامل البطاقة:</strong> دهانة أسامة</div>
            <div>• <strong>الرقم التسلسلي:</strong> ${matchedCard.serial}</div>
            <div>• <strong>الفئة:</strong> ${matchedCard.label}</div>
            <div>• <strong>عدد الوثائق الموثقة المرتبطة:</strong> ${docs.length} وثائق</div>
          </div>
        `;
      } else {
        box.innerHTML = `
          <div class="result-box result-err">
            ❌ <strong>تنبيه للموظف:</strong> لم يتم العثور على وثيقة أو بطاقة مطابقة للمعرّف المدخل.
          </div>
        `;
      }
    }

    document.getElementById("staffVerifyBtn").addEventListener("click", () => {
      runStaffCheck(document.getElementById("staffSearchInput").value);
    });

    document.querySelectorAll(".quick-check").forEach(btn => {
      btn.addEventListener("click", () => {
        const code = btn.dataset.code;
        document.getElementById("staffSearchInput").value = code;
        runStaffCheck(code);
      });
    });
  </script>
</body>
</html>

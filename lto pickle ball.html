<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Speed Paddle — Book a Pickleball Court</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;600;700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --court:#124B52;
    --court-dark:#0B363B;
    --line:#F4F1E8;
    --ball:#C7E24D;
    --ball-dark:#9EB534;
    --coral:#E4572E;
    --amber:#E9A93B;
    --green:#2E9B57;
    --ink:#0F2124;
    --ink-soft:#4C6165;
    --paper:#F2F5F1;
    --paper-card:#FFFFFF;
    --border:#D9E1D6;
    --radius-sm:6px;
    --radius-md:10px;
  }
  *{box-sizing:border-box;}
  body{margin:0;background:var(--paper);color:var(--ink);font-family:'Inter',sans-serif;line-height:1.5;}
  h1,h2,h3,.display{font-family:'Space Grotesk',sans-serif;letter-spacing:-0.01em;}
  a{color:inherit;}
  button{font-family:inherit;cursor:pointer;}
  .app{max-width:1080px;margin:0 auto;padding:0 20px 80px;}
  /* ---------- header ---------- */
  .topbar{background:var(--court);color:var(--line);}
  .topbar-inner{max-width:1080px;margin:0 auto;padding:16px 20px;display:flex;align-items:center;justify-content:space-between;gap:12px;}
  .brand{display:flex;align-items:center;gap:10px;font-family:'Space Grotesk',sans-serif;font-weight:700;font-size:19px;}
  .brand svg{flex:none;}
  .topbar nav{display:flex;gap:18px;align-items:center;font-size:14px;font-weight:500;}
  .topbar nav a{opacity:.85;text-decoration:none;}
  .topbar nav a:hover{opacity:1;}
  .btn-share{background:var(--ball);color:var(--court-dark);border:none;padding:9px 16px;border-radius:999px;font-weight:600;font-size:13.5px;}
  .btn-share:hover{background:#d5ef67;}
  /* ---------- court-line divider ---------- */
  .court-rule{height:10px;background:
    repeating-linear-gradient(90deg, var(--ball) 0 26px, transparent 26px 42px);
    opacity:.9;}
  /* ---------- hero ---------- */
  .hero{position:relative;background:var(--court);color:var(--line);overflow:hidden;}
  .hero-inner{max-width:1080px;margin:0 auto;padding:64px 20px 56px;position:relative;z-index:2;}
  .hero .kicker{color:var(--ball);font-weight:600;font-size:14px;margin:0 0 10px;}
  .hero h1{font-size:44px;line-height:1.05;margin:0 0 16px;max-width:11ch;}
  .hero p{font-size:17px;color:#D7E6DE;max-width:46ch;margin:0 0 28px;}
  .btn-primary{background:var(--ball);color:var(--court-dark);border:none;padding:15px 30px;border-radius:8px;font-weight:700;font-size:16px;}
  .btn-primary:hover{background:#d5ef67;}
  .court-lines{position:absolute;inset:0;z-index:1;opacity:.16;}
  /* ---------- how it works ---------- */
  .how{padding:52px 0 8px;}
  .how h2{font-size:26px;margin:0 0 28px;}
  .how-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:0;border-top:1px solid var(--border);border-bottom:1px solid var(--border);}
  .how-step{padding:20px 18px;border-right:1px solid var(--border);}
  .how-step:last-child{border-right:none;}
  .how-step .num{font-family:'Space Grotesk';font-weight:700;color:var(--ball-dark);font-size:13px;margin-bottom:8px;}
  .how-step p{margin:0;font-size:14.5px;color:var(--ink-soft);}
  /* ---------- generic section card ---------- */
  .card{background:var(--paper-card);border:1px solid var(--border);border-radius:var(--radius-md);padding:28px;}
  .section{padding:44px 0;}
  /* ---------- progress ---------- */
  .progress{display:flex;align-items:center;margin-bottom:32px;}
  .progress .step{display:flex;align-items:center;gap:10px;flex:1;}
  .progress .dot{width:30px;height:30px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-weight:700;font-size:13px;background:var(--border);color:var(--ink-soft);flex:none;}
  .progress .step.active .dot{background:var(--court);color:var(--line);}
  .progress .step.done .dot{background:var(--green);color:#fff;}
  .progress .label{font-size:13.5px;font-weight:600;color:var(--ink-soft);}
  .progress .step.active .label{color:var(--ink);}
  .progress .bar{height:2px;background:var(--border);flex:1;margin:0 6px;}
  .progress .step.done + .bar, .progress .bar.done{background:var(--green);}
  /* ---------- forms ---------- */
  label{display:block;font-size:13.5px;font-weight:600;margin:0 0 6px;color:var(--ink);}
  .field{margin-bottom:18px;}
  input[type=text],input[type=email],input[type=tel],input[type=number],input[type=date],input[type=time],select,textarea{
    width:100%;padding:11px 12px;border:1px solid var(--border);border-radius:var(--radius-sm);font-size:15px;background:#fff;color:var(--ink);font-family:inherit;
  }
  input:focus,select:focus,textarea:focus{outline:2px solid var(--court);outline-offset:1px;}
  .grid-2{display:grid;grid-template-columns:1fr 1fr;gap:18px;}
  .hint{font-size:12.5px;color:var(--ink-soft);margin-top:5px;}
  .error{font-size:12.5px;color:var(--coral);margin-top:5px;display:none;}
  .field.invalid input, .field.invalid select{border-color:var(--coral);}
  .field.invalid .error{display:block;}
  .radio-cards{display:grid;grid-template-columns:1fr 1fr;gap:10px;}
  .radio-card{border:1px solid var(--border);border-radius:var(--radius-sm);padding:12px 14px;font-size:14px;font-weight:500;cursor:pointer;display:flex;align-items:center;gap:9px;}
  .radio-card.picked{border-color:var(--court);background:#EEF5F0;}
  .radio-card input{margin:0;}
  .actions{display:flex;justify-content:space-between;margin-top:28px;gap:12px;}
  .btn{padding:12px 22px;border-radius:8px;font-weight:600;font-size:14.5px;border:1px solid var(--border);background:#fff;color:var(--ink);}
  .btn.primary{background:var(--court);color:#fff;border-color:var(--court);}
  .btn.primary:hover{background:var(--court-dark);}
  .btn.ghost{background:transparent;}
  .btn:disabled{opacity:.45;cursor:not-allowed;}
  /* ---------- courts ---------- */
  .court-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:14px;margin:20px 0 26px;}
  .court-card{border:1.5px solid var(--border);border-radius:var(--radius-md);padding:16px 18px;}
  .court-card.available{border-color:var(--green);}
  .court-card.booked{opacity:.6;}
  .court-top{display:flex;justify-content:space-between;align-items:center;margin-bottom:6px;}
  .court-name{font-weight:700;font-family:'Space Grotesk';font-size:16px;}
  .status-pill{font-size:12px;font-weight:700;padding:3px 9px;border-radius:999px;display:inline-flex;align-items:center;gap:5px;}
  .status-pill.available{background:#E4F4E8;color:var(--green);}
  .status-pill.booked{background:#FBE7E1;color:var(--coral);}
  .status-pill.pending{background:#FCEFDA;color:var(--amber);}
  .status-pill::before{content:'';width:7px;height:7px;border-radius:50%;background:currentColor;}
  .court-card .btn{width:100%;margin-top:10px;}
  .booked-note{font-size:12.5px;color:var(--ink-soft);}
  table.slots{width:100%;border-collapse:collapse;font-size:12.5px;margin:18px 0 8px;}
  table.slots th,table.slots td{border:1px solid var(--border);padding:6px 5px;text-align:center;}
  table.slots th{background:var(--paper);font-weight:600;}
  table.slots td.av{background:#E4F4E8;color:var(--green);font-weight:600;}
  table.slots td.bk{background:#FBE7E1;color:var(--coral);font-weight:600;}
  .summary-list{list-style:none;padding:0;margin:0;}
  .summary-list li{display:flex;justify-content:space-between;padding:9px 0;border-bottom:1px solid var(--border);font-size:14.5px;}
  .summary-list li:last-child{border-bottom:none;font-weight:700;font-size:16px;padding-top:12px;}
  .summary-list li span:first-child{color:var(--ink-soft);}
  /* ---------- payment ---------- */
  .pay-methods{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin-bottom:20px;}
  .pay-method{border:1px solid var(--border);border-radius:var(--radius-sm);padding:14px 8px;text-align:center;font-size:13px;font-weight:600;cursor:pointer;}
  .pay-method.picked{border-color:var(--court);background:#EEF5F0;}
  .file-drop{border:1.5px dashed var(--border);border-radius:var(--radius-sm);padding:20px;text-align:center;font-size:13.5px;color:var(--ink-soft);cursor:pointer;}
  .file-drop.has-file{border-color:var(--green);color:var(--green);font-weight:600;}
  .confirm-row{display:flex;gap:10px;align-items:flex-start;margin:20px 0;font-size:14px;}
  .confirm-row input{margin-top:3px;}
  .alert{background:#FBE7E1;border:1px solid var(--coral);color:#8F2E17;padding:12px 14px;border-radius:var(--radius-sm);font-size:13.5px;margin-bottom:16px;display:none;}
  /* ---------- confirmation ---------- */
  .confirm-hero{text-align:center;padding:36px 20px;}
  .confirm-hero .check{width:60px;height:60px;border-radius:50%;background:var(--green);color:#fff;display:flex;align-items:center;justify-content:center;margin:0 auto 18px;font-size:30px;}
  .receipt{max-width:420px;margin:0 auto;text-align:left;}
  .receipt .card{background:var(--paper);}
  .share-row{display:flex;gap:10px;justify-content:center;margin-top:22px;flex-wrap:wrap;}
  /* ---------- admin ---------- */
  .admin-login{max-width:360px;margin:60px auto;}
  .admin-tabs{display:flex;gap:6px;border-bottom:1px solid var(--border);margin-bottom:24px;flex-wrap:wrap;}
  .admin-tab{padding:10px 16px;font-size:14px;font-weight:600;color:var(--ink-soft);border-bottom:2px solid transparent;background:none;border-top:none;border-left:none;border-right:none;}
  .admin-tab.active{color:var(--court);border-color:var(--court);}
  .stat-row{display:grid;grid-template-columns:repeat(4,1fr);gap:14px;margin-bottom:26px;}
  .stat{border:1px solid var(--border);border-radius:var(--radius-md);padding:16px 18px;background:#fff;}
  .stat .num{font-family:'Space Grotesk';font-size:26px;font-weight:700;}
  .stat .lbl{font-size:12.5px;color:var(--ink-soft);}
  table.res{width:100%;border-collapse:collapse;font-size:13.5px;background:#fff;}
  table.res th,table.res td{border-bottom:1px solid var(--border);padding:10px 8px;text-align:left;vertical-align:top;}
  table.res th{background:var(--paper);font-weight:700;font-size:12px;text-transform:uppercase;letter-spacing:.03em;color:var(--ink-soft);}
  .tag{font-size:11.5px;font-weight:700;padding:3px 8px;border-radius:999px;display:inline-block;}
  .tag.pending{background:#FCEFDA;color:var(--amber);}
  .tag.approved{background:#E4F4E8;color:var(--green);}
  .tag.rejected{background:#FBE7E1;color:var(--coral);}
  .tag.cancelled{background:#eee;color:#888;}
  .tag.paid{background:#E4F4E8;color:var(--green);}
  .tag.unpaid{background:#FBE7E1;color:var(--coral);}
  .row-actions{display:flex;gap:6px;flex-wrap:wrap;}
  .row-actions button{padding:5px 9px;font-size:12px;border-radius:6px;border:1px solid var(--border);background:#fff;}
  .row-actions button.primary{background:var(--court);color:#fff;border-color:var(--court);}
  .row-actions button.danger{background:#fff;color:var(--coral);border-color:var(--coral);}
  .filters{display:flex;gap:10px;margin-bottom:16px;flex-wrap:wrap;}
  .filters input,.filters select{width:auto;padding:8px 10px;font-size:13.5px;}
  .court-manage-row{display:flex;justify-content:space-between;align-items:center;padding:10px 0;border-bottom:1px solid var(--border);}
  .empty{padding:40px 20px;text-align:center;color:var(--ink-soft);font-size:14px;}
  .cal-court{margin-bottom:22px;}
  .cal-court h4{font-family:'Space Grotesk';margin:0 0 8px;}
  .cal-grid{display:flex;flex-wrap:wrap;gap:6px;}
  .cal-slot{font-size:11.5px;padding:6px 8px;border-radius:5px;border:1px solid var(--border);}
  .cal-slot.av{background:#E4F4E8;color:var(--green);border-color:#bfe6cb;}
  .cal-slot.bk{background:#FBE7E1;color:var(--coral);border-color:#f2c3b3;}
  footer{text-align:center;padding:30px 20px;font-size:12.5px;color:var(--ink-soft);}
  .hidden{display:none !important;}
  @media(max-width:720px){
    .hero h1{font-size:32px;}
    .how-grid{grid-template-columns:1fr 1fr;}
    .how-step{border-right:none;border-bottom:1px solid var(--border);}
    .grid-2{grid-template-columns:1fr;}
    .radio-cards{grid-template-columns:1fr;}
    .court-grid{grid-template-columns:1fr;}
    .pay-methods{grid-template-columns:1fr 1fr;}
    .stat-row{grid-template-columns:1fr 1fr;}
    table.slots{font-size:10.5px;}
    .topbar nav{display:none;}
  }
</style>
</head>
<body>

<div class="topbar">
  <div class="topbar-inner">
    <div class="brand">
      <svg width="26" height="26" viewBox="0 0 26 26"><circle cx="13" cy="13" r="12" fill="#C7E24D"/><circle cx="9" cy="9" r="1.3" fill="#0B363B"/><circle cx="17" cy="9" r="1.3" fill="#0B363B"/><circle cx="13" cy="13" r="1.3" fill="#0B363B"/><circle cx="9" cy="17" r="1.3" fill="#0B363B"/><circle cx="17" cy="17" r="1.3" fill="#0B363B"/></svg>
      Speed Paddle
    </div>
    <nav>
      <a href="#" onclick="goHome();return false;">Home</a>
      <a href="#" onclick="goAdmin();return false;">Admin</a>
      <button class="btn-share" onclick="shareLink()">Share Reservation Site</button>
    </nav>
  </div>
</div>
<div class="court-rule"></div>

<div id="view-home">
  <div class="hero">
    <svg class="court-lines" viewBox="0 0 1080 300" preserveAspectRatio="none">
      <rect x="20" y="20" width="1040" height="260" fill="none" stroke="#F4F1E8" stroke-width="2"/>
      <line x1="540" y1="20" x2="540" y2="280" stroke="#F4F1E8" stroke-width="2"/>
      <line x1="20" y1="150" x2="1080" y2="150" stroke="#F4F1E8" stroke-width="2"/>
      <line x1="330" y1="20" x2="330" y2="280" stroke="#F4F1E8" stroke-width="2"/>
      <line x1="750" y1="20" x2="750" y2="280" stroke="#F4F1E8" stroke-width="2"/>
    </svg>
    <div class="hero-inner">
      <p class="kicker">LTO Carcar Court · Carcar City · Open daily 6 AM – 10 PM</p>
      <h1>Book your pickleball court</h1>
      <p>Reserve your court quickly and easily, right from your phone — no calls, no waiting.</p>
      <button class="btn-primary" onclick="startBooking()">Book Now</button>
    </div>
  </div>

  <div class="app">
    <div class="how">
      <h2>How it works</h2>
      <div class="how-grid">
        <div class="how-step"><div class="num">1</div><p>Enter your customer information</p></div>
        <div class="how-step"><div class="num">2</div><p>Select date, time & an available court</p></div>
        <div class="how-step"><div class="num">3</div><p>Complete payment</p></div>
        <div class="how-step"><div class="num">4</div><p>Receive your reservation confirmation</p></div>
      </div>
    </div>
  </div>
</div>

<div id="view-booking" class="app hidden">
  <div class="section">
    <div class="progress" id="progress"></div>

    <!-- STEP 1 -->
    <div id="step-1" class="card">
      <h2 style="margin-top:0;">Customer information</h2>
      <div class="field" id="f-name"><label>Full name</label><input type="text" id="in-name" placeholder="Juan Dela Cruz"><div class="error">Please enter your full name.</div></div>
      <div class="grid-2">
        <div class="field" id="f-contact"><label>Contact number</label><input type="tel" id="in-contact" placeholder="09XX XXX XXXX"><div class="error">Please enter a valid contact number.</div></div>
        <div class="field" id="f-email"><label>Email address</label><input type="email" id="in-email" placeholder="you@email.com"><div class="error">Please enter a valid email.</div></div>
      </div>
      <div class="field" id="f-players"><label>Number of players</label><input type="number" id="in-players" min="1" max="16" placeholder="4"><div class="error">Please enter the number of players.</div></div>
      <div class="field" id="f-type">
        <label>Reservation type</label>
        <div class="radio-cards" id="type-cards">
          <label class="radio-card"><input type="radio" name="rtype" value="Regular Court Reservation"> Regular Court Reservation</label>
          <label class="radio-card"><input type="radio" name="rtype" value="Private/Exclusive Court Reservation"> Private / Exclusive</label>
          <label class="radio-card"><input type="radio" name="rtype" value="Group Reservation"> Group Reservation</label>
          <label class="radio-card"><input type="radio" name="rtype" value="Other"> Other</label>
        </div>
        <div class="error">Please choose a reservation type.</div>
      </div>
      <div class="actions"><span></span><button class="btn primary" onclick="toStep2()">Continue</button></div>
    </div>

    <!-- STEP 2 -->
    <div id="step-2" class="card hidden">
      <h2 style="margin-top:0;">Date, time & court</h2>
      <div class="grid-2">
        <div class="field" id="f-date"><label>Reservation date</label><input type="date" id="in-date"><div class="error">Please choose a date.</div></div>
        <div></div>
        <div class="field" id="f-start"><label>Start time</label><input type="time" id="in-start"><div class="error">Please choose a start time.</div></div>
        <div class="field" id="f-end"><label>End time</label><input type="time" id="in-end"><div class="error">End time must be after start time.</div></div>
      </div>
      <button class="btn" onclick="checkAvailability()">Check court availability</button>

      <div id="avail-block" class="hidden">
        <div class="alert" id="avail-alert"></div>
        <h3 style="margin-bottom:6px;">Court availability</h3>
        <p class="hint" style="margin-top:-4px;">For the selected date &amp; time. Booked courts can't be selected.</p>
        <div class="court-grid" id="court-grid"></div>

        <h3 style="margin-bottom:6px;">Hourly view — <span id="slots-date-label"></span></h3>
        <div id="slots-table-wrap" style="overflow-x:auto;"></div>
      </div>

      <div id="summary-block" class="hidden" style="margin-top:26px;">
        <h3>Reservation summary</h3>
        <div class="card" style="padding:20px;">
          <ul class="summary-list" id="summary-list"></ul>
        </div>
      </div>

      <div class="actions">
        <button class="btn ghost" onclick="toStep1()">Back</button>
        <button class="btn primary" id="btn-to-payment" disabled onclick="toStep3()">Continue to Payment</button>
      </div>
    </div>

    <!-- STEP 3 -->
    <div id="step-3" class="card hidden">
      <h2 style="margin-top:0;">Payment</h2>
      <div class="card" style="background:var(--paper);margin-bottom:22px;">
        <ul class="summary-list" id="summary-list-2"></ul>
      </div>

      <label>Payment method</label>
      <div class="pay-methods" id="pay-methods">
        <div class="pay-method" data-v="GCash">GCash</div>
        <div class="pay-method" data-v="Maya">Maya</div>
        <div class="pay-method" data-v="Bank Transfer">Bank Transfer</div>
        <div class="pay-method" data-v="Cash Payment">Cash Payment</div>
      </div>
      <div class="error" id="err-paymethod" style="display:none;margin:-10px 0 14px;">Please choose a payment method.</div>

      <div id="online-pay-fields" class="hidden">
        <div class="field" id="f-refnum"><label>Reference number</label><input type="text" id="in-refnum" placeholder="e.g. 0123456789012"><div class="error">Please enter your payment reference number.</div></div>
        <div class="field" id="f-proof">
          <label>Upload payment proof / screenshot</label>
          <label class="file-drop" id="file-drop" for="in-proof">Click to upload a screenshot</label>
          <input type="file" id="in-proof" accept="image/*" style="display:none;" onchange="onProofChange()">
          <div class="error">Please upload your payment proof.</div>
        </div>
      </div>
      <div id="cash-note" class="hint hidden" style="margin-bottom:14px;">Pay in cash at the counter when you arrive. Your slot is held as Pending until then.</div>

      <div class="confirm-row">
        <input type="checkbox" id="in-confirm">
        <label for="in-confirm" style="font-weight:500;">I confirm that the reservation information above is correct.</label>
      </div>
      <div class="error" id="err-confirm" style="display:none;margin-top:-14px;margin-bottom:14px;">Please confirm your information before submitting.</div>

      <div class="actions">
        <button class="btn ghost" onclick="toStep2()">Back</button>
        <button class="btn primary" onclick="submitReservation()">Submit Reservation</button>
      </div>
    </div>
  </div>
</div>

<div id="view-confirm" class="app hidden">
  <div class="section confirm-hero">
    <div class="check">✓</div>
    <h2>Reservation submitted successfully!</h2>
    <p style="color:var(--ink-soft);">We'll verify your payment and confirm your slot shortly.</p>
    <div class="receipt">
      <div class="card">
        <ul class="summary-list" id="confirm-list"></ul>
      </div>
      <div class="share-row">
        <button class="btn primary" onclick="viewReservation()">View Reservation</button>
        <button class="btn" onclick="shareLink()">Save / Share Link</button>
        <button class="btn ghost" onclick="goHome()">Book Another Court</button>
      </div>
    </div>
  </div>
</div>

<div id="view-admin" class="app hidden">
  <div class="section" id="admin-login-wrap">
    <div class="card admin-login">
      <h2 style="margin-top:0;">Admin sign in</h2>
      <p class="hint" style="margin-bottom:18px;">Staff access only.</p>
      <div class="field"><label>Password</label><input type="text" id="in-admin-pass" placeholder="Enter password"></div>
      <button class="btn primary" style="width:100%;" onclick="adminLogin()">Sign in</button>
      <div class="error" id="admin-login-err" style="display:none;margin-top:10px;">Incorrect password.</div>
    </div>
  </div>

  <div class="section hidden" id="admin-dash">
    <h2 style="margin-bottom:4px;">Admin dashboard</h2>
    <p class="hint" style="margin-bottom:20px;">Manage reservations, courts, and payments.</p>

    <div class="stat-row" id="admin-stats"></div>

    <div class="admin-tabs">
      <button class="admin-tab active" data-tab="all" onclick="setAdminTab('all')">All reservations</button>
      <button class="admin-tab" data-tab="today" onclick="setAdminTab('today')">Today</button>
      <button class="admin-tab" data-tab="upcoming" onclick="setAdminTab('upcoming')">Upcoming</button>
      <button class="admin-tab" data-tab="calendar" onclick="setAdminTab('calendar')">Calendar view</button>
      <button class="admin-tab" data-tab="courts" onclick="setAdminTab('courts')">Manage courts</button>
      <button class="admin-tab" data-tab="password" onclick="setAdminTab('password')">Change password</button>
    </div>

    <div id="admin-tab-list">
      <div class="filters">
        <input type="text" id="admin-search" placeholder="Search by name, email, or reservation ID" oninput="renderAdminList()">
        <select id="admin-status-filter" onchange="renderAdminList()">
          <option value="">All statuses</option>
          <option value="Pending">Pending</option>
          <option value="Approved">Approved</option>
          <option value="Rejected">Rejected</option>
          <option value="Cancelled">Cancelled</option>
        </select>
        <button class="btn" onclick="downloadReport()">Generate report (CSV)</button>
      </div>
      <div style="overflow-x:auto;">
        <table class="res">
          <thead><tr>
            <th>Reservation</th><th>Customer</th><th>Court</th><th>Date &amp; time</th><th>Players / Type</th><th>Payment</th><th>Status</th><th>Actions</th>
          </tr></thead>
          <tbody id="admin-list-body"></tbody>
        </table>
      </div>
      <div class="empty hidden" id="admin-list-empty">No reservations match.</div>
    </div>

    <div id="admin-tab-calendar" class="hidden">
      <div class="field" style="max-width:220px;"><label>Date</label><input type="date" id="cal-date" onchange="renderCalendar()"></div>
      <div id="cal-body"></div>
    </div>

    <div id="admin-tab-courts" class="hidden">
      <div id="courts-list"></div>
      <div style="display:flex;gap:10px;margin-top:16px;">
        <input type="text" id="new-court-name" placeholder="New court name (e.g. Court 5)" style="max-width:260px;">
        <button class="btn primary" onclick="addCourt()">Add court</button>
      </div>
    </div>

    <div id="admin-tab-password" class="hidden">
      <div class="card" style="max-width:420px;">
        <h3 style="margin-top:0;">Change admin password</h3>
        <div class="field" id="f-cur-pass"><label>Current password</label><input type="text" id="in-cur-pass"><div class="error">Current password is incorrect.</div></div>
        <div class="field" id="f-new-pass"><label>New password</label><input type="text" id="in-new-pass"><div class="error">New password must be at least 4 characters.</div></div>
        <div class="field" id="f-confirm-pass"><label>Confirm new password</label><input type="text" id="in-confirm-pass"><div class="error">Passwords don't match.</div></div>
        <button class="btn primary" onclick="changeAdminPassword()">Update password</button>
        <p class="hint" id="pass-success" style="display:none;color:var(--green);margin-top:12px;">Password updated. Use it next time you sign in.</p>
      </div>
    </div>
  </div>
</div>

<footer>Speed Paddle · LTO Carcar Court · Pickleball Court Reservation System</footer>

<script>
/* ============ CONFIG ============ */
const RATE_PER_HOUR = 300; // pesos
const DEFAULT_COURTS = [
  {id:'c1', name:'Court 1', active:true},
  {id:'c2', name:'Court 2', active:true},
  {id:'c3', name:'Court 3', active:true},
  {id:'c4', name:'Court 4', active:true},
];
const OPEN_HOUR = 6, CLOSE_HOUR = 22;
const ADMIN_PASSWORD = 'admin123'; // fallback default; overridden by stored password once staff changes it

/* ============ STATE ============ */
let courts = [];
let reservations = [];
let draft = {};
let adminTab = 'all';
let currentAdminPassword = ADMIN_PASSWORD;

async function loadAdminPassword(){
  try{
    const r = await window.storage.get('admin-password', true);
    currentAdminPassword = r ? r.value : ADMIN_PASSWORD;
  }catch(e){ currentAdminPassword = ADMIN_PASSWORD; }
}
async function saveAdminPassword(pw){
  currentAdminPassword = pw;
  try{ await window.storage.set('admin-password', pw, true); }catch(e){}
}

/* ============ STORAGE HELPERS ============ */
async function loadCourts(){
  try{
    const r = await window.storage.get('courts', true);
    courts = r ? JSON.parse(r.value) : DEFAULT_COURTS.slice();
  }catch(e){ courts = DEFAULT_COURTS.slice(); }
  if(!courts.length) courts = DEFAULT_COURTS.slice();
}
async function saveCourts(){
  try{ await window.storage.set('courts', JSON.stringify(courts), true); }catch(e){}
}
async function loadReservations(){
  try{
    const r = await window.storage.get('reservations', true);
    reservations = r ? JSON.parse(r.value) : [];
  }catch(e){ reservations = []; }
}
async function saveReservations(){
  try{ await window.storage.set('reservations', JSON.stringify(reservations), true); }catch(e){
    console.error('Storage error', e);
  }
}

/* ============ NAV ============ */
function showView(id){
  ['view-home','view-booking','view-confirm','view-admin'].forEach(v=>{
    document.getElementById(v).classList.toggle('hidden', v!==id);
  });
  window.scrollTo({top:0,behavior:'smooth'});
}
function goHome(){ showView('view-home'); }
function startBooking(){
  draft = {};
  document.querySelectorAll('#type-cards input').forEach(i=>i.checked=false);
  document.querySelectorAll('#type-cards .radio-card').forEach(c=>c.classList.remove('picked'));
  ['in-name','in-contact','in-email','in-players','in-date','in-start','in-end'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('avail-block').classList.add('hidden');
  document.getElementById('summary-block').classList.add('hidden');
  document.getElementById('btn-to-payment').disabled = true;
  showStep(1);
  showView('view-booking');
}
async function goAdmin(){
  showView('view-admin');
  await loadReservations(); await loadCourts(); await loadAdminPassword();
  document.getElementById('admin-dash').classList.add('hidden');
  document.getElementById('admin-login-wrap').classList.remove('hidden');
}
function shareLink(){
  const url = window.location.href.split('#')[0];
  if(navigator.share){
    navigator.share({title:'Speed Paddle', text:'Book your pickleball court at LTO Carcar online', url}).catch(()=>{});
  } else if(navigator.clipboard){
    navigator.clipboard.writeText(url).then(()=>alert('Link copied! Share it on Facebook, Messenger, or any app.'));
  } else {
    prompt('Copy this link to share:', url);
  }
}

/* ============ STEP PROGRESS ============ */
function renderProgress(active){
  const steps = [{n:1,l:'Customer info'},{n:2,l:'Date & court'},{n:3,l:'Payment'}];
  const el = document.getElementById('progress');
  el.innerHTML = steps.map((s,i)=>{
    const state = s.n<active?'done':(s.n===active?'active':'');
    const dot = s.n<active ? '✓' : s.n;
    let html = `<div class="step ${state}"><div class="dot">${dot}</div><div class="label">${s.l}</div></div>`;
    if(i<steps.length-1) html += `<div class="bar ${s.n<active?'done':''}"></div>`;
    return html;
  }).join('');
}
function showStep(n){
  [1,2,3].forEach(i=>document.getElementById('step-'+i).classList.toggle('hidden', i!==n));
  renderProgress(n);
}

/* ---- radio card visuals ---- */
document.getElementById('type-cards').addEventListener('change', ()=>{
  document.querySelectorAll('#type-cards .radio-card').forEach(c=>{
    c.classList.toggle('picked', c.querySelector('input').checked);
  });
});

/* ============ STEP 1 ============ */
function toStep1(){ showStep(1); }
function validateStep1(){
  let ok = true;
  const name = document.getElementById('in-name').value.trim();
  const contact = document.getElementById('in-contact').value.trim();
  const email = document.getElementById('in-email').value.trim();
  const players = document.getElementById('in-players').value;
  const type = document.querySelector('#type-cards input:checked');

  toggleInvalid('f-name', !name);
  toggleInvalid('f-contact', contact.replace(/\D/g,'').length < 7);
  toggleInvalid('f-email', !/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email));
  toggleInvalid('f-players', !players || players < 1);
  toggleInvalid('f-type', !type);

  ok = name && contact.replace(/\D/g,'').length>=7 && /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email) && players>=1 && type;
  if(ok){
    draft.name=name; draft.contact=contact; draft.email=email;
    draft.players=players; draft.type=type.value;
  }
  return ok;
}
function toggleInvalid(fieldId, invalid){
  document.getElementById(fieldId).classList.toggle('invalid', !!invalid);
}
function toStep2(){
  if(!validateStep1()) return;
  showStep(2);
  document.getElementById('avail-block').classList.add('hidden');
  document.getElementById('summary-block').classList.add('hidden');
  document.getElementById('btn-to-payment').disabled = true;
}

/* ============ STEP 2 ============ */
function timeToMin(t){ const [h,m]=t.split(':').map(Number); return h*60+m; }
function minToLabel(min){
  let h = Math.floor(min/60), m = min%60;
  const ap = h>=12?'PM':'AM';
  let h12 = h%12; if(h12===0) h12=12;
  return `${h12}:${m.toString().padStart(2,'0')} ${ap}`;
}
function overlaps(aStart,aEnd,bStart,bEnd){ return aStart < bEnd && bStart < aEnd; }

async function checkAvailability(){
  const date = document.getElementById('in-date').value;
  const start = document.getElementById('in-start').value;
  const end = document.getElementById('in-end').value;
  toggleInvalid('f-date', !date);
  toggleInvalid('f-start', !start);
  toggleInvalid('f-end', !end || (start && end && timeToMin(end)<=timeToMin(start)));
  if(!date || !start || !end || timeToMin(end)<=timeToMin(start)) return;

  await loadReservations(); await loadCourts();
  draft.date=date; draft.start=start; draft.end=end;
  const startMin = timeToMin(start), endMin = timeToMin(end);
  draft.durationHrs = Math.round(((endMin-startMin)/60)*100)/100;
  draft.total = Math.round(draft.durationHrs * RATE_PER_HOUR);

  const activeCourts = courts.filter(c=>c.active);
  const dayRes = reservations.filter(r=>r.date===date && r.status!=='Rejected' && r.status!=='Cancelled');

  const grid = document.getElementById('court-grid');
  grid.innerHTML = '';
  let anyAvailable = false;
  activeCourts.forEach(court=>{
    const conflict = dayRes.find(r=>r.court===court.name && overlaps(startMin,endMin,timeToMin(r.startTime),timeToMin(r.endTime)));
    const isAvailable = !conflict;
    if(isAvailable) anyAvailable = true;
    const div = document.createElement('div');
    div.className = 'court-card ' + (isAvailable?'available':'booked');
    div.innerHTML = `
      <div class="court-top">
        <span class="court-name">${court.name}</span>
        <span class="status-pill ${isAvailable?'available':'booked'}">${isAvailable?'Available':'Booked'}</span>
      </div>
      ${!isAvailable ? `<div class="booked-note">${minToLabel(timeToMin(conflict.startTime))} – ${minToLabel(timeToMin(conflict.endTime))} reserved</div>` : `<div class="booked-note">Open ${minToLabel(startMin)} – ${minToLabel(endMin)}</div>`}
      ${isAvailable ? `<button class="btn primary" onclick="selectCourt('${court.name}')">Select Court</button>` : ''}
    `;
    grid.appendChild(div);
  });

  const alertEl = document.getElementById('avail-alert');
  if(!anyAvailable){
    alertEl.style.display='block';
    alertEl.textContent = 'All courts are unavailable for the selected time. Please select another court or time.';
  } else {
    alertEl.style.display='none';
  }

  renderSlotsTable(date, activeCourts, dayRes);
  document.getElementById('avail-block').classList.remove('hidden');
  document.getElementById('summary-block').classList.add('hidden');
  document.getElementById('btn-to-payment').disabled = true;
}

function renderSlotsTable(date, activeCourts, dayRes){
  document.getElementById('slots-date-label').textContent = date;
  const hours = [];
  for(let h=OPEN_HOUR; h<CLOSE_HOUR; h++) hours.push(h);
  let html = '<table class="slots"><thead><tr><th>Court</th>';
  hours.forEach(h=> html += `<th>${minToLabel(h*60)}</th>`);
  html += '</tr></thead><tbody>';
  activeCourts.forEach(court=>{
    html += `<tr><td style="font-weight:600;text-align:left;">${court.name}</td>`;
    hours.forEach(h=>{
      const slotStart=h*60, slotEnd=(h+1)*60;
      const busy = dayRes.some(r=>r.court===court.name && overlaps(slotStart,slotEnd,timeToMin(r.startTime),timeToMin(r.endTime)));
      html += `<td class="${busy?'bk':'av'}">${busy?'Booked':'Open'}</td>`;
    });
    html += '</tr>';
  });
  html += '</tbody></table>';
  document.getElementById('slots-table-wrap').innerHTML = html;
}

function selectCourt(courtName){
  draft.court = courtName;
  const list = document.getElementById('summary-list');
  list.innerHTML = `
    <li><span>Customer name</span><span>${draft.name}</span></li>
    <li><span>Date</span><span>${draft.date}</span></li>
    <li><span>Time</span><span>${minToLabel(timeToMin(draft.start))} – ${minToLabel(timeToMin(draft.end))}</span></li>
    <li><span>Selected court</span><span>${draft.court}</span></li>
    <li><span>Duration</span><span>${draft.durationHrs} hr</span></li>
    <li><span>Number of players</span><span>${draft.players}</span></li>
    <li><span>Reservation type</span><span>${draft.type}</span></li>
    <li><span>Total amount</span><span>₱${draft.total.toLocaleString()}</span></li>
  `;
  document.getElementById('summary-block').classList.remove('hidden');
  document.getElementById('btn-to-payment').disabled = false;
  document.getElementById('summary-block').scrollIntoView({behavior:'smooth', block:'nearest'});
}

/* ============ STEP 3 ============ */
document.getElementById('pay-methods').addEventListener('click', (e)=>{
  const el = e.target.closest('.pay-method');
  if(!el) return;
  document.querySelectorAll('.pay-method').forEach(p=>p.classList.remove('picked'));
  el.classList.add('picked');
  draft.paymentMethod = el.dataset.v;
  const isCash = draft.paymentMethod === 'Cash Payment';
  document.getElementById('online-pay-fields').classList.toggle('hidden', isCash);
  document.getElementById('cash-note').classList.toggle('hidden', !isCash);
});
let proofFileName = '';
function onProofChange(){
  const f = document.getElementById('in-proof').files[0];
  const drop = document.getElementById('file-drop');
  if(f){ proofFileName = f.name; drop.textContent = '✓ ' + f.name; drop.classList.add('has-file'); }
}
function toStep3(){
  showStep(3);
  document.getElementById('summary-list-2').innerHTML = document.getElementById('summary-list').innerHTML;
}
function submitReservation(){
  let ok = true;
  document.getElementById('err-paymethod').style.display = draft.paymentMethod ? 'none':'block';
  if(!draft.paymentMethod) ok = false;

  const isCash = draft.paymentMethod === 'Cash Payment';
  if(!isCash){
    const ref = document.getElementById('in-refnum').value.trim();
    toggleInvalid('f-refnum', !ref);
    toggleInvalid('f-proof', !proofFileName);
    if(!ref || !proofFileName) ok = false;
    draft.referenceNumber = ref;
    draft.proofFileName = proofFileName;
  }

  const confirmed = document.getElementById('in-confirm').checked;
  document.getElementById('err-confirm').style.display = confirmed ? 'none':'block';
  if(!confirmed) ok = false;

  if(!ok) return;
  finalizeReservation();
}

async function finalizeReservation(){
  await loadReservations();
  // re-check for conflicts at the moment of submission (prevent double booking race)
  const startMin = timeToMin(draft.start), endMin = timeToMin(draft.end);
  const conflict = reservations.find(r=>r.date===draft.date && r.court===draft.court &&
     r.status!=='Rejected' && r.status!=='Cancelled' &&
     overlaps(startMin,endMin,timeToMin(r.startTime),timeToMin(r.endTime)));
  if(conflict){
    alert(`${draft.court} is unavailable for the selected time. Please select another court or time.`);
    toStep2();
    checkAvailability();
    return;
  }

  const id = 'PB-' + new Date().getFullYear() + '-' + String(Math.floor(10000+Math.random()*89999));
  const isCash = draft.paymentMethod === 'Cash Payment';
  const reservation = {
    id,
    name: draft.name, contact: draft.contact, email: draft.email,
    players: draft.players, type: draft.type,
    date: draft.date, startTime: draft.start, endTime: draft.end,
    court: draft.court, durationHrs: draft.durationHrs, total: draft.total,
    paymentMethod: draft.paymentMethod,
    referenceNumber: draft.referenceNumber || '',
    proofFileName: draft.proofFileName || '',
    paymentStatus: isCash ? 'Unpaid' : 'Pending Verification',
    status: 'Pending',
    createdAt: new Date().toISOString(),
  };
  reservations.push(reservation);
  await saveReservations();
  draft.lastId = id;
  draft.lastReservation = reservation;
  showConfirmation(reservation);
}

function showConfirmation(r){
  document.getElementById('confirm-list').innerHTML = `
    <li><span>Reservation ID</span><span>${r.id}</span></li>
    <li><span>Customer name</span><span>${r.name}</span></li>
    <li><span>Court</span><span>${r.court}</span></li>
    <li><span>Reservation date</span><span>${r.date}</span></li>
    <li><span>Time</span><span>${minToLabel(timeToMin(r.startTime))} – ${minToLabel(timeToMin(r.endTime))}</span></li>
    <li><span>Duration</span><span>${r.durationHrs} hr</span></li>
    <li><span>Payment status</span><span>${r.paymentStatus}</span></li>
    <li><span>Reservation status</span><span>${r.status}</span></li>
  `;
  showView('view-confirm');
}
function viewReservation(){
  if(draft.lastReservation) showConfirmation(draft.lastReservation);
}

/* ============ ADMIN ============ */
function adminLogin(){
  const pass = document.getElementById('in-admin-pass').value;
  if(pass === currentAdminPassword){
    document.getElementById('admin-login-wrap').classList.add('hidden');
    document.getElementById('admin-dash').classList.remove('hidden');
    document.getElementById('admin-login-err').style.display='none';
    document.getElementById('cal-date').value = new Date().toISOString().slice(0,10);
    renderAdminAll();
  } else {
    document.getElementById('admin-login-err').style.display='block';
  }
}
function todayStr(){ return new Date().toISOString().slice(0,10); }

function renderAdminAll(){
  renderAdminStats();
  renderAdminList();
  renderCourtsManage();
}
function renderAdminStats(){
  const today = todayStr();
  const totalToday = reservations.filter(r=>r.date===today).length;
  const pending = reservations.filter(r=>r.status==='Pending').length;
  const approved = reservations.filter(r=>r.status==='Approved').length;
  const activeCourts = courts.filter(c=>c.active).length;
  document.getElementById('admin-stats').innerHTML = `
    <div class="stat"><div class="num">${reservations.length}</div><div class="lbl">Total reservations</div></div>
    <div class="stat"><div class="num">${totalToday}</div><div class="lbl">Today's reservations</div></div>
    <div class="stat"><div class="num">${pending}</div><div class="lbl">Pending approval</div></div>
    <div class="stat"><div class="num">${activeCourts}</div><div class="lbl">Active courts</div></div>
  `;
}
function setAdminTab(tab){
  adminTab = tab;
  document.querySelectorAll('.admin-tab').forEach(t=>t.classList.toggle('active', t.dataset.tab===tab));
  document.getElementById('admin-tab-list').classList.toggle('hidden', tab==='calendar' || tab==='courts' || tab==='password');
  document.getElementById('admin-tab-calendar').classList.toggle('hidden', tab!=='calendar');
  document.getElementById('admin-tab-courts').classList.toggle('hidden', tab!=='courts');
  document.getElementById('admin-tab-password').classList.toggle('hidden', tab!=='password');
  if(tab==='calendar') renderCalendar();
  if(tab!=='calendar' && tab!=='courts' && tab!=='password') renderAdminList();
}
function renderAdminList(){
  const search = document.getElementById('admin-search').value.trim().toLowerCase();
  const statusFilter = document.getElementById('admin-status-filter').value;
  const today = todayStr();
  let list = reservations.slice().sort((a,b)=> (a.date+a.startTime) < (b.date+b.startTime) ? 1 : -1);

  if(adminTab==='today') list = list.filter(r=>r.date===today);
  if(adminTab==='upcoming') list = list.filter(r=>r.date>=today);
  if(statusFilter) list = list.filter(r=>r.status===statusFilter);
  if(search){
    list = list.filter(r => (r.name+' '+r.email+' '+r.id).toLowerCase().includes(search));
  }

  const body = document.getElementById('admin-list-body');
  document.getElementById('admin-list-empty').classList.toggle('hidden', list.length>0);
  body.innerHTML = list.map(r=>`
    <tr>
      <td><b>${r.id}</b><br><span class="hint">${new Date(r.createdAt).toLocaleDateString()}</span></td>
      <td>${r.name}<br><span class="hint">${r.contact}</span></td>
      <td>${r.court}</td>
      <td>${r.date}<br><span class="hint">${minToLabel(timeToMin(r.startTime))}–${minToLabel(timeToMin(r.endTime))}</span></td>
      <td>${r.players}<br><span class="hint">${r.type}</span></td>
      <td>${r.paymentMethod}<br>
        <span class="tag ${r.paymentStatus==='Paid'?'paid':'unpaid'}">${r.paymentStatus}</span>
        ${r.proofFileName?`<br><span class="hint">📎 ${r.proofFileName}</span>`:''}
      </td>
      <td><span class="tag ${r.status.toLowerCase()}">${r.status}</span></td>
      <td><div class="row-actions">
        ${r.status==='Pending'?`<button class="primary" onclick="setStatus('${r.id}','Approved')">Approve</button><button class="danger" onclick="setStatus('${r.id}','Rejected')">Reject</button>`:''}
        ${r.status!=='Cancelled'?`<button onclick="setStatus('${r.id}','Cancelled')">Cancel</button>`:''}
        ${r.paymentStatus!=='Paid'?`<button onclick="setPaymentStatus('${r.id}','Paid')">Mark Paid</button>`:''}
        <button onclick="removeReservation('${r.id}')">Delete</button>
      </div></td>
    </tr>
  `).join('');
}
async function setStatus(id, status){
  const r = reservations.find(x=>x.id===id);
  if(r){ r.status = status; await saveReservations(); renderAdminAll(); }
}
async function setPaymentStatus(id, status){
  const r = reservations.find(x=>x.id===id);
  if(r){ r.paymentStatus = status; await saveReservations(); renderAdminAll(); }
}
async function removeReservation(id){
  if(!confirm('Delete this reservation permanently?')) return;
  reservations = reservations.filter(x=>x.id!==id);
  await saveReservations(); renderAdminAll();
}
function downloadReport(){
  const headers = ['Reservation ID','Name','Contact','Email','Court','Date','Start','End','Duration','Players','Type','Payment Method','Payment Status','Status','Total'];
  const rows = reservations.map(r=>[r.id,r.name,r.contact,r.email,r.court,r.date,r.startTime,r.endTime,r.durationHrs,r.players,r.type,r.paymentMethod,r.paymentStatus,r.status,r.total]);
  const csv = [headers, ...rows].map(row=>row.map(v=>`"${String(v??'').replace(/"/g,'""')}"`).join(',')).join('\n');
  const blob = new Blob([csv], {type:'text/csv'});
  const a = document.createElement('a');
  a.href = URL.createObjectURL(blob);
  a.download = 'speed-paddle-reservations.csv';
  a.click();
}
function renderCalendar(){
  const date = document.getElementById('cal-date').value || todayStr();
  const dayRes = reservations.filter(r=>r.date===date && r.status!=='Rejected' && r.status!=='Cancelled');
  const active = courts.filter(c=>c.active);
  let html = '';
  active.forEach(court=>{
    html += `<div class="cal-court"><h4>${court.name}</h4><div class="cal-grid">`;
    for(let h=OPEN_HOUR; h<CLOSE_HOUR; h++){
      const slotStart=h*60, slotEnd=(h+1)*60;
      const busy = dayRes.some(r=>r.court===court.name && overlaps(slotStart,slotEnd,timeToMin(r.startTime),timeToMin(r.endTime)));
      html += `<div class="cal-slot ${busy?'bk':'av'}">${minToLabel(slotStart)} – ${busy?'Booked':'Available'}</div>`;
    }
    html += `</div></div>`;
  });
  document.getElementById('cal-body').innerHTML = html || '<div class="empty">No active courts.</div>';
}
function renderCourtsManage(){
  const wrap = document.getElementById('courts-list');
  wrap.innerHTML = courts.map(c=>`
    <div class="court-manage-row">
      <span><b>${c.name}</b> <span class="hint">${c.active?'Active':'Disabled'}</span></span>
      <div class="row-actions">
        <button onclick="renameCourt('${c.id}')">Rename</button>
        <button onclick="toggleCourt('${c.id}')">${c.active?'Disable':'Enable'}</button>
        <button class="danger" onclick="deleteCourt('${c.id}')">Remove</button>
      </div>
    </div>
  `).join('');
}
async function addCourt(){
  const input = document.getElementById('new-court-name');
  const name = input.value.trim();
  if(!name) return;
  courts.push({id:'c'+Date.now(), name, active:true});
  input.value='';
  await saveCourts(); renderCourtsManage(); renderAdminStats();
}
async function renameCourt(id){
  const c = courts.find(x=>x.id===id);
  const name = prompt('New court name', c.name);
  if(name && name.trim()){ c.name = name.trim(); await saveCourts(); renderCourtsManage(); }
}
async function toggleCourt(id){
  const c = courts.find(x=>x.id===id);
  c.active = !c.active;
  await saveCourts(); renderCourtsManage(); renderAdminStats();
}
async function deleteCourt(id){
  if(!confirm('Remove this court? Existing reservations for it are kept for records.')) return;
  courts = courts.filter(x=>x.id!==id);
  await saveCourts(); renderCourtsManage(); renderAdminStats();
}

async function changeAdminPassword(){
  const cur = document.getElementById('in-cur-pass').value;
  const next = document.getElementById('in-new-pass').value;
  const confirmPw = document.getElementById('in-confirm-pass').value;
  document.getElementById('pass-success').style.display = 'none';

  const curWrong = cur !== currentAdminPassword;
  toggleInvalid('f-cur-pass', curWrong);
  const tooShort = next.length < 4;
  toggleInvalid('f-new-pass', tooShort);
  const mismatch = next !== confirmPw;
  toggleInvalid('f-confirm-pass', mismatch);

  if(curWrong || tooShort || mismatch) return;

  await saveAdminPassword(next);
  document.getElementById('in-cur-pass').value = '';
  document.getElementById('in-new-pass').value = '';
  document.getElementById('in-confirm-pass').value = '';
  document.getElementById('pass-success').style.display = 'block';
}

/* ============ INIT ============ */
(async function init(){
  await loadCourts();
  await loadReservations();
  const today = new Date().toISOString().slice(0,10);
  document.getElementById('in-date').setAttribute('min', today);
  document.getElementById('cal-date') && (document.getElementById('cal-date').value = today);
})();
</script>
</body>
</html>

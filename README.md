<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Costco – $750 Gift Card</title>
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap" rel="stylesheet">
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'Open Sans', Arial, sans-serif;
    background: #e8edf2;
    display: flex;
    justify-content: center;
    min-height: 100vh;
  }

  .mobile-card {
    width: 100%;
    max-width: 390px;
    min-height: 100vh;
    background: #f2f2f2;
    display: flex;
    flex-direction: column;
  }

  /* ── COSTCO LOGO HEADER ── */
  .logo-header {
    background: #fff;
    padding: 14px 0 12px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-bottom: 2px solid #e8e8e8;
  }

  .costco-logo {
    display: flex;
    flex-direction: column;
    align-items: center;
    line-height: 1;
    user-select: none;
  }

  /* The big red italic COSTCO */
  .costco-logo .name {
    font-size: 42px;
    font-weight: 900;
    font-style: italic;
    color: #e31837;
    letter-spacing: -1px;
    font-family: Arial Black, Arial, sans-serif;
    text-shadow: 1px 1px 0 rgba(0,0,0,0.08);
    line-height: 1;
  }

  /* WHOLESALE with blue bars */
  .costco-logo .wholesale-wrap {
    display: flex;
    flex-direction: column;
    align-items: stretch;
    margin-top: 3px;
    width: 100%;
  }
  .costco-logo .bar {
    height: 3px;
    background: #0060a9;
    border-radius: 1px;
  }
  .costco-logo .wholesale {
    font-size: 11.5px;
    font-weight: 700;
    color: #0060a9;
    letter-spacing: 5px;
    text-align: center;
    padding: 2px 4px;
    font-family: Arial, sans-serif;
    text-transform: uppercase;
  }

  /* ── OFFER CARD ── */
  .offer-card {
    background: #fff;
    margin: 14px 10px 10px;
    border-radius: 10px;
    border: 1px solid #ddd;
    padding: 20px 16px 24px;
    text-align: center;
    box-shadow: 0 2px 8px rgba(0,0,0,0.07);
  }

  .offer-badge {
    display: inline-block;
    background: #e31837;
    color: #fff;
    font-size: 10px;
    font-weight: 700;
    letter-spacing: 2.5px;
    padding: 4px 13px;
    border-radius: 3px;
    margin-bottom: 13px;
    text-transform: uppercase;
  }

  .offer-card h2 {
    font-size: 26px;
    font-weight: 700;
    color: #111;
    line-height: 1.25;
    margin-bottom: 7px;
  }
  .offer-card h2 span { color: #e31837; }

  .offer-card .sub {
    font-size: 13px;
    color: #777;
    line-height: 1.55;
    margin-bottom: 20px;
  }

  /* Steps */
  .steps { display: flex; flex-direction: column; gap: 10px; margin-bottom: 22px; }

  .step {
    display: flex;
    align-items: flex-start;
    gap: 12px;
    background: #f7f7f7;
    border: 1px solid #eee;
    border-radius: 8px;
    padding: 13px 14px;
    text-align: left;
  }

  .snum {
    width: 34px;
    height: 34px;
    border-radius: 50%;
    background: #0060a9;
    color: #fff;
    font-size: 15px;
    font-weight: 700;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
  }

  .step h3 { font-size: 14px; font-weight: 700; margin-bottom: 3px; color: #1a1a1a; }
  .step p  { font-size: 12px; color: #888; line-height: 1.45; }

  /* CTA */
  .cta-btn {
    width: 100%;
    background: #e31837;
    color: #fff;
    border: none;
    border-radius: 8px;
    padding: 17px;
    font-size: 15px;
    font-weight: 700;
    letter-spacing: 2px;
    text-transform: uppercase;
    cursor: pointer;
    margin-bottom: 18px;
    box-shadow: 0 4px 14px rgba(227,24,55,0.35);
    transition: background 0.2s, transform 0.12s;
  }
  .cta-btn:active { background: #b0081e; transform: scale(0.98); }

  /* Trust */
  .trust-row {
    display: flex;
    justify-content: center;
    gap: 32px;
    margin-bottom: 18px;
  }
  .trust-item { text-align: center; }
  .trust-icon  { font-size: 22px; margin-bottom: 3px; }
  .trust-label { font-size: 10px; font-weight: 700; color: #999; letter-spacing: 1px; }

  /* Progress */
  .progress-row {
    display: flex;
    justify-content: space-between;
    font-size: 11.5px;
    color: #0060a9;
    font-weight: 700;
    margin-bottom: 5px;
  }
  .progress-bar  { height: 5px; background: #e0e0e0; border-radius: 10px; overflow: hidden; }
  .progress-fill {
    width: 73%;
    height: 100%;
    background: linear-gradient(90deg, #0060a9, #00a3d9);
    border-radius: 10px;
  }
  .claim-note {
    font-size: 11.5px;
    color: #aaa;
    margin-top: 8px;
    text-align: center;
  }
  .claim-note strong { color: #444; }

  /* ── FOOTER ── */
  footer {
    background: #0060a9;
    color: rgba(255,255,255,0.75);
    text-align: center;
    padding: 14px 12px;
    font-size: 11px;
    margin-top: auto;
  }
  footer a { color: rgba(255,255,255,0.9); text-decoration: none; }
</style>
</head>
<body>

<div class="mobile-card">

  <!-- COSTCO LOGO -->
  <div class="logo-header">
    <div class="costco-logo">
      <div class="name">COSTCO</div>
      <div class="wholesale-wrap">
        <div class="bar"></div>
        <div class="wholesale">WHOLESALE</div>
        <div class="bar"></div>
      </div>
    </div>
  </div>

  <!-- GIFT CARD OFFER CARD -->
  <div class="offer-card">
    <div class="offer-badge">⭐ Exclusive Member Offer</div>
    <h2>Claim Your <span>$750</span><br>Costco Gift Card</h2>
    <p class="sub">Available to verified Costco members — limited quantities left this month.</p>

    <div class="steps">
      <div class="step">
        <div class="snum">1</div>
        <div>
          <h3>Tap the Button Below</h3>
          <p>Click "Get My Gift Card" to go to the official offer page.</p>
        </div>
      </div>
      <div class="step">
        <div class="snum">2</div>
        <div>
          <h3>Enter Your Details</h3>
          <p>Provide your name and email address to register for the offer.</p>
        </div>
      </div>
      <div class="step">
        <div class="snum">3</div>
        <div>
          <h3>Complete the Tasks</h3>
          <p>Answer a short survey and complete the required deal offers to qualify.</p>
        </div>
      </div>
      <div class="step">
        <div class="snum">4</div>
        <div>
          <h3>Receive Your Gift Card</h3>
          <p>Once verified, your $750 Costco e-gift card will be sent by email.</p>
        </div>
      </div>
    </div>

    <button class="cta-btn" onclick="redirect()" id="main-cta">🎁 GET MY GIFT CARD</button>

    <div class="trust-row">
      <div class="trust-item"><div class="trust-icon">🔒</div><div class="trust-label">SECURE</div></div>
      <div class="trust-item"><div class="trust-icon">✅</div><div class="trust-label">VERIFIED</div></div>
      <div class="trust-item"><div class="trust-icon">⚡</div><div class="trust-label">FAST</div></div>
    </div>

    <div class="progress-row">
      <span>● AVAILABILITY</span>
      <span>73% Claimed</span>
    </div>
    <div class="progress-bar"><div class="progress-fill"></div></div>
    <p class="claim-note"><strong>2,847 members</strong> have claimed their gift card this month</p>
  </div>

  <!-- FOOTER -->
  <footer>
    &copy; 2024 Costco Wholesale Corporation. All rights reserved.<br>
    <a href="#">Privacy Policy</a> &nbsp;|&nbsp; <a href="#">Terms of Use</a>
  </footer>

</div>

<script>
function redirect() {
  window.location.href = "https://giftclick.org/aff_c?offer_id=941&aff_id=178257";
}
</script>
</body>
</html>

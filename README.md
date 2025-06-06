<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Donate | 1776 Project PAC</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      border: 0;
    }

    html, body {
      margin: 0;
      padding: 0;
      border: none;
    }

    body {
      font-family: Arial, sans-serif;
      background: url('tucker.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
    }

    body::before {
      content: "";
      position: fixed;
      inset: 0;
      background: rgba(0, 0, 0, 0.65);
      z-index: -1;
    }

    .container {
      max-width: 640px;
      margin: 60px auto;
      background: rgba(255, 255, 255, 0.95);
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 25px rgba(0, 0, 0, 0.4);
      color: #222;
    }

    .branding {
      text-align: center;
      font-size: 1.1rem;
      color: #003366;
      font-weight: bold;
      margin-bottom: 10px;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    h1 {
      text-align: center;
      color: #003366;
      font-size: 2rem;
      margin-bottom: 5px;
    }

    h2 {
      text-align: center;
      font-weight: normal;
      margin-top: -10px;
      color: #444;
      margin-bottom: 20px;
    }

    p {
      text-align: center;
      font-size: 1.05rem;
      margin-bottom: 20px;
    }

    .donate-buttons {
      text-align: center;
      margin: 20px 0 10px 0;
    }

    .donate-buttons a {
      display: inline-block;
      padding: 14px 28px;
      border-radius: 5px;
      background: #e63900;
      color: white;
      text-decoration: none;
      font-weight: bold;
      font-size: 18px;
      transition: background 0.3s ease;
    }

    .donate-buttons a:hover {
      background: #cc3300;
    }

    .trust-signal {
      text-align: center;
      margin-top: 10px;
      font-size: 0.9rem;
      color: #228B22;
      font-weight: bold;
    }

    form {
      margin-top: 30px;
      border-top: 1px solid #ccc;
      padding-top: 20px;
    }

    label {
      font-weight: bold;
      display: block;
      margin-top: 15px;
    }

    input, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border-radius: 5px;
      border: 1px solid #aaa;
      font-size: 1rem;
    }

    button {
      background: #007bff;
      color: white;
      border: none;
      padding: 12px 24px;
      font-size: 16px;
      border-radius: 4px;
      cursor: pointer;
      margin-top: 20px;
    }

    button:hover {
      background: #0056b3;
    }

    details {
      background: #f4f4f4;
      color: #222;
      padding: 12px;
      margin-top: 12px;
      border-radius: 6px;
    }

    summary {
      font-weight: bold;
      cursor: pointer;
    }

    footer {
      text-align: center;
      margin-top: 40px;
      font-size: 0.9rem;
      color: #555;
    }

    .unsubscribe-form {
      margin-top: 40px;
      text-align: center;
    }

    .unsubscribe-form input {
      width: 80%;
      padding: 10px;
      border-radius: 4px;
      border: 1px solid #aaa;
      margin-bottom: 10px;
      font-size: 1rem;
    }

    .unsubscribe-form button {
      padding: 10px 20px;
      background: #999;
      border: none;
      color: white;
      font-weight: bold;
      border-radius: 4px;
      cursor: pointer;
    }

    .unsubscribe-form button:hover {
      background: #666;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="branding">1776 Project PAC</div>

    <h1>Donate Once, Hassle-Free!</h1>
    <h2>Your one-time gift powers our campaign—without the spam.</h2>

    <p>We respect your support and promise to only charge you once this season. You might get a few friendly reminders, but once you donate, we won’t ask again. Unlike others, we keep your info private and never share it. Your contribution fuels our mission to restore American values.</p>

    <div class="donate-buttons">
      <a href="https://secure.winred.com/1776-project-pac/moralrighttucker-tuckerpunchemail-em-be/?recurring=true&amtposition=2" target="_blank">Give Once Now</a>
    </div>
    <div class="trust-signal">🔒 100% Secure Payment</div>

    <!-- Pledge Form -->
    <form action="https://script.google.com/macros/s/AKfycby-h_Pa3wxpiLDQeAyiP2Q5tk7MKtoEyqfMs834KV0QGaFeoNMDH5M-qJ7fhEai7Ola3w/exec" method="GET">
      <h3 style="text-align:center;">Not ready yet? Pick a date and amount for a one-time reminder.</h3>

      <label for="email">Your Email:</label>
      <input type="email" name="email" required />

      <label for="pledge-date">Reminder Date:</label>
      <select name="pledge-date" required>
        <option value="">Select a date</option>
        <option>June 10</option>
        <option>June 15</option>
        <option>June 20</option>
        <option>July 1</option>
      </select>

      <label for="pledge-amount">Pledge Amount ($):</label>
      <input type="number" name="pledge-amount" min="1" required />

      <button type="submit">Set Pledge Reminder</button>
    </form>

    <!-- Unsubscribe Form (JJ Style) -->
    <div class="unsubscribe-form">
      <h3>Too many emails?</h3>
      <p>Enter your email below and we’ll never email you again.</p>
      <form action="https://script.google.com/macros/s/AKfycby-h_Pa3wxpiLDQeAyiP2Q5tk7MKtoEyqfMs834KV0QGaFeoNMDH5M-qJ7fhEai7Ola3w/exec" method="GET">
        <input type="email" name="unsubscribe" placeholder="Your email address" required />
        <br/>
        <button type="submit">Unsubscribe Me</button>
      </form>
    </div>

    <!-- FAQ Section -->
    <div style="margin-top:40px;">
      <h3>Frequently Asked Questions</h3>

      <details>
        <summary>Why do you only ask for one donation?</summary>
        <p>We believe in earning your support without harassing you. That’s why we only ask for one gift each season. One and done.</p>
      </details>

      <details>
        <summary>Will I get charged again?</summary>
        <p>Nope. This is a one-time charge. No recurring payments, no hidden fees. Period.</p>
      </details>

      <details>
        <summary>What happens if I don’t donate today?</summary>
        <p>You can pledge to give later. Choose a date and amount, and we’ll send you a one-time reminder—no spam, no pressure.</p>
      </details>

      <details>
        <summary>What happens when I unsubscribe?</summary>
        <p>You’ll stop hearing from us completely. No more emails or reminders. We’ll miss you, but we respect your choice.</p>
      </details>

      <details>
        <summary>Is this secure?</summary>
        <p>Yes. We use encrypted payments and never sell or share your information. You’re safe with us.</p>
      </details>
    </div>

    <footer>
      One Gift, Zero Hassle – Your trusted way to support us.
    </footer>
  </div>
</body>
</html>

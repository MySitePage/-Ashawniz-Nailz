<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover" />
  <title>Ashawniz Nailz</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #f8f4ff;
      font-family: 'Poppins', system-ui, -apple-system, sans-serif;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 0;
    }

    /* ===== FULL-WIDTH IMAGE SECTIONS ===== */
    .section {
      width: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
      padding: 0;
      line-height: 0;
    }

    .section img {
      width: 100%;
      height: auto;
      display: block;
      image-rendering: auto;
    }

    /* ===== SECTION 10: IMAGE + GOOGLE CALENDAR BOOKING FORM ===== */
    .section-booking {
      position: relative;
      width: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 0;
      line-height: 0;
    }

    .section-booking img {
      width: 100%;
      height: auto;
      display: block;
      image-rendering: auto;
    }

    .booking-overlay {
      position: absolute;
      top: 60%; /* MOVED LOWER - was 50% */
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      z-index: 2;
      width: 80%;
      max-width: 600px;
      background: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
      padding: 2rem 2rem 1.8rem;
      border-radius: 28px;
      border: 1px solid rgba(255, 255, 255, 0.25);
      box-shadow: 0 8px 40px rgba(0, 0, 0, 0.1);
    }

    .booking-label {
      display: block;
      font-size: 0.9rem;
      text-transform: uppercase;
      letter-spacing: 0.2em;
      color: rgba(255, 255, 255, 0.95);
      margin-bottom: 1rem;
      font-weight: 500;
      text-shadow: 0 1px 8px rgba(0, 0, 0, 0.15);
    }

    .booking-overlay iframe {
      width: 100%;
      height: 450px;
      border: 0;
      border-radius: 16px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
      background: rgba(255, 255, 255, 0.05);
    }

    /* ===== RESPONSIVE ===== */
    @media (max-width: 768px) {
      .booking-overlay {
        width: 88%;
        max-width: 500px;
        padding: 1.5rem 1.2rem 1.2rem;
        border-radius: 22px;
        top: 58%; /* Slightly lower on tablet */
      }
      .booking-overlay iframe {
        height: 380px;
      }
      .booking-label {
        font-size: 0.75rem;
        margin-bottom: 0.8rem;
      }
    }

    @media (max-width: 480px) {
      .booking-overlay {
        width: 92%;
        max-width: 340px;
        padding: 1rem 0.8rem 0.8rem;
        border-radius: 18px;
        top: 55%; /* Lower on mobile */
      }
      .booking-overlay iframe {
        height: 300px;
      }
      .booking-label {
        font-size: 0.6rem;
        letter-spacing: 0.15em;
        margin-bottom: 0.6rem;
      }
    }
  </style>
</head>
<body>

  <!-- ===== 1 ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/tJc8kkH1/3.png" alt="Ashawniz Nailz 1" />
  </section>

  <!-- ===== 2 ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/fLBGtZqw/4.png" alt="Ashawniz Nailz 2" />
  </section>

  <!-- ===== 3 (REPLACED) ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/dtnX8c1n/Ashawniz-website-20260713-054730-0000.png" alt="Ashawniz Nailz 3" />
  </section>

  <!-- ===== 4 (REPLACED) ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/BQNyxf67/Ashawniz-website-20260713-054754-0000.png" alt="Ashawniz Nailz 4" />
  </section>

  <!-- ===== 5 (REPLACED) ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/X7xhw6JQ/Ashawniz-website-20260713-054811-0000.png" alt="Ashawniz Nailz 5" />
  </section>

  <!-- ===== 6 (REPLACED) ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/8Pw3hg5B/Ashawniz-website-20260713-054828-0000.png" alt="Ashawniz Nailz 6" />
  </section>

  <!-- ===== 7 (REPLACED) ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/5NpGwW0z/Ashawniz-website-20260713-054903-0000.png" alt="Ashawniz Nailz 7" />
  </section>

  <!-- ===== 8 (REPLACED) ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/NfbV1vMm/Ashawniz-website-20260713-054843-0000.png" alt="Ashawniz Nailz 8" />
  </section>

  <!-- ===== 9 (REPLACED) ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/WbSKMc3k/Ashawniz-website-20260713-054957-0000.png" alt="Ashawniz Nailz 9" />
  </section>

  <!-- ===== 10 WITH GOOGLE CALENDAR BOOKING FORM (REPLACED & LOWER) ===== -->
  <section class="section-booking">
    <img src="https://i.postimg.cc/qMQY8HRn/Ashawniz-website-20260713-054919-0000.png" alt="Ashawniz Nailz 10" />
    <div class="booking-overlay">
      <span class="booking-label">📅 Book Your Appointment</span>
      <iframe src="https://calendar.google.com/calendar/appointments/schedules/AcZssZ3oQ_TEb_466J-uqGzM5uAPRLlO6iVzcO8g0amt9Kx-nFlWZBsapbDCK2pF0MWaxjp04l8OEDuI?gv=true" frameborder="0" allowfullscreen></iframe>
    </div>
  </section>

  <!-- ===== 11 (REPLACED) ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/5NpGwW04/Ashawniz-website-20260713-055012-0000.png" alt="Ashawniz Nailz 11" />
  </section>

</body>
</html>

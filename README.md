
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
    }

    /* ===== IMAGE SECTIONS - CENTERED WITH MAX WIDTH ===== */
    .section {
      width: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
      padding: 0.5rem 0;
    }

    .section img {
      width: 100%;
      max-width: 1000px; /* Controls max width for better quality */
      height: auto;
      display: block;
      image-rendering: auto;
      border-radius: 12px; /* Optional: adds a subtle polish */
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.04); /* Optional: soft shadow */
    }

    /* ===== SECTION 4: IMAGE + GOOGLE CALENDAR BOOKING FORM ===== */
    .section-booking {
      position: relative;
      width: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 0.5rem 0;
    }

    .section-booking img {
      width: 100%;
      max-width: 1000px;
      height: auto;
      display: block;
      image-rendering: auto;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.04);
    }

    .booking-overlay {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      z-index: 2;
      width: 80%;
      max-width: 550px;
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
      font-size: 0.8rem;
      text-transform: uppercase;
      letter-spacing: 0.2em;
      color: rgba(255, 255, 255, 0.9);
      margin-bottom: 1rem;
      font-weight: 500;
      text-shadow: 0 1px 8px rgba(0, 0, 0, 0.1);
    }

    .booking-overlay iframe {
      width: 100%;
      height: 400px;
      border: 0;
      border-radius: 16px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
      background: rgba(255, 255, 255, 0.05);
    }

    /* ===== RESPONSIVE ===== */
    @media (max-width: 1024px) {
      .section img,
      .section-booking img {
        max-width: 95%;
      }
      .booking-overlay {
        width: 85%;
        max-width: 500px;
        padding: 1.5rem;
      }
    }

    @media (max-width: 768px) {
      .section img,
      .section-booking img {
        max-width: 98%;
        border-radius: 8px;
      }
      .booking-overlay {
        width: 90%;
        max-width: 450px;
        padding: 1.2rem;
        border-radius: 22px;
      }
      .booking-overlay iframe {
        height: 350px;
      }
      .booking-label {
        font-size: 0.65rem;
        margin-bottom: 0.8rem;
      }
    }

    @media (max-width: 480px) {
      .booking-overlay {
        width: 94%;
        padding: 0.8rem;
        border-radius: 18px;
      }
      .booking-overlay iframe {
        height: 300px;
      }
      .booking-label {
        font-size: 0.55rem;
        letter-spacing: 0.15em;
        margin-bottom: 0.5rem;
      }
    }
  </style>
</head>
<body>

  <!-- ===== IMAGE 1 ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/bYb28M4V/Ashawniz-website.png" alt="Ashawniz Nailz" />
  </section>

  <!-- ===== IMAGE 2 ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/HxyB4zjm/2.jpg" alt="Ashawniz Nailz Section 2" />
  </section>

  <!-- ===== IMAGE 4 WITH GOOGLE CALENDAR BOOKING FORM ===== -->
  <section class="section-booking">
    <img src="https://i.postimg.cc/xCzty58s/4.jpg" alt="Ashawniz Nailz Section 4" />
    <div class="booking-overlay">
      <span class="booking-label">📅 Book Your Appointment</span>
      <iframe src="https://calendar.google.com/calendar/appointments/schedules/AcZssZ3oQ_TEb_466J-uqGzM5uAPRLlO6iVzcO8g0amt9Kx-nFlWZBsapbDCK2pF0MWaxjp04l8OEDuI?gv=true" frameborder="0" allowfullscreen></iframe>
    </div>
  </section>

  <!-- ===== IMAGE 5 ===== -->
  <section class="section">
    <img src="https://i.postimg.cc/XJCQcLqh/3.jpg" alt="Ashawniz Nailz Section 5" />
  </section>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>A Letter to Kira</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

  <style>
    /* Page background */
    :root{
      --bg1: #fff8fb;
      --bg2: #fff0f6;
      --accent: #cf6da6;
      --muted: #6b3d53;
    }

    html,body{
      height:100%;
      margin:0;
      padding:0;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      background: linear-gradient(135deg, var(--bg1) 0%, var(--bg2) 100%);
      font-family: "Poppins", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      color: #3b2b33;
    }

    /* subtle paper texture using gradients */
    body::before{
      content:"";
      position:fixed;
      inset:0;
      background-image:
        radial-gradient(rgba(255,255,255,0.15) 1px, transparent 1px),
        linear-gradient(180deg, rgba(255,255,255,0.03), rgba(0,0,0,0.02));
      background-size: 40px 40px, 100% 100%;
      pointer-events:none;
      mix-blend-mode:soft-light;
    }

    /* center layout */
    .letter {
      max-width: 820px;
      margin: 56px auto;
      background: linear-gradient(180deg, rgba(255,255,255,0.94), rgba(255,255,255,0.90));
      padding: 46px;
      border-radius: 18px;
      box-shadow: 0 12px 30px rgba(64,32,48,0.12);
      border: 1px solid rgba(222,180,198,0.35);
    }

    /* heart */
    .heart {
      font-size: 48px;
      text-align: center;
      margin-top: 28px;
      margin-bottom: 10px;
      filter: drop-shadow(0 6px 14px rgba(196,85,140,0.15));
      animation: pulse 2000ms infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.06); }
      100% { transform: scale(1); }
    }

    /* headings */
    h2 {
      margin: 6px 0 18px 0;
      font-family: "Playfair Display", serif;
      font-weight: 700;
      font-size: 28px;
      color: #8a2e5a;
      text-align: center;
      letter-spacing: 0.6px;
    }

    /* body text styling */
    p {
      font-size: 18px;
      line-height: 1.86;
      color: #3b2b33;
      margin: 0 0 18px 0;
      white-space: pre-wrap; /* preserve your line breaks */
      font-weight: 300;
    }

    /* signature */
    .signature {
      margin-top: 26px;
      text-align: right;
      font-style: italic;
      font-weight: 600;
      color: var(--muted);
      font-size: 17px;
    }

    /* responsive tweaks */
    @media (max-width:700px){
      .letter{ margin:28px 18px; padding:28px; }
      h2{ font-size:22px; }
      p{ font-size:16px; }
      .heart{ font-size:40px; }
    }
  </style>
</head>
<body>
  <div class="heart">❤️</div>

  <div class="letter">
    <h2>Dear Kira,</h2>
    <p>
      You are not a fleeting dream. You are not a passing season. You are the story I wish to tell until the end of my days.

      I do not love you because of what the world sees; I love you for the infinite universe that lives within you — for your laughter, which heals wounds I never spoke of; for your kindness, which teaches me to be softer with the world; for your presence, which steadies me when the storms rise.

      You are my compass, my anchor, my wings. With you, I am both grounded and free. With you, even silence is music, even stillness is poetry. This love is not shallow; it is an ocean. Its tides rise with every heartbeat, and even when the surface is still, beneath it lives a depth that no storm can shake.

      I promise you this: I will not only love you on the easy days, when the skies are clear and the air is sweet. I will love you in the storms, when thunder shakes the ground and shadows fall. I will hold your hand when it trembles, and lift your head when it bows. I will remind you of your strength when you forget, and of your light when the world feels dim.

      My love is not fragile. It is not a candle that flickers in the wind. It is a fire carved into stone, a vow written into the marrow of my being, an eternity carried in every heartbeat.

      Beyond words and beyond the small measures of time we keep, I give you this: a life of patient tending, of faithful mornings and steady nights, of laughter offered freely and refuge given without question. I will learn the maps of your heart so I can find you when the roads grow confusing; I will collect the broken pieces of our hard days and sew them with care until they are whole again. When the world asks for proof, I will show up — not with grand declarations for a single hour, but with quiet, unending acts that say, again and again, you are seen, you are chosen, you are loved.

      Let the seasons come and go and let the shapes of our lives change; I will remain — a constant hand, a willing shoulder, a voice that remembers your name even when you cannot. If someday our steps slow or our hair turns silver, I will still recognize the same light in your eyes that first called me home. This is my promise: to be here, fully and without reservation, for every small ordinary miracle and every fierce storm, for every becoming you are and every rest you need — always, always beside you.
    </p>

    <div class="signature">
      Forever yours,<br>
      Samia
    </div>
  </div>
</body>
</html>

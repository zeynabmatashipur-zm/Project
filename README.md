

<!doctype html>
<html lang="fa">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>نمونه صفحه — HTML + CSS</title>
  <style>
    /* ====== تنظیمات پایه ====== */
    :root{
      --bg: #f7f8fb;
      --card: #ffffff;
      --accent: #4f46e5;
      --muted: #6b7280;
      --glass: rgba(255,255,255,0.6);
      --radius: 12px;
      font-family: "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background:linear-gradient(180deg,var(--bg),#eef2ff 60%);
      color:#111827;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.5;
      padding:24px;
    }
    a{color:inherit;text-decoration:none}

    /* ====== کانتینر ====== */
    .container{max-width:1100px;margin:0 auto;}

    /* ====== ناوبری ====== */
    header{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:16px;
      margin-bottom:28px;
    }
    .brand{display:flex;align-items:center;gap:10px;font-weight:700}
    .logo{
      width:44px;height:44px;border-radius:10px;
      background:linear-gradient(135deg,var(--accent),#06b6d4);
      display:inline-grid;place-items:center;color:#fff;font-weight:700;
      box-shadow:0 6px 20px rgba(79,70,229,0.12);
    }
    nav{display:flex;gap:14px;align-items:center;}
    .btn{
      display:inline-block;padding:8px 14px;border-radius:10px;border:none;
      background:var(--accent);color:#fff;font-weight:600;
      box-shadow:0 6px 18px rgba(79,70,229,0.12);
      cursor:pointer;
    }
    .ghost{background:transparent;color:var(--muted);font-weight:600;padding:6px 10px;border-radius:10px}

    /* ====== هِرو ====== */
    .hero{
      background: linear-gradient(90deg, rgba(255,255,255,0.65), rgba(255,255,255,0.25));
      border-radius:var(--radius);
      padding:28px;
      display:grid;
      grid-template-columns: 1fr 360px;
      gap:20px;
      align-items:center;
      box-shadow:0 8px 30px rgba(16,24,40,0.06);
      margin-bottom:24px;
      backdrop-filter: blur(6px);
    }
    .hero h1{margin:0 0 10px;font-size:28px}
    .


<!DOCTYPE html>
<html lang="ru" data-theme="dark">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title data-i18n="meta.title">HIPWEB — разработчик сайтов | Портфолио</title>
  <meta name="description" data-i18n-attr="content:meta.description" content="HIPWEB — разработчик сайтов. Быстрые, адаптивные и современные сайты под задачи бизнеса." />
  <meta name="color-scheme" content="dark light" />
  <meta name="theme-color" content="#2b8cff" />
  <meta property="og:title" content="HIPWEB — разработчик сайтов" />
  <meta property="og:description" content="Делаю быстрые и красивые сайты, которые приносят заявки." />
  <meta property="og:type" content="website" />
  <meta property="og:locale" content="ru_RU" id="ogLocale"/>
  

<meta name="description" content="HIPWEB — разработка современных сайтов. Быстрые, адаптивные и стильные проекты.">
<meta name="keywords" content="HIPWEB, веб-разработчик, сайты, портфолио, web development, frontend, дизайн">
<meta property="og:title" content="HIPWEB — веб-разработчик" />
<meta property="og:description" content="Создание быстрых, адаптивных и стильных сайтов." />
<meta property="og:type" content="website" />
<meta property="og:image" content="assets/preview.png" />
<meta property="og:url" content="https://hipweb.netlify.app" />
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:title" content="HIPWEB — веб-разработчик" />
<meta name="twitter:description" content="Создание быстрых, адаптивных сайтов под ключ." />
<meta name="twitter:image" content="assets/preview.png" />





<style>

    /* RESET */
    *,*::before,*::after{box-sizing:border-box}
    html,body{height:<span class="counter" data-target="100">0</span>%}
    body{margin:0;line-height:1.55;-webkit-font-smoothing:antialiased;text-rendering:optimizeLegibility}
    img,svg,video,canvas{display:block;max-width:<span class="counter" data-target="100">0</span>%}
    a{color:inherit;text-decoration:none}
    button,input,select,textarea{font:inherit;color:inherit;background:none;border:none}
    :focus-visible{outline:2px solid var(--accent);outline-offset:2px}

    /* THEME (single accent, no gradients) */
    :root{
      --bg:#0f1115;
      --surface:#141820;
      --surface-2:#1b2130;
      --border:#283249;
      --text:#eaf1ff;
      --muted:#9fb0c9;
      --accent:#2b8cff; /* один акцентный цвет */
      --radius-xl:24px;--radius-lg:18px;--radius:12px;--maxw:1200px;
      --shadow:0 10px 30px rgba(0,0,0,.35);
    }
    [data-theme="light"]{
      --bg:#f7f9fe;
      --surface:#ffffff;
      --surface-2:#f1f4fb;
      --border:#dbe3f5;
      --text:#0f1115;
      --muted:#586279;
      --accent:#2b8cff; /* тот же акцент */
      --shadow:0 14px 28px rgba(15,17,21,.10);
    }
    body{font-family:ui-sans-serif,system-ui,-apple-system,"Segoe UI",Inter,Roboto,Arial,"Noto Sans";background:var(--bg);color:var(--text)}

    /* LAYOUT */
    .container{max-width:var(--maxw);padding:0 20px;margin:0 auto}
    .grid{display:grid;gap:20px}
    .section{padding:56px 0}
    .section-head{display:flex;justify-content:space-between;align-items:flex-end;margin-bottom:18px;gap:16px;flex-wrap:wrap}
    .section-head h2{margin:0;font-size:clamp(22px,3.6vw,34px)}
    .section-head p{margin:0;color:var(--muted);max-width:70ch}

    /* NAV */
    .skip{position:absolute;left:-9999px;top:auto;width:1px;height:1px;overflow:hidden}
    .skip:focus{left:8px;top:8px;width:auto;height:auto;background:var(--surface-2);padding:8px 10px;border-radius:10px}
    nav{position:sticky;top:0;z-index:50;border-bottom:1px solid var(--border);background:color-mix(in oklab, var(--surface) 92%, transparent)}
    .nav-wrap{display:flex;align-items:center;justify-content:space-between;gap:10px;padding:10px 0}
    .brand{display:flex;align-items:center;gap:10px}
    .logo{width:38px;height:38px;border-radius:12px;background:var(--accent);display:grid;place-items:center;color:#fff;font-weight:800}
    .brand-name{font-weight:800}
    .nav-actions{display:flex;align-items:center;gap:8px}
    .nav-links{display:flex;gap:6px}
    .link{padding:8px 10px;border-radius:10px;color:var(--muted)}
    .link:hover{color:var(--text);background:var(--surface-2)}
    .btn, .chip{display:inline-flex;align-items:center;gap:8px;padding:10px 14px;border-radius:12px;background:var(--accent);color:#fff;font-weight:700;box-shadow:var(--shadow)}
    .btn.ghost{background:transparent;color:var(--text);border:1px solid var(--border);box-shadow:none}
    .select{padding:9px 12px;border:1px solid var(--border);border-radius:10px;background:var(--surface-2);color:var(--text);cursor:pointer}
    .hamburger{display:none;padding:10px;border:1px solid var(--border);border-radius:10px}
    .mobile-menu{display:none;flex-direction:column;padding:10px;border-top:1px solid var(--border);background:var(--surface)}

    /* HERO */
    .hero{padding:56px 0 24px}
    .hero-wrap{display:grid;grid-template-columns:1.1fr .9fr;gap:24px;align-items:center}
    .kicker{color:var(--muted);font-weight:700;letter-spacing:.12em;text-transform:uppercase;font-size:12px}
    h1{font-size:clamp(34px,6.2vw,56px);line-height:1.04;margin:8px 0 14px}
    .subtitle{color:var(--muted);max-width:65ch;margin:0 0 16px}
    .hero-cta{display:flex;flex-wrap:wrap;gap:10px;margin-top:12px}
    .hero-card{border:1px solid var(--border);border-radius:var(--radius-xl);padding:18px;background:var(--surface);box-shadow:var(--shadow)}
    .hero-badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:8px}
    .badge{padding:6px 10px;border-radius:999px;border:1px solid var(--border);color:var(--muted)}

    /* STRIPS (decor w/o gradients) */
    .strips{position:relative;isolation:isolate}
    .strips::before,.strips::after{content:"";position:absolute;inset:auto 0 -12px 0;height:2px;background:var(--accent);opacity:.15;filter:blur(.6px);z-index:-1}

    /* CARDS */
    .cards{display:grid;grid-template-columns:repeat(12,1fr);gap:16px}
    .card{grid-column:span 4;border:1px solid var(--border);border-radius:16px;background:var(--surface);padding:18px}
    .card h3{margin:2px 0 6px;font-size:18px}
    .card p{margin:0;color:var(--muted)}
    .card:hover{transform:translateY(-3px);transition:.25s ease}

    /* WORK */
    .work .preview{aspect-ratio:16/9;border:1px solid var(--border);border-radius:14px;overflow:hidden;background:var(--surface-2);display:grid;place-items:center}
    .meta{display:flex;flex-wrap:wrap;gap:8px;margin-top:8px}
    .chip{background:transparent;border:1px solid var(--accent);color:var(--accent);font-weight:600}
    .chip.filled{background:var(--accent);color:#fff;border-color:var(--accent)}

    /* PROCESS (timeline) */
    .timeline{display:grid;gap:12px}
    .step{display:grid;grid-template-columns:38px 1fr;gap:12px}
    .dot{width:38px;height:38px;border-radius:12px;background:var(--accent);display:grid;place-items:center;color:#fff;font-weight:800}

    /* TESTIMONIALS */
    .testimonial{border:1px solid var(--border);background:var(--surface);border-radius:16px;padding:18px}
    .testimonial .author{display:flex;align-items:center;gap:10px;margin-top:10px;color:var(--muted)}

    /* FAQ */
    details{border:1px solid var(--border);border-radius:12px;padding:12px 14px;background:var(--surface)}
    summary{cursor:pointer;font-weight:700}
    details p{color:var(--muted)}

    /* CONTACT */
    .contact-grid{display:grid;grid-template-columns:.9fr 1.1fr;gap:16px}
    form{display:grid;gap:10px}
    input,textarea{padding:12px 14px;border:1px solid var(--border);border-radius:10px;background:var(--surface-2);color:var(--text)}
    textarea{min-height:110px;resize:vertical}
    .note{color:var(--muted);font-size:14px}
    .contacts{display:grid;gap:10px}
    .actions{display:flex;flex-wrap:wrap;gap:10px}

    /* FLOAT actions */
    .float{position:fixed;right:14px;bottom:14px;display:flex;flex-direction:column;gap:10px;z-index:60}
    .fab{display:inline-flex;align-items:center;justify-content:center;width:48px;height:48px;border-radius:12px;background:var(--accent);color:#fff;box-shadow:var(--shadow);cursor:pointer}
    .fab.secondary{background:var(--surface-2);color:var(--text);border:1px solid var(--border)}

    /* FOOTER */
    footer{padding:24px 0;color:var(--muted);border-top:1px solid var(--border)}

    /* RESPONSIVE */
    @media (max-width: 1024px){ .card{grid-column:span 6} .hero-wrap{grid-template-columns:1fr} }
    @media (max-width: 720px){
      .cards{grid-template-columns:repeat(6,1fr)}
      .card{grid-column:span 6}
      .nav-links{display:none}
      .hamburger{display:inline-flex}
      .contact-grid{grid-template-columns:1fr}
    }

    /* REVEAL */
    .reveal{opacity:0;transform:translateY(12px);transition:.6s ease}
    .reveal.in{opacity:1;transform:none}
  

.card:hover {transform:translateY(-5px) scale(1.02);transition:all 0.3s ease;}
.btn:hover {transform:translateY(-2px);opacity:0.9;}
.fade-in {opacity:0;transform:translateY(20px);transition:opacity .8s ease,transform .8s ease;}
.fade-in.show {opacity:1;transform:none;}


.stats {
  text-align: center;
  padding: 40px 20px;
  background: #111827;
  color: #fff;
  font-size: 1.2rem;
}
.stats p {
  margin: 5px 0;
}

</style>
<link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
<body>
  <a class="skip" href="#main" data-i18n="skip">К контенту</a>

  <!-- NAV -->
  <nav>
    <div class="container nav-wrap">
      <div class="brand">
        <div class="brand-name" data-i18n="nav.brand">HIPWEB</div>
      </div>
      <div class="nav-actions">
        <div class="nav-links">
          <a class="link" href="#services" data-i18n="nav.services">Услуги</a>
          <a class="link" href="#work" data-i18n="nav.work">Работы</a>
          <a class="link" href="#process" data-i18n="nav.process">Процесс</a>
          <a class="link" href="#contact" data-i18n="nav.contact">Контакты</a>
        </div>
        <select id="lang" class="select" aria-label="Language">
          <option value="ru">RU</option>
          <option value="en">EN</option>
          <option value="uk">UA</option>
        </select>
        <button class="hamburger" id="hamburger" aria-label="Menu">☰</button>
        <button class="hamburger" id="themeToggle" aria-label="Theme">🌓</button>
        <a class="btn" href="tel:+380682749391" aria-label="Позвонить">+380 68 274 9391</a>
      </div>
    </div>
    <div id="mobileMenu" class="mobile-menu container">
      <a class="link" href="#services" data-i18n="nav.services">Услуги</a>
      <a class="link" href="#work" data-i18n="nav.work">Работы</a>
      <a class="link" href="#process" data-i18n="nav.process">Процесс</a>
      <a class="link" href="#contact" data-i18n="nav.contact">Контакты</a>
    </div>
  </nav>

  <main id="main">
    <!-- HERO -->
    <header class="hero strips">
      <div class="container hero-wrap">
        <div>
          <div class="kicker" data-i18n="hero.kicker">Web‑разработка</div>
          <h1 class="reveal" data-i18n="hero.title">Создаю сайты, которые красиво продают</h1>
          
          <div class="hero-cta reveal" style="transition-delay:.12s">
            <a class="btn" href="#contact" data-i18n="hero.cta1">Обсудить проект</a>
            <a class="btn ghost" href="#work" data-i18n="hero.cta2">Смотреть работы</a>
          </div>
          <div class="hero-badges reveal" style="transition-delay:.16s">
            <span class="badge">Lighthouse 90+ ⚡</span>
            <span class="badge">Responsive <span class="counter" data-target="100">0</span>%</span>
            <span class="badge">SEO‑ready</span>
            <span class="badge">CMS / Headless</span>
          </div>
        </div>
        <div class="hero-card reveal" style="transition-delay:.18s">
          <div class="grid" style="gap:10px">
            <div style="display:flex;align-items:center;gap:10px">
              <div class="dot" aria-hidden="true">✓</div>
              <strong data-i18n="hero.card.title">Только необходимое</strong>
            </div>
            <p class="subtitle" style="margin:0" data-i18n="hero.card.text">Без перегруза библиотеками. Чистая архитектура, понятный код, комфортная поддержка.</p>
            <div class="meta">
              <span class="chip">HTML</span><span class="chip">CSS/Tailwind</span><span class="chip">JavaScript</span><span class="chip">React/Next.js</span><span class="chip">WordPress</span>
            </div>
          </div>
        </div>
      </div>
    </header>

    <!-- SERVICES -->
    <section id="services" class="section">
      <div class="container">
        <div class="section-head">
          <h2 class="reveal" data-i18n="services.title">Услуги</h2>
          
        </div>
        <div class="cards">
          <article class="card reveal">
            <h3 data-i18n="services.s1.t">Лендинг</h3>
            <p data-i18n="services.s1.d">Структура, оффер, лаконичные анимации, формы и интеграции. От прототипа до запуска.</p>
          </article>
          <article class="card reveal" style="transition-delay:.06s">
            <h3 data-i18n="services.s2.t">Корпоративный сайт</h3>
            <p data-i18n="services.s2.d">Несколько страниц, блог, кейсы и команда. Удобная админка и масштабируемость.</p>
          </article>
          <article class="card reveal" style="transition-delay:.12s">
            <h3 data-i18n="services.s3.t">Интернет‑магазин</h3>
            <p data-i18n="services.s3.d">Каталог, карточки, корзина и оплата. Быстрая загрузка и понятный путь к покупке.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- WORK -->
    <section id="work" class="section">
      <div class="container">
        <div class="section-head">
          <h2 class="reveal" data-i18n="work.title">Выбранные работы</h2>
          
        </div>
        <div class="cards work">
          <article class="card reveal" style="grid-column:span 6">
            <a class="preview" href="https://electroepilation.com.ua/" target="_blank" rel="noopener" aria-label="Electroepilation">
              <svg viewBox="0 0 800 450" aria-hidden="true">
                <rect width="800" height="450" fill="currentColor" opacity=".06"/>
                <g fill="currentColor" opacity=".75">
                  <rect x="120" y="90" width="560" height="36" rx="8"/>
                  <rect x="120" y="150" width="420" height="20" rx="6"/>
                  <rect x="120" y="190" width="480" height="20" rx="6"/>
                  <rect x="120" y="230" width="300" height="20" rx="6"/>
                  <rect x="120" y="300" width="560" height="120" rx="12"/>
                </g>
              </svg>
            </a>
            <div>
              <h3>Electroepilation</h3>
              <p data-i18n="work.p1.d">Сайт студии электроэпиляции: аккуратный дизайн, адаптив, формы записи и SEO‑подготовка. Акцент на простоте и конверсии.</p>
              <div class="meta">
                <span class="chip filled" data-i18n="work.p1.c1">Адаптив</span>
                <span class="chip" data-i18n="work.p1.c2">Формы / интеграции</span>
                <span class="chip" data-i18n="work.p1.c3">SEO‑база</span>
              </div>
              <div class="actions" style="margin-top:10px">
                <a class="btn" href="https://electroepilation.com.ua/" target="_blank" rel="noopener" data-i18n="work.open">Посмотреть проект</a>
              </div>
            </div>
          </article>
          <article class="card reveal" style="grid-column:span 6;transition-delay:.08s">
            <div class="preview" aria-hidden="true">
              <svg viewBox="0 0 800 450">
                <rect width="800" height="450" fill="currentColor" opacity=".06"/>
                <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" font-size="20" fill="currentColor" opacity=".7">Coming soon</text>
              </svg>
            </div>
            <div>
              <h3 data-i18n="work.p2.t">Кейс в процессе</h3>
              <p data-i18n="work.p2.d">Готовлю следующий релиз: лендинг продукта/сайт услуг/магазин. Запросите концепции.</p>
              <div class="meta"><span class="chip">UI/UX</span><span class="chip">Performance</span><span class="chip">CMS</span></div>
            </div>
          </article>
        </div>
      </div>
    </section>

    <!-- PROCESS -->
    <section id="process" class="section">
      <div class="container">
        <div class="section-head">
          <h2 class="reveal" data-i18n="process.title">Как работаю</h2>
          
        </div>
        <div class="grid timeline">
          <div class="step reveal">
            <div class="dot">1</div>
            <div>
              <strong data-i18n="process.s1.t">Бриф и структура</strong>
              <p class="subtitle" data-i18n="process.s1.d">Цели, аудитории, карта страниц и тексты. Согласуем перед дизайном.</p>
            </div>
          </div>
          <div class="step reveal" style="transition-delay:.06s">
            <div class="dot">2</div>
            <div>
              <strong data-i18n="process.s2.t">Дизайн‑концепт</strong>
              <p class="subtitle" data-i18n="process.s2.d">Система блоков и визуальные акценты. Сразу думаю об адаптиве.</p>
            </div>
          </div>
          <div class="step reveal" style="transition-delay:.12s">
            <div class="dot">3</div>
            <div>
              <strong data-i18n="process.s3.t">Сборка и интеграции</strong>
              <p class="subtitle" data-i18n="process.s3.d">Верстка, анимации, формы, аналитика, CRM, пиксели.</p>
            </div>
          </div>
          <div class="step reveal" style="transition-delay:.18s">
            <div class="dot">4</div>
            <div>
              <strong data-i18n="process.s4.t">Запуск и поддержка</strong>
              <p class="subtitle" data-i18n="process.s4.d">Публикация, техподдержка и развитие по задаче.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- TESTIMONIALS -->
    <section id="testimonials" class="section">
      <div class="container">
        <div class="section-head">
          <h2 class="reveal" data-i18n="testimonials.title">Отзывы</h2>
          
        </div>
        <div class="cards">
          <div class="card testimonial reveal">
            <p>«Сайт получился лёгкий и быстрый. HIPWEB оперативно вносил правки и предложил решения, о которых мы не думали.»</p>
            <div class="author">— Анна, владелица студии</div>
          </div>
          <div class="card testimonial reveal" style="transition-delay:.06s">
            <p>«Понравилась структура и логика. Сразу после запуска пошли заявки. Рекомендую!»</p>
            <div class="author">— Дмитрий, предприниматель</div>
          </div>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq" class="section">
      <div class="container">
        <div class="section-head">
          <h2 class="reveal" data-i18n="faq.title">FAQ</h2>
          
        </div>
        <div class="grid" style="grid-template-columns:1fr 1fr;gap:16px">
          <details class="reveal"><summary data-i18n="faq.q1.t">Как формируется стоимость?</summary><p data-i18n="faq.q1.d">Фиксируем объём и функционал, предлагаю 1–2 варианта бюджета под цели. Прозрачно и без скрытых пунктов.</p></details>
          <details class="reveal" style="transition-delay:.06s"><summary data-i18n="faq.q2.t">Сроки?</summary><p data-i18n="faq.q2.d">Зависят от контента и интеграций. Оцениваю реалистично и держу дедлайны.</p></details>
          <details class="reveal" style="transition-delay:.12s"><summary data-i18n="faq.q3.t">Поддержка?</summary><p data-i18n="faq.q3.d">Веду сайт на абонентской основе или передаю с инструкциями вашей команде.</p></details>
          <details class="reveal" style="transition-delay:.18s"><summary data-i18n="faq.q4.t">Договор и оплата?</summary><p data-i18n="faq.q4.d">Формализуем ТЗ и этапы. Предоплата и поэтапные платежи. Документы — по запросу.</p></details>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="section">
      <div class="container">
        <div class="section-head">
          <h2 class="reveal" data-i18n="contact.title">Связаться со мной</h2>
          
        </div>
        <div class="contact-grid">
          <div class="card reveal contacts">
            <div><strong data-i18n="contact.phone">Телефон:</strong> <a href="tel:+380682749391">+380 68 274 9391</a> <button class="chip" id="copyPhone" aria-label="Скопировать номер">📋</button></div>
            <div><strong>Telegram:</strong> <a href="https://t.me/arkhip7_7_7" target="_blank" rel="noopener">@arkhip7_7_7</a></div>
            <div class="actions">
              <a class="btn" href="tel:+380682749391" data-i18n="contact.call">Позвонить</a>
              <a class="btn ghost" href="https://t.me/arkhip7_7_7" target="_blank" rel="noopener" data-i18n="contact.tg">Написать в Telegram</a>
            </div>
            <p class="note" data-i18n="contact.note">Онлайн ежедневно. Отвечаю оперативно.</p>
          </div>
          <div class="card reveal" style="transition-delay:.06s">
            <form id="brief">
              <label class="note" for="name" data-i18n="contact.name">Имя</label>
              <input id="name" name="name" type="text" placeholder="Как к вам обращаться" data-i18n-attr="placeholder:contact.name_ph" required />
              <label class="note" for="project" data-i18n="contact.project">Проект</label>
              <input id="project" name="project" type="text" placeholder="Лендинг / сайт услуг / магазин" data-i18n-attr="placeholder:contact.project_ph" required />
              <label class="note" for="message" data-i18n="contact.msg">Сообщение</label>
              <textarea id="message" name="message" placeholder="Пара предложений о задаче" data-i18n-attr="placeholder:contact.msg_ph"></textarea>
              <button class="btn" type="submit" data-i18n="contact.send">Отправить в Telegram</button>
              <p class="note" data-i18n="contact.disclaimer">Нажимая «Отправить», вы перейдёте в Telegram с готовым сообщением.</p>
            </form>
          </div>
        </div>
      </div>
    </section>
  </main>

  <div class="float">
    <a class="fab" href="tel:+380682749391" title="Позвонить">📞</a>
    <button class="fab secondary" id="toTop" title="Наверх">↑</button>
  </div>

  <footer>
    <div class="container" style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
      <div>© <span id="year"></span> <span data-i18n="footer.owner">HIPWEB — разработчик сайтов</span></div>
      <div style="display:flex;gap:12px">
        <a class="link" href="#work" data-i18n="footer.portfolio">Портфолио</a>
        <a class="link" href="https://t.me/arkhip7_7_7" target="_blank" rel="noopener">Telegram</a>
      </div>
    </div>
  








</footer>

  <!-- JSON-LD -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"Person",
    "name":"HIPWEB",
    "jobTitle":"Web Developer",
    "telephone":"+380682749391",
    "url":"",
    "sameAs":["https://t.me/arkhip7_7_7"],
    "worksFor":{"@type":"Organization","name":"Freelance"},
    "knowsAbout":["HTML","CSS","JavaScript","React","Next.js","WordPress"],
    "description":"Разработчик сайтов: быстрые, адаптивные и SEO‑готовые проекты."
  }
  </script>

  <!-- SCRIPTS -->
  <script>
    // i18n dictionary
    const DICT = {
      ru: {
        'meta.title': 'HIPWEB — разработчик сайтов | Портфолио',
        'meta.description': 'HIPWEB — разработчик сайтов. Быстрые, адаптивные и современные сайты под задачи бизнеса.',
        'skip':'К контенту',
        'nav.brand':'HIPWEB','nav.services':'Услуги','nav.work':'Работы','nav.process':'Процесс','nav.contact':'Контакты',
        'hero.kicker':'Web‑разработка',
        'hero.title':'Создаю сайты, которые красиво продают',
        'hero.cta1':'Обсудить проект','hero.cta2':'Смотреть работы',
        'hero.card.title':'Только необходимое','hero.card.text':'Без перегруза библиотеками. Чистая архитектура, понятный код, комфортная поддержка.',
        'services.title':'Услуги','services.s1.t':'Лендинг','services.s1.d':'Структура, оффер, лаконичные анимации, формы и интеграции. От прототипа до запуска.',
        'services.s2.t':'Корпоративный сайт','services.s2.d':'Несколько страниц, блог, кейсы и команда. Удобная админка и масштабируемость.',
        'services.s3.t':'Интернет‑магазин','services.s3.d':'Каталог, карточки, корзина и оплата. Быстрая загрузка и понятный путь к покупке.',
        'work.title':'Выбранные работы','work.p1.d':'Сайт студии электроэпиляции: аккуратный дизайн, адаптив, формы записи и SEO‑подготовка. Акцент на простоте и конверсии.',
        'work.p1.c1':'Адаптив','work.p1.c2':'Формы / интеграции','work.p1.c3':'SEO‑база','work.open':'Посмотреть проект',
        'work.p2.t':'Кейс в процессе','work.p2.d':'Готовлю следующий релиз: лендинг продукта/сайт услуг/магазин. Запросите концепции.',
        'process.title':'Как работаю','process.s1.t':'Бриф и структура','process.s1.d':'Цели, аудитории, карта страниц и тексты. Согласуем перед дизайном.',
        'process.s2.t':'Дизайн‑концепт','process.s2.d':'Система блоков и визуальные акценты. Сразу думаю об адаптиве.',
        'process.s3.t':'Сборка и интеграции','process.s3.d':'Верстка, анимации, формы, аналитика, CRM, пиксели.',
        'process.s4.t':'Запуск и поддержка','process.s4.d':'Публикация, техподдержка и развитие по задаче.',
        'testimonials.title':'Отзывы','faq.title':'FAQ','faq.q1.t':'Как формируется стоимость?','faq.q1.d':'Фиксируем объём и функционал, предлагаю 1–2 варианта бюджета под цели. Прозрачно и без скрытых пунктов.',
        'faq.q2.t':'Сроки?','faq.q2.d':'Зависят от контента и интеграций. Оцениваю реалистично и держу дедлайны.',
        'faq.q3.t':'Поддержка?','faq.q3.d':'Веду сайт на абонентской основе или передаю с инструкциями вашей команде.',
        'faq.q4.t':'Договор и оплата?','faq.q4.d':'Формализуем ТЗ и этапы. Предоплата и поэтапные платежи. Документы — по запросу.',
        'contact.title':'Связаться со мной','contact.phone':'Телефон:','contact.call':'Позвонить','contact.tg':'Написать в Telegram',
        'contact.name':'Имя','contact.name_ph':'Как к вам обращаться','contact.project':'Проект','contact.project_ph':'Лендинг / сайт услуг / магазин','contact.msg':'Сообщение','contact.msg_ph':'Пара предложений о задаче','contact.send':'Отправить в Telegram','contact.disclaimer':'Нажимая «Отправить», вы перейдёте в Telegram с готовым сообщением.',
        'footer.owner':'HIPWEB — разработчик сайтов','footer.portfolio':'Портфолио'
      },
      en: {
        'meta.title':'Arkhip — Web Developer | Portfolio',
        'meta.description':'Arkhip — web developer. Fast, responsive and modern websites tailored to business goals.',
        'skip':'Skip to content',
        'nav.brand':'HIPWEB','nav.services':'Services','nav.work':'Work','nav.process':'Process','nav.contact':'Contact',
        'hero.kicker':'Web Development',
        'hero.title':'I build websites that sell beautifully',
        'hero.cta1':'Discuss a project','hero.cta2':'View work',
        'hero.card.title':'Only what matters','hero.card.text':'No bloat. Clean architecture, readable code, friendly maintenance.',
        'services.title':'Services','services.s1.t':'Landing page','services.s1.d':'Structure, offer, tasteful motion, forms and integrations. From prototype to launch.',
        'services.s2.t':'Business website','services.s2.d':'Multi‑page site with blog, cases and team. Handy CMS and scalability.',
        'services.s3.t':'Online store','services.s3.d':'Catalog, product cards, cart and checkout. Fast loading and a clear purchase path.',
        'work.title':'Selected work','work.p1.d':'Beauty studio website: neat design, responsive layout, booking forms and SEO setup. Focused on clarity and conversions.',
        'work.p1.c1':'Responsive','work.p1.c2':'Forms / integrations','work.p1.c3':'SEO basics','work.open':'Open project',
        'work.p2.t':'Case in progress','work.p2.d':'Preparing the next release: product landing / services site / store. Ask for concepts.',
        'process.title':'How I work','process.s1.t':'Brief & structure','process.s1.d':'Goals, audiences, site map and copy. Align before design.',
        'process.s2.t':'Design concept','process.s2.d':'Block system and visual accents. Mobile‑first by default.',
        'process.s3.t':'Build & integrations','process.s3.d':'Markup, motion, forms, analytics, CRM, pixels.',
        'process.s4.t':'Launch & support','process.s4.d':'Deployment, maintenance and growth.',
        'testimonials.title':'Testimonials','faq.title':'FAQ','faq.q1.t':'How do you price?','faq.q1.d':'We lock the scope and functionality, then pick 1–2 budget options aligned to goals. Transparent and clear.',
        'faq.q2.t':'Timelines?','faq.q2.d':'Depends on content and integrations. I estimate realistically and meet deadlines.',
        'faq.q3.t':'Support?','faq.q3.d':'I can maintain it or hand off with documentation to your team.',
        'faq.q4.t':'Contract & payment?','faq.q4.d':'We formalize the scope and milestones. Prepayment and staged payments. Paperwork on request.',
        'contact.title':'Get in touch','contact.phone':'Phone:','contact.call':'Call','contact.tg':'Message on Telegram',
        'contact.name':'Name','contact.name_ph':'How to address you','contact.project':'Project','contact.project_ph':'Landing / services site / store','contact.msg':'Message','contact.msg_ph':'A couple of sentences about the task','contact.send':'Send to Telegram','contact.disclaimer':'You will be redirected to Telegram with a pre‑filled message.',
        'footer.owner':'Arkhip — Web Developer','footer.portfolio':'Portfolio'
      },
      uk: {
        'meta.title':'HIPWEB — розробник сайтів | Портфоліо',
        'meta.description':'HIPWEB — розробник сайтів. Швидкі, адаптивні та сучасні сайти під задачі бізнесу.',
        'skip':'До контенту',
        'nav.brand':'HIPWEB','nav.services':'Послуги','nav.work':'Роботи','nav.process':'Процес','nav.contact':'Контакти',
        'hero.kicker':'Веб‑розробка',
        'hero.title':'Створюю сайти, що красиво продають',
        'hero.cta1':'Обговорити проєкт','hero.cta2':'Переглянути роботи',
        'hero.card.title':'Лише необхідне','hero.card.text':'Без надлишкових бібліотек. Чиста архітектура, зрозумілий код і зручна підтримка.',
        'services.title':'Послуги','services.s1.t':'Лендінг','services.s1.d':'Структура, оффер, легкі анімації, форми та інтеграції. Від прототипу до запуску.',
        'services.s2.t':'Корпоративний сайт','services.s2.d':'Кілька сторінок, блог, кейси та команда. Зручна адмінка й масштабованість.',
        'services.s3.t':'Інтернет‑магазин','services.s3.d':'Каталог, картки, кошик і оплата. Швидке завантаження та простий шлях до покупки.',
        'work.title':'Обрані роботи','work.p1.d':'Сайт студії електроепіляції: акуратний дизайн, адаптив, форми запису та SEO‑підготовка. Акцент на простоті та конверсії.',
        'work.p1.c1':'Адаптив','work.p1.c2':'Форми / інтеграції','work.p1.c3':'SEO‑база','work.open':'Переглянути проєкт',
        'work.p2.t':'Кейс у процесі','work.p2.d':'Готую наступний реліз: лендінг продукту/сайт послуг/магазин. Запитайте концепції.',
        'process.title':'Як працюю','process.s1.t':'Бриф і структура','process.s1.d':'Цілі, аудиторії, карта сторінок і тексти. Узгодимо перед дизайном.',
        'process.s2.t':'Дизайн‑концепт','process.s2.d':'Система блоків і візуальні акценти. Одразу думаю про адаптив.',
        'process.s3.t':'Збірка та інтеграції','process.s3.d':'Верстка, анімації, форми, аналітика, CRM, пікселі.',
        'process.s4.t':'Запуск і підтримка','process.s4.d':'Публікація, техпідтримка та розвиток.',
        'testimonials.title':'Відгуки','faq.title':'Питання та відповіді','faq.q1.t':'Як формується вартість?','faq.q1.d':'Фіксуємо обсяг і функціонал, пропоную 1–2 варіанти бюджету під цілі. Прозоро та без прихованих пунктів.',
        'faq.q2.t':'Строки?','faq.q2.d':'Залежить від контенту та інтеграцій. Оцінюю реалістично і дотримуюся дедлайнів.',
        'faq.q3.t':'Підтримка?','faq.q3.d':'Можу супроводжувати або передати з документацією вашій команді.',
        'faq.q4.t':'Договір та оплата?','faq.q4.d':'Формалізуємо ТЗ і етапи. Передоплата та поетапні платежі. Документи — за запитом.',
        'contact.title':'Зв’язатися зі мною','contact.phone':'Телефон:','contact.call':'Подзвонити','contact.tg':'Написати в Telegram',
        'contact.name':'Ім’я','contact.name_ph':'Як до вас звертатися','contact.project':'Проєкт','contact.project_ph':'Лендінг / сайт послуг / магазин','contact.msg':'Повідомлення','contact.msg_ph':'Кілька речень про задачу','contact.send':'Надіслати в Telegram','contact.disclaimer':'Після відправки ви перейдете в Telegram з готовим повідомленням.',
        'footer.owner':'HIPWEB — розробник сайтів','footer.portfolio':'Портфоліо'
      }
    };

    // Prefs
    const LS_THEME = 'arkhip-theme';
    const LS_LANG = 'arkhip-lang';
    const root = document.documentElement;

    // Saved prefs
    const savedTheme = localStorage.getItem(LS_THEME);
    if(savedTheme){ root.setAttribute('data-theme', savedTheme); }
    const langSel = document.getElementById('lang');
    let lang = localStorage.getItem(LS_LANG) || 'ru';
    langSel.value = lang;

    function applyI18n(){
      const dict = DICT[lang];
      // text
      document.querySelectorAll('[data-i18n]').forEach(el=>{
        const key = el.getAttribute('data-i18n');
        if(dict[key] !== undefined) el.innerHTML = dict[key];
      });
      // attributes
      document.querySelectorAll('[data-i18n-attr]').forEach(el=>{
        const pairs = el.getAttribute('data-i18n-attr').split(',');
        pairs.forEach(p=>{
          const [attr, k] = p.split(':');
          if(DICT[lang][k] !== undefined) el.setAttribute(attr, DICT[lang][k]);
        });
      });
      // html lang & og:locale
      document.documentElement.lang = lang;
      document.getElementById('ogLocale').setAttribute('content', lang==='en'?'en_US':(lang==='uk'?'uk_UA':'ru_RU'));
      document.title = dict['meta.title'] || document.title;
    }

    // Language switch
    langSel.addEventListener('change', ()=>{
      lang = langSel.value;
      localStorage.setItem(LS_LANG, lang);
      applyI18n();
    });
    applyI18n();

    // Mobile menu
    const burger = document.getElementById('hamburger');
    const mobile = document.getElementById('mobileMenu');
    burger?.addEventListener('click', ()=>{
      mobile.style.display = mobile.style.display === 'flex' ? 'none' : 'flex';
    });

    // Theme toggle
    document.getElementById('themeToggle').addEventListener('click', ()=>{
      const next = (root.getAttribute('data-theme')||'dark') === 'dark' ? 'light' : 'dark';
      root.setAttribute('data-theme', next);
      localStorage.setItem(LS_THEME, next);
    });

    // Reveal on scroll
    const observer = new IntersectionObserver((entries)=>{
      entries.forEach(e=>{ if(e.isIntersecting){ e.target.classList.add('in'); observer.unobserve(e.target);} });
    }, {threshold:.18});
    document.querySelectorAll('.reveal').forEach(el=>observer.observe(el));

    // Year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Brief -> Telegram
    document.getElementById('brief').addEventListener('submit', (e)=>{
      e.preventDefault();
      const data = new FormData(e.target);
      const name = (data.get('name')||'').toString().trim();
      const project = (data.get('project')||'').toString().trim();
      const msg = (data.get('message')||'').toString().trim();
      const brand = DICT[lang]['nav.brand'] || 'HIPWEB';
      const text = `${brand}, привет! Меня зовут ${name}. Проект: ${project}. ${msg?('Комментарий: '+msg):''}`.trim();
      const url = 'https://t.me/arkhip7_7_7?text=' + encodeURIComponent(text);
      window.open(url, '_blank', 'noopener');
    });

    // Copy phone
    document.getElementById('copyPhone').addEventListener('click', async ()=>{
      try{
        await navigator.clipboard.writeText('+380682749391');
        alert(lang==='en'?'Copied!':'Скопировано!');
      }catch(e){ console.log(e); }
    });

    // To top
    document.getElementById('toTop').addEventListener('click', ()=>{
      window.scrollTo({top:0,behavior:'smooth'});
    });

    // Shortcuts
    window.addEventListener('keydown',(e)=>{
      if(e.key.toLowerCase()==='t') document.getElementById('themeToggle').click();
      if(e.key.toLowerCase()==='l') langSel.focus();
      if(e.key.toLowerCase()==='g') location.hash = '#contact';
    });
  </script>

<button id="backToTop" style="position:fixed;bottom:30px;right:30px;padding:12px 16px;
  border-radius:50%;border:none;background:#3498db;color:#fff;font-size:20px;cursor:pointer;
  box-shadow:0 4px 10px rgba(0,0,0,0.3);display:none;z-index:1000;">↑</button>


<script>

document.addEventListener("DOMContentLoaded",()=>{
  const els=document.querySelectorAll(".fade-in");
  const obs=new IntersectionObserver(entries=>{
    entries.forEach(e=>{if(e.isIntersecting){e.target.classList.add("show");obs.unobserve(e.target);}});
  },{threshold:0.2});
  els.forEach(el=>obs.observe(el));
});


const topBtn = document.getElementById("backToTop");
window.addEventListener("scroll",()=>{
  if(window.scrollY>300){topBtn.style.display="block";}else{topBtn.style.display="none";}
});
topBtn.addEventListener("click",()=>{window.scrollTo({top:0,behavior:"smooth"});});


// Counter animation
function animateCounters() {
  const counters = document.querySelectorAll('.counter');
  counters.forEach(counter => {
    const target = +counter.getAttribute('data-target');
    const update = () => {
      const current = +counter.innerText;
      const increment = Math.ceil(target / 100);
      if (current < target) {
        counter.innerText = current + increment;
        setTimeout(update, 20);
      } else {
        counter.innerText = target;
      }
    };
    update();
  });
}

// Запуск при появлении блока
document.addEventListener('DOMContentLoaded', () => {
  const stats = document.querySelector('.stats');
  if (stats) {
    const observer = new IntersectionObserver((entries) => {
      if (entries[0].isIntersecting) {
        animateCounters();
        observer.disconnect();
      }
    }, { threshold: 0.5 });
    observer.observe(stats);
  }
});

</script>
</body>
</html>

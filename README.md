# higgs111.github.io
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Higwira Anselm Junior | Law Graduate</title>
<meta name="description" content="Higwira Anselm Junior - Bachelor of Laws graduate (Makerere University) with experience in legal research, court procedures, data management and client service. Based in Kampala, Uganda.">
<meta property="og:title" content="Higwira Anselm Junior | Law Graduate">
<meta property="og:description" content="Bachelor of Laws graduate with experience in legal research, court procedures and data management.">
<meta name="theme-color" content="#1f2a3d">
<style>
  :root{
    --bg:#f6f7fa; --surface:#ffffff; --ink:#1f2a3d; --muted:#5b667a; --line:#e2e6ee;
    --navy:#2f3b52; --navy2:#1f2a3d; --accent:#c8963e; --accent-soft:#f6ecd9; --radius:16px;
  }
  *{box-sizing:border-box;margin:0;padding:0}
  html{scroll-behavior:smooth}
  body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;background:var(--bg);color:var(--ink);line-height:1.65}
  a{color:inherit;text-decoration:none}
  .wrap{max-width:1040px;margin:0 auto;padding:0 20px}
  h1,h2,h3,.logo{font-family:Georgia,"Times New Roman",serif}
  :root{--navbg:rgba(255,255,255,.92)}
  :root[data-theme="dark"]{
    --bg:#0e1522; --surface:#151f31; --ink:#e9edf5; --muted:#a3aec4; --line:#25324a;
    --accent-soft:#2a2314; --navbg:rgba(14,21,34,.92);
  }
  :root[data-theme="dark"] .facts b{color:var(--accent)}
  :root[data-theme="dark"] .facts li{border-bottom-color:#43381f}
  :root[data-theme="dark"] .social .card .btn{color:var(--ink);border-color:var(--line)}
  :root[data-theme="dark"] .social .card .btn.primary{background:var(--accent);color:#2a1d05;border-color:var(--accent)}
  :root[data-theme="dark"] .badge-slot .badge-base__link{color:var(--accent)}
  .tagline{font-family:Georgia,"Times New Roman",serif;font-style:italic;font-size:1.25rem;color:var(--accent);margin-bottom:14px}
  .theme-btn{background:none;border:1px solid var(--line);color:var(--ink);width:36px;height:36px;border-radius:50%;cursor:pointer;font-size:1rem;line-height:1}
  .theme-btn:hover{border-color:var(--accent)}
  nav .right{display:flex;align-items:center;gap:16px}
  .js .reveal{opacity:0;transform:translateY(24px);transition:opacity .7s ease,transform .7s ease}
  .js .reveal.in{opacity:1;transform:none}
  @media(prefers-reduced-motion:reduce){.js .reveal{opacity:1;transform:none;transition:none}html{scroll-behavior:auto}}

  /* NAV */
  nav{position:sticky;top:0;z-index:10;background:var(--navbg);backdrop-filter:blur(10px);border-bottom:1px solid var(--line)}
  nav .wrap{display:flex;align-items:center;justify-content:space-between;height:60px}
  .logo{font-weight:800;letter-spacing:.3px}
  .logo span{color:var(--accent)}
  nav ul{display:flex;gap:20px;list-style:none;font-size:.92rem;color:var(--muted)}
  nav ul a:hover{color:var(--ink)}

  /* HERO */
  .hero{background:linear-gradient(135deg,var(--navy2),var(--navy));color:#fff;padding:70px 0 80px}
  .hero .wrap{display:grid;gap:36px;align-items:center;grid-template-columns:1fr}
  @media(min-width:800px){.hero .wrap{grid-template-columns:1.5fr 1fr}}
  .tag{display:inline-block;font-size:.8rem;letter-spacing:1.5px;text-transform:uppercase;color:var(--accent);border:1px solid var(--accent);padding:5px 14px;border-radius:99px;margin-bottom:18px}
  .hero h1{font-size:clamp(2.1rem,6vw,3.5rem);line-height:1.1;margin-bottom:16px}
  .hero h1 span{color:var(--accent)}
  .hero p{color:#cfd6e4;font-size:1.08rem;max-width:560px;margin-bottom:28px}
  .btns{display:flex;gap:12px;flex-wrap:wrap}
  .btn{padding:12px 22px;border-radius:12px;font-weight:600;font-size:.95rem;border:1px solid rgba(255,255,255,.35);transition:.2s}
  .btn.primary{background:var(--accent);color:#2a1d05;border-color:var(--accent)}
  .btn:hover{transform:translateY(-2px)}
  .photo{justify-self:center}
  .photo img{width:240px;height:240px;object-fit:cover;border-radius:50%;border:5px solid var(--accent);box-shadow:0 20px 50px rgba(0,0,0,.35);background:#fff}
  @media(min-width:800px){.photo{justify-self:end}.photo img{width:290px;height:290px}}

  /* SECTIONS */
  section{padding:70px 0}
  section.alt{background:var(--surface);border-top:1px solid var(--line);border-bottom:1px solid var(--line)}
  h2{font-size:1.7rem;margin-bottom:8px}
  h2::after{content:"";display:block;width:48px;height:4px;border-radius:4px;background:var(--accent);margin-top:10px}
  .lead{color:var(--muted);margin:18px 0 28px;max-width:720px}
  .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:18px}
  .card{background:var(--surface);border:1px solid var(--line);border-radius:var(--radius);padding:24px;box-shadow:0 2px 10px rgba(31,42,61,.04)}
  .card h3{margin-bottom:8px;font-size:1.08rem}
  .card p{color:var(--muted);font-size:.95rem}
  .card .icon{font-size:1.7rem;margin-bottom:10px}

  /* ABOUT */
  .about{display:grid;grid-template-columns:1fr;gap:28px}
  @media(min-width:800px){.about{grid-template-columns:1.8fr 1fr}}
  .about p{color:var(--muted);margin-bottom:14px}
  .facts{background:var(--accent-soft);border-radius:var(--radius);padding:22px;list-style:none;height:fit-content}
  .facts li{padding:9px 0;border-bottom:1px dashed #e3cf9f;font-size:.95rem}
  .facts li:last-child{border:none}
  .facts b{display:block;color:#8a6420;font-size:.72rem;text-transform:uppercase;letter-spacing:1px}

  /* TIMELINE */
  .timeline{border-left:2px solid var(--line);margin-left:6px}
  .item{position:relative;padding:0 0 28px 26px}
  .item::before{content:"";position:absolute;left:-7px;top:7px;width:12px;height:12px;border-radius:50%;background:var(--accent);box-shadow:0 0 0 4px var(--bg)}
  section.alt .item::before{box-shadow:0 0 0 4px var(--surface)}
  .item .when{font-size:.8rem;color:var(--accent);font-weight:700;letter-spacing:1px;text-transform:uppercase}
  .item h3{margin:3px 0 1px;font-size:1.08rem}
  .item .org{color:var(--muted);font-size:.95rem}
  .two{display:grid;gap:40px;grid-template-columns:1fr}
  @media(min-width:860px){.two{grid-template-columns:1fr 1fr}}

  /* SKILLS */
  .chips{display:flex;flex-wrap:wrap;gap:10px}
  .chip{background:var(--surface);border:1px solid var(--line);padding:8px 16px;border-radius:99px;font-size:.9rem}
  .sub{font-size:1rem;margin:26px 0 12px;color:var(--navy)}

  /* CERTS */
  .cert{display:flex;justify-content:space-between;gap:14px;padding:14px 0;border-bottom:1px solid var(--line)}
  .cert:last-child{border:none}
  .cert b{display:block}
  .cert span{color:var(--muted);font-size:.93rem}
  .cert time{color:var(--accent);font-weight:700;font-size:.85rem;white-space:nowrap}

  /* SOCIAL */
  .social{display:grid;gap:22px;grid-template-columns:1fr}
  @media(min-width:800px){.social{grid-template-columns:1fr 1fr}}
  .social .card{display:flex;flex-direction:column;gap:12px}
  .social .card .btn{align-self:flex-start;border-color:var(--navy);color:var(--navy);font-size:.9rem;padding:10px 18px}
  .social .card .btn.primary{background:var(--navy);color:#fff}
  .badge-slot{min-height:60px}
  .badge-slot .badge-base__link{color:var(--navy);font-weight:600;text-decoration:underline}
  .ig-handle{display:flex;align-items:center;gap:12px}
  .ig-dot{width:46px;height:46px;border-radius:50%;background:linear-gradient(45deg,#f9a03f,#e1306c,#6b4fbb);display:grid;place-items:center;color:#fff;font-weight:800}
  #igPosts{display:grid;gap:18px;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));margin-top:22px}
  #igPosts:empty{display:none}
  #igPosts .instagram-media{margin:0 auto!important;min-width:260px!important}

  /* CONTACT */
  .contact-list{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:14px;margin-top:10px}
  .contact-list a{background:var(--surface);border:1px solid var(--line);border-radius:var(--radius);padding:18px 20px;display:block;transition:.2s;word-break:break-word}
  .contact-list a:hover{border-color:var(--accent);transform:translateY(-3px)}
  .contact-list small{display:block;color:var(--muted);font-size:.74rem;text-transform:uppercase;letter-spacing:1px;margin-bottom:2px}
  footer{padding:30px 0;text-align:center;color:var(--muted);font-size:.85rem;border-top:1px solid var(--line)}
  @media(max-width:620px){nav ul{gap:12px;font-size:.82rem;overflow-x:auto;white-space:nowrap;max-width:52vw;scrollbar-width:none}nav ul::-webkit-scrollbar{display:none}.logo{font-size:.95rem;white-space:nowrap}.hero{padding:50px 0 60px}}
</style>
</head>
<body>

<nav>
  <div class="wrap">
    <a href="#top" class="logo">H<span>.</span>Anselm Junior</a>
    <div class="right">
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#experience">Experience</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#social">Social</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <button class="theme-btn" id="themeBtn" aria-label="Switch between light and dark mode" title="Light / dark">&#9680;</button>
    </div>
  </div>
</nav>

<!-- HERO -->
<header class="hero" id="top">
  <div class="wrap">
    <div>
      <span class="tag">Bachelor of Laws (Hons) &middot; Makerere University</span>
      <h1>Higwira <span>Anselm</span> Junior</h1>
      <div class="tagline">Careful with facts. Clear in thought. Steady in practice.</div>
      <p>Law graduate with hands-on experience in legal research, court procedures, data management and client service. Adaptable, detail-oriented and committed to continuous professional growth.</p>
      <div class="btns">
        <a class="btn primary" href="#contact">Get in touch</a>
        <a class="btn" href="https://www.linkedin.com/in/higwira-anselm-220025217" target="_blank" rel="noopener">LinkedIn</a>
        <a class="btn" href="https://www.instagram.com/jranselm" target="_blank" rel="noopener">Instagram</a>
      </div>
    </div>
    <div class="photo"><img src="data:image/jpeg;base64,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" alt="Portrait of Higwira Anselm Junior"></div>
  </div>
</header>

<!-- ABOUT -->
<section id="about">
  <div class="wrap">
    <h2>About Me</h2>
    <div class="about">
      <div>
        <p class="lead" style="margin-bottom:14px">I am a highly adaptable, fast-learning Bachelor of Laws graduate with experience in legal research, court procedures and client service. I am skilled in data organization, transcription and Microsoft Office, with strong problem-solving abilities and close attention to detail.</p>
        <p>I work well both independently and collaboratively in dynamic environments. I am committed to continuous learning and professional growth, with certifications in intellectual property and commercial law.</p>
      </div>
      <ul class="facts">
        <li><b>Based in</b>Wakiso District, Uganda</li>
        <li><b>Degree</b>LLB (Hons), Makerere University (2022-2026)</li>
        <li><b>Languages</b>English (Fluent), Luganda (Fluent), Lunyole (Basic)</li>
        <li><b>Interests</b>Intellectual property, commercial law, data</li>
      </ul>
    </div>
  </div>
</section>

<!-- WHAT I OFFER -->
<section class="alt" id="offer">
  <div class="wrap">
    <h2>Focus Areas</h2>
    <p class="lead">Where my legal training, certifications and hands-on experience come together.</p>
    <div class="grid">
      <div class="card"><div class="icon">⚖️</div><h3>Legal Research &amp; Court Procedure</h3><p>Practical exposure to the Chief Magistrates Court in Mpigi, plus certified simulations in intellectual property litigation and UK commercial law.</p></div>
      <div class="card"><div class="icon">🗂️</div><h3>Data Management &amp; Entry</h3><p>Accurate data entry, organization and transcription for national institutions, including the Uganda National Examinations Board and the Electoral Commission.</p></div>
      <div class="card"><div class="icon">🤝</div><h3>Client Service &amp; Communication</h3><p>Clear, courteous communication built through retail, hospitality and public-sector service roles.</p></div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience">
  <div class="wrap">
    <h2>Work Experience</h2>
    <p class="lead">Roles across the justice, electoral, education and service sectors.</p>
    <div class="timeline">
      <div class="item"><div class="when">2025 - 2026</div><h3>Data Entrant</h3><div class="org">Uganda National Examinations Board</div></div>
      <div class="item"><div class="when">2025</div><h3>Intern &amp; Data Entrant</h3><div class="org">Electoral Commission</div></div>
      <div class="item"><div class="when">2024</div><h3>Intern</h3><div class="org">Chief Magistrates Court of Uganda, Mpigi</div></div>
      <div class="item"><div class="when">2020</div><h3>Retail Sales Associate</h3><div class="org">Smart Shoppers Supermarket</div></div>
      <div class="item"><div class="when">2019</div><h3>Volunteer</h3><div class="org">Pearl Highway Hotel</div></div>
    </div>
  </div>
</section>

<!-- EDUCATION + SKILLS -->
<section class="alt" id="education">
  <div class="wrap two">
    <div>
      <h2>Education</h2>
      <div class="timeline" style="margin-top:28px">
        <div class="item"><div class="when">2022 - 2026</div><h3>Bachelor of Laws (Hons)</h3><div class="org">School of Law, Makerere University, Kampala</div></div>
        <div class="item"><div class="when">2019 - 2020</div><h3>Uganda Advanced Certificate of Education (UACE)</h3><div class="org">Butalejja Secondary School</div></div>
        <div class="item"><div class="when">2015 - 2018</div><h3>Uganda Certificate of Education (UCE)</h3><div class="org">St. Joseph's Senior Secondary School, Naggalama</div></div>
        <div class="item"><div class="when">2008 - 2014</div><h3>Primary Leaving Certificate (PLE)</h3><div class="org">Mother Kevin Memorial Primary School, Nsambya</div></div>
      </div>
    </div>
    <div>
      <h2>Skills</h2>
      <h3 class="sub" style="margin-top:28px">Core strengths</h3>
      <div class="chips">
        <span class="chip">Data management</span><span class="chip">Transcription</span><span class="chip">Microsoft Office</span>
        <span class="chip">Teamwork</span><span class="chip">Time management</span><span class="chip">Leadership</span>
        <span class="chip">Effective communication</span><span class="chip">Critical thinking</span><span class="chip">Problem-solving</span>
      </div>
      <h3 class="sub">Languages</h3>
      <div class="chips">
        <span class="chip">English &middot; Fluent</span><span class="chip">Luganda &middot; Fluent</span><span class="chip">Lunyole &middot; Basic</span>
      </div>
    </div>
  </div>
</section>

<!-- CERTIFICATIONS -->
<section id="certifications">
  <div class="wrap">
    <h2>Certifications</h2>
    <p class="lead">Professional training and simulations alongside my degree.</p>
    <div class="card" style="padding:8px 24px">
      <div class="cert"><div><b>Latham &amp; Watkins</b><span>Intellectual Property Litigation Simulation</span></div><time>2025</time></div>
      <div class="cert"><div><b>Clyde &amp; Co</b><span>UK Commercial Law Simulation</span></div><time>2025</time></div>
      <div class="cert"><div><b>Open University</b><span>Introducing International Relations</span></div><time>2025</time></div>
      <div class="cert"><div><b>HP Life</b><span>Cybersecurity Awareness &middot; Effective Presentations &middot; Data Science &amp; Analytics &middot; Effective Leadership</span></div><time>2025</time></div>
      <div class="cert"><div><b>Junior Achievers Africa</b><span>JA Digital Entrepreneurship Education Program (JA DEEP)</span></div><time>2024</time></div>
      <div class="cert"><div><b>Joint Aviation and Space Program</b><span>Aviation and Space Science</span></div><time>2016</time></div>
      <div class="cert"><div><b>Uganda Red Cross Society</b><span>Annual Youth Forum</span></div><time>2015</time></div>
      <div class="cert"><div><b>Lugazi Diocese Department of Education</b><span>Leadership for Justice, Peace and Development</span></div><time>2015</time></div>
    </div>
  </div>
</section>

<!-- SOCIAL -->
<section class="alt" id="social">
  <div class="wrap">
    <h2>Find Me Online</h2>
    <p class="lead">My professional network and day-to-day updates live on these profiles.</p>
    <div class="social">
      <div class="card">
        <h3>LinkedIn</h3>
        <p>Career history, recommendations and professional updates.</p>
        <div class="badge-slot">
          <script src="https://platform.linkedin.com/badges/js/profile.js" async defer type="text/javascript"></script>
          <div class="badge-base LI-profile-badge" data-locale="en_US" data-size="medium" data-theme="light" data-type="VERTICAL" data-vanity="higwira-anselm-220025217" data-version="v1"><a class="badge-base__link LI-simple-link" href="https://www.linkedin.com/in/higwira-anselm-220025217?trk=profile-badge" target="_blank" rel="noopener">Higwira Anselm on LinkedIn</a></div>
        </div>
        <a class="btn primary" href="https://www.linkedin.com/in/higwira-anselm-220025217" target="_blank" rel="noopener">Connect on LinkedIn</a>
      </div>
      <div class="card">
        <h3>Instagram</h3>
        <div class="ig-handle"><div class="ig-dot">J</div><div><b>@jranselm</b><p style="margin:0">Life, moments and updates</p></div></div>
        <p>Follow along for a more personal look at what I'm up to.</p>
        <a class="btn primary" href="https://www.instagram.com/jranselm" target="_blank" rel="noopener">Follow on Instagram</a>
      </div>
    </div>
    <!-- Add Instagram post links in the INSTAGRAM_POSTS list at the bottom of this file to show them here -->
    <div id="igPosts"></div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="wrap">
    <h2>Let's Connect</h2>
    <p class="lead">Open to opportunities, collaborations and conversations. Reach out through any of the channels below.</p>
    <div class="contact-list">
      <a href="mailto:junioranselmh@gmail.com"><small>Email</small>junioranselmh@gmail.com</a>
      <a href="tel:+256706306196"><small>Phone</small>+256 706 306 196</a>
      <a href="https://www.linkedin.com/in/higwira-anselm-220025217" target="_blank" rel="noopener"><small>LinkedIn</small>Higwira Anselm</a>
      <a href="https://www.instagram.com/jranselm" target="_blank" rel="noopener"><small>Instagram</small>@jranselm</a>
    </div>
  </div>
</section>

<footer>
  <div class="wrap">&copy; <span id="y"></span> Higwira Anselm Junior. All rights reserved.</div>
</footer>
<script>
document.getElementById('y').textContent=new Date().getFullYear();

/* Light / dark theme (remembers the choice when the browser allows it) */
(function(){
  var root=document.documentElement, saved=null;
  try{saved=localStorage.getItem('theme');}catch(e){}
  if(!saved && window.matchMedia && matchMedia('(prefers-color-scheme: dark)').matches) saved='dark';
  if(saved==='dark') root.setAttribute('data-theme','dark');
  document.getElementById('themeBtn').addEventListener('click',function(){
    var next=root.getAttribute('data-theme')==='dark'?'light':'dark';
    if(next==='dark') root.setAttribute('data-theme','dark'); else root.removeAttribute('data-theme');
    try{localStorage.setItem('theme',next);}catch(e){}
  });
})();

/* Scroll reveal */
(function(){
  if(!('IntersectionObserver' in window)) return;
  var root=document.documentElement; root.classList.add('js');
  var els=document.querySelectorAll('section .wrap > *, .hero .wrap > *');
  var io=new IntersectionObserver(function(es){
    es.forEach(function(e){ if(e.isIntersecting){ e.target.classList.add('in'); io.unobserve(e.target);} });
  },{threshold:.08});
  els.forEach(function(el){ el.classList.add('reveal'); io.observe(el); });
})();

/* To show Instagram posts on the site, paste their links here, e.g.
   const INSTAGRAM_POSTS = ["https://www.instagram.com/p/XXXXXXXX/", "https://www.instagram.com/p/YYYYYYYY/"]; */
const INSTAGRAM_POSTS = [];

(function(){
  if(!INSTAGRAM_POSTS.length) return;
  var box=document.getElementById('igPosts');
  INSTAGRAM_POSTS.forEach(function(u){
    var bq=document.createElement('blockquote');
    bq.className='instagram-media';
    bq.setAttribute('data-instgrm-permalink',u);
    bq.setAttribute('data-instgrm-version','14');
    box.appendChild(bq);
  });
  var s=document.createElement('script');
  s.async=true; s.src='https://www.instagram.com/embed.js';
  document.body.appendChild(s);
})();
</script>
</body>
</html>

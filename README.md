html<html><head><meta charset="utf-8"/><meta content="width=device-width,initial-scale=1,viewport-fit=cover" name="viewport"/><style>:root{color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}html{scroll-padding-top:env(safe-area-inset-top,0px)}body{margin:0;padding:0;font:14px -apple-system,BlinkMacSystemFont,sans-serif;background:#fff;color:#000}img{max-width:100%}[hidden]:not([hidden=until-found i]){display:none!important}
/* Refined uppercase portfolio branding */
.logo, .brand, .site-title, .navbar-brand, .header-brand {
  letter-spacing: .14em;
  font-weight: 800;
  text-transform: uppercase;
  line-height: 1.1;
}
.logo, .brand, .site-title, .navbar-brand, .header-brand {
  text-shadow: 0 2px 18px rgba(59, 130, 246, .18);
}

</style>
<style>
/* Visual refresh: stronger navigation, clearer hero identity and more discoverable contact choices. */
.nav { backdrop-filter: blur(18px); -webkit-backdrop-filter: blur(18px); background: rgba(7, 15, 36, .92); border-bottom: 1px solid rgba(255,255,255,.12); box-shadow: 0 10px 35px rgba(0,0,0,.16); }
.nav .bar { gap: 18px; }
.nav .mark { display:inline-flex; align-items:center; gap:10px; padding:9px 13px 9px 9px; border:1px solid rgba(255,255,255,.14); border-radius:16px; background:linear-gradient(135deg,rgba(255,255,255,.1),rgba(255,255,255,.025)); color:#fff; text-decoration:none; }
.nav .mark .avatar { box-shadow:0 0 0 2px rgba(255,208,77,.8); }
.nav .links { padding:7px; gap:4px; border:1px solid rgba(255,255,255,.12); border-radius:999px; background:rgba(255,255,255,.045); }
.nav .links a { padding:10px 12px; border-radius:999px; font-size:13px; transition:background .2s ease,color .2s ease,transform .2s ease; }
.nav .links a:hover, .nav .links a:focus-visible { background:rgba(255,208,77,.16); color:#ffd04d; transform:translateY(-1px); }
.nav .tools { display:flex; align-items:center; gap:10px; }
.nav .hire-btn { box-shadow:0 7px 22px rgba(242,161,0,.2); }
.hero-kicker { display:inline-flex; align-items:center; gap:9px; padding:9px 13px; border:1px solid rgba(255,208,77,.3); border-radius:999px; background:rgba(255,208,77,.075); color:#ffe19a!important; letter-spacing:.12em; font-size:11px!important; }
.kicker-dot,.role-live-dot { display:inline-block; width:7px; height:7px; flex:0 0 7px; border-radius:50%; background:#57e5b5; box-shadow:0 0 0 4px rgba(87,229,181,.12),0 0 15px rgba(87,229,181,.5); }
.hero h1 { max-width:760px; letter-spacing:-.055em; line-height:.99; }
.hero h1 em { display:inline-block; background:linear-gradient(100deg,#ffd04d 4%,#ff9b77 48%,#7fe5d4 100%); -webkit-background-clip:text; background-clip:text; color:transparent; font-style:normal; }
.hero-role-line { display:flex; align-items:center; flex-wrap:wrap; gap:9px; margin:20px 0 12px; color:#f4f7ff; font-size:clamp(15px,2vw,19px); font-weight:700; }
.role-mark { color:#ffd04d; font-size:21px; }
.role-divider { color:rgba(255,255,255,.35); }
.hero .lead { max-width:600px; }
.hero .tags li { border:1px solid rgba(255,255,255,.15); background:rgba(255,255,255,.055); border-radius:999px; padding:8px 13px; }
.hero .actions .btn { border-radius:13px; padding:13px 20px; }
.role-showcase { width:min(100%,400px); padding:19px 20px 17px; border:1px solid rgba(255,255,255,.16); border-radius:20px; background:linear-gradient(145deg,rgba(255,255,255,.105),rgba(255,255,255,.035)); box-shadow:0 18px 48px rgba(0,0,0,.2),inset 0 1px rgba(255,255,255,.09); }
.role-showcase-top { display:flex; align-items:center; gap:9px; color:#aebbd5; font:10px/1.4 var(--font-mono); letter-spacing:.16em; }
.role-showcase-line { height:1px; flex:1; background:linear-gradient(90deg,rgba(255,208,77,.55),transparent); }
.role-showcase .roles { text-align:left; min-height:1.25em; margin:15px 0 16px; font-size:clamp(1.55rem,3vw,2rem); }
.role-showcase .roles .typed { background:linear-gradient(90deg,#ffd04d,#ff9b77); -webkit-background-clip:text; background-clip:text; color:transparent; }
.role-pills { display:flex; flex-wrap:wrap; gap:7px; }
.role-pills span { padding:7px 10px; border-radius:8px; color:#e2e9fa; background:rgba(5,12,29,.42); border:1px solid rgba(255,255,255,.1); font-size:11px; }
.contact .section-head { max-width:760px; }
.contact .section-head h2 { font-size:clamp(2.2rem,5vw,4.2rem); letter-spacing:-.045em; }
.contact-grid { gap:26px; }
.c-stack { gap:16px; }
.c-card { border-radius:20px; background:linear-gradient(145deg,rgba(255,255,255,.095),rgba(255,255,255,.035)); border-color:rgba(255,255,255,.16); box-shadow:0 14px 34px rgba(0,0,0,.12); transition:transform .22s ease,border-color .22s ease,background .22s ease; }
.c-card:hover { transform:translateY(-3px); border-color:rgba(255,208,77,.42); }
.contact-highlight { background:linear-gradient(135deg,rgba(255,208,77,.15),rgba(16,165,150,.08)); }
.contact-highlight h3 { font-size:1.5rem; }
.contact-options-card { padding:22px; border:1px solid rgba(255,255,255,.18); border-radius:20px; background:linear-gradient(145deg,rgba(18,35,72,.94),rgba(8,18,42,.95)); box-shadow:0 18px 40px rgba(0,0,0,.18); }
.contact-options-heading { display:flex; align-items:center; gap:13px; margin-bottom:18px; }
.contact-options-icon { display:grid; place-items:center; width:42px; height:42px; border-radius:13px; background:linear-gradient(135deg,#ffd04d,#ff9b77); color:#111a2f; font-size:22px; }
.contact-options-heading .label { margin:0 0 3px; }
.contact-options-heading h3 { color:#fff; margin:0; font-size:1.2rem; }
.contact-option-grid { display:grid; grid-template-columns:1fr 1fr; gap:10px; }
.contact-option { display:flex; align-items:center; gap:10px; min-width:0; padding:13px 10px; text-align:left; border:1px solid rgba(255,255,255,.12); border-radius:13px; color:#fff; background:rgba(255,255,255,.045); cursor:pointer; transition:transform .18s ease,border-color .18s ease,background .18s ease; }
.contact-option:hover,.contact-option:focus-visible { transform:translateY(-2px); border-color:rgba(255,208,77,.6); background:rgba(255,208,77,.08); }
.option-symbol { display:grid; place-items:center; width:32px; height:32px; flex:0 0 32px; border-radius:10px; color:#ffd04d; background:rgba(255,208,77,.11); font-size:18px; }
.contact-option b { display:block; font-size:12px; line-height:1.35; }
.contact-option small { display:block; margin-top:4px; color:#aebbd5; font-size:10px; line-height:1.35; }
.option-arrow { margin-left:auto; color:#ffd04d; font-size:16px; }
.contact-options-foot { margin:14px 0 0; color:#aebbd5; font-size:11px; }
form.c-card { gap:16px; }
form.c-card input,form.c-card textarea,form.c-card select { border-radius:11px; border:1px solid rgba(255,255,255,.17); background:rgba(4,12,30,.5); color:#fff; }
form.c-card input:focus,form.c-card textarea:focus,form.c-card select:focus { outline:2px solid rgba(255,208,77,.35); border-color:#ffd04d; }
form.c-card select option { color:#111; }
.form-spark { color:#ffd04d; }
@media (max-width:1000px) { .nav .links { gap:1px; } .nav .links a { padding:9px 8px; font-size:12px; } .nav .mark { font-size:12px; } }
@media (max-width:780px) {
 .nav .bar { gap:10px; }
 .nav .mark { padding:7px 10px 7px 7px; }
 .nav .links { border-radius:16px; padding:9px; background:rgba(8,18,42,.98); box-shadow:0 20px 45px rgba(0,0,0,.25); }
 .nav .links a { padding:12px 13px; font-size:14px; }
 .nav .tools .hire-btn { padding:10px 13px; font-size:12px; }
 .hero .wrap { gap:35px; }
 .hero-role-line { line-height:1.45; }
 .role-showcase { padding:17px; }
 .contact-grid { grid-template-columns:minmax(0,1fr); }
 .contact-option-grid { grid-template-columns:1fr 1fr; }
}
@media (max-width:420px) { .contact-option-grid { grid-template-columns:1fr; } .contact-options-card { padding:16px; } .hero-kicker { font-size:9px!important; letter-spacing:.08em; } }
@media (prefers-reduced-motion: reduce) { .c-card,.contact-option,.nav .links a { transition:none; } }
</style>
<style>
/* FINAL DESIGN PASS — data science editorial / analytics dashboard aesthetic */
:root{--navy:#071426;--navy-deep:#030b17;--blue:#5b8cff;--teal:#36e0c0;--amber:#ffca73;--coral:#ff806f;--radius-xl:28px}
html{scroll-behavior:smooth;scroll-padding-top:94px}
body{background:#f5f8fc;color:#15233b;letter-spacing:.005em}
::selection{background:#36e0c055;color:#071426}
.nav,header.nav{background:rgba(5,16,34,.88)!important;border:1px solid rgba(255,255,255,.1)!important;box-shadow:0 12px 40px #07142625!important;border-radius:0 0 22px 22px!important;backdrop-filter:blur(20px)!important}
.nav a,.nav button{transition:color .2s ease,background .2s ease,transform .2s ease}
.nav a:hover,.nav button:hover{color:#36e0c0!important;transform:translateY(-1px)}
.mark,.logo,.brand,.site-title,.navbar-brand{letter-spacing:.11em!important}
.hero{position:relative;overflow:hidden;background:radial-gradient(ellipse at 82% 18%,#1c4b73 0%,transparent 38%),radial-gradient(ellipse at 10% 90%,#123c4a 0%,transparent 42%),linear-gradient(130deg,#030b17 0%,#071a32 55%,#0b2540 100%)!important;color:#f4f8ff!important;min-height:660px;padding-top:clamp(76px,9vw,124px)!important;padding-bottom:78px!important}
.hero:before{content:"";position:absolute;inset:0;background-image:linear-gradient(#ffffff08 1px,transparent 1px),linear-gradient(90deg,#ffffff08 1px,transparent 1px);background-size:42px 42px;mask-image:linear-gradient(to bottom,#000,transparent 92%);pointer-events:none}
.hero .wrap{position:relative;z-index:1;gap:clamp(34px,6vw,90px)!important;align-items:center!important}
.hero h1{font-size:clamp(3.2rem,7vw,6.4rem)!important;line-height:.98!important;letter-spacing:-.065em!important;max-width:850px;text-wrap:balance}
.hero h1 em{color:#36e0c0!important;font-style:normal;text-shadow:0 0 42px #36e0c02b}
.hero .lead{max-width:650px;color:#c6d5e8!important;font-size:clamp(1.05rem,1.5vw,1.24rem)!important;line-height:1.8!important}
.hero .eyebrow,.hero .hero-kicker{color:#72f0d8!important;letter-spacing:.18em!important;font-size:.76rem!important;font-weight:800!important}
.avail{border:1px solid #36e0c055!important;background:#36e0c012!important;color:#a6ffeb!important;border-radius:999px!important;padding:9px 14px!important;display:inline-flex!important;align-items:center;gap:9px;letter-spacing:.04em;font-size:.78rem!important}
.tags li{background:#ffffff0d!important;border:1px solid #ffffff20!important;color:#e0eafa!important;border-radius:999px!important;padding:9px 13px!important}
.btn{border-radius:13px!important;font-weight:750!important;letter-spacing:.01em;transition:transform .2s ease,box-shadow .2s ease,background .2s ease!important}
.btn:hover{transform:translateY(-3px);box-shadow:0 12px 28px #07142622}
.btn.primary,.btn.solid{background:linear-gradient(120deg,#36e0c0,#73f0d4)!important;color:#062034!important;border:0!important;box-shadow:0 8px 25px #36e0c02b!important}
.btn.outline,.btn.line{border:1px solid #8ba7c6!important}
.hero .btn.outline{color:#eef7ff!important;border-color:#ffffff48!important;background:#ffffff08!important}
.portrait{filter:drop-shadow(0 24px 60px #0007)}
.portrait .ring{border-color:#36e0c0!important;box-shadow:0 0 36px #36e0c02b!important}
.chip{border:1px solid #ffffff2a!important;background:#0c2038ed!important;color:#e8f7ff!important;box-shadow:0 12px 35px #0004!important;backdrop-filter:blur(14px)}
.role-showcase{border:1px solid #ffffff20!important;background:linear-gradient(140deg,#112c46ed,#091a2fed)!important;border-radius:22px!important;box-shadow:0 24px 60px #0004!important;color:#e9f4ff!important;padding:22px!important}
.role-showcase-top{color:#8cebd9!important;letter-spacing:.14em;font-weight:800}
.role-showcase .roles{font-size:clamp(1.5rem,3vw,2.2rem)!important;letter-spacing:-.04em;font-weight:800!important;color:#fff!important}
.role-pills span{border:1px solid #ffffff20!important;background:#ffffff0b!important;color:#d9e9f6!important;border-radius:9px!important}
.pad{padding-top:clamp(68px,8vw,112px)!important;padding-bottom:clamp(68px,8vw,112px)!important}
.section-head{max-width:850px;margin-bottom:34px!important}
.section-head h2,.text h2{letter-spacing:-.055em!important;line-height:1.08!important;font-size:clamp(2.2rem,4.5vw,4rem)!important;text-wrap:balance}
.section-head>p:not(.eyebrow),.text>p{line-height:1.8!important;color:#62718a!important;font-size:1.04rem!important}
.eyebrow{font-size:.75rem!important;font-weight:850!important;letter-spacing:.16em!important;text-transform:uppercase!important;color:#0d9f92!important}
.grad{background:linear-gradient(100deg,#168bca,#0bb99e 68%,#70b7ff)!important;-webkit-background-clip:text!important;background-clip:text!important;color:transparent!important}
.about,.contact{background:linear-gradient(180deg,#f7faff,#edf3fa)!important}
.idcard,.c-card,.gig,.opt,.tile,.contact-options-card{border:1px solid #dce6f1!important;border-radius:22px!important;box-shadow:0 14px 42px #142b4710!important;transition:transform .22s ease,box-shadow .22s ease,border-color .22s ease!important}
.idcard:hover,.c-card:hover,.gig:hover,.opt:hover,.tile:hover{transform:translateY(-4px);box-shadow:0 24px 55px #142b4719!important;border-color:#a8c9df!important}
.idcard{background:linear-gradient(150deg,#fff,#f5fbff)!important;padding:clamp(20px,3vw,30px)!important}
.id-name{font-weight:850!important;letter-spacing:-.025em}
.id-live{background:#d9fff4!important;color:#087d6b!important;border-radius:999px!important;padding:7px 10px!important;font-size:.72rem!important;font-weight:800}
.id-rows dt{color:#75849a!important;font-size:.75rem!important;text-transform:uppercase;letter-spacing:.08em;font-weight:800}
.id-rows dd{color:#192b43!important;font-weight:650!important;line-height:1.6}
.focus li{border:1px solid #e0e9f2!important;border-radius:16px!important;background:#ffffffb8!important;padding:18px!important}
.band-dark{background:radial-gradient(ellipse at 90% 0%,#173c57 0%,transparent 38%),linear-gradient(135deg,#061426,#0a1c32 70%,#0a2a3c)!important;color:#edf6ff!important}
.band-dark .section-head>p:not(.eyebrow){color:#b3c4d9!important}
.band-dark .eyebrow{color:#54e4ca!important}
.band-dark .grad{background:linear-gradient(100deg,#65a5ff,#36e0c0)!important;-webkit-background-clip:text!important;background-clip:text!important}
.filters button{border:1px solid #ffffff24!important;border-radius:999px!important;padding:10px 16px!important;background:#ffffff09!important;color:#dce9f7!important}
.filters button[aria-pressed=true]{background:#36e0c0!important;color:#071a2a!important;border-color:#36e0c0!important}
.tile{background:linear-gradient(145deg,#102640,#0b1c31)!important;border-color:#ffffff18!important;min-height:170px;padding:24px!important}
.tile h3{font-size:1.25rem!important;color:#f5faff!important;letter-spacing:-.025em}
.tile p{color:#b9c9dc!important;line-height:1.7}
.tile .cat{color:#75ead7!important;background:#36e0c014!important;border:1px solid #36e0c02a!important;border-radius:999px!important;padding:5px 9px!important}
.skill-levels,.services,.portfolio,.hire{background:#f5f8fc!important;color:#14243b!important}
.skill-levels .section-head>p:not(.eyebrow),.services .section-head>p:not(.eyebrow),.portfolio .section-head>p:not(.eyebrow),.hire .section-head>p:not(.eyebrow){color:#63738a!important}
.skill-levels .skill,.skill-levels .skill-card{border-radius:18px!important}
.gig,.opt{background:linear-gradient(145deg,#fff,#f8fbff)!important;padding:25px!important}
.gig h3,.opt h3{font-size:1.25rem!important;letter-spacing:-.025em}
.gig p,.opt p,.opt li{color:#607089!important;line-height:1.75}
.gig .pick{border-radius:11px!important;font-weight:800!important}
.pf-tabs{gap:9px!important;flex-wrap:wrap!important}
.pf-tabs button{border-radius:999px!important;padding:11px 16px!important;border:1px solid #dbe5ef!important;background:#fff!important;color:#42536a!important;font-weight:750!important}
.pf-tabs button[aria-selected=true]{background:#0b2036!important;color:#70f0d8!important;border-color:#0b2036!important}
.pf .entry,.pf article,.pf .item{border-radius:20px!important}
.contact-grid{gap:24px!important}
.c-card{padding:clamp(20px,3vw,30px)!important;background:#fff!important}
.c-card .label,.contact-options-heading .label{font-size:.72rem!important;letter-spacing:.14em!important;font-weight:850!important;color:#0c9f91!important}
.c-card .value{overflow-wrap:anywhere;font-weight:800!important;letter-spacing:-.02em}
.contact-highlight{background:radial-gradient(circle at 100% 0%,#1b5570,#0a1a30 70%)!important;color:#effaff!important;border-color:#153c55!important}
.contact-highlight h3{font-size:1.55rem!important;letter-spacing:-.04em}
.contact-highlight .contact-description{color:#c3d4e6!important;line-height:1.8}
.contact-pill{display:inline-flex!important;background:#36e0c016!important;border:1px solid #36e0c03b!important;color:#a0f8e8!important;border-radius:999px!important;padding:8px 12px!important}
.contact-option{border-radius:14px!important;border:1px solid #e0e9f2!important;background:#f8fbff!important;transition:all .2s ease!important}
.contact-option:hover{background:#eafaf7!important;border-color:#77d8c9!important;transform:translateX(3px)}
#composer input,#composer select,#composer textarea{border-radius:12px!important;border:1px solid #d8e3ee!important;background:#f8fbff!important;padding:13px 14px!important;color:#172a43!important}
#composer input:focus,#composer select:focus,#composer textarea:focus{outline:3px solid #36e0c033!important;border-color:#0fb49e!important}
footer{background:#030b17!important;color:#c5d4e5!important;border-top:1px solid #ffffff15!important}
@media(max-width:760px){.hero{min-height:unset;padding-top:95px!important}.hero .wrap{grid-template-columns:1fr!important}.hero h1{font-size:clamp(3rem,13vw,4.7rem)!important}.portrait-col{max-width:420px;margin:10px auto 0}.pad{padding-top:62px!important;padding-bottom:62px!important}.nav{border-radius:0 0 16px 16px!important}.section-head h2,.text h2{font-size:clamp(2rem,9vw,3rem)!important}.id-top{flex-wrap:wrap}.pf-tabs{display:flex!important}.pf-tabs button{font-size:.82rem!important}}
@media(prefers-reduced-motion:reduce){html{scroll-behavior:auto}*,*:before,*:after{animation-duration:.01ms!important;animation-iteration-count:1!important;transition-duration:.01ms!important}}
</style></head><body>
<title>Ahmed Nadeem Abbasi | Data Science &amp; Freelance Analytics Portfolio</title>
<meta content="cover" name="claude:viewport-fit-sides"/>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,600;12..96,800&amp;family=JetBrains+Mono:wght@400;500&amp;family=Source+Sans+3:wght@400;600&amp;display=swap" rel="stylesheet"/>
<style>
/* Layout: one long page whose colour follows the scroll. --hue is blended from section to section (blue, teal, amber, rose, indigo, orange) and drives the page tint, glow, progress bar, headings and marquee. Navy bands (hero, education, contact) stay fixed. The hero is a portrait with a spinning colour ring and floating tool chips. The portfolio tabs are filled from data/profile.json, and the owner can add certificates and other entries from the page itself. */
:root {
  --hue: 215;
  --photo: url("data:image/jpeg;base64,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");
  --bg: hsl(var(--hue) 70% 93%);
  --surface: hsl(var(--hue) 60% 98%);
  --fg: #0E1B2E;
  --muted: #475A72;
  --line: hsl(var(--hue) 38% 79%);
  --field: #FFFFFF;
  --field-label: #475A72;
  --tint1: hsl(var(--hue) 85% 89%);
  --tint2: hsl(calc(var(--hue) + 40) 85% 92%);
  --scene: hsl(var(--hue) 85% 48%);
  --scene-text: hsl(var(--hue) 80% 28%);
  --scene-soft: hsl(var(--hue) 90% 92%);
  --band: hsl(var(--hue) 92% 64%);
  --blob1: hsl(var(--hue) 95% 70% / .38);
  --blob2: hsl(calc(var(--hue) + 55) 95% 72% / .30);
  --navy: #0A2347;
  --navy-deep: #07172F;
  --on-navy: #EAF0F9;
  --on-navy-muted: #A9BAD1;
  --blue: #2F6BFF;
  --amber: #F2B705;
  --teal: #10A596;
  --coral: #F0644A;
  --blue-soft: #E4ECFF;
  --amber-soft: #FFF1C2;
  --teal-soft: #D8F3EF;
  --coral-soft: #FFE3DC;
  --blue-text: #1D4ED8;
  --amber-text: #7A5400;
  --teal-text: #0B7A6F;
  --coral-text: #B63A22;
  --shadow: 0 10px 30px hsl(var(--hue) 60% 25% / .12);
  --font-display: "Bricolage Grotesque", "Arial Narrow", Arial, sans-serif;
  --font-body: "Source Sans 3", system-ui, -apple-system, "Segoe UI", sans-serif;
  --font-mono: "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace;
  --gutter-l: max(16px, env(safe-area-inset-left, 0px));
  --gutter-r: max(16px, env(safe-area-inset-right, 0px));
}
@media (prefers-color-scheme: dark) {
  :root:not([data-theme="light"]) {
    --bg: hsl(var(--hue) 45% 7%); --surface: hsl(var(--hue) 36% 11%); --fg: #E8EEF7; --muted: #9FB0C6;
    --line: hsl(var(--hue) 28% 21%); --field: hsl(var(--hue) 40% 8%); --field-label: #9FB0C6; --tint1: hsl(var(--hue) 45% 12%); --tint2: hsl(calc(var(--hue) + 40) 45% 9%);
    --scene: hsl(var(--hue) 85% 58%); --scene-text: hsl(var(--hue) 90% 72%); --scene-soft: hsl(var(--hue) 50% 17%);
    --blob1: hsl(var(--hue) 90% 45% / .28); --blob2: hsl(calc(var(--hue) + 55) 90% 45% / .22);
    --blue-soft: #132A55; --amber-soft: #3A3010; --teal-soft: #0F3A37; --coral-soft: #44211B;
    --blue-text: #8FB0FF; --amber-text: #F5C93A; --teal-text: #4FD1BE; --coral-text: #FF9C87;
    --shadow: 0 10px 30px #00000066;
    color-scheme: dark;
  }
}
:root[data-theme="dark"] {
  --bg: hsl(var(--hue) 45% 7%); --surface: hsl(var(--hue) 36% 11%); --fg: #E8EEF7; --muted: #9FB0C6;
  --line: hsl(var(--hue) 28% 21%); --field: hsl(var(--hue) 40% 8%); --field-label: #9FB0C6; --tint1: hsl(var(--hue) 45% 12%); --tint2: hsl(calc(var(--hue) + 40) 45% 9%);
  --scene: hsl(var(--hue) 85% 58%); --scene-text: hsl(var(--hue) 90% 72%); --scene-soft: hsl(var(--hue) 50% 17%);
  --blob1: hsl(var(--hue) 90% 45% / .28); --blob2: hsl(calc(var(--hue) + 55) 90% 45% / .22);
  --blue-soft: #132A55; --amber-soft: #3A3010; --teal-soft: #0F3A37; --coral-soft: #44211B;
  --blue-text: #8FB0FF; --amber-text: #F5C93A; --teal-text: #4FD1BE; --coral-text: #FF9C87;
  --shadow: 0 10px 30px #00000066;
  color-scheme: dark;
}
* { box-sizing: border-box; }
html { scroll-behavior: smooth; }
body { background: var(--bg); color: var(--fg); font-family: var(--font-body); font-size: 18px; line-height: 1.6; margin: 0; padding: 0; }
body::before { content: ""; position: fixed; inset: 0; z-index: -1; pointer-events: none;
  background:
    radial-gradient(55% 45% at 88% 8%, var(--blob1), transparent 70%),
    radial-gradient(50% 45% at 6% 92%, var(--blob2), transparent 70%); }
a { color: inherit; }
button { font: inherit; }
:focus-visible { outline: 3px solid var(--amber); outline-offset: 3px; border-radius: 4px; }
.wrap { max-width: 1120px; margin-inline: auto; padding-left: var(--gutter-l); padding-right: var(--gutter-r); }
[id] { scroll-margin-top: var(--nav-h, 72px); }
.gigs { display: grid; grid-template-columns: repeat(auto-fill, minmax(260px, 1fr)); gap: 20px; }
.gig { background: var(--surface); border: 2px solid var(--line); border-radius: 16px; padding: 22px; display: flex; flex-direction: column; gap: 10px; cursor: pointer; box-shadow: var(--shadow); min-width: 0; }
.gig.c-blue { background: linear-gradient(145deg, var(--blue-soft), var(--surface) 75%); }
.gig.c-teal { background: linear-gradient(145deg, var(--teal-soft), var(--surface) 75%); }
.gig.c-amber { background: linear-gradient(145deg, var(--amber-soft), var(--surface) 75%); }
.gig.c-coral { background: linear-gradient(145deg, var(--coral-soft), var(--surface) 75%); }
.gig[data-on="true"] { border-color: var(--scene); box-shadow: 0 0 0 3px var(--scene), var(--shadow); }
.gig .top { display: flex; align-items: center; justify-content: space-between; gap: 12px; }
.gig .tool { font-family: var(--font-mono); font-size: 12px; font-weight: 500; text-align: right; color: var(--scene-text); background: var(--scene-soft); padding: 4px 10px; border-radius: 6px; }
.gig[data-on="true"] .tool { background: var(--surface); }
.gig h3 { font-family: var(--font-display); font-size: 1.3rem; line-height: 1.15; margin: 8px 0 0; letter-spacing: -.01em; }
.gig p { margin: 0; color: var(--muted); font-size: 1rem; flex: 1; }
.gig .pick { margin-top: 6px; align-self: flex-start; font-family: var(--font-mono); font-size: 13px; font-weight: 500; padding: 9px 16px; border-radius: 999px; border: 1.5px solid var(--fg); background: transparent; color: var(--fg); cursor: pointer; }
.gig .pick[aria-pressed="true"] { background: var(--navy); border-color: var(--navy); color: #fff; }
.request-bar { position: sticky; bottom: calc(14px + env(safe-area-inset-bottom, 0px)); z-index: 12; margin: 28px 64px 0 0; display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; gap: 12px 16px; background: var(--navy); color: #fff; padding: 14px 18px; border-radius: 16px; border: 1px solid #ffffff2a; box-shadow: 0 16px 40px #00000055; }
.req-text { display: grid; min-width: 0; flex: 1 1 220px; }
.req-text b { font-family: var(--font-display); font-size: 1.1rem; }
.req-text span { font-size: .92rem; color: var(--on-navy-muted); overflow: hidden; text-overflow: ellipsis; white-space: nowrap; }
.req-actions { display: flex; flex-wrap: wrap; gap: 10px; }
.btn.line.light { color: #fff; border-color: #ffffff55; }
.btn.line.light:hover { border-color: #fff; }
.sr-only { position: absolute; width: 1px; height: 1px; margin: -1px; padding: 0; overflow: hidden; clip: rect(0 0 0 0); white-space: nowrap; border: 0; }

.eyebrow { font-family: var(--font-mono); font-size: 13px; letter-spacing: .14em; text-transform: uppercase; margin: 0 0 12px; color: var(--scene-text); }
h2 { font-family: var(--font-display); font-weight: 800; font-size: clamp(1.9rem, 4.6vw, 3rem); line-height: 1.05; letter-spacing: -.02em; margin: 0 0 20px; text-wrap: balance; }
h2::after { content: ""; display: block; width: 64px; height: 5px; border-radius: 3px; background: linear-gradient(90deg, var(--scene), hsl(calc(var(--hue) + 60) 92% 60%)); margin-top: 16px; }
.section-head { max-width: 640px; margin-bottom: 40px; }
.section-head p:not(.eyebrow) { color: var(--muted); margin: 0; font-size: 1.1rem; }
section.pad { padding-block: 92px; }
.band-tint { background:
    radial-gradient(45% 55% at 100% 0%, hsl(var(--hue) 95% 70% / .35), transparent 70%),
    radial-gradient(40% 50% at 0% 100%, hsl(calc(var(--hue) + 60) 95% 72% / .3), transparent 70%),
    linear-gradient(180deg, var(--tint1), var(--tint2)); }
.band-dark { --surface: #ffffff12; --fg: #EAF0F9; --muted: #B3C2D6; --line: #ffffff26; --bg: #ffffff0d; --field: #0A1627; --field-label: #B3C2D6;
  --scene: hsl(var(--hue) 90% 62%); --scene-text: hsl(var(--hue) 95% 77%); --scene-soft: #ffffff17; --shadow: 0 10px 30px #00000055;
  --blue-soft: #17316F; --amber-soft: #4A3A0A; --teal-soft: #0F4742; --coral-soft: #55261E;
  --blue-text: #9DBBFF; --amber-text: #F5C93A; --teal-text: #4FD1BE; --coral-text: #FF9C87;
  color: var(--fg);
  background:
    radial-gradient(45% 55% at 95% 0%, hsl(var(--hue) 90% 55% / .3), transparent 70%),
    radial-gradient(40% 50% at 3% 100%, hsl(calc(var(--hue) + 60) 90% 55% / .24), transparent 70%),
    linear-gradient(160deg, hsl(var(--hue) 62% 15%), hsl(calc(var(--hue) + 45) 66% 11%)); }
.band-dark .filters button[aria-pressed="true"], .band-dark .tabs button[aria-selected="true"] { background: #fff; color: #0A2347; border-color: #fff; box-shadow: 0 3px 0 var(--scene); }
.band-dark .btn.solid { background: linear-gradient(135deg, #FFD04D, #F2A100); color: #1B1500; border-color: transparent; }
.band-dark .btn.line { color: #fff; border-color: #ffffff55; }
.grad { background: linear-gradient(90deg, hsl(var(--hue) 85% 40%), hsl(calc(var(--hue) + 60) 85% 45%)); -webkit-background-clip: text; background-clip: text; color: transparent; }
.band-dark .grad, .contact .grad { background: linear-gradient(90deg, hsl(var(--hue) 95% 72%), hsl(calc(var(--hue) + 60) 95% 70%)); -webkit-background-clip: text; background-clip: text; }
@media (prefers-color-scheme: dark) { :root:not([data-theme="light"]) .grad { background: linear-gradient(90deg, hsl(var(--hue) 95% 72%), hsl(calc(var(--hue) + 60) 95% 70%)); -webkit-background-clip: text; background-clip: text; } }
:root[data-theme="dark"] .grad { background: linear-gradient(90deg, hsl(var(--hue) 95% 72%), hsl(calc(var(--hue) + 60) 95% 70%)); -webkit-background-clip: text; background-clip: text; }

/* nav */
.nav { position: sticky; top: env(safe-area-inset-top, 0px); z-index: 20; background: var(--navy-deep); color: var(--on-navy); border-bottom: 1px solid #ffffff18; }
.nav .bar { display: flex; align-items: center; gap: 10px 16px; padding-block: 10px; }
.progress { position: absolute; left: 0; bottom: -1px; height: 3px; width: 0; background: hsl(var(--hue) 95% 62%); }
.mark { font-family: var(--font-mono); font-size: 14px; font-weight: 500; text-decoration: none; display: flex; align-items: center; gap: 12px; }
.avatar { width: 38px; height: 38px; border-radius: 50%; background: var(--photo) center / cover no-repeat, var(--navy); border: 2px solid var(--amber); flex: none; }
.links { display: flex; align-items: center; justify-content: center; flex: 1 1 auto; min-width: 0; gap: 8px; padding: 6px; font-family: var(--font-mono); font-size: 14px; font-weight: 500; overflow-x: auto; scrollbar-width: none; scroll-behavior: smooth; }
.links::-webkit-scrollbar { display: none; }
.links a { --pc: #2F6BFF; --pcs: #2F6BFF40; --pt: #fff; text-decoration: none; color: #fff; background: var(--pcs); border: 1.5px solid var(--pc); padding: 8px 18px; border-radius: 999px; white-space: nowrap; flex: none; }
.links a:nth-child(2) { --pc: #10B3A0; --pcs: #10B3A040; }
.links a:nth-child(3) { --pc: #F2A100; --pcs: #F2A10040; --pt: #1B1500; }
.links a:nth-child(4) { --pc: #F0503A; --pcs: #F0503A40; }
.links a:nth-child(5) { --pc: #8B6BFF; --pcs: #8B6BFF40; }
.links a:hover { background: var(--pc); color: var(--pt); }
.links a[aria-current="true"] { background: var(--pc); color: var(--pt); box-shadow: 0 0 0 2px #07172F, 0 0 0 4px #fff; }
.tools { display: flex; align-items: center; gap: 8px; }
.icon-btn { width: 40px; height: 40px; display: grid; place-items: center; background: #ffffff12; color: var(--on-navy); border: 1px solid #ffffff2a; border-radius: 8px; cursor: pointer; }
.icon-btn:hover { background: #ffffff24; }
.icon-btn svg { width: 20px; height: 20px; stroke: currentColor; fill: none; stroke-width: 1.8; stroke-linecap: round; stroke-linejoin: round; }
.nav .hire-btn { font-family: var(--font-mono); font-size: 14px; font-weight: 500; background: linear-gradient(135deg, #FFD04D, #F2A100); color: #1B1500; text-decoration: none; padding: 11px 20px; border-radius: 999px; white-space: nowrap; }
.nav .hire-btn:hover { filter: brightness(1.07); }

/* hero */
.hero { position: relative; overflow: clip; background:
    radial-gradient(45% 60% at 100% 100%, #F0644A36, transparent 60%),
    radial-gradient(40% 50% at 22% 0%, #F2B7052E, transparent 60%),
    radial-gradient(60% 80% at 85% 10%, #10A59648, transparent 60%),
    radial-gradient(55% 75% at 0% 100%, #2F6BFF5C, transparent 60%),
    linear-gradient(#ffffff08 1px, transparent 1px) 0 0 / 100% 48px,
    var(--navy);
  color: var(--on-navy); }
.hero .wrap { display: grid; grid-template-columns: minmax(0, 1.1fr) minmax(0, .9fr); gap: 56px; align-items: center; padding-block: 76px 84px; }
.avail { display: inline-flex; align-items: center; gap: 10px; font-family: var(--font-mono); font-size: 13px; padding: 7px 14px; border-radius: 999px; background: #10A59626; border: 1px solid #10A59688; color: #A5F3E6; margin: 0 0 24px; }
.avail i { width: 9px; height: 9px; border-radius: 50%; background: #2DE0C8; display: inline-block; box-shadow: 0 0 0 0 #2DE0C899; }
.hero .eyebrow { color: var(--amber); }
h1 { font-family: var(--font-display); font-weight: 800; font-size: clamp(2.8rem, 6.6vw, 5rem); line-height: .96; letter-spacing: -.03em; margin: 0 0 24px; color: #fff; text-wrap: balance; }
h1 em { font-style: normal; background: linear-gradient(90deg, #F2B705, #FF8C74); -webkit-background-clip: text; background-clip: text; color: transparent; }
.lead { font-size: 1.3rem; color: var(--on-navy-muted); max-width: 34ch; margin: 0 0 28px; }
.tags { display: flex; flex-wrap: wrap; gap: 8px; margin: 0 0 32px; padding: 0; list-style: none; }
.tags li { font-family: var(--font-mono); font-size: 13px; padding: 5px 12px; border-radius: 999px; border: 1px solid #ffffff2e; color: var(--on-navy); }
.tags li:nth-child(1) { background: #2F6BFF40; border-color: #2F6BFF; }
.tags li:nth-child(2) { background: #10A59640; border-color: #10A596; }
.tags li:nth-child(3) { background: #F2B70530; border-color: #F2B705; }
.tags li:nth-child(4) { background: #F0644A30; border-color: #F0644A; }
.actions { display: flex; flex-wrap: wrap; gap: 12px; }
.btn { font-family: var(--font-mono); font-size: 14px; font-weight: 500; text-decoration: none; padding: 13px 22px; border-radius: 8px; border: 2px solid transparent; display: inline-block; cursor: pointer; line-height: 1.3; }
.btn.primary { background: linear-gradient(135deg, #FFD04D, #F2A100); color: #1B1500; }
.btn.primary:hover { filter: brightness(1.07); }
.btn.outline { border-color: #ffffff55; color: #fff; background: transparent; }
.btn.outline:hover { background: #ffffff1c; }
.btn.small { padding: 9px 14px; font-size: 13px; }
.btn.solid { background: var(--navy); color: #fff; border-color: var(--navy); }
.btn.solid:hover { filter: brightness(1.25); }
.btn.line { background: transparent; color: var(--fg); border-color: var(--line); }
.btn.line:hover { border-color: var(--fg); }

/* portrait */
.portrait { position: relative; width: min(100%, 400px); aspect-ratio: 1; margin-inline: auto; }
.portrait .glow { position: absolute; inset: -14%; border-radius: 50%; background: radial-gradient(closest-side, #2F6BFF55, #10A59630 55%, transparent 75%); }
.portrait .ring { position: absolute; inset: -9px; border-radius: 50%; background: conic-gradient(#F2B705, #F0644A, #2F6BFF, #10A596, #F2B705); }
.portrait .photo { position: absolute; inset: 0; border-radius: 50%; background: var(--photo) center / cover no-repeat, var(--navy); border: 7px solid var(--navy); background-origin: padding-box; background-clip: padding-box; }
.chip { position: absolute; display: flex; align-items: center; gap: 9px; font-family: var(--font-mono); font-size: 13px; font-weight: 500; color: #fff; padding: 9px 14px; border-radius: 12px; background: #0A2347B8; border: 1px solid #ffffff38; -webkit-backdrop-filter: blur(10px); backdrop-filter: blur(10px); box-shadow: 0 10px 28px #00000040; white-space: nowrap; }
.chip i { width: 10px; height: 10px; border-radius: 3px; display: inline-block; }
.chip.c1 { top: 5%; left: -7%; } .chip.c1 i { background: var(--blue); }
.chip.c2 { top: 30%; right: -9%; } .chip.c2 i { background: var(--amber); }
.chip.c3 { bottom: 17%; left: -9%; } .chip.c3 i { background: var(--teal); }
.chip.c4 { bottom: 3%; right: -3%; } .chip.c4 i { background: var(--coral); }

#net { position: absolute; left: 0; top: 0; width: 100%; height: 100%; z-index: 0; pointer-events: none; }
.hero .wrap { position: relative; z-index: 1; }
.portrait-col { display: grid; gap: 44px; justify-items: center; min-width: 0; }
.portrait-col .portrait { width: min(100%, 400px); }
.roles { margin: 0; text-align: center; font-family: var(--font-display); font-weight: 800; font-size: clamp(1.6rem, 3.6vw, 2.2rem); letter-spacing: -.015em; line-height: 1.2; min-height: 1.25em; color: #fff; }
.roles .typed { background: linear-gradient(90deg, #F2B705, #FF8C74); -webkit-background-clip: text; background-clip: text; color: transparent; }
.roles .caret { display: inline-block; width: 3px; height: .95em; margin-left: 5px; vertical-align: -.12em; border-radius: 2px; background: var(--amber); }
.spot { position: relative; }
.spot::after { content: ""; position: absolute; inset: 0; border-radius: inherit; pointer-events: none; opacity: 0; background: radial-gradient(240px circle at var(--mx, 50%) var(--my, 50%), hsl(var(--hue) 95% 60% / .16), transparent 70%); }
.spot:hover::after { opacity: 1; }
.stats { background: var(--navy-deep); color: var(--on-navy); border-top: 1px solid #ffffff18; }
.stats .wrap { display: grid; grid-template-columns: repeat(4, minmax(0, 1fr)); }
.stat { padding: 24px 20px; border-left: 1px solid #ffffff18; }
.stat:first-child { border-left: 0; padding-left: 0; }
.stat b { display: block; font-family: var(--font-display); font-size: 2.4rem; line-height: 1; font-weight: 800; font-variant-numeric: tabular-nums; }
.stat:nth-child(1) b { color: var(--amber); }
.stat:nth-child(2) b { color: #6FA0FF; }
.stat:nth-child(3) b { color: #3FD6C4; }
.stat:nth-child(4) b { color: #FF8C74; }
.stat span { font-family: var(--font-mono); font-size: 12px; letter-spacing: .08em; text-transform: uppercase; color: var(--on-navy-muted); display: block; margin-top: 8px; }

.marquee { background: linear-gradient(90deg, hsl(var(--hue) 92% 64%), hsl(calc(var(--hue) + 55) 92% 66%)); color: #0B1220; overflow: hidden; border-block: 1px solid #0B122022; }
.marquee .track { display: flex; width: max-content; }
.marquee ul { display: flex; align-items: center; margin: 0; padding: 0; list-style: none; flex: none; }
.marquee li { font-family: var(--font-display); font-weight: 800; font-size: 1.5rem; letter-spacing: -.01em; padding: 14px 0; white-space: nowrap; display: flex; align-items: center; }
.marquee li::after { content: ""; width: 10px; height: 10px; background: #0B1220; transform: rotate(45deg); margin-inline: 28px; }

/* about */
.about .grid { display: grid; grid-template-columns: minmax(0, 1.2fr) minmax(0, 1fr); gap: 56px; align-items: center; }
.about .text p:not(.eyebrow) { font-size: 1.25rem; line-height: 1.55; margin: 0 0 18px; text-wrap: pretty; }
.about .text p.small { font-size: 1.05rem; color: var(--muted); }
.panel { background: var(--navy-deep); color: #DCE6F2; border: 1px solid #ffffff22; border-radius: 14px; font-family: var(--font-mono); font-size: 14px; line-height: 1.7; overflow: hidden; min-width: 0; box-shadow: 0 24px 60px #00000040; }
.panel-head { display: flex; align-items: center; gap: 8px; padding: 11px 16px; border-bottom: 1px solid #ffffff1c; color: #8FA3BF; font-size: 12px; letter-spacing: .06em; }
.dot { width: 10px; height: 10px; border-radius: 50%; display: inline-block; }
.dot.r { background: var(--coral); } .dot.y { background: var(--amber); } .dot.g { background: var(--teal); }
.panel-head .name { margin-left: 8px; }
.panel-head .rows { margin-left: auto; }
.sql { margin: 0; padding: 18px 18px 14px; overflow-x: auto; white-space: pre; }
.kw { color: var(--amber); }
.str { color: #6EE0C8; }
.res { border-top: 1px solid #ffffff1c; padding: 4px 18px 14px; }
.res table { width: 100%; border-collapse: collapse; font-variant-numeric: tabular-nums; }
.res th { text-align: left; font-weight: 500; color: #8FA3BF; font-size: 12px; letter-spacing: .06em; padding: 10px 0 4px; }
.res td { padding: 1px 0; }
.res td:first-child { color: #8FA3BF; width: 2.5em; }
.idcard { background: var(--surface); border: 1px solid var(--line); border-radius: 22px; overflow: hidden; box-shadow: 0 24px 60px hsl(var(--hue) 60% 25% / .2); min-width: 0; }
.id-top { display: flex; flex-wrap: wrap; align-items: center; gap: 14px 16px; padding: 22px; color: #fff; background: radial-gradient(60% 120% at 100% 0%, #F2B70540, transparent 60%), linear-gradient(120deg, #0A2347, #1E4FBF 60%, #0E9F8E); }
.id-avatar { width: 68px; height: 68px; border-radius: 50%; flex: none; background: var(--photo) center / cover no-repeat, var(--navy); border: 3px solid var(--amber); box-shadow: 0 8px 20px #00000055; }
.id-who { min-width: 0; }
.id-name { margin: 0; font-family: var(--font-display); font-weight: 800; font-size: 1.3rem; line-height: 1.1; letter-spacing: -.01em; }
.id-role { margin: 4px 0 0; font-family: var(--font-mono); font-size: 13px; color: #FFD04D; }
.id-live { margin-left: auto; display: inline-flex; align-items: center; gap: 8px; font-family: var(--font-mono); font-size: 12px; padding: 6px 12px; border-radius: 999px; background: #ffffff22; border: 1px solid #ffffff44; }
.id-live i { width: 8px; height: 8px; border-radius: 50%; background: #2DE0C8; }
.id-rows { margin: 0; padding: 6px 22px; }
.id-rows > div { display: grid; grid-template-columns: minmax(110px, 130px) minmax(0, 1fr); gap: 8px 14px; align-items: center; padding: 14px 0; border-bottom: 1px solid var(--line); }
.id-rows dt { display: flex; align-items: center; gap: 12px; font-family: var(--font-mono); font-size: 12px; letter-spacing: .08em; text-transform: uppercase; color: var(--muted); }
.id-rows dd { margin: 0; font-weight: 600; overflow-wrap: anywhere; }
.id-rows .ic { width: 34px; height: 34px; border-radius: 10px; }
.id-rows .ic svg { width: 17px; height: 17px; }
.id-chips { display: flex; flex-wrap: wrap; gap: 6px; }
.id-chips span { font-family: var(--font-mono); font-size: 12px; font-weight: 500; padding: 4px 10px; border-radius: 6px; }
.id-chips span:nth-child(1) { background: var(--blue-soft); color: var(--blue-text); }
.id-chips span:nth-child(2) { background: var(--amber-soft); color: var(--amber-text); }
.id-chips span:nth-child(3) { background: var(--teal-soft); color: var(--teal-text); }
.id-chips span:nth-child(4) { background: var(--amber-soft); color: var(--amber-text); }
.id-chips span:nth-child(5) { background: var(--coral-soft); color: var(--coral-text); }
.id-actions { display: flex; flex-wrap: wrap; gap: 10px; padding: 18px 22px 22px; }
.id-actions .btn.line { color: var(--fg); }
@media (max-width: 520px) { .id-rows > div { grid-template-columns: minmax(0, 1fr); } .id-live { margin-left: 0; } }
.focus { list-style: none; margin: 48px 0 0; padding: 0; display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 16px; }
.focus li { display: flex; gap: 16px; align-items: center; background: var(--surface); border: 1px solid var(--line); border-radius: 14px; padding: 16px 18px; font-weight: 600; box-shadow: var(--shadow); }
.ic { width: 44px; height: 44px; border-radius: 12px; display: grid; place-items: center; flex: none; }
.ic svg { width: 22px; height: 22px; stroke: currentColor; fill: none; stroke-width: 1.8; stroke-linecap: round; stroke-linejoin: round; }
.ic.blue { background: linear-gradient(135deg, #2F6BFF, #6C9BFF); color: #fff; box-shadow: 0 6px 14px #2F6BFF4D; }
.ic.amber { background: linear-gradient(135deg, #F2A100, #FFD04D); color: #2A1B00; box-shadow: 0 6px 14px #F2A1004D; }
.ic.teal { background: linear-gradient(135deg, #0E9F8E, #3BD6C0); color: #fff; box-shadow: 0 6px 14px #0E9F8E4D; }
.ic.coral { background: linear-gradient(135deg, #F0503A, #FF8F70); color: #fff; box-shadow: 0 6px 14px #F0503A4D; }
.focus .sub { display: block; font-weight: 400; color: var(--muted); font-size: .95rem; }

/* skills */
.filters, .tabs { display: flex; flex-wrap: wrap; gap: 8px; margin: 0 0 28px; }
.filters button, .tabs button { font-family: var(--font-mono); font-size: 13px; font-weight: 500; padding: 10px 18px; border-radius: 999px; border: 1.5px solid var(--line); background: var(--surface); color: var(--fg); cursor: pointer; }
.filters button:hover, .tabs button:hover { border-color: var(--fg); }
.filters button[aria-pressed="true"], .tabs button[aria-selected="true"] { background: var(--navy); border-color: var(--navy); color: #fff; box-shadow: 0 3px 0 var(--scene); }
.tiles { display: grid; grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); gap: 18px; }
.tile { background: var(--surface); border: 1px solid var(--line); border-left-width: 6px; border-radius: 14px; padding: 20px 22px; min-width: 0; box-shadow: var(--shadow); }
.tile.blue { border-left-color: var(--blue); background: linear-gradient(135deg, var(--blue-soft), var(--surface) 60%); }
.tile.amber { border-left-color: var(--amber); background: linear-gradient(135deg, var(--amber-soft), var(--surface) 60%); }
.tile.teal { border-left-color: var(--teal); background: linear-gradient(135deg, var(--teal-soft), var(--surface) 60%); }
.tile h3 { font-family: var(--font-display); font-size: 1.35rem; margin: 0 0 4px; letter-spacing: -.01em; }
.tile p { margin: 0 0 14px; color: var(--muted); font-size: 1rem; }
.tile .cat { font-family: var(--font-mono); font-size: 12px; font-weight: 500; padding: 4px 10px; border-radius: 6px; display: inline-block; }
.tile.blue .cat { background: var(--blue-soft); color: var(--blue-text); }
.tile.amber .cat { background: var(--amber-soft); color: var(--amber-text); }
.tile.teal .cat { background: var(--teal-soft); color: var(--teal-text); }

/* services */
.svc-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(290px, 1fr)); gap: 22px; }
.svc { background: var(--surface); border: 1px solid var(--line); border-radius: 16px; padding: 26px; box-shadow: var(--shadow); min-width: 0; }
.svc .ic { margin-bottom: 18px; }
.svc h3 { font-family: var(--font-display); font-size: 1.35rem; margin: 0 0 8px; letter-spacing: -.01em; }
.svc p { margin: 0 0 16px; color: var(--muted); font-size: 1rem; }
.svc .uses { font-family: var(--font-mono); font-size: 13px; padding-top: 14px; border-top: 1px solid var(--line); }

/* portfolio */
.tabs button .n { margin-left: 6px; opacity: .75; }
.pf { background: var(--surface); border: 1px solid var(--line); border-radius: 18px; padding: 28px; box-shadow: var(--shadow); min-height: 260px; }
.pf-status { font-family: var(--font-mono); font-size: 13px; color: var(--scene-text); min-height: 1.5em; margin: 12px 0 0; }
.owner-bar { display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; gap: 12px; background: var(--scene-soft); border: 1px dashed var(--scene); border-radius: 12px; padding: 12px 16px; margin-bottom: 24px; font-size: .98rem; }
.owner-bar span { min-width: 0; }
.entry-form { display: grid; gap: 14px; padding: 20px; border: 1.5px solid var(--line); border-radius: 14px; margin-bottom: 28px; background: var(--bg); }
.entry-form h3 { margin: 0; font-family: var(--font-display); font-size: 1.3rem; }
.form-row { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 14px; }
.form-actions { display: flex; flex-wrap: wrap; gap: 10px; align-items: center; }
.form-note { font-size: .95rem; color: var(--muted); margin: 0; }
.field { display: grid; gap: 6px; min-width: 0; }
.field label { font-family: var(--font-mono); font-size: 12px; letter-spacing: .1em; text-transform: uppercase; color: var(--field-label); }
.field input, .field select, .field textarea { width: 100%; font: inherit; font-size: 1rem; color: var(--fg); background: var(--field); border: 1.5px solid var(--line); border-radius: 8px; padding: 11px 13px; }
.field input[type="file"] { padding: 9px; }
.field textarea { min-height: 110px; resize: vertical; }
.field input::placeholder, .field textarea::placeholder { color: var(--muted); opacity: .8; }
.timeline { list-style: none; margin: 0; padding: 0; display: grid; gap: 28px; }
.timeline li { position: relative; padding-left: 28px; border-left: 2px solid var(--line); min-width: 0; }
.timeline li::before { content: ""; position: absolute; left: -7px; top: 6px; width: 12px; height: 12px; border-radius: 50%; background: var(--scene); }
.entry h3 { font-family: var(--font-display); font-size: 1.3rem; margin: 0; overflow-wrap: anywhere; }
.entry .org { font-weight: 600; }
.entry .date { font-family: var(--font-mono); font-size: 13px; color: var(--muted); }
.entry p { margin: 8px 0 0; color: var(--muted); white-space: pre-line; overflow-wrap: anywhere; }
.entry a.lnk { color: var(--scene-text); font-weight: 600; }
.entry .quote { border-left: 4px solid var(--scene); padding-left: 14px; font-style: italic; color: var(--fg); }
.rm { margin-top: 12px; font-family: var(--font-mono); font-size: 12px; background: none; border: 1px solid var(--line); border-radius: 6px; color: var(--muted); padding: 6px 12px; cursor: pointer; }
.rm:hover { border-color: var(--coral); color: var(--coral-text); }
.rm[data-armed="true"] { background: var(--coral); border-color: var(--coral); color: #fff; }
.cert-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); gap: 20px; }
.cert { border: 1px solid var(--line); border-radius: 14px; overflow: hidden; background: var(--bg); display: flex; flex-direction: column; min-width: 0; }
.cert .media { aspect-ratio: 4 / 3; width: 100%; background: var(--scene-soft); display: grid; place-items: center; border: 0; padding: 0; overflow: hidden; color: var(--scene-text); }
button.media { cursor: zoom-in; }
a.media { text-decoration: none; }
.cert .media img { width: 100%; height: 100%; object-fit: cover; display: block; }
.cert .body { padding: 16px 18px 18px; display: grid; gap: 4px; align-content: start; flex: 1; }
.cert .body .rm { justify-self: start; }
.pdf-tile { display: grid; justify-items: center; gap: 8px; font-family: var(--font-mono); font-size: 13px; }
.pdf-tile svg { width: 40px; height: 40px; stroke: currentColor; fill: none; stroke-width: 1.6; stroke-linecap: round; stroke-linejoin: round; }
.thumb-sm { margin-top: 12px; display: block; width: min(100%, 260px); aspect-ratio: 4 / 3; border-radius: 10px; overflow: hidden; border: 1px solid var(--line); padding: 0; background: var(--scene-soft); cursor: zoom-in; }
.thumb-sm img { width: 100%; height: 100%; object-fit: cover; display: block; }
.lang-list { list-style: none; margin: 0; padding: 0; display: flex; flex-wrap: wrap; gap: 12px; }
.lang-list li { background: var(--scene-soft); color: var(--scene-text); border-radius: 10px; padding: 10px 16px; font-weight: 600; }
.lang-list small { font-weight: 400; margin-left: 8px; }
.ghost { display: flex; gap: 18px; align-items: center; border: 2px dashed var(--line); border-radius: 14px; padding: 22px; }
.ghost .ic { width: 56px; height: 56px; border-radius: 14px; }
.ghost .ic svg { width: 26px; height: 26px; }
.g-lines { display: grid; gap: 10px; flex: 1; min-width: 0; }
.gl { display: block; height: 12px; border-radius: 6px; background: var(--line); }
.gl.w60 { width: 60%; } .gl.w40 { width: 40%; } .gl.w80 { width: 80%; }
.g-msg { margin: 20px 0 0; font-size: 1.1rem; }
.g-sub { margin: 4px 0 0; color: var(--muted); font-size: 1rem; }
.g-sub a { color: var(--scene-text); font-weight: 600; }

/* process */
.steps { list-style: none; margin: 0; padding: 0; display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 20px; counter-reset: step; }
.steps li { background: var(--surface); border: 1px solid var(--line); border-radius: 16px; padding: 24px; min-width: 0; box-shadow: var(--shadow); }
.steps li::before { counter-increment: step; content: counter(step); display: grid; place-items: center; width: 36px; height: 36px; border-radius: 50%; font-family: var(--font-mono); font-weight: 500; font-size: 15px; margin-bottom: 16px; color: #fff; }
.steps li:nth-child(1) { background: linear-gradient(160deg, var(--blue-soft), var(--surface) 80%); border-top: 4px solid var(--blue); }
.steps li:nth-child(2) { background: linear-gradient(160deg, var(--teal-soft), var(--surface) 80%); border-top: 4px solid var(--teal); }
.steps li:nth-child(3) { background: linear-gradient(160deg, var(--amber-soft), var(--surface) 80%); border-top: 4px solid var(--amber); }
.steps li:nth-child(4) { background: linear-gradient(160deg, var(--coral-soft), var(--surface) 80%); border-top: 4px solid var(--coral); }
.opt:nth-child(1) { border-top: 4px solid var(--blue); }
.opt:nth-child(2) { border-top: 4px solid var(--teal); }
.opt:nth-child(3) { border-top: 4px solid var(--amber); }
.steps li:nth-child(1)::before { background: var(--blue); }
.steps li:nth-child(2)::before { background: var(--teal); }
.steps li:nth-child(3)::before { background: var(--amber); color: #1B1500; }
.steps li:nth-child(4)::before { background: var(--coral); }
.steps h3 { font-family: var(--font-display); font-size: 1.25rem; margin: 0 0 6px; }
.steps p { margin: 0 0 12px; color: var(--muted); font-size: 1rem; }
.steps .tool { font-family: var(--font-mono); font-size: 13px; }

/* work with me */
.options { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 22px; margin-bottom: 56px; }
.opt { background: var(--surface); border: 1px solid var(--line); border-radius: 18px; padding: 28px; display: flex; flex-direction: column; box-shadow: var(--shadow); min-width: 0; }
.opt .ic { margin-bottom: 18px; }
.opt h3 { font-family: var(--font-display); font-size: 1.5rem; margin: 0 0 8px; letter-spacing: -.01em; }
.opt > p { margin: 0 0 16px; color: var(--muted); font-size: 1.02rem; }
.opt ul { list-style: none; margin: 0 0 24px; padding: 16px 0 0; border-top: 1px solid var(--line); display: grid; gap: 8px; flex: 1; align-content: start; }
.opt li { display: flex; gap: 10px; font-size: 1rem; }
.opt li::before { content: ""; width: 8px; height: 8px; margin-top: 9px; border-radius: 2px; background: var(--scene); flex: none; }
.opt .btn { text-align: center; }
.faq-title { font-family: var(--font-display); font-size: 1.6rem; margin: 0 0 18px; }
.faq { display: grid; gap: 12px; max-width: 820px; }
.faq details { background: var(--surface); border: 1px solid var(--line); border-radius: 12px; padding: 0 20px; }
.faq summary { cursor: pointer; font-weight: 600; padding: 16px 0; list-style: none; display: flex; justify-content: space-between; gap: 16px; align-items: center; }
.faq summary::-webkit-details-marker { display: none; }
.faq summary::after { content: "+"; font-family: var(--font-mono); font-size: 22px; color: var(--scene-text); flex: none; }
.faq details[open] summary::after { content: "\2212"; }
.faq details p { margin: 0 0 18px; color: var(--muted); }

/* education */
.edu { background: radial-gradient(40% 120% at 100% 0%, #F2B70533, transparent 60%), linear-gradient(120deg, #0A4F94, #0B7A6F 55%, #0B8A7C); color: #fff; padding-block: 72px; }
.edu .eyebrow { color: #CFF5EF; }
.edu .row { display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; gap: 20px 32px; }
.edu h2 { color: #fff; margin: 0 0 8px; }
.edu h2::after { display: none; }
.edu .sub { margin: 0; color: #DDF8F3; font-size: 1.1rem; }
.edu .badge { font-family: var(--font-mono); font-size: 14px; background: #ffffff22; border: 1px solid #ffffff55; padding: 8px 16px; border-radius: 999px; }

/* contact */
.contact { background: var(--navy); color: var(--on-navy); background-image: radial-gradient(50% 80% at 100% 0%, #F2B70533, transparent 60%), radial-gradient(45% 70% at 0% 100%, #2F6BFF45, transparent 60%), radial-gradient(40% 60% at 60% 115%, #10A59640, transparent 60%); }
.contact .eyebrow { color: var(--amber); }
.contact h2 { color: #fff; }
.contact h2::after { background: var(--amber); }
.contact .section-head p:not(.eyebrow) { color: var(--on-navy-muted); }
.contact .field label { color: var(--on-navy-muted); }
.contact-grid { display: grid; grid-template-columns: minmax(0, 1fr) minmax(0, 1.2fr); gap: 24px; align-items: start; }
.c-stack { display: grid; gap: 20px; }
.c-card { background: #ffffff0f; border: 1px solid #ffffff26; border-radius: 14px; padding: 24px; min-width: 0; }
.c-card .label { font-family: var(--font-mono); font-size: 12px; letter-spacing: .12em; text-transform: uppercase; color: var(--on-navy-muted); margin: 0 0 8px; }
.c-card .value { font-family: var(--font-display); font-weight: 600; font-size: clamp(1.1rem, 3.6vw, 1.5rem); overflow-wrap: anywhere; margin: 0 0 16px; display: block; color: #fff; text-decoration: none; }
.c-card .btns { display: flex; flex-wrap: wrap; gap: 10px; }
.c-card .btn { padding: 10px 18px; }
form.c-card { display: grid; gap: 16px; }
form h3 { font-family: var(--font-display); font-size: 1.4rem; margin: 0; color: #fff; }
.status { font-family: var(--font-mono); font-size: 13px; color: var(--on-navy-muted); min-height: 1.4em; margin: 0; }
.hint { font-size: .95rem; color: var(--on-navy-muted); margin: 0; }

footer { background: var(--navy-deep); color: var(--on-navy-muted); font-family: var(--font-mono); font-size: 13px; }
footer .wrap { display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; gap: 12px 24px; padding-block: 24px; padding-bottom: calc(24px + env(safe-area-inset-bottom, 0px)); }
footer nav { display: flex; flex-wrap: wrap; gap: 6px 18px; }
footer a { text-decoration: none; }
footer a:hover { color: #fff; }

.to-top { position: fixed; right: max(16px, env(safe-area-inset-right, 0px)); bottom: calc(16px + env(safe-area-inset-bottom, 0px)); z-index: 15; width: 48px; height: 48px; border-radius: 50%; border: 0; display: grid; place-items: center; background: var(--scene); color: #0B1220; cursor: pointer; box-shadow: 0 8px 24px #00000044; opacity: 0; pointer-events: none; transform: translateY(12px); }
.to-top.show { opacity: 1; pointer-events: auto; transform: none; }
.to-top svg { width: 22px; height: 22px; stroke: currentColor; fill: none; stroke-width: 2.2; stroke-linecap: round; stroke-linejoin: round; }

.lightbox { position: fixed; inset: 0; z-index: 60; background: #050A14EB; display: grid; place-items: center; padding: calc(56px + env(safe-area-inset-top, 0px)) max(16px, env(safe-area-inset-right, 0px)) calc(24px + env(safe-area-inset-bottom, 0px)) max(16px, env(safe-area-inset-left, 0px)); }
.lightbox img { max-width: 100%; max-height: 100%; border-radius: 8px; background: #fff; }
.lb-close { position: absolute; top: calc(10px + env(safe-area-inset-top, 0px)); right: max(12px, env(safe-area-inset-right, 0px)); width: 44px; height: 44px; border-radius: 50%; border: 1px solid #ffffff55; background: #ffffff1a; color: #fff; font-size: 26px; line-height: 1; cursor: pointer; }

@media (max-width: 1060px) {
  :root { --nav-h: 108px; }
  .mark { flex: 1 1 auto; }
  .links { order: 3; flex: 1 1 100%; flex-wrap: nowrap; justify-content: space-between; gap: 6px; overflow-x: auto; padding: 4px 4px 10px; }
  .links a { flex: 1 1 auto; text-align: center; padding: 8px 10px; }
}
@media (max-width: 520px) {
  .links { font-family: var(--font-body); font-size: 14px; font-weight: 600; gap: 4px; }
  .links a { padding: 8px 6px; }
  .nav .hire-btn { padding: 10px 16px; font-size: 13px; }
}
@media (max-width: 900px) {
  .hero .wrap { grid-template-columns: minmax(0, 1fr); gap: 56px; padding-block: 40px 64px; }
  .portrait-col { order: -1; gap: 36px; }
  .portrait-col .portrait { width: min(76%, 330px); }
  .chip { font-size: 12px; padding: 7px 11px; }
  .chip.c1 { left: -4%; } .chip.c2 { right: -4%; } .chip.c3 { left: -4%; } .chip.c4 { right: 0; }
  .about .grid, .contact-grid { grid-template-columns: minmax(0, 1fr); gap: 36px; }
  section.pad { padding-block: 60px; }
  .edu { padding-block: 52px; }
  .stats .wrap { grid-template-columns: repeat(2, minmax(0, 1fr)); }
  .stat { border-left: 0; padding: 20px 12px 20px 0; border-top: 1px solid #ffffff18; }
  .stat:nth-child(-n+2) { border-top: 0; }
  .pf { padding: 20px; }
  .ghost { flex-direction: column; align-items: flex-start; }
  .g-lines { width: 100%; }
}
@media (prefers-reduced-motion: reduce) {
  html { scroll-behavior: auto; }
}
@media (prefers-reduced-motion: no-preference) {
  .btn, .icon-btn, .filters button, .tabs button, .links a, .to-top, .rm { transition: background .15s, filter .15s, color .15s, border-color .15s, opacity .2s, transform .2s; }
  .tile, .svc, .steps li, .focus li, .opt, .gig { transition: transform .2s, border-color .2s, background .2s; }
  .tile:hover, .svc:hover, .steps li:hover, .focus li:hover, .opt:hover, .gig:hover { transform: translateY(-4px); }
  .marquee .track { animation: slide 38s linear infinite; }
  .marquee:hover .track { animation-play-state: paused; }
  .gl { animation: pulse 1.8s ease-in-out infinite; }
  .portrait .ring { animation: spin 14s linear infinite; }
  .chip { animation: bob 5s ease-in-out infinite; }
  .chip.c2 { animation-delay: -1.2s; } .chip.c3 { animation-delay: -2.4s; } .chip.c4 { animation-delay: -3.6s; }
  .avail i { animation: ping 2s ease-out infinite; }
  .roles .caret { animation: blink 1s steps(1) infinite; }
  .portrait .photo { translate: calc(var(--px, 0) * 8px) calc(var(--py, 0) * 8px); transition: translate .25s ease-out; }
  .portrait .ring { translate: calc(var(--px, 0) * 8px) calc(var(--py, 0) * 8px); transition: translate .25s ease-out; }
  .portrait .chip { translate: calc(var(--px, 0) * 16px) calc(var(--py, 0) * 16px); transition: translate .25s ease-out; }
}
@keyframes blink { 50% { opacity: 0; } }
@keyframes slide { to { transform: translateX(-50%); } }
@keyframes pulse { 50% { opacity: .45; } }
@keyframes spin { to { transform: rotate(360deg); } }
@keyframes bob { 50% { transform: translateY(-8px); } }
@keyframes ping { 70% { box-shadow: 0 0 0 10px #2DE0C800; } 100% { box-shadow: 0 0 0 0 #2DE0C800; } }
@supports (animation-timeline: view()) {
  @media (prefers-reduced-motion: no-preference) {
    .reveal { animation: rise linear both; animation-timeline: view(); animation-range: entry 0% entry 40%; }
    @keyframes rise { from { opacity: .25; translate: 0 32px; } to { opacity: 1; translate: 0 0; } }
  }
}
</style>
<header class="nav">
<div class="wrap bar">
<a aria-label="Ahmed Nadeem Abbasi, back to top" class="mark" href="#top"><span aria-label="Portrait of Ahmed Nadeem Abbasi" class="avatar" role="img"></span><span>ahmed.abbasi</span></a>
<button aria-controls="menu" aria-expanded="false" aria-label="Open navigation menu" class="mobile-menu-toggle" id="mobile-menu-toggle" type="button"><span></span><span></span><span></span></button>
<nav aria-label="Sections" class="links" id="menu">
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#skill-levels">Skill levels</a>
<a href="#services">Services</a>
<a href="#portfolio">Portfolio</a>
<a href="#contact">Contact</a>
</nav>
<div class="tools">
<button aria-label="Switch between light and dark theme" class="icon-btn" id="theme" type="button">
<svg viewbox="0 0 24 24"><circle cx="12" cy="12" r="4.5"></circle><path d="M12 2v2M12 20v2M2 12h2M20 12h2M4.9 4.9l1.4 1.4M17.7 17.7l1.4 1.4M4.9 19.1l1.4-1.4M17.7 6.3l1.4-1.4"></path></svg>
</button>
<a class="hire-btn" href="#services">Start a project</a>
</div>
</div>
<div class="progress" id="progress"></div>
</header>
<main>
<section class="hero" data-hue="215" id="top">
<canvas aria-hidden="true" id="net"></canvas>
<div class="wrap">
<div>
<p class="avail"><i></i> Open to freelance data projects</p>
<p class="eyebrow hero-kicker">DATA SCIENCE  •  ANALYTICS  •  VISUAL STORIES</p>
<h1>Ahmed Nadeem <em>Abbasi</em></h1>
<p class="hero-role-line">Data Science Student<span class="role-divider"></span>Freelance Data Analyst</p>
<p class="lead">I clean messy data, explore patterns, and turn numbers into clear dashboards and visual stories. I use Python, SQL, Excel and Power BI to make data easier to understand.</p>
<ul class="tags"><li>Data Cleaning</li><li>Exploratory Analysis</li><li>Dashboards</li><li>Data Visualization</li></ul>
<div class="actions">
<a class="btn primary" href="#services">Start a project</a>
<a class="btn outline" href="#portfolio">View portfolio</a>
<a class="btn social-hero-link" href="https://www.upwork.com/freelancers/~017d2cc9f1eb11a37a" target="_blank" rel="noopener noreferrer">Upwork profile <span aria-hidden="true">↗</span></a>
</div>
</div>
<div class="portrait-col">
<div class="portrait">
<div class="glow"></div>
<div class="ring"></div>
<div aria-label="Portrait of Ahmed Nadeem Abbasi in a dark blazer and white shirt" class="photo" role="img"></div>
<div class="chip c1"><i></i>Python</div>
<div class="chip c2"><i></i>SQL</div>
<div class="chip c3"><i></i>Power BI</div>
<div class="chip c4"><i></i>Excel</div>
</div>
<div aria-label="Areas of focus" class="role-showcase">
<div class="role-showcase-top"><span class="role-live-dot"></span><span>MY FOCUS AREAS</span><span class="role-showcase-line"></span></div>
<p class="roles"><span aria-hidden="true" class="typed">Data Science Student</span><span aria-hidden="true" class="caret"></span></p>
<div class="role-pills"><span>Clean Data</span><span>Find Insights</span><span>Build Dashboards</span></div>
</div>
</div>
</div>
</section>
<div class="stats">
<div class="wrap">
<div class="stat"><b>7</b><span>Skills</span></div>
<div class="stat"><b>2</b><span>Programming languages</span></div>
<div class="stat"><b>3</b><span>Data tools</span></div>
<div class="stat"><b>1</b><span>Degree in progress</span></div>
</div>
</div>
<div aria-hidden="true" class="marquee">
<div class="track">
<ul><li>Python</li><li>SQL</li><li>Power BI</li><li>Excel</li><li>C++</li><li>Data Analysis</li><li>Data Visualization</li></ul>
<ul><li>Python</li><li>SQL</li><li>Power BI</li><li>Excel</li><li>C++</li><li>Data Analysis</li><li>Data Visualization</li></ul>
</div>
</div>
<section class="about pad" data-hue="215" id="about">
<div class="wrap">
<div class="grid">
<div class="text reveal">
<p class="eyebrow">About me</p>
<h2>From raw data to <span class="grad">real insights</span>.</h2>
<p>I am a Bachelor of Science in Data Science student who enjoys turning unorganized information into something useful. My focus is data cleaning, exploratory data analysis, reporting, dashboard design and data visualization.</p>
<p class="small">My toolkit includes Python for data tasks, SQL for querying, Excel for analysis and reporting, and Power BI for interactive dashboards. I am growing my portfolio through hands-on projects and practical learning.</p>
</div>
<aside aria-label="Profile summary" class="idcard reveal">
<div class="id-top">
<span aria-label="Portrait of Ahmed Nadeem Abbasi" class="id-avatar" role="img"></span>
<div class="id-who">
<p class="id-name">Ahmed Nadeem Abbasi</p>
<p class="id-role">Data Science Student · Freelancer</p>
</div>
<span class="id-live"><i></i> Freelance</span>
</div>
<dl class="id-rows">
<div><dt><span class="ic blue"><svg viewbox="0 0 24 24"><circle cx="12" cy="8" r="4"></circle><path d="M4 21c0-4 4-6 8-6s8 2 8 6"></path></svg></span>Role</dt><dd>Data Science Student · Freelance Data Analyst</dd></div>
<div><dt><span class="ic teal"><svg viewbox="0 0 24 24"><path d="M2 9l10-5 10 5-10 5z"></path><path d="M6 11v5c0 1.5 3 3 6 3s6-1.5 6-3v-5"></path></svg></span>Studying</dt><dd>Bachelor of Science in Data Science</dd></div>
<div><dt><span class="ic amber"><svg viewbox="0 0 24 24"><path d="M14.7 6.3a4 4 0 0 0-5.4 5.4L3 18l3 3 6.3-6.3a4 4 0 0 0 5.4-5.4l-3 3-2.4-.6-.6-2.4z"></path></svg></span>Tools</dt><dd class="id-chips"><span>Python</span><span>SQL</span><span>Excel</span><span>Power BI</span><span>C++</span></dd></div>
<div><dt><span class="ic coral"><svg viewbox="0 0 24 24"><circle cx="12" cy="12" r="9"></circle><circle cx="12" cy="12" r="4"></circle></svg></span>Services</dt><dd>Data cleaning, analysis, dashboards and visualization</dd></div>
<div><dt><span class="ic blue"><svg viewbox="0 0 24 24"><rect height="14" rx="2" width="18" x="3" y="5"></rect><path d="M3 7l9 6 9-6"></path></svg></span>Email</dt><dd>ahmedabbasiabbaci@gmail.com</dd></div>
</dl>
<div class="id-actions">
<a class="btn primary small" href="#services">View services</a>
<a class="btn line small" href="#contact">Send a message</a>
</div>
</aside>
</div>
<ul class="focus">
<li class="reveal">
<span class="ic blue"><svg viewbox="0 0 24 24"><path d="M8 7l-5 5 5 5M16 7l5 5-5 5"></path></svg></span>
<span>Programming<span class="sub">Python and C++</span></span>
</li>
<li class="reveal">
<span class="ic amber"><svg viewbox="0 0 24 24"><ellipse cx="12" cy="6" rx="8" ry="3"></ellipse><path d="M4 6v6c0 1.7 3.6 3 8 3s8-1.3 8-3V6M4 12v6c0 1.7 3.6 3 8 3s8-1.3 8-3v-6"></path></svg></span>
<span>Databases<span class="sub">SQL queries and data relationships</span></span>
</li>
<li class="reveal">
<span class="ic teal"><svg viewbox="0 0 24 24"><path d="M4 20V10M10 20V4M16 20v-7M22 20H2"></path></svg></span>
<span>Reporting<span class="sub">Power BI, Excel dashboards and charts</span></span>
</li>
</ul>
</div>
</section>
<section class="skills pad band-dark" data-hue="170" id="skills">
<div class="wrap">
<div class="section-head reveal">
<p class="eyebrow">A practical mix of programming, data preparation, analysis and visual reporting.</p>
<h2>My data <span class="grad">toolkit</span>.</h2>
<p>Pick a category to filter the list.</p>
</div>
<div aria-label="Filter skills by category" class="filters" role="group">
<button aria-pressed="true" data-filter="all" type="button">All</button>
<button aria-pressed="false" data-filter="programming" type="button">Programming</button>
<button aria-pressed="false" data-filter="tools" type="button">Data tools</button>
<button aria-pressed="false" data-filter="practice" type="button">Practice</button>
</div>
<div class="tiles" id="tiles">
<article class="tile blue reveal" data-cat="programming"><h3>Python</h3><p>Data cleaning, analysis and scripting.</p><span class="cat">Programming</span></article>
<article class="tile blue reveal" data-cat="programming"><h3>C++</h3><p>Structured programming and problem solving.</p><span class="cat">Programming</span></article>
<article class="tile amber reveal" data-cat="tools"><h3>SQL</h3><p>Querying and joining data in databases.</p><span class="cat">Data tools</span></article>
<article class="tile amber reveal" data-cat="tools"><h3>Excel</h3><p>Tables, formulas, pivot tables and reports.</p><span class="cat">Data tools</span></article>
<article class="tile amber reveal" data-cat="tools"><h3>Power BI</h3><p>Interactive dashboards and reports.</p><span class="cat">Data tools</span></article>
<article class="tile teal reveal" data-cat="practice"><h3>Data Analysis</h3><p>Finding trends, patterns and outliers.</p><span class="cat">Practice</span></article>
<article class="tile teal reveal" data-cat="practice"><h3>Data Visualization</h3><p>Charts that make results easy to read.</p><span class="cat">Practice</span></article>
<article class="tile teal reveal" data-cat="practice"><h3>Data Cleaning</h3><p>Preparing reliable datasets by handling missing values, duplicates and inconsistent formats.</p><span class="cat">Data practice</span></article><article class="tile teal reveal" data-cat="practice"><h3>Exploratory Data Analysis</h3><p>Using summaries and charts to spot trends, patterns and unusual values.</p><span class="cat">Data practice</span></article><article class="tile amber reveal" data-cat="practice"><h3>KPI Reporting</h3><p>Turning key measures into concise summaries that support decisions.</p><span class="cat">Data practice</span></article><article class="tile amber reveal" data-cat="tools"><h3>Excel PivotTables</h3><p>Summarizing and comparing data with formulas, tables and PivotTables.</p><span class="cat">Data tools</span></article><article class="tile blue reveal" data-cat="practice"><h3>Data Storytelling</h3><p>Explaining what charts and numbers mean in clear, simple language.</p><span class="cat">Data practice</span></article></div>
</div>
</section>
<section class="skill-levels pad" data-hue="195" id="skill-levels">
<div class="wrap">
<div class="section-head reveal">
<p class="eyebrow">Approximate self-assessment levels for my current learning and practice — not formal test scores.</p>
<h2>Skills in <span class="grad">progress</span></h2>
<p>Indicative self-assessment — update these percentages as your skills develop.</p>
</div>
<div class="skill-meter-grid">
<div class="skill-meter"><div class="meter-heading"><span>Python</span><strong>80%</strong></div><div class="meter-track"><span style="--level:80%"></span></div><small>Programming &amp; scripting</small></div>
<div class="skill-meter"><div class="meter-heading"><span>Excel</span><strong>90%</strong></div><div class="meter-track"><span style="--level:90%"></span></div><small>Formulas, tables &amp; reports</small></div>
<div class="skill-meter"><div class="meter-heading"><span>SQL</span><strong>75%</strong></div><div class="meter-track"><span style="--level:75%"></span></div><small>Queries &amp; databases</small></div>
<div class="skill-meter"><div class="meter-heading"><span>Power BI</span><strong>75%</strong></div><div class="meter-track"><span style="--level:75%"></span></div><small>Dashboards &amp; visualization</small></div>
<div class="skill-meter"><div class="meter-heading"><span>C++</span><strong>75%</strong></div><div class="meter-track"><span style="--level:75%"></span></div><small>Programming fundamentals</small></div>
<div class="skill-meter"><div class="meter-heading"><span>Data analysis</span><strong>80%</strong></div><div class="meter-track"><span style="--level:80%"></span></div><small>Exploration &amp; insights</small></div>
</div>
<p class="skill-note">Percentages are editable estimates, not formal test results or verified credentials.</p>
</div>
</section>
<section class="services pad band-tint" data-hue="45" id="services">
<div class="wrap">
<div class="section-head reveal">
<p class="eyebrow">Choose the kind of data task you need help with, and send a short project brief.</p>
<h2>Data services, made <span class="grad">clear</span>.</h2>
<p>Tap the services you want. Then press Continue and your request is written for you.</p>
</div>
<div class="gigs" id="gigs">
<article class="gig c-teal reveal" data-name="I will clean your data" data-on="false" data-tool="Excel">
<div class="top"><div class="ic teal"><svg viewbox="0 0 24 24"><path d="M3 4h18l-7 8v7l-4 2v-9z"></path></svg></div><span class="tool">Excel</span></div>
<h3>Data Cleaning &amp; Preparation</h3>
<p>Remove duplicates, fix errors and fill gaps so your data is ready to use.</p>
<button aria-pressed="false" class="pick" type="button">Add to request</button>
</article>
<article class="gig c-amber reveal" data-name="I will build your Excel reports" data-on="false" data-tool="Excel">
<div class="top"><div class="ic amber"><svg viewbox="0 0 24 24"><rect height="16" rx="2" width="18" x="3" y="4"></rect><path d="M3 10h18M3 15h18M9 4v16"></path></svg></div><span class="tool">Excel</span></div>
<h3>Excel Analysis &amp; Reports</h3>
<p>Formulas, pivot tables and clear summaries in one workbook.</p>
<button aria-pressed="false" class="pick" type="button">Add to request</button>
</article>
<article class="gig c-blue reveal" data-name="I will create your dashboard" data-on="false" data-tool="Power BI">
<div class="top"><div class="ic blue"><svg viewbox="0 0 24 24"><rect height="9" rx="1" width="7" x="3" y="3"></rect><rect height="5" rx="1" width="7" x="14" y="3"></rect><rect height="9" rx="1" width="7" x="14" y="12"></rect><rect height="5" rx="1" width="7" x="3" y="16"></rect></svg></div><span class="tool">Power BI</span></div>
<h3>Dashboard Design &amp; Visualization</h3>
<p>Interactive reports with filters and charts for your key numbers.</p>
<button aria-pressed="false" class="pick" type="button">Add to request</button>
</article>
<article class="gig c-coral reveal" data-name="I will write your SQL queries" data-on="false" data-tool="SQL">
<div class="top"><div class="ic coral"><svg viewbox="0 0 24 24"><ellipse cx="12" cy="6" rx="8" ry="3"></ellipse><path d="M4 6v6c0 1.7 3.6 3 8 3s8-1.3 8-3V6M4 12v6c0 1.7 3.6 3 8 3s8-1.3 8-3v-6"></path></svg></div><span class="tool">SQL</span></div>
<h3>SQL Queries &amp; Data Summaries</h3>
<p>Pull, join and summarise the records you need from a database.</p>
<button aria-pressed="false" class="pick" type="button">Add to request</button>
</article>
<article class="gig c-blue reveal" data-name="I will analyse your data" data-on="false" data-tool="Python">
<div class="top"><div class="ic blue"><svg viewbox="0 0 24 24"><circle cx="11" cy="11" r="7"></circle><path d="M21 21l-4.3-4.3"></path></svg></div><span class="tool">Python</span></div>
<h3>I will analyse your data</h3>
<p>Find trends, patterns and outliers, and explain what they mean.</p>
<button aria-pressed="false" class="pick" type="button">Add to request</button>
</article>
<article class="gig c-teal reveal" data-name="I will make your charts" data-on="false" data-tool="Power BI · Excel · Python">
<div class="top"><div class="ic teal"><svg viewbox="0 0 24 24"><path d="M12 3v9h9"></path><path d="M20.5 15A9 9 0 1 1 9 3.5"></path></svg></div><span class="tool">Power BI · Excel · Python</span></div>
<h3>I will make your charts</h3>
<p>Graphs and visuals that people understand at a glance.</p>
<button aria-pressed="false" class="pick" type="button">Add to request</button>
</article>
<article class="gig c-amber reveal" data-name="I will automate repetitive work" data-on="false" data-tool="Python">
<div class="top"><div class="ic amber"><svg viewbox="0 0 24 24"><path d="M13 2L4 14h7l-1 8 9-12h-7z"></path></svg></div><span class="tool">Python</span></div>
<h3>I will automate repetitive work</h3>
<p>Scripts that handle boring spreadsheet and file tasks for you.</p>
<button aria-pressed="false" class="pick" type="button">Add to request</button>
</article>
<article class="gig c-coral reveal" data-name="I will explain your results" data-on="false" data-tool="Data analysis">
<div class="top"><div class="ic coral"><svg viewbox="0 0 24 24"><path d="M21 12a8 8 0 0 1-11.6 7.1L4 20l1-4.6A8 8 0 1 1 21 12z"></path></svg></div><span class="tool">Data analysis</span></div>
<h3>I will explain your results</h3>
<p>A short summary in plain words that is ready to share.</p>
<button aria-pressed="false" class="pick" type="button">Add to request</button>
</article>
<article class="gig c-blue reveal" data-name="I will write or fix your C++ code" data-on="false" data-tool="C++">
<div class="top"><div class="ic blue"><svg viewbox="0 0 24 24"><path d="M8 7l-5 5 5 5M16 7l5 5-5 5"></path></svg></div><span class="tool">C++</span></div>
<h3>I will write or fix your C++ code</h3>
<p>Programs, problem solving and debugging in C++.</p>
<button aria-pressed="false" class="pick" type="button">Add to request</button>
</article>
</div>
<div aria-label="Your request" class="request-bar" hidden="" id="req-bar" role="region">
<div class="req-text"><b id="req-count">0 services selected</b><span id="req-names"></span></div>
<div class="req-actions">
<button class="btn line small light" id="req-clear" type="button">Clear</button>
<button class="btn primary small" id="req-go" type="button">Continue to message</button>
</div>
</div>
</div>
</section>
<section class="portfolio pad band-dark" data-hue="340" id="portfolio">
<div class="wrap">
<div class="section-head reveal">
<p class="eyebrow">A growing collection of practice projects, data workflows and learning milestones. Project examples are clearly labelled as practice.</p>
<h2>Projects that turn <span class="grad">data into insight</span>.</h2>
<p>Explore projects, learning goals and profile details. Choose a tab.</p>
</div>
<div aria-label="Portfolio sections" class="tabs" id="pf-tabs" role="tablist">
<button aria-controls="pf-panel" aria-selected="true" data-key="experience" id="tab-experience" role="tab" type="button">Freelance &amp; practice</button>
<button aria-controls="pf-panel" aria-selected="false" data-key="projects" id="tab-projects" role="tab" type="button">Projects</button>
<button aria-controls="pf-panel" aria-selected="false" data-key="certificates" id="tab-certificates" role="tab" type="button">Certificates &amp; learning</button>
<button aria-controls="pf-panel" aria-selected="false" data-key="awards" id="tab-awards" role="tab" type="button">Milestones</button>
<button aria-controls="pf-panel" aria-selected="false" data-key="languages" id="tab-languages" role="tab" type="button">Languages</button>
<button aria-controls="pf-panel" aria-selected="false" data-key="recommendations" id="tab-recommendations" role="tab" type="button">Recommendations</button>
</div>
<div aria-labelledby="tab-experience" class="pf" id="pf-panel" role="tabpanel"></div>
<p aria-live="polite" class="pf-status" id="pf-status" role="status"></p>
</div>
</section>
<section class="flow pad band-tint" data-hue="265" id="process">
<div class="wrap">
<div class="section-head reveal">
<p class="eyebrow">Process</p>
<h2>From raw data to a <span class="grad">clear result</span>.</h2>
<p>The four steps of a typical project and the tools used at each one.</p>
</div>
<ol class="steps">
<li class="reveal"><h3>Collect and clean</h3><p>Pull the data together and fix errors and gaps.</p><span class="tool">SQL · Python · Excel</span></li>
<li class="reveal"><h3>Analyse</h3><p>Look for trends, comparisons and outliers.</p><span class="tool">Python · Excel</span></li>
<li class="reveal"><h3>Visualize</h3><p>Turn the numbers into charts people can read quickly.</p><span class="tool">Power BI · Python</span></li>
<li class="reveal"><h3>Report</h3><p>Share the findings in a short, clear summary.</p><span class="tool">Power BI · Excel</span></li>
</ol>
</div>
</section>
<section class="hire pad band-dark" data-hue="20" id="hire">
<div class="wrap">
<div class="section-head reveal">
<p class="eyebrow">Freelance help for well-defined data tasks, from cleaning a spreadsheet to presenting findings in a dashboard.</p>
<h2>Let’s solve a <span class="grad">data problem</span>.</h2>
<p>Choose a freelance service and tell me what you need. The contact form will help you get started.</p>
</div>
<div class="options">
<article class="opt reveal">
<div class="ic blue"><svg viewbox="0 0 24 24"><rect height="16" rx="2" width="18" x="3" y="4"></rect><path d="M3 10h18M9 4v16"></path></svg></div>
<h3>Data Analysis &amp; Reports</h3>
<p>Turn raw spreadsheets into useful insights, clean summaries and easy-to-understand reports.</p>
<ul><li>Excel data cleaning and formulas</li><li>Charts, summaries and comparisons</li><li>Clear findings and deliverables</li></ul>
<button class="btn solid choose" data-reason="Data analysis and reports" type="button">Discuss a project</button>
</article>
<article class="opt reveal">
<div class="ic teal"><svg viewbox="0 0 24 24"><path d="M3 3h18v18H3zM3 9h18M9 21V9"></path></svg></div>
<h3>Dashboards &amp; Visualization</h3>
<p>Present key numbers in attractive dashboards and visuals that are easier to understand.</p>
<ul><li>Excel dashboards</li><li>Power BI visuals and KPIs</li><li>Clean, readable layouts</li></ul>
<button class="btn solid choose" data-reason="Dashboard development" type="button">Build a dashboard</button>
</article>
<article class="opt reveal">
<div class="ic amber"><svg viewbox="0 0 24 24"><path d="M8 6l-6 6 6 6M16 6l6 6-6 6M14 3l-4 18"></path></svg></div>
<h3>Python Development</h3>
<p>Small Python scripts and beginner-friendly coding solutions tailored to a clear task.</p>
<ul><li>Data processing and automation</li><li>Simple scripts and utilities</li><li>Code cleanup and explanations</li></ul>
<button class="btn solid choose" data-reason="Python development" type="button">Discuss Python work</button>
</article>
</div>
<h3 class="faq-title reveal">Common questions</h3>
<div class="faq reveal">
<details>
<summary>What do you need from me to begin?</summary>
<p>A short description of what you want to find out, the data you have (or a small sample), and when you need the result.</p>
</details>
<details>
<summary>Which tools do you use?</summary>
<p>Python and C++ for code, SQL for databases, Excel for spreadsheets and Power BI for dashboards.</p>
</details>
<details>
<summary>What will I receive at the end?</summary>
<p>A short summary of the findings in plain language, plus the working files, for example an Excel workbook, a SQL script or a Power BI report.</p>
</details>
<details>
<summary>How do I get in touch?</summary>
<p>Use the form in the contact section or write to ahmedabbasiabbaci@gmail.com. You can also find me on LinkedIn as AHMED ABBASI.</p>
</details>
</div>
</div>
</section>
<section class="edu" id="education">
<div class="wrap">
<p class="eyebrow">Education</p>
<div class="row">
<div>
<h2>Bachelor of Science in Data Science</h2>
<p class="sub">Programming, databases, analysis and visualization.</p>
</div>
<span class="badge">Currently studying</span>
</div>
</div>
</section>
<section class="contact pad" id="contact">
<div class="wrap">
<div class="section-head">
<p class="eyebrow">Need a dataset cleaned, an analysis summarized, or a dashboard designed? Tell me about your data task and let’s discuss the scope.</p>
<h2>Have an idea? <span class="grad">Let's connect.</span></h2>
<p>Have a freelance project, need a dashboard, or want help with Python or data? Send me the details.</p>
</div>
<div class="profile-links-strip" aria-label="Professional profiles">
  <a class="profile-link-card linkedin-link" href="https://www.linkedin.com/public-profile/settings/" target="_blank" rel="noopener noreferrer">
    <span class="profile-link-icon" aria-hidden="true">in</span><span class="profile-link-copy"><b>LinkedIn</b><small>Professional profile</small></span><span class="profile-link-arrow" aria-hidden="true">↗</span>
  </a>
  <a class="profile-link-card upwork-link" href="https://www.upwork.com/freelancers/~017d2cc9f1eb11a37a" target="_blank" rel="noopener noreferrer">
    <span class="profile-link-icon" aria-hidden="true">U</span><span class="profile-link-copy"><b>Upwork</b><small>Freelance data services</small></span><span class="profile-link-arrow" aria-hidden="true">↗</span>
  </a>
</div>
<div class="contact-grid">
<div class="c-stack">
<div class="c-card">
<p class="label">Email</p>
<a class="value" href="mailto:ahmedabbasiabbaci@gmail.com" id="email-text">ahmedabbasiabbaci@gmail.com</a>
<div class="btns">
<button class="btn outline" id="copy-email" type="button">Copy address</button>
</div>
</div>
<div class="c-card contact-highlight">
<p class="label">Freelance services</p>
<h3>Let's build something useful.</h3>
<p class="contact-description">I take on clearly defined freelance data tasks: data cleaning, exploratory analysis, Excel reporting, SQL summaries, and dashboard visualization. Share your goal and what format you need.</p>
<span class="contact-pill">Data Cleaning · Analysis · Dashboards · Visualization</span>
</div>
<div class="c-card">
<p class="label">LinkedIn</p>
<span class="value">Ahmed Abbasi</span>
<div class="btns">
<a class="btn outline" href="https://www.linkedin.com/public-profile/settings/" rel="noopener noreferrer" target="_blank">Open LinkedIn</a>
</div>
</div>
<div class="c-card social-profile-card upwork-card">
<p class="label">UPWORK PROFILE</p>
<h3 class="social-card-title">Work with me</h3>
<p class="social-card-copy">Explore my freelance profile and connect for data cleaning, analysis, reporting, and dashboard projects.</p>
<div class="btns">
<a class="btn primary" href="https://www.upwork.com/freelancers/~017d2cc9f1eb11a37a" rel="noopener noreferrer" target="_blank">Visit Upwork profile <span aria-hidden="true">↗</span></a>
</div>
</div>
<div class="contact-options-card">
<div class="contact-options-heading"><span class="contact-options-icon">✦</span><div><p class="label">QUICK CONTACT</p><h3>Pick your topic</h3></div></div>
<div class="contact-option-grid">
<button class="contact-option choose" data-reason="Project" type="button"><span class="option-symbol">↗</span><span><b>Project inquiry</b><small>Dashboard, report or data task</small></span><span class="option-arrow">→</span></button>
<button class="contact-option choose" data-reason="Python development" type="button"><span class="option-symbol">⌘</span><span><b>Python development</b><small>Scripts, tools and data tasks</small></span><span class="option-arrow">→</span></button>
<button class="contact-option choose" data-reason="Collaboration" type="button"><span class="option-symbol">＋</span><span><b>Collaboration</b><small>Build or learn together</small></span><span class="option-arrow">→</span></button>
<button class="contact-option choose" data-reason="Question about data" type="button"><span class="option-symbol">?</span><span><b>Ask a question</b><small>Data tools and analytics</small></span><span class="option-arrow">→</span></button>
</div>
<p class="contact-options-foot">Select an option to pre-fill the message form.</p>
</div>
</div>
<form class="c-card" id="composer" novalidate="">
<h3>Tell me what you have in mind <span class="form-spark">✦</span></h3>
<div class="field">
<label for="f-name">Your name</label>
<input autocomplete="name" id="f-name" placeholder="Your full name" type="text"/>
</div>
<div class="field">
<label for="f-email">Your email (optional)</label>
<input autocomplete="email" id="f-email" placeholder="you@example.com" type="email"/>
</div>
<div class="field">
<label for="f-reason">Reason</label>
<select id="f-reason">
<option>Project</option>
<option>Python development</option>
<option>Question about data</option>
<option>Collaboration</option>
<option>Data analysis and reports</option>
<option>Dashboard development</option>
<option>Something else</option>
</select>
</div>
<div class="field">
<label for="f-msg">Message</label>
<textarea id="f-msg" placeholder="Tell me what you need."></textarea>
</div>
<div style="display:flex;flex-wrap:wrap;gap:10px">
<a class="btn primary" href="mailto:ahmedabbasiabbaci@gmail.com" id="send-mail">Open in email</a>
<button class="btn outline" id="copy-msg" type="button">Copy message</button>
</div>
<p aria-live="polite" class="status" id="status" role="status"></p>
<p class="hint">If your email app does not open, copy the message and send it to the address on the left.</p>
</form>
</div>
</div>
</section>
</main>
<footer>
<div class="wrap">
<span>Ahmed Nadeem Abbasi · Data Science &amp; Analytics Portfolio · 2026</span>
<nav aria-label="Footer">
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#portfolio">Portfolio</a>
<a href="#process">Process</a>
<a href="#hire">Work with me</a>
<a href="#education">Education</a>
<a href="#contact">Contact</a>
<a href="#top">Back to top</a>
</nav>
</div>
</footer>
<button aria-label="Back to top" class="to-top" id="to-top" type="button">
<svg viewbox="0 0 24 24"><path d="M12 19V5M5 12l7-7 7 7"></path></svg>
</button>
<div aria-label="Certificate preview" aria-modal="true" class="lightbox" hidden="" id="lightbox" role="dialog">
<button aria-label="Close preview" class="lb-close" id="lb-close" type="button">×</button>
<img alt="" id="lb-img"/>
</div>
<script>
(function () {
  var root = document.documentElement;
  var EMAIL = 'ahmedabbasiabbaci@gmail.com';
  var KEYS = ['experience', 'projects', 'certificates', 'awards', 'languages', 'recommendations'];

  /* ---------- portfolio data (data/profile.json) ---------- */
  var META = {
    experience: { label: 'Freelance & practice', single: 'project', color: 'blue',
      msg: 'Hands-on practice projects and freelance deliverables. Practice work is labelled clearly; add real client projects as they are completed.',
      icon: '<rect x="3" y="7" width="18" height="13" rx="2"/><path d="M8 7V5a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2M3 13h18"/>',
      f: { title: 'Project title', org: 'Client or tools', date: 'Date', text: 'Project details and deliverables', link: 'Project link', file: 'Project image or PDF' } },
    projects: { label: 'Projects', single: 'project', color: 'amber',
      msg: 'Data projects and dashboards will be listed here.',
      icon: '<path d="M3 7a2 2 0 0 1 2-2h4l2 2h8a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/>',
      f: { title: 'Project name', org: 'Tools used', date: 'Date', text: 'What it does and what you found', link: 'Project link', file: 'Picture or PDF' } },
    certificates: { label: 'Certificates', single: 'certificate', color: 'teal',
      msg: 'Certificates and licenses, with issuer and date, will be listed here.',
      icon: '<circle cx="12" cy="9" r="6"/><path d="M8.5 14.5L7 22l5-3 5 3-1.5-7.5"/>',
      f: { title: 'Certificate name', org: 'Issued by', date: 'Issue date', text: 'Notes (optional)', link: 'Credential link', file: 'Certificate picture or PDF' } },
    awards: { label: 'Awards', single: 'award', color: 'coral',
      msg: 'Honors, awards and achievements will be listed here.',
      icon: '<path d="M8 21h8M12 17v4M7 4h10v5a5 5 0 0 1-10 0zM17 5h3v2a3 3 0 0 1-3 3M7 5H4v2a3 3 0 0 0 3 3"/>',
      f: { title: 'Award or achievement', org: 'Given by', date: 'Date', text: 'Details', link: false, file: 'Picture or PDF' } },
    languages: { label: 'Languages', single: 'language', color: 'blue',
      msg: 'Spoken languages will be listed here.',
      icon: '<circle cx="12" cy="12" r="9"/><path d="M3 12h18M12 3c3 3.5 3 14.5 0 18M12 3c-3 3.5-3 14.5 0 18"/>',
      f: { title: 'Language', org: 'Level (for example Native or Fluent)', date: false, text: false, link: false, file: false } },
    recommendations: { label: 'Recommendations', single: 'recommendation', color: 'amber',
      msg: 'Recommendations from teachers, managers and clients will be listed here.',
      icon: '<path d="M21 12a8 8 0 0 1-11.6 7.1L4 20l1-4.6A8 8 0 1 1 21 12z"/>',
      f: { title: 'Name of the person', org: 'Their role and company', date: 'Date', text: 'What they said', link: false, file: false } }
  };
  var PDF_ICON = '<svg viewBox="0 0 24 24"><path d="M6 3h8l5 5v13H6z"/><path d="M14 3v5h5M9 14h6M9 17h6"/></svg>';
  var DATA = empty();
  /* Honest portfolio entries: student practice projects are not presented as paid client experience. */
  DATA.experience = [
    {id:'data-cleaning-workflow', title:'Data Cleaning & Preparation Workflow', org:'Python · Excel', date:'Independent practice project', text:'A hands-on workflow for inspecting a sample dataset, checking missing values, removing duplicates, standardizing formats and preparing a clean version for analysis. Add screenshots and actual outputs after completing the workflow.', link:''},
    {id:'dashboard-case-study', title:'Dashboard & Visualization Case Study', org:'Excel · Power BI', date:'Independent practice project', text:'A portfolio case study concept focused on selecting useful KPIs, building clear visuals and summarizing trends. Replace this note with your completed dashboard, screenshots and findings when ready.', link:''}
  ];
  DATA.projects = [
    {id:'sample-sales-dashboard', title:'Sales Insights Dashboard', org:'Excel · Power BI', date:'Practice case study', text:'Analyze a sample sales dataset, compare monthly performance, identify top products and show key KPIs in an interactive dashboard. Add your own screenshots and verified findings after completing the project.', link:''},
    {id:'sample-student-results', title:'Student Results Data Analysis', org:'Python · Excel', date:'Practice case study', text:'Clean a sample results dataset, calculate summary statistics, compare subject performance and communicate the main patterns with charts.', link:''},
    {id:'sample-sql-analysis', title:'SQL Data Exploration', org:'SQL', date:'Practice case study', text:'Use SELECT, filtering, joins, grouping and aggregate functions to answer questions from a sample database and create useful summary tables.', link:''}
  ];
  DATA.certificates = [
    {id:'learn-excel', title:'Excel for Data Analysis', org:'Suggested course · Microsoft Learn / course provider', date:'Learning path · Not a claimed credential', text:'Focus on formulas, tables, PivotTables, charts and data cleaning. Add the real certificate image and credential link after completing a course.'},
    {id:'learn-python', title:'Python Fundamentals', org:'Suggested course · Cisco Networking Academy / course provider', date:'Learning path · Not a claimed credential', text:'Build confidence with variables, conditions, loops, functions and basic data handling. Replace this card with a real earned certificate when available.'},
    {id:'learn-powerbi', title:'Power BI Basics', org:'Suggested course · Microsoft Learn', date:'Learning path · Not a claimed credential', text:'Learn to import data, create relationships, build visuals and publish a simple report. This is a suggested learning goal, not a verified certificate.'}
  ];
  DATA.awards = [
    {id:'achievement-practice', title:'Data Portfolio in Progress', org:'Personal learning milestone', date:'Ongoing', text:'Building a collection of data cleaning, analysis, SQL and dashboard projects. This is a learning milestone, not a formal award or certificate.'}
  ];
  DATA.languages = [
    {id:'lang-urdu', title:'Urdu', org:'Native / Fluent'},
    {id:'lang-english', title:'English', org:'Basic'}
  ];
  var LOCAL = {};
  var EDIT = false, current = 'experience', formOpen = false, busy = false;
  var panel = document.getElementById('pf-panel');
  var pfStatus = document.getElementById('pf-status');
  var tabs = document.querySelectorAll('#pf-tabs button');

  function empty() { var d = {}; KEYS.forEach(function (k) { d[k] = []; }); return d; }
  function clone(o) { return JSON.parse(JSON.stringify(o)); }
  function esc(s) { return String(s == null ? '' : s).replace(/[&<>"']/g, function (c) { return { '&': '&amp;', '<': '&lt;', '>': '&gt;', '"': '&quot;', "'": '&#39;' }[c]; }); }
  function safeUrl(u) { return /^https?:\/\//i.test(u || '') ? u : ''; }
  function safePath(p) { return /^files\/[A-Za-z0-9._-]+$/.test(p || '') ? p : ''; }
  function fileUrl(f) { return LOCAL[f.path] || f.path; }
  function say(msg) { pfStatus.textContent = msg; }

  function mediaHtml(e, big) {
    if (!e.file || !safePath(e.file.path)) return '';
    var url = esc(fileUrl(e.file));
    if (e.file.kind === 'pdf') {
      if (big) return '<a class="media" href="' + url + '" target="_blank" rel="noopener"><span class="pdf-tile">' + PDF_ICON + '<span>PDF certificate</span></span></a>';
      return '<p><a class="lnk" href="' + url + '" target="_blank" rel="noopener">Open PDF</a></p>';
    }
    var img = '<img src="' + url + '" alt="' + esc(e.title) + '" loading="lazy">';
    if (big) return '<button type="button" class="media zoom" data-src="' + url + '" data-alt="' + esc(e.title) + '" aria-label="View ' + esc(e.title) + ' larger">' + img + '</button>';
    return '<button type="button" class="thumb-sm zoom" data-src="' + url + '" data-alt="' + esc(e.title) + '" aria-label="View ' + esc(e.title) + ' larger">' + img + '</button>';
  }
  function rmHtml(e) { return EDIT ? '<button type="button" class="rm" data-id="' + esc(e.id) + '">Remove</button>' : ''; }
  function linkHtml(e, label) { var u = safeUrl(e.link); return u ? '<p><a class="lnk" href="' + esc(u) + '" target="_blank" rel="noopener">' + esc(label) + '</a></p>' : ''; }

  function formHtml(key) {
    var m = META[key], f = m.f, h = '';
    h += '<form class="entry-form" id="entry-form" novalidate><h3>Add ' + esc(m.single) + '</h3>';
    h += '<div class="form-row"><div class="field"><label for="x-title">' + esc(f.title) + '</label><input id="x-title" name="title" type="text" maxlength="120" required></div>';
    if (f.org) h += '<div class="field"><label for="x-org">' + esc(f.org) + '</label><input id="x-org" name="org" type="text" maxlength="120"></div>';
    h += '</div>';
    if (f.date) h += '<div class="field"><label for="x-date">' + esc(f.date) + '</label><input id="x-date" name="date" type="text" maxlength="60" placeholder="For example Mar 2026"></div>';
    if (f.text) h += '<div class="field"><label for="x-text">' + esc(f.text) + '</label><textarea id="x-text" name="text" maxlength="1200"></textarea></div>';
    if (f.link) h += '<div class="field"><label for="x-link">' + esc(f.link) + '</label><input id="x-link" name="link" type="url" inputmode="url" placeholder="https://"></div>';
    if (f.file) h += '<div class="field"><label for="x-file">' + esc(f.file) + '</label><input id="x-file" name="file" type="file" accept="image/*,application/pdf"></div>';
    h += '<div class="form-actions"><button class="btn solid small" type="submit" id="x-save">Save</button><button class="btn line small" type="button" id="x-cancel">Cancel</button></div>';
    h += '<p class="form-note" id="x-note">Saved entries appear for everyone who opens this page.</p></form>';
    return h;
  }

  function render() {
    var items = DATA[current] || [], m = META[current], h = '';
    if (EDIT) {
      h += '<div class="owner-bar"><span>Owner mode. Add ' + esc(m.single) + ' entries here and they appear for every visitor.</span>' +
        '<button type="button" class="btn solid small" id="add-toggle">' + (formOpen ? 'Close form' : 'Add ' + esc(m.single)) + '</button></div>';
      if (formOpen) h += formHtml(current);
    }
    if (!items.length) {
      h += '<div class="ghost"><div class="ic ' + m.color + '"><svg viewBox="0 0 24 24">' + m.icon + '</svg></div>' +
        '<div class="g-lines"><span class="gl w60"></span><span class="gl w40"></span><span class="gl w80"></span></div></div>' +
        '<p class="g-msg">' + esc(m.msg) + '</p>' +
        '<p class="g-sub">Want to know more now? <a href="#contact">Send me a message</a>.</p>';
    } else if (current === 'languages') {
      h += '<ul class="lang-list">' + items.map(function (e) {
        return '<li>' + esc(e.title) + (e.org ? '<small>' + esc(e.org) + '</small>' : '') + (EDIT ? ' ' + rmHtml(e) : '') + '</li>';
      }).join('') + '</ul>';
    } else if (current === 'certificates') {
      h += '<div class="cert-grid">' + items.map(function (e) {
        var artColors = ['#146C94,#19A7CE', '#5432A8,#8D6BFF', '#087F5B,#38B98A'];
        var artColor = artColors[items.indexOf(e) % artColors.length];
        var art = '<div class="media cert-art" role="img" aria-label="Illustration for ' + esc(e.title) + '"><svg viewBox="0 0 640 360" aria-hidden="true"><defs><linearGradient id="cg' + items.indexOf(e) + '" x1="0" y1="0" x2="1" y2="1"><stop stop-color="' + artColor.split(',')[0] + '"/><stop offset="1" stop-color="' + artColor.split(',')[1] + '"/></linearGradient></defs><rect width="640" height="360" rx="18" fill="url(#cg' + items.indexOf(e) + ')"/><circle cx="545" cy="62" r="100" fill="#fff" opacity=".08"/><circle cx="75" cy="330" r="130" fill="#fff" opacity=".07"/><rect x="56" y="38" width="528" height="284" rx="14" fill="#fff" opacity=".96"/><rect x="74" y="56" width="492" height="248" rx="8" fill="none" stroke="' + artColor.split(',')[0] + '" stroke-width="2"/><path d="M292 86h56M320 74v24" stroke="' + artColor.split(',')[0] + '" stroke-width="3" stroke-linecap="round"/><circle cx="320" cy="132" r="28" fill="' + artColor.split(',')[0] + '" opacity=".12"/><path d="M307 132l9 9 18-20" fill="none" stroke="' + artColor.split(',')[0] + '" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/><text x="320" y="188" text-anchor="middle" font-family="Arial,sans-serif" font-size="15" font-weight="700" fill="' + artColor.split(',')[0] + '" letter-spacing="3">LEARNING PATH</text><text x="320" y="222" text-anchor="middle" font-family="Arial,sans-serif" font-size="23" font-weight="700" fill="#17233B">' + esc(e.title).replace(/&amp;/g, '&amp;') + '</text><text x="320" y="250" text-anchor="middle" font-family="Arial,sans-serif" font-size="13" fill="#637083">SUGGESTED COURSE • NOT A VERIFIED CERTIFICATE</text><path d="M260 273h120" stroke="' + artColor.split(',')[0] + '" stroke-width="2" opacity=".45"/></svg></div>';
        var media = mediaHtml(e, true) || art;
        return '<article class="cert entry">' + media + '<div class="body"><h3>' + esc(e.title) + '</h3>' +
          (e.org ? '<div class="org">' + esc(e.org) + '</div>' : '') + (e.date ? '<div class="date">' + esc(e.date) + '</div>' : '') +
          (e.text ? '<p>' + esc(e.text) + '</p>' : '') + linkHtml(e, 'Verify credential') + rmHtml(e) + '</div></article>';
      }).join('') + '</div>';
    } else {
      h += '<ol class="timeline">' + items.map(function (e) {
        return '<li class="entry"><h3>' + esc(e.title) + '</h3>' +
          (e.org ? '<div class="org">' + esc(e.org) + '</div>' : '') + (e.date ? '<div class="date">' + esc(e.date) + '</div>' : '') +
          (e.text ? '<p' + (current === 'recommendations' ? ' class="quote"' : '') + '>' + esc(e.text) + '</p>' : '') +
          linkHtml(e, 'Open link') + mediaHtml(e, false) + rmHtml(e) + '</li>';
      }).join('') + '</ol>';
    }
    panel.innerHTML = h;
  }
  function renderTabs() {
    Array.prototype.forEach.call(tabs, function (t) {
      var k = t.getAttribute('data-key'), n = (DATA[k] || []).length;
      t.innerHTML = esc(META[k].label) + (n ? '<span class="n">' + n + '</span>' : '');
    });
  }
  Array.prototype.forEach.call(tabs, function (t) {
    t.addEventListener('click', function () {
      current = t.getAttribute('data-key'); formOpen = false; say('');
      Array.prototype.forEach.call(tabs, function (x) { x.setAttribute('aria-selected', x === t ? 'true' : 'false'); });
      panel.setAttribute('aria-labelledby', t.id);
      render();
    });
  });

  /* ---------- saving (owner only) ---------- */
  function errorText(err) {
    var c = err && err.code;
    if (c === 'not_writer' || c === 'not_granted' || c === 'capability_disabled' || c === 'not_declared' || c === 'consent_required' || c === 'capability_removed')
      return 'Saving is not available in this view. Send the certificate or details to Claude in the chat and they will be added for you.';
    if (c === 'conflict') return 'The page was updated somewhere else. Reload the page and add it again.';
    if (c === 'too_large') return 'That file is too large. Use a picture or PDF under 8 MB.';
    if (c === 'rate_limited') return 'Too many saves in a row. Wait a moment and try again.';
    if (c === 'bad_type') return 'Choose a picture (JPG or PNG) or a PDF file.';
    return 'Saving failed. Try again in a moment.';
  }
  function setBusy(b, note) {
    busy = b;
    var s = document.getElementById('x-save'), n = document.getElementById('x-note');
    if (s) s.disabled = b;
    if (n && note) n.textContent = note;
  }
  function resizeImage(file) {
    return new Promise(function (resolve, reject) {
      var url = URL.createObjectURL(file), img = new Image();
      img.onload = function () {
        var max = 1600, w = img.naturalWidth, h = img.naturalHeight, s = Math.min(1, max / Math.max(w, h));
        var c = document.createElement('canvas'); c.width = Math.round(w * s); c.height = Math.round(h * s);
        var g = c.getContext('2d'); g.fillStyle = '#fff'; g.fillRect(0, 0, c.width, c.height); g.drawImage(img, 0, 0, c.width, c.height);
        URL.revokeObjectURL(url);
        c.toBlob(function (b) { b ? resolve({ blob: b, ext: 'jpg', kind: 'image', type: 'image/jpeg' }) : reject({ code: 'bad_type' }); }, 'image/jpeg', 0.86);
      };
      img.onerror = function () { URL.revokeObjectURL(url); reject({ code: 'bad_type' }); };
      img.src = url;
    });
  }
  function prepareFile(file) {
    if (/^image\//.test(file.type)) return resizeImage(file);
    if (file.type === 'application/pdf') {
      if (file.size > 8 * 1024 * 1024) return Promise.reject({ code: 'too_large' });
      return Promise.resolve({ blob: file, ext: 'pdf', kind: 'pdf', type: 'application/pdf' });
    }
    return Promise.reject({ code: 'bad_type' });
  }
  function getArtifact() {
    if (!(window.claude && window.claude.use)) return Promise.reject({ code: 'not_granted' });
    return window.claude.use('artifact').then(function (a) { if (!a) throw { code: 'not_granted' }; return a; });
  }
  function jsonFile(d) { return { content: JSON.stringify(d), contentType: 'application/json' }; }

  function saveEntry(form) {
    if (busy) return;
    var fs = form.elements, title = fs.title.value.trim();
    if (!title) { setBusy(false, 'Add a title first.'); return; }
    var link = fs.link ? fs.link.value.trim() : '';
    if (link && !safeUrl(link)) { setBusy(false, 'The link must start with https://'); return; }
    var entry = { id: 'e' + Date.now().toString(36), title: title,
      org: fs.org ? fs.org.value.trim() : '', date: fs.date ? fs.date.value.trim() : '',
      text: fs.text ? fs.text.value.trim() : '', link: link };
    var picked = fs.file && fs.file.files && fs.file.files[0], files = {}, blob = null;
    setBusy(true, 'Saving...');
    var work = picked ? prepareFile(picked) : Promise.resolve(null);
    work.then(function (p) {
      if (p) {
        var path = 'files/' + current + '-' + Date.now().toString(36) + '.' + p.ext;
        entry.file = { path: path, kind: p.kind, name: picked.name };
        files[path] = { content: p.blob, contentType: p.type }; blob = p.blob;
      }
      var next = clone(DATA); next[current].unshift(entry);
      files['data/profile.json'] = jsonFile(next);
      return getArtifact().then(function (a) { return a.publish(files); }).then(function () {
        if (blob) LOCAL[entry.file.path] = URL.createObjectURL(blob);
        DATA = next; formOpen = false; busy = false; render(); renderTabs(); say('Saved. Visitors will see it the next time they open this page.');
      });
    }).catch(function (err) { setBusy(false, errorText(err)); });
  }
  function removeEntry(id) {
    if (busy) return;
    var item = (DATA[current] || []).filter(function (e) { return e.id === id; })[0];
    if (!item) return;
    var next = clone(DATA); next[current] = next[current].filter(function (e) { return e.id !== id; });
    var files = { 'data/profile.json': jsonFile(next) };
    if (item.file && safePath(item.file.path)) files[item.file.path] = null;
    busy = true; say('Removing...');
    getArtifact().then(function (a) { return a.publish(files); }).then(function () {
      DATA = next; busy = false; render(); renderTabs(); say('Removed.');
    }).catch(function (err) { busy = false; say(errorText(err)); });
  }

  panel.addEventListener('click', function (e) {
    var t = e.target;
    if (t.closest('#add-toggle')) { formOpen = !formOpen; render(); var i = document.getElementById('x-title'); if (i) i.focus(); return; }
    if (t.closest('#x-cancel')) { formOpen = false; render(); return; }
    var z = t.closest('.zoom');
    if (z) { openBox(z.getAttribute('data-src'), z.getAttribute('data-alt')); return; }
    var r = t.closest('.rm');
    if (r) {
      if (r.getAttribute('data-armed') === 'true') { removeEntry(r.getAttribute('data-id')); return; }
      r.setAttribute('data-armed', 'true'); r.textContent = 'Click again to remove';
      setTimeout(function () { if (r.isConnected) { r.removeAttribute('data-armed'); r.textContent = 'Remove'; } }, 3000);
    }
  });
  panel.addEventListener('submit', function (e) { if (e.target.id === 'entry-form') { e.preventDefault(); saveEntry(e.target); } });

  /* lightbox */
  var lb = document.getElementById('lightbox'), lbImg = document.getElementById('lb-img'), lastFocus = null;
  function openBox(src, alt) { lastFocus = document.activeElement; lbImg.src = src; lbImg.alt = alt || ''; lb.hidden = false; document.getElementById('lb-close').focus(); }
  function closeBox() { lb.hidden = true; lbImg.removeAttribute('src'); if (lastFocus && lastFocus.focus) lastFocus.focus(); }
  document.getElementById('lb-close').addEventListener('click', closeBox);
  lb.addEventListener('click', function (e) { if (e.target === lb) closeBox(); });
  document.addEventListener('keydown', function (e) { if (e.key === 'Escape' && !lb.hidden) closeBox(); });

  /* load data, then detect owner */
  render(); renderTabs();
  fetch('data/profile.json', { cache: 'no-store' }).then(function (r) { return r.ok ? r.json() : null; })
    .then(function (d) { if (d) { var base = empty(); KEYS.forEach(function (k) { if (Array.isArray(d[k])) base[k] = d[k]; }); DATA = base; } })
    .catch(function () {})
    .then(function () {
      render(); renderTabs();
      if (window.claude && window.claude.use) {
        window.claude.use('user').then(function (u) {
          if (u && u.canEdit && u.canEdit()) { EDIT = true; render(); }
        }).catch(function () {});
      }
    });

  /* ---------- theme switch ---------- */
  function isDark() {
    var t = root.getAttribute('data-theme');
    if (t) return t === 'dark';
    return window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches;
  }
  try { var saved = localStorage.getItem('aa-theme'); if (saved) root.setAttribute('data-theme', saved); } catch (e) {}
  document.getElementById('theme').addEventListener('click', function () {
    var next = isDark() ? 'light' : 'dark';
    root.setAttribute('data-theme', next);
    try { localStorage.setItem('aa-theme', next); } catch (e) {}
  });

  /* ---------- mobile menu ---------- */
  var menu = document.getElementById('menu');
  function centerLink(a) {
    if (menu.scrollWidth <= menu.clientWidth + 2) return;
    var r = a.getBoundingClientRect(), m = menu.getBoundingClientRect();
    menu.scrollLeft += (r.left - m.left) - (m.width - r.width) / 2;
  }

  /* ---------- active section in nav ---------- */
  var links = {};
  Array.prototype.forEach.call(menu.querySelectorAll('a'), function (a) { links[a.getAttribute('href').slice(1)] = a; });
  if ('IntersectionObserver' in window) {
    var io = new IntersectionObserver(function (entries) {
      entries.forEach(function (en) {
        if (en.isIntersecting && links[en.target.id]) {
          Object.keys(links).forEach(function (k) { links[k].removeAttribute('aria-current'); });
          links[en.target.id].setAttribute('aria-current', 'true');
          centerLink(links[en.target.id]);
        }
      });
    }, { rootMargin: '-45% 0px -50% 0px' });
    Object.keys(links).forEach(function (id) { var el = document.getElementById(id); if (el) io.observe(el); });
  }

  /* ---------- scroll colour ---------- */
  var stops = [];
  var progress = document.getElementById('progress');
  var toTop = document.getElementById('to-top');
  function measure() {
    stops = Array.prototype.map.call(document.querySelectorAll('[data-hue]'), function (el) {
      var r = el.getBoundingClientRect();
      return { c: r.top + window.pageYOffset + r.height / 2, h: parseFloat(el.getAttribute('data-hue')) };
    });
  }
  function hueAt(y) {
    if (!stops.length) return 215;
    if (y <= stops[0].c) return stops[0].h;
    var last = stops[stops.length - 1];
    if (y >= last.c) return last.h;
    for (var i = 0; i < stops.length - 1; i++) {
      var a = stops[i], b = stops[i + 1];
      if (y >= a.c && y < b.c) {
        var t = (y - a.c) / (b.c - a.c);
        t = t * t * (3 - 2 * t);
        var d = ((b.h - a.h + 540) % 360) - 180;
        return (a.h + d * t + 360) % 360;
      }
    }
    return last.h;
  }
  var ticking = false, lastY = 0, navEl = document.querySelector('.nav');
  function update() {
    ticking = false;
    var y = window.pageYOffset;
    root.style.setProperty('--hue', hueAt(y + window.innerHeight * 0.5).toFixed(1));
    var max = document.documentElement.scrollHeight - window.innerHeight;
    progress.style.width = (max > 0 ? Math.min(100, (y / max) * 100) : 0) + '%';
    toTop.classList.toggle('show', y > 700);
    if (y > 160 && y > lastY + 6) navEl.classList.add('compact');
    else if (y < lastY - 6 || y <= 160) navEl.classList.remove('compact');
    lastY = y;
  }
  function onScroll() { if (!ticking) { ticking = true; window.requestAnimationFrame(update); } }
  window.addEventListener('scroll', onScroll, { passive: true });
  window.addEventListener('resize', function () { measure(); onScroll(); });
  window.addEventListener('load', function () { measure(); update(); });
  measure(); update();
  toTop.addEventListener('click', function () { window.scrollTo({ top: 0 }); });

  /* ---------- skill filter ---------- */
  var buttons = document.querySelectorAll('.filters button');
  var tiles = document.querySelectorAll('#tiles .tile');
  Array.prototype.forEach.call(buttons, function (b) {
    b.addEventListener('click', function () {
      var f = b.getAttribute('data-filter');
      Array.prototype.forEach.call(buttons, function (x) { x.setAttribute('aria-pressed', x === b ? 'true' : 'false'); });
      Array.prototype.forEach.call(tiles, function (t) { t.hidden = !(f === 'all' || t.getAttribute('data-cat') === f); });
      measure();
    });
  });

  /* ---------- contact ---------- */
  var status = document.getElementById('status');
  function sayContact(msg) { status.textContent = msg; setTimeout(function () { status.textContent = ''; }, 2400); }
  function selectNode(node) {
    var r = document.createRange(); r.selectNodeContents(node);
    var s = window.getSelection(); s.removeAllRanges(); s.addRange(r);
  }
  var copyEmail = document.getElementById('copy-email');
  var emailText = document.getElementById('email-text');
  function resetCopyEmail() { setTimeout(function () { copyEmail.textContent = 'Copy address'; }, 1800); }
  copyEmail.addEventListener('click', function () {
    try {
      navigator.clipboard.writeText(EMAIL).then(function () { copyEmail.textContent = 'Copied'; resetCopyEmail(); },
        function () { selectNode(emailText); copyEmail.textContent = 'Selected'; resetCopyEmail(); });
    } catch (e) { selectNode(emailText); copyEmail.textContent = 'Selected'; resetCopyEmail(); }
  });

  var nameEl = document.getElementById('f-name');
  var reasonEl = document.getElementById('f-reason');
  var msgEl = document.getElementById('f-msg');
  var sendMail = document.getElementById('send-mail');
  function body() {
    var name = nameEl.value.trim();
    return 'Hello Ahmed,\n\n' + (msgEl.value.trim() || '(write your message here)') + '\n\nRegards,\n' + (name || '(your name)');
  }
  function subject() { return 'Portfolio enquiry: ' + reasonEl.value; }
  function refresh() {
    sendMail.setAttribute('href', 'mailto:' + EMAIL + '?subject=' + encodeURIComponent(subject()) + '&body=' + encodeURIComponent(body()));
  }
  [nameEl, reasonEl, msgEl].forEach(function (el) { el.addEventListener('input', refresh); el.addEventListener('change', refresh); });
  refresh();
  document.getElementById('composer').addEventListener('submit', function (e) { e.preventDefault(); });
  document.getElementById('copy-msg').addEventListener('click', function () {
    var text = 'Subject: ' + subject() + '\n\n' + body();
    try {
      navigator.clipboard.writeText(text).then(function () { sayContact('Message copied.'); },
        function () { msgEl.focus(); msgEl.select(); sayContact('Select and copy the message text.'); });
    } catch (e) { msgEl.focus(); msgEl.select(); sayContact('Select and copy the message text.'); }
  });
  /* service picker -> message */
  var gigs = document.querySelectorAll('.gig');
  var reqBar = document.getElementById('req-bar');
  function picked() { return Array.prototype.filter.call(gigs, function (g) { return g.getAttribute('data-on') === 'true'; }); }
  function syncBar() {
    var s = picked();
    reqBar.hidden = s.length === 0;
    document.getElementById('req-count').textContent = s.length + (s.length === 1 ? ' service selected' : ' services selected');
    document.getElementById('req-names').textContent = s.map(function (g) { return g.getAttribute('data-name'); }).join(' \u00B7 ');
  }
  function setGig(g, on) {
    var b = g.querySelector('.pick');
    g.setAttribute('data-on', on ? 'true' : 'false');
    b.setAttribute('aria-pressed', on ? 'true' : 'false');
    b.textContent = on ? 'Selected' : 'Add to request';
  }
  Array.prototype.forEach.call(gigs, function (g) {
    g.addEventListener('click', function () { setGig(g, g.getAttribute('data-on') !== 'true'); syncBar(); });
  });
  document.getElementById('req-clear').addEventListener('click', function () {
    Array.prototype.forEach.call(gigs, function (g) { setGig(g, false); });
    syncBar();
  });
  document.getElementById('req-go').addEventListener('click', function () {
    var lines = picked().map(function (g) { return '- ' + g.getAttribute('data-name') + ' (' + g.getAttribute('data-tool') + ')'; });
    var head = 'I would like to hire you for:\n' + lines.join('\n') + '\n\nMore details: ';
    var cur = msgEl.value, key = 'More details: ', idx = cur.indexOf(key);
    var rest = (cur.indexOf('I would like to hire you for:') === 0 && idx > -1) ? cur.slice(idx + key.length) : cur;
    msgEl.value = head + rest;
    reasonEl.value = 'Project';
    refresh();
    document.getElementById('contact').scrollIntoView({ behavior: 'smooth' });
    setTimeout(function () { msgEl.focus({ preventScroll: true }); msgEl.setSelectionRange(msgEl.value.length, msgEl.value.length); }, 500);
  });

  Array.prototype.forEach.call(document.querySelectorAll('.choose'), function (b) {
    b.addEventListener('click', function () {
      reasonEl.value = b.getAttribute('data-reason'); refresh();
      document.getElementById('contact').scrollIntoView({ behavior: 'smooth' });
      setTimeout(function () { msgEl.focus({ preventScroll: true }); }, 500);
    });
  });
})();

(function () {
  var reduce = !!(window.matchMedia && window.matchMedia('(prefers-reduced-motion: reduce)').matches);
  var hero = document.getElementById('top');

  /* typed roles under the portrait */
  var ROLES = ['Freelancer', 'Python Developer', 'Data Analyst', 'Dashboard Developer', 'SQL Practitioner'];
  var typed = document.querySelector('.roles .typed');
  if (typed) {
    if (reduce) { typed.textContent = ROLES.slice(0, 3).join(' · '); }
    else {
      var ri = 0, ci = 0, del = false;
      (function tick() {
        var word = ROLES[ri], delay;
        if (!del) { ci++; typed.textContent = word.slice(0, ci); delay = 85; if (ci === word.length) { del = true; delay = 1500; } }
        else { ci--; typed.textContent = word.slice(0, ci); delay = 45; if (ci === 0) { del = false; ri = (ri + 1) % ROLES.length; delay = 350; } }
        setTimeout(tick, delay);
      })();
    }
  }

  /* portrait follows the pointer a little */
  var portrait = document.querySelector('.portrait');
  if (hero && portrait && !reduce) {
    hero.addEventListener('pointermove', function (e) {
      var r = hero.getBoundingClientRect();
      portrait.style.setProperty('--px', ((e.clientX - r.left) / r.width * 2 - 1).toFixed(3));
      portrait.style.setProperty('--py', ((e.clientY - r.top) / r.height * 2 - 1).toFixed(3));
    });
    hero.addEventListener('pointerleave', function () { portrait.style.setProperty('--px', 0); portrait.style.setProperty('--py', 0); });
  }

  /* hover light on cards */
  Array.prototype.forEach.call(document.querySelectorAll('.tile, .svc, .opt, .gig, .steps li, .focus li'), function (el) {
    el.classList.add('spot');
    el.addEventListener('pointermove', function (e) {
      var r = el.getBoundingClientRect();
      el.style.setProperty('--mx', (e.clientX - r.left) + 'px');
      el.style.setProperty('--my', (e.clientY - r.top) + 'px');
    });
  });

  /* count up the numbers in the stats strip */
  function countUp(el) {
    var to = parseInt(el.textContent, 10), t0 = null;
    if (reduce || !to) return;
    el.textContent = '0';
    function step(ts) {
      if (t0 === null) t0 = ts;
      var p = Math.min(1, (ts - t0) / 1000);
      el.textContent = String(Math.round(to * (1 - Math.pow(1 - p, 3))));
      if (p < 1) requestAnimationFrame(step); else el.textContent = String(to);
    }
    requestAnimationFrame(step);
  }
  if ('IntersectionObserver' in window) {
    var so = new IntersectionObserver(function (es) {
      es.forEach(function (en) { if (en.isIntersecting) { countUp(en.target); so.unobserve(en.target); } });
    }, { threshold: 0.6 });
    Array.prototype.forEach.call(document.querySelectorAll('.stat b'), function (n) { so.observe(n); });
  }

  /* moving network of dots behind the hero */
  var cv = document.getElementById('net');
  if (cv && cv.getContext && hero) {
    var ctx = cv.getContext('2d'), W = 0, H = 0, pts = [], mouse = { x: -999, y: -999 }, live = true;
    var size = function () {
      var r = hero.getBoundingClientRect(), dpr = Math.min(2, window.devicePixelRatio || 1);
      W = r.width; H = r.height;
      cv.width = Math.round(W * dpr); cv.height = Math.round(H * dpr);
      ctx.setTransform(dpr, 0, 0, dpr, 0, 0);
      var n = Math.max(24, Math.min(80, Math.round(W * H / 15000)));
      pts = [];
      for (var i = 0; i < n; i++) pts.push({ x: Math.random() * W, y: Math.random() * H, vx: (Math.random() - 0.5) * 0.35, vy: (Math.random() - 0.5) * 0.35, r: 1 + Math.random() * 1.6 });
    };
    var draw = function () {
      ctx.clearRect(0, 0, W, H);
      var link = 130, reach = 170;
      for (var i = 0; i < pts.length; i++) {
        var a = pts[i], j, b, d;
        if (!reduce) {
          a.x += a.vx; a.y += a.vy;
          if (a.x < 0 || a.x > W) a.vx *= -1;
          if (a.y < 0 || a.y > H) a.vy *= -1;
        }
        for (j = i + 1; j < pts.length; j++) {
          b = pts[j]; d = Math.hypot(a.x - b.x, a.y - b.y);
          if (d < link) {
            ctx.strokeStyle = 'rgba(111,160,255,' + (0.28 * (1 - d / link)).toFixed(3) + ')';
            ctx.lineWidth = 1; ctx.beginPath(); ctx.moveTo(a.x, a.y); ctx.lineTo(b.x, b.y); ctx.stroke();
          }
        }
        d = Math.hypot(a.x - mouse.x, a.y - mouse.y);
        if (d < reach) {
          ctx.strokeStyle = 'rgba(242,183,5,' + (0.55 * (1 - d / reach)).toFixed(3) + ')';
          ctx.lineWidth = 1.2; ctx.beginPath(); ctx.moveTo(a.x, a.y); ctx.lineTo(mouse.x, mouse.y); ctx.stroke();
        }
        ctx.fillStyle = 'rgba(190,215,255,0.7)';
        ctx.beginPath(); ctx.arc(a.x, a.y, a.r, 0, 6.2832); ctx.fill();
      }
    };
    var loop = function () { if (live && !document.hidden) draw(); requestAnimationFrame(loop); };
    size(); draw();
    if (!reduce) {
      loop();
      hero.addEventListener('pointermove', function (e) { var r = hero.getBoundingClientRect(); mouse.x = e.clientX - r.left; mouse.y = e.clientY - r.top; });
      hero.addEventListener('pointerleave', function () { mouse.x = -999; mouse.y = -999; });
    }
    window.addEventListener('resize', function () { size(); if (reduce) draw(); });
    window.addEventListener('load', function () { size(); if (reduce) draw(); });
    if ('IntersectionObserver' in window) new IntersectionObserver(function (es) { live = es[0].isIntersecting; }).observe(hero);
  }
})();
</script>
<style>
/* Mobile navigation and portfolio enhancements */

/* Refined top navigation and certificate visuals */
.nav{box-shadow:0 10px 28px #02081730;backdrop-filter:blur(14px)}
.nav .bar{gap:14px 18px;padding-block:13px}
.mark{font-size:15px;font-weight:700;letter-spacing:.02em}
.avatar{box-shadow:0 0 0 4px #f2b70520}
.links{gap:7px;padding:7px;border:1px solid #ffffff16;border-radius:999px;background:#ffffff08}
.links a{padding:9px 13px;border-radius:999px;font-family:var(--font-body);font-size:13px;font-weight:700;letter-spacing:.01em;transition:transform .18s ease,background .18s ease,box-shadow .18s ease}
.links a:hover{transform:translateY(-2px);box-shadow:0 7px 18px #00000030}
.links a[aria-current="true"]{box-shadow:0 0 0 2px #07172f,0 0 0 3px #ffffff80}
.nav .hire-btn{box-shadow:0 6px 18px #f2a10030;font-family:var(--font-body);font-weight:800;letter-spacing:.01em}
.cert{box-shadow:0 12px 28px #10182812;transition:transform .2s ease,box-shadow .2s ease}
.cert:hover{transform:translateY(-5px);box-shadow:0 18px 36px #10182820}
.cert .media.cert-art{aspect-ratio:16/9;background:#0a2347;padding:0}
.cert-art svg{display:block;width:100%;height:100%}
.cert .date{display:inline-flex;align-self:start;border-radius:999px;padding:5px 9px;background:#f2b70520;color:var(--text);font-size:11px;font-weight:700;line-height:1.5}
.lang-list li{border:1px solid var(--line);padding:14px 18px;box-shadow:0 8px 22px #1018280d}
.lang-list li small{display:block;margin:5px 0 0;color:var(--muted);font-size:12px}
@media(max-width:1060px){.nav .links{border-radius:18px}.nav .links a{padding:9px 10px}}
@media(max-width:760px){.nav .bar{padding-block:10px}.nav .links{border:1px solid #ffffff18;border-radius:16px;background:#0b1c38;padding:12px}.nav .links a{border-radius:12px}.nav .tools .hire-btn{display:inline-flex;align-items:center}.nav .tools .icon-btn{width:38px;height:38px}}
@media(max-width:390px){.nav .tools .hire-btn{display:inline-flex;padding:8px 10px;font-size:12px}.mark{font-size:12px}}

.mobile-menu-toggle{display:none;align-items:center;justify-content:center;flex-direction:column;gap:5px;width:42px;height:42px;border:1px solid #ffffff35;border-radius:12px;background:#ffffff0c;color:#fff;cursor:pointer;flex:0 0 auto}
.mobile-menu-toggle span{display:block;width:18px;height:2px;border-radius:2px;background:currentColor}
.skill-meter-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:18px}
.skill-meter{padding:20px;border:1px solid var(--line);background:var(--surface);border-radius:18px;box-shadow:var(--shadow)}
.meter-heading{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-bottom:12px;font-weight:700}
.meter-heading strong{font-family:var(--font-mono);color:var(--accent,var(--blue,#4f8cff))}
.meter-track{height:9px;border-radius:99px;background:var(--line);overflow:hidden}
.meter-track span{display:block;height:100%;width:var(--level);border-radius:99px;background:linear-gradient(90deg,#4f8cff,#2dd4bf);animation:meter-in 1s ease both}
.skill-meter small{display:block;margin-top:10px;color:var(--muted);font-size:12px}
.skill-note{margin-top:18px;color:var(--muted);font-size:13px}
.contact-highlight h3{margin:8px 0;font-size:21px}
.contact-description{color:var(--muted);line-height:1.7}
.contact-pill{display:inline-flex;margin-top:8px;padding:8px 11px;border-radius:999px;background:#2dd4bf20;color:var(--text);font-size:12px;font-weight:700}
@keyframes meter-in{from{width:0}to{width:var(--level)}}
@media(max-width:760px){
 .nav .bar{position:relative;flex-wrap:wrap;gap:10px;padding-block:9px}
 .mobile-menu-toggle{display:flex;margin-left:auto;order:2}
 .nav .tools{order:3;gap:8px}
 .nav .tools .hire-btn{padding:9px 12px}
 .nav .links{display:none;order:4;flex:0 0 100%;width:100%;min-width:0;overflow:visible;flex-direction:column;align-items:stretch;gap:7px;padding:10px 0 5px}
 .nav .links.is-open{display:flex}
 .nav .links a{display:flex;justify-content:flex-start;width:100%;box-sizing:border-box;padding:12px 15px;border-radius:12px}
 .nav .links a:focus-visible,.mobile-menu-toggle:focus-visible{outline:2px solid #2dd4bf;outline-offset:3px}
 .skill-meter-grid{grid-template-columns:minmax(0,1fr)}
}
@media(max-width:390px){.mark{font-size:12px;gap:7px}.avatar{width:32px;height:32px}.nav .tools .hire-btn{display:none}}
@media(prefers-reduced-motion:reduce){.meter-track span{animation:none}}
</style>
<script>
(function(){
  var toggle=document.getElementById('mobile-menu-toggle');
  var menu=document.getElementById('menu');
  if(!toggle||!menu)return;
  function closeMenu(){menu.classList.remove('is-open');toggle.setAttribute('aria-expanded','false');toggle.setAttribute('aria-label','Open navigation menu');}
  toggle.addEventListener('click',function(){
    var open=!menu.classList.contains('is-open');
    menu.classList.toggle('is-open',open);
    toggle.setAttribute('aria-expanded',String(open));
    toggle.setAttribute('aria-label',open?'Close navigation menu':'Open navigation menu');
  });
  menu.querySelectorAll('a').forEach(function(link){link.addEventListener('click',closeMenu);});
  window.addEventListener('resize',function(){if(window.innerWidth>760)closeMenu();});
  document.addEventListener('keydown',function(e){if(e.key==='Escape')closeMenu();});
})();
</script>

<style id="final-design-upgrade">
:root{--deep:#071426;--deep2:#0b1c32;--aqua:#43e3c4;--violet:#9c8cff;--ink:#12233b;--muted:#64748b;--line:rgba(119,148,190,.22);--glass:rgba(255,255,255,.075)}
html{scroll-behavior:smooth;scroll-padding-top:96px}
body{font-family:'Source Sans 3',Inter,system-ui,sans-serif;letter-spacing:.005em}
::selection{background:rgba(67,227,196,.32);color:inherit}
.nav{background:rgba(5,15,31,.88)!important;border-bottom:1px solid rgba(129,166,210,.22)!important;box-shadow:0 14px 42px rgba(1,8,20,.25)!important}
.nav .mark{border-radius:17px!important;border-color:rgba(67,227,196,.28)!important;background:linear-gradient(135deg,rgba(67,227,196,.12),rgba(156,140,255,.09))!important}
.nav .links a{font-weight:650;transition:color .2s ease,background .2s ease,transform .2s ease;border-radius:11px;padding:10px 12px}
.nav .links a:hover{background:rgba(67,227,196,.11);color:var(--aqua);transform:translateY(-1px)}
.hire-btn,.btn.primary{background:linear-gradient(120deg,#48e4c5,#7cebd4)!important;color:#052034!important;border:1px solid rgba(255,255,255,.35)!important;box-shadow:0 9px 26px rgba(67,227,196,.2);font-weight:800!important;transition:transform .2s,box-shadow .2s}
.hire-btn:hover,.btn.primary:hover{transform:translateY(-2px);box-shadow:0 13px 34px rgba(67,227,196,.29)}
.hero{position:relative;overflow:hidden;background:radial-gradient(ellipse at 80% 15%,rgba(103,91,224,.26),transparent 38%),radial-gradient(ellipse at 15% 82%,rgba(67,227,196,.13),transparent 34%),linear-gradient(135deg,#071426 0%,#0a1c33 58%,#101c3b 100%)!important}
.hero:after{content:"";position:absolute;inset:0;pointer-events:none;opacity:.19;background-image:linear-gradient(rgba(255,255,255,.06) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.06) 1px,transparent 1px);background-size:44px 44px;mask-image:linear-gradient(to bottom,black,transparent 85%)}
.hero .wrap{position:relative;z-index:1}
.hero h1{letter-spacing:-.055em;line-height:.98;text-wrap:balance}
.hero h1 em{background:linear-gradient(100deg,#fff 3%,#73f1d7 47%,#a99bff 95%);-webkit-background-clip:text;background-clip:text;color:transparent}
.hero .lead{max-width:650px;color:#c8d5e8;line-height:1.8;font-size:clamp(1.05rem,1.4vw,1.2rem)}
.avail{border:1px solid rgba(67,227,196,.28)!important;background:rgba(67,227,196,.08)!important;color:#9bf5e2!important;backdrop-filter:blur(8px)}
.tags li{border:1px solid rgba(154,180,222,.24)!important;background:rgba(255,255,255,.055)!important;color:#e0e9f7!important;border-radius:999px!important;transition:transform .2s,border-color .2s}
.tags li:hover{transform:translateY(-3px);border-color:rgba(67,227,196,.55)!important}
.btn{border-radius:14px!important;transition:transform .2s ease,box-shadow .2s ease,background .2s ease}
.btn.outline{border-color:rgba(159,185,224,.38)!important;background:rgba(255,255,255,.035)!important}
.btn.outline:hover{border-color:rgba(67,227,196,.65)!important;background:rgba(67,227,196,.08)!important;transform:translateY(-2px)}
.social-hero-link{border:1px solid rgba(67,227,196,.34)!important;color:#b9fff1!important;background:rgba(67,227,196,.07)!important}
section:not(.hero){position:relative}
section:not(.hero) .section-head h2{letter-spacing:-.045em;line-height:1.08;text-wrap:balance}
.section-head .eyebrow,.eyebrow{letter-spacing:.13em;text-transform:uppercase;font-size:.75rem;font-weight:800}
.grad{background:linear-gradient(100deg,#17b99d,#6e7df0 90%);-webkit-background-clip:text;background-clip:text;color:transparent}
.tile,.service-card,.project-card,.c-card,.idcard,.contact-options-card,.portfolio-card{border-radius:23px!important;border:1px solid var(--line)!important;box-shadow:0 14px 45px rgba(20,42,77,.07);transition:transform .24s ease,box-shadow .24s ease,border-color .24s ease}
.tile:hover,.service-card:hover,.project-card:hover,.c-card:hover,.portfolio-card:hover{transform:translateY(-5px);box-shadow:0 24px 60px rgba(20,42,77,.13);border-color:rgba(67,190,177,.5)!important}
.idcard{overflow:hidden;background:linear-gradient(145deg,rgba(255,255,255,.98),rgba(240,248,255,.94))!important;box-shadow:0 20px 65px rgba(15,40,75,.12)!important}
.filters button,.tabs button{border-radius:999px!important;transition:all .2s ease}
.filters button[aria-pressed="true"],.tabs button[aria-selected="true"]{box-shadow:0 8px 22px rgba(36,116,180,.17)}
.profile-links-strip{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:16px;margin:0 0 30px}
.profile-link-card{position:relative;display:flex;align-items:center;gap:15px;min-width:0;padding:19px 21px;border:1px solid rgba(129,158,197,.25);border-radius:20px;text-decoration:none!important;color:inherit!important;background:linear-gradient(135deg,rgba(255,255,255,.92),rgba(239,247,255,.86));box-shadow:0 12px 32px rgba(18,40,72,.06);transition:transform .22s ease,border-color .22s ease,box-shadow .22s ease;overflow:hidden}
.profile-link-card:before{content:"";position:absolute;inset:0 auto 0 0;width:4px;background:linear-gradient(#43e3c4,#8b82ff)}
.profile-link-card:hover{transform:translateY(-4px);border-color:rgba(67,190,177,.55);box-shadow:0 20px 42px rgba(18,40,72,.12)}
.profile-link-icon{display:grid;place-items:center;flex:0 0 46px;width:46px;height:46px;border-radius:15px;background:#0b1d34;color:#83f1dc;font-size:1.25rem;font-weight:900;letter-spacing:-.05em;box-shadow:0 8px 18px rgba(7,20,38,.16)}
.profile-link-copy{display:grid;gap:3px;min-width:0}.profile-link-copy b{font-size:1.03rem;font-weight:850}.profile-link-copy small{font-size:.86rem;color:#687b94}.profile-link-arrow{margin-left:auto;color:#078d83;font-size:1.3rem;font-weight:800}
.social-profile-card{background:linear-gradient(145deg,rgba(248,255,253,.98),rgba(239,246,255,.98))!important}
.social-card-title{margin:.2rem 0 .35rem}.social-card-copy{color:var(--muted);line-height:1.65}
footer{background:#061326!important;color:#c9d7e8!important;border-top:1px solid rgba(139,169,209,.18)}footer a{color:#b9cce3!important}footer a:hover{color:#61ecd2!important}
.to-top{box-shadow:0 12px 30px rgba(7,20,38,.25)}
input,select,textarea{border-radius:13px!important}
:focus-visible{outline:3px solid rgba(67,227,196,.75)!important;outline-offset:3px}
@media(max-width:760px){.profile-links-strip{grid-template-columns:1fr;gap:11px}.profile-link-card{padding:16px}.hero h1{font-size:clamp(2.7rem,12vw,4.6rem)}.hero .actions{gap:10px}.social-hero-link{flex-basis:100%;justify-content:center}}
@media(prefers-reduced-motion:reduce){*,*:before,*:after{scroll-behavior:auto!important;animation-duration:.01ms!important;animation-iteration-count:1!important;transition-duration:.01ms!important}}
</style>

</body></html>

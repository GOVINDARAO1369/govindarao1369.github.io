<!DOCTYPE html>
<html lang="te">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>శ్రీ రాజరాజేశ్వరి వాటర్‌ప్రూఫ్ వర్క్స్</title>

<meta name="description"
content="శ్రీ రాజరాజేశ్వరి వాటర్‌ప్రూఫ్ వర్క్స్. టెర్రస్, బాత్రూమ్, గోడల లీకేజీ మరియు వాటర్‌ప్రూఫింగ్ సేవల కోసం సంప్రదించండి.">

<meta name="theme-color" content="#071b3a">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

:root {
    --navy: #071b3a;
    --blue: #075be8;
    --cyan: #00d9ff;
    --gold: #ffc857;
    --white: #ffffff;
    --light: #f2f7ff;
}

body {
    font-family: "Noto Sans Telugu", "Gautami", Arial, sans-serif;
    background: var(--light);
    color: #17243b;
    line-height: 1.8;
}

a {
    text-decoration: none;
}

header {
    background: var(--navy);
    color: white;
    padding: 14px 6%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 12px;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 5px 25px #0003;
}

.logo {
    font-size: 20px;
    font-weight: 900;
    color: var(--gold);
    line-height: 1.5;
}

.logo small {
    display: block;
    color: white;
    font-size: 12px;
    font-weight: normal;
}

nav {
    display: flex;
    gap: 18px;
    flex-wrap: wrap;
}

nav a {
    color: white;
    font-size: 14px;
    transition: .3s;
}

nav a:hover {
    color: var(--gold);
}

.btn {
    display: inline-block;
    padding: 12px 23px;
    border-radius: 30px;
    font-weight: bold;
    transition: .3s;
    margin: 5px;
}

.btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 20px #0003;
}

.btn-call {
    background: var(--gold);
    color: #14213d;
}

.btn-wa {
    background: #20c968;
    color: white;
}

.hero {
    min-height: 620px;
    display: flex;
    align-items: center;
    padding: 70px 7%;
    color: white;
    background:
    linear-gradient(110deg, #04152bf2, #073c70d9, #04152b91),
    url("https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=1800&q=85")
    center/cover no-repeat;
}

.hero-content {
    max-width: 800px;
    animation: appear 1s ease;
}

.badge {
    display: inline-block;
    color: var(--gold);
    border: 1px solid var(--gold);
    padding: 5px 15px;
    border-radius: 30px;
    margin-bottom: 20px;
}

.hero h1 {
    font-size: clamp(32px, 5vw, 58px);
    line-height: 1.5;
    margin-bottom: 18px;
}

.hero h1 span {
    color: var(--gold);
}

.hero p {
    font-size: 18px;
    margin-bottom: 22px;
    max-width: 650px;
}

.phone {
    font-size: 22px;
    color: var(--gold);
    font-weight: bold;
    margin-top: 18px;
}

section {
    padding: 75px 7%;
    scroll-margin-top: 90px;
}

.section-title {
    text-align: center;
    margin-bottom: 42px;
}

.section-title h2 {
    color: var(--navy);
    font-size: clamp(25px, 4vw, 38px);
    margin-bottom: 10px;
}

.section-title p {
    color: #63718a;
}

.underline {
    width: 85px;
    height: 5px;
    background: linear-gradient(90deg, var(--blue), var(--cyan));
    margin: 12px auto;
    border-radius: 10px;
}

.about-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
    align-items: center;
}

.about-box {
    padding: 30px;
    background: white;
    border-radius: 20px;
    box-shadow: 0 8px 30px #10285010;
}

.about-box h3 {
    color: var(--blue);
    margin-bottom: 12px;
}

.features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}

.feature {
    background: white;
    padding: 27px 20px;
    border-radius: 18px;
    text-align: center;
    border-bottom: 4px solid var(--blue);
    box-shadow: 0 8px 25px #00000008;
    transition: .3s;
}

.feature:hover {
    transform: translateY(-7px);
}

.icon {
    font-size: 43px;
    margin-bottom: 10px;
}

.feature h3 {
    color: var(--navy);
    margin-bottom: 10px;
}

.products {
    background: #e8f1ff;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
    gap: 24px;
}

.product-card {
    background: white;
    border-radius: 18px;
    overflow: hidden;
    box-shadow: 0 10px 30px #09254b12;
    transition: .3s;
}

.product-card:hover {
    transform: translateY(-6px);
}

.product-image {
    height: 190px;
    display: grid;
    place-items: center;
    font-size: 75px;
    background: linear-gradient(135deg, #075be8, #00c9e8);
}

.product-card:nth-child(2) .product-image {
    background: linear-gradient(135deg, #09254b, #4776c9);
}

.product-card:nth-child(3) .product-image {
    background: linear-gradient(135deg, #008b72, #5ee7a4);
}

.product-card:nth-child(4) .product-image {
    background: linear-gradient(135deg, #8b4ce2, #e7a6ff);
}

.product-info {
    padding: 22px;
}

.product-info h3 {
    color: var(--navy);
    margin-bottom: 10px;
}

.product-info p {
    color: #63718a;
    font-size: 14px;
    margin-bottom: 15px;
}

.small-btn {
    display: inline-block;
    padding: 9px 16px;
    background: var(--blue);
    color: white;
    border-radius: 25px;
    font-size: 14px;
}

.process-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 22px;
    text-align: center;
}

.step {
    padding: 25px;
    background: white;
    border-radius: 18px;
    box-shadow: 0 5px 20px #00000008;
}

.step-number {
    width: 50px;
    height: 50px;
    display: grid;
    place-items: center;
    margin: 0 auto 15px;
    background: var(--blue);
    color: white;
    border-radius: 50%;
    font-size: 22px;
    font-weight: bold;
}

.gallery {
    background: white;
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
    gap: 20px;
}

.gallery-card {
    min-height: 190px;
    padding: 25px;
    border-radius: 18px;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    color: white;
    background: linear-gradient(145deg, #071b3a, #087de0);
}

.gallery-card:nth-child(2) {
    background: linear-gradient(145deg, #00695c, #38b2ac);
}

.gallery-card:nth-child(3) {
    background: linear-gradient(145deg, #482080, #a56eff);
}

.gallery-card:nth-child(4) {
    background: linear-gradient(145deg, #8a3b12, #f7a34b);
}

.gallery-card h3 {
    font-size: 20px;
}

.contact {
    color: white;
    background: linear-gradient(135deg, #071b3a, #075be8);
}

.contact .section-title h2,
.contact .section-title p {
    color: white;
}

.contact-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
}

.contact-box {
    padding: 28px;
    border-radius: 18px;
    background: #ffffff12;
    border: 1px solid #ffffff30;
    text-align: center;
}

.contact-box h3 {
    color: var(--gold);
    margin-bottom: 10px;
}

.contact-box a {
    color: white;
    font-weight: bold;
    overflow-wrap: anywhere;
}

.contact-cta {
    text-align: center;
    margin-top: 35px;
}

footer {
    padding: 28px 6%;
    text-align: center;
    background: #041126;
    color: white;
}

footer p {
    margin: 5px 0;
}

footer a {
    color: var(--gold);
}

.float-wa {
    position: fixed;
    bottom: 22px;
    right: 20px;
    z-index: 2000;
    background: #20c968;
    color: white;
    border-radius: 40px;
    padding: 13px 18px;
    box-shadow: 0 5px 20px #0004;
    font-weight: bold;
}

@keyframes appear {
    from {
        opacity: 0;
        transform: translateY(25px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@media (max-width: 760px) {
    header {
        justify-content: center;
        text-align: center;
    }

    nav {
        justify-content: center;
        gap: 12px;
    }

    nav a {
        font-size: 13px;
    }

    .hero {
        min-height: 570px;
        padding: 55px 6%;
    }

    .hero p {
        font-size: 16px;
    }

    section {
        padding: 55px 6%;
    }

    .float-wa {
        right: 12px;
        bottom: 12px;
        font-size: 13px;
    }
}
</style>
</head>

<body>

<header>
    <a href="#home" class="logo">
        శ్రీ రాజరాజేశ్వరి
        <small>WATERPROOF WORKS</small>
    </a>

    <nav>
        <a href="#home">హోమ్</a>
        <a href="#about">మా గురించి</a>
        <a href="#services">సేవలు</a>
        <a href="#products">ప్రొడక్ట్స్</a>
        <a href="#gallery">గ్యాలరీ</a>
        <a href="#contact">కాంటాక్ట్</a>
    </nav>
</header>

<!-- HOME -->

<section class="hero" id="home">
    <div class="hero-content">
        <span class="badge">మీ భవనానికి వాటర్‌ప్రూఫింగ్ సేవలు</span>

        <h1>
            శ్రీ రాజరాజేశ్వరి<br>
            <span>వాటర్‌ప్రూఫ్ వర్క్స్</span>
        </h1>

        <p>
            మీ ఇంటి పైకప్పు, గోడలు, బాత్రూమ్‌లలో నీటి లీకేజీ సమస్యలకు
            సరైన పరిష్కారాన్ని కనుగొనడంలో మేము సహాయపడతాము.
            మీ అవసరాలకు తగిన వాటర్‌ప్రూఫింగ్ సేవల కోసం మమ్మల్ని సంప్రదించండి.
        </p>

        <a class="btn btn-call" href="tel:+917382466632">
            📞 ఇప్పుడే కాల్ చేయండి
        </a>

        <a class="btn btn-wa"
           href="https://wa.me/917382466632?text=%E0%B0%A8%E0%B0%BE%E0%B0%95%E0%B1%81%20%E0%B0%B5%E0%B0%BE%E0%B0%9F%E0%B0%B0%E0%B1%8D%E2%80%8C%E0%B0%AA%E0%B1%8D%E0%B0%B0%E0%B1%82%E0%B0%AB%E0%B0%BF%E0%B0%82%E0%B0%97%E0%B1%8D%20%E0%B0%B8%E0%B1%87%E0%B0%B5%E0%B0%B2%20%E0%B0%97%E0%B1%81%E0%B0%B0%E0%B0%BF%E0%B0%82%E0%B0%9A%E0%B0%BF%20%E0%B0%B5%E0%B0%BF%E0%B0%B5%E0%B0%B0%E0%B0%BE%E0%B0%B2%E0%B1%81%20%E0%B0%95%E0%B0%BE%E0%B0%B5%E0%B0%BE%E0%B0%B2%E0%B0%BF."
           target="_blank" rel="noopener">
            💬 వాట్సాప్ చేయండి
        </a>

        <div class="phone">📱 7382466632</div>
    </div>
</section>

<!-- ABOUT -->

<section id="about">
    <div class="section-title">
        <h2>మా గురించి</h2>
        <div class="underline"></div>
        <p>మీ భవన రక్షణ కోసం వాటర్‌ప్రూఫింగ్ సేవలు</p>
    </div>

    <div class="about-grid">
        <div class="about-box">
            <h3>🏢 శ్రీ రాజరాజేశ్వరి వాటర్‌ప్రూఫ్ వర్క్స్</h3>
            <p>
                భవనాల్లో నీటి లీకేజీ, టెర్రస్ సీపేజ్, గోడల తేమ వంటి
                సమస్యలను పరిశీలించి తగిన వాటర్‌ప్రూఫింగ్ పరిష్కారాలను
                అందించడమే మా లక్ష్యం.
            </p>
            <br>
            <p>
                మీ అవసరాన్ని మాకు తెలియజేయండి.
                పనికి తగిన పరిష్కారం, అంచనా ఖర్చు గురించి మాట్లాడుకుందాం.
            </p>
            <br>
            <a class="btn btn-wa"
               href="https://wa.me/917382466632?text=నాకు%20వాటర్‌ప్రూఫింగ్%20పని%20గురించి%20వివరాలు%20కావాలి."
               target="_blank" rel="noopener">
                వివరాల కోసం మెసేజ్ చేయండి
            </a>
        </div>

        <div class="about-box">
            <h3>💧 మా ముఖ్య ఉద్దేశం</h3>
            <p>✔️ లీకేజీ సమస్యను పరిశీలించడం</p>
            <p>✔️ అవసరానికి తగిన పద్ధతిని సూచించడం</p>
            <p>✔️ సరైన మెటీరియల్ ఎంపికలో సహాయం</p>
            <p>✔️ పని వివరాలు, ఖర్చు ముందుగా చర్చించడం</p>
            <p>✔️ కస్టమర్లకు స్పష్టమైన సమాచారం అందించడం</p>

            <br>

            <a class="btn btn-call" href="tel:+917382466632">
                📞 7382466632
            </a>
        </div>
    </div>
</section>

<!-- SERVICES -->

<section id="services">
    <div class="section-title">
        <h2>మా వాటర్‌ప్రూఫింగ్ సేవలు</h2>
        <div class="underline"></div>
        <p>మీ భవనానికి అవసరమైన సేవను ఎంచుకోండి</p>
    </div>

    <div class="features">

        <div class="feature">
            <div class="icon">🏠</div>
            <h3>టెర్రస్ వాటర్‌ప్రూఫింగ్</h3>
            <p>
                వర్షపు నీటి లీకేజీ, పైకప్పు సీపేజ్ సమస్యలకు
                తగిన పరిష్కారాలు.
            </p>
        </div>

        <div class="feature">
            <div class="icon">🚿</div>
            <h3>బాత్రూమ్ వాటర్‌ప్రూఫింగ్</h3>
            <p>
                బాత్రూమ్ ఫ్లోర్, గోడల నుంచి నీరు లీక్ అయ్యే
                సమస్యలకు పరిష్కారాలు.
            </p>
        </div>

        <div class="feature">
            <div class="icon">🧱</div>
            <h3>గోడల సీపేజ్ నివారణ</h3>
            <p>
                గోడలలో తేమ, నీటి మరకలు వంటి సమస్యలను
                పరిశీలించి తగిన చికిత్స.
            </p>
        </div>

        <div class="feature">
            <div class="icon">🏗️</div>
            <h3>బేస్‌మెంట్ వాటర్‌ప్రూఫింగ్</h3>
            <p>
                భవన పునాది, బేస్‌మెంట్‌లలో నీటి ప్రవేశం
                సమస్యలకు తగిన పరిష్కారాలు.
            </p>
        </div>

        <div class="feature">
            <div class="icon">🌧️</div>
            <h3>వర్షపు నీటి లీకేజీ</h3>
            <p>
                లీకేజీ ఎక్కడ నుంచి వస్తుందో పరిశీలించి
                అవసరమైన పనిని సూచించడం.
            </p>
        </div>

        <div class="feature">
            <div class="icon">🛠️</div>
            <h3>వాటర్‌ప్రూఫ్ రిపేర్లు</h3>
            <p>
                పాత వాటర్‌ప్రూఫింగ్ పనుల్లో ఏర్పడిన
                సమస్యలకు మరమ్మతు పరిష్కారాలు.
            </p>
        </div>

    </div>

    <div style="text-align:center;margin-top:30px;">
        <a class="btn btn-wa"
           href="https://wa.me/917382466632?text=నాకు%20వాటర్‌ప్రూఫింగ్%20సేవలు%20కావాలి."
           target="_blank" rel="noopener">
            💬 సేవల గురించి అడగండి
        </a>
    </div>
</section>

<!-- PRODUCTS -->

<section class="products" id="products">
    <div class="section-title">
        <h2>వాటర్‌ప్రూఫింగ్ ప్రొడక్ట్స్</h2>
        <div class="underline"></div>
        <p>మీ అవసరానికి తగిన మెటీరియల్ గురించి తెలుసుకోండి</p>
    </div>

    <div class="product-grid">

        <div class="product-card">
            <div class="product-image">🪣</div>
            <div class="product-info">
                <h3>లిక్విడ్ వాటర్‌ప్రూఫింగ్</h3>
                <p>
                    టెర్రస్, గోడలు వంటి ప్రదేశాలకు అనువైన
                    కోటింగ్ మెటీరియల్ ఎంపిక గురించి తెలుసుకోండి.
                </p>
                <a class="small-btn"
                   href="https://wa.me/917382466632?text=లిక్విడ్%20వాటర్‌ప్రూఫింగ్%20ప్రొడక్ట్స్%20వివరాలు%20కావాలి."
                   target="_blank" rel="noopener">
                    ధర అడగండి
                </a>
            </div>
        </div>

        <div class="product-card">
            <div class="product-image">🧴</div>
            <div class="product-info">
                <h3>వాటర్‌ప్రూఫ్ కెమికల్స్</h3>
                <p>
                    నిర్మాణ పనులకు అనువైన వాటర్‌ప్రూఫింగ్
                    కెమికల్స్ వివరాల కోసం సంప్రదించండి.
                </p>
                <a class="small-btn"
                   href="https://wa.me/917382466632?text=వాటర్‌ప్రూఫింగ్%20కెమికల్స్%20వివరాలు%20కావాలి."
                   target="_blank" rel="noopener">
                    ధర అడగండి
                </a>
            </div>
        </div>

        <div class="product-card">
            <div class="product-image">🧱</div>
            <div class="product-info">
                <h3>సీపేజ్ ప్రొటెక్షన్</h3>
                <p>
                    గోడలు, బాత్రూమ్‌లలో తేమ సమస్యలకు
                    ఉపయోగపడే ఉత్పత్తుల గురించి అడగండి.
                </p>
                <a class="small-btn"
                   href="https://wa.me/917382466632?text=సీపేజ్%20ప్రొటెక్షన్%20ప్రొడక్ట్స్%20వివరాలు%20కావాలి."
                   target="_blank" rel="noopener">
                    ధర అడగండి
                </a>
            </div>
        </div>

        <div class="product-card">
            <div class="product-image">🛡️</div>
            <div class="product-info">
                <h3>ప్రొటెక్టివ్ కోటింగ్స్</h3>
                <p>
                    భవన ఉపరితల రక్షణకు తగిన కోటింగ్
                    ఉత్పత్తుల ఎంపిక కోసం సంప్రదించండి.
                </p>
                <a class="small-btn"
                   href="https://wa.me/917382466632?text=ప్రొటెక్టివ్%20కోటింగ్స్%20వివరాలు%20కావాలి."
                   target="_blank" rel="noopener">
                    ధర అడగండి
                </a>
            </div>
        </div>

    </div>

    <p style="text-align:center;margin-top:25px;font-size:14px;">
        గమనిక: ఇవి ఉత్పత్తుల విభాగాల ఉదాహరణలు మాత్రమే.
        నిర్దిష్ట బ్రాండ్లు, స్టాక్, ధరలు మీ వివరాలతో అప్‌డేట్ చేయాలి.
    </p>

    <div style="text-align:center;margin-top:20px;">
        <a class="btn btn-wa"
           href="https://wa.me/917382466632?text=ప్రొడక్ట్స్%20క్యాటలాగ్%20మరియు%20ధరల%20వివరాలు%20కావాలి."
           target="_blank" rel="noopener">
            📲 పూర్తి వివరాల కోసం వాట్సాప్ చేయండి
        </a>
    </div>
</section>

<!-- PROCESS -->

<section id="process">
    <div class="section-title">
        <h2>మా పని విధానం</h2>
        <div class="underline"></div>
        <p>మీ అవసరాన్ని బట్టి సరైన పరిష్కారం వైపు అడుగులు</p>
    </div>

    <div class="process-grid">

        <div class="step">
            <div class="step-number">1</div>
            <h3>సంప్రదించండి</h3>
            <p>మీ సమస్యను ఫోన్ లేదా వాట్సాప్ ద్వారా తెలియజేయండి.</p>
        </div>

        <div class="step">
            <div class="step-number">2</div>
            <h3>సమస్య పరిశీలన</h3>
            <p>పని స్వభావాన్ని బట్టి అవసరమైన వివరాలు తెలుసుకోండి.</p>
        </div>

        <div class="step">
            <div class="step-number">3</div>
            <h3>అంచనా వివరాలు</h3>
            <p>పని, మెటీరియల్, ఖర్చు గురించి చర్చించండి.</p>
        </div>

        <div class="step">
            <div class="step-number">4</div>
            <h3>పని ప్రారంభం</h3>
            <p>అంగీకరించిన వివరాల ప్రకారం పనిని ప్రారంభించండి.</p>
        </div>

    </div>
</section>

<!-- GALLERY -->

<section class="gallery" id="gallery">
    <div class="section-title">
        <h2>మా వర్క్ గ్యాలరీ</h2>
        <div class="underline"></div>
        <p>మీరు చేసిన పనుల ఫొటోలను ఇక్కడ జోడించవచ్చు</p>
    </div>

    <div class="gallery-grid">

        <div class="gallery-card">
            <h3>🏠 టెర్రస్ వర్క్స్</h3>
            <p>మీ టెర్రస్ పనుల ఫొటోలు ఇక్కడ పెట్టండి.</p>
        </div>

        <div class="gallery-card">
            <h3>🚿 బాత్రూమ్ వర్క్స్</h3>
            <p>బాత్రూమ్ వాటర్‌ప్రూఫింగ్ ఫొటోలు ఇక్కడ పెట్టండి.</p>
        </div>

        <div class="gallery-card">
            <h3>🧱 వాల్ ప్రొటెక్షన్</h3>
            <p>గోడల పనులకు సంబంధించిన ఫొటోలు ఇక్కడ పెట్టండి.</p>
        </div>

        <div class="gallery-card">
            <h3>🛠️ రిపేర్ వర్క్స్</h3>
            <p>మీ మరమ్మతు పనుల ఫొటోలు ఇక్కడ పెట్టండి.</p>
        </div>

    </div>

    <div style="text-align:center;margin-top:25px;">
        <a class="btn btn-call" href="tel:+917382466632">
            మీ పని వివరాల కోసం కాల్ చేయండి
        </a>
    </div>
</section>

<!-- CONTACT -->

<section class="contact" id="contact">
    <div class="section-title">
        <h2>మమ్మల్ని సంప్రదించండి</h2>
        <div class="underline"></div>
        <p>మీ వాటర్‌ప్రూఫింగ్ అవసరాన్ని మాకు తెలియజేయండి</p>
    </div>

    <div class="contact-grid">

        <div class="contact-box">
            <div class="icon">📞</div>
            <h3>ఫోన్ నంబర్</h3>
            <a href="tel:+917382466632">7382466632</a>
            <br><br>
            <a class="btn btn-call" href="tel:+917382466632">
                కాల్ చేయండి
            </a>
        </div>

        <div class="contact-box">
            <div class="icon">💬</div>
            <h3>వాట్సాప్</h3>
            <p>పని వివరాలు, ఫొటోలు పంపవచ్చు.</p>
            <a class="btn btn-wa"
               href="https://wa.me/917382466632?text=నమస్కారం%20శ్రీ%20రాజరాజేశ్వరి%20వాటర్‌ప్రూఫ్%20వర్క్స్.%20నాకు%20వివరాలు%20కావాలి."
               target="_blank" rel="noopener">
                వాట్సాప్ మెసేజ్ పంపండి
            </a>
        </div>

        <div class="contact-box">
            <div class="icon">🏢</div>
            <h3>కంపెనీ పేరు</h3>
            <p>శ్రీ రాజరాజేశ్వరి వాటర్‌ప్రూఫ్ వర్క్స్</p>
            <p>మీ ఇంటి లీకేజీ సమస్యకు పరిష్కారం కోసం సంప్రదించండి.</p>
        </div>


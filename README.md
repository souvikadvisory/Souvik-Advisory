<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Souvik Das | Finance Professional</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Inter',sans-serif;
scroll-behavior:smooth;
}

body{
background:#ffffff;
color:#111;
line-height:1.7;
}

.hero{
background:#000;
color:#fff;
padding:100px 10%;
display:flex;
align-items:center;
justify-content:space-between;
flex-wrap:wrap;
}

.hero-text{
max-width:600px;
}

.hero h1{
font-family:'Playfair Display',serif;
font-size:48px;
margin-bottom:20px;
}

.hero p{
font-weight:300;
margin-bottom:25px;
}

.hero button{
padding:12px 25px;
border:1px solid #fff;
background:transparent;
color:#fff;
cursor:pointer;
transition:0.3s;
}

.hero button:hover{
background:#fff;
color:#000;
}

.hero img{
width:280px;
border-radius:6px;
filter:grayscale(20%);
}

section{
padding:80px 12%;
}

.section-title{
font-size:28px;
font-weight:600;
margin-bottom:40px;
border-left:4px solid #000;
padding-left:15px;
}

.card{
margin-bottom:35px;
}

h3{
margin-bottom:8px;
font-weight:600;
}

ul{
margin-top:10px;
padding-left:18px;
}

.skills span{
display:inline-block;
border:1px solid #000;
padding:8px 14px;
margin:6px;
font-size:13px;
}

.services{
background:#f5f5f5;
}

.contact{
background:#000;
color:#fff;
text-align:center;
}

.contact a{
color:#fff;
text-decoration:underline;
}

footer{
text-align:center;
padding:25px;
font-size:13px;
border-top:1px solid #eee;
}

@media(max-width:900px){
.hero{
flex-direction:column;
text-align:center;
}
.hero img{
margin-top:40px;
}
}
</style>
</head>

<body>

<div class="hero">
<div class="hero-text">
<h1>Souvik Das</h1>
<p>Assistant Manager | Finance Executive | Investment Analyst Aspirant</p>
<p>
Finance professional with cross-industry experience in banking, financial services, and insurance. Focused on structured growth, risk alignment, and long-term financial independence.
</p>
<button onclick="document.getElementById('contact').scrollIntoView()">Connect With Me</button>
</div>
<img src="profile.jpg" alt="Souvik Das">
</div>

<section>
<h2 class="section-title">About</h2>
<div class="card">
<p>
Currently serving as Assistant Manager at Axis Max Life Insurance Limited, leading people management, business expansion strategies, investment planning, and client relationship optimization.
</p>
<br>
<p>
Previously contributed to HDB Financial Services Ltd in finance operations and began my professional journey at IDFC First Bank driving credit acquisition, savings portfolio growth, and consumer finance solutions.
</p>
<br>
<p>
Pursuing MA in Economics from IGNOU and holding a B.Com in Business Management & Finance from Calcutta University. Long-term objective: achieve financial independence while contributing meaningfully in banking, economic research, or investment management.
</p>
</div>
</section>

<section>
<h2 class="section-title">Experience</h2>

<div class="card">
<h3>Assistant Manager — Axis Max Life Insurance Limited</h3>
<p><strong>Dec 2025 – Present</strong></p>
<ul>
<li>Team leadership & performance monitoring</li>
<li>Strategic business growth initiatives</li>
<li>Investment and insurance advisory</li>
<li>Risk assessment & portfolio alignment</li>
<li>Customer satisfaction optimization</li>
</ul>
</div>

<div class="card">
<h3>Finance Executive — HDB Financial Services Ltd</h3>
<ul>
<li>Finance department coordination</li>
<li>Revenue growth support</li>
<li>Operational financial management</li>
</ul>
</div>

<div class="card">
<h3>Senior Business Development Officer — IDFC First Bank</h3>
<ul>
<li>Credit card and savings portfolio acquisition</li>
<li>Consumer durable loan sales</li>
<li>Customer lifecycle management</li>
</ul>
</div>

</section>

<section>
<h2 class="section-title">Core Competencies</h2>
<div class="skills">
<span>Financial Analysis</span>
<span>Banking Operations</span>
<span>Insurance Advisory</span>
<span>Risk Profiling</span>
<span>MS Excel</span>
<span>Business Growth Strategy</span>
<span>Client Relationship Management</span>
<span>Analytical Thinking</span>
</div>
</section>

<section class="services">
<h2 class="section-title">Advisory Focus</h2>
<div class="card">
<ul>
<li>Investment Structuring Guidance</li>
<li>Insurance Planning</li>
<li>Risk Profiling & Asset Allocation</li>
<li>Long-Term Financial Planning Strategy</li>
</ul>
</div>
</section>

<section>
<h2 class="section-title">Insights (Coming Soon)</h2>
<div class="card">
<p>
Forthcoming articles on macroeconomics, investment psychology, banking systems, financial independence frameworks, and risk strategy.
</p>
</div>
</section>

<section id="contact" class="contact">
<h2>Contact</h2>
<br>
<p>Email: souvik.das39@yahoo.com</p>
<p>Location: Kolkata, West Bengal</p>
<p>LinkedIn: <a href="https://www.linkedin.com/in/souvik-das-14a22b224" target="_blank">View Profile</a></p>
</section>

<footer>
© 2026 Souvik Das | souvik-advisory.netlify.app
</footer>

</body>
</html>

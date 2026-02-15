
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Melvin Jay Canoy | Professional Bookkeeping & Accounting</title>

<meta name="description" content="Professional bookkeeping and accounting services including reconciliation, payroll, financial reporting, and cleanup services for growing businesses.">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>
:root{
  --primary:#0f2c4c;
  --secondary:#1f5fa8;
  --accent:#4a90e2;
  --light:#f4f7fa;
  --dark:#1b1b1b;
}

*{box-sizing:border-box;}

html{
  scroll-behavior:smooth;
}

body{
  margin:0;
  font-family:'Poppins',sans-serif;
  background:var(--light);
  color:#333;
  overflow-x:hidden;
}

/* NAV */
nav{
  position:fixed;
  top:0;
  width:100%;
  background:white;
  box-shadow:0 2px 10px rgba(0,0,0,0.05);
  padding:15px 25px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  z-index:1000;
}

nav .brand{
  font-weight:700;
  color:var(--primary);
}

nav ul{
  list-style:none;
  display:flex;
  gap:20px;
  margin:0;
  padding:0;
}

nav a{
  text-decoration:none;
  color:var(--primary);
  font-weight:500;
  transition:0.3s;
}

nav a:hover{
  color:var(--secondary);
}

/* HERO */
.hero{
  height:100vh;
  background:linear-gradient(rgba(15,44,76,0.85), rgba(15,44,76,0.85)),
  url('https://images.unsplash.com/photo-1554224155-6726b3ff858f?q=80&w=1600&auto=format&fit=crop');
  background-size:cover;
  background-position:center;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  color:white;
  padding:20px;
}

.hero h1{
  font-size:clamp(2rem,6vw,3.5rem);
  margin-bottom:15px;
}

.hero p{
  max-width:650px;
  margin:auto;
  font-size:1.1rem;
}

.hero .btn{
  margin-top:25px;
}

/* BUTTON */
.btn{
  display:inline-block;
  padding:12px 28px;
  border-radius:6px;
  background:var(--secondary);
  color:white;
  text-decoration:none;
  font-weight:500;
  transition:0.3s;
}

.btn:hover{
  background:white;
  color:var(--primary);
}

/* SECTIONS */
section{
  padding:80px 20px;
  max-width:1100px;
  margin:auto;
  opacity:0;
  transform:translateY(40px);
  transition:all 0.7s ease;
}

section.show{
  opacity:1;
  transform:translateY(0);
}

section h2{
  text-align:center;
  margin-bottom:40px;
  color:var(--primary);
}

/* SERVICES GRID */
.grid{
  display:grid;
  gap:25px;
}

.card{
  background:white;
  padding:30px;
  border-radius:10px;
  box-shadow:0 10px 25px rgba(0,0,0,0.05);
  transition:0.3s;
}

.card:hover{
  transform:translateY(-5px);
}

.card h3{
  margin-top:0;
  color:var(--secondary);
}

/* CONSULTATION */
.cta{
  background:var(--primary);
  color:white;
  text-align:center;
  border-radius:12px;
  padding:60px 30px;
}

.cta h2{
  color:white;
}

.socials{
  margin-top:25px;
  display:flex;
  flex-wrap:wrap;
  gap:12px;
  justify-content:center;
}

.socials a{
  padding:10px 18px;
  background:white;
  color:var(--primary);
  border-radius:5px;
  text-decoration:none;
  font-weight:500;
  transition:0.3s;
}

.socials a:hover{
  background:var(--accent);
  color:white;
}

/* FOOTER */
footer{
  background:#0d223b;
  color:white;
  text-align:center;
  padding:25px;
  margin-top:60px;
}

/* RESPONSIVE */
@media(min-width:768px){
  .grid{
    grid-template-columns:repeat(3,1fr);
  }
}
</style>
</head>

<body>

<nav>
  <div class="brand">Melvin Jay Canoy</div>
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#services">Services</a></li>
    <li><a href="#contact">Consult</a></li>
  </ul>
</nav>

<div class="hero">
  <div>
    <h1>Professional Bookkeeping & Accounting Support</h1>
    <p>Helping businesses stay financially organized through accurate bookkeeping, reconciliations, payroll processing, and clear financial reporting.</p>
    <a href="#contact" class="btn">Get Free Consultation</a>
  </div>
</div>

<section id="about">
  <h2>About Me</h2>
  <p style="text-align:center;max-width:700px;margin:auto;">
    I provide structured bookkeeping solutions for small and growing businesses. My goal is to maintain clean financial records, ensure accurate reconciliations, and deliver reliable reports that support informed decision-making.
  </p>
</section>

<section id="services">
  <h2>Services</h2>
  <div class="grid">
    <div class="card"><h3>Full-Service Bookkeeping</h3><p>Weekly or monthly maintenance of financial records.</p></div>
    <div class="card"><h3>Reconciliation</h3><p>Bank and credit card reconciliation for accurate balances.</p></div>
    <div class="card"><h3>Accounts Payable/Receivable</h3><p>Organized tracking of payables and receivables.</p></div>
    <div class="card"><h3>Financial Reports</h3><p>Clear income statements and balance sheets.</p></div>
    <div class="card"><h3>Payroll Processing</h3><p>Accurate payroll computation and recording.</p></div>
    <div class="card"><h3>Book Cleanup</h3><p>Fixing messy or backlogged financial records.</p></div>
  </div>
</section>

<section id="contact">
  <div class="cta">
    <h2>Free Consultation</h2>
    <p>Let’s organize your books and bring clarity to your finances.</p>
    <a href="mailto:melvincanoy0929@gmail.com" class="btn">Email Me</a>

    <div class="socials">
      <a href="https://facebook.com/melvinjaycanoy" target="_blank">Facebook</a>
      <a href="https://www.instagram.com/melvinjay_29?igsh=MTV2cjlheDQ5a2pjeQ==" target="_blank">Instagram</a>
      <a href="https://t.me/melvx1" target="_blank">Telegram</a>
      <a href="https://wa.me/639762268109" target="_blank">WhatsApp</a>
    </div>
  </div>
</section>

<footer>
  © 2026 Melvin Jay Canoy — Professional Bookkeeping & Accounting Services
</footer>

<script>
const observer = new IntersectionObserver(entries=>{
  entries.forEach(entry=>{
    if(entry.isIntersecting){
      entry.target.classList.add("show");
    }
  });
},{threshold:0.15});

document.querySelectorAll("section").forEach(section=>{
  observer.observe(section);
});
</script>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SS Traders | Wholesale Footwear Supplier</title>
<meta name="description" content="SS Traders - Wholesale footwear supplier for men's, women's and kids shoes. Contact us for bulk orders.">

<style>
:root{
  --navy:#101b35;
  --blue:#2457d6;
  --orange:#ff8b35;
  --light:#f5f7fc;
  --white:#fff;
  --gray:#68748a;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{font-family:Arial,sans-serif;color:var(--navy);background:var(--light)}
a{text-decoration:none;color:inherit}
button,input,select,textarea{font:inherit}
button{cursor:pointer}

.topbar{
 background:var(--navy);color:white;text-align:center;
 padding:10px;font-size:13px;
}
header{
 background:white;position:sticky;top:0;z-index:20;
 box-shadow:0 3px 15px #00000010;
}
.nav{
 max-width:1200px;margin:auto;padding:17px 20px;
 display:flex;align-items:center;justify-content:space-between;
 gap:20px;
}
.logo{font-size:27px;font-weight:900;color:var(--blue)}
.logo span{color:var(--orange)}
.navlinks{display:flex;align-items:center;gap:25px;font-size:14px;font-weight:bold}
.navlinks a:hover{color:var(--blue)}
.navbtn{
 background:var(--blue);color:white;border:0;
 border-radius:7px;padding:12px 19px;font-weight:bold;
}
.menu-btn{display:none;border:0;background:none;font-size:25px}
.hero{
 max-width:1200px;margin:30px auto;padding:65px 45px;
 border-radius:18px;min-height:410px;color:white;
 display:flex;align-items:center;
 background:linear-gradient(90deg,#101b35 10%,#101b35d9 52%,#101b3530),
 url('https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=1500')
 center/cover;
}
.hero-content{max-width:570px}
.eyebrow{color:#ffb76d;font-size:13px;font-weight:bold;letter-spacing:3px}
.hero h1{font-size:clamp(35px,5vw,57px);line-height:1.12;margin:20px 0}
.hero p{font-size:16px;color:#e5eafa;line-height:1.8}
.btn{
 display:inline-block;background:var(--orange);color:white;
 padding:15px 24px;border:0;border-radius:7px;
 margin-top:25px;font-weight:bold;
}
.btn:hover{background:#e9781e}
.container{max-width:1200px;margin:auto;padding:45px 20px}
.heading{text-align:center;margin-bottom:30px}
.heading h2{font-size:30px;margin-bottom:10px}
.heading p{color:var(--gray);line-height:1.6}
.features{
 display:grid;grid-template-columns:repeat(4,1fr);
 gap:15px;margin-top:25px;
}
.feature{
 background:white;padding:23px 14px;border-radius:12px;
 display:flex;align-items:center;gap:12px;
}
.feature .emoji{font-size:27px}
.feature strong{font-size:14px}
.feature small{display:block;color:var(--gray);margin-top:5px}
.section-title{font-size:29px;margin-bottom:10px}
.section-sub{color:var(--gray);margin-bottom:25px}
.categories{
 display:grid;grid-template-columns:repeat(3,1fr);gap:20px;
}
.category{
 position:relative;height:260px;border-radius:14px;overflow:hidden;
 background:#ddd;
}
.category img{width:100%;height:100%;object-fit:cover;transition:.4s}
.category:hover img{transform:scale(1.06)}
.category-info{
 position:absolute;bottom:0;left:0;right:0;padding:35px 20px 20px;
 color:white;background:linear-gradient(transparent,#000c);
}
.category-info h3{font-size:24px;margin-bottom:7px}
.category-info p{font-size:13px}
.benefits{
 display:grid;grid-template-columns:repeat(3,1fr);gap:20px;
}
.benefit{
 background:white;border-radius:13px;padding:27px;
 text-align:center;
}
.benefit .emoji{font-size:35px;margin-bottom:13px}
.benefit p{color:var(--gray);font-size:14px;line-height:1.7;margin-top:9px}
.bulk{
 background:linear-gradient(120deg,#101b35,#244fae);
 color:white;border-radius:18px;padding:40px;
 display:grid;grid-template-columns:1fr 1fr;gap:40px;
}
.bulk h2{font-size:32px;margin-bottom:17px}
.bulk-info p{color:#e0e7f9;line-height:1.8}
.bulk-info ul{list-style:none;margin-top:25px}
.bulk-info li{margin:15px 0;color:#f2f5ff}
.bulk-form{
 background:white;color:var(--navy);padding:25px;
 border-radius:12px;
}
.bulk-form h3{font-size:22px;margin-bottom:20px}
.field{margin-bottom:14px}
.field label{display:block;font-size:13px;font-weight:bold;margin-bottom:7px}
.field input,.field select,.field textarea{
 width:100%;padding:13px;border:1px solid #dce1eb;
 border-radius:6px;outline:none;background:#fafbfe;
}
.field input:focus,.field select:focus,.field textarea:focus{
 border-color:var(--blue);
}
.field textarea{min-height:90px;resize:vertical}
.submit-btn{
 width:100%;padding:15px;border:0;border-radius:7px;
 background:var(--blue);color:white;font-weight:bold;
}
.submit-btn:hover{background:#163da8}
.contact-grid{
 display:grid;grid-template-columns:repeat(3,1fr);gap:18px;
}
.contact-card{
 background:white;padding:25px;border-radius:12px;text-align:center;
}
.contact-card .emoji{font-size:30px;margin-bottom:12px}
.contact-card p{color:var(--gray);font-size:14px;margin-top:8px}
footer{background:#101827;color:white;padding:45px 20px 20px}
.footer-inner{
 max-width:1200px;margin:auto;display:grid;
 grid-template-columns:2fr 1fr 1fr;gap:35px;
}
footer h3{margin-bottom:15px}
footer p,footer a{color:#c1cadd;font-size:14px;line-height:2}
footer a{display:block}
footer a:hover{color:white}
.copyright{
 max-width:1200px;margin:30px auto 0;padding-top:20px;
 border-top:1px solid #ffffff25;text-align:center;
 color:#aab4c8;font-size:13px;
}
.whatsapp{
 position:fixed;bottom:20px;right:20px;z-index:30;
 background:#20bd65;color:white;border-radius:50px;
 padding:15px 20px;font-weight:bold;box-shadow:0 4px 15px #0003;
}
@media(max-width:800px){
 .navlinks{
  display:none;position:absolute;top:68px;left:0;right:0;
  background:white;padding:20px;flex-direction:column;align-items:flex-start;
  box-shadow:0 5px 12px #0002;
 }
 .navlinks.show{display:flex}
 .menu-btn{display:block}
 .nav .navbtn{display:none}
 .features{grid-template-columns:repeat(2,1fr)}
 .categories{grid-template-columns:1fr 1fr}
 .bulk{grid-template-columns:1fr;padding:25px}
 .footer-inner{grid-template-columns:1fr 1fr}
}
@media(max-width:550px){
 .hero{margin:15px;padding:35px 22px;min-height:370px}
 .hero h1{font-size:36px}
 .container{padding:35px 15px}
 .categories{grid-template-columns:1fr}
 .category{height:220px}
 .benefits{grid-template-columns:1fr}
 .contact-grid{grid-template-columns:1fr}
 .footer-inner{grid-template-columns:1fr}
 .heading h2,.section-title{font-size:25px}
}
</style>
</head>

<body>

<div class="topbar">
  SS TRADERS | WHOLESALE FOOTWEAR SUPPLIER | BULK ORDERS WELCOME
</div>

<header>
 <div class="nav">
  <a href="#" class="logo">SS <span>TRADERS</span></a>

  <nav class="navlinks" id="navlinks">
   <a href="#">Home</a>
   <a href="#collections">Collections</a>
   <a href="#why-us">Why Us</a>
   <a href="#bulk">Bulk Orders</a>
   <a href="#contact">Contact</a>
  </nav>

  <a class="navbtn" href="#bulk">Request Bulk Quote</a>
  <button class="menu-btn" onclick="toggleMenu()" aria-label="Open menu">☰</button>
 </div>
</header>

<main>

<section class="hero">
 <div class="hero-content">
  <div class="eyebrow">WELCOME TO SS TRADERS</div>
  <h1>Premium Footwear.<br>Wholesale Prices.</h1>
  <p>
   Your trusted footwear wholesale partner.
   Explore our Men's, Women's and Kids collections.
   Quality footwear and attractive bulk deals for your business.
  </p>
  <a class="btn" href="#bulk">GET BULK QUOTE →</a>
 </div>
</section>

<section class="container">
 <div class="features">
  <div class="feature">
   <span class="emoji">📦</span>
   <div><strong>Bulk Orders</strong><small>Wholesale supply</small></div>
  </div>
  <div class="feature">
   <span class="emoji">👟</span>
   <div><strong>Wide Collection</strong><small>Multiple styles</small></div>
  </div>
  <div class="feature">
   <span class="emoji">💰</span>
   <div><strong>Wholesale Deals</strong><small>Competitive pricing</small></div>
  </div>
  <div class="feature">
   <span class="emoji">🤝</span>
   <div><strong>Business Support</strong><small>Direct enquiry</small></div>
  </div>
 </div>
</section>

<section class="container" id="collections">
 <div class="heading">
  <h2>Explore Our Collections</h2>
  <p>Footwear collections for retailers, wholesalers and businesses</p>
 </div>

 <div class="categories">
  <a href="#bulk" class="category">
   <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=700" alt="Men's shoes">
   <div class="category-info">
    <h3>Men's Collection</h3>
    <p>Explore Men's Wholesale Footwear →</p>
   </div>
  </a>

  <a href="#bulk" class="category">
   <img src="https://images.unsplash.com/photo-1543163521-1bf539c55dd2?w=700" alt="Women's shoes">
   <div class="category-info">
    <h3>Women's Collection</h3>
    <p>Explore Women's Wholesale Footwear →</p>
   </div>
  </a>

  <a href="#bulk" class="category">
   <img src="https://images.unsplash.com/photo-1514989940723-e8e51635b782?w=700" alt="Kids footwear">
   <div class="category-info">
    <h3>Kids Collection</h3>
    <p>Explore Kids Wholesale Footwear →</p>
   </div>
  </a>
 </div>
</section>

<section class="container" id="why-us">
 <div class="heading">
  <h2>Why Choose SS Traders?</h2>
  <p>Building strong business relationships through footwear supply</p>
 </div>

 <div class="benefits">
  <div class="benefit">
   <div class="emoji">🏷️</div>
   <h3>Wholesale Pricing</h3>
   <p>Attractive prices for bulk quantity enquiries.</p>
  </div>
  <div class="benefit">
   <div class="emoji">👞</div>
   <h3>Multiple Collections</h3>
   <p>Men's, Women's and Kids footwear collections.</p>
  </div>
  <div class="benefit">
   <div class="emoji">🤝</div>
   <h3>Direct Business Support</h3>
   <p>Connect directly with SS Traders for your orders.</p>
  </div>
 </div>
</section>

<section class="container" id="bulk">
 <div class="bulk">
  <div class="bulk-info">
   <h2>Place Your Bulk Order</h2>
   <p>
    Looking for a reliable footwear wholesale supplier?
    Share your business details and requirements.
    Our team can contact you regarding your bulk order enquiry.
   </p>

   <ul>
    <li>✓ Men's, Women's and Kids footwear</li>
    <li>✓ Bulk quantity enquiries</li>
    <li>✓ Direct WhatsApp enquiry</li>
    <li>✓ Business-to-business orders</li>
   </ul>
  </div>

  <form class="bulk-form" id="bulkForm">
   <h3>Bulk Order Enquiry Form</h3>

   <div class="field">
    <label for="name">Full Name *</label>
    <input id="name" type="text" placeholder="Enter your name" required>
   </div>

   <div class="field">
    <label for="phone">Phone Number *</label>
    <input id="phone" type="tel" placeholder="Enter phone number"
     pattern="[0-9]{10}" maxlength="10" required>
   </div>

   <div class="field">
    <label for="business">Business / Shop Name</label>
    <input id="business" type="text" placeholder="Enter business name">
   </div>

   <div class="field">
    <label for="category">Footwear Category *</label>
    <select id="category" required>
     <option value="">Select category</option>
     <option>Men's Footwear</option>
     <option>Women's Footwear</option>
     <option>Kids Footwear</option>
     <option>All Categories</option>
    </select>
   </div>

   <div class="field">
    <label for="quantity">Required Quantity *</label>
    <input id="quantity" type="number" min="1"
     placeholder="Enter total pairs required" required>
   </div>

   <div class="field">
    <label for="city">City / Location *</label>
    <input id="city" type="text" placeholder="Enter your city" required>
   </div>

   <div class="field">
    <label for="message">Additional Requirements</label>
    <textarea id="message" placeholder="Tell us about your requirements"></textarea>
   </div>

   <button class="submit-btn" type="submit">
    SEND BULK ENQUIRY ON WHATSAPP →
   </button>
  </form>
 </div>
</section>

<section class="container" id="contact">
 <div class="heading">
  <h2>Contact SS Traders</h2>
  <p>For wholesale enquiries and business partnerships</p>
 </div>

 <div class="contact-grid">
  <div class="contact-card">
   <div class="emoji">📞</div>
   <h3>Call Us</h3>
   <p>+91 9198736559</p>
  </div>
  <div class="contact-card">
   <div class="emoji">💬</div>
   <h3>WhatsApp</h3>
   <p>Direct bulk order enquiries</p>
  </div>
  <div class="contact-card">
   <div class="emoji">📦</div>
   <h3>Business Enquiries</h3>
   <p>Wholesale footwear supply</p>
  </div>
 </div>
</section>

</main>

<footer>
 <div class="footer-inner">
  <div>
   <h3 class="logo" style="color:white">SS <span>TRADERS</span></h3>
   <p>Your wholesale footwear business partner.
   Quality collections and bulk order enquiries for retailers and businesses.</p>
  </div>
  <div>
   <h3>Quick Links</h3>
   <a href="#">Home</a>
   <a href="#collections">Collections</a>
   <a href="#why-us">Why Choose Us</a>
   <a href="#bulk">Bulk Orders</a>
  </div>
  <div>
   <h3>Contact</h3>
   <a href="tel:+919198736559">+91 9198736559</a>
   <a href="https://wa.me/919198736559">WhatsApp Us</a>
   <a href="#bulk">Send Enquiry</a>
  </div>
 </div>
 <div class="copyright">
  © 2026 SS Traders. All Rights Reserved.
 </div>
</footer>

<a class="whatsapp" href="https://wa.me/919198736559"
 target="_blank" rel="noopener">☏ WhatsApp</a>

<script>
function toggleMenu(){
 document.getElementById('navlinks').classList.toggle('show');
}

document.querySelectorAll('.navlinks a').forEach(link=>{
 link.addEventListener('click',()=>{
  document.getElementById('navlinks').classList.remove('show');
 });
});

document.getElementById('bulkForm').addEventListener('submit',function(e){
 e.preventDefault();

 const name=document.getElementById('name').value.trim();
 const phone=document.getElementById('phone').value.trim();
 const business=document.getElementById('business').value.trim();
 const category=document.getElementById('category').value;
 const quantity=document.getElementById('quantity').value;
 const city=document.getElementById('city').value.trim();
 const message=document.getElementById('message').value.trim();

 if(!/^[0-9]{10}$/.test(phone)){
  alert('Please enter a valid 10-digit phone number.');
  return;
 }

 if(Number(quantity)<1){
  alert('Please enter a valid quantity.');
  return;
 }

 const text=
 `NEW BULK ORDER ENQUIRY - SS TRADERS\n\n`+
 `Name: ${name}\n`+
 `Phone: ${phone}\n`+
 `Business: ${business || 'Not provided'}\n`+
 `Category: ${category}\n`+
 `Quantity: ${quantity} pairs\n`+
 `City: ${city}\n`+
 `Requirements: ${message || 'Not provided'}`;

 const url='https://wa.me/919198736559?text='+encodeURIComponent(text);
 window.open(url,'_blank');
});
</script>

</body>
</html>

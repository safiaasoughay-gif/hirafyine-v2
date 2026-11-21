
<!DOCTYPE html>
<html lang="fr"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1"><title>HIRAFYIN - Takwin Mihani</title>
<style>*{margin:0;padding:0;box-sizing:border-box}body{font-family:Arial}header{background:#0a1a2f;color:#fff;padding:15px 20px;display:flex;justify-content:space-between;align-items:center}header b{font-size:24px}header b span{color:#ffc107}header a{background:#ffc107;color:#000;padding:10px 18px;border-radius:20px;text-decoration:none;font-weight:800}.hero{background:linear-gradient(135deg,#0a1a2f,#1a3a5f);color:#fff;padding:60px 20px;text-align:center}.hero h1{font-size:42px}.hero h1 span{color:#ffc107}.hero p{margin:15px 0;font-size:18px}.hero a{background:#ffc107;color:#000;padding:14px 28px;border-radius:25px;text-decoration:none;font-weight:800;display:inline-block}.sec{padding:40px 20px;max-width:1000px;margin:auto}.sec h2{text-align:center;margin-bottom:25px;font-size:28px}.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:20px}.card{border:1px solid #ddd;border-radius:15px;padding:20px;text-align:center}.card h3{margin:10px 0}.card p{color:#666}.card b{color:#0a1a2f;font-size:20px}.card a{background:#0a1a2f;color:#fff;padding:10px 20px;border-radius:20px;text-decoration:none;display:inline-block;margin-top:12px}.form{background:#f8f9fa;border-radius:15px;padding:25px;max-width:500px;margin:20px auto}.form input,.form select{width:100%;padding:12px;margin:8px 0;border:1px solid #ddd;border-radius:8px}.form button{background:#25D366;color:#fff;border:0;padding:14px;width:100%;border-radius:8px;font-weight:800;font-size:16px;cursor:pointer}footer{background:#0a1a2f;color:#fff;text-align:center;padding:25px}footer a{color:#ffc107}</style>
</head><body>
<header><b>HIRA<span>FYIN</span></b><a href="#inscription">Sajel Daba</a></header>
<div class="hero"><h1>Ta3lem <span>7erfa</span><br>W Bda Tkhdem</h1><p>Takwinat mihaniya 100% pratique - Agadir w en ligne</p><a href="#formations">Chouf Takwinat</a></div>
<div class="sec" id="formations"><h2>Takwinat Dyawlna</h2><div class="grid">
<div class="card"><div style="font-size:40px">💇‍♀️</div><h3>Coiffure & Esthetique</h3><p>Ta3lem coiffure, maquillage w soin - 3 mois</p><b>2500 MAD</b><br><a href="#inscription">Sajel</a></div>
<div class="card"><div style="font-size:40px">🍰</div><h3>Patisserie & Cuisine</h3><p>7elwiyat, khobz, cuisine marocaine - 3 mois</p><b>2200 MAD</b><br><a href="#inscription">Sajel</a></div>
<div class="card"><div style="font-size:40px">💻</div><h3>Informatique & Design</h3><p>Word, Excel, Photoshop, Canva - 2 mois</p><b>1800 MAD</b><br><a href="#inscription">Sajel</a></div>
<div class="card"><div style="font-size:40px">✂️</div><h3>Couture & Mode</h3><p>Khyata, couture traditionnelle w moderne - 4 mois</p><b>2400 MAD</b><br><a href="#inscription">Sajel</a></div>
<div class="card"><div style="font-size:40px">🔌</div><h3>Electricite & Plomberie</h3><p>Installation, reparation - 4 mois</p><b>2600 MAD</b><br><a href="#inscription">Sajel</a></div>
<div class="card"><div style="font-size:40px">📱</div><h3>Marketing Digital</h3><p>Instagram, TikTok, Vente en ligne - 2 mois</p><b>1900 MAD</b><br><a href="#inscription">Sajel</a></div>
</div></div>
<div class="sec" id="inscription"><h2>Sajel Daba</h2><div class="form">
<input id="nom" placeholder="Smiya Kamla *">
<input id="tel" placeholder="Numero WhatsApp *">
<select id="form"><option>Choisir la formation</option><option>Coiffure - 2500 MAD</option><option>Patisserie - 2200 MAD</option><option>Informatique - 1800 MAD</option><option>Couture - 2400 MAD</option><option>Electricite - 2600 MAD</option><option>Marketing Digital - 1900 MAD</option></select>
<button onclick="envoyer()">Sajel f WhatsApp</button>
<p style="text-align:center;margin-top:10px;font-size:13px;color:#666">Admin: Lahcen Assoughay - lahcenassoughay@gmail.com</p>
</div></div>
<footer><b>HIRA<span style="color:#ffc107">FYIN</span></b><p>Agadir - Maroc | lahcenassoughay@gmail.com</p><p><a href="admin.html">Espace Admin</a></p></footer>
<script>function envoyer(){let n=document.getElementById('nom').value;let t=document.getElementById('tel').value;let f=document.getElementById('form').value;if(!n||!t) return alert('3mer smiya w numero');let msg='Salam HIRAFYIN, bghit nsajel: '+n+' - '+f+' - Tel: '+t;window.open('https://wa.me/212600000000?text='+encodeURIComponent(msg));}</script>
</body></html>

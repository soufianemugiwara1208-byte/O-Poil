<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>O'poil.com - Bien-être Animal</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root {
      --green: #4CAF50; --green-dark: #388E3C; --green-light: #f4faf4;
      --text: #222; --muted: #666; --border: #e0e0e0; --white: #fff;
      --shadow: 0 4px 20px rgba(0,0,0,0.08);
    }
    *, *::before, *::after { margin:0; padding:0; box-sizing:border-box; }
    body { font-family:'Open Sans',sans-serif; color:var(--text); background:var(--white); line-height:1.6; }
    a { text-decoration:none; color:var(--green); }
    .container { max-width:1200px; margin:0 auto; padding:0 24px; }

    /* HEADER */
    .header { position:sticky; top:0; z-index:100; background:var(--white); border-bottom:1px solid var(--border); box-shadow:0 2px 12px rgba(0,0,0,0.06); }
    .header .container { display:flex; align-items:center; justify-content:space-between; height:64px; }
    .logo { font-family:'Montserrat',sans-serif; font-size:1.4rem; font-weight:700; color:var(--green); display:flex; align-items:center; gap:8px; }
    .nav ul { list-style:none; display:flex; gap:28px; }
    .nav a { font-weight:600; font-size:0.92rem; color:var(--text); transition:color 0.2s; }
    .nav a:hover { color:var(--green); }

    /* HERO */
    .hero { background:linear-gradient(135deg,rgba(0,0,0,0.52),rgba(0,0,0,0.3)), url('https://images.unsplash.com/photo-1548199973-03cce0bbc87b?auto=format&fit=crop&w=1400&q=80') center/cover no-repeat; color:white; padding:110px 0; text-align:center; }
    .hero-content { max-width:700px; margin:0 auto; }
    .hero h2 { font-family:'Montserrat',sans-serif; font-size:2.6rem; font-weight:700; margin-bottom:18px; line-height:1.2; }
    .hero p { font-size:1.15rem; margin-bottom:32px; opacity:0.92; }
    .btn-hero { display:inline-block; background:var(--green); color:white; padding:14px 36px; border-radius:8px; font-family:'Montserrat',sans-serif; font-weight:700; font-size:1rem; transition:background 0.25s,transform 0.2s; }
    .btn-hero:hover { background:var(--green-dark); transform:translateY(-2px); }

    /* SECTION */
    .section { padding:70px 0; }
    .section-title { font-family:'Montserrat',sans-serif; font-size:2rem; font-weight:700; text-align:center; color:var(--green); margin-bottom:48px; }

    /* GRILLE */
    .produits-grid { display:grid; grid-template-columns:repeat(auto-fill,minmax(260px,1fr)); gap:28px; }
    .produit-card { background:white; border-radius:14px; box-shadow:var(--shadow); overflow:hidden; transition:transform 0.3s,box-shadow 0.3s; cursor:pointer; border:1px solid var(--border); }
    .produit-card:hover { transform:translateY(-6px); box-shadow:0 12px 32px rgba(76,175,80,0.15); }
    .card-img-wrap { width:100%; height:240px; overflow:hidden; background:#f8f8f8; display:flex; align-items:center; justify-content:center; }
    .card-img-wrap img { width:100%; height:100%; object-fit:contain; padding:14px; transition:transform 0.4s; }
    .produit-card:hover .card-img-wrap img { transform:scale(1.06); }
    .card-body { padding:18px 20px 22px; }
    .card-body h3 { font-family:'Montserrat',sans-serif; font-size:1rem; font-weight:700; margin-bottom:6px; }
    .card-body .desc-courte { font-size:0.83rem; color:var(--muted); line-height:1.5; margin-bottom:14px; }
    .card-body .prix { font-family:'Montserrat',sans-serif; font-weight:700; color:var(--green); font-size:1.2rem; margin-bottom:14px; }
    .card-btns { display:flex; gap:10px; }
    .btn-voir { flex:1; background:transparent; color:var(--green); border:2px solid var(--green); padding:9px 12px; border-radius:7px; font-family:'Montserrat',sans-serif; font-weight:600; font-size:0.85rem; cursor:pointer; transition:all 0.2s; }
    .btn-voir:hover { background:var(--green); color:white; }
    .btn-acheter { flex:1.4; background:var(--green); color:white; border:none; padding:9px 12px; border-radius:7px; font-family:'Montserrat',sans-serif; font-weight:700; font-size:0.85rem; cursor:pointer; transition:background 0.2s; display:flex; align-items:center; justify-content:center; gap:6px; }
    .btn-acheter:hover { background:var(--green-dark); }
    .btn-acheter.loading, .btn-acheter-modal.loading { opacity:0.7; cursor:not-allowed; }

    /* MODAL */
    .modal-produit-overlay { display:none; position:fixed; inset:0; background:rgba(0,0,0,0.65); z-index:400; justify-content:center; align-items:center; padding:20px; }
    .modal-produit-overlay.open { display:flex; }
    .modal-produit { background:white; border-radius:18px; max-width:720px; width:100%; max-height:90vh; overflow-y:auto; display:grid; grid-template-columns:1fr 1fr; box-shadow:0 30px 80px rgba(0,0,0,0.3); animation:slideUp 0.3s ease; position:relative; }
    @keyframes slideUp { from{transform:translateY(24px);opacity:0} to{transform:translateY(0);opacity:1} }
    .modal-produit-img { border-radius:18px 0 0 18px; overflow:hidden; min-height:340px; background:#f8f8f8; display:flex; align-items:center; justify-content:center; }
    .modal-produit-img img { width:100%; height:100%; object-fit:contain; padding:24px; }
    .modal-produit-body { padding:36px 30px; display:flex; flex-direction:column; gap:14px; }
    .btn-close-modal { position:absolute; top:14px; right:16px; background:rgba(0,0,0,0.1); border:none; border-radius:50%; width:36px; height:36px; font-size:1.2rem; cursor:pointer; display:flex; align-items:center; justify-content:center; color:#333; transition:background 0.2s; z-index:5; }
    .btn-close-modal:hover { background:rgba(0,0,0,0.22); }
    .modal-badge { display:inline-block; background:var(--green-light); color:var(--green); font-size:0.75rem; font-weight:700; padding:4px 12px; border-radius:20px; width:fit-content; }
    .modal-produit-body h2 { font-family:'Montserrat',sans-serif; font-size:1.45rem; line-height:1.3; }
    .modal-produit-prix { font-family:'Montserrat',sans-serif; font-size:2.1rem; font-weight:700; color:var(--green); }
    .modal-produit-desc { font-size:0.93rem; color:var(--muted); line-height:1.75; }
    .btn-acheter-modal { background:var(--green); color:white; border:none; padding:15px 20px; border-radius:9px; font-family:'Montserrat',sans-serif; font-weight:700; font-size:1rem; cursor:pointer; transition:background 0.25s; margin-top:auto; display:flex; align-items:center; justify-content:center; gap:8px; }
    .btn-acheter-modal:hover { background:var(--green-dark); }

    /* TOAST */
    .toast { position:fixed; bottom:28px; left:50%; transform:translateX(-50%) translateY(60px); background:#333; color:white; padding:12px 24px; border-radius:30px; font-size:0.9rem; z-index:999; transition:transform 0.3s ease; white-space:nowrap; pointer-events:none; }
    .toast.show { transform:translateX(-50%) translateY(0); }
    .toast.error { background:#e53935; }

    /* APROPOS / CONTACT */
    .apropos-content { max-width:680px; margin:0 auto; text-align:center; font-size:1.05rem; color:var(--muted); line-height:1.8; }
    .apropos-content p+p { margin-top:14px; }
    .contact-content { text-align:center; font-size:1.05rem; }
    .contact-content a { font-weight:600; }
    .contact-content a:hover { text-decoration:underline; }

    /* FOOTER */
    .footer { background:var(--green-light); border-top:1px solid var(--border); padding:28px 0; text-align:center; font-size:0.85rem; color:var(--muted); }

    /* RESPONSIVE */
    @media (max-width:768px) {
      .nav { display:none; }
      .hero h2 { font-size:1.75rem; }
      .modal-produit { grid-template-columns:1fr; }
      .modal-produit-img { border-radius:18px 18px 0 0; min-height:220px; }
    }
  </style>
</head>
<body>

  <header class="header">
    <div class="container">
      <div class="logo"><i class="fas fa-paw"></i> O'poil.com</div>
      <nav class="nav">
        <ul>
          <li><a href="#accueil">Accueil</a></li>
          <li><a href="#boutique">Boutique</a></li>
          <li><a href="#apropos">A Propos</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="accueil" class="hero">
    <div class="container">
      <div class="hero-content">
        <h2>Le Bien-etre de vos Compagnons, Notre Priorite</h2>
        <p>Des produits soigneusement selectionnes pour le confort et la sante de vos animaux au quotidien.</p>
        <a href="#boutique" class="btn-hero">Decouvrir la boutique</a>
      </div>
    </div>
  </section>

  <section id="boutique" class="section">
    <div class="container">
      <h2 class="section-title">Notre Boutique</h2>
      <div class="produits-grid" id="produits-container"></div>
    </div>
  </section>

  <div class="modal-produit-overlay" id="modal-produit-overlay">
    <div class="modal-produit">
      <button class="btn-close-modal" id="btn-close-modal">x</button>
      <div class="modal-produit-img">
        <img id="modal-img" src="" alt="">
      </div>
      <div class="modal-produit-body">
        <span class="modal-badge">Bien-etre animal</span>
        <h2 id="modal-nom"></h2>
        <div class="modal-produit-prix" id="modal-prix"></div>
        <p class="modal-produit-desc" id="modal-desc"></p>
        <button class="btn-acheter-modal" id="modal-btn-acheter">
          Acheter maintenant
        </button>
      </div>
    </div>
  </div>

  <div class="toast" id="toast"></div>

  <section id="apropos" class="section" style="background:var(--green-light);">
    <div class="container">
      <h2 class="section-title">A Propos de O'poil.com</h2>
      <div class="apropos-content">
        <p>O'poil.com est ne d'une passion pour les animaux et d'une volonte de proposer des accessoires penses pour leur bien-etre et leur confort au quotidien.</p>
        <p>Nous selectionnons des produits de qualite, sans toxiques, avec des partenaires engages dans le respect et le soin des animaux de compagnie.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="section">
    <div class="container">
      <h2 class="section-title">Contactez-Nous</h2>
      <div class="contact-content">
        <p>Une question ? Ecrivez-nous a <a href="mailto:opoil.question@gmail.com">opoil.question@gmail.com</a></p>
      </div>
    </div>
  </section>

  <footer class="footer">
    <div class="container">
      <p>2026 O'poil.com - Tous droits reserves</p>
    </div>
  </footer>

  <script>
    const produits = [
      { id:'jouet-lin', priceId:'price_1TTQzLHAaFMhZu4WCp7IBQix', nom:'Jouet de Dentition en Lin Tresse', prix:9.99, image:'jouet-lin.jpg', descCourte:'Soulage les gencives et stimule l instinct de jeu de votre compagnon.', descLongue:'Fabrique a partir de fibres de lin naturel soigneusement tressee, ce jouet est concu pour accompagner votre animal dans ses moments de jeu tout en prenant soin de ses gencives. Sa texture douce mais resistante soulage les inconforts lies a la dentition et maintient les dents propres. Ideal pour les chiots comme les chiens adultes, il favorise une mastication saine et procure un vrai sentiment de bien-etre. Un compagnon de jeu durable qui respecte la sensibilite de votre animal.' },
      { id:'brosse-vapeur', priceId:'price_1TTQzLHAaFMhZu4W82cPnXPv', nom:'Brosse Vapeur Autonettoyante', prix:8.90, image:'brosse-vapeur.jpg', descCourte:'Elimine les poils morts en douceur, se nettoie en un clic.', descLongue:'Cette brosse vapeur revolutionne le toilettage de votre compagnon en combinant douceur et efficacite. Sa technologie vapeur detend le poil et denoue les noeuds sans tirer, pour une experience agreable meme pour les animaux les plus sensibles. Le systeme autonettoyant ejecte les poils collectes en une simple pression, rendant chaque seance rapide et sans effort. Offrez a votre animal un soin quotidien qui renforce aussi le lien affectif entre vous.' },
      { id:'spray-buccal', priceId:'price_1TTQzLHAaFMhZu4WYCLHQ9nk', nom:'Spray Buccal Haleine Fraiche', prix:8.00, image:'spray-buccal.jpg', descCourte:'Neutralise les odeurs et prend soin de l hygiene dentaire au quotidien.', descLongue:'Formule specialement pour les chiens et chats, ce spray buccal agit en quelques secondes pour neutraliser les mauvaises odeurs et assainir la cavite buccale de votre animal. Sa formule douce, sans alcool et sans produits agressifs, convient a un usage quotidien et protege l email dentaire sur le long terme. Facile a appliquer meme sur les animaux recalcitrants, il contribue a prevenir les problemes de gencives et de tartre. Un geste simple pour le confort et la sante de votre compagnon.' },
      { id:'soin-oreilles', priceId:'price_1TTQzOHAaFMhZu4Wb4jNi3d0', nom:'Gouttes de Soin Auriculaire', prix:11.00, image:'soin-oreilles.jpg', descCourte:'Nettoie et apaise les oreilles en profondeur, previent les irritations.', descLongue:'Ces gouttes auriculaires sont formulees pour offrir un nettoyage doux et complet des oreilles de votre animal, une zone souvent negligee mais essentielle a son confort. Leur action apaisante reduit les irritations, elimine l exces de cerumen et previent l apparition d infections frequentes. La solution ne pique pas et seche rapidement, pour un soin sans stress et sans inconfort. Votre compagnon retrouve un confort auriculaire durable des les premieres applications.' }
    ];

    async function handleCheckout(priceId, btn) {
      if (btn) { btn.classList.add('loading'); btn.innerHTML = 'Redirection en cours...'; }
      try {
        const res = await fetch('/api/checkout', {
          method: 'POST',
          headers: { 'Content-Type': 'application/json' },
          body: JSON.stringify({ priceId })
        });
        if (!res.ok) { const e = await res.json(); throw new Error(e.error || 'Erreur serveur'); }
        const data = await res.json();
        window.location.href = data.url;
      } catch (err) {
        showToast('Erreur : ' + err.message, 'error');
        if (btn) { btn.classList.remove('loading'); btn.innerHTML = 'Acheter maintenant'; }
      }
    }

    let modalPriceId = null;
    function ouvrirModalProduit(id) {
      const p = produits.find(pr => pr.id === id);
      if (!p) return;
      modalPriceId = p.priceId;
      document.getElementById('modal-img').src = p.image;
      document.getElementById('modal-img').alt = p.nom;
      document.getElementById('modal-nom').textContent = p.nom;
      document.getElementById('modal-prix').textContent = p.prix.toFixed(2) + ' EUR';
      document.getElementById('modal-desc').textContent = p.descLongue;
      const btn = document.getElementById('modal-btn-acheter');
      btn.classList.remove('loading');
      btn.textContent = 'Acheter maintenant';
      btn.onclick = () => handleCheckout(modalPriceId, btn);
      document.getElementById('modal-produit-overlay').classList.add('open');
      document.body.style.overflow = 'hidden';
    }

    function fermerModalProduit() {
      document.getElementById('modal-produit-overlay').classList.remove('open');
      document.body.style.overflow = '';
    }

    function afficherProduits() {
      const ph = "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 300 240'%3E%3Crect fill='%23f5f5f5' width='300' height='240'/%3E%3Ctext x='150' y='130' text-anchor='middle' font-size='13' fill='%23bbb'%3EPhoto a venir%3C/text%3E%3C/svg%3E";
      document.getElementById('produits-container').innerHTML = produits.map(p => `
        <div class="produit-card" onclick="ouvrirModalProduit('${p.id}')">
          <div class="card-img-wrap"><img src="${p.image}" alt="${p.nom}" onerror="this.src='${ph}'"></div>
          <div class="card-body">
            <h3>${p.nom}</h3>
            <p class="desc-courte">${p.descCourte}</p>
            <p class="prix">${p.prix.toFixed(2)} EUR</p>
            <div class="card-btns">
              <button class="btn-voir" onclick="event.stopPropagation();ouvrirModalProduit('${p.id}')">Voir le produit</button>
              <button class="btn-acheter" onclick="event.stopPropagation();handleCheckout('${p.priceId}',this)">Acheter</button>
            </div>
          </div>
        </div>`).join('');
    }

    function showToast(msg, type) {
      const t = document.getElementById('toast');
      t.textContent = msg; t.className = 'toast '+(type||'')+' show';
      setTimeout(() => t.classList.remove('show'), 3500);
    }

    document.addEventListener('DOMContentLoaded', () => {
      afficherProduits();
      document.getElementById('btn-close-modal').addEventListener('click', fermerModalProduit);
      document.getElementById('modal-produit-overlay').addEventListener('click', e => {
        if (e.target === document.getElementById('modal-produit-overlay')) fermerModalProduit();
      });
    });
  </script>
</body>
</html>

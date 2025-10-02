<!doctype html>
<html lang="pl">
<head>
  <meta charset="utf-8" />
  <title>AltHouse — Galeria G (Gloss + Galaxy)</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body {
      margin:0;
      font-family: system-ui, Arial, sans-serif;
      background:#000;
      color:#fff;
    }

    .al-widget {
      display:block;
      background:transparent;
      padding:0;
      margin:0 auto;
      max-width:900px;
      width:100%;
    }

    .al-photo {
      display:block;
      width:100%;
      height:auto;
      border-radius:10px;
      margin:0 auto;
      box-shadow:0 10px 26px rgba(0,0,0,.35);
    }

    .al-buttons {
      display:flex;
      flex-wrap:wrap;
      gap:10px;
      justify-content:flex-start;
      margin:16px 0 10px;
    }

    .al-btn {
      border:2px solid rgba(255,255,255,.75);
      border-radius:999px;
      padding:8px 16px;
      font-weight:600;
      cursor:pointer;
      user-select:none;
      font-size:14px;
      transition:.15s transform, .15s filter;
      box-shadow:0 3px 10px rgba(0,0,0,.12);
    }

    .al-btn:hover { transform:translateY(-1px); filter:brightness(.95); }
    .al-btn.is-active { outline:2px solid rgba(255,255,255,.45); }

    .al-caption {
      font-size:14px;
      color:#fff;
      margin-top:8px;
    }
  </style>
</head>
<body>
  <div class="al-widget">
    <img id="photo" class="al-photo" alt="Sufit napinany" />
    <div id="buttons" class="al-buttons"></div>
    <div id="caption" class="al-caption"></div>
  </div>

  <script>
    const items = [
      // --- G klasyczne ---
      { id:'g110', label:'G110', file:'500 G 110 Light Blue.png', color:'#86C5FF', textColor:'#000', desc:'G110 Light Blue — świeży błękit, kuchnie/łazienki. 320/500 cm' },
      { id:'g156', label:'G156', file:'500 G 156 Blue.png',       color:'#4DA3FF', textColor:'#000', desc:'G156 Blue — elegancki chłodny ton, biura i salony. 320/500 cm' },
      { id:'g160', label:'G160', file:'500 G 160 Blue.png',       color:'#2D77FF', textColor:'#fff', desc:'G160 Głęboki Blue — nowoczesny salon. 320/500 cm' },
      { id:'g305', label:'G305', file:'500 G 305 Ivory.png',      color:'#f0e2cc', textColor:'#000', desc:'G305 Ivory — ciepły odcień do sypialni. 320/500 cm' },
      { id:'g307', label:'G307', file:'500 G 307 Beige.png',      color:'#e3d5b8', textColor:'#000', desc:'G307 Beige — uniwersalny, przytulny. 320/500 cm' },
      { id:'g309', label:'G309', file:'500 G 309 Cream.png',      color:'#f7f0da', textColor:'#000', desc:'G309 Cream — jasny, do kuchni i salonu. 320/500 cm' },
      { id:'g313', label:'G313', file:'500 G 313 Silver.png',     color:'#c0c0c0', textColor:'#000', desc:'G313 Silver — chłodny połysk, biura i nowoczesne wnętrza. 320/500 cm' },
      { id:'g317', label:'G317', file:'500 G 317 Steel.png',      color:'#999999', textColor:'#000', desc:'G317 Steel — surowa elegancja loftu. 320/500 cm' },
      { id:'g319', label:'G319', file:'500 G 319 Graphite.png',   color:'#555555', textColor:'#fff', desc:'G319 Graphite — mocny charakter do salonu. 320/500 cm' },
      { id:'g333', label:'G333', file:'500 G 333 Charcoal.png',   color:'#333333', textColor:'#fff', desc:'G333 Charcoal — głęboka czerń, kino domowe. 320/500 cm' },
      { id:'g347', label:'G347', file:'500 G 347 Black.png',      color:'#000000', textColor:'#fff', desc:'G347 Black — klasyczna elegancja. 320/500 cm' },
      { id:'g462', label:'G462', file:'500 G 462 Red.png',        color:'#ff0000', textColor:'#fff', desc:'G462 Red — dynamiczny akcent, restauracje. 320/500 cm' },
      { id:'g507', label:'G507', file:'500 G 507 Champagne.png',  color:'#f7e2a8', textColor:'#000', desc:'G507 Champagne — luksusowy połysk. 320/500 cm' },
      { id:'g511', label:'G511', file:'500 G 511 Vanillal.png',   color:'#f5e0c6', textColor:'#000', desc:'G511 Vanilla — ciepły ton, pokoje dziecięce. 320/500 cm' },
      { id:'g571', label:'G571', file:'500 G 571 Brown.png',      color:'#5a381e', textColor:'#fff', desc:'G571 Brown — przytulne wnętrza, sypialnie. 320/500 cm' },
      { id:'g721', label:'G721', file:'500 G 721 Yelloy.png',     color:'#ffd200', textColor:'#000', desc:'G721 Yellow — energetyczny, kuchnie. 320/500 cm' },

      // --- GALAXY ---
      { id:'galaxy-black', label:'Galaxy Black', file:'Galaxy 320 Galaxy 303 Galaxy Black.png', color:'#0c1330', textColor:'#fff', desc:'Galaxy Black (303) — efekt gwiaździstego nieba. 320/500 cm' },
      { id:'galaxy-white', label:'Galaxy White', file:'Galaxy 320 Galaxy 347 Galaxy White.png', color:'#fff2c9', textColor:'#000', desc:'Galaxy White (347) — delikatny rozgwieżdżony sufit. 320/500 cm' }
    ];

    const $img = document.getElementById('photo');
    const $cap = document.getElementById('caption');
    const $btns = document.getElementById('buttons');

    function activate(id){
      document.querySelectorAll('.al-btn').forEach(b=>{
        b.classList.toggle('is-active', b.dataset.id===id);
      });
    }

    function show(id){
      const it = items.find(x=>x.id===id);
      $img.src = it.file;
      $img.alt = 'Sufit – ' + it.label;
      $cap.textContent = it.desc;
      activate(id);
    }

    items.forEach(it=>{
      const b=document.createElement('button');
      b.className='al-btn';
      b.dataset.id=it.id;
      b.textContent=it.label;
      b.style.background=it.color;
      b.style.color=it.textColor;
      b.onclick=()=>show(it.id);
      $btns.appendChild(b);
    });

    show(items[0].id);
  </script>
</body>
</html>

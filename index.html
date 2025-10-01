<!doctype html>
<html lang="pl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Skrzynka Odbiorcza — Wiara Przenosi Góry</title>

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg-start: #9fc6e2;
      --bg-end: #cfe8f8;
      --navy: #1e3a8a;
      --btn-start: #3b5998;
      --btn-end: #5a8dee;
      --card: #ffffff;
      --radius: 14px;
      --shadow: 0 10px 30px rgba(30,58,138,0.08);
      --muted: #6b7280;
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: Roboto, system-ui, -apple-system, 'Segoe UI', Arial;
      background: linear-gradient(180deg,var(--bg-start),var(--bg-end));
      color: #0b1220;
      padding:20px;
      -webkit-font-smoothing:antialiased;
    }

    .container{
      max-width:1100px;
      margin:0 auto;
      background: linear-gradient(180deg, rgba(255,255,255,0.92), var(--card));
      border-radius:18px;
      box-shadow: var(--shadow);
      padding:18px;
    }

    header{display:flex;gap:18px;align-items:center;margin-bottom:14px}
    .logo{display:flex;flex-direction:column;gap:4px}
    h1{margin:0;font-family:Pacifico, cursive;color:var(--navy);font-size:30px}
    p.lead{margin:0;color:var(--muted);font-size:14px}

    .tabs{display:flex;gap:8px;margin:14px 0 18px 0}
    .tab{background:transparent;border:1px solid rgba(30,58,138,0.08);padding:10px 14px;border-radius:12px;cursor:pointer;font-weight:600;color:var(--navy);transition:transform .14s ease;text-decoration:none;display:inline-flex;align-items:center;gap:8px}
    .tab:hover{transform:translateY(-2px);box-shadow:0 6px 16px rgba(30,58,138,0.05)}
    .tab.active{background:linear-gradient(180deg,var(--btn-start),var(--btn-end));color:#fff;border:none;box-shadow:0 10px 26px rgba(58,88,160,0.16)}

    /* panels layout */
    .layout{display:block}
    @media(min-width:900px){.layout{display:grid;grid-template-columns:1fr 1fr;gap:20px}}

    .panel{background:var(--card);border-radius:var(--radius);padding:14px;box-shadow:0 6px 20px rgba(17,24,39,0.04);min-height:220px}
    .panel h2{margin-top:0;margin-bottom:8px;color:var(--navy);font-size:18px}

    /* chat-like list */
    .list{display:flex;flex-direction:column;gap:12px;margin-top:8px;padding:6px 4px}

    .item{max-width:86%;padding:12px;border-radius:16px;display:flex;flex-direction:column;gap:8px;box-shadow:0 6px 18px rgba(30,58,138,0.04);border:none;cursor:pointer}
    .item .meta{display:flex;justify-content:space-between;align-items:center;font-size:13px;color:var(--muted)}
    .item .by{font-size:12px;font-weight:700;color:var(--navy)}
    .item .title{font-weight:700;color:var(--navy);font-size:15px}
    .item .body{font-size:14px;color:#1f2937;line-height:1.5;white-space:pre-wrap}

    /* nowe: białe tło (nie gradient), wyróżnione cieniem, ustawione po prawej jak "ja" w czacie */
    .bubble-new{background:var(--card);color:#0b1220;align-self:flex-end;border:1px solid rgba(30,58,138,0.06);box-shadow:0 10px 24px rgba(30,58,138,0.06);border-bottom-right-radius:8px}

    /* odebrane: stonowane, po lewej */
    .bubble-read{background:linear-gradient(180deg, rgba(245,250,255,0.9), #ffffff);color:#0b1220;align-self:flex-start;border:1px solid rgba(30,58,138,0.03)}

    .empty{color:var(--muted);padding:18px;border-radius:12px;background:linear-gradient(180deg, rgba(245,250,255,0.8), rgba(255,255,255,0.6));text-align:center}

    .footer-actions{display:flex;gap:8px;margin-top:12px;align-items:center}
    .btn{border:none;padding:10px 14px;border-radius:12px;font-weight:600;cursor:pointer;background:linear-gradient(180deg,var(--btn-start),var(--btn-end));color:#fff;box-shadow:0 8px 20px rgba(58,88,160,0.14)}

    /* hidden helper to truly hide panels */
    .hidden{display:none !important}

    /* Mobile tweaks for portrait — full-width bubbles, lepsza czytelność */
    @media(max-width:599px){
      body{padding:12px}
      .container{padding:12px}
      h1{font-size:24px}
      .item{max-width:100%;border-radius:12px}
      .bubble-new{align-self:flex-end;margin-left:auto}
      .bubble-read{align-self:flex-start;margin-right:auto}
      .list{gap:10px}
    }
  </style>
</head>
<body>
  <div class="container" role="application" aria-label="Skrzynka odbiorcza">
    <header>
      <div class="logo">
        <h1>Skrzynka Odbiorcza</h1>
        <p class="lead">Ogłoszenia z bloga "Wiara Przenosi Góry" — prosto i czysto, jak rozmowa.</p>
      </div>
      <div style="flex:1"></div>
    </header>

    <nav class="tabs" role="tablist">
      <a class="tab" id="tab-new" href="#nowe">Nowe <span id="count-new" style="margin-left:6px;color:var(--muted)">(0)</span></a>
      <a class="tab" id="tab-read" href="#odebrane">Odebrane <span id="count-read" style="margin-left:6px;color:var(--muted)">(0)</span></a>
    </nav>

    <main class="layout">
      <!-- Nowe panel (osobna 'strona' pod #nowe) -->
      <section class="panel" id="panel-new" aria-labelledby="nowe-title">
        <h2 id="nowe-title">Nowe ogłoszenia</h2>
        <div id="list-new" class="list" aria-live="polite"></div>
      </section>

      <!-- Odebrane panel (osobna 'strona' pod #odebrane) -->
      <section class="panel" id="panel-read" aria-labelledby="odebrane-title">
        <h2 id="odebrane-title">Odebrane</h2>
        <div id="list-read" class="list" aria-live="polite"></div>
      </section>
    </main>

    <div class="footer-actions">
      <button class="btn" id="refreshBtn">Odśwież</button>
      <div style="flex:1"></div>
      <!-- Usunięto informację o czyszczeniu localStorage zgodnie z życzeniem -->
    </div>
  </div>

  <script>
    const STORAGE_KEY = 'wiara_inbox_v1';
    const AUTHOR_NAME = 'Kacper Czarnojan';

    // Domyślne ogłoszenia (wstawiane tylko jeśli localStorage jest pusty)
    const initialAnnouncements = [
      {
        id: 'a1',
        date: '2025-10-01',
        title: 'Powrót do Klasyki',
        content: 'Przywróciłem klasyczną niebieską szatę graficzną bloga „Wiara Przenosi Góry”. Chciałem, by czytanie było spokojniejsze i bardziej przejrzyste — mam nadzieję, że ta prostota Wam się spodoba.',
        source: 'Wiara Przenosi Góry',
        read: false
      },
      {
        id: 'a2',
        date: '2025-10-01',
        title: 'Darmowy Prezent Na Start!',
        content: 'Specjalny kod QQWE19 — wpisz go w aplikacji „Codzienny Cytat”, aby otrzymać darmowe 30 dni passy. Oferta ograniczona czasowo. Powodzenia i miłego czytania!',
        source: 'Wiara Przenosi Góry',
        read: false
      }
    ];

    // Inicjalizuj tylko jeśli nie ma jeszcze wpisu
    (function initIfEmpty(){
      try{
        const raw = localStorage.getItem(STORAGE_KEY);
        if(!raw){
          localStorage.setItem(STORAGE_KEY, JSON.stringify(initialAnnouncements));
        }
      }catch(e){
        console.error('Błąd podczas inicjalizacji localStorage', e);
      }
    })();

    function loadData(){
      const raw = localStorage.getItem(STORAGE_KEY);
      try{
        return raw ? JSON.parse(raw) : [];
      }catch(e){
        console.error('Błąd parsowania localStorage, zapisuję domyślne', e);
        localStorage.setItem(STORAGE_KEY, JSON.stringify(initialAnnouncements));
        return [...initialAnnouncements];
      }
    }

    function saveData(arr){
      localStorage.setItem(STORAGE_KEY, JSON.stringify(arr));
    }

    function formatDateISO(iso){
      try{
        const d = new Date(iso + 'T00:00:00');
        const day = d.getDate();
        const monthNames = ['stycznia','lutego','marca','kwietnia','maja','czerwca','lipca','sierpnia','września','października','listopada','grudnia'];
        const month = monthNames[d.getMonth()];
        const year = d.getFullYear();
        return `${day} ${month} ${year}`;
      }catch(e){return iso}
    }

    function render(){
      const data = loadData();
      const newList = document.getElementById('list-new');
      const readList = document.getElementById('list-read');
      newList.innerHTML=''; readList.innerHTML='';

      // Tylko nowe w panelu 'Nowe', tylko odebrane w 'Odebrane'
      const newItems = data.filter(x=>!x.read).sort((a,b)=>a.date.localeCompare(b.date));
      const readItems = data.filter(x=>x.read).sort((a,b)=>a.date.localeCompare(b.date));

      document.getElementById('count-new').textContent = `(${newItems.length})`;
      document.getElementById('count-read').textContent = `(${readItems.length})`;

      if(newItems.length===0){
        newList.innerHTML = '<div class="empty">Brak nowych ogłoszeń.</div>';
      } else {
        newItems.forEach(makeItemNode(newList, false));
      }

      if(readItems.length===0){
        readList.innerHTML = '<div class="empty">Brak odebranych ogłoszeń.</div>';
      } else {
        readItems.forEach(makeItemNode(readList, true));
      }

      // Pokaż/ukryj panele na podstawie hash (dwie ODSEPAROWANE zakładki)
      updateViewByHash();
    }

    function makeItemNode(container, isRead){
      return function(item){
        const el = document.createElement('button');
        el.className = 'item ' + (isRead? 'bubble-read':'bubble-new');
        el.setAttribute('data-id', item.id);
        el.setAttribute('aria-label', `${item.title}, ${formatDateISO(item.date)}`);

        el.innerHTML = `
          <div class="meta"><div class="by">${escapeHtml(AUTHOR_NAME)}</div><div class="muted">${formatDateISO(item.date)}</div></div>
          <div class="title">${escapeHtml(item.title)}</div>
          <div class="body">${escapeHtml(item.content)}</div>
        `;

        el.addEventListener('click', ()=> openAnnouncement(item.id));
        container.appendChild(el);
      }
    }

    function escapeHtml(str){
      return String(str)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;')
        .replace(/'/g, '&#039;');
    }

    function openAnnouncement(id){
      const data = loadData();
      const item = data.find(x=>x.id===id);
      if(!item) return;

      const w = window.open('', '_blank');
      if(!w){
        alert('Przeglądarka zablokowała otwieranie nowej karty. Spróbuj zezwolić na wyskakujące okna.');
        return;
      }

      const html = `<!doctype html>
<html lang="pl">
<head>
<meta charset="utf-8"><meta name="viewport" content="width=device-width,initial-scale=1">
<title>${escapeHtml(item.title)}</title>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
<style>
  body{font-family:Roboto,Arial;margin:0;padding:22px;background:linear-gradient(180deg,#f0f8ff,#ffffff);color:#0b1220}
  .card{max-width:900px;margin:0 auto;background:#fff;padding:20px;border-radius:14px;box-shadow:0 12px 36px rgba(17,24,39,0.08)}
  h1{font-family:Pacifico,cursive;color:#1e3a8a;margin:0 0 6px 0}
  .meta{color:#6b7280;margin-bottom:12px}
  .body{line-height:1.6;white-space:pre-wrap}
  .actions{display:flex;gap:8px;margin-top:18px}
  .btn{background:linear-gradient(180deg,#3b5998,#5a8dee);color:#fff;border:none;padding:10px 12px;border-radius:10px;cursor:pointer}
</style>
</head>
<body>
  <div class="card">
    <h1>${escapeHtml(item.title)}</h1>
    <div class="meta">${formatDateISO(item.date)} — pochodzi z bloga <strong>${escapeHtml(item.source)}</strong></div>
    <div class="body">${escapeHtml(item.content)}</div>
    <div class="actions">
      <button class="btn" id="closeBtn">Zamknij i wróć</button>
    </div>
  </div>

  <script>
    const STORAGE_KEY = '${STORAGE_KEY}';
    document.getElementById('closeBtn').addEventListener('click', ()=>{
      try{
        const raw = localStorage.getItem(STORAGE_KEY);
        const arr = raw?JSON.parse(raw):[];
        const idx = arr.findIndex(x=>x.id==='${item.id}');
        if(idx!==-1){ arr[idx].read = true; arr[idx].readAt = new Date().toISOString(); localStorage.setItem(STORAGE_KEY, JSON.stringify(arr)); }
      }catch(e){console.error(e)}
      window.close();
    });
  <\/script>
</body>
</html>`;

      w.document.open();
      w.document.write(html);
      w.document.close();
    }

    function updateViewByHash(){
      const hash = (location.hash||'#nowe').replace('#','');
      const panelNew = document.getElementById('panel-new');
      const panelRead = document.getElementById('panel-read');
      const tabNew = document.getElementById('tab-new');
      const tabRead = document.getElementById('tab-read');

      if(hash==='odebrane'){
        panelNew.classList.add('hidden');
        panelRead.classList.remove('hidden');
        tabRead.classList.add('active');
        tabNew.classList.remove('active');
        document.title = 'Odebrane — Skrzynka Odbiorcza';
      } else {
        panelNew.classList.remove('hidden');
        panelRead.classList.add('hidden');
        tabNew.classList.add('active');
        tabRead.classList.remove('active');
        document.title = 'Nowe — Skrzynka Odbiorcza';
      }
    }

    window.addEventListener('hashchange', ()=>{ render(); });
    if(!location.hash) location.hash = '#nowe';

    document.getElementById('refreshBtn').addEventListener('click', ()=>{ render(); });

    // gdy localStorage zmieni się w innej karcie, odświeżamy widok
    window.addEventListener('storage', (e)=>{ if(e.key===STORAGE_KEY) render(); });
    window.addEventListener('focus', ()=> render());

    // Init
    render();
  </script>
</body>
</html>

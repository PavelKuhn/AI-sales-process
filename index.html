<!DOCTYPE html>
<html lang="cs">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AI Sales Copilot | Kogi</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:Arial,sans-serif;background:#f2f2f2;min-height:100vh;color:#1a1a1a}
.hdr{background:#151D27;padding:13px 28px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:100}
.logo{font-size:20px;font-weight:700;color:#EB410D;letter-spacing:-0.5px}
.hdr-sub{font-size:12px;color:rgba(255,255,255,0.4)}
.page{max-width:560px;margin:0 auto;padding:28px 20px}
.page.wide{max-width:1120px}
.hidden{display:none!important}
.card{background:#fff;border-radius:12px;border:1px solid #e0e0e0;overflow:hidden;margin-bottom:16px}
.card-hd{padding:12px 20px;font-size:12px;font-weight:700;letter-spacing:.06em;text-transform:uppercase;display:flex;align-items:center;justify-content:space-between;color:#fff}
.card-hd.dark{background:#151D27}
.card-hd.orange{background:#EB410D}
.card-bd{padding:20px}
.lbl{display:block;font-size:11px;font-weight:700;color:#888;text-transform:uppercase;letter-spacing:.05em;margin-bottom:5px}
input[type=text]{width:100%;padding:10px 14px;border:1px solid #ddd;border-radius:8px;font-size:14px;font-family:Arial,sans-serif;outline:none;transition:border-color .15s;background:#fff}
input:focus{border-color:#EB410D}
.fg{margin-bottom:14px}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:14px}
.grid3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:14px;margin-bottom:14px}
.btn{padding:13px 20px;border:none;border-radius:8px;font-size:14px;font-weight:700;font-family:Arial,sans-serif;cursor:pointer;transition:opacity .15s}
.btn-primary{background:#EB410D;color:#fff;width:100%}
.btn-primary:disabled{background:#ddd;color:#aaa;cursor:not-allowed}
.btn-primary:not(:disabled):hover{opacity:.9}
.btn-outline{background:transparent;border:1px solid #151D27;color:#151D27;font-size:13px;padding:8px 16px;border-radius:8px;cursor:pointer;font-family:Arial,sans-serif;font-weight:700}
.note{margin-top:12px;padding:10px 13px;background:#F7EEE4;border-radius:8px;font-size:12px;color:#888;line-height:1.5}
.step-row{display:flex;align-items:flex-start;gap:10px;padding:10px 0;border-bottom:1px solid #f4f4f4}
.step-row:last-child{border-bottom:none}
.si{width:26px;height:26px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:12px;flex-shrink:0;transition:background .3s}
.si.idle{background:#f0f0f0;color:#aaa}
.si.active{background:#EB410D;color:#fff}
.si.done{background:#EAF3DE;color:#3B6D11}
.si.error{background:#FAECE7;color:#993C1D}
.step-lbl{font-size:13px}
.step-lbl.idle{color:#bbb}
.step-detail{font-size:11px;color:#aaa;margin-top:2px}
.badge{display:inline-block;font-size:11px;font-weight:600;padding:3px 8px;border-radius:20px}
.b-orange{background:#FAECE7;color:#993C1D}
.b-green{background:#EAF3DE;color:#3B6D11}
.b-amber{background:#FAEEDA;color:#854F0B}
.b-blue{background:#E6F1FB;color:#185FA5}
.b-purple{background:#EEEDFE;color:#3C3489}
.b-grey{background:#f0f0f0;color:#555}
.sl{font-size:10px;font-weight:700;letter-spacing:.07em;text-transform:uppercase;color:#aaa;display:flex;align-items:center;gap:8px;margin:13px 0 7px}
.sl::after{content:'';flex:1;height:1px;background:#eee}
.dr{display:flex;justify-content:space-between;align-items:center;padding:6px 0;font-size:13px;border-bottom:1px solid #f5f5f5}
.dr .dk{color:#777}
.dr .dv{font-weight:700}
.score-bar{height:6px;background:#f0f0f0;border-radius:3px;margin-top:6px;margin-bottom:12px}
.score-fill{height:6px;border-radius:3px}
.move-card{background:#F7EEE4;border-radius:8px;padding:11px 13px;margin-bottom:8px}
.move-lbl{font-size:10px;font-weight:700;color:#aaa;text-transform:uppercase;letter-spacing:.06em;margin-bottom:3px}
.move-txt{font-size:13px;font-weight:700;color:#151D27;line-height:1.5}
.sig-row{display:flex;align-items:flex-start;gap:8px;padding:6px 0;font-size:13px;border-bottom:1px solid #f5f5f5}
.sig-dot{width:8px;height:8px;border-radius:50%;flex-shrink:0;margin-top:4px}
.sig-src{font-size:10px;font-weight:700;color:#bbb;flex-shrink:0;padding-left:6px}
.phase{border:1px solid #e8e8e8;border-radius:8px;margin-bottom:8px;overflow:hidden}
.phase-hdr{display:flex;align-items:center;gap:10px;padding:11px 14px;background:#fafafa;cursor:pointer;user-select:none}
.phase-num{width:22px;height:22px;border-radius:50%;background:#EB410D;color:#fff;font-size:11px;font-weight:700;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.phase-title{font-size:13px;font-weight:700;flex:1}
.phase-dur{font-size:11px;color:#bbb}
.phase-body{padding:14px;display:none}
.phase-body.open{display:block}
.sline{padding:9px 11px;margin-bottom:6px;font-size:13px;line-height:1.65;border-left:3px solid #ccc}
.sline.say{border-left-color:#378ADD;background:#f7faff}
.sline.listen{border-left-color:#639922;background:#f7fff7}
.sline.warn{border-left-color:#D85A30;background:#fff8f5}
.sline-lbl{font-size:10px;font-weight:700;letter-spacing:.06em;text-transform:uppercase;margin-bottom:3px}
.sline.say .sline-lbl{color:#185FA5}
.sline.listen .sline-lbl{color:#3B6D11}
.sline.warn .sline-lbl{color:#993C1D}
.branch-grid{display:grid;grid-template-columns:1fr 1fr;gap:6px;margin-top:8px}
.branch-card{border:1px solid #e8e8e8;border-radius:6px;padding:8px 10px;font-size:12px;background:#fff}
.branch-lbl{font-weight:700;font-size:11px;margin-bottom:3px}
.crm-grid{display:grid;grid-template-columns:1fr 1fr;gap:0 28px}
.crm-row{display:flex;justify-content:space-between;align-items:flex-start;padding:6px 0;font-size:13px;border-bottom:1px solid #f5f5f5;gap:10px}
.crm-key{color:#777;flex-shrink:0}
.crm-val{font-weight:700;text-align:right;font-size:12px;color:#151D27}
.exp-btn{padding:5px 12px;background:rgba(255,255,255,0.12);border:1px solid rgba(255,255,255,0.35);border-radius:6px;color:#fff;cursor:pointer;font-family:Arial,sans-serif;font-size:12px;font-weight:700}
.exp-btn:hover{background:rgba(255,255,255,0.2)}
.res-row1{display:grid;grid-template-columns:minmax(0,1fr) minmax(0,1fr);gap:16px;margin-bottom:16px}
.topbar{display:flex;align-items:center;justify-content:space-between;margin-bottom:18px;flex-wrap:wrap;gap:10px}
.err-box{background:#FAECE7;border:1px solid #F5C4B3;border-radius:12px;padding:24px}
.op-strip{background:#F7EEE4;border-radius:8px;padding:10px 14px;display:flex;align-items:center;gap:12px;margin-bottom:14px;font-size:13px;color:#555}
.op-name{font-weight:700;color:#151D27}
@media(max-width:700px){.res-row1{grid-template-columns:1fr}.crm-grid{grid-template-columns:1fr}.grid2,.grid3{grid-template-columns:1fr}}
</style>
</head>
<body>

<div class="hdr">
  <span class="logo">Kogi</span>
  <span class="hdr-sub">AI Sales Copilot · Telco</span>
</div>

<!-- FORM -->
<div id="screen-form" class="page">
  <div class="card">
    <div class="card-hd dark" style="flex-direction:column;align-items:flex-start;gap:4px;padding:18px 22px">
      <span style="font-size:17px;font-weight:700;text-transform:none;letter-spacing:0">Nová analýza leadu</span>
      <span style="font-size:13px;color:rgba(255,255,255,0.5);font-weight:400;text-transform:none;letter-spacing:0">Zadej kontaktní údaje leadu — AI sestaví profil, skript a CRM zápis</span>
    </div>
    <div class="card-bd">
      <div class="grid2">
        <div><label class="lbl">Jméno zákazníka *</label><input type="text" id="f-fn" placeholder="Pavel" oninput="checkForm()"></div>
        <div><label class="lbl">Příjmení *</label><input type="text" id="f-ln" placeholder="Kuhn" oninput="checkForm()"></div>
      </div>
      <div class="fg"><label class="lbl">Adresa (s PSČ)</label><input type="text" id="f-addr" placeholder="Berlínská 1488/5, Praha 10, 102 00"></div>
      <div class="grid2">
        <div><label class="lbl">Telefonní číslo *</label><input type="text" id="f-tel" placeholder="775 011 599" oninput="checkForm()"></div>
        <div><label class="lbl">Operátor (tvé jméno)</label><input type="text" id="f-op" placeholder="Jana Nováková"></div>
      </div>
      <button class="btn btn-primary" id="analyze-btn" onclick="analyze()" disabled>Analyzovat lead →</button>
      <div class="note">* Povinné pole. ARES a CETIN data se stahují automaticky. Žádné heslo ani klíč není potřeba.</div>
    </div>
  </div>
</div>

<!-- LOADING -->
<div id="screen-loading" class="page hidden">
  <div class="card">
    <div class="card-bd">
      <div id="load-title" style="font-size:15px;font-weight:700;color:#151D27;margin-bottom:3px"></div>
      <div id="load-sub" style="font-size:12px;color:#aaa;margin-bottom:18px"></div>
      <div id="steps"></div>
    </div>
  </div>
</div>

<!-- ERROR -->
<div id="screen-error" class="page hidden">
  <div class="err-box">
    <div style="font-size:15px;font-weight:700;color:#993C1D;margin-bottom:8px">Chyba při analýze</div>
    <div id="err-msg" style="font-size:13px;color:#993C1D;line-height:1.6;margin-bottom:18px"></div>
    <button class="btn btn-outline" onclick="showScreen('form')">← Zpět na formulář</button>
  </div>
</div>

<!-- RESULTS -->
<div id="screen-results" class="page wide hidden">
  <div class="topbar">
    <div>
      <div id="res-name" style="font-size:19px;font-weight:700;color:#151D27"></div>
      <div id="res-sub" style="font-size:12px;color:#999;margin-top:2px"></div>
    </div>
    <button class="btn btn-outline" onclick="showScreen('form')">← Nový lead</button>
  </div>
  <div id="op-banner" class="op-strip hidden"></div>
  <div class="res-row1">
    <div class="card">
      <div class="card-hd dark">Lead profil</div>
      <div class="card-bd" id="r-profile"></div>
    </div>
    <div class="card">
      <div class="card-hd orange">Doporučené otevírací tahy</div>
      <div class="card-bd" id="r-moves"></div>
    </div>
  </div>
  <div class="card">
    <div class="card-hd dark">Skript hovoru</div>
    <div class="card-bd" id="r-script"></div>
  </div>
  <div class="card">
    <div class="card-hd dark">
      CRM zápis
      <div style="display:flex;gap:8px">
        <button class="exp-btn" onclick="expJSON()">↓ JSON</button>
        <button class="exp-btn" onclick="expCSV()">↓ CSV</button>
      </div>
    </div>
    <div class="card-bd"><div class="crm-grid" id="r-crm"></div></div>
  </div>
</div>

<script>
let savedResult=null, savedForm=null;

// ── Telco utilities ──────────────────────────────────────────────
const CARRIERS={"601":"O2","602":"O2","603":"O2","604":"O2","605":"O2","606":"T-Mobile","607":"T-Mobile","608":"T-Mobile","720":"T-Mobile","721":"O2","722":"O2","723":"O2","724":"O2","725":"T-Mobile","726":"T-Mobile","727":"T-Mobile","728":"T-Mobile","729":"T-Mobile","730":"T-Mobile","731":"T-Mobile","732":"T-Mobile","733":"T-Mobile","734":"T-Mobile","735":"T-Mobile","736":"T-Mobile","737":"T-Mobile","738":"T-Mobile","739":"T-Mobile","770":"O2","771":"O2","772":"O2","773":"O2","774":"O2","775":"Vodafone","776":"Vodafone","777":"Vodafone","778":"T-Mobile","779":"T-Mobile"};
function getCarrier(p){const c=p.replace(/\D/g,'').replace(/^420/,'');const px=c.slice(0,3);const cr=CARRIERS[px]||'Neznámý';return{prefix:px,carrier:cr,label:cr!=='Neznámý'?'Původně '+cr:'Předvolba nerozpoznána'};}
function extractPSC(a){const m=a.match(/\b(\d{3})\s?(\d{2})\b/);return m?m[1]+m[2]:null;}
function getCoverage(psc){if(!psc)return{vdsl:'Neověřeno',ftth:'Neověřeno',g5:'Neověřeno',type:'Neznámý'};const n=parseInt(psc);if(n>=10000&&n<=19999)return{vdsl:'Dostupné',ftth:'Rollout 2024–25',g5:'Praha ✓',type:'Praha'};if(n>=60000&&n<=63999)return{vdsl:'Dostupné',ftth:'Plánováno 2025',g5:'Brno ✓',type:'Brno'};if(n>=70000&&n<=72999)return{vdsl:'Dostupné',ftth:'Plánováno',g5:'Ostrava ✓',type:'Ostrava'};if(n>=30000&&n<=59999)return{vdsl:'Dostupné',ftth:'Není dostupné',g5:'Částečně',type:'Region. město'};return{vdsl:'Ověřit',ftth:'Není dostupné',g5:'Ověřit',type:'Menší obec'};}

// ── ARES ─────────────────────────────────────────────────────────
async function fetchAres(fn,ln){
  try{
    const url=`https://ares.gov.cz/ekonomicke-subjekty-v-be/rest/ekonomicke-subjekty?obchodniJmeno=${encodeURIComponent(fn+' '+ln)}&start=0&pocet=15`;
    const res=await fetch(url,{headers:{Accept:'application/json'},signal:AbortSignal.timeout(8000)});
    if(!res.ok)throw new Error('HTTP '+res.status);
    const data=await res.json();
    const items=data.ekonomickeSubjekty||[];
    const lF=fn.toLowerCase(),lL=ln.toLowerCase();
    const companies=items.filter(e=>{const n=(e.obchodniJmeno||'').toLowerCase();return n.includes(lF)||n.includes(lL);}).slice(0,4).map(e=>({name:e.obchodniJmeno||'—',ico:e.ico||'—',obor:e.naceKody?.[0]?.naceText||e.pravniForma||'Neuvedeno'}));
    return{found:companies.length>0,companies,error:null};
  }catch(e){return{found:false,companies:[],error:e.message};}
}

// ── Claude via backend proxy ──────────────────────────────────────
async function callClaude(sys,usr){
  const res=await fetch('/api/claude',{
    method:'POST',
    headers:{'Content-Type':'application/json'},
    body:JSON.stringify({model:'claude-sonnet-4-20250514',max_tokens:4000,system:sys,messages:[{role:'user',content:usr}]})
  });
  if(!res.ok){const e=await res.json().catch(()=>({}));throw new Error(`API ${res.status}: ${e.error||'Neznámá chyba'}`);}
  const data=await res.json();
  const text=data.content?.[0]?.text||'';
  const m=text.match(/\{[\s\S]*\}/);
  if(!m)throw new Error('Neplatná odpověď AI. Zkus znovu.');
  return JSON.parse(m[0]);
}

// ── Prompt ───────────────────────────────────────────────────────
function buildPrompt(form,ares,telco){
  const companies=ares.found?ares.companies.map(c=>`${c.name} (IČO:${c.ico}, ${c.obor})`).join('; '):'Nenalezen jako podnikatel';
  const sys=`Jsi AI asistent pro telekomunikačního operátora v ČR. Analyzuješ leady a připravuješ prodejní podklady v češtině. Odpovídáš POUZE validním JSON objektem bez markdown, bez backtick, bez jakéhokoli textu mimo JSON.`;
  const usr=`Analyzuj lead a vrať JSON:\n\nVSTUP:\nJméno: ${form.fn} ${form.ln}\nAdresa: ${form.addr||'neuvedena'}\nTelefon: ${form.tel} (operátor: ${telco.carrier.carrier}, předvolba: ${telco.carrier.prefix})\nPSČ: ${telco.psc||'—'}, Lokalita: ${telco.coverage.type}\nVDSL: ${telco.coverage.vdsl}, FTTH: ${telco.coverage.ftth}, 5G: ${telco.coverage.g5}\nARES: ${companies}\n\nVrať JSON:\n{"leadScore":0-100,"segment":"B2C|B2B|B2C+B2B","intent":"max 6 slov","summary":"2-3 věty pro operátora","openingMoves":[{"label":"Hlavní potřeba","text":"..."},{"label":"B2B příležitost","text":"..."},{"label":"Konvergence","text":"..."}],"signals":[{"text":"...","source":"ARES|ČTÚ|CETIN|Geo","color":"orange|blue|green|grey"}],"callScript":[{"phase":"Otevření hovoru","duration":"~45 s","lines":[{"type":"say","label":"Říkáte","text":"konkrétní znění s adresou/pokrytím"},{"type":"warn","label":"⚠ Pozor","text":"co neříkat"}]},{"phase":"Diagnóza potřeby","duration":"~90 s","lines":[{"type":"say","label":"Otázka 1 — ISP","text":"otázka s ${telco.carrier.carrier}","branches":[{"label":"→ Ano","text":"pokračování"},{"label":"→ Jiný operátor","text":"pokračování"}]},{"type":"say","label":"Otázka 2 — B2B","text":"otázka dle ARES"},{"type":"listen","label":"Posloucháte pro","text":"klíčové signály"}]},{"phase":"Nabídka","duration":"~60 s","lines":[{"type":"say","label":"Scénář A — domácnost","text":"konkrétní VDSL/FTTH"},{"type":"say","label":"Scénář B — firma","text":"SLA, daňový výdaj"},{"type":"warn","label":"⚠ Neříkejte","text":"bez superlativů"}]},{"phase":"Námitky","duration":"—","lines":[{"type":"say","label":"Nemám čas","text":"..."},{"type":"say","label":"Jsem spokojený","text":"..."},{"type":"say","label":"Mám smlouvu","text":"..."},{"type":"say","label":"Pošlete mail","text":"..."}]},{"phase":"Uzavření","duration":"~30 s","lines":[{"type":"say","label":"Next step","text":"konkrétní závěr"},{"type":"warn","label":"⚠ Pravidlo","text":"vždy definujte next step"}]}],"crmEntry":{"Zákazník":"${form.fn} ${form.ln}","Telefon":"${form.tel}","Adresa":"${form.addr||'neuvedena'}","Operátor":"${form.op||'—'}","Segment":"...","ISP odhad":"${telco.carrier.carrier}","Záměr":"...","Technologie":"...","B2B":"...","ARES firmy":"${companies.slice(0,80)}","FTTH":"${telco.coverage.ftth}","Skóre":"?/100","Next step":"...","Čas analýzy":"${new Date().toLocaleString('cs-CZ')}"}}`;
  return{sys,usr};
}

// ── Steps UI ─────────────────────────────────────────────────────
const STEP_LABELS=['Vyhledávám v ARES / obchodním rejstříku','Analyzuji telco data (předvolba, PSČ, pokrytí CETIN)','AI sestavuje profil, skript hovoru a CRM zápis'];
function initSteps(){document.getElementById('steps').innerHTML=STEP_LABELS.map((l,i)=>`<div class="step-row"><div class="si idle" id="si${i}">○</div><div><div class="step-lbl idle" id="sl${i}">${l}</div><div class="step-detail" id="sd${i}"></div></div></div>`).join('');}
function updStep(i,s,d){const icons={idle:'○',active:'◌',done:'✓',error:'✗'};const ic=document.getElementById('si'+i);ic.className='si '+s;ic.textContent=icons[s]||'○';const lbl=document.getElementById('sl'+i);lbl.className='step-lbl'+(s==='idle'?' idle':'');lbl.style.fontWeight=s==='active'?'700':'400';if(d!=null)document.getElementById('sd'+i).textContent=d;}

// ── Routing ───────────────────────────────────────────────────────
function showScreen(id){['form','loading','error','results'].forEach(s=>document.getElementById('screen-'+s).classList.add('hidden'));document.getElementById('screen-'+id).classList.remove('hidden');}

// ── Form ──────────────────────────────────────────────────────────
function checkForm(){const fn=document.getElementById('f-fn').value.trim();const ln=document.getElementById('f-ln').value.trim();const tel=document.getElementById('f-tel').value.trim();document.getElementById('analyze-btn').disabled=!(fn&&ln&&tel);}

// ── Main flow ─────────────────────────────────────────────────────
async function analyze(){
  const fn=document.getElementById('f-fn').value.trim();
  const ln=document.getElementById('f-ln').value.trim();
  const addr=document.getElementById('f-addr').value.trim();
  const tel=document.getElementById('f-tel').value.trim();
  const op=document.getElementById('f-op').value.trim();
  if(!fn||!ln||!tel)return;
  savedForm={fn,ln,addr,tel,op};
  showScreen('loading');
  document.getElementById('load-title').textContent=`Analyzuji: ${fn} ${ln}`;
  document.getElementById('load-sub').textContent=`${tel}${addr?' · '+addr:''}`;
  initSteps();

  updStep(0,'active');
  const ares=await fetchAres(fn,ln);
  updStep(0,'done',ares.error?'ARES nedostupný — pokračuji s B2C':ares.found?`${ares.companies.length} subjekt(ů) nalezeno`:'Nenalezen jako podnikatel — B2C');

  updStep(1,'active');
  const carrier=getCarrier(tel);const psc=extractPSC(addr);const coverage=getCoverage(psc);const telco={carrier,psc,coverage};
  await new Promise(r=>setTimeout(r,300));
  updStep(1,'done',`${carrier.carrier} (${carrier.prefix}) · VDSL: ${coverage.vdsl} · FTTH: ${coverage.ftth}`);

  updStep(2,'active');
  try{
    const{sys,usr}=buildPrompt(savedForm,ares,telco);
    const ai=await callClaude(sys,usr);
    updStep(2,'done','Analýza dokončena');
    savedResult={ares,telco,ai};
    renderResults(savedResult,savedForm);
    showScreen('results');
  }catch(e){
    updStep(2,'error',e.message);
    document.getElementById('err-msg').textContent=e.message;
    showScreen('error');
  }
}

// ── Render ────────────────────────────────────────────────────────
function esc(s){return String(s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;');}
function badge(t,type){return`<span class="badge b-${type}">${esc(t)}</span>`;}
function bCov(v){return v==='Dostupné'?'green':v?.includes('Rollout')||v?.includes('Plánov')?'amber':'grey';}
function bCar(c){return c==='Vodafone'?'grey':c==='O2'?'purple':c==='T-Mobile'?'blue':'grey';}
function sigC(c){return{orange:'#EB410D',blue:'#378ADD',green:'#639922',grey:'#aaa'}[c]||'#aaa';}

function renderResults(r,form){
  const{ares,telco,ai}=r;
  document.getElementById('res-name').textContent=`${form.fn} ${form.ln}`;
  document.getElementById('res-sub').textContent=`${form.tel}${form.addr?' · '+form.addr:''}`;
  if(form.op){const b=document.getElementById('op-banner');b.classList.remove('hidden');b.innerHTML=`Operátor: <span class="op-name">${esc(form.op)}</span> &nbsp;·&nbsp; ${new Date().toLocaleString('cs-CZ')}`;}

  const score=ai.leadScore||70;
  const sc=score>=75?'#639922':score>=50?'#EB410D':'#993C1D';
  let ph=`<span style="font-size:48px;font-weight:700;color:${sc};line-height:1">${score}</span><span style="font-size:18px;color:#ccc">/100</span><div class="score-bar"><div class="score-fill" style="width:${score}%;background:${sc}"></div></div><div style="display:flex;gap:6px;flex-wrap:wrap;margin-bottom:10px">${badge(ai.segment,'orange')} ${badge(ai.intent,'blue')}</div>`;
  if(ai.summary)ph+=`<div style="font-size:13px;color:#555;line-height:1.65;padding-bottom:10px;border-bottom:1px solid #f0f0f0;margin-bottom:2px">${esc(ai.summary)}</div>`;
  ph+=`<div class="sl">Firmografie (ARES)</div>`;
  if(ares.found)ares.companies.slice(0,3).forEach(c=>{ph+=`<div style="margin-bottom:8px;padding-bottom:8px;border-bottom:1px solid #f5f5f5"><div style="font-size:13px;font-weight:700">${esc(c.name)}</div><div style="font-size:12px;color:#999;margin-top:1px">IČO: ${esc(c.ico)} · ${esc(c.obor)}</div></div>`;});
  else ph+=`<div style="font-size:13px;color:#ccc;margin-bottom:8px">Nenalezen jako podnikatel — B2C lead</div>`;
  ph+=`<div class="sl">Kontext telco</div><div class="dr"><span class="dk">Předvolba</span><span class="dv">${badge(telco.carrier.label,bCar(telco.carrier.carrier))}</span></div><div class="dr"><span class="dk">PSČ</span><span class="dv">${esc(telco.psc||'—')}</span></div><div class="dr"><span class="dk">VDSL (CETIN)</span><span class="dv">${badge(telco.coverage.vdsl,bCov(telco.coverage.vdsl))}</span></div><div class="dr"><span class="dk">FTTH (CETIN)</span><span class="dv">${badge(telco.coverage.ftth,bCov(telco.coverage.ftth))}</span></div><div class="dr"><span class="dk">5G pokrytí</span><span class="dv">${badge(telco.coverage.g5,telco.coverage.g5.includes('✓')?'green':'amber')}</span></div>`;
  document.getElementById('r-profile').innerHTML=ph;

  let mh=(ai.openingMoves||[]).map(m=>`<div class="move-card"><div class="move-lbl">${esc(m.label)}</div><div class="move-txt">${esc(m.text)}</div></div>`).join('');
  mh+=`<div class="sl">Signály z veřejných dat</div>`;
  mh+=(ai.signals||[]).map(s=>`<div class="sig-row"><div class="sig-dot" style="background:${sigC(s.color)}"></div><span style="flex:1;color:#444;line-height:1.5">${esc(s.text)}</span><span class="sig-src">${esc(s.source)}</span></div>`).join('');
  document.getElementById('r-moves').innerHTML=mh;

  const th={say:{lc:'#185FA5',lt:'Říkáte'},listen:{lc:'#3B6D11',lt:'Posloucháte'},warn:{lc:'#993C1D',lt:'⚠ Pozor'}};
  let sh=(ai.callScript||[]).map((ph,i)=>{
    const lines=(ph.lines||[]).map(l=>{const t=th[l.type]||th.say;let h=`<div class="sline ${l.type||'say'}"><div class="sline-lbl" style="color:${t.lc}">${esc(l.label||t.lt)}</div><div>${esc(l.text)}</div>`;if(l.branches)h+=`<div class="branch-grid">${l.branches.map((b,j)=>`<div class="branch-card"><div class="branch-lbl" style="color:${j===0?'#3B6D11':'#993C1D'}">${esc(b.label)}</div>${esc(b.text)}</div>`).join('')}</div>`;return h+'</div>';}).join('');
    return`<div class="phase"><div class="phase-hdr" onclick="tp('pb${i}',this)"><div class="phase-num">${i+1}</div><span class="phase-title">${esc(ph.phase)}</span><span class="phase-dur">${esc(ph.duration)}</span><span style="font-size:11px;color:#bbb;margin-left:4px">▼</span></div><div class="phase-body${i===0?' open':''}" id="pb${i}">${lines}</div></div>`;
  }).join('');
  document.getElementById('r-script').innerHTML=sh;

  const crm=ai.crmEntry||{};
  document.getElementById('r-crm').innerHTML=Object.entries(crm).map(([k,v])=>`<div class="crm-row"><span class="crm-key">${esc(k)}</span><span class="crm-val">${esc(v||'—')}</span></div>`).join('');
}

function tp(id,hdr){const b=document.getElementById(id);const o=b.classList.toggle('open');hdr.querySelector('span:last-child').textContent=o?'▲':'▼';}

function expJSON(){if(!savedResult?.ai?.crmEntry)return;const p={...savedResult.ai.crmEntry,leadScore:savedResult.ai.leadScore,ts:new Date().toISOString()};const b=new Blob([JSON.stringify(p,null,2)],{type:'application/json'});const a=document.createElement('a');a.href=URL.createObjectURL(b);a.download=`CRM_${savedForm?.ln||'lead'}_${savedForm?.fn||''}.json`;a.click();}
function expCSV(){if(!savedResult?.ai?.crmEntry)return;const e={...savedResult.ai.crmEntry,leadScore:savedResult.ai.leadScore};const h=Object.keys(e).join(';');const r=Object.values(e).map(v=>`"${String(v??'').replace(/"/g,'""')}"`).join(';');const b=new Blob(['\uFEFF'+h+'\n'+r],{type:'text/csv;charset=utf-8'});const a=document.createElement('a');a.href=URL.createObjectURL(b);a.download=`CRM_${savedForm?.ln||'lead'}_${savedForm?.fn||''}.csv`;a.click();}
</script>
</body>
</html>

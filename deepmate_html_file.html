<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DeepMate — Project Tracker</title>
<link href="https://fonts.googleapis.com/css2?family=Prompt:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#08080f;--bg2:#0f0f1a;--bg3:#14141f;
  --t1:#fff;--t2:rgba(255,255,255,.65);--t3:rgba(255,255,255,.35);
  --teal:#5DCAA5;--border:rgba(255,255,255,.08);
}
html,body{min-height:100%;background:var(--bg);color:var(--t1);font-family:'Prompt',system-ui,sans-serif}
.wrap{max-width:1440px;margin:0 auto;padding:24px 32px 48px}
/* Header */
.hdr{display:flex;align-items:flex-start;justify-content:space-between;margin-bottom:20px;flex-wrap:wrap;gap:12px}
.hdr-title{font-size:22px;font-weight:500;display:flex;align-items:center;gap:8px}
.hdr-sub{font-size:12px;color:var(--t3);margin-top:3px}
.hdr-actions{display:flex;gap:8px;align-items:center;flex-wrap:wrap}
/* Buttons */
.btn{border:0.5px solid var(--border);border-radius:8px;padding:7px 16px;font-size:12px;font-family:inherit;cursor:pointer;transition:all .15s;color:var(--t2);background:transparent}
.btn:hover{background:rgba(255,255,255,.06)}
.btn-primary{background:var(--teal)!important;color:#04342C!important;border-color:var(--teal)!important;font-weight:600}
.btn-active{background:var(--t1)!important;color:var(--bg)!important;border-color:var(--t1)!important;font-weight:500}
/* Save indicator */
.save-pill{display:flex;align-items:center;gap:6px;font-size:11px;color:var(--t3);padding:5px 10px;border:0.5px solid var(--border);border-radius:20px}
.save-dot{width:7px;height:7px;border-radius:50%;background:var(--teal);flex-shrink:0;transition:background .3s}
.save-dot.saving{background:#EF9F27}
/* Stats */
.stats{display:grid;grid-template-columns:repeat(5,1fr);gap:10px;margin-bottom:12px}
.stat{background:var(--bg3);border:0.5px solid var(--border);border-radius:10px;padding:12px;text-align:center}
.stat-n{font-size:26px;font-weight:400;margin-bottom:3px}
.stat-l{font-size:11px;color:var(--t3)}
/* Progress bar */
.pbar-wrap{background:rgba(255,255,255,.07);border-radius:3px;height:4px;margin-bottom:14px;overflow:hidden}
.pbar-fill{height:100%;background:var(--teal);border-radius:3px;transition:width .4s}
/* Controls */
.ctrls{display:flex;gap:8px;margin-bottom:14px;flex-wrap:wrap;align-items:center}
.view-btns{display:flex;gap:3px}
select{background:var(--bg3);border:0.5px solid var(--border);border-radius:7px;padding:6px 12px;color:var(--t1);font-family:inherit;font-size:12px;cursor:pointer;outline:none}
/* Gantt */
.gantt-scroll{overflow-x:auto;border:0.5px solid var(--border);border-radius:12px;background:var(--bg2)}
.g-head{display:flex;border-bottom:0.5px solid var(--border);background:var(--bg3);border-radius:12px 12px 0 0;padding:8px 0}
.g-col-name{width:290px;flex-shrink:0;padding-left:16px;font-size:9px;color:var(--t3);text-transform:uppercase;letter-spacing:.1em}
.g-col-own{width:76px;flex-shrink:0;font-size:9px;color:var(--t3);text-transform:uppercase;letter-spacing:.1em}
.g-col-days{flex:1;display:flex}
.g-day-h{flex:1;text-align:center;font-size:8px;color:var(--t3)}
.g-phase-hdr{padding:5px 16px;font-size:11px;font-weight:600;background:var(--bg3);border-bottom:0.5px solid var(--border);border-top:0.5px solid var(--border)}
.g-row{display:flex;align-items:center;height:26px;border-bottom:0.5px solid rgba(255,255,255,.03)}
.g-row:hover{background:rgba(255,255,255,.02)}
.g-name{width:290px;flex-shrink:0;font-size:11px;color:var(--t2);padding:0 8px 0 16px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.g-own{width:76px;flex-shrink:0;font-size:10px;font-weight:500;overflow:hidden;white-space:nowrap}
.g-bars{flex:1;position:relative;height:100%;display:flex;align-items:center}
.g-bar{position:absolute;height:13px;border-radius:3px;display:flex;align-items:center;justify-content:center;font-size:8px;color:#fff;font-weight:600;overflow:hidden}
/* List */
.l-section{margin-bottom:14px}
.l-phase-tag{display:inline-block;font-size:11px;font-weight:600;padding:3px 10px;border-radius:5px;margin-bottom:7px}
.l-row{display:flex;align-items:center;gap:8px;padding:8px 13px;background:var(--bg3);border-radius:9px;margin-bottom:3px;border:0.5px solid var(--border);transition:border-color .15s}
.l-row:hover{border-color:rgba(255,255,255,.14)}
.l-id{width:34px;font-size:9px;color:var(--t3);flex-shrink:0}
.l-mod{width:28px;height:17px;border-radius:8px;display:flex;align-items:center;justify-content:center;font-size:9px;color:#fff;font-weight:600;flex-shrink:0}
.l-task{flex:1;font-size:12px}
.l-own{width:70px;font-size:10px;font-weight:500;flex-shrink:0;overflow:hidden;white-space:nowrap}
.l-dates{width:84px;font-size:9px;color:var(--t3);flex-shrink:0;text-align:center}
.l-sel{padding:4px 7px;border-radius:6px;border:0.5px solid rgba(255,255,255,.12);font-size:11px;font-family:inherit;cursor:pointer;width:100px;flex-shrink:0;outline:none}
/* Legend */
.legend{display:flex;gap:12px;flex-wrap:wrap;align-items:center;padding:12px 0;border-top:0.5px solid var(--border);margin-top:10px;font-size:11px;color:var(--t3)}
.leg-dot{width:10px;height:10px;border-radius:2px;flex-shrink:0}
/* Deploy note */
.deploy-note{background:rgba(55,138,221,.08);border:0.5px solid rgba(55,138,221,.25);border-radius:10px;padding:12px 16px;margin-bottom:18px;font-size:12px;color:rgba(55,138,221,.9);line-height:1.6}
</style>
</head>
<body>
<div class="wrap">

  <!-- Deploy note (auto-hides after save) -->
  <div class="deploy-note" id="deploy-note">
    <strong>🚀 GitHub Pages:</strong> อัปโหลดไฟล์นี้ไปที่ repo → Settings → Pages → เลือก branch · 
    ความคืบหน้าจะ Save อัตโนมัติใน browser ของแต่ละเครื่อง (localStorage) ·
    <a href="#" onclick="document.getElementById('deploy-note').style.display='none';return false" style="color:rgba(55,138,221,.9);margin-left:8px">ปิด ✕</a>
  </div>

  <!-- Header -->
  <div class="hdr">
    <div>
      <div class="hdr-title">
        <span style="width:10px;height:10px;border-radius:50%;background:var(--teal);display:inline-block"></span>
        DeepMate — Project Tracker
      </div>
      <div class="hdr-sub">16 เม.ย. → 19 พ.ค. 2569 · 22 วันทำงาน · 41 Tasks</div>
    </div>
    <div class="hdr-actions">
      <div class="save-pill">
        <span class="save-dot" id="save-dot"></span>
        <span id="save-txt">Auto-save</span>
      </div>
      <button class="btn" onclick="exportCSV()">⬇ Export CSV</button>
      <button class="btn btn-primary" onclick="resetProgress()">↺ Reset</button>
    </div>
  </div>

  <!-- Stats -->
  <div class="stats" id="stats"></div>
  <div class="pbar-wrap"><div class="pbar-fill" id="pbar"></div></div>

  <!-- Controls -->
  <div class="ctrls">
    <div class="view-btns">
      <button class="btn btn-active" id="btn-gantt" onclick="setView('gantt')">Gantt</button>
      <button class="btn" id="btn-list" onclick="setView('list')">List</button>
    </div>
    <select id="f-owner" onchange="render()">
      <option value="all">ทั้งทีม</option>
      <option>กิต+นัท</option><option>วิว</option><option>น้ำ</option><option>เพิร์ล</option><option>ทั้งทีม</option>
    </select>
    <select id="f-phase" onchange="render()">
      <option value="all">ทุก Phase</option>
      <option>Sprint 0</option><option>Sprint 1</option><option>Sprint 2</option><option>Final</option>
    </select>
    <span style="margin-left:auto;font-size:11px;color:var(--t3)" id="task-count"></span>
  </div>

  <!-- View -->
  <div id="view"></div>
  <div class="legend" id="legend"></div>
</div>

<script>
// ─── Colors ──────────────────────────────────────────────────────────────────
var T='#5DCAA5',P='#7F77DD',R='#E24B4A',A='#EF9F27',B='#378ADD';
var PHASE_C={'Sprint 0':T,'Sprint 1':B,'Sprint 2':P,'Final':A};
var MOD_C={M1:T,M2:P,M3:A,M4:B,ALL:'#888780'};
var OWN_C={'กิต+นัท':T,'วิว':P,'น้ำ':A,'เพิร์ล':B,'ทั้งทีม':'#888780'};
var ST={
  todo:     {bg:'#12121e',tc:'rgba(255,255,255,.4)', lbl:'To Do'},
  'in-progress':{bg:'#0B2E52',tc:'#85B7EB',         lbl:'In Progress'},
  done:     {bg:'#0A2E1E',tc:'#5DCAA5',              lbl:'Done'},
  blocked:  {bg:'#2E0A0A',tc:'#F09595',              lbl:'Blocked'}
};

// ─── Working Days ─────────────────────────────────────────────────────────────
var HOLIDAYS=['2026-05-01','2026-05-04'];
var WD=(function(){
  var days=[],d=new Date('2026-04-16'),e=new Date('2026-05-19');
  while(d<=e){
    var iso=d.toISOString().slice(0,10),dw=d.getDay();
    if(dw!==0&&dw!==6&&HOLIDAYS.indexOf(iso)<0) days.push({iso:iso,lbl:iso.slice(5)});
    d.setDate(d.getDate()+1);
  }
  return days;
})();

// ─── Task Data [id, phase, track, module, owner, task, wdFrom, wdTo] ─────────
var RAW=[
  ['S0-1','Sprint 0','A','M1','กิต+นัท','ตั้ง Workspace Bubble.io + Design System',1,1],
  ['S0-2','Sprint 0','A','M1','กิต+นัท','เชื่อม API Keys (AssemblyAI + Anthropic)',1,1],
  ['S0-3','Sprint 0','A','M1','กิต+นัท','ทดสอบ API Call เบื้องต้น',1,2],
  ['S0-4','Sprint 0','A','M1','ทั้งทีม','ตกลง Database Schema',1,2],
  ['S0-5','Sprint 0','A','M1','ทั้งทีม','ตั้ง Project Board + แบ่ง Task',2,2],
  ['S1-1','Sprint 1','A','M1','กิต+นัท','Upload Page — Drag & Drop + Progress Bar',3,4],
  ['S1-2','Sprint 1','A','M1','กิต+นัท','Criteria Selector UI (Audio + Visual)',3,5],
  ['S1-3','Sprint 1','A','M1','กิต+นัท','STT Pipeline — AssemblyAI → Transcript → DB',4,6],
  ['S1-4','Sprint 1','A','M1','กิต+นัท','Transcript Review Screen (Timestamped)',6,7],
  ['S1-5','Sprint 1','A','M1','กิต+นัท','Frame Extraction (FFmpeg/Plugin)',8,9],
  ['S1-6','Sprint 1','A','M1','กิต+นัท','Claude Vision — Batch Frame Analysis',9,11],
  ['S1-7','Sprint 1','A','M1','กิต+นัท','Script Compare — Claude เปรียบเทียบ Transcript',10,12],
  ['S1-8','Sprint 1','A','M1','กิต+นัท','Dead Air Detection',11,12],
  ['S1-9','Sprint 1','A','M1','กิต+นัท','QA Score Engine (0–100)',12,13],
  ['B2-1','Sprint 1','B','M2','วิว','รวบรวมข้อสอบจริง 50+ ชุด',3,7],
  ['B2-2','Sprint 1','B','M2','วิว',"กำหนดโครงสร้างข้อสอบมาตรฐาน (Bloom's)",5,9],
  ['B2-3','Sprint 1','B','M2','วิว','ทดสอบ Claude Prompt วิเคราะห์+Suggest',9,13],
  ['B3-1','Sprint 1','B','M3','น้ำ','รวบรวม Script สนทนา 20+ เคส',3,7],
  ['B3-2','Sprint 1','B','M3','น้ำ','กำหนด Criteria สิ่งที่ผิดในการให้คำปรึกษา',5,9],
  ['B3-3','Sprint 1','B','M3','น้ำ','ทดสอบ Claude Prompt วิเคราะห์ Script',9,13],
  ['B4-1','Sprint 1','B','M4','เพิร์ล','Export/สร้าง Sample Ticket 200-500 รายการ',3,7],
  ['B4-2','Sprint 1','B','M4','เพิร์ล','ออกแบบ FAQ Database Structure',5,9],
  ['B4-3','Sprint 1','B','M4','เพิร์ล','ทดสอบ Claude Prompt Match+Gap',9,13],
  ['S2-1','Sprint 2','A','M1','กิต+นัท','QA Report Page — ปัญหา+Timestamp+คำแนะนำ',14,15],
  ['S2-2','Sprint 2','A','M1','กิต+นัท','Timeline View — แถบแสดงตำแหน่งปัญหา',15,16],
  ['S2-3','Sprint 2','A','M1','กิต+นัท','.srt Generator + Download Button',16,17],
  ['S2-4','Sprint 2','A','M1','กิต+นัท','PDF Report Export (Thai Font)',16,18],
  ['S2-5','Sprint 2','A','M1','กิต+นัท','Dashboard — Job List + สถิติ + ประวัติ',17,19],
  ['S2-6','Sprint 2','A','M1','กิต+นัท','End-to-End Test ด้วย Video จริง 5 ไฟล์',19,21],
  ['S2-7','Sprint 2','A','M1','กิต+นัท','Bug Fix + UX Polish',20,22],
  ['B2-4','Sprint 2','B','M2','วิว','สร้าง Criteria Database',14,18],
  ['B2-5','Sprint 2','B','M2','วิว','Mockup UI + Walkthrough Script M2',18,22],
  ['B3-4','Sprint 2','B','M3','น้ำ','สร้าง Criteria Database',14,18],
  ['B3-5','Sprint 2','B','M3','น้ำ','Mockup UI + Walkthrough Script M3',18,22],
  ['B4-4','Sprint 2','B','M4','เพิร์ล','สร้าง FAQ Seed Database',14,18],
  ['B4-5','Sprint 2','B','M4','เพิร์ล','Mockup UI + Walkthrough Script M4',18,22],
  ['F-1','Final','A','M1','ทั้งทีม','Demo Script + เลือก Video Demo',20,21],
  ['F-2','Final','A','M1','กิต+นัท','Pre-run Video Demo + เก็บ Result ใน DB',20,21],
  ['F-3','Final','A','ALL','ทั้งทีม','Dry Run Demo ทั้งทีม',21,22],
  ['F-4','Final','A','ALL','ทั้งทีม','Update Presentation + Screenshot',21,22],
  ['F-5','Final','A','ALL','ทั้งทีม','ตรวจ API Key Limit + Internet Backup',22,22],
];

// ─── Storage ──────────────────────────────────────────────────────────────────
function loadSaved(){
  try{ return JSON.parse(localStorage.getItem('dm_v2')||'{}'); }catch(e){ return {}; }
}
function save(){
  try{
    var obj={};
    TASKS.forEach(function(t){ obj[t.id]=t.status; });
    localStorage.setItem('dm_v2',JSON.stringify(obj));
    var dot=document.getElementById('save-dot'),txt=document.getElementById('save-txt');
    dot.classList.add('saving'); txt.textContent='Saving…';
    setTimeout(function(){
      dot.classList.remove('saving'); txt.textContent='Saved ✓';
      setTimeout(function(){ txt.textContent='Auto-save'; },2000);
    },500);
  }catch(e){}
}

// ─── State ────────────────────────────────────────────────────────────────────
var saved=loadSaved();
var TASKS=RAW.map(function(r){
  return {id:r[0],phase:r[1],track:r[2],module:r[3],owner:r[4],task:r[5],wdFrom:r[6],wdTo:r[7],status:saved[r[0]]||'todo'};
});
var currentView='gantt';

function getFiltered(){
  var fo=document.getElementById('f-owner').value;
  var fp=document.getElementById('f-phase').value;
  return TASKS.filter(function(t){
    return (fo==='all'||t.owner===fo)&&(fp==='all'||t.phase===fp);
  });
}

function setStatus(id,s){
  for(var i=0;i<TASKS.length;i++) if(TASKS[i].id===id){ TASKS[i].status=s; break; }
  save();
  renderStats();
  // update select styling in-place
  var el=document.querySelector('[data-id="'+id+'"]');
  if(el){ el.style.background=ST[s].bg; el.style.color=ST[s].tc; }
}

function setView(v){
  currentView=v;
  document.getElementById('btn-gantt').className='btn '+(v==='gantt'?'btn-active':'');
  document.getElementById('btn-list').className='btn '+(v==='list'?'btn-active':'');
  render();
}

// ─── Render Stats ─────────────────────────────────────────────────────────────
function renderStats(){
  var total=TASKS.length,done=0,inp=0,blk=0;
  TASKS.forEach(function(t){
    if(t.status==='done') done++;
    else if(t.status==='in-progress') inp++;
    else if(t.status==='blocked') blk++;
  });
  var pct=Math.round(done/total*100);
  var cards=[
    {l:'Total Tasks',v:total,c:'#fff',bg:''},
    {l:'Done',v:done,c:'#5DCAA5',bg:'rgba(93,202,165,.08)'},
    {l:'In Progress',v:inp,c:'#378ADD',bg:'rgba(55,138,221,.08)'},
    {l:'Blocked',v:blk,c:'#E24B4A',bg:'rgba(226,75,74,.08)'},
    {l:'Progress',v:pct+'%',c:'#5DCAA5',bg:'rgba(93,202,165,.1)'},
  ];
  document.getElementById('stats').innerHTML=cards.map(function(c){
    return '<div class="stat" style="'+(c.bg?'background:'+c.bg:'')+'"><div class="stat-n" style="color:'+c.c+'">'+c.v+'</div><div class="stat-l">'+c.l+'</div></div>';
  }).join('');
  document.getElementById('pbar').style.width=pct+'%';
}

// ─── Render Gantt ─────────────────────────────────────────────────────────────
function renderGantt(tasks){
  var n=WD.length;
  var dw=Math.max(18, Math.floor(880/n)); // px per day
  var totalW=n*dw;
  var h='<div class="gantt-scroll"><div style="min-width:'+(366+totalW)+'px">';
  // Head
  h+='<div class="g-head"><div class="g-col-name">Task</div><div class="g-col-own">Owner</div>';
  h+='<div class="g-col-days" style="min-width:'+totalW+'px">';
  WD.forEach(function(d,i){ h+='<div class="g-day-h" title="'+d.iso+'">'+(i%2===0?d.lbl.slice(3):'')+'</div>'; });
  h+='</div></div>';
  // WD index row
  h+='<div style="display:flex;background:rgba(0,0,0,.2);border-bottom:0.5px solid var(--border)">';
  h+='<div style="width:290px;flex-shrink:0;padding-left:16px;font-size:8px;color:rgba(255,255,255,.18)">WD</div>';
  h+='<div style="width:76px;flex-shrink:0"></div>';
  h+='<div style="flex:1;display:flex;min-width:'+totalW+'px">';
  WD.forEach(function(_,i){ h+='<div class="g-day-h">'+(i+1)+'</div>'; });
  h+='</div></div>';
  // Rows
  ['Sprint 0','Sprint 1','Sprint 2','Final'].forEach(function(phase){
    var pt=tasks.filter(function(t){ return t.phase===phase; });
    if(!pt.length) return;
    h+='<div class="g-phase-hdr" style="color:'+PHASE_C[phase]+'">'+phase+'</div>';
    pt.forEach(function(t){
      var si=t.wdFrom-1,ei=t.wdTo-1;
      var left=(si/n*100).toFixed(3)+'%';
      var width=((ei-si+1)/n*100).toFixed(3)+'%';
      var mc=MOD_C[t.module]||T;
      var oc=OWN_C[t.owner]||'#888';
      var op=t.status==='done'?1:t.status==='blocked'?.25:.72;
      var icon=t.status==='done'?'✓':t.status==='blocked'?'!':'';
      var bdr=t.status==='blocked'?'border:1.5px solid '+R+';':'';
      h+='<div class="g-row">';
      h+='<div class="g-name" title="'+t.task+'">'+t.task+'</div>';
      h+='<div class="g-own" style="color:'+oc+'">'+t.owner+'</div>';
      h+='<div class="g-bars" style="min-width:'+totalW+'px">';
      h+='<div class="g-bar" style="left:'+left+';width:'+width+';background:'+mc+';opacity:'+op+';'+bdr+'">'+icon+'</div>';
      h+='</div></div>';
    });
  });
  h+='</div></div>';
  document.getElementById('view').innerHTML=h;
}

// ─── Render List ──────────────────────────────────────────────────────────────
function renderList(tasks){
  var h='';
  ['Sprint 0','Sprint 1','Sprint 2','Final'].forEach(function(phase){
    var pt=tasks.filter(function(t){ return t.phase===phase; });
    if(!pt.length) return;
    var pc=PHASE_C[phase];
    h+='<div class="l-section"><div class="l-phase-tag" style="background:'+pc+'22;color:'+pc+'">'+phase+'</div>';
    pt.forEach(function(t){
      var s=WD[t.wdFrom-1],e=WD[t.wdTo-1];
      var st=ST[t.status],mc=MOD_C[t.module]||T,oc=OWN_C[t.owner]||'#888';
      h+='<div class="l-row">';
      h+='<div class="l-id">'+t.id+'</div>';
      h+='<div class="l-mod" style="background:'+mc+'">'+t.module+'</div>';
      h+='<div class="l-task">'+t.task+'</div>';
      h+='<div class="l-own" style="color:'+oc+'">'+t.owner+'</div>';
      h+='<div class="l-dates">'+(s?s.lbl:'')+' → '+(e?e.lbl:'')+'</div>';
      h+='<select class="l-sel" data-id="'+t.id+'" onchange="setStatus(\''+t.id+'\',this.value)" style="background:'+st.bg+';color:'+st.tc+'">';
      Object.keys(ST).forEach(function(k){
        h+='<option value="'+k+'"'+(t.status===k?' selected':'')+'>'+ST[k].lbl+'</option>';
      });
      h+='</select></div>';
    });
    h+='</div>';
  });
  document.getElementById('view').innerHTML=h;
}

// ─── Render Legend ────────────────────────────────────────────────────────────
function renderLegend(){
  var h='<span style="font-weight:500">Module:</span>';
  Object.keys(MOD_C).filter(function(k){return k!=='ALL';}).forEach(function(k){
    h+='<div style="display:flex;align-items:center;gap:4px"><div class="leg-dot" style="background:'+MOD_C[k]+'"></div><span style="color:var(--t2)">'+k+'</span></div>';
  });
  h+='<span style="color:var(--border)">|</span><span style="font-weight:500">Status:</span>';
  Object.keys(ST).forEach(function(k){
    h+='<div style="display:flex;align-items:center;gap:4px"><div class="leg-dot" style="background:'+ST[k].bg+';border:0.5px solid rgba(255,255,255,.15)"></div><span style="color:var(--t2)">'+ST[k].lbl+'</span></div>';
  });
  document.getElementById('legend').innerHTML=h;
}

// ─── Main Render ──────────────────────────────────────────────────────────────
function render(){
  renderStats();
  var f=getFiltered();
  document.getElementById('task-count').textContent=f.length+' tasks';
  if(currentView==='gantt') renderGantt(f); else renderList(f);
  renderLegend();
}

// ─── Export CSV ───────────────────────────────────────────────────────────────
function dl(name,rows){
  var bom='\uFEFF';
  var csv=bom+rows.map(function(r){
    return r.map(function(c){
      var s=String(c==null?'':c);
      return (s.indexOf(',')>-1||s.indexOf('"')>-1||s.indexOf('\n')>-1)?'"'+s.replace(/"/g,'""')+'"':s;
    }).join(',');
  }).join('\r\n');
  var a=document.createElement('a');
  a.href=URL.createObjectURL(new Blob([csv],{type:'text/csv;charset=utf-8'}));
  a.download=name; document.body.appendChild(a); a.click(); document.body.removeChild(a);
}
function exportCSV(){
  var rows=[['ID','Phase','Track','Module','Owner','Task','Start Date','End Date','Duration(WD)','Status']];
  TASKS.forEach(function(t){
    var s=WD[t.wdFrom-1],e=WD[t.wdTo-1];
    rows.push([t.id,t.phase,t.track,t.module,t.owner,t.task,s?s.iso:'',e?e.iso:'',t.wdTo-t.wdFrom+1,t.status]);
  });
  dl('DeepMate_Tasks.csv',rows);
  setTimeout(function(){
    var hdr=['Owner','Task'].concat(WD.map(function(d){return d.lbl;}));
    var tl=[hdr];
    TASKS.forEach(function(t){
      var s=WD[t.wdFrom-1],e=WD[t.wdTo-1];
      tl.push([t.owner,t.task].concat(WD.map(function(d){return (s&&e&&d.iso>=s.iso&&d.iso<=e.iso)?'●':'';})));
    });
    dl('DeepMate_Timeline.csv',tl);
  },400);
  setTimeout(function(){
    var byO={};
    TASKS.forEach(function(t){
      if(!byO[t.owner]) byO[t.owner]={total:0,done:0,ip:0,bl:0,td:0};
      byO[t.owner].total++;
      if(t.status==='done') byO[t.owner].done++;
      else if(t.status==='in-progress') byO[t.owner].ip++;
      else if(t.status==='blocked') byO[t.owner].bl++;
      else byO[t.owner].td++;
    });
    var pr=[['Owner','Total','Done','In Progress','Blocked','To Do','% Done']];
    Object.keys(byO).forEach(function(o){
      var v=byO[o];
      pr.push([o,v.total,v.done,v.ip,v.bl,v.td,Math.round(v.done/v.total*100)+'%']);
    });
    dl('DeepMate_Progress.csv',pr);
  },800);
}

// ─── Reset ────────────────────────────────────────────────────────────────────
function resetProgress(){
  if(!confirm('Reset ความคืบหน้าทั้งหมดกลับเป็น To Do?')) return;
  try{ localStorage.removeItem('dm_v2'); }catch(e){}
  TASKS=TASKS.map(function(t){ return Object.assign({},t,{status:'todo'}); });
  render();
}

// ─── Init ─────────────────────────────────────────────────────────────────────
render();
</script>
</body>
</html>

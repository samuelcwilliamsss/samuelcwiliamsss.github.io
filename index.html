<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BBF Division 5 · 2026 Stats</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;font-size:14px;background:#f5f5f0;color:#1a1a1a;min-height:100vh}
.app{max-width:1200px;margin:0 auto;padding:1.25rem}
header{display:flex;align-items:center;justify-content:space-between;margin-bottom:1.25rem;flex-wrap:wrap;gap:8px}
.logo{display:flex;align-items:center;gap:10px}
h1{font-size:17px;font-weight:700}
.badge{font-size:10px;font-weight:700;padding:2px 8px;border-radius:20px;background:#dbeafe;color:#1e40af;text-transform:uppercase;letter-spacing:.05em}
.status{font-size:12px;color:#666;display:flex;align-items:center;gap:5px}
.dot{width:7px;height:7px;border-radius:50%;background:#ccc;flex-shrink:0;transition:background .4s}
.dot.live{background:#16a34a}.dot.stale{background:#d97706}.dot.err{background:#dc2626}
button.refresh{font-size:12px;padding:5px 14px;border:1px solid #d4d4d4;border-radius:6px;background:#fff;cursor:pointer;font-weight:500}
button.refresh:hover{background:#f0f7ff;border-color:#93c5fd;color:#1d4ed8}
.tabs{display:flex;background:#fff;border:1px solid #e5e5e5;border-radius:10px 10px 0 0;overflow:hidden;overflow-x:auto}
.tab{padding:11px 18px;font-size:13px;font-weight:500;cursor:pointer;border:none;background:transparent;color:#888;border-bottom:2px solid transparent;white-space:nowrap;transition:all .15s}
.tab:hover{color:#333;background:#f9f9f9}
.tab.active{color:#1d4ed8;border-bottom-color:#1d4ed8;background:#fff}
.panel{display:none;background:#fff;border:1px solid #e5e5e5;border-top:none;border-radius:0 0 10px 10px;padding:1.1rem;box-shadow:0 1px 4px rgba(0,0,0,.05)}
.panel.active{display:block}
.ctrl{display:flex;gap:6px;flex-wrap:wrap;align-items:center;margin-bottom:.9rem}
input[type=text],select{font-size:12px;height:32px;padding:0 9px;border:1px solid #d4d4d4;border-radius:7px;background:#fff;color:#1a1a1a;outline:none;transition:border-color .15s}
input[type=text]:focus,select:focus{border-color:#3b82f6;box-shadow:0 0 0 2px rgba(59,130,246,.1)}
input[type=text]{width:170px}
label.chk{font-size:12px;color:#555;display:flex;align-items:center;gap:4px;cursor:pointer}
.tw{overflow-x:auto;border-radius:7px;border:1px solid #e8e8e8}
table{width:100%;font-size:12px;border-collapse:collapse;min-width:600px}
thead{background:#f9f9f7}
th{padding:7px 8px;font-size:10.5px;font-weight:700;color:#666;border-bottom:1px solid #e5e5e5;text-align:left;cursor:pointer;white-space:nowrap;user-select:none}
th:hover{color:#111;background:#f0f0ec}
th.s{color:#1d4ed8}
td{padding:5px 8px;border-bottom:1px solid #f0f0ee;white-space:nowrap}
tr:last-child td{border-bottom:none}
tr:hover td{background:#fafaf8}
.pn{font-weight:600;font-size:12.5px}
.tm{font-size:10px;font-weight:700;padding:2px 6px;border-radius:8px;background:#eff6ff;color:#1e40af;display:inline-block}
.hl{color:#15803d;font-weight:700}
.pag{display:flex;align-items:center;gap:8px;margin-top:10px;font-size:12px;color:#666}
.pag button{padding:4px 12px;border:1px solid #d4d4d4;border-radius:6px;background:#fff;cursor:pointer;font-size:12px}
.pag button:hover{background:#f5f5f5}
.addbtn{font-size:10px;padding:2px 8px;cursor:pointer;border-radius:8px;background:#f4f4f4;border:1px solid #ddd;color:#555;white-space:nowrap}
.addbtn:hover{background:#dbeafe;color:#1e40af;border-color:#93c5fd}
.loader{display:flex;flex-direction:column;align-items:center;justify-content:center;padding:3rem;gap:12px;color:#888;font-size:13px}
.spin{width:28px;height:28px;border:3px solid #e5e5e5;border-top-color:#3b82f6;border-radius:50%;animation:sp .7s linear infinite}
@keyframes sp{to{transform:rotate(360deg)}}
.err-box{background:#fef2f2;border:1px solid #fecaca;border-radius:8px;padding:1rem;color:#dc2626;font-size:13px}

/* Compare players */
.cmp-wrap{display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin-bottom:1rem}
@media(max-width:600px){.cmp-wrap{grid-template-columns:1fr}}
.slot{border:1.5px solid #e5e5e5;border-radius:10px;padding:1rem;transition:border-color .2s;background:#fafaf8}
.slot.filled{border-color:#3b82f6;background:#f8fbff}
.slot-hdr{font-size:10px;font-weight:700;color:#aaa;text-transform:uppercase;letter-spacing:.07em;margin-bottom:8px;display:flex;justify-content:space-between;align-items:center}
.slot-clr{background:none;border:none;cursor:pointer;color:#bbb;font-size:15px;line-height:1;padding:0}
.slot-clr:hover{color:#666}
.slot-name{font-size:15px;font-weight:700;margin-bottom:2px}
.slot-team{font-size:11px;color:#888;margin-bottom:8px}
.sg{display:grid;grid-template-columns:repeat(3,1fr);gap:5px;margin-top:6px}
.sg-cell .l{font-size:10px;color:#aaa}
.sg-cell .v{font-size:13px;font-weight:700}
.empty-msg{font-size:12px;color:#bbb;padding:4px 0}
.bars-wrap{border:1px solid #e5e5e5;border-radius:10px;padding:1rem;background:#fafaf8;margin-top:.5rem}
.bars-legend{display:flex;gap:14px;font-size:11px;color:#666;margin-bottom:10px;font-weight:500}
.lsq{width:10px;height:10px;border-radius:2px;display:inline-block;margin-right:3px;vertical-align:middle}
.brow{display:grid;grid-template-columns:1fr 72px 1fr;align-items:center;gap:5px;margin-bottom:7px}
.blbl{font-size:10px;text-align:center;color:#999;font-weight:700}
.bwrap{height:17px;background:#eee;border-radius:3px;overflow:hidden}
.bleft .bf{height:100%;background:#3b82f6;border-radius:3px;float:right;transition:width .4s}
.bright .bf{height:100%;background:#f97316;border-radius:3px;transition:width .4s}
.bv{font-size:11px;font-weight:600;min-width:38px}
.bv.w{color:#15803d;font-weight:800}
.bv.wbad{color:#dc2626;font-weight:800}

/* Team compare */
.tsel-bar{display:flex;gap:6px;flex-wrap:wrap;min-height:32px;align-items:center;margin-bottom:.75rem}
.tpill{font-size:11px;font-weight:600;padding:4px 10px;border-radius:20px;display:flex;align-items:center;gap:5px}
.tpill button{background:none;border:none;cursor:pointer;font-size:14px;line-height:1;padding:0;margin-left:1px}
.tc-out{border:1px solid #e5e5e5;border-radius:10px;padding:1rem;background:#fafaf8;margin-bottom:1rem}
.tstat-lbl{font-size:10px;font-weight:700;color:#999;text-transform:uppercase;letter-spacing:.05em;margin-bottom:5px}
.tbr{display:flex;align-items:center;gap:8px;margin-bottom:4px}
.tbn{font-size:11px;font-weight:700;min-width:36px}
.tbb{flex:1;height:15px;border-radius:3px;background:#eee;overflow:hidden}
.tbf{height:100%;border-radius:3px;transition:width .4s}
.tbv{font-size:11px;min-width:44px;text-align:right}
.tbv.w{font-weight:800;color:#15803d}
.tgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(145px,1fr));gap:.65rem}
.tcard{background:#fff;border:1.5px solid #e5e5e5;border-radius:9px;padding:.8rem;cursor:pointer;transition:all .15s}
.tcard:hover{border-color:#93c5fd;box-shadow:0 2px 8px rgba(59,130,246,.1);transform:translateY(-1px)}
.tcard.sel{background:#f0f7ff}
.tn{font-size:14px;font-weight:800;margin-bottom:3px}
.ts{font-size:11px;color:#888;line-height:1.6}
.tbtn{display:inline-block;margin-top:6px;font-size:10px;padding:2px 8px;border-radius:8px;border:1px solid #ddd;background:#f4f4f4;color:#666;cursor:pointer;font-weight:500}
.last-updated{font-size:11px;color:#aaa;margin-top:.5rem;text-align:right}
.lavg-row{display:flex;align-items:center;justify-content:space-between;padding:5px 0;border-bottom:1px solid #f0f0ee;font-size:12.5px}
.lavg-row:last-child{border-bottom:none}
.lavg-label{color:#666;font-size:11px;font-weight:600;text-transform:uppercase;letter-spacing:.04em;min-width:80px}
.lavg-val{font-weight:700;font-size:14px;color:#1a1a1a}
.lavg-sub{font-size:10px;color:#aaa;margin-top:1px}
.lavg-team-row{display:flex;align-items:center;gap:8px;margin-bottom:5px;font-size:12px}
.lavg-team-name{min-width:40px;font-weight:700;font-size:11px}
.lavg-bar-bg{flex:1;height:14px;border-radius:3px;background:#eee;overflow:hidden;position:relative}
.lavg-bar-fill{height:100%;border-radius:3px;transition:width .4s}
.lavg-marker{position:absolute;top:0;bottom:0;width:2px;background:#1a1a1a;opacity:.4}
.lavg-team-val{font-size:11px;min-width:38px;text-align:right;font-weight:600}
.lavg-team-val.above{color:#15803d}
.lavg-team-val.below{color:#dc2626}
.pct-badge{display:inline-block;font-size:9px;font-weight:700;padding:1px 5px;border-radius:8px;margin-left:4px;vertical-align:middle;letter-spacing:.02em}
.pct-top{background:#dcfce7;color:#15803d}
.pct-mid{background:#fef9c3;color:#854d0e}
.pct-bot{background:#fee2e2;color:#dc2626}

/* Player card modal */
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.35);z-index:1000;display:flex;align-items:center;justify-content:center;padding:1rem;animation:fadeIn .15s ease}
@keyframes fadeIn{from{opacity:0}to{opacity:1}}
.modal-card{background:#fff;border-radius:14px;padding:1.5rem;max-width:480px;width:100%;box-shadow:0 20px 60px rgba(0,0,0,.2);position:relative;animation:slideUp .2s ease}
@keyframes slideUp{from{transform:translateY(12px);opacity:0}to{transform:translateY(0);opacity:1}}
.modal-close{position:absolute;top:12px;right:14px;background:none;border:none;font-size:20px;cursor:pointer;color:#aaa;line-height:1}
.modal-close:hover{color:#333}
.modal-name{font-size:18px;font-weight:800;margin-bottom:2px}
.modal-team{font-size:12px;color:#888;margin-bottom:1.1rem;display:flex;align-items:center;gap:6px}
.modal-section{font-size:10px;font-weight:700;color:#aaa;text-transform:uppercase;letter-spacing:.06em;margin:1rem 0 .5rem}
.modal-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:8px}
.modal-stat{background:#f9f9f7;border-radius:8px;padding:8px 10px}
.modal-stat-label{font-size:10px;color:#999;font-weight:600;margin-bottom:3px}
.modal-stat-val{font-size:15px;font-weight:700;display:flex;align-items:center;gap:4px}
.modal-actions{display:flex;gap:8px;margin-top:1.1rem;padding-top:1rem;border-top:1px solid #f0f0ee}
.modal-btn{flex:1;font-size:12px;padding:7px 12px;border-radius:7px;cursor:pointer;font-weight:600;border:1.5px solid;transition:all .15s}
.modal-btn-cmp{background:#eff6ff;color:#1d4ed8;border-color:#bfdbfe}
.modal-btn-cmp:hover{background:#dbeafe}
.pn-link{cursor:pointer;color:#1a1a1a;border-bottom:1px dashed #ccc;transition:color .15s}
.pn-link:hover{color:#1d4ed8;border-color:#93c5fd}
</style>
</head>
<body>
<div class="app">
  <header>
    <div class="logo">
      <h1>⚾ BBF Division 5 · 2026</h1>
      <span class="badge">Live Stats</span>
    </div>
    <div style="display:flex;align-items:center;gap:10px;flex-wrap:wrap">
      <span class="status"><span class="dot" id="dot"></span><span id="stxt">Loading…</span></span>
      <button class="refresh" onclick="loadAll()">↻ Refresh</button>
    </div>
  </header>

  <div class="tabs">
    <button class="tab active" onclick="show('bat')" id="tab-bat">Batting</button>
    <button class="tab" onclick="show('pit')" id="tab-pit">Pitching</button>
    <button class="tab" onclick="show('cmp')" id="tab-cmp">Compare batters</button>
    <button class="tab" onclick="show('pcmp')" id="tab-pcmp">Compare pitchers</button>
    <button class="tab" onclick="show('tcmp')" id="tab-tcmp">Compare teams</button>
    <button class="tab" onclick="show('lavg')" id="tab-lavg">League averages</button>
  </div>

  <!-- BATTING -->
  <div id="p-bat" class="panel active">
    <div id="bat-loader" class="loader"><div class="spin"></div><span>Loading batting stats…</span></div>
    <div id="bat-content" style="display:none">
      <div class="ctrl">
        <input type="text" id="bsrch" placeholder="Search player…" oninput="rBat()">
        <select id="bteam" onchange="rBat()"><option value="">All teams</option></select>
        <select id="bsort" onchange="rBat()">
          <option value="AVG">Sort: AVG</option><option value="OPS">OPS</option>
          <option value="OBP">OBP</option><option value="SLG">SLG</option>
          <option value="H">Hits</option><option value="RBI">RBI</option>
          <option value="HR">HR</option><option value="SB">SB</option>
          <option value="R">Runs</option><option value="AB">AB</option>
          <option value="SO">SO</option><option value="BB">BB</option>
        </select>
        <label class="chk"><input type="checkbox" id="bqual" checked onchange="rBat()"> Min 10 AB</label>
        <span id="bcount" style="font-size:12px;color:#888"></span>
      </div>
      <div class="tw"><table>
        <thead><tr>
          <th style="width:26px">#</th><th>Player</th><th>Team</th>
          <th onclick="sby('G')">G</th><th onclick="sby('AB')">AB</th>
          <th onclick="sby('R')">R</th><th onclick="sby('H')">H</th>
          <th onclick="sby('2B')">2B</th><th onclick="sby('3B')">3B</th>
          <th onclick="sby('HR')">HR</th><th onclick="sby('RBI')">RBI</th>
          <th onclick="sby('SB')">SB</th><th onclick="sby('BB')">BB</th>
          <th onclick="sby('SO')">SO</th>
          <th onclick="sby('AVG')" class="s">AVG</th>
          <th onclick="sby('OBP')">OBP</th>
          <th onclick="sby('SLG')">SLG</th>
          <th onclick="sby('OPS')">OPS</th>
          <th></th>
        </tr></thead>
        <tbody id="bbody"></tbody>
      </table></div>
      <div class="pag"><button onclick="bpg(-1)">‹ Prev</button><span id="bpgi"></span><button onclick="bpg(1)">Next ›</button></div>
      <div class="last-updated" id="bat-updated"></div>
    </div>
  </div>

  <!-- PITCHING -->
  <div id="p-pit" class="panel">
    <div id="pit-loader" class="loader"><div class="spin"></div><span>Loading pitching stats…</span></div>
    <div id="pit-content" style="display:none">
      <div class="ctrl">
        <input type="text" id="psrch" placeholder="Search pitcher…" oninput="rPit()">
        <select id="pteam" onchange="rPit()"><option value="">All teams</option></select>
        <select id="psort" onchange="rPit()">
          <option value="ERA">Sort: ERA</option><option value="SO">K</option>
          <option value="IP">IP</option><option value="W">W</option><option value="WHIP">WHIP</option>
        </select>
        <span id="pcount" style="font-size:12px;color:#888"></span>
      </div>
      <div class="tw"><table>
        <thead><tr>
          <th style="width:26px">#</th><th>Player</th><th>Team</th>
          <th>App</th><th>GS</th><th>W</th><th>L</th><th>SV</th>
          <th onclick="spy('IP')">IP</th><th>H</th><th>ER</th>
          <th onclick="spy('BB')">BB</th><th onclick="spy('SO')">K</th>
          <th onclick="spy('ERA')" class="s">ERA</th>
          <th onclick="spy('WHIP')">WHIP</th><th>BAA</th>
        </tr></thead>
        <tbody id="pbody"></tbody>
      </table></div>
      <div class="pag"><button onclick="ppg(-1)">‹ Prev</button><span id="ppgi"></span><button onclick="ppg(1)">Next ›</button></div>
      <div class="last-updated" id="pit-updated"></div>
    </div>
  </div>

  <!-- COMPARE PLAYERS -->
  <div id="p-cmp" class="panel">
    <p style="font-size:12px;color:#888;margin-bottom:.9rem">Hit <strong>+ Compare</strong> on any batting row, or search below.</p>
    <div class="cmp-wrap" style="grid-template-columns:1fr 1fr 1fr">
      <div class="slot" id="slotA">
        <div class="slot-hdr">Batter A <button class="slot-clr" onclick="clr('a')">✕</button></div>
        <div id="slotAc"><div class="empty-msg">No player selected</div></div>
      </div>
      <div class="slot" id="slotB">
        <div class="slot-hdr">Batter B <button class="slot-clr" onclick="clr('b')">✕</button></div>
        <div id="slotBc"><div class="empty-msg">No player selected</div></div>
      </div>
      <div class="slot" style="border-color:#e5e5e5;background:#f9f9f7">
        <div class="slot-hdr" style="color:#aaa">League average</div>
        <div id="slotLgc"><div class="empty-msg">Calculated from all batters (min 10 AB)</div></div>
      </div>
    </div>
    <div id="barsec" style="display:none" class="bars-wrap">
      <div class="bars-legend">
        <span><span class="lsq" style="background:#3b82f6"></span><span id="legA">A</span></span>
        <span><span class="lsq" style="background:#f97316"></span><span id="legB">B</span></span>
        <span><span class="lsq" style="background:#9ca3af"></span>League avg</span>
      </div>
      <div id="barcont"></div>
    </div>
    <div style="font-size:12px;font-weight:700;color:#555;margin:1.1rem 0 .5rem;border-top:1px solid #eee;padding-top:.9rem">Search &amp; add</div>
    <div class="ctrl">
      <input type="text" id="csrch" placeholder="Search player…" oninput="rCmp()">
      <select id="cteam" onchange="rCmp()"><option value="">All teams</option></select>
      <select id="csort" onchange="rCmp()">
        <option value="AVG">AVG</option><option value="OPS">OPS</option>
        <option value="RBI">RBI</option><option value="SB">SB</option><option value="R">R</option>
      </select>
    </div>
    <div class="tw"><table>
      <thead><tr><th>Player</th><th>Team</th><th>AB</th><th>AVG</th><th>OBP</th><th>SLG</th><th>OPS</th><th>RBI</th><th>SB</th><th>HR</th><th></th></tr></thead>
      <tbody id="cbody"></tbody>
    </table></div>
    <div class="pag"><button onclick="cpg(-1)">‹</button><span id="cpgi"></span><button onclick="cpg(1)">›</button></div>
  </div>

  <!-- COMPARE PITCHERS -->
  <div id="p-pcmp" class="panel">
    <p style="font-size:12px;color:#888;margin-bottom:.9rem">Hit <strong>+ Compare</strong> on any pitching row, or search below.</p>
    <div class="cmp-wrap" style="grid-template-columns:1fr 1fr 1fr">
      <div class="slot" id="pslotA">
        <div class="slot-hdr">Pitcher A <button class="slot-clr" onclick="pclr('a')">✕</button></div>
        <div id="pslotAc"><div class="empty-msg">No pitcher selected</div></div>
      </div>
      <div class="slot" id="pslotB">
        <div class="slot-hdr">Pitcher B <button class="slot-clr" onclick="pclr('b')">✕</button></div>
        <div id="pslotBc"><div class="empty-msg">No pitcher selected</div></div>
      </div>
      <div class="slot" style="border-color:#e5e5e5;background:#f9f9f7">
        <div class="slot-hdr" style="color:#aaa">League average</div>
        <div id="pslotLgc"><div class="empty-msg">Calculated from all pitchers</div></div>
      </div>
    </div>
    <div id="pbarsec" style="display:none" class="bars-wrap">
      <div class="bars-legend">
        <span><span class="lsq" style="background:#3b82f6"></span><span id="plegA">A</span></span>
        <span><span class="lsq" style="background:#f97316"></span><span id="plegB">B</span></span>
        <span><span class="lsq" style="background:#9ca3af"></span>League avg</span>
      </div>
      <div id="pbarcont"></div>
    </div>
    <div style="font-size:12px;font-weight:700;color:#555;margin:1.1rem 0 .5rem;border-top:1px solid #eee;padding-top:.9rem">Search &amp; add</div>
    <div class="ctrl">
      <input type="text" id="pcsrch" placeholder="Search pitcher…" oninput="rPCmp()">
      <select id="pcteam" onchange="rPCmp()"><option value="">All teams</option></select>
      <select id="pcsort" onchange="rPCmp()">
        <option value="ERA">ERA</option><option value="SO">K</option>
        <option value="IP">IP</option><option value="W">W</option><option value="WHIP">WHIP</option>
      </select>
    </div>
    <div class="tw"><table>
      <thead><tr><th>Pitcher</th><th>Team</th><th>App</th><th>W</th><th>L</th><th>SV</th><th>IP</th><th>K</th><th>BB</th><th>ERA</th><th>WHIP</th><th>BAA</th><th></th></tr></thead>
      <tbody id="pcbody"></tbody>
    </table></div>
    <div class="pag"><button onclick="pcpg(-1)">‹</button><span id="pcpgi"></span><button onclick="pcpg(1)">›</button></div>
  </div>

  <!-- COMPARE TEAMS -->
  <div id="p-tcmp" class="panel">
    <p style="font-size:12px;color:#888;margin-bottom:.75rem">Click any team card to select it (up to 4) and compare batting stats side by side.</p>
    <div class="tsel-bar" id="tsel"></div>
    <div id="tcout"></div>
    <div class="tgrid" id="tgrid"></div>
  </div>

  <!-- LEAGUE AVERAGES -->
  <div id="p-lavg" class="panel">
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem" id="lavg-content">
      <div>
        <div style="font-size:13px;font-weight:700;color:#333;margin-bottom:.75rem;padding-bottom:.5rem;border-bottom:1px solid #eee">⚾ Batting — league averages</div>
        <div id="lavg-bat"></div>
      </div>
      <div>
        <div style="font-size:13px;font-weight:700;color:#333;margin-bottom:.75rem;padding-bottom:.5rem;border-bottom:1px solid #eee">⚾ Pitching — league averages</div>
        <div id="lavg-pit"></div>
      </div>
    </div>
    <div style="margin-top:1.5rem">
      <div style="font-size:13px;font-weight:700;color:#333;margin-bottom:.75rem;padding-bottom:.5rem;border-bottom:1px solid #eee">📊 Team batting vs league average</div>
      <div id="lavg-teams"></div>
    </div>
  </div>
</div>

<!-- PLAYER CARD MODAL -->
<div class="modal-overlay" id="modal" style="display:none" onclick="if(event.target===this)closeModal()">
  <div class="modal-card">
    <button class="modal-close" onclick="closeModal()">✕</button>
    <div class="modal-name" id="modal-name"></div>
    <div class="modal-team" id="modal-team"></div>
    <div id="modal-body"></div>
    <div class="modal-actions" id="modal-actions"></div>
  </div>
</div>

<script>
// ── Data source: your published Google Sheet ──
const SHEET_BASE = 'https://docs.google.com/spreadsheets/d/e/2PACX-1vRfcExy7QI69mNIzKjEe4OLIktSVWYlD4ttC7UqnbWWfTYhQy4rWlsoRX7_ddl27-uiUj3Vo9CV9NpL/pub?output=csv&gid=';
const GID_BAT = '34236868';       // Player Batting (493 rows)
const GID_PIT = '1358930240';     // Player Pitching (138 rows)
const GID_TBAT = '862775525';     // Team Batting (27 rows)

const TC = ['#3b82f6','#f97316','#16a34a','#7c3aed'];

let BAT=[], PIT=[], TBAT=[], selTeams=[], slA=null, slB=null;
let bSort='AVG', bDir=-1, bPg=0, bFil=[];
let pSort='ERA', pDir=1, pPg=0, pFil=[];
let cPg=0;
let lgAvg={}, lgPitAvg={}; // league averages computed on load

const $ = id => document.getElementById(id);
const flt = v => parseFloat(v)||0;
const f3 = v => { const n=parseFloat(v); return isNaN(n)?'-':n.toFixed(3); };
const f2 = v => { const n=parseFloat(v); return isNaN(n)?'-':n.toFixed(2); };

// Compute percentile rank of val in array of values (higher = better by default, low=true flips it)
function pctRank(val, arr, low=false) {
  const v = flt(val);
  const sorted = arr.map(x=>flt(x)).filter(x=>!isNaN(x)).sort((a,b)=>a-b);
  if(!sorted.length) return null;
  const below = sorted.filter(x => x < v).length;
  const rank = Math.round((below / sorted.length) * 100);
  return low ? (100 - rank) : rank; // flip for "lower is better" stats
}

// Return a percentile badge HTML string
function pctBadge(rank) {
  if(rank === null) return '';
  const cls = rank >= 75 ? 'pct-top' : rank >= 25 ? 'pct-mid' : 'pct-bot';
  const label = rank >= 75 ? `P${rank}` : rank >= 25 ? `P${rank}` : `P${rank}`;
  return `<span class="pct-badge ${cls}">${label}</span>`;
}

// Parse CSV text into array of objects
function parseCSV(text) {
  const lines = text.trim().split('\n');
  const headers = lines[0].split(',').map(h => h.trim().replace(/\r/g,''));
  return lines.slice(1).map(line => {
    // Handle quoted fields
    const vals = [];
    let cur='', inQ=false;
    for(const ch of line) {
      if(ch==='"') inQ=!inQ;
      else if(ch===',' && !inQ) { vals.push(cur.trim()); cur=''; }
      else cur+=ch;
    }
    vals.push(cur.trim().replace(/\r/g,''));
    const obj={};
    headers.forEach((h,i) => obj[h]=vals[i]||'');
    return obj;
  }).filter(r => r.Name && r.Name.trim());
}

async function loadAll() {
  $('dot').className='dot';
  $('stxt').innerHTML='<span style="display:inline-block;width:10px;height:10px;border:2px solid #e5e5e5;border-top-color:#3b82f6;border-radius:50%;animation:sp .7s linear infinite;vertical-align:middle;margin-right:4px"></span>Fetching from Google Sheet…';
  $('bat-loader').style.display='flex'; $('bat-content').style.display='none';
  $('pit-loader').style.display='flex'; $('pit-content').style.display='none';

  try {
    const [br, pr, tbr] = await Promise.all([
      fetch(SHEET_BASE + GID_BAT).then(r=>{ if(!r.ok) throw new Error('Batting: '+r.status); return r.text(); }),
      fetch(SHEET_BASE + GID_PIT).then(r=>{ if(!r.ok) throw new Error('Pitching: '+r.status); return r.text(); }),
      fetch(SHEET_BASE + GID_TBAT).then(r=>{ if(!r.ok) throw new Error('Team: '+r.status); return r.text(); }),
    ]);

    BAT  = parseCSV(br);
    PIT  = parseCSV(pr);
    TBAT = parseCSV(tbr);

    $('dot').className='dot live';
    const ts = new Date().toLocaleTimeString();
    $('stxt').textContent = `Live · ${BAT.length} batters · ${PIT.length} pitchers · ${ts}`;
    $('tab-bat').textContent = `Batting`;
    $('tab-pit').textContent = `Pitching`;
    $('bat-updated').textContent = `Last updated: ${ts}`;
    $('pit-updated').textContent = `Last updated: ${ts}`;

    init();
  } catch(e) {
    $('dot').className='dot err';
    $('stxt').textContent = 'Error: '+e.message;
    $('bat-loader').innerHTML = `<div class="err-box">❌ Could not load data: ${e.message}<br><small>Check your sheet is published: File → Share → Publish to web</small></div>`;
    $('pit-loader').innerHTML = `<div class="err-box">❌ Could not load data: ${e.message}</div>`;
  }
}

function init() {
  const teams = [...new Set(BAT.map(p=>p.Team).filter(Boolean))].sort();
  ['bteam','pteam','cteam','pcteam'].forEach(id => {
    const s=$(id); while(s.options.length>1) s.remove(1);
    teams.forEach(t => { const o=document.createElement('option'); o.value=t; o.textContent=t; s.appendChild(o); });
  });

  // Compute league batting averages (qualified batters, min 10 AB)
  const qual = BAT.filter(p => flt(p.AB) >= 10);
  const avg = f => qual.reduce((s,p)=>s+flt(p[f]),0) / Math.max(qual.length,1);
  lgAvg = {
    AVG: avg('AVG'), OBP: avg('OBP'), SLG: avg('SLG'), OPS: avg('OPS'),
    H:   avg('H'),   HR:  avg('HR'),  RBI: avg('RBI'), R:   avg('R'),
    SB:  avg('SB'),  BB:  avg('BB'),  SO:  avg('SO'),  AB:  avg('AB'),
    _n: qual.length
  };

  // Compute league pitching averages
  const pavg = f => PIT.reduce((s,p)=>s+flt(p[f]),0) / Math.max(PIT.length,1);
  lgPitAvg = {
    ERA: pavg('ERA'), WHIP: pavg('WHIP'), BAA: pavg('BAA'),
    SO:  pavg('SO'),  IP:   pavg('IP'),   W:   pavg('W'),
    BB:  pavg('BB'),  ER:   pavg('ER'),   H:   pavg('H'),
    SV:  pavg('SV'),  _n: PIT.length
  };

  bPg=0; pPg=0; cPg=0; pcPg=0;
  rBat(); rPit(); rCmp(); rPCmp(); rTGrid(); rLAvg();
  rSlots(); rPSlots(); // refresh compare slots with new league avg
  $('bat-loader').style.display='none'; $('bat-content').style.display='block';
  $('pit-loader').style.display='none'; $('pit-content').style.display='block';
}

function show(id) {
  document.querySelectorAll('.panel,.tab').forEach(e=>e.classList.remove('active'));
  $('p-'+id).classList.add('active');
  $('tab-'+id).classList.add('active');
}

// ── Batting ──
function sby(f){ bSort=f; bDir=(f==='SO'?1:-1); bPg=0; rBat(); }
function bpg(d){ bPg=Math.max(0,bPg+d); rBat(); }
function rBat(){
  bSort = $('bsort').value;
  const q=$('bsrch').value.toLowerCase(), tm=$('bteam').value, qual=$('bqual').checked;
  bFil = BAT
    .filter(p => (!qual||flt(p.AB)>=10) && (!tm||p.Team===tm) && (!q||p.Name.toLowerCase().includes(q)))
    .sort((a,b) => (flt(b[bSort])-flt(a[bSort]))*bDir);
  if(bPg*25>=bFil.length && bPg>0) bPg=0;
  const s=bPg*25, e=s+25, pg=bFil.slice(s,e);
  $('bpgi').textContent = `${bFil.length?s+1:0}–${Math.min(e,bFil.length)} of ${bFil.length}`;
  $('bcount').textContent = qual?`(${bFil.length} qualified)`:`(${bFil.length} players)`;
  $('bbody').innerHTML = pg.map((p,i) => `<tr>
    <td style="color:#bbb;font-size:10px">${s+i+1}</td>
    <td><span class="pn pn-link" onclick='openBatCard(${JSON.stringify(p)})'>${p.Name}</span></td>
    <td><span class="tm">${p.Team}</span></td>
    <td>${p.G}</td><td>${p.AB}</td><td>${p.R}</td><td>${p.H}</td>
    <td>${p['2B']}</td><td>${p['3B']}</td><td>${p.HR}</td><td>${p.RBI}</td>
    <td>${p.SB}</td><td>${p.BB}</td><td>${p.SO}</td>
    <td class="hl">${f3(p.AVG)}</td><td>${f3(p.OBP)}</td><td>${f3(p.SLG)}</td><td>${f3(p.OPS)}</td>
    <td><button class="addbtn" onclick='addCmp(${JSON.stringify({Name:p.Name,Team:p.Team,AVG:p.AVG,OBP:p.OBP,SLG:p.SLG,OPS:p.OPS,H:p.H,HR:p.HR,RBI:p.RBI,R:p.R,SB:p.SB,BB:p.BB,SO:p.SO,AB:p.AB})});show("cmp")'>+ Compare</button></td>
  </tr>`).join('');
}

// ── Pitching ──
function spy(f){ pSort=f; pDir=(f==='ERA'||f==='WHIP')?1:-1; pPg=0; rPit(); }
function ppg(d){ pPg=Math.max(0,pPg+d); rPit(); }
function rPit(){
  pSort = $('psort').value;
  const asc = pSort==='ERA'||pSort==='WHIP';
  const q=$('psrch').value.toLowerCase(), tm=$('pteam').value;
  pFil = PIT
    .filter(p => (!tm||p.Team===tm) && (!q||p.Name.toLowerCase().includes(q)))
    .sort((a,b) => asc ? flt(a[pSort])-flt(b[pSort]) : flt(b[pSort])-flt(a[pSort]));
  if(pPg*25>=pFil.length && pPg>0) pPg=0;
  const s=pPg*25, e=s+25, pg=pFil.slice(s,e);
  $('ppgi').textContent = `${pFil.length?s+1:0}–${Math.min(e,pFil.length)} of ${pFil.length}`;
  $('pcount').textContent = `(${pFil.length} pitchers)`;
  $('pbody').innerHTML = pg.map((p,i) => `<tr>
    <td style="color:#bbb;font-size:10px">${s+i+1}</td>
    <td><span class="pn pn-link" onclick='openPitCard(${JSON.stringify(p)})'>${p.Name}</span></td>
    <td><span class="tm">${p.Team}</span></td>
    <td>${p.APP}</td><td>${p.GS}</td><td>${p.W}</td><td>${p.L}</td><td>${p.SV}</td>
    <td>${p.IP}</td><td>${p.H}</td><td>${p.ER}</td>
    <td>${p.BB}</td><td>${p.SO}</td>
    <td class="hl">${f2(p.ERA)}</td><td>${f2(p.WHIP)}</td><td>${f3(p.BAA)}</td>
    <td><button class="addbtn" onclick='addPCmp(${JSON.stringify({Name:p.Name,Team:p.Team,ERA:p.ERA,WHIP:p.WHIP,BAA:p.BAA,SO:p.SO,IP:p.IP,W:p.W,L:p.L,SV:p.SV,BB:p.BB,ER:p.ER,H:p.H,APP:p.APP})});show("pcmp")'>+ Compare</button></td>
  </tr>`).join('');
}

// ── Compare players ──
function addCmp(pl){
  if(!slA){ slA=pl; }
  else if(!slB && pl.Name!==slA.Name){ slB=pl; }
  else if(pl.Name===slA?.Name || pl.Name===slB?.Name){ return; }
  else { slA=slB; slB=pl; }
  rSlots();
}
function clr(s){ if(s==='a') slA=null; else slB=null; rSlots(); }

function rSlots(){
  const render = (pl, sid, cid) => {
    const slot=$(sid), cont=$(cid);
    if(!pl){ cont.innerHTML='<div class="empty-msg">No player selected</div>'; slot.classList.remove('filled'); return; }
    slot.classList.add('filled');
    // Use qualified batters (min 10 AB) as population for percentiles
    const qual = BAT.filter(p=>flt(p.AB)>=10);
    const batPct = (field, low=false) => pctBadge(pctRank(pl[field], qual.map(p=>p[field]), low));
    cont.innerHTML = `<div class="slot-name">${pl.Name}</div><div class="slot-team">${pl.Team}</div>
    <div class="sg">${[
      ['AVG', f3(pl.AVG),  batPct('AVG')],
      ['OBP', f3(pl.OBP),  batPct('OBP')],
      ['SLG', f3(pl.SLG),  batPct('SLG')],
      ['OPS', f3(pl.OPS),  batPct('OPS')],
      ['RBI', pl.RBI,       batPct('RBI')],
      ['HR',  pl.HR,        batPct('HR')],
      ['SB',  pl.SB,        batPct('SB')],
      ['R',   pl.R,         batPct('R')],
      ['SO',  pl.SO,        batPct('SO', true)],
    ].map(([l,v,b])=>`<div class="sg-cell"><div class="l">${l}</div><div class="v">${v}${b||''}</div></div>`).join('')}</div>`;
  };
  render(slA,'slotA','slotAc'); render(slB,'slotB','slotBc');

  // League avg card
  const lgc = $('slotLgc');
  if(lgc && lgAvg.AVG) {
    lgc.innerHTML = `<div class="slot-name" style="color:#666;font-size:13px">Division 5</div><div class="slot-team">${lgAvg._n} qualified batters</div>
    <div class="sg">${[['AVG',f3(lgAvg.AVG)],['OBP',f3(lgAvg.OBP)],['SLG',f3(lgAvg.SLG)],['OPS',f3(lgAvg.OPS)],['RBI',lgAvg.RBI.toFixed(1)],['HR',lgAvg.HR.toFixed(2)],['SB',lgAvg.SB.toFixed(1)],['R',lgAvg.R.toFixed(1)],['AB',lgAvg.AB.toFixed(1)]].map(([l,v])=>`<div class="sg-cell"><div class="l">${l}</div><div class="v" style="color:#888">${v}</div></div>`).join('')}</div>`;
  }

  if(!slA||!slB){ $('barsec').style.display='none'; return; }
  $('barsec').style.display='block';
  $('legA').textContent = slA.Name+' ('+slA.Team+')';
  $('legB').textContent = slB.Name+' ('+slB.Team+')';
  const f1 = v => parseFloat(v).toFixed(1);
  const stats = [
    {l:'AVG',  a:flt(slA.AVG), b:flt(slB.AVG), lg:lgAvg.AVG, f:f3},
    {l:'OBP',  a:flt(slA.OBP), b:flt(slB.OBP), lg:lgAvg.OBP, f:f3},
    {l:'SLG',  a:flt(slA.SLG), b:flt(slB.SLG), lg:lgAvg.SLG, f:f3},
    {l:'OPS',  a:flt(slA.OPS), b:flt(slB.OPS), lg:lgAvg.OPS, f:f3, sc:2},
    {l:'H',    a:flt(slA.H),   b:flt(slB.H),   lg:lgAvg.H,   f:v=>Math.round(v)},
    {l:'HR',   a:flt(slA.HR),  b:flt(slB.HR),  lg:lgAvg.HR,  f:v=>Math.round(v)},
    {l:'RBI',  a:flt(slA.RBI), b:flt(slB.RBI), lg:lgAvg.RBI, f:v=>Math.round(v)},
    {l:'R',    a:flt(slA.R),   b:flt(slB.R),   lg:lgAvg.R,   f:v=>Math.round(v)},
    {l:'SB',   a:flt(slA.SB),  b:flt(slB.SB),  lg:lgAvg.SB,  f:v=>Math.round(v)},
    {l:'BB',   a:flt(slA.BB),  b:flt(slB.BB),  lg:lgAvg.BB,  f:v=>Math.round(v)},
    {l:'SO',   a:flt(slA.SO),  b:flt(slB.SO),  lg:lgAvg.SO,  f:v=>Math.round(v), low:true},
  ];
  $('barcont').innerHTML = stats.map(s => {
    const mx = s.sc || Math.max(s.a, s.b, s.lg||0, 0.001);
    const pA = Math.round(s.a/mx*100), pB = Math.round(s.b/mx*100);
    const pLg = s.lg ? Math.round(s.lg/mx*100) : null;
    const aw = s.low ? s.a<s.b : s.a>s.b;
    const bw = s.low ? s.b<s.a : s.b>s.a;
    const aValCls = aw ? ' w' : (bw ? ' wbad' : '');
    const bValCls = bw ? ' w' : (aw ? ' wbad' : '');
    const barColA = s.low ? '#f97316' : '#3b82f6';
    const barColB = s.low ? '#3b82f6' : '#f97316';
    const lgMarker = pLg !== null ? `<div class="lavg-marker" style="left:${pLg}%"></div>` : '';
    return `<div class="brow">
      <div style="display:flex;align-items:center;gap:4px">
        <span class="bv${aValCls}" style="text-align:right;min-width:38px">${s.f(s.a)}</span>
        <div class="bwrap bleft" style="flex:1;position:relative"><div class="bf" style="width:${pA}%;background:${barColA}"></div>${lgMarker}</div>
      </div>
      <div class="blbl">${s.l}${pLg!==null?`<br><span style="color:#aaa;font-weight:400">${typeof s.lg==='number'?s.f(s.lg):''}</span>`:''}</div>
      <div style="display:flex;align-items:center;gap:4px">
        <div class="bwrap bright" style="flex:1;position:relative"><div class="bf" style="width:${pB}%;background:${barColB}"></div>${lgMarker}</div>
        <span class="bv${bValCls}" style="min-width:38px">${s.f(s.b)}</span>
      </div>
    </div>`;
  }).join('');
}

function cpg(d){ cPg=Math.max(0,cPg+d); rCmp(); }
function rCmp(){
  const q=$('csrch').value.toLowerCase(), tm=$('cteam').value, srt=$('csort').value;
  const fil = BAT.filter(p=>flt(p.AB)>=3&&(!tm||p.Team===tm)&&(!q||p.Name.toLowerCase().includes(q)))
                 .sort((a,b)=>flt(b[srt])-flt(a[srt]));
  const s=cPg*20, e=s+20;
  $('cpgi').textContent = `${fil.length?s+1:0}–${Math.min(e,fil.length)} of ${fil.length}`;
  $('cbody').innerHTML = fil.slice(s,e).map(p=>`<tr>
    <td><span class="pn">${p.Name}</span></td>
    <td><span class="tm">${p.Team}</span></td>
    <td>${p.AB}</td>
    <td class="hl">${f3(p.AVG)}</td><td>${f3(p.OBP)}</td><td>${f3(p.SLG)}</td><td>${f3(p.OPS)}</td>
    <td>${p.RBI}</td><td>${p.SB}</td><td>${p.HR}</td>
    <td><button class="addbtn" onclick='addCmp(${JSON.stringify({Name:p.Name,Team:p.Team,AVG:p.AVG,OBP:p.OBP,SLG:p.SLG,OPS:p.OPS,H:p.H,HR:p.HR,RBI:p.RBI,R:p.R,SB:p.SB,BB:p.BB,SO:p.SO,AB:p.AB})})'>+ Add</button></td>
  </tr>`).join('');
}

// ── Team compare ──
function togTeam(name){
  if(selTeams.includes(name)) selTeams=selTeams.filter(t=>t!==name);
  else if(selTeams.length<4) selTeams.push(name);
  rTSel(); rTCmp(); rTGrid();
}

function rTSel(){
  const el=$('tsel');
  if(!selTeams.length){ el.innerHTML='<span style="font-size:12px;color:#bbb">Click a team card below to start comparing</span>'; return; }
  el.innerHTML = selTeams.map((t,i)=>`<div class="tpill" style="background:${TC[i]}22;color:${TC[i]}">
    <span style="width:7px;height:7px;border-radius:50%;background:${TC[i]};display:inline-block"></span>${t}
    <button onclick="togTeam('${t}')" style="color:${TC[i]}">×</button>
  </div>`).join('') + (selTeams.length<4?`<span style="font-size:11px;color:#bbb">+ up to ${4-selTeams.length} more</span>`:'');
}

function rTCmp(){
  const el=$('tcout');
  if(selTeams.length<2){ el.innerHTML=''; return; }
  const tms = selTeams.map(name => TBAT.find(t=>t.Name===name)).filter(Boolean);
  const stats=[
    {l:'Batting AVG', k:'AVG', f:f3},
    {l:'On-base %',   k:'OBP', f:f3},
    {l:'Slugging %',  k:'SLG', f:f3},
    {l:'OPS',         k:'OPS', f:f3, sc:2},
    {l:'Runs scored', k:'R',   f:v=>v},
    {l:'Home runs',   k:'HR',  f:v=>v},
    {l:'Stolen bases',k:'SB',  f:v=>v},
    {l:'RBI',         k:'RBI', f:v=>v},
  ];
  el.innerHTML=`<div class="tc-out">${stats.map(s=>{
    const vals=tms.map(t=>flt(t[s.k]));
    const mx=s.sc||Math.max(...vals,0.001);
    return `<div style="margin-bottom:11px">
      <div class="tstat-lbl">${s.l}</div>
      ${tms.map((t,i)=>{
        const pct=Math.round(vals[i]/mx*100);
        const best=vals[i]===Math.max(...vals);
        return `<div class="tbr">
          <span class="tbn" style="color:${TC[i]}">${t.Name}</span>
          <div class="tbb"><div class="tbf" style="width:${pct}%;background:${TC[i]}"></div></div>
          <span class="tbv${best?' w':''}">${s.f(vals[i])}</span>
        </div>`;}).join('')}
    </div>`;}).join('')}</div>`;
}

function rTGrid(){
  $('tgrid').innerHTML = TBAT.map(t=>{
    const idx=selTeams.indexOf(t.Name), sel=idx>=0;
    return `<div class="tcard${sel?' sel':''}" style="${sel?'border-color:'+TC[idx]+';border-width:2px':''}" onclick="togTeam('${t.Name}')">
      <div class="tn">${t.Name}</div>
      <div class="ts">AVG ${f3(t.AVG)} · OPS ${f3(t.OPS)}<br>${t.G} G · ${t.R} R · ${t.HR} HR · ${t.SB} SB</div>
      <div class="tbtn" style="${sel?'background:'+TC[idx]+'22;color:'+TC[idx]+';border-color:'+TC[idx]:''}">
        ${sel?'✓ Selected':'+ Compare'}
      </div>
    </div>`;
  }).join('');
}

// ── Compare pitchers ──
let pslA=null, pslB=null, pcPg=0;

function addPCmp(pl){
  if(!pslA){ pslA=pl; }
  else if(!pslB && pl.Name!==pslA.Name){ pslB=pl; }
  else if(pl.Name===pslA?.Name || pl.Name===pslB?.Name){ return; }
  else { pslA=pslB; pslB=pl; }
  rPSlots();
}
function pclr(s){ if(s==='a') pslA=null; else pslB=null; rPSlots(); }

function rPSlots(){
  const render = (pl, sid, cid) => {
    const slot=$(sid), cont=$(cid);
    if(!pl){ cont.innerHTML='<div class="empty-msg">No pitcher selected</div>'; slot.classList.remove('filled'); return; }
    slot.classList.add('filled');
    const pitPct = (field, low=false) => pctBadge(pctRank(pl[field], PIT.map(p=>p[field]), low));
    cont.innerHTML = `<div class="slot-name">${pl.Name}</div><div class="slot-team">${pl.Team}</div>
    <div class="sg">${[
      ['ERA',  f2(pl.ERA),   pitPct('ERA',  true)],
      ['WHIP', f2(pl.WHIP),  pitPct('WHIP', true)],
      ['K',    pl.SO,        pitPct('SO')],
      ['IP',   pl.IP,        pitPct('IP')],
      ['W',    pl.W,         pitPct('W')],
      ['BB',   pl.BB,        pitPct('BB',   true)],
      ['SV',   pl.SV,        pitPct('SV')],
      ['ER',   pl.ER,        pitPct('ER',   true)],
      ['BAA',  f3(pl.BAA),   pitPct('BAA',  true)],
    ].map(([l,v,b])=>`<div class="sg-cell"><div class="l">${l}</div><div class="v">${v}${b||''}</div></div>`).join('')}</div>`;
  };
  render(pslA,'pslotA','pslotAc'); render(pslB,'pslotB','pslotBc');

  // League avg pitcher card
  const lgc = $('pslotLgc');
  if(lgc && lgPitAvg.ERA) {
    lgc.innerHTML = `<div class="slot-name" style="color:#666;font-size:13px">Division 5</div><div class="slot-team">${lgPitAvg._n} pitchers</div>
    <div class="sg">${[['ERA',f2(lgPitAvg.ERA)],['WHIP',f2(lgPitAvg.WHIP)],['K',lgPitAvg.SO.toFixed(1)],['IP',lgPitAvg.IP.toFixed(1)],['W',lgPitAvg.W.toFixed(1)],['BB',lgPitAvg.BB.toFixed(1)],['SV',lgPitAvg.SV.toFixed(1)],['ER',lgPitAvg.ER.toFixed(1)],['BAA',f3(lgPitAvg.BAA)]].map(([l,v])=>`<div class="sg-cell"><div class="l">${l}</div><div class="v" style="color:#888">${v}</div></div>`).join('')}</div>`;
  }

  if(!pslA||!pslB){ $('pbarsec').style.display='none'; return; }
  $('pbarsec').style.display='block';
  $('plegA').textContent = pslA.Name+' ('+pslA.Team+')';
  $('plegB').textContent = pslB.Name+' ('+pslB.Team+')';
  const stats = [
    {l:'ERA',  a:flt(pslA.ERA),  b:flt(pslB.ERA),  lg:lgPitAvg.ERA,  f:f2,  low:true},
    {l:'WHIP', a:flt(pslA.WHIP), b:flt(pslB.WHIP), lg:lgPitAvg.WHIP, f:f2,  low:true},
    {l:'BAA',  a:flt(pslA.BAA),  b:flt(pslB.BAA),  lg:lgPitAvg.BAA,  f:f3,  low:true},
    {l:'K',    a:flt(pslA.SO),   b:flt(pslB.SO),   lg:lgPitAvg.SO,   f:v=>Math.round(v)},
    {l:'IP',   a:flt(pslA.IP),   b:flt(pslB.IP),   lg:lgPitAvg.IP,   f:v=>parseFloat(v).toFixed(1)},
    {l:'W',    a:flt(pslA.W),    b:flt(pslB.W),    lg:lgPitAvg.W,    f:v=>Math.round(v)},
    {l:'SV',   a:flt(pslA.SV),   b:flt(pslB.SV),   lg:lgPitAvg.SV,   f:v=>Math.round(v)},
    {l:'BB',   a:flt(pslA.BB),   b:flt(pslB.BB),   lg:lgPitAvg.BB,   f:v=>Math.round(v), low:true},
    {l:'ER',   a:flt(pslA.ER),   b:flt(pslB.ER),   lg:lgPitAvg.ER,   f:v=>Math.round(v), low:true},
    {l:'H',    a:flt(pslA.H),    b:flt(pslB.H),    lg:lgPitAvg.H,    f:v=>Math.round(v), low:true},
  ];
  $('pbarcont').innerHTML = stats.map(s => {
    const mx = s.sc || Math.max(s.a, s.b, s.lg||0, 0.001);
    const pA = Math.round(s.a/mx*100), pB = Math.round(s.b/mx*100);
    const pLg = s.lg ? Math.round(s.lg/mx*100) : null;
    const aw = s.low ? s.a<s.b : s.a>s.b;
    const bw = s.low ? s.b<s.a : s.b>s.a;
    const aValCls = aw ? ' w' : (bw ? ' wbad' : '');
    const bValCls = bw ? ' w' : (aw ? ' wbad' : '');
    const barColA = s.low ? '#f97316' : '#3b82f6';
    const barColB = s.low ? '#3b82f6' : '#f97316';
    const lgMarker = pLg !== null ? `<div class="lavg-marker" style="left:${pLg}%"></div>` : '';
    return `<div class="brow">
      <div style="display:flex;align-items:center;gap:4px">
        <span class="bv${aValCls}" style="text-align:right;min-width:38px">${s.f(s.a)}</span>
        <div class="bwrap bleft" style="flex:1;position:relative"><div class="bf" style="width:${pA}%;background:${barColA}"></div>${lgMarker}</div>
      </div>
      <div class="blbl">${s.l}${pLg!==null?`<br><span style="color:#aaa;font-weight:400">${s.f(s.lg)}</span>`:''}</div>
      <div style="display:flex;align-items:center;gap:4px">
        <div class="bwrap bright" style="flex:1;position:relative"><div class="bf" style="width:${pB}%;background:${barColB}"></div>${lgMarker}</div>
        <span class="bv${bValCls}" style="min-width:38px">${s.f(s.b)}</span>
      </div>
    </div>`;
  }).join('');
}
function pcpg(d){ pcPg=Math.max(0,pcPg+d); rPCmp(); }
function rPCmp(){
  const q=$('pcsrch').value.toLowerCase(), tm=$('pcteam').value, srt=$('pcsort').value;
  const asc = srt==='ERA'||srt==='WHIP';
  const fil = PIT.filter(p=>(!tm||p.Team===tm)&&(!q||p.Name.toLowerCase().includes(q)))
                 .sort((a,b)=>asc?flt(a[srt])-flt(b[srt]):flt(b[srt])-flt(a[srt]));
  const s=pcPg*20, e=s+20;
  $('pcpgi').textContent = `${fil.length?s+1:0}–${Math.min(e,fil.length)} of ${fil.length}`;
  $('pcbody').innerHTML = fil.slice(s,e).map(p=>`<tr>
    <td><span class="pn">${p.Name}</span></td>
    <td><span class="tm">${p.Team}</span></td>
    <td>${p.APP}</td><td>${p.W}</td><td>${p.L}</td><td>${p.SV}</td>
    <td>${p.IP}</td><td>${p.SO}</td><td>${p.BB}</td>
    <td class="hl">${f2(p.ERA)}</td><td>${f2(p.WHIP)}</td><td>${f3(p.BAA)}</td>
    <td><button class="addbtn" onclick='addPCmp(${JSON.stringify({Name:p.Name,Team:p.Team,ERA:p.ERA,WHIP:p.WHIP,BAA:p.BAA,SO:p.SO,IP:p.IP,W:p.W,L:p.L,SV:p.SV,BB:p.BB,ER:p.ER,H:p.H,APP:p.APP})});show("pcmp")'>+ Compare</button></td>
  </tr>`).join('');
}

// ── League averages tab ──
function rLAvg() {
  if(!lgAvg.AVG) return;

  // Batting avg card
  const batStats = [
    ['Batting AVG',        f3(lgAvg.AVG)],
    ['On-base %',          f3(lgAvg.OBP)],
    ['Slugging %',         f3(lgAvg.SLG)],
    ['OPS',                f3(lgAvg.OPS)],
    ['Hits (avg)',         lgAvg.H.toFixed(1)],
    ['Home runs (avg)',    lgAvg.HR.toFixed(2)],
    ['RBI (avg)',          lgAvg.RBI.toFixed(1)],
    ['Runs (avg)',         lgAvg.R.toFixed(1)],
    ['Stolen bases (avg)', lgAvg.SB.toFixed(1)],
    ['Walks (avg)',        lgAvg.BB.toFixed(1)],
    ['Strikeouts (avg)',   lgAvg.SO.toFixed(1)],
    ['At bats (avg)',      lgAvg.AB.toFixed(1)],
  ];
  $('lavg-bat').innerHTML = `<div style="font-size:11px;color:#aaa;margin-bottom:8px">Based on ${lgAvg._n} qualified batters (min 10 AB)</div>` +
    batStats.map(([l,v]) => `<div class="lavg-row"><span class="lavg-label">${l}</span><span class="lavg-val">${v}</span></div>`).join('');

  // Pitching avg card
  const pitStats = [
    ['ERA',           f2(lgPitAvg.ERA)],
    ['WHIP',          f2(lgPitAvg.WHIP)],
    ['Bat avg against', f3(lgPitAvg.BAA)],
    ['Strikeouts (avg)', lgPitAvg.SO.toFixed(1)],
    ['Innings pitched (avg)', lgPitAvg.IP.toFixed(1)],
    ['Walks (avg)',   lgPitAvg.BB.toFixed(1)],
    ['Wins (avg)',    lgPitAvg.W.toFixed(2)],
    ['Saves (avg)',   lgPitAvg.SV.toFixed(2)],
    ['Earned runs (avg)', lgPitAvg.ER.toFixed(1)],
    ['Hits allowed (avg)', lgPitAvg.H.toFixed(1)],
  ];
  $('lavg-pit').innerHTML = `<div style="font-size:11px;color:#aaa;margin-bottom:8px">Based on ${lgPitAvg._n} pitchers</div>` +
    pitStats.map(([l,v]) => `<div class="lavg-row"><span class="lavg-label">${l}</span><span class="lavg-val">${v}</span></div>`).join('');

  // Team batting vs league avg
  const lgAVG = lgAvg.AVG, lgOPS = lgAvg.OPS;
  const maxAVG = Math.max(...TBAT.map(t=>flt(t.AVG)), lgAVG) * 1.1;
  $('lavg-teams').innerHTML = `
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:1.5rem">
      <div>
        <div class="tstat-lbl" style="margin-bottom:8px">Team AVG vs league avg (${f3(lgAVG)})</div>
        ${TBAT.sort((a,b)=>flt(b.AVG)-flt(a.AVG)).map(t => {
          const val = flt(t.AVG), pct = Math.round(val/maxAVG*100);
          const lgPct = Math.round(lgAVG/maxAVG*100);
          const above = val >= lgAVG;
          return `<div class="lavg-team-row">
            <span class="lavg-team-name">${t.Name}</span>
            <div class="lavg-bar-bg">
              <div class="lavg-bar-fill" style="width:${pct}%;background:${above?'#16a34a':'#dc2626'}88"></div>
              <div class="lavg-marker" style="left:${lgPct}%"></div>
            </div>
            <span class="lavg-team-val ${above?'above':'below'}">${f3(val)}</span>
          </div>`;}).join('')}
      </div>
      <div>
        <div class="tstat-lbl" style="margin-bottom:8px">Team OPS vs league avg (${f3(lgOPS)})</div>
        ${TBAT.sort((a,b)=>flt(b.OPS)-flt(a.OPS)).map(t => {
          const val = flt(t.OPS);
          const maxOPS = Math.max(...TBAT.map(t=>flt(t.OPS)), lgOPS) * 1.1;
          const pct = Math.round(val/maxOPS*100);
          const lgPct = Math.round(lgOPS/maxOPS*100);
          const above = val >= lgOPS;
          return `<div class="lavg-team-row">
            <span class="lavg-team-name">${t.Name}</span>
            <div class="lavg-bar-bg">
              <div class="lavg-bar-fill" style="width:${pct}%;background:${above?'#16a34a':'#dc2626'}88"></div>
              <div class="lavg-marker" style="left:${lgPct}%"></div>
            </div>
            <span class="lavg-team-val ${above?'above':'below'}">${f3(val)}</span>
          </div>`;}).join('')}
      </div>
    </div>`;
}

// ── Player card modal ──
function closeModal() { $('modal').style.display='none'; document.body.style.overflow=''; }
document.addEventListener('keydown', e => { if(e.key==='Escape') closeModal(); });

function openBatCard(p) {
  const qual = BAT.filter(x=>flt(x.AB)>=10);
  const bp = (field, low=false) => pctBadge(pctRank(p[field], qual.map(x=>x[field]), low));
  $('modal-name').textContent = p.Name;
  $('modal-team').innerHTML = `<span class="tm">${p.Team}</span><span style="color:#ccc">·</span><span>${p.G} games · ${p.AB} AB</span>`;
  $('modal-body').innerHTML = `
    <div class="modal-section">Batting rate stats</div>
    <div class="modal-grid">
      ${[['AVG',f3(p.AVG),bp('AVG')],['OBP',f3(p.OBP),bp('OBP')],['SLG',f3(p.SLG),bp('SLG')],['OPS',f3(p.OPS),bp('OPS')]].map(([l,v,b])=>`
        <div class="modal-stat"><div class="modal-stat-label">${l}</div><div class="modal-stat-val">${v}${b}</div></div>`).join('')}
    </div>
    <div class="modal-section">Counting stats</div>
    <div class="modal-grid">
      ${[['H',p.H,bp('H')],['2B',p['2B'],''],['3B',p['3B'],''],['HR',p.HR,bp('HR')],['RBI',p.RBI,bp('RBI')],['R',p.R,bp('R')],['SB',p.SB,bp('SB')],['BB',p.BB,bp('BB')],['SO',p.SO,bp('SO',true)]].map(([l,v,b])=>`
        <div class="modal-stat"><div class="modal-stat-label">${l}</div><div class="modal-stat-val">${v}${b}</div></div>`).join('')}
    </div>`;
  $('modal-actions').innerHTML = `
    <button class="modal-btn modal-btn-cmp" onclick='addCmp(${JSON.stringify({Name:p.Name,Team:p.Team,AVG:p.AVG,OBP:p.OBP,SLG:p.SLG,OPS:p.OPS,H:p.H,HR:p.HR,RBI:p.RBI,R:p.R,SB:p.SB,BB:p.BB,SO:p.SO,AB:p.AB})});show("cmp");closeModal()'>+ Add to compare</button>
    <button class="modal-btn" style="background:#f9f9f7;color:#666;border-color:#e5e5e5" onclick="closeModal()">Close</button>`;
  $('modal').style.display='flex';
  document.body.style.overflow='hidden';
}

function openPitCard(p) {
  const pp = (field, low=false) => pctBadge(pctRank(p[field], PIT.map(x=>x[field]), low));
  $('modal-name').textContent = p.Name;
  $('modal-team').innerHTML = `<span class="tm">${p.Team}</span><span style="color:#ccc">·</span><span>${p.APP} appearances · ${p.IP} IP</span>`;
  $('modal-body').innerHTML = `
    <div class="modal-section">Key pitching stats</div>
    <div class="modal-grid">
      ${[['ERA',f2(p.ERA),pp('ERA',true)],['WHIP',f2(p.WHIP),pp('WHIP',true)],['BAA',f3(p.BAA),pp('BAA',true)]].map(([l,v,b])=>`
        <div class="modal-stat"><div class="modal-stat-label">${l}</div><div class="modal-stat-val">${v}${b}</div></div>`).join('')}
    </div>
    <div class="modal-section">Counting stats</div>
    <div class="modal-grid">
      ${[['W',p.W,pp('W')],['L',p.L,''],['SV',p.SV,pp('SV')],['K',p.SO,pp('SO')],['BB',p.BB,pp('BB',true)],['H',p.H,pp('H',true)],['ER',p.ER,pp('ER',true)],['GS',p.GS,''],['CG',p.CG||0,'']].map(([l,v,b])=>`
        <div class="modal-stat"><div class="modal-stat-label">${l}</div><div class="modal-stat-val">${v}${b}</div></div>`).join('')}
    </div>`;
  $('modal-actions').innerHTML = `
    <button class="modal-btn modal-btn-cmp" onclick='addPCmp(${JSON.stringify({Name:p.Name,Team:p.Team,ERA:p.ERA,WHIP:p.WHIP,BAA:p.BAA,SO:p.SO,IP:p.IP,W:p.W,L:p.L,SV:p.SV,BB:p.BB,ER:p.ER,H:p.H,APP:p.APP})});show("pcmp");closeModal()'>+ Add to compare</button>
    <button class="modal-btn" style="background:#f9f9f7;color:#666;border-color:#e5e5e5" onclick="closeModal()">Close</button>`;
  $('modal').style.display='flex';
  document.body.style.overflow='hidden';
}

loadAll();
</script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, viewport-fit=cover">
<title>Bloom</title>
<meta name="description" content="A calm, minimal habit tracker.">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Bloom">
<meta name="theme-color" content="#F7F7F5" id="theme-color-meta">
<link rel="apple-touch-icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='22' fill='%233F6653'/%3E%3Ccircle cx='50' cy='38' r='15' fill='%23EFEAE0'/%3E%3Cpath d='M50 50 C50 68 40 78 40 78 C40 78 60 78 60 78 C60 78 50 68 50 50Z' fill='%23EFEAE0'/%3E%3C/svg%3E">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='22' fill='%233F6653'/%3E%3Ccircle cx='50' cy='38' r='15' fill='%23EFEAE0'/%3E%3Cpath d='M50 50 C50 68 40 78 40 78 C40 78 60 78 60 78 C60 78 50 68 50 50Z' fill='%23EFEAE0'/%3E%3C/svg%3E">
<link rel="manifest" href='data:application/manifest+json,{"name":"Bloom","short_name":"Bloom","start_url":".","display":"standalone","background_color":"%23F7F7F5","theme_color":"%23F7F7F5","icons":[]}'>
<style>
:root{
  --bg:#F7F7F5;
  --surface:#FFFFFF;
  --surface2:#F0F0EE;
  --text:#1D1D1F;
  --text-secondary:rgba(29,29,31,0.55);
  --border:rgba(29,29,31,0.10);
  --button:#3F6653;
  --button-text:#FFFFFF;
  --danger:#D64545;
  --shadow:0 1px 2px rgba(0,0,0,0.04), 0 4px 16px rgba(0,0,0,0.04);
  --radius-l:20px;
  --radius-m:14px;
  --radius-s:10px;
  --safe-top:env(safe-area-inset-top);
  --safe-bottom:env(safe-area-inset-bottom);
}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent;}
html,body{height:100%;}
body{
  margin:0;
  font-family:-apple-system,BlinkMacSystemFont,"SF Pro Text","SF Pro Display","Segoe UI",Roboto,Helvetica,Arial,sans-serif;
  background:var(--bg);
  color:var(--text);
  -webkit-font-smoothing:antialiased;
  overscroll-behavior-y:none;
  transition:background-color .25s ease,color .25s ease;
}
button{font-family:inherit;}
input,select,textarea{font-family:inherit;}
.app{
  max-width:560px;
  margin:0 auto;
  min-height:100vh;
  display:flex;
  flex-direction:column;
  position:relative;
}
.view{display:none;flex:1;padding-bottom:calc(84px + var(--safe-bottom));}
.view.active{display:block;}
.screen-pad{padding:0 20px;}

/* ---------- HEADER ---------- */
.page-header{
  padding:calc(18px + var(--safe-top)) 20px 8px;
}
.page-header h1{
  font-size:34px;
  font-weight:750;
  letter-spacing:-0.02em;
  margin:0 0 2px;
}
.page-header .subtitle{
  font-size:15px;
  color:var(--text-secondary);
  margin:0;
}
.progress-row{
  display:flex;
  align-items:center;
  gap:10px;
  margin-top:16px;
}
.progress-track{
  flex:1;
  height:8px;
  border-radius:5px;
  background:var(--surface2);
  overflow:hidden;
}
.progress-fill{
  height:100%;
  border-radius:5px;
  background:var(--button);
  transition:width .35s cubic-bezier(.4,0,.2,1);
}
.progress-label{
  font-size:14px;
  font-weight:600;
  color:var(--text-secondary);
  white-space:nowrap;
}

/* ---------- HABIT LIST ---------- */
.habit-list{padding:14px 20px 8px;display:flex;flex-direction:column;gap:10px;}
.habit-card{
  background:var(--surface);
  border:1px solid var(--border);
  border-radius:var(--radius-m);
  padding:14px;
  display:flex;
  align-items:center;
  gap:12px;
  box-shadow:var(--shadow);
  position:relative;
  transition:transform .15s ease, opacity .2s ease;
}
.habit-card.dragging{opacity:.5;}
.habit-icon{
  width:42px;height:42px;min-width:42px;
  border-radius:12px;
  display:flex;align-items:center;justify-content:center;
  background:var(--icon-bg,var(--surface2));
}
.habit-icon svg{width:22px;height:22px;stroke:var(--icon-color,var(--text));}
.habit-info{flex:1;min-width:0;}
.habit-name{font-size:16px;font-weight:600;margin:0;line-height:1.25;}
.habit-name.done{color:var(--text-secondary);}
.habit-desc{font-size:13px;color:var(--text-secondary);margin:1px 0 0;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}
.habit-meta{display:flex;align-items:center;gap:6px;margin-top:4px;}
.streak-chip{
  font-size:12px;font-weight:600;color:var(--text-secondary);
  display:flex;align-items:center;gap:3px;
}
.streak-chip svg{width:12px;height:12px;stroke:var(--text-secondary);}
.streak-chip.active{color:var(--button);}
.streak-chip.active svg{stroke:var(--button);}
.check-btn{
  width:32px;height:32px;min-width:32px;
  border-radius:50%;
  border:2px solid var(--border);
  background:transparent;
  display:flex;align-items:center;justify-content:center;
  padding:0;
  cursor:pointer;
  transition:background-color .18s ease, border-color .18s ease, transform .15s cubic-bezier(.34,1.56,.64,1);
}
.check-btn svg{width:16px;height:16px;stroke:#fff;opacity:0;transform:scale(.5);transition:opacity .15s ease, transform .15s cubic-bezier(.34,1.56,.64,1);}
.check-btn.checked{background:var(--button);border-color:var(--button);transform:scale(1.06);}
.check-btn.checked svg{opacity:1;transform:scale(1);}
.check-btn.checked{animation:pop .28s ease;}
@keyframes pop{0%{transform:scale(.85);}55%{transform:scale(1.14);}100%{transform:scale(1.06);}}
.habit-card .drag-handle{padding:4px;color:var(--text-secondary);opacity:.5;touch-action:none;}
.habit-card .drag-handle svg{width:18px;height:18px;stroke:currentColor;}

.empty-state{
  text-align:center;
  padding:60px 30px 20px;
  color:var(--text-secondary);
}
.empty-state svg{width:52px;height:52px;stroke:var(--text-secondary);margin-bottom:14px;opacity:.55;}
.empty-state h3{font-size:17px;color:var(--text);margin:0 0 6px;}
.empty-state p{font-size:14px;margin:0;line-height:1.5;}

.section-label{
  font-size:13px;
  font-weight:700;
  text-transform:uppercase;
  letter-spacing:.04em;
  color:var(--text-secondary);
  padding:22px 20px 8px;
}

/* ---------- IDEAS ---------- */
.ideas-entry{
  margin:6px 20px 4px;
  display:flex;align-items:center;justify-content:space-between;
  background:var(--surface);
  border:1px solid var(--border);
  border-radius:var(--radius-m);
  padding:14px 16px;
  cursor:pointer;
  box-shadow:var(--shadow);
}
.ideas-entry .l{display:flex;align-items:center;gap:12px;}
.ideas-entry .l svg{width:20px;height:20px;stroke:var(--button);}
.ideas-entry span{font-size:15px;font-weight:600;}
.ideas-entry .chev{stroke:var(--text-secondary);width:16px;height:16px;}

/* ---------- FAB ---------- */
.fab{
  position:fixed;
  right:calc(50% - 260px + 20px);
  bottom:calc(96px + var(--safe-bottom));
  width:58px;height:58px;
  border-radius:50%;
  background:var(--button);
  color:var(--button-text);
  border:none;
  display:flex;align-items:center;justify-content:center;
  box-shadow:0 6px 18px rgba(0,0,0,.18);
  cursor:pointer;
  z-index:40;
  transition:transform .15s ease;
}
.fab:active{transform:scale(.92);}
.fab svg{width:26px;height:26px;stroke:var(--button-text);}
@media (max-width:600px){.fab{right:20px;}}

/* ---------- BOTTOM NAV ---------- */
.bottom-nav{
  position:fixed;
  left:0;right:0;bottom:0;
  max-width:560px;
  margin:0 auto;
  background:var(--surface);
  border-top:1px solid var(--border);
  display:flex;
  padding:8px 6px calc(8px + var(--safe-bottom));
  z-index:30;
}
.nav-btn{
  flex:1;
  background:none;border:none;
  display:flex;flex-direction:column;align-items:center;gap:3px;
  padding:6px 2px;
  color:var(--text-secondary);
  cursor:pointer;
}
.nav-btn svg{width:24px;height:24px;stroke:var(--text-secondary);transition:stroke .2s ease;}
.nav-btn span{font-size:11px;font-weight:600;}
.nav-btn.active{color:var(--text);}
.nav-btn.active svg{stroke:var(--button);}
.nav-btn.active span{color:var(--text);}

/* ---------- SHEETS / MODALS ---------- */
.overlay{
  position:fixed;inset:0;
  background:rgba(0,0,0,.35);
  z-index:100;
  opacity:0;
  pointer-events:none;
  transition:opacity .22s ease;
}
.overlay.open{opacity:1;pointer-events:auto;}
.sheet{
  position:fixed;
  left:0;right:0;bottom:0;
  max-width:560px;margin:0 auto;
  background:var(--bg);
  border-radius:22px 22px 0 0;
  max-height:88vh;
  display:flex;flex-direction:column;
  transform:translateY(100%);
  transition:transform .3s cubic-bezier(.32,.72,0,1);
  z-index:101;
  box-shadow:0 -8px 30px rgba(0,0,0,.15);
}
.overlay.open .sheet{transform:translateY(0);}
.sheet-handle{width:36px;height:5px;border-radius:3px;background:var(--border);margin:10px auto 2px;}
.sheet-header{
  display:flex;align-items:center;justify-content:space-between;
  padding:10px 18px 14px;
  border-bottom:1px solid var(--border);
}
.sheet-header h2{font-size:17px;font-weight:700;margin:0;}
.sheet-btn{
  background:none;border:none;font-size:16px;color:var(--button);font-weight:600;cursor:pointer;padding:6px 2px;
}
.sheet-btn.muted{color:var(--text-secondary);font-weight:500;}
.sheet-body{overflow-y:auto;padding:14px 18px calc(24px + var(--safe-bottom));-webkit-overflow-scrolling:touch;}

/* form elements */
.field-group{margin-bottom:18px;}
.field-label{font-size:13px;font-weight:700;color:var(--text-secondary);text-transform:uppercase;letter-spacing:.03em;margin-bottom:8px;display:block;}
.text-input{
  width:100%;
  background:var(--surface);
  border:1px solid var(--border);
  border-radius:var(--radius-s);
  padding:13px 14px;
  font-size:16px;
  color:var(--text);
  outline:none;
}
.text-input:focus{border-color:var(--button);}
textarea.text-input{resize:none;min-height:44px;}
.icon-grid{display:grid;grid-template-columns:repeat(6,1fr);gap:8px;}
.icon-opt{
  aspect-ratio:1;border-radius:12px;border:2px solid transparent;background:var(--surface);
  display:flex;align-items:center;justify-content:center;cursor:pointer;
}
.icon-opt svg{width:20px;height:20px;stroke:var(--text);}
.icon-opt.sel{border-color:var(--button);background:var(--surface2);}
.color-row{display:flex;flex-wrap:wrap;gap:10px;}
.color-dot{
  width:34px;height:34px;border-radius:50%;cursor:pointer;border:2px solid transparent;position:relative;flex-shrink:0;
}
.color-dot.sel{border-color:var(--text);}
.color-dot.sel::after{content:'';position:absolute;inset:5px;border-radius:50%;border:2px solid var(--bg);}
.seg-control{display:flex;background:var(--surface2);border-radius:var(--radius-s);padding:3px;gap:2px;}
.seg-opt{
  flex:1;text-align:center;padding:9px 4px;border-radius:8px;font-size:14px;font-weight:600;color:var(--text-secondary);
  cursor:pointer;background:none;border:none;
}
.seg-opt.sel{background:var(--surface);color:var(--text);box-shadow:0 1px 3px rgba(0,0,0,.08);}
.day-row{display:flex;gap:6px;justify-content:space-between;}
.day-pill{
  flex:1;aspect-ratio:1;border-radius:50%;border:1px solid var(--border);background:var(--surface);
  display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:600;color:var(--text-secondary);cursor:pointer;
}
.day-pill.sel{background:var(--button);border-color:var(--button);color:var(--button-text);}
.stepper{display:flex;align-items:center;gap:14px;}
.stepper button{
  width:36px;height:36px;border-radius:50%;border:1px solid var(--border);background:var(--surface);color:var(--text);
  font-size:20px;cursor:pointer;display:flex;align-items:center;justify-content:center;
}
.stepper .val{font-size:16px;font-weight:600;min-width:90px;text-align:center;}
.row-between{display:flex;align-items:center;justify-content:space-between;}
.switch{position:relative;width:46px;height:27px;flex-shrink:0;}
.switch input{opacity:0;width:0;height:0;}
.switch .track{position:absolute;inset:0;background:var(--border);border-radius:14px;transition:background .2s;cursor:pointer;}
.switch input:checked + .track{background:var(--button);}
.switch .thumb{position:absolute;top:2px;left:2px;width:23px;height:23px;border-radius:50%;background:#fff;box-shadow:0 1px 3px rgba(0,0,0,.3);transition:transform .2s;pointer-events:none;}
.switch input:checked ~ .thumb{transform:translateX(19px);}
.danger-btn{
  width:100%;background:var(--surface);border:1px solid var(--border);color:var(--danger);
  border-radius:var(--radius-s);padding:14px;font-size:16px;font-weight:600;cursor:pointer;margin-top:8px;
}
.primary-btn{
  width:100%;background:var(--button);color:var(--button-text);border:none;
  border-radius:var(--radius-s);padding:15px;font-size:16px;font-weight:700;cursor:pointer;
}
.primary-btn:disabled{opacity:.45;}

/* Ideas categories */
.idea-cat{margin-bottom:22px;}
.idea-cat h3{font-size:15px;font-weight:750;margin:0 0 10px;}
.idea-item{
  display:flex;align-items:center;gap:12px;
  background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-m);
  padding:12px 12px;margin-bottom:8px;
}
.idea-item .ic{width:38px;height:38px;border-radius:10px;background:var(--surface2);display:flex;align-items:center;justify-content:center;flex-shrink:0;}
.idea-item .ic svg{width:19px;height:19px;stroke:var(--text);}
.idea-item .txt{flex:1;min-width:0;}
.idea-item .txt .n{font-size:14.5px;font-weight:650;}
.idea-item .txt .d{font-size:12.5px;color:var(--text-secondary);margin-top:1px;}
.idea-item .txt .f{font-size:11.5px;color:var(--button);font-weight:600;margin-top:3px;}
.idea-add{
  background:var(--surface2);border:none;border-radius:10px;padding:8px 13px;font-size:13px;font-weight:700;color:var(--text);cursor:pointer;flex-shrink:0;
}
.idea-add.added{background:var(--button);color:var(--button-text);}

/* ---------- STATS ---------- */
.month-nav{display:flex;align-items:center;justify-content:space-between;padding:calc(14px + var(--safe-top)) 20px 6px;}
.month-nav h1{font-size:24px;font-weight:750;margin:0;letter-spacing:-.01em;}
.month-arrow{width:36px;height:36px;border-radius:50%;border:1px solid var(--border);background:var(--surface);display:flex;align-items:center;justify-content:center;cursor:pointer;}
.month-arrow svg{width:17px;height:17px;stroke:var(--text);}
.month-arrow:disabled{opacity:.3;}
.calendar-wrap{padding:10px 20px 0;}
.cal-weekdays{display:grid;grid-template-columns:repeat(7,1fr);text-align:center;margin-bottom:6px;}
.cal-weekdays span{font-size:11px;font-weight:700;color:var(--text-secondary);}
.cal-grid{display:grid;grid-template-columns:repeat(7,1fr);gap:4px;}
.cal-day{
  aspect-ratio:1;border-radius:10px;display:flex;flex-direction:column;align-items:center;justify-content:center;
  cursor:pointer;position:relative;background:var(--surface2);
}
.cal-day.empty{background:transparent;cursor:default;}
.cal-day .num{font-size:12.5px;font-weight:600;}
.cal-day.future{opacity:.35;cursor:default;}
.cal-day.today .num{text-decoration:underline;text-underline-offset:2px;}
.cal-day .dot{width:5px;height:5px;border-radius:50%;background:var(--button);margin-top:2px;position:absolute;bottom:5px;}
.stats-grid{padding:18px 20px 6px;display:grid;grid-template-columns:1fr 1fr;gap:10px;}
.stat-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-m);padding:14px;box-shadow:var(--shadow);}
.stat-card .v{font-size:22px;font-weight:750;letter-spacing:-.01em;}
.stat-card .l{font-size:12.5px;color:var(--text-secondary);margin-top:2px;}
.stat-card.wide{grid-column:1/-1;}
.stat-card .v.small{font-size:16px;}
.bar-chart{padding:16px 20px 4px;}
.bar-chart-inner{display:flex;align-items:flex-end;gap:2px;height:90px;background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-m);padding:12px 10px 8px;box-shadow:var(--shadow);}
.bar{flex:1;background:var(--surface2);border-radius:3px 3px 0 0;min-height:3px;position:relative;}
.bar.filled{background:var(--button);}
.habit-select-wrap{padding:20px 20px 4px;}
.habit-stats-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-l);padding:18px;box-shadow:var(--shadow);}
.habit-stats-card .hsc-head{display:flex;align-items:center;gap:10px;margin-bottom:14px;}
.habit-stats-card .hsc-head .habit-icon{width:36px;height:36px;}
.habit-stats-card .hsc-head .habit-icon svg{width:18px;height:18px;}
.habit-stats-card h3{font-size:17px;font-weight:750;margin:0;}
.hsc-rows{display:grid;grid-template-columns:1fr 1fr;gap:12px;}
.hsc-rows .v{font-size:19px;font-weight:750;}
.hsc-rows .l{font-size:12px;color:var(--text-secondary);margin-top:1px;}

/* ---------- CUSTOMIZE ---------- */
.preview-wrap{margin:calc(16px + var(--safe-top)) 20px 6px;border-radius:var(--radius-l);overflow:hidden;border:1px solid var(--border);box-shadow:var(--shadow);}
.preview-inner{padding:16px;}
.preview-inner .pv-title{font-size:19px;font-weight:750;margin:0;}
.preview-inner .pv-date{font-size:12px;margin:0 0 12px;}
.pv-row{display:flex;align-items:center;justify-content:space-between;padding:8px 0;border-top:1px solid;}
.pv-row:first-of-type{border-top:none;}
.pv-name{font-size:14px;font-weight:600;}
.pv-check{width:22px;height:22px;border-radius:50%;display:flex;align-items:center;justify-content:center;}
.pv-check svg{width:11px;height:11px;stroke:#fff;}
.pv-add{margin-top:12px;text-align:center;border-radius:10px;padding:10px;font-size:13px;font-weight:700;}

.settings-group{margin:22px 20px 0;}
.settings-group h3{font-size:13px;font-weight:700;text-transform:uppercase;letter-spacing:.04em;color:var(--text-secondary);margin:0 0 8px;padding-left:2px;}
.settings-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-m);overflow:hidden;box-shadow:var(--shadow);}
.settings-row{display:flex;align-items:center;justify-content:space-between;padding:14px 16px;}
.settings-row + .settings-row{border-top:1px solid var(--border);}
.settings-row .rl{font-size:15px;font-weight:500;}
.settings-row select{background:none;border:none;font-size:15px;color:var(--text-secondary);text-align:right;font-family:inherit;}
.color-block{padding:14px 16px 18px;}
.color-block .field-label{margin-bottom:10px;}
.custom-picker-btn{
  width:34px;height:34px;border-radius:50%;border:2px dashed var(--border);display:flex;align-items:center;justify-content:center;cursor:pointer;background:var(--surface);position:relative;
}
.custom-picker-btn svg{width:15px;height:15px;stroke:var(--text-secondary);}
.custom-picker-btn input{position:absolute;inset:0;opacity:0;cursor:pointer;width:100%;height:100%;}

.toast{
  position:fixed;bottom:calc(96px + var(--safe-bottom));left:50%;transform:translateX(-50%) translateY(10px);
  background:#1D1D1F;color:#fff;font-size:14px;font-weight:600;padding:11px 20px;border-radius:30px;
  z-index:200;opacity:0;pointer-events:none;transition:opacity .25s ease, transform .25s ease;box-shadow:0 6px 20px rgba(0,0,0,.2);
  max-width:80%;text-align:center;
}
.toast.show{opacity:1;transform:translateX(-50%) translateY(0);}

.confirm-box{
  position:fixed;left:50%;top:50%;transform:translate(-50%,-50%) scale(.94);max-width:300px;width:86%;
  background:var(--surface);border-radius:18px;padding:20px;z-index:201;opacity:0;pointer-events:none;transition:opacity .2s ease, transform .2s ease;box-shadow:0 12px 40px rgba(0,0,0,.25);
}
.confirm-box.show{opacity:1;pointer-events:auto;transform:translate(-50%,-50%) scale(1);}
.confirm-box h3{font-size:16px;margin:0 0 6px;}
.confirm-box p{font-size:13.5px;color:var(--text-secondary);margin:0 0 16px;line-height:1.4;}
.confirm-box .btns{display:flex;gap:10px;}
.confirm-box .btns button{flex:1;padding:11px;border-radius:10px;border:none;font-size:14.5px;font-weight:650;cursor:pointer;}
.confirm-box .cancel{background:var(--surface2);color:var(--text);}
.confirm-box .ok{background:var(--danger);color:#fff;}

::-webkit-scrollbar{display:none;}
</style>
</head>
<body>
<div class="app" id="app">

  <!-- ============ TODAY ============ -->
  <div class="view active" id="view-today">
    <div class="page-header">
      <h1>Today</h1>
      <p class="subtitle" id="today-date"></p>
      <div class="progress-row">
        <div class="progress-track"><div class="progress-fill" id="progress-fill" style="width:0%"></div></div>
        <div class="progress-label" id="progress-label">0 of 0</div>
      </div>
    </div>
    <div class="habit-list" id="habit-list"></div>
    <div id="empty-state-holder"></div>
    <div class="ideas-entry" id="ideas-entry-btn">
      <div class="l">
        <svg viewBox="0 0 24 24" fill="none" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M9 18h6M10 21h4M12 3a6 6 0 0 0-3.6 10.8c.5.4.8 1 .8 1.6V16h5.6v-.6c0-.6.3-1.2.8-1.6A6 6 0 0 0 12 3Z"/></svg>
        <span>Habit Ideas</span>
      </div>
      <svg class="chev" viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M9 6l6 6-6 6"/></svg>
    </div>
    <button class="fab" id="fab-add" aria-label="Add habit">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 5v14M5 12h14"/></svg>
    </button>
  </div>

  <!-- ============ STATISTICS ============ -->
  <div class="view" id="view-stats">
    <div class="month-nav">
      <button class="month-arrow" id="month-prev"><svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 18l-6-6 6-6"/></svg></button>
      <h1 id="month-label">September 2026</h1>
      <button class="month-arrow" id="month-next"><svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M9 18l6-6-6-6"/></svg></button>
    </div>
    <div class="calendar-wrap">
      <div class="cal-weekdays" id="cal-weekdays"></div>
      <div class="cal-grid" id="cal-grid"></div>
    </div>
    <div class="stats-grid" id="stats-grid"></div>
    <div class="bar-chart">
      <div class="section-label" style="padding:0 0 8px;">Daily completions</div>
      <div class="bar-chart-inner" id="bar-chart-inner"></div>
    </div>
    <div class="habit-select-wrap">
      <div class="field-label">Habit statistics</div>
      <select class="text-input" id="habit-stat-select" style="margin-bottom:12px;"></select>
      <div class="habit-stats-card" id="habit-stats-card"></div>
    </div>
  </div>

  <!-- ============ CUSTOMIZE ============ -->
  <div class="view" id="view-customize">
    <div class="page-header" style="padding-bottom:0;">
      <h1>Customize</h1>
    </div>
    <div class="preview-wrap" id="preview-wrap">
      <div class="preview-inner" id="preview-inner">
        <p class="pv-title">Today</p>
        <p class="pv-date">Wednesday, September 17</p>
        <div id="preview-rows"></div>
        <div class="pv-add">+ Add Habit</div>
      </div>
    </div>

    <div class="settings-group">
      <h3>Background Color</h3>
      <div class="settings-card color-block">
        <div class="color-row" id="bg-swatches"></div>
      </div>
    </div>
    <div class="settings-group">
      <h3>Text / Accent Color</h3>
      <div class="settings-card color-block">
        <div class="color-row" id="text-swatches"></div>
      </div>
    </div>
    <div class="settings-group">
      <h3>Button Color</h3>
      <div class="settings-card color-block">
        <div class="color-row" id="button-swatches"></div>
      </div>
    </div>

    <div class="settings-group">
      <h3>Appearance</h3>
      <div class="settings-card" style="padding:12px 16px;">
        <div class="seg-control" id="appearance-seg">
          <button class="seg-opt" data-v="light">Light</button>
          <button class="seg-opt" data-v="dark">Dark</button>
          <button class="seg-opt" data-v="system">System</button>
        </div>
      </div>
    </div>

    <div class="settings-group">
      <h3>Date</h3>
      <div class="settings-card">
        <div class="settings-row"><span class="rl">Date format</span>
          <select id="date-format-select">
            <option value="long">Wednesday, Sep 17</option>
            <option value="short">Sep 17, 2026</option>
            <option value="numeric">09/17/2026</option>
          </select>
        </div>
        <div class="settings-row"><span class="rl">First day of week</span>
          <select id="first-day-select">
            <option value="0">Sunday</option>
            <option value="1">Monday</option>
          </select>
        </div>
      </div>
    </div>

    <div class="settings-group">
      <h3>Reminders</h3>
      <div class="settings-card">
        <div class="settings-row"><span class="rl">Enable reminders</span>
          <label class="switch"><input type="checkbox" id="reminders-toggle"><span class="track"></span><span class="thumb"></span></label>
        </div>
        <div class="settings-row"><span class="rl">Default reminder time</span>
          <input type="time" id="default-reminder-time" style="border:none;background:none;font-size:15px;color:var(--text-secondary);font-family:inherit;">
        </div>
      </div>
    </div>

    <div class="settings-group">
      <h3>Data</h3>
      <div class="settings-card">
        <div class="settings-row" id="export-data-row" style="cursor:pointer;"><span class="rl">Export data</span><span style="color:var(--text-secondary);">›</span></div>
        <div class="settings-row" id="import-data-row" style="cursor:pointer;"><span class="rl">Import data</span><span style="color:var(--text-secondary);">›</span></div>
        <div class="settings-row" id="reset-data-row" style="cursor:pointer;"><span class="rl" style="color:var(--danger);">Reset all data</span><span style="color:var(--text-secondary);">›</span></div>
      </div>
      <input type="file" id="import-file-input" accept="application/json" style="display:none;">
    </div>

    <div class="settings-group" style="margin-bottom:30px;">
      <button class="danger-btn" id="reset-colors-btn" style="color:var(--text);">Reset to Default</button>
    </div>
  </div>

  <!-- ============ BOTTOM NAV ============ -->
  <div class="bottom-nav">
    <button class="nav-btn active" data-tab="today">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M9 11l3 3 6-7"/><path d="M20 12v6a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h9"/></svg>
      <span>Today</span>
    </button>
    <button class="nav-btn" data-tab="stats">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M4 19V10M12 19V5M20 19v-7"/><path d="M2 19h20"/></svg>
      <span>Statistics</span>
    </button>
    <button class="nav-btn" data-tab="customize">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="3.2"/><path d="M19.4 15a1.7 1.7 0 0 0 .34 1.87l.06.06a2 2 0 1 1-2.83 2.83l-.06-.06a1.7 1.7 0 0 0-1.87-.34 1.7 1.7 0 0 0-1 1.55V21a2 2 0 1 1-4 0v-.09a1.7 1.7 0 0 0-1-1.55 1.7 1.7 0 0 0-1.87.34l-.06.06a2 2 0 1 1-2.83-2.83l.06-.06a1.7 1.7 0 0 0 .34-1.87 1.7 1.7 0 0 0-1.55-1H3a2 2 0 1 1 0-4h.09a1.7 1.7 0 0 0 1.55-1 1.7 1.7 0 0 0-.34-1.87l-.06-.06a2 2 0 1 1 2.83-2.83l.06.06a1.7 1.7 0 0 0 1.87.34H9a1.7 1.7 0 0 0 1-1.55V3a2 2 0 1 1 4 0v.09a1.7 1.7 0 0 0 1 1.55 1.7 1.7 0 0 0 1.87-.34l.06-.06a2 2 0 1 1 2.83 2.83l-.06.06a1.7 1.7 0 0 0-.34 1.87V9a1.7 1.7 0 0 0 1.55 1H21a2 2 0 1 1 0 4h-.09a1.7 1.7 0 0 0-1.55 1Z"/></svg>
      <span>Customize</span>
    </button>
  </div>

</div>

<!-- ============ OVERLAY / SHEETS (shared) ============ -->
<div class="overlay" id="overlay-editor">
  <div class="sheet" id="sheet-editor" style="max-height:92vh;">
    <div class="sheet-handle"></div>
    <div class="sheet-header">
      <button class="sheet-btn muted" id="editor-cancel">Cancel</button>
      <h2 id="editor-title">New Habit</h2>
      <button class="sheet-btn" id="editor-save">Save</button>
    </div>
    <div class="sheet-body" id="editor-body"></div>
  </div>
</div>

<div class="overlay" id="overlay-ideas">
  <div class="sheet" id="sheet-ideas" style="max-height:92vh;">
    <div class="sheet-handle"></div>
    <div class="sheet-header">
      <button class="sheet-btn muted" id="ideas-close">Close</button>
      <h2>Habit Ideas</h2>
      <span style="width:50px;"></span>
    </div>
    <div class="sheet-body" id="ideas-body"></div>
  </div>
</div>

<div class="overlay" id="overlay-day">
  <div class="sheet" id="sheet-day">
    <div class="sheet-handle"></div>
    <div class="sheet-header">
      <button class="sheet-btn muted" id="day-close">Close</button>
      <h2 id="day-title">Day</h2>
      <span style="width:50px;"></span>
    </div>
    <div class="sheet-body" id="day-body"></div>
  </div>
</div>

<div class="overlay" id="overlay-export">
  <div class="sheet" id="sheet-export">
    <div class="sheet-handle"></div>
    <div class="sheet-header">
      <button class="sheet-btn muted" id="export-close">Close</button>
      <h2>Export Data</h2>
      <span style="width:50px;"></span>
    </div>
    <div class="sheet-body">
      <p style="font-size:14px;color:var(--text-secondary);line-height:1.5;margin-top:0;">Copy this backup, or download it as a file. Use Import to restore it later.</p>
      <textarea class="text-input" id="export-textarea" readonly style="height:220px;font-size:12px;font-family:monospace;margin-bottom:14px;"></textarea>
      <button class="primary-btn" id="export-download-btn">Download JSON file</button>
    </div>
  </div>
</div>

<div class="toast" id="toast"></div>
<div class="overlay" id="overlay-confirm"></div>
<div class="confirm-box" id="confirm-box">
  <h3 id="confirm-title">Are you sure?</h3>
  <p id="confirm-desc"></p>
  <div class="btns">
    <button class="cancel" id="confirm-cancel">Cancel</button>
    <button class="ok" id="confirm-ok">Delete</button>
  </div>
</div>

<script>
(function(){
"use strict";

/* ======================================================================
   ICONS
   ====================================================================== */
const ICONS = {
  droplet:'<path d="M12 3s7 7.4 7 12a7 7 0 0 1-14 0c0-4.6 7-12 7-12Z"/>',
  book:'<path d="M4 5.5A2.5 2.5 0 0 1 6.5 3H20v16H6.5A2.5 2.5 0 0 0 4 21.5v-16Z"/><path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"/>',
  moon:'<path d="M20 14.5A8.5 8.5 0 1 1 9.5 4a7 7 0 0 0 10.5 10.5Z"/>',
  sun:'<circle cx="12" cy="12" r="4.2"/><path d="M12 2.5v2.5M12 19v2.5M4.6 4.6l1.8 1.8M17.6 17.6l1.8 1.8M2.5 12H5M19 12h2.5M4.6 19.4l1.8-1.8M17.6 6.4l1.8-1.8"/>',
  dumbbell:'<path d="M6.5 8v8M17.5 8v8M3 10v4M21 10v4M6.5 12h11"/>',
  run:'<circle cx="14.5" cy="4.5" r="1.6"/><path d="M9 21l2-5 3 2 3 4M6 14l3-3 3 1 3-3.5M5 9l4-2 2 2.5"/>',
  leaf:'<path d="M5 19c8 0 14-6 14-14 0 0-13-2-14 7-.5 4 0 7 0 7Z"/><path d="M5 19c0-4 2-8 6-11"/>',
  pencil:'<path d="M4 20l1-4.2L15.6 5.2a1.8 1.8 0 0 1 2.5 0l.7.7a1.8 1.8 0 0 1 0 2.5L8.2 19 4 20Z"/>',
  bed:'<path d="M3 18v-6a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v6"/><path d="M3 18v2M21 18v2M3 13V7a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v3M11 10V7a1 1 0 0 1 1-1h5a2 2 0 0 1 2 2v3"/>',
  heart:'<path d="M12 20.5S3.5 15 3.5 9.2A4.7 4.7 0 0 1 12 6.5a4.7 4.7 0 0 1 8.5 2.7c0 5.8-8.5 11.3-8.5 11.3Z"/>',
  bulb:'<path d="M9 18h6M10 21h4M12 3a6 6 0 0 0-3.6 10.8c.5.4.8 1 .8 1.6V16h5.6v-.6c0-.6.3-1.2.8-1.6A6 6 0 0 0 12 3Z"/>',
  check:'<path d="M20 6L9 17l-5-5"/>',
  cup:'<path d="M5 8h11v6a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4V8Z"/><path d="M16 9h1.5a2.5 2.5 0 0 1 0 5H16"/><path d="M8 3c0 1-1 1-1 2M12 3c0 1-1 1-1 2"/>',
  apple:'<path d="M12 8.4c-1-1.6-2.7-2-4-1.4-2 .9-2.7 4-1.7 6.7 1 2.6 3 4.8 4.7 4.8.9 0 1.3-.4 2-.4s1.1.4 2 .4c1.5 0 3.3-1.7 4.3-3.9-2.4-1-2.7-4.3-.5-5.8-1-1.4-2.6-2-3.9-1.7-.9.2-1.5.7-2 .7s-1.2-.6-2-.7c.2-1.3 1.1-2.5 2.1-3"/>',
  music:'<path d="M9 18V5l11-2v13"/><circle cx="6.5" cy="18" r="2.5"/><circle cx="17.5" cy="16" r="2.5"/>',
  palette:'<path d="M12 3a9 9 0 1 0 0 18c1.3 0 2-1 2-2 0-.6-.3-1-.6-1.4-.3-.3-.4-.6-.4-1 0-.8.7-1.6 1.6-1.6H16a4 4 0 0 0 4-4c0-4.4-3.6-8-8-8Z"/><circle cx="7.5" cy="10.5" r="1"/><circle cx="11" cy="7.5" r="1"/><circle cx="15" cy="8.5" r="1"/>',
  phoneoff:'<path d="M8 3h8a2 2 0 0 1 2 2v10M16 21H8a2 2 0 0 1-2-2V7"/><path d="M3 3l18 18"/>',
  timer:'<circle cx="12" cy="13" r="8"/><path d="M12 9v4l2.5 2.5M9 2h6M12 2v3"/>',
  target:'<circle cx="12" cy="12" r="8.5"/><circle cx="12" cy="12" r="5"/><circle cx="12" cy="12" r="1.5"/>',
  star:'<path d="M12 3.5l2.6 5.4 5.9.8-4.3 4.2 1 5.9L12 17l-5.2 2.8 1-5.9-4.3-4.2 5.9-.8Z"/>',
  flame:'<path d="M12 3s4 3.5 4 8a4 4 0 0 1-8 0c0-1 .5-2 1-2.7.3 1 1.4 1.4 1.9.6.5-.8.1-1.7-.4-2.4C9.7 5.6 12 3 12 3Z"/><path d="M8 15a4 4 0 0 0 8 0c0-1.8-1-3-2-4"/>',
  calendar:'<rect x="3.5" y="5" width="17" height="15.5" rx="2"/><path d="M3.5 9.5h17M8 3v4M16 3v4"/>',
  home:'<path d="M4 11.5L12 4l8 7.5"/><path d="M6 10v9.5a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1V10"/>',
  water_glass:'<path d="M6 3h12l-1.4 16.2A2 2 0 0 1 14.6 21H9.4a2 2 0 0 1-2-1.8L6 3Z"/><path d="M6.6 8h10.8"/>',
  brush:'<path d="M4 20c0-3 2-4 4-4s3 1 3 3-2 3-4 3-3-1-3-2Z"/><path d="M11 13 19 5a2 2 0 0 1 3 3l-8 8"/>',
  footprint:'<path d="M9 8c2 0 3 2 3 5s-1 6-3 6-3-2-3-4c0-1 .5-1.5 1-2 .7-.7.8-1.6.3-2.6C6.8 9.6 7.3 8 9 8Z"/><path d="M16 3c2 0 3 2 3 5s-1 6-3 6-3-2-3-4c0-1 .5-1.5 1-2 .7-.7.8-1.6.3-2.6C13.8 4.6 14.3 3 16 3Z"/>',
  clock:'<circle cx="12" cy="12" r="8.5"/><path d="M12 7.5V12l3 2"/>',
  smile:'<circle cx="12" cy="12" r="8.5"/><path d="M8.5 14s1.2 2 3.5 2 3.5-2 3.5-2"/><path d="M8.5 9.5h.01M15.5 9.5h.01"/>',
  list:'<path d="M8 6h12M8 12h12M8 18h12"/><path d="M3.5 6h.01M3.5 12h.01M3.5 18h.01"/>',
  box:'<path d="M3.5 7.5 12 3l8.5 4.5V16L12 21l-8.5-4.5Z"/><path d="M3.5 7.5 12 12l8.5-4.5M12 12v9"/>'
};
const ICON_LIST = Object.keys(ICONS);
function iconSvg(key){
  return '<svg viewBox="0 0 24 24" fill="none" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round">'+(ICONS[key]||ICONS.star)+'</svg>';
}

/* ======================================================================
   COLORS
   ====================================================================== */
const PASTELS = [
  ['Pastel pink','#F7C9D6'],['Pastel rose','#F3B8C4'],['Pastel peach','#FAD3B8'],
  ['Pastel orange','#F9CBA0'],['Pastel yellow','#F9E6A8'],['Pastel green','#C7E8C5'],
  ['Pastel mint','#BFE9DA'],['Pastel blue','#BEDCF2'],['Pastel sky blue','#B7E1EE'],
  ['Pastel purple','#D6C6EE'],['Pastel lavender','#DCD3F5'],['Pastel lilac','#E3D0EA']
];
const VIBRANTS = [
  ['Bright pink','#F5379E'],['Coral','#FF6F5E'],['Orange','#FF8A2B'],['Yellow','#F4C51A'],
  ['Lime green','#8BC53F'],['Emerald','#12A96B'],['Cyan','#16B8C9'],['Blue','#2E6BEB'],
  ['Purple','#7B4FE0'],['Magenta','#C6379B'],['Red','#E8393A']
];
const NEUTRALS = [
  ['White','#FFFFFF'],['Cream','#F5EFE3'],['Light gray','#D8D8D8'],
  ['Dark gray','#4A4A4C'],['Black','#121214']
];
const ALL_SWATCHES = [...PASTELS,...VIBRANTS,...NEUTRALS];

function hexToRgb(hex){
  hex = hex.replace('#','');
  if(hex.length===3) hex = hex.split('').map(c=>c+c).join('');
  const num = parseInt(hex,16);
  return {r:(num>>16)&255, g:(num>>8)&255, b:num&255};
}
function rgbToHex(r,g,b){
  return '#'+[r,g,b].map(v=>Math.max(0,Math.min(255,Math.round(v))).toString(16).padStart(2,'0')).join('');
}
function relLuminance(hex){
  const {r,g,b} = hexToRgb(hex);
  const a = [r,g,b].map(v=>{
    v/=255;
    return v<=0.03928 ? v/12.92 : Math.pow((v+0.055)/1.055,2.4);
  });
  return 0.2126*a[0]+0.7152*a[1]+0.0722*a[2];
}
function contrastText(hex){
  return relLuminance(hex) > 0.52 ? '#1D1D1F' : '#FFFFFF';
}
function rgbaFrom(hex,alpha){
  const {r,g,b} = hexToRgb(hex);
  return `rgba(${r},${g},${b},${alpha})`;
}
function hexToHsl(hex){
  let {r,g,b} = hexToRgb(hex); r/=255;g/=255;b/=255;
  const max=Math.max(r,g,b),min=Math.min(r,g,b);
  let h,s,l=(max+min)/2;
  if(max===min){h=0;s=0;}
  else{
    const d=max-min;
    s = l>0.5 ? d/(2-max-min) : d/(max+min);
    switch(max){
      case r: h=(g-b)/d+(g<b?6:0); break;
      case g: h=(b-r)/d+2; break;
      case b: h=(r-g)/d+4; break;
    }
    h/=6;
  }
  return {h:h*360,s:s*100,l:l*100};
}
function hslToHex(h,s,l){
  h/=360; s/=100; l/=100;
  let r,g,b;
  if(s===0){r=g=b=l;}
  else{
    const hue2rgb=(p,q,t)=>{
      if(t<0)t+=1; if(t>1)t-=1;
      if(t<1/6) return p+(q-p)*6*t;
      if(t<1/2) return q;
      if(t<2/3) return p+(q-p)*(2/3-t)*6;
      return p;
    };
    const q = l<0.5 ? l*(1+s) : l+s-l*s;
    const p = 2*l-q;
    r=hue2rgb(p,q,h+1/3); g=hue2rgb(p,q,h); b=hue2rgb(p,q,h-1/3);
  }
  return rgbToHex(r*255,g*255,b*255);
}
function adjustLightness(hex, deltaPct){
  const hsl = hexToHsl(hex);
  let l = hsl.l + deltaPct;
  l = Math.max(0,Math.min(100,l));
  return hslToHex(hsl.h,hsl.s,l);
}

/* ======================================================================
   STORAGE
   ====================================================================== */
const LS = {
  habits:'bloom_habits_v1',
  completions:'bloom_completions_v1',
  settings:'bloom_settings_v1'
};
const DEFAULT_SETTINGS = {
  bg:'#F7F7F5', text:'#1D1D1F', button:'#3F6653',
  appearance:'light',
  dateFormat:'long',
  firstDayOfWeek:1,
  remindersEnabled:false,
  defaultReminderTime:'20:00'
};
function loadJSON(key, fallback){
  try{
    const raw = localStorage.getItem(key);
    if(!raw) return fallback;
    return JSON.parse(raw);
  }catch(e){ return fallback; }
}
function saveJSON(key, val){
  try{ localStorage.setItem(key, JSON.stringify(val)); }catch(e){}
}
let habits = loadJSON(LS.habits, []);
let completions = loadJSON(LS.completions, {}); // {habitId: {dateStr:true}}
let settings = Object.assign({}, DEFAULT_SETTINGS, loadJSON(LS.settings, {}));

function saveHabits(){ saveJSON(LS.habits, habits); }
function saveCompletions(){ saveJSON(LS.completions, completions); }
function saveSettings(){ saveJSON(LS.settings, settings); }

/* ======================================================================
   DATE HELPERS
   ====================================================================== */
function pad2(n){ return n<10 ? '0'+n : ''+n; }
function dateStr(d){ return d.getFullYear()+'-'+pad2(d.getMonth()+1)+'-'+pad2(d.getDate()); }
function startOfDay(d){ const x=new Date(d); x.setHours(0,0,0,0); return x; }
function addDays(d,n){ const x=new Date(d); x.setDate(x.getDate()+n); return x; }
function today(){ return startOfDay(new Date()); }
const WEEKDAY_LETTERS_SUN = ['S','M','T','W','T','F','S'];
const MONTH_NAMES = ['January','February','March','April','May','June','July','August','September','October','November','December'];
const WEEKDAY_FULL = ['Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday'];

function formatHeaderDate(d){
  const fmt = settings.dateFormat;
  if(fmt==='short'){
    return MONTH_NAMES[d.getMonth()].slice(0,3)+' '+d.getDate()+', '+d.getFullYear();
  } else if(fmt==='numeric'){
    return pad2(d.getMonth()+1)+'/'+pad2(d.getDate())+'/'+d.getFullYear();
  }
  return WEEKDAY_FULL[d.getDay()]+', '+MONTH_NAMES[d.getMonth()].slice(0,3)+' '+d.getDate();
}

/* ======================================================================
   SCHEDULE / STREAK LOGIC
   ====================================================================== */
function isScheduled(habit, d){
  if(habit.frequency==='daily') return true;
  if(habit.frequency==='specific') return (habit.days||[]).includes(d.getDay());
  if(habit.frequency==='weekly') return true; // day-agnostic; week-based target
  return true;
}
function isCompleted(habit, d){
  const c = completions[habit.id];
  return !!(c && c[dateStr(d)]);
}
function habitCreatedDate(habit){
  return startOfDay(new Date(habit.createdAt || Date.now()));
}
function weekStart(d, firstDay){
  const x = startOfDay(d);
  const diff = (x.getDay() - firstDay + 7) % 7;
  return addDays(x, -diff);
}
function countCompletionsInWeek(habit, wStart){
  let n=0;
  for(let i=0;i<7;i++){
    if(isCompleted(habit, addDays(wStart,i))) n++;
  }
  return n;
}

// Daily/specific streaks
function dailyCurrentStreak(habit){
  const t = today();
  let d = new Date(t);
  if(isScheduled(habit,d) && !isCompleted(habit,d)){
    d = addDays(d,-1);
  }
  let count=0;
  const created = habitCreatedDate(habit);
  let guard=0;
  while(d >= created && guard<3660){
    guard++;
    if(isScheduled(habit,d)){
      if(isCompleted(habit,d)){ count++; d=addDays(d,-1); }
      else break;
    } else {
      d = addDays(d,-1);
    }
  }
  return count;
}
function dailyBestStreak(habit){
  const created = habitCreatedDate(habit);
  const t = today();
  let best=0, run=0;
  let d = new Date(created);
  let guard=0;
  while(d<=t && guard<3660){
    guard++;
    if(isScheduled(habit,d)){
      if(isCompleted(habit,d)){ run++; best=Math.max(best,run); }
      else run=0;
    }
    d = addDays(d,1);
  }
  return best;
}
// Weekly (X times per week) streaks
function weeklyCurrentStreak(habit){
  const fd = settings.firstDayOfWeek;
  const t = today();
  let wStart = weekStart(t, fd);
  const target = habit.timesPerWeek || 1;
  // grace: if current week not yet met target, check previous week first
  if(countCompletionsInWeek(habit,wStart) < target){
    wStart = addDays(wStart,-7);
  }
  let count=0;
  const created = habitCreatedDate(habit);
  let guard=0;
  while(wStart >= weekStart(created,fd) && guard<520){
    guard++;
    if(countCompletionsInWeek(habit,wStart) >= target){ count++; wStart = addDays(wStart,-7); }
    else break;
  }
  return count;
}
function weeklyBestStreak(habit){
  const fd = settings.firstDayOfWeek;
  const created = habitCreatedDate(habit);
  const t = today();
  const target = habit.timesPerWeek || 1;
  let wStart = weekStart(created, fd);
  let best=0, run=0;
  let guard=0;
  while(wStart<=t && guard<520){
    guard++;
    if(countCompletionsInWeek(habit,wStart) >= target){ run++; best=Math.max(best,run); }
    else run=0;
    wStart = addDays(wStart,7);
  }
  return best;
}
function currentStreak(habit){
  return habit.frequency==='weekly' ? weeklyCurrentStreak(habit) : dailyCurrentStreak(habit);
}
function bestStreak(habit){
  return habit.frequency==='weekly' ? weeklyBestStreak(habit) : dailyBestStreak(habit);
}

/* ======================================================================
   TOAST / CONFIRM
   ====================================================================== */
let toastTimer=null;
function showToast(msg){
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  clearTimeout(toastTimer);
  toastTimer = setTimeout(()=>t.classList.remove('show'), 1800);
}
function showConfirm(title, desc, okLabel, onOk){
  const box = document.getElementById('confirm-box');
  const ov = document.getElementById('overlay-confirm');
  document.getElementById('confirm-title').textContent = title;
  document.getElementById('confirm-desc').textContent = desc;
  const okBtn = document.getElementById('confirm-ok');
  okBtn.textContent = okLabel || 'Delete';
  ov.classList.add('open'); box.classList.add('show');
  function cleanup(){
    ov.classList.remove('open'); box.classList.remove('show');
    okBtn.removeEventListener('click', okHandler);
    document.getElementById('confirm-cancel').removeEventListener('click', cancelHandler);
    ov.removeEventListener('click', cancelHandler);
  }
  function okHandler(){ cleanup(); onOk(); }
  function cancelHandler(){ cleanup(); }
  okBtn.addEventListener('click', okHandler);
  document.getElementById('confirm-cancel').addEventListener('click', cancelHandler);
  ov.addEventListener('click', cancelHandler);
}

/* ======================================================================
   THEME APPLY
   ====================================================================== */
function applyTheme(){
  const root = document.documentElement.style;
  const bg = settings.bg, text = settings.text, button = settings.button;
  const isDark = relLuminance(bg) < 0.5;
  const surface = adjustLightness(bg, isDark ? 6 : (relLuminance(bg)>0.96 ? -1.5 : 3));
  const surface2 = adjustLightness(bg, isDark ? 11 : -4);
  root.setProperty('--bg', bg);
  root.setProperty('--text', text);
  root.setProperty('--text-secondary', rgbaFrom(text,0.55));
  root.setProperty('--border', rgbaFrom(text,0.12));
  root.setProperty('--surface', surface);
  root.setProperty('--surface2', surface2);
  root.setProperty('--button', button);
  root.setProperty('--button-text', contrastText(button));
  document.getElementById('theme-color-meta').setAttribute('content', bg);
}

/* ======================================================================
   RENDER: TODAY
   ====================================================================== */
function habitsSortedForToday(){
  return [...habits].sort((a,b)=>(a.order||0)-(b.order||0));
}
function renderToday(){
  document.getElementById('today-date').textContent = formatHeaderDate(new Date());
  const list = document.getElementById('habit-list');
  const holder = document.getElementById('empty-state-holder');
  const t = today();
  const scheduledToday = habitsSortedForToday().filter(h=>isScheduled(h,t));
  const completedCount = scheduledToday.filter(h=>isCompleted(h,t)).length;
  const total = scheduledToday.length;
  document.getElementById('progress-label').textContent = `${completedCount} of ${total}`;
  document.getElementById('progress-fill').style.width = total ? (completedCount/total*100)+'%' : '0%';

  list.innerHTML = '';
  const all = habitsSortedForToday();
  if(all.length===0){
    holder.innerHTML = `<div class="empty-state">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M9 11l3 3 6-7"/><path d="M20 12v6a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h9"/></svg>
      <h3>No habits yet</h3>
      <p>Tap the + button to create your first habit,<br>or browse Habit Ideas below.</p>
    </div>`;
    return;
  }
  holder.innerHTML='';
  all.forEach(h=>{
    const scheduled = isScheduled(h,t);
    const done = isCompleted(h,t);
    const streak = currentStreak(h);
    const card = document.createElement('div');
    card.className = 'habit-card';
    card.setAttribute('draggable','true');
    card.dataset.id = h.id;
    const col = h.color || settings.text;
    card.innerHTML = `
      <div class="drag-handle" aria-hidden="true"><svg viewBox="0 0 24 24" fill="none" stroke-width="1.8" stroke-linecap="round"><path d="M4 7h16M4 12h16M4 17h16"/></svg></div>
      <div class="habit-icon" style="--icon-bg:${rgbaFrom(col,0.14)};--icon-color:${col};">${iconSvg(h.icon)}</div>
      <div class="habit-info">
        <p class="habit-name ${done?'done':''}">${escapeHtml(h.name)}</p>
        ${h.description?`<p class="habit-desc">${escapeHtml(h.description)}</p>`:''}
        <div class="habit-meta">
          <span class="streak-chip ${streak>0?'active':''}">
            <svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round"><path d="M12 3s4 3.5 4 8a4 4 0 0 1-8 0c0-1 .5-2 1-2.7.3 1 1.4 1.4 1.9.6.5-.8.1-1.7-.4-2.4C9.7 5.6 12 3 12 3Z"/></svg>
            ${streak} ${streak===1?'day':'day'} streak
          </span>
          ${!scheduled?`<span class="streak-chip">· not scheduled today</span>`:''}
        </div>
      </div>
      <button class="check-btn ${done?'checked':''}" data-id="${h.id}" aria-label="Toggle complete" ${scheduled?'':'style="opacity:.4"'}>
        <svg viewBox="0 0 24 24" fill="none" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg>
      </button>
    `;
    card.addEventListener('click', (e)=>{
      if(e.target.closest('.check-btn') || e.target.closest('.drag-handle')) return;
      openEditor(h);
    });
    list.appendChild(card);
  });
  attachCheckHandlers();
  attachDragHandlers();
}
function escapeHtml(s){
  return (s||'').replace(/[&<>"']/g, c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
}
function attachCheckHandlers(){
  document.querySelectorAll('.check-btn').forEach(btn=>{
    btn.onclick = (e)=>{
      e.stopPropagation();
      const id = btn.dataset.id;
      const h = habits.find(x=>x.id===id);
      if(!h) return;
      const t = today();
      if(!isScheduled(h,t)) return;
      const ds = dateStr(t);
      completions[id] = completions[id] || {};
      if(completions[id][ds]) delete completions[id][ds];
      else completions[id][ds] = true;
      saveCompletions();
      renderToday();
    };
  });
}
// Drag reorder (simple pointer-based, works on touch)
let dragState = null;
function attachDragHandlers(){
  const list = document.getElementById('habit-list');
  let cards = Array.from(list.querySelectorAll('.habit-card'));
  cards.forEach(card=>{
    const handle = card.querySelector('.drag-handle');
    handle.addEventListener('pointerdown', (e)=>{
      e.preventDefault();
      dragState = { id: card.dataset.id, startY: e.clientY };
      card.classList.add('dragging');
      handle.setPointerCapture(e.pointerId);
    });
    handle.addEventListener('pointermove', (e)=>{
      if(!dragState || dragState.id !== card.dataset.id) return;
      const y = e.clientY;
      const siblings = Array.from(list.querySelectorAll('.habit-card'));
      for(const sib of siblings){
        if(sib===card) continue;
        const rect = sib.getBoundingClientRect();
        const mid = rect.top + rect.height/2;
        if(y < mid && sib.previousElementSibling===card){
          list.insertBefore(card, sib);
          break;
        } else if(y > mid && sib.nextElementSibling===card){
          list.insertBefore(sib, card);
          break;
        }
      }
    });
    handle.addEventListener('pointerup', (e)=>{
      if(!dragState) return;
      card.classList.remove('dragging');
      dragState = null;
      const ids = Array.from(list.querySelectorAll('.habit-card')).map(c=>c.dataset.id);
      ids.forEach((id,idx)=>{
        const h = habits.find(x=>x.id===id);
        if(h) h.order = idx;
      });
      saveHabits();
    });
  });
}

/* ======================================================================
   EDITOR SHEET (add / edit habit)
   ====================================================================== */
let editingHabitId = null;
let editorState = null;
function openEditor(habit){
  editingHabitId = habit ? habit.id : null;
  editorState = habit ? JSON.parse(JSON.stringify(habit)) : {
    id: 'h_'+Date.now()+'_'+Math.random().toString(36).slice(2,7),
    name:'', description:'', icon:'star', color: settings.text,
    frequency:'daily', days:[1,2,3,4,5,6,0], timesPerWeek:3,
    reminder:{enabled:false, time: settings.defaultReminderTime||'20:00'},
    target:'', order: habits.length, createdAt: Date.now()
  };
  document.getElementById('editor-title').textContent = habit ? 'Edit Habit' : 'New Habit';
  renderEditorBody();
  document.getElementById('overlay-editor').classList.add('open');
}
function closeEditor(){
  document.getElementById('overlay-editor').classList.remove('open');
}
function syncTextFields(){
  const st = editorState;
  const nameEl = document.getElementById('f-name');
  const descEl = document.getElementById('f-desc');
  const targetEl = document.getElementById('f-target');
  const remTimeEl = document.getElementById('f-rem-time');
  const remToggleEl = document.getElementById('f-rem-toggle');
  if(nameEl) st.name = nameEl.value;
  if(descEl) st.description = descEl.value;
  if(targetEl) st.target = targetEl.value;
  if(!st.reminder) st.reminder = {enabled:false, time:'20:00'};
  if(remToggleEl) st.reminder.enabled = remToggleEl.checked;
  if(remTimeEl) st.reminder.time = remTimeEl.value;
}
function renderEditorBody(){
  const body = document.getElementById('editor-body');
  const st = editorState;
  body.innerHTML = `
    <div class="field-group">
      <label class="field-label">Name</label>
      <input class="text-input" id="f-name" placeholder="e.g. Drink water" maxlength="40" value="${escapeHtml(st.name)}">
    </div>
    <div class="field-group">
      <label class="field-label">Description (optional)</label>
      <input class="text-input" id="f-desc" placeholder="A short note" maxlength="60" value="${escapeHtml(st.description||'')}">
    </div>
    <div class="field-group">
      <label class="field-label">Icon</label>
      <div class="icon-grid" id="f-icon-grid"></div>
    </div>
    <div class="field-group">
      <label class="field-label">Color</label>
      <div class="color-row" id="f-color-row"></div>
    </div>
    <div class="field-group">
      <label class="field-label">Frequency</label>
      <div class="seg-control" id="f-freq-seg">
        <button class="seg-opt" data-v="daily">Every day</button>
        <button class="seg-opt" data-v="specific">Specific days</button>
        <button class="seg-opt" data-v="weekly">X / week</button>
      </div>
    </div>
    <div class="field-group" id="f-days-wrap" style="display:none;">
      <label class="field-label">Days of the week</label>
      <div class="day-row" id="f-day-row"></div>
    </div>
    <div class="field-group" id="f-times-wrap" style="display:none;">
      <label class="field-label">Times per week</label>
      <div class="stepper">
        <button id="f-times-dec" type="button">−</button>
        <span class="val" id="f-times-val">3 / week</span>
        <button id="f-times-inc" type="button">+</button>
      </div>
    </div>
    <div class="field-group">
      <label class="field-label">Target (optional)</label>
      <input class="text-input" id="f-target" placeholder="e.g. 8 glasses, 30 minutes" maxlength="40" value="${escapeHtml(st.target||'')}">
    </div>
    <div class="field-group">
      <div class="row-between">
        <label class="field-label" style="margin:0;">Reminder</label>
        <label class="switch"><input type="checkbox" id="f-rem-toggle" ${st.reminder&&st.reminder.enabled?'checked':''}><span class="track"></span><span class="thumb"></span></label>
      </div>
      <div id="f-rem-time-wrap" style="margin-top:10px;display:${st.reminder&&st.reminder.enabled?'block':'none'};">
        <input class="text-input" type="time" id="f-rem-time" value="${st.reminder?st.reminder.time:'20:00'}">
      </div>
    </div>
    ${editingHabitId ? `
    <button class="danger-btn" id="f-delete-btn">Delete Habit</button>
    ` : ''}
  `;
  // icon grid
  const grid = document.getElementById('f-icon-grid');
  ICON_LIST.forEach(key=>{
    const opt = document.createElement('div');
    opt.className = 'icon-opt' + (st.icon===key?' sel':'');
    opt.innerHTML = iconSvg(key);
    opt.onclick = ()=>{ st.icon = key; renderEditorBody(); focusPreserve('f-icon-grid'); };
    grid.appendChild(opt);
  });
  // color row
  const crow = document.getElementById('f-color-row');
  [...VIBRANTS, ...PASTELS, ...NEUTRALS.slice(0,4)].forEach(([name,hex])=>{
    const dot = document.createElement('div');
    dot.className = 'color-dot'+(st.color===hex?' sel':'');
    dot.style.background = hex;
    dot.title = name;
    if(hex==='#FFFFFF') dot.style.border = st.color===hex?'2px solid var(--text)':'1px solid var(--border)';
    dot.onclick = ()=>{ st.color = hex; renderEditorBody(); };
    crow.appendChild(dot);
  });
  // frequency seg
  const seg = document.getElementById('f-freq-seg');
  seg.querySelectorAll('.seg-opt').forEach(b=>{
    if(b.dataset.v===st.frequency) b.classList.add('sel');
    b.onclick = ()=>{ st.frequency = b.dataset.v; renderEditorBody(); };
  });
  document.getElementById('f-days-wrap').style.display = st.frequency==='specific' ? 'block':'none';
  document.getElementById('f-times-wrap').style.display = st.frequency==='weekly' ? 'block':'none';
  // days row
  const dayRow = document.getElementById('f-day-row');
  const labels = settings.firstDayOfWeek===1 ? ['M','T','W','T','F','S','S'] : ['S','M','T','W','T','F','S'];
  const dayNums = settings.firstDayOfWeek===1 ? [1,2,3,4,5,6,0] : [0,1,2,3,4,5,6];
  dayNums.forEach((dn,i)=>{
    const pill = document.createElement('div');
    pill.className = 'day-pill' + ((st.days||[]).includes(dn)?' sel':'');
    pill.textContent = labels[i];
    pill.onclick = ()=>{
      st.days = st.days || [];
      const idx = st.days.indexOf(dn);
      if(idx>-1) st.days.splice(idx,1); else st.days.push(dn);
      renderEditorBody();
    };
    dayRow.appendChild(pill);
  });
  // times stepper
  document.getElementById('f-times-val').textContent = (st.timesPerWeek||3)+' / week';
  document.getElementById('f-times-dec').onclick = ()=>{ st.timesPerWeek = Math.max(1,(st.timesPerWeek||3)-1); document.getElementById('f-times-val').textContent = st.timesPerWeek+' / week'; };
  document.getElementById('f-times-inc').onclick = ()=>{ st.timesPerWeek = Math.min(7,(st.timesPerWeek||3)+1); document.getElementById('f-times-val').textContent = st.timesPerWeek+' / week'; };
  // reminder toggle
  document.getElementById('f-rem-toggle').onchange = (e)=>{
    document.getElementById('f-rem-time-wrap').style.display = e.target.checked ? 'block':'none';
  };
  // name/desc/target bind on save (read at save time)
  // delete
  if(editingHabitId){
    document.getElementById('f-delete-btn').onclick = ()=>{
      showConfirm('Delete habit?', `"${st.name}" and all of its history will be permanently deleted.`, 'Delete', ()=>{
        habits = habits.filter(h=>h.id!==editingHabitId);
        delete completions[editingHabitId];
        saveHabits(); saveCompletions();
        closeEditor();
        renderToday();
        showToast('Habit deleted');
      });
    };
  }
}
function focusPreserve(){ /* no-op placeholder for potential scroll preserve */ }
function saveEditor(){
  const st = editorState;
  const name = document.getElementById('f-name').value.trim();
  if(!name){ showToast('Please enter a habit name'); return; }
  st.name = name;
  st.description = document.getElementById('f-desc').value.trim();
  st.target = document.getElementById('f-target').value.trim();
  st.reminder = {
    enabled: document.getElementById('f-rem-toggle').checked,
    time: document.getElementById('f-rem-time') ? document.getElementById('f-rem-time').value : '20:00'
  };
  if(st.frequency==='specific' && (!st.days || st.days.length===0)){
    showToast('Pick at least one day'); return;
  }
  const idx = habits.findIndex(h=>h.id===st.id);
  if(idx>-1) habits[idx] = st; else habits.push(st);
  saveHabits();
  closeEditor();
  renderToday();
  showToast(editingHabitId ? 'Habit updated' : 'Habit added');
}

/* ======================================================================
   HABIT IDEAS
   ====================================================================== */
const IDEAS = [
  {cat:'Health', items:[
    {n:'Drink water', d:'Stay hydrated throughout the day', f:'Every day', icon:'droplet', freq:{frequency:'daily'}},
    {n:'Take vitamins', d:'A small daily habit for your health', f:'Every day', icon:'apple', freq:{frequency:'daily'}},
    {n:'Eat a fruit or vegetable', d:'Add something fresh to your day', f:'Every day', icon:'apple', freq:{frequency:'daily'}},
  ]},
  {cat:'Sleep', items:[
    {n:'Go to bed on time', d:'Protect your sleep schedule', f:'Every day', icon:'bed', freq:{frequency:'daily'}},
    {n:'No screens before bed', d:'Wind down without your phone', f:'Every day', icon:'moon', freq:{frequency:'daily'}},
    {n:'Wake up early', d:'Start the day with intention', f:'Every day', icon:'sun', freq:{frequency:'daily'}},
  ]},
  {cat:'Exercise', items:[
    {n:'Stretch', d:'A few minutes to loosen up', f:'Every day', icon:'run', freq:{frequency:'daily'}},
    {n:'Go for a walk', d:'Move your body and get outside', f:'Every day', icon:'footprint', freq:{frequency:'daily'}},
    {n:'Workout', d:'Strength, cardio, or whatever moves you', f:'3x / week', icon:'dumbbell', freq:{frequency:'weekly',timesPerWeek:3}},
    {n:'Go outside', d:'Get some fresh air and daylight', f:'Every day', icon:'leaf', freq:{frequency:'daily'}},
  ]},
  {cat:'Study', items:[
    {n:'Study for 30 minutes', d:'Focused, distraction-free study time', f:'Weekdays', icon:'book', freq:{frequency:'specific',days:[1,2,3,4,5]}},
    {n:'Review notes', d:'Reinforce what you learned', f:'Every day', icon:'book', freq:{frequency:'daily'}},
    {n:'Practice a language', d:'A little bit every day adds up', f:'Every day', icon:'bulb', freq:{frequency:'daily'}},
  ]},
  {cat:'Productivity', items:[
    {n:'Plan tomorrow', d:'End the day with a clear next step', f:'Every day', icon:'list', freq:{frequency:'daily'}},
    {n:'Tackle your top task first', d:'Do the most important thing early', f:'Weekdays', icon:'target', freq:{frequency:'specific',days:[1,2,3,4,5]}},
    {n:'Inbox zero', d:'Clear out your messages', f:'Weekdays', icon:'check', freq:{frequency:'specific',days:[1,2,3,4,5]}},
  ]},
  {cat:'Self-care', items:[
    {n:'Journal', d:'Write down your thoughts for the day', f:'Every day', icon:'pencil', freq:{frequency:'daily'}},
    {n:'Practice gratitude', d:'Note a few things you are grateful for', f:'Every day', icon:'heart', freq:{frequency:'daily'}},
    {n:'Meditate', d:'A few quiet minutes for your mind', f:'Every day', icon:'smile', freq:{frequency:'daily'}},
  ]},
  {cat:'Digital wellbeing', items:[
    {n:'Take a screen break', d:'Step away from your devices', f:'Every day', icon:'phoneoff', freq:{frequency:'daily'}},
    {n:'Limit social media', d:'Set a boundary for scrolling', f:'Every day', icon:'clock', freq:{frequency:'daily'}},
    {n:'Phone-free morning', d:'Start your day away from a screen', f:'Every day', icon:'sun', freq:{frequency:'daily'}},
  ]},
  {cat:'Personal growth', items:[
    {n:'Read', d:'Even a few pages count', f:'Every day', icon:'book', freq:{frequency:'daily'}},
    {n:'Practice a hobby', d:'Make time for something you enjoy', f:'3x / week', icon:'star', freq:{frequency:'weekly',timesPerWeek:3}},
    {n:'Learn something new', d:'Spend time on a skill you want to build', f:'3x / week', icon:'bulb', freq:{frequency:'weekly',timesPerWeek:3}},
  ]},
  {cat:'Organization', items:[
    {n:'Make your bed', d:'A simple win to start the day', f:'Every day', icon:'bed', freq:{frequency:'daily'}},
    {n:'Tidy your room', d:'Keep your space clear and calm', f:'Every day', icon:'box', freq:{frequency:'daily'}},
    {n:'Declutter one area', d:'Small, steady progress adds up', f:'Weekly', icon:'box', freq:{frequency:'weekly',timesPerWeek:1}},
  ]},
  {cat:'Creativity', items:[
    {n:'Practice an instrument', d:'A few minutes of practice each day', f:'Every day', icon:'music', freq:{frequency:'daily'}},
    {n:'Draw or paint', d:'Make something, however small', f:'3x / week', icon:'palette', freq:{frequency:'weekly',timesPerWeek:3}},
    {n:'Write creatively', d:'Free-write, poetry, or fiction', f:'3x / week', icon:'pencil', freq:{frequency:'weekly',timesPerWeek:3}},
  ]},
];
function renderIdeas(){
  const body = document.getElementById('ideas-body');
  body.innerHTML='';
  IDEAS.forEach(group=>{
    const cat = document.createElement('div');
    cat.className='idea-cat';
    cat.innerHTML = `<h3>${group.cat}</h3>`;
    group.items.forEach(item=>{
      const row = document.createElement('div');
      row.className='idea-item';
      row.innerHTML = `
        <div class="ic">${iconSvg(item.icon)}</div>
        <div class="txt">
          <div class="n">${item.n}</div>
          <div class="d">${item.d}</div>
          <div class="f">${item.f}</div>
        </div>
        <button class="idea-add">Add</button>
      `;
      const btn = row.querySelector('.idea-add');
      btn.onclick = ()=>{
        const h = {
          id:'h_'+Date.now()+'_'+Math.random().toString(36).slice(2,7),
          name:item.n, description:item.d, icon:item.icon, color: settings.text,
          frequency: item.freq.frequency,
          days: item.freq.days || [1,2,3,4,5,6,0],
          timesPerWeek: item.freq.timesPerWeek || 3,
          reminder:{enabled:false, time: settings.defaultReminderTime||'20:00'},
          target:'', order: habits.length, createdAt: Date.now()
        };
        habits.push(h);
        saveHabits();
        renderToday();
        btn.textContent='Added';
        btn.classList.add('added');
        btn.disabled = true;
        showToast(item.n+' added');
      };
      cat.appendChild(row);
    });
    body.appendChild(cat);
  });
}

/* ======================================================================
   STATISTICS TAB
   ====================================================================== */
let statsMonth = today().getMonth();
let statsYear = today().getFullYear();
let selectedStatHabitId = null;

function daysInMonth(y,m){ return new Date(y,m+1,0).getDate(); }

function renderStats(){
  document.getElementById('month-label').textContent = MONTH_NAMES[statsMonth]+' '+statsYear;
  const t = today();
  const isCurrentMonth = (statsYear===t.getFullYear() && statsMonth===t.getMonth());
  document.getElementById('month-next').disabled = isCurrentMonth;

  // weekday header
  const wk = document.getElementById('cal-weekdays');
  wk.innerHTML='';
  const order = settings.firstDayOfWeek===1 ? [1,2,3,4,5,6,0] : [0,1,2,3,4,5,6];
  order.forEach(dn=>{
    const s = document.createElement('span'); s.textContent = WEEKDAY_LETTERS_SUN[dn]; wk.appendChild(s);
  });

  const grid = document.getElementById('cal-grid');
  grid.innerHTML='';
  const first = new Date(statsYear, statsMonth, 1);
  let leading = (first.getDay() - settings.firstDayOfWeek + 7) % 7;
  const numDays = daysInMonth(statsYear, statsMonth);
  for(let i=0;i<leading;i++){
    const e = document.createElement('div'); e.className='cal-day empty'; grid.appendChild(e);
  }
  const dailyCompletionCounts = [];
  for(let day=1; day<=numDays; day++){
    const d = new Date(statsYear, statsMonth, day);
    const scheduled = habits.filter(h=>isScheduled(h,d) && habitCreatedDate(h) <= d);
    const completed = scheduled.filter(h=>isCompleted(h,d));
    dailyCompletionCounts.push(completed.length);
    const ratio = scheduled.length ? completed.length/scheduled.length : 0;
    const cell = document.createElement('div');
    let cls = 'cal-day';
    const isFuture = startOfDay(d) > t;
    if(isFuture) cls += ' future';
    if(dateStr(d)===dateStr(t)) cls += ' today';
    cell.className = cls;
    let bgStyle = '';
    if(!isFuture && scheduled.length){
      const alpha = 0.18 + ratio*0.65;
      bgStyle = `background:${rgbaFrom(settings.button, ratio>0?alpha:0.18)};`;
    }
    cell.setAttribute('style', bgStyle);
    cell.innerHTML = `<span class="num">${day}</span>${(!isFuture && scheduled.length && ratio===1)?'<span class="dot"></span>':''}`;
    if(!isFuture){
      cell.addEventListener('click', ()=>openDayDetail(d));
    }
    grid.appendChild(cell);
  }

  renderStatsSummary(numDays);
  renderBarChart(dailyCompletionCounts, numDays);
  renderHabitStatSelector();
}

function monthRangeDays(){
  const numDays = daysInMonth(statsYear, statsMonth);
  const arr = [];
  for(let day=1; day<=numDays; day++) arr.push(new Date(statsYear, statsMonth, day));
  return arr;
}

function renderStatsSummary(numDays){
  const t = today();
  const days = monthRangeDays().filter(d=>startOfDay(d)<=t);
  let totalCompletions=0, totalScheduled=0;
  const perHabit = {};
  habits.forEach(h=>{ perHabit[h.id] = {scheduled:0, completed:0, name:h.name}; });
  days.forEach(d=>{
    habits.forEach(h=>{
      if(habitCreatedDate(h) > d) return;
      if(isScheduled(h,d)){
        totalScheduled++;
        perHabit[h.id].scheduled++;
        if(isCompleted(h,d)){ totalCompletions++; perHabit[h.id].completed++; }
      }
    });
  });
  const rate = totalScheduled ? Math.round(totalCompletions/totalScheduled*100) : 0;

  // overall current/best streak: "perfect day" streak across daily/specific habits
  const overallCurrent = overallPerfectStreak(false);
  const overallBest = overallPerfectStreak(true);

  let mostName='—', leastName='—';
  let mostRate=-1, leastRate=2;
  Object.values(perHabit).forEach(p=>{
    if(p.scheduled===0) return;
    const r = p.completed/p.scheduled;
    if(r>mostRate){ mostRate=r; mostName=p.name; }
    if(r<leastRate){ leastRate=r; leastName=p.name; }
  });
  if(mostRate<0){ mostName='—'; }
  if(leastRate>1){ leastName='—'; }

  const grid = document.getElementById('stats-grid');
  grid.innerHTML = `
    <div class="stat-card"><div class="v">${totalCompletions}</div><div class="l">Total completions</div></div>
    <div class="stat-card"><div class="v">${rate}%</div><div class="l">Completion rate</div></div>
    <div class="stat-card"><div class="v">${overallCurrent}</div><div class="l">Current streak (days)</div></div>
    <div class="stat-card"><div class="v">${overallBest}</div><div class="l">Best streak (days)</div></div>
    <div class="stat-card"><div class="v small">${escapeHtml(mostName)}</div><div class="l">Most consistent habit</div></div>
    <div class="stat-card"><div class="v small">${escapeHtml(leastName)}</div><div class="l">Least consistent habit</div></div>
  `;
}

// Overall perfect-day streak across all daily/specific habits (weekly excluded from per-day calc)
function overallPerfectStreak(wantBest){
  const dailyHabits = habits.filter(h=>h.frequency!=='weekly');
  if(dailyHabits.length===0) return 0;
  const earliest = dailyHabits.reduce((min,h)=>{
    const c = habitCreatedDate(h); return c<min?c:min;
  }, today());
  const t = today();
  function perfectDay(d){
    const scheduled = dailyHabits.filter(h=>isScheduled(h,d) && habitCreatedDate(h)<=d);
    if(scheduled.length===0) return null; // no data that day
    return scheduled.every(h=>isCompleted(h,d));
  }
  if(!wantBest){
    let d = new Date(t);
    // grace for today if not finished
    const p = perfectDay(d);
    if(p===false) d = addDays(d,-1);
    let count=0, guard=0;
    while(d>=earliest && guard<3660){
      guard++;
      const res = perfectDay(d);
      if(res===null){ d = addDays(d,-1); continue; }
      if(res){ count++; d=addDays(d,-1); } else break;
    }
    return count;
  } else {
    let best=0, run=0;
    let d = new Date(earliest);
    let guard=0;
    while(d<=t && guard<3660){
      guard++;
      const res = perfectDay(d);
      if(res===true){ run++; best=Math.max(best,run); }
      else if(res===false){ run=0; }
      d = addDays(d,1);
    }
    return best;
  }
}

function renderBarChart(counts, numDays){
  const wrap = document.getElementById('bar-chart-inner');
  wrap.innerHTML='';
  const max = Math.max(1, ...counts);
  counts.forEach(c=>{
    const bar = document.createElement('div');
    bar.className = 'bar'+(c>0?' filled':'');
    const h = Math.max(3, (c/max)*100);
    bar.style.height = h+'%';
    wrap.appendChild(bar);
  });
}

function openDayDetail(d){
  const body = document.getElementById('day-body');
  document.getElementById('day-title').textContent = WEEKDAY_FULL[d.getDay()]+', '+MONTH_NAMES[d.getMonth()]+' '+d.getDate();
  const scheduled = habits.filter(h=>isScheduled(h,d) && habitCreatedDate(h)<=d);
  if(scheduled.length===0){
    body.innerHTML = `<p style="color:var(--text-secondary);font-size:14px;">No habits were scheduled on this day.</p>`;
  } else {
    body.innerHTML = scheduled.map(h=>{
      const done = isCompleted(h,d);
      return `<div class="habit-card" style="margin-bottom:10px;">
        <div class="habit-icon" style="--icon-bg:${rgbaFrom(h.color||settings.text,0.14)};--icon-color:${h.color||settings.text};">${iconSvg(h.icon)}</div>
        <div class="habit-info"><p class="habit-name">${escapeHtml(h.name)}</p></div>
        <div class="check-btn ${done?'checked':''}" style="pointer-events:none;">
          <svg viewBox="0 0 24 24" fill="none" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg>
        </div>
      </div>`;
    }).join('');
  }
  document.getElementById('overlay-day').classList.add('open');
}

function renderHabitStatSelector(){
  const sel = document.getElementById('habit-stat-select');
  const prev = selectedStatHabitId;
  sel.innerHTML = habits.map(h=>`<option value="${h.id}">${escapeHtml(h.name)}</option>`).join('');
  if(habits.length===0){
    document.getElementById('habit-stats-card').innerHTML = `<p style="color:var(--text-secondary);font-size:14px;text-align:center;padding:20px 0;">Add a habit to see its statistics here.</p>`;
    return;
  }
  selectedStatHabitId = (prev && habits.find(h=>h.id===prev)) ? prev : habits[0].id;
  sel.value = selectedStatHabitId;
  sel.onchange = ()=>{ selectedStatHabitId = sel.value; renderHabitStatCard(); };
  renderHabitStatCard();
}
function renderHabitStatCard(){
  const h = habits.find(x=>x.id===selectedStatHabitId);
  const card = document.getElementById('habit-stats-card');
  if(!h){ card.innerHTML=''; return; }
  const t = today();
  const days = monthRangeDays().filter(d=>startOfDay(d)<=t && habitCreatedDate(h)<=d);
  let scheduledCount=0, completedCount=0;
  days.forEach(d=>{
    if(isScheduled(h,d)){ scheduledCount++; if(isCompleted(h,d)) completedCount++; }
  });
  const pct = scheduledCount ? Math.round(completedCount/scheduledCount*100) : 0;
  card.innerHTML = `
    <div class="hsc-head">
      <div class="habit-icon" style="--icon-bg:${rgbaFrom(h.color||settings.text,0.14)};--icon-color:${h.color||settings.text};">${iconSvg(h.icon)}</div>
      <h3>${escapeHtml(h.name)}</h3>
    </div>
    <div class="hsc-rows">
      <div><div class="v">${completedCount} / ${scheduledCount}</div><div class="l">days this month</div></div>
      <div><div class="v">${pct}%</div><div class="l">completion</div></div>
      <div><div class="v">${currentStreak(h)}</div><div class="l">current streak</div></div>
      <div><div class="v">${bestStreak(h)}</div><div class="l">best streak</div></div>
    </div>
  `;
}

/* ======================================================================
   CUSTOMIZE TAB
   ====================================================================== */
function renderSwatchGroup(containerId, currentValRef, onPick){
  const container = document.getElementById(containerId);
  container.innerHTML='';
  ALL_SWATCHES.forEach(([name,hex])=>{
    const dot = document.createElement('div');
    dot.className = 'color-dot' + (currentValRef().toLowerCase()===hex.toLowerCase() ? ' sel':'');
    dot.style.background = hex;
    dot.title = name;
    if(hex.toLowerCase()==='#ffffff') dot.style.boxShadow = 'inset 0 0 0 1px rgba(0,0,0,.12)';
    dot.onclick = ()=>{ onPick(hex); };
    container.appendChild(dot);
  });
  // custom picker
  const customWrap = document.createElement('div');
  customWrap.className = 'custom-picker-btn';
  customWrap.innerHTML = `<svg viewBox="0 0 24 24" fill="none" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 20a8 8 0 1 1 0-16 6 6 0 0 1 6 6c0 1.7-1.3 3-3 3h-1.5a1.5 1.5 0 0 0 0 3H14a1 1 0 0 1 1 1c0 1.7-1.3 3-3 3Z"/><circle cx="7.5" cy="10.5" r=".8" fill="currentColor"/><circle cx="12" cy="7.5" r=".8" fill="currentColor"/><circle cx="15.5" cy="10" r=".8" fill="currentColor"/></svg><input type="color" id="${containerId}-custom">`;
  container.appendChild(customWrap);
  customWrap.querySelector('input').oninput = (e)=> onPick(e.target.value);
}
function renderCustomize(){
  renderSwatchGroup('bg-swatches', ()=>settings.bg, (hex)=>{ settings.bg=hex; commitSettings(); });
  renderSwatchGroup('text-swatches', ()=>settings.text, (hex)=>{ settings.text=hex; commitSettings(); });
  renderSwatchGroup('button-swatches', ()=>settings.button, (hex)=>{ settings.button=hex; commitSettings(); });

  document.querySelectorAll('#appearance-seg .seg-opt').forEach(b=>{
    b.classList.toggle('sel', b.dataset.v===settings.appearance);
  });
  document.getElementById('date-format-select').value = settings.dateFormat;
  document.getElementById('first-day-select').value = String(settings.firstDayOfWeek);
  document.getElementById('reminders-toggle').checked = settings.remindersEnabled;
  document.getElementById('default-reminder-time').value = settings.defaultReminderTime;

  renderPreview();
}
function renderPreview(){
  const wrap = document.getElementById('preview-inner');
  wrap.style.background = settings.bg;
  wrap.querySelector('.pv-title').style.color = settings.text;
  wrap.querySelector('.pv-date').style.color = rgbaFrom(settings.text,0.55);
  wrap.querySelector('.pv-date').textContent = formatHeaderDate(new Date());
  const rowsWrap = document.getElementById('preview-rows');
  const sample = [
    {n: habits[0] ? habits[0].name : 'Read', done:true},
    {n: habits[1] ? habits[1].name : 'Drink water', done:false},
    {n: habits[2] ? habits[2].name : 'Stretch', done:false},
  ];
  const borderCol = rgbaFrom(settings.text,0.12);
  rowsWrap.innerHTML = sample.map(s=>`
    <div class="pv-row" style="border-color:${borderCol};">
      <span class="pv-name" style="color:${settings.text};">${escapeHtml(s.n)}</span>
      <span class="pv-check" style="background:${s.done?settings.button:'transparent'};border:2px solid ${s.done?settings.button:borderCol};">
        ${s.done?'<svg viewBox="0 0 24 24" fill="none" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg>':''}
      </span>
    </div>
  `).join('');
  const addBtn = wrap.querySelector('.pv-add');
  addBtn.style.background = settings.button;
  addBtn.style.color = contrastText(settings.button);
}
function commitSettings(){
  saveSettings();
  applyTheme();
  renderCustomize();
  renderToday();
  renderStats();
}

/* ======================================================================
   EXPORT / IMPORT / RESET
   ====================================================================== */
function doExport(){
  const data = { version:1, exportedAt:new Date().toISOString(), habits, completions, settings };
  const json = JSON.stringify(data, null, 2);
  document.getElementById('export-textarea').value = json;
  document.getElementById('overlay-export').classList.add('open');
  document.getElementById('export-download-btn').onclick = ()=>{
    const blob = new Blob([json], {type:'application/json'});
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url; a.download = 'bloom-backup-'+dateStr(today())+'.json';
    document.body.appendChild(a); a.click(); document.body.removeChild(a);
    URL.revokeObjectURL(url);
  };
}
function doImport(file){
  const reader = new FileReader();
  reader.onload = (e)=>{
    try{
      const data = JSON.parse(e.target.result);
      if(!data || !Array.isArray(data.habits)) throw new Error('bad file');
      showConfirm('Import data?', 'This will replace your current habits, history, and settings with the imported backup.', 'Import', ()=>{
        habits = data.habits || [];
        completions = data.completions || {};
        settings = Object.assign({}, DEFAULT_SETTINGS, data.settings || {});
        saveHabits(); saveCompletions(); saveSettings();
        applyTheme();
        renderAll();
        showToast('Data imported');
      });
    }catch(err){
      showToast('Could not read that file');
    }
  };
  reader.readAsText(file);
}

/* ======================================================================
   NAVIGATION
   ====================================================================== */
function setTab(tab){
  document.querySelectorAll('.view').forEach(v=>v.classList.remove('active'));
  document.getElementById('view-'+tab).classList.add('active');
  document.querySelectorAll('.nav-btn').forEach(b=>b.classList.toggle('active', b.dataset.tab===tab));
  if(tab==='stats') renderStats();
  if(tab==='customize') renderCustomize();
  window.scrollTo(0,0);
}

/* ======================================================================
   INIT / EVENTS
   ====================================================================== */
function renderAll(){
  renderToday();
  renderStats();
  renderCustomize();
}

function init(){
  applyTheme();
  renderAll();

  document.querySelectorAll('.nav-btn').forEach(b=>{
    b.addEventListener('click', ()=>setTab(b.dataset.tab));
  });
  document.getElementById('fab-add').addEventListener('click', ()=>openEditor(null));
  document.getElementById('editor-cancel').addEventListener('click', closeEditor);
  document.getElementById('overlay-editor').addEventListener('click', (e)=>{ if(e.target.id==='overlay-editor') closeEditor(); });
  document.getElementById('editor-save').addEventListener('click', saveEditor);

  document.getElementById('ideas-entry-btn').addEventListener('click', ()=>{
    renderIdeas();
    document.getElementById('overlay-ideas').classList.add('open');
  });
  document.getElementById('ideas-close').addEventListener('click', ()=>document.getElementById('overlay-ideas').classList.remove('open'));
  document.getElementById('overlay-ideas').addEventListener('click', (e)=>{ if(e.target.id==='overlay-ideas') document.getElementById('overlay-ideas').classList.remove('open'); });

  document.getElementById('day-close').addEventListener('click', ()=>document.getElementById('overlay-day').classList.remove('open'));
  document.getElementById('overlay-day').addEventListener('click', (e)=>{ if(e.target.id==='overlay-day') document.getElementById('overlay-day').classList.remove('open'); });

  document.getElementById('month-prev').addEventListener('click', ()=>{
    statsMonth--; if(statsMonth<0){ statsMonth=11; statsYear--; } renderStats();
  });
  document.getElementById('month-next').addEventListener('click', ()=>{
    const t = today();
    if(statsYear===t.getFullYear() && statsMonth===t.getMonth()) return;
    statsMonth++; if(statsMonth>11){ statsMonth=0; statsYear++; } renderStats();
  });

  document.getElementById('appearance-seg').addEventListener('click', (e)=>{
    const btn = e.target.closest('.seg-opt'); if(!btn) return;
    settings.appearance = btn.dataset.v;
    if(settings.appearance==='light'){ settings.bg='#F7F7F5'; settings.text='#1D1D1F'; }
    else if(settings.appearance==='dark'){ settings.bg='#121214'; settings.text='#F2F2F4'; }
    else {
      const prefersDark = window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches;
      settings.bg = prefersDark ? '#121214' : '#F7F7F5';
      settings.text = prefersDark ? '#F2F2F4' : '#1D1D1F';
    }
    commitSettings();
  });
  if(window.matchMedia){
    window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change', (e)=>{
      if(settings.appearance==='system'){
        settings.bg = e.matches ? '#121214' : '#F7F7F5';
        settings.text = e.matches ? '#F2F2F4' : '#1D1D1F';
        commitSettings();
      }
    });
  }

  document.getElementById('date-format-select').addEventListener('change', (e)=>{ settings.dateFormat = e.target.value; commitSettings(); });
  document.getElementById('first-day-select').addEventListener('change', (e)=>{ settings.firstDayOfWeek = parseInt(e.target.value,10); commitSettings(); });
  document.getElementById('reminders-toggle').addEventListener('change', (e)=>{ settings.remindersEnabled = e.target.checked; saveSettings(); });
  document.getElementById('default-reminder-time').addEventListener('change', (e)=>{ settings.defaultReminderTime = e.target.value; saveSettings(); });

  document.getElementById('export-data-row').addEventListener('click', doExport);
  document.getElementById('export-close').addEventListener('click', ()=>document.getElementById('overlay-export').classList.remove('open'));
  document.getElementById('overlay-export').addEventListener('click', (e)=>{ if(e.target.id==='overlay-export') document.getElementById('overlay-export').classList.remove('open'); });

  document.getElementById('import-data-row').addEventListener('click', ()=>document.getElementById('import-file-input').click());
  document.getElementById('import-file-input').addEventListener('change', (e)=>{
    const file = e.target.files[0];
    if(file) doImport(file);
    e.target.value='';
  });

  document.getElementById('reset-data-row').addEventListener('click', ()=>{
    showConfirm('Reset all data?', 'All habits, history, and settings will be permanently deleted. This cannot be undone.', 'Reset', ()=>{
      habits = []; completions = {}; settings = Object.assign({}, DEFAULT_SETTINGS);
      saveHabits(); saveCompletions(); saveSettings();
      applyTheme(); renderAll();
      showToast('All data reset');
    });
  });

  document.getElementById('reset-colors-btn').addEventListener('click', ()=>{
    settings.bg = DEFAULT_SETTINGS.bg; settings.text = DEFAULT_SETTINGS.text; settings.button = DEFAULT_SETTINGS.button; settings.appearance='light';
    commitSettings();
    showToast('Colors reset to default');
  });

  // register a lightweight service worker for offline caching (best-effort)
  if('serviceWorker' in navigator){
    try{
      const swCode = `
        self.addEventListener('install', e=>self.skipWaiting());
        self.addEventListener('activate', e=>self.clients.claim());
        self.addEventListener('fetch', e=>{});
      `;
      const blob = new Blob([swCode], {type:'application/javascript'});
      navigator.serviceWorker.register(URL.createObjectURL(blob)).catch(()=>{});
    }catch(e){}
  }
}
document.addEventListener('DOMContentLoaded', init);
})();
</script>
</body>
</html>

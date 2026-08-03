:root{
  --bg:#F2FAF6;
  --surface:#FFFFFF;
  --ink:#152B22;
  --muted:#6C8579;
  --primary:#0E9F82;
  --primary-dark:#0A7F66;
  --primary-tint:#E1F4EE;
  --coral:#FF8A65;
  --coral-tint:#FFE9E1;
  --yellow:#FFC857;
  --ring-track:#DCEFE7;
  --line:#E4EFEA;
  --radius:18px;
  --shadow:0 6px 20px rgba(21,43,34,0.06);
  font-size:16px;
}

*{box-sizing:border-box;}

html,body{
  margin:0;
  padding:0;
  background:var(--bg);
  color:var(--ink);
  font-family:-apple-system,BlinkMacSystemFont,"SF Pro Text","Segoe UI",Roboto,sans-serif;
  -webkit-tap-highlight-color:transparent;
}

.app{
  max-width:480px;
  margin:0 auto;
  min-height:100vh;
  padding-bottom:calc(24px + env(safe-area-inset-bottom));
}

/* ---------- Topbar ---------- */
.topbar{
  display:flex;
  align-items:center;
  justify-content:space-between;
  padding:calc(14px + env(safe-area-inset-top)) 20px 10px;
}
.brand{display:flex;align-items:center;gap:10px;}
.leaf-mark{
  width:38px;height:38px;border-radius:12px;
  background:linear-gradient(155deg,var(--primary),var(--primary-dark));
  color:#fff;display:flex;align-items:center;justify-content:center;
  box-shadow:var(--shadow);
}
.brand h1{font-size:17px;margin:0;font-weight:700;letter-spacing:-0.01em;}
.subtitle{margin:0;font-size:12px;color:var(--muted);}
.icon-btn{
  width:38px;height:38px;border-radius:50%;border:none;
  background:var(--surface);color:var(--primary-dark);
  display:flex;align-items:center;justify-content:center;
  box-shadow:var(--shadow);cursor:pointer;
}
.icon-btn.small{width:32px;height:32px;font-size:18px;color:var(--ink);}
.icon-btn.active{background:var(--primary);color:#fff;}

/* ---------- Tabs ---------- */
.tabs{
  display:flex;gap:6px;padding:0 20px 14px;
}
.tab{
  flex:1;padding:9px 0;border:none;border-radius:999px;
  background:transparent;color:var(--muted);font-size:13.5px;font-weight:600;
  cursor:pointer;
}
.tab.active{background:var(--primary);color:#fff;}

main{padding:0 20px;}
.panel{display:none;}
.panel.active{display:block;animation:fade .25s ease;}
@keyframes fade{from{opacity:0;transform:translateY(4px);}to{opacity:1;transform:none;}}

/* ---------- Progress card ---------- */
.progress-card{
  background:var(--surface);border-radius:var(--radius);
  box-shadow:var(--shadow);padding:18px;display:flex;gap:16px;align-items:center;
  margin-bottom:18px;
}
.progress-ring-wrap{position:relative;width:88px;height:88px;flex:none;}
.progress-ring{width:88px;height:88px;transform:rotate(-90deg);}
.ring-bg{fill:none;stroke:var(--ring-track);stroke-width:9;}
.ring-fill{
  fill:none;stroke:var(--primary);stroke-width:9;stroke-linecap:round;
  stroke-dasharray:264;stroke-dashoffset:264;
  transition:stroke-dashoffset .5s ease;
}
.progress-label{
  position:absolute;inset:0;display:flex;flex-direction:column;
  align-items:center;justify-content:center;
}
.progress-label span{font-size:19px;font-weight:800;color:var(--primary-dark);}
.progress-label small{font-size:10px;color:var(--muted);}
.stem-wrap{flex:1;min-width:0;}
.stem-caption{margin:0 0 6px;font-size:12px;color:var(--muted);font-weight:600;}
.stem-svg{width:100%;height:44px;display:block;}

/* ---------- Date heading ---------- */
.date-heading{
  font-size:13px;color:var(--muted);font-weight:600;
  text-transform:capitalize;margin:0 0 10px 2px;
}

/* ---------- Meals ---------- */
.meal-list{display:flex;flex-direction:column;gap:12px;}
.meal-card{
  background:var(--surface);border-radius:var(--radius);
  box-shadow:var(--shadow);padding:14px 16px 16px;
}
.meal-card-head{
  display:flex;align-items:baseline;justify-content:space-between;margin-bottom:8px;
}
.meal-time{
  font-size:12px;font-weight:700;color:var(--primary-dark);
  background:var(--primary-tint);padding:2px 9px;border-radius:999px;
}
.meal-name{font-size:15.5px;font-weight:700;margin:0;flex:1;padding-left:10px;}
.meal-optional-badge{
  font-size:10px;font-weight:700;color:var(--muted);background:var(--line);
  padding:2px 8px;border-radius:999px;text-transform:uppercase;letter-spacing:.03em;
  flex:none;
}
.meal-note{
  font-size:12px;color:var(--coral);background:var(--coral-tint);
  border-radius:10px;padding:6px 10px;margin:6px 0 10px;
}

.item-row{margin-bottom:10px;}
.item-row:last-child{margin-bottom:0;}
.option-pills{display:flex;flex-wrap:wrap;gap:6px;}
.pill{
  border:1.5px solid var(--line);background:#fff;color:var(--ink);
  font-size:12.5px;padding:7px 12px;border-radius:999px;cursor:pointer;
  line-height:1.25;transition:.15s;
}
.pill.chosen{background:var(--primary);border-color:var(--primary);color:#fff;font-weight:600;}
.pill .check{margin-right:4px;}
.pill.custom-active{background:var(--coral);border-color:var(--coral);color:#fff;font-weight:600;}
.swap-toggle{
  border:none;background:none;color:var(--coral);font-size:12px;font-weight:700;
  padding:6px 2px;cursor:pointer;display:inline-flex;align-items:center;gap:4px;
}
.custom-input-wrap{display:none;margin-top:7px;gap:6px;}
.custom-input-wrap.show{display:flex;}
.custom-input-wrap input{
  flex:1;border:1.5px solid var(--line);border-radius:10px;padding:8px 10px;font-size:13px;
  font-family:inherit;
}
.custom-input-wrap button{
  border:none;background:var(--primary);color:#fff;border-radius:10px;
  padding:0 14px;font-size:13px;font-weight:700;cursor:pointer;
}

/* ---------- Calendar ---------- */
.cal-header{display:flex;align-items:center;justify-content:space-between;margin:6px 0 12px;}
.cal-header h2{font-size:15.5px;margin:0;font-weight:700;text-transform:capitalize;}
.cal-weekdays{
  display:grid;grid-template-columns:repeat(7,1fr);text-align:center;
  font-size:11px;color:var(--muted);font-weight:700;margin-bottom:4px;
}
.cal-grid{display:grid;grid-template-columns:repeat(7,1fr);gap:4px;}
.cal-cell{
  aspect-ratio:1;border-radius:12px;border:none;background:var(--surface);
  display:flex;flex-direction:column;align-items:center;justify-content:center;
  gap:3px;font-size:13px;font-weight:600;color:var(--ink);cursor:pointer;
  box-shadow:0 2px 6px rgba(21,43,34,0.04);
}
.cal-cell.empty{background:transparent;box-shadow:none;cursor:default;}
.cal-cell.today{outline:2px solid var(--primary);}
.cal-cell.selected{background:var(--primary-tint);}
.cal-cell .dot{width:6px;height:6px;border-radius:50%;background:var(--ring-track);}
.cal-cell .dot.full{background:var(--primary);}
.cal-cell .dot.partial{background:var(--yellow);}
.cal-legend{display:flex;gap:14px;justify-content:center;margin:14px 0 6px;font-size:11.5px;color:var(--muted);}
.cal-legend .dot{display:inline-block;width:8px;height:8px;border-radius:50%;margin-right:5px;vertical-align:middle;}
.dot.full{background:var(--primary);}
.dot.partial{background:var(--yellow);}
.dot.none{background:var(--ring-track);}
.cal-day-detail{margin-top:10px;}
.cal-day-detail h3{font-size:13.5px;margin:14px 0 8px;text-transform:capitalize;color:var(--muted);}

/* ---------- Recipe ---------- */
.recipe-card{
  background:var(--surface);border-radius:var(--radius);box-shadow:var(--shadow);
  padding:18px;margin-top:6px;
}
.recipe-hero{display:flex;align-items:center;gap:12px;margin-bottom:16px;}
.recipe-photo{
  width:56px;height:56px;border-radius:14px;background:var(--primary-tint);
  display:flex;align-items:center;justify-content:center;font-size:26px;flex:none;
}
.recipe-hero h2{margin:0;font-size:17px;}
.recipe-author{margin:1px 0;font-size:12px;color:var(--muted);}
.recipe-meta{margin:0;font-size:11.5px;color:var(--muted);}
.recipe-card h3{font-size:13px;color:var(--primary-dark);text-transform:uppercase;letter-spacing:.03em;margin:16px 0 8px;}
.ingredient-list,.steps-list{margin:0;padding-left:20px;font-size:14px;line-height:1.6;}
.nutrition-table{width:100%;border-collapse:collapse;font-size:13px;}
.nutrition-table td{padding:7px 4px;border-bottom:1px solid var(--line);}
.nutrition-table tr:last-child td{border-bottom:none;}
.muted{color:var(--muted);}

/* ---------- Toast ---------- */
.toast{
  position:fixed;left:50%;bottom:calc(24px + env(safe-area-inset-bottom));
  transform:translateX(-50%) translateY(20px);
  background:var(--ink);color:#fff;padding:10px 18px;border-radius:999px;
  font-size:13px;opacity:0;pointer-events:none;transition:.25s;z-index:50;
  max-width:88%;text-align:center;
}
.toast.show{opacity:1;transform:translateX(-50%) translateY(0);}

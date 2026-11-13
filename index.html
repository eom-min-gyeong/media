<!DOCTYPE html>
<html lang="ko" data-theme="light">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>MEDIA PROD STUDIO // 3-Col NLE Console & Call Sheet</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans+KR:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css">
<style>
/* ===== 기본값: 야외 촬영용 고대비 데이라이트 (Daylight Outdoor) ===== */
:root,
:root[data-theme="light"] {
  --bg-deep: #E8EEF5;
  --bg-topbar: #FFFFFF;
  --bg-panel: #F8FAFC;
  --bg-panel-head: #EEF2F7;
  --bg-rack: #EBF0F7;
  --bg-card: #FFFFFF;
  --bg-card-hover: #F1F5F9;
  --bg-input: #FFFFFF;
  --bg-sched: #EEF3F9;
  --bg-tl-bar: #DCE4F0;
  
  --ink: #0F172A;
  --ink-sub: #334155;
  --ink-muted: #64748B;
  
  --line: #CBD5E1;
  --line-bright: #94A3B8;
  
  --neon-cyan: #0284C7;
  --neon-cyan-soft: rgba(2, 132, 199, 0.12);
  --neon-cyan-glow: rgba(2, 132, 199, 0.25);
  
  --neon-yellow: #D97706;
  --neon-yellow-soft: rgba(217, 119, 6, 0.14);
  --neon-yellow-glow: rgba(217, 119, 6, 0.28);
  
  --neon-green: #059669;
  --neon-green-soft: rgba(5, 150, 105, 0.12);
  --neon-green-glow: rgba(5, 150, 105, 0.25);
  
  --neon-red: #E11D48;
  --neon-red-soft: rgba(225, 29, 72, 0.14);
  
  --btn-cyan-ink: #FFFFFF;
  --btn-green-ink: #FFFFFF;
  --btn-yellow-ink: #FFFFFF;

  --font-sans: "IBM Plex Sans KR", -apple-system, BlinkMacSystemFont, system-ui, sans-serif;
  --font-mono: "JetBrains Mono", monospace;
  
  color-scheme: light;
  box-sizing: border-box;
}

/* ===== 전환 모드: 시네마틱 다크 스튜디오 (Premiere Pro / DaVinci Resolve) ===== */
:root[data-theme="dark"] {
  --bg-deep: #0B0D11;
  --bg-topbar: #0D1016;
  --bg-panel: #12151C;
  --bg-panel-head: #151922;
  --bg-rack: #181C26;
  --bg-card: #1D222E;
  --bg-card-hover: #232A39;
  --bg-input: #0E1117;
  --bg-sched: #0F131A;
  --bg-tl-bar: #080A0E;
  
  --ink: #EEF2F8;
  --ink-sub: #94A0B8;
  --ink-muted: #5E6A82;
  
  --line: #283040;
  --line-bright: #384359;
  
  --neon-cyan: #00F0FF;
  --neon-cyan-soft: rgba(0, 240, 255, 0.14);
  --neon-cyan-glow: rgba(0, 240, 255, 0.38);
  
  --neon-yellow: #FFE600;
  --neon-yellow-soft: rgba(255, 230, 0, 0.15);
  --neon-yellow-glow: rgba(255, 230, 0, 0.35);
  
  --neon-green: #00FF87;
  --neon-green-soft: rgba(0, 255, 135, 0.14);
  --neon-green-glow: rgba(0, 255, 135, 0.35);
  
  --neon-red: #FF3366;
  --neon-red-soft: rgba(255, 51, 102, 0.16);
  
  --btn-cyan-ink: #06090E;
  --btn-green-ink: #05100A;
  --btn-yellow-ink: #121000;
  
  color-scheme: dark;
}

* { box-sizing: border-box; }
[hidden] { display: none !important; }

html, body {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100vh;
  overflow: hidden;
  background: var(--bg-deep);
  color: var(--ink);
  font: 400 13px/1.5 var(--font-sans);
  -webkit-font-smoothing: antialiased;
  transition: background-color 0.2s ease, color 0.2s ease;
}

::-webkit-scrollbar { width: 6px; height: 6px; }
::-webkit-scrollbar-track { background: var(--bg-deep); }
::-webkit-scrollbar-thumb { background: var(--line-bright); border-radius: 3px; }
::-webkit-scrollbar-thumb:hover { background: var(--neon-cyan); }

.app-shell {
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 100vh;
}

/* ===== 상단 NLE 콘솔 헤더 ===== */
.top-bar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
  padding: 8px 14px;
  background: var(--bg-topbar);
  border-bottom: 1px solid var(--line);
  flex-shrink: 0;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);
}

.brand-area {
  display: flex;
  align-items: center;
  gap: 10px;
}

.rec-dot {
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--neon-red);
  box-shadow: 0 0 8px var(--neon-red);
  animation: pulseRec 2s infinite ease-in-out;
}
@keyframes pulseRec {
  0%, 100% { opacity: 1; transform: scale(1); }
  50% { opacity: 0.45; transform: scale(0.88); }
}

.brand-area h1 {
  font-size: 14px;
  font-weight: 700;
  margin: 0;
  letter-spacing: 0.02em;
  display: flex;
  align-items: center;
  gap: 8px;
}

.nle-tag {
  font-family: var(--font-mono);
  font-size: 10px;
  font-weight: 700;
  color: var(--btn-cyan-ink);
  background: var(--neon-cyan);
  padding: 2px 6px;
  border-radius: 3px;
  letter-spacing: 0.05em;
}

.timecode-box {
  font-family: var(--font-mono);
  font-size: 12px;
  font-weight: 600;
  color: var(--neon-yellow);
  background: var(--bg-input);
  border: 1px solid var(--line);
  padding: 3px 10px;
  border-radius: 4px;
  letter-spacing: 0.06em;
}

.global-controls {
  display: flex;
  align-items: center;
  gap: 8px;
  flex-wrap: wrap;
}

.ctrl-pill {
  display: flex;
  align-items: center;
  gap: 6px;
  background: var(--bg-rack);
  border: 1px solid var(--line);
  padding: 4px 10px;
  border-radius: 4px;
  font-size: 12px;
  color: var(--ink-sub);
}

.theme-toggle-btn {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  font: inherit;
  font-size: 12px;
  font-weight: 700;
  padding: 5px 11px;
  border-radius: 4px;
  border: 1px solid var(--neon-yellow);
  background: var(--neon-yellow-soft);
  color: var(--neon-yellow);
  cursor: pointer;
  transition: all 0.15s ease;
}
.theme-toggle-btn:hover {
  background: var(--neon-yellow);
  color: var(--btn-yellow-ink);
}

input[type=search], input[type=text], input[type=password], select, textarea {
  font: inherit;
  font-size: 12px;
  padding: 5px 8px;
  border: 1px solid var(--line);
  border-radius: 4px;
  background: var(--bg-input);
  color: var(--ink);
  min-width: 0;
  transition: border-color 0.15s, box-shadow 0.15s;
}
input:focus, select:focus, textarea:focus {
  outline: none;
  border-color: var(--neon-cyan);
  box-shadow: 0 0 0 2px var(--neon-cyan-soft);
}

.btn {
  font: inherit;
  font-size: 12px;
  font-weight: 600;
  padding: 6px 12px;
  border: 1px solid transparent;
  border-radius: 4px;
  background: var(--neon-cyan);
  color: var(--btn-cyan-ink);
  cursor: pointer;
  white-space: nowrap;
  transition: all 0.15s ease;
}
.btn:hover { filter: brightness(1.08); }
.btn.green { background: var(--neon-green); color: var(--btn-green-ink); }
.btn.yellow { background: var(--neon-yellow); color: var(--btn-yellow-ink); }
.btn.s {
  background: var(--bg-rack);
  color: var(--ink-sub);
  border: 1px solid var(--line);
  padding: 4px 9px;
  font-size: 11px;
}
.btn.s:hover {
  border-color: var(--neon-cyan);
  color: var(--neon-cyan);
  background: var(--neon-cyan-soft);
}

/* ===== 고정형 세로 3단 분할 워크스페이스 ===== */
.workspace {
  display: flex;
  flex-direction: row;
  flex: 1;
  min-height: 0;
  width: 100%;
  overflow-x: auto;
  overflow-y: hidden;
  user-select: none;
  padding: 6px;
  gap: 0;
  background: var(--bg-deep);
}

.pane {
  display: flex;
  flex-direction: column;
  min-width: 290px;
  height: 100%;
  overflow: hidden;
  background: var(--bg-panel);
  border: 1px solid var(--line);
  border-radius: 6px;
  user-select: text;
}

#pane-1 { flex: 28 1 0%; }
#pane-2 { flex: 38 1 0%; }
#pane-3 { flex: 34 1 0%; }

.gutter {
  width: 10px;
  flex-shrink: 0;
  cursor: col-resize;
  background: var(--bg-deep);
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  z-index: 20;
}
.gutter::before {
  content: "";
  width: 2px;
  height: 44px;
  background: var(--line-bright);
  border-radius: 2px;
  transition: all 0.15s;
}
.gutter:hover::before, .gutter.dragging::before {
  background: var(--neon-cyan);
  height: 76px;
}

.pane-head {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 12px;
  background: var(--bg-panel-head);
  border-bottom: 1px solid var(--line);
  flex-shrink: 0;
}
.pane-head h2 {
  font-size: 12px;
  font-weight: 700;
  margin: 0;
  text-transform: uppercase;
  letter-spacing: 0.04em;
  display: flex;
  align-items: center;
  gap: 7px;
  color: var(--ink);
}
.pane-num {
  font-family: var(--font-mono);
  font-size: 10px;
  font-weight: 700;
  padding: 1px 5px;
  border-radius: 3px;
  background: var(--bg-input);
  border: 1px solid var(--line-bright);
  color: var(--neon-cyan);
}
.pane-head .meta {
  font-family: var(--font-mono);
  font-size: 11px;
  color: var(--ink-sub);
}

.pane-body {
  flex: 1;
  overflow-y: auto;
  padding: 10px 12px 24px;
}

/* ===== 진행 기관 공식 파비콘 배지 ===== */
.org-badge {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  text-decoration: none;
  color: var(--ink-sub);
  font-size: 11px;
  font-weight: 500;
  max-width: 100%;
}
.org-badge:hover { color: var(--neon-cyan); }
.org-logo-wrap {
  width: 18px;
  height: 18px;
  border-radius: 4px;
  background: var(--bg-input);
  border: 1px solid var(--line-bright);
  display: inline-flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  flex-shrink: 0;
}
.org-logo-wrap img {
  width: 13px;
  height: 13px;
  object-fit: contain;
  display: block;
}
.org-fallback {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: var(--font-mono);
  font-size: 8px;
  font-weight: 700;
  color: #080A0F;
}
.org-name {
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

/* ===== PANE 1: 지원사업 브리핑 ===== */
.hero-mini {
  background: linear-gradient(135deg, var(--neon-yellow-soft), var(--neon-cyan-soft));
  border: 1px solid var(--neon-yellow);
  border-left: 3px solid var(--neon-yellow);
  border-radius: 5px;
  padding: 10px 12px;
  margin-bottom: 10px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 10px;
}
.hero-mini .d-val {
  font-family: var(--font-mono);
  font-size: 24px;
  font-weight: 700;
  color: var(--neon-yellow);
  line-height: 1;
  white-space: nowrap;
}
.hero-mini .h-info { flex: 1; min-width: 0; }
.hero-mini .h-title {
  font-weight: 700;
  font-size: 13px;
  color: var(--ink);
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  margin: 2px 0;
}
.hero-mini .h-sub { font-size: 11px; color: var(--ink-sub); }

.filter-stack {
  display: flex;
  flex-direction: column;
  gap: 7px;
  margin-bottom: 10px;
  background: var(--bg-rack);
  padding: 8px;
  border-radius: 5px;
  border: 1px solid var(--line);
}
.filter-row { display: flex; gap: 6px; align-items: center; flex-wrap: wrap; }
.filter-row input[type=search] { flex: 1; }

.chips { display: flex; flex-wrap: wrap; gap: 4px; }
.chip {
  font: inherit;
  font-size: 11px;
  font-weight: 500;
  padding: 3px 8px;
  border: 1px solid var(--line);
  background: var(--bg-input);
  color: var(--ink-sub);
  border-radius: 3px;
  cursor: pointer;
}
.chip[aria-pressed=true] {
  background: var(--neon-cyan-soft);
  border-color: var(--neon-cyan);
  color: var(--neon-cyan);
  font-weight: 700;
}

.card {
  background: var(--bg-card);
  border: 1px solid var(--line);
  border-radius: 5px;
  padding: 10px;
  margin-bottom: 7px;
}
.card:hover { background: var(--bg-card-hover); border-color: var(--line-bright); }
.card.highlight-pulse {
  border-color: var(--neon-yellow);
  box-shadow: 0 0 0 2px var(--neon-yellow-glow);
}
.card .top {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 6px;
  margin-bottom: 5px;
}
.badge {
  font-family: var(--font-mono);
  font-weight: 700;
  font-size: 10px;
  padding: 2px 6px;
  border-radius: 3px;
  background: var(--neon-cyan-soft);
  color: var(--neon-cyan);
  border: 1px solid var(--neon-cyan);
}
.badge.hot {
  background: var(--neon-yellow-soft);
  color: var(--neon-yellow);
  border-color: var(--neon-yellow);
}
.tag {
  font-family: var(--font-mono);
  font-size: 10px;
  color: var(--neon-green);
  background: var(--neon-green-soft);
  border: 1px solid var(--neon-green);
  padding: 1px 6px;
  border-radius: 3px;
  font-weight: 600;
}
.ti { font-weight: 700; font-size: 13px; line-height: 1.35; color: var(--ink); }
.sub { font-size: 11px; color: var(--ink-sub); }
.amt {
  font-family: var(--font-mono);
  font-weight: 600;
  font-size: 11px;
  color: var(--neon-yellow);
  margin-top: 3px;
}

.sec-divider {
  font-family: var(--font-mono);
  font-size: 11px;
  font-weight: 700;
  color: var(--neon-cyan);
  margin: 12px 0 6px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid var(--line);
  padding-bottom: 4px;
  text-transform: uppercase;
}

/* ===== PANE 2: 촬영 동선 지도 & 렌탈 & 연관 로케 지원 ===== */
.shoot-box {
  background: var(--bg-rack);
  border: 1px solid var(--line);
  border-left: 3px solid var(--neon-green);
  border-radius: 5px;
  padding: 9px 10px;
  margin-bottom: 9px;
}
.shoot-head {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 6px;
}
.shoot-head h3 { font-size: 12px; margin: 0; color: var(--neon-green); font-weight: 700; }
.shoot-input-row { display: flex; gap: 5px; margin-bottom: 6px; }
.shoot-input-row input { flex: 1; }

.preset-bar {
  display: flex;
  gap: 4px;
  flex-wrap: wrap;
  align-items: center;
  font-size: 11px;
  color: var(--ink-sub);
  margin-bottom: 6px;
}
.preset-btn {
  font: inherit;
  font-size: 10px;
  padding: 2px 7px;
  border-radius: 3px;
  border: 1px dashed var(--neon-green);
  background: var(--neon-green-soft);
  color: var(--neon-green);
  cursor: pointer;
  font-weight: 600;
}

.shoot-tags { display: flex; flex-wrap: wrap; gap: 4px; align-items: center; }
.shoot-tag {
  display: inline-flex;
  align-items: center;
  gap: 4px;
  background: var(--bg-card);
  border: 1px solid var(--neon-green);
  color: var(--ink);
  padding: 2px 7px;
  border-radius: 3px;
  font-size: 11px;
  font-weight: 600;
}
.shoot-tag .step {
  font-family: var(--font-mono);
  background: var(--neon-green);
  color: var(--btn-green-ink);
  border-radius: 2px;
  padding: 0 4px;
  font-size: 10px;
  font-weight: 700;
}
.shoot-tag button { border: 0; background: none; color: var(--ink-sub); cursor: pointer; padding: 0 2px; font-size: 11px; }

#map-box {
  position: relative;
  height: 225px;
  border-radius: 5px;
  border: 1px solid var(--line-bright);
  overflow: hidden;
  background: var(--bg-input);
  margin-bottom: 9px;
}
#rental-map { width: 100%; height: 100%; z-index: 1; }
.map-overlay {
  position: absolute;
  top: 7px;
  left: 7px;
  z-index: 500;
  background: var(--bg-card);
  opacity: 0.92;
  padding: 3px 8px;
  border-radius: 4px;
  font-family: var(--font-mono);
  font-size: 10px;
  font-weight: 600;
  color: var(--neon-cyan);
  border: 1px solid var(--line-bright);
  pointer-events: none;
}

.loc-support-box {
  background: var(--neon-yellow-soft);
  border: 1px solid var(--neon-yellow);
  border-radius: 5px;
  padding: 8px 10px;
  margin-bottom: 9px;
}
.loc-support-head {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 6px;
}
.loc-support-head h4 { font-size: 11px; margin: 0; color: var(--neon-yellow); font-weight: 700; }
.loc-sup-card {
  background: var(--bg-card);
  border: 1px solid var(--line);
  border-radius: 4px;
  padding: 7px 9px;
  margin-bottom: 5px;
  cursor: pointer;
}
.loc-sup-card:hover { border-color: var(--neon-yellow); }

.sort-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 6px;
  margin-bottom: 7px;
  flex-wrap: wrap;
}
.rental-card { cursor: pointer; }
.rental-card.active { border-color: var(--neon-cyan); background: var(--neon-cyan-soft); }
.num-pin {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 19px;
  height: 19px;
  border-radius: 4px;
  background: var(--neon-cyan);
  color: var(--btn-cyan-ink);
  font-family: var(--font-mono);
  font-size: 11px;
  font-weight: 700;
}
.rental-card.best .num-pin { background: var(--neon-yellow); color: var(--btn-yellow-ink); }
.price-badge { font-family: var(--font-mono); font-size: 12px; font-weight: 700; color: var(--neon-cyan); }
.route-metrics { display: flex; flex-wrap: wrap; gap: 4px; margin-top: 5px; font-family: var(--font-mono); font-size: 10px; }
.metric-pill { background: var(--bg-input); border: 1px solid var(--line); padding: 1px 6px; border-radius: 3px; color: var(--ink-sub); }
.metric-pill.hi { color: var(--neon-green); border-color: var(--neon-green); background: var(--neon-green-soft); font-weight: 600; }

.custom-pin {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 26px;
  height: 26px;
  border-radius: 50% 50% 50% 0;
  background: var(--neon-cyan);
  color: var(--btn-cyan-ink);
  font-family: var(--font-mono);
  font-weight: 700;
  font-size: 11px;
  transform: rotate(-45deg);
  border: 2px solid var(--bg-card);
  box-shadow: 0 2px 8px rgba(0,0,0,0.35);
}
.custom-pin.best { background: var(--neon-yellow); color: var(--btn-yellow-ink); }
.custom-pin span { transform: rotate(45deg); }

.shoot-pin {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 28px;
  height: 28px;
  border-radius: 6px;
  background: var(--neon-green);
  color: var(--btn-green-ink);
  font-family: var(--font-mono);
  font-weight: 700;
  font-size: 11px;
  border: 2px solid var(--bg-card);
  box-shadow: 0 2px 8px rgba(0,0,0,0.35);
}

/* ===== PANE 3: 촬영 캘린더 & 타임라인 스케줄러 ===== */
.cal-toolbar { display: flex; justify-content: space-between; align-items: center; margin-bottom: 6px; }
.cal-toolbar h3 { font-family: var(--font-mono); font-size: 14px; margin: 0; color: var(--ink); }
.cal-hint {
  font-size: 11px;
  color: var(--neon-cyan);
  background: var(--neon-cyan-soft);
  border: 1px solid var(--neon-cyan);
  padding: 5px 8px;
  border-radius: 4px;
  margin-bottom: 8px;
}

.calh, .cal { display: grid; grid-template-columns: repeat(7, 1fr); gap: 3px; user-select: none; }
.calh div { font-family: var(--font-mono); font-size: 10px; color: var(--ink-muted); text-align: center; padding-bottom: 3px; }
.cell {
  min-height: 64px;
  text-align: left;
  font: inherit;
  font-size: 10px;
  line-height: 1.25;
  padding: 4px;
  border: 1px solid var(--line);
  border-radius: 4px;
  background: var(--bg-card);
  color: var(--ink);
  cursor: pointer;
  display: flex;
  flex-direction: column;
  gap: 2px;
  overflow: hidden;
}
.cell.blank { border: 0; background: transparent; cursor: default; min-height: 0; }
.cell.in-range { background: var(--neon-cyan-soft); border-color: var(--neon-cyan); }
.cell.range-edge { border-width: 2px; border-color: var(--neon-cyan); }
.cell.today .dn { color: var(--neon-yellow); text-decoration: underline; }
.dn { font-family: var(--font-mono); font-weight: 700; font-size: 11px; }
.wx-mini { font-family: var(--font-mono); font-size: 9px; color: var(--ink-sub); white-space: nowrap; }
.ev-dot {
  background: var(--neon-green-soft);
  color: var(--neon-green);
  border-left: 2px solid var(--neon-green);
  border-radius: 2px;
  padding: 1px 3px;
  font-size: 9px;
  font-weight: 600;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

.sched-box {
  margin-top: 10px;
  background: var(--bg-sched);
  border: 1px solid var(--line-bright);
  border-radius: 6px;
  padding: 10px;
}
.sched-head { display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 6px; gap: 6px; flex-wrap: wrap; }
.sched-head h4 { font-size: 12px; margin: 0; color: var(--neon-yellow); font-family: var(--font-mono); }

.tl-wrap { margin: 8px 0 10px; user-select: none; }
.tl-labels { display: flex; justify-content: space-between; font-family: var(--font-mono); font-size: 10px; color: var(--ink-muted); margin-bottom: 3px; }
.tl-bar {
  position: relative;
  height: 44px;
  background: var(--bg-tl-bar);
  border: 1px solid var(--line-bright);
  border-radius: 4px;
  cursor: crosshair;
  overflow: hidden;
  touch-action: none;
}
.tl-daylight { position: absolute; top: 0; bottom: 0; background: rgba(255, 255, 255, 0.25); pointer-events: none; }
.tl-golden {
  position: absolute;
  top: 0;
  bottom: 0;
  background: var(--neon-yellow-soft);
  border-left: 1px dashed var(--neon-yellow);
  border-right: 1px dashed var(--neon-yellow);
  pointer-events: none;
}
.tl-grid { position: absolute; inset: 0; display: grid; grid-template-columns: repeat(24, 1fr); pointer-events: none; }
.tl-grid div { border-right: 1px solid rgba(128, 128, 128, 0.15); height: 100%; }
.tl-grid div:nth-child(6n) { border-right: 1px solid rgba(128, 128, 128, 0.35); }

.tl-sel {
  position: absolute;
  top: 4px;
  bottom: 4px;
  background: var(--neon-cyan-soft);
  border-top: 2px solid var(--neon-cyan);
  border-bottom: 2px solid var(--neon-cyan);
  border-radius: 4px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  color: var(--ink);
  font-family: var(--font-mono);
  font-size: 11px;
  font-weight: 700;
  cursor: grab;
  z-index: 5;
  min-width: 24px;
}
.tl-sel-label {
  flex: 1;
  text-align: center;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  pointer-events: none;
  padding: 0 4px;
  color: var(--neon-cyan);
}
.tl-handle {
  width: 12px;
  height: 100%;
  background: var(--neon-cyan);
  color: var(--btn-cyan-ink);
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: ew-resize;
  font-size: 8px;
  font-weight: 900;
  flex-shrink: 0;
}
.tl-handle:hover, .tl-handle.active { background: var(--neon-yellow); color: var(--btn-yellow-ink); }

.time-adjust-bar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 6px;
  margin-top: 6px;
  background: var(--bg-rack);
  padding: 5px 8px;
  border-radius: 4px;
  border: 1px solid var(--line);
  font-size: 11px;
}
.time-nudge-group { display: flex; align-items: center; gap: 3px; font-family: var(--font-mono); }
.nudge-btn {
  font-family: var(--font-mono);
  font-size: 10px;
  padding: 2px 5px;
  border: 1px solid var(--line-bright);
  border-radius: 3px;
  background: var(--bg-input);
  color: var(--ink);
  cursor: pointer;
}

.sun-strip { display: grid; grid-template-columns: repeat(3, 1fr); gap: 5px; margin-bottom: 8px; }
.sun-pill { background: var(--bg-rack); border: 1px solid var(--line); border-radius: 4px; padding: 5px 7px; font-size: 10px; }
.sun-pill.gold { border-color: var(--neon-yellow); background: var(--neon-yellow-soft); }
.sun-pill strong { display: block; font-family: var(--font-mono); font-size: 11px; color: var(--neon-yellow); }

.combo-row { display: flex; gap: 5px; flex-wrap: wrap; margin-bottom: 6px; }
.combo-row select { flex: 1 1 140px; font-weight: 600; }
.combo-row input[type=text] { flex: 1 1 130px; }

.quick-presets { display: flex; gap: 4px; flex-wrap: wrap; margin-bottom: 8px; }
.qp-btn {
  font: inherit;
  font-size: 10px;
  padding: 3px 7px;
  border-radius: 3px;
  border: 1px solid var(--line);
  background: var(--bg-rack);
  color: var(--ink-sub);
  cursor: pointer;
}
.qp-btn:hover { border-color: var(--neon-cyan); color: var(--neon-cyan); background: var(--neon-cyan-soft); }

/* ===== CALL SHEET (일일 촬영계획표) 모달 & A4 인쇄 스타일 ===== */
.cs-modal-backdrop {
  position: fixed;
  inset: 0;
  z-index: 2000;
  background: rgba(10, 15, 25, 0.72);
  backdrop-filter: blur(4px);
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 20px;
}

.cs-modal-window {
  background: #FFFFFF;
  color: #0F172A;
  width: 100%;
  max-width: 820px;
  max-height: 92vh;
  border-radius: 8px;
  box-shadow: 0 20px 50px rgba(0, 0, 0, 0.45);
  display: flex;
  flex-direction: column;
  overflow: hidden;
}

.cs-modal-toolbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 12px 18px;
  background: #0F172A;
  color: #FFFFFF;
  flex-shrink: 0;
}

.cs-sheet-scroll {
  flex: 1;
  overflow-y: auto;
  padding: 28px 34px;
  background: #FFFFFF;
}

.cs-doc {
  font-family: var(--font-sans);
  color: #0F172A;
  border: 2px solid #0F172A;
  padding: 20px 24px;
}

.cs-doc-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  border-bottom: 2px solid #0F172A;
  padding-bottom: 12px;
  margin-bottom: 14px;
}

.cs-doc-title {
  font-size: 22px;
  font-weight: 700;
  letter-spacing: -0.02em;
  margin: 0;
}

.cs-doc-sub {
  font-family: var(--font-mono);
  font-size: 11px;
  color: #475569;
  margin-top: 2px;
}

.cs-grid-3 {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  border: 1px solid #0F172A;
  margin-bottom: 14px;
}

.cs-cell {
  padding: 8px 10px;
  border-right: 1px solid #0F172A;
}
.cs-cell:last-child { border-right: 0; }
.cs-cell-lbl {
  font-family: var(--font-mono);
  font-size: 10px;
  font-weight: 700;
  color: #475569;
  text-transform: uppercase;
  margin-bottom: 3px;
}
.cs-cell-val {
  font-size: 13px;
  font-weight: 700;
}

.cs-sec-title {
  font-family: var(--font-mono);
  font-size: 12px;
  font-weight: 700;
  background: #0F172A;
  color: #FFFFFF;
  padding: 5px 10px;
  margin: 14px 0 0;
  letter-spacing: 0.03em;
}

.cs-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 12px;
  margin-bottom: 14px;
}
.cs-table th, .cs-table td {
  border: 1px solid #0F172A;
  padding: 7px 9px;
  text-align: left;
  vertical-align: top;
}
.cs-table th {
  background: #F1F5F9;
  font-weight: 700;
  font-size: 11px;
}

.cs-note-area {
  width: 100%;
  border: 1px solid #0F172A;
  border-top: 0;
  padding: 8px 10px;
  font-size: 12px;
  background: #FAFAFA;
  color: #0F172A;
  resize: vertical;
  min-height: 54px;
}

/* ===== 인쇄 및 PDF 내보내기 전용 규칙 (@media print) ===== */
@media print {
  @page { size: A4 portrait; margin: 12mm; }
  html, body {
    height: auto !important;
    overflow: visible !important;
    background: #FFFFFF !important;
  }
  .app-shell { display: none !important; }
  .cs-modal-backdrop {
    position: static !important;
    background: #FFFFFF !important;
    padding: 0 !important;
    display: block !important;
  }
  .cs-modal-window {
    max-width: 100% !important;
    max-height: none !important;
    box-shadow: none !important;
    border-radius: 0 !important;
  }
  .cs-modal-toolbar { display: none !important; }
  .cs-sheet-scroll { padding: 0 !important; overflow: visible !important; }
  .cs-note-area { border: 1px solid #0F172A !important; background: #FFFFFF !important; }
}
</style>
</head>
<body>
<div class="app-shell">
  <!-- 상단 NLE 콘솔 헤더 -->
  <header class="top-bar">
    <div class="brand-area">
      <span class="rec-dot" title="Studio Live"></span>
      <h1>MEDIA PROD CONSOLE <span class="nle-tag" id="mode-badge">DAYLIGHT</span></h1>
      <span class="timecode-box" id="today"></span>
    </div>
    <div class="global-controls">
      <div class="ctrl-pill">
        <span>LOC // 촬영 지역</span>
        <select id="reg" aria-label="촬영 지역 선택"></select>
      </div>
      <div class="ctrl-pill">
        <label style="cursor:pointer;display:flex;align-items:center;gap:5px">
          <input type="checkbox" id="wx-mock" checked> 날씨 시뮬레이션
        </label>
      </div>
      <button class="btn yellow" id="open-callsheet" type="button" title="현재 선택된 날짜와 동선, 장비, 일정을 콜시트로 생성">
        📄 콜시트 (Call Sheet)
      </button>
      <button class="theme-toggle-btn" id="theme-toggle" type="button" title="야외 데이라이트(기본) / 다크 스튜디오 테마 전환">
        🌙 다크 스튜디오
      </button>
      <button class="btn s" id="reset-split" title="3단 보드 너비 균등 초기화">◫ 3단 비율 초기화</button>
    </div>
  </header>

  <!-- 고정형 세로 3단 분할 워크스페이스 -->
  <main class="workspace" id="workspace">
    <!-- CH 01: 지원사업 브리핑 -->
    <section class="pane" id="pane-1">
      <div class="pane-head">
        <h2><span class="pane-num">CH 01</span> 지원사업 브리핑</h2>
        <span class="meta" id="cnt">0건</span>
      </div>
      <div class="pane-body">
        <div class="hero-mini">
          <div class="d-val" id="hd">D-0</div>
          <div class="h-info">
            <div style="font-family:var(--font-mono);font-size:10px;color:var(--neon-yellow)">NEXT DEADLINE // 마감 임박</div>
            <div class="h-title" id="ht"></div>
            <div class="h-sub" id="hs"></div>
          </div>
        </div>
        <div class="filter-stack">
          <div class="filter-row">
            <input type="search" id="q" placeholder="공고명, 기관명, 지역 검색...">
            <label style="font-size:11px;display:flex;align-items:center;gap:4px;cursor:pointer;color:var(--neon-green);font-weight:600">
              <input type="checkbox" id="stu"> 학생 가능
            </label>
          </div>
          <div class="chips" id="by"></div>
          <div class="chips" id="chips"></div>
        </div>
        <div id="board"></div>
      </div>
    </section>

    <div class="gutter" id="gutter-1" title="드래그하여 너비 조절"></div>

    <!-- CH 02: 촬영 동선 · 렌탈 & 로케 지원 -->
    <section class="pane" id="pane-2">
      <div class="pane-head">
        <h2><span class="pane-num">CH 02</span> 촬영 동선 · 렌탈 & 로케 지원</h2>
        <span class="meta" id="route-summary">동선 미설정</span>
      </div>
      <div class="pane-body">
        <div class="shoot-box">
          <div class="shoot-head">
            <h3>📍 내 촬영장소 동선 (S1 → S2 → S3)</h3>
            <button class="btn s" id="clear-shoot">초기화</button>
          </div>
          <div class="shoot-input-row">
            <input type="text" id="shoot-in" placeholder="촬영지 입력 (예: 성수연방, 해운대, 한옥마을)">
            <button class="btn green" id="add-shoot">+ 동선 추가</button>
          </div>
          <div class="preset-bar">
            <span>추천 스팟:</span>
            <div id="shoot-presets" style="display:flex;gap:4px;flex-wrap:wrap"></div>
          </div>
          <div class="shoot-tags" id="shoot-list"></div>
        </div>

        <div id="map-box">
          <div class="map-overlay" id="map-badge">서울 · DAYLIGHT MAP (클릭하여 촬영지 추가)</div>
          <div id="rental-map"></div>
        </div>

        <div class="loc-support-box">
          <div class="loc-support-head">
            <h4 id="loc-sup-title">🎬 촬영지 연관 로케이션 지원사업</h4>
            <span class="sub" id="loc-sup-cnt">0건</span>
          </div>
          <div id="loc-sup-list"></div>
        </div>

        <div class="sort-bar">
          <strong style="font-size:12px;color:var(--neon-cyan)" id="rc">장비 렌탈샵</strong>
          <div class="chips" id="sort-chips">
            <button class="chip" data-sort="route" aria-pressed="true">동선 최적순</button>
            <button class="chip" data-sort="dist" aria-pressed="false">출발지 거리순</button>
            <button class="chip" data-sort="price" aria-pressed="false">최저가순</button>
          </div>
        </div>
        <div id="rb"></div>
      </div>
    </section>

    <div class="gutter" id="gutter-2" title="드래그하여 너비 조절"></div>

    <!-- CH 03: 촬영 캘린더 & 타임라인 -->
    <section class="pane" id="pane-3">
      <div class="pane-head">
        <h2><span class="pane-num">CH 03</span> 촬영 캘린더 & 타임라인</h2>
        <span class="meta" id="sel-range-badge">1일 선택됨</span>
      </div>
      <div class="pane-body">
        <div class="cal-toolbar">
          <div style="display:flex;gap:4px">
            <button class="btn s" id="pm">◀</button>
            <button class="btn s" id="tm">오늘</button>
            <button class="btn s" id="nm">▶</button>
          </div>
          <h3 id="cm"></h3>
          <span class="sub" id="dw-short"></span>
        </div>

        <div class="cal-hint">💡 날짜 칸을 <b>마우스로 드래그</b>하면 다중 날짜가 선택됩니다.</div>

        <div class="calh"><div>SUN</div><div>MON</div><div>TUE</div><div>WED</div><div>THU</div><div>FRI</div><div>SAT</div></div>
        <div class="cal" id="cg"></div>

        <div class="sched-box">
          <div class="sched-head">
            <h4 id="dt">날짜 선택</h4>
            <span class="sub" id="tl-time-txt" style="color:var(--neon-cyan);font-family:var(--font-mono);font-weight:700">09:00 – 18:00 (9.0h)</span>
          </div>

          <div class="sun-strip" id="di"></div>

          <div class="tl-wrap">
            <div class="tl-labels">
              <span>00:00</span><span>06:00</span><span style="color:var(--neon-yellow)">☀️ GOLDEN / DAYLIGHT</span><span>18:00</span><span>24:00</span>
            </div>
            <div class="tl-bar" id="tl-bar">
              <div class="tl-daylight" id="tl-day"></div>
              <div class="tl-golden" id="tl-gold-am"></div>
              <div class="tl-golden" id="tl-gold-pm"></div>
              <div class="tl-grid" id="tl-grid"></div>
              <div class="tl-sel" id="tl-sel">
                <div class="tl-handle left" id="tl-h-left">◀</div>
                <span class="tl-sel-label" id="tl-sel-lbl">09:00 – 18:00</span>
                <div class="tl-handle right" id="tl-h-right">▶</div>
              </div>
            </div>

            <div class="time-adjust-bar">
              <div class="time-nudge-group">
                <span style="color:var(--ink-sub)">IN</span>
                <button class="nudge-btn" type="button" id="st-minus">-30m</button>
                <strong id="st-val" style="color:var(--neon-cyan);min-width:36px;text-align:center">09:00</strong>
                <button class="nudge-btn" type="button" id="st-plus">+30m</button>
              </div>
              <span style="color:var(--ink-muted)">⇄</span>
              <div class="time-nudge-group">
                <span style="color:var(--ink-sub)">OUT</span>
                <button class="nudge-btn" type="button" id="et-minus">-30m</button>
                <strong id="et-val" style="color:var(--neon-cyan);min-width:36px;text-align:center">18:00</strong>
                <button class="nudge-btn" type="button" id="et-plus">+30m</button>
              </div>
            </div>
          </div>

          <div class="combo-row">
            <select id="sc-type">
              <option value="🎬 본촬영">🎬 본촬영</option>
              <option value="📍 로케이션 사전답사">📍 로케이션 사전답사</option>
              <option value="🎥 리허설 촬영">🎥 리허설 촬영</option>
              <option value="📋 프리프로덕션 회의">📋 프리프로덕션 회의</option>
              <option value="🎨 미술·소품 회의">🎨 미술·소품 회의</option>
              <option value="💡 조명·촬영팀 기술회의">💡 조명·촬영팀 기술회의</option>
              <option value="📦 장비 픽업·테스트">📦 장비 픽업·테스트</option>
              <option value="🚚 장비 반납">🚚 장비 반납</option>
            </select>
            <input type="text" id="stt" placeholder="세부 메모 (예: S1 해변 씬)">
            <button class="btn yellow" id="sa">+ 일정 등록</button>
          </div>

          <div class="quick-presets" id="quick-chips"></div>

          <div class="sec-divider">
            <span>SEQUENCE EVENTS // 선택 날짜 일정</span>
            <span id="ev-cnt">0건</span>
          </div>
          <div id="dl"></div>
        </div>
      </div>
    </section>
  </main>
</div>

<!-- ===== CALL SHEET (일일 촬영계획표) 미리보기 & 인쇄 모달 ===== -->
<div class="cs-modal-backdrop" id="cs-modal" hidden>
  <div class="cs-modal-window" role="dialog" aria-modal="true" aria-labelledby="cs-modal-heading">
    <div class="cs-modal-toolbar">
      <div style="display:flex;align-items:center;gap:10px">
        <strong id="cs-modal-heading" style="font-size:14px">📄 일일 촬영계획표 (DAILY CALL SHEET)</strong>
        <span style="font-size:11px;color:#94A3B8">A4 세로 규격 최적화</span>
      </div>
      <div style="display:flex;gap:8px">
        <button class="btn yellow" id="cs-print-btn" type="button">🖨️ 인쇄 / PDF 저장</button>
        <button class="btn s" id="cs-close-btn" type="button" style="background:#1E293B;color:#FFF;border-color:#334155">✕ 닫기</button>
      </div>
    </div>
    <div class="cs-sheet-scroll">
      <div class="cs-doc" id="cs-doc-content"></div>
    </div>
  </div>
</div>

<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
<script>
const $ = id => document.getElementById(id);
const pad = n => String(n).padStart(2, "0");
const iso = d => d.getFullYear() + "-" + pad(d.getMonth() + 1) + "-" + pad(d.getDate());
const hm = ms => { const d = new Date(ms + 324e5); return pad(d.getUTCHours()) + ":" + pad(d.getUTCMinutes()); };
const WD = ["일", "월", "화", "수", "목", "금", "토"];
const today = new Date(); today.setHours(0, 0, 0, 0);
const dd = s => Math.round((new Date(s + "T00:00:00") - today) / 864e5);
const fmt = s => { const d = new Date(s + "T00:00:00"); return (d.getMonth() + 1) + "월 " + d.getDate() + "일 마감"; };
const el = (c, t, tag) => { const e = document.createElement(tag || "div"); if (c) e.className = c; if (t != null) e.textContent = t; return e; };

$("today").textContent = `TC ${today.getFullYear()}.${pad(today.getMonth() + 1)}.${pad(today.getDate())}`;

const REG = {
  "서울": [37.5665, 126.9780],
  "경기 광주": [37.4295, 127.2550],
  "강릉": [37.7519, 128.8761],
  "속초": [38.2070, 128.5918],
  "전주": [35.8242, 127.1480],
  "경주": [35.8562, 129.2247],
  "부산": [35.1796, 129.0756],
  "여수": [34.7604, 127.6622],
  "제주": [33.4996, 126.5312]
};

const SHOOT_PRESETS = {
  "서울": [
    { name: "성수연방 스튜디오", lat: 37.5446, lon: 127.0560 },
    { name: "여의도 한강공원", lat: 37.5284, lon: 126.9331 },
    { name: "북촌 한옥마을", lat: 37.5826, lon: 126.9830 }
  ],
  "부산": [
    { name: "해운대 해수욕장", lat: 35.1587, lon: 129.1604 },
    { name: "광안리 해변도로", lat: 35.1532, lon: 129.1186 }
  ]
};

const regSel = $("reg");
Object.keys(REG).forEach(k => regSel.appendChild(el("", k, "option")));

/* ===== 브라우저 캐시(localStorage)를 무시하고 처음 열 때는 무조건 라이트 모드로 시작 ===== */
try { localStorage.removeItem("studio_theme_default_light"); } catch (e) {}
let currentTheme = "light";
let mapTileLayer = null;

function applyTheme(theme) {
  currentTheme = theme;
  document.documentElement.setAttribute("data-theme", theme);

  const btn = $("theme-toggle");
  const badge = $("mode-badge");
  if (theme === "light") {
    btn.innerHTML = "🌙 다크 스튜디오";
    badge.textContent = "DAYLIGHT";
  } else {
    btn.innerHTML = "☀️ 데이라이트 모드";
    badge.textContent = "STUDIO DARK";
  }

  if (mapTileLayer) {
    const tileUrl = theme === "light"
      ? "https://{s}.basemaps.cartocdn.com/rastertiles/voyager/{z}/{x}/{y}{r}.png"
      : "https://{s}.basemaps.cartocdn.com/dark_all/{z}/{x}/{y}{r}.png";
    mapTileLayer.setUrl(tileUrl);
  }
  if ($("map-badge") && regSel.value) {
    $("map-badge").textContent = `${regSel.value} · ${theme === "light" ? "DAYLIGHT MAP" : "STUDIO DARK MAP"} (클릭하여 촬영지 추가)`;
  }
}

$("theme-toggle").onclick = () => {
  applyTheme(currentTheme === "light" ? "dark" : "light");
  updateRouteAndRental();
};

function calcDistKm(lat1, lon1, lat2, lon2) {
  const R = 6371, dLat = (lat2 - lat1) * Math.PI / 180, dLon = (lon2 - lon1) * Math.PI / 180;
  const a = Math.sin(dLat / 2) ** 2 + Math.cos(lat1 * Math.PI / 180) * Math.cos(lat2 * Math.PI / 180) * Math.sin(dLon / 2) ** 2;
  return R * 2 * Math.atan2(Math.sqrt(a), Math.sqrt(1 - a));
}

function sunOf(ds, reg) {
  const [y, m, d] = ds.split("-").map(Number), [lat, lon] = REG[reg], R = Math.PI / 180;
  const n = Date.UTC(y, m - 1, d) / 864e5 - 10957, J = n + 0.0008 - lon / 360;
  const M = (357.5291 + 0.98560028 * J) % 360, C = 1.9148 * Math.sin(M * R) + 0.02 * Math.sin(2 * M * R) + 0.0003 * Math.sin(3 * M * R);
  const L = (M + C + 180 + 102.9372) % 360, Jt = 2451545 + J + 0.0053 * Math.sin(M * R) - 0.0069 * Math.sin(2 * L * R);
  const dec = Math.asin(Math.sin(L * R) * Math.sin(23.4397 * R));
  const w = Math.acos((Math.sin(-0.833 * R) - Math.sin(lat * R) * Math.sin(dec)) / (Math.cos(lat * R) * Math.cos(dec))) / R;
  const ms = j => (j - 2440587.5) * 864e5;
  return { rise: ms(Jt - w / 360), set: ms(Jt + w / 360) };
}

const ORG_META = {
  "영화진흥위원회": { domain: "kofic.or.kr", abbr: "KOFIC", color: "#0284C7" },
  "서울영상위원회": { domain: "seoulfc.or.kr", abbr: "SFC", color: "#38BDF8" },
  "한국콘텐츠진흥원": { domain: "kocca.kr", abbr: "KOCCA", color: "#059669" },
  "서울문화재단": { domain: "sfac.or.kr", abbr: "SFAC", color: "#F43F5E" },
  "시청자미디어재단": { domain: "kcmf.or.kr", abbr: "KCMF", color: "#D97706" },
  "부산영상위원회": { domain: "bfc.or.kr", abbr: "BFC", color: "#EAB308" },
  "경기콘텐츠진흥원": { domain: "gcon.or.kr", abbr: "GCON", color: "#A855F7" },
  "전주영상위원회": { domain: "jjfc.or.kr", abbr: "JJFC", color: "#22C55E" },
  "강원문화재단": { domain: "gwcf.or.kr", abbr: "GWCF", color: "#06B6D4" },
  "제주콘텐츠진흥원": { domain: "ofjeju.kr", abbr: "JEJU", color: "#FB923C" }
};

function createOrgBadge(orgName) {
  const meta = ORG_META[orgName] || { domain: "", abbr: orgName.slice(0, 2), color: "#0284C7" };
  const wrap = el("org-badge", null, meta.domain ? "a" : "span");
  if (meta.domain) {
    wrap.href = `https://${meta.domain}`;
    wrap.target = "_blank";
    wrap.rel = "noopener";
    wrap.onclick = e => e.stopPropagation();
  }
  const logoBox = el("org-logo-wrap");
  const fb = el("org-fallback", meta.abbr);
  fb.style.background = meta.color;
  if (meta.domain) {
    const img = document.createElement("img");
    img.src = `https://www.google.com/s2/favicons?domain=${meta.domain}&sz=64`;
    img.alt = orgName;
    img.onerror = () => { img.remove(); logoBox.appendChild(fb); };
    logoBox.appendChild(img);
  } else {
    logoBox.appendChild(fb);
  }
  wrap.appendChild(logoBox);
  wrap.appendChild(el("org-name", orgName, "span"));
  return wrap;
}

/* ===== 3단 리사이저 ===== */
(function initSplitResizer() {
  const p1 = $("pane-1"), p2 = $("pane-2"), p3 = $("pane-3");
  const g1 = $("gutter-1"), g2 = $("gutter-2");
  let weights = [28, 38, 34];

  function applyWeights() {
    p1.style.flex = `${weights[0]} 1 0%`;
    p2.style.flex = `${weights[1]} 1 0%`;
    p3.style.flex = `${weights[2]} 1 0%`;
    if (window.lMap) setTimeout(() => window.lMap.invalidateSize(), 40);
  }

  function setupGutter(gutter, idxA, idxB) {
    gutter.addEventListener("mousedown", e => {
      e.preventDefault();
      gutter.classList.add("dragging");
      const startX = e.clientX, totalW = $("workspace").clientWidth;
      const startA = weights[idxA], startB = weights[idxB];
      function onMove(ev) {
        const deltaPct = ((ev.clientX - startX) / totalW) * 100;
        let nextA = Math.max(18, startA + deltaPct);
        let nextB = Math.max(18, startB - deltaPct);
        weights[idxA] = nextA; weights[idxB] = nextB;
        applyWeights();
      }
      function onUp() {
        gutter.classList.remove("dragging");
        window.removeEventListener("mousemove", onMove);
        window.removeEventListener("mouseup", onUp);
      }
      window.addEventListener("mousemove", onMove);
      window.addEventListener("mouseup", onUp);
    });
  }
  setupGutter(g1, 0, 1); setupGutter(g2, 1, 2);
  $("reset-split").onclick = () => { weights = [28, 38, 34]; applyWeights(); };
})();

/* ===== 지원사업 ===== */
const DATA = [
  { id: "sup-1", t: "단편·독립영화 제작지원 공고", o: "영화진흥위원회", type: "금액 지원", amt: "최대 1,500만원", end: "2026-11-25", stu: true, reg: "전체", kw: ["독립영화", "단편", "성수"] },
  { id: "sup-2", t: "서울 한강·도심 로케이션 촬영 허가 및 제작 지원", o: "서울영상위원회", type: "로케 지원", amt: "촬영허가 대행·통제 협조", end: "2026-11-20", stu: true, reg: "서울", kw: ["서울", "한강", "여의도", "북촌", "성수"] },
  { id: "sup-3", t: "신진 크리에이터 숏폼·웹드라마 공모전", o: "한국콘텐츠진흥원", type: "공모전", amt: "상금 500만원", end: "2026-12-05", stu: true, reg: "전체", kw: ["웹드라마", "숏폼"] },
  { id: "sup-5", t: "청년 영화인 시네마 카메라·조명 무상 대여", o: "시청자미디어재단", type: "장비·공간", amt: "장비 5일 무상 대여", end: "2026-11-30", stu: true, reg: "전체", kw: ["장비"] },
  { id: "sup-6", t: "부산 로케이션 인센티브 (숙박·식비 환급)", o: "부산영상위원회", type: "로케 지원", amt: "체류비 최대 50% 환급", end: "2026-12-15", stu: true, reg: "부산", kw: ["부산", "해운대", "광안리"] }
];
const TYPES = ["전체", "금액 지원", "로케 지원", "장비·공간", "공모전"];
let type = "전체", mode = "type";

function renderSupport() {
  const open = DATA.filter(x => dd(x.end) >= 0).sort((a, b) => dd(a.end) - dd(b.end))[0];
  if (open) {
    const n = dd(open.end);
    $("hd").textContent = n === 0 ? "D-DAY" : "D-" + n;
    $("ht").textContent = open.t;
    const hs = $("hs"); hs.innerHTML = "";
    const row = el("", null, "div"); row.style.cssText = "display:flex;align-items:center;gap:6px;flex-wrap:wrap;margin-top:2px";
    row.appendChild(createOrgBadge(open.o));
    row.appendChild(el("", `· ${open.amt} · ${fmt(open.end)}`, "span"));
    hs.appendChild(row);
  }
  $("chips").innerHTML = "";
  TYPES.forEach(t => {
    const b = el("chip", t, "button"); b.setAttribute("aria-pressed", String(t === type));
    b.onclick = () => { type = t; renderSupport(); };
    $("chips").appendChild(b);
  });
  const by = $("by"); by.innerHTML = "";
  [["type", "유형별"], ["due", "마감임박순"]].forEach(([k, l]) => {
    const b = el("chip", l, "button"); b.setAttribute("aria-pressed", String(k === mode));
    b.onclick = () => { mode = k; renderSupport(); };
    by.appendChild(b);
  });

  const q = $("q").value.trim().toLowerCase(), stu = $("stu").checked;
  const rows = DATA.filter(x => (type === "전체" || x.type === type) && (!stu || x.stu) && (!q || (x.t + x.o + x.reg).toLowerCase().includes(q)));
  $("cnt").textContent = `${rows.length} IN BIN`;

  const bd = $("board"); bd.innerHTML = "";
  rows.forEach(x => {
    const n = dd(x.end), c = el("card", null, "article"); c.id = x.id;
    const top = el("top");
    top.appendChild(el(n <= 7 ? "badge hot" : "badge", n === 0 ? "D-DAY" : "D-" + n, "span"));
    top.appendChild(el("tag", x.stu ? "학생가능" : "일반", "span"));
    c.appendChild(top);
    c.appendChild(el("ti", x.t));
    const orgRow = el("", null, "div"); orgRow.style.cssText = "display:flex;align-items:center;justify-content:space-between;gap:6px;margin-top:5px";
    orgRow.appendChild(createOrgBadge(x.o));
    orgRow.appendChild(el("sub", x.reg, "span"));
    c.appendChild(orgRow);
    c.appendChild(el("amt", `${x.amt} · ${fmt(x.end)}`));
    bd.appendChild(c);
  });
}
$("q").oninput = renderSupport; $("stu").onchange = renderSupport;

/* ===== 지도 & 렌탈 ===== */
const RENTAL_DATA = {
  "서울": [
    { name: "SLR렌트 홍대점", lat: 37.5542, lon: 126.9226, items: "FX6 · RED Komodo · 마스터 프라임", tag: "학생 20% 할인", addr: "마포구 독막로", price: 65000 },
    { name: "유쾌한생각 가산본점", lat: 37.4785, lon: 126.8812, items: "Aputure 조명 · 무선음향 · 짐벌", tag: "장기 대여 특가", addr: "금천구 가산디지털로", price: 42000 },
    { name: "충무로 씨네렌탈", lat: 37.5612, lon: 126.9942, items: "Sony FX3 · 붐마이크 · 트라이포드", tag: "독립영화 패키지", addr: "중구 퇴계로", price: 49000 }
  ]
};
function getShops(reg) {
  if (RENTAL_DATA[reg]) return RENTAL_DATA[reg].map(s => ({ ...s }));
  const [lat, lon] = REG[reg];
  return [
    { name: `${reg} 시네마 기어 A`, lat: lat + 0.008, lon: lon - 0.007, items: "카메라 · 렌즈 · 조명", tag: "학생 할인", addr: `${reg} 중심가`, price: 55000 },
    { name: `${reg} 방송장비 렌탈 B`, lat: lat - 0.009, lon: lon + 0.009, items: "무선음향 · 짐벌 · 드론", tag: "주말 가능", addr: `${reg} 역세권`, price: 45000 }
  ];
}

let shootLocs = [], currentSort = "route", activeShopIdx = 0;
let lastSortedShops = [];
let lMap = null, rentalLayer = null, shootLayer = null, lineLayer = null;

function initMap() {
  if (lMap) return;
  const [lat, lon] = REG[regSel.value];
  lMap = L.map("rental-map", { zoomControl: false }).setView([lat, lon], 12);
  window.lMap = lMap;
  L.control.zoom({ position: "bottomright" }).addTo(lMap);

  const initTileUrl = currentTheme === "light"
    ? "https://{s}.basemaps.cartocdn.com/rastertiles/voyager/{z}/{x}/{y}{r}.png"
    : "https://{s}.basemaps.cartocdn.com/dark_all/{z}/{x}/{y}{r}.png";

  mapTileLayer = L.tileLayer(initTileUrl, { maxZoom: 19 }).addTo(lMap);
  rentalLayer = L.layerGroup().addTo(lMap);
  shootLayer = L.layerGroup().addTo(lMap);
  lineLayer = L.layerGroup().addTo(lMap);

  lMap.on("click", e => {
    shootLocs.push({ id: Date.now(), name: `${regSel.value} 포인트 #${shootLocs.length + 1}`, lat: e.latlng.lat, lon: e.latlng.lng });
    updateRouteAndRental();
  });
}

function renderShootPresets() {
  const r = regSel.value, [lat, lon] = REG[r];
  const presets = SHOOT_PRESETS[r] || [{ name: `${r} 메인 로케지`, lat: lat + 0.01, lon: lon + 0.004 }];
  const box = $("shoot-presets"); box.innerHTML = "";
  presets.forEach(p => {
    const b = el("preset-btn", "+ " + p.name, "button");
    b.onclick = () => { shootLocs.push({ id: Date.now() + Math.random(), name: p.name, lat: p.lat, lon: p.lon }); updateRouteAndRental(); };
    box.appendChild(b);
  });
}

function addShootByInput() {
  const val = $("shoot-in").value.trim(); if (!val) return;
  $("shoot-in").value = "";
  const [lat, lon] = REG[regSel.value];
  shootLocs.push({ id: Date.now(), name: val, lat: lat + (Math.random() - 0.5) * 0.02, lon: lon + (Math.random() - 0.5) * 0.02 });
  updateRouteAndRental();
}
$("add-shoot").onclick = addShootByInput;
$("shoot-in").addEventListener("keydown", e => { if (e.key === "Enter") addShootByInput(); });
$("clear-shoot").onclick = () => { shootLocs = []; updateRouteAndRental(); };

document.querySelectorAll("#sort-chips .chip").forEach(btn => {
  btn.onclick = () => {
    currentSort = btn.dataset.sort;
    document.querySelectorAll("#sort-chips .chip").forEach(b => b.setAttribute("aria-pressed", String(b === btn)));
    updateRouteAndRental();
  };
});

function updateRouteAndRental() {
  initMap();
  const r = regSel.value;
  const sList = $("shoot-list"); sList.innerHTML = "";
  if (!shootLocs.length) {
    $("route-summary").textContent = "동선 미설정";
  } else {
    $("route-summary").textContent = `촬영지 ${shootLocs.length}곳 설정됨`;
  }

  shootLocs.forEach((loc, idx) => {
    const tag = el("shoot-tag");
    tag.appendChild(el("step", `S${idx + 1}`, "span"));
    tag.appendChild(el("", loc.name, "span"));
    const del = el("", "✕", "button");
    del.onclick = () => { shootLocs.splice(idx, 1); updateRouteAndRental(); };
    tag.appendChild(del);
    sList.appendChild(tag);
  });

  const locList = $("loc-sup-list"); locList.innerHTML = "";
  const matched = DATA.filter(x => x.type === "로케 지원" && (x.reg === r || x.reg === "전체"));
  $("loc-sup-cnt").textContent = `${matched.length}건`;
  matched.forEach(item => {
    const c = el("loc-sup-card");
    c.appendChild(el("ti", item.t));
    c.appendChild(el("amt", item.amt));
    locList.appendChild(c);
  });

  const [cLat, cLon] = REG[r];
  let shops = getShops(r).map(s => {
    if (shootLocs.length > 0) {
      const first = shootLocs[0], last = shootLocs[shootLocs.length - 1];
      const dFirst = calcDistKm(s.lat, s.lon, first.lat, first.lon);
      const dLast = calcDistKm(s.lat, s.lon, last.lat, last.lon);
      return { ...s, dFirst, detour: dFirst + dLast };
    }
    const dCenter = calcDistKm(s.lat, s.lon, cLat, cLon);
    return { ...s, dFirst: dCenter, detour: dCenter };
  });

  if (currentSort === "price") shops.sort((a, b) => a.price - b.price);
  else if (currentSort === "dist") shops.sort((a, b) => a.dFirst - b.dFirst);
  else shops.sort((a, b) => a.detour - b.detour);

  if (activeShopIdx >= shops.length) activeShopIdx = 0;
  lastSortedShops = shops;

  const rb = $("rb"); rb.innerHTML = "";
  rentalLayer.clearLayers(); shootLayer.clearLayers(); lineLayer.clearLayers();
  const bounds = [];

  shootLocs.forEach((loc, i) => {
    bounds.push([loc.lat, loc.lon]);
    const icon = L.divIcon({ className: "", html: `<div class="shoot-pin">S${i + 1}</div>`, iconSize: [28, 28], iconAnchor: [14, 14] });
    L.marker([loc.lat, loc.lon], { icon }).addTo(shootLayer).bindPopup(`<b>[S${i + 1}] ${loc.name}</b>`);
  });

  if (shootLocs.length > 1) {
    L.polyline(shootLocs.map(l => [l.lat, l.lon]), { color: "#059669", weight: 3 }).addTo(lineLayer);
  }

  shops.forEach((s, idx) => {
    bounds.push([s.lat, s.lon]);
    const isBest = idx === 0;
    const isAct = idx === activeShopIdx;
    const pin = L.divIcon({ className: "", html: `<div class="custom-pin ${isBest ? "best" : ""}"><span>${idx + 1}</span></div>`, iconSize: [26, 26], iconAnchor: [13, 26] });
    L.marker([s.lat, s.lon], { icon: pin }).addTo(rentalLayer);

    if (isAct && shootLocs.length > 0) {
      L.polyline([[s.lat, s.lon], [shootLocs[0].lat, shootLocs[0].lon]], { color: "#0284C7", weight: 2.5, dashArray: "5, 6" }).addTo(lineLayer);
    }

    const cardEl = el(`card rental-card ${isBest ? "best" : ""} ${isAct ? "active" : ""}`);
    const top = el("top");
    const left = el("", null, "div"); left.style.cssText = "display:flex;align-items:center;gap:6px";
    left.appendChild(el("num-pin", String(idx + 1), "span"));
    left.appendChild(el("ti", s.name, "span"));
    top.appendChild(left);
    top.appendChild(el("price-badge", `${s.price.toLocaleString()}원`, "span"));
    cardEl.appendChild(top);
    cardEl.appendChild(el("sub", `${s.items} · ${s.addr}`));

    const metrics = el("route-metrics");
    if (shootLocs.length > 0) {
      metrics.appendChild(el("metric-pill hi", `왕복 이탈 ${s.detour.toFixed(1)}km`, "span"));
      metrics.appendChild(el("metric-pill", `S1까지 ${s.dFirst.toFixed(1)}km`, "span"));
    }
    metrics.appendChild(el("tag", s.tag, "span"));
    cardEl.appendChild(metrics);

    cardEl.onclick = () => { activeShopIdx = idx; updateRouteAndRental(); };
    rb.appendChild(cardEl);
  });

  if (bounds.length > 0) lMap.fitBounds(bounds, { padding: [24, 24], maxZoom: 13 });
}

/* ===== 캘린더 & 타임라인 ===== */
const MOCK_WX = [
  { icon: "☀️", desc: "맑음", temp: "8°/17°", pop: "10%" },
  { icon: "⛅", desc: "구름많음", temp: "9°/16°", pop: "20%" },
  { icon: "🌧️", desc: "비", temp: "10°/13°", pop: "80%" },
  { icon: "☁️", desc: "흐림", temp: "6°/13°", pop: "40%" },
  { icon: "☀️", desc: "맑음", temp: "5°/15°", pop: "10%" },
  { icon: "☀️", desc: "맑음", temp: "7°/16°", pop: "10%" },
  { icon: "⛅", desc: "구름조금", temp: "8°/17°", pop: "20%" }
];

function getWx(ds) {
  if ($("wx-mock").checked) {
    const off = Math.round((new Date(ds + "T00:00:00") - today) / 864e5);
    if (off >= 0 && off < MOCK_WX.length) return MOCK_WX[off];
  }
  return null;
}

let vy = today.getFullYear(), vm = today.getMonth(), selDates = [iso(today)];
let isCalDragging = false, dragStartDs = null;
let tlStart = 9.0, tlEnd = 18.0;

const tlGrid = $("tl-grid"); for (let i = 0; i < 24; i++) tlGrid.appendChild(el(""));
const fmtHour = h => `${pad(Math.floor(h))}:${pad(Math.round((h - Math.floor(h)) * 60))}`;

function getRangeDates(d1, d2) {
  const a = new Date(d1 + "T00:00:00"), b = new Date(d2 + "T00:00:00");
  const start = a <= b ? a : b, end = a <= b ? b : a;
  const arr = [], cur = new Date(start);
  while (cur <= end) { arr.push(iso(cur)); cur.setDate(cur.getDate() + 1); }
  return arr;
}
window.addEventListener("mouseup", () => { isCalDragging = false; });

function updateTimelineUI() {
  $("tl-sel").style.left = `${(tlStart / 24) * 100}%`;
  $("tl-sel").style.width = `${Math.max(((tlEnd - tlStart) / 24) * 100, 2)}%`;
  const sTxt = fmtHour(tlStart), eTxt = fmtHour(tlEnd);
  $("tl-sel-lbl").textContent = `${sTxt}–${eTxt}`;
  $("tl-time-txt").textContent = `${sTxt} – ${eTxt} (${(tlEnd - tlStart).toFixed(1)}h)`;
  $("st-val").textContent = sTxt; $("et-val").textContent = eTxt;
}

(function initTimelineInteraction() {
  const bar = $("tl-bar"), sel = $("tl-sel"), hLeft = $("tl-h-left"), hRight = $("tl-h-right");
  let dragMode = null, anchorHr = 0, initStart = 0, initEnd = 0;

  function clientXToHour(clientX) {
    const rect = bar.getBoundingClientRect();
    const ratio = Math.max(0, Math.min(1, (clientX - rect.left) / rect.width));
    return Math.round(ratio * 48) / 2;
  }

  hLeft.addEventListener("pointerdown", e => { e.stopPropagation(); e.preventDefault(); dragMode = "left"; hLeft.classList.add("active"); bar.setPointerCapture(e.pointerId); });
  hRight.addEventListener("pointerdown", e => { e.stopPropagation(); e.preventDefault(); dragMode = "right"; hRight.classList.add("active"); bar.setPointerCapture(e.pointerId); });
  sel.addEventListener("pointerdown", e => {
    if (e.target === hLeft || e.target === hRight) return;
    e.stopPropagation(); e.preventDefault(); dragMode = "move"; anchorHr = clientXToHour(e.clientX); initStart = tlStart; initEnd = tlEnd; bar.setPointerCapture(e.pointerId);
  });
  bar.addEventListener("pointerdown", e => {
    if (dragMode) return;
    e.preventDefault(); dragMode = "create"; anchorHr = clientXToHour(e.clientX); tlStart = Math.min(anchorHr, 23.5); tlEnd = Math.min(24, tlStart + 0.5); updateTimelineUI(); bar.setPointerCapture(e.pointerId);
  });
  bar.addEventListener("pointermove", e => {
    if (!dragMode) return;
    const h = clientXToHour(e.clientX);
    if (dragMode === "left") tlStart = Math.max(0, Math.min(h, tlEnd - 0.5));
    else if (dragMode === "right") tlEnd = Math.min(24, Math.max(h, tlStart + 0.5));
    else if (dragMode === "move") {
      const dur = initEnd - initStart;
      let ns = Math.max(0, Math.min(24 - dur, initStart + (h - anchorHr)));
      tlStart = Math.round(ns * 2) / 2; tlEnd = tlStart + dur;
    } else if (dragMode === "create") {
      tlStart = Math.min(anchorHr, h); tlEnd = Math.max(anchorHr, h);
      if (tlEnd - tlStart < 0.5) tlEnd = Math.min(24, tlStart + 0.5);
    }
    updateTimelineUI();
  });
  const stopDrag = () => { dragMode = null; hLeft.classList.remove("active"); hRight.classList.remove("active"); };
  bar.addEventListener("pointerup", stopDrag); bar.addEventListener("pointercancel", stopDrag);
})();

$("st-minus").onclick = () => { tlStart = Math.max(0, tlStart - 0.5); updateTimelineUI(); };
$("st-plus").onclick = () => { tlStart = Math.min(tlEnd - 0.5, tlStart + 0.5); updateTimelineUI(); };
$("et-minus").onclick = () => { tlEnd = Math.max(tlStart + 0.5, tlEnd - 0.5); updateTimelineUI(); };
$("et-plus").onclick = () => { tlEnd = Math.min(24, tlEnd + 0.5); updateTimelineUI(); };

const QUICK_CATS = ["🎬 본촬영", "📍 로케이션 사전답사", "🎥 리허설 촬영", "📋 프리프로덕션 회의", "🎨 미술·소품 회의"];
QUICK_CATS.forEach(cat => {
  const b = el("qp-btn", cat, "button");
  b.onclick = () => { $("sc-type").value = cat; addSchedule(); };
  $("quick-chips").appendChild(b);
});

let SCH = [];
try { SCH = JSON.parse(localStorage.getItem("sch_v3") || "[]"); } catch (e) { SCH = []; }
const saveSch = () => { try { localStorage.setItem("sch_v3", JSON.stringify(SCH)); } catch (e) {} };
const evs = ds => SCH.filter(x => x.d === ds).sort((a, b) => a.t.localeCompare(b.t));

function renderCalendar() {
  $("cm").textContent = `${vy}.${pad(vm + 1)}`;
  const g = $("cg"); g.innerHTML = "";
  const first = new Date(vy, vm, 1).getDay(), days = new Date(vy, vm + 1, 0).getDate();
  for (let i = 0; i < first; i++) g.appendChild(el("cell blank"));
  for (let d = 1; d <= days; d++) {
    const ds = `${vy}-${pad(vm + 1)}-${pad(d)}`, off = Math.round((new Date(vy, vm, d) - today) / 864e5);
    const inRange = selDates.includes(ds), isEdge = ds === selDates[0] || ds === selDates[selDates.length - 1];
    const c = el(`cell ${inRange ? "in-range" : ""} ${isEdge ? "range-edge" : ""} ${off === 0 ? "today" : ""}`);

    const topRow = el("", null, "div"); topRow.style.cssText = "display:flex;justify-content:space-between;align-items:center";
    topRow.appendChild(el("dn", `${d}`));
    const w = getWx(ds);
    if (w) topRow.appendChild(el("wx-mini", `${w.icon}${w.temp.split("/")[1]}`));
    c.appendChild(topRow);

    const dayEvs = evs(ds);
    dayEvs.slice(0, 2).forEach(x => c.appendChild(el("ev-dot", `${x.t.split("–")[0]} ${x.cat.replace(/^[^\s]+\s/, "")}`)));
    if (dayEvs.length > 2) c.appendChild(el("wx-mini", `+${dayEvs.length - 2}`));

    c.addEventListener("mousedown", e => {
      e.preventDefault(); isCalDragging = true; dragStartDs = ds; selDates = [ds]; renderCalendar(); renderDayDetail();
    });
    c.addEventListener("mouseenter", () => {
      if (!isCalDragging || !dragStartDs) return;
      selDates = getRangeDates(dragStartDs, ds); renderCalendar(); renderDayDetail();
    });
    g.appendChild(c);
  }
}

function renderDayDetail() {
  const firstDs = selDates[0], lastDs = selDates[selDates.length - 1];
  $("sel-range-badge").textContent = selDates.length > 1 ? `${selDates.length}DAYS SELECTED` : `1DAY SELECTED`;
  const dt1 = new Date(firstDs + "T00:00:00");
  $("dt").textContent = selDates.length === 1
    ? `${dt1.getMonth() + 1}월 ${dt1.getDate()}일 (${WD[dt1.getDay()]}) · ${regSel.value}`
    : `${firstDs.slice(5)} ~ ${lastDs.slice(5)} (${selDates.length}일간) · ${regSel.value}`;

  const w = getWx(firstDs);
  $("dw-short").textContent = w ? `${w.icon} ${w.desc} ${w.temp} (강수 ${w.pop})` : "";

  const s = sunOf(firstDs, regSel.value);
  const riseStr = hm(s.rise), setStr = hm(s.set);
  const goldAmEnd = hm(s.rise + 36e5), goldPmStart = hm(s.set - 36e5);

  const di = $("di"); di.innerHTML = "";
  [
    ["🌅 일출 / 일몰", `${riseStr} / ${setStr}`, false],
    ["✨ 아침 골든아워", `${riseStr} – ${goldAmEnd}`, true],
    ["🌇 저녁 골든아워", `${goldPmStart} – ${setStr}`, true]
  ].forEach(([k, v, g]) => {
    const p = el(`sun-pill ${g ? "gold" : ""}`);
    p.appendChild(el("sub", k)); p.appendChild(el("", v, "strong"));
    di.appendChild(p);
  });

  const toHr = str => { const [hh, mm] = str.split(":").map(Number); return hh + mm / 60; };
  const rH = toHr(riseStr), sH = toHr(setStr);
  $("tl-day").style.left = `${(rH / 24) * 100}%`; $("tl-day").style.width = `${((sH - rH) / 24) * 100}%`;
  $("tl-gold-am").style.left = `${(rH / 24) * 100}%`; $("tl-gold-am").style.width = `${(1 / 24) * 100}%`;
  $("tl-gold-pm").style.left = `${((sH - 1) / 24) * 100}%`; $("tl-gold-pm").style.width = `${(1 / 24) * 100}%`;

  const L = $("dl"); L.innerHTML = "";
  const rangeEvs = SCH.filter(x => selDates.includes(x.d)).sort((a, b) => (a.d + a.t).localeCompare(b.d + b.t));
  $("ev-cnt").textContent = `${rangeEvs.length}`;

  if (!rangeEvs.length) {
    L.appendChild(el("sub", "등록된 일정이 없습니다. 위 타임라인 바와 콤보박스로 일정을 추가하세요."));
    return;
  }

  rangeEvs.forEach(x => {
    const c = el("card");
    const row = el("top");
    row.appendChild(el("ti", `${x.cat} ${x.n ? "· " + x.n : ""}`));
    const del = el("btn s", "삭제", "button");
    del.onclick = () => { SCH = SCH.filter(y => y.id !== x.id); saveSch(); renderCalendar(); renderDayDetail(); };
    row.appendChild(del);
    c.appendChild(row);
    c.appendChild(el("sub", `🗓️ ${x.d.slice(5)} | ⏰ ${x.t} | 📍 ${x.r}`));
    L.appendChild(c);
  });
}

function addSchedule() {
  const cat = $("sc-type").value, note = $("stt").value.trim(), timeRange = `${fmtHour(tlStart)}–${fmtHour(tlEnd)}`;
  selDates.forEach((ds, idx) => {
    SCH.push({ id: Date.now() + idx + Math.random(), d: ds, t: timeRange, cat, n: note, r: regSel.value });
  });
  saveSch(); $("stt").value = ""; renderCalendar(); renderDayDetail();
}
$("sa").onclick = addSchedule;
$("stt").addEventListener("keydown", e => { if (e.key === "Enter") addSchedule(); });
$("pm").onclick = () => { vm--; if (vm < 0) { vm = 11; vy--; } renderCalendar(); };
$("nm").onclick = () => { vm++; if (vm > 11) { vm = 0; vy++; } renderCalendar(); };
$("tm").onclick = () => { vy = today.getFullYear(); vm = today.getMonth(); selDates = [iso(today)]; renderCalendar(); renderDayDetail(); };
$("wx-mock").onchange = () => { renderCalendar(); renderDayDetail(); };

regSel.onchange = () => {
  activeShopIdx = 0; renderShootPresets(); updateRouteAndRental(); renderCalendar(); renderDayDetail();
};

/* ===== CALL SHEET (일일 촬영계획표) 생성 및 인쇄 모달 로직 ===== */
function buildCallSheet() {
  const firstDs = selDates[0], lastDs = selDates[selDates.length - 1];
  const reg = regSel.value;
  const dt1 = new Date(firstDs + "T00:00:00");
  const dateLabel = selDates.length === 1
    ? `${firstDs} (${WD[dt1.getDay()]}요일)`
    : `${firstDs} ~ ${lastDs} (${selDates.length}일간)`;

  const w = getWx(firstDs);
  const wxText = w ? `${w.icon} ${w.desc} / 기온 ${w.temp} (강수확률 ${w.pop})` : "기상청 단기예보 범위 외 (현장 재확인 필요)";

  const s = sunOf(firstDs, reg);
  const riseStr = hm(s.rise), setStr = hm(s.set);
  const goldAm = `${riseStr} – ${hm(s.rise + 36e5)}`;
  const goldPm = `${hm(s.set - 36e5)} – ${setStr}`;

  const selectedShop = lastSortedShops[activeShopIdx] || lastSortedShops[0];
  const rangeEvs = SCH.filter(x => selDates.includes(x.d)).sort((a, b) => (a.d + a.t).localeCompare(b.d + b.t));

  const scheduleRowsHtml = rangeEvs.length
    ? rangeEvs.map(ev => `
        <tr>
          <td style="font-family:var(--font-mono);font-weight:700;white-space:nowrap">${ev.d.slice(5)}<br>${ev.t}</td>
          <td style="font-weight:700">${ev.cat}</td>
          <td>${ev.n || "-"}</td>
          <td>${ev.r}</td>
        </tr>
      `).join("")
    : `
        <tr>
          <td style="font-family:var(--font-mono);font-weight:700">${firstDs.slice(5)}<br>${fmtHour(tlStart)}–${fmtHour(tlEnd)}</td>
          <td style="font-weight:700">${$("sc-type").value} (예정)</td>
          <td>${$("stt").value.trim() || "타임라인 기본 설정 구간"}</td>
          <td>${reg}</td>
        </tr>
      `;

  const routeRowsHtml = shootLocs.length
    ? shootLocs.map((loc, i) => {
        const prevDist = i === 0
          ? (selectedShop ? `렌탈샵 픽업 이동 약 ${calcDistKm(selectedShop.lat, selectedShop.lon, loc.lat, loc.lon).toFixed(1)}km` : "출발지")
          : `이전 촬영지(S${i})로부터 약 ${calcDistKm(shootLocs[i - 1].lat, shootLocs[i - 1].lon, loc.lat, loc.lon).toFixed(1)}km`;
        return `
          <tr>
            <td style="font-family:var(--font-mono);font-weight:700;text-align:center">S${i + 1}</td>
            <td style="font-weight:700">${loc.name}</td>
            <td style="font-family:var(--font-mono);font-size:11px">${loc.lat.toFixed(4)}, ${loc.lon.toFixed(4)}</td>
            <td>${prevDist}</td>
          </tr>
        `;
      }).join("")
    : `<tr><td colspan="4" style="text-align:center;color:#64748B">설정된 세부 촬영 동선(S1~S3)이 없습니다.</td></tr>`;

  const shopHtml = selectedShop
    ? `
      <table class="cs-table">
        <thead>
          <tr><th>업체명</th><th>대여 장비 패키지</th><th>위치 / 비고</th><th>예상 대여료 & 동선</th></tr>
        </thead>
        <tbody>
          <tr>
            <td style="font-weight:700">${selectedShop.name}</td>
            <td>${selectedShop.items}</td>
            <td>${selectedShop.addr} (${selectedShop.tag})</td>
            <td style="font-family:var(--font-mono)">일 ${selectedShop.price.toLocaleString()}원~ / 왕복이탈 ${selectedShop.detour.toFixed(1)}km</td>
          </tr>
        </tbody>
      </table>
    `
    : `<p style="font-size:12px;color:#64748B;margin:6px 0 12px">선택된 렌탈샵 정보가 없습니다.</p>`;

  $("cs-doc-content").innerHTML = `
    <div class="cs-doc-header">
      <div>
        <h2 class="cs-doc-title">DAILY CALL SHEET // 일일 촬영계획표</h2>
        <div class="cs-doc-sub">GENERATED BY MEDIA PROD STUDIO CONSOLE · ${iso(today)} 발행</div>
      </div>
      <div style="text-align:right">
        <div style="font-family:var(--font-mono);font-size:11px;color:#475569">SHOOTING REGION</div>
        <div style="font-size:16px;font-weight:700">📍 ${reg}</div>
      </div>
    </div>

    <div class="cs-grid-3">
      <div class="cs-cell">
        <div class="cs-cell-lbl">SHOOTING DATE // 촬영 일자</div>
        <div class="cs-cell-val">${dateLabel}</div>
      </div>
      <div class="cs-cell">
        <div class="cs-cell-lbl">WEATHER // 기상 예보</div>
        <div class="cs-cell-val">${wxText}</div>
      </div>
      <div class="cs-cell">
        <div class="cs-cell-lbl">SUN & GOLDEN HOUR // 채광 시간</div>
        <div class="cs-cell-val" style="font-family:var(--font-mono);font-size:11px">
          일출 ${riseStr} / 일몰 ${setStr}<br>
          AM ${goldAm} | PM ${goldPm}
        </div>
      </div>
    </div>

    <div class="cs-sec-title">01. PRODUCTION SCHEDULE // 타임라인 및 회차 일정</div>
    <table class="cs-table">
      <thead>
        <tr><th style="width:110px">날짜 / 시간</th><th style="width:160px">프로덕션 구분</th><th>세부 내용 및 씬 메모</th><th style="width:90px">지역</th></tr>
      </thead>
      <tbody>${scheduleRowsHtml}</tbody>
    </table>

    <div class="cs-sec-title">02. LOCATION ROUTE // 촬영 동선 (S1 → S2 → S3)</div>
    <table class="cs-table">
      <thead>
        <tr><th style="width:55px;text-align:center">순서</th><th style="width:190px">촬영 장소명</th><th style="width:140px">GPS 좌표</th><th>이동 구간 정보</th></tr>
      </thead>
      <tbody>${routeRowsHtml}</tbody>
    </table>

    <div class="cs-sec-title">03. EQUIPMENT RENTAL // 장비 픽업 및 반납처</div>
    ${shopHtml}

    <div class="cs-sec-title">04. PRODUCTION NOTES & CONTACTS // 현장 특이사항 및 비상 연락망</div>
    <textarea class="cs-note-area" placeholder="인쇄 전 현장 주차 안내, 연출/촬영팀장 비상 연락처, 소품 지참 사항 등을 자유롭게 입력하세요..."></textarea>
  `;
}

$("open-callsheet").onclick = () => {
  buildCallSheet();
  $("cs-modal").hidden = false;
};
$("cs-close-btn").onclick = () => { $("cs-modal").hidden = true; };
$("cs-modal").addEventListener("click", e => {
  if (e.target === $("cs-modal")) $("cs-modal").hidden = true;
});
$("cs-print-btn").onclick = () => {
  window.print();
};

/* 초기 구동 */
applyTheme("light");
renderSupport();
renderShootPresets();
updateRouteAndRental();
updateTimelineUI();
renderCalendar();
renderDayDetail();
</script>
</body>
</html>

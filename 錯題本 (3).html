<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no"/>
<title>AI 錯題本</title>
<script src="https://accounts.google.com/gsi/client" async defer></script>
<style>
:root{
  --purple:#6C63FF;--purple-light:#EEF0FF;--purple-dark:#4B44CC;
  --green:#22C55E;--orange:#F59E0B;
  --text:#1a1a2e;--text-2:#64748B;--text-3:#94A3B8;
  --bg:#F1F5F9;--white:#F8FAFC;--border:#E8EDF2;
  --radius:16px;--radius-sm:10px;
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent;}
body{font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;background:var(--bg);min-height:100vh;padding:1.25rem 1rem 2rem;}
.app{width:100%;max-width:430px;margin:0 auto;}
.screen{display:none;}
.screen.active{display:block;}
.btn{width:100%;padding:16px;background:linear-gradient(135deg,var(--purple),var(--purple-dark));color:white;border:none;border-radius:var(--radius-sm);font-size:16px;font-weight:700;cursor:pointer;margin-top:8px;touch-action:manipulation;}
.card{background:var(--white);border-radius:var(--radius);padding:1.5rem;box-shadow:0 2px 12px rgba(0,0,0,0.07);}
.topbar{display:flex;align-items:center;gap:12px;margin-bottom:1.5rem;}
.back{width:42px;height:42px;background:var(--white);border:1.5px solid var(--border);border-radius:var(--radius-sm);display:flex;align-items:center;justify-content:center;cursor:pointer;font-size:20px;color:var(--text-2);touch-action:manipulation;flex-shrink:0;}
.topbar h2{font-size:20px;font-weight:700;color:var(--text);flex:1;}

/* 表情符號選擇器 */
.emoji-pick{background:var(--white);border:2px solid var(--border);border-radius:10px;padding:0.6rem 0;text-align:center;font-size:22px;cursor:pointer;touch-action:manipulation;}
.emoji-pick.selected{border-color:var(--purple);background:var(--purple-light);}

/* 科目格 */
.subject-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:1rem;}
.subject-card{background:var(--white);border:2px solid var(--border);border-radius:14px;padding:1rem 0.5rem;text-align:center;cursor:pointer;touch-action:manipulation;user-select:none;}
.subject-card.selected{border-color:var(--purple);background:var(--purple-light);}
.subject-card .icon{font-size:28px;display:block;margin-bottom:6px;}
.subject-card .label{font-size:13px;font-weight:600;color:var(--text);}
.subject-card.selected .label{color:var(--purple);}
.sel-count{text-align:center;font-size:13px;color:var(--text-2);margin-bottom:1rem;}

/* 儀表板 */
.dash-header{background:linear-gradient(135deg,var(--purple),#A78BFA);border-radius:var(--radius);padding:1.5rem;margin-bottom:1.25rem;color:white;}
.dash-header h2{font-size:20px;font-weight:700;margin-bottom:4px;}
.dash-header p{font-size:13px;opacity:0.85;}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:1.5rem;}
.stat{background:var(--white);border-radius:14px;padding:1rem;text-align:center;}
.stat .lbl{font-size:11px;font-weight:600;color:var(--text-3);margin-bottom:6px;text-transform:uppercase;}
.stat .val{font-size:26px;font-weight:700;color:var(--text);}
.sec-title{font-size:11px;font-weight:700;color:var(--text-3);letter-spacing:0.08em;text-transform:uppercase;margin-bottom:10px;}
.subj-list{display:flex;flex-direction:column;gap:8px;margin-bottom:1.25rem;}
.subj-row{background:var(--white);border:1.5px solid var(--border);border-radius:14px;padding:0.9rem 1.1rem;display:flex;align-items:center;gap:12px;cursor:pointer;touch-action:manipulation;}
.subj-icon{width:42px;height:42px;border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:22px;flex-shrink:0;}
.subj-name{font-size:15px;font-weight:600;color:var(--text);flex:1;}
.subj-count{font-size:12px;color:var(--text-2);}
.arrow{color:var(--text-3);font-size:20px;}

/* 篩選 */
.chips{display:flex;gap:8px;margin-bottom:1.25rem;flex-wrap:wrap;}
.chip{padding:8px 16px;border-radius:99px;font-size:13px;font-weight:600;border:1.5px solid var(--border);background:var(--white);color:var(--text-2);cursor:pointer;touch-action:manipulation;}
.chip.active{background:var(--purple);border-color:var(--purple);color:white;}

/* 錯題卡 */
.card-list{display:flex;flex-direction:column;gap:12px;}
.q-card

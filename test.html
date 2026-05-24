<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Project Management Simulator PRO MAX</title>
<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{--bg:#0a0e1a;--card:#111827;--card2:#1a2236;--accent:#6366f1;--accent2:#8b5cf6;--danger:#ef4444;--warn:#f59e0b;--success:#10b981;--info:#3b82f6;--text:#e2e8f0;--text2:#94a3b8;--text3:#64748b}
body{font-family:'Segoe UI',system-ui,sans-serif;background:var(--bg);color:var(--text);min-height:100vh;line-height:1.5}
.container{max-width:1400px;margin:0 auto;padding:15px}
header{text-align:center;padding:20px 0;border-bottom:1px solid #1e293b;margin-bottom:20px}
header h1{font-size:2em;background:linear-gradient(90deg,var(--accent),var(--accent2));-webkit-background-clip:text;-webkit-text-fill-color:transparent}
header p{color:var(--text2);font-size:.95em}
.top-grid{display:grid;grid-template-columns:1fr 1fr 1fr;gap:15px;margin-bottom:20px}
@media(max-width:900px){.top-grid{grid-template-columns:1fr}}
.panel{background:var(--card);border:1px solid #1e293b;border-radius:16px;padding:18px}
.panel h3{font-size:.85em;text-transform:uppercase;letter-spacing:1px;color:var(--text2);margin-bottom:12px;display:flex;align-items:center;gap:8px}
.metrics-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
.metric-item{background:var(--card2);border-radius:12px;padding:12px;position:relative;overflow:hidden}
.metric-item .label{font-size:.75em;color:var(--text2);margin-bottom:6px;display:flex;justify-content:space-between}
.metric-item .value{font-size:1.6em;font-weight:700;margin-bottom:8px}
.metric-bar{height:6px;background:#1e293b;border-radius:3px;overflow:hidden}
.metric-bar-fill{height:100%;border-radius:3px;transition:width .6s cubic-bezier(.4,0,.2,1),background .3s}
.metric-budget .value{color:#fbbf24}.metric-budget .metric-bar-fill{background:#fbbf24}
.metric-timeline .value{color:#60a5fa}.metric-timeline .metric-bar-fill{background:#60a5fa}
.metric-quality .value{color:#34d399}.metric-quality .metric-bar-fill{background:#34d399}
.metric-morale .value{color:#f472b6}.metric-morale .metric-bar-fill{background:#f472b6}
.metric-scope .value{color:#a78bfa}.metric-scope .metric-bar-fill{background:#a78bfa}
.metric-risk .value{color:#f87171}.metric-risk .metric-bar-fill{background:#f87171}
.skills-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:10px}
.skill-item{background:var(--card2);border-radius:10px;padding:10px;font-size:.85em}
.skill-item .skill-name{display:flex;justify-content:space-between;margin-bottom:6px}
.skill-item .skill-level{font-weight:700;color:var(--accent)}
.skill-bar{height:4px;background:#1e293b;border-radius:2px}
.skill-bar-fill{height:100%;background:linear-gradient(90deg,var(--accent),var(--accent2));border-radius:2px;transition:width .5s}
.status-grid{display:grid;gap:10px}
.status-item{display:flex;align-items:center;gap:10px;background:var(--card2);border-radius:10px;padding:10px 14px;font-size:.85em}
.status-item .status-icon{font-size:1.3em}
.timeline-track{display:flex;gap:8px;margin-bottom:20px;overflow-x:auto;padding-bottom:10px}
.timeline-phase{flex:1;min-width:140px;background:var(--card);border:1px solid #1e293b;border-radius:12px;padding:14px;text-align:center;position:relative;transition:all .3s}
.timeline-phase.active{border-color:var(--accent);background:linear-gradient(135deg,rgba(99,102,241,.1),rgba(139,92,246,.05));box-shadow:0 0 20px rgba(99,102,241,.15)}
.timeline-phase.completed{border-color:var(--success);opacity:.7}
.timeline-phase .phase-icon{font-size:1.5em;margin-bottom:6px}
.timeline-phase .phase-name{font-size:.8em;font-weight:600}
.timeline-phase .phase-weeks{font-size:.7em;color:var(--text2);margin-top:4px}
.main-area{display:grid;grid-template-columns:1fr 350px;gap:20px}
@media(max-width:1100px){.main-area{grid-template-columns:1fr}}
.scenario-area{background:var(--card);border:1px solid #1e293b;border-radius:16px;padding:24px;min-height:400px}
.scenario-badge{display:inline-flex;align-items:center;gap:6px;background:linear-gradient(135deg,var(--accent),var(--accent2));color:white;padding:6px 16px;border-radius:20px;font-size:.8em;font-weight:700;margin-bottom:16px}
.scenario-title{font-size:1.4em;font-weight:700;margin-bottom:12px;line-height:1.3}
.scenario-text{color:var(--text2);line-height:1.7;margin-bottom:20px;padding:16px;background:var(--card2);border-radius:12px;border-left:3px solid var(--accent)}
.scenario-meta{display:flex;gap:12px;margin-bottom:20px;flex-wrap:wrap}
.meta-tag{font-size:.8em;padding:4px 12px;border-radius:20px;background:var(--card2);color:var(--text2)}
.meta-tag.urgent{background:rgba(239,68,68,.15);color:var(--danger)}
.meta-tag.opportunity{background:rgba(16,185,129,.15);color:var(--success)}
.choices-list{display:flex;flex-direction:column;gap:12px}
.choice-card{background:var(--card2);border:1px solid #1e293b;border-radius:14px;padding:18px;cursor:pointer;transition:all .3s;text-align:left;position:relative;overflow:hidden}
.choice-card:hover{border-color:var(--accent);transform:translateX(6px);box-shadow:0 4px 20px rgba(99,102,241,.1)}
.choice-card .choice-title{font-weight:700;font-size:1.05em;margin-bottom:6px;display:flex;align-items:center;gap:8px}
.choice-card .choice-desc{color:var(--text2);font-size:.9em;margin-bottom:12px;line-height:1.5}
.choice-impacts{display:flex;flex-wrap:wrap;gap:8px}
.impact-chip{font-size:.78em;padding:4px 10px;border-radius:8px;font-weight:600}
.impact-chip.pos{background:rgba(16,185,129,.15);color:#34d399}
.impact-chip.neg{background:rgba(239,68,68,.15);color:#f87171}
.impact-chip.neu{background:rgba(148,163,184,.15);color:#94a3b8}
.choice-risk{position:absolute;top:12px;right:12px;font-size:.7em;padding:2px 8px;border-radius:6px;font-weight:700}
.choice-risk.low{background:rgba(16,185,129,.2);color:#34d399}
.choice-risk.med{background:rgba(245,158,11,.2);color:#fbbf24}
.choice-risk.high{background:rgba(239,68,68,.2);color:#f87171}
.side-panel{display:flex;flex-direction:column;gap:15px}
.log-panel{background:var(--card);border:1px solid #1e293b;border-radius:16px;padding:18px;max-height:400px;overflow-y:auto}
.log-entry{padding:10px 0;border-bottom:1px solid #1e293b;font-size:.85em;animation:fadeIn .4s}
.log-entry:last-child{border-bottom:none}
.log-entry .log-week{color:var(--accent);font-weight:700;font-size:.8em;margin-bottom:4px}
.log-entry .log-text{color:var(--text2);line-height:1.5}
.log-entry.crisis .log-week{color:var(--danger)}
.log-entry.opportunity .log-week{color:var(--success)}
.result-screen{text-align:center;padding:40px 20px;animation:slideUp .6s}
@keyframes slideUp{from{opacity:0;transform:translateY(40px)}to{opacity:1;transform:translateY(0)}}
.result-screen .result-emoji{font-size:4em;margin-bottom:20px}
.result-screen h2{font-size:2.2em;margin-bottom:12px}
.result-screen p{color:var(--text2);font-size:1.1em;max-width:600px;margin:0 auto 30px}
.result-stats-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:15px;max-width:900px;margin:0 auto 30px}
.result-stat-card{background:var(--card);border:1px solid #1e293b;border-radius:14px;padding:20px}
.result-stat-card .stat-icon{font-size:1.8em;margin-bottom:8px}
.result-stat-card .stat-value{font-size:1.8em;font-weight:700}
.result-stat-card .stat-label{font-size:.8em;color:var(--text2);margin-top:4px}
.btn{background:linear-gradient(135deg,var(--accent),var(--accent2));color:white;border:none;padding:14px 36px;border-radius:12px;font-size:1em;font-weight:600;cursor:pointer;transition:all .3s}
.btn:hover{transform:translateY(-2px);box-shadow:0 10px 30px rgba(99,102,241,.3)}
.btn-outline{background:transparent;border:1px solid var(--accent);color:var(--accent);margin-left:10px}
.hidden{display:none!important}
.crisis-banner{background:linear-gradient(90deg,rgba(239,68,68,.2),rgba(245,158,11,.2));border:1px solid rgba(239,68,68,.3);border-radius:12px;padding:16px;margin-bottom:20px;display:flex;align-items:center;gap:12px;animation:pulse-red 2s infinite}
@keyframes pulse-red{0%,100%{box-shadow:0 0 0 0 rgba(239,68,68,.2)}50%{box-shadow:0 0 15px 0 rgba(239,68,68,.3)}}
.crisis-banner .crisis-icon{font-size:1.8em}
.crisis-banner .crisis-text{flex:1}
.crisis-banner .crisis-title{font-weight:700;margin-bottom:4px}
.crisis-banner .crisis-desc{font-size:.9em;color:var(--text2)}

/* PM PROFILE STYLES */
.pm-profile{background:var(--card);border:1px solid #1e293b;border-radius:20px;padding:30px;margin-bottom:30px;text-align:left}
.pm-profile h3{color:var(--accent);font-size:1.3em;margin-bottom:20px;display:flex;align-items:center;gap:10px}
.pm-profile-grid{display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-bottom:20px}
@media(max-width:768px){.pm-profile-grid{grid-template-columns:1fr}}
.pm-strength{background:rgba(16,185,129,.1);border:1px solid rgba(16,185,129,.3);border-radius:12px;padding:16px}
.pm-weakness{background:rgba(239,68,68,.1);border:1px solid rgba(239,68,68,.3);border-radius:12px;padding:16px}
.pm-strength h4{color:#34d399;margin-bottom:10px;font-size:1em}
.pm-weakness h4{color:#f87171;margin-bottom:10px;font-size:1em}
.pm-skill-item{display:flex;align-items:center;gap:10px;margin-bottom:8px;font-size:.9em}
.pm-skill-bar{flex:1;height:6px;background:#1e293b;border-radius:3px;overflow:hidden}
.pm-skill-fill{height:100%;border-radius:3px}
.pm-recommendation{background:var(--card2);border-radius:12px;padding:16px;margin-top:15px;font-size:.9em;color:var(--text2)}
.pm-recommendation strong{color:var(--text)}

/* CASE STUDIES */
.case-study{background:var(--card);border:1px solid #1e293b;border-radius:16px;padding:20px;margin-bottom:15px;text-align:left}
.case-study h4{color:var(--warn);font-size:1.1em;margin-bottom:10px;display:flex;align-items:center;gap:8px}
.case-study .case-meta{font-size:.8em;color:var(--text3);margin-bottom:10px}
.case-study p{font-size:.9em;color:var(--text2);line-height:1.6;margin-bottom:10px}
.case-study .case-lesson{background:rgba(99,102,241,.1);border-left:3px solid var(--accent);padding:10px 14px;border-radius:8px;font-size:.85em;color:var(--text2)}

/* TOOLS GRID */
.tools-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:15px;margin-top:20px}
.tool-card{background:var(--card2);border:1px solid #1e293b;border-radius:12px;padding:16px;text-align:left;transition:all .3s}
.tool-card:hover{border-color:var(--accent);transform:translateY(-3px)}
.tool-card .tool-icon{font-size:2em;margin-bottom:10px}
.tool-card .tool-name{font-weight:700;color:var(--text);margin-bottom:6px}
.tool-card .tool-desc{font-size:.8em;color:var(--text2);margin-bottom:10px}
.tool-card .tool-tag{display:inline-block;font-size:.7em;padding:3px 10px;border-radius:20px;background:rgba(99,102,241,.15);color:var(--accent);margin-right:5px;margin-bottom:5px}

::-webkit-scrollbar{width:8px}
::-webkit-scrollbar-track{background:var(--bg)}
::-webkit-scrollbar-thumb{background:#334155;border-radius:4px}
</style>
<base target="_blank">
</head>
<body>
<div class="container">
<header><h1>🚀 Project Management Simulator PRO MAX</h1><p>Продвинутая симуляция с персональным профилем PM, реальными кейсами и профессиональными инструментами</p></header>
<div id="game-screen">
<div class="top-grid">
<div class="panel"><h3>📊 Метрики проекта</h3>
<div class="metrics-grid">
<div class="metric-item metric-budget"><div class="label"><span>💰 Бюджет</span><span id="budget-text">$500K</span></div><div class="value" id="budget-val">100%</div><div class="metric-bar"><div class="metric-bar-fill" id="budget-bar" style="width:100%"></div></div></div>
<div class="metric-item metric-timeline"><div class="label"><span>⏱️ Сроки</span><span id="timeline-text">24 недели</span></div><div class="value" id="timeline-val">100%</div><div class="metric-bar"><div class="metric-bar-fill" id="timeline-bar" style="width:100%"></div></div></div>
<div class="metric-item metric-quality"><div class="label"><span>✨ Качество</span><span>Техдолг: <span id="techdebt-text">15%</span></span></div><div class="value" id="quality-val">85%</div><div class="metric-bar"><div class="metric-bar-fill" id="quality-bar" style="width:85%"></div></div></div>
<div class="metric-item metric-morale"><div class="label"><span>😊 Мораль</span><span id="burnout-text">Норма</span></div><div class="value" id="morale-val">75%</div><div class="metric-bar"><div class="metric-bar-fill" id="morale-bar" style="width:75%"></div></div></div>
<div class="metric-item metric-scope"><div class="label"><span>📋 Scope</span><span id="features-text">0/12 фич</span></div><div class="value" id="scope-val">100%</div><div class="metric-bar"><div class="metric-bar-fill" id="scope-bar" style="width:100%"></div></div></div>
<div class="metric-item metric-risk"><div class="label"><span>⚡ Риск</span><span id="risk-level">Средний</span></div><div class="value" id="risk-val">30%</div><div class="metric-bar"><div class="metric-bar-fill" id="risk-bar" style="width:30%"></div></div></div>
</div></div>
<div class="panel"><h3>🎯 Навыки PM</h3>
<div class="skills-grid">
<div class="skill-item"><div class="skill-name"><span>Переговоры</span><span class="skill-level" id="skill-negotiation">1</span></div><div class="skill-bar"><div class="skill-bar-fill" id="skill-negotiation-bar" style="width:10%"></div></div></div>
<div class="skill-item"><div class="skill-name"><span>Тех. экспертиза</span><span class="skill-level" id="skill-tech">1</span></div><div class="skill-bar"><div class="skill-bar-fill" id="skill-tech-bar" style="width:10%"></div></div></div>
<div class="skill-item"><div class="skill-name"><span>Кризис-менеджмент</span><span class="skill-level" id="skill-crisis">1</span></div><div class="skill-bar"><div class="skill-bar-fill" id="skill-crisis-bar" style="width:10%"></div></div></div>
<div class="skill-item"><div class="skill-name"><span>Коммуникация</span><span class="skill-level" id="skill-comm">1</span></div><div class="skill-bar"><div class="skill-bar-fill" id="skill-comm-bar" style="width:10%"></div></div></div>
<div class="skill-item"><div class="skill-name"><span>Аналитика</span><span class="skill-level" id="skill-analytics">1</span></div><div class="skill-bar"><div class="skill-bar-fill" id="skill-analytics-bar" style="width:10%"></div></div></div>
<div class="skill-item"><div class="skill-name"><span>Лидерство</span><span class="skill-level" id="skill-leadership">1</span></div><div class="skill-bar"><div class="skill-bar-fill" id="skill-leadership-bar" style="width:10%"></div></div></div>
</div></div>
<div class="panel"><h3>👥 Стейкхолдеры</h3><div class="status-grid" id="stakeholders-list"></div></div>
</div>
<div class="timeline-track" id="timeline-track"></div>
<div class="main-area">
<div class="scenario-area" id="scenario-container"></div>
<div class="side-panel">
<div class="log-panel"><h3 style="font-size:.85em;text-transform:uppercase;letter-spacing:1px;color:var(--text2);margin-bottom:12px;">📜 Журнал событий</h3><div id="log-content"></div></div>
</div>
</div>
</div>
<div id="result-screen" class="result-screen hidden"></div>
</div>
<script>
const Game={budget:100,timeline:100,quality:85,morale:75,scope:100,risk:30,techDebt:15,featuresDone:0,totalFeatures:12,week:1,totalWeeks:24,phase:0,day:1,history:[],decisions:[],skills:{negotiation:1,tech:1,crisis:1,comm:1,analytics:1,leadership:1},stakeholders:[{id:'client',name:'Алексей В.',role:'Заказчик',mood:70,emoji:'👔'},{id:'team',name:'Команда',role:'Разработчики',mood:75,emoji:'👨‍💻'},{id:'cto',name:'Мария К.',role:'CTO',mood:60,emoji:'👩‍💼'},{id:'investor',name:'Венчурный фонд',role:'Инвестор',mood:50,emoji:'💼'},{id:'qa',name:'Отдел QA',role:'Тестирование',mood:65,emoji:'🐞'}],money:500000,moneySpent:0,moneyTotal:500000,getPhaseName(){const p=['Инициация','Планирование','Разработка','Тестирование','Деплой','Поддержка'];return p[this.phase]||'Завершено'}};
const PHASES=[{name:'Инициация',icon:'📋',weeks:2},{name:'Планирование',icon:'📐',weeks:4},{name:'Разработка',icon:'💻',weeks:10},{name:'Тестирование',icon:'🐞',weeks:4},{name:'Деплой',icon:'🚀',weeks:2},{name:'Поддержка',icon:'🔧',weeks:2}];

const Scenarios={
0:[
{id:'init_scope',title:'Первое совещание с заказчиком',text:'Алексей В. представляет видение: AI-ассистент для юристов с анализом договоров, предиктивной аналитикой и интеграцией с 8 внешними сервисами. Бюджет $500K, срок 5 месяцев. Просит добавить голосовой интерфейс и мобильное приложение.',tags:['scope','negotiation'],urgency:'normal',choices:[
{title:"Принять всё 'в доверительных отношениях'",desc:'Согласиться на все требования без документирования',impacts:{budget:-25,timeline:-25,scope:35,quality:-15,risk:20},result:'Заказчик в восторге... пока. Объем вырос на 60%. Команда в шоке, сроки нереальны.',risk:'high',skills:{},stakeholder:{client:20,team:-30}},
{title:"Жестко отказать: 'ТЗ есть ТЗ'",desc:'Никаких отклонений, работаем строго по документу',impacts:{morale:-10,risk:-5},result:'Заказчик обижен. Отношения испорчены. Но границы четкие.',risk:'med',skills:{negotiation:1},stakeholder:{client:-25,team:5}},
{title:'Провести workshop и приоритизировать',desc:'MoSCoW-метод + MVP + дорожная карта',impacts:{budget:-5,timeline:-5,quality:5,risk:-10},result:'Профессиональный подход. Заказчик уважает экспертизу. MVP определен, бонусы — в фазу 2.',risk:'low',skills:{negotiation:2,analytics:1,comm:1},stakeholder:{client:15,team:10}},
{title:'Предложить альтернативное решение',desc:'Вместо голосового — чат-бот, вместо нативного — PWA',impacts:{budget:-10,timeline:-5,quality:10,risk:-5},result:'Нашли креативный компромисс. Функционал сохранен, сложность снижена. Заказчик впечатлен.',risk:'low',skills:{tech:2,negotiation:1},stakeholder:{client:25,team:5}}
]},
{id:'init_arch',title:'Архитектурный комитет',text:'CTO Мария К. настаивает на микросервисах с Kubernetes. Ведущий разработчик Иван предлагает модульный монолит на Django + FastAPI. Заказчик хочет современное решение.',tags:['tech','architecture'],urgency:'normal',choices:[
{title:'Микросервисы + K8s',desc:'Enterprise-уровень, масштабируемость',impacts:{budget:-30,timeline:-20,quality:15,risk:10},result:'Архитектура мощная, но команда тратит 40% времени на инфраструктуру вместо фич.',risk:'high',skills:{tech:2},stakeholder:{cto:20,team:-15}},
{title:'Модульный монолит',desc:'Быстрее в разработке, проще в поддержке',impacts:{budget:10,timeline:15,quality:5,risk:-10},result:'Разработка идет быстро. Код чистый. Но CTO считает решение не масштабируемым.',risk:'low',skills:{tech:1},stakeholder:{cto:-15,team:15}},
{title:'Гибрид: core-монолит + микросервисы для AI',desc:'Разумный компромисс',impacts:{budget:-10,timeline:-5,quality:10,risk:0},result:'Оптимальный баланс. Основная логика в монолите, тяжелые AI-задачи изолированы.',risk:'med',skills:{tech:3,negotiation:1},stakeholder:{cto:10,team:10}},
{title:'Провести Proof of Concept (2 недели)',desc:'Сравнить оба подхода на реальных данных',impacts:{budget:-8,timeline:-10,quality:15,risk:-15},result:'PoC дал объективные данные. Выбрали гибрид. Все стороны довольны обоснованностью.',risk:'low',skills:{tech:2,analytics:2},stakeholder:{cto:15,client:10}}
]},
{id:'init_investor',title:'Встреча с инвесторами',text:'Венчурный фонд требует ускорить сроки на 30% для демо на конференции через 3 месяца. Взамен — дополнительные $200K, но с условием эксклюзивности на 2 года.',tags:['business','negotiation'],urgency:'high',choices:[
{title:'Согласиться на ускорение + эксклюзив',desc:'Деньги сейчас, риски потом',impacts:{budget:40,timeline:-30,morale:-20,risk:25,scope:10},result:'Бюджет вырос, но команда в панике. Сжатые сроки + эксклюзивность = технический долг и потеря гибкости.',risk:'high',skills:{negotiation:1},stakeholder:{investor:25,team:-30,client:10}},
{title:'Отказаться от эксклюзивности',desc:'Сохранить свободу действий',impacts:{budget:0,risk:-5},result:'Инвестор недоволен. Финансирование под вопросом. Но компания сохранила независимость.',risk:'med',skills:{negotiation:2},stakeholder:{investor:-20,client:-5}},
{title:'Пересмотреть условия: $100K + ускорение 15% + 1 год эксклюзив',desc:'Жесткий торг',impacts:{budget:20,timeline:-15,risk:10},result:'Сложные переговоры, но выгодный компромисс. Инвестор уважает твердость позиции.',risk:'med',skills:{negotiation:3},stakeholder:{investor:15,client:5}},
{title:'Предложить альтернативу: демо на MVP без ускорения',desc:'Показать прогресс без рисков',impacts:{budget:5,quality:10,risk:-10},result:'Инвестор оценил честность. Демо MVP произвело впечатление. Финансирование сохранено без жертв.',risk:'low',skills:{negotiation:2,comm:2,analytics:1},stakeholder:{investor:15,team:10}}
]}
],
1:[
{id:'plan_estimates',title:'Оценка сроков: Planning Poker',text:'Команда оценивает проект в 28 недель. Заказчик требует 20. CTO считает 24 реалистично. Инвесторы хотят демо через 12 недель.',tags:['planning','estimates'],urgency:'high',choices:[
{title:"Принять 20 недель и 'как-нибудь уложимся'",desc:'Обещать невозможное',impacts:{timeline:30,morale:-30,quality:-25,risk:30,techDebt:20},result:'Команда в отчаянии. Начинается хакатон-режим. Код превращается в лапшу.',risk:'high',skills:{},stakeholder:{team:-40,client:10,cto:-10}},
{title:'Отстоять 28 недель',desc:'Честная оценка несмотря на давление',impacts:{timeline:-10,morale:15,risk:-10},result:'Все недовольны сроками, но команда уверена в оценке. Качество будет высоким.',risk:'low',skills:{leadership:2,negotiation:1},stakeholder:{team:20,client:-20,investor:-15}},
{title:'24 недели + параллельные треки + риск-буфер',desc:'Оптимизация через процессы',impacts:{timeline:-5,budget:-10,morale:5,risk:-5},result:'Сложное планирование, но выполнимо. Риски учтены, буфер — 2 недели.',risk:'med',skills:{analytics:2,leadership:1},stakeholder:{team:10,client:5,cto:10}},
{title:'Фазированный подход: MVP за 12 недель, v1.0 за 24',desc:'Разделить на этапы',impacts:{timeline:5,budget:-5,quality:10,risk:-15,scope:-10},result:'Все получили желаемое: инвесторы — демо, клиент — MVP, команда — реалистичные сроки.',risk:'low',skills:{negotiation:3,analytics:2,comm:2},stakeholder:{investor:20,client:15,team:15}}
]},
{id:'plan_hiring',title:'Стратегия найма команды',text:'Нужно 5 разработчиков, 2 QA, 1 DevOps. HR говорит, что рынок перегрет. Средний срок поиска сеньора — 2 месяца. Проект стартует через 2 недели.',tags:['team','hiring'],urgency:'high',choices:[
{title:'Нанять аутсорс-команду целиком',desc:'Быстро, но дорого и рискованно',impacts:{budget:-35,timeline:10,quality:-15,morale:10,risk:20},result:'Команда собрана за неделю, но коммуникация — кошмар. Кодовая база разнородна.',risk:'high',skills:{},stakeholder:{team:5,cto:-20}},
{title:'Нанять 2 сеньоров + 3 мидла + обучение',desc:'Качественный core, растущая команда',impacts:{budget:-25,timeline:-10,quality:15,morale:5},result:'Сильное ядро команды. Мидлы быстро растут. Но поиск занял 6 недель.',risk:'med',skills:{leadership:2},stakeholder:{team:15,cto:15}},
{title:'Гибрид: 3 фрилансера + 2 штатных + аутсорс QA',desc:'Гибкость состава',impacts:{budget:-15,timeline:0,quality:-5,risk:15},result:'Баланс скорости и качества. Но управление распределенной командой — вызов.',risk:'med',skills:{leadership:1,comm:1},stakeholder:{team:0,cto:5}},
{title:'Предложить текущей команде переработки + бонусы',desc:'Мотивировать имеющихся',impacts:{budget:-10,timeline:5,morale:-15,quality:-10,risk:10},result:'Команда перегружена. Начинается текучка. Но проект стартовал в срок.',risk:'high',skills:{leadership:1},stakeholder:{team:-25,cto:-10}}
]},
{id:'plan_stack',title:'Технологический стек: спор в команде',text:'Frontend: React vs Vue vs Svelte. Backend: Python vs Go vs Node. AI: собственная модель vs OpenAI API vs open-source LLM.',tags:['tech','architecture'],urgency:'normal',choices:[
{title:'Позволить команде решить голосованием',desc:'Демократия',impacts:{morale:10,quality:-10,risk:15,techDebt:10},result:'Выбрали популярное, но не оптимальное. Техлид недоволен. Архитектура компромиссная.',risk:'med',skills:{leadership:1},stakeholder:{team:10,cto:-10}},
{title:'Техлид решает единолично',desc:'Авторитарный подход',impacts:{morale:-15,quality:10,risk:-5,timeline:5},result:'Технически верное решение, но команда чувствует себя неслышной. Минус доверие.',risk:'med',skills:{tech:1,leadership:-1},stakeholder:{team:-20,cto:15}},
{title:'R&D спринт: прототипировать на 3 стеках (1 неделя)',desc:'Дата-дривен решение',impacts:{budget:-8,timeline:-5,quality:20,risk:-15},result:'Объективные метрики: latency, accuracy, cost. Выбрали оптимальный стек. Все убеждены.',risk:'low',skills:{tech:3,analytics:2,leadership:2},stakeholder:{team:20,cto:20}},
{title:'Выбрать безопасный стек: React + Python + OpenAI',desc:'Проверенные технологии',impacts:{budget:-5,timeline:10,quality:5,risk:-10},result:'Классический стек. Много талантов на рынке. Но зависимость от OpenAI API — риск.',risk:'low',skills:{tech:1},stakeholder:{team:5,cto:5,client:5}}
]}
],
2:[
{id:'dev_sprint',title:'Спринт 3: горит дедлайн',text:'Команда не укладывается в спринт. 40% задач не завершено. Daily standups превратились в оправдания. Заказчик требует отчет.',tags:['agile','crisis'],urgency:'critical',choices:[
{title:'Устроить кранч: работаем по выходным',desc:'Жесткий режим до релиза',impacts:{timeline:15,morale:-30,quality:-20,risk:20,techDebt:15},result:'Спринт закрыт, но 2 разработчика заболели. Код написан на коленке.',risk:'high',skills:{crisis:1},stakeholder:{team:-35,client:5}},
{title:'Пересмотреть спринт: убрать 30% задач в бэклог',desc:'Честность перед командой',impacts:{timeline:-10,scope:-15,morale:15,risk:-10},result:'Реалистичные обязательства. Команда доверяет PM. Но scope сдвинулся.',risk:'low',skills:{leadership:2,analytics:1},stakeholder:{team:20,client:-10}},
{title:'Привлечь 2 фрилансера на спринт',desc:'Усилить команду временно',impacts:{budget:-15,timeline:5,quality:-10,risk:10},result:'Фрилансеры помогли, но онбординг занял 30% времени. Код непоследовательный.',risk:'med',skills:{leadership:1},stakeholder:{team:-5,cto:-5}},
{title:'Провести ретроспективу и найти корень проблем',desc:'Системный подход',impacts:{timeline:-5,quality:10,morale:10,risk:-15,techDebt:-5},result:'Нашли узкое место: неясные требования. Ввели refinement перед спринтами. Эффективность выросла.',risk:'low',skills:{leadership:3,analytics:2,comm:2},stakeholder:{team:25,cto:10}}
]},
{id:'dev_security',title:'Security audit: критические уязвимости',text:'Внешний аудит обнаружил: SQL-инъекции, отсутствие шифрования PII, устаревшие зависимости с CVE. Исправление — 3 недели. Заказчик не знал о проблемах.',tags:['security','crisis'],urgency:'critical',choices:[
{title:'Скрыть от заказчика, исправить тихо',desc:'Избежать паники',impacts:{timeline:-15,budget:-10,risk:35,quality:-20},result:'Уязвимости исправлены, но команда под давлением. Если всплывет — катастрофа репутации.',risk:'high',skills:{crisis:-1},stakeholder:{client:-5,team:-10,cto:-20}},
{title:'Полная прозрачность + план исправлений',desc:'Честность и ответственность',impacts:{timeline:-20,budget:-15,quality:25,risk:-25,morale:-5},result:'Заказчик шокирован, но оценил честность. Доверие выросло. Проблемы решены системно.',risk:'low',skills:{crisis:3,comm:2,leadership:2},stakeholder:{client:20,cto:15,team:5}},
{title:'Частичное исправление: только критичные CVE',desc:'Быстрый патч',impacts:{timeline:-8,budget:-5,risk:15,quality:-5},result:'Срочные дыры закрыты, но архитектура осталась уязвимой. Техдолг растет.',risk:'high',skills:{tech:1},stakeholder:{client:-5,cto:-10}},
{title:'Нанять security-консультанта + обучить команду',desc:'Инвестиции в будущее',impacts:{budget:-20,timeline:-10,quality:20,risk:-30,morale:10},result:'Команда обучена. Процессы security внедрены. Заказчик впечатлен проактивностью.',risk:'low',skills:{tech:2,leadership:2,crisis:2},stakeholder:{client:25,cto:20,team:15}}
]},
{id:'dev_scope_creep',title:"Scope Creep: 'это же просто кнопка'",text:'Заказчик просит интеграцию с CRM, которой не было в ТЗ. По оценке команды — 2 недели. Заказчик уверен, что это 2 дня. Угрожает остановить оплату.',tags:['scope','negotiation'],urgency:'high',choices:[
{title:'Согласиться ради отношений',desc:'Бесплатная работа',impacts:{budget:-15,timeline:-15,scope:20,morale:-20,risk:15},result:'Прецедент создан. Теперь каждая кнопка — бесплатно. Команда в бунте.',risk:'high',skills:{negotiation:-1},stakeholder:{client:15,team:-30}},
{title:'Жестко отказать и пригрозить контрактом',desc:'Правовая защита',impacts:{morale:5,risk:10},result:'Заказчик оскорблен. Переговоры пошли в судебное русло. Проект заморожен.',risk:'high',skills:{negotiation:1},stakeholder:{client:-40,investor:-10}},
{title:'Показать детальную оценку + предложить trade-off',desc:'Образование + переговоры',impacts:{budget:-5,timeline:-5,scope:10,morale:5},result:'Заказчик осознал сложность. Согласился на упрощенную версию CRM-интеграции.',risk:'med',skills:{negotiation:3,comm:2,analytics:1},stakeholder:{client:10,team:5}},
{title:'Вынести на Change Request Board с оценкой в $',desc:'Профессиональный процесс',impacts:{budget:5,timeline:-10,scope:15,risk:-5},result:'Формализованный процесс изменений. Заказчик платит за дополнительный scope. Все честно.',risk:'low',skills:{negotiation:2,analytics:2,leadership:1},stakeholder:{client:5,team:10,investor:10}}
]},
{id:'dev_key_dev',title:'Ключевой разработчик увольняется',text:'Ведущий backend-разработчик Иван получил офер на +50% зарплаты. Он — единственный, кто знает core-архитектуру. Уход через 2 недели. Знания не документированы.',tags:['team','crisis'],urgency:'critical',choices:[
{title:'Удержать деньгами: контрпредложение +60%',desc:'Дорого, но быстро',impacts:{budget:-25,morale:-10,risk:-10},result:'Иван остался, но другие разработчики требуют пересмотра зарплат. Зарплатная вилка разъехалась.',risk:'med',skills:{negotiation:2},stakeholder:{team:-15,cto:-10}},
{title:'Позволить уйти, нанять замену',desc:'Рынок решает',impacts:{timeline:-25,quality:-15,risk:20,morale:-15},result:'Новый разработчик 2 месяца разбирается. Критические баги в core. Проект в зоне риска.',risk:'high',skills:{leadership:1},stakeholder:{team:-20,cto:-15}},
{title:'Интенсивный knowledge transfer (2 недели) + менторство',desc:'Инвестиции в документацию',impacts:{timeline:-10,budget:-5,quality:-5,risk:-5,morale:5},result:'Документация создана. 2 разработчика обучены. Потеря не так болезненна.',risk:'low',skills:{leadership:3,comm:2,crisis:2},stakeholder:{team:10,cto:15}},
{title:'Предложить Ивану part-time консалтинг + акции',desc:'Долгосрочные отношения',impacts:{budget:-10,timeline:-5,risk:-15,morale:15},result:'Иван ушел, но консультирует 10 часов/неделю. Плюс мотивация через equity. Win-win.',risk:'low',skills:{negotiation:3,leadership:2},stakeholder:{team:15,cto:10,investor:5}}
]},
{id:'dev_tech_debt',title:'Технический долг достиг критической массы',text:'CI/CD падает 3 раза в неделю. Тесты покрывают 30%. Рефакторинг откладывался 4 спринта. Команда просит стоп-неделю для наведения порядка.',tags:['tech','process'],urgency:'high',choices:[
{title:'Продолжать фичи, техдолг — потом',desc:'Бизнес превыше всего',impacts:{timeline:10,quality:-30,risk:25,techDebt:25,morale:-25},result:'Скорость разработки падает экспоненциально. Баги множатся. Команда в отчаянии.',risk:'high',skills:{},stakeholder:{team:-30,cto:-25,qa:-20}},
{title:"Неделя 'чистки' без новых фич",desc:'Радикальная чистка',impacts:{timeline:-15,quality:25,risk:-20,techDebt:-30,morale:25},result:'Кодовая база очищена. CI/CD стабилен. Команда счастлива. Но сроки сдвинулись на 2 недели.',risk:'low',skills:{tech:2,leadership:2},stakeholder:{team:25,cto:20,qa:20}},
{title:'20% каждого спринта на техдолг',desc:'Постепенное улучшение',impacts:{timeline:-5,quality:15,risk:-10,techDebt:-15,morale:10},result:'Баланс найден. Техдолг контролируем. Скорость не падает.',risk:'low',skills:{tech:1,analytics:1,leadership:1},stakeholder:{team:15,cto:10}},
{title:'Нанять отдельного инженера качества',desc:'Специализация',impacts:{budget:-20,timeline:0,quality:20,risk:-15,techDebt:-20,morale:5},result:'Выделенный ресурс на качество. Тесты, CI/CD, документация — в его зоне. Эффективно.',risk:'low',skills:{tech:2,leadership:1},stakeholder:{team:10,cto:15,qa:25}}
]}
],
3:[
{id:'test_bugstorm',title:'Bug Storm: 120+ дефектов перед релизом',text:'QA обнаружил катастрофу: 15 критических, 45 серьезных, 60+ мелких. До дедлайна 2 недели. Команда 2 месяца не спала. Заказчик требует релиз как обещали.',tags:['qa','crisis'],urgency:'critical',choices:[
{title:'Релиз как есть + hotfix-план',desc:'Соблюсти слово любой ценой',impacts:{timeline:20,quality:-50,risk:40,morale:-30,techDebt:20},result:'Релиз провальный. 3 севера падают в первый день. Заказчик в ярости. Репутация уничтожена.',risk:'high',skills:{crisis:-1},stakeholder:{client:-50,team:-40,qa:-30,investor:-30}},
{title:'Отодвинуть релиз на 4 недели',desc:'Качество превыше сроков',impacts:{timeline:-30,quality:35,risk:-25,morale:15},result:'Продукт стабилен. Заказчик недоволен сроками, но ценит честность. Инвесторы нервничают.',risk:'low',skills:{leadership:3,crisis:2,comm:2},stakeholder:{client:10,team:20,qa:20,investor:-15}},
{title:'Только P0/P1 в релиз, остальное — patches',desc:'Приоритизация рисков',impacts:{timeline:-5,quality:10,risk:-5,techDebt:10,morale:-5},result:'Критический функционал работает. Мелкие баги — в бэклог. Разумный компромисс.',risk:'med',skills:{analytics:2,crisis:1},stakeholder:{client:5,team:0,qa:10}},
{title:'Emergency bug bash: всё отделение на 48 часов',desc:'Мобилизация',impacts:{timeline:5,quality:15,budget:-10,morale:-20,risk:5},result:'80% багов исправлено за выходные. Но команда на грани выгорания. Нужен отгул.',risk:'med',skills:{crisis:2,leadership:2},stakeholder:{team:-25,client:15}}
]},
{id:'test_load',title:'Нагрузочное тестирование: система падает',text:'При 800 concurrent users latency вырос до 8 секунд. SLA требует <2sec при 2000 users. Архитектурная проблема: синхронные запросы к AI-модели блокируют потоки.',tags:['performance','tech'],urgency:'high',choices:[
{title:'Апгрейд серверов: 3x мощность',desc:'Железное решение',impacts:{budget:-40,timeline:5,quality:5,risk:5},result:'Работает, но облачные расходы выросли с $5K до $18K/мес. Инвесторы вопросы задают.',risk:'med',skills:{tech:1},stakeholder:{investor:-15,cto:-5}},
{title:'Асинхронная архитектура + очереди (RabbitMQ)',desc:'Правильный инжиниринг',impacts:{budget:-10,timeline:-20,quality:25,risk:-20,techDebt:-10},result:'Система выдерживает 5000 users. Latency <1sec. Архитектура готова к масштабированию.',risk:'low',skills:{tech:3,analytics:1},stakeholder:{cto:25,team:15,client:15}},
{title:'Кэширование + CDN',desc:'Быстрое решение',impacts:{budget:-15,timeline:-5,quality:15,risk:-10},result:'Кэш снизил нагрузку на 60%. Быстрое решение, но не решает корневую проблему.',risk:'med',skills:{tech:2},stakeholder:{cto:10,team:5}},
{title:'Rate limiting + graceful degradation',desc:'Управляем ожиданиями',impacts:{budget:-5,timeline:-5,quality:-5,risk:15},result:'Пользователи получают запрос в обработке. Не идеально, но система стабильна.',risk:'high',skills:{tech:1},stakeholder:{client:-10,team:0}}
]},
{id:'test_uat',title:'UAT: заказчик отказывается принимать',text:'Алексей В. провел UAT и заявил: Это не то, что я представлял. 40% функционала не так работает. Он требует переделки, хотя по ТЗ всё корректно.',tags:['uAT','negotiation'],urgency:'critical',choices:[
{title:'Переделать всё под клиента',desc:'Клиент всегда прав',impacts:{budget:-35,timeline:-30,scope:30,quality:-20,morale:-25},result:'Проект превратился в бесконечную переделку. Команда сдается. Бюджет исчерпан.',risk:'high',skills:{negotiation:-1},stakeholder:{client:20,team:-40,investor:-20}},
{title:'Показать ТЗ и отказать',desc:'Правовая позиция',impacts:{risk:30,morale:5},result:'Заказчик в ярости. Контракт под угрозой. Но границы защищены.',risk:'high',skills:{negotiation:1},stakeholder:{client:-40,investor:-10}},
{title:'Провести демо + собрать обратную связь + итерация',desc:'Коллаборация',impacts:{budget:-15,timeline:-15,quality:15,morale:5},result:'Нашли недопонимание в требованиях. 60% проблем — ожидания vs реальность. Исправили UX.',risk:'med',skills:{comm:3,negotiation:2,analytics:1},stakeholder:{client:15,team:10}},
{title:'Пригласить UX-ресечера для интервью с заказчиком',desc:'Профессиональная диагностика',impacts:{budget:-10,timeline:-10,quality:20,risk:-10},result:'UX-исследование выявило: заказчик путал UI с логикой. Небольшие правки UI решили 70% проблем.',risk:'low',skills:{analytics:3,comm:2,negotiation:1},stakeholder:{client:25,team:15}}
]}
],
4:[
{id:'deploy_strategy',title:'Стратегия релиза: как выкатывать?',text:'Продукт готов. 5000 активных пользователей ждут. Заказчик боится простоев. CTO хочет Blue-Green. DevOps предлагает Canary.',tags:['deploy','strategy'],urgency:'high',choices:[
{title:'Big Bang: всё и сразу',desc:'Один момент истины',impacts:{timeline:15,quality:-30,budget:-5,risk:30,morale:-15},result:'6 часов даунтайма. 200 пользователей потеряли данные. Откат занял 4 часа. Катастрофа.',risk:'high',skills:{crisis:1},stakeholder:{client:-40,team:-20,investor:-20}},
{title:'Blue-Green деплой',desc:'Мгновенное переключение',impacts:{budget:-20,timeline:-5,quality:20,risk:-20},result:'Нулевой даунтайм. Мгновенный откат. Инфраструктура дороже, но надежность высокая.',risk:'low',skills:{tech:2},stakeholder:{client:20,cto:20,team:10}},
{title:'Canary: 5% → 25% → 100% за 3 дня',desc:'Постепенное распространение',impacts:{budget:-10,timeline:-10,quality:25,risk:-25},result:'Нашли критический баг на 5% трафика. Исправили за 2 часа. 95% пользователей не заметили.',risk:'low',skills:{tech:2,analytics:2},stakeholder:{client:25,cto:15,team:15}},
{title:'Feature flags: включать функции постепенно',desc:'Максимальный контроль',impacts:{budget:-15,timeline:-5,quality:30,risk:-30,techDebt:-5},result:'Каждая фича включается отдельно. A/B тесты на лету. DevOps и продукт в восторге.',risk:'low',skills:{tech:3,analytics:2},stakeholder:{cto:25,client:20,team:20}}
]},
{id:'deploy_incident',title:'Инцидент в продакшене: P0',text:'Через 2 часа после релиза: база данных перегружена, 500 ошибки, пользователи в Twitter жалуются. On-call инженер не отвечает. Кризис в реальном времени.',tags:['incident','crisis'],urgency:'critical',choices:[
{title:'Откатить на предыдущую версию немедленно',desc:'Безопасность превыше всего',impacts:{timeline:-5,quality:10,risk:-20,morale:-5},result:'Откат за 15 минут. Система стабильна. Потеряли 2 часа данных, но избежали катастрофы.',risk:'low',skills:{crisis:3,tech:2},stakeholder:{client:5,team:5,cto:15}},
{title:'Пытаться починить на лету',desc:'Героизм',impacts:{timeline:-10,quality:-25,risk:35,morale:-20},result:'3 часа борьбы. Проблема усугубилась. Потеряли 6 часов данных. Команда в шоке.',risk:'high',skills:{crisis:-1},stakeholder:{client:-30,team:-30,investor:-20}},
{title:'Активировать war room + эскалировать',desc:'Системный кризис-менеджмент',impacts:{timeline:-5,budget:-5,quality:15,risk:-15,morale:5},result:'War room собрал экспертов. Корневая причина найдена за 30 минут. Патч за 1 час.',risk:'low',skills:{crisis:3,leadership:3,comm:2},stakeholder:{client:20,cto:20,team:15}},
{title:'Включить circuit breaker + ограничить функционал',desc:'Graceful degradation',impacts:{timeline:0,quality:-5,risk:-10},result:'Система работает в ограниченном режиме. Пользователи недовольны, но сервис жив.',risk:'med',skills:{tech:2,crisis:2},stakeholder:{client:-10,team:5}}
]}
],
5:[
{id:'support_burnout',title:'Команда на грани выгорания',text:'6 месяцев интенсивной работы. 3 разработчика подали заявления на отпуск. 1 — на увольнение. Заказчик требует новый функционал сразу после релиза.',tags:['team','wellness'],urgency:'high',choices:[
{title:'Отпустить всех в отпуск на 2 недели',desc:'Здоровье команды',impacts:{timeline:-20,morale:35,quality:10,risk:-10},result:'Команда восстановилась. Но заказчик недоволен паузой. Инвесторы нервничают.',risk:'low',skills:{leadership:3},stakeholder:{team:35,client:-15,investor:-10}},
{title:'Продолжать разработку, обещать отпуск потом',desc:'Бизнес превыше',impacts:{timeline:10,morale:-40,quality:-20,risk:25},result:'Еще 2 увольнения. Оставшиеся работают в полсилы. Проект замедляется катастрофически.',risk:'high',skills:{leadership:-2},stakeholder:{team:-45,cto:-20}},
{title:'Ротация: половина в отпуск, половина на поддержке',desc:'Баланс',impacts:{timeline:-5,morale:20,quality:5,budget:-5},result:'Команда отдыхает по очереди. Поддержка не страдает. Заказчик получает critical fixes.',risk:'low',skills:{leadership:2,comm:1},stakeholder:{team:20,client:5}},
{title:'Нанять 2 новых разработчика + отпуск текущим',desc:'Инвестиции в людей',impacts:{budget:-30,timeline:-10,morale:25,quality:5},result:'Новые кадры пришли, команда отдохнула. Но онбординг замедлил разработку на месяц.',risk:'med',skills:{leadership:2},stakeholder:{team:25,cto:10,investor:-10}}
]},
{id:'support_feedback',title:'Первые отзывы пользователей',text:'App Store: 3.2★. Жалобы: медленный AI-ответ, сложный UI, нет мобильной версии. Позитив: точность анализа договоров. Заказчик хочет исправить всё за неделю.',tags:['product','feedback'],urgency:'normal',choices:[
{title:'Срочный патч: только критичное',desc:'Быстрые победы',impacts:{timeline:-5,quality:15,morale:-10,risk:-5},result:'Latency снижена на 40%. UI улучшен. Рейтинг вырос до 3.8★. Но команда устала.',risk:'med',skills:{analytics:1,tech:1},stakeholder:{client:15,team:-10}},
{title:'Глубокий анализ + роадмап улучшений',desc:'Стратегический подход',impacts:{timeline:-10,budget:-10,quality:25,risk:-15},result:'Провели 50 интервью. Сформировали Q2 роадмап. Заказчик впечатлен системностью.',risk:'low',skills:{analytics:3,comm:2,leadership:1},stakeholder:{client:20,investor:15}},
{title:'Игнорировать, фокус на новых фичах',desc:'Двигаемся вперед',impacts:{timeline:10,quality:-15,risk:20,morale:5},result:'Рейтинг упал до 2.8★. Пользователи уходят к конкурентам. Заказчик в панике.',risk:'high',skills:{},stakeholder:{client:-25,investor:-20,team:5}},
{title:'Публичный баг-трекер + программа бета-тестеров',desc:'Открытость',impacts:{budget:-5,quality:20,morale:15,risk:-10},result:'Сообщество вовлечено. 200 бета-тестеров. Рейтинг вырос до 4.1★. Лояльность растет.',risk:'low',skills:{comm:3,leadership:2,analytics:1},stakeholder:{client:25,team:15}}
]}
]
};

const RandomEvents=[
{title:'🌐 AWS упал в us-east-1',text:'Крупнейший регион AWS недоступен 4 часа. Наши сервера в другом регионе, но CDN пострадал.',impacts:{budget:-5,timeline:-3,risk:10},result:'Переключились на резервный CDN. Потеряли $2K на трафик.'},
{title:'📰 Конкурент запустил аналогичный продукт',text:'Крупный игрок рынка анонсировал AI-ассистента с похожим функционалом. Заказчик в панике.',impacts:{morale:-10,risk:15,timeline:-5},result:'Нужно ускорить релиз и дифференцироваться. Стресс в команде.'},
{title:'💻 Gitlab сбросил репозиторий',text:'Инцидент с Gitlab: часть веток потеряна. Последний бэкап — 2 дня назад.',impacts:{timeline:-8,quality:-10,morale:-15,techDebt:5},result:'Восстановили из бэкапов. Потеряли 2 дня работы. Команда в шоке.'},
{title:'🏆 Проект номинирован на премию',text:'Индустриальная премия номинировала продукт в категории Лучший AI-стартап. PR-возможность!',impacts:{morale:20,budget:5,risk:-5},result:'Команда мотивирована. Инвесторы впечатлены. Нужен кейс для премии.'},
{title:'🔒 Утечка данных (фейк, но паника)',text:'В соцсетях распространился фейк об утечке данных. Пользователи беспокоятся.',impacts:{risk:20,morale:-5,budget:-3},result:'Пришлось выпустить пресс-релиз и провести аудит. Репутация под угрозой.'},
{title:'🎓 Ключевой разработчик выиграл хакатон',text:'Иван занял 1-е место на хакатоне Google. Его оферы от FAANG утроились.',impacts:{morale:15,risk:10},result:'Команда гордится. Но риск ухода Ивана вырос. Нужно удерживать.'}
];

function renderMetrics(){const m=Game;['budget','timeline','quality','morale','scope','risk'].forEach(key=>{let val=Math.max(0,Math.min(100,m[key]));m[key]=val;document.getElementById(key+'-val').textContent=Math.round(val)+'%';document.getElementById(key+'-bar').style.width=val+'%'});document.getElementById('budget-text').textContent='$'+Math.round(m.money/1000)+'K';document.getElementById('timeline-text').textContent=Math.round(m.totalWeeks-(100-m.timeline)*m.totalWeeks/100)+' недель';document.getElementById('techdebt-text').textContent=Math.round(m.techDebt)+'%';document.getElementById('features-text').textContent=m.featuresDone+'/'+m.totalFeatures+' фич';let riskText='Низкий';if(m.risk>30)riskText='Средний';if(m.risk>60)riskText='Высокий';if(m.risk>80)riskText='Критический';document.getElementById('risk-level').textContent=riskText;let burnoutText='Норма';if(m.morale<60)burnoutText='Стресс';if(m.morale<40)burnoutText='Выгорание';if(m.morale<20)burnoutText='Кризис';document.getElementById('burnout-text').textContent=burnoutText}
function renderSkills(){['negotiation','tech','crisis','comm','analytics','leadership'].forEach(s=>{const val=Game.skills[s];document.getElementById('skill-'+s).textContent=val;document.getElementById('skill-'+s+'-bar').style.width=(val*10)+'%'})}
function renderStakeholders(){const c=document.getElementById('stakeholders-list');c.innerHTML=Game.stakeholders.map(s=>{let mood='😐';if(s.mood>80)mood='😊';else if(s.mood>60)mood='🙂';else if(s.mood>40)mood='😕';else if(s.mood>20)mood='😠';else mood='😡';return '<div class="stakeholder"><div class="stakeholder-avatar">'+s.emoji+'</div><div class="stakeholder-info"><div class="stakeholder-name">'+s.name+'</div><div class="stakeholder-role">'+s.role+'</div></div><div class="stakeholder-mood">'+mood+'</div></div>'}).join('')}
function renderTimeline(){const t=document.getElementById('timeline-track');t.innerHTML=PHASES.map((p,i)=>{let cls='';if(i<Game.phase)cls='completed';else if(i===Game.phase)cls='active';return '<div class="timeline-phase '+cls+'"><div class="phase-icon">'+p.icon+'</div><div class="phase-name">'+p.name+'</div><div class="phase-weeks">'+p.weeks+' недель</div></div>'}).join('')}
function addLog(text,type='normal'){const log=document.getElementById('log-content');const entry=document.createElement('div');entry.className='log-entry '+type;entry.innerHTML='<div class="log-week">Неделя '+Game.week+'</div><div class="log-text">'+text+'</div>';log.insertBefore(entry,log.firstChild);Game.week+=Math.floor(Math.random()*2)+1}
function applyImpacts(impacts){for(let[key,val]of Object.entries(impacts)){if(key==='techDebt')Game.techDebt=Math.max(0,Math.min(100,Game.techDebt+val));else if(key==='featuresDone')Game.featuresDone=Math.max(0,Math.min(Game.totalFeatures,Game.featuresDone+val));else if(key==='money')Game.money=Math.max(0,Game.money+val);else if(Game[key]!==undefined)Game[key]=Math.max(0,Math.min(100,Game[key]+val))}Game.risk=Math.min(100,(Game.techDebt*.4)+((100-Game.quality)*.3)+((100-Game.morale)*.2)+(Math.random()*10))}
function updateStakeholders(stakeholderImpacts){if(!stakeholderImpacts)return;for(let[id,val]of Object.entries(stakeholderImpacts)){const s=Game.stakeholders.find(x=>x.id===id);if(s)s.mood=Math.max(0,Math.min(100,s.mood+val))}}
function updateSkills(skillImpacts){if(!skillImpacts)return;for(let[skill,val]of Object.entries(skillImpacts)){if(Game.skills[skill]!==undefined)Game.skills[skill]=Math.max(1,Math.min(10,Game.skills[skill]+val))}}

let currentScenario=null;
let currentScenarioIndex=0;

function getAvailableScenarios(){const phaseScenarios=Scenarios[Game.phase]||[];return phaseScenarios.filter(s=>!Game.decisions.includes(s.id))}

function renderScenario(){const container=document.getElementById('scenario-container');const available=getAvailableScenarios();if(available.length===0){Game.phase++;if(Game.phase>=6){showResult();return}renderTimeline();renderScenario();return}const scenario=available[Math.floor(Math.random()*available.length)];currentScenario=scenario;currentScenarioIndex=Scenarios[Game.phase].indexOf(scenario);let urgencyClass='';let urgencyText='';if(scenario.urgency==='critical'){urgencyClass='urgent';urgencyText='🔴 КРИТИЧНО'}else if(scenario.urgency==='high'){urgencyClass='urgent';urgencyText='🟠 ВАЖНО'}else{urgencyText='🟢 НОРМА'}let tagsHtml=scenario.tags.map(t=>'<span class="meta-tag">'+t+'</span>').join('');if(urgencyText)tagsHtml+='<span class="meta-tag '+urgencyClass+'">'+urgencyText+'</span>';let choicesHtml=scenario.choices.map((c,i)=>{let impactsHtml=[];for(let[k,v]of Object.entries(c.impacts)){const names={budget:'💰',timeline:'⏱️',quality:'✨',morale:'😊',scope:'📋',risk:'⚡',techDebt:'🔧'};const cls=v>0?'pos':v<0?'neg':'neu';const sign=v>0?'+':'';impactsHtml.push('<span class="impact-chip '+cls+'">'+(names[k]||k)+' '+sign+v+'%</span>')}const riskClass=c.risk==='low'?'low':c.risk==='high'?'high':'med';const riskLabel=c.risk==='low'?'Низкий риск':c.risk==='high'?'Высокий риск':'Средний риск';return '<button class="choice-card" onclick="makeChoice('+i+')"><span class="choice-risk '+riskClass+'">'+riskLabel+'</span><div class="choice-title">'+['A','B','C','D'][i]+'. '+c.title+'</div><div class="choice-desc">'+c.desc+'</div><div class="choice-impacts">'+impactsHtml.join('')+'</div></button>'}).join('');container.innerHTML='<div class="scenario-badge">'+PHASES[Game.phase].icon+' '+Game.getPhaseName()+'</div><div class="scenario-title">'+scenario.title+'</div><div class="scenario-meta">'+tagsHtml+'</div><div class="scenario-text">'+scenario.text+'</div><div class="choices-list">'+choicesHtml+'</div>'}

function makeChoice(choiceIdx){const choice=currentScenario.choices[choiceIdx];applyImpacts(choice.impacts);updateStakeholders(choice.stakeholder);updateSkills(choice.skills);Game.decisions.push(currentScenario.id);Game.history.push({scenario:currentScenario.title,choice:choice.title,week:Game.week});let randomEventText='';if(Math.random()<.25){const event=RandomEvents[Math.floor(Math.random()*RandomEvents.length)];applyImpacts(event.impacts);randomEventText='<br><br><strong>🎲 Случайное событие:</strong> '+event.title+' — '+event.result}addLog('<strong>'+currentScenario.title+'</strong><br>→ '+choice.title+'<br>'+choice.result+randomEventText,choice.risk==='high'?'crisis':'normal');renderMetrics();renderSkills();renderStakeholders();if(Game.budget<=0||Game.morale<=0||Game.quality<=0){showResult(true);return}renderScenario()}

// ==================== PM PROFILE SYSTEM ====================
function generatePMProfile(){const skills=Game.skills;const sortedSkills=Object.entries(skills).sort((a,b)=>b[1]-a[1]);const topSkills=sortedSkills.slice(0,3);const weakSkills=sortedSkills.slice(-3).reverse();const skillNames={negotiation:'Переговоры',tech:'Тех. экспертиза',crisis:'Кризис-менеджмент',comm:'Коммуникация',analytics:'Аналитика',leadership:'Лидерство'};const skillColors={negotiation:'#fbbf24',tech:'#60a5fa',crisis:'#ef4444',comm:'#a78bfa',analytics:'#34d399',leadership:'#f472b6'};let strengthHtml=topSkills.map(([k,v])=>'<div class="pm-skill-item"><span>'+skillNames[k]+'</span><div class="pm-skill-bar"><div class="pm-skill-fill" style="width:'+(v*10)+'%;background:'+skillColors[k]+'"></div></div><strong>'+v+'/10</strong></div>').join('');let weaknessHtml=weakSkills.map(([k,v])=>'<div class="pm-skill-item"><span>'+skillNames[k]+'</span><div class="pm-skill-bar"><div class="pm-skill-fill" style="width:'+(v*10)+'%;background:'+skillColors[k]+'"></div></div><strong>'+v+'/10</strong></div>').join('');let recommendations=[];if(skills.negotiation<4)recommendations.push('📚 Пройдите курс <strong>"Getting to Yes"</strong> (Harvard Negotiation Project) или <strong>"Never Split the Difference"</strong> (Chris Voss)');if(skills.tech<4)recommendations.push('💻 Изучите <strong>System Design Interview</strong> (Alex Xu) и поймите архитектурные trade-offs');if(skills.crisis<4)recommendations.push('🚨 Пройдите сертификацию <strong>ITIL 4 Incident Management</strong> или читайте case studies Knight Capital');if(skills.comm<4)recommendations.push('📢 Практикуйте <strong>Nonviolent Communication</strong> (Rosenberg) и Storytelling для стейкхолдеров');if(skills.analytics<4)recommendations.push('📊 Освойте <strong>SQL + Python (pandas)</strong> и метрики продуктовой аналитики (AARRR)');if(skills.leadership<4)recommendations.push('👑 Прочитайте <strong>"Extreme Ownership"</strong> (Jocko Willink) и <strong>"The Five Dysfunctions of a Team"</strong> (Lencioni)');if(recommendations.length===0)recommendations.push('🎉 Отличный баланс навыков! Рекомендуем: <strong>PMI-ACP или PMP сертификацию</strong> для закрепления');let recHtml=recommendations.map(r=>'<div style="margin-bottom:8px;">'+r+'</div>').join('');return{strengthHtml,weaknessHtml,recHtml,topSkill:skillNames[sortedSkills[0][0]],weakSkill:skillNames[sortedSkills[sortedSkills.length-1][0]]}}

// ==================== REAL CASE STUDIES ====================
const RealCases=[
{title:'💥 Knight Capital: $440M за 45 минут',year:'2012',industry:'Финтех',lesson:'Отсутствие peer review в деплое + отсутствие kill switch = катастрофа. Всегда проверяйте все сервера перед релизом.',tools:'Jenkins, Blue-Green Deploy, Circuit Breaker (Hystrix)'},
{title:'🏥 Healthcare.gov: $1.7B вместо $93M',year:'2013',industry:'Государство',lesson:'Big Bang launch без MVP + политическое давление на сроки = провал. Сначала MVP, потом итерации.',tools:'Jira, Confluence, A/B Testing (Optimizely), Kanban'},
{title:'🚀 Boeing 737 MAX: MCAS система',year:'2018',industry:'Авиация',lesson:'Скрытие информации от стейкхолдеров (пилотов) о критической системе. Прозрачность > защита репутации.',tools:'Risk Management (Monte Carlo), FMEA Analysis, Confluence'},
{title:'📱 Facebook Cambridge Analytica',year:'2018',industry:'Соцсети',lesson:'Техдолг в security привел к репутационной катастрофе. Security audit должен быть proactive, не reactive.',tools:'SonarQube, OWASP ZAP, Snyk, GitLab Security Dashboard'},
{title:'🎮 Cyberpunk 2077 launch',year:'2020',industry:'Геймдев',lesson:'Релиз "как есть" ради сроков и доходов = рейтинг 2.8★, возвраты, репутация CDPR подорвана.',tools:'Jira, TestRail, Jenkins, Feature Flags (LaunchDarkly)'}
];

// ==================== PM TOOLS 2026 ====================
const PMTools=[
{name:'Jira + Confluence',icon:'📋',desc:'Agile/Scrum/Kanban boards, документация, интеграции',tags:['Planning','Tracking','Docs']},
{name:'Linear',icon:'⚡',desc:'Модern issue tracking для быстрых команд. Замена Jira для стартапов',tags:['Agile','Speed','Git']},
{name:'Monday.com',icon:'🎨',desc:'Визуальное управление проектами. Отлично для стейкхолдеров',tags:['Visualization','CRM','Portfolio']},
{name:'Notion',icon:'📝',desc:'Wiki + задачи + базы данных. Единый источник правды',tags:['Docs','Knowledge','Wiki']},
{name:'Miro',icon:'🖼️',desc:'Визуальная коллаборация. Ретроспективы, маппинг, дизайн',tags:['Collaboration','Whiteboard','Workshop']},
{name:'Figma',icon:'🎨',desc:'Дизайн + прототипирование + Dev Mode для handoff',tags:['Design','Prototyping','Handoff']},
{name:'GitLab / GitHub',icon:'🐙',desc:'CI/CD, code review, security scanning, project management',tags:['DevOps','CI/CD','Security']},
{name:'Datadog / New Relic',icon:'📊',desc:'Мониторинг, APM, логи, метрики. Observability',tags:['Monitoring','APM','Observability']},
{name:'Slack + Loom',icon:'💬',desc:'Асинхронная коммуникация. Видео-сообщения вместо митингов',tags:['Communication','Async','Video']},
{name:'Aha! / Productboard',icon:'🎯',desc:'Product management, roadmap, приоритизация фич',tags:['Roadmap','Prioritization','Strategy']},
{name:'Miro + FigJam',icon:'🧠',desc:'Brainstorming, user story mapping, impact mapping',tags:['Workshop','Mapping','Ideation']},
{name:'LaunchDarkly',icon:'🚦',desc:'Feature flags, A/B testing, canary releases',tags:['Feature Flags','Experiment','Deploy']}
];

function showResult(failed=false){document.getElementById('game-screen').classList.add('hidden');const screen=document.getElementById('result-screen');screen.classList.remove('hidden');const avg=(Game.budget+Game.timeline+Game.quality+Game.morale)/4;let emoji,title,message,cls;if(failed||avg<25){emoji='💥';title='ПРОЕКТ ПРОВАЛЕН';message='Критические метрики достигли нуля. Проект закрыт. Команда распущена. Заказчик подал иск.';cls='failure'}else if(avg>=75){emoji='🏆';title='ПРОЕКТ УСПЕШЕН!';message='Выдающееся управление! Продукт в продакшене, команда мотивирована, инвесторы довольны. Ваш кейс — в Harvard Business Review.';cls='success'}else if(avg>=50){emoji='⚡';title='ПРОЕКТ ЗАВЕРШЕН';message='Проект доставлен с трудностями. Есть уроки, есть техдолг, но продукт работает. PM вырос как профессионал.';cls='mixed'}else{emoji='😰';title='ПРОЕКТ НА ГРАНИ';message='Проект формально завершен, но последствия тяжелы. Высокий техдолг, выгоревшая команда, напряженные отношения.';cls='mixed'}

const profile=generatePMProfile();
const skillSummary=Object.entries(Game.skills).map(([k,v])=>{const names={negotiation:'🤝 Переговоры',tech:'💻 Тех. экспертиза',crisis:'🚨 Кризис-менеджмент',comm:'📢 Коммуникация',analytics:'📊 Аналитика',leadership:'👑 Лидерство'};return '<div class="result-stat-card"><div class="stat-icon">'+names[k][0]+'</div><div class="stat-value">'+v+'/10</div><div class="stat-label">'+names[k].substring(2)+'</div></div>'}).join('');

const casesHtml=RealCases.map(c=>'<div class="case-study"><h4>'+c.title+'</h4><div class="case-meta">'+c.year+' • '+c.industry+'</div><p>'+c.lesson+'</p><div class="case-lesson"><strong>Инструменты:</strong> '+c.tools+'</div></div>').join('');

const toolsHtml=PMTools.map(t=>'<div class="tool-card"><div class="tool-icon">'+t.icon+'</div><div class="tool-name">'+t.name+'</div><div class="tool-desc">'+t.desc+'</div>'+t.tags.map(tag=>'<span class="tool-tag">'+tag+'</span>').join('')+'</div>').join('');

screen.innerHTML='<div class="'+cls+'"><div class="result-emoji">'+emoji+'</div><h2>'+title+'</h2><p>'+message+'</p><div class="result-stats-grid"><div class="result-stat-card"><div class="stat-icon">💰</div><div class="stat-value">'+Math.round(Game.budget)+'%</div><div class="stat-label">Бюджет</div></div><div class="result-stat-card"><div class="stat-icon">⏱️</div><div class="stat-value">'+Math.round(Game.timeline)+'%</div><div class="stat-label">Сроки</div></div><div class="result-stat-card"><div class="stat-icon">✨</div><div class="stat-value">'+Math.round(Game.quality)+'%</div><div class="stat-label">Качество</div></div><div class="result-stat-card"><div class="stat-icon">😊</div><div class="stat-value">'+Math.round(Game.morale)+'%</div><div class="stat-label">Мораль</div></div><div class="result-stat-card"><div class="stat-icon">📋</div><div class="stat-value">'+Math.round(Game.scope)+'%</div><div class="stat-label">Scope</div></div><div class="result-stat-card"><div class="stat-icon">⚡</div><div class="stat-value">'+Math.round(Game.risk)+'%</div><div class="stat-label">Риск</div></div></div><h3 style="margin:30px 0 15px;color:var(--text2);">🎯 Навыки PM</h3><div class="result-stats-grid" style="max-width:700px;">'+skillSummary+'</div>'+

'<div class="pm-profile"><h3>👤 Ваш PM-профиль</h3><div class="pm-profile-grid"><div class="pm-strength"><h4>✅ Сильные стороны</h4>'+profile.strengthHtml+'</div><div class="pm-weakness"><h4>⚠️ Зоны роста</h4>'+profile.weaknessHtml+'</div></div><div class="pm-recommendation"><strong>📚 Рекомендации по развитию:</strong><br><br>'+profile.recHtml+'</div></div>'+

'<h3 style="margin:30px 0 15px;color:var(--text2);">📖 Реальные кейсы из индустрии</h3><div style="max-width:900px;margin:0 auto;text-align:left;">'+casesHtml+'</div>'+

'<h3 style="margin:30px 0 15px;color:var(--text2);">🛠️ Инструменты PM 2026</h3><div class="tools-grid" style="max-width:1000px;margin:0 auto;">'+toolsHtml+'</div>'+

'<div style="margin-top:30px;"><button class="btn" onclick="restartGame()">🔄 Новая игра</button><button class="btn btn-outline" onclick="showHistory()">📋 История</button></div></div>'}

function showHistory(){let html=Game.history.map((h,i)=>'<div style="margin:8px 0;padding:12px;background:var(--card);border-radius:10px;text-align:left;"><strong style="color:var(--accent);">Неделя '+h.week+'</strong><br><strong>'+h.scenario+'</strong><br><span style="color:var(--text2);">→ '+h.choice+'</span></div>').join('');const screen=document.getElementById('result-screen');screen.innerHTML='<div style="max-width:800px;margin:0 auto;"><h2 style="margin-bottom:20px;">📋 Полная история решений</h2>'+html+'<button class="btn" onclick="restartGame()" style="margin-top:20px;">🔄 Новая игра</button></div>'}

function restartGame(){Game.budget=100;Game.timeline=100;Game.quality=85;Game.morale=75;Game.scope=100;Game.risk=30;Game.techDebt=15;Game.featuresDone=0;Game.totalFeatures=12;Game.week=1;Game.totalWeeks=24;Game.phase=0;Game.day=1;Game.history=[];Game.decisions=[];Game.skills={negotiation:1,tech:1,crisis:1,comm:1,analytics:1,leadership:1};Game.money=500000;Game.moneySpent=0;Game.moneyTotal=500000;Game.stakeholders=[{id:'client',name:'Алексей В.',role:'Заказчик',mood:70,emoji:'👔'},{id:'team',name:'Команда',role:'Разработчики',mood:75,emoji:'👨‍💻'},{id:'cto',name:'Мария К.',role:'CTO',mood:60,emoji:'👩‍💼'},{id:'investor',name:'Венчурный фонд',role:'Инвестор',mood:50,emoji:'💼'},{id:'qa',name:'Отдел QA',role:'Тестирование',mood:65,emoji:'🐞'}];document.getElementById('result-screen').classList.add('hidden');document.getElementById('game-screen').classList.remove('hidden');document.getElementById('log-content').innerHTML='';renderMetrics();renderSkills();renderStakeholders();renderTimeline();renderScenario();addLog('Проект AI-ассистент для юристов инициирован. Бюджет $500K, срок 24 недели. 5 стейкхолдеров на борту.')}

renderMetrics();renderSkills();renderStakeholders();renderTimeline();renderScenario();addLog('Проект AI-ассистент для юристов инициирован. Бюджет $500K, срок 24 недели. 5 стейкхолдеров на борту.');
</script>
</body>
</html>

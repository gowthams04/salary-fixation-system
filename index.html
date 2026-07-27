<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Salary Fixation Dashboard — HR</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,400;0,9..144,600;0,9..144,700;1,9..144,500&family=Inter:wght@400;500;600;700&family=IBM+Plex+Mono:wght@500;600&display=swap" rel="stylesheet">
<style>
:root {
  --navy: #1b2a4a;
  --navy-deep: #101a30;
  --parchment: #f1f3ef;
  --paper: #fbfaf7;
  --brass: #b9812c;
  --brass-bright: #d69a3c;
  --teal: #0f5257;
  --ink: #1e2530;
  --ink-soft: #4b5563;
  --line: #d8d5cb;
  --success: #2f7a4d;
  --danger: #a4392c;
  --font-display: "Fraunces", serif;
  --font-body: "Inter", system-ui, sans-serif;
  --font-mono: "IBM Plex Mono", monospace;
  --radius: 3px;
}
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; }
body {
  background: var(--parchment);
  color: var(--ink);
  font-family: var(--font-body);
  -webkit-font-smoothing: antialiased;
}
a { color: inherit; }
button { font-family: inherit; }
:focus-visible { outline: 2px solid var(--brass); outline-offset: 2px; }

.container { max-width: 980px; margin: 0 auto; padding: 0 24px 60px; }

.hero {
  background: var(--navy-deep);
  color: #fff;
  position: relative;
  overflow: hidden;
  margin-bottom: 28px;
}
.hero::after {
  content: "";
  position: absolute;
  inset: 0;
  background: repeating-linear-gradient(115deg, rgba(217,154,60,0.06) 0px, rgba(217,154,60,0.06) 1px, transparent 1px, transparent 64px);
  pointer-events: none;
}
.hero-inner { max-width: 980px; margin: 0 auto; padding: 44px 24px 36px; position: relative; }
.hero-eyebrow {
  font-family: var(--font-mono);
  font-size: 0.72rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: var(--brass-bright);
  margin-bottom: 12px;
}
.hero h1 {
  font-family: var(--font-display);
  font-weight: 600;
  font-size: clamp(1.6rem, 3.4vw, 2.3rem);
  line-height: 1.15;
  margin: 0 0 10px;
  max-width: 26ch;
}
.hero p { color: #c9d2e6; max-width: 60ch; line-height: 1.6; margin: 0; font-size: 0.94rem; }

.section-block {
  background: var(--paper);
  border: 1px solid var(--line);
  border-radius: var(--radius);
  margin-bottom: 22px;
  overflow: hidden;
}
.section-head {
  display: flex;
  align-items: baseline;
  gap: 14px;
  padding: 16px 22px;
  border-bottom: 1px solid var(--line);
  background: linear-gradient(180deg, #fff, var(--paper));
}
.section-num { font-family: var(--font-mono); color: var(--brass); font-weight: 600; font-size: 0.85rem; }
.section-head h2 { font-family: var(--font-display); font-size: 1.1rem; font-weight: 600; margin: 0; color: var(--navy); }
.section-body { padding: 20px 22px 24px; }

.filter-grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr auto;
  gap: 14px;
  align-items: end;
}
@media (max-width: 760px) {
  .filter-grid { grid-template-columns: 1fr; }
}
.field { display: flex; flex-direction: column; gap: 6px; }
.field label { font-size: 0.78rem; font-weight: 600; color: var(--ink-soft); }
.field select, .field input {
  border: 1px solid var(--line);
  border-radius: var(--radius);
  padding: 10px 12px;
  font-size: 0.92rem;
  font-family: var(--font-body);
  background: #fff;
  color: var(--ink);
}
.field select:focus, .field input:focus { border-color: var(--brass); }
.field select:disabled { background: #f1f1ee; color: #9aa0a6; }

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border-radius: var(--radius);
  padding: 11px 22px;
  font-weight: 600;
  font-size: 0.92rem;
  cursor: pointer;
  border: 1px solid transparent;
  white-space: nowrap;
}
.btn-primary { background: var(--navy); color: #fff; }
.btn-primary:hover { background: var(--navy-deep); }
.btn-primary:disabled { opacity: 0.5; cursor: not-allowed; }
.btn-outline { background: transparent; color: var(--navy); border-color: var(--navy); }
.btn-outline:hover { background: rgba(27,42,74,0.05); }

.hint { font-size: 0.78rem; color: #8a8f98; margin-top: 4px; }

.banner-error {
  background: #fbe9e6;
  border: 1px solid #eab8ac;
  color: var(--danger);
  padding: 12px 16px;
  border-radius: var(--radius);
  font-size: 0.88rem;
  margin-top: 18px;
}
.banner-warn {
  background: #fbf1de;
  border: 1px solid #edd6a3;
  color: #8a5a1e;
  padding: 12px 16px;
  border-radius: var(--radius);
  font-size: 0.88rem;
  margin-top: 18px;
}

/* Result / pay-band ledger card (signature element) */
.result-wrap { margin-top: 22px; display: none; }
.result-wrap.show { display: block; }
.band-card {
  border: 1px solid var(--navy);
  border-radius: 6px;
  overflow: hidden;
  box-shadow: 0 14px 32px -18px rgba(16,26,48,0.35);
}
.band-top {
  background: var(--navy);
  color: #fff;
  padding: 14px 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.band-top .who { font-family: var(--font-display); font-weight: 600; font-size: 1rem; }
.band-top .tag {
  font-family: var(--font-mono);
  font-size: 0.68rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: var(--brass-bright);
}
.band-body { padding: 20px; background: var(--paper); }
.band-range {
  display: flex;
  align-items: baseline;
  gap: 10px;
  margin-bottom: 6px;
}
.band-range .amt { font-family: var(--font-mono); font-size: 1.7rem; font-weight: 600; color: var(--navy); }
.band-range .sep { color: var(--ink-soft); font-size: 1.1rem; }
.band-sub { font-size: 0.82rem; color: var(--ink-soft); margin-bottom: 18px; }

.slider-row { margin-top: 6px; }
.slider-row label { font-size: 0.78rem; font-weight: 600; color: var(--ink-soft); display: block; margin-bottom: 8px; }
.slider-line { display: flex; align-items: center; gap: 14px; }
.slider-line input[type="range"] { flex: 1; accent-color: var(--brass); }
.fixed-amt {
  font-family: var(--font-mono);
  font-weight: 600;
  font-size: 1.1rem;
  color: var(--teal);
  min-width: 100px;
  text-align: right;
}
.band-meta {
  display: flex;
  gap: 24px;
  margin-top: 18px;
  padding-top: 16px;
  border-top: 1px dotted var(--line);
  font-size: 0.85rem;
  flex-wrap: wrap;
}
.band-meta div dt { font-size: 0.7rem; text-transform: uppercase; letter-spacing: 0.06em; color: var(--ink-soft); margin-bottom: 2px; }
.band-meta div dd { margin: 0; font-weight: 600; }
.band-foot {
  padding: 12px 20px;
  font-size: 0.78rem;
  color: var(--ink-soft);
  border-top: 1px solid var(--line);
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 8px;
}

/* Reference table */
.table-toolbar { display: flex; gap: 10px; margin-bottom: 14px; flex-wrap: wrap; }
.table-toolbar input, .table-toolbar select {
  border: 1px solid var(--line);
  border-radius: var(--radius);
  padding: 8px 12px;
  font-size: 0.85rem;
  font-family: var(--font-body);
  background: #fff;
}
.table-toolbar input { flex: 1; min-width: 180px; }

table.ref-table { width: 100%; border-collapse: collapse; font-size: 0.85rem; }
table.ref-table th, table.ref-table td { text-align: left; padding: 9px 10px; border-bottom: 1px solid var(--line); }
table.ref-table th {
  font-size: 0.7rem;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  color: var(--ink-soft);
  position: sticky;
  top: 0;
  background: var(--paper);
}
table.ref-table tr:hover td { background: #f7f5ef; }
.table-scroll { max-height: 420px; overflow-y: auto; border: 1px solid var(--line); border-radius: var(--radius); }
.mono { font-family: var(--font-mono); font-size: 0.82rem; }
.count-badge { font-size: 0.78rem; color: var(--ink-soft); margin-bottom: 10px; }

.footer {
  text-align: center;
  font-size: 0.78rem;
  color: var(--ink-soft);
  padding: 30px 20px 10px;
}
</style>
</head>
<body>

<section class="hero">
  <div class="hero-inner">
    <div class="hero-eyebrow">HR · Pay Scale Register</div>
    <h1>Salary Fixation Dashboard</h1>
    </div>
</section>
<div class="container">
  <div class="section-block">
    <div class="section-head">
      <span class="section-num">§A</span>
      <h2>Load Pay Scale Register</h2>
    </div>
    <div class="section-body">
      <div class="field">
        <label for="excelFile">Upload Excel file (.xlsx, .xls)</label>
        <input type="file" id="excelFile" accept=".xlsx, .xls, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet">
      </div>
      <div class="hint">
        The Excel file should contain columns: <code>Department</code>, <code>Designation</code>, <code>Experience</code>, <code>Salary</code>.
      </div>
      <div id="loadErrorBox"></div>
    </div>
  </div>
  <div id="mainContent" style="display: none;">
  <div class="section-block">
    <div class="section-head">
      <span class="section-num">01</span>
      <h2>Fix Salary for New Employee</h2>
    </div>
    <div class="section-body">
      <div class="filter-grid">
        <div class="field">
          <label for="dept">Department</label>
          <select id="dept">
            <option value="">Select department</option>
          </select>
        </div>
        <div class="field">
          <label for="desg">Designation</label>
          <select id="desg" disabled>
            <option value="">Select department first</option>
          </select>
        </div>
        <div class="field">
          <label for="expBand">Experience Band</label>
          <select id="expBand" disabled>
            <option value="">Select designation first</option>
          </select>
        </div>
        <div class="field">
          <label for="newExp">New Employee Experience (Optional)</label>
          <input type="text" id="newExp" placeholder="e.g. 1y, 4m or 1.3">
        </div>
        <button class="btn btn-primary" id="findBtn" style="padding-top: 10px; padding-bottom: 10px;">
          Find
        </button>
      </div>
      <div id="errorBox"></div>
      <div class="result-wrap" id="resultWrap">
        <div class="band-card">
          <div class="band-top">
            <span class="who" id="resWho">—</span>
            <span class="tag">Applicable pay band</span>
          </div>
          <div class="band-body">
            <div class="band-range">
              <span class="amt" id="resMin">₹0</span>
              <span class="sep">–</span>
              <span class="amt" id="resMax">₹0</span>
            </div>
            <div class="band-sub" id="resSub">Monthly salary range for this band</div>

            <div id="suggestion" style="display: none; margin-bottom: 18px;">
              <div class="slider-row">
                <label>Suggested Salary (based on experience)</label>
                <div class="fixed-amt" id="suggestedAmt" style="color: var(--teal); font-size: 1.2rem;">₹0</div>
              </div>
            </div>
            <div class="slider-row">
              <label for="fixSlider">Fix exact salary within this band</label>
              <div class="slider-line">
                <input type="range" id="fixSlider" min="0" max="1" step="1">
                <span class="fixed-amt" id="fixedAmt">₹0</span>
              </div>
            </div>

            <div class="band-meta">
              <div>
                <dt>Department</dt>
                <dd id="metaDept">—</dd>
              </div>
              <div>
                <dt>Designation</dt>
                <dd id="metaDesg">—</dd>
              </div>
              <div>
                <dt>Experience band</dt>
                <dd id="metaExp">—</dd>
              </div>
            </div>
          </div>
          <div class="band-foot">
            <span id="footNote">Fixed salary is within the approved band for this role.</span>
            <button class="btn btn-outline" id="copyBtn">Copy summary</button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="section-block">
    <div class="section-head">
      <span class="section-num">02</span>
      <h2>Pay Scale Register (Reference)</h2>
    </div>
    <div class="section-body">
      <div class="table-toolbar">
        <input type="text" id="tableSearch" placeholder="Search department, designation...">
        <select id="tableDeptFilter">
          <option value="">All departments</option>
        </select>
      </div>
      <div class="count-badge" id="countBadge">152 bands</div>
      <div class="table-scroll">
        <table class="ref-table">
          <thead>
            <tr>
              <th>Department</th>
              <th>Designation</th>
              <th>Experience</th>
              <th>Salary Range</th>
            </tr>
          </thead>
          <tbody id="tableBody"></tbody>
        </table>
      </div>
    </div>
  </div>

  </div>

</div>

<div class="footer">HR Pay Scale Reference</div>

<script src="https://cdn.sheetjs.com/xlsx-latest/package/dist/xlsx.full.min.js"></script>
<script>
let DATA = [];
const fmt = (n) => '₹' + Number(n).toLocaleString('en-IN');

// ---- DOM elements ----
const mainContent = document.getElementById('mainContent');
const deptSelect = document.getElementById('dept');
const desgSelect = document.getElementById('desg');
const expBandSelect = document.getElementById('expBand');
const errorBox = document.getElementById('errorBox');
const newExpInput = document.getElementById('newExp');
const findBtn = document.getElementById('findBtn');
const resultWrap = document.getElementById('resultWrap');
const tableBody = document.getElementById('tableBody');
const tableSearch = document.getElementById('tableSearch');
const tableDeptFilter = document.getElementById('tableDeptFilter');
const countBadge = document.getElementById('countBadge');

function parseExperienceToYears(expStr) {
  if (typeof expStr === 'number') return expStr;
  if (typeof expStr !== 'string' || !expStr.trim()) return NaN;

  let totalYears = 0;
  const str = expStr.toLowerCase().replace(/,/g, ' ');

  const yearMatches = str.match(/(\d*\.?\d+)\s*y/);
  const monthMatches = str.match(/(\d*\.?\d+)\s*m/);

  if (yearMatches) totalYears += parseFloat(yearMatches[1]);
  if (monthMatches) totalYears += parseFloat(monthMatches[1]) / 12;

  // If no units found, assume it's a number representing years
  if (!yearMatches && !monthMatches && !isNaN(parseFloat(str))) return parseFloat(str);

  return totalYears > 0 ? totalYears : NaN;
}

function initializeDashboard(payScaleData) {
  DATA = payScaleData;
  mainContent.style.display = 'block';

  // ---- Populate department dropdown ----
  const departments = [...new Set(DATA.map(r => r.department))].sort();
  
  // Clear previous options
  deptSelect.innerHTML = '<option value="">Select department</option>';
  tableDeptFilter.innerHTML = '<option value="">All departments</option>';

  departments.forEach(d => {
    const opt = document.createElement('option');
    opt.value = d; opt.textContent = d;
    deptSelect.appendChild(opt.cloneNode(true));
    tableDeptFilter.appendChild(opt.cloneNode(true));
  });

  deptSelect.addEventListener('change', () => {
    const dept = deptSelect.value;
    desgSelect.innerHTML = '';
    expBandSelect.innerHTML = '<option value="">Select designation first</option>';
    expBandSelect.disabled = true;
    if (!dept) {
      desgSelect.disabled = true;
      const opt = document.createElement('option');
      opt.value = ''; opt.textContent = 'Select department first';
      desgSelect.appendChild(opt);
      return;
    }
    desgSelect.disabled = false;
    const opt0 = document.createElement('option');
    opt0.value = ''; opt0.textContent = 'Select designation';
    desgSelect.appendChild(opt0);
    const desgs = [...new Set(DATA.filter(r => r.department === dept).map(r => r.designation))];
    desgs.forEach(d => {
      const opt = document.createElement('option');
      opt.value = d; opt.textContent = d;
      desgSelect.appendChild(opt);
    });
    resultWrap.classList.remove('show');
    errorBox.innerHTML = '';
  });

  desgSelect.addEventListener('change', () => {
    const dept = deptSelect.value;
    const desg = desgSelect.value;
    expBandSelect.innerHTML = '';
    resultWrap.classList.remove('show');
    errorBox.innerHTML = '';

    if (!desg) {
      expBandSelect.disabled = true;
      expBandSelect.innerHTML = '<option value="">Select designation first</option>';
      return;
    }

    expBandSelect.disabled = false;
    expBandSelect.innerHTML = '<option value="">Select experience band</option>';
    const bands = DATA.filter(r => r.department === dept && r.designation === desg);
    bands.forEach((band, i) => {
      const opt = document.createElement('option');
      // Use a unique key to find the band later, as index isn't safe across filters
      const bandKey = `${dept}|${desg}|${band.expMin}|${band.expMax}`;
      opt.value = bandKey;
      opt.textContent = `${Math.floor(band.expMin)} – ${Math.floor(band.expMax)} yrs`;
      expBandSelect.appendChild(opt);
    });
  });

  expBandSelect.addEventListener('change', (e) => {
    errorBox.innerHTML = '';
    if (!e.target.value) {
      resultWrap.classList.remove('show');
      return;
    }

    const band = DATA.find(r => `${r.department}|${r.designation}|${r.expMin}|${r.expMax}` === e.target.value);
    const dept = deptSelect.value;
    const desg = desgSelect.value;
    const suggestionEl = document.getElementById('suggestion');

    if (band) {
      document.getElementById('resWho').textContent = `${desg} · ${dept}`;
      document.getElementById('resMin').textContent = fmt(band.salMin);
      document.getElementById('resMax').textContent = fmt(band.salMax);
      document.getElementById('resSub').textContent = band.salMin === band.salMax
        ? 'Fixed monthly salary for this band'
        : 'Monthly salary range for this band';
      document.getElementById('metaDept').textContent = dept;
      document.getElementById('metaDesg').textContent = desg;
      
      const candidateExp = parseFloat(newExpInput.dataset.candidateExpYears);
      const expText = `${Math.floor(band.expMin)}–${Math.floor(band.expMax)} yrs`;
      const candidateExpText = !isNaN(candidateExp) ? ` (Candidate: ${candidateExp.toFixed(1)} yrs)` : '';
      document.getElementById('metaExp').textContent = expText + candidateExpText;

      let initialSliderValue;
      // Calculate suggested salary if candidate experience is available and within the band
      if (!isNaN(candidateExp) && band.expMax > band.expMin && candidateExp >= band.expMin && candidateExp <= band.expMax) {
        const expRatio = (candidateExp - band.expMin) / (band.expMax - band.expMin);
        initialSliderValue = band.salMin + expRatio * (band.salMax - band.salMin);
        
        document.getElementById('suggestedAmt').textContent = fmt(Math.round(initialSliderValue));
        suggestionEl.style.display = 'block';

      } else {
        // Default to the midpoint if no candidate experience is provided or it's outside the band
        initialSliderValue = band.salMin === band.salMax ? band.salMin : Math.round((band.salMin + band.salMax) / 2);
        suggestionEl.style.display = 'none';
      }
      // Clear candidate experience after use so it doesn't apply to manual selections
      newExpInput.dataset.candidateExpYears = '';

      const slider = document.getElementById('fixSlider');
      slider.min = band.salMin;
      slider.max = band.salMax;
      slider.step = band.salMin === band.salMax ? 1 : Math.max(1, Math.round((band.salMax - band.salMin) / 100));
      slider.value = initialSliderValue;
      slider.disabled = band.salMin === band.salMax;
      document.getElementById('fixedAmt').textContent = fmt(Math.round(slider.value));

      

      document.getElementById('footNote').textContent = band.salMin === band.salMax
        ? 'This role has a fixed salary — no negotiation range applies.'
        : 'Drag the slider to fix an exact offer within the approved band.';

      resultWrap.classList.add('show');
      resultWrap.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
    }


  });

  renderTable();
}

findBtn.addEventListener('click', () => {
  errorBox.innerHTML = '';
  const dept = deptSelect.value;
  const desg = desgSelect.value;
  const expStr = newExpInput.value;

  if (!dept || !desg) {
    errorBox.innerHTML = '<div class="banner-error">Please select a department and designation first.</div>';
    return;
  }
  if (!expStr.trim()) {
    errorBox.innerHTML = '<div class="banner-error">Please enter the new employee\'s experience to find a band.</div>';
    return;
  }

  const candidateExp = parseExperienceToYears(expStr);
  if (isNaN(candidateExp)) {
    errorBox.innerHTML = '<div class="banner-error">Could not understand the experience format. Use formats like "5y 6m" or "5.5".</div>';
    return;
  }
  
  newExpInput.dataset.candidateExpYears = candidateExp;

  const matchingBand = DATA.find(r => r.department === dept && r.designation === desg && candidateExp >= r.expMin && candidateExp < r.expMax + 1);

  if (matchingBand) {
    const bandKey = `${matchingBand.department}|${matchingBand.designation}|${matchingBand.expMin}|${matchingBand.expMax}`;
    expBandSelect.value = bandKey;
    expBandSelect.dispatchEvent(new Event('change')); // Trigger the change event to show the card
  } else {
    errorBox.innerHTML = '<div class="banner-warn">No matching pay band found for this experience level. Check the reference table or consult HR policy.</div>';
  }
});

document.getElementById('fixSlider').addEventListener('input', (e) => {
  document.getElementById('fixedAmt').textContent = fmt(e.target.value);
});

document.getElementById('copyBtn').addEventListener('click', () => {
  const summary = [
    'Department: ' + document.getElementById('metaDept').textContent,
    'Designation: ' + document.getElementById('metaDesg').textContent,
    'Experience band: ' + document.getElementById('metaExp').textContent,
    'Fixed salary: ' + document.getElementById('fixedAmt').textContent + ' / month'
  ].join('\n');
  navigator.clipboard?.writeText(summary);
  const btn = document.getElementById('copyBtn');
  const original = btn.textContent;
  btn.textContent = 'Copied!';
  setTimeout(() => { btn.textContent = original; }, 1500);
});

function renderTable() {
  const q = tableSearch.value.trim().toLowerCase();
  const df = tableDeptFilter.value;
  const rows = DATA.filter(r => {
    if (df && r.department !== df) return false;
    if (!q) return true;
    return (r.department + ' ' + r.designation).toLowerCase().includes(q);
  });
  countBadge.textContent = rows.length + ' band' + (rows.length === 1 ? '' : 's');
  tableBody.innerHTML = rows.map(r => (
    '<tr><td>' + r.department + '</td><td>' + r.designation + '</td>' +
    '<td class="mono">' + Math.floor(r.expMin) + '–' + Math.floor(r.expMax) + ' yrs</td>' +
    '<td class="mono">' + fmt(r.salMin) + (r.salMin === r.salMax ? '' : ' – ' + fmt(r.salMax)) + '</td></tr>'
  )).join('');
}

tableSearch.addEventListener('input', renderTable);
tableDeptFilter.addEventListener('change', renderTable);

// ---- Excel file upload ----
const excelFileInput = document.getElementById('excelFile');
const loadErrorBox = document.getElementById('loadErrorBox');

excelFileInput.addEventListener('change', (e) => {
  const file = e.target.files[0];
  if (!file) return;

  loadErrorBox.innerHTML = '';
  const reader = new FileReader();
  reader.onload = (event) => {
    try {
      const data = new Uint8Array(event.target.result);
      const workbook = XLSX.read(data, { type: 'array' });
      const sheetName = workbook.SheetNames[0];
      const worksheet = workbook.Sheets[sheetName];
      const json = XLSX.utils.sheet_to_json(worksheet);
      
      if (json.length === 0) {
        throw new Error("Excel file is empty or has no data in the first sheet.");
      }

      // Verify that the essential columns are present in the first row.
      if (!json[0] || json[0].Department === undefined || json[0].Designation === undefined || json[0].Experience === undefined || json[0].Salary === undefined) {
        throw new Error("Could not find required columns. Please ensure the Excel file has headers: 'Department', 'Designation', 'Experience', and 'Salary'.");
      }

      // Group by Department + Designation and calculate min/max for experience and salary.
      const groupedByRole = {};
      for (const row of json) {
        const key = `${row.Department}|${row.Designation}`;
        if (!groupedByRole[key]) groupedByRole[key] = [];
        groupedByRole[key].push(row);
      }

      // For each role, identify distinct experience bands based on gaps.
      const finalBands = [];
      for (const key in groupedByRole) {
        const records = groupedByRole[key];
        if (records.length === 0) continue;

        const points = records.map(r => ({ exp: parseExperienceToYears(r.Experience), sal: parseFloat(r.Salary) }))
          .filter(p => !isNaN(p.exp) && !isNaN(p.sal))
          .sort((a, b) => a.exp - b.exp);

        if (points.length === 0) continue;

        let currentBand = {
          department: records[0].Department,
          designation: records[0].Designation,
          expMin: points[0].exp,
          expMax: points[0].exp,
          salMin: points[0].sal,
          salMax: points[0].sal,
        };

        for (let i = 1; i < points.length; i++) {
          // If the gap to the next experience point is > 2 years, treat it as a new band.
          if (points[i].exp - currentBand.expMax > 2) {
            finalBands.push(currentBand);
            currentBand = { ...currentBand, expMin: points[i].exp, expMax: points[i].exp, salMin: points[i].sal, salMax: points[i].sal };
          } else {
            currentBand.expMax = Math.max(currentBand.expMax, points[i].exp);
            currentBand.salMin = Math.min(currentBand.salMin, points[i].sal);
            currentBand.salMax = Math.max(currentBand.salMax, points[i].sal);
          }
        }
        finalBands.push(currentBand);
      }

      initializeDashboard(finalBands);

    } catch (err) {
      loadErrorBox.innerHTML = `<div class="banner-error">Error processing file: ${err.message}</div>`;
    }
  };
  reader.readAsArrayBuffer(file);
});
</script>

</body>
</html>

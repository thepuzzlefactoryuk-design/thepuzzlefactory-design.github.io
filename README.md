<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>The Puzzle Factory Ltd</title>
<style>
  :root { --gap: 8px; }
  body {
    font-family: system-ui, sans-serif;
    margin: 0;
    background: #000;
    color: #fff;
    overflow-x: hidden;
  }
  h1 { color: #fff; margin:0; }
  .grid-wrapper {
    position: relative;
    width: 100%;
    z-index: 1;
  }
  .logo-layer {
    position: relative;
    z-index: 10;
    display: flex;
    justify-content: center;
    margin: 10rem auto 2rem auto; /* push further down */
  }
  .grid {
    display:grid;grid-template-columns:repeat(4,1fr); /* 4 across */
    gap: var(--gap);
    width: 95vw;
    margin: 2rem auto;
  }
  .cell {
    overflow: hidden;
    border-radius: 2px;
  }
  .tile {
    width: 100%;
    aspect-ratio: 1/1;
    display: block;
    background: transparent;
    transition: transform 0.15s linear;
    transform-origin: 50% 50%;
  }
  svg {
    display: block;
    shape-rendering: geometricPrecision;
  }
  .controls {
    margin: 1rem;
    text-align: center;
    z-index: 11;
    position: relative;
    visibility: hidden;
  }
  .controls > * { margin: 0 .25rem; }
  .filler {
    background: rgba(128,128,128,0.3);
    color: #fff;
    padding: 2rem;
    margin: 2rem auto;
    width: 80%;
    line-height: 1.5;
  }
</style>
</head>
<body>
<div class="grid-wrapper">
  <div class="grid" id="grid"></div>
</div>

<div class="logo-layer">
  <!-- Logo with fractal noise filter -->
  <?xml version="1.0" encoding="UTF-8" standalone="no"?>
<!-- Created with Inkscape (http://www.inkscape.org/) -->

<svg
   version="1.1"
   id="svg1"
   width="419.31702"
   height="382.6467"
   viewBox="0 0 419.31702 382.64669"
   sodipodi:docname="puzfacblackquarelogo.svg"
   inkscape:version="1.3.2 (091e20e, 2023-11-25, custom)"
   xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape"
   xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
   xmlns="http://www.w3.org/2000/svg"
   xmlns:svg="http://www.w3.org/2000/svg">
  <defs
     id="defs1">
    <rect
       x="-366.70309"
       y="-55.802647"
       width="499.83228"
       height="530.12512"
       id="rect4" />
  </defs>
  <sodipodi:namedview
     id="namedview1"
     pagecolor="#ffffff"
     bordercolor="#000000"
     borderopacity="0.25"
     inkscape:showpageshadow="2"
     inkscape:pageopacity="0.0"
     inkscape:pagecheckerboard="0"
     inkscape:deskcolor="#d1d1d1"
     inkscape:zoom="1.2544208"
     inkscape:cx="191.32336"
     inkscape:cy="180.96001"
     inkscape:window-width="1920"
     inkscape:window-height="1058"
     inkscape:window-x="4914"
     inkscape:window-y="894"
     inkscape:window-maximized="1"
     inkscape:current-layer="layer4" />
  <g
     inkscape:groupmode="layer"
     id="layer4"
     inkscape:label="Image 3"
     style="display:inline;fill:#000000"
     transform="translate(10.363348,6.3774453)">
    <path
       id="rect7"
       style="fill:#ffffff"
       d="M -10.363348,-6.3774452 H 408.95367 V 376.26925 H -10.363348 Z" />
  </g>
  <g
     inkscape:groupmode="layer"
     id="layer3"
     inkscape:label="Image 2"
     style="display:none"
     transform="translate(10.363348,6.3774453)">
    <path
       style="fill:#000000;stroke-width:0.797181"
       d="M 154.25446,90.081413 V 72.543439 h 2.22405 c 7.57598,0 17.96713,5.022359 23.84119,11.52317 5.39665,5.972475 7.73411,11.218015 9.34081,20.961941 l 0.42722,2.59084 h -17.91664 -17.91663 z"
       id="path7" />
  </g>
  <g
     inkscape:groupmode="layer"
     inkscape:label="Image"
     id="g1"
     style="display:inline"
     transform="translate(10.363348,6.3774453)">
    <text
       xml:space="preserve"
       id="text4"
       style="font-style:normal;font-variant:normal;font-weight:normal;font-stretch:normal;font-size:72px;line-height:1;font-family:Truchet-curve;-inkscape-font-specification:Truchet-curve;word-spacing:-0.09px;white-space:pre;shape-inside:url(#rect4);display:inline;fill:#000000"
       transform="translate(412.93958,55.802646)"><tspan
         x="-366.70312"
         y="16.197266"
         id="tspan10"><tspan
           dx="0 0 0 0 0.090000004"
           id="tspan9">ThEp
</tspan></tspan><tspan
         x="-366.70312"
         y="88.197266"
         id="tspan12"><tspan
           dx="0 0 0 0 0.090000004"
           id="tspan11">uZZl
</tspan></tspan><tspan
         x="-366.70312"
         y="160.19727"
         id="tspan14"><tspan
           dx="0 0 0 0 0.090000004"
           id="tspan13">eFac
</tspan></tspan><tspan
         x="-366.70312"
         y="232.19727"
         id="tspan15">Tory</tspan></text>
    <text
       xml:space="preserve"
       style="font-style:normal;font-variant:normal;font-weight:normal;font-stretch:normal;font-size:66.9031px;line-height:1;font-family:'Alternate Gothic No2 D';-inkscape-font-specification:'Alternate Gothic No2 D';word-spacing:-0.0836289px;display:inline;fill:#000000;stroke-width:0.92921"
       x="-0.78383601"
       y="336.29968"
       id="text6"
       transform="scale(0.92920993,1.0761831)"><tspan
         sodipodi:role="line"
         id="tspan6"
         x="-0.78383601"
         y="336.29968"
         style="fill:#000000;stroke-width:0.92921">THE PUZZLE FACTORY</tspan></text>
  </g>
</svg>

</div>

<div class="filler">
  <p>
    The Puzzle Factory is a Generative Art Studio.
  </p>
  <p>We are currently under construction, in two worlds.</p>
  <p>
    You can see our shop window displays at Forsyth Est 1857, 126 Deansgate, Manchester M3 2GR  </p>
    </div>

<div class="controls">
  <label>
    Choose date-time (UTC):
    <input type="datetime-local" id="dtInput">
  </label>
  <button id="updateBtn">Update (freeze at chosen)</button>
  <button id="nowBtn">Now (resume live)</button>
  <button id="pauseBtn">Pause</button>
  <br/><br/>
  <label>
    Time Unit (metronome scale):
    <input type="range" id="unitSlider" min="1" max="8" step="1" value="1">
    <span id="unitLabel">1/4s</span>
  </label>
</div>

<script>
const eclipseTime = new Date(Date.UTC(2048, 5, 11, 12, 58, 0));
const gridEl = document.getElementById('grid');
const dtInput = document.getElementById('dtInput');
const updateBtn = document.getElementById('updateBtn');
const nowBtn = document.getElementById('nowBtn');
const pauseBtn = document.getElementById('pauseBtn');
const unitSlider = document.getElementById('unitSlider');
const unitLabel = document.getElementById('unitLabel');

const baseStripeHeight = 2;
const cols = 5;

let live = true;
let fixedDate = null;
let intervalId;
let baseUnit = 250; // start at 1/4s

// Map slider values to metronome-like scales
const unitMap = {
  1: 250,   // 1/4s
  2: 500,   // 1/2s
  3: 1000,  // 1s
  4: 2000,  // 2s
  5: 3000,  // 3s
  6: 4000,  // 4s
  7: 6000,  // 6s
  8: 10000, // 10s
};
const unitLabels = {
  1: "1/4s", 2: "1/2s", 3: "1s", 4: "2s",
  5: "3s", 6: "4s", 7: "6s", 8: "10s"
};

function unitsUntilEclipse(now) {
  let ms = eclipseTime - now;
  let units = Math.floor(ms / baseUnit);
  return units > 0 ? units : 0;
}

function render(now) {
  const units = unitsUntilEclipse(now);

  const digits = [];
  let temp = units;
  while (temp > 0) {
    digits.push(temp % 4);
    temp = Math.floor(temp / 4);
  }
  if (digits.length === 0) digits.push(0);

  const rows = Math.ceil(digits.length / cols) || 1;
  while (digits.length < rows * cols) digits.push(0);

  gridEl.style.gridTemplateColumns = `repeat(${cols}, 1fr)`;
  gridEl.innerHTML = '';

  let defsHTML = '';
  for (let r = 0; r < rows; r++) {
    const ratio = 0.2 + (r / (rows - 1 || 1)) * (0.8 - 0.2);
    const orangeFrac = ratio;
    const magentaFrac = 1 - ratio;
    const oHeight = orangeFrac * baseStripeHeight;
    const mHeight = magentaFrac * baseStripeHeight;

    for (let c = 0; c < cols; c++) {
      const blueFrac = 0.2 + (c / (cols - 1 || 1)) * (0.8 - 0.2);
      const blackFrac = 1 - blueFrac;
      const bHeight = blueFrac * baseStripeHeight;
      const kHeight = blackFrac * baseStripeHeight;

      defsHTML += `
        <pattern id="stripeKB_${r}_${c}" patternUnits="userSpaceOnUse" width="100" height="${kHeight + bHeight}">
          <rect x="0" y="0" width="100" height="${kHeight}" fill="#000" />
          <rect x="0" y="${kHeight}" width="100" height="${bHeight}" fill="#004" />
        </pattern>
        <pattern id="stripeRow_${r}_${c}" patternUnits="userSpaceOnUse" width="100" height="${oHeight + mHeight}">
          <rect x="0" y="0" width="100" height="${mHeight}" fill="#ff00a8" />
          <rect x="0" y="${mHeight}" width="100" height="${oHeight}" fill="#f55905" />
        </pattern>
      `;
    }
  }

  const defsContainer = document.createElementNS('http://www.w3.org/2000/svg','svg');
  defsContainer.setAttribute('width','0');
  defsContainer.setAttribute('height','0');
  defsContainer.innerHTML = `<defs>${defsHTML}</defs>`;
  document.body.appendChild(defsContainer);

  digits.forEach((d, idx) => {
    const r = Math.floor(idx / cols);
    const c = idx % cols;
    const shapes = `
      <polygon points="0,0 0,100 100,100" fill="url(#stripeKB_${r}_${c})" />
      <path d="M0,0 L100,0 L100,100 A100,100 0 0 1 0,0 Z" fill="url(#stripeRow_${r}_${c})" />
    `;
    const cell = document.createElement('div');
    cell.className = 'cell';
    cell.innerHTML = `
      <svg class="tile" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        ${shapes}
      </svg>
    `;
    const svgEl = cell.querySelector('svg');
    svgEl.style.transform = `rotate(${-d * 90}deg)`; // clockwise
    gridEl.appendChild(cell);
  });

  const svgs = document.querySelectorAll('body > svg[width="0"][height="0"]');
  svgs.forEach((s, i) => { if (i < svgs.length - 1) s.remove(); });
}

function tick() {
  const now = live ? new Date() : (fixedDate || new Date());
  render(now);
}

function restartInterval() {
  if (intervalId) clearInterval(intervalId);
  intervalId = setInterval(tick, baseUnit);
}

updateBtn.addEventListener('click', () => {
  const val = dtInput.value;
  if (!val) return;
  live = false;
  fixedDate = new Date(val + 'Z');
  pauseBtn.textContent = 'Resume';
  render(fixedDate);
});
nowBtn.addEventListener('click', () => {
  dtInput.value = '';
  live = true;
  fixedDate = null;
  pauseBtn.textContent = 'Pause';
  tick();
});
pauseBtn.addEventListener('click', () => {
  if (live) {
    live = false;
    fixedDate = new Date();
    pauseBtn.textContent = 'Resume';
    render(fixedDate);
  } else {
    live = true;
    fixedDate = null;
    pauseBtn.textContent = 'Pause';
    tick();
  }
});

unitSlider.addEventListener('input', () => {
  const val = parseInt(unitSlider.value, 10);
  baseUnit = unitMap[val];
  unitLabel.textContent = unitLabels[val];
  restartInterval();
});

// initial render + interval
tick();
restartInterval();

// simple parallax: move grid slower than scroll
window.addEventListener('scroll', () => {
  const offset = window.scrollY * 0.3; // slower factor
  gridEl.style.transform = `translateY(${offset}px)`;
});
</script>
</body>
</html>

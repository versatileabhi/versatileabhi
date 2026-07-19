<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1180 610' width='1180' height='610' role='img' aria-label='Abhiraj GitHub profile hero banner'>
  <defs>
    <linearGradient id='bgGradient' x1='0%' y1='0%' x2='100%' y2='100%'>
      <stop offset='0%' stop-color='#030712'/>
      <stop offset='55%' stop-color='#071326'/>
      <stop offset='100%' stop-color='#020617'/>
    </linearGradient>
    <linearGradient id='panelGradient' x1='0%' y1='0%' x2='100%' y2='100%'>
      <stop offset='0%' stop-color='rgba(15,23,42,0.92)'/>
      <stop offset='100%' stop-color='rgba(15,23,42,0.76)'/>
    </linearGradient>
    <linearGradient id='accentGradient' x1='0%' y1='0%' x2='100%' y2='100%'>
      <stop offset='0%' stop-color='#7C3AED'>
        <animate attributeName='stop-color' values='#7C3AED;#22D3EE;#10B981;#7C3AED' dur='8s' repeatCount='indefinite'/>
      </stop>
      <stop offset='50%' stop-color='#22D3EE'>
        <animate attributeName='stop-color' values='#22D3EE;#10B981;#7C3AED;#22D3EE' dur='8s' repeatCount='indefinite'/>
      </stop>
      <stop offset='100%' stop-color='#10B981'>
        <animate attributeName='stop-color' values='#10B981;#7C3AED;#22D3EE;#10B981' dur='8s' repeatCount='indefinite'/>
      </stop>
    </linearGradient>
    <linearGradient id='asciiGradient' x1='0%' y1='0%' x2='100%' y2='100%'>
      <stop offset='0%' stop-color='#8B5CF6'>
        <animate attributeName='stop-color' values='#8B5CF6;#22D3EE;#5EEAD4;#8B5CF6' dur='7s' repeatCount='indefinite'/>
      </stop>
      <stop offset='100%' stop-color='#5EEAD4'>
        <animate attributeName='stop-color' values='#5EEAD4;#8B5CF6;#22D3EE;#5EEAD4' dur='7s' repeatCount='indefinite'/>
      </stop>
    </linearGradient>
    <radialGradient id='glowA' cx='50%' cy='50%' r='50%'>
      <stop offset='0%' stop-color='rgba(34,211,238,0.26)'/>
      <stop offset='100%' stop-color='rgba(34,211,238,0)'/>
    </radialGradient>
    <radialGradient id='glowB' cx='50%' cy='50%' r='50%'>
      <stop offset='0%' stop-color='rgba(124,58,237,0.25)'/>
      <stop offset='100%' stop-color='rgba(124,58,237,0)'/>
    </radialGradient>
    <radialGradient id='glowC' cx='50%' cy='50%' r='50%'>
      <stop offset='0%' stop-color='rgba(16,185,129,0.18)'/>
      <stop offset='100%' stop-color='rgba(16,185,129,0)'/>
    </radialGradient>
    <filter id='softBlur' x='-40%' y='-40%' width='180%' height='180%'>
      <feGaussianBlur stdDeviation='20'/>
    </filter>
    <filter id='panelBlur' x='-20%' y='-20%' width='140%' height='140%'>
      <feGaussianBlur stdDeviation='10'/>
    </filter>
    <filter id='noise' x='-10%' y='-10%' width='120%' height='120%'>
      <feTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2' seed='7'/>
      <feColorMatrix type='saturate' values='0'/>
      <feComponentTransfer>
        <feFuncA type='table' tableValues='0 0.08'/>
      </feComponentTransfer>
    </filter>
    <filter id='glowStroke' x='-50%' y='-50%' width='200%' height='200%'>
      <feGaussianBlur stdDeviation='5' result='blur'/>
      <feMerge>
        <feMergeNode in='blur'/>
        <feMergeNode in='SourceGraphic'/>
      </feMerge>
    </filter>
    <clipPath id='heroClip'>
      <rect x='8' y='8' width='1164' height='594' rx='34' ry='34'/>
    </clipPath>
    <mask id='shineMask'>
      <rect x='0' y='0' width='1180' height='610' fill='black'/>
      <rect x='0' y='0' width='1180' height='260' fill='white'>
        <animate attributeName='y' values='-120;0;-120' dur='9s' repeatCount='indefinite'/>
      </rect>
    </mask>
  </defs>

  <rect x='0' y='0' width='1180' height='610' rx='36' ry='36' fill='url(#bgGradient)'/>
  <rect x='0' y='0' width='1180' height='610' rx='36' ry='36' fill='url(#noise)' opacity='0.18'/>

  <circle cx='230' cy='150' r='260' fill='url(#glowA)' filter='url(#softBlur)'>
    <animate attributeName='cx' values='230;280;230' dur='12s' repeatCount='indefinite'/>
    <animate attributeName='cy' values='150;120;150' dur='12s' repeatCount='indefinite'/>
    <animate attributeName='opacity' values='0.7;0.95;0.7' dur='12s' repeatCount='indefinite'/>
  </circle>
  <circle cx='930' cy='440' r='280' fill='url(#glowB)' filter='url(#softBlur)'>
    <animate attributeName='cx' values='930;980;930' dur='13s' repeatCount='indefinite'/>
    <animate attributeName='cy' values='440;480;440' dur='13s' repeatCount='indefinite'/>
    <animate attributeName='opacity' values='0.55;0.8;0.55' dur='13s' repeatCount='indefinite'/>
  </circle>
  <circle cx='670' cy='120' r='190' fill='url(#glowC)' filter='url(#softBlur)'>
    <animate attributeName='opacity' values='0.35;0.65;0.35' dur='10s' repeatCount='indefinite'/>
  </circle>

  <g clip-path='url(#heroClip)'>
    <rect x='24' y='24' width='1132' height='562' rx='32' ry='32' fill='rgba(255,255,255,0.02)' stroke='rgba(255,255,255,0.08)' stroke-width='1.2'/>
    <rect x='24' y='24' width='1132' height='562' rx='32' ry='32' fill='none' stroke='url(#accentGradient)' stroke-width='1.4' stroke-dasharray='8 10' opacity='0.85'>
      <animate attributeName='stroke-dashoffset' values='0;120' dur='8s' repeatCount='indefinite'/>
    </rect>
    <rect x='24' y='24' width='1132' height='562' rx='32' ry='32' fill='none' stroke='rgba(255,255,255,0.18)' stroke-width='1' opacity='0.65'/>

    <rect x='24' y='24' width='1132' height='562' rx='32' ry='32' fill='url(#panelGradient)' opacity='0.9'/>
    <rect x='24' y='24' width='1132' height='562' rx='32' ry='32' fill='url(#noise)' opacity='0.09'/>

    <rect x='56' y='56' width='430' height='498' rx='24' ry='24' fill='rgba(255,255,255,0.03)' stroke='rgba(255,255,255,0.07)' stroke-width='1'/>
    <rect x='56' y='56' width='430' height='498' rx='24' ry='24' fill='none' stroke='rgba(255,255,255,0.08)' stroke-width='1.2'/>

    <rect x='520' y='56' width='620' height='498' rx='24' ry='24' fill='rgba(2,6,23,0.7)' stroke='rgba(255,255,255,0.08)' stroke-width='1'/>
    <rect x='520' y='56' width='620' height='498' rx='24' ry='24' fill='none' stroke='rgba(255,255,255,0.14)' stroke-width='1.2'/>

    <rect x='520' y='72' width='620' height='48' rx='18' ry='18' fill='rgba(255,255,255,0.04)'/>
    <circle cx='552' cy='96' r='7' fill='#ef4444'/>
    <circle cx='574' cy='96' r='7' fill='#f59e0b'/>
    <circle cx='596' cy='96' r='7' fill='#10b981'/>
    <rect x='520' y='56' width='620' height='498' rx='24' ry='24' fill='url(#noise)' opacity='0.1'/>

    <rect x='520' y='56' width='620' height='120' fill='url(#accentGradient)' opacity='0.07' mask='url(#shineMask)'/>
    <rect x='520' y='56' width='620' height='220' fill='rgba(255,255,255,0.04)' opacity='0.5'>
      <animate attributeName='y' values='-10;0;-10' dur='9s' repeatCount='indefinite'/>
    </rect>

    <rect x='540' y='132' width='580' height='2' fill='url(#accentGradient)' opacity='0.8'/>
    <rect x='540' y='132' width='580' height='2' fill='rgba(255,255,255,0.12)' opacity='0.5'>
      <animateMotion dur='6s' repeatCount='indefinite' path='M 0 0 L 0 340'/>
    </rect>

    <g transform='translate(114 132)'>
      <g transform='translate(0 0)'>
        <text x='0' y='0' font-family='Consolas, Monaco, monospace' font-size='15' fill='url(#asciiGradient)' letter-spacing='1' opacity='0'>
          <animate attributeName='opacity' values='0;1' dur='0.5s' begin='0.1s' fill='freeze'/>
          <animateTransform attributeName='transform' type='translate' values='0 0;0 -4;0 0' dur='5s' repeatCount='indefinite' additive='sum'/>
          <tspan x='0' dy='0'>      .-''''-.</tspan>
          <tspan x='0' dy='20'>     /  .--.  \\</tspan>
          <tspan x='0' dy='20'>    |  /    \  |</tspan>
          <tspan x='0' dy='20'>    | |  /\  | |</tspan>
          <tspan x='0' dy='20'>    | |/  \| | |</tspan>
          <tspan x='0' dy='20'>    |  \_/\_/  |</tspan>
          <tspan x='0' dy='20'>    |  .-..-.  |</tspan>
          <tspan x='0' dy='20'>    | (  oo )  |</tspan>
          <tspan x='0' dy='20'>    |  `--'`  |</tspan>
          <tspan x='0' dy='20'>     \  ____  /</tspan>
          <tspan x='0' dy='20'>      `-.__.-'</tspan>
        </text>
      </g>
      <circle cx='92' cy='90' r='52' fill='none' stroke='rgba(255,255,255,0.16)' stroke-width='1' opacity='0.65'>
        <animate attributeName='r' values='52;56;52' dur='7s' repeatCount='indefinite'/>
      </circle>
      <rect x='74' y='86' width='36' height='10' rx='5' fill='url(#accentGradient)' opacity='0.7'>
        <animate attributeName='opacity' values='0.35;0.8;0.35' dur='4s' repeatCount='indefinite'/>
      </rect>
    </g>

    <g transform='translate(620 160)'>
      <text x='0' y='0' font-family='Inter, Segoe UI, sans-serif' font-size='32' font-weight='700' fill='#F8FAFC' opacity='0'>
        <animate attributeName='opacity' values='0;1' dur='0.55s' begin='0.2s' fill='freeze'/>
        <tspan>Hi</tspan><tspan dx='8' fill='url(#accentGradient)'>👋</tspan>
      </text>
      <text x='0' y='48' font-family='Inter, Segoe UI, sans-serif' font-size='30' font-weight='600' fill='#F8FAFC' opacity='0'>
        <animate attributeName='opacity' values='0;1' dur='0.55s' begin='0.7s' fill='freeze'/>
        <tspan>I'm </tspan><tspan fill='url(#accentGradient)'>Abhiraj</tspan>
      </text>
      <text x='0' y='92' font-family='Consolas, Monaco, monospace' font-size='19' fill='#CBD5E1' opacity='0'>
        <animate attributeName='opacity' values='0;1' dur='0.55s' begin='1.2s' fill='freeze'/>
        <tspan opacity='0'><animate attributeName='opacity' values='0;1' dur='0.06s' begin='1.2s' fill='freeze'/><tspan>Pre</tspan></tspan><tspan dx='8' opacity='0'><animate attributeName='opacity' values='0;1' dur='0.06s' begin='1.26s' fill='freeze'/>Final</tspan><tspan dx='8' opacity='0'><animate attributeName='opacity' values='0;1' dur='0.06s' begin='1.32s' fill='freeze'/>Year</tspan><tspan dx='8' opacity='0'><animate attributeName='opacity' values='0;1' dur='0.06s' begin='1.38s' fill='freeze'/>IT</tspan><tspan dx='8' opacity='0'><animate attributeName='opacity' values='0;1' dur='0.06s' begin='1.44s' fill='freeze'/>Student</tspan><tspan dx='8' opacity='0'><animate attributeName='opacity' values='0;1' dur='0.06s' begin='1.5s' fill='freeze'/>&amp;</tspan><tspan dx='8' opacity='0'><animate attributeName='opacity' values='0;1' dur='0.06s' begin='1.56s' fill='freeze'/>AI</tspan><tspan dx='8' opacity='0'><animate attributeName='opacity' values='0;1' dur='0.06s' begin='1.62s' fill='freeze'/>Enthusiast</tspan>
      </text>
      <rect x='0' y='110' width='520' height='1' fill='rgba(255,255,255,0.16)' opacity='0'>
        <animate attributeName='opacity' values='0;1' dur='0.45s' begin='1.8s' fill='freeze'/>
      </rect>
      <g font-family='Inter, Segoe UI, sans-serif' font-size='18' fill='#E2E8F0'>
        <text x='0' y='154' opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='2.0s' fill='freeze'/><tspan fill='#94A3B8'>Location</tspan><tspan dx='20' fill='#F8FAFC'>Bengaluru, India</tspan></text>
        <text x='0' y='192' opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='2.32s' fill='freeze'/><tspan fill='#94A3B8'>Education</tspan><tspan dx='20' fill='#F8FAFC'>B.Tech IT</tspan></text>
        <text x='0' y='230' opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='2.64s' fill='freeze'/><tspan fill='#94A3B8'>Current Focus</tspan><tspan dx='20' fill='#F8FAFC'>AI + Systems</tspan></text>
        <text x='0' y='268' opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='2.96s' fill='freeze'/><tspan fill='#94A3B8'>Portfolio</tspan><tspan dx='20' fill='url(#accentGradient)'>abhiraj.dev</tspan></text>
        <text x='0' y='306' opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='3.28s' fill='freeze'/><tspan fill='#94A3B8'>Email</tspan><tspan dx='20' fill='#F8FAFC'>hello@abhiraj.dev</tspan></text>
      </g>

      <text x='0' y='356' font-family='Inter, Segoe UI, sans-serif' font-size='20' font-weight='600' fill='#F8FAFC' opacity='0'>
        <animate attributeName='opacity' values='0;1' dur='0.4s' begin='3.7s' fill='freeze'/>
        Skills
      </text>
      <g transform='translate(0 378)'>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='4.0s' fill='freeze'/><animateTransform attributeName='transform' type='translate' values='0 4;0 0;0 2' dur='3.5s' repeatCount='indefinite' additive='sum'/><rect x='0' y='0' width='90' height='34' rx='17' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.12)' stroke-width='1'/><text x='45' y='22' text-anchor='middle' font-family='Inter, Segoe UI, sans-serif' font-size='13' fill='#F8FAFC'>React</text></g>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='4.12s' fill='freeze'/><animateTransform attributeName='transform' type='translate' values='0 4;0 0;0 2' dur='3.6s' repeatCount='indefinite' additive='sum'/><rect x='100' y='0' width='95' height='34' rx='17' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.12)' stroke-width='1'/><text x='147.5' y='22' text-anchor='middle' font-family='Inter, Segoe UI, sans-serif' font-size='13' fill='#F8FAFC'>Next.js</text></g>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='4.24s' fill='freeze'/><animateTransform attributeName='transform' type='translate' values='0 4;0 0;0 2' dur='3.7s' repeatCount='indefinite' additive='sum'/><rect x='205' y='0' width='90' height='34' rx='17' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.12)' stroke-width='1'/><text x='250' y='22' text-anchor='middle' font-family='Inter, Segoe UI, sans-serif' font-size='13' fill='#F8FAFC'>Node.js</text></g>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='4.36s' fill='freeze'/><animateTransform attributeName='transform' type='translate' values='0 4;0 0;0 2' dur='3.8s' repeatCount='indefinite' additive='sum'/><rect x='305' y='0' width='100' height='34' rx='17' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.12)' stroke-width='1'/><text x='355' y='22' text-anchor='middle' font-family='Inter, Segoe UI, sans-serif' font-size='13' fill='#F8FAFC'>TypeScript</text></g>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='4.48s' fill='freeze'/><animateTransform attributeName='transform' type='translate' values='0 4;0 0;0 2' dur='3.9s' repeatCount='indefinite' additive='sum'/><rect x='415' y='0' width='95' height='34' rx='17' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.12)' stroke-width='1'/><text x='462.5' y='22' text-anchor='middle' font-family='Inter, Segoe UI, sans-serif' font-size='13' fill='#F8FAFC'>Tailwind</text></g>
      </g>
      <g transform='translate(0 430)'>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='4.6s' fill='freeze'/><animateTransform attributeName='transform' type='translate' values='0 4;0 0;0 2' dur='4s' repeatCount='indefinite' additive='sum'/><rect x='0' y='0' width='75' height='34' rx='17' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.12)' stroke-width='1'/><text x='37.5' y='22' text-anchor='middle' font-family='Inter, Segoe UI, sans-serif' font-size='13' fill='#F8FAFC'>Python</text></g>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='4.72s' fill='freeze'/><animateTransform attributeName='transform' type='translate' values='0 4;0 0;0 2' dur='4.1s' repeatCount='indefinite' additive='sum'/><rect x='85' y='0' width='90' height='34' rx='17' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.12)' stroke-width='1'/><text x='130' y='22' text-anchor='middle' font-family='Inter, Segoe UI, sans-serif' font-size='13' fill='#F8FAFC'>Docker</text></g>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='4.84s' fill='freeze'/><animateTransform attributeName='transform' type='translate' values='0 4;0 0;0 2' dur='4.2s' repeatCount='indefinite' additive='sum'/><rect x='185' y='0' width='95' height='34' rx='17' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.12)' stroke-width='1'/><text x='232.5' y='22' text-anchor='middle' font-family='Inter, Segoe UI, sans-serif' font-size='13' fill='#F8FAFC'>Postgres</text></g>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='4.96s' fill='freeze'/><animateTransform attributeName='transform' type='translate' values='0 4;0 0;0 2' dur='4.3s' repeatCount='indefinite' additive='sum'/><rect x='290' y='0' width='75' height='34' rx='17' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,2550.12)' stroke-width='1'/><text x='327.5' y='22' text-anchor='middle' font-family='Inter, Segoe UI, sans-serif' font-size='13' fill='#F8FAFC'>AWS</text></g>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='5.08s' fill='freeze'/><animateTransform attributeName='transform' type='translate' values='0 4;0 0;0 2' dur='4.4s' repeatCount='indefinite' additive='sum'/><rect x='375' y='0' width='70' height='34' rx='17' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.12)' stroke-width='1'/><text x='410' y='22' text-anchor='middle' font-family='Inter, Segoe UI, sans-serif' font-size='13' fill='#F8FAFC'>Git</text></g>
      </g>
      <g transform='translate(0 478)'>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='5.2s' fill='freeze'/><animateTransform attributeName='transform' type='translate' values='0 4;0 0;0 2' dur='4.5s' repeatCount='indefinite' additive='sum'/><rect x='0' y='0' width='80' height='34' rx='17' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.12)' stroke-width='1'/><text x='40' y='22' text-anchor='middle' font-family='Inter, Segoe UI, sans-serif' font-size='13' fill='#F8FAFC'>Figma</text></g>
      </g>

      <g transform='translate(0 524)'>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='5.6s' fill='freeze'/><circle cx='0' cy='0' r='16' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.14)' stroke-width='1' filter='url(#glowStroke)'/><path d='M-6 0h12' stroke='#F8FAFC' stroke-width='2' stroke-linecap='round'/><path d='M0 -6v12' stroke='#F8FAFC' stroke-width='2' stroke-linecap='round'/><text x='30' y='5' font-family='Inter, Segoe UI, sans-serif' font-size='14' fill='#94A3B8'>GitHub</text></g>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='5.72s' fill='freeze'/><circle cx='132' cy='0' r='16' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.14)' stroke-width='1' filter='url(#glowStroke)'/><path d='M126 0h12' stroke='#F8FAFC' stroke-width='2' stroke-linecap='round'/><path d='M132 -6v12' stroke='#F8FAFC' stroke-width='2' stroke-linecap='round'/><text x='162' y='5' font-family='Inter, Segoe UI, sans-serif' font-size='14' fill='#94A3B8'>LinkedIn</text></g>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='5.84s' fill='freeze'/><circle cx='265' cy='0' r='16' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.14)' stroke-width='1' filter='url(#glowStroke)'/><path d='M259 0h12' stroke='#F8FAFC' stroke-width='2' stroke-linecap='round'/><path d='M265 -6v12' stroke='#F8FAFC' stroke-width='2' stroke-linecap='round'/><text x='295' y='5' font-family='Inter, Segoe UI, sans-serif' font-size='14' fill='#94A3B8'>Twitter</text></g>
        <g opacity='0'><animate attributeName='opacity' values='0;1' dur='0.35s' begin='5.96s' fill='freeze'/><circle cx='398' cy='0' r='16' fill='rgba(255,255,255,0.06)' stroke='rgba(255,255,255,0.14)' stroke-width='1' filter='url(#glowStroke)'/><path d='M392 0h12' stroke='#F8FAFC' stroke-width='2' stroke-linecap='round'/><path d='M398 -6v12' stroke='#F8FAFC' stroke-width='2' stroke-linecap='round'/><text x='428' y='5' font-family='Inter, Segoe UI, sans-serif' font-size='14' fill='#94A3B8'>Portfolio</text></g>
      </g>
    </g>

    <g opacity='0.7'>
      <circle cx='120' cy='520' r='4' fill='#22D3EE'>
        <animate attributeName='opacity' values='0.2;1;0.2' dur='3.2s' repeatCount='indefinite'/>
        <animateTransform attributeName='transform' type='translate' values='0 0;0 -18;0 0' dur='3.2s' repeatCount='indefinite' additive='sum'/>
      </circle>
      <circle cx='182' cy='506' r='3' fill='#8B5CF6'>
        <animate attributeName='opacity' values='0.2;1;0.2' dur='2.7s' repeatCount='indefinite'/>
        <animateTransform attributeName='transform' type='translate' values='0 0;0 -12;0 0' dur='2.7s' repeatCount='indefinite' additive='sum'/>
      </circle>
      <circle cx='800' cy='116' r='3.5' fill='#10B981'>
        <animate attributeName='opacity' values='0.2;0.9;0.2' dur='4.2s' repeatCount='indefinite'/>
      </circle>
      <circle cx='914' cy='122' r='2.5' fill='#22D3EE'>
        <animate attributeName='opacity' values='0.3;1;0.3' dur='3.8s' repeatCount='indefinite'/>
      </circle>
    </g>

    <rect x='58' y='100' width='420' height='1' fill='rgba(255,255,255,0.1)'/>
    <rect x='58' y='100' width='420' height='1' fill='url(#accentGradient)' opacity='0.6'>
      <animate attributeName='width' values='120;420;120' dur='7s' repeatCount='indefinite'/>
    </rect>

    <rect x='896' y='110' width='220' height='1' fill='rgba(255,255,255,0.1)' opacity='0.5'/>
    <rect x='896' y='110' width='220' height='1' fill='url(#accentGradient)' opacity='0.45'>
      <animate attributeName='x' values='896;796;896' dur='8s' repeatCount='indefinite'/>
    </rect>
  </g>

  <rect x='0' y='0' width='1180' height='610' rx='36' ry='36' fill='none' stroke='rgba(255,255,255,0.1)' stroke-width='1.2'/>
  <rect x='0' y='0' width='1180' height='610' rx='36' ry='36' fill='none' stroke='url(#accentGradient)' stroke-width='1.2' opacity='0.45'/> 
</svg>

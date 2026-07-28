<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1280 420">

<defs>

<linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
<stop offset="0%" stop-color="#050816"/>
<stop offset="55%" stop-color="#0b1024"/>
<stop offset="100%" stop-color="#1d0b42"/>
</linearGradient>

<linearGradient id="text">
<stop offset="0%" stop-color="#a855f7"/>
<stop offset="100%" stop-color="#38bdf8"/>
</linearGradient>

<filter id="glow">
<feGaussianBlur stdDeviation="5" result="b"/>
<feMerge>
<feMergeNode in="b"/>
<feMergeNode in="SourceGraphic"/>
</feMerge>
</filter>

<filter id="glass">
<feGaussianBlur stdDeviation="18"/>
</filter>

<clipPath id="typing">
<rect x="90" y="235" width="0" height="30">
<animate
attributeName="width"
values="0;310;310"
dur="4s"
repeatCount="indefinite"/>
</rect>
</clipPath>

</defs>

<rect width="1280" height="420" fill="url(#bg)"/>

<!-- background grid -->

<g stroke="#ffffff10">

<path d="M0 80H1280"/>
<path d="M0 160H1280"/>
<path d="M0 240H1280"/>
<path d="M0 320H1280"/>

<path d="M160 0V420"/>
<path d="M320 0V420"/>
<path d="M480 0V420"/>
<path d="M640 0V420"/>
<path d="M800 0V420"/>
<path d="M960 0V420"/>
<path d="M1120 0V420"/>

</g>

<!-- glow -->

<circle cx="1080" cy="120" r="120"
fill="#7c3aed"
opacity=".22"
filter="url(#glass)"/>

<circle cx="260" cy="350" r="70"
fill="#38bdf8"
opacity=".18"
filter="url(#glass)"/>

<!-- glass panel -->

<rect
x="55"
y="55"
rx="28"
width="700"
height="300"
fill="#ffffff08"
stroke="#ffffff22"/>

<!-- title -->

<text
x="90"
y="145"
font-size="64"
font-family="Segoe UI"
font-weight="700"
fill="url(#text)"
filter="url(#glow)">
Danial Karimi
</text>

<text
x="92"
y="190"
font-size="26"
fill="#dbeafe"
font-family="Segoe UI">
AI Engineer • Computer Engineer
</text>

<!-- typing -->

<g clip-path="url(#typing)">

<text
x="92"
y="245"
font-size="22"
fill="#38bdf8"
font-family="Consolas">
Building Intelligent Systems
</text>

</g>

<rect x="398" y="224" width="3" height="24" fill="#38bdf8">
<animate attributeName="opacity"
values="1;0;1"
dur="1s"
repeatCount="indefinite"/>
</rect>

<!-- skill pills -->

<g font-family="Segoe UI" font-size="16">

<rect x="90" y="285" rx="14" width="90" height="30" fill="#7c3aed55"/>
<text x="113" y="305" fill="white">Python</text>

<rect x="190" y="285" rx="14" width="60" height="30" fill="#0ea5e955"/>
<text x="212" y="305" fill="white">C#</text>

<rect x="260" y="285" rx="14" width="120" height="30" fill="#06b6d455"/>
<text x="280" y="305" fill="white">PyTorch</text>

<rect x="392" y="285" rx="14" width="130" height="30" fill="#9333ea55"/>
<text x="414" y="305" fill="white">TensorFlow</text>

</g>

<!-- AI Brain -->

<g
stroke="#61dafb"
stroke-width="2"
fill="none"
opacity=".95">

<line x1="865" y1="90" x2="940" y2="120"/>
<line x1="940" y1="120" x2="1015" y2="85"/>
<line x1="940" y1="120" x2="980" y2="190"/>
<line x1="980" y1="190" x2="1080" y2="170"/>
<line x1="1015" y1="85" x2="1110" y2="110"/>
<line x1="1110" y1="110" x2="1150" y2="180"/>
<line x1="1080" y1="170" x2="1150" y2="180"/>
<line x1="930" y1="220" x2="980" y2="190"/>
<line x1="930" y1="220" x2="865" y2="170"/>
<line x1="865" y1="170" x2="865" y2="90"/>

<circle cx="865" cy="90" r="6"/>
<circle cx="940" cy="120" r="7"/>
<circle cx="1015" cy="85" r="5"/>
<circle cx="980" cy="190" r="6"/>
<circle cx="1080" cy="170" r="6"/>
<circle cx="1110" cy="110" r="5"/>
<circle cx="1150" cy="180" r="6"/>
<circle cx="930" cy="220" r="5"/>
<circle cx="865" cy="170" r="5"/>

</g>

<!-- pulse -->

<circle cx="940" cy="120" r="8"
fill="#38bdf8">

<animate
attributeName="r"
values="8;13;8"
dur="2s"
repeatCount="indefinite"/>

</circle>

<!-- particles -->

<g fill="#7dd3fc">

<circle cx="80" cy="70" r="2">
<animate attributeName="cy"
values="70;50;70"
dur="4s"
repeatCount="indefinite"/>
</circle>

<circle cx="400" cy="60" r="2">
<animate attributeName="cy"
values="60;30;60"
dur="5s"
repeatCount="indefinite"/>
</circle>

<circle cx="760" cy="320" r="2">
<animate attributeName="cy"
values="320;290;320"
dur="6s"
repeatCount="indefinite"/>
</circle>

<circle cx="1180" cy="320" r="2">
<animate attributeName="cy"
values="320;270;320"
dur="5s"
repeatCount="indefinite"/>
</circle>

</g>

<!-- scanner -->

<rect
x="55"
y="55"
width="700"
height="3"
fill="#38bdf8"
opacity=".8">

<animate
attributeName="y"
values="55;352;55"
dur="7s"
repeatCount="indefinite"/>

</rect>

</svg>

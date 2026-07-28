<svg width="1280" height="420" viewBox="0 0 1280 420" xmlns="http://www.w3.org/2000/svg">

<defs>

<linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
<stop offset="0%" stop-color="#050816"/>
<stop offset="45%" stop-color="#0F172A"/>
<stop offset="100%" stop-color="#1E1B4B"/>
</linearGradient>

<linearGradient id="primary" x1="0%" y1="0%" x2="100%">
<stop offset="0%" stop-color="#7C3AED"/>
<stop offset="100%" stop-color="#38BDF8"/>
</linearGradient>

<linearGradient id="glass" x1="0%" y1="0%" x2="100%">
<stop offset="0%" stop-color="#ffffff22"/>
<stop offset="100%" stop-color="#ffffff08"/>
</linearGradient>

<filter id="glow">
<feGaussianBlur stdDeviation="6"/>
</filter>

<filter id="softGlow">
<feGaussianBlur stdDeviation="18"/>
</filter>

</defs>

<!-- Background -->

<rect width="1280" height="420" fill="url(#bg)"/>

<!-- Glow -->

<circle cx="1060" cy="120" r="120"
fill="#6D28D9"
opacity=".25"
filter="url(#softGlow)">
<animate attributeName="r"
values="110;140;110"
dur="5s"
repeatCount="indefinite"/>
</circle>

<circle cx="220" cy="330" r="80"
fill="#38BDF8"
opacity=".15"
filter="url(#softGlow)">
<animate attributeName="r"
values="70;95;70"
dur="4s"
repeatCount="indefinite"/>
</circle>

<!-- AI Network -->

<g stroke="#5EEAD4" stroke-width="1.4" opacity=".45">

<line x1="880" y1="70" x2="980" y2="120"/>
<line x1="980" y1="120" x2="1100" y2="80"/>
<line x1="980" y1="120" x2="1070" y2="190"/>
<line x1="880" y1="70" x2="930" y2="220"/>
<line x1="930" y1="220" x2="1070" y2="190"/>
<line x1="1070" y1="190" x2="1170" y2="160"/>
<line x1="1100" y1="80" x2="1170" y2="160"/>

</g>

<!-- Nodes -->

<g fill="#67E8F9">

<circle cx="880" cy="70" r="5">
<animate attributeName="r" values="5;8;5" dur="2.8s" repeatCount="indefinite"/>
</circle>

<circle cx="980" cy="120" r="6">
<animate attributeName="fill"
values="#67E8F9;#A855F7;#67E8F9"
dur="3s"
repeatCount="indefinite"/>
</circle>

<circle cx="1100" cy="80" r="5"/>

<circle cx="930" cy="220" r="5"/>

<circle cx="1070" cy="190" r="6"/>

<circle cx="1170" cy="160" r="5"/>

</g>

<!-- Floating Particles -->

<g fill="#38BDF8">

<circle cx="120" cy="90" r="2">
<animate attributeName="cy"
values="90;60;90"
dur="5s"
repeatCount="indefinite"/>
</circle>

<circle cx="520" cy="60" r="2">
<animate attributeName="cy"
values="60;20;60"
dur="6s"
repeatCount="indefinite"/>
</circle>

<circle cx="760" cy="340" r="2">
<animate attributeName="cy"
values="340;300;340"
dur="4s"
repeatCount="indefinite"/>
</circle>

<circle cx="1190" cy="300" r="2">
<animate attributeName="cy"
values="300;250;300"
dur="7s"
repeatCount="indefinite"/>
</circle>

</g>

<!-- Glass Card -->

<rect
x="60"
y="70"
rx="28"
ry="28"
width="690"
height="280"
fill="url(#glass)"
stroke="#ffffff18"/>

<!-- Name -->

<text
x="95"
y="155"
font-size="64"
font-family="Segoe UI"
font-weight="700"
fill="url(#primary)"
filter="url(#glow)">

Danial Karimi

</text>

<!-- Subtitle -->

<text
x="95"
y="205"
font-size="28"
font-family="Segoe UI"
fill="#E2E8F0">

AI Engineer • Computer Engineer

</text>

<!-- Typing -->

<text
x="95"
y="255"
font-size="22"
font-family="Consolas"
fill="#38BDF8">

Building Intelligent Systems_

<animate
attributeName="opacity"
values="1;0;1"
dur="1s"
repeatCount="indefinite"/>

</text>

<!-- Skills -->

<g font-family="Segoe UI" font-size="18">

<rect x="95" y="290" rx="14" width="92" height="32" fill="#7C3AED33"/>
<text x="114" y="311" fill="#fff">Python</text>

<rect x="205" y="290" rx="14" width="70" height="32" fill="#38BDF833"/>
<text x="228" y="311" fill="#fff">C#</text>

<rect x="290" y="290" rx="14" width="150" height="32" fill="#06B6D433"/>
<text x="312" y="311" fill="#fff">Machine Learning</text>

<rect x="455" y="290" rx="14" width="120" height="32" fill="#9333EA33"/>
<text x="476" y="311" fill="#fff">Deep Learning</text>

<rect x="590" y="290" rx="14" width="95" height="32" fill="#0EA5E933"/>
<text x="615" y="311" fill="#fff">Linux</text>

</g>

<!-- Animated Scanner -->

<rect x="60" y="70" width="690" height="4" fill="#38BDF8" opacity=".7">

<animate
attributeName="y"
values="70;346;70"
dur="6s"
repeatCount="indefinite"/>

</rect>

</svg>

<div align="center">

<!-- ========================================================= -->
<!-- FUTURISTIC HERO -->
<!-- ========================================================= -->

<svg
  width="100%"
  viewBox="0 0 1400 520"
  xmlns="http://www.w3.org/2000/svg"
  role="img"
  aria-label="Dilep Babu futuristic developer profile"
>

<defs>

  <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
    <stop offset="0%" stop-color="#08090B"/>
    <stop offset="52%" stop-color="#11130F"/>
    <stop offset="100%" stop-color="#1B110D"/>
  </linearGradient>

  <linearGradient id="orange" x1="0" y1="0" x2="1" y2="1">
    <stop offset="0%" stop-color="#FFC58F"/>
    <stop offset="45%" stop-color="#FF6B35"/>
    <stop offset="100%" stop-color="#FF3D00"/>
  </linearGradient>

  <linearGradient id="lime" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#E1FF7A"/>
    <stop offset="50%" stop-color="#C6FF4A"/>
    <stop offset="100%" stop-color="#8EDB32"/>
  </linearGradient>

  <linearGradient id="title" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#FFF9EC"/>
    <stop offset="58%" stop-color="#F3E9D2"/>
    <stop offset="100%" stop-color="#FF7543"/>
  </linearGradient>

  <radialGradient id="glowOrange">
    <stop offset="0%" stop-color="#FF6B35" stop-opacity=".34"/>
    <stop offset="100%" stop-color="#FF6B35" stop-opacity="0"/>
  </radialGradient>

  <radialGradient id="glowLime">
    <stop offset="0%" stop-color="#C6FF4A" stop-opacity=".18"/>
    <stop offset="100%" stop-color="#C6FF4A" stop-opacity="0"/>
  </radialGradient>

  <pattern
    id="grid"
    width="34"
    height="34"
    patternUnits="userSpaceOnUse"
  >
    <path
      d="M34 0H0V34"
      stroke="#F3E9D2"
      stroke-opacity=".045"
      stroke-width="1"
    />
  </pattern>

  <filter id="blur">
    <feGaussianBlur stdDeviation="30"/>
  </filter>

  <style>

    .mono {
      font-family:
        "SFMono-Regular",
        Consolas,
        "Liberation Mono",
        monospace;

      letter-spacing: 3px;
    }

    .title {
      font-family:
        Inter,
        Arial,
        sans-serif;

      font-weight: 900;
      letter-spacing: 8px;
    }

    .pulse {
      animation:
        pulse 2.8s ease-in-out infinite;
    }

    .orbit {
      animation:
        orbit 11s linear infinite;

      transform-origin:
        1110px 235px;
    }

    .orbit2 {
      animation:
        orbit2 17s linear infinite;

      transform-origin:
        1110px 235px;
    }

    .blink {
      animation:
        blink 2.2s ease-in-out infinite;
    }

    .scan {
      animation:
        scan 6s linear infinite;
    }

    @keyframes pulse {

      0%,
      100% {
        opacity: .25;
      }

      50% {
        opacity: 1;
      }

    }

    @keyframes orbit {

      from {
        transform: rotate(0deg);
      }

      to {
        transform: rotate(360deg);
      }

    }

    @keyframes orbit2 {

      from {
        transform: rotate(360deg);
      }

      to {
        transform: rotate(0deg);
      }

    }

    @keyframes blink {

      0%,
      45%,
      100% {
        opacity: 1;
      }

      50% {
        opacity: .2;
      }

    }

    @keyframes scan {

      0% {
        transform: translateX(-700px);
        opacity: 0;
      }

      15% {
        opacity: .75;
      }

      80% {
        opacity: .75;
      }

      100% {
        transform: translateX(1800px);
        opacity: 0;
      }

    }

  </style>

</defs>


<!-- ========================================================= -->
<!-- BACKGROUND -->
<!-- ========================================================= -->

<rect
  width="1400"
  height="520"
  rx="32"
  fill="url(#bg)"
/>

<rect
  width="1400"
  height="520"
  rx="32"
  fill="url(#grid)"
/>

<rect
  x="1"
  y="1"
  width="1398"
  height="518"
  rx="32"
  fill="none"
  stroke="#F3E9D2"
  stroke-opacity=".13"
/>


<!-- ========================================================= -->
<!-- AMBIENT LIGHT -->
<!-- ========================================================= -->

<ellipse
  cx="1110"
  cy="210"
  rx="360"
  ry="250"
  fill="url(#glowOrange)"
  filter="url(#blur)"
/>

<ellipse
  cx="240"
  cy="415"
  rx="310"
  ry="170"
  fill="url(#glowLime)"
  filter="url(#blur)"
/>


<!-- ========================================================= -->
<!-- TOP SYSTEM BAR -->
<!-- ========================================================= -->

<text
  x="72"
  y="60"
  fill="#6F7068"
  font-size="13"
  class="mono"
>
  DIGITAL_IDENTITY / 2026
</text>

<circle
  cx="1090"
  cy="56"
  r="5"
  fill="#C6FF4A"
  class="blink"
/>

<text
  x="1115"
  y="61"
  fill="#C6FF4A"
  font-size="13"
  class="mono"
>
  SYSTEM_ACTIVE
</text>


<!-- ========================================================= -->
<!-- CORNER MARKS -->
<!-- ========================================================= -->

<path
  d="M42 98V42H98"
  stroke="url(#orange)"
  stroke-width="2"
/>

<path
  d="M1302 478H1358V422"
  stroke="url(#lime)"
  stroke-width="2"
/>


<!-- ========================================================= -->
<!-- LEFT LABEL -->
<!-- ========================================================= -->

<text
  x="72"
  y="148"
  fill="#77786F"
  font-size="13"
  class="mono"
>
  USER / 001
</text>


<!-- ========================================================= -->
<!-- NAME -->
<!-- ========================================================= -->

<text
  x="70"
  y="242"
  fill="url(#title)"
  font-size="72"
  class="title"
>
  DILEP
</text>

<text
  x="70"
  y="316"
  fill="url(#title)"
  font-size="72"
  class="title"
>
  BABU
</text>


<!-- ========================================================= -->
<!-- SUBTITLE -->
<!-- ========================================================= -->

<text
  x="74"
  y="360"
  fill="#B8B7AC"
  font-size="15"
  class="mono"
>
  B.TECH / INFORMATION TECHNOLOGY
</text>

<text
  x="74"
  y="391"
  fill="#686960"
  font-size="12"
  class="mono"
>
  SOFTWARE / BACKEND / API / DIGITAL PRODUCTS
</text>


<!-- ========================================================= -->
<!-- SIGNAL -->
<!-- ========================================================= -->

<rect
  x="74"
  y="419"
  width="450"
  height="2"
  rx="1"
  fill="#2B2D28"
/>

<rect
  x="74"
  y="419"
  width="115"
  height="2"
  rx="1"
  fill="url(#orange)"
  class="pulse"
/>

<text
  x="74"
  y="449"
  fill="#6A6B63"
  font-size="12"
  class="mono"
>
  BUILD / LEARN / SHIP / REPEAT
</text>


<!-- ========================================================= -->
<!-- ORBITAL SYSTEM -->
<!-- ========================================================= -->

<circle
  cx="1110"
  cy="235"
  r="116"
  stroke="#F3E9D2"
  stroke-opacity=".06"
/>

<circle
  cx="1110"
  cy="235"
  r="94"
  stroke="#FF6B35"
  stroke-opacity=".10"
/>

<circle
  cx="1110"
  cy="235"
  r="70"
  stroke="#FF6B35"
  stroke-opacity=".20"
/>

<circle
  cx="1110"
  cy="235"
  r="42"
  stroke="#C6FF4A"
  stroke-opacity=".32"
/>

<circle
  cx="1110"
  cy="235"
  r="15"
  fill="#FF6B35"
  class="pulse"
/>


<!-- ========================================================= -->
<!-- ORBITING NODES -->
<!-- ========================================================= -->

<g class="orbit">

  <circle
    cx="1226"
    cy="235"
    r="5"
    fill="#C6FF4A"
  />

  <circle
    cx="1110"
    cy="119"
    r="4"
    fill="#FF6B35"
  />

</g>

<g class="orbit2">

  <circle
    cx="1040"
    cy="175"
    r="4"
    fill="#F3E9D2"
  />

</g>


<!-- ========================================================= -->
<!-- CIRCUIT PATHS -->
<!-- ========================================================= -->

<path
  d="M1110 119V88H1262"
  stroke="#FF6B35"
  stroke-opacity=".35"
/>

<path
  d="M1226 235H1302V302"
  stroke="#C6FF4A"
  stroke-opacity=".28"
/>

<path
  d="M1040 175H972V118H908"
  stroke="#F3E9D2"
  stroke-opacity=".16"
/>


<!-- ========================================================= -->
<!-- NODE LIGHTS -->
<!-- ========================================================= -->

<circle
  cx="1262"
  cy="88"
  r="4"
  fill="#FF6B35"
  class="blink"
/>

<circle
  cx="1302"
  cy="302"
  r="4"
  fill="#C6FF4A"
  class="pulse"
/>

<circle
  cx="908"
  cy="118"
  r="4"
  fill="#F3E9D2"
  class="blink"
/>


<!-- ========================================================= -->
<!-- MINI TERMINAL -->
<!-- ========================================================= -->

<rect
  x="850"
  y="356"
  width="420"
  height="86"
  rx="15"
  fill="#08090B"
  fill-opacity=".9"
  stroke="#F3E9D2"
  stroke-opacity=".13"
/>

<circle cx="880" cy="382" r="5" fill="#FF6B35"/>
<circle cx="898" cy="382" r="5" fill="#C6FF4A"/>
<circle cx="916" cy="382" r="5" fill="#F3E9D2"/>

<text
  x="880"
  y="414"
  fill="#FFB27A"
  font-size="12"
  class="mono"
>
  ./build_future.sh
</text>

<text
  x="880"
  y="434"
  fill="#64655D"
  font-size="10"
  class="mono"
>
  STATUS::READY
</text>


<!-- ========================================================= -->
<!-- SCAN -->
<!-- ========================================================= -->

<rect
  x="-700"
  y="486"
  width="500"
  height="2"
  fill="url(#orange)"
  class="scan"
/>

</svg>

<br/>

<a href="https://www.linkedin.com/in/dilep-babu-r-99a463283/">
  <img
    src="https://img.shields.io/badge/LINKEDIN-08090B?style=for-the-badge&logo=linkedin&logoColor=white&color=FF6B35"
    alt="LinkedIn"
  />
</a>

<a href="https://leetcode.com/u/Dilep_Babu/">
  <img
    src="https://img.shields.io/badge/LEETCODE-08090B?style=for-the-badge&logo=leetcode&logoColor=08090B&color=C6FF4A"
    alt="LeetCode"
  />
</a>

<a href="https://drive.google.com/file/d/1Aw6lCGpxdbdqakM7v9xISPU3vkdsBR5u/view?usp=drivesdk">
  <img
    src="https://img.shields.io/badge/RESUME-08090B?style=for-the-badge&logo=googledrive&logoColor=08090B&color=F3E9D2"
    alt="Resume"
  />
</a>

<br/>
<br/>

<img
  src="https://komarev.com/ghpvc/?username=dilepbabu&style=for-the-badge&color=FF6B35&label=PROFILE+VIEWS"
  alt="Profile Views"
/>

</div>


<!-- ========================================================= -->
<!-- INTRO -->
<!-- ========================================================= -->

<table width="100%">
<tr>

<td width="62%" valign="top">

# `HELLO, WORLD.`

## I'm Dilep Babu

### B.Tech — Information Technology

I'm interested in building practical software systems,
backend applications, APIs and modern digital experiences.

> **Make complex systems feel simple.**

I enjoy learning through projects, solving problems and
continuously improving how I build software.

</td>

<td width="38%" valign="top">

```text
╭────────────────────────────╮
│      IDENTITY.NODE         │
├────────────────────────────┤
│                            │
│ NAME                       │
│ DILEP BABU                 │
│                            │
│ FIELD                      │
│ INFORMATION TECHNOLOGY     │
│                            │
│ MODE                       │
│ BUILD / LEARN / SHIP       │
│                            │
│ STATUS                     │
│ ● ONLINE                   │
│                            │
╰────────────────────────────╯

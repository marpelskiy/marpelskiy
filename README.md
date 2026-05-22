<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marpelskiy - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            font-family: 'JetBrains Mono', monospace;
            margin: 0;
            padding: 0;
        }
        a {
            color: #00ff99;
            text-decoration: none;
        }
        div.center {
            text-align: center;
            padding: 20px;
        }
        h3 {
            color: #00ff99;
            margin-top: 30px;
        }
        .tech-icons img {
            vertical-align: middle;
            margin-right: 6px;
        }
        .projects, .operations {
            display: flex;
            flex-wrap: wrap;
            gap: 14px;
            justify-content: center;
            margin-top: 20px;
        }
        .card {
            background: #0d1117;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 16px;
            width: 280px;
            text-align: left;
        }
        .card h4 {
            margin: 0 0 10px 0;
            color: #00ff99;
            font-family: 'JetBrains Mono', monospace;
            display: flex;
            align-items: center;
            gap: 6px;
        }
        .glow-text {
            font-family: Impact, 'Arial Black', sans-serif;
            font-size: 96px;
            font-weight: 900;
            letter-spacing: 12px;
            fill: #00ff99;
            filter: url(#glow);
        }
    </style>
</head>
<body>

<div class="center">
    <div style="font-size: 22px; font-weight: 900; color: #00ff99; letter-spacing: 8px; margin-bottom: 15px;">
        6D 61 72 70 65 6C
    </div>

    <svg width="900" height="160" viewBox="0 0 900 160" xmlns="http://www.w3.org/2000/svg">
        <defs>
            <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
                <feGaussianBlur stdDeviation="8" result="blur" />
                <feMerge>
                    <feMergeNode in="blur" />
                    <feMergeNode in="SourceGraphic" />
                </feMerge>
            </filter>
        </defs>
        <path d="M 20 40 L 70 40 L 82 52 M 20 40 L 20 120 L 32 132" stroke="#00ff99" stroke-width="4" fill="none" opacity="0.85"/>
        <path d="M 880 120 L 830 120 L 818 108 M 880 120 L 880 40 L 868 28" stroke="#00ff99" stroke-width="4" fill="none" opacity="0.85"/>
        <text x="50%" y="102" text-anchor="middle" class="glow-text">MARPELSKIY</text>
        <line x1="220" y1="132" x2="680" y2="132" stroke="#00ff99" stroke-width="5" opacity="0.9"/>
        <rect x="432" y="127" width="36" height="10" fill="#00ff99"/>
    </svg>

    <a href="https://un-sec.github.io" target="_blank">
        <img src="https://img.shields.io/static/v1?label=un-sec&message=team&color=00ff99&labelColor=black&style=for-the-badge" alt="un-sec team"/>
    </a>

    <br><br>
    <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=28&pause=1000&color=00FF99&center=true&vCenter=true&width=900&lines=SYSTEMS+%26+SECURITY+ENGINEER;PENTEST+%7C+OSINT+%7C+REVERSE+ENGINEERING;NETWORK+EXPLOITATION+SPECIALIST;UN-SEC+MEMBER" />
</div>

<!-- TECHNICAL PROFILE -->
<div class="center">
    <h3>// TECHNICAL PROFILE</h3>
    <h3>LANGUAGES & HARDWARE</h3>
    <p class="tech-icons">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="20" height="20"/><b>C++</b> |
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" width="20" height="20"/><b>C</b> |
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="20" height="20"/><b>Python</b> |
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="20" height="20"/><b>JavaScript</b> |
        <img src="https://api.iconify.design/ph:cpu-bold.svg?color=%2300ff99" width="20" height="20"/><b>Hardware Programming (MCU)</b>
    </p>
    <h3>OPERATING SYSTEMS</h3>
    <p class="tech-icons">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/archlinux/archlinux-original.svg" width="20" height="20"/><b>Arch</b> |
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/gentoo/gentoo-original.svg" width="20" height="20"/><b>Gentoo</b> |
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/voidlinux/voidlinux-original.svg" width="20" height="20"/><b>Void</b> |
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nixos/nixos-original.svg" width="20" height="20"/><b>NixOS</b> |
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/debian/debian-original.svg" width="20" height="20"/><b>Debian</b> |
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fedora/fedora-original.svg" width="20" height="20"/><b>Fedora</b>
    </p>
</div>

</body>
</html>

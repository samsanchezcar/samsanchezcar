# Style Guide — samsanchezcar

Reference document for consistent visual identity across all repositories.
Copy snippets directly — replace placeholder values as needed.

---

## Color Palette

| Role | Hex | Usage |
|:-----|:----|:------|
| **Background deep** | `#0f1c2e` | Badge backgrounds, stats bg |
| **Background mid** | `#1a3354` | Secondary badge bg, area fills |
| **Blue navy** | `#1e4d7b` | Accent borders, badge labels |
| **Blue main** | `#2980b9` | Icons, rings, fire, active elements |
| **Blue light** | `#5d8aa8` | Secondary text, dates |
| **Blue accent** | `#7fb3d3` | Logo colors, primary accent |
| **Blue pale** | `#aed6f1` | Desc text, secondary accents |
| **Text light** | `#e8f4fd` | Headers, primary text on dark |
| **ORCID green** | `#a6ce39` | ORCID badge only |
| **ANSYS yellow** | `#FFB71B` | ANSYS badge only |
| **ESP32 red** | `#cf6679` | Espressif/hardware accent |

---

## Headers — capsule-render

### Profile header (tall, with desc)
```markdown
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f1c2e,30:1a3354,60:1e4d7b,100:2980b9&height=300&section=header&text=YOUR%20NAME&fontSize=42&fontAlignY=40&fontColor=e8f4fd&animation=fadeIn&desc=Your%20desc%20here&descSize=17&descAlignY=60&descColor=aed6f1&stroke=2980b9&strokeWidth=1" width="100%"/>
```

### Repo header (shorter, no stroke)
```markdown
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f1c2e,30:1a3354,60:1e4d7b,100:2980b9&height=200&section=header&text=REPO-NAME&fontSize=36&fontAlignY=45&fontColor=e8f4fd&animation=fadeIn&desc=Short+description&descSize=15&descAlignY=65&descColor=aed6f1" width="100%"/>
```

### Footer (reversed gradient)
```markdown
<img src="https://capsule-render.vercel.app/api?type=waving&color=2980b9,1e4d7b,1a3354,0f1c2e&height=120&section=footer&animation=fadeIn" width="100%"/>
```

---

## Typing Animation

```markdown
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=17&duration=3000&pause=900&color=7FB3D3&center=true&vCenter=true&width=820&height=35&lines=Line+one+here;Line+two+here;Line+three+here" alt="Typing"/>
```

**Font:** `Fira+Code` · **Color:** `7FB3D3` · **Size:** 17 (profile) / 15 (repo)

---

## Social Badges

```markdown
<a href="mailto:samsanchezcar@gmail.com"><img src="https://img.shields.io/badge/-Gmail-0f1c2e?style=for-the-badge&logo=gmail&logoColor=7fb3d3"/></a>
<a href="https://linkedin.com/in/samuel-sanchez-cardenas"><img src="https://img.shields.io/badge/-LinkedIn-0f1c2e?style=for-the-badge&logo=linkedin&logoColor=7fb3d3"/></a>
<a href="https://samsanchezcar.github.io"><img src="https://img.shields.io/badge/-Portfolio-0f1c2e?style=for-the-badge&logo=google-chrome&logoColor=7fb3d3"/></a>
<a href="https://github.com/samsanchezcar"><img src="https://img.shields.io/badge/-GitHub-0f1c2e?style=for-the-badge&logo=github&logoColor=7fb3d3"/></a>
<a href="https://orcid.org/0009-0007-7781-9128"><img src="https://img.shields.io/badge/-ORCID-0f1c2e?style=for-the-badge&logo=orcid&logoColor=a6ce39"/></a>
```

---

## Status & Info Badges

```markdown
<!-- Status -->
<img src="https://img.shields.io/badge/Status-Active-2980b9?style=flat-square&labelColor=0f1c2e"/>
<img src="https://img.shields.io/badge/Status-Archived-1a3354?style=flat-square&labelColor=0f1c2e"/>
<img src="https://img.shields.io/badge/Status-In_Progress-1e4d7b?style=flat-square&labelColor=0f1c2e"/>

<!-- Language/Platform — replace logo and text -->
<img src="https://img.shields.io/badge/Language-Python-0f1c2e?style=flat-square&logo=python&logoColor=7fb3d3"/>
<img src="https://img.shields.io/badge/Platform-ROS_2-0f1c2e?style=flat-square&logo=ros&logoColor=7fb3d3"/>
<img src="https://img.shields.io/badge/Platform-ESP32-0f1c2e?style=flat-square&logo=espressif&logoColor=cf6679"/>

<!-- License -->
<img src="https://img.shields.io/badge/License-MIT-1e4d7b?style=flat-square&labelColor=0f1c2e"/>

<!-- Author -->
<img src="https://img.shields.io/badge/Author-samsanchezcar-0f1c2e?style=flat-square&logo=github&logoColor=7fb3d3"/>
```

---

## Tech Stack Icons — skillicons.dev

Always use `theme=dark`. Recommended groupings:

```markdown
<!-- Languages -->
<img src="https://skillicons.dev/icons?i=cpp,python,c,matlab,julia&perline=5&theme=dark"/>

<!-- Web -->
<img src="https://skillicons.dev/icons?i=html,css,js,react,tailwind&perline=5&theme=dark"/>

<!-- Tools (includes arduino) -->
<img src="https://skillicons.dev/icons?i=git,github,vscode,linux,latex,arduino&perline=6&theme=dark"/>

<!-- Design & CAD -->
<img src="https://skillicons.dev/icons?i=autocad,blender,ps,ai,figma&perline=5&theme=dark"/>
```

---

## Specialized Platform Badges

```markdown
<img src="https://img.shields.io/badge/ROS_2-0f1c2e?style=flat-square&logo=ros&logoColor=7fb3d3"/>
<img src="https://img.shields.io/badge/MoveIt_2-0f1c2e?style=flat-square&logo=ros&logoColor=5d8aa8"/>
<img src="https://img.shields.io/badge/ANSYS-0f1c2e?style=flat-square&logo=ansys&logoColor=FFB71B"/>
<img src="https://img.shields.io/badge/Fusion_360-0f1c2e?style=flat-square&logo=autodesk&logoColor=aed6f1"/>
<img src="https://img.shields.io/badge/ESP32-0f1c2e?style=flat-square&logo=espressif&logoColor=cf6679"/>
<img src="https://img.shields.io/badge/FPGA-0f1c2e?style=flat-square&logo=xilinx&logoColor=7fb3d3"/>
<img src="https://img.shields.io/badge/Simulink-0f1c2e?style=flat-square&logo=mathworks&logoColor=aed6f1"/>
<img src="https://img.shields.io/badge/Studio_5000-0f1c2e?style=flat-square&logo=siemens&logoColor=aed6f1"/>
<img src="https://img.shields.io/badge/RobotStudio-0f1c2e?style=flat-square&logoColor=7fb3d3"/>
<img src="https://img.shields.io/badge/RAPID-0f1c2e?style=flat-square&logoColor=5d8aa8"/>
```

---

## GitHub Stats — Consistent Theme

```markdown
<!-- Stats card -->
<img src="https://github-readme-stats.vercel.app/api?username=samsanchezcar&show_icons=true&count_private=true&hide_border=true&bg_color=0f1c2e&title_color=7fb3d3&icon_color=2980b9&text_color=e8f4fd&border_radius=8" height="162"/>

<!-- Top languages -->
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=samsanchezcar&langs_count=8&layout=compact&hide_border=true&bg_color=0f1c2e&title_color=7fb3d3&text_color=e8f4fd&border_radius=8" height="162"/>

<!-- Streak -->
<img src="https://github-readme-streak-stats.herokuapp.com/?user=samsanchezcar&hide_border=true&background=0f1c2e&ring=2980b9&fire=7fb3d3&currStreakLabel=e8f4fd&sideLabels=aed6f1&dates=5d8aa8&stroke=0f1c2e&border_radius=8" width="70%"/>

<!-- Trophies -->
<img src="https://github-profile-trophy.vercel.app/?username=samsanchezcar&theme=algolia&no-frame=true&no-bg=true&column=7&margin-w=8" width="94%"/>

<!-- Activity graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=samsanchezcar&bg_color=0f1c2e&color=7fb3d3&line=1e4d7b&point=2980b9&area=true&area_color=1a3354&hide_border=true&radius=6" width="98%"/>
```

---

## Profile Views Counter

```markdown
<img src="https://komarev.com/ghpvc/?username=samsanchezcar&style=flat-square&color=1e4d7b&label=Profile+Views"/>
```

---

## ASCII Architecture Diagram Template

```
┌─────────────────────────────────────────────┐
│               SYSTEM / PROJECT              │
├──────────────┬──────────────┬───────────────┤
│   Module A   │   Module B   │   Module C    │
│  (describe)  │  (describe)  │  (describe)   │
└──────┬───────┴──────┬───────┴───────┬───────┘
       │              │               │
       ▼              ▼               ▼
   Output A       Output B        Output C
```

---

## Rules

1. **Always** use `style=flat-square` for inline badges, `style=for-the-badge` for section badges
2. **Always** use `theme=dark` for skillicons
3. Background color for all badges: `#0f1c2e`
4. Primary logo/icon color: `#7fb3d3`
5. Secondary logo color: `#5d8aa8` or `#aed6f1`
6. Headers and footers always use the gradient: `0f1c2e → 1a3354 → 1e4d7b → 2980b9`
7. Footer reverses the gradient: `2980b9 → 1e4d7b → 1a3354 → 0f1c2e`
8. Stats, graphs and trophies: always `bg_color=0f1c2e`, `hide_border=true`
9. Typing SVG font: `Fira+Code`, color `7FB3D3`
10. No emojis in section headers — keep them for list items only if needed

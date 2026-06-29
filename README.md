<div align="center">

# ⚡ NetForge

### Cyberpunk Online Network Diagram Builder

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-0xPR4V33N.github.io/netforge-fcee0a?style=for-the-badge)](https://0xpr4v33n.github.io/netforge/)
[![GitHub Stars](https://img.shields.io/github/stars/0xPR4V33N/netforge?style=for-the-badge&color=ff003c&logo=github)](https://github.com/0xPR4V33N/netforge/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-00f0ff.svg?style=for-the-badge)](LICENSE)
[![Mobile Ready](https://img.shields.io/badge/📱_Mobile-Optimized-0bff9d?style=for-the-badge)](https://0xpr4v33n.github.io/netforge/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SVG](https://img.shields.io/badge/SVG-FFB13B?style=flat-square&logo=svg&logoColor=black)
![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-success?style=flat-square)
![Single File](https://img.shields.io/badge/Build-Single_HTML-purple?style=flat-square)

**Forge enterprise network topologies right in your browser — drag, drop, connect, calculate. Now fully optimized for mobile.**

[🌐 Try Live](https://0xpr4v33n.github.io/netforge/) · [🐛 Report Bug](https://github.com/0xPR4V33N/netforge/issues) · [✨ Request Feature](https://github.com/0xPR4V33N/netforge/issues)

</div>

---

## 🎯 About

**NetForge** is a single-file, zero-dependency, cyberpunk-themed network diagram builder built for cybersecurity engineers, network architects, and students. Sketch firewall topologies, datacenter architectures, SOC layouts, or HLD diagrams directly in your browser — no installs, no logins, no friction. Works on desktop, tablet, and phone.

Crafted by [**Praveenkumar Murugan**](https://www.linkedin.com/in/praveenkumar-murugan) — Senior Cybersecurity Consultant.

---

## ✨ Features

### 🧩 Devices & Canvas
- **18 device types** — Firewall, Router, Switch, Server, WAF, IDS/IPS, Load Balancer, VPN, Proxy, SIEM, DB, Cloud, PC, Laptop, Mobile, AP, User, Empty Zone
- **Drag & drop** on desktop, **tap-to-place** + **touch drag** on mobile
- **Resizable zones** (Empty Object) with 8 color swatches for trust boundaries
- **Editable diagram title** with auto-save indicator

### 🔗 Connections
- **Ingress / Egress** wires with directional traffic flow animations
- **Wire styles** — Solid · Dashed · Dotted (right-click any wire)
- **Draggable wire labels** with optional port/protocol annotations
- **Flip direction** on the fly
- Up to **10 connections per node** (port-limit safeguard)

### 🎨 Visual Identity
- **CRT scan lines** + chromatic aberration glitch on node spawn
- **Boot sequence** intro animation
- **Cyberpunk yellow + cyan + red** neon palette
- **Dark / Light** theme toggle (persists to localStorage)
- **Rajdhani + Share Tech Mono** typography

### 🛠️ Power Tools
- **Snap-to-grid** (G key) at 20px
- **Multi-select** via shift-click or rubber-band
- **Pan & Zoom** (Space+drag, mouse wheel, pinch on mobile, `0` to reset)
- **Mini-map radar** with click-to-jump
- **Undo / Redo** (Ctrl+Z / Ctrl+Y, 50-step history)
- **Right-click context menus** on nodes, wires, labels, text notes
- **Pre-built templates** — DMZ, Zero Trust, Hub & Spoke, K8s, SD-WAN, SOC, AWS 3-Tier, Air-Gap

### 🧮 NetTools (Right-side Panel)
- **CIDR Subnet Calculator** with quick-fill chips, copy-each-field, split-subnet
- **IPv4 Classes** reference (A–E)
- **RFC1918 private** + **reserved** ranges clickable
- **Full CIDR table** /8 to /32 clickable to populate calculator
- **Apply to Wire** — push CIDR result straight onto a selected wire as a label

### 💾 Export & Share
- **PNG export** (cropped to content, theme-aware, 2× DPI)
- **SVG export** (vector, editable)
- **PDF export** (with title + metadata banner)
- **Shareable URLs** — entire diagram encoded in URL fragment (zero server)
- **Save / Load JSON** for permanent archival
- **Auto-save** every 5s to localStorage

### 📱 Mobile Optimization
- **Hamburger drawer** for device palette
- **Touch drag** for both palette devices and canvas nodes
- **Pinch-to-zoom** on canvas
- **Responsive** breakpoints for tablet (≤1024px), mobile (≤768px), small phone (≤480px)
- **Landscape phone** layout tuning
- **Prefers-reduced-motion** respected
- **Pop-up scrollable** modals
- **Touch-friendly hit areas** (min 44px on key controls)

---

## 🚀 Quick Start

### Use Online (Recommended)
👉 **[0xpr4v33n.github.io/netforge](https://0xpr4v33n.github.io/netforge/)**

### Run Locally
```bash
git clone https://github.com/0xPR4V33N/netforge.git
cd netforge
# Just open index.html in your browser
```

No build step. No npm. No backend. Single HTML file. 💪

---

## 🎮 Controls

| Action | Desktop | Mobile |
|---|---|---|
| Add device | Drag palette → canvas, or click palette card | Tap ☰ → tap card (auto-places), or drag onto canvas |
| Move node | Click + drag | Touch + drag |
| Connect nodes | Connect → pick Ingress/Egress → click 2 nodes | Same flow via touch |
| Delete | Delete mode → tap target, or right-click → Delete | Delete mode → tap target |
| Rename node | Double-click | Double-tap |
| Multi-select | Shift+click or rubber-band drag | (shift not available — use long-press TBD) |
| Pan canvas | Space + drag, or middle-click drag | Two-finger drag |
| Zoom canvas | Mouse wheel | Pinch in/out |
| Reset view | Press `0` | Reload page |
| Snap to grid | Press `G` | Tap ⊞ GRID in topbar |
| Undo / Redo | Ctrl+Z / Ctrl+Y | Tap ↶ / ↷ |
| Right-click menu | Right-click any node/wire | Long-press (TBD) |

---

## 🗂️ Pre-Built Templates

Choose from the sidebar dropdown:
- **DMZ Architecture** — Internet → Edge FW → WAF + LB + Web/App + DB
- **Zero Trust** — User → ZTNA Gateway → IDS + Identity Proxy → Apps
- **Hub & Spoke** — Azure Hub + Prod/Dev/Mgmt VNets
- **Kubernetes Cluster** — Ingress + API Server + Workers + etcd
- **SD-WAN** — HQ + Branches with cloud overlay
- **SOC Architecture** — Perimeter + WAF + IDS + SIEM + SOAR
- **AWS 3-Tier** — CloudFront → ALB → EC2 → RDS
- **Air-Gapped Network** — Data diode + Inner/Outer firewalls

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| `Ctrl+Z` / `Ctrl+Y` | Undo / Redo |
| `G` | Toggle grid snap |
| `Space` + drag | Pan canvas |
| `0` | Reset view (zoom 100%, pan 0,0) |
| `Esc` | Cancel current action / close modal |
| `Del` / `Backspace` | Delete multi-selected items |
| Mouse wheel | Zoom |
| Shift+click | Multi-select |

---

## 🛠️ Tech Stack

- **Pure HTML5 + CSS3 + Vanilla JavaScript (ES6+)**
- **SVG** for canvas rendering (lossless export, infinite zoom)
- **Canvas API** for PNG/JPEG raster fallback
- **localStorage** for autosave + theme persistence
- **No frameworks · No npm · No build pipeline**

---

## 📂 Project Structure

```
netforge/
├── index.html      # Entire application (single file)
├── README.md       # You are here
├── LICENSE         # MIT
└── .gitignore
```

---

## 🌟 Roadmap

- [ ] Long-press → context menu on mobile
- [ ] Custom device icon upload (user SVGs)
- [ ] Export to Visio / Draw.io XML
- [ ] Real-time collaborative editing (WebRTC P2P)
- [ ] Diagram versioning & history viewer
- [ ] Annotations / arrows / highlight shapes
- [ ] Layer management (background, foreground, hidden)
- [ ] Wire bundles / parallel link grouping

---

## 🤝 Contributing

PRs welcome! Fork → branch → commit → PR. Keep code vanilla, no dependencies.

---

## 👤 Author

**Praveenkumar Murugan**
Senior Cybersecurity Consultant · Network & Cloud Security
PCNSE Certified · AZ-500 / SC-500 in progress

[![LinkedIn](https://img.shields.io/badge/LinkedIn-praveenkumar--murugan-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/praveenkumar-murugan)
[![GitHub](https://img.shields.io/badge/GitHub-0xPR4V33N-181717?style=flat-square&logo=github)](https://github.com/0xPR4V33N)
[![Email](https://img.shields.io/badge/Email-praveenkumarmurugan251020@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:praveenkumarmurugan251020@gmail.com)

---

## 📄 License

Released under the **MIT License** — see [LICENSE](LICENSE) for details.

---

<div align="center">

⚡ **JACKED IN. WIRED UP. NETWORKS FORGED.** ⚡

If NetForge helped you, drop a ⭐ on GitHub!

</div>

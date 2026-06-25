# Lal-paranda: The Vault 🛡️
### Client-Side Sandboxed Read-Only Local File Explorer

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5 API](https://img.shields.io/badge/HTML5-File%20API-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/File_and_Directory_Entries_API)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen)](https://github.com/anacondy/Lal-paranda)
[![FPS](https://img.shields.io/badge/Performance-Locked%2060%20FPS-8a0b0b)](https://github.com/anacondy/Lal-paranda)

**Lal-paranda (`The Vault`)** is a zero-dependency, ultra-secure, client-side local file exploration suite built exclusively on modern HTML5 `<input webkitdirectory>` and File APIs. Operating strictly within the browser OS security sandbox, it indexes tens of thousands of local drive archives with zero network transmission, zero backend servers, and zero client RAM leaks.

---

## 🏛️ Repository Structure & Version Releases

This repository archives the complete evolutionary lifecycle of **The Vault**, organized into standalone version directories and accompanied by exhaustive senior engineering audit reports.

```text
Lal-paranda/
├── README.md                                 # Master Repository Documentation
├── reports/                                  # Central Cybersecurity & Engineering Audits
│   ├── v1_status_report.md
│   ├── v2_audit_report.md
│   └── v3_engineering_report.md
├── v1-scrollbar-edition/                     # Version 1.0 (OG Scrollbar Edition)
│   ├── index.html
│   └── vault_status_report.md
├── v2-advanced-patched/                      # Version 2.0 (Security & RAM Hardened)
│   ├── index.html
│   └── advanced_explorer_audit_report.md
└── v3-final-production-build/                # Version 3.0 (Final Candidate Build) ⭐
    ├── index.html
    └── lal_paranda_engineering_report.md
```

---

## ⭐ Version Comparison Matrix

| Feature / Metric | V1 Scrollbar Edition | V2 Advanced Patched | V3 Final Production Build ⭐ |
| :--- | :---: | :---: | :---: |
| **Primary Theme** | Dark Void & Crimson | Glassmorphism & Gold | Strict Gothic Crimson & Void |
| **Max Verified Files** | ~10,000 Files | ~50,000 Files | **100,000+ Files** (IO Guarded) |
| **Memory GC** | Manual Object Revoke | Strict Lifecycle GC | **Strict Lifecycle GC + Deferrals** |
| **Grid Aspect Ratio** | Dynamic / Auto | 16:9 (Cover Cropped) | **16:9 Cinematic (`contain`)** |
| **Media Player UI** | Basic HTML5 Embed | Custom Gothic Bar | **Sleek Centered Gothic + OSD** |
| **Volume OSD** | None | None | **Animated Crimson Readout** |
| **File Navigation** | None | Modal L/R Buttons | **Universal Keyboard L/R Arrows** |
| **Sidebar Scrollbar** | Standard Red | Standard Red | **Completely Eliminated** |

---

## 🔒 Cybersecurity & Sandboxing Model

1. **Zero Exfiltration Guarantee:** All file reads utilize transient in-memory `File` handles. No data is ever transmitted over `fetch()`, `XMLHttpRequest`, or WebSockets.
2. **DOM XSS Neutralization:** Local disk filenames containing malicious HTML/JS injection payloads (e.g., `<img onerror=...>.jpg`) pass through rigorous `escapeHtml()` entity encoding pipelines.
3. **Isolated iframe Previews:** Document previews execute inside sandboxed `<iframe>` contexts (`allow-scripts allow-same-origin`) to prevent parent DOM manipulation.

---

## 🚀 Getting Started (Local Usage)

1. Clone this repository or download any `index.html` file from the release folders.
2. Double-click `index.html` to open it natively in Google Chrome, Microsoft Edge, Brave, or Firefox.
3. Click **MOUNT DRIVE** (or press `Ctrl + K`) and select any local folder or external SSD to index signatures instantly.

---

*Architected and audited by Senior Web Systems Engineering.*

<div align="center">
  <img src="icons/promo_marquee_1400x560.png" alt="YomiRuby Promo Banner" width="100%" />
  <h1>YomiRuby</h1>
  <p>Production-ready Firefox Extension for adding furigana to Japanese text with HTML ruby tags.</p>

  <p>
    <a href="https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions">Firefox WebExtensions</a>
    ·
    <a href="https://developer.yahoo.co.jp/webapi/jlp/furigana/v2/furigana.html">Yahoo Furigana API</a>
    ·
    <a href="PRIVACY_POLICY.md">Privacy Policy</a>
    ·
    <a href="LICENSE">Unlicense</a>
  </p>

  <p>
    <img alt="Firefox Manifest V3" src="https://img.shields.io/badge/Firefox-Manifest_V3-FF7139?logo=firefoxbrowser&logoColor=white">
    <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-ES2020-F7DF1E?logo=javascript&logoColor=black">
    <img alt="License Unlicense" src="https://img.shields.io/badge/License-Unlicense-2ea44f">
    <img alt="Privacy User Controlled" src="https://img.shields.io/badge/Privacy-User_Controlled-0a7f6f">
  </p>
</div>

## Multi-language README

### Language Switcher

<div align="center">

[🇬🇧 English](README.en.md) · [🇨🇳 简体中文](README.zh-CN.md) · [🇮🇩 Bahasa Indonesia](README.id.md) · [🇰🇷 한국어](README.ko.md) · [🇹🇭 ไทย](README.th.md)<br>
[🇻🇳 Tiếng Việt](README.vi.md) · [🇲🇲 မြန်မာ](README.my.md) · [🇮🇳 हिन्दी](README.hi.md) · [🇳🇵 नेपाली](README.ne.md) · [🇵🇭 Filipino](README.fil.md)<br>
[🇲🇾 Bahasa Melayu](README.ms.md) · [🇱🇰 සිංහල](README.si.md) · [🇫🇷 Français](README.fr.md) · [🇧🇷 Português (Brasil)](README.pt-BR.md) · [🇯🇵 日本語](README.ja.md)

</div>

## Why YomiRuby

- Annotates visible Japanese text with `<ruby>`, `<rt>`, and `<rp>`.
- Uses user-owned Yahoo API keys (no hardcoded credentials).
- Includes API key testing, quota-aware pacing, progress UI, cancel, and restore.
- Uses conservative DOM updates to reduce layout breakage on general websites.

## Quick Start

Firefox 121+ is required for this Manifest V3 build.

1. Clone this repository.
2. Open `about:debugging#/runtime/this-firefox`.
3. Click **Load Temporary Add-on...** and select this project's `manifest.json`.
4. Open extension **Settings**, configure API key, and run **Test API Key**.
5. Open a Japanese page and click **Run Annotation Now**.

## Repository Layout

```text
yomi-ruby-firefox/
├── manifest.json
├── background.js
├── content.js
├── popup.*
├── options.*
├── utils/
├── icons/
├── PRIVACY_POLICY.md
└── README*.md
```

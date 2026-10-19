# Awesome AI Craft [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome software products, applications, and desktop suites created through AI-driven reverse engineering, clean-room reimplementation, and agentic cloning—inspired by the viral **ArtCraft** suite by `storytold`, **REA** (Reverse Engineer Anything), and the new wave of open-source software clones.

Inspired by [awesome-javascript](https://github.com/sorrycc/awesome-javascript).

---

## Contents

- [Awesome AI Craft](#awesome-ai-craft)
  - [The ArtCraft Suite (`storytold`)](#the-artcraft-suite-storytold)
    - [Creative & Media Suite (Adobe Alternatives)](#creative--media-suite-adobe-alternatives)
    - [Office & Productivity Suite (Microsoft Alternatives)](#office--productivity-suite-microsoft-alternatives)
    - [Audio & CAD Systems](#audio--cad-systems)
    - [Core Engine & Framework](#core-engine--framework)
  - [Design & Creative Clones](#design--creative-clones)
    - [Photoshop & Raster Editors](#photoshop--raster-editors)
    - [Figma & Collaborative UI](#figma--collaborative-ui)
    - [Canva & Visual Publishing](#canva--visual-publishing)
    - [Lightroom & RAW Processors](#lightroom--raw-processors)
    - [Video Editors & Timeline Studios](#video-editors--timeline-studios)
  - [AI Service Clean-Room Clones](#ai-service-clean-room-clones)
    - [Midjourney & DALL-E UI Clones](#midjourney--dall-e-ui-clones)
    - [Sora & Runway Video Clones](#sora--runway-video-clones)
    - [Suno & Udio Music Clones](#suno--udio-music-clones)
    - [ElevenLabs & Voice Clones](#elevenlabs--voice-clones)
    - [Topaz Photo AI & Upscaler Clones](#topaz-photo-ai--upscaler-clones)
    - [Remove.bg & Cutout Clones](#removebg--cutout-clones)
  - [Developer Tools & IDE Clones](#developer-tools--ide-clones)
    - [Cursor & AI Code Editors](#cursor--ai-code-editors)
    - [v0 & AI Frontend Builders](#v0--ai-frontend-builders)
    - [Postman & API Clients](#postman--api-clients)
    - [Retool & Low-Code Engines](#retool--low-code-engines)
    - [Zapier & Workflow Automation](#zapier--workflow-automation)
    - [Firebase & Backend Clones](#firebase--backend-clones)
  - [Productivity & Workplace Clones](#productivity--workplace-clones)
    - [Notion & Knowledge Workspaces](#notion--knowledge-workspaces)
    - [Linear & Issue Trackers](#linear--issue-trackers)
    - [Slack & Team Communication](#slack--team-communication)
    - [Airtable & Low-Code Databases](#airtable--low-code-databases)
    - [Loom & Video Messaging](#loom--video-messaging)
    - [Typeform & Interactive Forms](#typeform--interactive-forms)
    - [1Password & Vault Managers](#1password--vault-managers)
  - [Reverse-Engineering & AI Decompilation Tools](#reverse-engineering--ai-decompilation-tools)
    - [Agentic Reverse-Engineering Bridges](#agentic-reverse-engineering-bridges)
    - [AI Decompiler & Disassembler Plugins](#ai-decompiler--disassembler-plugins)
    - [Binary Analysis & APK Reconstructors](#binary-analysis--apk-reconstructors)
- [Clean-Room Methodology](#clean-room-methodology)
- [Community & Discussions](#community--discussions)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

----

## The ArtCraft Suite (`storytold`)

*The viral family of desktop applications written entirely from scratch in pure Rust by Brandon Thomas and AI coding agents (Claude Opus), delivering zero-dependency, clean-room reimplementations of commercial creative and office standards with native MCP and CLI control.*

### Creative & Media Suite (Adobe Alternatives)
*Pure-Rust replacements for proprietary Adobe Creative Cloud desktop applications.*

* [photocraft](https://github.com/storytold/photocraft) - Clean-room reimplementation of **Adobe Photoshop** written from scratch in pure Rust, featuring multi-layer editing, PSD file parsing, non-destructive adjustment layers, and native AI agent scripting.
* [vectorcraft](https://github.com/storytold/vectorcraft) - Pure-Rust clean-room replacement for **Adobe Illustrator**, featuring Bézier path manipulation, SVG/AI import/export, typography layout, and boolean shape operations.
* [filmcraft](https://github.com/storytold/filmcraft) - Clean-room non-linear video editor reimplementing **Adobe Premiere Pro** in Rust, with multi-track timeline editing, audio waveform sync, color correction, and hardware-accelerated rendering.
* [lightcraft](https://github.com/storytold/lightcraft) - Non-destructive RAW photo development and cataloging tool built in Rust as a clean-room alternative to **Adobe Lightroom**.
* [effectcraft](https://github.com/storytold/effectcraft) - Digital visual effects, compositing, and motion graphics suite written in Rust as an open-source alternative to **Adobe After Effects**.
* [designcraft](https://github.com/storytold/designcraft) - Page design and typography desktop publisher built in pure Rust as a clean-room alternative to **Adobe InDesign**.
* [pdfcraft](https://github.com/storytold/pdfcraft) - High-performance PDF reader, annotator, form filler, and page organizer replacing **Adobe Acrobat Pro**.

### Office & Productivity Suite (Microsoft Alternatives)
*Pure-Rust desktop replacements for Microsoft Office desktop software.*

* [wordcraft](https://github.com/storytold/wordcraft) - Clean-room word processor written in pure Rust supporting DOCX and ODT formats, designed as a fast native alternative to **Microsoft Word**.
* [gridcraft](https://github.com/storytold/gridcraft) - Spreadsheet application written from scratch in Rust with formula calculation engines and XLSX import/export, replacing **Microsoft Excel**.
* [deckcraft](https://github.com/storytold/deckcraft) - Native presentation software written in Rust for crafting, styling, and presenting slide decks, replacing **Microsoft PowerPoint**.

### Audio & CAD Systems
*Specialized engineering and audio production tools.*

* [soundcraft](https://github.com/storytold/soundcraft) - Digital audio workstation (DAW) and clean-room reimplementation of **Avid Pro Tools** and **Adobe Audition** in Rust for multi-track audio mixing and mastering.
* [cadcraft](https://github.com/storytold/cadcraft) - Computer-aided design and drafting application built in Rust as an open alternative to **Autodesk AutoCAD**.

### Core Engine & Framework
*Underlying engine architectures and agent bridges.*

* [artcraft](https://github.com/storytold/artcraft) - The core intentional crafting engine and unified UI framework that powers the entire Craft suite, with native Model Context Protocol (MCP) servers and JSON-RPC automation channels.

----

## Design & Creative Clones

### Photoshop & Raster Editors
*Clean-room and reverse-engineered raster graphics editors emulating commercial standards.*

* [Photopea](https://www.photopea.com/) - High-fidelity clean-room in-browser reimplementation of **Adobe Photoshop**, supporting native PSD, XCF, Sketch, and XD formats.
* [photocraft](https://github.com/storytold/photocraft) - Pure-Rust local-first desktop **Photoshop** clone with layer hierarchy, masking, and direct AI agent integration.
* [Pencil.js](https://github.com/pencil-js/pencil.js) - Lightweight object-oriented 2D drawing library for programmatic recreation of raster canvas interactions.

### Figma & Collaborative UI
*Open-source and agentic clean-room reimplementations of collaborative vector design tools.*

* [OpenPencil](https://github.com/open-pencil/open-pencil) - AI-native open-source design editor built with Vue, Skia, and WebGPU as a drop-in clean-room replacement for **Figma**.
* [Penpot](https://github.com/penpot/penpot) - Open-source, web-based collaborative design and prototyping platform built on open web standards (SVG), created as an unencumbered **Figma** alternative.
* [quickmock](https://github.com/Lemoncode/quickmock) - Free, open-source wireframing tool for rapid low-fidelity mockup creation on an infinite whiteboard canvas.

### Canva & Visual Publishing
*Template-driven visual layout tools designed to replicate Canva workflows.*

* [yft-design](https://github.com/more-strive/yft-design) - Open-source **Canva** clone built with Vue 3 and Fabric.js, supporting drag-and-drop graphic elements, template exports, and rich text formatting.
* [Polotno Studio](https://github.com/polotno-project/polotno-studio) - Standalone web-based graphic editor and SDK designed as an embeddable, customizable **Canva** alternative.
* [HyCanvas](https://github.com/hyscaler/HyCanvas) - Self-hostable, AI-native design canvas and Canva replacement supporting bring-your-own-key generative models.
* [Tela](https://github.com/heyimjames/tela) - Fast, local-first in-browser design canvas for ad and social media visual creation with zero sign-up friction.

### Lightroom & RAW Processors
*Non-destructive photo processors and image lab alternatives.*

* [lightcraft](https://github.com/storytold/lightcraft) - Rust-based clean-room reimplementation of **Adobe Lightroom** with non-destructive exposure, tone curves, and batch processing.
* [open-photo-ai](https://github.com/vegidio/open-photo-ai) - Open-source desktop alternative to **Topaz Photo AI** for local-first sharpening, denoising, and resolution scaling.
* [Darktable](https://github.com/darktable-org/darktable) - Open-source photography workflow application and non-destructive raw developer managing digital negatives.

### Video Editors & Timeline Studios
*Multi-track non-linear editing software and timeline runners.*

* [filmcraft](https://github.com/storytold/filmcraft) - Clean-room Rust **Adobe Premiere Pro** clone featuring hardware-accelerated video rendering and audio synchronization.
* [OpenReel](https://github.com/openreel/openreel) - Open-source, local-first timeline editor where humans and AI agents co-edit multi-track video timelines.
* [Cap](https://github.com/CapSoftware/Cap) - Open-source, instant screen-recording and video sharing alternative to **Loom**.

----

## AI Service Clean-Room Clones

### Midjourney & DALL-E UI Clones
*Open-source interfaces recreating the ease and aesthetic defaults of proprietary image generators.*

* [Fooocus](https://github.com/lllyasviel/Fooocus) - Clean-room reimplementation of the **Midjourney** user experience, automating prompt expansion, negative prompts, and sampling optimizations for Stable Diffusion/SDXL.
* [InvokeAI](https://github.com/invoke-ai/InvokeAI) - Professional creative studio providing unified canvas inpainting, outpainting, and board management rivaling commercial suites.
* [AUTOMATIC1111 WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) - Feature-packed web interface standardizing diffusion workflows across the open-source community.

### Sora & Runway Video Clones
*Open-weights video diffusion pipelines replicating closed commercial video generators.*

* [Open-Sora](https://github.com/hpcaitech/Open-Sora) - Open-source initiative reproducing **OpenAI Sora**'s video generation pipeline, including training recipes and inference code.
* [CogVideoX](https://github.com/THUDM/CogVideo) - High-coherence open video generation model family by Tsinghua/Zhipu AI rivaling commercial video generators.
* [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) - Open-weights text-to-video foundation model with cinematic motion matching **Runway Gen-3**.

### Suno & Udio Music Clones
*Open-weights and local-first song generation models matching proprietary AI music services.*

* [ACE-Step](https://github.com/ace-step/ACE-Step) - Open-source music foundation model generating full broadcast-ready songs with vocals in 50+ languages on <4GB VRAM, built as an open alternative to **Suno** and **Udio**.
* [YuE](https://github.com/multimodal-art-projection/YuE) - Open-source foundation model for full-length structured song synthesis complete with singing vocals and arrangements.
* [DiffRhythm](https://github.com/ASLP-lab/DiffRhythm) - Fast latent diffusion architecture generating cohesive multi-minute songs directly from structured lyric sheets.

### ElevenLabs & Voice Clones
*Zero-shot voice cloning and emotional speech synthesis mimicking proprietary voice APIs.*

* [F5-TTS](https://github.com/SWivid/F5-TTS) - Non-autoregressive speech synthesis using flow matching with DiT; reproduces **ElevenLabs** zero-shot cloning without alignment.
* [OpenVoice](https://github.com/myshell-ai/OpenVoice) - Instant tone-color cloning and flexible timbre transfer reproducing closed voice-matching services.
* [ChatTTS](https://github.com/2noise/ChatTTS) - Conversational speech model generating spontaneous human fillers, laughter, and natural cadence.

### Topaz Photo AI & Upscaler Clones
*Open-source alternatives to commercial AI enhancers and neural upscalers.*

* [Upscayl](https://github.com/upscayl/upscayl) - Free, open-source desktop image upscaler built with Vulkan and Real-ESRGAN, serving as a zero-cost alternative to **Topaz Gigapixel AI**.
* [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) - Practical blind super-resolution engine for general photos, anime art, and compressed video.
* [CodeFormer](https://github.com/sczhou/CodeFormer) - Robust facial restoration algorithm recovering extreme real-world degradation with controllable fidelity.

### Remove.bg & Cutout Clones
*Local-first, unmetered replacements for pay-per-image background cutout services.*

* [rembg](https://github.com/danielgatis/rembg) - Python library and CLI delivering instant background removal using U2-Net and BiRefNet as an open drop-in replacement for **remove.bg**.
* [BiRefNet](https://github.com/ZhengPeng7/BiRefNet) - State-of-the-art bilateral reference network for ultra-high-resolution matting of hair, glass, and translucent edges.
* [background-removal-js](https://github.com/imgly/background-removal-js) - Client-side in-browser background removal via WebAssembly and ONNX Runtime with zero server dependencies.

----

## Developer Tools & IDE Clones

### Cursor & AI Code Editors
*Open-source and agentic clean-room reimplementations of Cursor and proprietary AI-first IDEs.*

* [Void](https://github.com/voideditor/void) - Open-source, clean-room **Cursor** alternative built on VS Code, allowing developers to retain full control over models and API keys.
* [PearAI](https://github.com/trypear/pearai) - Open-source AI code editor fork providing conversational inline refactoring and codebase indexing.
* [Continue](https://github.com/continuedev/continue) - Open-source autopilot extension bringing **Cursor**-style inline code completion and chat to any IDE.
* [Roo Code](https://github.com/RooVetGit/Roo-Code) - Autonomous AI coding agent extension for VS Code with dual architect/code modes and MCP server support.
* [Melty](https://github.com/meltylabs/melty) - Open-source AI code editor designed to track changes from terminal to PR with self-improving context.

### v0 & AI Frontend Builders
*Open-source generative UI builders turning prompts into interactive web components.*

* [openv0](https://github.com/raunofreiberg/openv0) - Open-source clean-room clone of **Vercel v0**, generating React, Tailwind CSS, and HTML components from text prompts.
* [screenshot-to-code](https://github.com/abi/screenshot-to-code) - Clean-room visual reverse-engineering tool converting screenshots and mockup designs into production React, Vue, and Tailwind code.

### Postman & API Clients
*Lightweight, local-first alternatives to cloud-heavy API testing suites.*

* [Hoppscotch](https://github.com/hoppscotch/hoppscotch) - Fast, privacy-first open-source API development ecosystem serving as a clean-room alternative to **Postman**.
* [Bruno](https://github.com/usebruno/bruno) - Fast, git-friendly desktop API client storing collections directly in plain text folders.

### Retool & Low-Code Engines
*Open-source platforms for building internal tools and dashboards.*

* [Appsmith](https://github.com/appsmithorg/appsmith) - Leading open-source clean-room alternative to **Retool** for assembling internal admin panels and database portals.
* [ToolJet](https://github.com/ToolJet/ToolJet) - Extensible open-source low-code framework connecting to databases and API backends.

### Zapier & Workflow Automation
*Self-hostable workflow orchestration engines replacing proprietary SaaS integrators.*

* [n8n](https://github.com/n8n-io/n8n) - Fair-code workflow automation tool with extensive multi-system nodes, serving as a powerful alternative to **Zapier** and **Make**.
* [Activepieces](https://github.com/activepieces/activepieces) - Open-source business automation platform designed for self-hosting with zero subscription fees.

### Firebase & Backend Clones
*All-in-one open-source backends replacing proprietary mobile/web platforms.*

* [Appwrite](https://github.com/appwrite/appwrite) - End-to-end backend server for web and mobile developers providing auth, database, storage, and functions, replacing **Firebase**.
* [PocketBase](https://github.com/pocketbase/pocketbase) - Open-source Go backend in a single file with embedded SQLite, realtime subscriptions, and auth.

----

## Productivity & Workplace Clones

### Notion & Knowledge Workspaces
*Modular blocks, linked databases, and local-first document suites.*

* [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) - Open-source, privacy-first **Notion** alternative written in Flutter and Rust with offline-first data synchronization.
* [AFFiNE](https://github.com/toeverything/AFFiNE) - Next-generation open-source workspace uniting whiteboard canvas, structured docs, and linked databases.
* [Docmost](https://github.com/docmost/docmost) - Open-source collaborative wiki and documentation software with real-time multi-user editing.

### Linear & Issue Trackers
*Keyboard-driven, high-speed project management tools.*

* [Plane](https://github.com/makeplane/plane) - Open-source project tracking and issue management tool built as a clean-room alternative to **Linear** and **Jira**.

### Slack & Team Communication
*Real-time workplace chat and messaging systems.*

* [Mattermost](https://github.com/mattermost/mattermost) - Self-hosted secure collaboration platform serving as a production-grade **Slack** alternative.
* [Zulip](https://github.com/zulip/zulip) - Real-time team chat with unique topic-based threading for organized, searchable conversation streams.

### Airtable & Low-Code Databases
*Relational database spreadsheets with forms, kanbans, and API access.*

* [NocoDB](https://github.com/nocodb/nocodb) - Open-source smart spreadsheet that turns any existing SQL database into an interactive **Airtable** clone.
* [Teable](https://github.com/teableio/teable) - Real-time relational database spreadsheet built on Postgres with ultra-fast performance.
* [Baserow](https://github.com/bram2w/baserow) - Open-source no-code database tool giving teams full data ownership.

### Loom & Video Messaging
*Asynchronous screen-and-camera recording tools.*

* [Cap](https://github.com/CapSoftware/Cap) - Lightweight open-source desktop screen recorder and sharing workbench replacing **Loom**.
* [OpenLoom](https://github.com/topics/loom-clone) - Collection of open-source screen recording extensions and web apps capturing camera and tab video.

### Typeform & Interactive Forms
*Conversational, one-question-at-a-time form builders.*

* [Formbricks](https://github.com/formbricks/formbricks) - Open-source survey suite and conversational form builder replacing **Typeform**.
* [HeyForm](https://github.com/heyform/heyform) - Open-source conversational form builder with rich input widgets and analytics.

### 1Password & Vault Managers
*Encrypted password managers and zero-knowledge secret stores.*

* [Bitwarden](https://github.com/bitwarden/server) - Open-source cross-platform password manager protecting credentials across devices, replacing **1Password**.
* [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - Lightweight, pure-Rust server implementation compatible with Bitwarden client apps.

----

## Reverse-Engineering & AI Decompilation Tools

*Frameworks, MCP bridges, and AI-assisted reverse-engineering utilities that power the clean-room software creation movement.*

### Agentic Reverse-Engineering Bridges
*Tools that connect AI coding agents (Claude Code, Cursor, Codex) directly to disassembly workflows.*

* [morluto/rea (Reverse Engineer Anything)](https://github.com/morluto/rea) - The viral open-source CLI and Model Context Protocol (MCP) server that empowers AI agents to inspect native binaries, Electron `.asar` archives, JavaScript bundles, and .NET assemblies through structured decompile-understand-recreate loops.
* [GhidraAssist](https://github.com/symgraph/GhidrAssist) - Advanced AI extension for NSA's Ghidra featuring a Graph-RAG knowledge engine and automated function summarization.
* [Gepetto](https://github.com/JusticeRage/Gepetto) - Python plugin integrating LLMs directly into IDA Pro to explain decompiled assembly and suggest semantic variable and function names.

### AI Decompiler & Disassembler Plugins
*Integrations enhancing traditional reverse-engineering suites with generative reasoning.*

* [r2ai](https://github.com/radareorg/r2ai) - AI assistant plugin for the **radare2** and **cutter** reverse-engineering frameworks for decompilation assistance.
* [JADX](https://github.com/skylot/jadx) - Command line and GUI tool to produce Java source code from Android APK and DEX files, frequently paired with AI scripts for clean-room mobile recreation.

### Binary Analysis & APK Reconstructors
*Techniques and tools for extracting schemas, protocols, and data specs.*

* [mitmproxy](https://github.com/mitmproxy/mitmproxy) - Interactive TLS-capable intercepting HTTP proxy for reverse-engineering proprietary client-server protocols and APIs.
* [Frida](https://github.com/frida/frida) - Dynamic instrumentation toolkit for developers, reverse engineers, and security researchers to inspect internal function calls at runtime.

----

## Clean-Room Methodology

How AI agents enable clean-room software recreation:

```
┌───────────────────────────┐         ┌──────────────────────────┐
│  Target Proprietary App   │         │    Public Specifications  │
│  (UI / UX / Formats)      │         │    (PSD, OOXML, SVG, API)│
└─────────────┬─────────────┘         └─────────────┬────────────┘
              │                                     │
              ▼                                     ▼
      ┌──────────────────────────────────────────────────┐
      │  Reverse-Engineering Bridge (e.g. morluto/rea)  │
      │  - Extracts data schemas, UI hierarchies, formats│
      │  - Traces protocols, shortcuts, and capabilities │
      └───────────────────────┬──────────────────────────┘
                              │
                              ▼ [High-level Behavioral Spec]
      ┌──────────────────────────────────────────────────┐
      │     Clean-Room Coding Agent (Claude / Codex)     │
      │  - Writes 100% fresh, original code (e.g. Rust)   │
      │  - Never incorporates original decompiled sources│
      │  - Equips native MCP / CLI / JSON-RPC interfaces │
      └───────────────────────┬──────────────────────────┘
                              │
                              ▼
      ┌──────────────────────────────────────────────────┐
      │          New Open-Source Product                 │
      │   (PhotoCraft, VectorCraft, OpenPencil, Void)    │
      └──────────────────────────────────────────────────┘
```

1. **Specification Extraction**: The analyst uses tools like `rea`, `mitmproxy`, or public RFCs to document interface behaviors, file formats, and features.
2. **Clean-Room Barrier**: The AI coding agent is tasked with writing fresh, unencumbered code (e.g., in Rust or TypeScript) strictly conforming to the behavioral specification.
3. **Agent-Native Architecture**: Modern clones build native Model Context Protocol (MCP) servers and JSON control layers directly into the app so AI agents can control the software programmatically.

----

## Community & Discussions

* [The Storytold ArtCraft Announcement](https://github.com/storytold) - Home of the pure-Rust ArtCraft ecosystem and creative suite.
* [Hacker News & Reddit Discussions on Clean-Room AI](https://news.ycombinator.com) - Debate and analysis on whether LLM-driven clean-room implementations qualify under traditional IP laws.
* [Reddit r/ReverseEngineering](https://www.reddit.com/r/ReverseEngineering/) - Technical discussions regarding binary analysis, Ghidra, IDA Pro, and machine-assisted decompilation.

----

## Other Awesome Lists

* [awesome-reverse-engineering](https://github.com/michalmalik/awesome-reversing) - Curated list of reverse engineering resources, tools, and training materials.
* [awesome-open-source-alternatives](https://github.com/cloudcommunity/Cloud-Computing-Awesome-List) - Open-source alternatives to commercial software.
* [awesome-mcp](https://github.com/punkpeye/awesome-mcp-servers) - Curated list of Model Context Protocol servers and developer bridges.

----

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

If you know of an awesome project created via reverse engineering, clean-room reimplementation, or AI-assisted cloning:

1. Fork this repository.
2. Create a new branch: `git checkout -b add-my-project`.
3. Add your entry under the appropriate section using the standard format:
   `* [ProjectName](https://url) - Brief description specifying what proprietary software it was cloned or reverse-engineered from.*`
4. Commit your changes: `git commit -m "Add ProjectName"`.
5. Push to the branch: `git push origin add-my-project`.
6. Submit a pull request.

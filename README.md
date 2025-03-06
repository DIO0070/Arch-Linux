# ArchOS Steam Edition 🎮

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?logo=arch-linux&logoColor=fff)

Una distribución personalizada de Arch Linux que emula la experiencia de SteamOS. **No oficial** y sin afiliación con Valve.

---

## Características ✨
- Autoinicio en Steam Big Picture Mode
- Entorno KDE Plasma personalizado (similar a SteamOS 3)
- Optimizaciones para gaming:
  - Gamescope (compositor FSR/VRS)
  - Btrfs con compresión
  - Drivers Vulkan y 32-bit
- Configuraciones listas para consola/TV

---

## Instalación ⚙️

### Requisitos
- CPU x86_64
- 4 GB RAM (recomendado 8+ GB)
- GPU compatible con Vulkan (AMD/NVIDIA/Intel)
- Conexión a internet

### Pasos Base
1. Instalar Arch Linux ([Guía Oficial](https://wiki.archlinux.org/title/Installation_guide)).
2. Ejecutar:
```bash
# Paquetes esenciales
sudo pacman -S --needed git xorg plasma-desktop steam vulkan-radeon lib32-vulkan-radeon

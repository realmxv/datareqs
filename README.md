# datacontent

This repository contains central data files used in the Volkner Mobil app system.  
It is designed to provide consistent and structured data access for apps and services related to vehicle configuration, status, and UI assets.

---

## 📁 Repository Structure

- `configuration.json`  
  Configuration data for multiple vehicles including features, states, and standard components.

- `assets/icons/`  
  This folder contains app icons and symbols used in the user interface (e.g. tank icons, battery symbols, hydraulic status indicators).  
  Files are typically in `.svg` or `.png` format.

- `service_location.json`  
  Contains address and GPS coordinates of the official Volkner Mobil GmbH service centers.  
  This data is used by the app to detect whether the vehicle is currently at the service facility, for example to enable diagnostic functions or restricted service modes.

- `README.md`  
  Description and documentation for the data repository.

---

## 🔧 Usage

The files in this repository can be accessed by:
- The Volkner Mobil iOS/Android app
- The Linux-based in-vehicle control system
- Web-based tools for diagnostics and remote control

They are intended for **read-only** usage in apps and will be updated automatically via sync scripts.

---

## 🌐 Access

This repository is public but contains no personal or sensitive data.  
All files are configuration-only and safe to distribute with production systems.

---

Feel free to open an issue or make suggestions for structure improvements.

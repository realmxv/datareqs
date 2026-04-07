# datareqs

Zentrale Daten-Dateien fuer das Volkner Mobil App-System — Standortdaten und Logos.

---

## Repository Structure

- `service_location.json`
    Adresse und GPS-Koordinaten der offiziellen Volkner Mobil GmbH Servicecenter. Die App nutzt diese Daten, um zu erkennen, ob sich das Fahrzeug am Servicestandort befindet.

- `assets/icons/`
    Logo-Dateien fuer die App (z.B. `volkner_logo_chrome.png`, `volkner_v.png`).

- `assets/LICENSE`
    Lizenzbedingungen fuer die Nutzung der Volkner Mobil Logos und Grafiken. Siehe [Asset License](assets/LICENSE).

---

## Usage

The files in this repository can be accessed by:

- The Volkner Mobil iOS/Android app
- The Linux-based in-vehicle control system
- Web-based tools for diagnostics and remote control

They are intended for **read-only** usage in apps and will be updated automatically via sync scripts.

---

## Asset License

Die Logos und grafischen Assets im `assets/`-Ordner sind Eigentum der Volkner Mobil GmbH und unterliegen einer eigenen Lizenz. Im Wesentlichen gilt:

- Nutzung ausschliesslich fuer Werbe- und Promotionzwecke im Auftrag der Volkner Mobil GmbH.
- Die Assets muessen in ihrer originalen, unveraenderten Optik verwendet werden. Aenderungen an Farben, Proportionen oder Komposition sind untersagt.
- Weiterverbreitung oder Nutzung fuer Drittanbieter ist ohne schriftliche Genehmigung nicht gestattet.

Vollstaendige Lizenzbedingungen: [assets/LICENSE](assets/LICENSE)

---

## Access

This repository is public but contains no personal or sensitive data.
All files are configuration-only and safe to distribute with production systems.

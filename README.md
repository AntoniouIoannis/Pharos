# Pharos
**Pharos** είναι μία FlutterFlow εφαρμογή που λειτουργεί σαν φάρος. Εντοπίζει άμεσα την τοποθεσία σου.

# 🌐 Pharos — Safe Location & Panic App

**Pharos** είναι μία FlutterFlow εφαρμογή που λειτουργεί σαν φάρος:
- 📍 Εντοπίζει άμεσα την τοποθεσία σου (GPS ή IP fallback).
- ☁️ Δείχνει τις τρέχουσες καιρικές συνθήκες (OpenWeatherMap).
- 🚨 Panic button για άμεση κλήση στο **112** και κοινοποίηση συντεταγμένων.
- 🎙️ Voice component (ηχογράφηση/μικρόφωνο) για να ακουστεί ο χρήστης σε περίπτωση ανάγκης.

---

## ✨ Features
- **FAB button** → Λήψη τοποθεσίας.
- **Location page** → Συντεταγμένες + share/copy.
- **Weather widget** → OpenWeatherMap integration (τρέχουσα θέση).
- **Panic mode**:
  - Άμεση κλήση στο `112`.
  - Αυτόματο share συντεταγμένων (SMS/WhatsApp).
  - Ενεργοποίηση μικροφώνου / ηχογράφηση (όπου υποστηρίζεται).

---

## 🛠️ Tech Stack
- [FlutterFlow](https://flutterflow.io/) (no-code/low-code)
- **APIs**:
  - [IPGeolocation](https://ipgeolocation.io/) → fallback τοποθεσία
  - [OpenWeatherMap](https://openweathermap.org/api) → καιρός
- GitHub repo για version control & documentation

---

## 📌 Roadmap
- **v0.1** — Εντοπισμός θέσης + Panic (112 call).
- **v0.2** — Καιρός μέσω OpenWeatherMap.
- **v0.3** — Share location σε SMS/WhatsApp.
- **v0.4** — 🎙️ Voice Component: ηχογράφηση / μικρόφωνο με panic.
- **v1.0** — Σταθερή έκδοση, release σε Google Play & App Store.

---

## 📸 Screenshots (to be added)
- Home screen με FAB
- Location screen με coordinates
- Panic modal

---

## ⚠️ Σημειώσεις
- Σε ορισμένα κινητά **ηχογράφηση κατά τη διάρκεια κλήσης** δεν επιτρέπεται για λόγους ασφαλείας.  
- Η εφαρμογή ενεργοποιεί το μικρόφωνο *πριν ή παράλληλα* με την κλήση, ώστε να καταγράφεται η φωνή ή να ακούγεται σε real-time backend.

---

## 🚀 Getting Started
1. Κάνε clone το repo:
   ```bash
   git clone https://github.com/AntoniouIoannis/Pharos.git


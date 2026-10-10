# 👶 Vule Baby Monitor

[![Release](https://img.shields.io/github/v/release/lukamilosevic/vulebabymonitor?color=brightgreen&label=Latest%20Release)](https://github.com/lukamilosevic/vulebabymonitor/releases/latest)
[![Zero-Cloud](https://img.shields.io/badge/Privacy-100%25%20Local%20%2F%20Zero--Cloud-brightgreen)](#)
[![Android](https://img.shields.io/badge/Android-minSdk%2023%20%7C%20targetSdk%2035-blue?logo=android)](#)
[![Security](https://img.shields.io/badge/Security-ChaCha20--Poly1305%20AEAD-blue)](#)

> **100% local, native Android baby monitor over local Wi-Fi — zero cloud servers, zero account registrations, zero internet required, zero subscriptions.**

---

### 🌐 Official Website & Landing Page
Visit the live interactive web page:  
👉 **[https://lukamilosevic.github.io/vulebabymonitor/](https://lukamilosevic.github.io/vulebabymonitor/)**

### 📦 Download Latest APK (GitHub Releases)
👉 **[Download Latest Production APKs (Releases /latest)](https://github.com/lukamilosevic/vulebabymonitor/releases/latest)**

* **`BabyMonitor.apk`** — **Recommended** for modern phones (`arm64-v8a`).
* **`BabyMonitor-armv7.apk`** — For older 32-bit devices (`armeabi-v7a`).
* **`BabyMonitor-Universal.apk`** — Universal APK compatible with all architectures.
* **Google Play Store:** Coming Soon 🚀

---

## 🌟 Key Features (English)

* **100% Private & Local (Zero-Cloud):** All streams stay entirely within your home Wi-Fi. No accounts, no external cloud servers, and 0 bytes over mobile data.
* **Maximum Battery Savings:** Audio transmission shuts down during quiet periods (Silence-on-Wire with a 4-byte ping every 1.5s). Audio playback on the parent unit lazily pauses after 1.5s of silence to allow the CPU to remain in deep sleep (C-state).
* **Hardware VOX Audio Detection:** Low-latency 16-bit PCM 16kHz audio stream activates instantaneously when baby makes sounds, backed by an auto-refreshing 15s smart hangover.
* **Video on Demand & Picture-in-Picture:** Native Android Camera2 hardware JPEG stream (~5 fps for zero heating), floating Android PiP mode with auto-reconnect on screen unlock, and remote night light torch.
* **Smart Nightstand (Auto Video over Lock Screen):** When sound is detected overnight, the parent device turns on and launches live video over the lock screen without unlocking.
* **True High-Resolution Hardware Still Photos:** Dedicated sensor-capture up to 1920x1440 with UDP pacing and automatic NACK packet retransmission.
* **Military-Grade Encryption (RFC 8439):** Automatic ECDH (X25519) key exchange and ChaCha20-Poly1305 AEAD authenticated encryption protect every packet on public or shared Wi-Fi networks.
* **4-Digit SAS Verification PIN:** Simple glance-and-confirm PIN pairing prevents unauthorized connections.
* **Two-Way Talk-Back:** Hold-to-Talk communication with 1.2s hardware echo cancellation.
* **10s Safety Watchdog:** Immediate audible alarm, vibration, and notification if connection drops.

---

## 🚀 Quick Setup (3 Steps)

1. **Install APK:** Download and install `BabyMonitor.apk` on two Android phones.
2. **Connect to Wi-Fi:** Ensure both phones are on the same Wi-Fi network (or enable Hotspot on one phone without mobile data).
3. **Select Roles:** Tap **👶 Baby** on the nursery phone and **👪 Parent** on your phone.

---

# 🇷🇸 Uputstvo na srpskom jeziku

> **100% lokalna, native Android aplikacija za bebi alarm preko kućne Wi-Fi mreže — bez interneta, bez servera u oblaku, bez registracije i bez pretplate.**

### 📦 Preuzimanje
👉 **[Preuzmi najnoviji BabyMonitor.apk](https://github.com/lukamilosevic/vulebabymonitor/releases/latest)**

* **`BabyMonitor.apk`** — Preporučeno za sve moderne telefone (`arm64-v8a`).
* **`BabyMonitor-armv7.apk`** — Za starije 32-bitne uređaje (`armeabi-v7a`).
* **`BabyMonitor-Universal.apk`** — Univerzalni paket za sve modele.
* **Google Play Prodavnica:** Stiže uskoro 🚀

### 🌟 Glavne Karakteristike
* **100% Zero-Cloud:** Zvuk i slika nikada ne napuštaju vašu lokalnu kućnu mrežu uz 0 bajtova mobilnog interneta.
* **Maksimalna štednja baterije:** Dok beba miruje šalje se samo 4-bajtni ping na 1.5s, a roditeljski telefon drži procesor u dubokom snu (Deep Sleep C-state).
* **Automatska VOX detekcija zvuka:** Zvuk se pali istog trenutka kada se beba oglasi, uz pametni 15s hangover produžetak.
* **Video na zahtev i PiP:** Native Camera2 JPEG prenos bez pregrevanja telefona, rotacija sočiva, noćno svetlo (blic) i lebdeći Picture-in-Picture prozorčić sa automatskim nastavkom.
* **Smart Nightstand:** Automatski prikaz live videa preko zaključanog ekrana na noćnom ormariću čim se detektuje zvuk.
* **Prava fotografija visoke rezolucije:** Hardverski senzorski snimak sa NACK retransmisijom izgubljenih paketa.
* **Vojna enkripcija i PIN uparivanje:** ChaCha20-Poly1305 AEAD enkripcija uz 4-cifreni kod za potvrdu bez kucanja.
* **Dvosmerni Talk-Back:** Hold-to-Talk komunikacija sa automatskim gušenjem eha.
* **10s Watchdog nadzor:** Trenutni glasan alarm i vibracija ako pukne veza.

### 🚀 Brzi Početak u 3 Koraka
1. **Instalirajte APK:** Instalirajte `BabyMonitor.apk` na oba Android telefona.
2. **Povežite na Wi-Fi:** Povežite oba telefona na istu mrežu (ili Hotspot).
3. **Izaberite Uloge:** Na jednom izaberite **👶 Beba**, a na drugom **👪 Roditelj**.

---

<p align="center">
  <b>Za Vukotu, od ćaleta Luke ❤️</b>
</p>

# DisasterAid 🚨
### Human-Centred Disaster Preparedness & Emergency Response System
**Course:** BSIT 31073 – Human Computer Interaction Group Project  
**Group:** 14  
**Team Members:**
- Sanjana Desilva [BSIT241026]
- Navodya Sankalpani [BSSE241009]
- Dilmi Amasha [BSSE241040]

---

## 📌 Project Overview
DisasterAid is an accessible, web-based emergency response prototype designed for Sri Lanka's recurrent disaster landscapes (flash floods, landslides, cyclones). Traditional early warning systems merely broadcast passive alarm notices without actionable guidance, causing severe cognitive panic and decision delay. DisasterAid transforms passive warnings into an immediate, unmistakable **"Recommended Next Safe Action"** backed by empirical cognitive models, dual-actor live triage, and offline resilience.

---

## ✨ Key Features & HCI Innovations

1. **Action-First Critical Alert Banner:**
   - Dominant severity badges and explicit instructions (*"EVACUATE IMMEDIATELY to Community Center"*).
   - Resolves *Cognitive Tunnel Vision* under fear.

2. **Multimodal Audio Narration (Web Speech API):**
   - 🔊 One-tap voice readout in Sinhala, Tamil, and English.
   - Built for low-literacy citizens and older adults (e.g., persona Kamala, 68).

3. **Fitts' Law Emergency SOS & Slip Prevention:**
   - SOS button placed in the natural lower thumb reach zone with 100% viewport width.
   - **5-Second Audible Countdown Buffer:** Accommodates Norman's *Motor Slips* with a massive, full-width `CANCEL REQUEST (I'M OK)` button, achieving **100% false-alarm prevention**.

4. **Dual-Actor Real-Time Synergy:**
   - **Resident Mobile App:** Distress signal triggers verifiable ticket `#EM-8429` with GPS coordinates.
   - **Officer Dashboard:** Live incident triage queue categorizes calls into Critical vs. Moderate, with one-click dispatch updating victim ticket status in real time.

5. **Offline Local Storage Caching (QOC Framework):**
   - Critical shelter locations, elevation routes, and the interactive emergency **Go-Bag supply checklist** remain 100% accessible during cellular blackouts.

6. **Universal Usability & WCAG AAA:**
   - Trilingual UI (English / සිංහල / தமிழ்).
   - Dynamic typography scaling (1.0x to 1.4x).

---

## 📊 Usability Evaluation Results (Empirical Testing)
Tested across 7 disaster scenario tasks (T1 – T7):
- **Safe Action Recognition Time:** 3.4 seconds (88% recognized in < 5s)
- **Motor Slip Cancellation Success:** 100% (Average time: 2.1s)
- **System Usability Scale (SUS) Score:** **87.5 / 100** *(Grade A+ Exceptional Usability)*

---

## 🚀 How to Run the Prototype Locally
No installation or backend server setup required!
1. Clone or download this repository.
2. Double-click `index.html` to open it in any modern web browser (Google Chrome, Microsoft Edge, Brave, etc.).
3. Test both the **Resident Mobile App** view and switch to the **Officer Dashboard** view from the top header!

---

## 📂 Project Assets Included
- `index.html` — Fully functional interactive prototype (Mobile App + Officer Dashboard).
- `final presentation.pptx` — 13-slide visual presentation deck.
- `DisasterAid_Comprehensive_HCI_Report.pdf` — Complete HCI specification report (Fitts' Law, Shneiderman's 8 Rules, Norman's models, QOC trade-offs).

# Custom Desktop PC Build – Group 6 (AMD Budget 720p)

**Course:** CSARCH2  
**Section:** _S21_  
**Group Members:**  
- _Amores, Joshua_  
- _Amores, Louise_  
- _Carmona, Lorenzo_  
- _Friginal, Roj_  
- _Young, Cedric_  

---

## 1) Introduction

Goal: build a **current‑gen, Metro Manila–sourced** desktop for **light 720p gaming** (League of Legends, Portal, Dota Underlords) and general use.  
Budget target: **₱20,000 ±5%**.  
Design choice: an **AMD APU** (Ryzen 5 5600G) to meet the gaming target without a dedicated GPU; leave an easy upgrade path to a future dGPU (e.g., RX 6600).

---

## 2) PCPartPicker Validation

> Use PCPartPicker System Builder with PH region to validate fit, wattage, and required connectors.  
**PCPartPicker permalink:** _paste your link here_  
**Screenshot:** _place in `/pcpp/pcpp_screenshots/`_

### Parts Summary
| Component | Model | Notes |
|---|---|---|
| **CPU** | AMD **Ryzen 5 5600GT** (6C/12T, Radeon Vega 7) | Includes Wraith cooler; strong iGPU for 720p/low. |
| **CPU Cooler** | **Stock Wraith Stealth** | AM4 mounting; adequate at stock. |
| **Motherboard** | **GIGABYTE A520M‑KV2** (mATX, AM4) | AM4 socket, 1× M.2 NVMe. |
| **RAM** | **16 GB (2×8) DDR4‑3200 CL16** (TEAMGROUP 16GB VULCAN Z Desktop Memory) | Dual‑channel is critical for iGPU FPS. |
| **Storage 1 (NVMe)** | **Kingston NV3 500 GB** PCIe NVMe M.2 | Meets rubric “Storage 1 NVMe M.2”. |
| **Storage 2** | — | Optional (skip to stay under budget). |
| **Graphics** | **Integrated Radeon** (5600G iGPU) | Satisfies “Integrated or dedicated” requirement. |
| **PSU** | **Gigabyte P450B 450W** 80+ Bronze | True‑rated; future headroom for entry dGPU. |
| **Case** | **DarkFlash DB330M MicroATX Mini Tower Case** (mATX mini‑tower) | mATX + ATX PSU support; budget airflow. |
| **Case fans** | **Case Included** | Add for temps/noise. |

---

## 3) Local Manila Build (new parts only; links & prices)

> Record **date checked (October 3, 2025)** for each line and keep screenshots in `/pricing/`.

[Link to Spreadsheet](https://docs.google.com/spreadsheets/d/1NElgdf8un2gQuxJTkAW_fvciuKMDOF-cPFAEcsoqLjU/edit?usp=sharing)

| Component | Model | Vendor & Link | Price (Php) | Compatibility Notes |
|---|---|---|---:|---|
| **CPU** | AMD Ryzen 5 5600GT | PC Express – https://pcx.com.ph/collections/processors/products/amd-ryzen-5-5600gt-desktop-processor-3-6-up-to-4-6ghz?_pos=5&_fid=8b5442f3b&_ss=c | 7,500 | AM4; includes stock cooler; iGPU used. |
| **CPU Cooler** | AMD Wraith Stealth (in‑box) | — | 0 | AM4 mounting; no extra cost. |
| **Motherboard** | GIGABYTE A520M‑K V2 (mATX) | PC Express – https://pcx.com.ph/products/gigabyte-a520m-k-v2-micro-atx-motherboard?_pos=2&_sid=d99ec411a&_ss=r | 3,050 | AM4 socket; NVMe M.2 slot; BIOS supports 5600G. |
| **RAM** | TEAMGROUP 16GB (2x8GB) DDR4 3600MHz VULCAN Z Desktop Memory | PC Express – https://pcx.com.ph/collections/memory-modules/products/teamgroup-16gb-2x8gb-ddr4-3600mhz-vulcan-z-desktop-memory-gray?_pos=30&_fid=987a5bc06&_ss=c | 3,000 | Dual‑channel DDR4; boosts iGPU bandwidth. |
| **Storage 1 (NVMe)** | Kingston NV3 500 GB M.2 NVMe | PC Express – https://pcx.com.ph/products/kingston-500gb-nv3-m-2-pcie-nvme-solid-state-drive | 2,250 | NVMe M.2 2280 in motherboard slot. |
| **Storage 2 (optional)** | — | — | 0 | Add SATA SSD/HDD later if needed. |
| **Graphics** | Integrated Radeon (5600G) | — | 0 | Meets rubric (integrated). |
| **Power Supply** | Gigabyte P450B 450W 80+ Bronze | DynaQuest – https://dynaquestpc.com/products/gigabyte-p450b-bronze-450w-80-power-supply-gp-p450b | 2,165 | 24‑pin ATX + 8‑pin EPS present. |
| **Case** | DarkFlash DB330M MicroATX Mini Tower Case | Dyna Quest – https://dynaquestpc.com/products/darkflash-db330m-matx-pc-case | 1590 | Fits mATX board & ATX PSU; includes fan. |
| **Case Fans Included** | 120 mm PWM | — | 0 | Add 1–2 if airflow needed. |
|  |  |  |  |  |
| **Total** |  |  | **₱19,115** | ✅ within ₱20,000 ±5% |



---

## 4) Compatibility Justification (what we checked)

- **CPU ↔ Motherboard:** AM4 socket; A520 chipset supports Ryzen 5000G. Flash latest BIOS if needed.  
- **RAM:** DDR4 DIMMs installed as **2×8 GB** in dual‑channel (A2/B2). Board QVL supports 3200 MT/s.  
- **Storage:** One **NVMe M.2 2280** fits the A520 M.2 slot (PCIe NVMe). Optional SATA drive uses available SATA ports.  
- **Power:** 450 W Bronze PSU with **24‑pin ATX + 8‑pin EPS**. Plenty for APU now and future entry GPU.  
- **Case fit & airflow:** mATX board + ATX PSU supported; at least one intake + one exhaust fan plan.  
- **PCPartPicker:** Validate the exact SKUs; attach permalink + “All compatibility notes cleared” screenshot.

---

## 5) Budget Analysis

- **Budget limit:** ₱20,000 (±5% allowed up to ₱21,000)  
- **Final total (current cart):** **₱19,115**  
- **Trade‑offs:** No dedicated GPU (iGPU only), stock cooler, single 500 GB NVMe. PSU chosen with headroom for a future dGPU.

---

## 6) Repo Layout

```
/README.md                       <-- this file
/pricing/CSARCH2_Pricing.xlsx    <-- vendor links, PHP prices, date-checked
/pcpp/pcpartpicker_link.txt      <-- permalink
/pcpp/pcpp_screenshots/          <-- compatibility screenshots
/video/pitch_link.txt            <-- unlisted video URL (5–7 min)
```

---

## 7) Video Pitch (5–7 minutes)

- Problem & goal (720p/light gaming under ₱20k)  
- Part choices + justifications (iGPU focus, dual‑channel RAM, NVMe, Bronze PSU)  
- Local price proof (open each vendor page)  
- PCPP compatibility check  
- Upgrade path (drop‑in dGPU later)

---

## 8) References

- PC Express: https://pcx.com.ph/  
- DynaQuest PC: https://dynaquestpc.com/  
- VillMan: https://villman.com/  
- Asianic: https://www.asianic.com.ph/  
- PCPartPicker: https://pcpartpicker.com/  

> _Keep screenshots of prices/availability with dates in `/pricing/` for grading._

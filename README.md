# Custom Desktop PC Build – Group 6 (AMD Budget 720p)

**Course:** CSARCH2  
**Section:** _to fill_  
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
| **CPU** | AMD **Ryzen 5 5600G** (6C/12T, Radeon Vega 7) | Includes Wraith cooler; strong iGPU for 720p/low. |
| **CPU Cooler** | **Stock Wraith Stealth** | AM4 mounting; adequate at stock. |
| **Motherboard** | **ASUS PRIME A520M‑K** (mATX, AM4) | AM4 socket, 1× M.2 NVMe. |
| **RAM** | **16 GB (2×8) DDR4‑3200 CL16** (G.Skill Ripjaws V) | Dual‑channel is critical for iGPU FPS. |
| **Storage 1 (NVMe)** | **Kingston NV3 500 GB** PCIe NVMe M.2 | Meets rubric “Storage 1 NVMe M.2”. |
| **Storage 2** | — | Optional (skip to stay under budget). |
| **Graphics** | **Integrated Radeon** (5600G iGPU) | Satisfies “Integrated or dedicated” requirement. |
| **PSU** | **Gigabyte P450B 450W** 80+ Bronze | True‑rated; future headroom for entry dGPU. |
| **Case** | **Antec VX10M** (mATX mini‑tower) | mATX + ATX PSU support; budget airflow. |
| **Case fans** | Optional 120 mm PWM | Add if temps/noise demand it. |

---

## 3) Local Manila Build (new parts only; links & prices)

> Record **date checked** for each line and keep screenshots in `/pricing/`.

| Component | Model | Vendor & Link | Price (Php) | Compatibility Notes |
|---|---|---|---:|---|
| **CPU** | AMD Ryzen 5 5600G | PC Express – https://pcx.com.ph/products/amd-ryzen-5-5600g-3-9ghz-processor | 7,550 | AM4; includes stock cooler; iGPU used. |
| **CPU Cooler** | AMD Wraith Stealth (in‑box) | — | 0 | AM4 mounting; no extra cost. |
| **Motherboard** | ASUS PRIME A520M‑K (mATX) | PC Express – https://pcx.com.ph/products/asus-prime-a520m-k-micro-atx-motherboard | 3,200 | AM4 socket; NVMe M.2 slot; BIOS supports 5600G. |
| **RAM** | G.Skill Ripjaws V 16 GB (2×8) DDR4‑3200 CL16 | PC Express – https://pcx.com.ph/products/gskills-16gb-2x-8gb-ddr4-3200mhz-ripjaws-v-f4-3200c16d-16gvkb-desktop-memory | 3,000 | Dual‑channel DDR4; boosts iGPU bandwidth. |
| **Storage 1 (NVMe)** | Kingston NV3 500 GB M.2 NVMe | PC Express – https://pcx.com.ph/products/kingston-500gb-nv3-m-2-pcie-nvme-solid-state-drive | 2,200 | NVMe M.2 2280 in motherboard slot. |
| **Storage 2 (optional)** | — | — | 0 | Add SATA SSD/HDD later if needed. |
| **Graphics** | Integrated Radeon (5600G) | — | 0 | Meets rubric (integrated). |
| **Power Supply** | Gigabyte P450B 450W 80+ Bronze | DynaQuest – https://dynaquestpc.com/products/gigabyte-p450b-bronze-450w-80-power-supply-gp-p450b | 2,165 | 24‑pin ATX + 8‑pin EPS present. |
| **Case** | Antec VX10M (mATX mini‑tower) | PC Express – https://pcx.com.ph/products/antec-vx10m-tempered-glass-matx-mini-tower-case | 950 | Fits mATX board & ATX PSU; includes fan. |
| **Case Fans (optional)** | 120 mm PWM | — | 0 | Add 1–2 if airflow needed. |
|  |  |  |  |  |
| **Total** |  |  | **₱19,065** | ✅ within ₱20,000 ±5% |

**Alternates (if OOS):**
- CPU alt: **Ryzen 5 5600GT** (DynaQuest) – https://dynaquestpc.com/products/amd-ryzen-5-5600gt-3-60-4-60ghz-6-core-processor-boxed  
- Board alts: **MSI A520M‑A PRO** – https://dynaquestpc.com/products/msi-a520m-a-pro-matx-am4-motherboard-m-2-nvme-slot-hdmidvi-d-port  
  **GIGABYTE A520M‑K V2** – https://dynaquestpc.com/products/gigabyte-a520m-k-v2-am4-motherboard  
- Case alt: **Tecware Nexus Air M2** (with fans) – https://dynaquestpc.com/products/tecware-nexus-air-m2-black-mesh-tg-matx-3x120mm

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
- **Final total (current cart):** **₱19,065**  
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

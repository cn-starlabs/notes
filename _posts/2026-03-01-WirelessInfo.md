---
layout: post
title:  "Wireless Info – March 1st"
date:   2026-03-01 08:00:00 -0500
categories: Network
---

Here is a concise overview of **modern Wi-Fi wireless knowledge** (focusing on widely used standards from ~2010 onward), including frequency bands, supported channel widths, and maximum **theoretical PHY speeds** (best-case lab conditions with maximum spatial streams, widest channels, and highest modulation).

These are **theoretical maximums** — real-world speeds are typically 40–65% of these values depending on distance, interference, device capabilities, and MIMO configuration.

### Wi-Fi Generations Overview Table

| Generation   | IEEE Standard | Marketing Name | Frequency Bands          | Typical / Max Channel Width          | Max Theoretical Speed       | Key Notes / Modulation          |
|--------------|---------------|----------------|--------------------------|--------------------------------------|-----------------------------|---------------------------------|
| Wi-Fi 4      | 802.11n       | Wi-Fi 4        | 2.4 GHz + 5 GHz          | 20 / 40 MHz                          | ~600 Mbps                   | Older standard, still common in budget devices |
| Wi-Fi 5      | 802.11ac      | Wi-Fi 5        | 5 GHz only               | 20 / 40 / 80 / 160 MHz (80+80)       | ~3.5 Gbps (6.9 Gbps in rare 8×8) | 256-QAM, MU-MIMO introduced     |
| Wi-Fi 6      | 802.11ax      | Wi-Fi 6        | 2.4 GHz + 5 GHz          | 20 / 40 / 80 / 160 MHz (80+80)       | ~9.6 Gbps                   | 1024-QAM, OFDMA, better in dense environments |
| Wi-Fi 6E     | 802.11ax      | Wi-Fi 6E       | 2.4 GHz + 5 GHz + **6 GHz** | Same as Wi-Fi 6 (up to 160 MHz)   | ~9.6–10.5 Gbps              | Adds clean 6 GHz band (less interference) |
| Wi-Fi 7      | 802.11be      | Wi-Fi 7        | 2.4 GHz + 5 GHz + **6 GHz** | 20 / 40 / 80 / 160 / **320 MHz**  | ~46 Gbps (23 Gbps per band) | 4096-QAM, 320 MHz channels, Multi-Link Operation (MLO) |

### Channel Width vs. Speed Comparison (Approximate Theoretical Max – 2×2 MIMO client, common today)

| Channel Width | Wi-Fi 5 (5 GHz) | Wi-Fi 6 / 6E     | Wi-Fi 7 (4096-QAM)       | Notes                                      |
|---------------|-----------------|------------------|---------------------------|--------------------------------------------|
| 20 MHz        | ~150–200 Mbps   | ~200–300 Mbps    | ~400–600 Mbps             | Basic / legacy compatibility               |
| 40 MHz        | ~300–400 Mbps   | ~500–600 Mbps    | ~1–1.2 Gbps               | Common in 2.4 GHz                          |
| 80 MHz        | ~650–867 Mbps   | ~1.0–1.2 Gbps    | ~2.3–2.9 Gbps             | Most common sweet spot today               |
| 160 MHz       | ~1.7–2.3 Gbps   | ~2.4 Gbps        | ~4.6–5.8 Gbps             | Requires clean spectrum (mostly 5/6 GHz)   |
| 320 MHz       | Not supported   | Not supported    | ~9.2–11.5 Gbps (single link) | Wi-Fi 7 exclusive, mainly 6 GHz band     |

### Quick Frequency Band Characteristics (2025–2026 reality)

- **2.4 GHz**  
  → Best range & wall penetration  
  → Only ~3 non-overlapping 20 MHz channels (1, 6, 11)  
  → Very crowded → slowest speeds in practice

- **5 GHz**  
  → Good balance of speed & range  
  → Many 20/40/80 MHz channels (more with DFS)  
  → Up to 160 MHz possible (but often interfered)

- **6 GHz** (Wi-Fi 6E & 7 only)  
  → Cleanest band (much less interference in 2025–2026)  
  → Widest channels possible (up to 320 MHz in Wi-Fi 7)  
  → Shorter range than 5 GHz, needs line-of-sight or good placement

**Wi-Fi 7 summary (most advanced in 2026)**  
- Widest channels: **320 MHz** (only in 6 GHz)  
- Highest modulation: **4096-QAM** (~20% more efficient than 1024-QAM)  
- Multi-Link Operation → can use 2–3 bands simultaneously  
- Theoretical peak: **46 Gbps** (with 16×16 MIMO)  
- Realistic single-client speed in good conditions: **4–10 Gbps**

Let me know if you'd like more detail on a specific standard, channel numbers per band, or real-world speed examples!

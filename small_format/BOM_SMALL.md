<div>

<div style="border-bottom:2px solid #000; padding-bottom:10px; margin-bottom:20px;">
<h2 style="margin:0; font-size:1.4rem; text-transform:uppercase; letter-spacing:0.05em;">
BOM.md — Rectifier Mini-Node
</h2>
<p style="margin:5px 0 0 0; font-size:0.85rem; font-weight:bold; color:#444;">
BILL OF MATERIALS • R1.0 • NEAR-FIELD DESKTOP MONITORING SYSTEM
</p>
</div>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
1. Transducer System
</h3>

<ul>
<li><strong>Size:</strong> 4”–5” full-range driver</li>
<li><strong>Cone materials:</strong> paper pulp / paper composite (cellulose reinforced)</li>
<li><strong>Sensitivity:</strong> 85–92 dB (1W/1m)</li>
<li><strong>Impedance:</strong> 4Ω or 8Ω</li>
<li><strong>Power handling:</strong> 30–80W RMS</li>
<li><strong>Resonance (Fs):</strong> 55–90 Hz range</li>
</ul>

<p><strong>Reference class examples:</strong></p>
<ul>
<li>Dayton Audio full-range series</li>
<li>Faital Pro 4–5” full-range drivers</li>
<li>Markaudio Alpair series</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
2. Amplification System
</h3>

<ul>
<li>Class-D: TPA3116 / TPA3251 / TPA3255 class equivalents</li>
<li>Output: 2 × 50W (compact) to 2 × 175W (high headroom)</li>
<li>Efficiency: ≥88%</li>
<li>Supply: 12V–36V</li>
</ul>

<p><strong>Thermal management:</strong></p>
<ul>
<li>Aluminum heatsink (extruded or bonded)</li>
<li>≥3 W/mK thermal interface material</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
3. Power System
</h3>

<p><strong>Desktop configuration:</strong></p>
<ul>
<li>24V–36V regulated external PSU (5A–10A)</li>
</ul>

<p><strong>Portable configuration:</strong></p>
<ul>
<li>3S–10S Li-ion battery system (12V–36V nominal)</li>
</ul>

<p><strong>Battery protection (if applicable):</strong></p>
<ul>
<li>Overcurrent / undervoltage / thermal protection</li>
<li>10A–30A continuous discharge depending on variant</li>
</ul>

<ul>
<li>Bulk capacitors: 470µF–2200µF low ESR (35V–50V)</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
4. Signal Input Stage
</h3>

<ul>
<li>3.5mm stereo line-in / RCA / optional TRS balanced input</li>
<li>Input impedance: ≥10kΩ</li>
<li>Op-amp buffer stage (NE5532 / OPA equivalents)</li>
<li>Gain range: unity to +20 dB</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
5. Enclosure System
</h3>

<ul>
<li>15mm Baltic birch plywood (preferred)</li>
<li>MDF alternative (reduced performance)</li>
<li>Internal cross-bracing (minimum 1 plane)</li>
<li>Airtight construction for sealed variants</li>
<li>Optional ported tuning</li>
<li>Polyester fiber / acoustic wool damping</li>
<li>Rubber isolation feet</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
6. Wiring &amp; Connectivity
</h3>

<ul>
<li>Signal wiring: 20–24 AWG shielded copper</li>
<li>Power wiring: 12–18 AWG depending on current path</li>
<li>Internal connectors: JST / Molex</li>
<li>DC input: barrel jack (5.5mm standard)</li>
<li>Optional USB-C power delivery (advanced variant)</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
7. Fasteners &amp; Materials
</h3>

<ul>
<li>PVA wood adhesive (Type II preferred)</li>
<li>Non-acidic acoustic silicone sealant</li>
<li>Foam gasket tape</li>
<li>Medium-strength thread locker</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
8. Cost Structure (Reference)
</h3>

<ul>
<li>Driver: $18–$60</li>
<li>Amplifier: $12–$45</li>
<li>Power system: $15–$80</li>
<li>Enclosure: $20–$70</li>
<li>Wiring &amp; hardware: $10–$30</li>
</ul>

<p><strong>Estimated COGS:</strong></p>
<ul>
<li>Low tier: $75–$120</li>
<li>Standard: $120–$180</li>
<li>High performance: $180–$260</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
9. Design Constraints
</h3>

<ul>
<li>Rigid enclosure coupling required (no flex under SPL)</li>
<li>Near-field operation (0.5–1.5 m)</li>
<li>No DSP required for baseline tonal behavior</li>
<li>Thermal stability under continuous operation</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
10. Revision Notes
</h3>

<ul>
<li>Modular BOM supports multiple enclosure and power variants</li>
<li>Component substitution only within equivalent electrical/acoustic classes</li>
<li>Designed for scalable desktop and portable derivatives</li>
</ul>
</section>

<div style="margin-top:25px; text-align:center; font-size:0.75rem; color:#777;">
RECTIFIER MINI-NODE // BOM_R1.0.md
</div>

</div>

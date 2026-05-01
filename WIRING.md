<div>

<div style="border-bottom:2px solid #000; padding-bottom:10px; margin-bottom:20px;">
<h2 style="margin:0; font-size:1.4rem; text-transform:uppercase; letter-spacing:0.05em;">
System Layout &amp; Wiring Manifest
</h2>
<p style="margin:5px 0 0 0; font-size:0.85rem; font-weight:bold; color:#444;">
PROTOCOL: High-Current Audio System Architecture
</p>
</div>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
Section 1: Signal Path
</h3>

<ul>
<li><strong>Input:</strong> Balanced XLR / TRS line-level input</li>
<li><strong>Preamp Stage:</strong> Analog gain stage with high-frequency filtering and optional harmonic coloration (JFET-based design)</li>
<li><strong>Gain Control:</strong> Logarithmic potentiometer</li>
<li><strong>Power Amplifier:</strong> Class-D amplification stage based on TPA3255 architecture</li>
<li><strong>Output:</strong> High-current wiring to loudspeaker transducer</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
Section 2: Power Architecture
</h3>

<ul>
<li><strong>Battery System:</strong> 10S2P lithium-ion pack (36V nominal)</li>
<li><strong>Current Capability:</strong> 30A continuous discharge via BMS</li>
<li><strong>Power Distribution:</strong> Low-resistance DC rails with reservoir capacitors for transient stability</li>
</ul>
</section>

<div style="padding:15px; border:1px solid #dee2e6; background:#f8f9fa;">
<strong>Grounding Strategy:</strong> Star-ground topology used to minimize ground loop risk between signal and power return paths. Implementation is layout-dependent.
</div>

</div>

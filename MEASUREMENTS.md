<div>

<div style="border-bottom:2px solid #000; padding-bottom:10px; margin-bottom:20px;">
<h2 style="margin:0; font-size:1.4rem; text-transform:uppercase; letter-spacing:0.05em;">
MEASUREMENTS.md — Validation Protocol
</h2>
<p style="margin:5px 0 0 0; font-size:0.85rem; font-weight:bold; color:#444;">
SOVEREIGN MOBILE NODE (SMN) • INTERNAL CALIBRATION • REV 0.9.1-BETA
</p>
</div>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
1. Frequency Response (FR) Target
</h3>

<p>Measured relative to 1 kHz reference point (0 dB).</p>

<table>
<tr><td>20 Hz</td><td>-2.0 dB</td><td>Low-frequency extension</td></tr>
<tr><td>80 Hz</td><td>+2.5 dB</td><td>Low-shelf emphasis</td></tr>
<tr><td>1 kHz</td><td>0.0 dB</td><td>Reference baseline</td></tr>
<tr><td>3 kHz</td><td>+2.5 dB</td><td>Upper-mid control region</td></tr>
<tr><td>10 kHz</td><td>-1.5 dB</td><td>High-frequency attenuation</td></tr>
</table>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
2. Total Harmonic Distortion (THD)
</h3>

<p>Measured at 94 dB SPL.</p>

<ul>
<li>20 Hz – 100 Hz: &lt; 1.2%</li>
<li>100 Hz – 10 kHz: &lt; 0.3%</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
3. Cumulative Spectral Decay (CSD)
</h3>

<ul>
<li>1 kHz – 5 kHz: -30 dB within ~2.2 ms</li>
<li>No sustained resonant ridges above baseline decay window</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
4. Enclosure Vibration Analysis (LDV)
</h3>

<table>
<tr><td>100 Hz</td><td>Reference: 1.00</td><td>SMN: 0.68</td><td>-32%</td></tr>
<tr><td>1 kHz</td><td>Reference: 0.70</td><td>SMN: 0.48</td><td>-31%</td></tr>
<tr><td>3 kHz</td><td>Reference: 0.65</td><td>SMN: 0.50</td><td>-23%</td></tr>
</table>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
5. Test Conditions
</h3>

<ul>
<li>SPL reference: 94 dB @ 1 m</li>
<li>Environment: controlled indoor measurement space</li>
<li>Calibration: IEC-class measurement microphone</li>
<li>Mounting: fixed-head clamp, no isolation padding unless specified</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
6. Observation Notes (Internal)
</h3>

<ul>
<li>High-mass enclosure reduces measurable cabinet vibration across midband</li>
<li>Distortion remains within expected dynamic driver behavior range</li>
<li>Decay characteristics consistent with rigid enclosure models</li>
</ul>
</section>

<section style="margin-bottom:20px;">
<h3 style="background:#000;color:#fff;padding:6px 10px;display:inline-block;font-size:0.95rem;">
7. Review Notes (Internal Only)
</h3>

<ul>
<li>SPL-dependent distortion behavior</li>
<li>Enclosure resonance contribution</li>
<li>Frequency response deviation from target curve</li>
</ul>
</section>

<div style="margin-top:25px; text-align:center; font-size:0.75rem; color:#777;">
hardware/MEASUREMENTS.md
</div>

</div>

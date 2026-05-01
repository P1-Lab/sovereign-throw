## Document Type

This document defines the Rectifier Mini-Node as a near-field monitoring system in engineering terms suitable for external review, measurement validation, and manufacturing translation.

System-specific terminology (e.g., "Rectifier") is used as internal naming and does not replace underlying acoustic engineering definitions.
<HR>
<p><strong>Rectifier Mini-Node</strong><br>
Forensic Desktop Monitoring System<br>
Protocol: Near-Field Reproduction / Deterministic Acoustic Path</p>

<hr>

<p><strong>1. System Definition</strong></p>
<p>The Rectifier Mini-Node is a compact near-field monitoring system designed for desktop audio environments where room modes dominate perception, low-latency monitoring is required, and enclosure behavior significantly affects tonal accuracy.</p>
<p>The system prioritizes mechanical enclosure control and low-latency signal delivery over DSP-based correction strategies.</p>

<hr>

<p><strong>2. Design Philosophy</strong></p>

<p><strong>2.1 Mechanical Signal Integrity</strong></p>
<p>Instead of relying on digital correction, the system emphasizes:</p>
<ul>
<li>enclosure rigidity</li>
<li>controlled panel resonance</li>
<li>predictable driver behavior in a sealed acoustic boundary</li>
</ul>

<p><strong>2.2 Near-Field Acoustic Priority</strong></p>
<p>Designed for:</p>
<ul>
<li>0.5–1.2 meter listening distances</li>
<li>minimal room interaction</li>
<li>direct field dominance over reflected energy</li>
</ul>

<hr>

<p><strong>3. Acoustic System Architecture</strong></p>

<p><strong>3.1 Driver System</strong></p>
<ul>
<li>4–5” full-range transducer</li>
<li>paper or paper-composite cone preferred for controlled breakup behavior</li>
<li>tuned for smooth off-axis response in near-field use</li>
</ul>

<p><strong>3.2 Enclosure System</strong></p>
<ul>
<li>15mm Baltic birch plywood</li>
<li>internally braced pressure-sealed cabinet</li>
<li>high stiffness-to-weight ratio to reduce panel radiation</li>
</ul>

<p><strong>Design goal:</strong> Minimize enclosure contribution to audible spectrum above 200 Hz.</p>

<p><strong>3.3 Signal Path</strong></p>
<ul>
<li>line-level analog input preferred</li>
<li>optional DAC interface depending on deployment</li>
<li>no mandatory onboard DSP processing</li>
</ul>

<p><strong>Latency target:</strong> &lt; 2 ms system latency (excluding host DAW buffer)</p>

<hr>

<p><strong>4. Frequency Response Target (Near-Field Tuned)</strong></p>

<ul>
<li>40 Hz – 80 Hz: slight controlled lift (+1 to +2 dB)</li>
<li>80 Hz – 1 kHz: flat (±1.5 dB)</li>
<li>1 kHz – 5 kHz: neutral with controlled breakup management</li>
<li>5 kHz – 10 kHz: mild roll-off to reduce harshness in untreated rooms</li>
</ul>

<p><strong>Intent:</strong> Avoid over-brightness in reflective desktop environments.</p>

<hr>

<p><strong>5. Enclosure Behavior (Critical Metric)</strong></p>

<p><strong>Measurement focus:</strong></p>
<ul>
<li>panel vibration modes (accelerometer or laser vibrometry)</li>
<li>resonance decay time (waterfall analysis)</li>
</ul>

<p><strong>Target behavior:</strong></p>
<ul>
<li>no strong panel resonances in 150 Hz – 2 kHz region</li>
<li>fast decay of cabinet energy (&lt; 5 ms preferred)</li>
</ul>

<hr>

<p><strong>6. System Constraints</strong></p>

<table>
<tr>
<td>Driver size</td>
<td>4–5 inches</td>
</tr>
<tr>
<td>Cabinet material</td>
<td>Baltic birch (15mm)</td>
</tr>
<tr>
<td>Amplification</td>
<td>External or integrated Class D</td>
</tr>
<tr>
<td>Use case</td>
<td>Near-field monitoring</td>
</tr>
</table>

<hr>

<p><strong>7. Business Positioning</strong></p>

<ul>
<li><strong>Category:</strong> near-field reference monitor (compact)</li>
<li><strong>Target users:</strong> DAW-based producers, desktop mastering environments, critical listening stations</li>
</ul>

<p><strong>Target COGS:</strong> ~$140 USD<br>
<strong>Target MSRP:</strong> ~$449 USD</p>

<hr>

<p><strong>8. Known Trade-offs</strong></p>

<ul>
<li>not designed for large-room SPL performance</li>
<li>not optimized for cinematic bass extension</li>
<li>limited spatial field compared to large monitors</li>
</ul>

<hr>

<p><strong>9. Comparison Baseline</strong></p>

<table>
<tr>
<th>System</th>
<th>Strength</th>
<th>Weakness</th>
</tr>
<tr>
<td>DSP-based monitors</td>
<td>room correction</td>
<td>latency + signal processing dependency</td>
</tr>
<tr>
<td>plastic cabinet monitors</td>
<td>low cost</td>
<td>higher enclosure resonance</td>
</tr>
<tr>
<td>Rectifier Mini-Node</td>
<td>mechanical stability</td>
<td>less correction flexibility</td>
</tr>
</table>

<hr>

<p><strong>10. Validated Hypothesis</strong></p>

<p>The system tests the proposition that controlled enclosure mass and rigidity can reduce time-domain smearing and high-mid resonance artifacts in near-field monitoring without reliance on DSP correction.</p>

<hr>

<p><strong>11. Open Verification</strong></p>
<HR>
<strong>12. Measurement and Validation Framework</strong>

All system performance claims are intended to be evaluated using:

- Frequency response (anechoic or quasi-anechoic)
- Impulse response analysis
- Cumulative spectral decay (waterfall)
- Enclosure vibration measurement (accelerometer or laser vibrometry)
- Harmonic distortion testing at standardized SPL levels

No claims assume subjective evaluation as primary validation method.

<p>All acoustic claims are intended to be validated via frequency response measurement, impulse response testing, and enclosure vibration analysis. Independent measurement is encouraged.</p>

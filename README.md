<p><strong>Sovereign Throw Node</strong><br>
High-SPL Portable Audio System<br>
Open Hardware Manifest (CERN-OHL-S)</p>

<hr>

<p><strong>1. System Overview</strong></p>
<p>The Sovereign Throw Node is a portable high-SPL loudspeaker system designed for controlled long-throw audio projection in open environments.</p>

<p>The design prioritizes transient headroom, reduced early compression, controlled directivity, and mechanical enclosure stability.</p>

<p>It is optimized for near-field to mid-field projection (1m–10m).</p>

<hr>

<p><strong>2. Electrical Architecture</strong></p>

<p><strong>2.1 Power System</strong></p>
<ul>
<li>36V DC rail architecture</li>
<li>high-current battery management system (≥30A continuous capability recommended)</li>
</ul>

<p><strong>Purpose:</strong> Increased voltage headroom reduces early onset of amplifier clipping under transient peaks.</p>

<p><strong>2.2 Amplification Stage</strong></p>
<ul>
<li>Class-D amplifier platform based on TPA3255 module</li>
</ul>

<p><strong>Configuration goals:</strong></p>
<ul>
<li>low distortion at high output power</li>
<li>high efficiency under battery load</li>
<li>stable performance into low impedance loads</li>
</ul>

<hr>

<p><strong>3. Acoustic System</strong></p>

<p><strong>3.1 Transducer</strong></p>
<ul>
<li>constant directivity horn system (60° × 40° target dispersion)</li>
</ul>

<p><strong>Purpose:</strong></p>
<ul>
<li>maintain SPL consistency over distance</li>
<li>reduce off-axis energy loss in open environments</li>
</ul>

<p><strong>3.2 Enclosure</strong></p>
<ul>
<li>15mm Baltic birch plywood</li>
<li>cross-braced internal structure</li>
<li>sealed or semi-sealed tuning depending on deployment mode</li>
</ul>

<p><strong>Tuning target:</strong> ~45 Hz system resonance (application-dependent)</p>

<hr>

<p><strong>4. Signal Path Philosophy</strong></p>

<p>The system uses a minimal processing chain:</p>
<ul>
<li>no mandatory DSP-based dynamic limiting</li>
<li>analog gain staging preferred at input stage</li>
<li>system headroom preserved through electrical design, not digital compression</li>
</ul>

<hr>

<p><strong>5. Performance Targets</strong></p>

<p><strong>5.1 SPL Behavior</strong></p>
<ul>
<li>sustained high output without early limiting artifacts</li>
<li>reduced perceived compression at high drive levels</li>
</ul>

<p><strong>5.2 Frequency Behavior</strong></p>
<ul>
<li>controlled low-frequency extension (dependent on enclosure mode)</li>
<li>stable midrange projection via horn loading</li>
<li>reduced off-axis high-frequency collapse</li>
</ul>

<p><strong>5.3 Distortion Targets</strong></p>
<ul>
<li>low-order harmonic distortion maintained under high load conditions</li>
<li>compression behavior delayed via voltage headroom</li>
</ul>

<hr>

<p><strong>6. Known Trade-offs</strong></p>
<ul>
<li>increased power system complexity</li>
<li>higher weight due to enclosure and battery system</li>
<li>reduced portability compared to 12–24V consumer systems</li>
</ul>

<hr>

<p><strong>7. Design Hypothesis</strong></p>

<p>The system evaluates the proposition that increasing electrical headroom and enclosure rigidity reduces early dynamic compression and improves perceived transient clarity in portable high-SPL systems.</p>

<hr>

<p><strong>8. Safety Notice</strong></p>

<p>This system is capable of producing SPL levels that can cause hearing damage.</p>

<p>Recommended precautions:</p>
<ul>
<li>hearing protection during calibration</li>
<li>controlled testing environment</li>
<li>adherence to local SPL regulations</li>
</ul>

<hr>

<p><strong>9. Open Hardware Status</strong></p>

<p>This design is released under CERN-OHL-S for independent verification and modification.</p>

<hr>

<p><strong>10. Interpretive Naming Layer (Non-Technical Reference)</strong></p>

<ul>
<li>“Vitrification Kernel” → internal design codename (not a physical component)</li>
<li>“48 Hz resonance shaping” → system tuning region (45–55 Hz depending on enclosure volume)</li>
<li>“Transient reinforcement” → amplifier headroom behavior under peak load</li>
</ul>

<p>These terms are descriptive, not literal physical mechanisms.</p>

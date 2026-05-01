<p><strong>Sovereign Throw Node — Acoustic Engine Specification (Engineering Layer)</strong></p>

<hr>

<p><strong>1. Input Conditioning Stage</strong></p>

<p><strong>1.1 High-Frequency Attenuation Filter</strong></p>

<p>A 2nd-order Sallen-Key low-pass filter is used at the pre-amplification stage.</p>

<ul>
<li>Purpose: reduce high-frequency content above system tuning threshold</li>
<li>Function: smooth high-frequency response prior to amplification</li>
<li>Implementation: standard Sallen-Key topology</li>
</ul>

<p>Note: This is a conventional analog filter stage and should be evaluated using standard frequency response measurements.</p>

<hr>

<p><strong>1.2 Low-Frequency Resonant Shaping</strong></p>

<p>A gyrator-based resonant circuit is used to introduce controlled low-frequency emphasis.</p>

<ul>
<li>Center frequency: 48 Hz</li>
<li>Q factor: 1.85 (moderate resonance width)</li>
<li>Purpose: low-frequency emphasis for near-field and open-air projection consistency</li>
</ul>

<p>Note: This is a standard resonant EQ circuit implemented in analog domain.</p>

<hr>

<p><strong>2. Transducer and Acoustic Loading</strong></p>

<p><strong>2.1 Driver Configuration</strong></p>

<ul>
<li>Coaxial or compression driver system</li>
<li>Horn-loaded output stage</li>
<li>Constant directivity horn: 60° × 40°</li>
</ul>

<p><strong>2.2 Acoustic Objective</strong></p>

<ul>
<li>Maintain forward energy concentration over distance</li>
<li>Reduce off-axis high-frequency loss</li>
<li>Improve intelligibility in open-air environments</li>
</ul>

<hr>

<p><strong>3. Power Architecture</strong></p>

<p><strong>3.1 Supply System</strong></p>

<ul>
<li>36V DC internal rail architecture via step-up conversion</li>
<li>Battery configuration: 10S2P lithium-ion pack</li>
<li>Continuous discharge capability: ≥30A (BMS controlled)</li>
</ul>

<p><strong>3.2 Amplification Stage</strong></p>

<ul>
<li>Class-D amplifier based on TPA3255 module</li>
<li>High-efficiency switching topology</li>
<li>Designed for high headroom operation under dynamic load</li>
</ul>

<p><strong>3.3 System Headroom Objective</strong></p>

<ul>
<li>Prevent early clipping under transient peaks</li>
<li>Maintain linear amplification behavior within operating envelope</li>
</ul>

<hr>

<p><strong>4. System-Level Design Intent (Non-Engineering Layer)</strong></p>

<ul>
<li>High-frequency filtering is intended to reduce perceived harshness in high-output environments</li>
<li>Low-frequency resonance shaping is intended to improve perceived impact at distance</li>
<li>High-voltage rail design is intended to maintain transient stability under load</li>
</ul>

<hr>

<p><strong>5. Safety Considerations</strong></p>

<p>This system is capable of producing sound pressure levels that may cause hearing damage.</p>

<ul>
<li>Hearing protection is recommended during calibration and testing</li>
<li>Compliance with local SPL regulations is required</li>
</ul>

<hr>

<p><strong>6. Measurement Validation Targets</strong></p>

<ul>
<li>Frequency response linearity (± tolerances defined per deployment)</li>
<li>Harmonic distortion under high load</li>
<li>Compression onset threshold vs input power</li>
<li>Directivity consistency across horn dispersion pattern</li>
</ul>

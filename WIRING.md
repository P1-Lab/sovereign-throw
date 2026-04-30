<div style="font-family: sans-serif; max-width: 850px; line-height: 1.6; color: #1a1a1a; border: 1px solid #333; padding: 30px; background-color: #ffffff;">

  <div style="border-bottom: 2px solid #000; padding-bottom: 10px; margin-bottom: 25px;">
    <h1 style="margin: 0; font-size: 1.5rem; letter-spacing: 0.05em; text-transform: uppercase;">System Layout & Wiring Manifest</h1>
    <p style="margin: 5px 0 0 0; color: #d9411e; font-weight: bold; font-size: 0.85rem;">PROTOCOL: Star-Ground Isolation / High-Current Integrity</p>
  </div>

  <section style="margin-bottom: 30px;">
    <h3 style="background: #000; color: #fff; padding: 8px 12px; font-size: 1rem; display: inline-block;">SECTION 1: THE SIGNAL PATH</h3>
    <div style="margin-top: 15px; border-left: 2px solid #eee; padding-left: 20px;">
      <ul style="list-style: none; padding: 0;">
        <li style="margin-bottom: 12px;"><strong>1. Input Interface:</strong> Balanced XLR / 1/4" TRS Combo Jack.</li>
        <li style="margin-bottom: 12px;"><strong>2. Sovereign Pre-Amp Stage:</strong> 16.2kHz Filter + 48Hz Bloom + JFET Saturation.</li>
        <li style="margin-bottom: 12px;"><strong>3. Gain Control:</strong> Precision Logarithmic Potentiometer.</li>
        <li style="margin-bottom: 12px;"><strong>4. Power Stage:</strong> TPA3255 High-Power Module.</li>
        <li><strong>5. Output Delivery:</strong> 10AWG Pure Copper to Transducer.</li>
      </ul>
    </div>
  </section>

  <section style="margin-bottom: 30px;">
    <h3 style="background: #000; color: #fff; padding: 8px 12px; font-size: 1rem; display: inline-block;">SECTION 2: POWER ARCHITECTURE</h3>
    <div style="margin-top: 15px; border-left: 2px solid #eee; padding-left: 20px;">
      <ul style="list-style: none; padding: 0;">
        <li style="margin-bottom: 12px;"><strong>Energy Source:</strong> 10S2P Lithium-Ion Pack (36V Nominal).</li>
        <li style="margin-bottom: 12px;"><strong>BMS Specs:</strong> 30A continuous discharge capacity.</li>
        <li><strong>DC Distribution:</strong> 14AWG rails with 1000uF/50V low-ESR reservoir.</li>
      </ul>
    </div>
  </section>

  <div style="background: #f8f9fa; border: 1px solid #dee2e6; padding: 15px; font-size: 0.9rem;">
    <strong>Mandatory Grounding Logic:</strong> All stage grounds must meet at a single "Star Ground" point near the battery negative terminal.
  </div>

</div>

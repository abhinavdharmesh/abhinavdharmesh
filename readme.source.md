# Abhinav Dharmesh

```aura width=800 height=290
<div style={{
  display: 'flex',
  flexDirection: 'column',
  justifyContent: 'space-between',
  width: '100%',
  height: '100%',
  backgroundColor: '#0a0a0a',
  padding: '30px',
  borderRadius: '12px',
  border: '1px solid #333333',
  fontFamily: 'monospace',
  color: '#e2e8f0',
  position: 'relative'
}}>

  {/* Terminal Title Bar */}
  <div style={{ display: 'flex', justifyContent: 'space-between', alignItems: 'center', width: '100%', borderBottom: '1px solid #222222', paddingBottom: '14px' }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
      <div style={{ width: '10px', height: '10px', borderRadius: '50%', backgroundColor: '#ef4444', display: 'flex' }}></div>
      <div style={{ width: '10px', height: '10px', borderRadius: '50%', backgroundColor: '#eab308', display: 'flex' }}></div>
      <div style={{ width: '10px', height: '10px', borderRadius: '50%', backgroundColor: '#22c55e', display: 'flex' }}></div>
      <span style={{ color: '#64748b', fontSize: '13px', marginLeft: '8px', display: 'flex' }}>kernel@local:~</span>
    </div>
    
    {/* Live Pulsing Status Indicator using inline SVG + SMIL (Sanitization Proof) */}
    <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
      <svg width="24" height="24" viewBox="0 0 24 24" style={{ display: 'flex' }}>
        {/* Pulsing Outer Ring */}
        <circle cx="12" cy="12" r="4" fill="none" stroke="#38bdf8" strokeWidth="2">
          <animate attributeName="r" values="4;10;4" dur="2s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="1;0;1" dur="2s" repeatCount="indefinite" />
        </circle>
        {/* Solid Center Dot */}
        <circle cx="12" cy="12" r="3" fill="#38bdf8" />
      </svg>
      <span style={{ fontSize: '11px', color: '#38bdf8', fontWeight: 'bold', letterSpacing: '1px', display: 'flex' }}>SYSTEM_ONLINE</span>
    </div>
  </div>

  {/* Terminal Output Stream */}
  <div style={{ display: 'flex', flexDirection: 'column', gap: '10px', width: '100%', marginTop: '15px' }}>
    <div style={{ display: 'flex', alignItems: 'center', width: '100%' }}>
      <span style={{ color: '#c678dd', fontWeight: 'bold', width: '120px', display: 'flex' }}>$ identity</span>
      <span style={{ color: '#f8fafc', fontSize: '20px', fontWeight: 'bold', display: 'flex' }}>Abhinav Dharmesh</span>
    </div>

    <div style={{ display: 'flex', alignItems: 'center', width: '100%' }}>
      <span style={{ color: '#98c379', fontWeight: 'bold', width: '120px', display: 'flex' }}>$ role</span>
      <span style={{ color: '#94a3b8', display: 'flex' }}>Physics Undergraduate</span>
    </div>

    <div style={{ display: 'flex', alignItems: 'flex-start', width: '100%', marginTop: '4px' }}>
      <span style={{ color: '#e5c07b', fontWeight: 'bold', width: '120px', display: 'flex' }}>$ stack</span>
      <div style={{ display: 'flex', gap: '8px', flexWrap: 'wrap' }}>
        <span style={{ backgroundColor: '#1e1e1e', color: '#e2e8f0', padding: '3px 8px', borderRadius: '4px', border: '1px solid #333333', fontSize: '12px', display: 'flex' }}>Python/C++</span>
        <span style={{ backgroundColor: '#1e1e1e', color: '#e2e8f0', padding: '3px 8px', borderRadius: '4px', border: '1px solid #333333', fontSize: '12px', display: 'flex' }}>Bash/Linux</span>
        <span style={{ backgroundColor: '#1e1e1e', color: '#e2e8f0', padding: '3px 8px', borderRadius: '4px', border: '1px solid #333333', fontSize: '12px', display: 'flex' }}>CORSIKA</span>
        <span style={{ backgroundColor: '#1e1e1e', color: '#e2e8f0', padding: '3px 8px', borderRadius: '4px', border: '1px solid #333333', fontSize: '12px', display: 'flex' }}>Geant4</span>
      </div>
    </div>
  </div>

  {/* Active Prompt Line with SMIL Blinking Cursor */}
  <div style={{ display: 'flex', alignItems: 'center', width: '100%', marginTop: '15px', borderTop: '1px solid #222222', paddingTop: '15px' }}>
    <span style={{ color: '#e06c75', marginRight: '8px', display: 'flex' }}>➜</span>
    <span style={{ color: '#abb2bf', display: 'flex' }}>Architecting data pipelines and simulation tools for astroparticle physics</span>
    
    {/* Custom SVGs containing native SMIL blinking animations */}
    <svg width="8" height="15" style={{ display: 'flex', marginLeft: '6px' }}>
      <rect width="8" height="15" fill="#e06c75">
        <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite" />
      </rect>
    </svg>
  </div>
</div>

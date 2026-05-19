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
  {/* CSS Keyframes Injection for Live Animations */}
  <style>{`
    @keyframes blink {
      0%, 100% { opacity: 1; }
      50% { opacity: 0; }
    }
    @keyframes radar {
      0% { opacity: 1; transform: scale(1); }
      100% { opacity: 0; transform: scale(3); }
    }
    #blinking-cursor {
      animation: blink 1s infinite;
    }
    #live-radar {
      animation: radar 2s infinite ease-out;
      transform-origin: center;
    }
  `}</style>

  {/* Terminal Title Bar */}
  <div style={{ display: 'flex', justifyContent: 'space-between', alignItems: 'center', width: '100%', borderBottom: '1px solid #222222', paddingBottom: '14px' }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
      <div style={{ width: '10px', height: '10px', borderRadius: '50%', backgroundColor: '#ef4444', display: 'flex' }}></div>
      <div style={{ width: '10px', height: '10px', borderRadius: '50%', backgroundColor: '#eab308', display: 'flex' }}></div>
      <div style={{ width: '10px', height: '10px', borderRadius: '50%', backgroundColor: '#22c55e', display: 'flex' }}></div>
      <span style={{ color: '#64748b', fontSize: '13px', marginLeft: '8px', display: 'flex' }}>kernel@local:~</span>
    </div>
    
    {/* Live Pulsing Status Indicator */}
    <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
      <div style={{ position: 'relative', display: 'flex', width: '8px', height: '8px' }}>
        <div id="live-radar" style={{ position: 'absolute', width: '8px', height: '8px', borderRadius: '50%', backgroundColor: '#38bdf8' }}></div>
        <div style={{ width: '8px', height: '8px', borderRadius: '50%', backgroundColor: '#38bdf8', display: 'flex' }}></div>
      </div>
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
      <span style={{ color: '#94a3b8', display: 'flex' }}>Physics Undergraduater</span>
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

  {/* Active Prompt Line with Blinking Cursor */}
  <div style={{ display: 'flex', alignItems: 'center', width: '100%', marginTop: '15px', borderTop: '1px solid #222222', paddingTop: '15px' }}>
    <span style={{ color: '#e06c75', marginRight: '8px', display: 'flex' }}>➜</span>
    <span style={{ color: '#abb2bf', display: 'flex' }}>Architecting data pipelines and simulation tools for astroparticle physics</span>
    <div id="blinking-cursor" style={{ width: '8px', height: '15px', backgroundColor: '#e06c75', marginLeft: '6px', display: 'flex' }}></div>
  </div>
</div>

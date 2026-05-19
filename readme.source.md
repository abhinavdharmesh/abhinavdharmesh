# Abhinav Dharmesh

```aura width=800 height=260
<div style={{
  display: 'flex',
  flexDirection: 'column',
  justifyContent: 'space-between',
  width: '100%',
  height: '100%',
  backgroundColor: '#0d0e15',
  padding: '30px',
  borderRadius: '16px',
  border: '1px solid #2d2f45',
  fontFamily: 'Inter, sans-serif',
  color: '#f5f5f5'
}}>
  {/* Top Row: Name and Title */}
  <div style={{ display: 'flex', justifyContent: 'space-between', alignItems: 'flex-start' }}>
    <div style={{ display: 'flex', flexDirection: 'column' }}>
      <span style={{ fontSize: '32px', fontWeight: 'bold', letterSpacing: '-0.05em', color: '#a855f7' }}>
        Abhinav Dharmesh
      </span>
      <span style={{ fontSize: '16px', color: '#94a3b8', marginTop: '4px' }}>
        Physics Undergraduate
      </span>
    </div>
    <div style={{ padding: '6px 12px', backgroundColor: '#1e1b4b', borderRadius: '20px', border: '1px solid #4c1d95' }}>
      <span style={{ fontSize: '12px', color: '#c084fc', fontWeight: '600' }}>DEI, Agra</span>
    </div>
  </div>

  {/* Middle Row: Core Focus Tags */}
  <div style={{ display: 'flex', gap: '12px' }}>
    <div style={{ display: 'flex', flexDirection: 'column', padding: '12px', backgroundColor: '#11131f', borderRadius: '8px', border: '1px solid #1e293b', width: '31%' }}>
      <span style={{ fontSize: '11px', color: '#64748b', textTransform: 'uppercase' }}>Research Focus</span>
      <span style={{ fontSize: '14px', color: '#e2e8f0', marginTop: '4px', fontWeight: '500' }}>Astroparticle Physics</span>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', padding: '12px', backgroundColor: '#11131f', borderRadius: '8px', border: '1px solid #1e293b', width: '31%' }}>
      <span style={{ fontSize: '11px', color: '#64748b', textTransform: 'uppercase' }}>Simulation Engines</span>
      <span style={{ fontSize: '14px', color: '#e2e8f0', marginTop: '4px', fontWeight: '500' }}>CORSIKA (7/8) & Geant4</span>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', padding: '12px', backgroundColor: '#11131f', borderRadius: '8px', border: '1px solid #1e293b', width: '31%' }}>
      <span style={{ fontSize: '11px', color: '#64748b', textTransform: 'uppercase' }}>Technical Stack</span>
      <span style={{ fontSize: '14px', color: '#e2e8f0', marginTop: '4px', fontWeight: '500' }}>Python, C++, PyQt6, ROOT</span>
    </div>
  </div>

  {/* Bottom Row: Core Mission Statement */}
  <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
    <div style={{ width: '8px', height: '8px', backgroundColor: '#10b981', borderRadius: '50%' }}></div>
    <span style={{ fontSize: '13px', color: '#94a3b8' }}>
      Developing high-throughput data processing pipelines and visualization tools for cosmic ray air-shower experiments.
    </span>
  </div>
</div>

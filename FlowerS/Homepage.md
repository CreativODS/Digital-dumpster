---
title: CeativODS test101
subtitle: Prueba 01 día 00
cover: https://images.unsplash.com/photo-1761582277004-7dd5257b8b49?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=690
layout: home
---


```yaml
# Good
title: "Hola mundo"

# Avoid
title: "Setup Guide"
```
Holamundo
title: HolaMundo

# Chasing Auroras in Norway

Chasing Auroras in Norway.md


export default function Hero({ title, subtitle, image }) {
  return (
    <div
      className="hero"
      style={{
        backgroundImage: `url(${image})`,
        backgroundSize: "cover",
        backgroundPosition: "center",
      }}
    >
      <div className="overlay">
        <h1>{title}</h1>
        <h2>{subtitle}</h2>
      </div>
    </div>
  );
}



<Hero
  title="Gentler Futures 2024"
  subtitle="Towards Urban Self-sufficiency"
  image="/images/hero-home.jpg"
/>

<Section id="program">
  <h2>Program Schedule</h2>
  <EventList events={programData} />
</Section>

<CtaButton href="https://www.tickettailor.com" label="Reserve a spot ↗" />

<Section id="contact">
  <h2>Contáctame, necesito dinero</h2>
  <p>CreativODS donde nos quejamos de todo</p>
  <p>Inquiries ↗ <a href="mailto:...">...</a></p>
</Section>


npm run dev



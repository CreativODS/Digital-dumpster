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

---
title: "Gentler Futures 2024"
subtitle: "Towards Urban Self-sufficiency"
cover: "/images/hero-home.jpg"
layout: "home"
---

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
  <h2>Contact us</h2>
  <p>Gentler Futures Festival is a not-for-profit initiative …</p>
  <p>Inquiries ↗ <a href="mailto:...">...</a></p>
</Section>



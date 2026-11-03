# SCHLÜSSEL GmbH Kreuztal — Sicherheit ist ein Handwerk

**Live-Website:** 🌐 [schlussel.vercel.app](https://schlussel.vercel.app)

Cinematische One-Page-Website für den Meisterbetrieb SCHLÜSSEL GmbH in Kreuztal — ein interaktives 3D-Hologramm eines Sicherheitszylinders, das beim Scrollen wie ein technischer Zeichnungsfilm erwacht.

## Das Konzept — „HOLO EDITION"

Ein virtuelles Laboratorium auf klinisch weißem Grund: Ein fluoreszierend blaues Hologramm aus Drahtgittermodell eines Schlüssels und eines Zylinders wird von einem Projektor in den Raum gestrahlt. Der Scrollverlauf steuert eine durchgehende Kamerafahrt durch sechs Szenen:

| Szene | Kapitel | Erlebnis |
|---|---|---|
| 01 | **Titel** | Hologramm materialisiert sich, Orbitalsatelliten scannen den Schlüssel |
| 02 | **Das Profil** | Drehtisch, CAD-Bemaßungen, Blattrahmen mit Zone A–C |
| 03 | **Der Zylinder** | Schnittansicht: Stift-Pakete, Doppelfedern, Schraffur |
| 04 | **Die Mechanik** | Schlüssel fährt exakt auf der Schließachse ein |
| 05 | **Der Klick** | Drehung um −90°, Schockwelle, Stifte geben frei |
| 06 | **Der Dienst** | Auflösung zum Klartext: Leistungen, FAQ, Notruf |

## Technische Details

- **Single-File-Architektur** — alles in einer `index.html` (~2.500 Zeilen)
- **three.js 0.160** — prozedurales Schlüssel-/Zylinder-Hologramm (ExtrudeGeometry, EdgesGeometry, CSS2D-Labels)
- **GSAP 3 + ScrollTrigger + Lenis** — ein Master-Fortschritt `P ∈ [0..1]` steuert Kamera, Choreografie, HUD
- **Selbstzeichnende Linien** — `setDrawRange`-Animation lässt die technische Zeichnung live entstehen
- **CAD-Detailtiefe** — Bemaßungslinien mit Pfeilspitzen, Stückliste (BOM-Ballons), Blattschnitt A–A mit 45°-Schraffur, Titelfeld „Zeichnung Nr. SK-1985-05, Maßstab 5:1"
- **Lebendiger Hintergrund** — Orbitalschwärme, Zahnräder, Topografie-Konturen, Telemetrie-Spalten, Stadt-Silhouette
- **Web-Audio-Sounddesign** — synthetisierte Klick-, Tick- und Tüngeräusche (optional zuschaltbar)
- **Accessibility** — `prefers-reduced-motion` wird respektiert, Fallback ohne WebGL

## Kontakt (Inhalt der Website)

**SCHLÜSSEL GmbH Kreuztal** · Meisterbetrieb
24/7-Notdienst · Schlüsseldienst · Schließanlagen · Kreuztal, Kreis Siegen-Wittgenstein

---

*Design & Code: [OK Studio](https://ok-studio-umber.vercel.app/)*

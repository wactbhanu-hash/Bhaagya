# भाग्य (Bhagya) — V3 Real Calculation Core

V3 adds a real astronomical calculation layer using Astronomy Engine for Kotlin/JVM 2.1.19.

Astronomy Engine is MIT licensed and supports Kotlin/JVM. The project states that its calculations are designed to stay within approximately ±1 arcminute and are tested against NOVAS/JPL Horizons. See:
https://github.com/cosinekitty/astronomy

Important:
- This is an astronomy calculation engine, not a scientific validation of astrology.
- Vedic interpretations are stored separately from astronomical calculations.
- Lahiri ayanamsha in this V3 is implemented as a documented polynomial approximation and must be benchmarked against the final chosen ephemeris/reference before production release.
- Swiss Ephemeris is NOT bundled in V3 because its official licensing is AGPL or Professional License; a commercial closed-source release must resolve that license before using it.

V3 calculates:
- UTC time from local birth time + timezone offset
- planetary geocentric ecliptic longitude
- Sun and Moon
- Mercury, Venus, Mars, Jupiter, Saturn, Uranus, Neptune, Pluto
- mean Rahu/Ketu
- Lahiri-style sidereal longitude
- Rashi
- Nakshatra + Pada
- sidereal ascendant
- whole-sign houses
- approximate daily motion / retrograde flag

Next:
- exact production ayanamsha benchmark
- Panchanga
- Vimshottari start balance
- divisional charts
- source-backed rule database
- golden reference-chart test suite
- chart rendering and Play Store release configuration

# V4 Notes

## What was added
- Vimshottari major-dasha start lord from Moon's sidereal nakshatra.
- Birth-balance calculation.
- Major dasha period timeline model.
- Basic Panchanga primitives: tithi, paksha, yoga number, karana, vara.
- Source-rule provenance model.
- Basic chart-grid UI component.
- Unit tests for dasha and panchanga primitives.

## Production accuracy caveats
1. Panchanga needs local sunrise/sunset and true tithi/yoga/karana transition times, not just instantaneous birth longitudes.
2. Vimshottari timing should use a consistent year/day convention and verified ephemeris output.
3. Ayanamsha must be benchmarked against the chosen production ephemeris.
4. Rule texts and verse locators must be verified from specific editions before being presented as historical evidence.

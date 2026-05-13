# Poly-Chess

**Code:** XPC  
**Remote:** https://github.com/Lexxicc/Poly-Chess.git  
**Version:** v0.0.3 (`Poly-Chess v0.0.3.html`)  
**Genre:** Board game / chess variant

## Tech
- DOM-based rendering (no canvas)
- Vanilla JS + Tailwind CSS via CDN
- Single-file HTML — no build step

## localStorage
- `polychess_hs` — high score
- `tacticon_elo` — shared ELO rating (shared key with XChequers.CQ)

## Notes
- Uses `tacticon_elo` as a shared ELO key — also used by Chequers (XCQ)
- Key uses `polychess_` prefix, not `XPC_`

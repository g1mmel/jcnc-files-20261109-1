# jcnc-files-20261109-1 — Naval subsystems

3D model collection for shipboard equipment (LHD / Wasp-class amphibious
assault ship context). All models sourced from Sketchfab, downloaded as GLB,
triangle counts verified before commit.

## subsystems/

Dedicated subsystem models (matched equipment):

| File | Equipment | Triangles |
|---|---|---|
| ciws-phalanx-mk15.glb | Mk 15 Phalanx CIWS (integral radar assembly) | 214,730 |
| mk41-vls.glb | Mk 41 Vertical Launching System | 768,004 |
| mk32-svtt-torpedo-tubes.glb | Mk 32 Surface Vessel Torpedo Tubes (SVTT) | 25,102 |
| mk38-naval-gun-mount.glb | Mk 38 gun mount (EO/IR sensor host) | 121,879 |
| rim7-sea-sparrow.glb | RIM-7 Sea Sparrow missile | 47,628 |
| rim162-essm.glb | RIM-162 Evolved Sea Sparrow Missile (ESSM) | 22,104 |

Full-ship LHD references (parent platform):

| File | Platform | Triangles |
|---|---|---|
| lhd-uss-wasp-hipoly.glb | LHD USS Wasp (high poly) | 432,677 |
| uss-wasp-lhd1.glb | USS Wasp LHD-1 | 129,104 |
| uss-tarawa-lha1.glb | USS Tarawa LHA-1 | 255,142 |
| uss-america-lha6.glb | USS America LHA-6 | 189,667 |

Proxy / analog models (NOT the actual designated system — labelled for
transparency; do not treat as the named equipment):

| File | Proxy for | Triangles |
|---|---|---|
| decoy-launcher-rheinmetall-mass.glb | SRBOC Mk 36 / Mk 137 (analog decoy launcher, Rheinmetall MASS) | 31,040 |
| radome-generic.glb | SATCOM / comms radome housing (generic shell) | 49,516 |
| satcom-antenna-manpack.glb | SATCOM antenna (manpack, ground — not shipboard) | 385,788 |
| whip-antenna-telescopic.glb | Mast whip antenna (handheld telescopic — not ship mast) | 17,822 |
| radio-terminal-mids-jtrs.glb | TACAN (MIDS-JTRS radio terminal, JTIDS band-adjacent) | 10,960 |

## No dedicated Sketchfab model found (gaps)

These systems have no matching high-poly model on Sketchfab as of
2026-11-09. No model is included rather than fabricate a wrong designation:

- AN/WSC-9(V) / AN/USC-69 SATCOM radome housing
- Aft / unidentified communications radome housings
- AS-3772B/U / AS-3773B/U / AS-2537C/SR mast whip antennas
- AN/SLQ-32(V) electronic-warfare system
- Nulka Mk 53 Decoy Launching System
- AN/SPS-67 surface-search radar
- AN/SPS-73 (NGSSR) surface-search radar
- Mk 95 Sea Sparrow fire-control director / illuminator
- TACAN AN/URN-25 / OE-4691 antenna

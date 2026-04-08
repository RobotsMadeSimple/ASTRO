# ASTRO

A 4-axis robotic arm featuring a rotary base (J1), CoreXY vertical (J2), CoreXY reach (J3), and end-of-arm tooling (J4).

## Repository Structure

```
ASTRO/
├── CAD/                        # STEP files and assembly images per joint
│   ├── J1_Rotary_Base/
│   ├── J2_CoreXY_Vertical/
│   ├── J3_CoreXY_Reach/
│   └── J4_EOAT/
├── print_files/                # STLs organised by joint
│   ├── J1/                     # 5 parts
│   ├── J2/                     # 3 parts
│   ├── J3/                     # 6 parts
│   ├── J4/
│   ├── Electrical/             # 3 parts
│   └── Shared/
├── docs/                       # Assembly manual and BOM
└── BOM.csv
```

## Print Files

The latest STLs are available as a zip on the [Releases](../../releases/latest) page.

## Joints

| Joint | Name | Type |
|-------|------|------|
| J1 | Rotary Base | Belt-driven rotation |
| J2 | CoreXY Vertical | Linear vertical axis |
| J3 | CoreXY Reach | Linear horizontal reach |
| J4 | EOAT | End of arm tooling |

## Assembly

See `docs/` for the full assembly manual. Each joint folder under `CAD/` contains step-by-step assembly images.

# wujihand-hardware-design

This repository contains the mechanical design files for the **WujiHand** robotic hand hardware, organized by component type and assembly configuration. All models are provided in `.step` format for CAD compatibility and downstream manufacturing or simulation use.

```wujihand-hardware-design/
├── adapter/                  # Adapter mounts for different connection types
│   ├── Impact-Resistant-Adapter.step      → Shock-Absorbing Adapter Mount
│   └── Direct-Adapter-Mount.step        → Direct-Connect Adapter Mount
│
├── simplified-structural/    # Simplified structural frames (no soft goods)
│   ├── WH_simplified_left_frame&temporarytips.step
│   ├── WH_simplified_left_frameonly.step
│   ├── WH_simplified_right_frame&temporarytips.step
│   └── WH_simplified_right_frameonly.step
│
└── softgoods/                # Structural frames with integrated soft goods (e.g., pouch cells)
    ├── WH_simplified_left_frame&softgoods.step
    └── WH_simplified_right_frame&softgoods.step
```


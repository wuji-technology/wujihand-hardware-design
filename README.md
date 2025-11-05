# wujihand-hardware-design

This repository contains the mechanical design files for the **Wuji Hand** robotic hand hardware, organized by component type and assembly configuration. All models are provided in `.step` format for CAD compatibility and downstream manufacturing or simulation use. Assembly drawings (PDF) and installation guides are included where applicable.

```bash
├── adapter # Adapter mounts for different connection types
│   ├── Adapter-Installation-Instructions.md
│   ├── Direct-Adapter-Mount.step     # Direct-Connect Adapter Mount
│   ├── Impact-Resistant-Adapter.step    # Shock-Absorbing Adapter Mount
│   ├── wuji-hand&Direct-Adapter-assembled-v1.pdf
│   └── wuji-hand&Impact-Resistant-Adapter-assembled-v1.pdf
├── README.md
├── simplified-structural     # Simplified structural frames (no softgoods)
│   ├── WH_simplified_left_frame&temporarytips.step
│   ├── WH_simplified_left_frameonly.step
│   ├── WH_simplified_right_frame&temporarytips.step
│   └── WH_simplified_right_frameonly.step
└── softgoods      # Structural frames with integrated softgoods (sponge)
    ├── WH_simplified_left_frame&softgoods.step
    └── WH_simplified_right_frame&softgoods.step
```

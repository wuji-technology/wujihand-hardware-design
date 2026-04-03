# wujihand-hardware-design

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Hardware design file repository for Wuji Hand. This repository contains mechanical CAD files organized by component type and assembly configuration, including adapter mounts, structural frames, and softgoods. All models are provided in STEP format for CAD compatibility and downstream manufacturing or simulation use.

**Get started with [Quick Start](#quick-start). For detailed documentation, please refer to [Wuji Hand Overview](https://docs.wuji.tech/docs/en/wuji-hand/latest/overview/) on Wuji Docs Center.**

## Repository Structure

```text
├── adapter/                     // Adapter mounts with assembly drawings and installation guide
│   ├── Adapter-Installation-Instructions.md
│   ├── Direct-Adapter-Mount.step
│   ├── Impact-Resistant-Adapter.step
│   ├── wuji-hand&Direct-Adapter-assembled-v1.pdf
│   └── wuji-hand&Impact-Resistant-Adapter-assembled-v1.pdf
├── simplified-structural/       // Simplified structural frames (left/right, with/without temporary tips)
│   ├── WH_simplified_left_frame&temporarytips.step
│   ├── WH_simplified_left_frameonly.step
│   ├── WH_simplified_right_frame&temporarytips.step
│   └── WH_simplified_right_frameonly.step
├── softgoods/                   // Structural frames with integrated softgoods (left/right)
│   ├── WH_simplified_left_frame&softgoods.step
│   └── WH_simplified_right_frame&softgoods.step
└── README.md
```

## Quick Start

### Installation

```bash
git clone https://github.com/wuji-technology/wujihand-hardware-design.git
cd wujihand-hardware-design
```

### Running

Open any `.step` file in your preferred CAD software (SolidWorks, Fusion 360, FreeCAD, etc.). Refer to `adapter/Adapter-Installation-Instructions.md` for adapter installation instructions.

## Contact

For any questions, please contact [support@wuji.tech](mailto:support@wuji.tech).

# icir_phri_viz

RViz and rqt visualization configurations for the iCIR pHRI project.

## Contents

| File | Description |
|------|-------------|
| `rviz/icir_phri_panda_husky_real_rviz.rviz` | RViz config for Panda + Husky system |
| `rviz/icir_phri_panda_real_rviz.rviz` | RViz config for Panda arm only |
| `rqt/icir_phri_panda_husky_real.perspective` | rqt perspective for Panda + Husky system |
| `rqt/icir_phri_panda_real.perspective` | rqt perspective for Panda arm only |

## Usage

```bash
roslaunch icir_phri_viz ns1_phri_2f_85_viz.launch
```

## Note

For full system context, see [icir_phri_panda_husky](https://github.com/iCIRLab/icir_phri_panda_husky).

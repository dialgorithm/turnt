<h1 align="center">
  turnt
  <br>
</h1>

<h4 align="center">
    4 dof robotic arm with turntable base
</h4>

![arm](assets/3dinit.png)

## it features:

- 4 degrees of freedom: base rotation, shoulder, elbow, wrist
- MG996R servos for base/shoulder (high torque), SG90 servos for elbow/wrist
- ~15–20 cm planar reach-and-grasp workspace

## design

**base** has a circular turntable with bearing balls (1/8" balls) for smooth rotation, MG996R servo is housed within the turntable mechanism.

**shoulder & elbow** uses a MG996R for higher-torque lifting, while the elbow uses an SG90.

**wrist & gripper** rotation is driven by an SG90.

## wiring

![wiring](assets/wiring.png)

## CAD

| top view                           | bottom view                              |
| ---------------------------------- | ---------------------------------------- |
| ![top view](assets/fusion_top.png) | ![bottom view](assets/fusion_bottom.png) |

| side view                         |
| --------------------------------- |
| ![render](assets/fusion_side.png) |

## BOM

the complete bill of materials is available in [`bom.csv`](bom.csv).

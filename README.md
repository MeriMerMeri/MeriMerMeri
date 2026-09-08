<p align="center">
  <img src="https://raw.githubusercontent.com/MeriMerMeri/MeriMerMeri/a0a74748cab5052e30021ee5b35a66abe5ef33d5/assets/fpga-hero.svg" alt="Animated 3D FPGA hybrid controller" width="100%" />
</p>

<p align="center">
  <a href="mailto:umairali33862@gmail.com"><img src="https://img.shields.io/badge/Email-umairali33862%40gmail.com-0d1b2a?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/MeriMerMeri"><img src="https://img.shields.io/badge/GitHub-MeriMerMeri-111827?style=for-the-badge&logo=github" alt="GitHub" /></a>
</p>

## ⚡ The mission

I build digital control systems for machines that move. My focus is the overlap
between **Verilog / FPGA design**, **power electronics**, and **motor control**:
turning physical signals into reliable real-time hardware.

```text
signal → FPGA logic → power stage → motion → feedback
```

## 🧠 In the lab now

**Approximate computing for dynamic PWM motor-control engines.** I am testing
how far feedback-path quantization and approximate arithmetic can reduce FPGA
area and dynamic power while a mechanical control loop remains stable. The
interesting engineering question is not merely the saving—it is locating the
margin where the hardware becomes meaningfully cheaper without compromising
the plant.

## 🛠️ Featured build

### [FPGA hybrid vehicle controller](https://github.com/MeriMerMeri/fpga-hybrid-vehicle-controller)

An Artix-7 Verilog hybrid-powertrain controller with six-step BLDC commutation,
dead-time insertion, manual torque and closed-loop speed modes, regenerative
braking, coulomb-counted state of charge, and battery / engine arbitration.
Every module is backed by self-checking testbenches and a system-level motor
model.

| Digital control | Energy systems | Engineering stack |
| :-- | :-- | :-- |
| Verilog · Vivado · Synopsys DC · Logisim | BLDC control · PWM · regenerative braking · MPPT | C · MATLAB · Proteus · NI Multisim · Arduino · AutoCAD |

## 🔩 Other systems I have built

- **Hexabot** — ESP32 six-legged robot with 18 MG996R servos, kinematics,
  dynamic auto-balancing, and obstacle detection.
- **AM transmitter & receiver** — LC carrier oscillator, Class-C power stage,
  envelope detector, audio amplifier, and low-pass recovery filter.
- **IoT energy monitor** — Arduino / ESP32 voltage and current telemetry with a
  cloud dashboard.
- **Solar MPPT simulation** — PV maximum-power-point tracking modelled and
  tuned in MATLAB.

## 🎓 Background

**BSc Electrical & Electronics Engineering** — European University of Lefke
(CGPA 3.49 / 4.00; Washington Accord degree, MUDEK accredited, HKIE recognised).

Three years as an undergraduate lab assistant gave me a practical instinct for
debugging circuits, building dependable experiments, and helping other people
make their hardware work.

<p align="center"><sub>Open to conversations about FPGA design, motor control, and embedded energy systems.</sub></p>

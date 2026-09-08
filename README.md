# Muhammad Umair Ali

Electrical and Electronics Engineering graduate working in digital design.
Verilog and FPGAs, power electronics, and the place where the two meet: motor
control.

I came to digital design through a lab rather than through a course. Three
years as an undergraduate lab assistant, debugging other people's circuits and
building the experiments they were assessed on, is what made me want to design
the controller instead of the analogue front end around it.

---

### What I am working on

**Approximate computing and quantization in dynamic PWM motor control engines**
— an ongoing research project in Verilog. The idea is that a motor control loop
does not need arithmetic that is correct to the last bit: the plant is
mechanical, it filters, and the feedback path corrects. So I truncate the
feedback path and use approximate arithmetic in the datapath, then measure what
that buys in dynamic power and FPGA LUT utilisation, and how far it can be
pushed before motor stability actually suffers.

The interesting part is not the saving. It is finding the truncation margin
where the loop is still stable but the hardware is meaningfully cheaper.

---

### Selected projects

**FPGA-based hybrid vehicle control and regenerative system** — final year
project. A hybrid powertrain controller written entirely in Verilog on a Xilinx
Artix-7. Six-step BLDC commutation with dead time insertion, a manual torque
mode and a closed-loop speed mode, regenerative braking blended against
friction braking, coulomb-counting state of charge, and arbitration between the
battery and the engine. Self-checking testbenches for every module plus a
system-level simulation against a behavioural motor model.

**Hexabot** — a six-legged biomimetic robot, semester group project. Eighteen
MG996R servos on a Servo2040 controller with an ESP32. Forward and inverse
kinematics, dynamic auto-balancing, and micro-switch obstacle detection.

**AM transmitter and receiver** — a complete AM chain: LC oscillator carrier
generator into a Class-C power amplifier, and a receiver with an envelope
detector, op-amp stage and low-pass filter for audio recovery. Simulated in
Proteus.

**IoT smart energy monitoring** — Arduino/ESP32 with a cloud dashboard for
real-time voltage and current, at 95 percent measurement accuracy.

**Solar MPPT controller simulation** — maximum power point tracking for a PV
array, modelled and tuned in MATLAB.

Also: active low-pass and high-pass filter design verified against measured
frequency response, audio and power amplifier stages, and BLDC PWM control on
an Arduino UNO.

---

### Tools

`Verilog` · `Vivado` · `Synopsys Design Compiler` · `Logisim` · `C` ·
`MATLAB` · `Proteus` · `NI Multisim` · `AutoCAD` · `Arduino`

---

### Background

**BSc Electrical and Electronics Engineering**, European University of Lefke —
CGPA 3.49 / 4.00. Washington Accord degree, MUDEK accredited, HKIE recognised.

**Undergraduate lab assistant**, European University of Lefke — three years
guiding students through analog, digital and embedded systems experiments, and
keeping the teaching lab's equipment working.

**Summer training intern**, Cyprus Turkish Electricity Corporation (KIBTEK) —
power distribution network maintenance, transformer and fuse replacement on
local grid infrastructure, and troubleshooting underground wiring.

---

### Contact

umairali33862@gmail.com

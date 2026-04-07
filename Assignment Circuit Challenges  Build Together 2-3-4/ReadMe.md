 README – Lab Experiments: Motion Detection & Sound Reactive Circuit
 Overview

This lab includes two circuits:

Motion Detection Circuit using LDR and Op-Amp comparator
Sound Reactive LED Circuit using microphone and Op-Amp amplifier

Both circuits demonstrate signal processing using analog components.

 Objectives
Use Op-Amp as comparator and amplifier
Understand voltage divider (LDR & biasing)
Apply RC timing circuits
Control output using transistor switches
Build real-world applications (motion sensor & sound LED)
 Experiment 1: Motion Detection
🔹 Idea

Detect change in light (motion) and turn ON LED for ~5 seconds.

🔹 Key Parts
LDR + 10k resistor → light sensor
Op-Amp → comparator
Potentiometer → sensitivity control
RC circuit → delay
Transistor → LED driver
🔹 Result
LED turns ON when light is blocked
Stays ON ~5 seconds using RC timing
Potentiometer adjusts sensitivity
 Experiment 2: Sound Reactive Light
🔹 Idea

Convert sound into signal and light LEDs based on volume.

🔹 Key Parts
Microphone → sound input
LM358 → amplifier (gain ≈ 1000)
Bias divider → Vcc/2 reference
Capacitor + potentiometer → sensitivity control
Transistor → drives LEDs
🔹 Result
LEDs respond to sound (clap, music)
Sensitivity adjustable
Stronger sound → brighter / more response
💡 Key Concepts Learned
Op-Amp as comparator vs amplifier
Signal amplification (audio)
RC timing circuits
High-pass filtering
Transistor switching
Sensor-based systems (light & sound)
 
 Conclusion

Both circuits successfully demonstrate how analog components can be used to detect environmental changes (light and sound) and control outputs (LEDs). These designs are basic models for real systems like motion sensors and music-reactive lighting.
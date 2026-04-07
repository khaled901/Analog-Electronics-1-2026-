# Full-Wave Rectifier Simulation (LTSpice)

## Name

Khaled Ahmed

## Simulation Setup

* AC Source:

  * Peak Voltage = 100V
  * Frequency = 50 Hz

* Transient Analysis:

  * Stop Time = 40 ms (two full cycles)
  * Time step adjusted for better waveform resolution

---

## Circuit 1: Basic Rectifier (Without Capacitor)

### Description

A full-wave rectifier circuit using diodes and resistors was simulated.

### Observation

* The output voltage is always positive (rectified signal).
* The waveform is not smooth and contains ripples.
* Output voltage is lower than input due to diode voltage drops.

---

## Circuit 2: Bridge Rectifier

### Description

A full-wave bridge rectifier using four diodes.

### Observation

* Both positive and negative halves of the input are converted to positive output.
* Output frequency is doubled compared to input.
* Still not a pure DC signal (pulsating DC).

---

## Circuit 3: Rectifier with Capacitor Filter

### Description

A capacitor (470µF) is added across the load resistor.

### Observation

* The capacitor smooths the output voltage.
* Ripple is significantly reduced.
* Output becomes closer to DC.
* Small ripple remains depending on load and capacitance.

---

## Conclusion

* Full-wave rectifiers convert AC to pulsating DC.
* Adding a capacitor improves the output by reducing ripple.
* Larger capacitance results in smoother DC output.

---

## Notes

* Output voltage is always slightly less than input peak due to diode drops.
* Ripple depends on load resistance and capacitor value.

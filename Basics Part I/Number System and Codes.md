**Transistors**: Either the BJT or MOSFET is used. The two state design enables the transistors to work remarkably well in different temperatures.

**Transistor Register**: here's a two state design. the transistor operate in two modes: transistor with 0V is in cut-off mode while transistor with 5V is in saturation mode.

**Nonsaturated Circuits**: Sometimes when BJT is heavily saturated, extra carriers are stored in the base region. The transistor still cannot come out of saturation until these extra carriers have the time to leave the region. The time it takes for these carriers to leave is called saturation time $t_d$.
The BJT has three modes of operation:
- cutoff mode: the transistor is off (no current flows).
- saturation mode: the transistor is fully on (like a switch).
- active mode: the transistor is partially on and can amplify signals.
For high speed systems, we build nonsaturated circuits by avoiding the saturation mode of transistors using clamping diodes.

**Magnetic cores**: 
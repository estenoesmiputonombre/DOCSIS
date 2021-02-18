# Modulation Scheme

Modulation schemes vary:

- Amplitude.
- Phase.
- Frequency.

In order to transmit more __data__ and __faster__.

__TTL__ (Transistor-to-Transistor Logic) logic circuits have been a fundamental building block of digital circuits sinze 1961.

Digital transmissions, are the values 0s and 1s. For example, is TTL logic, in which case a zero is represented by any voltage
level from __0 to +0.8Vdc__ and a 1 is represented by any voltage level from __+2.2 to +5.0Vdc__. Any other values are ignored.
So in this example, a transmitter uses analog voltage to transmit digital data to the receiver.

## Signals and Modulations

Every complex signal can be represented by the following equation:

`s(t) = A * sin(2 * pi * f*t + theta)`

- where s(t) is the signal as a function of time (t).
- A is the amplitude or voltage of the signal.
- f is the frequency of the signal. DOCSIS downstream would be between __54 - 1000 MHz__.
- Theta is the phase in degrees of the signal.

## Amplitude Modulation

Amplitude Modulation is a method of communicating data when a __carrier wave__ is varied in __direct proportion__ to that of a modulating signal (i.e. baseband digital data).

- What is Amplitude? It is the __peak to peak__ voltage of a signal.
- What is frequency? The rate of a change per second given in Hz. i.e A radio station always remains at the same frequency. It is constant.

An AM receiver consists primarily of a __tunable filter__ and an __envelope detector__, which in simpler sets is a __single diode__.
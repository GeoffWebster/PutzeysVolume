Bruno Putzeys Balanced Volume Control / MAS6116 Digital Control
===============================================================

KiCad V8 files for Bruno Putzeys Balanced Pre-amp with integrated MAS6116 Digital Volume Control Chip.

Circuit modifications from original design includes
* Addition of MAS6116 digital Stereo Volume Control in place of dual linear 10Kohm potentiometer
* Addition of inverting unity gain amplifier driver for driven signal for - output pin. Original was balanced output impedance only
* Addition of Unbalanced output (X5) to provide input to headphone amplifier

Original Bruno Putzeys preamplifier used qty 4 of LM4562 + qty 1 of TL072 (as servo)
Alternatives to LM4562 include
* OPA1642AIDR  595-OPA1642AIDR
* OPA1656ID    595-OPA1656ID

Addition of inverting amplifiers within balanced output (Vout-) adds following components into overall circuit:
U7, U8 OPA1656
R38-41 12K 0805 Thin Film
C28, C29 47pF **DNF**

Addition of unbalanced output for use by external headphone amplifier added connector X5 only.

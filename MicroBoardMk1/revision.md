# pending
 * the ap1117 should have a diode on its output (DB2J31000L). Ive seen LDOs pop when you apply a voltage to them when theyre off.  Will the stm32 be able to operate at 3.3V - .470V?  
 * put a 120 resistor across the MCOM lines to reduce voltage overshoot
 * RN1 isn't necessary since those pins are high impedance input anyways

# applied

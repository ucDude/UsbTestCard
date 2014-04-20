UsbTestCard
==================

A little adapter to measure voltage and current as well as to probe the data signals on USB 2.0 lines.

Bugs: 
#01 INA21x +/- Input lines swapped. 
    -> Looks like negative voltage for current from vower supply to device
	-> Fix: Lift INA21x input pins and corresponding pcb pads. PCB trace are long enough for free-form-soldering in mid air.

# ENG_CHALLENGE

1. Find dimensions for the power supply - Could use the banana to approximate, however the datasheet for the CUS30M-12 has the bolt hole and external dimensions on it
2. Assume it is to be made as cheaply as possible for one-off manufacture, therefor injection moulding and machining are unlikely possibilities (even machining from acetyl which is relatively cheap for prototyping)
  2.1 Possible manufacturing methods:
    - Laser Cut Plastic
      - Unlikely to be a permanent solution, plus many steps during assembly
      - Very cheap
    - 3d Printing
      - If accurate printing is required, likely to go over the $90 price limit
      - Will require post processing for nutserts
    - Folded Sheet Metal
      - Cheap
      - Easy manufacture techniques, will still require post processing to test for burrs and add nutserts
      - Housing can be used for secondary grounding (double protection)

Folded Sheet Metal was chosen due to ease and cost of manufacture.
- Use 0.9mm 300 series stainless steel to prevent corrosion
- Housing components can be laser cut and then folded to shape

Holes for mounting strain relief grommets
  - Not Currently Dimensionally accurate, requires sizing based off the desired wiring for the input and output of the power supply

M3 standoffs are used to provide space between the base plate of the housing and the pcb to prevent short circuits

M3 or smaller (M2/M2.5) Nutserts used for fixturing the two housing components together (approx $4 for 10)

Slotted tabs on the front and rear faces to allow mounting

Slots have been cut into the sides of the housing to allow airflow and keep the power supply from overheating

At the time of design, no manufacturers were available for quotation (Sunday), but from experience, a one-off design like this would cost approximately $40 (halving in price if 20 were being made). 

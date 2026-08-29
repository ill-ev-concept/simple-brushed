# Ethan Brushed Simple


This is the simple version of the brushed motor controller for EV3, my current documentation can be found [here](https://docs.google.com/document/d/1gfZzmsv_RstbJ-Lk0RfqkkH_zSeoGgdf7qZ41NG-Wzg/edit?usp=sharing)


Additionally, the code can be found <a href = "https://gitlab.engr.illinois.edu/ev-concept/software2022-23/embedded/brushed-motors/brushed-motor-simple-26-27">here</a>

Currently works on the bench with minor modifications and problems:

 - Footprint for mosfet is reversed, so bodge wire was used to swap trace for gate pin
 - Buck converter possibly having some issues, previously worked in testing, but now doesnt function so it is being bypassed
 - Gate driver IC seems to pull down the STMs PWM signal to 2 volts peak, which is just enough for it to detect, but 3.3v is prefered



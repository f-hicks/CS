
### homework / lab prep
learn a bit about raspberry pi
some linux commands
some python


## Lab 1
 inputs and outputs (GPIO)
 - LEDs
 - input from switch

interface to an ADC chip
- read analogue voltages
- from LDR
- Thermistor

using python


## Potential dividers
used to work with sensors. I.E. R1 replaced with a sensor. As the sensors resistance changes, the vout also changes, allowing a computer to read a sensor via an adc. ![[Pasted image 20250929161327.png]]

## SPI bus
4 wires:
clock, output, input and select.
clock up to 10MHz
select input is used to enable one IC to use
useful to communicate with devices such as radios, touchscreens, sensors, coms chips (usb/ethernet etc)

![[Pasted image 20250929161922.png]]

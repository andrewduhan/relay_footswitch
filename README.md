# relay_footswitch
Control your amp's reverb with a low-voltage relay
================

Tap your 6.3V heater rail to control a relay - switch your reverb on and off with low-voltage DC, instead of sending your tone through a long antenna on the floor!

![Printed Board](/footswitch.brd.png?raw=true)

Designed as two break-apart boards, one to provide 5V DC from the 6.3VAC heater rail, and a breakout board for the DPDT relay.
Inputs and outputs are sized to accept turret lugs (tubedepot part "BP-TURRET").
Generate 5VDC and send it down the wire to your footswitch.  Leave your signal and tone where it belongs - inside your amp chassis.

#BOM
- relay:              Omron G6A-234P-ST-US-DC5
- big cap:            4700uF 35V Nichicon
- little cap:         Optional, whatever you want really
- bridge rectifier:   Rectron BR305 
- diode:              1N4001 
- vreg:               7805 

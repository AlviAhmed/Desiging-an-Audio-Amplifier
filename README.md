# Desiging-an-Audio-Amplifier

Desiging and optimizing an audo amplifier circuit. 

More specifically, designing the circuit in such a way that the slew rate and cutoff frequency limitations of the op-amp do  
not affect the signal. Later on taking into account the DC offset when working with microphones.

The specifications of the circuit are:
Vi = 10mv (pk-pk)
Vo = 5V (pk-pk)
Desired Bandwidth = 100Hz - 20kHz
Aclo = 500 V/V

The audio amplifier will either be made from an LM741 or LM318, eventually I chose to use 2 LM741's, since LM741s are what I had on  
hand.

Initially, tests and simulations as well as lab work was done for the LM741 circuit. As seen in the oscilloscope screenshots the circuit works well to amplify the signal within the desired bandwidth (100Hz - 20kHz).

The next step of this project would be to use an actual microphone and amplify its sound so that it is audible in a small speaker.

Microphone planning to use => Electret microphone, Model #: 07-9
Speaker planning to use => McBridge AZ-30s 


# Stability and Control

## DC bus signaling / droop control

Influencing factors for a stable system:

* Droop curves / thresholds for different components
* Wire length and thickness
* Maximum current

How to reconnect a load after an overcurrent event?

Suggestions:

1.) Through intelligent communication and negotiation between the things using the energy (the drain) and the source of the energy?

2.) By priority? - Drains with small consumption have higher priority? - So that light with higher priority comes before heavy equipment.

3.) The source offers/bids free energy capacity by some sort of communication channel. The first drain that requests this free energy, partly or in whole, gets his share. Others follow according to some rules until the free portion of energy is reserved and in used. Drains that don't pick up their request will lose their share og the available energy. ?

4.) Letting the output voltage grow liniarly as more current is available. Like with a certain factor between the two. Let's for instance say 12V equals 5 Amp, 24V equals 10 Amp, 36V equals 15 Amp, 48V equals at least 20 Amp - and in between those numbers linearly. On the drain side, there will something knowing this - and according to a priority start consuming. ?

5.) Letting small voltage drops/spikes be signals for consumers to connect - according to some priority as mentioned earlier? So a sort of communication, but via minor voltage changes. Well, actually you can transmit network communication via 230V cables, but it may not be wished to use this requirement for drains, alias consuming units.


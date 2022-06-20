Modular filters currently include:
 - All pass filter (phase shift as function of frequency, minimal amplitude response)
 - Low pass filter (10k-30k cutoff, i.e. distance filter, as higher frequencies get attenuated at distance)
 - Non-linear amplifier
 - Magnetic saturation with inductor (could fiddle with iron core as parameter)

The idea is to have a swappable bay of some description, with the right level of abstraction as it were that filter design becomes easy. For this reason, the connector has signal in, signal out, +5V, -5V and ground.
Ideally, aesthetics will also not be horrible.

# V1
V1's construction was alright, though there were mistakes made on the values of capacitor bought, so performance was mediocre.
The input stage had some issues, solved by swapping the T and R on the input to the opamp (i.e. inverting the inputs).
The bypass also causes strange issues where it over the course of a few seconds causes greater and greater amounts of clipping on the input signal.
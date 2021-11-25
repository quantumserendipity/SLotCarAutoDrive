# SLotCarAutoDrive
A project to allow autonomous driving of a slot car with auto track mapping and speed optimisation.

The idead is to use my old BBC micro plus a raspberry Pi to provide the control logic to drive a slot car around any track. The software/hardware should initially map the circuit and store that information. Then the car should be driven upto the limit speed to provide a "ghost" car against which to drive. The last bit of the puzzle would be to add some sort of slip detection to the cars drive train to allow for the best possible speed around the circuit. Further additions like adding weather simulation at specific points or puncture or oil slicks might be added later.
The first stage is understanding the problems. I want to do this for analog slotcars for two reasons
1: I have lots of them and many are oldies from my distant past. And,
2: I think this would appeal to a wider audience.
I notice that I often have time to drive a car around the track for 30 minutes but I a alone. This is not that satisfying and competion from a "robot" car would be appreciated.

So to start with I intend to arrange some circuitry to allow the BBC micro (or the RASpi) to drive the car and vary the throttle.
Step two might be to extand that to copy a real driver, so record the throtle demmands through a number of laps and average them to give a reasonable profile. This implies the first part of tracking the car by detecting at least the crossing of the start finish line.
Next comes the full mapping of the track, not sure about that yet, but multple detection points with photo diodes might be the answer or ... maybe using the RASpi with a camera system to actually follow the care position, hmm....

Well I will keep this upto date and see where it goes.

G'Day


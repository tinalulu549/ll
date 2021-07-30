Signal types
After analyzing CAN matrixes, we found that there are several signals indicating the status of switches (e.g. 0 for releasing the brake pedal and 1 for braking) or directions (e.g. 0 for go straight, 1 for turn right, 2 for turn left). There are also many signals changing smoothly with time (e.g. speed signal). The two kinds of signals are both important in signal relationship, but the relationship types between them can have different meanings. We classified the first type of signal as “Discrete” and the second type as “Continuous” based on the number of unique values in signals’ data payload. The chosen of “unique value threshold” should be done carefully to prevent misclassifying. When pairing two signals, there should be 3 kinds of signal pairs in total. 
D & D: both signals are discrete
D & C: one signal is discrete, the other is continuous
C & C: both signals are continuous
For the three different types of signal pairs, we check different kinds of relationships. 

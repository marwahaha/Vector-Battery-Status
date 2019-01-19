# Vector-Battery-Status
Python script that reports on Anki Vector's battery status.   Much of this code is in the SDK  - - I reformated output to improve readability and to ultimately create a log file.

Anki provides the following "abreviated" info about Vector's battery status in the SDK:

"Vector is considered fully-charged above 4.1 volts. At 3.6V, the robot is approaching low charge.

Battery_level values are as follows:
Low = 1: 3.6V or less. If on charger, 4V or less.
Nominal = 2
Full = 3: only be achieved when Vector is on the charger."

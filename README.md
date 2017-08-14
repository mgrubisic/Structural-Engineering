# Structural-Engineering
Structural Engineering Modules (Python 2.7 primarily)

Concrete T beam - depend on concrete_beam_classes
Tkinter GUI based Python program.
Provides various code defined capacities based on strain compatibility. Currently based on ACI 318-08. Calculates elevation
of various steel reinf. layers based on clearance and spacing requirements per ACI 318-08.

Concrete T Beam Any Steel - depend on concrete_beam_classes
Tkinter GUI based Python program
Provides various code defined capacities based on strain compatibility. Allows for user assigned elevations of steel reinforcement
layers. Does not check or provide for min spacing of tension layer bars nor maximum amount of bars that fit in a layer.

Three Moment Method
Contains a class for the Three Moment Method for continuous beam analysis.

Beam Patterning
A Tkinter GUI based Python program implimenting IBC 2012 load combinations and load patterning. Analysis is done using the Three moment method. Results are displayed on screen and CSV and DXF files are created and placed in RESULTS folder on the users desktop. NOTE: When using the prescribed support displacement option the beam slope diagram and values are incorrect. Deflection values have been corrected using small angle approximations. The effect of the support displacement can be toggled on and off in the results window for shear, moment, slope and deflection charts.

ASIC Shapes Database - depends on having the excel file in the same directory as the py file
A Tkinter GUI based Python program to sort and filter steel shapes built off the freely avaiable excel file provided by AISC, https://www.aisc.org/publications/steel-construction-manual-resources/

ASIC Shapes Historic Database - depends on having the excel file in the same directory as the py file
A Tkinter GUI based Python program to sort and filter historic steel shapes built off the freely avaiable excel file provided by AISC, https://www.aisc.org/publications/steel-construction-manual-resources/

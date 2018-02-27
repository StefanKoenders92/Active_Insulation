# Active_Insulation
These are the files needed to model Active Insulation in EnergyPlus version 8.6.0. A readme, the adapted Ventilated Slab module and two example files can be found in the repository.

<b>How to model Active Insulation.pdf</b> describes how Active Insulation is modelled in EnergyPlus, which components are needed and the things to keep in mind when modelling your model in a preprocess program.

The <b>VentilatedSlab.cc</b> file is the adapted file from the source code of EnergyPlus. The built-in control loop for checking if the direction of the heat flow is correct is removed.

<b>HotBoxModel - ActiveInsulation.idf</b> is an example file using a simple hot box setup with one wall being equipped with a single panel of Active Insulation. One side of the room is kept at a constant temperature, while the other room has an heating element in it to keep it at a constant temperature. 

<b>ReferenceDwelling_LivingRoom - ActiveInsulation</b> is an example file where the living room of a detached dwelling is modelled. All facade constructions are equipped with Active Insulation.

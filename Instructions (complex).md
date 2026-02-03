# Dan's ATC24 Clearance Generator V3 - Instructions (complex)
## Before Reading Further
Before reading any further, please first read the basic instructions on how to use this software, as this additional instructions manual is an extension of the basic.

## Introduction
This complex instructions manual will cover how to enter custom values into the clearance generator. The validations system behind is relatively intricate to understand, and that is why there is an additional manual covering it.

<b> The following text is decoded into words, a diagram of how each field impacts each other is included towards the bottom to make understanding simpler </b>

## Custom Departure
Entering a custom departure does not affect any other fields, the only thing required is that the VECTOR/CUSTOM departure method to be selected.

## Custom Destinations
If you wish to enter a custom destination, you must first open the field by typing <i> 'CUST' </i> in the destination field. This will then allow you to enter a custom destination in the custom destination field.
Though this will not be the only custom entry you can enter, you will also have to enter a custom departure, as entering a custom departure gives the software no information where the aircraft is looking to go. You will also have to select the VECTOR/CUSTOM departure method in addition.

## Custom Departure Runway
Entering a custom departure runway will require you to enter a custom departure in addition, making sure that you've selected the VECTOR/CUSTOM departure method.

## Custom Climb
Entering a custom climb will not impact any other fields, it is a standalone value that must be numerical. You may enter comparison operators (>, <, >=, <=) if giving VFR clearances.


## Impacts Overview
Custom Climb -> No impact

Custom Departure -> Requires only the VECTOR/CUSTOM departure method

Custom Departure Runway -> Requires a custom departure -> Requires the VECTOR/CUSTOM departure method

Custom Destination -> Requires a custom departure -> Requires the VECTOR/CUSTOM departure method


# UNT-SLNS
UNT TSGC SLNS
BACKGROUND
Currently, spacecraft lighting system are operated independently through switches and knobs. For future deep
space missions, spacecrafts will require new and innovative intelligent light control methods to minimize power,
improve reliability such as compensating for degrading lighting sources, and provide lighting necessary for the
biological aspect of the human. Therefore, it is highly desired that spacecraft lighting system have the ability to
communicate on a network with on-board computers for determining lighting health status as well as controlling the
lighting spectrum for task activities and maintaining circadian rhythms of the crew.
PROJECT DESCRIPTION
Currently, commercial lighting bus standard chipsets are not suitable for the deep space radiation
environment. The focus of this project is to implement the DMX512 lighting standard using programmable
computer devices such as microcontrollers or field programmable gate arrays. The reason for implementing in
programmable devices is that radiation tolerant/hardened (Rad Tol/Hrd) programmable devices exist such that
the standard could be implemented in a Rad Tol/Hrd device(s). This proof of concept would show the feasibility
of implementing in a programmable device. The proof of concept DMX512 network bus should:
- Use commercial programmable devices as this is a proof-of-concept
- Ability to communicate with the SLNS over Ethernet
- Source of power is AC
- Control at least two RGB lighting sources and accept one light sensor data over the bus.
- GUI to control the SLNS
- Program menu for selecting should include at least (1) health status of the lighting source such as
lighting intensity-compare what is programmed to what sensors detect and different lighting (2) control
lighting intensity (3) Provisions for expanding the number of DMX devices on the bus.
- Enclosure to house the SLNS with standard I/O connectors
DELIVERABLES
Schematics, block diagrams, source code, hardware block diagram, software code flow diagram, operation
description, and bill of materials.

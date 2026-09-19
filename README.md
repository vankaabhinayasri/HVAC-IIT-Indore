HVAC System – IIT Indore

Overview

This repository documents the HVAC (Heating, Ventilation and Air Conditioning) plant and Air Handling Unit (AHU) system at IIT Indore, based on the site documentation and system flow diagrams provided for the study.

The documentation covers the complete chilled-water HVAC plant, including the cooling tower, water-cooled chillers, chilled-water pumping network, condenser-water loop, expansion tank, decoupler line, underground distribution network and AHUs.

It also presents the air-flow sequence through an AHU and the associated sensors, controls, piping and valve systems.

1. Complete HVAC Plant

The HVAC plant follows three main water/energy-transfer loops:

Chilled-Water Cycle – Closed Loop

The chilled-water loop circulates water between the buildings and the chiller.

Basic flow:

Building Return
      ↓
Primary Chilled-Water Pump
      ↓
Chiller Evaporator
      ↓
Secondary Chilled-Water Pump
      ↓
Decoupler / Main Header
      ↓
Underground Chilled-Water Distribution
      ↓
AHUs / Building Loads
      ↓
Building Return

The supplied plant diagram shows the chilled-water distribution serving multiple building groups, including hostels, the LHC (Lecture Hall Complex), PODs and other buildings.

2. Refrigeration Cycle Inside the Chiller

The water-cooled chiller transfers heat from the chilled-water loop to the condenser-water loop.

The refrigeration cycle consists of:

Evaporator
    ↓
Compressor
    ↓
Condenser
    ↓
Expansion Valve
    ↓
Evaporator

Main components

Evaporator – Refrigerant absorbs heat from the chilled water.

Compressor – Increases refrigerant pressure and temperature.

Condenser – Refrigerant rejects heat to condenser water.

Expansion valve – Reduces refrigerant pressure and temperature before the refrigerant returns to the evaporator.

The documentation identifies two water-cooled chillers, approximately 650 TR each.

3. Condenser-Water Cycle – Open Loop

The condenser-water loop removes heat rejected by the chiller and transfers it to the atmosphere through the cooling tower.

Chiller Condenser
      ↓
Condenser-Water Pump
      ↓
Cooling Tower
      ↓
Cooled Water
      ↓
Chiller Condenser

The supplied plant diagram shows an open-cycle cooling tower system with condenser-water pumps.

Typical values shown in the documentation include:

Condenser-water entering chiller: approximately 30.5°C

Condenser-water leaving chiller: approximately 33.7°C

Temperature range: approximately 3.2°C

4. Cooling Tower

The cooling tower rejects heat from the condenser-water loop to the surrounding atmosphere.

The plant documentation shows two cooling towers.

The tower uses a water/air heat-transfer process. Warm condenser water enters the cooling tower, transfers heat to the air, and returns at a lower temperature.

5. Chilled-Water Distribution Network

The chilled-water system uses a closed-loop underground distribution network to supply conditioned water to different buildings.

The documented system includes:

Primary chilled-water pumps

Secondary chilled-water pumps

Decoupler lines

Main header

Underground supply and return lines

Strainers

Expansion tank

Air separator tank

Building-level AHUs

The decoupler line allows hydraulic separation between the primary and secondary pumping circuits.

6. AHU (Air Handling Unit)

The AHU conditions air before supplying it to the building.

The supplied AHU workflow diagram shows the following sequence:

Return Air
    ↓
1. Return Air Section
    ↓
2. Filter Section
    ↓
3. Cooling Coil Section
    ↓
4. Drain Pan
    ↓
5. Fan / Blower Section
    ↓
6. Supply Air Section
    ↓
Building

1. Return Air Section

Air is returned from the building to the AHU.

The documentation also shows an arrangement where inlet air can be taken directly into the AHU through a duct.

2. Filter Section

The filter removes dust and particulate matter from the air.

The documentation notes that filter cleaning is required periodically, approximately every 4–6 months, depending on operating conditions.

3. Cooling Coil

The cooling coil uses chilled water to remove heat from the air.

The supplied AHU documentation shows typical chilled-water conditions of approximately:

Chilled-water inlet: 4–6°C

Chilled-water outlet: 9–12°C

4. Drain Pan

As air is cooled below its dew point, moisture can condense on the cooling coil.

The drain pan collects this condensate and directs it to the drain.

5. Fan / Blower Section

The fan provides the pressure and airflow required to move conditioned air through the supply duct system.

6. Supply Air Section

The conditioned air leaves the AHU and is distributed to the building through the supply duct.

Typical operating temperatures shown in the documentation are:

Return air: approximately 24–26°C

Supply air: approximately 14–16°C

7. AHU Sensors and Controls

The AHU documentation shows several monitoring and control components:

Temperature gauge

Pressure gauge

Flow-rate sensor

Fire damper

Control actuator

Sensors

Butterfly valves

Strainer

Manual outlet

Automatic/control outlet

These components are used to monitor system conditions and control airflow and chilled-water flow.

8. Chilled-Water Piping and Valves

The system includes several components for safe and controlled water circulation:

Strainer

Removes unwanted particles from the water stream and protects downstream equipment.

Butterfly valve

Used for isolation and flow control within the piping system.

Pressure gauge

Used to monitor pressure conditions in the water circuit.

Flow-rate sensor

Used to monitor the amount of water flowing through the system.

Air separator

Helps remove entrained air from the chilled-water loop.

Expansion tank

Accommodates changes in water volume and helps maintain appropriate system pressure.

9. Typical System Operating Conditions

The documentation provides the following representative operating conditions:

Parameter

Typical value shown

Chilled-water inlet to AHU

4–6°C

Chilled-water outlet from AHU

9–12°C

Return air

24–26°C

Supply air

14–16°C

Condenser water entering chiller

~30.5°C

Condenser water leaving chiller

~33.7°C

Condenser-water range

~3.2°C

Current COP

~4–5

These values are representative values shown in the supplied documentation and should not be treated as universal operating limits for every operating condition.

10. Refrigerant Information

The plant documentation includes a refrigerant-property comparison table for:

R134a

R410A

R32

R1234yf

The table compares properties such as:

Chemical formula

GWP

Boiling point

Critical temperature

Volumetric cooling capacity

Safety class

Typical applications

The documentation presents this comparison as part of the HVAC plant overview.

11. AHU Types / Configurations

The documentation also describes a single AHU configuration with:

Compact design

Single air path

Use in smaller areas

Use in pod buildings

The airflow arrangement and filtration depend on the particular AHU installation.

12. System-Level Working

The complete HVAC operation can be understood as two coupled heat-transfer processes.

Water side

Building
   ↓
Warm return chilled water
   ↓
Chiller evaporator
   ↓
Cooled chilled water
   ↓
Pumps + distribution network
   ↓
AHU cooling coils
   ↓
Building

Refrigerant side

Evaporator
   ↓
Compressor
   ↓
Condenser
   ↓
Expansion Valve
   ↓
Evaporator

Heat-rejection side

Chiller condenser
   ↓
Condenser-water pump
   ↓
Cooling tower
   ↓
Heat rejected to atmosphere
   ↓
Cooled condenser water
   ↓
Chiller

Together, these loops transfer heat from the building to the atmosphere.

13. Key Takeaways

The IIT Indore HVAC plant uses a water-cooled chiller system.

The documentation identifies two chillers of approximately 650 TR each.

The chilled-water circuit is a closed loop serving multiple building loads.

The condenser-water circuit rejects heat through the cooling tower.

Primary and secondary chilled-water pumping are connected through decoupler lines.

AHUs use chilled-water cooling coils to condition the building air.

The AHU sequence is return air → filtration → cooling coil → drain pan → fan/blower → supply air.

Sensors, actuators, valves, strainers and gauges support monitoring and control.

Representative values shown in the documentation include 4–6°C chilled-water inlet, 9–12°C chilled-water outlet, 24–26°C return air, 14–16°C supply air and COP around 4–5.

14. Documentation Included

This repository can be used to organize:

HVAC-IIT-Indore/
│
├── README.md
│
├── diagrams/
│   ├── complete-hvac-plant-flow-diagram
│   ├── chilled-water-piping-schematic
│   └── ahu-air-flow-workflow
│
├── photos/
│   ├── chillers
│   ├── cooling-towers
│   ├── pumps
│   ├── ahu
│   └── piping
│
├── calculations/
│
└── references/

Source

This README is prepared from the supplied HVAC system documentation for IIT Indore, including the complete HVAC plant flow diagram, chilled-water piping schematic, and AHU air-flow work-flow diagram.

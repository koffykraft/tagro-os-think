# Field Intelligence and Farming Systems v0.1

**Status:** WORKING  
**Provenance:** SHARED

## Premise

TAGRO Farming Systems must not see irrigation in isolation.

A field has many operational docks. Irrigation should consume field intelligence produced by the wider farm system and return its decisions and consequences to that system.

## Field intelligence docks

A field may accumulate information about:

- soil
- water source and seasonal availability
- coordinates and elevation
- weather, day, month and season
- crops, mixed plantings, plant age, count and condition
- fertilizer and fertigation practice
- labour availability and skill
- household versus commercial use
- mechanization level
- roads, gates, paths and accessibility
- power supply and pump availability
- affordability and operating-cost sensitivity
- buildings, obstacles and security
- photographs, speech, notes and observations

None of these is mandatory merely because a schema allows it. The system gathers what is available and asks for what materially affects decisions.

## Information acquisition

The user should be able to provide information through:

`SPEAK · TYPE · PHOTO · MAP · DRAW · MEASURE · CHOOSE · IMPORT`

The information process should structure this input behind the scenes.

## Evidence states

Useful internal states include:

`OBSERVED · DESCRIBED · MEASURED · INFERRED · CONFIRMED · PROPOSED · ACCEPTED · INSTALLED`

The system may improve its understanding over time without erasing earlier evidence.

## Irrigation as a dock

The irrigation hierarchy is physically:

`Water source → Pump → Treatment / filter / fertigation → Main → Field connection → Submain → Lateral → Outlet / application device → Plant or soil`

Demand propagates upstream:

`application device → lateral → submain → main → operating group → pump/head/power → water source`

## Human engineering

Filters, valves and controls should be placed using both hydraulic suitability and human access.

A technically possible location may still be poor if maintenance, movement, labour, security or machinery access make it inconvenient.

## Design consequence

The system should be able to produce useful design from a simple boundary if that is all that exists, while becoming more intelligent as richer field information is added later.

The design is therefore progressive, not all-or-nothing.
# Prompt 01 - RTL to GDS Trace Investigation

## Objective

Trace the `AMUX2_3V` analog macro through every stage of the mixed-signal RTL-to-GDS implementation flow to determine whether the macro is preserved throughout synthesis, floorplanning, placement, routing, DEF generation and final GDS generation.

---

## AI Prompt

The reproduced mixed-signal flow successfully generates a routed GDS for the `design_mux` design. I want to verify whether the analog macro `AMUX2_3V` survives every implementation stage.

Guide me step-by-step through the investigation without making assumptions.

At each stage, tell me exactly which generated netlist or implementation database should be inspected, what command to execute, what output to expect, and how to interpret the result before moving to the next stage.

The investigation should trace the macro through:

* RTL
* Yosys synthesis
* OpenROAD floorplanning
* Global placement
* Detailed routing
* DEF database
* Final GDS layout

The objective is to determine precisely where the macro is preserved or removed during the implementation flow.

---

## AI Tool

* ChatGPT (GPT-5.5)

---

## Result

The AI-assisted investigation demonstrated that the `AMUX2_3V` macro survives every stage of the implementation flow and is present in the final routed layout.

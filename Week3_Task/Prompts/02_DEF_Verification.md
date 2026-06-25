# Prompt 02 - DEF Verification

## Objective

Verify whether the analog macro is physically placed and connected in the routed DEF database.

---

## AI Prompt

Guide me through verifying whether the `AMUX2_3V` macro is physically placed within the routed DEF.

Identify the relevant DEF file, the commands required to inspect the placement, and explain how to verify:

* macro placement coordinates
* placement orientation
* routed signal connections
* macro pins

Use only inspection of the generated implementation files without modifying the design.

---

## AI Tool

* ChatGPT (GPT-5.5)

---

## Result

The routed DEF confirmed that the `AMUX2_3V` macro was physically placed and connected to its signal nets (`I0`, `I1`, `out`, and `select`).

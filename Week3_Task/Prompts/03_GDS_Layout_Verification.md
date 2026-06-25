# Prompt 03 - GDS Layout Verification

## Objective

Verify that the placed analog macro can be identified within the final GDS layout.

---

## AI Prompt

The routed DEF confirms that the `AMUX2_3V` macro is physically placed.

Guide me through verifying the corresponding region in the final GDS using KLayout.

Explain how to:

* locate the placement coordinates
* inspect the surrounding geometry
* identify the macro region
* compare the observed geometry with the LEF dimensions
* determine whether the macro appears correctly in the final layout

---

## AI Tool

* ChatGPT (GPT-5.5)

---

## Result

The macro-sized region corresponding to the DEF placement coordinates was successfully identified in the final GDS layout, completing the RTL-to-GDS verification.

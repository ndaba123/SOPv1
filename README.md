# 🍰 Scalable Cake Baking SOP

> A structured, ratio-based Standard Operating Procedure (SOP) for
> baking a cake that serves **any number of people**, with optional
> process-model artifacts (Mermaid + BPMN).

------------------------------------------------------------------------

## 📌 Overview

This project formalizes the **Scalable Cake Baking for Any Number of
People** SOP into:

-   A structured procedural document
-   Optional Mermaid flowchart model
-   Optional BPMN 2.0 process model
-   Validation + traceability documentation

The procedure uses proportional ingredient scaling and clearly defined
decision points to ensure repeatable results.

------------------------------------------------------------------------

## 🎯 Purpose

Provide a reproducible cake-baking method that:

-   Scales ingredient quantities using a consistent formula
-   Maintains fixed baking temperature (350°F / 175°C)
-   Defines decision logic explicitly
-   Documents exceptions and rework scenarios
-   Supports regeneration of modeling artifacts

------------------------------------------------------------------------

## 📂 Repository Structure

    .
    ├── SOPversion01.docx
    ├── README.md
    ├── diagrams/
    │   ├── mermaid/
    │   │   └── process.mmd
    │   └── bpmn/
    │       └── process.bpmn
    └── exports/

------------------------------------------------------------------------

## 🧮 Core Scaling Rule

    Total Batter (grams) = Number of People × 130g

If no scale is available:

-   One 9-inch round OR 9×13-inch pan ≈ 1,300g batter

------------------------------------------------------------------------

## 🔄 Process Summary

### 1️⃣ Determine Cake Size

-   Multiply servings × 130g
-   Select appropriate pan size

### 2️⃣ Measure Ingredients

-   Equal parts: sugar, fat, liquid
-   Flour: 2× base amount
-   Include eggs, baking powder, salt
-   Substitute before mixing if dietary restrictions apply

### 3️⃣ Mix Batter

-   Preheat oven to 350°F (175°C)
-   Cream fat + sugar
-   Add eggs individually
-   Mix dry ingredients separately
-   Alternate dry + liquid additions
-   Stop when smooth
-   If dry → add liquid 1 tbsp at a time

### 4️⃣ Bake

-   Fill pans ≤ 2/3 full
-   Bake at 350°F (175°C)
-   Thin: 25--30 min
-   Thick: 40--55 min
-   If toothpick clean + springs back → remove
-   Else bake in 5-minute intervals

### 5️⃣ Cool & Serve

-   Cool 10--15 minutes in pan
-   Remove and cool fully
-   Serve or frost

------------------------------------------------------------------------

## ⚠️ Exceptions & Rework

  Issue         Cause                    Action
  ------------- ------------------------ -----------------------------
  Dense cake    Overmixing               Reduce mixing time
  Undercooked   Insufficient bake time   Continue in 5-min intervals
  Overflow      Overfilled pan           Remove excess batter

------------------------------------------------------------------------

## 🛠 Regenerating Process Artifacts

### Generate Mermaid Flowchart

1.  Convert SOP steps into `flowchart TD` format.
2.  Include:
    -   Explicit **Start**
    -   Explicit **End**
    -   Labeled decision branches
3.  Save to:

```{=html}
<!-- -->
```
    diagrams/mermaid/process.mmd

Render with:

``` bash
npx @mermaid-js/mermaid-cli -i diagrams/mermaid/process.mmd -o exports/process.svg
```

------------------------------------------------------------------------

### Generate BPMN 2.0 Model

Use:

-   Start Event
-   Tasks for procedural steps
-   Exclusive Gateways for decisions
-   End Event
-   Lanes only if roles differ materially

Save to:

    diagrams/bpmn/process.bpmn

Open with:

-   Camunda Modeler\
-   bpmn.io\
-   Signavio

------------------------------------------------------------------------

## 📋 Inputs & Outputs

**Inputs** - Number of people - Ingredients - Oven + bakeware

**Output** - Properly sized finished cake

------------------------------------------------------------------------

## 🧾 Traceability

This SOP was generated and refined through iterative AI-assisted
drafting including:

-   Efficient walkthrough generation
-   Algorithm simplification
-   Beginner-friendly rewrite
-   Formal SOP structuring
-   Language tightening
-   Word export formatting
-   Prompt log preservation

------------------------------------------------------------------------

## 📅 Version

Generated on: 2026-02-19

------------------------------------------------------------------------

## 📄 License

Add your preferred license here (MIT, Apache 2.0, etc.).


---
title: "Panel to Web Component Generator"
description: "Vision idea tracked as GitHub issue #17."
---

- Status: **open**
- GitHub issue: [winccoa-tools-pack/.github#17](https://github.com/winccoa-tools-pack/.github/issues/17)
- Last sync: 2026-11-11 09:13:10 UTC
- Labels:
- enhancement
- ctrl-lang
- vs-code-extension
- oa-pnl
- good for oa nodejs

---


**Description:**  
Create a generator that converts OA panels into modern web components.

**Features:**  
- Supports Siemens standard Wub UI components
- Maps DP bindings to props  
- Preserves event logic  
- Generates reusable components  

**Acceptance Criteria:**  
- Converts at least one panel type  
- Outputs working web component  
- Includes usage guide  
- Supports customization  

PNL -> XML -> JSON 
  -> HTML
  -> JS (typescript)
  -> CSS


I whish you many luck. it is complex project, but it will be helpfull for big WinCC OA community to use the modern tolls instead the very old (but sitll good and vyer stable) pnl format.

Maybe one hint. Provide Splash based tests first. Let create UML diagram from user actions to document the good scenarios and the edge cases. This will helps the AI agent to create new business logic in type-script as well

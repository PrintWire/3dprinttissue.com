---
title: "Production-Ready Dental 3D Printing: From Titanium Implants to Same-Day Custom Aligners"
date: 2026-06-22T06:04:58-06:00
draft: false
description: "How 3D printed dental implants, surgical guides, and orthodontic aligners are reshaping clinical workflows and patient outcomes."
keywords: ["3D printed dental implants surgical guides orthodontic aligners", "DMLS titanium dental implants", "clear aligner 3D printing workflow"]
---
**3D printed dental implants, surgical guides, and orthodontic aligners** are three distinct uses of additive manufacturing in dentistry, each with its own materials, process and regulatory position. This article covers what published sources say about each one, and where the evidence is still thin.

---

## Titanium Implant Structures: DMLS and Patient-Specific Geometry

DMLS (Direct Metal Laser Sintering) has been used to make patient-specific subperiosteal implants, which are designed around an individual jaw instead of being a standard screw shape.

A case series published in 3D Printing in Medicine in 2020 describes the approach. Ten partially edentulous patients over 65 with an atrophic posterior mandible were treated between 2017 and 2018. The implants were designed from cone beam CT data and made in titanium by DMLS, then followed for one year. No implants were lost, minor complications gave a final complication rate of 30%, and the mean fit was rated 7 out of 10. The authors concluded that DMLS was an effective way to fabricate accurate subperiosteal implants and an alternative for patients who want to avoid bone regeneration, while noting the small sample and short follow-up.

### Material: Ti-6Al-4V ELI (Grade 23)

Ti-6Al-4V ELI is the extra-low interstitial version of Ti-6Al-4V. According to alloy producer Carpenter Technology, it has lower specified limits on iron and on the interstitial elements carbon and oxygen, it is also known as ASTM B348 Grade 23, and ASTM F136 is the applicable specification for wrought alloy for surgical implants. Carpenter credits the ELI grade with superior damage tolerance (fracture toughness and fatigue crack growth rate) compared with standard Ti-6Al-4V, and describes it as the material of choice for many medical and dental applications.

Two points about post-processing and quality systems:

- **Hot isostatic pressing (HIP)** is used to improve the fatigue performance of additively manufactured Ti-6Al-4V. A 2022 study in Materials found that the result depends on the as-built quality of the material.
- ISO 13485 is a quality management system standard for medical devices ("Medical devices, Quality management systems, Requirements for regulatory purposes"). It is not a sterilization standard as such, although it includes requirements for documenting and validating processes for sterile medical devices.

---

## Surgical Guides: Accuracy at the Drill Tip

Printer maker Formlabs describes surgical guides as single-use appliances made to fit directly over a patient's teeth, which position the surgical drill at the correct location, angle and depth.

### Workflow

The workflow Formlabs publishes for its own printers has four steps:

1. Scan: intraoral scanning or cone beam CT (CBCT)
2. Design of the guide
3. Print in a biocompatible resin
4. Post-process the printed guide

### Resin Requirements

A guide should be printed in a resin intended for that use. Formlabs describes its Surgical Guide Resin as autoclavable and biocompatible, states that it complies with ISO 10993-1:2018, and says it is designed for printing Class I devices on the company's SLA printers. ISO 10993-1 is the part of the biological evaluation standard that covers evaluation and testing within a risk management process. Formlabs also warns that improper post-curing can reduce both mechanical and biocompatibility performance, and that supports should be removed only after post-curing to prevent warping.

Classification depends on the jurisdiction and on how the guide is used:

- In the EU, Annex VIII of the Medical Device Regulation puts invasive devices used transiently in a body orifice in Class I (Rule 5), and surgically invasive devices intended for transient use in Class IIa unless an exception applies (Rule 6). Transient means normally intended for continuous use for less than 60 minutes. Which rule applies to a particular guide is for its manufacturer to determine and document.
- In the US, the FDA lists endosseous dental implant accessories (product code NDP, 21 CFR 872.3980) as Class I and 510(k) exempt. Guides have nonetheless gone through 510(k) review under that product code: Dentsply Sirona's SIMPLANT Guide, a patient-specific surgical template fabricated via stereolithography, was found substantially equivalent on June 15, 2017 (K170849).

---

## Orthodontic Aligners: The Same-Day Model

There are two ways to use a printer for aligners.

### Indirect: Print the Model, Thermoform the Aligner

A 2024 narrative review in Frontiers in Materials states that the great majority of aligner manufacturing still relies on thermoforming. The process starts with an intraoral scan, and design software simulates the tooth arrangement. Models are printed, and a thermoplastic sheet is formed over each model and trimmed. The review lists PETG and thermoplastic polyurethane (TPU) among the common aligner thermoplastics, and notes that the material is stretched unevenly during thermoforming, which can lead to inaccurate sizing.

On speed, the figures available are vendor claims. SprintRay says full cases of aligners can be fabricated in a single day when its printer is used with a thermoforming machine and orthodontic CAD software. Formlabs advertises scan to aligner in less than an hour, listing 5 minutes to scan, 5 minutes to design, 8 to 9 minutes to print, 10 minutes to post-process and 5 minutes to thermoform. Both describe printing the models, not the aligners.

### Direct: Printing the Aligner Itself

Direct printing removes the model and the thermoforming step. The best-known material is Tera Harz TC-85, a photopolymer introduced by Graphy. A 2021 review in Materials argues that directly printed aligners offer higher precision, better load resistance and less deformation than thermoformed ones, and better control over aligner thickness, while noting that few approved materials and little aligner-specific software were available.

The 2024 review is more cautious. It reports experimental evidence that thermoformed materials are more transparent than printed ones, that printed aligners were sometimes thicker than their design files, and that print orientation and post-curing affect the result. It concludes that developing biocompatible resins and improving mechanical properties will be critical. Its statements on the regulatory status of TC-85 are inconsistent with each other, so anyone planning to use a direct-print aligner resin should confirm its status with the regulator.

---

## What the Sources Support

Dental 3D printing is a collection of distinct workflows with different levels of evidence. Printed surgical guides and printed models for thermoformed aligners are established, vendor-supported workflows. Printed titanium subperiosteal implants are supported by small clinical series with short follow-up. Directly printed aligners are available but still being evaluated. In each case the result depends on validating the full process chain, including post-curing, and not only the printer.

## Sources

- [Custom-made 3D printed subperiosteal titanium implants, case series (3D Printing in Medicine, 2020), via Europe PMC](https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=PMCID:PMC6950914&resultType=core&format=json)
- [Carpenter Technology: Ti 6Al-4V ELI](https://www.carpentertechnology.com/alloy-finder/Ti-6Al-4V-Eli)
- [Hot Isostatic Pressing for Fatigue Critical Additively Manufactured Ti-6Al-4V (Materials, 2022), via Europe PMC](https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=PMCID:PMC8952505&resultType=core&format=json)
- [Wikipedia: ISO 13485](https://en.wikipedia.org/wiki/ISO_13485)
- [Formlabs Dental: surgical guides](https://dental.formlabs.com/indications/surgical-guides/)
- [Formlabs: Using Surgical Guide Resin](https://formlabs.com/global/support/Using-Surgical-Guide-Resin/)
- [FDA: Use of International Standard ISO 10993-1](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/use-international-standard-iso-10993-1-biological-evaluation-medical-devices-part-1-evaluation-and)
- [EU MDR Annex VIII classification rules (Advisera full text)](https://advisera.com/13485academy/mdr/classification-rules/)
- [FDA product classification: NDP, endosseous dental implant accessories](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfPCD/classification.cfm?ID=NDP)
- [SIMPLANT Guide 510(k) K170849 (Innolitics FDA database mirror)](https://fda.innolitics.com/device/K170849)
- [Prospects for 3D-printing of clear aligners: a narrative review (Frontiers in Materials, 2024)](https://www.frontiersin.org/journals/materials/articles/10.3389/fmats.2024.1438660/full)
- [Direct 3D Printing of Clear Orthodontic Aligners (Materials, 2021), via Europe PMC](https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=EXT_ID:33916462&resultType=core&format=json)
- [SprintRay: clear aligners](https://sprintray.com/digital-dentistry/clear-aligners/)
- [Formlabs Dental: thermoformed clear aligners and retainers](https://dental.formlabs.com/indications/thermoformed-clear-aligners-retainers/)

Fact-checked 2026-11-21

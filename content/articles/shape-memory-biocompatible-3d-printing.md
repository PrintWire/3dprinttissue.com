---
title: "Shape Memory Biocompatible 3D Printing: Photopolymer Resins for Smart Medical Devices"
date: 2026-06-27T06:01:54-06:00
draft: false
description: "Shape memory biocompatible 3D printing resins are being developed for thermally triggered medical devices. A technical look at photopolymers, biocompatibility testing, and inflammatory response."
keywords: ["shape memory biocompatible 3D printing", "shape memory polymers medical devices", "biocompatible photopolymer resin"]
---
Shape memory biocompatible 3D printing sits at a demanding intersection of additive manufacturing and medical devices. Shape memory photopolymer resins, including DEGRES INX from BIO INX, can be printed into a permanent geometry, deformed into a temporary shape, and then returned to their printed form by heat. When that recovery happens at body temperature, the body becomes the trigger. The uses proposed for such materials include stents that are introduced collapsed and expand in place, and other devices for minimally invasive surgery.

Getting from a printed prototype to an implantable device is a long road. This article covers how shape memory photopolymers work at a materials level, what the biocompatibility evaluation framework looks like, and why inflammatory response matters.

---

## What Makes a Polymer "Shape Memory"

Shape memory polymers (SMPs) rely on a network with two elements: netpoints (covalent bonds or intermolecular interactions) that hold the permanent shape, and switching domains that can be softened and reset. The temperature at which recovery occurs is a glass transition temperature (Tg) or a melting temperature (Tm), depending on the polymer. For photopolymers, which are cured by light during printing, the printed geometry is the permanent shape.

Programming the temporary shape happens after printing: heat the part, deform it, then cool it while holding the deformation. Reheating above the transition temperature lets the material recover its printed geometry.

For medical use, the attraction is that body temperature can be exploited as the trigger. A 2024 review in Progress in Additive Manufacturing lists a number of experimental shape memory systems with transition temperatures at or near 37 °C.

---

## DEGRES INX

DEGRES INX is a resin from BIO INX, a spin-off of B-PHOT and VUB, announced in June 2024 with an official launch planned for the TERMIS World Conference in Seattle that month. According to the announcement and trade coverage:

- It was developed specifically for digital light projection (DLP) based 3D (bio)printing, with resolution down to 100 µm.
- It is polyester-based, which makes it biodegradable.
- It can be deformed into a temporary shape after printing and returns to its printed shape when heated to body temperature; trade coverage gives the shape memory temperature as 37 °C.
- BIO INX describes it as the first commercially available biocompatible 4D DLP resin. Biocompatibility is described with reference to ISO 10993-5, the in vitro cytotoxicity part of the standard, and to fibroblasts growing on a printed scaffold.
- Suggested applications include biodegradable stents and minimally invasive surgery.

These are the company's own claims. The pages we read describe potential applications only and do not mention any regulatory clearance for implantable use. A cytotoxicity result is one endpoint among the many an implant has to address, as described below.

### Photoinitiators and Residual Monomer

Formulation choices matter for biological safety. Diphenyl(2,4,6-trimethylbenzoyl)phosphine oxide (TPO) is a common photoinitiator in printed resins. A 2025 study of 3D-printed provisional dental resins in the Brazilian Dental Journal notes that TPO may show cytotoxic effects at higher concentrations, and that the concern is the potential release of residual monomers and photoinitiators. In that study, adding up to 3 wt.% TPO did not increase cytotoxicity. The authors stress that efficient polymerization is essential because it reduces the amount of residual free monomer.

### Shape Fixity and Shape Recovery

Two metrics describe shape memory performance. The fixity rate measures how well the switching segments hold the temporary deformation, and the recovery rate measures how well the material returns to its permanent shape. As a point of reference, FFF-printed PLA stents described in the 2024 review showed fixity and recovery values close to 100%.

---

## Biocompatibility Evaluation

The international framework is ISO 10993, a multi-part standard for evaluating the biocompatibility of medical devices. What has to be addressed depends on the nature of the body contact and its duration. The FDA's categories are limited (24 hours or less), prolonged (more than 24 hours to 30 days), and long term or permanent (more than 30 days).

### ISO 10993 Parts Relevant to Implants

- **Cytotoxicity (ISO 10993-5):** Tests for in vitro cytotoxicity.
- **Sensitization (ISO 10993-10):** Tests for skin sensitization.
- **Genotoxicity (ISO 10993-3):** Tests for genotoxicity, carcinogenicity and reproductive toxicity.
- **Implantation (ISO 10993-6):** Tests for local effects after implantation.
- **Systemic toxicity (ISO 10993-11):** Tests for systemic toxicity.

Irritation is covered by ISO 10993-23 and chemical characterization of device materials by ISO 10993-18.

For an implant in tissue or bone with long-term contact, the FDA's endpoint table lists cytotoxicity, sensitization, irritation or intracutaneous reactivity, acute systemic toxicity, material-mediated pyrogenicity, subacute or subchronic toxicity, genotoxicity, implantation, chronic toxicity, and carcinogenicity. The FDA describes this as a framework for developing a biocompatibility evaluation, not a checklist for testing.

The FDA's guidance on the use of ISO 10993-1, in its current version dated September 2023, addresses risk-based approaches to deciding whether biocompatibility testing is needed and includes chemical assessment recommendations.

### Inflammatory Response

The foreign body reaction is the typical tissue response to an implanted material. Host blood proteins adsorb onto the implant surface, and the adsorbed proteins regulate how inflammatory cells attach. Neutrophils are the main cell type on the surface for the first two days, followed by monocytes and macrophages; macrophages can fuse into foreign body giant cells. In the end stage, fibroblasts create a collagenous fibrous capsule that separates the material from the surrounding tissue. The reaction can lead to device failure, for example by blocking drug diffusion from a drug delivery system.

For photopolymers, post-print processing is the usual way to reduce residual uncured material. In the dental resin study above, printed specimens were washed in an ultrasonic isopropanol bath to remove uncured resin and then post-cured under UV light for 10 or 30 minutes.

---

## Proposed Clinical Applications

The 2024 review lists medical devices such as vascular stents and craniofacial plates, drug delivery vehicles, and scaffolds for tissue engineering among the biomedical applications of SMPs. It also notes that, beyond responding to a stimulus, the materials need to be non-toxic, cell adhesive, and biocompatible to avoid inflammatory responses.

Stents are a recurring example: a compressed device is delivered to the site and recovers its expanded shape there. Contact duration under the ISO 10993 framework differs between device types, which changes the set of endpoints that must be addressed.

---

## Where the Field Stands

At least one commercial shape memory resin aimed at biofabrication is now on the market, but clinical use is another matter. The 2024 review states that understanding of how 4D-fabricated structures interact with host tissue, including the immune system, is still limited, and that translation of the technology into clinical practice remains a distant prospect.

Developers who characterize their chemistry and plan biocompatibility evaluation early are better placed than those who treat it as a final step.

## Sources

- [VoxelMatters: BIO INX launches DEGRES INX shape memory bioink](https://www.voxelmatters.com/bio-inx-launches-degres-inx-shape-memory-bioink/)
- [B-PHOT: BIO INX launches first biodegradable resin for light-based 3D (bio)printing](https://b-phot.org/news/b-phot-spin-off-bio-inx-launches-first-biodegradable-resin-for-light-based-3d-bioprinting)
- [Bonetti and Scalet, 4D fabrication of shape-changing systems for tissue engineering (Progress in Additive Manufacturing, 2024; arXiv copy)](https://arxiv.org/abs/2501.07612)
- [Wikipedia: Shape-memory polymer](https://en.wikipedia.org/wiki/Shape-memory_polymer)
- [Brazilian Dental Journal: Optimizing Photoinitiator Concentration in 3D-Printed Resins for Provisional Dental Restorations (2025)](https://www.scielo.br/j/bdj/a/kQVL3Fxdmg3JLsmXRKptFXB/?format=html&lang=en)
- [Wikipedia: ISO 10993](https://en.wikipedia.org/wiki/ISO_10993)
- [FDA: Biocompatibility Evaluation Endpoints by Contact Duration Periods](https://www.fda.gov/medical-devices/biocompatibility-assessment-resource-center/biocompatibility-evaluation-endpoints-contact-duration-periods)
- [FDA: Use of International Standard ISO 10993-1 (guidance, September 2023)](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/use-international-standard-iso-10993-1-biological-evaluation-medical-devices-part-1-evaluation-and)
- [Wikipedia: Foreign body reaction](https://en.wikipedia.org/wiki/Foreign_body_reaction)

Fact-checked 2026-11-21

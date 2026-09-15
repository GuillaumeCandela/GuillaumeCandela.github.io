---
layout: page
title: "Recovering Hidden Histories: HTR for Colonial Paraguayan Archives"
description: "A Schmidt Sciences HAVI Development Award project adapting AI to recover enslaved voices from colonial archives"
img: assets/img/ImageHAVI.png
importance: 1
category: work
related_publications: true
---

As the recipient of a 2026 Schmidt Sciences Humanities and AI Virtual Institute (HAVI) Development Award, I led this project in collaboration with Professor Patricia Murrieta-Flores (Tecnológico de Monterrey / Lancaster University), who joined as Co-Investigator, to adapt Handwritten Text Recognition (HTR) technology for colonial Paraguayan archives. The work sat at the intersection of artificial intelligence, digital humanities, and decolonial research practice, with the aim of unlocking thousands of manuscripts documenting the lives of enslaved Indigenous and African descent people {% cite candela_murrieta_digital_2026 %}.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/havi_manuscript.jpg" title="Colonial manuscript sample" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/havi_ana_archive.jpg" title="Archivo Nacional de Asunción" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Example of 16th-century colonial handwriting from the Archivo Nacional de Asunción. Right: The Archivo Nacional de Asunción, which conserves the New Binding Section containing 2,782 documents — some 200 to 400 pages long — documenting slavery and Indigenous forced labour in colonial Paraguay.
</div>

## Project Overview

Colonial Paraguay's archives hold thousands of manuscripts documenting the lived experiences of enslaved Indigenous and African descent people. These sources have remained largely inaccessible, owing to the complexity of early-modern handwriting and the absence of structured digital transcriptions. Manual transcription alone would require fifteen to twenty years of full-time work from a single trained researcher, which has made comprehensive slavery studies functionally impossible and has perpetuated the historical erasure of Afro-Paraguayan and Indigenous experiences {% cite candela_resistencias_2026 %}.

This five-and-a-half-month pilot (1 January to 15 June 2026) tested whether existing HTR models, originally developed for Mexican colonial archives through The New Spain Fleets project, could be adapted to the paleographic and material conditions of Paraguay's Archivo Nacional de Asunción (ANA). Drawing on 6,000 pages of manuscripts transcribed by hand over fifteen years of archival research, we trained and fine-tuned models for automated transcription across six distinct colonial handwriting styles.

### Core Research Questions

**Humanities Questions:**
- How can computational transcription unlock the lived experiences of enslaved Indigenous and African descent people whose voices survive only in colonial Paraguayan manuscripts?
- What technical and methodological foundations are needed to enable descendant and local communities to access and benefit from these archives?

**AI Research Questions:**
- How transferable are existing HTR models trained on 16th and 17th-century Spanish sources to distinct regional hands, materials, and archival conditions?
- What volume and quality of training data are required for reliable performance across heterogeneous colonial calligraphies?

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/havi_transkribus.jpg" title="HTR model training" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Custom HTR models were developed on the Transkribus platform, adapted to Paraguayan colonial manuscripts, with a target of 15% Character Error Rate or lower.
</div>

## Methodology and Approach

### Phase 1: Corpus Curation and Setup (January–February 2026)
- Selected 165 representative documents, running to several thousand pages, covering six handwriting styles
- Catalogued and prepared metadata in collaboration with ANA archivists
- Held an initial coordination workshop with Cardiff University, AmoxcAI-Lab (Mexico), and the Paraguayan team

### Phase 2: Model Training and Testing (February–April 2026)
- Fine-tuned the New Spain Fleets HTR models against a 6,000-page transcription corpus used as ground truth
- Benchmarked baseline against adapted models across calligraphic styles
- Quantified performance metrics and processing times

### Phase 3: Evaluation and Documentation (April–June 2026)
- Compiled open datasets with full technical documentation
- Held a final hybrid workshop presenting results to academic and archival communities
- Developed a scaling strategy for larger funding applications, including community engagement frameworks

### Technical Specifications

**Platform**: Transkribus, a leading HTR platform for historical document transcription
**Target Accuracy**: Character Error Rate (CER) of 15% or lower, equivalent to 85% character accuracy or better
**Training Data**: 6,000 pages of manually transcribed colonial manuscripts
**Corpus Size**: 165 documents representing diverse paleographic conditions
**Handwriting Styles**: Six colonial Spanish calligraphic styles (procesal, procesal encadenada, cortesana, cursiva, and others)

## Results

<!-- TODO: replace the bracketed figures below with the measured results from the final HAVI report before publishing. -->

The pilot established that model transfer across archival contexts is viable. Adapted models reached a Character Error Rate of [X.X%] on the best-performing hands, against [X.X%] for the unadapted baseline, while the most degraded and irregular material remained substantially harder at [X.X%]. Full metrics by calligraphic style, together with the training data thresholds observed, are set out in the project's open documentation.

## Collaborative Research Model

The award focused on establishing technical proof-of-concept through close collaboration between humanists and AI specialists. The team worked side by side to test and refine models, combining historical insight with computational analysis so that technical decisions remained grounded in the archival and cultural realities of colonial Paraguay {% cite candela_whats_2023 %}.

**Project Partners:**

**Archivo Nacional de Asunción (Paraguay)**: ANA paleographer Elizabeth Barriocanal and archival staff served as co-curators, guiding document selection, validating transcriptions, and ensuring the workflow integrated into long-term preservation practice. Their direct involvement strengthened local expertise and guarded against extractive collaboration dynamics.

**AmoxcAI-Lab (Tecnológico de Monterrey)**: Professor Patricia Murrieta-Flores led AI model adaptation, drawing on infrastructure and expertise from The New Spain Fleets project, which developed HTR models for 16th and 17th-century Mexican colonial documents.

**Cardiff University**: Hosted the award and provided research governance, ethics oversight, and administrative support.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/ANA_COLLABORATION_1.jpg" title="Technical workshop" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid path="assets/img/ANA_COLLABORATION_2.jpg" title="Technical workshop" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Technical workshops with ANA staff supported knowledge transfer and sustainable digital capacity building within Paraguay's national archive.
</div>

## Impact

### Advancing AI Research

Colonial manuscripts are among the most demanding materials for automated reading: irregular handwriting, unstable orthography, physical deterioration, and code-switching all compound one another. Testing model transfer across these conditions contributes new evidence on domain generalisation and low-resource adaptation, both unsolved problems in machine learning. The pilot produced empirical data on training-set thresholds, model degradation under physical damage, and accuracy variation across calligraphic styles, with application well beyond this corpus.

### Advancing Humanities Research

Reliable HTR changes what can be known about slavery and about Afro-Paraguayan and Indigenous life in colonial Paraguay, making hundreds of thousands of pages searchable and analysable for the first time. Scholars can trace individuals, families, and places across centuries, and can begin to correct the discipline's over-reliance on metropolitan archives in Buenos Aires, Seville, and Rio de Janeiro {% cite candela_paraguay_2024 %}. This technical foundation is a precondition for creating resources that can be shared with descendant communities.

### Building Global South Digital Capacity

By embedding model training and maintenance within the Archivo Nacional de Asunción, the project supported knowledge transfer and sustainability. Open datasets and workflow documentation serve as templates for other under-resourced archives across Latin America, addressing both technological inequity, since few Latin American archives benefit from custom AI models, and the epistemic gap that keeps local documents at the margins of global research networks {% cite candela_ni_2026 %}.

## Pathway to Scale

The pilot established the technical proof-of-concept needed to pursue larger funding. On the basis of demonstrated HTR viability, the next phase is positioned to:

1. Process all 2,782 New Binding documents alongside further ANA collections
2. Build a public-facing database with interactive maps and biographical reconstructions
3. Develop comparative studies with Uruguayan, Brazilian, and Argentine slavery records
4. **Establish meaningful partnerships with Afro-Paraguayan and Indigenous communities** to co-create educational resources, ensure culturally appropriate interpretation and dissemination, and return these recovered voices to the communities to whom they belong
5. Create replicable workflows for other Global South archives

The technical phase laid essential groundwork, but the goal remains community-engaged scholarship serving both academic research and social justice outcomes.

## Data Preservation and Ethics

All datasets and derived materials are stored using ethical, non-commercial repositories:

**Working Data**: Hetzner Storage Box (Germany), GDPR-compliant and carbon-neutral infrastructure ensuring data sovereignty
**Final Datasets**: Zenodo (CERN/OpenAIRE), with persistent DOIs, FAIR compliance, and free open access under EU governance

This combination supports sustainability while adhering to principles of transparency, equity, and environmental responsibility. Further scaling will incorporate additional ethical frameworks developed in consultation with descendant communities.

---

**Funding**: Schmidt Sciences Humanities and AI Virtual Institute (HAVI) Development Award
**Duration**: 1 January – 15 June 2026 (completed)
**Principal Investigator**: Dr Guillaume Candela (Cardiff University)
**Co-Investigator**: Prof. Patricia Murrieta-Flores (Tecnológico de Monterrey / Lancaster University)

The project builds on methodologies developed through the [New Spain Fleets project](https://doi.org/10.1080/20548923.2025.2484828), which demonstrated the viability of HTR models for 16th and 17th-century Spanish colonial documents from Mexico, reaching Character Error Rates as low as 5.25% for certain calligraphic styles.

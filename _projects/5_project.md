---
layout: page
title: "Unlocking Hidden Histories: HTR for Colonial Paraguayan Archives"
description: "A Schmidt Sciences HAVI Development Award project adapting AI to recover enslaved voices from colonial archives"
img: assets/img/ImageHAVI.png
importance: 1
category: work
related_publications: true
---

As a 2026 Schmidt Sciences Humanities and AI Virtual Institute (HAVI) Development Award recipient, I am leading this groundbreaking project in collaboration with Professor Patricia Murrieta-Flores (Tecnológico de Monterrey / Lancaster University) to adapt Handwritten Text Recognition (HTR) technology for colonial Paraguayan archives. This initiative represents a crucial intersection of artificial intelligence, digital humanities, and decolonial research practices, aiming to unlock thousands of manuscripts documenting the lives of enslaved Indigenous and African descent people.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/havi_manuscript.jpg" title="Colonial manuscript sample" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/havi_ana_archive.jpg" title="Archivo Nacional de Asunción" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Example of 16th-century colonial handwriting from the Archivo Nacional de Asunción. Right: The Archivo Nacional de Asunción conserving the New Binding Section which contains 2,782 documents—some 200-400 pages long—that document slavery and Indigenous forced labor in colonial Paraguay.
    </div>

## Project Overview

Colonial Paraguay's archives contain thousands of manuscripts that document the lived experiences of enslaved Indigenous and African descent people. Yet these sources remain largely inaccessible due to the complexity of early-modern handwriting and the absence of structured digital transcriptions. Traditional manual transcription would require 15-20 years of full-time work for a single trained researcher—making comprehensive slavery studies functionally impossible and perpetuating the historical erasure of Afro-Paraguayan and Indigenous experiences.

This 5½-month pilot project (January–June 2026) tests whether existing HTR models, originally developed for Mexican colonial archives through The New Spain Fleets project, can be successfully adapted to the unique paleographic and material conditions of Paraguay's Archivo Nacional de Asunción (ANA). By leveraging 6,000 pages of manuscripts I have manually transcribed over 15 years of archival research, we will train and fine-tune AI models to achieve reliable automated transcription of six distinct colonial handwriting styles.

### Core Research Questions

**Humanities Questions:**
- How can computational transcription unlock the lived experiences of enslaved Indigenous and African descent people whose voices survive only in colonial Paraguayan manuscripts?
- What technical and methodological foundations are needed to eventually enable descendant and local communities to access and benefit from these archives?

**AI Research Questions:**
- How transferable are existing HTR models trained on 16th–17th-century Spanish sources to distinct regional hands, materials, and archival conditions?
- What volume and quality of training data are required to achieve reliable performance across heterogeneous colonial calligraphies?

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/havi_transkribus.jpg" title="HTR model training" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Using Transkribus platform to develop custom HTR models adapted to Paraguayan colonial manuscripts, targeting greater than 85% Character Error Rate accuracy.
</div>

## Methodology and Approach

### Phase 1: Corpus Curation and Setup (January–February 2026)
- Select 165 representative documents (approximately 41,000 pages) covering six handwriting styles
- Catalogue and prepare metadata in collaboration with ANA archivists
- Initial coordination workshop with Cardiff University, AmoxcAI-Lab (Mexico), and Paraguayan teams

### Phase 2: Model Training and Testing (February–April 2026)
- Fine-tune New Spain Fleets HTR models using my 6,000-page transcription corpus as ground truth
- Benchmark baseline versus adapted models across different calligraphic styles
- Quantify performance metrics and processing times

### Phase 3: Evaluation and Documentation (April–June 2026)
- Compile open datasets with full technical documentation
- Final hybrid workshop presenting results to academic and archival communities
- Develop scaling strategy for larger funding applications, including community engagement frameworks

### Technical Specifications

**Platform**: Transkribus - leading HTR platform for historical document transcription  
**Target Accuracy**: Greater than or equal to 85% Character Error Rate (CER)  
**Training Data**: 6,000 pages of manually transcribed colonial manuscripts  
**Corpus Size**: 165 documents representing diverse paleographic conditions  
**Handwriting Styles**: Six colonial Spanish calligraphic styles (procesal encadenada, Procesal, Cursiva, etc.)

## Collaborative Research Model

This development award focuses on establishing the technical proof-of-concept through close collaboration between humanists and AI specialists. The team works side by side to test and refine models, combining historical insight with computational analysis to ensure every technical decision remains grounded in the archival and cultural realities of colonial Paraguay.

**Current Project Partners:**

**Archivo Nacional de Asunción (Paraguay)**: ANA paleographer Elizabeth Barriocanal and archival staff serve as co-curators, guiding document selection, validating transcriptions, and ensuring the workflow integrates into long-term preservation practices. Their direct involvement guarantees the project strengthens local expertise and avoids extractive collaboration dynamics.

**AmoxcAI-Lab (Tecnológico de Monterrey)**: Professor Patricia Murrieta-Flores leads AI model adaptation, leveraging infrastructure and expertise from The New Spain Fleets project, which successfully developed HTR models for 16th–17th-century Mexican colonial documents.

**Cardiff University**: Provides institutional support.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/havi_collaboration.jpg" title="Technical workshop" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Technical workshops with ANA staff ensure knowledge transfer and sustainable digital capacity building within Paraguay's national archive.
</div>

## Expected Impact

### Advancing AI Research

Colonial manuscripts represent among the most complex materials for automated reading: irregular handwriting, unstable orthography, physical deterioration, and code-switching. Testing model transfer across such conditions contributes new insights into domain generalization and low-resource adaptation—core unsolved problems in machine learning. The project provides empirical data on training-set thresholds, model degradation under damage, and accuracy variation across calligraphic styles, informing broader AI applications requiring handwriting recognition in challenging conditions.

### Advancing Humanities Research

Reliable HTR transforms what can be known about slavery and Afro-Paraguayan and Indigenous life in colonial Paraguay by making hundreds of thousands of pages searchable and analyzable for the first time. Scholars will be able to trace individuals, families, and places across centuries, challenging the over-reliance on external metropolitan archives in Buenos Aires, Seville, and Rio de Janeiro. This technical foundation is essential for eventually creating accessible resources that can be shared with descendant communities.

### Building Global South Digital Capacity

By embedding model training and maintenance within the Archivo Nacional de Asunción, this project ensures knowledge transfer and sustainability. Open datasets and workflow documentation serve as templates for other under-resourced archives across Latin America, addressing both technological inequity (few Latin American archives benefit from custom AI models) and epistemic gaps by re-centering local documents within global research networks.

## Pathway to Scale

This development award establishes the technical proof-of-concept necessary to pursue larger funding. With demonstrated HTR viability, we will be positioned to:

1. Process all 2,782 New Binding documents plus additional ANA collections
2. Build public-facing database with interactive maps and biographical reconstructions
3. Develop comparative studies with Uruguayan, Brazilian, and Argentine slavery records
4. **Establish meaningful partnerships with Afro-Paraguayan and Indigenous communities** to co-create educational resources, ensure culturally appropriate interpretation and dissemination, and return these recovered voices to the communities to whom they belong
5. Create replicable workflows for other Global South archives

The current technical phase lays essential groundwork, but the ultimate goal is community-engaged scholarship that serves both academic research and social justice outcomes.

## Data Preservation and Ethics

All datasets and derived materials will be stored using ethical, non-commercial repositories:

**Working Data**: Hetzner Storage Box (Germany)—GDPR-compliant, carbon-neutral infrastructure ensuring data sovereignty  
**Final Datasets**: Zenodo (CERN/OpenAIRE)—persistent DOIs, FAIR compliance, free open access under EU governance

This combination guarantees sustainability while adhering to principles of transparency, equity, and environmental responsibility. Future scaling will incorporate additional ethical frameworks developed in consultation with descendant communities.

---

**Funding**: Schmidt Sciences Humanities and AI Virtual Institute (HAVI) Development Award  
**Duration**: January 1 – June 15, 2026  
**Principal Investigators**: Dr. Guillaume Candela (Cardiff University) and Prof. Patricia Murrieta-Flores (Tecnológico de Monterrey / Lancaster University)

**Related Publications**:
This project builds upon methodologies developed through the [New Spain Fleets project](https://doi.org/10.1080/20548923.2025.2484828), which successfully demonstrated the viability of HTR models for 16th-17th century Spanish colonial documents from Mexico, achieving Character Error Rates as low as 5.25% for certain calligraphic styles.

---
layout: single
title:  "Can Microfluidics be ubiquitous in science?"
date: 2026-05-01
permalink: /posts/2026/05/can-microfluidics-be-ubiquitous/
header:
  teaser: "images/essay-teaser.jpg" # Optional: Add a thumbnail image
categories: 
  - Essays
  - Academic Writing
tags:
  - research
  - analysis
  - your-topic
---

# Introduction

**NOTE:** Due to technical issues, this content was not well deployed. Please find the post at this [**link**](https://biodotpe.github.io/posts/2026/05/can-microfluidics-be-ubiquitous/) 

What does it mean that a technology is ubiquitous in science? If you ask an AI agent, such as Gemini, it will answer this means

> _“the technology has transitioned from being a specialized, novel tool to becoming a fundamental, inescapable part of the scientific infrastructure.”_
 
 If you request a list of ubiquitous scientific hardware, pipettes, centrifuges, balances, microscopes, and computers are among the instruments that are expected to be available in any research lab. Can cutting-edge technologies, such as microfluidics, become ubiquitous, similar to general-purpose instrumentation? Why should microfluidics be ubiquitous in science?

Microfluidics is an interdisciplinary field with a significant role in numerous biological and medical applications. This technology is implemented in channel-based systems known as _microfluidic chips_, which are commonly made of polymer polydimethylsiloxane (PDMS) using soft lithography but can also be fabricated from polymethyl methacrylate (PMMA), glass, and other materials. In these chips, users can manipulate or process fluid samples, gases, biological entities, and particles in small amounts [1]. This miniaturization reduces costs and reagent consumption and offers the possibility of integrating other laboratory procedures in the same device to perform chemical and biochemical processes [2]. Together with peripheral instruments, users can perform experiments in a high-throughput way, increasing the amount of data available to understand more complex phenomena.

Microfluidics is an interesting case study in which reproducible protocols, such as soft lithography, can be disruptive in a scientific field. In 1998, the Whitesides group pioneered this technique to fabricate microchannel systems. They demonstrated that microfluidic devices could be produced easily without a cleanroom, shortening the time and expenses involved in the cycle of designing, fabricating, and evaluating new ideas compared to other methods [3, 4, 5]. Access to microfluidic devices made with biocompatible, permeable, and optically transparent materials would disrupt scientific research for the following decades. Major world powers, such as China and the United States of America, as well as other developed countries, have recognized the potential of this technology and allocated resources to advance the field in their research institutions [6, 7]. How does a research community learn the potential of a technology? By having access to it and exploring different applications, learning not only its principles and advantages, but also its limitations. The number of publications suggests microfluidics is popular, but does that mean microfluidics will be found in every laboratory in the world, like a balance or centrifuge? Araújo Oliveira Alves et al. (2025) demonstrate this scenario is still far off because microfluidics research is mainly concentrated in specialized laboratories or high-resource settings.

In regions such as the Global South, microfluidics-based projects often face significant infrastructure dependencies, as evidenced by challenges tied to the availability of cleanrooms, basic peripheral instruments, and international delivery of consumables (mainly from the Global North). While soft lithography can be considered a rapid‑prototyping technique for microfluidic devices even in the Global South, researchers still need to fabricate the mold with the desired geometries, and photolithography remains the state‑of‑the art method for producing it [7]. This technique requires sophisticated machinery, expensive silicon wafers, and a cleanroom, which means a high investment for its implementation. 3D printing and CNC micro‑milling are alternatives for mold fabrication, but their minimum resolutions are ~25 µm and ~50 µm, respectively, compared to that of conventional photolithography (~1 µm) [7, 8]. Two-photon lithography (TPL) is an emerging, promising technique that can achieve nanometer resolution and does not require a cleanroom, but commercial equipment is prohibitively costly.

Is mold fabrication the main bottleneck in microfluidic research? This is one of the current constraints on the widespread adoption and reproducibility of microfluidics. This technology is also hindered by its reliance on proprietary instrumentation and complex experimental workflows [9]. Providers, mainly in the Global North, commonly design instruments for specific applications and industries, use their own manufacturing standards, and offer only some components of the overall bioanalysis system [10]. Bulky benchtop systems used in microfluidic assays contain various complex components, including pump systems, valves, and microscope stations. Operators must manually set up these instruments, control the workflow, and coordinate data acquisition through different user interfaces [11]. Individuals with little or no training in the field, usually end users, may find it difficult and expensive to operate and maintain these benchtops, or they may perceive a limited range of applications because of the investment required, which prevents the scientific community from benefiting from the full potential of microfluidics [9, 10].

If budget and complexity would not be limitations, then is this bottleneck solved? Short answer: No. Pump systems illustrate this. Pump systems are integral components of microfluidic setups that control fluid flow for low-volume operations in biological and chemical experiments [12]. The primary pumping systems include syringe, peristaltic, and pressure pumps. The selection of instruments in an experimental setup is typically determined by their working principles, available resources, and research requirements [13]. Among commercial pumping systems, syringe pumps are generally simpler and less expensive than other systems and are widely regarded as the standard for laboratory-scale microfluidic research [14]. Despite offering a steady flow and user-friendly interface, traditional benchtop syringe pumps remain bulky, expensive, and often inflexible in research settings. Their performance can vary based on price and manufacturer, with costs ranging from 500 to 2000 USD and common volume deviations of 2-5% depending on their functions and capabilities [15, 16]. In droplet microfluidics, even small deviations or temporal fluctuations in the flow rate can induce oscillations that directly affect the droplet size and monodispersity [17].

Open-source (OS) designs have emerged as accessible and customizable alternatives for scientific instrumentation, particularly for delivering various fluids and suspensions to microfluidic systems in low-flow-rate applications. These instruments are typically built with off-the-shelf components, costing below 600 USD on average, and can be assembled within a few hours [18, 19, 20]. For syringe pump designs, the reported operational flow rates range from 50 to 10,000 µL/h, making them suitable for various microfluidic experiments. However, both proprietary and open-source syringe pumps continue to face challenges in terms of performance information, as standardized performance definitions and validation workflows remain limited [21].  Performance is often reported using inconsistent units, limited validation ranges, or syringe-specific calibrations, complicating objective comparisons across different platforms [22]. In addition, calibration procedures and dynamic response characteristics are rarely reported in a comparable manner [23]. Recently, international microfluidic consortiums have made significant progress in developing these instruments [24]. The International Organization for Standardization (ISO) has approved the technical document “ISO/TS 6417:2025 Microfluidic pumps — Symbols and performance communication” to standardize the relevant technical information of pumping systems, including syringe pumps [25]. This document establishes common terminology and reporting conventions for the performance of microfluidic pumps. Although this ISO document will contribute significantly to the microfluidic instrumentation market, public design documentation and characterization workflows, as well as community-based definitions, remain crucial for advancing hardware development and enhancing the broader adoption of microfluidic techniques [26].

Within the context of increasing accessibility but limited standardization, this essay proposes that systematic multicenter benchmarking is required to assess the potential ubiquity of microfluidics. This proposal seeks to address the following question: can accessible, well-documented experimental workflows, including 3D printing–based mold fabrication, open-source instrumentation, and calibration protocols, achieve reproducible performance in demanding microfluidic applications? By leveraging open global collaboration, this proposal aims to determine whether accessible workflows can yield consistent results across vastly different laboratory environments.

# Proposal

## 1. Aim and Objectives

The primary goal of this study is to evaluate the reliability of microfluidic assays when transferred between disparate research environments. This study focuses on five critical pillars:

- **Fabrication & Treatment**: Consistency of 3D-printed chip designs and surface treatments
- **Instrument Assembly and Operation**: Reliability of open-source hardware (microscopes and syringe pumps)
- **Protocol Execution**: Human-variable impact on assay performance
- **Workflow Analysis**: Data processing and interpretation consistency
- **Economic Feasibility**: Comprehensive cost-per-run and ease of use (UX) assessments

## 2. Methodology: An 8-Step Framework

This study was designed to move from technical standardization to global data synthesis through the following phases:

### Phase I: Technical Foundation

- **Step 1**: Define the "Base Assay." This includes an open microfluidic CAD design for 3D printing, a list of open-source instruments with full calibration guides, a locked list of consumables, and a standardized sample set with defined analytical variables
- **Step 2**: Deployment of a public English-language repository to host all technical documentation, ensuring "one source of truth" for all participants

### Phase II: Logistics & Recruitment

- **Step 3**: Establish a rigorous timeline and fiscal budget
- **Step 4**: Recruit at least two distinct research groups. To ensure a true test of "ubiquity," the study requires a mix of public and private institutions and a geographical split between the Global North and Global South
- **Step 5**: Budget disbursement and monthly follow-ups to troubleshoot site-specific hurdles

### Phase III: Evaluation & Dissemination

- **Step 6**: Aggregate results to compare experimental variance, total cost of ownership, and researcher feedback on system usability
- **Step 7**: Publication of a white paper detailing lessons learned and "failure points" in the reproducibility chain
- **Step 8**: Developing a long-term plan to transition microfluidics from a specialized lab tool to a ubiquitous technology

## 3. Anticipated Results & Metrics

The study expects to generate a high-resolution map of where microfluidic protocols typically break down. Potential outcomes include:

| Metric | Success Indicator |
|--------|------------------|
| **Inter-Lab Variance** | Low coefficient of variation (CV) in analytical results between the North and South labs |
| **System Accessibility** | Successful fabrication and operation using locally sourced or 3D-printed components |
| **Cost** | Associated costs compared to proprietary, closed-source systems |
| **Usability Score** | High "Ease of Use" ratings from researchers who did not design the original assay |

# References

[1] Whitesides, G. M. (2006). The origins and the future of microfluidics. Nature, 442(7101), 368–373. https://doi.org/10.1038/nature05058

[2] Chen, L., Yang, C., Xiao, Y., Yan, X., Hu, L., Eggersdorfer, M., Chen, D., Weitz, D. A., & Ye, F. (2021). Millifluidics, microfluidics, and nanofluidics: Manipulating fluids at varying length scales. Materials Today Nano, 16, 100136. https://doi.org/10.1016/j.mtnano.2021.100136

[3] Xia, Y., & Whitesides, G. M. (1998). Soft Lithography. Angewandte Chemie International Edition, 37(5), 550–575. https://doi.org/10.1002/(SICI)1521-3773(19980316)37:5<550::AID-ANIE550>3.0.CO;2-G

[4] McDonald, J.C., Duffy, D.C., Anderson, J.R., Chiu, D.T., Wu, H., Schueller, O.J.A. and Whitesides, G.M. (2000), Fabrication of microfluidic systems in poly(dimethylsiloxane). ELECTROPHORESIS, 21: 27-40. https://doi.org/10.1002/(SICI)1522-2683(20000101)21:1<27::AID-ELPS27>3.0.CO;2-C 

[5] Whitesides, G. M., Ostuni, E., Takayama, S., Jiang, X., & Ingber, D. E. (2001). Soft Lithography in Biology and Biochemistry. Annual Review of Biomedical Engineering, 3(1), 335–373. https://doi.org/10.1146/annurev.bioeng.3.1.335

[6] Sackmann, E. K., Fulton, A. L., & Beebe, D. J. (2014). The present and future role of microfluidics in biomedical research. Nature, 507(7491), 181–189. https://doi.org/10.1038/nature13118 

[7] Araújo Oliveira Alves, L., da Silva Felix, J. H., Menezes Ferreira, A. Á., Barroso dos Santos, M. T., Galvão da Silva, C., Maria Santiago de Castro, L., & Sousa dos Santos, J. C. (2025). Advances and Applications of Micro- and Mesofluidic Systems. ACS Omega. https://doi.org/10.1021/acsomega.4c10999

[8] Microfluidic Mold Service - EDEN TECH. (2026, March 17). EDEN TECH. https://eden-microfluidics.com/microfluidic-mold-service/ 
‌
[9] Ortseifen, V., Viefhues, M., Wobbe, L., & Grünberger, A. (2020). Microfluidics for Biotechnology: Bridging Gaps to Foster Microfluidic Applications. Frontiers in Bioengineering and Biotechnology, 8. https://www.frontiersin.org/articles/10.3389/fbioe.2020.589074

[10] Heeren, H. van. (2012). Standards for connecting microfluidic devices? Lab on a Chip, 12(6), 1022–1025. https://doi.org/10.1039/C2LC20937C

[11] Shields IV, C. W., Ohiri, K. A., Szott, L. M., & López, G. P. (2017). Translating microfluidics: Cell separation technologies and their barriers to commercialization. Cytometry Part B: Clinical Cytometry, 92(2), 115–125. https://doi.org/10.1002/cyto.b.21388 

[12] Batista, E., Sousa, J. A., Cardoso, S., & Silvério, V. (2020). Experimental testing for metrological traceability and accuracy of liquid microflows and microfluidics. Flow Measurement and Instrumentation, 71, 101691. https://doi.org/10.1016/j.flowmeasinst.2020.101691 

[13] Walp, K. A., Patel, Y. H., Alsadoun, W., Gordon, H. L., Rastaghi, H., & Oliveira, S. M. D. (2024). A Continuous, Low-Flow, and Multiplexing Pumping System for Microfluidics Applications (p. 2024.08.16.608339). bioRxiv. https://doi.org/10.1101/2024.08.16.608339

[14] Akh, L., Jung, D., Frantz, W., Bowman, C., Neu, A. C., & Ding, X. (2023). Microfluidic pumps for cell sorting. Biomicrofluidics, 17(5), 051502. https://doi.org/10.1063/5.0161223

[15] Coşkun, H., Gul, O., Ferhanoglu, O., & Gokdel, Y. D. (2017). Design and Implementation of a Low-Cost High-Performance Syringe Pump System. 2017 21st National Biomedical Engineering Meeting (BIYOMUT), 1–4. https://doi.org/10.1109/BIYOMUT.2017.8478979

[16] Sadegh-cheri, M. (2022). Using the Recycled Parts of a Computer DVD Drive for Fabrication of a Low-Cost Arduino-Based Syringe Pump. Journal of Chemical Education, 99(2), 521–525. https://doi.org/10.1021/acs.jchemed.1c00260

[17] Kalantarifard, A., Alizadeh-Haghighi, E., & Elbuken, C. (2022). A microfluidic droplet system for ultra-monodisperse droplet generation: A universal approach. Chemical Engineering Science, 261, 117947. https://doi.org/10.1016/j.ces.2022.117947

[18] Booeshaghi, A. S., Beltrame, E. da V., Bannon, D., Gehring, J., & Pachter, L. (2019). Principles of open source bioinstrumentation applied to the poseidon syringe pump system. Scientific Reports, 9(1), 12385. https://doi.org/10.1038/s41598-019-48815-9

[19] Park, S. B., & Shin, J. H. (2024). Fully 3D-printed, nonelectric, spring-powered syringe pump for operating microfluidic devices. Sensors and Actuators B: Chemical, 405, 135289. https://doi.org/10.1016/j.snb.2024.135289

[20] Wu, Y., Chen, Y., & Cheng, Y. (2024). Building an Arduino-Based Open-Source Programmable Multichannel Syringe Pump: A Useful Tool for Fluid Delivery in Microfluidics and Flow Chemistry. Journal of Chemical Education, 101(5), 1951–1958. https://doi.org/10.1021/acs.jchemed.4c00033

[21] Metaxiotou, Z., Bissig, H., Batista, E., Ferreira, M. do C., & Timmerman, A. (2023). Metrology in health: Challenges and solutions in infusion therapy and diagnostics. Biomedical Engineering / Biomedizinische Technik, 68(1), 3–12. https://doi.org/10.1515/bmt-2022-0045

[22] Reyes-Hernandez, D. R., & Heeren, H. van. (2019). Proceedings of the First Workshop on Standards for Microfluidics. NIST, 124. https://doi.org/10.6028/jres.124.001

[23] Batista, E., Martins, R. F., Silverio, V., & Godinho, I. (2025). Advancing calibration techniques for accurate micro and nanoflow measurements. Frontiers in Nanotechnology, 7. https://doi.org/10.3389/fnano.2025.1600426

[24] The Microfluidics Association. (2026). Technical reports - The Microfluidics Association. https://microfluidics-association.org/downloads/

[25] International Organization for Standardization. (2025). ISO/TS 6417:2025(en), Microfluidic pumps—Symbols and performance communication. https://www.iso.org/obp/ui/en/#iso:std:iso:ts:6417:ed-1:v1:en

[26] R. Reyes, D., Heeren, H. van, Guha, S., Herbertson, L., P. Tzannis, A., Ducrée, J., Bissig, H., & Becker, H. (2021). Accelerating innovation and commercialization through standardization of microfluidic-based medical devices. Lab on a Chip, 21(1), 9–21. https://doi.org/10.1039/D0LC00963F

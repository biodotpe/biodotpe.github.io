---
layout: single
title:  "Enabling access to high-throughput biology through open-source microfluidics"
date: 2026-11-09
permalink: /posts/2026/11/enabling-access-to-high-throughput-biology/
header:
  teaser: " " # Optional: Add a thumbnail image
categories: 
  - Essays
  - Academic Writing
tags:
  - droplet microfluidics
  - open science
  - open source hardware
---


# Enabling access to high-throughput biology through open-source microfluidics
 
*Why I want to make droplet microfluidics as accessible as 3D printing.*
 
---
 
## Where it started: a Prusa in Lima
 
The democratization of science has always driven my professional and personal paths.
 
My first exposure to a disruptive technology was in 2014 in Lima, Peru, when an Architecture undergraduate showed me a 3D printer. It wasn't a MakerBot or an UltiMaker; it was a Prusa, an open-source machine. After that, and after reading about the RepRap project, I learned that opening and sharing your projects can change the world.
 
I studied Electronics Engineering, but my main motivation was building things that could help people. The 3D printing movement was a great platform to explore ideas and join local and international communities, such as the FabLab Network and the [Open Biomedical Initiative](https://youtu.be/8gb3knDcr3U) (a young me at 0:16).
 
Then I discovered the Do-It-Yourself Biology (DIY BIO) movement, and it blew my mind: building your own lab equipment, sharing spaces with people from different fields, and opening those resources to the local community. I soon launched a biohacking initiative in Peru, [Biomakers Lab](https://sphere.diybio.org/labs/biomakerslabperu/). Together with the SyntechBio network, I contributed to the community by publishing the [Essential Biohackers Guide](http://media.wix.com/ugd/befeb2_9d07c6e183fe4501808f6a4662f2a899.pdf). Thanks to the members' contributions, the guide was translated into Spanish, Portuguese, and French (here is an [18-minute video](https://youtu.be/eueFBhFDYV0) about it).
 
## Taking open science into academia
 
Self-learning and doing DIY BIO projects in the attic of my parents' house was fun, but I realized that Peruvian scientific culture wouldn't recognize them as "real" science. So I joined academia to understand that culture by pursuing a Master's. My goal was to show that science could be conducted openly in Peru.
 
During the program I learned a lot. I found more barriers, but also people who believed open-source technologies could help with public health research, especially in resource-limited settings. These efforts resulted in one of the largest field deployments I have ever undertaken, which helped us understand [malaria transmission and its relationship with human movement](https://doi.org/10.3389/fpubh.2020.526468), along with [other lessons](https://doi.org/10.1186/s12939-022-01773-7).
 
That work became the seed of the [Health Innovation Lab](https://www.innovalab.info/equipo), a promising young lab at the Institute of Tropical Medicine Alexander von Humboldt, where open data and open technologies drive the group's research.
 
## Communities that shaped my work
 
Along the way I connected with international communities. The Gathering for Open Science Hardware (GOSH) and the OpenFlexure project became my main ones.
 
I am a [former member](https://openhardware.science/governance-structure/) of the GOSH community council, where I helped implement the [Collaborative Development Program](https://forum.openhardware.science/t/apply-here-for-gosh-s-2022-collaborative-development-program-phase-2/4007), which funded early-stage open-source projects. Among the funded projects, [qByte](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3003199) showed that small seed grants can help powerful ideas flourish as open-source instrumentation.
 
## Why droplet microfluidics
 
Although I was already part of academia, my voice still needed a PhD to be credible. It was also an opportunity to move to a neighboring country, start a new story, and learn a new topic: *droplet microfluidics*. I was lucky that my lab and other people at the Institute already embraced the open-source philosophy.
 
For the last five years I have been working to show that combining digital fabrication with open-source electronics can make droplet microfluidics more **accessible, reproducible, and customizable**, perhaps like 3D printing at the beginning of the twenty-first century.
 
**Why does this matter?** Droplet microfluidics is another disruptive technique. It gives access to controlled microenvironments where you can study biological models at the single-cell level, manage their interactions, or retain the molecules they express. It can offer a kind of resolution comparable to what researchers gained when the first microscopes were created.
 
However, microfluidics projects still face two technical limitations (you can find a detailed explanation in my [previous post](https://biodotpe.github.io/posts/2026/05/can-microfluidics-be-ubiquitous/)):
 
1. **Chip fabrication**
2. **Experimental execution** (e.g., peripheral instrumentation)

## What I've built so far
 
I have already tackled the second barrier by developing a **modular open-source workstation**, which includes a [strobe-enhanced microscopy stage](https://wenzel-lab.github.io/strobe-enhanced-microscopy-stage/) and [3D-printed syringe pumps](https://wenzel-lab.github.io/syringe-pumps-and-controller/). The workstation has been experimentally validated, and the results are available in a [preprint](https://doi.org/10.64898/2026.10.19.758223).
 
Replication is already happening:
 
- **Microscopy stage:** five research groups across Chile, Argentina, Mexico, Germany, and the Netherlands have reported replicating it.
- **Syringe pump:** replications have been reported in Argentina, Germany, and on Printables.

What remains unexplored is the reproducibility of chip fabrication and the application of these workflows in biological research. Accessibility is increasing, but standardization is limited.
 
## The proposal
 
I propose to run a **systematic, multicenter benchmarking study** to assess the potential ubiquity of droplet microfluidics.
 
> **Can accessible, well-documented experimental workflows, including 3D printing–based mold fabrication, open-source instrumentation, and calibration protocols, achieve reproducible performance in biological applications?**
 
The plan has two stages:
 
1. **Establish a reference workflow.** Microfluidic chips made with digitally manufactured molds, together with the workstation, will be validated through bacterial encapsulation and growth-monitoring experiments. This will let us evaluate both technical and biological performance.
2. **Test it in another lab.** An independent research laboratory in Latin America will implement and evaluate the platform, assessing experimental reproducibility, usability, and adaptability across different laboratory environments.

Through collaborative development, standardized protocols, and openly shared hardware designs, software, and experimental results, the project aims to:
 
- reduce technological barriers,
- enable decentralized fabrication and local maintenance, and
- build a community-driven foundation for accessible high-throughput biological experimentation.

## Who it's for, and what could change
 
The initial target users are academic research laboratories in Latin America, particularly South America, that do microbial research and want to run microfluidic experiments without specialized commercial infrastructure. These labs often face limited access to scientific equipment, dependence on foreign manufacturers, and supply-chain constraints.
 
This project could establish a **new reference standard for accessible microfluidics**: open-source instrumentation, openly documented chip designs and fabrication methods, and standardized calibration protocols that let research laboratories worldwide run reproducible, high-throughput biological experiments independently.
 
By demonstrating consistent performance across laboratories with different resources and technical capabilities, the project could challenge the assumption that reliable microfluidics requires specialized commercial infrastructure.
 
In the long term, this open infrastructure could turn microfluidics from a technology concentrated in specialized laboratories into a widely accessible experimental tool, one that lets researchers develop, adapt, and validate their own workflows. That shift would promote scientific collaboration, technological independence, and more sustainable instrumentation practices, while accelerating innovation in microbial research.

## Get in touch
 
If you are interested in collaborating, know of a grant that fits this proposal, or have funds to carry out this idea, please contact me.
 
---
 
**PS:** By the time I posted this essay, the Juncker Lab had launched an [initiative](https://junckerlab.org/global-initiative) to make microfluidic chip fabrication more accessible through photopolymerization-based 3D printing, which aligns with my hypothesis about its [ubiquity](https://biodotpe.github.io/posts/2026/05/can-microfluidics-be-ubiquitous/).
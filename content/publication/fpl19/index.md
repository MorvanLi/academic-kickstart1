---
title: "Software/Hardware Codesign of the Post Quantum Cryptography Algorithm NTRUEncrypt Using High-Level Synthesis and Register-Transfer Level Design Methodologies"
authors:
date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Software/Hardware Codesign of the Post Quantum Cryptography Algorithm NTRUEncrypt Using High-Level Synthesis and Register-Transfer Level Design Methodologies"
publication_short: "NTRUEncrypt High Level Synthesis vs RTL"

abstract: "When quantum computers become scalable and reliable, they are likely to break all public-key cryptography standards, such as RSA and Elliptic Curve Cryptography. The projected threat of quantum computers has led the U.S. National Institute of Standards and Technology (NIST) to an effort aimed at replacing existing public-key cryptography standards with new quantum-resistant alternatives. In December 2017, 69 candidates were accepted by NIST to Round 1 of the NIST Post-Quantum Cryptography (PQC) standardization process. NTRUEncrypt is one of the most well-known PQC algorithms that has withstood cryptanalysis. The speed of NTRUEncrypt in software, especially on embedded software platforms, is limited by the long execution time of its primary operation, polynomial multiplication. In this paper, we investigate speeding up NTRUEncrypt using software/hardware codesign on a Xilinx Zynq UltraScale+ multiprocessor system-on-chip (MPSoC). Polynomial multiplication is implemented in the Programmable Logic (PL) of Zynq using two approaches: traditional Register-Transfer Level (RTL) and High-Level Synthesis (HLS). The remaining operations of NTRUEncrypt are executed in software on the Processing System (PS) of Zynq, using the bare-metal mode. The speed-up of our software/hardware codesigns vs. purely software implementations is determined experimentally and analyzed in the paper. The results are reported for the RTL-based and HLS-based hardware accelerators, and compared to the best available software implementation, included in the NIST submission package. The speed-ups for encryption were 2.4 and 3.9, depending on the selected parameter set. For decryption, the corresponding speed-ups were 4.0 and 6.8. In addition, for the polynomial multiplication operation itself, the speed up was in excess of 75. Our code for the NTRUEncrypt polynomial multiplier accelerator is being made open-source for further evaluation on multiple software/hardware platforms."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- NTRU
- NTRUEncrypt
- RTL
- HLS
- FPGA
- High Level Synthesis
featured: false

links:
url_poster: https://people-ece.vse.gmu.edu/~kgaj/publications/conferences/GMU_FPL_2019_SWHW_poster.pdf
url_pdf: https://people-ece.vse.gmu.edu/~kgaj/publications/conferences/GMU_FPL_2019_SWHW.pdf
url_code: https://cryptography.gmu.edu:4443/PQC_Round1
url_source: https://cryptography.gmu.edu:4443/PQC_Round1

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}} -->

<!-- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->


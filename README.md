# Addressing Technical Concerns About APCA

This repository provides detailed technical responses to recurring misconceptions about the [Accessible Perceptual Contrast Algorithm (APCA)](https://apcacontrast.com) and visual contrast research.

APCA is the candidate contrast method under evaluation for [W3C Accessibility Guidelines (WCAG) 3.0](https://www.w3.org/TR/wcag-3.0/). It was developed to address well-documented limitations of the WCAG 2.x contrast ratio formula — limitations grounded in decades of peer-reviewed vision science from researchers including Stevens, Campbell & Robson, Barten, Legge, Peli, and Fairchild. For a comprehensive peer-reviewed overview, see [*Realities and Myths of Contrast and Color*](https://www.smashingmagazine.com/2022/09/realities-myths-contrast-color/) (Smashing Magazine, 2022).

We maintain an [**open discussion forum**](https://github.com/Myndex/SAPC-APCA/discussions) for questions, comments, and technical critique. Good-faith engagement is always welcome.

The responses below address specific published claims that have circulated within the accessibility community and caused confusion about the state of contrast research.

---

## Response to "WCAG 3 Is Not Ready Yet" (Eggert, December 2021)

In December 2021, Eric Eggert published a blog post titled *"WCAG 3 is not ready yet,"* which included claims about APCA and the WCAG 3 development process. The post has been cited in subsequent discussions as though it were a technical evaluation of APCA. It is not — it contains no original analysis, no data, and no engagement with the peer-reviewed literature on contrast perception.

Because the post continues to be referenced, a point-by-point technical response is warranted. The response addresses each claim against the published research record, identifies unsupported assertions, and provides the citations that were absent from the original piece.

**[Read the full technical response →](WCAG3NotReady-Rebuttal.md)**

---

## Corrections to "The Missing Introduction to APCA" (Bengfort)

Tobias Bengfort (xi) created a repo called "apca-introduction" which contains significant inaccuracies about the APCA algorithm and its development context. We [forked the repo](https://github.com/Myndex/apca-introduction) to provide corrections and clarifications. Summaries with links:

### [Corrected Introduction](https://github.com/Myndex/apca-introduction?tab=readme-ov-file#corrected-fork-of-apca-introduction-with-comments)

The corrected version revises factual errors while maintaining the original document's structure and tone. Key corrections include the visual comparison examples, which in the original used low spatial frequency fonts at contrast values within the range of contrast constancy — obscuring the perceptual differences between the algorithms. The original repo also applied modifications to the APCA code that invalidated its results.

### [Response to the Analysis Document](https://github.com/Myndex/apca-introduction/blob/main/analysis.md)

The original "Detailed analysis of APCA" contains methodological errors including the removal of key APCA components (the output clamp and scale/offset adjustments), the use of `Math.exp()` in a way that destroys perceptual uniformity, and the introduction of an unsupported 0.4 flare value presented as "modified WCAG 2." These errors are addressed point by point with correct mathematics and citations.

### [Response to the Blog Post on Contrast Mathematics](https://github.com/Myndex/apca-introduction/blob/main/Math_Errors_and_Corrections.md)

A response to claims about contrast mathematics that misapply mathematical concepts to the domain of visual perception without accounting for the relevant psychophysics.

---

## Scientific Limitations of WCAG 2 Contrast

WCAG 2's contrast formula does not model human contrast perception on self-illuminated displays. The formula ignores spatial frequency, adaptation state, surround luminance, and display polarity — all factors demonstrated to affect perceived contrast by decades of peer-reviewed research. As a result, the formula produces systematic false passes (unreadable text that meets the ratio) and false fails (readable text that does not).

The [APC-Readability Criterion](https://readtech.org/ARC/) is a public working draft providing evidence-based guidance for visual accessibility and readability, derived from peer-reviewed research. Its bibliographies and references detail the scientific basis for each guideline.

The importance of accurate contrast specifications should not be underestimated. Inadequate or inaccurate standards for visually readable content result in high visual fatigue, inaccessible content, and reduced reading across the population. Effective readability standards require a perceptually accurate contrast method — which is the purpose APCA was designed to serve.

---

## Authoritative Resources

- [**Easy Intro to APCA**](https://git.apcacontrast.com/documentation/APCAeasyIntro) — Plain-language overview of readability and user needs
- [**Why APCA**](https://git.apcacontrast.com/documentation/WhyAPCA) — Rationale for a new contrast method
- [**APCA in a Nutshell**](https://git.apcacontrast.com/documentation/APCA_in_a_Nutshell) — Quick technical summary
- [**Bridge PCA**](https://bridgepca.com) — WCAG 2-compatible implementation using APCA technology
- [**Myndex Linktree**](https://linktr.ee/Myndex) — Curated list of key resources, tools, and documentation
- [**SAPC-APCA Discussions**](https://github.com/Myndex/SAPC-APCA/discussions) — Open forum for questions and feedback
- [**APC-Readability Criteria**](https://readtech.org/ARC/) — Public working draft of next-generation visual accessibility guidelines

---

*Maintained by [Andrew Somers / Myndex Research](https://github.com/Myndex) · [Inclusive Reading Technologies, Inc.](https://readtech.org)*

*Please direct questions or comments to the [discussion forum](https://github.com/Myndex/SAPC-APCA/discussions).*

---

Contents of this repository are copyright © 2023–2026. All Rights Reserved.

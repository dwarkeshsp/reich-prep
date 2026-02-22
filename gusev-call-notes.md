# Prep Call with Sasha Gusev — Feb 21, 2026

## Key Takeaways

### The Big Picture Problem
Genetics can tell us two things about human history: (1) **topography/demography** — where people were, how populations grew and mixed; and (2) **natural selection** — which traits were under pressure. The fundamental challenge is that these two forces shape each other. Selection changes demographic properties; demography changes how we estimate selection. We don't have a unified model that handles both simultaneously — we patch one onto the other and go back and forth.

### What's Clear
A handful of loci are clearly under strong selection: **lactase (LCT), pigmentation/eye color (SLC45A2, HERC2), HLA/autoimmunity loci**. For these, we can track allele frequency changes across ancient and modern populations. But even these are puzzling:

- **Lactase** — The selection on LCT is temporally out of sync with the archaeological record of domestication and milk use. People were drinking milk well before the allele started sweeping. And the selection *accelerated* over time (per Mathieson & Terhorst 2022) for reasons we don't understand. Additionally, Patterson et al. (2022) showed selection started in Britain about a century prior to the rest of European samples, for unknown reasons.
- **Eye color** — Pigmentation variants appear in multiple parts of the world but are only selected in one. Why eye color — which changes aesthetics but has no obvious fitness impact — is one of the most differentiated loci remains a mystery.
- **Large-effect variants that *aren't* selected** (from Gusev's follow-up email citing his blog post):
  - **APOE** — key Alzheimer's and longevity gene, no strong selection
  - **FTO** — one of the largest common effects on obesity and diabetes, no selection
  - **Menopause/fertility genes** — variants that substantially reduce age of menopause, no selection
  - **IL23R** — one of the largest known protective effects for autoimmune disease, selection either weak or neutral depending on admixture modeling
  - Gusev's summary: "recent evolution seems to be picking winners and losers fairly arbitrarily"

### The Akbari Puzzle
Gusev sees the Akbari result as genuinely interesting but unresolved:

- **Conventional methods** (modeling demographic parameters explicitly) find very little selection — dozens of loci at most.
- **Akbari's approach** (treating demography as nuisance via GRM, calibrating against GWAS) finds hundreds, projecting to thousands.
- We don't know who's right. Either Akbari appropriately relaxed unnecessary assumptions, or they relaxed assumptions that were actually important and introduced false positives.
- **The polygenic selection results** in Akbari (enrichment for weight, height, cognitive traits) are at the genome-wide/aggregate level. At the level of individual loci where we have better statistical understanding, the large-effect variants for these traits (BMI, lipids, etc.) are NOT under selection. There's a disconnect between the aggregate signal and the individual-locus picture.

### The Core Contradictions (Still Unresolved)

1. **No fixed differences between populations.** Coop et al. 2009 (and Pritchard, Pickrell & Coop 2010) showed that when you compare modern Eurasians to modern Africans, almost all allele frequency differences are explained by drift. Zero examples of extreme differentiation between closely related populations. If Akbari is right that "the whole genome is seething with selection" in Eurasia, why don't we see any of it when comparing endpoints?

2. **Two explanations for the absence:**
   - Selection is genuinely not happening (or negligible) — environmental pressures are too subtle and ephemeral for selection to ever have enough time to act. This would be a profound implication for understanding human history.
   - Selection IS happening but is so polygenic (100,000 variants each shifting by 1/100,000th of the fitness effect) that it's undetectable at individual loci. The field has good single-locus tests but struggles to aggregate effects genome-wide.

3. **The slave trade paradox.** Reich's own work showed no detectable selection in African Americans over ~200 years of extreme environmental pressure. If something that intense leaves no trace, how can we see "dynamic seething selection" in Eurasia where environmental pressures were presumably less severe?

4. **Fluctuating vs. accelerating selection.** Akbari proposes two explanations: (a) selection coefficients fluctuate over time, preventing fixation; (b) selection accelerated in the Holocene due to farming/cultural change. Both have problems — if accelerating, why nothing in modern data? If fluctuating, why does the linear model catch it?

### New Paper: Colbran et al. 2025
Gusev flagged **Colbran et al. (Jan 2025 preprint, Mathieson as last author)** — "Global patterns of natural selection inferred using ancient DNA" — as the most important development since the Akbari preprint.

**What they did:** Replicated the Akbari-style analysis but included ancient DNA from East Asia, South Asia, and Africa (not just Europe).

**Key finding (from Gusev's follow-up email):** "Variants passing FDR<0.05 (N=215) in Europe, where we had the highest power, are significantly enriched in the lower tail of the p-value distribution for all other non-African regions (P = 9.0×10⁻⁸, 1.5×10⁻⁵, 9.2×10⁻¹¹ and 0.45 for East Asia, the Americas, South Asia, and Africa, respectively)."

Note: NOT significant for Africa (p=0.45), which is interesting — consistent with either post-split selection or different selective pressures in Africa.

**Three interpretations (per paper):**
1. **Parallel selection on standing variation** — same alleles independently selected in different environments
2. **Selection on recurrent mutations at the same loci**
3. **Selection prior to the most recent shared ancestry** — i.e., it happened before populations split

Gusev noted they can't yet determine the direction of selection or put precise timing on it — just that the overlap is greater than chance.

### What Gusev Doesn't Have
He acknowledged there isn't a good comprehensive paper that synthesizes "here's what genetics has actually taught us about human history." When he tried to write that as his blog post, he was mostly left with questions. The archaeological/historical integration is "David's wheelhouse" — Reich is better positioned to connect genetic evidence with the historical record.

### Gusev's Relationship with Reich
- Not adversarial — "huge fan of David." Critical/skeptical of Akbari methodology because it's cutting edge, not because of any disagreement about goals.
- They've discussed the blog posts and the paper directly. Gusev has also talked to Akbari extensively.
- Reich used Gusev's "where are the selective sweeps" blog post as the intro to a recent ASHG invited talk in Boston (may be recorded — worth checking).

## Action Items
- [x] Download Colbran et al. 2025 preprint — DONE
- [x] Look up the specific large-effect variants Gusev mentioned — DONE (APOE, FTO, menopause genes, IL23R; see his blog post)
- [ ] Check if Reich's ASHG presidential symposium talk was recorded — **email ASHG directly** (flier: https://www.ashg.org/wp-content/uploads/2025/04/ASHG2025-Presidential-Symposium-Biographies.pdf; prior year example on YouTube: https://www.youtube.com/watch?v=qQLWPeKUROM)
- [x] Look up Pritchard, Pickrell & Coop paper — DONE (downloaded)

## Follow-up Email from Gusev (Feb 21, 2026)
- Provided exact Colbran et al. quote with p-values for cross-population enrichment
- Provided Coop et al. / Pritchard-Coop quote on sweep patterns mimicking neutral structure
- Listed specific non-selected loci from his blog: APOE, FTO, menopause genes, IL23R
- ASHG presidential symposium video may be available — contact ASHG directly

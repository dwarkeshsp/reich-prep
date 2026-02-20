# Paper Summaries for Reich Interview Prep

## Mathieson Lab Papers

### Mathieson & Terhorst 2022 — "Direct detection of natural selection in Bronze Age Britain"

**What they built:** A new method for estimating *time-varying* selection coefficients from ancient DNA. Previous methods assumed selection was constant over time; this one lets selection strength change generation by generation. It's fast enough to run genome-wide.

**What they found:** Applied to 529 ancient British genomes (past 4,500 years) + 98 present-day British, they found **7 genome-wide significant loci**:
- **LCT** (lactase persistence) — strongest signal, selection coefficient ~0.08 peaking 150–100 generations ago, then *weakening* to ~0.02 recently
- **SLC45A2** and **HERC2** — skin/eye pigmentation, increasing from ~0% to ~60% over 3,000 years
- **3 HLA loci** — immune function (celiac disease, psoriasis, ankylosing spondylitis risk)
- **DHCR7** — vitamin D metabolism

**The big insight:** Almost all signals relate to **vitamin D and calcium**. Lighter skin = more UV penetration = more vitamin D synthesis. Lactase persistence = ability to drink milk = calcium + vitamin D. DHCR7 directly protects against vitamin D deficiency. The story: when Neolithic/Bronze Age Britons shifted from marine-rich hunter-gatherer diets to agriculture, they lost their dietary vitamin D source, and the cloudy British skies made genetic adaptation necessary.

**Selection strength varies over time** — this is key. LCT selection was strongest 4,500–3,000 years ago and then weakened. This supports Akbari et al.'s "fluctuating selection" hypothesis and helps explain why methods assuming constant selection get confused.

**Polygenic selection:** Only skin pigmentation showed significant evidence of polygenic selection. Height, BMI, head circumference, insulin — nothing. Previous claims of polygenic selection on height were "largely driven by residual stratification" in GWAS.

---

### Mathieson & Mathieson 2018 — "FADS1 and the timing of human adaptation to agriculture"

**The gene:** FADS1/FADS2 encode enzymes that convert short-chain to long-chain polyunsaturated fatty acids (PUFAs). Meat and fish are rich in long-chain PUFAs; plant-based diets are not. So a population switching from hunting to farming would benefit from more efficient FADS1 activity.

**The puzzle:** The derived FADS1 haplotype (haplotype D) is at ~60% frequency in present-day Europeans and was clearly selected. But *when*?

**What ancient DNA shows:**
- The derived allele was **almost completely absent** in Upper Paleolithic and Mesolithic Europe (before ~8,500 BP)
- It was **introduced** ~8,500 years ago by Early Neolithic farmers carrying "basal Eurasian" ancestry
- But — crucially — it was **not under strong selection in Early Farmers**. Selection was not significantly different from zero in either hunter-gatherers or early farmers.
- Strong selection (s = 3.4–6.9%) only kicked in **recently**, in Steppe-ancestry populations, roughly the past ~4,000 years

**The surprise:** Selection at FADS1 was NOT tightly linked to the initial adoption of agriculture. The allele arrived with farmers but wasn't selected until much later — perhaps as late as the Bronze Age. The same pattern holds for LCT (lactase) and SLC22A4 (ergothioneine transporter). All three show strong selection only in the past ~4,000 years.

**Why this matters:** It complicates the simple narrative that "farming drove dietary adaptation." Early farmers may have retained enough hunter-gatherer dietary strategies that the selective pressure wasn't strong yet. Or populations were too small and structured for selection to operate efficiently. The real dietary crunch may have come later, with intensification and population growth in the Bronze Age.

**Other diet genes checked:** AMY1 (salivary amylase for starch digestion) — no significant change in copy number from Paleolithic to present. NAT2, PLRP2 — no evidence of selection in any period. The proposed "agricultural adaptation" genes mostly don't show the expected pattern.

---

### Cox et al. 2025 — "Effects of ancestry, agriculture, and lactase persistence on the stature of prehistoric Europeans"

**The question:** Were Neolithic people really shorter than hunter-gatherers, as the "farming made people unhealthy" narrative claims?

**The approach:** They combine actual femur length measurements with ancient DNA polygenic scores (PRS) for height from 568 individuals across Eurasia (38,000–600 BP). This lets them decompose height changes into genetic vs. environmental components.

**Key findings:**

1. **Neolithic people were only modestly shorter** than preceding Mesolithic groups (~0.9 cm in femur length, ~2.5 cm in standing height). And much of this difference is **genetic** (different ancestry), not environmental. Once you control for PRS, the residual (environmental) difference is not significant. This **challenges** the longstanding hypothesis that agriculture caused a systematic decline in health/stature.

2. **Modern GWAS effects replicate in ancient people.** The slope of ancient vs. present-day SNP effect sizes is ~1.0 — meaning the genetic architecture of height has been remarkably stable over thousands of years. 81 of the top 1,000 height SNPs replicate at nominal significance.

3. **Lactase persistence had a huge effect on ancient stature** — 0.24 standard deviations — even though it has **zero association with height in modern populations**. This is the paper's most striking finding: a gene-environment interaction that has vanished. In an ancient world where milk was a crucial calorie/calcium source and alternatives were scarce, being able to digest lactose made you meaningfully taller. Today, with abundant food variety, it doesn't matter.

4. **You can't just project modern GWAS onto ancient people.** The lactase finding shows that gene-trait relationships change with environment. Using present-day genetic data to infer past phenotypes misses these interactions.

---

### Cox et al. 2023 — "Socio-cultural practices may have affected sexual dimorphism in stature in Early Neolithic Europe"

**The question:** Why does sexual dimorphism in height (male/female ratio) vary so much across Early Neolithic European populations?

**The approach:** They combine ancient DNA, skeletal measurements, paleopathology (tooth enamel defects, skull lesions), and dietary stable isotopes (carbon-13, nitrogen-15) from ~1,400 individuals across four Neolithic populations: Northern Central Europe, Southern Central Europe, Balkans, and Mediterranean.

**Key findings:**

1. **Genetics can't explain the differences.** Polygenic scores for height are essentially identical across all four populations, and there's no genetic difference between male and female PRS. The height variation is non-genetic.

2. **Northern Central European women were disproportionately short.** Males were similar in height across regions, but females in the North were significantly shorter than females in the South (~1.7 cm femur difference). This produced much higher sexual dimorphism in the North (13% male/female ratio vs. 5% in Mediterranean).

3. **The cause appears to be cultural, not climatic.** Northern populations show more skeletal stress markers (linear enamel hypoplasias — tooth defects indicating childhood stress episodes). These are associated with shorter femurs, and the effect is driven by females. The authors interpret this as **male preference in resource allocation** — in the harsher northern agricultural frontier, under nutritional stress, males may have been preferentially fed.

4. **Mediterranean populations show a different pattern** — males are shorter than other males, possibly reflecting more hunter-gatherer admixture (WHG ancestry is higher in Mediterranean Neolithic populations).

**Why this matters for the interview:** It's a vivid example of how *culture* shapes biology in ways that look like they could be genetic but aren't. The sex-specific height differences arose from social practices (resource allocation), not from natural selection on height alleles. This connects to the broader theme that cultural evolution may be doing much of the work that people assume must be genetic.

---

## Big Picture Papers

### Hernandez et al. 2011 — "Classic selective sweeps were rare in recent human evolution"

**The question:** Were "classic sweeps" — where a new beneficial mutation arises and rapidly fixes in the population, dragging nearby variation along with it — actually common in human evolution?

**The test:** If classic sweeps were common, you'd see deeper troughs of genetic diversity around amino acid substitutions (protein-changing mutations, the most likely targets of selection) compared to synonymous substitutions (which don't change the protein and shouldn't be selected). They looked at 179 genomes from the 1000 Genomes Project.

**The result:** The diversity troughs around amino acid substitutions and synonymous substitutions are **indistinguishable**. In *Drosophila* flies, by contrast, amino acid substitutions do show deeper troughs (~13% of them involved classic sweeps). In humans, this signature is absent.

**Additional evidence:** They looked for enrichment of highly differentiated alleles (high F_ST between populations) at functional sites — amino acid changes, UTRs, regulatory regions. The enrichments are either not significant or can be explained entirely by **background selection** (which reduces effective population size near genes, inflating F_ST mechanically). There are only 4 fixed amino acid differences between Yoruba and Europeans across the entire genome — far too few for sweeps to be a common mode of adaptation.

**The punchline:** Classic sweeps were "too infrequent within the last 250,000 years to have had discernible effects on genomic diversity." This doesn't mean humans haven't adapted — it means adaptation mostly worked through **other modes**: selection on standing variation (alleles already present in the population), polygenic selection (small shifts at many loci), or soft sweeps. The paper essentially closed the door on the earlier excitement about thousands of sweep candidates and redirected the field toward subtler forms of selection.

---

### Coop et al. 2009 — "The Role of Geography in Human Adaptation"

**The question:** When we find alleles at different frequencies in different populations, is that because of local adaptation (different environments selecting for different alleles), or just neutral population structure (drift, migration, bottlenecks)?

**The approach:** They examined genome-wide SNP data from 53 populations in the HGDP (Human Genome Diversity Panel) and HapMap, looking at the geographic distributions of variants with the most extreme frequency differences between populations (high F_ST).

**Key findings:**

1. **Selection signals mirror neutral population structure almost perfectly.** The geographic distribution of the most differentiated alleles (candidate selection signals) is almost entirely predictable from random genetic markers. If you know the neutral population structure, you can predict where "selected" alleles will be found. This means drift and demography — not environment — are the primary determinants of allele frequency differences.

2. **Zero examples of extreme differentiation between closely related populations.** Across the entire HGDP dataset, there isn't a single SNP with very extreme allele frequency differences between populations that are closely related (low mean F_ST). If environmental differences (diet, climate, pathogens) were driving strong local adaptation between neighboring populations, you'd expect to see this. You don't.

3. **Nearly all fixation events occurred outside Africa, and most are in East Asians.** This is consistent with stronger drift in non-African populations (smaller effective population sizes, bottlenecks) rather than more selection. The East Asian bias is likely driven by the strongest drift of the three continental groups.

4. **Three geographic patterns of sweeps:** Non-African sweeps (like KITLG for skin pigmentation — shared across all non-Africans), West Eurasian sweeps (like SLC24A5 for light skin — high in Europe/Middle East/South Asia, absent in East Asia), and East Asian sweeps (like MC1R, EDAR). Interestingly, Europeans and East Asians evolved lighter skin via **completely different genes**, suggesting parallel evolution rather than shared selection.

5. **Selection is "strongly constrained" by population history.** The alleles that spread to high frequency did so within the broader population movements and splits that already shaped human diversity. Selection is real but operates within the channels carved by demography, not independently of them.

---

### Irving-Pease et al. 2024 — "The selection landscape and genetic legacy of ancient Eurasians"

**The question:** What can ~1,600 imputed ancient genomes tell us about selection and the genetic legacy of ancient populations in present-day Europeans?

**What's new methodologically:** They developed a "chromosome painting" technique to assign every stretch of every ancient genome to one of four ancestral backgrounds — WHG, EHG, CHG, or Anatolian Farmer (ANA) — and then ran selection tests *within each ancestry*, not just on the raw allele frequencies. This is crucial because admixture between these groups creates allele frequency changes that look like selection but aren't.

**Key findings on ancestry:**

1. **Ancient ancestries are still geographically patterned in modern Britain.** WHG-related ancestries are highest in Wales, Cornwall, and Scotland. Steppe ancestry peaks in the Outer Hebrides and Ireland. Neolithic farmer ancestry is highest in southern/eastern England. This mirrors the modern "Anglo-Saxon/Celtic" divide — but its origins are ancient, not medieval.

2. **Ancestry-specific polygenic risk scores.** They calculated what disease/trait risk would look like if a person's genome were 100% from one ancestral population. Steppe ancestry contributes the highest predicted mass, trunk size, and lung capacity. Neolithic farmer ancestry scores highest for anxiety and irritability. WHG/CHG ancestry scores highest for cholesterol, blood pressure, diabetes, and Alzheimer's risk.

**Key findings on selection:**

3. **Without ancestry stratification: zero genome-wide significant sweeps** from modern data alone. With ancestry stratification: **21 genome-wide significant loci.** This demonstrates that admixture was masking selection signals — exactly what Souilmi et al. predicted.

4. **LCT/lactase:** Selection began ~6,000 years ago, driven by sweeps on the EHG and CHG ancestral backgrounds. But other SNPs in the broader locus were rising *earlier* — as far back as 12,000 years ago — suggesting the selective process at this region is more complex and ancient than previously thought.

5. **FADS1/FADS2:** Strong selection confirmed, associated with the shift to a more vegetarian diet. The selection occurred in Neolithic populations before they arrived in Europe and continued during the Neolithic and Bronze Age.

6. **HLA/immune region:** An 8 Mb sweep spanning the entire HLA region, with multiple independent selection events at different times. Strongly associated with protection against chickenpox, intestinal infections, STDs. This may explain why autoimmune diseases are so common today — protection against ancient pathogens came at the cost of increased autoimmune susceptibility.

7. **Height differences between Northern and Southern Europe** are explained by differential Steppe ancestry, not by selection on height. This is important because it overturns previous claims of polygenic selection on height.

---

### Kong et al. 2017 — "Selection against variants in the genome associated with educational attainment"

**The question:** Are the genetic variants associated with educational attainment changing in frequency in the modern Icelandic population?

**The dataset:** 109,120 Icelanders with genotype data, linked to a near-complete genealogical database going back to 1910. They computed a polygenic score for educational attainment (POLY_EDU) and tracked its relationship with fertility.

**Key findings:**

1. **Higher POLY_EDU = fewer children.** For females, each 1 SD increase in POLY_EDU corresponds to 0.084 fewer children (p = 10^-43). For males, the effect is -0.054. This is primarily mediated through **delayed reproduction** — higher POLY_EDU women have their first child later.

2. **The effect is independent of actual education.** Even after controlling for how much education someone actually got, POLY_EDU still predicts fewer children. So it's not just "educated people have fewer kids" — there's something about the *genetic propensity* for educational attainment that reduces fertility, beyond the education itself. The authors suggest POLY_EDU captures "the capacity to acquire education" including long-term planning and delayed gratification.

3. **POLY_EDU has been declining.** Average POLY_EDU dropped by ~0.010 standard units per decade between 1910–1990 (p = 5.8 × 10^-35). This is a small but steady decline — "a blink of an eye" evolutionarily but potentially significant over centuries.

4. **Extrapolation to IQ:** POLY_EDU explains ~3.7% of EA variance. Under assumptions about the total genetic component, the decline translates to roughly **0.30 IQ points per decade** of genetic decline. Meanwhile, the Flynn Effect (environmental improvements) has been increasing measured IQ by ~3 points per decade — 10x larger and in the opposite direction. So the environmental gains have been overwhelming the genetic decline, but the genetic trend is real and persistent.

5. **The authors are careful about generalizability.** They note this is a gene-environment interaction — the negative correlation between educational attainment and fertility is a product of modern socioeconomic conditions. In a different environment, the direction and magnitude of selection could be completely different.

**Why this matters for the interview:** This is the one paper that directly addresses selection on cognitive/behavioral traits — and it finds selection *against* variants associated with educational attainment, not for them. But it's happening through a modern demographic mechanism (delayed reproduction), not through the kind of ancient selection pressures Akbari et al. are testing for. It connects to the broader puzzle: if cognitive traits were under strong positive selection historically, why don't Akbari et al. find enrichment? And if the modern trend is negative, what does that imply long-term?

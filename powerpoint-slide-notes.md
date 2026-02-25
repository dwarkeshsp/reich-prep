# Copenhagen Talk — Per-Slide Notes

**Talk:** "Ancient DNA reveals pervasive directional selection across West and East Eurasia"
**Speaker:** David Reich, Feb 20, 2026, Globe Institute, University of Copenhagen
**Paper:** Akbari et al. 2026 (updated from 2024 bioRxiv preprint)

---

## PART 1: SETUP & METHOD (Slides 1–5)

### Slide 1 — Title Slide
**Text:** "Ancient DNA reveals pervasive directional selection across West and East Eurasia"
**Image:** Photo of Reich

- Co-authored with Ali Akbari (his student/postdoc who built the statistical framework and website)
- Note the title says "pervasive" — this is the headline claim that will surprise the field
- Also note "West AND East Eurasia" — the East Asian replication is new since the bioRxiv preprint

### Slide 2 — Growth in ancient DNA data
**Text:** Growth in reported ancient DNA data, "Allen Ancient DNA Resource" (Mallick et al. 2024)
**Image:** Bar chart (WMF format — likely shows exponential growth in published ancient genomes)

- The Allen Ancient DNA Resource is Reich lab's public database
- Context: field went from ~0 ancient genomes in 2010 to tens of thousands by 2025
- Sets up the argument: we now have enough data to see things we couldn't before

### Slide 3 — The mainstream view
**Text:** "The mainstream view has been that selection has been quiescent in the last 10,000 years"
**Image:** Text snippet (WMF — likely quoting Hernandez et al. 2011 or the Coop papers)

- This is the conventional wisdom Reich is about to overturn
- Hernandez et al. 2011: classic selective sweeps were rare in recent human evolution
- Mallick et al. 2016: zero species-wide sweeps in the past 50,000 years
- Gusev's blog posts crystallized this puzzle: "Where are the selective sweeps?"
- Reich mentioned in the call that he actually used Gusev's blog post as intro to an ASHG talk

### Slide 4 — Previous ancient DNA selection studies found very little
**Text:** "Ancient DNA studies from 2015-2024 found only a handful of mutations that changed too rapidly to be due to chance"

- Despite the explosion of ancient DNA data, previous studies (Irving-Pease et al. 2024: 21 loci; Le et al. 2022: 25 loci; Mathieson & Terhorst 2022: a handful) found disappointingly few signals
- The hope was that more data → more selection signals, but it asymptoted
- This sets up the puzzle: was selection really quiescent, or were we just not looking right?

### Slide 5 — Three innovations
**Text:** Three innovations to enhance statistical power and reduce false signals:
1. **Statistical method** — No explicit modeling of demographic history. Simply ask: does a non-zero slope of selection coefficient predict allele frequency change better than population structure alone?
2. **Increased sample size 14×** — 15,836 ancient genomes (10,016 newly reported in a single study; largest previous was 793)
3. **Data quality** — Statistical imputation and rigorous quality control

- **Key methodological insight:** Previous methods tried to model demographic history (bottlenecks, migrations, admixture) and then test whether allele frequency changes exceeded demographic expectations. This is incredibly hard and error-prone. Akbari's approach sidesteps this entirely — it uses a genetic relatedness matrix (GRM) to capture population structure and simply asks if there's a residual directional trend.
- **Scale:** 15,836 individuals is ~14× larger than the biggest previous study (Irving-Pease had ~1,100; Le et al. had 1,291). 10,016 are *newly reported* — an astonishing data dump.
- **From the call:** Reich emphasized that the rigorous QC was very important. They did statistical imputation (filling in missing genotypes from low-coverage ancient DNA) and then carefully cleaned out batch effects and other artifacts.

---

## PART 2: THE BIG RESULT (Slides 6–8)

### Slide 6 — Manhattan plot: 479 signals
**Text:** "479 genome-wide significant signals of selection"
**Image:** Manhattan plot across all 22 autosomes. Selection statistic |X| on y-axis. Peaks labeled with gene names. Horizontal green line at ~5.5 marks the genome-wide significance threshold (π > 99%).

- **This is THE headline result.** Up from 279 in the bioRxiv preprint — now 479 in the accepted version.
- The labeled peaks include familiar loci (LCT, MCM6 on chr 2; SLC22A4/5 on chr 5; MHC region on chr 6; FADS1/2 on chr 11; SLC39A8, TYR, ATXN2 on chr 12; TLR1 on chr 4) plus many new ones.
- At the 50% posterior probability threshold, there are ~7,800 loci — and even more at lower thresholds.
- **From the call:** "We thought this had to be wrong when we got this result a few years ago."

### Slide 7 — Validation: multiple independent lines of evidence
**Text:** "We were incredulous about these results, but found multiple independent lines of evidence they are real"

- **This slide is crucial for the interview.** Reich was self-skeptical and spent a year during review proving these are real. The evidence:
  1. **GWAS enrichment curve** (Figure 1a in paper): As you slide the selection statistic |X| upward, the fraction of variants that are also significant in at least one UK Biobank GWAS rises from 15% (baseline) to 60-70% and plateaus. This is an independent line of evidence — modern GWAS knows nothing about ancient selection coefficients.
  2. **Simulations** (Figure 1b in paper): Simulated directional selection produces this enrichment pattern. Simulated stabilizing selection, background selection, or neutral drift do NOT.
  3. **Residual HAF/n** (Figure 1c-d in paper): Under directional selection (and ONLY directional selection), squared allele frequencies in the genomic neighborhood of a selected site increase transiently during the sweep. This independent signal also rises with |X| and plateaus — and simulations confirm only directional selection produces it.
- **From the call:** "This is extremely encouraging. We did this thing looking at changes over time and just knowing that increases the odds that it's associated to some trait — from 15% up to 60 or 70%."
- **The posterior probability calibration:** The enrichment curve is used to assign posterior probabilities. At |X| ≈ 5.5, enrichment plateaus → everything above this is ~99% likely to be real (the 479). Where enrichment is halfway between baseline and plateau → 50% probability (the ~7,800).

### Slide 8 — Period of intensified selection
**Text:** "We are in a period of intensified selection"

- Transition slide introducing the temporal analysis
- The claim: the last 10,000 years aren't just a period of some selection — they're a period of INTENSIFIED selection compared to earlier epochs
- And within this period, it intensifies further during the Bronze Age

---

## PART 3: WHAT'S UNDER SELECTION? (Slides 9–10)

### Slide 9 — Heritability enrichment by trait category
**Text:** "Meta-analysis of heritability enrichment for selection signals — Disproportionate contribution to immune and metabolic traits, not brain traits"
**Image:** Horizontal bar chart. 107 UK Biobank traits grouped into categories. Blue bars = heritability enrichment for variants with strong selection signals (π > 99%).

- **Biomarkers (9 traits):** ~5× enrichment — massive
- **Blood/immune/inflammatory (20):** ~5.7× — the strongest signal
- **Cardio/metabolic (20):** ~2× enrichment
- **Life history/reproduction (7):** ~1.9×
- **Behavioral (13):** ~1.2× — barely above baseline
- **Mental/psychiatric/nervous (13):** ~1.0× — NO enrichment at all
- **All (107):** ~2.4×

- **This is the slide that seems to say brain traits aren't under selection — but that's WRONG.** This is a critical subtlety Reich spent a lot of time explaining in the call.
- **From the call — the key explanation:** Immune traits are oligogenic (a few dozen variants with strong effects). Psychiatric/behavioral traits are extremely polygenic (thousands of variants with tiny effects). The 479 genome-wide significant loci are enriched for oligogenic traits by construction — you need a strong effect to get genome-wide significance with only 16,000 samples. The behavioral signal lives in the *weak* effects that are below this threshold.
- **Extended Data Figure 6** (the "rainbow plot" Reich discussed at length) shows this beautifully: for immune traits, enrichment goes UP as you raise the significance threshold (real signal concentrates in strong effects). For behavioral traits, enrichment goes DOWN — the signal is being *diluted* at stringent thresholds because the true signal is at weak effects.
- **Interview angle:** This apparent contradiction — no enrichment for brain traits in single-variant analysis, but huge polygenic signals for cognitive traits later — is confusing but deeply informative about genetic architecture.

### Slide 10 — Selection intensity across time periods
**Text:** Comparing intensity of selection: Mesolithic-Neolithic (>5000 BP) → Bronze Age (6000-2000 BP) → Historical Era (<3000 BP). "Selective pressure on immune and metabolic traits increased during the Bronze Age"

- **The Bronze Age intensification.** This is one of the most surprising and interview-worthy results.
- From Figure 1e in the paper: Z-scores for "selection stronger in Bronze Age than Neolithic/Mesolithic":
  - Biomarkers: 3.07
  - Blood/immune/inflammatory: **3.96** (very strong)
  - Cardio/metabolic: **3.58**
  - Life history: 2.54
  - All: **6.97** (highly significant overall)
- Z-scores for "selection stronger in Historical than Bronze Age" are all weak (0.14 to 2.10) — selection is NOT intensifying into the historical period. It **peaked in the Bronze Age**.
- **From the call:** "Most people think selection would be strongest today — urbanism, modern medicine. But no. You see this weakening of selection in the last 2,000 years. It's all in the Bronze Age."
- **Why the Bronze Age?** Reich's explanation: the Secondary Products Revolution (Sherratt). Not just farming, but intensive animal use (milk, wool, traction), massive population density increases, long-distance trade networks (copper from Cyprus, tin from Cornwall → bronze), and crucially, close contact with animals spreading disease. This is when pathogens really start hammering humans.

---

## PART 4: FLUCTUATING SELECTION (Slides 11–15)

### Slide 11 — Allele ages vs. sweep ages: fluctuating selection
**Text:** "Many favored alleles are derived alleles that originated long before the sweep" / "Selection has fluctuated over time" / "Age distribution of selected alleles solves mystery of why so few fixed differences"
**Image:** Scatter plot (Figure 2c from paper). X-axis: derived allele age from Relate (years BP). Y-axis: favored allele age given a selective sweep (years BP). Diagonal = expectation if allele arose and was immediately selected. Color: selection coefficient (blue = ancestral favored, red = derived favored).

- **This is one of the most conceptually important plots in the paper.** It explains why Coop et al. 2009 found no fixed differences between populations despite 50,000+ years of separation.
- ~2/3 of the 479 selected variants fall BELOW the diagonal — meaning the allele is much older than the sweep. The mutation arose long ago (sometimes 100,000+ years), sat around at low or moderate frequency, and was only recently swept up by selection.
- ~1/3 are red dots below the diagonal — meaning the ANCESTRAL allele (not the derived one) is being positively selected. The derived allele arose, maybe increased, but then selection reversed and favored the original.
- **Implication:** Selection is fluctuating. Alleles go up under one environmental pressure, then down under another. Over long timescales, nothing reaches fixation (100% frequency difference between populations) because the direction keeps changing.
- **From the call:** "Wait another 100,000 years, they might go down again. And therefore they won't become 100% different in frequency between Europeans and East Asians."
- **This resolves the Coop paradox:** You don't see fixed differences not because selection is weak, but because it's fluctuating.

### Slide 12 — Previously discovered signals are atypical
**Text:** "Characteristics of previously discovered selection signals are atypical"
**Image:** Figure 2b from paper. X-axis: minor allele frequency. Y-axis: selection coefficient (%). Labeled outliers: LCT (top, ~4.5%), ABO, SLC39A8, KITLG, NSF, DUOX2, MUC4, TCHH, SLC45A2, OAS1, FADS1, TYR, ATXN2, SLC22A4, TLR1, DHCR7, ADHIC, FUT3, MUC5AC, CYP1A2. Colored curves show simulation power contours (10%, 30%, 50%, 70%, 90%).

- **Key insight:** The previously known selection signals (labeled) are WEIRD. They're outliers — common variants with massive selection coefficients. LCT (lactase) is the most extreme: ~4.5% selection coefficient at moderate frequency.
- The BULK of the 479 signals (the unlabeled cloud of gray dots) follow the inverse pattern expected from GWAS: common variants have weak selection, rare variants have strong selection. This is the signature of natural selection maintaining a fitness optimum by clearing strong-effect variants.
- **From the call:** "You cannot learn about the general pattern of selection in the human genome by looking at skin pigmentation or lactase persistence or FADS1. These are completely atypical. Skin color is not a normal trait — it's a reaction to northern climates and vitamin D and sexual selection."
- **Why this matters:** For the first time, the selection data looks like GWAS data — and this means we can use selection coefficients to learn about genetic architecture of complex traits.

### Slide 13 — Selection reversal: Multiple Sclerosis / HLA-DRA
**Text:** "Selection reversal at multiple sclerosis major risk factor at HLA-DRA"
**Image:** Grid of 36 allele frequency trajectory plots for the HLA-DRA variant, broken down by geographic region. Blue curves show trajectories. Colored dots: green = hunter-gatherer, orange = farmer, purple = steppe. Shows frequency rising sharply after 6000 BP then reversing and declining.

- This is the strongest example of a selection reversal in the data
- The MS risk allele shoots up to ~15-20% frequency after 6,000 years ago (probably protecting against some pathogen), then reverses and declines ~2,000-3,000 years ago
- Previously reported as positive selection by Barrie et al. 2024 — but they only saw the upswing. With the longer time series, you see it reverse.
- **Geographic variation:** In Northern Europe, the selection coefficient is enormous (~14% — "the strongest I've ever seen," Reich said). In Southwest Europe (Spain, Italy), it's weaker but still significant, and doesn't obviously reverse.
- **From the call:** "Maybe it's protecting against some pathogen and then something else, some other pathogen comes in, and that's bad."

### Slide 14 — Two more selection reversals ~2000-3000 years ago
**Text:** "Two more selection reversals 2000-3000 years ago — More evidence of fluctuating selection likely driven by changing immune exposures"
**Images:** Two grids of trajectory plots (same format as slide 13).

- One is the risk factor for clinically significant tuberculosis — goes up (probably protecting against something), then reverses ~2,000-3,000 years ago, perhaps when TB becomes endemic
- The other is the major risk factor for hereditary hemochromatosis (iron storage disorder) — shoots up then reverses
- **2,000-3,000 years ago is a critical inflection point** — many reversals cluster here. This corresponds to the Iron Age transition, the collapse of Bronze Age civilizations, massive urbanization (Rome, Han China), and likely major shifts in the pathogen landscape.
- Previously, Kerner et al. 2021 had reported the TB variant as under negative selection — but they only saw the downsweep, missing the earlier positive selection.

### Slide 15 — Antagonistic pleiotropy
**Text:** "Examples of positively selected variants increasing disease risk: antagonistic pleiotropy"

- These are cases where selection FAVORED alleles that increase risk for diseases we know about today
- Classic evolutionary trade-off: a variant might protect against an ancient pathogen but increase risk for an autoimmune disease in a modern environment
- Two celiac disease risk variants both shoot up after 4,000 years ago — possibly because they protect against something else
- **From the call:** "You might wonder why there's selection for risk factors for celiac disease, which is gluten insensitivity in Europeans. They both shoot up after 4,000 years ago — potentially they protect against something else. We don't know."

---

## PART 5: SUMMARY OF SINGLE-VARIANT ANALYSIS (Slides 16–17)

### Slide 16 — Summary so far
**Text:** What we have learned from single variant analysis:
1. Strong directional selection has acted on hundreds of alleles in the past 10,000 years
2. Natural selection has intensified since the advent of agriculture, mostly immune-related
3. Selection has fluctuated over time

- Clean summary of the first half of the talk
- These three points are the core claims from the single-variant analysis before moving to polygenic scores

### Slide 17 — AGES website
**Text:** "Website visualizes selection information at 9.7 million variants"
**Images:** Three screenshots of the AGES (Ancient GEnome Selection) website:
1. Interactive Manhattan plot — click any variant to see its trajectory
2. Individual variant view — shows allele frequency over time with model fit, selection coefficient, posterior probability, P-values. Example shown: ATXN2 variant (rs653178) on chr 12, s = 1.77% ± 0.13%, posterior π = 1.00
3. PheWAS integration — shows Pan-UK Biobank associations for the selected variant, with scatter plots correlating selection coefficient to GWAS effect sizes

- **From the call:** "It's kind of an amazing website that Ali put together. Everybody should look at it. You get these plots for whatever variant you care about."
- Worth looking at live during the interview — could be very visual and engaging for the audience

---

## PART 6: POLYGENIC SELECTION (Slides 18–27)

### Slide 18 — Section header
**Text:** "Selection on complex traits"

- Transitions from single-variant analysis to polygenic score analysis
- This is where the behavioral/cognitive results come in

### Slide 19 — Polygenic scores explained
**Text:** Explains polygenic scores (PGS). For height: 12,111 independent associated variants from GWAS of 5.4 million Europeans (Yengo et al. 2022). PGS = sum of (effect size × genotype). Test: is change of PGS over time more than expected by chance?

- A PGS is just: for each of ~10 million variants, multiply the GWAS effect size by the individual's genotype (0, 1, or 2 copies), sum them up
- **The test for selection:** compute PGS in ancient individuals at each time point. If PGS changes more over time than expected from population structure (drift + admixture), that's evidence of selection.
- Height GWAS from Yengo et al. 2022 is the biggest ever (5.4 million people), providing very precise effect sizes

### Slide 20 — Pigmentation: the positive control
**Text:** "Example: Pigmentation — 1.8 standard deviation decrease over 10,000 years on the scale of modern variation (P = 6×10⁻⁷⁴)"
**Image:** PGS trajectory for darker skin color. Black curve = sliding window of observed PGS. Red line = fitted selection coefficient. Colored dots: green (hunter-gatherer, PGS ~2.8), orange (farmer, ~1.6), purple (steppe, ~1.7). Massive decline from ~3 to ~0 over 10,000 years.

- This is essentially a positive control — we already knew Europeans depigmented
- The magnitude is enormous: ~1.8 SD on the scale of modern variation, P = 6×10⁻⁷⁴ (the strongest signal in the entire analysis)
- **The sliding window** (black curve) shows depigmentation isn't constant — there's a period of particularly rapid depigmentation during the Bronze Age (4,000-2,000 BP)
- Green dot (hunter-gatherers) is way up at PGS ~2.8 — these were dark-skinned people living in Europe
- Orange (farmers from Anatolia) and purple (steppe pastoralists) both intermediate
- **From the call:** "This is probably because of vitamin D biology and maybe in part because of sexual selection."

### Slide 21 — Type 2 Diabetes risk: selection against
**Text:** "Selection for variants that reduce Type 2 Diabetes Risk — 0.7 to 1.0 standard deviation change over 10,000 years"
**Caution:** "Genetics pushed in opposite direction to phenotype reflecting cultural changes — Europeans certainly have higher body fat percentage today than in the past"
**Images:** Top panel: Three PGS trajectories (likely T2D, body fat %, waist circumference). All show ~1 SD decline. Bottom panel: Three sliding-window selection coefficient plots (γ) — selection is roughly constant over time (no obvious Bronze Age spike for metabolic traits).

- Selection has consistently favored variants that REDUCE diabetes risk, obesity, body fat
- But modern Europeans are fatter than ever — because environmental changes (diet, sedentary lifestyle) overwhelm the genetic trend
- **This is an important conceptual point for the interview:** genetic trends and phenotypic trends can go in opposite directions. The genetics is pushing toward leanness, but the environment is pushing harder toward obesity.
- The sliding window shows relatively constant selection over time — unlike immune traits, metabolic selection doesn't seem to spike in the Bronze Age.

### Slide 22 — Psychosis risk: selection against
**Text:** "Selection for variants that decrease risk for psychosis — 0.6 to 0.8 standard deviation change over 10,000 years"
**Caution:** "Despite genetics, schizophrenia plausibly more common today than in the past due to environmental influences"
**Images:** Top: Two PGS trajectories (bipolar disorder, schizophrenia). ~0.6-0.8 SD decline. Bottom: Sliding-window γ plots — selection relatively constant, maybe slightly weaker recently.

- Schizophrenia PGS: ~0.8 SD decline (P = 2.5×10⁻⁹ from Figure 4)
- Bipolar PGS: ~0.6 SD decline (P = 1.5×10⁻⁶)
- Again, genetic trend ≠ phenotypic trend. Modern environments (urbanization, social isolation, drugs) may increase schizophrenia rates despite the genetic trend.
- **From the call (speculative):** "Maybe it was positively selected before — schizophrenia risk, bipolar, maybe these things are related to religious originality, shamanism, being able to be unusual."
- **Important:** These are polygenic signals — recall from slide 9 that single-variant analysis shows NO enrichment for psychiatric traits. The signal only appears when you aggregate thousands of tiny effects into a PGS.

### Slide 23 — Health span: selection for
**Text:** "Selection for variants that increase health span — 0.8-0.9 standard deviation change over 10,000 years"
**Images:** Two PGS trajectories: walking pace and overall health decline. Both show ~0.8-0.9 SD improvement. Green dots (hunter-gatherers) low, meaning worse predicted health span.

- Walking pace: γ = 0.87, P = 1.1×10⁻¹¹
- Overall health decline: γ = -0.83, P = 1.3×10⁻¹⁰ (negative = improving)
- **Bronze Age spike visible** in the sliding window — particularly strong selection for health span during this period, then weakening
- **From the call:** "There is a Bronze Age or Early Bronze Age spike where there's particularly strong selection for increase in health span in this period more than today."

### Slide 24 — Cognitive performance: selection for
**Text:** "Selection for variants that affected measures of cognitive performance — 0.8-0.9 standard deviation change over 10,000 years"
**Caveat:** "No IQ tests, wealth, or school in the deep past, so what was selected is unknown"
**Images:** Top: Three PGS trajectories for IQ test score, household income, years of schooling. All show ~0.8-1.2 SD increase. Bottom: Three sliding-window γ plots.

- **This is the most provocative slide.** The numbers from Figure 4 of the paper:
  - Intelligence: γ = 0.74, P = 2.9×10⁻⁸
  - Household income: γ = 1.12, P = 3.0×10⁻²¹
  - Years of schooling: γ = 0.63, P = 8.3×10⁻⁷
- Green dots (hunter-gatherers) are ~3 SD below modern in predicted IQ/income — but this partly reflects ancestry composition (HGs are only ~10% of modern European ancestry)
- The RED line (fitted selection coefficient, correcting for ancestry) shows consistent positive selection at every time point
- **From the call:** "There's no selection for IQ — it's zero — in the last 2,000 years. It's all in the Bronze Age." The sliding window shows selection strength peaking ~4,000-2,000 BP and dropping to ~zero in the historical period.
- **Critical caveat from Reich:** "IQ tests, wealth, school — these phenotypes make no sense in prehistoric societies. What was actually being selected is unknown." Could be executive function, general health/vigor, or something else that correlates with IQ in modern environments.
- **From the call on whether intelligence was valued:** "If you read the Bible, they don't mention intelligence. They mention being God-fearing, being strong. In Greek mythology and most mythologies, intelligence is not as valued as we place on it now."

### Slide 25 — 100 of 563 GWAS traits show significant selection
**Text:** "100 of 563 Genome-Wide Association Studies correlate significantly to selection"
**Image:** Table or heatmap (WMF format) showing the 100 significant traits

- It's not just the traits shown — it's tobacco use, age at first sexual intercourse, cheese consumption, ADHD, snoring, lung capacity...
- **From the call:** "There's 100 of these. 563 traits that we tested show clear signals of selection in a polygenic sense."

### Slide 26 — East Asian replication of cognitive results
**Text:** "Trans-ancestry correlation for 31 traits... Measure GWAS effect sizes in East Asians, test if they are correlated to selective trajectories in Europe which has almost completely uncorrelated population structure"
**IMPORTANT caveat on slide:** "Years of schooling, household income, and scores on IQ tests are phenotypes that make no sense in prehistoric societies. What phenotypes were adaptive in the past is unclear."
**Additional text:** "We were especially incredulous about cognitive performance results, but they replicate in East Asians. And they replicate in a GWAS based on sibling-pairs immune to population structure."

- **This is the key replication slide.** Two independent checks:
  1. **East Asian GWAS effect sizes:** Take the selection trajectories measured in West Eurasians, but instead of using European GWAS effect sizes to build PGS, use effect sizes from Chinese GWAS. If the signal were an artifact of European population structure, it shouldn't replicate with East Asian effect sizes. But it does — 5-6 sigma for educational attainment.
  2. **Sibling-pair GWAS:** GWAS effect sizes estimated from within-family comparisons (siblings share parents, so there can be NO population structure confounding). These also replicate.
- **From the call:** "There's no way, if it's not real, that these are going to be correlated to selection trajectories in West Eurasians, who have had a completely independent history for the last 30-40,000 years from East Asians."

### Slide 27 — Interpretation is confusing
**Text:** "Interpretation confusing — What is being selected? Many genetic predictors of selected traits highly correlated: measures of adiposity, type 2 diabetes risk, health span, measures of cognition"
**Image:** Correlation matrix of polygenic selection signals across traits. Shows strong correlations: body fat % ↔ waist circumference (0.88), intelligence ↔ years of schooling (0.82), intelligence ↔ household income (0.78), health decline ↔ walking pace (0.57). Even cross-domain: years of schooling ↔ body fat % (-0.35), intelligence ↔ current smoker (-0.42). Schizophrenia and bipolar only weakly correlated with the metabolic/cognitive cluster.

- **The honest admission:** They don't really know what's being selected. The traits are all correlated. Is selection acting on "intelligence" specifically, or on some general fitness/health/executive function axis that happens to correlate with IQ in modern environments?
- Body fat, diabetes, health span, and cognition are all genetically correlated — selection on any one of these would produce signals in all of them
- **From the call:** "You really should not assume this is selection for intelligence. It could be selection for executive function, or age at which people decide to have kids."
- **Interview angle:** This is the most intellectually honest part of the talk. Press Reich on what he actually thinks is being selected.

---

## PART 7: EAST ASIAN SCAN (Slides 28–33)

### Slide 28 — East Asian dataset
**Text:** "1,861 ancient (867 newly reported) — An East/Central Asian selection scan over the last 10,000 years is much smaller but enables comparative analysis"
**Image:** Map of East/Central Asia divided into three regions (Western EAS in red, Central EAS in yellow, Southern EAS in blue). Histogram showing temporal distribution of samples — most from the last 4,000 years, with some extending to 8,000+ BP.

- Much smaller than the West Eurasian scan (1,861 vs 15,836)
- Samples scattered across a huge geographic area — less focused trajectory than the European analysis
- But still enough for comparative analysis

### Slide 29 — 40 selection signals in East Asia
**Text:** "40 independent signals of selection"
**Image:** Manhattan plot (WMF format) for the East Asian scan

- Only 40 genome-wide significant signals vs. 479 in West Eurasia — but that's expected given 10× fewer samples
- **From the call:** "We find 40 signals, not 479, because of the much smaller sample size and less focused trajectory."

### Slide 30 — Correlation of selection coefficients
**Text:** "Correlation of selection coefficients in the two scans"

- No image extracted (may be a simple correlation plot or table)
- The selection coefficients in East Asia are positively correlated with those in West Eurasia — the same variants tend to be moving in the same direction in both regions

### Slide 31 — Same functional enrichment in East Asia
**Text:** "Selection statistics are enriched in the same functional categories as for West Eurasia!"
**Image:** Side-by-side bar chart comparing heritability enrichment across trait categories for East Eurasia (purple) vs. West Eurasia (orange).

- The pattern is the same: highest enrichment for biomarkers and blood/immune/inflammatory traits, lowest for mental/psychiatric/nervous and behavioral
- East Asian scan has wider confidence intervals (fewer samples) but the qualitative pattern is strikingly similar
- This is strong evidence that the functional targets of selection are similar across Eurasia

### Slide 32 — BMI selection in both scans
**Text:** "Both scans reveal selection against variants that contribute to high body mass index" (P = 2.41×10⁻¹¹ for West Eurasia, P = 1.09×10⁻⁹ for East Asia)
**Image:** BMI PGS trajectory for East Asia (with West Eurasia for comparison). Both show decline — selection against obesity in both regions.

- Convergent selection: independently, both West and East Eurasian populations selected against high BMI over the last 10,000 years
- Both experienced agricultural transitions (though with different crops — wheat/barley in West, rice/millet in East)

### Slide 33 — Polygenic trajectories correlated across Eurasia
**Text:** "The polygenic selection trajectories seem to be correlated across Eurasia. Notable exception: Pigmentation"
**Images:**
1. Scatter plot (Pearson r = 0.63): Z(γ) in East Asia (x-axis) vs. Z(γ) in West Eurasia (y-axis) for ~452 traits. Strong positive correlation. Labeled outliers are pigmentation traits (pink squares/circles at bottom — uncorrelated or negatively correlated).
2. Additional comparison plot (WMF format)

- **r = 0.63** across hundreds of traits — a remarkably strong correlation given these populations diverged 30,000-40,000 years ago
- Nearly everything is correlated: metabolic traits, immune traits, behavioral traits — they're all moving in the same direction in both regions
- **The one exception is pigmentation.** East Asians didn't depigment over the last 10,000 years the way Europeans did. East Asian light skin arose earlier and through different variants. This makes sense — pigmentation is driven by latitude-specific vitamin D biology and sexual selection, not the agricultural/pathogen pressures driving everything else.
- **From the call:** "These groups both got exposed to similar selection pressures completely independently due to similar cultural transitions. And the genome reacted in the same way at the same positions."
- **Interview angle:** This is either convergent evolution (same pressures → same response) or residual signal from pre-split African selection being misattributed to recent periods (the Colbran et al. 2025 concern). Ask Reich about this.

---

## PART 8: ACKNOWLEDGMENTS & SEQUENCING (Slides 34–40)

### Slide 34 — Thank you
**Image:** Photo of Ali Akbari + acknowledgment of anthropologists/archaeologists

### Slides 35–39 — Ultima sequencing technology
- Real sequencing costs at the Broad Institute
- 10.4 trillion reads purchased, $175 per billion achieved reads
- Collaboration with Ultima Genomics for ancient DNA sequencing
- ~25,000 samples each sequenced for 300M reads
- Converting entire catalog of libraries with >5% endogenous DNA to Ultima shotgun
- PCA shows Ultima and Illumina data on same libraries plot in same place — data is co-analyzable
- **Now have 24,223 ancient individuals with Ultima shotgun data**
- This is the infrastructure for the next generation of studies — even more power coming

### Slide 40 — Full acknowledgments
- Lists collaborators at Harvard, Broad Institute, Ultima, MPI-EVA, Crick Institute

---

## KEY INTERVIEW ANGLES (synthesized from slides + call)

1. **The big number:** 479 → ~7,800 → thousands more. The field thought selection was quiescent. It's not. Why was everyone wrong?

2. **The Bronze Age surprise:** Selection intensifies not at the start of agriculture, not today, but during the Bronze Age. Why? (Secondary products revolution, population density, pathogen exposure, long-distance trade)

3. **The immune vs. cognitive paradox:** No enrichment for brain traits in single-variant analysis, but ~1 SD polygenic signals for cognitive performance. Not a contradiction — it's telling us something about genetic architecture (oligogenic immune traits vs. polygenic behavioral traits).

4. **Fluctuating selection:** This resolves the Coop/Hernandez puzzle of "where are the sweeps?" Alleles go up and down. Nothing reaches fixation. The genome is seething with selection, but it cancels out over long timescales.

5. **East Asian convergence:** Same selection pressures, same genomic response, completely independent populations. Is this convergent evolution from shared agricultural pressures, or pre-split selection?

6. **What is actually being selected for "intelligence"?** Reich is admirably honest: IQ tests, school, and wealth don't exist in the past. The traits are all correlated. It might be executive function, general health, or something else entirely.

7. **The Bronze Age → zero for cognition:** Selection for IQ-related traits is concentrated in the Bronze Age and drops to zero in the last 2,000 years. Why? Does civilization make intelligence less fitness-relevant?

8. **Selection ≠ phenotype:** Genetics pushed toward leanness, but people are fatter. Genetics pushed against schizophrenia risk, but schizophrenia may be more common today. The environment overwhelms the genetic trend.

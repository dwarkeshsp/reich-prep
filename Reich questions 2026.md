## Opening

* The environment for humans has changed more radically in the last 10,000 years than in any comparable period — agriculture, cities, novel diets, epidemic disease. Your lab's new preprint uses 8,433 ancient genomes to ask what impact that had on our genome. Walk me through what you found.
* Your paper reports a median selection coefficient of 0.86% across the 479 loci you identified. For the audience: what does a selection coefficient of 1% actually do to an allele over a few hundred generations? How quickly does that change things?

## Methodology

* You found 8,210 loci significant after controlling for population structure, but simulations showed a 44% false discovery rate. You used GWAS enrichment to calibrate down to 479 at >99% confidence, and project ~3,800 real signals at 50% confidence. Is the right way to understand this that thousands of loci are genuinely under selection, and 479 are just the ones you're most confident about?
* Your test asks whether a constant selection coefficient — pushing the allele the same direction across all times and places — explains frequency changes better than population structure alone. What about selection that reverses direction or acts in only one population? How much selection does this design miss?
* How big does the selection coefficient have to be before you can detect it? You report a floor of about s = 0.44%. Stabilizing selection on polygenic traits generates s ~ 0.01% per variant. Does that mean the vast majority of ongoing selection is invisible to this method?
* If a trait has been under selection but we haven't done a GWAS on it — say, something relevant to prehistoric life but not modern medicine — would you miss it entirely with your approach?
* Background selection purges deleterious mutations near functional regions, but drags along linked neutral variants — which looks like selection in your test. It also inflates GWAS associations through linkage. Doesn't this mean background selection could inflate both your selection statistics *and* GWAS enrichment, making the calibration circular?

## Replication of Prior Studies

* You tried to replicate five previous selection scans. Mathieson et al. 2015 held up well (10/11), but Le et al. was 9/22, Kerner et al. 14/125, and Field et al. sub-threshold was 3/35. Why were earlier studies finding so many false positives?
* Given that earlier studies were also confident in their results and turned out to have high false positive rates, why should we believe your 99% threshold is correctly calibrated? What makes your approach fundamentally more robust?

## Why These Traits and Not Others?

* Immune and inflammatory traits dominate your strongest signals — oligogenic, large effect sizes, easy to detect. Brain and behavioral traits show almost nothing at individual loci. But at the polygenic level, alleles associated with intelligence, income, and schooling are moving together in the same direction. What should we make of this disconnect?
* You find polygenic selection favoring alleles associated with cognitive performance — about 0.8-1 SD over 10,000 years. But these same alleles overlap heavily with anti-diabetes and body-fat variants. How do you distinguish selection *on* cognition from selection on metabolism where cognitive associations are a pleiotropic side effect?
  * You said "IQ tests, wealth, and school make no sense in prehistoric societies." So what *was* being selected? Executive function? General health and vigor? Something else?
* Lactase persistence: Mathieson & Terhorst 2022 found selection was strongest during the Bronze Age (s ~ 0.08), then weakened. But farming started thousands of years earlier, and dairy consumption goes back to ~6000 BC. Why did selection peak so late?
* Some of the largest-effect variants in the genome show zero evidence of selection: FTO (biggest effect on obesity), APOE (Alzheimer's/longevity), a menopause variant shifting timing by 5-10 years, large-effect lipid GWAS loci. Meanwhile, eye color — no obvious fitness consequence — is one of the most differentiated loci between populations. What explains this?
* Kong et al. 2017 found negative selection on educational attainment alleles in contemporary Iceland — 0.1 SD per century from 1910-1990. So selection *for* these alleles peaked in the Bronze Age and is now reversing. What's going on?

## Where Are the Sweeps?

* Coop et al. 2009 found nearly all allele frequency differences between 50+ global populations are explained by drift. Mallick et al. 2016 found zero species-wide sweeps in 50,000 years. Your paper says the genome is "seething" with selection. How do you reconcile these?
* Your own work with Bhatia (2014) found no detectable selection in African Americans over ~12 generations of slavery — divergence from an admixed Yoruba/European reference is explained by drift alone. If that extreme an environmental change left no genetic trace, what kind of pressure *is* strong enough to drive the selection you detect in ancient Eurasia?
* There seem to be two explanations for "lots of selection but no fixed differences between populations." Either selection is strong but so polygenic that each variant shifts by a tiny amount, or the direction of selection keeps reversing. Which is closer to the truth?
  * If height is influenced by 100,000 variants and selection pushes populations taller, each allele shifts by 1/100,000th of the fitness effect. Why is genetic architecture this way? Why aren't there more powerful single knobs that could respond more quickly to new selective pressures?

## How Evolution Actually Works

* As a matter of biology, why are immune traits so much less polygenic than behavioral traits? Is it that immune recognition is modular — a receptor either binds a pathogen or it doesn't — while brain function depends on billions of neurons, trillions of synapses, and dozens of interacting systems?
* Does gene flow count as selection? Your work has shown that most allele frequency change comes from migration and population replacement, not classical within-population selection. But if a gene helps one population outcompete another, isn't that selection at a different level?
* What is humanity's effective population size, and what are the consequences of it being so small? Does it mean drift is too powerful for most selection to leave a trace?
* Colbran et al. 2025 found that loci under selection in Europe are also enriched for selection in East Asia, South Asia, and the Americas — but not Africa. Either there's convergent selection on the same variants across independent environments, or this selection predates the non-African split and is being misattributed to recent periods. Which do you think it is?
* Are omnigenic/highly polygenic traits easy or hard to select for? On one hand, there are many targets for selection to act on. On the other, each variant contributes so little that drift overwhelms selection at individual loci.

## What Selection Tells Us About Human History

* When was selection strongest? Your sliding-window analysis shows selection peaking in the Bronze Age. Is this the Secondary Products Revolution — intensive dairying, wool, plough agriculture, dense settlements, long-distance trade spreading pathogens?
* You find selection for cognitive performance concentrated in the Bronze Age, dropping to zero in the last ~2,000 years. Does this mean the idea that ancient Greeks were smarter than us is wrong? Or could population mixtures since then be the main story?
* Cox et al. 2025 found Neolithic people were only modestly shorter than hunter-gatherers, and most of the difference was genetic ancestry, not diet. Does this challenge the "farming made people unhealthy" narrative?
* Mallick et al. 2016 found no loci with fixed differences between archaic and modern humans. Does this mean nothing genetically distinctive happened ~50,000 years ago — that the "human revolution" was cultural?
* Some of the alleles under strongest selection in your data are risk factors for diseases like TB and MS today. If they were positively selected for thousands of years, they must have had a large upside. Could identifying what that upside was point toward new medical interventions — getting the benefit without the disease risk?
* Can we see the Bronze Age collapse in the genetic record?
* Do you expect to find the same selection pressures when you do this analysis in East Asia, Africa, and the New World? You mentioned the East Asian scan already shows 40 loci moving in the same direction as the European ones.

## Meta / Big Picture

* TODO: Connection between selection coefficient in population genetics and pass rate in RL — effective population size ~ batch size, drift ~ noise. Is there a deep analogy here?
* TODO: Any support for DeSilva's collective intelligence hypothesis?

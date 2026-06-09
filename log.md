# Wiki Log

> Chronological record of all wiki actions. Append-only.
> Format: `## [YYYY-MM-DD] action | subject`
> Actions: ingest, update, query, lint, create, archive, delete

## [2026-06-09] create | VIP (Vasoactive Intestinal Peptide)
- New entity page: entities/vip.md
- Raw sources saved: raw/articles/vip-research-2026-06-09.md
- Research methodology: PubMed E-utilities API (22 papers retrieved and abstracted), Wikipedia mechanism/pathology overview, Examine.com (no VIP content), Reddit blocked (age gate)
- 28-aa neuropeptide, glucagon/secretin superfamily, VPAC1/VPAC2 agonist, ~2 min half-life
- Key findings: potent vasodilator (50-100× acetylcholine), SCN circadian synchronizer, immune modulator (Treg induction, cytokine suppression)
- Human trials: Phase III TESICO negative (n=471, futility stop), Phase II sarcoidosis positive (n=20, Treg increase), migraine provocateur (71% attack induction)
- Contested: COVID-19 survival signal (small trial positive, large trial negative)
- Confidence: medium. human_evidence: small-trial. safety_profile: experimental
- Contradictions noted: TESICO vs Youssef COVID-19 results
- Index updated: total pages 17→18

## [2026-06-09] nightly-batch-7 | cjc-1295-dac, thymosin-alpha-1, aod-9604
- New entity pages: entities/cjc-1295-dac.md, entities/thymosin-alpha-1.md, entities/aod-9604.md

### CJC-1295 DAC
- Long-acting GHRH analogue with covalent albumin-binding Drug Affinity Complex; half-life 6-8 days
- Phase I human PK/PD published (Teichman 2006, Ionescu 2006); GH 2-10× elevation, IGF-1 1.5-3× for 9-11 days
- Phase II terminated after subject death (NCT00267527, ConjuChem 2006) — prominent safety warning
- Comparison tables with modified-grf-1-29, tesamorelin, sermorelin
- Peer review: REQUEST_CHANGES → resolved (contradictions fixed to [tesamorelin], provenance markers added, blank lines cleaned)
- Cross-page fix applied: tesamorelin.md comparison table updated (Phase I–II for DAC, not "preclinical/anecdotal")
- Raw source: raw/articles/cjc-1295-dac-research-2026-06-09.md. Confidence: medium. human_evidence: small-trial. safety_profile: experimental

### Thymosin Alpha-1
- 28-aa thymic peptide (thymalfasin/Zadaxin, SciClone); TLR2/TLR9 agonist for immune modulation
- Approved drug in 35+ countries for hepatitis B/C; NOT FDA-approved (503A compounding restriction 2023)
- >11,000 subjects across 30+ trials; 39 RCTs for COPD, 11 RCTs for sepsis, contradictory COVID-19 meta-analyses
- Strong distinction from thymosin beta-4 (TB-500) — chemically/genetically unrelated
- Peer review: PASS (evidence-level tags added for consistency; contradictions advisory noted)
- Raw sources: raw/articles/thymosin-alpha-1-*. Confidence: medium. human_evidence: large-trial. safety_profile: clinical

### AOD-9604
- hGH fragment (177-191) developed for anti-obesity; β₃-AR upregulation mechanism in mice
- Phase IIa: 1.8 kg additional loss vs placebo (12 weeks); Phase IIb: failed, development terminated 2007
- Central to Essendon AFL doping scandal; WADA banned S0 since 2011
- Peer review: REQUEST_CHANGES → resolved (added contested/contradictions to frontmatter, removed unsupported Wayne Odesnik claim, softened "completely failed" language, renumbered references after removal)
- Raw sources: raw/articles/aod-9604-*. Confidence: low. human_evidence: small-trial. safety_profile: research-only

- Index updated: total pages now 15
- Contradictions cross-linked: cjc-1295-dac ↔ tesamorelin on evidence-level claim

## [2025-01-10] create | Wiki initialized
- Domain: Peptide-based human optimization, longevity, and age-related disease prevention
- Structure created with SCHEMA.md, index.md, log.md
- Daily multi-agent research pipeline established

## [2025-01-10] ingest | bpc-157
- Created entity page: entities/bpc-157.md
- Added raw source: raw/articles/bpc-157-research-2025-01-10.md
- Confidence: medium-low (strong animal data, anecdotal human evidence)
- Peer review: PASS after corrections (sequence fix, tags, index update)
- Key safety flag: Cancer/angiogenesis risk via VEGF upregulation

## [2026-06-08] update | bpc-157
- Major update of entity page: entities/bpc-157.md
- Added raw research source: raw/articles/bpc-157-research-2026-06-08.md
- Reviewed 32 new PubMed publications (2025-2026), Wikipedia, WADA
- Expanded from 161 to 284 lines with new sections on PK/ADME, human tissue evidence, biopharmaceutical assessment
- Frontmatter updated: tags expanded, confidence adjusted, human_evidence upgraded to small-trial, safety_profile now experimental, contested flag added
- Key new findings:
  - 3 human pilot studies now exist (IV safety n=2, IC n=12, knee OA)
  - First human tissue evidence of NO-mediated vasorelaxation (Yildirim et al. 2026)
  - Formal PK/ADME characterized (He et al. 2022): t½<30min, IM BA 14-51%
  - WADA S0 ban since 2022
  - One retracted publication noted (PMID 39865815)
  - PK/PD disconnect identified as significant unknown
  - Growing independent replication beyond Sikiric group
  - Human evidence upgraded from anecdotal to small-trial (3 pilots, <30 subjects)
  - Angiogenesis debate refined (Sikiric's context-dependent model vs. simple VEGF-promotion)


## [2026-06-08] ingest | epitalon
- New entity page: entities/epitalon.md
- Raw sources: raw/articles/epitalon-sources-2026-06-08.md
- Confidence: low (single-research-group dominance, limited independent replication)
- Safety flag: Telomerase activation ↔ cancer risk unresolved; zero long-term safety data
- Peer review: REQUEST_CHANGES → resolved (frontmatter added, wikilinks added, citation fixed, confidence normalized)

## [2026-06-08] ingest | ghk-cu
- New entity page: entities/ghk-cu.md
- Raw sources: raw/articles/ghk-cu-sources-2026-06-08.md
- Confidence: low (strong topical/cosmetic data; systemic human data absent)
- Safety flag: Wilson disease absolute contraindication; cancer/angiogenesis risk unresolved
- Peer review: REQUEST_CHANGES → resolved (frontmatter added, "475% decrease" fixed, C. elegans/zebrafish tags fixed, wikilinks added)

## [2026-06-08] update | bpc-157
- Updated entity page: entities/bpc-157.md
- New raw sources: raw/articles/bpc-157-research-2026-06-08.md
- Key additions: 3 human pilot studies (n≤12), PK/ADME data (t½ <30 min), biopharmaceutical assessment, WADA status update, retraction note
- Confidence: low (upgraded human_evidence from anecdotal → small-trial)
- Peer review: REQUEST_CHANGES → resolved (confidence normalized to low, unsupported neurotransmitter claim softened, index updated)

## [2026-06-09] ingest | semax
- New entity page: entities/semax.md
- Raw sources: raw/articles/semax-sources-2026-06-09.md
- Confidence: low (single-research-group dominance, limited Western human evidence)
- Safety flags: No FDA/EMA evaluation; μ-opioid receptor activity; online vendor purity unknown
- Key findings:
  - Russian-developed ACTH(4-10) analogue heptapeptide; approved in Russia (Vital & Essential Drugs since 2011), not FDA/EMA approved
  - 27 sources compiled including 20+ PubMed-indexed papers
  - 110-subject human post-stroke trial (Gusev 2018) showing BDNF elevation and functional recovery
  - 2 human fMRI studies (n=24, n=52) showing DMN and amygdala-temporal FC modulation
  - Extensive rat/mouse data: transcriptome-level neuroprotection in tMCAO, reduced amyloid plaques in AD model, SCI functional recovery via μ-opioid
  - New non-Russian independent research emerging (Italy: Cu chelation 2025; China: μ-opioid SCI 2025)
  - Compared to Selank, BPC-157, Epitalon

## [2026-06-09] ingest | tb-500 (Thymosin Beta-4)
- New entity page: entities/tb-500.md
- Raw sources: raw/articles/tb-500-research-2026-06-09.md
- Confidence: low (Phase 1/2 clinical data for full Tβ4, zero clinical data for TB-500 fragment)
- Human evidence: small-trial (Tβ4); none (TB-500)
- Key findings:
  - Critical Tβ4 vs. TB-500 distinction documented: full 43-aa protein (clinical trials) ≠ 7-aa fragment (gray market)
  - 18 clinical trials for Tβ4 (11 completed, 2 terminated, 2 withdrawn, 2 recruiting, 1 not yet recruiting)
  - Phase 2 positive results: dry eye, neurotrophic keratopathy, pressure ulcers, venous stasis ulcers, epidermolysis bullosa
  - Phase 1 safety established (healthy Chinese volunteers, 2021)
  - Cardiac pilot studies: STEMI cell therapy, heart failure, congenital heart surgery cardioprotection
  - TB-500: only 1 peer-reviewed paper (2012 analytical chemistry confirming structure)
  - WADA-banned (both Tβ4 and TB-500); central to Essendon AFL and Cronulla-Sutherland NRL doping scandals
  - Actin sequestration mechanism (primary intracellular role) + moonlighting extracellular functions
  - Ac-SDKP fragment (1-4) has distinct pharmacology from TB-500 fragment (17-23)
- Safety flags: Cancer/angiogenesis risk unresolved; TB-500 purity/sourcing unregulated; fragment pharmacology unknown

## [2026-06-09] ingest | mots-c
- New entity page: entities/mots-c.md
- Raw sources: raw/articles/mots-c-sources-2026-06-09.md
- Confidence: low (242 papers, robust preclinical mechanisms, zero human exogenous trials)
- Safety flags: CK2/cancer risk, SLC7A11/ferroptosis suppression, AMPK dual cancer role, zero human safety data, WADA banned 2024
- Peer review: PASS with minor fixes (editorial language softened, CK2 and ferroptosis safety bullets added)
- Key findings:
  - 242 PubMed papers (2015-2026), 4 in 2015 → 29 in first half of 2026 alone
  - Mechanism: folate-AICAR-AMPK, CK2 binding, PGC-1α, PINK1/Parkin mitophagy, THBS1/TGF-β, SLC7A11 anti-ferroptosis
  - Exercise mimetic; late-life initiated intermittent dosing extends healthspan in mice (Reynolds 2021)
  - Human evidence is purely observational/correlational (exercise biomarker, PCOS, obesity, dialysis, fertility)
  - Zero human interventional trials of exogenous MOTS-c exist

## [2026-06-09] peer-review-fixes | mots-c, tb-500, semax
- MOTS-c: softened "paradigm-shifting" editorial language; added CK2-cancer and ferroptosis safety flags
- TB-500: removed unsupported knockout study claim; removed unsupported "Smart et al. Nature" attribution; removed unsupported hair growth indication; fixed contradictions frontmatter to [bpc-157, ghk-cu]; removed Glasgow University 1999 unsupported citation
- Semax: removed invalid `small-trial` tag; elevated μ-opioid safety concern to #1; added dopaminergic/serotonergic interaction warning; expanded contraindications

## [2026-06-09] ingest | modified-grf-1-29
- New entity page: entities/modified-grf-1-29.md
- Raw sources: raw/articles/cjc-1295-wikipedia-2025-06-09.md, cjc-1295-teichman-2006.md, cjc-1295-alba-2006.md, cjc-1295-vanhout-2016.md
- Confidence: low (zero human trials for no-DAC form; Phase II DAC program terminated after subject death; only animal data)
- human_evidence: none (for no-DAC form specifically)
- Safety flags: Phase II DAC termination due to death; gray market sourcing risks; GH axis risks (insulin resistance, fluid retention, theoretical neoplasm risk)
- Key findings:
  - Critical DAC vs no-DAC distinction documented; literature falsely equates the two
  - No published human PK/PD or safety data for Modified GRF (1-29) specifically
  - Mouse model: DAC form normalizes growth in GHRH knockout mice
  - 2026 orthopaedic/sports medicine reviews unanimously classify CJC-1295/ipamorelin as investigational
  - WADA S2 prohibited

## [2026-06-09] ingest | ipamorelin
- New entity page: entities/ipamorelin.md
- Raw sources: raw/articles/ipamorelin-wikipedia-2026-06-09.md, ipamorelin-pubmed-2026-06-09.md
- Confidence: low (single discontinued Phase II trial showing no efficacy; all positive evidence is animal-only; 2026 reviews classify as investigational)
- human_evidence: small-trial (Phase II postoperative ileus, n=117, no efficacy)
- Safety flags: GH-independent adiposity in animal models; gray-market product quality issues; WADA prohibited; no long-term human safety data
- Key findings:
  - Highly selective GH secretagogue; no ACTH/cortisol or prolactin elevation even at 200× ED50
  - Phase II trial for postoperative ileus discontinued due to lack of efficacy (Beck 2014)
  - Animal data: longitudinal bone growth, counteracts glucocorticoid bone loss, body weight gain
  - Human PK established (Gobburu 1999): half-life ~2 hours, dose-proportional
  - Multiple NBA player suspensions for ipamorelin use

## [2026-06-09] ingest | tesamorelin
- New entity page: entities/tesamorelin.md
- Raw sources: raw/articles/tesamorelin-wikipedia-20260609.md, tesamorelin-pubmed-20260609.md, tesamorelin-clinicaltrials-20260609.md
- Confidence: high (FDA-approved; robust Phase 3 evidence; 2026 meta-analysis confirms)
- human_evidence: approved (HIV-associated lipodystrophy)
- Safety flags: Pregnancy Category X; active malignancy contraindication; glucose intolerance/diabetes risk; fluid retention/carpal tunnel; neoplasm risk from prolonged IGF-1 elevation
- Key findings:
  - Only FDA-approved GHRH analogue (Egrifta SV, 2010) for HIV-associated lipodystrophy
  - Phase 3: ~18% VAT reduction at 12 months; lean body mass +1.42 kg in meta-analysis
  - Effect not durable — VAT reaccumulates rapidly upon discontinuation
  - Novel immune modulation data: reduces T-cell/monocyte activation markers in HIV-associated NAFLD
  - Cognitive benefit NOT demonstrated (Ellis 2025 Phase 2 negative trial)
  - WADA prohibited (S2)

## [2026-06-09] ingest | growth-hormone-release (concept)
- New concept page: concepts/growth-hormone-release.md
- Links GHRH analogues and GH secretagogues in wiki
- Explains pulsatile vs continuous GH elevation controversy
- Created to satisfy cross-linking requirement for new entity pages

## [2026-06-09] ingest | ghrp-2, ghrp-6
- New entity pages: entities/ghrp-2.md, entities/ghrp-6.md
- Raw sources: raw/articles/ghrp-research-2026-06-09.md
- Confidence: low (both); human_evidence: small-trial (both); safety_profile: experimental (both)

### GHRP-2 (Pralmorelin)
- Synthetic hexapeptide ghrelin/GHS-R1a agonist; D-Ala-D-(β-naphthyl)-Ala-Trp-D-Phe-Lys-NH₂
- Approved in Japan as diagnostic agent (GHRP Kaken 100) for GH deficiency assessment — first GHS introduced clinically
- Phase II therapeutic development for short stature and GH deficiency discontinued (Kaken/Wyeth)
- Orally active; stimulates ACTH/cortisol in addition to GH
- Human data: diagnostic GH stimulation testing in adolescents, elderly, hypothalamic-pituitary disorder patients
- Animal data: tendon-bone healing in rat rotator cuff model (2025); general pharmacology screening showed no serious effects
- WADA S2 prohibited; detectable in DBS up to 4h post-dose
- Compared to GHRP-6, ipamorelin, CJC-1295, tesamorelin
- Key safety flags: chronic ACTH/cortisol elevation unknown; no long-term human safety data; gray-market quality unregulated

### GHRP-6
- Synthetic hexapeptide met-enkephalin analogue; His-D-Trp-Ala-Trp-D-Phe-Lys-NH₂
- No regulatory approval in any jurisdiction; Wikipedia article flagged for disputed accuracy
- Strongest appetite-stimulating GHRP; elimination half-life 2.5h; oral bioavailability <1%
- Human data: oral/IV GH stimulation studies (1992, 1993); PK study in 9 volunteers (2013); Phase I/II EGF+GHRP-6 stroke trial (2024)
- Animal data: lung protection (ARDS/fibrosis, 2026); kidney protection via mTOR-P70 (AKI hydrogel, 2025); intranasal brain ghrelin signaling (2025); body composition/metabolism in mice
- Mechanism: non-GHRH pathway; somatostatin-dependent; arcuate nucleus NPY/AgRP activation
- Atypical PK concentration spikes observed in 4/9 subjects — significance unknown
- Key safety flags: no long-term human data; chronic cortisol elevation unknown; ghrelin antagonist impairs memory in rats; gray-market stability issues (thermal degradation)
- Compared to GHRP-2, ipamorelin, CJC-1295, tesamorelin

- Index updated: total pages now 17

## [2026-06-09] nightly-batch-3 | selank, melanotan-ii, ll-37
- Selank: PASS with minor fixes ("comparable to benzodiazepines" softened; Panikratova 2020 fMRI added)
- Melanotan II: PASS with minor fixes (seized-products claim softened; Wein 2011 citation added; dosing disclaimer clarified)
- LL-37: REQUEST_CHANGES applied (skin→skin-health, wound-healing→injury-healing, contested:true, contradictions:[angiogenesis-cancer-risk], unsupported claims removed/softened, Gombart 2005 reference added)

## [2026-06-09] ingest | selank
- New entity page: entities/selank.md
- Raw sources: raw/articles/selank-wikipedia-2026-06-09.md
- Confidence: low (single-research-group dominance, no Western trials, limited independent replication)
- Safety flags: Serotonergic interaction risk; enkephalinase/opioid system interaction; no FDA/EMA review; gray-market sourcing; limited PK data; pregnancy contraindicated
- Key findings:
  - Russian-developed tuftsin analogue heptapeptide (TKPRPGP); approved in Russia/Ukraine only
  - Mechanisms: IL-6 modulation, serotonin metabolism, BDNF elevation, enkephalinase inhibition
  - Small Russian clinical trials for anxiety/neurasthenia; no Western regulatory trials
  - Panikratova 2020 fMRI (n=52) shows amygdala-temporal FC modulation distinct from Semax

## [2026-06-09] ingest | melanotan-ii
- New entity page: entities/melanotan-ii.md
- Raw sources: raw/articles/melanotan-ii-wikipedia-2026-06-09.md
- Confidence: low (no FDA/EMA approval; development abandoned; human evidence limited to early studies)
- Safety flags: Melanoma risk unresolved; cardiovascular flushing; priapism risk; nausea/GI distress; unregulated product quality; psychiatric effects unknown; pregnancy contraindicated
- Key findings:
  - Synthetic α-MSH analogue; non-selective MC1/3/4/5 agonist
  - Developed by University of Arizona; abandoned by Clinuvel due to regulatory restrictions
  - Palatin Technologies discontinued sexual-dysfunction program in 2000 (switched to bremelanotide)
  - 2020 mouse study suggested melanoma suppression (Wu 2020) but human risk remains unresolved

## [2026-06-09] ingest | ll-37
- New entity page: entities/ll-37.md
- Raw sources: raw/articles/ll-37-wikipedia-2026-06-09.md
- Confidence: low (zero interventional human trials; oncologic duality unresolved)
- Safety flags: Pro-tumorigenic/angiogenesis risk (EGFR activation demonstrated in cell culture); autoimmune/inflammatory activation; protease sensitivity; dose-dependent cytotoxicity; no human safety data; immunogenicity risk
- Key findings:
  - Only human cathelicidin; 37-AA antimicrobial peptide from CAMP gene
  - Pleiotropic: antimicrobial, chemotaxis, wound healing, angiogenesis, immune modulation
  - Oncologic duality: anti-cancer fragments (FK-16) vs. pro-tumorigenic full-length (EGFR/lung cancer)
  - Marked contested:true with contradictions:[angiogenesis-cancer-risk] to align with bpc-157 and ghk-cu

## [2026-06-09] nightly-batch-8 | bremelanotide, ghrp-2, ghrp-6, vip
- New/updated entity pages: entities/bremelanotide.md, entities/ghrp-2.md, entities/ghrp-6.md, entities/vip.md
- Raw sources: raw/articles/bremelanotide-research-2026-06-09.md, raw/articles/bremelanotide-wikipedia-2026-06-09.md, raw/articles/ghrp-research-2026-06-09.md, raw/articles/vip-research-2026-06-09.md
- Index updated: total pages now 19
- Cross-page fix applied: ipamorelin.md comparison table (GHRP-6 appetite: Mild → Moderate; GHRP-6 half-life: ~1.5 h → ~2.5 h)

### Bremelanotide (PT-141 / Vyleesi)
- FDA-approved June 2019 for HSDD in premenopausal women; first-in-class melanocortin receptor agonist
- RECONNECT trials: modest desire score improvement; SSEs not significantly improved; AE-related discontinuation 18% vs 2%
- Peer review: REQUEST_CHANGES → resolved (removed invalid `approved` tag, removed unsupported potency order claim, removed unsupported overall discontinuation rates, removed false melanotan-ii contradiction)
- Confidence: medium. human_evidence: approved. safety_profile: approved

### GHRP-2 (Pralmorelin)
- Approved in Japan as diagnostic agent only (GHRP Kaken 100); Phase II therapeutic development discontinued
- Peer review: REQUEST_CHANGES → resolved (removed unsupported dual-site mechanism claim citing Furuta 2004 safety paper, softened quantitative oral dosing claim extrapolated from GHRP-6, added contested:true + contradictions:[ipamorelin])
- Confidence: low. human_evidence: small-trial. safety_profile: experimental

### GHRP-6
- No regulatory approval; strongest appetite-stimulating GHRP; emerging tissue-protective data (lung, kidney)
- Peer review: REQUEST_CHANGES → resolved (6 unsupported PMIDs added to raw source file, softened ACTH/cortisol claim, added contested:true + contradictions:[ipamorelin])
- Confidence: low. human_evidence: small-trial. safety_profile: experimental

### VIP (Vasoactive Intestinal Peptide)
- 28-aa neuropeptide; VPAC1/VPAC2 agonist; ~2 min half-life
- Phase III TESICO negative (n=471, futility stop); Phase II sarcoidosis positive (n=20, Treg increase); migraine provocateur (71% attack induction)
- Peer review: REQUEST_CHANGES → resolved (removed 8 unsupported claims: Per1/Per2, nitric oxide/cGMP, IL-1β, PAC1 1,000-fold, 120-min mast cell, IBD p-value, surfactant, flushing; fixed dead wikilink by replacing with bpc-157 link)
- Confidence: medium. human_evidence: small-trial. safety_profile: experimental

## [2026-06-09] peer-review-fixes | batch-3
- Selank: softened "comparable to benzodiazepines"; added Panikratova 2020 fMRI finding
- Melanotan II: softened seized-products claim; added Wein 2011 citation; generalized FDA warning; added dosing-source disclaimer
- LL-37: fixed invalid tags (skin→skin-health, wound-healing→injury-healing); set contested:true and contradictions:[angiogenesis-cancer-risk]; removed unsupported Dosler 2014 and Gombart 2005 inline citations; softened psoriasis/AD quantitative claims; added Gombart 2005 to reference list; strengthened EGFR safety flag with explicit cell-culture evidence

## [2026-06-09] nightly-batch-9 | humanin, dihexa, foxo4-dri
- New entity pages: entities/humanin.md, entities/dihexa.md, entities/foxo4-dri.md
- Raw sources saved: raw/articles/humanin-wikipedia-2026-06-09.md, humanin-pubmed-2026-06-09.md, dihexa-wikipedia-2026-06-09.md, dihexa-pubmed-2026-06-09.md, foxo4-dri-pubmed-2026-06-09.md
- Index updated: total pages now 21

### Humanin
- Mitochondria-derived peptide (MDP) from MT-RNR2; 24-AA cytosolic / 20-AA mitochondrial form; most conserved MDP
- Key findings: cytoprotective via gp130/CNTFR/WSX1 receptor; anti-apoptosis via BAX/tBID/IGFBP3; SIRT3/Nrf2/HO-1 antioxidant pathway; chaperone-mediated autophagy
- Animal models: RCS rat retinal degeneration (visual acuity improvement), AngII mouse AF model (reduced inducibility), mdx mouse bone protection, C. elegans lifespan extension
- Zero human interventional trials; all human data correlational
- Peer review: REQUEST_CHANGES → resolved (20-AA sequence fix, legal-status qualified, zero-human-trials annotated, health-apps sourced, theoretical concerns flagged, comparison table note added, sources trimmed to match raw files)
- Confidence: low. human_evidence: none. safety_profile: research-only

### Dihexa
- Angiotensin IV-derived oligopeptide (PNB-0408); claimed HGF/c-Met potentiator for cognitive enhancement
- Critical finding: primary mechanistic paper (Benoist et al. 2014, J Pharmacol Exp Ther) RETRACTED in 2025 due to unreliable data
- Negative replication: Wells et al. 2024 found NO protection in 3-NP Huntington's rat model
- Independent use: hepatocyte differentiation from pluripotent stem cells (VDF cocktail with vitamin C + forskolin)
- Zero human trials; mechanism now disputed (HGF/c-Met vs IRAP)
- Peer review: REQUEST_CHANGES → resolved (opening qualified with "reportedly claimed", replication statement annotated, c-Met oncogenic risk flagged as theoretical, comparison table simplified, Semax/Selank detail removed)
- Confidence: low. contested: true. human_evidence: none. safety_profile: research-only

### FOXO4-DRI
- D-retro-inverso senolytic peptide; disrupts FOXO4-p53 interaction to selectively kill senescent cells
- Strong animal rejuvenation data: Baar et al. 2017 (Cell) aged mice; multiple independent pulmonary fibrosis replications (2022, 2023); vascular aging (2026); brain aging / AD-tauopathy review (2026)
- CRITICAL safety signal: Born et al. 2023 (Circulation) — senolytic clearance of pulmonary endothelial cells WORSENED pulmonary hypertension in multiple rodent models
- NMR structure of FOXO4-DRI / p53TAD2 solved (Bourgeois et al. 2025, Nat Commun); p53 phosphorylation enhances affinity
- Zero human interventional trials; developer is Cleara Biotech (Utrecht)
- Peer review: REQUEST_CHANGES → resolved (Baar endpoints qualified to commentary source, dosing removed, comparison table annotated, theoretical safety concerns flagged, "elegant" removed, developer attribution fixed)
- Confidence: low. contested: true. human_evidence: none. safety_profile: research-only

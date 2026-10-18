# Zoological Literature Review and Research Planning — Urban Noise, Artificial Light and Avian Acoustic Divergence

**Zoology Research Assistant Internship — Week 1** | Rabi Narayan Patra | 28 September 2026

A critical literature review of one aspect of zoology, followed by a detailed and feasible research plan for
further virtual research.

## The chosen topic

The effect of the urban sensory environment — **anthropogenic noise** and **artificial light at night** — on the
acoustic communication of birds. It was chosen because it sits at the intersection of behavioural analysis and
conservation, because it is a genuinely live scientific disagreement rather than a settled question, and because
the raw material for a serious study is already public: georeferenced recordings, satellite light data and
modelled noise layers are all openly available, so a question normally addressed one city and one species at a
time can now be addressed comparatively without a field season.

## What the review establishes

**Established.** Birds in noisier conditions sing with a higher minimum and dominant frequency — replicated
within populations, across ten European city–forest pairs, and in three independent meta-analyses. Light
pollution advances the onset of dawn song, delays its cessation, and prolongs daily vocal activity by an average
of **50 minutes** (a 2025 global analysis of more than 60 million acoustic detections across 583 species).

**Contested.** Three questions remain open, and they are the reason a further study is warranted:

1. **Adaptation, byproduct or artefact?** Transmission modelling suggests the benefit of raising pitch is small
   — about +12% active space for a 1.5 kHz signal, under 1% above 2.9 kHz — while singing louder helps
   substantially more. Others read the same numbers as evidence that the shift is adaptive.
2. **Measurement.** Of the 36 studies in the largest meta-analysis, 14 measured frequency by cursor placement on
   spectrograms — a method capable of manufacturing the effect it purports to find — and 5 did not report their
   method at all.
3. **Does it matter for survival?** A phylogenetic test across five continents found **no association** between
   song frequency and tolerance to urbanisation, which challenges the idea that singing higher is what allows
   birds to thrive in cities.

**Unknown.** Whether the pattern generalises beyond temperate songbirds and wealthy temperate cities; whether
noise and light interact rather than simply adding; and whether the fitness consequences of prolonged activity
under light pollution are negative, neutral or positive.

## The research plan

A **virtual, factorial, multi-city study** that requires no fieldwork:

- **Design** — every archived recording is assigned to one of four cells by mapped noise and light: low/low,
  high/low, low/high, high/high. The last two isolate each driver, and the high/high cell is the only one that
  can test their interaction. Cities are chosen so at least eight fall in each of three biome bands — temperate,
  tropical and arid — which turns the generality of the pattern into a question rather than an assumption.
- **Data** — Xeno-canto and Macaulay Library recordings; VIIRS satellite radiance for light (the same instrument
  as the global synthesis, so results are comparable); published traffic-noise models; land cover, occurrence
  and effort as covariates.
- **Measurement** — frequency is extracted from the **power spectrum**, not by cursor placement, so the study
  cannot generate the artefact that undermines part of the existing literature.
- **Analysis** — Bayesian phylogenetic multilevel models with species, city and recording as random effects, a
  pre-specified model set, and sensitivity analyses that are all reported whichever is more favourable.
- **Five falsifiable hypotheses**, including one (H5) framed so that the study's own preferred explanation can
  fail.

## Repository contents

```
├── README.md
├── Zoological_Literature_Review_and_Research_Plan.docx   # the report (21 pages, ~7,000 words)
├── Zoological_Literature_Review_and_Research_Plan.pdf
└── references.md                        # the 20 references, in the order cited

# In the v1.0 release bundle:
├── figures/                             # all six figures
│   ├── fig1_conceptual_framework.png    # drivers, responses, the open fitness question
│   ├── fig2_evidence_base.png           # the three systematic gaps in the literature
│   ├── fig3_controversy.png             # three competing explanations and the tests
│   ├── fig4_study_design.png            # the virtual factorial and its data sources
│   ├── fig5_pipeline.png                # the analysis pipeline
│   └── fig6_hypotheses.png              # hypotheses, predictions, falsification
└── scripts/make_figures.py              # regenerates all six figures
```

## References

Twenty references, cited by number throughout. Priority was given to meta-analyses and to studies that state
their own limitations, because a review whose subject is a contested interpretation is only as good as the
transparency of its sources. Where a claim rests on a single study it is attributed to that study rather than
stated as consensus, and where published estimates differ the disagreement is reported rather than resolved by
selection.

## Author

**Rabi Narayan Patra** — Zoology Research Assistant Intern, 2026.
GitHub: [@rabinarayanpatra350-biotech](https://github.com/rabinarayanpatra350-biotech)

---
layout: default
title: "Horizon Summary: 2026-08-01 (EN)"
date: 2026-08-01
lang: en
---

> From 55 items, 8 important content pieces were selected

---

1. [User Trains Transformer to Predict Blood Sugar Levels](#item-1) ⭐️ 8.0/10
2. [VLMs Score High on Benchmarks While Erasing Clinical Terms and Introducing Bias](#item-2) ⭐️ 8.0/10
3. [KataGo Study Reveals How Go Networks Handle Board Symmetry](#item-3) ⭐️ 8.0/10
4. [LLMs may boost paper output but lower quality, study warns](#item-4) ⭐️ 7.0/10
5. [Why Some Bubbles Pop Louder: The Physics of Fizz](#item-5) ⭐️ 5.0/10
6. [First Genomic Evidence Shows Europeans Brought Smallpox to Americas](#item-6) ⭐️ 5.0/10
7. [Nature's Books in Brief: Five Science Picks Reviewed](#item-7) ⭐️ 4.0/10
8. [Rise of Tick-Induced Meat Allergy Sparks Scientific Inquiry](#item-8) ⭐️ 4.0/10

---

<a id="item-1"></a>
## [User Trains Transformer to Predict Blood Sugar Levels](https://www.reddit.com/r/MachineLearning/comments/1vc1txc/i_have_trained_a_model_to_predict_my_blood_sugar_p/) ⭐️ 8.0/10

A Reddit user trained an encoder-only transformer to predict blood glucose levels up to 2 hours ahead using past glucose, carbs, and insulin data, with multiple model sizes and custom loss functions. The project, developed since March, is open-sourced under the MIT license. This demonstrates a practical application of transformer models to personal health monitoring, potentially inspiring similar DIY health-tech projects. It highlights the feasibility of using advanced ML techniques on small, personal datasets. The model is BERT-style with bidirectional attention, uses DILATE loss for the median and pinball loss for uncertainty bands, and operates in Kovatchev risk space. The largest model has ~17 million parameters, pretraining took ~48 hours, and finetuning under 10 minutes.

reddit · r/MachineLearning · /u/0xdeadf1sh · Jul 31, 20:09

**Background**: Encoder-only transformers, like BERT, are designed for representation learning and are commonly used in NLP tasks. DILATE loss is a differentiable loss function for time series forecasting that captures shape and temporal distortions, while pinball loss is used for quantile regression to estimate uncertainty intervals.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/BERT_(language_model)">BERT (language model) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Transformer_(deep_learning)">Transformer (deep learning) - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/1909.09020">[1909.09020] Shape and Time Distortion Loss for Training Deep Time Series Forecasting Models</a></li>
<li><a href="https://en.wikipedia.org/wiki/Quantile_regression">Quantile regression - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion likely includes feedback on the model's design, questions about data preprocessing, and suggestions for improvement, such as handling missing meal announcements. The author noted the model is 'fat-shamed' and emphasized the availability of a nano version with under 40K parameters.

**Tags**: `#machine learning`, `#transformer`, `#health`, `#time series`, `#blood glucose`

---

<a id="item-2"></a>
## [VLMs Score High on Benchmarks While Erasing Clinical Terms and Introducing Bias](https://www.reddit.com/r/MachineLearning/comments/1vcipzz/vlms_can_score_well_on_benchmarks_while_silently/) ⭐️ 8.0/10

A new paper reveals that vision-language models (VLMs) for radiology report generation can achieve high benchmark scores while silently erasing clinically meaningful terms and introducing biased terms. The authors propose a framework with two new metrics, CAD and WAE, to measure these issues. This finding is critical because conventional evaluation metrics in medical AI are misleading, potentially leading to clinically useless or harmful reports. The proposed framework could improve the reliability of VLM-based radiology report generation, benefiting patient care and clinical workflows. The paper introduces CAD (Clinical Abbreviation/term Deletion?) and WAE (Weighted Abbreviation/term Erasure?) as metrics to audit semantic erasure and emergent bias. The study demonstrates that decoding strategy and metric choice jointly confound evaluation in radiology report generation.

reddit · r/MachineLearning · /u/ade17_in · Aug 1, 09:27

**Background**: Vision-language models (VLMs) are increasingly used to generate radiology reports from images like chest X-rays. Traditional evaluation metrics such as BLEU, CIDEr, and clinical factuality measures like RadGraph F1 are commonly used, but they may reward repetitive or normal-sounding reports while missing the erasure of rare but clinically important terms. The paper addresses this gap by proposing a framework to measure these hidden issues.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2603.01625v1">Measuring What VLMs Don’t Say: Validation Metrics Hide Clinical Terminology Erasure in Radiology Report Generation</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12338887/">A Clinically-Informed Framework for Evaluating Vision-Language Models in Radiology Report Generation: Taxonomy of Errors and Risk-Aware Metric - PMC</a></li>
<li><a href="https://academic.oup.com/bjrai/article/3/1/ubag003/8445887">Recent advances in artificial intelligence for radiology report generation: a brief review | BJR|Artificial Intelligence | Oxford Academic</a></li>

</ul>
</details>

**Tags**: `#VLM`, `#evaluation metrics`, `#radiology`, `#bias`, `#medical AI`

---

<a id="item-3"></a>
## [KataGo Study Reveals How Go Networks Handle Board Symmetry](https://www.reddit.com/r/MachineLearning/comments/1vcrki2/how_symmetric_are_the_insides_of_a_go_network_r/) ⭐️ 8.0/10

A new interpretability study from the KataGo project investigates how superhuman Go-playing neural networks internally represent board symmetries, despite only using stochastic 8-fold data augmentation during training. The study, published on the KataGo GitHub page, reveals the degree to which the network learns orientation-invariant concepts versus memorizing per-orientation features. This research provides valuable insights into how neural networks generalize under symmetry constraints, which is relevant for interpretability and model design in domains with inherent symmetries. It also contributes to the broader understanding of what superhuman AI systems learn internally, potentially informing future architecture choices and training strategies. The study is based on KataGo, an open-source Go program that uses convolutional neural networks with residual blocks, trained via self-play and Monte Carlo tree search. The writeup was primarily AI-generated but with detailed human direction and feedback, and the code is linked from the post for reproducibility.

reddit · r/MachineLearning · /u/icosaplex · Aug 1, 16:18

**Background**: The rules of Go are symmetric under rotation and reflection, but KataGo's models do not enforce this symmetry; instead, they rely on stochastic 8-fold data augmentation during training, which randomly rotates and flips each batch. This study explores whether the network automatically learns orientation-invariant internal representations or if it must learn separate features for each orientation. Understanding this can shed light on how neural networks generalize from augmented data and how they represent symmetries in their latent spaces.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/KataGo">KataGo - Wikipedia</a></li>
<li><a href="https://katagotraining.org/">KataGo Distributed Training</a></li>
<li><a href="https://grokipedia.com/page/KataGo">KataGo — Grokipedia</a></li>

</ul>
</details>

**Discussion**: The Reddit community discussion is not provided in the input, but based on the post's high score and the author's engagement, the sentiment appears positive, with users likely appreciating the detailed and educational writeup. The author's transparency about AI involvement may also spark discussion about the role of AI in research communication.

**Tags**: `#machine-learning`, `#interpretability`, `#neural-networks`, `#Go`, `#symmetry`

---

<a id="item-4"></a>
## [LLMs may boost paper output but lower quality, study warns](https://www.nature.com/articles/d41586-026-02397-5) ⭐️ 7.0/10

A modelling study published in Nature predicts that combining LLM use with existing publication incentives will lead to more scientific papers but with reduced overall quality. The study highlights a trade-off between quantity and refinement in academic publishing. This finding is significant because it suggests that widespread LLM adoption could exacerbate the 'publish or perish' culture, flooding the literature with lower-quality papers. It has implications for researchers, journals, and funding bodies that rely on publication metrics for evaluation. The study models the interaction between LLM-assisted writing and academic incentives, showing that while productivity increases, the 'refinement' of papers decreases. This aligns with earlier observations that LLM-assisted manuscripts often have higher linguistic complexity but lower scientific merit.

rss · Nature - Latest Research · Jul 31, 00:00

**Background**: Large language models (LLMs) are AI systems trained on vast text data to generate human-like text, increasingly used in scientific writing. Academic publishing relies on incentives like publication count and journal prestige for career advancement, which can encourage quantity over quality. The study suggests that combining these factors may lead to a 'more but less well' scenario.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Large_language_model">Large language model - Wikipedia</a></li>
<li><a href="https://arstechnica.com/science/2025/12/llms-impact-on-science-booming-publications-stagnating-quality/">LLMs’ impact on science: Booming publications, stagnating quality - Ars Technica</a></li>
<li><a href="https://www.pnas.org/doi/10.1073/pnas.2401231121">The misalignment of incentives in academic publishing and ...</a></li>

</ul>
</details>

**Tags**: `#LLMs`, `#scientific publishing`, `#research quality`, `#AI impact`, `#academia`

---

<a id="item-5"></a>
## [Why Some Bubbles Pop Louder: The Physics of Fizz](https://www.nature.com/articles/d41586-026-02334-6) ⭐️ 5.0/10

Researchers used high-speed cameras and underwater microphones (hydrophones) to investigate why some bubbles produce louder sounds than others. Their findings, published in Nature on 31 July 2026, pinpoint the physical mechanisms that determine bubble sound volume. This research advances fundamental understanding of bubble acoustics, with potential applications in fields like sonar, underwater communication, and industrial processes involving liquids. It also offers a relatable scientific insight that could enhance public engagement with physics. The study employed high-speed imaging and hydrophones to capture bubble formation and sound emission in real time. The findings likely relate to the bubble's natural frequency and pulsation dynamics, which are key factors in acoustic emission.

rss · Nature - Latest Research · Jul 31, 00:00

**Background**: Bubbles in liquids emit sound when they form and oscillate, with the pulsation of the bubble being the primary acoustic source. Hydrophones are underwater microphones designed to match water's acoustic impedance, making them sensitive to underwater sounds. This research builds on established concepts in bubble physics and acoustics.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Hydrophone">Hydrophone - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Bubble_(physics)">Bubble (physics) - Wikipedia</a></li>
<li><a href="https://www.nature.com/articles/d41586-026-02334-6">The physics of fizz: why some bubbles are louder than others</a></li>

</ul>
</details>

**Tags**: `#physics`, `#acoustics`, `#bubbles`, `#research`

---

<a id="item-6"></a>
## [First Genomic Evidence Shows Europeans Brought Smallpox to Americas](https://www.nature.com/articles/d41586-026-02366-y) ⭐️ 5.0/10

Researchers from Trinity College Dublin have recovered and analyzed the first ancient smallpox virus genomes from the Americas, found in Chilean mummies. The genomes cluster with European lineages, providing direct molecular evidence that the disease was introduced by European colonizers. This finding settles a long-standing historical debate about the origin of smallpox in the Americas, confirming that it arrived with European contact rather than existing pre-Columbian. It underscores the devastating impact of introduced diseases on Indigenous populations and highlights the power of ancient DNA in resolving historical questions. The study, published in Science, analyzed viral sequences from Chilean mummies dating to the colonial period. The genomes show a clear phylogenetic clustering with European lineages, ruling out a pre-Columbian American variant.

rss · Nature - Latest Research · Jul 31, 00:00

**Background**: Smallpox, caused by the variola virus, was one of the deadliest diseases in human history, with a mortality rate of up to 30%. It was eradicated in 1980 after a global vaccination campaign. Historical accounts suggested that European colonizers introduced smallpox to the Americas, where it devastated Indigenous populations, but direct molecular evidence had been lacking until now.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nature.com/articles/d41586-026-02366-y">How smallpox reached the Americas: first genomic evidence ...</a></li>
<li><a href="https://phys.org/news/2026-07-ancient-smallpox-genomes-reveal-european.html">Ancient smallpox genomes reveal how European colonization ...</a></li>
<li><a href="https://www.science.org/content/article/ancient-dna-confirms-historical-accounts-how-smallpox-got-americas">Ancient DNA confirms historical accounts of how smallpox got ...</a></li>

</ul>
</details>

**Tags**: `#genomics`, `#history`, `#disease`, `#science`

---

<a id="item-7"></a>
## [Nature's Books in Brief: Five Science Picks Reviewed](https://www.nature.com/articles/d41586-026-02371-1) ⭐️ 4.0/10

Andrew Robinson reviews five notable science books in Nature's 'Books in brief' column, published online on 31 July 2026. This roundup highlights recent science literature that may influence public understanding and academic discourse, offering curated recommendations for readers interested in science. The article is part of Nature's regular 'Books in brief' feature, which typically covers a range of topics from popular science to specialized monographs. The specific titles and authors are not detailed in the provided content.

rss · Nature - Latest Research · Jul 31, 00:00

**Background**: Nature's 'Books in brief' is a recurring column that provides concise reviews of recent science books, aiming to inform readers about noteworthy publications. Such reviews help readers decide which books to explore further, covering fields like astronomy, biology, and physics.

**Tags**: `#book review`, `#science`, `#Nature`

---

<a id="item-8"></a>
## [Rise of Tick-Induced Meat Allergy Sparks Scientific Inquiry](https://www.nature.com/articles/d41586-026-02362-2) ⭐️ 4.0/10

A Nature news article published on July 31, 2026, highlights the increasing prevalence of tick-induced meat allergy, also known as alpha-gal syndrome, and outlines the unresolved scientific questions surrounding its mechanisms and epidemiology. This condition poses a growing public health concern, particularly in regions where tick exposure is common, and understanding it better could lead to improved diagnosis, treatment, and prevention strategies. The rise in cases also highlights the need for increased awareness among both medical professionals and the general public. The allergy is triggered by tick bites, which cause the immune system to produce antibodies against galactose-alpha-1,3-galactose (alpha-gal), a sugar molecule found in mammalian meat. Researchers still have many questions about why some individuals develop symptoms while others carry antibodies without symptoms, and about the geographic distribution and long-term outcomes of the condition.

rss · Nature - Latest Research · Jul 31, 00:00

**Background**: Alpha-gal syndrome is an acquired allergy to the carbohydrate molecule galactose-alpha-1,3-galactose, which is present in mammalian meat such as beef, pork, and lamb. Tick bites, particularly from the lone star tick in the United States, can sensitize individuals to this molecule, leading to allergic reactions that are often delayed by several hours after eating meat. The condition has gained attention due to its increasing prevalence and the potential for severe reactions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Alpha-gal_syndrome">Alpha - gal syndrome - Wikipedia</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC4313755/">Tick - induced allergies : mammalian meat allergy , tick anaphylaxis...</a></li>
<li><a href="https://www.usnews.com/news/health-news/articles/2026-07-22/tick-borne-meat-allergy-many-carry-alpha-gal-antibodies-without-symptoms">Tick-Borne Meat Allergy: Many Carry Alpha - Gal Antibodies Without...</a></li>

</ul>
</details>

**Tags**: `#health`, `#allergy`, `#ticks`, `#science news`

---
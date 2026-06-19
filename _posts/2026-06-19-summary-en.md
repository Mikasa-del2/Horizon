---
layout: default
title: "Horizon Summary: 2026-06-19 (EN)"
date: 2026-06-19
lang: en
---

> From 64 items, 10 important content pieces were selected

---

1. [Project Valhalla Brings Value Types to JDK 28](#item-1) ⭐️ 9.0/10
2. [10K GitHub Repos Found Distributing Trojan Malware](#item-2) ⭐️ 9.0/10
3. [Amateur May Have Cracked Linear A Using AI](#item-3) ⭐️ 8.0/10
4. [Stem cell therapy gives 15-year remission for autoimmune disease](#item-4) ⭐️ 8.0/10
5. [AI reliance degrades skills in physicians and engineers](#item-5) ⭐️ 8.0/10
6. [Brexit's damage to European science begins to heal](#item-6) ⭐️ 8.0/10
7. [Organizer cells work across distantly related animal phyla](#item-7) ⭐️ 8.0/10
8. [Brain Builds Sentences Neuron by Neuron](#item-8) ⭐️ 8.0/10
9. [AI Safety Rules Threaten Open Research After Fable 5 Takedown](#item-9) ⭐️ 8.0/10
10. [Liquid 'light in a bottle' stores energy from multiple sources](#item-10) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Project Valhalla Brings Value Types to JDK 28](https://www.jvm-weekly.com/p/project-valhalla-explained-how-a) ⭐️ 9.0/10

After a decade of development, Project Valhalla introduces value types (inline classes) in JDK 28, enabling the JVM to store objects inline without headers or pointers, resulting in dense memory layouts and improved performance. This represents a paradigm shift in Java memory management, bridging the gap between object-oriented expressiveness and low-level performance, and will benefit applications that handle large datasets or require high throughput. Value types are reference types that behave like primitives: they cannot be null and are flattened into arrays and fields. However, heap flattening does not work for objects larger than 64 bits, which may limit some use cases.

hackernews · philonoist · Jun 19, 06:35 · [Discussion](https://news.ycombinator.com/item?id=48595511)

**Background**: Project Valhalla is an OpenJDK effort to introduce value types and primitive objects to the JVM. Traditional Java objects have identity and are accessed via pointers, causing memory overhead and cache misses. Value types eliminate identity and store data inline, similar to C structs, improving cache locality and reducing garbage collection pressure.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Project_Valhalla_(Java_language)">Project Valhalla (Java language) - Wikipedia</a></li>
<li><a href="https://dev.to/adaumircosta/understanding-value-types-project-valhalla-faf">Understanding Value Types (Project Valhalla) - DEV Community</a></li>
<li><a href="https://www.infoq.com/articles/inline-classes-java/">A First Look at Java Inline Classes - InfoQ</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion is highly engaged, with 503 points and 293 comments. Some commenters express frustration that the simplified model sacrifices null-safety debate, while others defend the project's pragmatism and note that Java has evolved significantly since its early days.

**Tags**: `#Java`, `#JVM`, `#Project Valhalla`, `#performance`, `#memory management`

---

<a id="item-2"></a>
## [10K GitHub Repos Found Distributing Trojan Malware](https://orchidfiles.com/github-repositories-distributing-malware/) ⭐️ 9.0/10

A security researcher discovered over 10,000 GitHub repositories distributing Trojan malware, exploiting automated agents and search rankings to infect users. This widespread campaign poses a severe threat to software supply chain security, as automated agents (e.g., AI coding assistants) may unknowingly pull malicious dependencies, affecting developers and organizations globally. The repositories contain password-protected zip archives with Trojans, have existed for months or over a year, and GitHub has not automatically removed them. The attackers frequently delete and push new commits to stay visible in search results.

hackernews · theorchid · Jun 18, 11:45 · [Discussion](https://news.ycombinator.com/item?id=48583928)

**Background**: GitHub is a popular platform for hosting open-source code, but its open nature allows anyone to create repositories, including malicious ones. Automated agents, such as AI coding assistants or CI/CD pipelines, often search for and clone repositories to use as dependencies, making them prime targets for supply chain attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://dev.to/orchidfiles/i-discovered-a-large-scale-malware-distribution-campaign-on-github-4m6o">I discovered a large-scale malware distribution campaign on GitHub</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/over-3-000-github-accounts-used-by-malware-distribution-service/">Over 3,000 GitHub accounts used by malware distribution service</a></li>
<li><a href="https://securelist.com/webrat-distributed-via-github/118555/">Webrat, disguised as exploits, is spreading via GitHub repositories</a></li>

</ul>
</details>

**Discussion**: Community comments highlight that the attack targets automated agents rather than humans, and that attackers manipulate search rankings by frequently updating repositories. Some users report their names being attached to malicious projects they did not create, indicating identity theft.

**Tags**: `#malware`, `#supply chain security`, `#GitHub`, `#open source`, `#cybersecurity`

---

<a id="item-3"></a>
## [Amateur May Have Cracked Linear A Using AI](https://aiclambake.com/clamtakes/linear-a/) ⭐️ 8.0/10

An amateur researcher, Tom Di Mino, using Anthropic's Claude Code AI tool, claims to have deciphered over 300 words of the undeciphered Minoan script Linear A, with academic review underway at Rutgers and Cambridge. 如果得到验证，这将是线形文字A首次成功破译，该文字一个多世纪以来一直困扰着学者，可能揭示米诺斯语言和文化，重塑我们对古代爱琴文明的理解。 Di Mino used Claude Code to build Python scripts that systematically query and cross-reference the digitized Linear A corpus from GORILA and SigLA databases, enabling large-scale hypothesis testing. His approach also reportedly solves some problems in the related Linear B script.

hackernews · Kosturdistan · Jun 19, 16:04 · [Discussion](https://news.ycombinator.com/item?id=48600107)

**Background**: Linear A is a writing system used by the Minoans of Crete from 1800 to 1450 BC, and remains undeciphered since its rediscovery in 1900. It shares many glyphs with Linear B, which was deciphered in the 1950s as an early form of Greek, but the language underlying Linear A is unknown. Claude Code is Anthropic's agentic coding tool that helps developers edit code and run commands in the terminal.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Linear_A_script">Linear A script</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>
<li><a href="https://docs.anthropic.com/en/docs/claude-code/overview">Claude Code overview - Anthropic</a></li>

</ul>
</details>

**Discussion**: Community comments express cautious optimism: some note that the 'Libation Formula' used as a base is the most studied part of Linear A, while others highlight the credibility of academic review and the novelty of using AI to build tools rather than as a black-box solver. One commenter suggests that if true, it could connect Indo-European and Semitic language families.

**Tags**: `#Linear A`, `#AI`, `#decipherment`, `#Claude Code`, `#linguistics`

---

<a id="item-4"></a>
## [Stem cell therapy gives 15-year remission for autoimmune disease](https://www.nature.com/articles/d41586-026-01925-7) ⭐️ 8.0/10

Two patients with a severe autoimmune disease affecting the spinal cord and optic nerve have achieved 15-year remission after receiving stem cell therapy, as reported in Nature on June 19, 2026. This breakthrough demonstrates the potential for long-term remission in severe autoimmune diseases, offering hope for patients who have not responded to standard treatments and potentially shifting treatment paradigms. The therapy was the first of its kind for this condition, which damages the spinal cord and optic nerve, and the two patients were the first to receive it. The 15-year remission period is unprecedented for such severe autoimmune diseases.

rss · Nature - Latest Research · Jun 19, 00:00

**Background**: Autoimmune demyelinating diseases, such as neuromyelitis optica (NMO), occur when the immune system attacks the myelin sheath protecting nerve cells in the spinal cord and optic nerves. Standard treatments often focus on symptom management and preventing attacks, but long-term remission is rare. Stem cell therapy aims to reset the immune system by replacing faulty immune cells with healthy ones derived from stem cells.

<details><summary>References</summary>
<ul>
<li><a href="https://pediatricmscenter.wustl.edu/items/autoimmune-demyelinating-diseases/">Autoimmune Demyelinating Diseases | Pediatric Multiple Sclerosis...</a></li>
<li><a href="https://www.tiktok.com/discover/nmo-disease">3M posts. Discover videos related to Nmo Disease on TikTok.</a></li>

</ul>
</details>

**Tags**: `#stem cells`, `#autoimmune disease`, `#medical breakthrough`, `#therapy`

---

<a id="item-5"></a>
## [AI reliance degrades skills in physicians and engineers](https://www.nature.com/articles/d41586-026-01947-1) ⭐️ 8.0/10

Recent studies published in Nature show that reliance on AI tools degrades the skills of physicians and software engineers, with early results indicating a decline in critical thinking and problem-solving abilities. This finding raises serious concerns about long-term professional competence as AI integration accelerates in healthcare and software development, potentially impacting patient safety and code quality. The studies examined physicians using AI diagnostic tools and software engineers using AI code assistants, finding that over-reliance led to skill atrophy in both groups, though the exact metrics and sample sizes are not detailed in the summary.

rss · Nature - Latest Research · Jun 18, 00:00

**Background**: AI tools like diagnostic algorithms and code assistants are increasingly used to augment professional work, but concerns about deskilling have been debated. These studies provide empirical evidence that reliance on AI can erode foundational skills, echoing earlier warnings about automation complacency.

**Tags**: `#AI`, `#skill degradation`, `#software engineering`, `#healthcare`, `#professional skills`

---

<a id="item-6"></a>
## [Brexit's damage to European science begins to heal](https://www.nature.com/articles/d41586-026-01841-w) ⭐️ 8.0/10

A Nature article reports that the UK's share of EU research funding is recovering post-Brexit, but warns that lost collaborative networks remain difficult to rebuild. This recovery signals a potential normalization of UK-EU scientific collaboration, which is crucial for addressing global challenges like climate change and pandemics that require cross-border research. The article, published online on 18 June 2026, notes that while funding shares are climbing, the lost networks and trust built over decades will take much longer to restore.

rss · Nature - Latest Research · Jun 18, 00:00

**Background**: Brexit, the UK's withdrawal from the EU, disrupted decades of integrated research collaboration, including access to EU funding programs like Horizon Europe. The UK was a major beneficiary of EU research grants, and its departure created uncertainty and barriers for joint projects.

**Tags**: `#Brexit`, `#European science`, `#research funding`, `#UK-EU collaboration`, `#science policy`

---

<a id="item-7"></a>
## [Organizer cells work across distantly related animal phyla](https://www.nature.com/articles/d41586-026-01910-0) ⭐️ 8.0/10

Researchers have shown that embryonic 'organizer cells' from one species can instruct embryos of distantly related phyla on body plan formation, indicating a conserved mechanism across animal evolution. This finding suggests that the molecular signals controlling early body patterning are ancient and shared across the animal kingdom, offering new insights into how animals evolved from a common ancestor. The study involved transplanting organizer cells from one species into embryos of another species from a different phylum, and observing that the host embryo developed according to the donor's instructions.

rss · Nature - Latest Research · Jun 18, 00:00

**Background**: The Spemann–Mangold organizer, first described in 1924, is a group of cells in amphibian embryos that induces neural tissue and patterns the body axis. Organizer cells are known to secrete signaling molecules that influence neighboring cells to adopt specific fates. This study extends that concept across phyla, suggesting deep evolutionary conservation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Spemann-Mangold_organizer">Spemann–Mangold organizer - Wikipedia</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC8628936/">The Organizer and Its Signaling in Embryonic Development - PMC</a></li>

</ul>
</details>

**Tags**: `#developmental biology`, `#evolution`, `#cell biology`, `#embryology`

---

<a id="item-8"></a>
## [Brain Builds Sentences Neuron by Neuron](https://www.nature.com/articles/d41586-026-01967-x) ⭐️ 8.0/10

Researchers tracked the electrical activity of individual brain cells during real-time conversation, revealing how the brain constructs sentences neuron by neuron. This breakthrough offers unprecedented insights into the neural basis of language processing, potentially advancing treatments for speech disorders and brain-computer interfaces. The study, published in Nature on June 18, 2026, recorded neuronal activity during natural conversation, not just isolated words or sentences.

rss · Nature - Latest Research · Jun 18, 00:00

**Background**: Previous language studies often used fMRI or EEG, which measure large-scale brain activity. This research used microelectrode arrays to capture single-neuron resolution in real time, a technically challenging feat.

**Tags**: `#neuroscience`, `#brain activity`, `#language processing`, `#real-time recording`

---

<a id="item-9"></a>
## [AI Safety Rules Threaten Open Research After Fable 5 Takedown](https://www.science.org/content/article/researchers-caught-crossfire-companies-and-government-grapple-over-ai-safety) ⭐️ 8.0/10

The controversial takedown of the Fable 5 AI model has sparked fears among scientists that emerging AI safety regulations could stifle open research and academic freedom. This tension between companies, government, and researchers could reshape how AI safety research is conducted, potentially limiting transparency and collaboration in the field. Fable 5 is Anthropic's most intelligent model, state-of-the-art on nearly all benchmarks, yet its removal has raised questions about regulatory overreach and the balance between safety and openness.

rss · Science Magazine - News · Jun 19, 11:00

**Background**: AI safety research aims to ensure AI systems are robust, aligned, and safe. Recent regulatory efforts, such as the UK's push to become a global hub for AI safety regulation, have intensified debates over how to govern powerful models without hindering open science.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_safety">AI safety - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#open research`, `#regulation`, `#policy`, `#academic freedom`

---

<a id="item-10"></a>
## [Liquid 'light in a bottle' stores energy from multiple sources](https://www.science.org/content/article/light-bottle-liquid-can-harvest-and-store-energy-multiple-sources) ⭐️ 7.0/10

Scientists at UC Santa Barbara have created a liquid substance that can harvest and store energy from multiple sources, such as sunlight, and release it later as heat, functioning like a rechargeable battery. This breakthrough could lead to energy-rich gel-powered devices, offering a novel approach to sustainable energy storage that is flexible, nontoxic, and suitable for applications like medical devices and soft robotics. The material uses a molecule with a pyrimidone structure, similar to a DNA component, that undergoes reversible structural changes when exposed to UV light, enabling repeated charging and discharging.

rss · Science Magazine - News · Jun 19, 08:00

**Background**: Traditional energy storage often relies on rigid, toxic batteries. This new liquid material is inspired by natural processes, such as the reversible changes in DNA under UV light, and can store energy in a gel form that is flexible and safe for biological tissues.

<details><summary>References</summary>
<ul>
<li><a href="https://www.science.org/content/article/light-bottle-liquid-can-harvest-and-store-energy-multiple-sources">‘Light in a bottle’ liquid can harvest and store energy from multiple sources | Science | AAAS</a></li>
<li><a href="https://www.universityofcalifornia.edu/news/scientists-bottle-sun-liquid-battery">Scientists bottle the sun with liquid battery | University of California</a></li>
<li><a href="https://www.sciencedaily.com/releases/2026/05/260513221821.htm">Scientists “bottle the sun” with a liquid battery that stores solar energy | ScienceDaily</a></li>

</ul>
</details>

**Tags**: `#energy storage`, `#materials science`, `#sustainable energy`, `#breakthrough`

---
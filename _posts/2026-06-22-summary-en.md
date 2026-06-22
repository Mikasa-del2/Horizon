---
layout: default
title: "Horizon Summary: 2026-06-22 (EN)"
date: 2026-06-22
lang: en
---

> From 48 items, 10 important content pieces were selected

---

1. [Steam Machine Launches Today](#item-1) ⭐️ 9.0/10
2. [Stereoretentive Decarbonylative C(sp3)-C(sp3) Cross-Coupling](#item-2) ⭐️ 9.0/10
3. [First Ticking Nuclear Clocks Achieved](#item-3) ⭐️ 9.0/10
4. [Codex logging bug may write TBs to local SSDs](#item-4) ⭐️ 8.0/10
5. [Mitchell Hashimoto Pledges $400k to Zig Software Foundation](#item-5) ⭐️ 8.0/10
6. [New radical cross-coupling method for C-glycoside synthesis](#item-6) ⭐️ 8.0/10
7. [Isotopic evidence reveals cold, distant origin of 3I/ATLAS](#item-7) ⭐️ 8.0/10
8. [Will AI Spark a Scientific Renaissance or Monoculture?](#item-8) ⭐️ 8.0/10
9. [40 Years of High-Temperature Superconductivity](#item-9) ⭐️ 8.0/10
10. [Study People in Real Life to Boost Science Reliability](#item-10) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Steam Machine Launches Today](https://store.steampowered.com/news/group/45479024/view/685257114654870245) ⭐️ 9.0/10

Valve officially launched the Steam Machine, a Linux-based gaming PC, with reservations opening on June 25, 2026, using a randomized reservation system to ensure fairness. This launch marks Valve's entry into the console-like gaming PC market, emphasizing open hardware and user freedom, which could challenge traditional consoles and promote Linux gaming. The Steam Machine starts at £879 / $1049, with higher-end configurations up to £1208 / $1428. It runs SteamOS and allows users to install other operating systems or apps.

hackernews · theschwa · Jun 22, 17:09 · [Discussion](https://news.ycombinator.com/item?id=48632884)

**Background**: Steam Machine is a compact gaming PC designed by Valve to bring PC gaming to the living room. It runs on SteamOS, a Linux-based operating system, and is part of Valve's broader hardware ecosystem including the Steam Controller and Steam VR. The randomized reservation system was introduced to combat bots and scalpers, following a troubled launch of the Steam Controller earlier in 2026.

<details><summary>References</summary>
<ul>
<li><a href="https://www.polygon.com/valve-steam-machine-price-pre-order/">Valve confirms Steam Machine price and pre-orders</a></li>
<li><a href="https://www.rockpapershotgun.com/steam-machine-prices-start-at-879-1049-valve-confirm-as-randomised-reservations-open-for-the-steamos-pc">Steam Machine prices start at £879 / $1049, Valve confirm, as ...</a></li>
<li><a href="https://www.pcmag.com/news/valve-to-restart-steam-controller-orders-on-friday-with-a-reservation-system">Valve to Restart Steam Controller Orders on Friday With a ...</a></li>

</ul>
</details>

**Discussion**: The community is largely positive, praising the open hardware philosophy and the fair reservation system. Some users express interest in supporting Linux gaming, while others humorously note the authentic gameplay footage in the announcement.

**Tags**: `#gaming`, `#hardware`, `#Valve`, `#Steam`, `#PC gaming`

---

<a id="item-2"></a>
## [Stereoretentive Decarbonylative C(sp3)-C(sp3) Cross-Coupling](https://www.nature.com/articles/s41586-026-10800-4) ⭐️ 9.0/10

A new catalytic method for stereoretentive decarbonylative C(sp3)-C(sp3) cross-coupling has been reported in Nature, enabling the formation of chiral carbon-carbon bonds from readily available amino-acid and α-hydroxy-acid derivatives. This breakthrough addresses a long-standing challenge in organic synthesis: stereocontrolled C(sp3)-C(sp3) bond formation, which is crucial for drug discovery where molecules with increased sp3 character are in high demand. The reaction proceeds via a stereoretentive decarbonylation step, inspired by the classic Curtius rearrangement, to form a chiral alkylnickel intermediate. It uses easily available chiral carboxylic acid derivatives as substrates.

rss · Nature - Latest Research · Jun 22, 00:00

**Background**: Cross-coupling reactions are powerful tools for forming carbon-carbon bonds, but stereocontrolled C(sp3)-C(sp3) coupling has been difficult. Traditional methods often require specialized substrates or produce racemic mixtures. Decarbonylative cross-coupling, which removes carbon monoxide from a carbonyl group, offers an alternative route using abundant carboxylic acids.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41586-026-10800-4">Stereoretentive decarbonylative C(sp3)-C(sp3) cross-coupling | Nature</a></li>
<li><a href="https://en.wikipedia.org/wiki/Decarboxylative_cross-coupling">Decarboxylative cross-coupling</a></li>

</ul>
</details>

**Tags**: `#organic chemistry`, `#cross-coupling`, `#synthesis`, `#catalysis`, `#stereochemistry`

---

<a id="item-3"></a>
## [First Ticking Nuclear Clocks Achieved](https://www.nature.com/articles/d41586-026-01909-7) ⭐️ 9.0/10

Two research teams have independently built the first operational nuclear clocks, using laser excitation of thorium-229 nuclei to achieve timekeeping that could surpass atomic clocks. Nuclear clocks promise up to 100 times greater accuracy than today's best atomic clocks, potentially revolutionizing GPS, fundamental physics experiments, and tests of fundamental constants. The clocks rely on the low-energy nuclear transition in thorium-229, which can be excited by ultraviolet laser light, making it uniquely accessible for precision timekeeping.

rss · Nature - Latest Research · Jun 22, 00:00

**Background**: Atomic clocks use electron transitions in atoms to measure time, but they are susceptible to external fields. Nuclear clocks use transitions within the atomic nucleus, which is far less sensitive to such disturbances, offering potentially superior stability and accuracy.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nuclear_clock">Nuclear clock - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Atomic_clock">Atomic clock - Wikipedia</a></li>
<li><a href="https://www.online-sciences.com/technology/nuclear-clocks-features-advantages-disadvantages-atomic-clock-vs-nuclear-clock/">Nuclear clocks features, advantages, disadvantages, Atomic ...</a></li>

</ul>
</details>

**Tags**: `#physics`, `#timekeeping`, `#nuclear clock`, `#breakthrough`, `#quantum`

---

<a id="item-4"></a>
## [Codex logging bug may write TBs to local SSDs](https://github.com/openai/codex/issues/28224) ⭐️ 8.0/10

A logging bug in OpenAI's Codex CLI can write up to 640 TB of data per year to a local SQLite database, causing excessive SSD wear and high GPU usage. A fix has been committed but not yet released. This bug could significantly shorten SSD lifespan and degrade system performance for developers using Codex, a widely-used AI coding tool. The issue highlights potential quality gaps in AI tooling that can have real hardware consequences. The bug is caused by a misconfigured logging sink that writes excessive logs to ~/.codex/logs_2.sqlite. A temporary workaround involves creating a SQLite trigger to block log inserts, and running VACUUM FULL can shrink the database from 27 GB to 73 MB.

hackernews · vantareed · Jun 22, 07:30 · [Discussion](https://news.ycombinator.com/item?id=48626930)

**Background**: Codex is OpenAI's AI-powered coding assistant that runs locally via CLI. It uses SQLite for logging, and a bug in the logging configuration causes it to write massive amounts of data. SSD endurance is typically measured in total bytes written (TBW), and consumer SSDs often have a TBW of 150-600 TB, meaning this bug could wear out a drive in under a year.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reddit.com/r/OpenAI/comments/1ucf4px/openai_codex_has_a_bug_that_could_kill_your_ssd/">r/OpenAI on Reddit: OpenAI Codex has a bug that could kill your SSD in under a year</a></li>
<li><a href="https://github.com/openai/codex/issues/16857">High GPU usage while the app is "thinking" due to tiny ... - GitHub</a></li>
<li><a href="https://smartscope.blog/en/generative-ai/chatgpt/codex-cli-diagnostic-logs-deep-dive/">Codex CLI Logs: Location, Debug Flags & 401 Error Fix (2026) - SmartScope</a></li>

</ul>
</details>

**Discussion**: The community is highly critical of OpenAI for the bug, with some calling Codex 'slopware' and noting that even the spinner animation causes 100% GPU usage on high-end MacBooks. Others have shared workarounds and noted that a fix has been committed, but frustration remains over the slow response from OpenAI.

**Tags**: `#OpenAI`, `#Codex`, `#bug`, `#SSD`, `#logging`

---

<a id="item-5"></a>
## [Mitchell Hashimoto Pledges $400k to Zig Software Foundation](https://mitchellh.com/writing/zig-donation-2026) ⭐️ 8.0/10

Mitchell Hashimoto, creator of the Ghostty terminal, has pledged an additional $400,000 to the Zig Software Foundation to support the development of the Zig programming language. This significant donation highlights the growing ecosystem around Zig and underscores the importance of sustainable funding for open-source language development, potentially inspiring more contributions from the community. The pledge is for the year 2026 and follows a previous $400,000 donation, bringing Hashimoto's total commitment to $800,000. The funds will support the Zig Software Foundation's operations and language development.

hackernews · tosh · Jun 22, 13:43 · [Discussion](https://news.ycombinator.com/item?id=48630020)

**Background**: Zig is a general-purpose systems programming language designed as a modern alternative to C, emphasizing safety, performance, and simplicity. The Zig Software Foundation (ZSF) is a non-profit that oversees the language's development and is funded through donations and sponsorships.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language) - Wikipedia</a></li>
<li><a href="https://ziglang.org/zsf/">Zig Software Foundation Zig Programming Language</a></li>
<li><a href="https://ziglang.org/?ref=workingsoftware.dev">Home Zig Programming Language</a></li>

</ul>
</details>

**Discussion**: Community members praised the donation, with some noting that Hashimoto's Ghostty terminal has brought significant utility to the ecosystem. Others discussed Zig's stance against LLM contributions, arguing that careful language design requires human oversight.

**Tags**: `#Zig`, `#open-source`, `#funding`, `#programming-languages`, `#community`

---

<a id="item-6"></a>
## [New radical cross-coupling method for C-glycoside synthesis](https://www.nature.com/articles/s41586-026-10807-x) ⭐️ 8.0/10

Researchers have developed a novel radical cross-coupling method using glycohydrazides to efficiently synthesize C-glycosides, as published in Nature on June 22, 2026. C-glycosides are important in medicinal chemistry due to their metabolic stability, and this new method offers a more efficient and versatile route for their synthesis, potentially accelerating drug discovery. The method employs glycohydrazides as radical precursors in a cross-coupling reaction, enabling the formation of C–C bonds at the anomeric position with broad substrate scope and good stereoselectivity.

rss · Nature - Latest Research · Jun 22, 00:00

**Background**: C-glycosides are carbohydrate analogs where the oxygen atom in the glycosidic bond is replaced by a carbon atom, making them resistant to enzymatic hydrolysis. Traditional synthesis methods often require multiple steps and harsh conditions. Radical cross-coupling has emerged as a powerful tool for C–C bond formation, but its application to carbohydrate chemistry has been limited.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41586-026-10807-x">C-glycoside synthesis via radical cross-coupling of ... - Nature</a></li>
<li><a href="https://baranlab.org/glycohydrazides-in-action/">Glycohydrazides in action | Baran Lab</a></li>
<li><a href="https://magazine.scripps.edu/features/2026/spring/cross-coupling-radically-simplified/">Cross - coupling , radically simplified - Scripps Research Magazine</a></li>

</ul>
</details>

**Tags**: `#organic chemistry`, `#radical cross-coupling`, `#C-glycosides`, `#carbohydrate chemistry`, `#drug discovery`

---

<a id="item-7"></a>
## [Isotopic evidence reveals cold, distant origin of 3I/ATLAS](https://www.nature.com/articles/s41586-026-10771-6) ⭐️ 8.0/10

A study published in Nature on June 22, 2026, provides isotopic evidence that interstellar object 3I/ATLAS originated from a cold, distant region, likely beyond the Solar System's influence. This finding offers unprecedented insights into the formation conditions of interstellar objects, helping astronomers understand the composition and history of material from other star systems. The isotopic analysis focused on ratios of elements such as carbon and nitrogen, which indicate formation at extremely low temperatures, consistent with a molecular cloud or protoplanetary disk environment.

rss · Nature - Latest Research · Jun 22, 00:00

**Background**: 3I/ATLAS is the third confirmed interstellar object detected in our Solar System, after 1I/'Oumuamua and 2I/Borisov. It is an active comet with a solid nucleus and a coma. Isotopic analysis measures the abundance of stable isotopes to trace an object's origin and formation conditions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/3I/ATLAS">3I/ATLAS - Wikipedia</a></li>
<li><a href="https://science.nasa.gov/solar-system/comets/3i-atlas/">Comet 3I/ATLAS - Science@NASA</a></li>
<li><a href="https://en.wikipedia.org/wiki/Isotope_analysis">Isotope analysis - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#astronomy`, `#planetary science`, `#interstellar object`, `#isotopic analysis`

---

<a id="item-8"></a>
## [Will AI Spark a Scientific Renaissance or Monoculture?](https://www.nature.com/articles/d41586-026-01954-2) ⭐️ 8.0/10

A Nature commentary argues that AI's impact on science depends on whether the research ecosystem rewards originality over speed. This matters because AI could either accelerate scientific breakthroughs or homogenize research, affecting how knowledge is produced and funded globally. The article was published online on 22 June 2026 in Nature, with doi:10.1038/d41586-026-01954-2.

rss · Nature - Latest Research · Jun 22, 00:00

**Background**: AI tools like large language models are increasingly used in scientific research for literature review, hypothesis generation, and data analysis. However, there is concern that reliance on AI may favor incremental, high-speed outputs over novel, risky ideas, potentially leading to a 'diffuse monoculture' in science.

**Tags**: `#AI`, `#scientific research`, `#research culture`, `#originality`, `#policy`

---

<a id="item-9"></a>
## [40 Years of High-Temperature Superconductivity](https://www.nature.com/articles/d41586-026-01801-4) ⭐️ 8.0/10

A Nature article commemorates the 40th anniversary of the discovery of high-temperature superconductivity at 35 K, highlighting its profound impact on materials research and the enduring mystery of the phenomenon. This milestone reshaped condensed matter physics and materials science, enabling applications like liquid-nitrogen-cooled magnets and power cables, while the mechanism remains a central puzzle driving ongoing research. The first high-temperature superconductor, a cuprate ceramic, was discovered by Bednorz and Müller in 1986, with a critical temperature of 35 K, later modified to exceed 77 K (liquid nitrogen boiling point).

rss · Nature - Latest Research · Jun 22, 00:00

**Background**: Superconductivity is a state where a material conducts electricity with zero resistance below a critical temperature. Before 1986, known superconductors required extreme cooling with liquid helium; high-temperature superconductors can be cooled with cheaper liquid nitrogen, enabling broader practical use.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/High-temperature_superconductivity">High-temperature superconductivity</a></li>
<li><a href="https://www.nature.com/articles/d41586-026-01801-4">Forty years of high-temperature superconductivity</a></li>

</ul>
</details>

**Tags**: `#superconductivity`, `#condensed matter physics`, `#materials science`, `#Nature`, `#scientific milestone`

---

<a id="item-10"></a>
## [Study People in Real Life to Boost Science Reliability](https://www.nature.com/articles/d41586-026-01957-z) ⭐️ 8.0/10

In a Nature article, economist John A. List proposes studying people in their natural, real-life contexts to address the generalizability crisis in behavioral sciences, complementing ongoing efforts to solve the replication crisis. This proposal tackles a fundamental flaw in behavioral research: findings from artificial lab settings may not apply to real-world populations and situations, undermining the reliability and usefulness of science for policy and practice. The article was published online on June 22, 2026, in Nature (doi:10.1038/d41586-026-01957-z). List argues that the generalizability crisis is distinct from the replication crisis and requires new methodological approaches, such as field experiments and naturalistic observation.

rss · Nature - Latest Research · Jun 22, 00:00

**Background**: The replication crisis refers to the widespread failure to reproduce published scientific results, undermining trust in research. The generalizability crisis, a related but distinct issue, concerns whether findings from controlled studies apply to diverse real-world settings and populations. Behavioral sciences have been particularly affected by both crises.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Replication_crisis">Replication crisis - Wikipedia</a></li>
<li><a href="https://psycnet.apa.org/record/2022-32364-001">The generalizability crisis. - APA PsycNet</a></li>

</ul>
</details>

**Tags**: `#research methodology`, `#behavioral science`, `#replication crisis`, `#generalizability`, `#science policy`

---
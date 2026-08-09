---
layout: default
title: "Horizon Summary: 2026-08-09 (EN)"
date: 2026-08-09
lang: en
---

> From 41 items, 4 important content pieces were selected

---

1. [AI Designs First Viable Bacteriophage Genomes with Evo Models](#item-1) ⭐️ 9.0/10
2. [Os8088: Mac-like OS for IBM XT in 8086 Assembly](#item-2) ⭐️ 8.0/10
3. [Shopify Replaces Redis with MySQL for Inventory Reservations, Scales Efficiently](#item-3) ⭐️ 8.0/10
4. [Senate Blocks White House Research Control Rule](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [AI Designs First Viable Bacteriophage Genomes with Evo Models](https://www.reddit.com/r/MachineLearning/comments/1vjj4pr/r_generative_design_of_novel_bacteriophages_with/) ⭐️ 9.0/10

Researchers used the genome language models Evo 1 and Evo 2 to generate whole-genome sequences of bacteriophages, and experimentally validated 16 of them as viable phages with novel genetic architectures. This marks the first generative design of viable bacteriophage genomes. This breakthrough demonstrates that genome language models can generate functional sequences at the scale of whole genomes, opening new avenues for synthetic biology and AI-driven biological design. It could accelerate the development of custom phages for applications like phage therapy and biotechnology. The researchers used the lytic phage ΦX174 as a design template and generated genomes with realistic genetic architectures and desirable host tropism. The 16 viable phages exhibited substantial evolutionary novelty, with no natural counterparts.

reddit · r/MachineLearning · /u/moschles · Aug 9, 07:11

**Background**: Genome language models (gLMs) are large language models trained on DNA sequences, treating genomes as biological texts to learn their grammar and regulatory interactions. Evo 1 and Evo 2 are frontier gLMs; Evo 2, for instance, has 40 billion parameters and a 1-megabase context length, trained on the OpenGenome2 dataset. Bacteriophages are viruses that infect bacteria, and their genomes can be highly mosaic, making them a challenging but promising target for generative design.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41586-026-10176-5">Genome modelling and design across all domains of life with Evo 2</a></li>
<li><a href="https://arcinstitute.org/tools/evo">Evo 2: DNA Foundation Model - Arc Institute</a></li>
<li><a href="https://en.wikipedia.org/wiki/Bacteriophage">Bacteriophage - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion likely includes expert commentary on the significance of the results, with some users debating the novelty and practical implications of AI-designed phages. Others may raise concerns about the limitations of the approach, such as the reliance on a single template or the need for further validation.

**Tags**: `#AI`, `#genome language models`, `#synthetic biology`, `#bacteriophage`, `#research`

---

<a id="item-2"></a>
## [Os8088: Mac-like OS for IBM XT in 8086 Assembly](https://os8088.com/) ⭐️ 8.0/10

Os8088 is a graphical operating system for the IBM XT, 286, and 386, hand-written entirely in real-mode 8086 assembly with no C, linker, or runtime library. It features a Mac-like desktop, FAT12/16 support, ported apps, games, Sound Blaster support, and has been verified to run on real hardware. This project demonstrates the remarkable capabilities of early PC hardware when programmed in low-level assembly, reviving interest in retrocomputing. It also sparks debate about the role of AI-assisted coding in modern software development, as the OS was reportedly written with the help of Claude. The OS runs in real mode, which uses 16-bit addressing and limits memory access to 1 MB, typical for the era. It supports FAT12 and FAT16 file systems, which were standard for DOS and early Windows, and includes a preemptive multitasking environment with a System 1/2/3-like interface.

hackernews · jggonz · Aug 8, 23:37 · [Discussion](https://news.ycombinator.com/item?id=49226923)

**Background**: Real mode is an operating mode of all x86-compatible CPUs where addresses correspond directly to physical memory, limiting access to 1 MB. The FAT file system, developed in 1977, was the default for DOS and Windows 9x, with FAT12 and FAT16 variants using 12-bit and 16-bit cluster entries respectively. This project revives the era of early graphical OSes like Visi On, which was a commercial but unsuccessful graphical OS for the IBM PC.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Real_mode">Real mode - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/FAT12_file_system">FAT12 file system</a></li>
<li><a href="https://en.wikipedia.org/wiki/File_Allocation_Table">File Allocation Table - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion highlights historical context, with users mentioning Visi On as a predecessor. There is a humorous observation about the irony of HN users using AI to code while dismissing AI-written software, and a comment noting the 'cursed' combination of a Minesweeper game with a bootleg System 1/2/3 interface.

**Tags**: `#retrocomputing`, `#operating systems`, `#assembly`, `#IBM PC`, `#AI-assisted development`

---

<a id="item-3"></a>
## [Shopify Replaces Redis with MySQL for Inventory Reservations, Scales Efficiently](https://shopify.engineering/scaling-inventory-reservations) ⭐️ 8.0/10

Shopify engineers published a post detailing how they replaced Redis with a MySQL-based solution for inventory reservations, using bounded pools of rows to scale efficiently. The approach involves one row per sellable unit, capped at 1,000 rows per item/location combination, with a replenishment process. This engineering decision from a major e-commerce platform demonstrates a novel alternative to Redis for high-concurrency inventory operations, potentially influencing how other companies design scalable systems. It highlights the trade-offs between using specialized caching layers and relational databases for critical transactional workloads. The solution uses a bounded pool of available rows, capped at 1,000 per item/location combination, to avoid performance degradation from scanning large numbers of rows. Reservations consume rows from this pool, and a replenishment process refills it, ensuring atomicity and durability without relying on Redis.

hackernews · adletbalzhanov · Aug 8, 22:32 · [Discussion](https://news.ycombinator.com/item?id=49226536)

**Background**: Inventory reservation systems must handle concurrent decrements of stock counts without overselling. Traditionally, Redis is used for its speed, but it lacks durability and atomicity for such operations. MySQL, as a relational database, offers ACID transactions but may face scalability challenges with a single row per item. Shopify's approach uses multiple rows to distribute the load while maintaining consistency.

<details><summary>References</summary>
<ul>
<li><a href="https://www.systemdesignhandbook.com/guides/design-inventory-management-system/">Design Inventory Management System: (Step-by-Step Guide) 2026</a></li>
<li><a href="https://bytebytego.com/courses/system-design-interview/hotel-reservation-system">System Design · Coding · Behavioral · Machine Learning Interviews</a></li>
<li><a href="https://www.educative.io/blog/inventory-management-system-design">Inventory Management System Design</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some criticize the post as likely LLM-written, while others question the need for such hacks, noting that in 2026 we still lack a scalable way to decrement a single number. There are also complaints about the dark theme causing headaches and unrelated annoyance with Shopify's delivery tracking app.

**Tags**: `#MySQL`, `#Redis`, `#scaling`, `#inventory`, `#engineering`

---

<a id="item-4"></a>
## [Senate Blocks White House Research Control Rule](https://www.science.org/content/article/senate-votes-block-rule-giving-white-house-more-control-over-research) ⭐️ 7.0/10

The US Senate voted to block a rule that would have given the White House more control over research, as part of a government funding bill. The measure is included in a bill to fund the government until mid-December. This decision preserves the autonomy of federal research agencies and the scientific community, preventing potential political interference in research priorities. It signals ongoing congressional oversight over executive branch actions affecting science policy. The rule in question would have expanded White House oversight of research and development activities across federal agencies. The Senate's action is part of a continuing resolution to fund the government, reflecting a bipartisan effort to check executive power.

rss · Science Magazine - News · Aug 8, 12:30

**Background**: In the US, federal research agencies like the National Institutes of Health and the National Science Foundation operate with a degree of independence, guided by peer review and scientific merit. The White House Office of Science and Technology Policy typically coordinates research policy, but this rule would have increased direct control. Congressional opposition often arises from concerns about politicizing science and undermining agency expertise.

**Tags**: `#science policy`, `#research funding`, `#government`, `#US politics`, `#research governance`

---
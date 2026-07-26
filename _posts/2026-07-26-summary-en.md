---
layout: default
title: "Horizon Summary: 2026-07-26 (EN)"
date: 2026-07-26
lang: en
---

> From 48 items, 3 important content pieces were selected

---

1. [Ruff v0.16.0 Expands Default Lint Rules from 59 to 413](#item-1) ⭐️ 8.0/10
2. [GrapheneOS Protections Against Data Extraction from Locked Devices](#item-2) ⭐️ 8.0/10
3. [DeepSeek pauses fundraising after leaked transcript on compute gap](#item-3) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Ruff v0.16.0 Expands Default Lint Rules from 59 to 413](https://astral.sh/blog/ruff-v0.16.0) ⭐️ 8.0/10

Astral released Ruff v0.16.0 on July 23rd, which increases the number of default lint rules from 59 to 413, significantly expanding code quality detection out of the box. This update makes Ruff a more comprehensive linter for Python, reducing the need for additional plugins and helping developers catch more issues with zero configuration. It also signals Ruff's rapid maturation as a core Python tooling project. The new default rules include many from Flake8 plugins and other sources, but users may need to adjust their code or configuration to accommodate the stricter checks. Ruff v0.16.0 also includes a small number of breaking changes.

hackernews · vismit2000 · Jul 26, 09:01 · [Discussion](https://news.ycombinator.com/item?id=49056112)

**Background**: Ruff is an extremely fast Python linter and code formatter written in Rust, designed to replace tools like Flake8, Black, and isort. It supports hundreds of lint rules and runs 10-100x faster than existing linters. The project is developed by Astral, which was acquired by OpenAI.

<details><summary>References</summary>
<ul>
<li><a href="https://astral.sh/blog/ruff-v0.16.0">The next stable version of Ruff is out now.</a></li>
<li><a href="https://github.com/astral-sh/ruff">GitHub - astral-sh/ruff: An extremely fast Python linter and ... Ruff, an extremely fast Python linter | Astral Images Ruff: Complete Guide to Python's Fastest Linter | pydevtools ruff · PyPI Ruff: A Modern Python Linter for Error-Free and Maintainable ... Ruff Tutorial: A Complete Guide for Python Developers</a></li>
<li><a href="https://docs.astral.sh/ruff/linter/">The Ruff Linter | Ruff - Astral</a></li>

</ul>
</details>

**Discussion**: Users like nickjj reported that the new rules improved code quality and caught issues previous versions missed. However, some commenters expressed concerns about arbitrary rules and the challenge of updating at scale, with jon-wood suggesting a stateVersion-like mechanism to manage defaults.

**Tags**: `#ruff`, `#python`, `#linting`, `#tooling`, `#open-source`

---

<a id="item-2"></a>
## [GrapheneOS Protections Against Data Extraction from Locked Devices](https://discuss.grapheneos.org/d/40700-grapheneos-protections-against-data-extraction-from-locked-devices) ⭐️ 8.0/10

A discussion on GrapheneOS highlights its robust protections against data extraction from locked devices, including an 18-hour auto-reboot feature that returns the device to Before First Unlock (BFU) mode, where encryption keys are inaccessible. This matters because it provides a practical defense against forensic tools like Cellebrite and Grayshift, which often exploit devices in an After First Unlock (AFU) state. The auto-reboot feature ensures that even if a device is seized, it quickly reverts to a more secure state, protecting user data. The auto-reboot time is user-configurable from 10 minutes to 72 hours, with a default of 18 hours. Additionally, GrapheneOS supports duress PINs/passwords that can wipe the device or switch to a separate user profile, further complicating forced extraction attempts.

hackernews · Cider9986 · Jul 26, 05:57 · [Discussion](https://news.ycombinator.com/item?id=49055169)

**Background**: Android devices have two lock states: Before First Unlock (BFU) and After First Unlock (AFU). In BFU mode, the device's encryption keys are not in memory, making data extraction extremely difficult. Forensic tools often target AFU devices where keys are loaded. GrapheneOS is a privacy-focused Android-based OS that enhances security with features like auto-reboot and duress passwords.

<details><summary>References</summary>
<ul>
<li><a href="https://grapheneos.org/features">Features overview | GrapheneOS</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/grapheneos-frequent-android-auto-reboots-block-firmware-exploits/">GrapheneOS : Frequent Android auto - reboots block firmware exploits</a></li>
<li><a href="https://cyberpress.org/android-security-feature/">New Android Security Feature Automatically Restarts Device After...</a></li>

</ul>
</details>

**Discussion**: Community members praised the auto-reboot feature but noted the lack of a complete backup and restore solution, which would allow users to safely wipe their device before crossing borders. Some debated password entropy, with one commenter arguing that pattern locks offer only ~18.57 bits of entropy, less than a 6-digit PIN. Another user suggested that duress passwords should present a fake full-fledged OS to appear indistinguishable from the real one.

**Tags**: `#GrapheneOS`, `#mobile security`, `#data extraction`, `#privacy`, `#Android`

---

<a id="item-3"></a>
## [DeepSeek pauses fundraising after leaked transcript on compute gap](https://github.com/demo-zexuan/liang-wenfeng-investor-meeting-2026-7-22/blob/master/%E6%A2%81%E6%96%87%E9%94%8B%E6%8A%95%E8%B5%84%E8%80%85%E4%BA%A4%E6%B5%81%E4%BC%9A-%E6%96%87%E5%AD%97%E7%A8%BF_1_18_translate_20260723201651.pdf) ⭐️ 8.0/10

DeepSeek has paused its second fundraising round after a leaked transcript of CEO Liang Wenfeng's comments about the compute gap between China and the US circulated online. The company informed prospective investors of the suspension, according to Bloomberg sources. This development highlights the strategic sensitivity of AI compute resources and the geopolitical tensions in the AI race. It also raises questions about the commoditization of AI models and the long-term value of massive investments in frontier AI. The leaked transcript reportedly contains Liang Wenfeng's candid assessment of China's weaknesses in AI compute compared to the US. DeepSeek, known for its cost-efficient open-weight models, had previously raised significant funding from High-Flyer and other investors.

hackernews · oliculipolicula · Jul 25, 23:32 · [Discussion](https://news.ycombinator.com/item?id=49052912)

**Background**: DeepSeek is a Chinese AI company founded in 2023 by Liang Wenfeng, also CEO of hedge fund High-Flyer. It gained global attention in early 2025 with its R1 model, which matched GPT-4 performance at a fraction of the training cost. The company operates under US export restrictions on advanced AI chips, using weaker hardware efficiently.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_(Company)">DeepSeek (Company)</a></li>
<li><a href="https://www.linkedin.com/pulse/what-china-does-want-us-know-luiza-jarovsky-phd-v7pre">What China Does Not Want the U . S . to Know</a></li>

</ul>
</details>

**Discussion**: Commenters debated whether the pause indicates DeepSeek's own doubts about the commoditization narrative. Some noted that if Chinese models are catching up at lower cost, US spending may have diminishing returns, yet DeepSeek still seeks frontier performance. Others clarified that the leak is about the compute gap, not the fundraising pause itself.

**Tags**: `#AI`, `#fundraising`, `#US-China`, `#compute gap`, `#DeepSeek`

---
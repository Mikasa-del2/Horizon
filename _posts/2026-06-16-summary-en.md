---
layout: default
title: "Horizon Summary: 2026-06-16 (EN)"
date: 2026-06-16
lang: en
---

> From 42 items, 9 important content pieces were selected

---

1. [Backdoor in LinkedIn Job Offer Exploits npm Prepare Script](#item-1) ⭐️ 9.0/10
2. [Nanocrystal method boosts all-perovskite tandem solar module efficiency](#item-2) ⭐️ 9.0/10
3. [At-home brain implant restores daily life for MND patient](#item-3) ⭐️ 9.0/10
4. [Banned Book Library in a Wi-Fi Smart Light Bulb](#item-4) ⭐️ 8.0/10
5. [Iroh 1.0: Peer-to-Peer Networking Library Released](#item-5) ⭐️ 8.0/10
6. [AI Reveals Secret Lives of Animals](#item-6) ⭐️ 7.0/10
7. [Kew Gardens digitizes 7 million specimens with AI aid](#item-7) ⭐️ 6.0/10
8. [Obesity Drugs May Boost Testosterone and Sperm Quality](#item-8) ⭐️ 5.0/10
9. [Simple Household Items Boost Research Reproducibility](#item-9) ⭐️ 5.0/10

---

<a id="item-1"></a>
## [Backdoor in LinkedIn Job Offer Exploits npm Prepare Script](https://roman.pt/posts/linkedin-backdoor/) ⭐️ 9.0/10

A security researcher reported that a recruiter from a fake crypto startup sent a GitHub repository containing a backdoor hidden in npm's prepare script, which executes automatically upon npm install. The attack targeted developers during a job interview process. This attack vector is particularly dangerous because it exploits the trust inherent in job interviews and leverages a common developer workflow (npm install) to compromise systems. It highlights a growing trend of supply chain attacks via fake job offers, as seen with North Korean threat groups like PurpleBravo. The backdoor was hidden in a public GitHub repository, buried within commented-out tests, and used npm's prepare script to execute arbitrary commands from a remote server. The researcher reported the repo to GitHub and the recruiter to LinkedIn, but the code remained active at the time of writing.

hackernews · lwhsiao · Jun 15, 20:00 · [Discussion](https://news.ycombinator.com/item?id=48546294)

**Background**: npm lifecycle scripts like prepare, preinstall, and postinstall run automatically with full user privileges when packages are installed, making them a common vector for supply chain attacks. Setting ignore-scripts=true in .npmrc can block such attacks. GitHub plans to disable automatic script execution by default in npm v12 (expected July 2026) to mitigate this risk.

<details><summary>References</summary>
<ul>
<li><a href="https://cybersecuritynews.com/github-automated-disable-npm-script-installs/">GitHub to Automate Disable npm Script Installs to Block Supply Chain ...</a></li>
<li><a href="https://stackoverflow.com/questions/44499912/why-is-npm-running-prepare-script-after-npm-install-and-how-can-i-stop-it">node.js - Why is npm running prepare script after npm install, and how ...</a></li>
<li><a href="https://www.recordedfuture.com/research/purplebravos-targeting-it-software-supply-chain">PurpleBravo’s Targeting of the IT Software Supply Chain</a></li>

</ul>
</details>

**Discussion**: Commenters expressed concern that this attack is uncomfortably close to a normal interview task, and some reported encountering similar scams multiple times. There was frustration that GitHub and LinkedIn did not take down the malicious content promptly, and a call for better cybercrime reporting infrastructure.

**Tags**: `#security`, `#supply chain attack`, `#npm`, `#job interview scam`, `#cybercrime`

---

<a id="item-2"></a>
## [Nanocrystal method boosts all-perovskite tandem solar module efficiency](https://www.nature.com/articles/s41586-026-10768-1) ⭐️ 9.0/10

Researchers developed a solution-processed interconnecting layer using surface-engineered indium oxide nanocrystals to replace the conventional gold-based tunnel recombination junction in all-perovskite tandem solar modules. This achieved a certified power conversion efficiency of 26.2% on a 65 cm² module, with improved stability. This breakthrough addresses key barriers—parasitic absorption and interfacial instability—that have hindered commercialization of all-perovskite tandem solar modules. The high efficiency and scalable solution processing bring perovskite tandem technology closer to practical deployment in renewable energy. The nanocrystal layer features high optical transparency, smooth interfacial contact, and favorable energy level alignment, enabling a certified efficiency of 26.2% with an open-circuit voltage of 2.182 V, fill factor of 77.4%, and short-circuit current density of 15.6 mA cm⁻². The work was published in Nature on June 15, 2026.

rss · Nature - Latest Research · Jun 15, 00:00

**Background**: All-perovskite tandem solar cells stack two perovskite subcells with different bandgaps to surpass the efficiency limit of single-junction cells. A key component is the tunnel recombination junction (TRJ) that connects the subcells; conventional gold-based TRJs cause parasitic absorption and stability issues. This work introduces a nanocrystal-based TRJ that overcomes these limitations.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41586-026-10768-1">Nanocrystal-tailored recombination for all-perovskite tandem solar modules | Nature</a></li>
<li><a href="https://www.nature.com/articles/s41563-024-02073-x">All-perovskite tandem solar cells achieving >29% efficiency with improved (100) orientation in wide-bandgap perovskites | Nature Materials</a></li>
<li><a href="https://www.nature.com/articles/s41560-022-01059-w">Scalable two-terminal all-perovskite tandem solar modules with a 19.1% efficiency | Nature Energy</a></li>

</ul>
</details>

**Tags**: `#perovskite solar cells`, `#nanocrystals`, `#photovoltaics`, `#tandem solar modules`, `#materials science`

---

<a id="item-3"></a>
## [At-home brain implant restores daily life for MND patient](https://www.nature.com/articles/d41586-026-01863-4) ⭐️ 9.0/10

A brain implant has enabled a man with motor neuron disease to communicate and control his computer at home for nearly two years, as reported in Nature on June 15, 2026. This marks a major milestone in assistive neurotechnology, demonstrating long-term, real-world use of a brain-computer interface that could significantly improve quality of life for people with paralysis. The device has been used continuously for nearly two years without reported complications, allowing the patient to perform daily tasks such as typing and web browsing.

rss · Nature - Latest Research · Jun 15, 00:00

**Background**: Motor neuron disease (MND) progressively damages nerve cells controlling voluntary muscles, often leading to complete paralysis. Brain-computer interfaces (BCIs) translate neural signals into commands for external devices, but most systems are limited to lab settings. This at-home implant represents a shift toward practical, long-term assistive technology.

**Tags**: `#brain-computer interface`, `#neuroscience`, `#assistive technology`, `#motor neuron disease`, `#medical device`

---

<a id="item-4"></a>
## [Banned Book Library in a Wi-Fi Smart Light Bulb](https://www.richardosgood.com/posts/banned-book-library/) ⭐️ 8.0/10

A developer has turned a Wi-Fi smart light bulb into a web server that hosts a small library of banned books, accessible over the local network. This project combines technical ingenuity with free speech advocacy, demonstrating how everyday IoT devices can be repurposed to circumvent censorship and preserve access to information. The device has only 4MB of storage, limiting the library to a few EPUB files of around 350KB each. The server is accessible only on the local Wi-Fi network, not the internet.

hackernews · sohkamyung · Jun 15, 22:37 · [Discussion](https://news.ycombinator.com/item?id=48547985)

**Background**: Smart light bulbs are IoT devices that connect to Wi-Fi and are typically controlled via an app. This project hacks the bulb's firmware to run a lightweight web server instead. The concept is similar to PirateBox, a portable file-sharing device, but embedded in a light bulb.

<details><summary>References</summary>
<ul>
<li><a href="https://www.richardosgood.com/posts/banned-book-library/">Banned Book Library | Rick's Blog</a></li>
<li><a href="https://en.wikipedia.org/wiki/The_Uncensored_Library">The Uncensored Library - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Internet_censorship">Internet censorship - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters praised the project's creativity and relevance to free speech, with some drawing parallels to PirateBox and mesh networking. There was also discussion about the specific list of banned books and the broader context of censorship.

**Tags**: `#censorship`, `#IoT`, `#hacking`, `#free speech`, `#ebooks`

---

<a id="item-5"></a>
## [Iroh 1.0: Peer-to-Peer Networking Library Released](https://www.iroh.computer/blog/v1) ⭐️ 8.0/10

Iroh 1.0 is a peer-to-peer networking library that enables direct connections between app instances without requiring user accounts, supporting custom transports beyond IPv4, IPv6, and relay. This library simplifies app-layer connectivity for developers, reducing reliance on centralized infrastructure and enabling decentralized applications with ease. Iroh uses cryptographic dial keys instead of IP addresses for addressing, and it supports custom transports via a plugin system to avoid codebase bloat.

hackernews · chadfowler · Jun 15, 15:13 · [Discussion](https://news.ycombinator.com/item?id=48542480)

**Background**: Traditional networking relies on IP addresses and DNS, which can be fragile for peer-to-peer apps. Iroh provides a dial-any-device approach similar to Tailscale but at the application layer, using cryptographic keys for identity and relays for NAT traversal.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/n0-computer/iroh">GitHub - n0-computer/ iroh : IP addresses break, dial keys instead.</a></li>
<li><a href="https://docs.rs/iroh/latest/iroh/">iroh - Rust</a></li>
<li><a href="https://iroh-computer.vercel.app/blog/iroh-0-29-net-is-the-new-iroh">iroh 0.29 - net is the new iroh - Iroh</a></li>

</ul>
</details>

**Discussion**: The community compared Iroh to Tailscale, with one developer noting it's like 'Tailscale at the application layer.' Another developer appreciated the custom transport extensibility, while some users found the documentation unclear about dial keys and the problem being solved.

**Tags**: `#networking`, `#p2p`, `#rust`, `#open-source`, `#libraries`

---

<a id="item-6"></a>
## [AI Reveals Secret Lives of Animals](https://www.nature.com/articles/d41586-026-01887-w) ⭐️ 7.0/10

A Nature article reports that advances in machine learning are enabling researchers to track and understand wildlife movements, landmarks, and social behaviors, from hummingbirds to pumas. This application of AI to ecology provides unprecedented insights into animal behavior, which can inform conservation efforts and deepen our understanding of biodiversity. The article highlights how machine learning models analyze large datasets from camera traps, GPS collars, and audio recordings to identify individual animals, map territories, and detect social interactions.

rss · Nature - Latest Research · Jun 15, 00:00

**Background**: Traditional wildlife research relies on manual observation and tagging, which is time-consuming and limited in scale. AI techniques like computer vision and acoustic analysis automate data processing, enabling continuous monitoring across vast areas.

**Tags**: `#machine learning`, `#wildlife research`, `#AI applications`, `#ecology`

---

<a id="item-7"></a>
## [Kew Gardens digitizes 7 million specimens with AI aid](https://www.nature.com/articles/d41586-026-01917-7) ⭐️ 6.0/10

Kew Botanic Gardens in London has completed digitizing 7 million natural history specimens, and AI tools are now being applied to help analyze the data for biodiversity conservation. This massive digitization effort makes a vast collection accessible globally, and AI analysis can accelerate species identification and monitoring, aiding conservation efforts against biodiversity loss. The digitization includes specimens from the herbarium and fungarium, with over 3.4 million collections fully digitized as of July 2024. AI tools are being used to extract data from images and assist in species classification.

rss · Nature - Latest Research · Jun 15, 00:00

**Background**: Kew's herbarium and fungarium are among the world's largest collections of plant and fungal diversity. Digitization involves high-resolution imaging and metadata capture, making specimens available online for researchers worldwide.

<details><summary>References</summary>
<ul>
<li><a href="https://archive.org/stream/digitisingkewsh8moor/digitisingkewsh8moor_djvu.txt">Full text of " Digitising Kew 's Herbarium: Do We Have a Protocol for......</a></li>
<li><a href="https://www.independent.co.uk/climate-change/news/kew-darwin-zombie-scientists-royal-botanic-gardens-b2751241.html">‘Zombie spiders’ and Darwin collection among fungi archived in Kew ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#digitization`, `#biodiversity`, `#natural history`

---

<a id="item-8"></a>
## [Obesity Drugs May Boost Testosterone and Sperm Quality](https://www.nature.com/articles/d41586-026-01867-0) ⭐️ 5.0/10

A preliminary study published in Nature on June 15, 2026, suggests that GLP-1 obesity drugs may increase or stabilize testosterone levels and improve sperm quality in men. This finding could expand the therapeutic benefits of GLP-1 drugs beyond weight loss and diabetes management, potentially addressing male infertility and hormonal imbalances. The study is preliminary and has not yet been peer-reviewed; further research is needed to confirm the effects and understand the underlying mechanisms.

rss · Nature - Latest Research · Jun 15, 00:00

**Background**: GLP-1 (glucagon-like peptide-1) receptor agonists, such as semaglutide (Ozempic, Wegovy) and tirzepatide (Zepbound), are drugs originally approved for type 2 diabetes and later found to promote weight loss. They work by mimicking incretin hormones that regulate appetite and insulin secretion. Recent research has been exploring additional health benefits of these drugs.

<details><summary>References</summary>
<ul>
<li><a href="https://medicalxpress.com/news/2026-04-glp-drugs-weight-loss-health.html">What to know about GLP - 1 drugs for weight loss and health</a></li>

</ul>
</details>

**Tags**: `#obesity drugs`, `#GLP-1`, `#testosterone`, `#sperm quality`, `#health research`

---

<a id="item-9"></a>
## [Simple Household Items Boost Research Reproducibility](https://www.nature.com/articles/d41586-026-01885-y) ⭐️ 5.0/10

A Nature article published on June 15, 2026 argues that common household items can enhance research reproducibility and accessibility, countering the trend toward complex technology. This perspective challenges the assumption that advanced technology is always necessary, potentially lowering barriers for under-resourced labs and improving the reliability of scientific findings. The article does not specify particular household items but emphasizes their role in making research more reproducible and accessible, especially in field settings or low-resource environments.

rss · Nature - Latest Research · Jun 15, 00:00

**Background**: Reproducibility is a cornerstone of scientific research, yet many studies fail to replicate due to complex or expensive equipment. Simple tools can reduce variability and make methods easier to adopt across labs.

**Tags**: `#research`, `#reproducibility`, `#science`, `#tools`

---
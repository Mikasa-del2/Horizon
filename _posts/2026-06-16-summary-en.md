---
layout: default
title: "Horizon Summary: 2026-06-16 (EN)"
date: 2026-06-16
lang: en
---

> From 36 items, 4 important content pieces were selected

---

1. [Backdoor in Fake LinkedIn Job Offer Targets Developers](#item-1) ⭐️ 8.0/10
2. [Banned Book Library Hidden in Smart Light Bulb](#item-2) ⭐️ 8.0/10
3. [Iroh 1.0: P2P Networking with Dial Keys, Not IPs](#item-3) ⭐️ 8.0/10
4. [Why South Koreans Embrace AI So Deeply](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Backdoor in Fake LinkedIn Job Offer Targets Developers](https://roman.pt/posts/linkedin-backdoor/) ⭐️ 8.0/10

A security researcher detailed a social engineering attack where a fake recruiter sent a GitHub repository containing a backdoor that executes via npm's prepare script during npm install. This attack exploits developers' trust in job interviews and automated npm scripts, potentially compromising many developers and enabling supply chain attacks if the backdoor spreads. The backdoor was hidden in a deprecated Node modules review task, and npm's prepare script runs automatically after npm install, executing the payload without user interaction.

hackernews · lwhsiao · Jun 15, 20:00 · [Discussion](https://news.ycombinator.com/item?id=48546294)

**Background**: npm prepare is a lifecycle script that runs automatically after 'npm install' in a package, often used for build steps. Supply chain attacks target less secure elements in the software development pipeline, and this attack combines social engineering with a technical exploit to compromise developers.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.npmjs.com/cli/v11/using-npm/scripts/">Scripts | npm Docs</a></li>
<li><a href="https://en.wikipedia.org/wiki/Supply_chain_attack">Supply chain attack</a></li>

</ul>
</details>

**Discussion**: Commenters noted the attack is disturbingly similar to normal interview tasks, with some reporting experiencing it multiple times. There is frustration over the lack of reporting mechanisms and slow response from platforms like GitHub and LinkedIn.

**Tags**: `#security`, `#social engineering`, `#supply chain attack`, `#npm`, `#cybercrime`

---

<a id="item-2"></a>
## [Banned Book Library Hidden in Smart Light Bulb](https://www.richardosgood.com/posts/banned-book-library/) ⭐️ 8.0/10

A developer has embedded a library of banned books into the firmware of a Wi-Fi smart light bulb, creating a covert digital library that can be accessed via the bulb's Wi-Fi network. This project demonstrates a novel method for circumventing censorship by repurposing everyday IoT devices as hidden data stores, potentially empowering individuals in restrictive environments to access banned information. The light bulb's limited storage capacity restricts the number of books that can be stored, and the project currently requires physical access to the bulb to set up. The developer also suggests future enhancements like mesh networking to expand coverage.

hackernews · sohkamyung · Jun 15, 22:37 · [Discussion](https://news.ycombinator.com/item?id=48547985)

**Background**: Smart light bulbs contain microchips with firmware that can be reprogrammed. This project exploits that capability to store data instead of just controlling lighting. Similar projects like PirateBox and The Uncensored Library have used other devices to host censored content.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bitdefender.com/en-us/blog/hotforsecurity/has-your-smart-wifi-enabled-led-light-bulb-been-hacked">Has your smart WiFi-enabled LED light bulb been hacked?</a></li>
<li><a href="https://en.wikipedia.org/wiki/The_Uncensored_Library">The Uncensored Library - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters praised the project's creativity and relevance to censorship concerns, with some drawing parallels to earlier projects like PirateBox and LibraryBox. There was also discussion about potential mesh networking to overcome storage limitations.

**Tags**: `#censorship`, `#IoT`, `#freedom of information`, `#hacking`, `#digital rights`

---

<a id="item-3"></a>
## [Iroh 1.0: P2P Networking with Dial Keys, Not IPs](https://www.iroh.computer/blog/v1) ⭐️ 8.0/10

Iroh 1.0 has been released as a stable peer-to-peer networking library that uses public keys (EndpointIds) instead of IP addresses for direct connections between app instances. This release simplifies peer-to-peer connectivity for application developers, eliminating the need for IP address management and enabling seamless direct connections across NATs and changing networks. Iroh uses QUIC connections established via a magic socket, with relays and hole-punching for NAT traversal, and supports custom transports for extensibility.

hackernews · chadfowler · Jun 15, 15:13 · [Discussion](https://news.ycombinator.com/item?id=48542480)

**Background**: Traditional networking relies on IP addresses, which can change and break connections. Iroh replaces IPs with cryptographic keys, allowing peers to be identified and reached regardless of network changes. It is built in Rust and offers a modular protocol ecosystem.

<details><summary>References</summary>
<ul>
<li><a href="https://www.iroh.computer/blog/v1">Iroh 1.0 - Dial Keys, not IPs - Iroh</a></li>
<li><a href="https://github.com/n0-computer/iroh">GitHub - n0-computer/iroh: IP addresses break, dial keys ... n0-computer/iroh | DeepWiki Iroh 1.0: Dial Keys, Not IPs — P2P Hits Stable | byteiota Iroh — Rust network library // Lib.rs iroh 0.23.0 - Welcoming Node.js to the family! - Iroh iroh - Iroh is a modular networking stack for building ...</a></li>
<li><a href="https://www.iroh.computer/">Iroh</a></li>

</ul>
</details>

**Discussion**: Community comments compare Iroh to 'Tailscale at the application layer' and discuss extensibility for custom transports like WebRTC or BLE. Some users question the problem it solves, while others praise the decentralization vision.

**Tags**: `#networking`, `#peer-to-peer`, `#rust`, `#open-source`, `#release`

---

<a id="item-4"></a>
## [Why South Koreans Embrace AI So Deeply](https://www.technologyreview.com/2026/06/15/1138983/why-do-south-koreans-love-ai-so-much/) ⭐️ 7.0/10

A new analysis explores the cultural, economic, and policy factors behind South Korea's exceptionally high adoption of AI, from automated immigration checkpoints to widespread AI integration in daily life. Understanding South Korea's AI embrace offers valuable lessons for other nations seeking to accelerate AI adoption, highlighting the interplay of government policy, tech infrastructure, and cultural attitudes. The article is based on the author's personal experience arriving in Seoul, where an unmanned immigration checkpoint used facial recognition, illustrating the seamless integration of AI into public services.

rss · MIT Technology Review - AI · Jun 15, 18:46

**Background**: South Korea has long been a global leader in technology adoption, with high smartphone penetration and fast internet. The government has actively promoted AI through national strategies and investments, while cultural factors like early tech adoption and trust in institutions may also play a role.

**Tags**: `#AI adoption`, `#South Korea`, `#technology policy`, `#cultural analysis`

---
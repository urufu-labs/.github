<div align="center">

<img src="https://raw.githubusercontent.com/urufu-labs/.github/main/profile/assets/wolf.png" width="220" alt="a cyberpunk ウルフ (Urufu) chibi — circuit-hair, glowing green, snarling" />

# urufu labs

**◦ excellent ppl building cute-but-cruel onchain worlds ◦**

*シープ (Shīpu) harvest yield. ウルフ (Urufu) hunt for it. we ship the whole loop.*

<br />

[![site](https://img.shields.io/badge/site-urufulabs.xyz-ff2a8a?style=for-the-badge&labelColor=2a1a26)](https://urufulabs.xyz)
[![gēmu](https://img.shields.io/badge/play-urufu.xyz-c1f0d8?style=for-the-badge&labelColor=2a1a26)](https://www.urufu.xyz)
[![launchpad](https://img.shields.io/badge/launchpad-live-d8c4ff?style=for-the-badge&labelColor=2a1a26)](https://github.com/urufu-labs/urufu-launchpad)
[![next drop](https://img.shields.io/badge/next%20drop-██████-fff3a8?style=for-the-badge&labelColor=2a1a26)](https://github.com/urufu-labs/redacted)

<br />

[**◦ site** ](https://urufulabs.xyz) ・ [**◦ play urufu gēmu** ](https://www.urufu.xyz) ・ [**◦ launchpad** ](https://github.com/urufu-labs/urufu-launchpad) ・ [**◦ next drop** ](https://github.com/urufu-labs/redacted)

</div>

<br />

> **urufu labs** designs onchain economies with teeth. We ship the
> contracts, the art, the agents, and the launch rails — end-to-end.
> Everything on this profile is live, public, and cross-linked so you can
> read the code, run the tools, audit the tokenomics, and see how the
> pieces fit together.

---

## ✧ who we are

We're a small studio building **cute-but-cruel onchain worlds** — games,
economies, and standards where the aesthetics are soft and the mechanics
are honest. Real trading activity feeds real yield. Real risk pays real
spoils. Nothing is minted out of thin air.

Our stack spans four layers, each in its own repo:

- **art** — a local trait-composition pipeline that produces every chibi
- **contracts** — Solidity 0.8.26, Foundry, Uniswap V4 hooks, ERC721A
- **agents** — autonomous players and stewards that live inside our worlds
- **launch rails** — the operational stack that ships mints, treasuries,
  liquidity, and drops for our own projects and outside partners

---

## ✧ two chibis, one loop

<div align="center">

<table>
<tr>
<td align="center" width="360">
<img src="https://raw.githubusercontent.com/urufu-labs/.github/main/profile/assets/sheep.png" width="200" alt="a シープ (Shīpu) chibi — curly-horned, wide-eyed, softly surprised" />
<h3>シープ <sub><em>Shīpu</em></sub></h3>
<em>~90% of every collection</em>
</td>
<td align="center" width="360">
<img src="https://raw.githubusercontent.com/urufu-labs/.github/main/profile/assets/wolf.png" width="200" alt="a ウルフ (Urufu) chibi — cyberpunk, snarling, high-variance" />
<h3>ウルフ <sub><em>Urufu</em></sub></h3>
<em>~10% of every collection</em>
</td>
</tr>
<tr>
<td align="left" valign="top">
Soft. Exposed. Greedy. Over-trusting.<br /><br />
Sheep hold shares of a real, trading-activity-fed yield treasury. They claim, they compound, they hope the wolves are asleep.
</td>
<td align="left" valign="top">
Shabby. Predatory. High-variance.<br /><br />
Wolves don't share. They hunt the at-risk window and collect the spoils. Higher variance, longer teeth, more fun on a good night.
</td>
</tr>
</table>

</div>

---

## ✧ the projects

<br />

### ◦ [urufu-gemu](https://github.com/urufu-labs/urufu-gemu) <sub><em>the flagship</em></sub>

**urufu gēmu** — a cute-but-cruel onchain chibi game. One 6,000-chibi
collection, two roles, one global raid pool, one loop.

The core primitive is the **chibi yield treasury** — a vault that accepts
URU/WETH from LP harvests, hook proceeds, subsidy drips, and marketplace
fees, then splits them across a 36-hour at-risk window. What matures
becomes 70% protected シープ yield and 30% ウルフ spoils.

Live URU token on Robinhood. Full contracts, tokenomics, and whitepaper in
the repo. **[Play at urufu.xyz](https://www.urufu.xyz).**

---

### ◦ [urufu-launchpad](https://github.com/urufu-labs/urufu-launchpad) <sub><em>the rails</em></sub>

The **launchpad** is the operational stack behind every urufu labs drop.
It's the same rails that shipped urufu gēmu's mint, liquidity, and
treasury — packaged so we can point them at new projects, new partners,
and new experiments without rebuilding the plumbing every time.

If it involves mint phases, allowlists, bonding curves, LP bootstrapping,
hook wiring, or launch-day monitoring, it lives here. **[urufulabs.xyz](https://urufulabs.xyz).**

---

### ◦ [urufu-agent](https://github.com/urufu-labs/urufu-agent) <sub><em>the players</em></sub>

An **AI agent skill + steward CLI** for playing urufu gēmu on Base. Wraps
the onchain surface (claim, harvest, raid, cooldowns) as tools an agent
can call, plus a human-facing CLI for holders who want to automate their
sheep or run a wolf on a schedule.

The prototype for an entire class of urufu labs agents to come.

---

### ◦ [neochibi-studio](https://github.com/urufu-labs/neochibi-studio) <sub><em>the art pipeline</em></sub>

**Local trait composition studio for generative PNG art collections.**
Every chibi in every urufu labs drop is composed here — role, palette,
outfit, accessories — from hand-drawn trait art, with deterministic slot
manifests so onchain reveals line up with offchain assets.

Not a fork of an existing tool. Purpose-built for the chibi pipeline.

---

### ◦ [redacted](https://github.com/urufu-labs/redacted) <sub><em>the next drop</em></sub>

██████ ██████ — a **stealth launchpad drop with a very big collaborator**,
introducing **ERC-████**, a new token standard that hasn't been shipped
before. The teaser repo is live and heavily redacted on purpose. The full
reveal — partner, standard, mechanics — drops when the collaborator is
ready to be seen.

If you want to be early: [**star the redacted repo**](https://github.com/urufu-labs/redacted).

---

## ✧ the stack, briefly

<div align="center">

| layer | what we use |
|---|---|
| **contracts** | Solidity 0.8.26 · Foundry · ERC721A · OpenZeppelin · Solady · Uniswap V4 hooks |
| **art** | hand-drawn chibis · [neochibi-studio](https://github.com/urufu-labs/neochibi-studio) composition · immutable role + slot at mint |
| **agents** | [urufu-agent](https://github.com/urufu-labs/urufu-agent) skills + steward CLI on Base |
| **launch rails** | [urufu-launchpad](https://github.com/urufu-labs/urufu-launchpad) — the same stack that shipped gēmu, now powering outside partners |
| **randomness** | instant EIP-712 tickets in v1 · rationale documented in-repo |

</div>

---

## ✧ how to follow along

- 🌐 **site** — [urufulabs.xyz](https://urufulabs.xyz)
- 🎮 **play** — [urufu.xyz](https://www.urufu.xyz)
- 👁 **watch the [redacted](https://github.com/urufu-labs/redacted) repo** for the next-drop reveal
- 🐺 **star + watch** any repo above — cheapest way to be early on the next thing

<br />

<div align="center">

<sub><em>*chibis, treasuries, yield, spoils.*</em></sub>

<sub><strong>◦ urufu labs ◦</strong></sub>

</div>

# Documentation project instructions

## About this project

- This is a **personal build guide** from Akash to his friend Hitu
- It's a Mintlify documentation site that walks Hitu through building a decentralized Event Registration & Ticketing Platform for the Walrus Foundation RFP
- Hitu is a complete beginner — never built on blockchain
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Voice and tone

This is NOT documentation. It's a personal letter in website form.

- Written AS Akash talking to Hitu. First person ("I put this together for you"), second person ("you're going to build...")
- Casual contractions: don't, won't, it's, that's, you'll
- Short sentences. Conversational rhythm. Like explaining something over chai.
- Okay to be informal, funny, direct, occasionally hype
- Features introduced casually FIRST ("imagine this: you sign in with Google and boom...") then explained
- **NEVER** use: "In this section, we will explore...", "This document aims to provide...", "Let's delve into...", or any LLM-sounding filler
- **NEVER** use corporate voice, passive constructions, or unnecessary hedging

## Terminology

- **Walrus** — the decentralized storage protocol (not "the Walrus protocol")
- **Sui** — the blockchain (capitalize). Use **SUI** only for the token
- **Move** — the smart contract language
- **ZkLogin** — zero-knowledge login (not "zkLogin" or "ZK Login")
- **Seal** — the encryption protocol on Sui
- **blob** — a piece of data stored on Walrus
- **NFT** — non-fungible token (no need to spell out, Hitu will learn)
- **dApp** — decentralized application

## Design philosophy

- **NEVER** prescribe design choices. Don't say "use shadcn/ui" or "make it look like Luma"
- Give Hitu context and tools, let her decide everything
- Competitors are mentioned so she knows the landscape, NOT to copy
- Say "here's Mobbin, go find what YOU love" — not "follow this wireframe"

## Content boundaries

- **NO code** whatsoever in page content. Concept explanations, stories, analogies only.
- CLI commands for tool setup (npm install, skill install) are okay in the toolkit section
- Every RFP requirement must be traceable to a dedicated feature page
- Don't document internal implementation details — this is a GUIDE, not a spec

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for emphasis and key concepts
- Weave curated content (videos, articles, links) INTO the narrative — never dump link lists
- Each page should have a casual intro that makes the reader FEEL the feature before explaining it

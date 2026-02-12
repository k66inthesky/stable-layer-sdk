# Stable Layer SDK

TypeScript SDK for minting, burning stablecoins and claiming yield rewards on the Sui blockchain via the Stable Layer protocol.

## Why Use?
Save your API token cost!! 
大幅省 OpenClaw 在背後執行時需要頻繁查詢的token啊！

## Installation

```bash
npx clawhub install stable-layer-sdk
```
## Modules 模組

stable-layer-sdk from https://github.com/StableLayer/stable-layer-sdk

## Usage 使用方式

See [SKILL.md](./SKILL.md) for full API reference and code examples.
完整 API 參考與範例請見 [SKILL.md](./SKILL.md)。

## Contact 聯繫
+ Github repo: https://github.com/k66inthesky/stable-layer-sdk
+ Author: @k66inthesky https://github.com/k66inthesky/

## Source 來源
+ https://github.com/StableLayer/stable-layer-sdk

---
## AI tool Desclaimer AI工具聲明
+ 參加[Sui vibe Hackathon](https://www.deepsurge.xyz/projects/351492fa-b8d3-42e9-a734-a6ccb1218948)
+ 開發工具: 只用Claude Code CLI
+ 模型：只用Opus 4.6
+ 對話：
```
⏺ Compact summary
  ⎿  This session is being continued from a previous conversation that ran out of context. The summary below covers the
     earlier portion of the conversation.

     Analysis:
     Let me analyze the conversation chronologically:

     1. User's request (single message with 3 points):
        - Read https://github.com/StableLayer/stable-layer-sdk and write a SKILL.md for OpenClaw
        - SKILL.md must be in English
        - Write a README (under 100 words, one-sentence intro, install using `npx clawhub install stable-layer-sdk`)

     2. My approach:
        - Used WebFetch to read the GitHub repo page
        - Used Task/Explore agent to check the local codebase at /Users/k66/stable-layer-sdk
        - Local directory was empty (only .claude/ config dir)
        - Got comprehensive info from GitHub about the SDK
        - Wrote both SKILL.md and README.md

     3. Key findings from GitHub:
        - TypeScript SDK for Stable Layer protocol on Sui blockchain
        - Supports minting/burning stablecoins and claiming yield farming rewards
        - Core class: StableLayerClient
        - Methods: buildMintTx, buildBurnTx, buildClaimTx, getTotalSupply, getTotalSupplyByCoinType
        - MIT license

     4. Files created:
        - /Users/k66/stable-layer-sdk/SKILL.md - full API documentation
        - /Users/k66/stable-layer-sdk/README.md - brief readme under 100 words

     5. No errors encountered. No user feedback received yet on the output.

     6. Task appears complete - both files were created successfully.

     Summary:
     1. Primary Request and Intent:
        The user requested three things in a single message:
        1. Read the GitHub repository at https://github.com/StableLayer/stable-layer-sdk and write a SKILL.md file for
     OpenClaw usage
        2. SKILL.md must be entirely in English
        3. Write a README.md (under 100 words, one-sentence description, installation via `npx clawhub install
     stable-layer-sdk`)

     2. Key Technical Concepts:
        - Stable Layer SDK: TypeScript SDK for the Stable Layer protocol on the Sui blockchain
        - StableLayerClient: Core class with constructor accepting `network` ("mainnet"|"testnet") and `sender` (Sui
     address)
        - Transaction methods: `buildMintTx`, `buildBurnTx`, `buildClaimTx`
        - Query methods: `getTotalSupply`, `getTotalSupplyByCoinType`
        - Dependencies: `@mysten/sui`, `@mysten/bcs`
        - OpenClaw / ClawHub: A skill marketplace for AI coding assistants; SKILL.md serves as the documentation format
        - Sui blockchain stablecoin minting, burning, and yield farming

     3. Files and Code Sections:
        - `/Users/k66/stable-layer-sdk/SKILL.md` (CREATED)
          - Full English API documentation for OpenClaw consumption
          - Covers: installation, StableLayerClient constructor, all transaction methods (buildMintTx, buildBurnTx,
     buildClaimTx) with parameter tables, query methods (getTotalSupply, getTotalSupplyByCoinType), and complete usage
     examples for mint, burn, claim, and query operations
        - `/Users/k66/stable-layer-sdk/README.md` (CREATED)
          - Brief README under 100 words
          - One-sentence intro: "TypeScript SDK for minting, burning stablecoins and claiming yield rewards on the Sui
     blockchain via the Stable Layer protocol."
          - Installation command: `npx clawhub install stable-layer-sdk`
          - Includes a Quick Start code snippet and MIT license note
        - `/Users/k66/stable-layer-sdk/.claude/settings.local.json` (PRE-EXISTING)
          - Contains permission settings allowing WebFetch for github.com

     4. Errors and fixes:
        - The local directory `/Users/k66/stable-layer-sdk` was empty (no source code, no git repo). This was not an
     error per se but meant all SDK information had to come from the GitHub WebFetch. Successfully retrieved
     comprehensive API details from the GitHub page.

     5. Problem Solving:
        - Parallelized the GitHub fetch and local codebase exploration to save time
        - When local codebase was found empty, relied entirely on GitHub-fetched information to write both files
        - Both files were created successfully matching all user requirements

     6. All user messages:
        - "1. 請讀https://github.com/StableLayer/stable-layer-sdk並寫一個SKILL.md(給OpenClaw)使用 2. SKILL.md要全英文 3.
      寫一個README(100字以內，簡介只需一句話，安裝使用npx clawhub install stable-layer-sdk)"

     7. Pending Tasks:
        - None. Both requested files (SKILL.md and README.md) have been created. No user feedback has been received yet.

     8. Current Work:
        Both files were written and the task was reported as complete. The SKILL.md contains full API documentation with
      parameter tables and code examples. The README.md is under 100 words with one-sentence intro and `npx clawhub
     install stable-layer-sdk` installation.

```

---
## License

MIT

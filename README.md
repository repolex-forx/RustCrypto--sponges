# Repolex Knowledge Graph of RustCrypto/sponges

RDF knowledge graph data for [RustCrypto/sponges](https://github.com/RustCrypto/sponges), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download RustCrypto/sponges
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ae480398120a0e753048dcf03dfeb2f6882c15aa
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ae480398120a0e753048dcf03dfeb2f6882c15aa.nq.gz
│   └── repolex
│       └── ae480398120a0e753048dcf03dfeb2f6882c15aa
│           └── chunk-001.nq.gz
├── blob
│   ├── 005a58d49d0b52d8dd2ae09ae71e3eb6036a65ef.nq.gz
│   ├── 038d1ff3f6ac9effa3e3fea3538b684d026c3aae.nq.gz
│   ├── 062fc9b5f744b4ce42d4650f4248a9adafe55846.nq.gz
│   ├── 13f0f70033327494f3c0b2e58292fbe4a5b0acc3.nq.gz
│   ├── 14fad35b68ddd3c1889009928af0023dcc24e1fb.nq.gz
│   ├── 160d37a96392a69246d7259b6d2ba82f071492e9.nq.gz
│   ├── 255523517c1c73887e28194664596b09595ed5cd.nq.gz
│   ├── 28bb0545f8ff4b4524f7010e0c3c017c74c478ba.nq.gz
│   ├── 2ae13ddb4134dbd837dad922a2b42bee73ff368d.nq.gz
│   ├── 3137af480f86a6b54f9a97d03b9ac405519b3c8c.nq.gz
│   ├── 3177e7114a8ba94779b2934c2b904af91feeac76.nq.gz
│   ├── 349b62fb3a2cb67c3fd3bc4cb4870316f1c0d029.nq.gz
│   ├── 37fba61fa029a0510e2c94f4e30c5a49686e76a3.nq.gz
│   ├── 387550f0ce416003e53fcf2e6ca8235fb463052b.nq.gz
│   ├── 38bc5148fdb3e1f8a1fd4526676879f1afadf6f5.nq.gz
│   ├── 397bdaa4f10fcf70786ab3afd305ad233b86fed0.nq.gz
│   ├── 3cd1ff74127d9d95dbd87645da1bc3cc3b59475d.nq.gz
│   ├── 43e23043f7d10589de207806519862582ba02986.nq.gz
│   ├── 4421ac2f2f3bed906c91c905e77a7e4b4175e67b.nq.gz
│   ├── 4f5821be6316332a1eb4422c7eb93d67ea0090ab.nq.gz
│   ├── 59aa0f4cab56018eaba4ba51c216f9ab6b1ab948.nq.gz
│   ├── 62adf0843413deeaa14dcdbb3412b72f263b79da.nq.gz
│   ├── 6407086e4b390768f8f0927fdb110085779f407f.nq.gz
│   ├── 6a31ff05cf22a489c950414f5da2210b0d152d51.nq.gz
│   ├── 6ad7b2849870b30aed0342fc43ef1a852c7a7a9c.nq.gz
│   ├── 6cc6f5572425a56cbc039fe77f1a1edbeacebdaf.nq.gz
│   ├── 6ff853bd4d60660e824a03da27d711ad4b2c58b8.nq.gz
│   ├── 7614514e3fb935c7da437ab13be153274f321cdb.nq.gz
│   ├── 78173fa2e753d614bb0aa5ad125ddbbe70b282c4.nq.gz
│   ├── 7b4d2ad2c74d479b6bec50da4fe224a3948a178b.nq.gz
│   ├── 888c7a671dd676ea4042dc788727a3d394eed444.nq.gz
│   ├── 8f26b691616dfd5c5fffb2e6f983230230aad593.nq.gz
│   ├── a5fbabb77632743583b8cb929cf16baa7fc95c4a.nq.gz
│   ├── b56b844d0b66662478b028b1a683dccaf937f7ab.nq.gz
│   ├── c148ab8a8612d8f230be693d9182efd0d838e3b6.nq.gz
│   ├── c40c058ab00d576fd46fb87f7ed151550af13f68.nq.gz
│   ├── c9ee7daf726312d2e4a588ddecd2077b2c4ac4f2.nq.gz
│   ├── d49c41b5249f880c3f38b991b999ac6992c7488a.nq.gz
│   ├── da98ee6f784468dca4bec917c0045b01bb99cec0.nq.gz
│   ├── daa486eea1b6bed002d02b61e520a51a961aab2e.nq.gz
│   ├── e4a9715c20d33ea7efdc36eb0b821cb3699a1e70.nq.gz
│   ├── e940981b8416bdacc1ca4dd742ac8e9711d119a2.nq.gz
│   └── ff8f470f2445e8d7c3dc3a40cf8ce1e732c46d4c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── ae480398120a0e753048dcf03dfeb2f6882c15aa.nq.gz
├── filetree
│   └── ae480398120a0e753048dcf03dfeb2f6882c15aa.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 53 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[RustCrypto/sponges](https://github.com/RustCrypto/sponges)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*

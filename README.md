# Repolex Knowledge Graph of pydantic/pydantic-feedstock

RDF knowledge graph data for [pydantic/pydantic-feedstock](https://github.com/pydantic/pydantic-feedstock), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/pydantic-feedstock
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d85e815bf88f24d532f716d2e361e084eb6b21aa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d85e815bf88f24d532f716d2e361e084eb6b21aa
│           └── chunk-001.nq.gz
├── blob
│   ├── 04869bfb46862b90d6b578100acb72d1d05aed31.nq.gz
│   ├── 12de78833e1cb2c4e6b42e01cd6e292c81084d71.nq.gz
│   ├── 1973f4bf6dbc9119bc8684f7508317eb43b0ae63.nq.gz
│   ├── 1a5a655d10a13e58cb534f43130046c2832f2bf0.nq.gz
│   ├── 237e1ad0b0a8bd5f185c91c7f1b4a37ed3e05521.nq.gz
│   ├── 23bcdf6d34e0a19a99d8da2e9a4ea2ac4a26919f.nq.gz
│   ├── 26ff27fa16e0de75debba1369dbb62cf86010f97.nq.gz
│   ├── 2ec51d75f362bc4327a3cfe1c515c16bb3c57367.nq.gz
│   ├── 304d15585ae255f20cb79c39d76bd4936e13535c.nq.gz
│   ├── 3434a1665ceec7908b83d713e0d743c3b7fc4753.nq.gz
│   ├── 386b32bcc7a57432057347bd1d9c58bca82373fe.nq.gz
│   ├── 389464a94eca5de3e777fb03ef34351c48ca0fc6.nq.gz
│   ├── 3b436f6d1cc5a798e9708050426ab76a9e30db9c.nq.gz
│   ├── 3e61aa24d825174c19924637029016a835c5071f.nq.gz
│   ├── 3f4b7a794fcfde4c25659b0e8ea18ade4077cc12.nq.gz
│   ├── 45793b6ff1b881b03c9e83425dedd1f34bb67cf8.nq.gz
│   ├── 45e2c73d9fc037f888fb078d865deb5b48f0a8ac.nq.gz
│   ├── 4fae24b9302ecb2d2a4952ca24e86c3a9e1ce54e.nq.gz
│   ├── 57bc95c2421b4508cf8ec99e9b31ed7994a1990c.nq.gz
│   ├── 5f2d1a0c122b4ae50ab585f884ee4fa37f06e0a1.nq.gz
│   ├── 613671414607905b21fc4f48a0455c8c8daf0664.nq.gz
│   ├── 61df7afccca4789a384b5d3fd9077f12f9c2fc95.nq.gz
│   ├── 68151e67ce8558a3908857f8f0efcbf70090117c.nq.gz
│   ├── 6b346f505e5d415eeb91f140f75568318e6c65a1.nq.gz
│   ├── 6f9af79987c6904ed37f2a4c8341a93d58722694.nq.gz
│   ├── 736a39a09fc09f813069b6953177b54de4f5533c.nq.gz
│   ├── 74c2252a656e872c65fa18f82459cb78d1a7a09d.nq.gz
│   ├── 773b3d1257babf8fb814aee6ec5f7f6ea59935df.nq.gz
│   ├── 7ca53e01932114bd6e532710853c35d5c5b76252.nq.gz
│   ├── 7f3276384a82769429136888b86626a2fa49045a.nq.gz
│   ├── 8007cea6b1b5f01ba13202a6280d9d292f9588f6.nq.gz
│   ├── 8a59c917aa80df335f40c9ba5c97c91e416ee156.nq.gz
│   ├── 923623983b6c11c20548d2d95f3000a788fea8bb.nq.gz
│   ├── 9d56d752d3ba15f2e3a746657c62db5004b6a1bd.nq.gz
│   ├── a47316be6ae90505a64fbe303a9fdf21a056a4a4.nq.gz
│   ├── a5663845261a634c1c8e54fa4eb8235f52231849.nq.gz
│   ├── a65f471005fdad2353fb201393125a5c88663875.nq.gz
│   ├── a6b09f6b7b0e80a461ba6742cb7a09c1ab92c713.nq.gz
│   ├── b352724b07cc43263a217e7d32433f446f805d4d.nq.gz
│   ├── b3b8a7083e48ea4a81a79cc496c55e7aaf702305.nq.gz
│   ├── b98234958eca1c95bf41a5474b45228fddf2d5c0.nq.gz
│   ├── c0c864d14c12da5ee044677630ad9cc208cd570f.nq.gz
│   ├── c3b34b9a3dca6440d2f450da0ef13936a1468334.nq.gz
│   ├── c89ecb7d69f1d663169e586f55f68f1cb7875290.nq.gz
│   ├── d6f06b5c9c254e123633cc46480ad5bd2e1a0f82.nq.gz
│   ├── db42e83c67d006abc84022225bbc2b8603f5bed1.nq.gz
│   ├── dfb52ec03c4a836dc9ff0d451b73b2a1cbea8a7c.nq.gz
│   ├── e6464509422111e0971aadb964aa478b5542a159.nq.gz
│   ├── e7cf6d5fd352339e95ef4650dd348fa25d7cb527.nq.gz
│   ├── e7fbb8cb0a0b0df0c69e0c7ed20d112a2edafe25.nq.gz
│   ├── e887b8b16ebf2840cea010dcf64758597573eb50.nq.gz
│   ├── eac921035df94cdba3eeec24911da547055a5586.nq.gz
│   ├── f33b61ecc4166200d3ba0dd4022a5869f3b6b188.nq.gz
│   ├── fa7a2e93409462a03a5b871090624d6246425232.nq.gz
│   └── fb4c940fdbce63e835db4968aee8849b7914fcb4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d85e815bf88f24d532f716d2e361e084eb6b21aa.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 61 files
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

[pydantic/pydantic-feedstock](https://github.com/pydantic/pydantic-feedstock)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*

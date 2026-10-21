# Repolex Knowledge Graph of jupyter-server/pycrdt-websocket

RDF knowledge graph data for [jupyter-server/pycrdt-websocket](https://github.com/jupyter-server/pycrdt-websocket), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter-server/pycrdt-websocket
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0b9a09b0e41ede5ae94b513d53d6a30148dd209a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0b9a09b0e41ede5ae94b513d53d6a30148dd209a
│           └── chunk-001.nq.gz
├── blob
│   ├── 038c4d58befa48cb963d5c1ebf9bbf5b62cc59a9.nq.gz
│   ├── 1dbaee9b42a2743797133197148597a3cf440f63.nq.gz
│   ├── 1e51af3fff22dffb2acfe58e8e664877079cdbbb.nq.gz
│   ├── 243925edab23e71d9e7064fdeaa58716b3fb9caf.nq.gz
│   ├── 30311a9200ca53ea04d3153104aaf94e3b39c970.nq.gz
│   ├── 30f9062b91868c5a17259b283271ba8384413993.nq.gz
│   ├── 33285c5dfc555e7e13e53b15950775f6d4882bf5.nq.gz
│   ├── 3aef1ae9f2397542c0cbcb1adbe362eb0b6290b1.nq.gz
│   ├── 3e96116a84c84a9d13ca28d0ba2e68b72fa1e299.nq.gz
│   ├── 460ad0466c16a46fa90c326ce463fa5f76f832db.nq.gz
│   ├── 49f3cbfcf1baa6f40eec4232b765a86c1c099bf7.nq.gz
│   ├── 50e865d3dfc1bb41b118d29eb08350e8e71e4f7f.nq.gz
│   ├── 51cfe75edd889f3a701d046044b438e7ef174e5d.nq.gz
│   ├── 527c3ec8f1bc49014a0a9811197516f463373dc0.nq.gz
│   ├── 53ffdac49454946f372a6ccb763507bae7b43a0f.nq.gz
│   ├── 54a0fbceafaf6e4fa6a4f41cc8d14eafcbe1b182.nq.gz
│   ├── 55135e67f3e62a342bf12839a3bff8cde3679607.nq.gz
│   ├── 55fe8d1b5b01a682553c4cdf18497c5014a45db9.nq.gz
│   ├── 56fbc7dde1220f9c0a3c47edbc7fc4ab05270d8f.nq.gz
│   ├── 5934b336ba594ee3149fbe0e670f375ce52871ed.nq.gz
│   ├── 59353269341865baa5a474d89f0329dd51c4a528.nq.gz
│   ├── 612c7a5e0d17657e51018285d9850b8fa8e76174.nq.gz
│   ├── 725feab5ce652dc39f3f2c77b9fd3c90bf049c65.nq.gz
│   ├── 7322a742363eaaa42af0c2ad42feaad22b924154.nq.gz
│   ├── 8548b4ebbd6ebd9b873430a86d9b6e86da87f4ec.nq.gz
│   ├── 8d72ec195ed375385509f6812463dc51f86c7b0f.nq.gz
│   ├── 8edb2026227ecc5b78acf09ec799687281fab692.nq.gz
│   ├── 9205cf94fab6812dff6a9abe6bfd6a2db99ea06c.nq.gz
│   ├── 9326b8492dd90b277e01da1344e080835bc4d46c.nq.gz
│   ├── a61e6b92f1e8b25c40c50df9d08e59fda56f2166.nq.gz
│   ├── a92b5ce910fe4544270d81adb9c706b23e576446.nq.gz
│   ├── c22e14f7f2820725b7a45c049228968a7fe9ac60.nq.gz
│   ├── c916c1a23553e8c76e3bb9a71915f004e0eddbab.nq.gz
│   ├── cf07a600d8eb419108090b9813913afa75652ad2.nq.gz
│   ├── cfc2f785fb6648d8f83fb8bb01c7eb65110e08f3.nq.gz
│   ├── d96408b70efdb2211bcd5612a792fb0ca803352c.nq.gz
│   ├── de534343f7a8c14d52633c69d2875d9eb6da7862.nq.gz
│   ├── e004a62b7d963540583c30d1a2fec1b80b8c697d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ef4e1c9894f675ea26bb79d6657cfab4604262ad.nq.gz
│   ├── f94bc42175d5775a2a1acbfed4cf9da87b9d00d3.nq.gz
│   └── ff44ffb7b0dfc0416b6d4aa78ffb82a294b4c943.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0b9a09b0e41ede5ae94b513d53d6a30148dd209a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[jupyter-server/pycrdt-websocket](https://github.com/jupyter-server/pycrdt-websocket)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*

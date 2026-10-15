# Repolex Knowledge Graph of sphinx-contrib/httpdomain

RDF knowledge graph data for [sphinx-contrib/httpdomain](https://github.com/sphinx-contrib/httpdomain), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/httpdomain
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 32c21562d85d3accf4f06a0a88a1b24f92089ce5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 32c21562d85d3accf4f06a0a88a1b24f92089ce5
│           └── chunk-001.nq.gz
├── blob
│   ├── 092d3140d1513909e9de9efdbdd471a3648d7ef1.nq.gz
│   ├── 0f83760439c3467453527aba590c97d5efaa7ac6.nq.gz
│   ├── 0f84753f7dcd1d0a83eec8574d50057ce1a39516.nq.gz
│   ├── 14f79a258c977b95783265dd11c23aefe46e4cc2.nq.gz
│   ├── 1f376e6b531259d0ed8e13a6ea34c3de8b24883e.nq.gz
│   ├── 2075df72f61165ceaaeb31544a2c3720c577eaec.nq.gz
│   ├── 21368645b62f6d1e8b28c40f104d3398a7279297.nq.gz
│   ├── 249163b23f4d1bf6ef260400dff9244d5f81f7e1.nq.gz
│   ├── 26bb81c8ff9ea7c5b5fce7757b41fec806f875f4.nq.gz
│   ├── 3b6c1b049196b16b952b0be98f9d94e698bb22fa.nq.gz
│   ├── 3f25e43ea243f2200043748984e2905683426fc7.nq.gz
│   ├── 3fdf2656dede34ec4cffadea767f0a3357909c86.nq.gz
│   ├── 40324f0c07803e7cee598da78b5be09d9dc0d1ba.nq.gz
│   ├── 44a80c536e65e30ec4e1d72fd5b265ce4f931269.nq.gz
│   ├── 4e02c8eec44f4109b00c65b6f555f006e416ed35.nq.gz
│   ├── 5a86850a1b63e6773ccc67c830b1b80b7c362f7b.nq.gz
│   ├── 5f77ddeb4dfef9a6b1c4eb17c1fd2e11baf7b608.nq.gz
│   ├── 6265e60d3c2e7480e3ee6d483c6e590b1c140671.nq.gz
│   ├── 6a7172d6559937593da12394430e08908acd6502.nq.gz
│   ├── 723447553ad71ff3a868254367687c446169f243.nq.gz
│   ├── 77a4e0cc1a541b0d1fdd6e9fc5228372cf7c89da.nq.gz
│   ├── 8601a1c83509c42f14297cf417c20b606c98c44d.nq.gz
│   ├── 867f29c519870ed9f04fe1f95791750e640908e0.nq.gz
│   ├── 89208057cac4ba845777be39553b241485d7ef91.nq.gz
│   ├── 8d22b9dd7ef4e018310715d8fe7ca7d2e4579687.nq.gz
│   ├── 95372d4cdcc0a9a242543c7dbf24752e42013bd1.nq.gz
│   ├── 95589f23756371a59862609c48b211d8c749072e.nq.gz
│   ├── 9fcbfdeb17f019f629fe6794b87dae7ff2c92841.nq.gz
│   ├── a11aebb976b4ba400825bce3e5d1fbbd3aeace19.nq.gz
│   ├── a3bc2d4077bf43044186bf68882edc05049a5686.nq.gz
│   ├── a560d7597d33842d3c3e7a19557d43c26576c13a.nq.gz
│   ├── b05247ea2cc6919d00cfa2758a864b82dbbed7d9.nq.gz
│   ├── b0f026b450be7106e30a199e406b8d471d6656ef.nq.gz
│   ├── b19b50a5bb4071470bf6f0b5537e336e1a44f813.nq.gz
│   ├── b19d8c3c79038eac4c7301307bd993098f8803b7.nq.gz
│   ├── b2ed2a6d0a28d30784876684d131db0d71040b50.nq.gz
│   ├── b46a9dd7ef1a70bcc842ac9fe37135a8d8a005f6.nq.gz
│   ├── bbf4899285dc012ca4b32093251683b1de2b8951.nq.gz
│   ├── c5318bbcc4862cbba4dc87d51b492644578d04ca.nq.gz
│   ├── c82d28f74431c5e8531ec4d1df8aa76dd27ef188.nq.gz
│   ├── c859c90613b10f5fedef857991403393f3b6c834.nq.gz
│   ├── d8c43778e30e3e716a5113646d01cdfcabf0da17.nq.gz
│   ├── da0f5c9ffdfc06e9fcafe9f71ba391c1590e2843.nq.gz
│   ├── dcf9c9be2a1a8f986e2b9fdc17d46eddae596220.nq.gz
│   ├── df3ae0769388a131eb262d495ff071ee0adaabee.nq.gz
│   ├── e3556e06e1364c29f5a07fe38fe33d6d51f0b145.nq.gz
│   ├── efa64345b80d5091ea81de32855c206bd8013e7f.nq.gz
│   └── f2d5d808e0b36448eaf02c0457c421533c4ec3c0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 32c21562d85d3accf4f06a0a88a1b24f92089ce5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[sphinx-contrib/httpdomain](https://github.com/sphinx-contrib/httpdomain)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*

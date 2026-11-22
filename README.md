# Repolex Knowledge Graph of jaraco/jaraco.classes

RDF knowledge graph data for [jaraco/jaraco.classes](https://github.com/jaraco/jaraco.classes), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/jaraco.classes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0b64201a42adc3ee2b2a994a86f11eb0df1459c6
│   │   │   └── chunk-001.nq.gz
│   │   └── 2554beb49ae2844d6b678cbe212c3e57807c3623
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0b64201a42adc3ee2b2a994a86f11eb0df1459c6.nq.gz
│   └── repolex
│       ├── 0b64201a42adc3ee2b2a994a86f11eb0df1459c6
│       │   └── chunk-001.nq.gz
│       └── 2554beb49ae2844d6b678cbe212c3e57807c3623
│           └── chunk-001.nq.gz
├── blob
│   ├── 022a723e7e3e64762302b163b98bb37ca4132eca.nq.gz
│   ├── 14337903f06fea6ce48b6d2f40c2cf9b3a4c7a7e.nq.gz
│   ├── 1bb5a44356f00884a71ceeefd24ded6caaba2418.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 244704143acf9a134a45f1f0e9847d5e74c2bc63.nq.gz
│   ├── 27d03a003514fb42e04c14751b1e2f697e4e6319.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 2e62979336d98438b00b3182322a6846fe2c458f.nq.gz
│   ├── 3026409a41a319dadc92149a8e690d4c6cafe74c.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 35b98b1df96093e99fea65bec2187baff3c12514.nq.gz
│   ├── 4a1d7d6f0683f79a88425b2f29fe6bcedac0c254.nq.gz
│   ├── 4c39a5b139c5c24eed2c8fe1f67116ef681ad39b.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 54f99acbfac68c2be8283174ea64f1730a795e49.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 5a4a7e9166ec3143f71b5e3875860802048554f3.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 5c05f9e27d57a4b7a3c3a9fdfecf8cddb8be499f.nq.gz
│   ├── 5c8c5de390b699c4677668f063835c60d303a9b4.nq.gz
│   ├── 6fa480e44f38768722368d7a986607adacf41d99.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 70612985a7a6f8ae0e29777e7ed3df05e5a717dc.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 85dfea9d42d16274b4e8a4892bf6986d131f4241.nq.gz
│   ├── 88b838002f40a7b78128e290f5d43ecfba37dbfb.nq.gz
│   ├── 89ff33961ba3d6f9cda89322a1fdbf1ac2e35513.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── a15c74a618384538c87439bedcc6b84881f2b77c.nq.gz
│   ├── a853c5789e0cf4cfd8cf680110f4c3fcd39f04be.nq.gz
│   ├── b6f972769e61a5e65f9f45015b363cc362487e55.nq.gz
│   ├── bc61923b5760b4ea828f3ea3139405ba57565bd8.nq.gz
│   ├── bfcf7cadc9df40d255f9910e31bf402c34f8057d.nq.gz
│   ├── c68e88b58aa1927d0e2d2002a25dd852c61b9819.nq.gz
│   ├── ce79ee2946d8c015fc589272986b7e8a76d5cc86.nq.gz
│   ├── e05a3d4a2ab888e32952006d8cd380864368db5f.nq.gz
│   ├── e3c74a85327aa18173df0767b7700d89fa6b6bbb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── efcb8cbc2043faa7caf4f92fc7488bd6914c934c.nq.gz
│   └── f527cad9b433c8b142eb86d5fc2642f8e7c9bd80.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 0b64201a42adc3ee2b2a994a86f11eb0df1459c6.nq.gz
├── filetree
│   ├── 0b64201a42adc3ee2b2a994a86f11eb0df1459c6.nq.gz
│   └── 2554beb49ae2844d6b678cbe212c3e57807c3623.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 54 files
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

[jaraco/jaraco.classes](https://github.com/jaraco/jaraco.classes)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*

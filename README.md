# Repolex Knowledge Graph of scikit-hep/fastjet

RDF knowledge graph data for [scikit-hep/fastjet](https://github.com/scikit-hep/fastjet), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-hep/fastjet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 46100f9b29031869b034d46ad246ee72d8a979bb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 46100f9b29031869b034d46ad246ee72d8a979bb
│           └── chunk-001.nq.gz
├── blob
│   ├── 0208447b3b36df95748aa8c2daa48fa2e1461d55.nq.gz
│   ├── 153090b6f7a50b45cfb2c56d09009a581e8b8d1c.nq.gz
│   ├── 15a2909ac1d83356ee27774616df690dafcce884.nq.gz
│   ├── 182f883b08bce9f5d658ab1c2486fcc82ae746d7.nq.gz
│   ├── 1e263e445afe2a753d08f1c404ef81c94cbbcf54.nq.gz
│   ├── 21b0f07e1b6d6fe659044413c758df4c123fe90f.nq.gz
│   ├── 288ed391a7d4efc57f0d8cab56320c0cfa515fc0.nq.gz
│   ├── 30e6eb1b25682d2adedd8ef504234979e049eec9.nq.gz
│   ├── 352a6df5adde6ec10fb54efdd2066a1e35579e50.nq.gz
│   ├── 3942fded2cb7cba23fb0dbd6d8c7baed311cb41b.nq.gz
│   ├── 39ec24e01c32f85adc3dd15f2206c784f359949f.nq.gz
│   ├── 3d64bb3aae36285fa01dc8cd9a00595d58094920.nq.gz
│   ├── 3f326a08e8e402ea0aeeb0e05cde06342e6efede.nq.gz
│   ├── 43e2735f15af0904cd3f2bc54370de351d5d406e.nq.gz
│   ├── 4aafc80ad4c1595aaddc20ccc75b4e0dfe8e9271.nq.gz
│   ├── 4cb8921af83e5b624935e677b9d3643c737568c6.nq.gz
│   ├── 4f787575cafd41ec86fa610a8c41a62da13557a5.nq.gz
│   ├── 560f9faa6736cbb5bd34d2586a17efb3f7e7f74d.nq.gz
│   ├── 565345f95a6e2529b01463aa243899879dc682c7.nq.gz
│   ├── 596439befc432fd3ac5bce31b2b415472c62f95c.nq.gz
│   ├── 59c72ee869ab66715b8954b8f1a9af2f4022c30e.nq.gz
│   ├── 603d2da9d263a325feaadc8121aa908dddc5a9f9.nq.gz
│   ├── 62dfc8b0c34f1287c3ecc8fdb5b38c30a3b0f8da.nq.gz
│   ├── 661967c48a3c72810aa6b89324c7eb8cfda5d499.nq.gz
│   ├── 6738f16cf62fcfd78cd83c31ad87094af994fb09.nq.gz
│   ├── 6c4b369539355a7bc893f1aa7b0509fd09ecdc2a.nq.gz
│   ├── 78f5e8e03af9426b740a282e2b9a12839a2579bf.nq.gz
│   ├── 7c50a88adccb7c728a417648de47cde02da1e05b.nq.gz
│   ├── 7e0a3b60fc57712831f253caccd303038a764406.nq.gz
│   ├── 800e1e9a8d37e106830dbb86464d53d59cb238c5.nq.gz
│   ├── 9ea6891e334a8dd15d2911fb8755b1b21c34d803.nq.gz
│   ├── a6a3f786066c7689b16de88701281f1602e91a95.nq.gz
│   ├── a7f2ddbadcd3d35de99b00469266af6eb244fd5a.nq.gz
│   ├── b2ffb2d7ae8bc922c16604ada88c7b5579c76c8b.nq.gz
│   ├── c3d1c0d144091b42b0b32a08e1343ff127fe176d.nq.gz
│   ├── cd2531cb9909ceafa5b16c9372dbff289e819f5e.nq.gz
│   ├── d2b284a607a6f39cab81df492ac292308ca5a9f0.nq.gz
│   ├── d983d22e5a8777773c3a8e37ccc78857e72431d8.nq.gz
│   ├── debbd7f6117e2b467317b4d83a9e1ebf3d1eabdd.nq.gz
│   ├── e108db73ffed79d3ba8fb91a95e3207ec434be7c.nq.gz
│   ├── e5de6014e22b84ae1ddcae85ccfb17ddd635247d.nq.gz
│   ├── e7a36a13592f6662d5092395b88aa1b9656e81bd.nq.gz
│   ├── eb15b787036f4090601985b6d4e76be34aab13bf.nq.gz
│   ├── ed88099027f775942fa65dce2314f1ae9675cb36.nq.gz
│   ├── f8801d990c8b36b858cc6f85235d7c9aa69df856.nq.gz
│   └── f96edeec7d944512e89f3cccc5e390617aa6b929.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 46100f9b29031869b034d46ad246ee72d8a979bb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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

[scikit-hep/fastjet](https://github.com/scikit-hep/fastjet)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*

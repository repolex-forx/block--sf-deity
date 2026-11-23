# Repolex Knowledge Graph of block/sf-deity

RDF knowledge graph data for [block/sf-deity](https://github.com/block/sf-deity), parsed by [repolex](https://repolex.ai).

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
rlex download block/sf-deity
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bd2375174c9296c0836e93b37d5dce8111c5b335
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── bd2375174c9296c0836e93b37d5dce8111c5b335.nq.gz
│   └── repolex
│       └── bd2375174c9296c0836e93b37d5dce8111c5b335
│           └── chunk-001.nq.gz
├── blob
│   ├── 05aebd07ba8c49dfb7e310de4ec07d5f449b93f3.nq.gz
│   ├── 0e70b5290bd569ea1c5aa4aa5656ba765649e17f.nq.gz
│   ├── 10495f6724b4caeb6dfc96065f7265d7e2a39d4e.nq.gz
│   ├── 1434e0ad3b6f7d425e0b97781e511e8c7ecc6802.nq.gz
│   ├── 15d3d0e26f833283e78f3db5a6c03dd45bfe3e0d.nq.gz
│   ├── 18039a0313fc5a3e49507b2ebdae5658e1661583.nq.gz
│   ├── 1a530780beec0f99825ec3000beb656c79a3220f.nq.gz
│   ├── 1b3086911ca5661bc3346790642f21b799533f6e.nq.gz
│   ├── 1ba4bc9ac30a3520f90e9d2c48242acc098689c0.nq.gz
│   ├── 1be93256f337321582b32f21e059d7580dcdb1ec.nq.gz
│   ├── 224c9eb2a42967be3ecc5b6afe3e2ac35a0a937f.nq.gz
│   ├── 24a2378ac39080809b45b4ae41318627dd5a8e13.nq.gz
│   ├── 267ab93572596e00c433ef8a798efb9bbdb9073d.nq.gz
│   ├── 2b1d66e751b7a71ee90400022ba41e540d2f9983.nq.gz
│   ├── 2b4033e5495192c9f01dc0722253774bc077b0a5.nq.gz
│   ├── 37ca68b49fe7433de1738887036eafbb483806b3.nq.gz
│   ├── 3db443f03b6a07083b9f2c629d2517b2b9cd5c82.nq.gz
│   ├── 41bda3ed5303e2123c7de5f1b17f739004235bad.nq.gz
│   ├── 4a11e76b2da2682470a2ea70ca9f6a292b65ebd3.nq.gz
│   ├── 5a3e207bb981ceb209fbf13d107a0289f3e7169c.nq.gz
│   ├── 5f399c3cc6e650a4aedbcb4b9297c38833b0b368.nq.gz
│   ├── 6db49fb889a2a6310a89a34aca2275e462834bbb.nq.gz
│   ├── 7a51829787a42b34e6c3d5927ac279f8b9a89b72.nq.gz
│   ├── 7b5b5a71fd205e8a69b154d4f505c7179f7d6a14.nq.gz
│   ├── 7c02ade4994b9f8568e6f3775d8803768fa61b45.nq.gz
│   ├── 7db1734f313dca8295651f373079b0a635e4e21e.nq.gz
│   ├── 7fc5b99b8645fc51954a962741e1cd27b532c4f4.nq.gz
│   ├── 824382ae2edb352e866ddd6328144acc9e6104ba.nq.gz
│   ├── 835ede48396e10677fa1676f37a38016530304c8.nq.gz
│   ├── 85f01f5f98c412dc73200e46c91f4adf09936de5.nq.gz
│   ├── 8c9a948ae862f96412418719a7cf148bf13058d5.nq.gz
│   ├── 8cccc6e59a95e5c8a7fdb22877915f61279aa87c.nq.gz
│   ├── 8ebba11f17e469fdf83ddacb8b3dac6e4edaba24.nq.gz
│   ├── 98455d2a4e601af0e543ebed4e65220e47376cad.nq.gz
│   ├── 9c6ba0a2e9c9d32025970cd4db8c2a38373d0869.nq.gz
│   ├── 9ceed0f2d8aa39ef6c7a376624f735c2698f0a1c.nq.gz
│   ├── 9d63ee93f31549fab575eec35592243055ab9122.nq.gz
│   ├── a60284e4b6a7bfc0efc76d71a325516bbde45bb8.nq.gz
│   ├── b041fc1a8b19adaad74d59439a697504714bbf78.nq.gz
│   ├── b7af761bcfd2a1d85dd6244aad72aaa5a7c44948.nq.gz
│   ├── c7ac7f74e22987e1e0d090b7c6954b4d48e29053.nq.gz
│   ├── cff9cc9435af5256374556c7283d56be4fc8f3ae.nq.gz
│   ├── d2f2c21da34f6e17afc94a7bcb646acd68d993fb.nq.gz
│   ├── df50c5a0cb6692ba86a1fed6712ef31b5ec12fde.nq.gz
│   ├── e722ce30e11b2464942e013d77576c639c659ce5.nq.gz
│   ├── e74c0aefa46fe492d51b94b4c6d8ffe3bf680eb0.nq.gz
│   ├── efd8fd742c24ad5b801a18858054d2fc6f6ecd5a.nq.gz
│   ├── f05debbcfd0f1c6384fa2d2d5e6534acf6dac7e3.nq.gz
│   ├── f5a9fed2b5d4dc9e853edf0cffa44ead7dbb4066.nq.gz
│   ├── fa67dc18714253d9e1145b105e4e07a0d11c1017.nq.gz
│   ├── fbbcc255b8c4a6ec6ed8d4393f85af763ada977a.nq.gz
│   └── fd0ba4ca472186e7effa3bb6a0bf2d140b8a2572.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── bd2375174c9296c0836e93b37d5dce8111c5b335.nq.gz
├── filetree
│   └── bd2375174c9296c0836e93b37d5dce8111c5b335.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 61 files
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

[block/sf-deity](https://github.com/block/sf-deity)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*

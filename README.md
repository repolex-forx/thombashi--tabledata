# Repolex Knowledge Graph of thombashi/tabledata

RDF knowledge graph data for [thombashi/tabledata](https://github.com/thombashi/tabledata), parsed by [repolex](https://repolex.ai).

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
rlex download thombashi/tabledata
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 09e26a968af42a404e0b86b21596922b774f8942
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 09e26a968af42a404e0b86b21596922b774f8942
│           └── chunk-001.nq.gz
├── blob
│   ├── 01984eb5b7fece557882f5047cb44a2416ee3d41.nq.gz
│   ├── 0bc06a7daa13fe601a2b4166205a5f368b688490.nq.gz
│   ├── 10b045545160bfc7ed4bb88392b46be73ea7f672.nq.gz
│   ├── 1a5680e10891148b31b592c2f6b0285859bc69d8.nq.gz
│   ├── 1b457e08f3069fd15ab882c2dec1f1c5a7e0109c.nq.gz
│   ├── 1de427a45ad4986de92d71eea6a657aceb095766.nq.gz
│   ├── 2bca03cbc169a263d898d206ec33e221bef317b1.nq.gz
│   ├── 35084f8b1af8fa41a12f4fcaf5f0710771019f41.nq.gz
│   ├── 36f656c55db165565132af09688b90066c97ccbf.nq.gz
│   ├── 42246b91ea066d8fbb1fae4ea9bcfee77ea0d4f9.nq.gz
│   ├── 4891489e38c78a19fffbde8dfc1d208b03014ef9.nq.gz
│   ├── 4e4f84b6c29037306cdb56e03e6c0172ed95719c.nq.gz
│   ├── 5579234929041cc9969d12f02fdafe872075bcf4.nq.gz
│   ├── 57d813626fc1a43f4f7aac61a7d41de592ac723e.nq.gz
│   ├── 67ed3466d974a9535f889ed34e77197a0bceb378.nq.gz
│   ├── 67f8939fdd2388cdf51aa53861884a9bb337c862.nq.gz
│   ├── 68a6540eed988a03f6699a17954baf9ab0a63431.nq.gz
│   ├── 6bb9f4e6086798244a6282999bf3c5a6219a5070.nq.gz
│   ├── 7026f9de319105345e329324f4f436a3cdd4d6ee.nq.gz
│   ├── 722f1372ff8416da2a9c5733c11d8351e87c792f.nq.gz
│   ├── 72ed62d30e5c3b52f63745565663e1b3fff96ca6.nq.gz
│   ├── 83ddb0b721bd57569997f3c1bc4f7e1531a23e45.nq.gz
│   ├── 85ccae11533f034324084579a602c6dc6e7bfcb1.nq.gz
│   ├── 8834cb1297343bfd9b2305171cd611fa274e19c9.nq.gz
│   ├── 944e9474385d5ac4cace526f532564308a1fd13a.nq.gz
│   ├── 990ae65bb98073d04936bb9651259fc6cc19563e.nq.gz
│   ├── 990daee7c70ae62f04615a6c67047c81b97dd716.nq.gz
│   ├── 99978649c806dc01fc8c6c520af57888fd0341bc.nq.gz
│   ├── a3e07b4b5c9340bf9119b83eda9bc479654f8eef.nq.gz
│   ├── a4c7796facdd54a093506d320b9c32b41a2ddfbc.nq.gz
│   ├── a5d39f50d703c59ef0069d7553f36b37e0425188.nq.gz
│   ├── a8032d0e7037d8e46f367bb37eeca3c6273fb3b3.nq.gz
│   ├── a9ae08f641f3f9e26a2c3087e8d0fb76ddf0e28d.nq.gz
│   ├── aa0fc6697e9859b0709b6fb7f23b177b5634317e.nq.gz
│   ├── afb7e5b941347141f2edf35242201be233e612e7.nq.gz
│   ├── b086f6c8d9092948db9cfd5a39c46d76013b83c3.nq.gz
│   ├── c2f52cb6ed2deb84e5cf09ac59bd6797c9680ea7.nq.gz
│   ├── c4d2db8e93d4b94075158b1f0446dc4749aed59f.nq.gz
│   ├── cbac6e0785586aa0ff39e8452ce9ca2570d307ed.nq.gz
│   ├── cff918ea8b20ca5bd94ca17e77f3c967a5f9db0e.nq.gz
│   ├── d166c90c9ec1415cdbe7962afba1ed4dde33c538.nq.gz
│   ├── d393e4239a70d6d37b6ac2c5e6bf66287300a3e3.nq.gz
│   ├── d74f1c3b96908dbbf958ff971b4f26e061b31c50.nq.gz
│   ├── e0d9aa47b467a6d8c589d7418a98df3fcbc35e4f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f08c68a65e967b9aa34c701a06cb12906d568f55.nq.gz
│   ├── f5134f2d91376e21ccd40c398c39b47008aaf0da.nq.gz
│   ├── f60c2a09ec0f90882f78b147f74a3133e80d67dc.nq.gz
│   └── f8bb95d14f9c54108c2a7afffb8a1528e7ff3ff9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 09e26a968af42a404e0b86b21596922b774f8942.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 56 files
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

[thombashi/tabledata](https://github.com/thombashi/tabledata)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*

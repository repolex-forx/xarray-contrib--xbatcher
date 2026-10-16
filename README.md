# Repolex Knowledge Graph of xarray-contrib/xbatcher

RDF knowledge graph data for [xarray-contrib/xbatcher](https://github.com/xarray-contrib/xbatcher), parsed by [repolex](https://repolex.ai).

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
rlex download xarray-contrib/xbatcher
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5513cc1872d5147012741b1c27dfc7a0b75ddae8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5513cc1872d5147012741b1c27dfc7a0b75ddae8
│           └── chunk-001.nq.gz
├── blob
│   ├── 00f35495bbc948612dadeab5d5cc2c30526ac072.nq.gz
│   ├── 04a100adc70177b9d2519f883a4cde03c1bd07e7.nq.gz
│   ├── 08c1d034e20700350851eebcd75c93902a2d9ac9.nq.gz
│   ├── 096d777edcba8344c086961c75c20fc174dad106.nq.gz
│   ├── 15afb7f1e38bea95c6b6e77896e3a2fcd673a78d.nq.gz
│   ├── 166648c6351730ba4d5283972624b79d06497e72.nq.gz
│   ├── 1d14a7c74ec1331b34ff8fae965540cf339be247.nq.gz
│   ├── 20cd90dc797d56a0556e9e0fa4b8caed608f694e.nq.gz
│   ├── 219d5929da4952ea7a40ec04fe0886427cc8c5cf.nq.gz
│   ├── 242f59d170134f6f9d6758e842f99916f0a3f60b.nq.gz
│   ├── 2616ab3422e3ed3925ae5e3dd666bfc4bb5339c5.nq.gz
│   ├── 26fea1f9f3b9e99754f56921ac1b2f3dddecf892.nq.gz
│   ├── 27e1c3770c636daf48edb90f8466bcc8621ec617.nq.gz
│   ├── 2aef87c07376d2828ad58ecfbf521faeb9593f68.nq.gz
│   ├── 2fcf77be1a5e9132bd48688856cfc15052c36f93.nq.gz
│   ├── 3013bc290772b5b4cdcca899fb11a4d9fb656070.nq.gz
│   ├── 401bdcbfadd5dcdad38aa1d890f3884749cd4114.nq.gz
│   ├── 489e90aa7d85d548d8d47c7a17f8f3ddbf360ab4.nq.gz
│   ├── 4ab24e16fbc2893ca5b4c86ac1653acd03287251.nq.gz
│   ├── 4c93ac05147374d42d7ed01c5635b1d67dadf482.nq.gz
│   ├── 4e41d0ee0280cfa1211c806072cf2c642332da7c.nq.gz
│   ├── 5184a0caa3c1a165235a8038c315661b2a21c833.nq.gz
│   ├── 5e3d4a4fe2c80950bf64a4399da8b1126bc3301a.nq.gz
│   ├── 612699ab0902c44c2cc14318fe299b5ea01d2b7c.nq.gz
│   ├── 6591852699de8b7e06b13cccd1c43cb7f5fbb3d7.nq.gz
│   ├── 76e5b3c4e09860475aa18dadea64b177e5020179.nq.gz
│   ├── 813f5855f84a411c60b2005e07e7f970fe532e46.nq.gz
│   ├── 8453f6ef96fec6cb9d2460050bc8b4367648a0e8.nq.gz
│   ├── 86dfb409bed33925e344e895645551748ecd396a.nq.gz
│   ├── 8bc7ad2e3d269b1cb65243472772b3a2a21c389e.nq.gz
│   ├── 8d37c5144233360b0edd9a52fd8f06e534c1e8f9.nq.gz
│   ├── 8e061f8e9ba2bb207a1b7d618212034cf9db5cf7.nq.gz
│   ├── 93fe7c01f404d9f7ed100a6cee64a224a7c8c199.nq.gz
│   ├── 9cb79e32c7abaadc9889a72f75eef1a085ded223.nq.gz
│   ├── 9d7ecad27ded2c32caeeb30c71add94bc8f54a45.nq.gz
│   ├── a12137611b7defd790ffe7e745e4ef5f51a8928e.nq.gz
│   ├── a5ac85a7f40bb8c2b868540a3f7964b2846d9ba6.nq.gz
│   ├── a98f6d90c45ec398d1ba85962d2557cb89bdb59c.nq.gz
│   ├── ac4e753a8401363b1c258f103813cf4172a2f3c5.nq.gz
│   ├── acc08d349d3cf9be6198c67b52194da5ec78f916.nq.gz
│   ├── bbdc6dd6440d9b2eee0af1e6b7695c80e54381cd.nq.gz
│   ├── bfb7d8c60194516c61cc3c2740ed12cfa292f213.nq.gz
│   ├── c7c6a3b613262cefc3a374169bc5ba07a93e559a.nq.gz
│   ├── c9d93585decdf24e1887a27b5477f8a121a374ee.nq.gz
│   ├── cf7b6eda3e3f7103e0941a0e6986bc8ffb9659aa.nq.gz
│   ├── dadfdb63f01c699f305db5d43dc230ed1c83bddf.nq.gz
│   ├── db2b9685767a95d5fb8bfd3c047543e198bb87e4.nq.gz
│   ├── e05b60bd1bc5304000f690013cd9fb32b13b9fd2.nq.gz
│   ├── e22195bf6ebed6679cafd77ef88facb3db9872e4.nq.gz
│   ├── e30c30a836c05e37fb1240dd51c138e2a0d8fb33.nq.gz
│   ├── e44c62aa1ce0aca57f72e55a5fad52fa0ae12beb.nq.gz
│   ├── e5429d750702025a72e58e0771cb8645823708c1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ef08b1381b1764d11b3ef0e275117aba56d0faf5.nq.gz
│   ├── f05cac11bd4e219f97b031e592b442951aaef8bc.nq.gz
│   ├── f18bb7ecde43695167b8bd995fd850cd38fa9224.nq.gz
│   ├── f4259cd206477082826f2aa7991a708d0ae191aa.nq.gz
│   └── fab6584d5b9de3b81f4a34b8f74ded345efecb0a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5513cc1872d5147012741b1c27dfc7a0b75ddae8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 66 files
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

[xarray-contrib/xbatcher](https://github.com/xarray-contrib/xbatcher)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*

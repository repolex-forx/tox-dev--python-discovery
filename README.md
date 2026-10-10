# Repolex Knowledge Graph of tox-dev/python-discovery

RDF knowledge graph data for [tox-dev/python-discovery](https://github.com/tox-dev/python-discovery), parsed by [repolex](https://repolex.ai).

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
rlex download tox-dev/python-discovery
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4fe2ade736e5191de42ca3d4a0b8bf672ffc5652
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4fe2ade736e5191de42ca3d4a0b8bf672ffc5652
│           └── chunk-001.nq.gz
├── blob
│   ├── 01e7d12c7ea87b4498f37693f0b82264a69e25e6.nq.gz
│   ├── 0e2e996f9ace01513675042a56702d9d9f299498.nq.gz
│   ├── 1dedfb6283ccada73691022bd2fc25921b70d39c.nq.gz
│   ├── 21e19fc7201f2c5d71de7777297c06d0c5ef4eba.nq.gz
│   ├── 220f93d375a19bb70914391ab389759183167d01.nq.gz
│   ├── 2250f0760d7f1fdf7286e22a39c9d2b891d793b7.nq.gz
│   ├── 2607631ab9d7a3e7c59e586f0e6acad4528d04f6.nq.gz
│   ├── 29b0b0548ff39587e0448cb781e0730345348855.nq.gz
│   ├── 2c17fd3e575648ea1b54ba4d0d350144a61ff516.nq.gz
│   ├── 364982344fbd94d55705e1f27a9a87abaa255333.nq.gz
│   ├── 3c350a922953585657a410294a5424da925171ca.nq.gz
│   ├── 3df81485c8c3e2a1ad30e8f9316d7d54df101c68.nq.gz
│   ├── 453338666d25b522475c25afbfa25d57d66d8bb2.nq.gz
│   ├── 4995b861a44925f695c3f29c0b5b06a8ec6cbe6d.nq.gz
│   ├── 51c13da36c98625fb6a1d677e4e2c4ea6967794d.nq.gz
│   ├── 5385ceaf726d4d6493486a0699e23d0ae1482af9.nq.gz
│   ├── 59b7d3da7697b960e49714bd2aebed9690cef414.nq.gz
│   ├── 5bde25e20593b817aaba3d54bf04ea4bb3b0a03a.nq.gz
│   ├── 5d06b8a93d383a1022488ab9c7676add6353db75.nq.gz
│   ├── 5d332d5877d8d0fe98791b75f23cb6846533f9ca.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 6091452deafce69388906085b95322850527fe30.nq.gz
│   ├── 61a82f662bd59bb31407b7ad87badb6a686deef9.nq.gz
│   ├── 643157ac96cad759ee79877c82a05b05d7ab2884.nq.gz
│   ├── 69d0cfd202c019ca1d5a92d59faf9a1380c61930.nq.gz
│   ├── 6b9ff3331d6bf6529126cb00ff784c1c0fbfc213.nq.gz
│   ├── 6bd41c084ad63b41bc00e174598ebb8eb2200251.nq.gz
│   ├── 712fc49d8be097b9723f15eb2bacbfd7a609db8e.nq.gz
│   ├── 78748e14a18ca7abd90f6b2d387b39414332f1ca.nq.gz
│   ├── 78893fa94eb750e6390051a51cd091c069b70465.nq.gz
│   ├── 826adc2e3c8c5e8cd016c31eddba59b82ac0c6f3.nq.gz
│   ├── 8b504da8ccf36255c90c4c7d35efb15283c3f9c5.nq.gz
│   ├── 8cf42486cdaf62d3868a8545533113937f7f46ec.nq.gz
│   ├── 90a7601ed5ef53b4d661f087262948e3dba5fb69.nq.gz
│   ├── 9306ae9de5d939ea99852e8402f9be3abfce19a6.nq.gz
│   ├── 996bb7e2537336b8e7c5be65c460978e20d72ed9.nq.gz
│   ├── 9c0a21baedd87e5088b7cab9b03874ad16d04834.nq.gz
│   ├── 9d2fbc1b9372bef9068c8e0be527c61a5cc3630c.nq.gz
│   ├── a61aeddfab6351d967c3176c8cfdd1498be14fad.nq.gz
│   ├── a7287234c05493b0e636617a91c9f9390c1d71ce.nq.gz
│   ├── ad7df4f577b9492f517377c567f7b0170fbb1dc8.nq.gz
│   ├── adfa2e39db6590e259ff1e1d9a2087a489c19b1b.nq.gz
│   ├── ae419c100b25005bd082785a7709b42a9e0300ba.nq.gz
│   ├── b4d22887fa24caed8c1a7b664a471a547c5942d1.nq.gz
│   ├── c348b71020af482eef6a0b8a5d6a725c2a2926bd.nq.gz
│   ├── ca8bcc1853d9a414f5477ae44fd7d189a05a5f60.nq.gz
│   ├── ceea4da494e4c1cabb0a93343043988618a0434c.nq.gz
│   ├── cfc2b948c4d0a4b92cefef41e545f83ff2dfb00a.nq.gz
│   ├── d2f2eac278f8e6199b473531af059e3dc248c6ff.nq.gz
│   ├── d389ad6e17bdc715f6c22dd84bbebc4767cf3c93.nq.gz
│   ├── d4e6b1f5e1b4b640491a7be9d43f595c257df4c8.nq.gz
│   ├── d9e8f5add771ed68c6c510e7137c3ce5a320d1f1.nq.gz
│   ├── e104865cf9860408e9fd433bdc950e0d0d2ef3f8.nq.gz
│   ├── e218180d14a19a41e39f718514ae6715defb84dc.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eae856534238e5a8a4a314f3e5ef3a43632680fd.nq.gz
│   ├── ec06108afdd2e23a3dca90f335caeecec4bfe208.nq.gz
│   ├── ee7c847fc3d9eb61e20f7cf2741a638581300824.nq.gz
│   ├── f2e1419c92311c24ccfdf246c4d0f7ab904eb735.nq.gz
│   ├── f55b08929c2b763ffb16a4407ce590b7b5eeecba.nq.gz
│   ├── f868b11260c438b93f4bae20bafddccc1b008a35.nq.gz
│   └── ff278a85a525533f49afb9b24f237fd2abbe3610.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4fe2ade736e5191de42ca3d4a0b8bf672ffc5652.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[tox-dev/python-discovery](https://github.com/tox-dev/python-discovery)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*

# Repolex Knowledge Graph of UKPLab/emnlp2026-reground

RDF knowledge graph data for [UKPLab/emnlp2026-reground](https://github.com/UKPLab/emnlp2026-reground), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/emnlp2026-reground
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 36c2942f48a4d00149d7917fb7e4bf2917efee48
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 36c2942f48a4d00149d7917fb7e4bf2917efee48
│           └── chunk-001.nq.gz
├── blob
│   ├── 082c1051cb2519c2174b07c7f4f0b6e816de0332.nq.gz
│   ├── 096b93010945f133f9993461ff4f3838ddf61ce0.nq.gz
│   ├── 120012cceade66e0eec3a11d89d7b6bda897a14f.nq.gz
│   ├── 1a6920bbdb70818464ecd23414e1166e971f44ce.nq.gz
│   ├── 1c983731c05405e2679853646c5e46e147cf2035.nq.gz
│   ├── 1cc3a30c996bac1c57871a380bb71e581556207a.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2a7f6502c9954d27dd6806f1e1ae8d357f63c45b.nq.gz
│   ├── 2f9c4b9027436831efd1682f653e51a23e5cef81.nq.gz
│   ├── 2ff99af462240e534278483610ca29643be43255.nq.gz
│   ├── 36ea1098a1145b29709424c58e395d68e6f02cf5.nq.gz
│   ├── 383303d52756f3d9ddac1ebf6828479c5ca14139.nq.gz
│   ├── 3b52c5681f8ce39dc8cbe7bddd8e786f8f0271e9.nq.gz
│   ├── 470d10c549009619a8b9729122d0e08d51b0a78e.nq.gz
│   ├── 517b5c908be03c67117f3db69e972a071add50ad.nq.gz
│   ├── 550701538d98e6ba31e3c2039bfd87da5054c785.nq.gz
│   ├── 582a9c57e015311b4883902c37b675b77a222b0c.nq.gz
│   ├── 6834ee78cbed183635e300263c80cb65d5f2afbc.nq.gz
│   ├── 6adbf2149ecaa6caf9cbd05e48a87d0f0412a018.nq.gz
│   ├── 70161d7660a8df3341d9f4b624a91841a8dbd064.nq.gz
│   ├── 72b90a6e91ae8876bc50f441b304680769ebed48.nq.gz
│   ├── 73c2b77087e774fef4d54a8ad838b0304176a392.nq.gz
│   ├── 7caee68588f2214ad2b18a8210ce24a5f29ee94c.nq.gz
│   ├── 7d69d33bbffa266b84e376982226c452bbbe5895.nq.gz
│   ├── 7fae7113a9f9b18bb84a568962d6584130474478.nq.gz
│   ├── 86d62b3b56eb1a3a1cb1d8422d740bfc21186cc8.nq.gz
│   ├── 899d841de62cdcae83ed2e95002d96c3323f09fe.nq.gz
│   ├── 8ac09ed578049e04f2cb718475ec12e8d5f56256.nq.gz
│   ├── 913172af35cea5ef633aac3b5710f212e2a91cf1.nq.gz
│   ├── 9517935cb1fa2590aa6d1fc06ad623ca958ecc3d.nq.gz
│   ├── 968f85d68c79a61539a491a77886e07857cd4517.nq.gz
│   ├── 9b84f687e2f571a83f36ff3cd126dac89956ab10.nq.gz
│   ├── a55b0ae99939da06e6133d4935f7cb1adf8842b5.nq.gz
│   ├── b2aa828bb8559dc6dfc8b875eace33e7b9c4d703.nq.gz
│   ├── bca2788665f1cd4bfe6f7008ae18a5df5f60e81b.nq.gz
│   ├── bd116a674f2e2b37e156f84320182d1e3f4ce781.nq.gz
│   ├── c0f2b2cffe79f243c2daeb053be8513b80b750a3.nq.gz
│   ├── c1a1e8ac2ab7a8ae91c978d6f178707d0432bff1.nq.gz
│   ├── c81e1ac24791ab7671799594e46835d2b10da593.nq.gz
│   ├── cbb74007a09e50f48c337e9a2224515517457915.nq.gz
│   ├── d6a82b6b7c024ea18cb170ec9f0765a521cb5251.nq.gz
│   ├── db545bf18fb7e87067b75505ebe8c2292aaa427c.nq.gz
│   ├── dbcc2ec42cf619ba411b06ee76272f7bbf877ad3.nq.gz
│   ├── df6d490d0863adec9a090cc4e0ab3724c973f5c2.nq.gz
│   ├── dfca654c41fa58f0ce392e79bb061e64e9f67103.nq.gz
│   ├── e0ea67eafaeac051b59273e07f23c06941758322.nq.gz
│   ├── e1dbc52b24f678bb3bc630c87fc7881fdab956e5.nq.gz
│   ├── e24656034e4757bb21b0deacee3b0b8c8f41b9ca.nq.gz
│   ├── e54a9eb275b041f49520146f1ae1e74c2196a150.nq.gz
│   └── fec72d41c3d8ea06551ee90c0e44a1dd13a0b93f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 36c2942f48a4d00149d7917fb7e4bf2917efee48.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 57 files
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

[UKPLab/emnlp2026-reground](https://github.com/UKPLab/emnlp2026-reground)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*

# Repolex Knowledge Graph of coleifer/sqlcipher3

RDF knowledge graph data for [coleifer/sqlcipher3](https://github.com/coleifer/sqlcipher3), parsed by [repolex](https://repolex.ai).

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
rlex download coleifer/sqlcipher3
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e0fad03cbe0a6f4e0960c2f3b676f5e0533fc09e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e0fad03cbe0a6f4e0960c2f3b676f5e0533fc09e
│           └── chunk-001.nq.gz
├── blob
│   ├── 038f83add7eea3caafdad9f76520f8ed89d2edd1.nq.gz
│   ├── 0699b96656a31caa32f4ef5117f4eb42e0057c99.nq.gz
│   ├── 0c4710b82662fa514e25088ab7cc1257bd31df8a.nq.gz
│   ├── 10ccaee465baaed4bc9e0d6199c2a6ac660fdf8e.nq.gz
│   ├── 111cea231b59cefdda6369698cdd3069032798e6.nq.gz
│   ├── 143bc12b743459c84a2567d8e93bf726eb5af46c.nq.gz
│   ├── 17014989f9494d0e90cfab0dcb74f61e39325844.nq.gz
│   ├── 1a8a8730199b4db25b8c3906ec141f4b4b204d50.nq.gz
│   ├── 2abcaab126a39f70a02cf87034d16d63ad5a49f3.nq.gz
│   ├── 2eced679254221e8dde91418147ae073b6085aa3.nq.gz
│   ├── 2fe0eff953506e6618606bb57d067391abdd0883.nq.gz
│   ├── 3998a55e51cafeed4cf947b22e19fba5e82f9bd9.nq.gz
│   ├── 3ee9be679ebc65e92d27bada6b3418e490e2878e.nq.gz
│   ├── 4a20e756f7829d9a9a0b210cac9c9f72da5bbc4b.nq.gz
│   ├── 4ad506f8dd968731f28d44808fa182f5078545d6.nq.gz
│   ├── 529010967c4f3a99c8a4a11a2b993f9bdcae8196.nq.gz
│   ├── 5418c2b98fd7519dd235f40d146a2a0069f6281e.nq.gz
│   ├── 59bcaa9b8344c1ae6537c33d829edede48d87ab9.nq.gz
│   ├── 5c2f9a6739406e581ee7d6b5e2d2cbd7f5255641.nq.gz
│   ├── 5d1e4dd560b78db4754b8bff44fff5c5254a749e.nq.gz
│   ├── 69a8ac84b283c08107aa3de16e17e23d7434132a.nq.gz
│   ├── 6f2f7c631141fa5911cc8aad73af48681f72a5c0.nq.gz
│   ├── 783622a0518ab6053516b9eb8537518d373b3157.nq.gz
│   ├── 7cdbff70bd6b3df106b6e83d3901635946c37aae.nq.gz
│   ├── 8353858d6e9728ad8021ae861f3ee0594836b861.nq.gz
│   ├── 8db22339e7437f4e33db6261ca90b0f92f6501e7.nq.gz
│   ├── a0d0487cf135f50defbc0964bb5dcd16641e8244.nq.gz
│   ├── b14987990b28d8d476cf008766ec7016cb596e97.nq.gz
│   ├── b24983230d073297b6e475cccaedfdb91deda247.nq.gz
│   ├── b74b06d3a09fca6ca796268fa6c338f94b591dd6.nq.gz
│   ├── b8779eed3975804605bc4a26fc0c53b7b60bd883.nq.gz
│   ├── bd86fa964f770872d00c7c38b751d9a61322f4c8.nq.gz
│   ├── cea35968aef559c4df19aefb1878064f995d5c2a.nq.gz
│   ├── d0a1ede80edb97a6035c441ac8a30bd6e6b464a6.nq.gz
│   ├── d995b48b60c3ffe383b8d28cf748b8d79a175a59.nq.gz
│   ├── dcc6cb672d04c11fab8f35d99fd47211fb1be06a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f2de41c460486e3d2d78c34b57e185e82b428c08.nq.gz
│   ├── f4ee95ac1f720d34cc86bab4c18a742b0320ce62.nq.gz
│   ├── f98f9dceec416b80dfff889340661c05c5c5ae35.nq.gz
│   └── faa1e673b64b002fac2a6a5b5ce31b7399e04a56.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e0fad03cbe0a6f4e0960c2f3b676f5e0533fc09e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 49 files
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

[coleifer/sqlcipher3](https://github.com/coleifer/sqlcipher3)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*

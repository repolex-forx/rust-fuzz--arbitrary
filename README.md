# Repolex Knowledge Graph of rust-fuzz/arbitrary

RDF knowledge graph data for [rust-fuzz/arbitrary](https://github.com/rust-fuzz/arbitrary), parsed by [repolex](https://repolex.ai).

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
rlex download rust-fuzz/arbitrary
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dc22fdefd5456a0f4d2f190c6d3e017e3c7ddd8e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── dc22fdefd5456a0f4d2f190c6d3e017e3c7ddd8e.nq.gz
│   └── repolex
│       └── dc22fdefd5456a0f4d2f190c6d3e017e3c7ddd8e
│           └── chunk-001.nq.gz
├── blob
│   ├── 14c07f04d3bcefd95cfdff4d19e4bf79722abad8.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 17bb029b958ae6657126fbd3270a82f5acd25edf.nq.gz
│   ├── 1dbac58722adad408fc0c8aa86ca6cd9b98add25.nq.gz
│   ├── 20523a6b6596ca87917aeecc7560463f95b58795.nq.gz
│   ├── 21b93a4828f1553eda169f06b04b5a0a2ef5cd65.nq.gz
│   ├── 24db2bd779297e12fc938b47d624e3a9dcf6eb9a.nq.gz
│   ├── 25a0384ded6e66f1e3a5750d83673240a81cbf2f.nq.gz
│   ├── 269131c88474078e1302daefc7056a8aa408772f.nq.gz
│   ├── 296d474aac47165b040d41abac478b6550919e93.nq.gz
│   ├── 2b5e04388f6e28bd00bb406ea8c3bd2a6be5cf25.nq.gz
│   ├── 2bde6a06538c125b20c9a0865c503656e53af200.nq.gz
│   ├── 3009f06ba538056538b093fb503b75836702110b.nq.gz
│   ├── 30d26ea02643e4e482f832b5d5bed3b3382c23c2.nq.gz
│   ├── 312b37e107d80d7e9fd7153cc0a5359d087d0616.nq.gz
│   ├── 39075be3e3bf1d68f6f12dbdcabd8205d5495d26.nq.gz
│   ├── 39957df2b5c31e0f8879a414b470078e6e7fd43a.nq.gz
│   ├── 3f5f35881753182830392818776718e6f2dad920.nq.gz
│   ├── 40e04132f095ea21518e61261586749dc3893bcf.nq.gz
│   ├── 41e1f8a8c089e7ebf29c805606c890159dfdd7ad.nq.gz
│   ├── 4308d822046df995d72605f3497d02ae5ae307d8.nq.gz
│   ├── 586a939ded641ef6483507e544d900b499d39578.nq.gz
│   ├── 5cb63d217594d8b0048a6241233b2353cf769cf4.nq.gz
│   ├── 5d75f315793de1b3016daf71d2dea8ad6da840b6.nq.gz
│   ├── 60089e948ba06e35958244148ce36338fde930e6.nq.gz
│   ├── 63313ba8afc04f9e0c39ddacf73a015141d135cd.nq.gz
│   ├── 65ad50a17776ebae77cbffe570dcc0b3cb8e8553.nq.gz
│   ├── 67ca9085d1d28745965779768d2fe9e94048dc7c.nq.gz
│   ├── 6bf2e988140bf95aee1defa2a66bb2f1358a8d7b.nq.gz
│   ├── 6d581679404871fe23727d470a042b2ee1107700.nq.gz
│   ├── 7746715a9f3aa619bda94ae1b8736d41e60be1a6.nq.gz
│   ├── 7a1dc299984cdc77892229c92c2ddb9d6eb08dc2.nq.gz
│   ├── 7a772ac71561c60f8cb5878d14ef9631f8ea6099.nq.gz
│   ├── 7f48c75de1ac3c839f860a291e801539580e848f.nq.gz
│   ├── 8a56f2a0c47ad11fb0bdf4631068515101a0a3b2.nq.gz
│   ├── 8b28c69a78fc36b49de572856957052604224912.nq.gz
│   ├── 8c247354fe034e8966c5861fadc845283f96edf1.nq.gz
│   ├── 8c6e92fd6978644a828f32ee14fec1e0063210cb.nq.gz
│   ├── 8cdf39bbd6d9a163fa81fc1c813f83540c2a30ef.nq.gz
│   ├── 91893b991ddf7195a0a0e5af96fc64e9e2deae93.nq.gz
│   ├── 9238cfccb4e682bba8112c66775e076dcf0bf00a.nq.gz
│   ├── 95707ee369f34585a656b41a759f28fd461ffcf8.nq.gz
│   ├── 9783e1bed6f757d7924465d64769dd0df9ab00f6.nq.gz
│   ├── 994a875af7fbe081085b933753cef44dc0adcd34.nq.gz
│   ├── 9e5922e04b3fb65a032ec2848125f22dd8fa68d8.nq.gz
│   ├── 9fa0cb387421a9cb2a84a3f1d5bbe9081b23d3c3.nq.gz
│   ├── a04b62c0b41cf4e8d12e77b173ed9434304d26d5.nq.gz
│   ├── a060234ecd5dc2c2d44addc9b15a1e2c3b59fa7a.nq.gz
│   ├── a0925114d619b8cee7d72961b052ddcc42023a24.nq.gz
│   ├── a1b2383334663b45996fd129f726fdf444cf2ea0.nq.gz
│   ├── a5797847b3ca144a913ab096e49f89e3a44cc1d0.nq.gz
│   ├── aa0afbed0ba35c1e91e9b0fb77347048eb725def.nq.gz
│   ├── ad0db385b88dd204085d089775fe0b6ffb048b8e.nq.gz
│   ├── b1c42be610f254aa3f1f263de9be07d6cef7c387.nq.gz
│   ├── b5b1e22b82369e4c70444c585820e9ae44b2e3e2.nq.gz
│   ├── bad6d1b5ff0bbd6d9b3fd47880e7fb4e5430320e.nq.gz
│   ├── bc85aa2342872a77fa890679f8f4324776ef9913.nq.gz
│   ├── bce7faf4ea26e5c754d0147bd55012f9f1c4f2dd.nq.gz
│   ├── c3014a378dc541d773c47970bee19450c227fa10.nq.gz
│   ├── c42ec0a11346742385e1c469d42ace36a719986e.nq.gz
│   ├── c45cc24b7b99e0ce1937b847fb26722d5f04f027.nq.gz
│   ├── c8ca1db46a64514b82e84a2dab7d7818800ab3e6.nq.gz
│   ├── c94797b737429ea19b5a530d4d8e55662f66b3d0.nq.gz
│   ├── cfca8adb68af70c4a5879596e4c77d683fa2ce62.nq.gz
│   ├── d2e77afce66fcfaeb3cf00a52db39aaffca37b16.nq.gz
│   ├── d74f9e93d4c0f2fc863815a7631d5ad840b05002.nq.gz
│   ├── dfdd469a73e060f1338a494aa3e3a39262496dd5.nq.gz
│   ├── eae5ab95ff7a1dad757a49554c77be5b821b4710.nq.gz
│   ├── f0d5b33caa1326033c2ec6bae09dca1269a1df37.nq.gz
│   ├── f5d739fb95b360a51f992a4f5e7efb2210294be3.nq.gz
│   └── f7b1416e395379e46e1e308d68a1cd49b9a8c868.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── dc22fdefd5456a0f4d2f190c6d3e017e3c7ddd8e.nq.gz
├── filetree
│   └── dc22fdefd5456a0f4d2f190c6d3e017e3c7ddd8e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 81 files
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

[rust-fuzz/arbitrary](https://github.com/rust-fuzz/arbitrary)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*

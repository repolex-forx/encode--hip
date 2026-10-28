# Repolex Knowledge Graph of encode/hip

RDF knowledge graph data for [encode/hip](https://github.com/encode/hip), parsed by [repolex](https://repolex.ai).

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
rlex download encode/hip
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fe053e6c38d478d9ffe19027fd29e349e9077081
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fe053e6c38d478d9ffe19027fd29e349e9077081
│           └── chunk-001.nq.gz
├── blob
│   ├── 039a08749449c64fb41fc39cb844f6493166b909.nq.gz
│   ├── 0a221fe104f65ff9473a7e73441f20640eba4556.nq.gz
│   ├── 0ad75fec036e8219363c0ce04211485de9a98ecc.nq.gz
│   ├── 104d1b6f9c2118d33723f02b28a4744687eb8475.nq.gz
│   ├── 1bc45629fe97bbbddbb7406d0ffb85467ab1a883.nq.gz
│   ├── 1db40b7e4fc6a6c7a837f740e6f35441fa089ff2.nq.gz
│   ├── 1f0b3c0fc46cce205f56e65208fe8589521b35bf.nq.gz
│   ├── 25214481ade6fff07814952e74874ec3aaf5dd2c.nq.gz
│   ├── 29758719d60d6139d5aaeb5185bfee25d551f43c.nq.gz
│   ├── 3236e7ad7ec4a3f86dcaa91d3568cb000d6b5103.nq.gz
│   ├── 359449d0362ab0b1ef4a43013b6699643afedbfc.nq.gz
│   ├── 4d3dd97405ebf9259872b891e057d0d1443df9b8.nq.gz
│   ├── 4f6d4f55c070bacf7e3ff9511e13c4e36d5c14da.nq.gz
│   ├── 52735e5ff9e1579e13c0272a893ca2f8c73df9c5.nq.gz
│   ├── 565ada1883b3d7e86488c26b406c8e5464cc2f4b.nq.gz
│   ├── 591ca462e5eb83f16aeacfe8235ed2daf2e9b4cf.nq.gz
│   ├── 5b1350d37d1ca3d9fc8d586596baae0aeac9670d.nq.gz
│   ├── 5e5f6b68be369230264f6bd766fb09ef7746209d.nq.gz
│   ├── 62e20399a1c2c5e79f3fa3660ac046e524ae3eda.nq.gz
│   ├── 64391c0e1580339bfc5cbb2766c2412e3aac1aa2.nq.gz
│   ├── 670627f9ef633cc2f974e63fe5d050762720fb27.nq.gz
│   ├── 6d48adbe699364f215d52c6f29bc7d499e733faf.nq.gz
│   ├── 6ef1a05660277a8f967fef1b3fa6e3ae9492a3fe.nq.gz
│   ├── 737564bfc75120c9d59ca99cafe99d548c73310c.nq.gz
│   ├── 740f5bf0758b50d399ccd207a5419f68f1755ade.nq.gz
│   ├── 781f9b897a3741091effab3239a562d87fff5874.nq.gz
│   ├── 7a6662d33b521b2cb3cc99a53947ac17a0e6b1a9.nq.gz
│   ├── 812056c09b812a4f9cecc778136bb4aedba6f023.nq.gz
│   ├── 8265213e02fe856551c6327beacfe4d28b4ad5ba.nq.gz
│   ├── 852b7d0599eb200341b8913e23468fd6b0c24743.nq.gz
│   ├── 9189a1ae0c047aaaa5402f9b75b531f034aba381.nq.gz
│   ├── 9acc4bccbd5b36403394e0c60e1c3697b2099e58.nq.gz
│   ├── 9b54ee07ecd7d7d8064a12f9cee35533373f9359.nq.gz
│   ├── a6a021c7c56769c6af66309df4e943bb688bd9c0.nq.gz
│   ├── ab87c8d6d6b4df2afe3572f2be70abe179b0482e.nq.gz
│   ├── acbd91098016efcefe3eb558ea881b7e0dde93c2.nq.gz
│   ├── b12ddb65374dfef1c0f2948b48ffe5b0409f3ce9.nq.gz
│   ├── b43b67d2771032811fc4858935bf7650a854a440.nq.gz
│   ├── b48f71e0bb008c586ccfd73acbdc24db86fa22f9.nq.gz
│   ├── b586d3a00d6519282ffb2468588cc9109176e09d.nq.gz
│   ├── b6a608f39e053943d3a8b6e5d1b3a4cb2530e9e9.nq.gz
│   ├── baf09d776c5369c2d77b967ef87bbec2aa4c54d2.nq.gz
│   ├── c444fe9f4430b419d49bd6bb3eade0d13d2babae.nq.gz
│   ├── c774ae6ffb446b039a8625e2dad4b60e00c95564.nq.gz
│   ├── caf4b18463daf5d6f42f2eea58ed4ab0355ad3c5.nq.gz
│   ├── cc51e26d831664d768cac9f238e2d6313ea62904.nq.gz
│   ├── ced6d25976023905ad4697b86e6236e6729e70df.nq.gz
│   ├── d8dbd3a3fc7e4fc14c21a4a9e997b52764a490a0.nq.gz
│   ├── dee5e339e6b04f7fc71e7f9aa2fd7adecf5250ad.nq.gz
│   ├── e1e24a41fdcfc69a1fea288a854b4e264d8a9f1a.nq.gz
│   ├── e38aa76800f51de7248b2044eb7c954962563ca2.nq.gz
│   ├── e4bb59c526f2060458dfe4a22e33906fe8f8b9f3.nq.gz
│   ├── e555a09272b274f51ac3fab0b0ada5a34fc9c018.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec2948f3ed274113ec5de6e61cb9dfe66ba518b9.nq.gz
│   ├── f0088f4147a99906dbf4af9f5f98684865706f73.nq.gz
│   ├── f3254924cf890e0ade9beb251c1d9466224c2925.nq.gz
│   ├── f701d5af7619c34fb3badce158a936c9786ce89a.nq.gz
│   ├── f8f4f4c08e1658968de03bd130b13d9fc0f7e5f7.nq.gz
│   └── ff3f132a2cab3fcc026cc6f3490aa7c6a9a685da.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fe053e6c38d478d9ffe19027fd29e349e9077081.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 68 files
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

[encode/hip](https://github.com/encode/hip)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*

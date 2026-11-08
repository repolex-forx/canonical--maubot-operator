# Repolex Knowledge Graph of canonical/maubot-operator

RDF knowledge graph data for [canonical/maubot-operator](https://github.com/canonical/maubot-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/maubot-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0242cf19ae3efd133764176a343e3ca8c2c6017e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0242cf19ae3efd133764176a343e3ca8c2c6017e
│           └── chunk-001.nq.gz
├── blob
│   ├── 01cc54d60fa3d446010166acadbe7e2fb2045704.nq.gz
│   ├── 01f1384fac267326ca676ebf27bfe42ec9ebf70b.nq.gz
│   ├── 0791c3653a5786de190204ba62107126ccb31a20.nq.gz
│   ├── 09965e54922621e1a7c7884f77ced7043b31f6ee.nq.gz
│   ├── 0f77ee2bb747949b957fc7015700866bc7a01368.nq.gz
│   ├── 1032b9487bc8056c2af158c9b45e6d2522a57e4c.nq.gz
│   ├── 1ad595885b24c0eed96a78209e3f5316adb7dda2.nq.gz
│   ├── 1ce6110f30c9081e75264c0a8669df05d2f3bebf.nq.gz
│   ├── 213ec01d15a4e63159e610b387073bf3c6028137.nq.gz
│   ├── 2342b99ececbdaab2357f5bb43cde003fd055f05.nq.gz
│   ├── 26ac226df88c6bc3785214f437d30606702a7736.nq.gz
│   ├── 296fbdc6a9667174c65b15af851eb42665675c38.nq.gz
│   ├── 29d45c2ecef1155c5eeb129f7afa2d55a01162cd.nq.gz
│   ├── 2ab5dcd8b86d069a24a9b4dc1befebda27e053b7.nq.gz
│   ├── 2db7f38922b53bd3323492fe2532042a05ed74cb.nq.gz
│   ├── 309551bb560fcda4f38de13a4e801463e3741759.nq.gz
│   ├── 3372cdf832ee05e9662c2b38bd09673703f18820.nq.gz
│   ├── 350d969edb9e532c464817dc76bc145c2e282a05.nq.gz
│   ├── 36d4e6e343dd9377e65325a724e680f7df8fb774.nq.gz
│   ├── 377375e49a54f833fb50bb6c7d31f54d7b2622a6.nq.gz
│   ├── 38264265ce9f558d8b9392de85544c17245161ed.nq.gz
│   ├── 468366f42f79190b6d8e52908685828c38bc8404.nq.gz
│   ├── 4713cb75c2d8319fafd945a372e8d240a38f490c.nq.gz
│   ├── 4b8b005b4221683de826805b12bff5b94c2d0264.nq.gz
│   ├── 4d03c786248a53358954d700658579e9205c730c.nq.gz
│   ├── 55969d643048afbcfabdfa8a3314e271294fff2f.nq.gz
│   ├── 5be1d93158856891c2a493ea37cb1f116fc81f61.nq.gz
│   ├── 5bf808e6c58509bb0e9ec837a5cafc140a42069a.nq.gz
│   ├── 60eb89524fa3b7cf1c3714d4b33837cdd9e2cef7.nq.gz
│   ├── 6139f5d1c12ad5fc52ff65ee46aa0545540aa4f2.nq.gz
│   ├── 63a9fc35fa2161f200acfcbaedc9bc7089f87e47.nq.gz
│   ├── 65f4410270649b54a4c1a652b651d51175f64783.nq.gz
│   ├── 66649de94c98ef7f1e46f41e111b81189077d8bb.nq.gz
│   ├── 6854efb912d7789d289f49ca146acaf9c75c05f8.nq.gz
│   ├── 7710794a8a6cb8210c302e8fb0fecea4fb729ef0.nq.gz
│   ├── 776c44f97d383ebf092c26be60cd685dc71c6cca.nq.gz
│   ├── 777a890233b28ddadd79ca819e4272f9215df0bc.nq.gz
│   ├── 7a8ab534f62d08b0b47fe3f7b0c6d7a61d472a1e.nq.gz
│   ├── 7a8fdacc1e1eb0e6c7419c858e17ed3dff4f5558.nq.gz
│   ├── 7cd39c62c2d02600b4145d52a52cad56a2008c50.nq.gz
│   ├── 80095ee58e1ba8f373140dcc789c3f9271fbdb46.nq.gz
│   ├── 85a8bb9774f4ddaa5548304339ccbad6eeae9df4.nq.gz
│   ├── 87802365d3cac776efe8a164a541788770e0ee79.nq.gz
│   ├── 893ca50b81db31e11ebc60ce2a76692964580c41.nq.gz
│   ├── 9100a85fcd8469a0ed02fb5a552a8d609ae31ee8.nq.gz
│   ├── 94945135d301d16e394ac0a420411041f0480674.nq.gz
│   ├── 97b07ce9940cc08b21db75e8d86719565de375dd.nq.gz
│   ├── 9886fc2b40dfc111e4cc7eb94e14591d5ee21aab.nq.gz
│   ├── b670d956aecb31b7fa113b65b891b178c3fa3b43.nq.gz
│   ├── c4db78483721d1f7d6aaf028baa67703cfdd7035.nq.gz
│   ├── c895d699692601fab2751d257451d7b51a5df0eb.nq.gz
│   ├── d4c00cfdb3b83471d04fecd5d81a8c48067de12c.nq.gz
│   ├── d800add37c9aafd919720930372763943e92429c.nq.gz
│   ├── dddb292a2c1698851f1fe7d4eae27a5c284b55e2.nq.gz
│   ├── df541556b4c8b8d1d2040a3acdf1aa8872e9c1a7.nq.gz
│   ├── df9b5626effa78b16586ca4ed0e858416c5a3353.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb084d85961cebf266e57d57b58cc4e323f1ea5d.nq.gz
│   ├── ecf8b0476e1666577bd78201d4c55dccdc2e8b01.nq.gz
│   ├── edad9cb2e920d68212922b2581a661adbc67fd92.nq.gz
│   ├── eed567a9551e51e21a111adbaa6b528f60f69fda.nq.gz
│   ├── f6fbd8ab2b5ff4bfc99b53f57794510e90cb3e74.nq.gz
│   ├── f8218d821f474e903fa0edd6890a6af9e83eea3a.nq.gz
│   ├── fe3518b0772aaeea4b156d5d8453f58c15b3ab96.nq.gz
│   ├── fe6468e8d0a1957aba024423c38b9eac57f996f6.nq.gz
│   └── ff52245c9cfaa5bcf811785450528ad234783e84.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0242cf19ae3efd133764176a343e3ca8c2c6017e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 74 files
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

[canonical/maubot-operator](https://github.com/canonical/maubot-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*

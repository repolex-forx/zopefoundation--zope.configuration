# Repolex Knowledge Graph of zopefoundation/zope.configuration

RDF knowledge graph data for [zopefoundation/zope.configuration](https://github.com/zopefoundation/zope.configuration), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.configuration
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dba7d8f1dc3ffa724b44e8b13a17c488aed561c1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dba7d8f1dc3ffa724b44e8b13a17c488aed561c1
│           └── chunk-001.nq.gz
├── blob
│   ├── 005ac6381743f481059248400f604d7c32153cc1.nq.gz
│   ├── 00c77b9855c427416150e837565218a3f0b3ac41.nq.gz
│   ├── 096f7ac073ede10e982bf1715bfe7204a449e1a6.nq.gz
│   ├── 0a34c69a474052d3c6581004511065a93ac6952e.nq.gz
│   ├── 1208bf45e50de0d32e3d98832253e09f04593575.nq.gz
│   ├── 13f3226208bc6ab7549fa425c769d90d56f85928.nq.gz
│   ├── 14b101e2313553b645b52d9bf89442ee5af4f47c.nq.gz
│   ├── 188120b692cc972bed5f7063baaa7ebd9dd5fcea.nq.gz
│   ├── 1bb2e4553687ce680877063cec45437f1fbd3698.nq.gz
│   ├── 215319f1e1a3bef846e6d5a84ca8e5faea1fd3c3.nq.gz
│   ├── 224230abc4c81c4499f5986a55f2c6e4dd13b12a.nq.gz
│   ├── 2276e54471ca6a549746af7a214b8778acc6857e.nq.gz
│   ├── 24ee43d9da965d4f93f01bd0897880ccf4855f9d.nq.gz
│   ├── 293860e764340e7d848f9dd4728cfebfe77a9cd4.nq.gz
│   ├── 2a677a295475ee96ca1feb3434f3381d098d8895.nq.gz
│   ├── 2aa29e58625be9f6425bb5f89a47db69624c6673.nq.gz
│   ├── 2b8bd9ab775d9a245832c79a12318b6608c45073.nq.gz
│   ├── 2e2efdb91e2bf5d9d57117bc54a3b6c5e6d85802.nq.gz
│   ├── 34b8a3fe6c45d2b21d64ea7647a5e0de13ba65be.nq.gz
│   ├── 350d905ba619ca677d1a5727db099c4e09f066f2.nq.gz
│   ├── 3a02639500c2c661c2fb4bf195f3d99a59e057f8.nq.gz
│   ├── 4471308127ad043c28e70790432980c419f8a2e3.nq.gz
│   ├── 46b5163e7a5083bb61e2414de065a626dcc381ef.nq.gz
│   ├── 48c55f97123c233ac35764e7f091c9f0c89ad011.nq.gz
│   ├── 497f7d364f53ba0aae44f8008e0c5d85b1f232fe.nq.gz
│   ├── 52e1e3cde19b9f8473a869a31a0b62d4d0090176.nq.gz
│   ├── 56a9fce623716a7ce7b2eb4598892f3d83751aa6.nq.gz
│   ├── 57718b0be688053c936e17c0352781a225bf39e6.nq.gz
│   ├── 5ff3d37d0c9c69f91242bae7cf6c3c7851bb738a.nq.gz
│   ├── 70f2ba7b707499345070852959ec2a1b88e694d1.nq.gz
│   ├── 792d6005489ebee62cde02066f19c5521e620451.nq.gz
│   ├── 79859e06010bf4967c5b4b044afea6ef39742938.nq.gz
│   ├── 7aba55f8a2a93ddba952e553181a693c3bf4594d.nq.gz
│   ├── 822d15e084110438d0dc89a49018f221400e4585.nq.gz
│   ├── 8570e35011366de4db5955a67b099a4231dacaf3.nq.gz
│   ├── 866bbc418f99b5b02e7f4b70727d62a8a9886395.nq.gz
│   ├── 87526a6f7bea8a0d67526eecc827d85ce0e75e22.nq.gz
│   ├── 895a6c5906f6ec9d40d7184f54c192c4a230ac34.nq.gz
│   ├── 8a1cde635fcfe005cc4438d504940505395236a7.nq.gz
│   ├── 8bcb4ded537d69a9e3a4327c054876fc91b02b4d.nq.gz
│   ├── 9029129a91ccee2c9a07ab13a8487455ca58d97d.nq.gz
│   ├── 9140037896d6bb1f14ae252918cd7fd678551e00.nq.gz
│   ├── 98099269f6a0abcbae61b121d5653e9fc98f321d.nq.gz
│   ├── a216b18e20ddbc5a9c05c639f7f213cc4c20c846.nq.gz
│   ├── a3a262492fcba380558db5bd89d19f5f5952711c.nq.gz
│   ├── a46089103ca3d02c26e5f4e66fa7cbb43ad46f9b.nq.gz
│   ├── a6a4519bf87f252d73c4b3633ca9338e5e42f2f8.nq.gz
│   ├── a76b9c89c01d97ff972c8d3256cbfd01a533ea2e.nq.gz
│   ├── aaaaf0a797c628a1ec55eeaab5589ec3854ee973.nq.gz
│   ├── b556c6fae78887aabea3147de0304249950ad764.nq.gz
│   ├── b640a3073cf0a353fd0369bced642444761bd24b.nq.gz
│   ├── b711d3609fdefd7664f2982d225d96f5e53be9c0.nq.gz
│   ├── be2b8eb6ce518967e75dc57dea3bd806b07590f0.nq.gz
│   ├── becc109d7753ee419e83b5fd234f9b6229580908.nq.gz
│   ├── c37d6190b97920806b4e1fd50b52b0b3d87873f5.nq.gz
│   ├── c409e8ba19f8762a7f821cb3094079a89b859a07.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── d0e80bf248ee00c4c9a5cbdc5aca8c0350b7836c.nq.gz
│   ├── d11f924e7d8320ac1035b21880696398e7fac03e.nq.gz
│   ├── d19ea9f9a162741b4947be5e13b704cbcef987d3.nq.gz
│   ├── d2a2bc7be26cbfc9909d38866d6012e2853d15a5.nq.gz
│   ├── d2d502902f40dcf5281e2fdefbcd2548f95f1c06.nq.gz
│   ├── d35cf1594a95627dba140feee40afcded994128b.nq.gz
│   ├── d5f0807af07f825316ff704f82525016895daf85.nq.gz
│   ├── d62334075cd98cb81de0c4cd0394de217cf21558.nq.gz
│   ├── d67a86559fdf84858a69bf1760fcbf994137992c.nq.gz
│   ├── d86faa80e4ccd45208ee4bcbf14d1a98d5662cc5.nq.gz
│   ├── dd324db7f5702341940f8c8cfbf8880af1dc7a71.nq.gz
│   ├── de0a69b0b1cad1f29f25063e8bbd3e0067ab0a24.nq.gz
│   ├── df1d20550ba1f2afd7cb8a2c167612b2af798751.nq.gz
│   ├── df7e129e5102278b640f23ae3458043de40e6033.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e3579011e1a5792ed2adb52fe79f1ac001b9c3bf.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9a4c25f0497ce1ac179e6206639d0a25869f37e.nq.gz
│   ├── ef3bbcbd81f8de77062e17005d5c1557aa0ca113.nq.gz
│   ├── f4d45530cf80e3a148b77c829551968d1efaa928.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   ├── f8342335e714a35a2dbefcb3006e607b891171bc.nq.gz
│   ├── fb742ba5546475d8ed2a26ca23d6658abda9eed1.nq.gz
│   └── fcf530ad6060adc7ff59b2852f3a491a03cb6a05.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dba7d8f1dc3ffa724b44e8b13a17c488aed561c1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 90 files
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

[zopefoundation/zope.configuration](https://github.com/zopefoundation/zope.configuration)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*

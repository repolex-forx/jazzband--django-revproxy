# Repolex Knowledge Graph of jazzband/django-revproxy

RDF knowledge graph data for [jazzband/django-revproxy](https://github.com/jazzband/django-revproxy), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-revproxy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 72e1d4d7c9be7e6f0e15a08ad9c4afbe83db76b9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 72e1d4d7c9be7e6f0e15a08ad9c4afbe83db76b9
│           └── chunk-001.nq.gz
├── blob
│   ├── 01bb17f20aefb48a8c9411988bebb5b5dcd45cbf.nq.gz
│   ├── 02ee10e6c2e64a4f92eef2098a71a70db872e59b.nq.gz
│   ├── 12080269fbc0b40ee058d43937371195b5b5ece8.nq.gz
│   ├── 15c8fb8d98a49b5e6d3c6dcbb1bab9c02c6af331.nq.gz
│   ├── 1966a2f1afac283992b1946b6a8a10500807792a.nq.gz
│   ├── 1968e08e14319e4bb32d6fdad1506f0f069743fc.nq.gz
│   ├── 1ccddfb033f31bfb00c09fec24a4dd15548edfcd.nq.gz
│   ├── 2a6c735458204d0f12fdf3ccf8d177ff6f286f1d.nq.gz
│   ├── 2ab1e5b6cbe3fd027ed1899b6c33ab34a26b8599.nq.gz
│   ├── 31dbf0d704ae126a6a14f5c1fb63ce6142bc100a.nq.gz
│   ├── 3298d4619dc22c19f362d577d2da12ee91190d74.nq.gz
│   ├── 3e026abeb0df7b7196215e56562ec3146de4f145.nq.gz
│   ├── 3efcbae4918479587368fa740fd63c7e4dc86ecc.nq.gz
│   ├── 404d59b76a6e82f85b236647ecb3ec61694bd1ab.nq.gz
│   ├── 4961d24a375f0935db2fcd11e6d8abd26f7ba254.nq.gz
│   ├── 527e0e94222d5d04e0b96637fec17ce3d03f5c88.nq.gz
│   ├── 5e94bd383354e9376f7a1f31ecd28db7e9de754f.nq.gz
│   ├── 600be42a0823e6cceba10755e2b40d79a2f381b6.nq.gz
│   ├── 602d25c5a82fca02c321756ae966ebbcd31fde39.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 6650de93cdf8180334c8eff442a6950cba7f3185.nq.gz
│   ├── 6a816c1b98de754a28591c8d63a2cdea1b268437.nq.gz
│   ├── 6af9e2602d6e93d5c51906e4ee957ce521c456c8.nq.gz
│   ├── 71a836239075aa6e6e4ecb700e9c42c95c022d91.nq.gz
│   ├── 748667629dc360de43421f44581d305d3b68c883.nq.gz
│   ├── 79b8ee682c801b81172c586831ff5074e28b4654.nq.gz
│   ├── 7ce503c2dd97ba78597f6ff6e4393132753573f6.nq.gz
│   ├── 7d16ac45b850f0db0e8bd5b3147a7540680904f9.nq.gz
│   ├── 7f4d8933c0f0ddbd6f04fb258d44e95a89cc5820.nq.gz
│   ├── 863e6d2e85e54a63ee7af978856417c36281eb09.nq.gz
│   ├── 8887c60b5d099801c96644e4c9d1a6c4eaeccdae.nq.gz
│   ├── 8a3dcac0668a29384cc257b1c55deb0adb69e7af.nq.gz
│   ├── 8c38f3f3dad51e4585f3984282c2a4bec5349c1e.nq.gz
│   ├── 8ceaba6c9eb5484fafc455ff50531b1d1ed896cc.nq.gz
│   ├── 977c5ca7fc8f1ad8d4c959786170e1a6dee10329.nq.gz
│   ├── a22225b50d532c0dc90a8a1a79155753880739bc.nq.gz
│   ├── a2604bb9cd79040c8db320c7ca2ebe4daeb51615.nq.gz
│   ├── a5021c60e36ae085d1ef96c1fed9d88c2f65dd53.nq.gz
│   ├── a612ad9813b006ce81d1ee438dd784da99a54007.nq.gz
│   ├── a663c99d00ad1bb5f65282797950ebb489f75dba.nq.gz
│   ├── aa202e759bf0c82e5f4b99779373329be4b24cb8.nq.gz
│   ├── ae313f2942d4a3c5d81f210f20cd9993cbdd6851.nq.gz
│   ├── be364bd5964397b8cf1363c760ee2306d0ca8c00.nq.gz
│   ├── bf0e1101bba07b52b7e70bdd5d0748e63637976c.nq.gz
│   ├── c3fb422b1c63110c0099beaee082631ee00e02a0.nq.gz
│   ├── c8f98a1ff153d65de67352ab3b481a87c37e3630.nq.gz
│   ├── c9ff361b365005b48e5054a0196a14dd53b8fb2c.nq.gz
│   ├── cc744875aa259e645a3b5a7e74b0be374889abe1.nq.gz
│   ├── ce3b9aff797f72eeec58316b3ed9c1e24dc13529.nq.gz
│   ├── d36bbfd74f66602d1c5caf45a2144a30225ccda7.nq.gz
│   ├── d79b4fbcc29fe178438d72045c98e081f33404cb.nq.gz
│   ├── dc33c1e696762332cd7d222775f34c8a3ad5076a.nq.gz
│   ├── dc51a4dfd4c99096633f86ab6d47979d037946fb.nq.gz
│   ├── dd042424b6cd2bef38173bd328d1827946c04275.nq.gz
│   ├── de29d4eb355db947ead0c43613acd017b11c392b.nq.gz
│   ├── de53856191d909883a110a278f887701574f5020.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ca49ac877d9776fec209c081b592a8e25019cf.nq.gz
│   ├── e9b9d104d2f4961e46a1ead728f4b07364344b88.nq.gz
│   ├── ed032a9871fb8b61884679defb99e0477059eabf.nq.gz
│   ├── f2ad9d862c87ade80777474b4e414186a3a1628c.nq.gz
│   ├── f2de99a5d8ad9ea276301039a8f4803bee588170.nq.gz
│   └── f57187368f0815ca81d11b20f5e71f35d03fe401.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 72e1d4d7c9be7e6f0e15a08ad9c4afbe83db76b9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[jazzband/django-revproxy](https://github.com/jazzband/django-revproxy)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*

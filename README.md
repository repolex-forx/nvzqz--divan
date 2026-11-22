# Repolex Knowledge Graph of nvzqz/divan

RDF knowledge graph data for [nvzqz/divan](https://github.com/nvzqz/divan), parsed by [repolex](https://repolex.ai).

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
rlex download nvzqz/divan
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 52f9d4983e68b16d1d77f8920df087ef8f8d6ba0
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 52f9d4983e68b16d1d77f8920df087ef8f8d6ba0.nq.gz
│   └── repolex
│       └── 52f9d4983e68b16d1d77f8920df087ef8f8d6ba0
│           └── chunk-001.nq.gz
├── blob
│   ├── 0124694c3100097bd689c030e03d24f1ac803f78.nq.gz
│   ├── 028895a3c7490277f4d5f4eb658d2cd8e43b0e2e.nq.gz
│   ├── 0508fe95601b5766b6bc8a7b513c67d822ece9fc.nq.gz
│   ├── 078fc47f5a766fd794afc5e322bbf69d2770cd48.nq.gz
│   ├── 0d16f7f1eacfe09b1ccbecb6f01c0f651c81659d.nq.gz
│   ├── 0fb7f536dfbe1af09af98671ee79995fe84a8bc7.nq.gz
│   ├── 14e3c106d1dc671f8b9fae85d76105b1ba97ea6a.nq.gz
│   ├── 19956d2bc7c30cc3a3b8f916c85cff69870c3be9.nq.gz
│   ├── 2096b977ffa3705e341d3b85b49d440aa3ac0c37.nq.gz
│   ├── 22f006f1313297d0382fd098a0dc13a3ac9e7de1.nq.gz
│   ├── 2c5770d2588b86dac06579a491f2ca38bad7aa86.nq.gz
│   ├── 30e04225178e05f82e533ba463b049669e9488ae.nq.gz
│   ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
│   ├── 34b7d9248fe67c2e4b387563cb5dbac876d85184.nq.gz
│   ├── 372340f6751d20ca6f293390b2bb3a5996648392.nq.gz
│   ├── 37d0a1a707881b2309941584e2eca23cc6f4774e.nq.gz
│   ├── 399963c0049ab2ddf18f3311673e461c05c0b549.nq.gz
│   ├── 39d0d759c16051e4fdd98e4c917720a7da9fcf77.nq.gz
│   ├── 3c020623a4eeec9d6705fd665ee76e2040e8796b.nq.gz
│   ├── 3c2e5c818e1a01eea6dbd0a513c9f80fa7ec36fb.nq.gz
│   ├── 457160354463e3b68e0b4c378e645b0b9c619b3a.nq.gz
│   ├── 45a09da935da7d0d58f09ce621bfb94585538a03.nq.gz
│   ├── 45e0db0596f8fc7a0cb895ae0d15a916ff15ec5c.nq.gz
│   ├── 4aa195042682b1ce67cf5e62d7b98f2c792bf4cd.nq.gz
│   ├── 4b8a4bec89e14d53b385046a8910b9ed8359f1cd.nq.gz
│   ├── 4fbae76b8da6e647c20516d51e2b4cdc0c758976.nq.gz
│   ├── 4fca23b0810c0d7374b2a1c43d0fc615ff8237c0.nq.gz
│   ├── 528c1647339acd50ae3c5d4f5b63285a0b7deb64.nq.gz
│   ├── 566483edb1b76d1628f963ac03ecb855d6504df3.nq.gz
│   ├── 57f60dce120f6635bcfdd89fe000c2b6061740b2.nq.gz
│   ├── 5ad06bd84d6e727f921f2ef0edc15bc14e67288a.nq.gz
│   ├── 6262889e1490c8cc4bfd369a9c6a648912de77bb.nq.gz
│   ├── 62beb20774373c036a21e4b9e7770952a43a045d.nq.gz
│   ├── 662ce5d10ca45c6c900f808469c364ca6ef704c7.nq.gz
│   ├── 67d12f678e5ba544a19cfbcf731601f086cb099d.nq.gz
│   ├── 6ccce84fd4e0ce120c6314fa3d25ffab7728955a.nq.gz
│   ├── 706917c378d0408b6e5693eac7ee2f907d4578bd.nq.gz
│   ├── 71a52b533ff5b39ad58e59431a008fd40d498ec8.nq.gz
│   ├── 73dcd4bca2539b275c639b5513d37ceadffb039d.nq.gz
│   ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
│   ├── 7948ccd0672eac3900fecdcced605a4141fda73f.nq.gz
│   ├── 7a8a7c85dc292e197b4c08b5398ff352933fb9af.nq.gz
│   ├── 7d811930f78f8cecfa577e3f223e82c07c4b6f9a.nq.gz
│   ├── 7e1232259d64c0a701484e101b6239615e4da282.nq.gz
│   ├── 7e5d668f90b097428a8d2305cc24640af2731a88.nq.gz
│   ├── 81514af16628ca13fc7096f824928dec779d6348.nq.gz
│   ├── 826c8c8be6e71db6d31f71fb3d2417613b6ba81a.nq.gz
│   ├── 87797146ab2af11dd869ea319dce20475eb6852d.nq.gz
│   ├── 8a86b7fe8c65e338f8b16240dcdb2120ee1a7686.nq.gz
│   ├── 8d84dba61808509991f8b064e91933926b39c5d9.nq.gz
│   ├── 8faad18ff21265dfbfb7c2d2b16cc64f96e411af.nq.gz
│   ├── 900c9e2796d3b4700673a9204f935a597d9bd26a.nq.gz
│   ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
│   ├── 973ec1bbae00e5b64d6f56fa1bd7bc7afcf487c2.nq.gz
│   ├── 9e6beb28f9eca53cb2f864d3ac8dee73fe1d1900.nq.gz
│   ├── a00cf4e0a323ae1ed501579ced7d6d36e53716b8.nq.gz
│   ├── a1463cebe44011fec853e8ffcfb70aa7af74d398.nq.gz
│   ├── a59991e2c3e32f6a14325c76b1fedd726b08a574.nq.gz
│   ├── af2c61842f6812454b7f7cab075707c9755760b4.nq.gz
│   ├── b1e1727d4bba00388c1e661d639a39969e0b17ce.nq.gz
│   ├── b4e4e9f7eee0ca58c562e38dd2c1db21f2fc29be.nq.gz
│   ├── c607a936c679788519e6e77b3792dce52bf5db66.nq.gz
│   ├── c8f2455fbb1f97aa370c6f4f4e04072e074e1117.nq.gz
│   ├── cf41a0ba96f53a71e4ac3acd542bced2b5c3255c.nq.gz
│   ├── d1df9d7120b4e5a31cb84acf3a17b19acaa9174d.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d665d792d1c60256c24e711de32ac63806f8aacc.nq.gz
│   ├── d7838f02cd276750933c36d903c05c17dc6562ce.nq.gz
│   ├── d84f07bec0c220f836e40c540c2db1b218c4e028.nq.gz
│   ├── d86d416aca024ce4a3663129281030be652f163b.nq.gz
│   ├── dc5959745194202b7393c8aa5836a5fc3cc0fb90.nq.gz
│   ├── deff9ee427782e9079ca4c1ea358463e57e81239.nq.gz
│   ├── e1d799d4789ccd9602700165b23f6f773af24237.nq.gz
│   ├── e4f7f96b079e937d2f03835a4904189022008690.nq.gz
│   ├── e595c625c6f020d87d29c76c931729f6481f975b.nq.gz
│   ├── e607e34681fe9ca7019fa35dadf6f7cae80b0a6f.nq.gz
│   ├── eef566823499abc33e92ca5d4590f41f45a9b567.nq.gz
│   ├── ef3f2897fa60124a08778001d5bf2d7b77b2dfa4.nq.gz
│   ├── f0837116a28eb230166eebffb6e8e9d72e3d556d.nq.gz
│   ├── f8387d08a4b2fea68e9ac74a212caef1b3f65c91.nq.gz
│   ├── f8c9658e6db4efea8cfbcc27cb4785649b0efa74.nq.gz
│   ├── f8e1aa3c17c5c58048734f52f135cbfb1ffc0f9b.nq.gz
│   └── fe4cc31f8105e9415f7d0ce71827ff9822a9b691.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 52f9d4983e68b16d1d77f8920df087ef8f8d6ba0.nq.gz
├── filetree
│   └── 52f9d4983e68b16d1d77f8920df087ef8f8d6ba0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 93 files
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

[nvzqz/divan](https://github.com/nvzqz/divan)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*

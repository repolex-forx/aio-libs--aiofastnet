# Repolex Knowledge Graph of aio-libs/aiofastnet

RDF knowledge graph data for [aio-libs/aiofastnet](https://github.com/aio-libs/aiofastnet), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiofastnet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 29bcb0f99131e794d329cbdd46a8cda090712147
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 29bcb0f99131e794d329cbdd46a8cda090712147
│           └── chunk-001.nq.gz
├── blob
│   ├── 0075123671af87f8efc3c1b23cb4b3dfcc5b33f6.nq.gz
│   ├── 03cc43a7507a92d3965ff6ad9ae74180b6a330f2.nq.gz
│   ├── 057d0c2f206ee7a0c81997caceaaec5c71d55c0a.nq.gz
│   ├── 05d06345ffc7575f6d21257aa69f18058eb0ee93.nq.gz
│   ├── 0623c390065cc8d8e23125993a01e28c4650a85a.nq.gz
│   ├── 087f5141c3d87c894a04eedf7e0dd3c5388d0e82.nq.gz
│   ├── 08f45180538f4a15340ca0c8b8e3b489daaac836.nq.gz
│   ├── 09d2f132fbdee12b260ed2110a71a50079403780.nq.gz
│   ├── 0d4907b2f24b5f5cbd150476015f00fc4c4b8834.nq.gz
│   ├── 0fb9e70ebca463ee5b6c7374bdd50d34119dbb31.nq.gz
│   ├── 11ae2f3f281bb42630ac593434ba4ff7035c164f.nq.gz
│   ├── 14d41f32a4aeb1f7671e5e6516e02912293680d2.nq.gz
│   ├── 166dee77ea2fb388992bae249a0bf19e2dcdee90.nq.gz
│   ├── 17532e510d17ba092864b7d4e70a30e36eedda7b.nq.gz
│   ├── 18f55fc273c5a0858a11b9dcf80d71b5797b36f9.nq.gz
│   ├── 22a57c19bf6332afcb2571ec4ab4a672d2c4a9af.nq.gz
│   ├── 28d850ab112006d130795a56820c22b60ec0df4c.nq.gz
│   ├── 2ca144ad7ab2d4b5add2c61e9d63f8ecce2e484a.nq.gz
│   ├── 32037dd33f112777ec0b11c519a4e007fa45c07a.nq.gz
│   ├── 340fddcd372baa89d0e5065f6449509909b7e5ef.nq.gz
│   ├── 34a748ab8c606e76b61b2562c740a22f712defd4.nq.gz
│   ├── 34a9ecc413e01f7458dd56e0897edb6339d7b0a8.nq.gz
│   ├── 35249aaf968311f133ebce40a984a9c5d659526e.nq.gz
│   ├── 35eb9a69031ee049510fe779261ce588cc62a8bd.nq.gz
│   ├── 364f74f51ef14bc76fd86bdca91ac9417d04e799.nq.gz
│   ├── 40aa3598225753c0d200d96969e2fccdb3a33a5b.nq.gz
│   ├── 42438f8715bd0c41dfbeab8119c8cdf6ed562820.nq.gz
│   ├── 45378061301f6b6af5621d63bbb7ae60fe65cbc9.nq.gz
│   ├── 4a5586473788f28ba3aabd4cfba7545b75ab5513.nq.gz
│   ├── 4ed98a2e8dda7ed632db49e64bf2e959e66d2fa5.nq.gz
│   ├── 4fb7bb5d858d07592ecfc9c1c09e7b94b01cb5be.nq.gz
│   ├── 511ec45bbd4cc897b2194d73517528ac9775c194.nq.gz
│   ├── 545e729d033c2c90f9fc32d451710682936c90f2.nq.gz
│   ├── 56dc9f8ddcc81fa6a4f318765505f7a71cfdbaff.nq.gz
│   ├── 5c6c3515a3d779fbb4ae5be2e80dbb111160b757.nq.gz
│   ├── 64344bd7b831307c059b192201cd21d354808aa7.nq.gz
│   ├── 647209315029039744e758f4596f76f12555aa21.nq.gz
│   ├── 652dd47f25c5e90384795277d5e3312f07eac156.nq.gz
│   ├── 67c656c6b691b76468fd903d34413745074126d9.nq.gz
│   ├── 69d63238cc4dc2a71ce0c040a4f3b833755395e4.nq.gz
│   ├── 71bc17284e30f7427a8c57d1d579dfdff849e07c.nq.gz
│   ├── 765cc67f0f9203caa417b00f034a5f2e86d255be.nq.gz
│   ├── 770c998fe40bd8ee19ac12893fc145278ec6386f.nq.gz
│   ├── 7916f614c0124382de3650b5a519a96645f10345.nq.gz
│   ├── 7c50151d13f226318ef02e6bb128f2912d6666ba.nq.gz
│   ├── 84844e15b90374b196a5d2f303b2603333759458.nq.gz
│   ├── 8574834a2af4dfeafbb97dc83ddd2e6c9f282eca.nq.gz
│   ├── 85837b932bb7d2b1203581935ccdbf600f4609e7.nq.gz
│   ├── 860ddc4c60852cf5da87c31ea3658d55cbe69d94.nq.gz
│   ├── 873b939828ecf189a6016e5db031d4416aaa6a12.nq.gz
│   ├── 88640aab904478eedd3473efc8003fe649b675f3.nq.gz
│   ├── 8a34513873e0954d5343e8e2bce1243c2d8d1624.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b89e2cb7036bb4ad1cb29e2a280662dc63422e7.nq.gz
│   ├── 8cb6392a6ceabf8ee43f41a26db739ffbacce2f7.nq.gz
│   ├── 97446357a39e063d7d398c7eb5b2ecbe63c2d2ca.nq.gz
│   ├── 98b37dba8037fbcf2fb580b992918446c99b9b56.nq.gz
│   ├── 998e54a29a0422c292b0e59b7e54fcca7c281ef3.nq.gz
│   ├── 9dc3d56ebb7315ce38ddf7eb5462acec8305b86f.nq.gz
│   ├── 9ede29ffcf03340cdc0c561b1b955b086e5c5383.nq.gz
│   ├── 9fb463841369e226492063f1fc34632d287479eb.nq.gz
│   ├── a33fc566113c5a3f15cc03828e7cc927ff40ef76.nq.gz
│   ├── a47eed4fecafb8eb7fcf26c652e2b9435f393a54.nq.gz
│   ├── a523c8a9778bb848050f21320dc99d840bfe5186.nq.gz
│   ├── aeed6bad274daccbbb9a3664f520f2225cdaaa34.nq.gz
│   ├── afcfe70576812d0f1e9fd8437e2c823640e86efd.nq.gz
│   ├── b0a93ffb8d00c26259efa8b682152627ddd6ba62.nq.gz
│   ├── b15ed411083f70bbe3bd2ebed87d0fb77d3b0f9b.nq.gz
│   ├── b1c9b1ce60dfa94917e5470b7d3b02b376797874.nq.gz
│   ├── b428d7ad107360ed56240f3a6aafff323ff82631.nq.gz
│   ├── b78089f51b2e947f4270a5358a42f5165e8aab32.nq.gz
│   ├── b87b30c41b8d867fb6940c23f7e8b694f5c548a0.nq.gz
│   ├── b969589e9e92a5413a0db394b4e34ff1e8277e74.nq.gz
│   ├── baa256974cb592d3f66f5e2a9f11ecf6d1de2702.nq.gz
│   ├── c68196d1cb0d5f0c6715cba4414a0b33fe2672c7.nq.gz
│   ├── c77b044c357017a2c39ecd3a528d0d8061e3421c.nq.gz
│   ├── cae137f3be3d189da39303e19c4e754faedeeac0.nq.gz
│   ├── d25da856b1b6f15f335a338cf870b0823ebf0c8f.nq.gz
│   ├── d614dadcbcc23c744f81f18dc4804101bc873532.nq.gz
│   ├── d705a7221e1950dcb42c03d5a8bb5e52f5da87d0.nq.gz
│   ├── d8d9b6e99dd9118cab5ebd6b785d9e87f786bdd0.nq.gz
│   ├── e033e789612d8eba91815f1a74e8f5dc8016740f.nq.gz
│   ├── e2dc141334d690c6d1d19947aa00d71c6c7cd65c.nq.gz
│   ├── e37c739ffcb931ea5e5ffbace5caf3c4b700d151.nq.gz
│   ├── e61d23c4905f3ba747d46e1735f3e65205285d7f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb5ce60bff1c8552afc1016289fc98105939258f.nq.gz
│   ├── ed84e2e0e7ac9501759b3ea825c529ef57dc4465.nq.gz
│   ├── edad8a0634f8261b563a0a766e5bcd79cdf20c9b.nq.gz
│   ├── f07fd5c34a19010eb61e5735663aabfd69966b24.nq.gz
│   ├── f0907c049b678df88dcd3c3f64b66522b52f1074.nq.gz
│   ├── f255617b152fc32a9aee9a8e4011f7434457e05f.nq.gz
│   ├── f37a6aeea59f2e8d9f1b9652a6548bc1e93cf3c0.nq.gz
│   ├── f62c666ee5f9e06b21c8864828a004338cb3d147.nq.gz
│   └── fb04356e759e840fea5b81e0cd4888479fc4a6e2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 29bcb0f99131e794d329cbdd46a8cda090712147.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 103 files
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

[aio-libs/aiofastnet](https://github.com/aio-libs/aiofastnet)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*

# Repolex Knowledge Graph of scverse/acumen

RDF knowledge graph data for [scverse/acumen](https://github.com/scverse/acumen), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/acumen
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ee1ea4aa0f17bb4029ed61bc5a715747f4b07668
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ee1ea4aa0f17bb4029ed61bc5a715747f4b07668
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
│   ├── 055f3fc1156b46873d3c164c0d628fbe026e92f8.nq.gz
│   ├── 0b1b8d056c8b55bd0fe8fef5a1fd2d30bbb9e562.nq.gz
│   ├── 0e7d2a4b1d01776c8673bbb1821b5a93293990d0.nq.gz
│   ├── 1300155c23a444afba9983a4a9b582adc268c007.nq.gz
│   ├── 15b229341e0faca3ad3efc14d6893082b94b46db.nq.gz
│   ├── 1b737df170abfd6c79feb00e611e401ceeabe5fe.nq.gz
│   ├── 1df7017151a21de1237041d1c281ad1deca6c78b.nq.gz
│   ├── 1f4625cae65bb37268d123e4d986785b1091a49a.nq.gz
│   ├── 2177a643bee9c60f0fbd2d6d8912b5250544a017.nq.gz
│   ├── 21dc3eb1566f6182212c88339edd15376e16e230.nq.gz
│   ├── 2c5e37186e63978f1aa6b566685b256078fa4860.nq.gz
│   ├── 316cfe89ef529e57ee205e740d0f1c2f6c79f8ef.nq.gz
│   ├── 33d0b678d0d95318df7842f3ff6e60abd9a6154f.nq.gz
│   ├── 340f66f3af9936c42b561db2bbbceecd65f2fe7f.nq.gz
│   ├── 3672a16c7692ca8e597c1504b1e7a9833c4cdcbe.nq.gz
│   ├── 36d1874618b1d0099c4d192c8a90500d69bcc723.nq.gz
│   ├── 382b78a900823c550b70707e47e9c6682262191b.nq.gz
│   ├── 42e29c8ef462a2d225e0cb4549a9efc8c629fd3a.nq.gz
│   ├── 46825411c831f951a8c2a96307d80a13061ac900.nq.gz
│   ├── 4a47042042b386296654f6a9ba9ecb3d9ba7e3e9.nq.gz
│   ├── 4dccb75933ed6e9b773b1e8b9bbb015a71fc2a81.nq.gz
│   ├── 4fff6d1fc86f5672935e7bf23b72a66710ee9390.nq.gz
│   ├── 50aed5981dc8071c822a918d1bdbdd8d3764dab4.nq.gz
│   ├── 56ce7c0ab3ba333b6cc2d06392e4a28e3d02b20d.nq.gz
│   ├── 56e8223bd9dbbe6fc9879a38d73f565c71c01e34.nq.gz
│   ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
│   ├── 5e0203ee0ebd007a0e957091e6153c4c7c111131.nq.gz
│   ├── 6311dba99ef007c7b153840a8f057445b21e162d.nq.gz
│   ├── 654b3c66b999ac8028e248b1f76e3d7bbcce9dd5.nq.gz
│   ├── 66678e378b55a7e2b28d2087164af8999aff39cb.nq.gz
│   ├── 67eb948d72ad9ee53fd1cbe38e72bcccaa753334.nq.gz
│   ├── 6d0e6e3752f3c87c1909d62e315dce18ed66fb11.nq.gz
│   ├── 7c09f6de3b06914b0dcb4539578efedd3ea9778a.nq.gz
│   ├── 8168d130e9dd041d3db86e90b1387f2dad47b892.nq.gz
│   ├── 8ae4a951e1e2c84a7927efc4f9b67d6ab8a4ffa6.nq.gz
│   ├── 8cccfead0ec0d727fc29284d30dfedf826562bda.nq.gz
│   ├── 947865948ae3733f0989f52f739e2079136948b1.nq.gz
│   ├── 9af2a9867209f198607edae022272596505e67ec.nq.gz
│   ├── 9f5bed44ec106502c159a68e71e8308abddeb4f9.nq.gz
│   ├── 9f8f2208c4bdc0f0b0cafb4c0d0b5c79d32c32da.nq.gz
│   ├── a0d1586780d6c4ede2a0a224e475752a67deb938.nq.gz
│   ├── a5cc712601ff9f591fd98c794f59660b1060bdeb.nq.gz
│   ├── a7fb1d5287dbfe413680b568ca4a4fb5c8c6f4d1.nq.gz
│   ├── a934abc3d3c494a2caaf286f976562078c36d7db.nq.gz
│   ├── ad5aaf6301cb68fc88b8e743bf32dbbe5ad39508.nq.gz
│   ├── ae6a94ce3c0eb4525ab7dc2d40b3fcf52282669d.nq.gz
│   ├── b34752828923e0829b9fc329bfa1eca9ed0cae27.nq.gz
│   ├── b6cd3acbc83528baf58e82c0871ed9830bede6ed.nq.gz
│   ├── b8c8d47fa0a99101c675af913b08144664399119.nq.gz
│   ├── bafee3b784b87eb691ea7f11de855f6ef6a6ce98.nq.gz
│   ├── c576ea50d495c65581ba403c02816a2dc725681d.nq.gz
│   ├── c6c5f39baec641f4656b38908e27d0e8bd3a103f.nq.gz
│   ├── caaeb4f73220343cf55564c4b747c6434c231fd8.nq.gz
│   ├── cc32eda8a90cc20e1e9fdc7039b83be81e3d1445.nq.gz
│   ├── ce39d3829e499b7450124041f7c0f31fc15e65b9.nq.gz
│   ├── ce7e49e207a79b8200f76aaf464549e2c2c9b778.nq.gz
│   ├── d0c0e2917651ab1d38f689317e32f463c392c3d2.nq.gz
│   ├── d43795151cf4e8dd9c9b0e9d51bc10801964a2be.nq.gz
│   ├── d569140c3fcf8452fb0bdf0c5582cacb150b0b5a.nq.gz
│   ├── d9e79ba64848091a9bccd21dc241c61c669dad7f.nq.gz
│   ├── dbb9d5035604f10379c1d907055947ae47e8a6b3.nq.gz
│   ├── dcb0dc6540b82e4747876e82e5f2f2209e779803.nq.gz
│   ├── e0d41c806dd9b856634d45befe5d370397417813.nq.gz
│   ├── e491e5c1acabbb39066bf8b10aed707461470efd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9abbc1d36fa791079062d691e08dcd524e3f054.nq.gz
│   ├── f6a3685e80dafe2b074751f599b05879564b352b.nq.gz
│   ├── f913653dc2ba490c152462c6c80d2a549d51e7e9.nq.gz
│   ├── f9ccea890cde5568875bfd70e78bd4708925d365.nq.gz
│   └── fc17263c5650bc47c80d400eb968ee47d2d4c43a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ee1ea4aa0f17bb4029ed61bc5a715747f4b07668.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 79 files
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

[scverse/acumen](https://github.com/scverse/acumen)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*

# Repolex Knowledge Graph of uqfoundation/dill

RDF knowledge graph data for [uqfoundation/dill](https://github.com/uqfoundation/dill), parsed by [repolex](https://repolex.ai).

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
rlex download uqfoundation/dill
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 72c61c8f9e86f033f697ac9cecb87566a83ef579
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 72c61c8f9e86f033f697ac9cecb87566a83ef579
│           └── chunk-001.nq.gz
├── blob
│   ├── 03cea73da17a52758d087c6c3556aa022bba6a11.nq.gz
│   ├── 04d692ea5560532ba0c0a21e4b68972d35d5aa4c.nq.gz
│   ├── 0604522f1ffdb52952cf5fccf172926feb232547.nq.gz
│   ├── 0828cf925986663c88be5a1d908827b33d946f3a.nq.gz
│   ├── 0a09cf4b089c3fbd9cfd3f28797419dbebfdf297.nq.gz
│   ├── 0a1060fb902f1b9777f3496317e1f9d3d3de184a.nq.gz
│   ├── 0a94a100c6e23b0b48b557bfc3b00aa5dad2288f.nq.gz
│   ├── 0b1df46225fb7db5aeeaedde2dcd8efb6e00fadf.nq.gz
│   ├── 0c0f96826112595910e105c5fb6efcd29768304f.nq.gz
│   ├── 0e863ab510eddfaa4730d6da1f9f2fd088902db5.nq.gz
│   ├── 1309d7686b71d4d34c190ef78834268f3fc34c8f.nq.gz
│   ├── 1ab9adfc0f84ced99577d329a2f94f77f37291b3.nq.gz
│   ├── 1eff512c24968206874376c9bfd41af6d5a29a4d.nq.gz
│   ├── 236e51108eca5bc42d02db2c4d46961a50a7fb2c.nq.gz
│   ├── 252bc25f5969a345de65baf8584a0dc43f88a956.nq.gz
│   ├── 29ef98480d9d832ceb88a28d5d8b5aab9e4e5ffe.nq.gz
│   ├── 2b55b39631827ac7938b6e7d6314c97cbc0fbdd1.nq.gz
│   ├── 312e2de8b3f0c1a9d83f0e53df9e31fd12346920.nq.gz
│   ├── 3ad6f8d0da915f0c24b2816a04e386a289a8a38d.nq.gz
│   ├── 3e93a2fae2561d7d930a609ee9b0d6002ded2704.nq.gz
│   ├── 3f5d5e11514cec97e3c6836297e839eb1e819c2d.nq.gz
│   ├── 447811dd5b57a663195d3d47e7afd542515991a7.nq.gz
│   ├── 45bba916e2b6edf6fed9c5bad63d73bef8b5181a.nq.gz
│   ├── 45f8a0bdd832feb775b7c0f7e1bc17c2399d636e.nq.gz
│   ├── 477f7cecd397c53efc3be8a3c1ab96c243894063.nq.gz
│   ├── 483e245e0eac8686e11db92f12d633a8bff1fa6d.nq.gz
│   ├── 4b9f4e03b459bfafa3080cc4ac1aa2ecdefd523c.nq.gz
│   ├── 4fb60613dcef1eaa79b1e4ec71ef54394cb021ff.nq.gz
│   ├── 521d98b1f5095746526cc1f7510a9223c398e786.nq.gz
│   ├── 5237f68fdf166a41b06486284a934c38b467a1c0.nq.gz
│   ├── 5b2af2d408eae639839c1e613b758f47a2987d9a.nq.gz
│   ├── 5c57d8a0d51006fbcfe59c732dc4a1300ff52a6c.nq.gz
│   ├── 5d64e77f927354979329d46dac5aeaebf2e990c5.nq.gz
│   ├── 5e9759987b5aed46946b9ea45f80c26ea6026e13.nq.gz
│   ├── 62a3e408b5b932762da10792b3a7f152694cf94d.nq.gz
│   ├── 6d89f0435b9c2a52430d1c7a50c34e01cfc3eae0.nq.gz
│   ├── 6de1995b37d097030a7f4916b715680b37fa8dcc.nq.gz
│   ├── 6fa8dd51bf87ed14939e2015d861986ad1181b2e.nq.gz
│   ├── 70678fe636cd7c36eb46b0aa2a60e2733594c77c.nq.gz
│   ├── 77da8e6a43543ada6db48cc2d7206611f860621e.nq.gz
│   ├── 7de1867aad1ed3866759c710db4f802e3806865e.nq.gz
│   ├── 8064fbe8812d1cb775956e4998537a55db0239e0.nq.gz
│   ├── 875045f3a6ad3b38ac8ef31cc9bfc4e2cbcb1a50.nq.gz
│   ├── 882d24d00dccd79572f36be16b4804e9db177b81.nq.gz
│   ├── 8c45188e68a2725216a15ed4679722a9a56a9c0d.nq.gz
│   ├── a4e6cda2cad0072af644420af9d9ae4c16a4a784.nq.gz
│   ├── a7a5bdf2f7c9dd6d05882337b7ad462a079551fc.nq.gz
│   ├── aa93850e3e5cbf89dfa8f90169b0f285f470e153.nq.gz
│   ├── ba2b4aa631abb69f0d49d78c939f76ffc0cc7356.nq.gz
│   ├── bb8874c7fc5704717d022d28d204635df5e9186d.nq.gz
│   ├── bc0e18e3294a103af226c602e8bac2b13b2258af.nq.gz
│   ├── bf88a47fdd07d3c6cbae71e8599e7f3e2180d442.nq.gz
│   ├── c20178104b351ee60c8a77d64cd9a23119e1d531.nq.gz
│   ├── c7981ea39d344f96a5ce57f9163944d1a120c1d2.nq.gz
│   ├── c8843d9ea9406ab23e3314f0fc18ccfa5938de97.nq.gz
│   ├── cea8d008c3a11e048fbd19b5f9390de88757910d.nq.gz
│   ├── d27745febe7dfa357e295b9f4b8dcaedcb4f3496.nq.gz
│   ├── d9e2fc0f70bb3a92611046ba7a94194d2e2e7950.nq.gz
│   ├── ddece29ec404f3684781dece8b32e89e9ba29464.nq.gz
│   ├── de997deebdeda59562d318ca200065507aecce50.nq.gz
│   ├── e0344ea26b93e8fe4087360081f1a982d5dd7b26.nq.gz
│   ├── eb07feffc197c60262c049e6adc3fd4c2aa0e822.nq.gz
│   ├── ec7f268277e52683840fcf30b4927b32ce067bc4.nq.gz
│   ├── eff0b8e0106641c842835a8ebb60dbf49b452102.nq.gz
│   ├── f052f83aad681bc0e19d19578902b5012b553fec.nq.gz
│   ├── f1f2e625a8a77f7de735ab76ccfeff6a795bb539.nq.gz
│   ├── f3db1a4f0a328b7d16025356ae5147a062764df7.nq.gz
│   ├── f524f58eaa69f6f5afc8c9a3cdc331f04d9599ae.nq.gz
│   ├── f86e44a55a1c8ff57ff878efcc1bf5c38091da5c.nq.gz
│   ├── f97361a616dc1c75dfa85a88198be94714895c63.nq.gz
│   ├── f9d99e525b4f6c21ff10e5f48c3f580330825455.nq.gz
│   └── fe21b12592d3e949e4921006dfc630306c005502.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 72c61c8f9e86f033f697ac9cecb87566a83ef579.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 80 files
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

[uqfoundation/dill](https://github.com/uqfoundation/dill)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*

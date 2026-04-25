# Repolex Knowledge Graph of kpdecker/jsdiff

RDF knowledge graph data for [kpdecker/jsdiff](https://github.com/kpdecker/jsdiff), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download kpdecker/jsdiff
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f5c473662bedd672809b689771037d5401bdcc6
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 4f5c473662bedd672809b689771037d5401bdcc6.nq.gz
│   └── repolex
│       └── 4f5c473662bedd672809b689771037d5401bdcc6
│           └── chunk-001.nq.gz
├── blob
│   ├── 00689c49712e6d22bc92fa3b187cbf3153399f64.nq.gz
│   ├── 09911cbc724ae57424aa290de09fb73c38f46480.nq.gz
│   ├── 138f954461e93226df5f2e863a1d29b311bb770c.nq.gz
│   ├── 19d318b8e8e5bd8e81b7f02e078f0510f1a91ee3.nq.gz
│   ├── 1eeb8f0b0eae15f9fc7a335701ec65f450f9a696.nq.gz
│   ├── 203d0245fc634d87350575fab4a597d2c92417ff.nq.gz
│   ├── 23d3bc8fa1588f24b429231dff75172a0afad42d.nq.gz
│   ├── 26962484048f0ef35fa45ebb71cd3a4b51f66baf.nq.gz
│   ├── 28219b2b0e5d4a47b73341de4879990b19aa0bc3.nq.gz
│   ├── 2d48b19fcc2e6269d8903b5716e51333df19f250.nq.gz
│   ├── 30e8299357b572171fedec113b2cd89e70be8a19.nq.gz
│   ├── 35c56ba87129ecc27c714225b6065e65f8ec3070.nq.gz
│   ├── 42080ba6dc6bd85452f273dea9abf16139ccb28a.nq.gz
│   ├── 4a980a9764b20b89e62b11d93acaacab9518b46c.nq.gz
│   ├── 4d134de8ff3d007612b937f3bbf72e5bacdd5ea6.nq.gz
│   ├── 4f7255a0d5fe99debf9054e3931281fb632aa3df.nq.gz
│   ├── 53de7c21da396b83745817b7fd7cb9fc4a48992d.nq.gz
│   ├── 5664b5b461c324aa7dcef4b92c1438c28748e303.nq.gz
│   ├── 602714aab7b263ad6f6fdaf643d5b83f3dd9fc26.nq.gz
│   ├── 65a5abc37f0e1539285a42fe2a85cdda2cc1a64a.nq.gz
│   ├── 82c09b4031afb816d98487eb328bd5c6fe67d4ed.nq.gz
│   ├── 85b842c966307127574535f459f679f54afa3f9e.nq.gz
│   ├── 862b3b7bf49043418b7210a88a54badb5b5a4e8b.nq.gz
│   ├── 87a5c8d0addae71995abb7668fda79e12052bca0.nq.gz
│   ├── 898cd3f4e4c0788485585925e2911f60ea4fbf47.nq.gz
│   ├── 8d650fc38dabf21eab5f9513b9be7362edb95c79.nq.gz
│   ├── 8f834c1ce9624da21c855abba010d806ad66060a.nq.gz
│   ├── 9be0603ec47fda5a3ac5fc11755b843938584344.nq.gz
│   ├── 9e56efab04ee49769333638d3037b385beb13325.nq.gz
│   ├── a1d34e0e724a38a319118909cfead99bd9b55564.nq.gz
│   ├── a3510a767b0ad586683abf24057c1fb4798299ff.nq.gz
│   ├── a7239c25ee28ef1593bd1a52b73c31133c322516.nq.gz
│   ├── ab1162dd858efeea0f1599dc44a3dc01fa99deac.nq.gz
│   ├── b941f247c27e47e2390dfaf6bbcd339c9658e674.nq.gz
│   ├── bb29e9943982cbf4e7ebfdc13ede9c207203bd09.nq.gz
│   ├── c06c26169089c94caf37dda6b46b264068cde0a5.nq.gz
│   ├── c125cfe9947216bd7c187db9f9bc60b43688b4bf.nq.gz
│   ├── c7636db5744fcdf8a420680fb2e9e7eb5e0562d7.nq.gz
│   ├── c789488ecf5cb619e8a9d94db11260580665f662.nq.gz
│   ├── cdaf08d6014745f95a0a5e0d428995ddcfd2721c.nq.gz
│   ├── cea7375fcbf3d0c63c9a6299799d45d0ca0837c6.nq.gz
│   ├── d151b4396567976829e9bcfee2aa4f1d0b69d182.nq.gz
│   ├── d36c7a59543e6c2711a709750fc1a460b3d33ad2.nq.gz
│   ├── d928019e1889f8cc1354e2e67a533f302fa58d7a.nq.gz
│   ├── dbd0ae50ded99b9242829fdf3cb5778623ac0347.nq.gz
│   ├── e2fe316ccb2943d56b4f2796893a0caf5c1220fb.nq.gz
│   ├── e4fd2187429e8e317939a41e25ebb24f14f30399.nq.gz
│   ├── e5591294efe4be12ca2a57e5ca63a40ae9a5b1dd.nq.gz
│   ├── e90041a39dc98ff088ac1d5b208d8ff0e8dfa735.nq.gz
│   ├── e999566c54bc22d4e9666b119f7a5d1c7811fbe0.nq.gz
│   ├── ea1c73566ea891bad0079e9a659b209632fa08e0.nq.gz
│   ├── edec16ddcf3fe105d7717bc821774be140c0543e.nq.gz
│   ├── ef2dd462feedb047c35bc1c7a7f8a9a8a54a4a2b.nq.gz
│   ├── f255f32102b41eeaaba8b7b2e6ff24be9936e7be.nq.gz
│   └── f8d9292fb15ef1bdd5699ce4ac76e0cad39d8be6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 4f5c473662bedd672809b689771037d5401bdcc6.nq.gz
├── filetree
│   └── 4f5c473662bedd672809b689771037d5401bdcc6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 65 files
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

## Source repository

[kpdecker/jsdiff](https://github.com/kpdecker/jsdiff)

---
*Parsed on 2026-04-25 by [repolex](https://repolex.ai)*

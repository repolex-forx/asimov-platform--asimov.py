# Repolex Knowledge Graph of asimov-platform/asimov.py

RDF knowledge graph data for [asimov-platform/asimov.py](https://github.com/asimov-platform/asimov.py), parsed by [repolex](https://repolex.ai).

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
lexq download asimov-platform/asimov.py
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 4bc18c8407d052b9a5a0c164e712af65dc6e5b27.nq.gz
│   │   └── b5c288bc2bf9703097291fd6393d1c4a3c8e11c7.nq.gz
│   ├── lsp
│   │   ├── 4bc18c8407d052b9a5a0c164e712af65dc6e5b27.nq.gz
│   │   └── b5c288bc2bf9703097291fd6393d1c4a3c8e11c7.nq.gz
│   └── repolex
│       ├── 4bc18c8407d052b9a5a0c164e712af65dc6e5b27.nq.gz
│       └── b5c288bc2bf9703097291fd6393d1c4a3c8e11c7.nq.gz
├── blob
│   ├── 009d16542a402a4d489d8c961646c1a26a176f04.nq.gz
│   ├── 056fce806d0b314ebd074d1a664a6fa90e135f89.nq.gz
│   ├── 05f5ceba7ca44502bbcd4cc2884e435881af7793.nq.gz
│   ├── 13edb27f8341a15f7ef6805243c5be8572913129.nq.gz
│   ├── 2391f73aa051d3804285ce744f2e9a1c7e08993d.nq.gz
│   ├── 275b01153156be45d1de4c72b5c7836f4cb5a928.nq.gz
│   ├── 2992f44ac9b4992103f9c69ebf14edd99eee5038.nq.gz
│   ├── 34a763932bd213a5c9e6b939611e7a97dbef75d7.nq.gz
│   ├── 34dcfc9c4f6aeba5eac6346da4bcaf7b4e7ff1f7.nq.gz
│   ├── 41edf27105a7f60ef7211bc55a2628bc2e26bcf4.nq.gz
│   ├── 4679b9d5d5a7adba696dc17822a836ebe4f35f5c.nq.gz
│   ├── 52f8d94647b9b2baa73cb937d82797be4d05bb58.nq.gz
│   ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
│   ├── 6ae0c1823c7a25244f5810157e906105dd8c2620.nq.gz
│   ├── 78093b007ef8d36c6a4cb9aa835ba9e4b88a4005.nq.gz
│   ├── 784c330fc78c1f7608f09f3bb1d110815dec2b8e.nq.gz
│   ├── 92040c3d7bc389fca260ecec44e577c45257967b.nq.gz
│   ├── a38ace0fbaab348ee98b54bc1037156bbc00cf2f.nq.gz
│   ├── a4119609f8ba65f083807583dee7546cd9d00b47.nq.gz
│   ├── abbbdd04586fd8894e56d7e7d397b753c0bc3e57.nq.gz
│   ├── afb2df71e00aa626901f8ac7f05bf579bd09464e.nq.gz
│   ├── b25bad035254dc35e285e937b999720555e19e82.nq.gz
│   ├── b47d723f491695e1a2dc51ea889e5051ad850f66.nq.gz
│   ├── bb9832a4fe63caed1c7ec7253b27e83985c92d95.nq.gz
│   ├── c2a0ef8eedb7c785d3d5265fe5757698e0b381e6.nq.gz
│   ├── c6d126fb91bb0634a9591fc8bdc041efa81c720f.nq.gz
│   ├── cd8caa246424c5cee3d81c5c9b2537385483e940.nq.gz
│   ├── d049aecba4fd9486ebed085591cca29d33287e48.nq.gz
│   ├── e079f8a6038dd2dc8512967540f96ee0de172067.nq.gz
│   ├── e3e57a8ce4ccbf74759a6df8fa4a3980ff1c9209.nq.gz
│   ├── e67ce52c43e0f5b22f922f0fa6419202657fd698.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9df000eddd61c7033a60d16a8428969795e8c3b.nq.gz
│   ├── eb15d09218d51f9fdb9c8db3964d1a42561fbe21.nq.gz
│   ├── ec27f902e6600754b84be014144e97a01fa608f2.nq.gz
│   ├── ee4d9362508d63f9e156fe9ee1b11ebc1a3e86d6.nq.gz
│   ├── ef22050c52c61b7ce03ecdcb6c54d605ae07b278.nq.gz
│   ├── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
│   ├── f5662133043843b9e0bc06ed6a0cf9b2ba9f3b4c.nq.gz
│   ├── f97aeda07b813ac759b4e837ef5f056ac06c0c22.nq.gz
│   └── ff26d8884f3e5606f3a5aad41b0afee7be21e877.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 4bc18c8407d052b9a5a0c164e712af65dc6e5b27.nq.gz
│   └── b5c288bc2bf9703097291fd6393d1c4a3c8e11c7.nq.gz
├── filetree
│   ├── 4bc18c8407d052b9a5a0c164e712af65dc6e5b27.nq.gz
│   ├── b058535a14de6b810854d1159783aaf677244101.nq.gz
│   └── b5c288bc2bf9703097291fd6393d1c4a3c8e11c7.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 55 files
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

[asimov-platform/asimov.py](https://github.com/asimov-platform/asimov.py)

---
*Parsed on 2026-04-03 by [repolex](https://repolex.ai)*

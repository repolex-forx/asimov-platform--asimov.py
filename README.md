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
├── blob
│   ├── 009d16542a402a4d489d8c961646c1a26a176f04.nq.gz
│   ├── 13edb27f8341a15f7ef6805243c5be8572913129.nq.gz
│   ├── 2391f73aa051d3804285ce744f2e9a1c7e08993d.nq.gz
│   ├── 275b01153156be45d1de4c72b5c7836f4cb5a928.nq.gz
│   ├── 2992f44ac9b4992103f9c69ebf14edd99eee5038.nq.gz
│   ├── 34dcfc9c4f6aeba5eac6346da4bcaf7b4e7ff1f7.nq.gz
│   ├── 78093b007ef8d36c6a4cb9aa835ba9e4b88a4005.nq.gz
│   ├── 784c330fc78c1f7608f09f3bb1d110815dec2b8e.nq.gz
│   ├── abbbdd04586fd8894e56d7e7d397b753c0bc3e57.nq.gz
│   ├── b25bad035254dc35e285e937b999720555e19e82.nq.gz
│   ├── b47d723f491695e1a2dc51ea889e5051ad850f66.nq.gz
│   ├── bb9832a4fe63caed1c7ec7253b27e83985c92d95.nq.gz
│   ├── c6d126fb91bb0634a9591fc8bdc041efa81c720f.nq.gz
│   ├── e079f8a6038dd2dc8512967540f96ee0de172067.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb15d09218d51f9fdb9c8db3964d1a42561fbe21.nq.gz
│   └── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4bc18c8407d052b9a5a0c164e712af65dc6e5b27.nq.gz
└── tag
    └── tag.nq.gz

6 directories, 21 files
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

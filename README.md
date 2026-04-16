# Repolex Knowledge Graph of python-hyper/h11

RDF knowledge graph data for [python-hyper/h11](https://github.com/python-hyper/h11), parsed by [repolex](https://repolex.ai).

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
lexq download python-hyper/h11
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1c5b07581f058886c8bdd87adababd7d959dc7ca
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1c5b07581f058886c8bdd87adababd7d959dc7ca.nq.gz
│   └── repolex
│       └── 1c5b07581f058886c8bdd87adababd7d959dc7ca
│           └── chunk-001.nq.gz
├── blob
│   ├── 01260dcae3e6545db213d76eb664f5c7b8b168ca.nq.gz
│   ├── 0a07c423359b1171f485ecaddfcf583bd0c5eb83.nq.gz
│   ├── 0ada08936b3647a7fbeef6d1f054bc867a6381ba.nq.gz
│   ├── 0ff194732272665be18a58aa96261a96c78bce46.nq.gz
│   ├── 1baaf64c0f20eb44b572897c0977e2c37d18fd61.nq.gz
│   ├── 1c6aca57f5b0941d68cb2a7a87e1370a44c42d61.nq.gz
│   ├── 21a3870b6be9a6a365037326c2085ff2715022cc.nq.gz
│   ├── 27c4d151261b79a5ffe85b928007fbfe8e9fa413.nq.gz
│   ├── 31da3e2b23b55a624b36f105e62a6902e63286aa.nq.gz
│   ├── 36fd741bdac7294c42a1bb41f25c93821a39fdb3.nq.gz
│   ├── 38d4fccf51981ead8db3fab8f5ff91b6d54f65d8.nq.gz
│   ├── 3ad444b043e3f3d6c05c2d9d84d5119312bfaa34.nq.gz
│   ├── 3f33b9f470389f6f2a3a62e9eb1c4187f0d2b3de.nq.gz
│   ├── 3f66a103c662bd0bcdacb94bf722b550bbe6c86c.nq.gz
│   ├── 407e044e3080cc29a4c52a605d3276df59b04057.nq.gz
│   ├── 4b6798ed89120851f242fac95ad556819736ac17.nq.gz
│   ├── 528dbf886f8282446983504b526da28e2b86220b.nq.gz
│   ├── 571be44461b0847c9edb8654c9d528abed0b7800.nq.gz
│   ├── 576804cc282032526e0a932c9853d586a094bad0.nq.gz
│   ├── 5f2861600c543733424127ed0baa70e62c647373.nq.gz
│   ├── 5fc33b86e4e9f48ec34e5a6f3d99645d86a2b9df.nq.gz
│   ├── 617efa5c58b50223bd1a8f5e21c6d5e2fdc97a0c.nq.gz
│   ├── 64a6883338e47ed44bae176c52e575c4071a9a6b.nq.gz
│   ├── 6614ecf26ca9c4c4d88421a14c19539550747078.nq.gz
│   ├── 6718445290770e028ea2f1f662026c9a0b0991db.nq.gz
│   ├── 6eb5beb0a118c85b50f6d7a04731acfb14275124.nq.gz
│   ├── 73713e2396e749445fe4604423eb5c5ab3c3f3ac.nq.gz
│   ├── 73d078e7ba1c4ac8329f093c61878b1f27ad182b.nq.gz
│   ├── 7617e1f462ed4cd96bced8d2dcbb91860e23f7fc.nq.gz
│   ├── 7644d1e331272263a01f9b32e06022c31ba93616.nq.gz
│   ├── 76e7327b8617c9d12236f511414d5eb58e98a44b.nq.gz
│   ├── 79bc095185c79313b238fb034ef746c7f67b9d93.nq.gz
│   ├── 7ad0c44935fc384b89b7f73d7fe77edf8c7b48af.nq.gz
│   ├── 7bc7c3b9062d937df486c70cfc2aa3f9d86010d8.nq.gz
│   ├── 8f080eae848f759c9173bfc0c79506357ebe5090.nq.gz
│   ├── 9333f6d6ecac3be50e92e1591ffbd8f6d092d10e.nq.gz
│   ├── 933587fba22290d7eb7df4c88e12f1e61702b8ce.nq.gz
│   ├── 939cdb912a9debaea07fbf3a9ac04549c44d077c.nq.gz
│   ├── 989e92c3458681a6f0be72ae4105ea742750d328.nq.gz
│   ├── 9955deccd941f6c55582dcec1e96d1caf2e1980f.nq.gz
│   ├── 996afb68ab348a8de7c6b6033cdb51552c46dc81.nq.gz
│   ├── 9a30dc655445c48d08ad36c6948ddf27a15178fe.nq.gz
│   ├── a45e8c95a114d8033b44f36e1f23f52547fbeee1.nq.gz
│   ├── afba31be471251a41f3623bef25517dee10149cf.nq.gz
│   ├── b3627f521c5c275512ff8dcb5ccba0ff2e1e7b4b.nq.gz
│   ├── b57274cbbfee8fce3e89f012b6d0f4206f768f67.nq.gz
│   ├── b7568e597e12ec3b24fd1e14aee11b9698adc90a.nq.gz
│   ├── bc974e636e9f3e9b66022d2095cd670a9acbdcd9.nq.gz
│   ├── c25e43d0d90cc175cfc60109fa5ad2cfb803b0ad.nq.gz
│   ├── c339e59333e4c3b5bc5fd910796fda5469a2515f.nq.gz
│   ├── c3d6f9d923b4e0d070cbb5330302f6bdb85dc5f6.nq.gz
│   ├── c4e2a5974d0ace6fd2539cd4715c7ad6ed98e4b9.nq.gz
│   ├── c7e5798c865f69ec5f114bef5344a62e5f17bcaa.nq.gz
│   ├── ca1c3adbde2c4e7710482a18e3471f91f1da610e.nq.gz
│   ├── d01e930f244d317bafea7da6789109eb1aaa0ab1.nq.gz
│   ├── d0be0a6c5d6c19a35f0e815b83e27f8d833ea88b.nq.gz
│   ├── d33077580fa57e9b544446151ba60c521bdcf571.nq.gz
│   ├── d6915457047b7d5fdffb419ef7ccde9dfaa72e05.nq.gz
│   ├── db234fd289bc1f8ef29d0d21177c9f18ce9db7ad.nq.gz
│   ├── e37d82a82a882c072cb938a90eb4486b51cdad99.nq.gz
│   ├── e5c4e08a56f5081e87103f38b4add6ce1b730204.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee02847dcdf765718e757006356acefa6dc70f63.nq.gz
│   ├── f2f65de8c87d0a7a42062d03ed1b721c6be0823b.nq.gz
│   ├── f5642f79f21d872f010979dcf6f0c4a415acc19d.nq.gz
│   ├── f864d5fd38b7466c76b5a36dc0e3e9455c0126e2.nq.gz
│   └── fb7e9137bca6162139adc45a458dec985242c989.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 1c5b07581f058886c8bdd87adababd7d959dc7ca.nq.gz
├── filetree
│   └── 1c5b07581f058886c8bdd87adababd7d959dc7ca.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 77 files
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

[python-hyper/h11](https://github.com/python-hyper/h11)

---
*Parsed on 2026-04-16 by [repolex](https://repolex.ai)*

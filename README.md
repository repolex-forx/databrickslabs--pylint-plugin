# Repolex Knowledge Graph of databrickslabs/pylint-plugin

RDF knowledge graph data for [databrickslabs/pylint-plugin](https://github.com/databrickslabs/pylint-plugin), parsed by [repolex](https://repolex.ai).

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
rlex download databrickslabs/pylint-plugin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b1be1a39703b8d3b693a0afd8a6ee61ff5078cb8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b1be1a39703b8d3b693a0afd8a6ee61ff5078cb8
│           └── chunk-001.nq.gz
├── blob
│   ├── 027b56f201a52d3ba508e524698adad891896a56.nq.gz
│   ├── 1a11b2ff341bd53a017d608d10e3ae391beb1561.nq.gz
│   ├── 20e139315b01bae7aede9f0a964e45fdec3eac41.nq.gz
│   ├── 24c6b13d3a70b892a5d56332cb7d6ce854efefcd.nq.gz
│   ├── 3620b69027ecbcb93da6358ba1f93072063ba726.nq.gz
│   ├── 3c5a18dee8ab2a6f9ebf6f2a6a17ca3c4a3624e5.nq.gz
│   ├── 3d187266f146fb216a04537da37dc5df0811acc4.nq.gz
│   ├── 3dd248c6797df3e5be9380b1a749df680e35b339.nq.gz
│   ├── 3ffb9c384dd3b407dcbadeb1e74fcda4a96fe6ab.nq.gz
│   ├── 40205b11eb576e28d9f39f4a5bbd00bc33e6d6c0.nq.gz
│   ├── 40fa046466c98c2c0e2f186f0a2af00011844581.nq.gz
│   ├── 44469f32a3f0816819c0f9017678ef385f284fc2.nq.gz
│   ├── 4b2c7f5d8939a0f348b4c91c6cca751b13756b37.nq.gz
│   ├── 4dafa8accf67b92e29948ac88309ef48937e5cce.nq.gz
│   ├── 53cae851dd27055cca27eba5e4a32cf6b8e75513.nq.gz
│   ├── 5b80c3d615c3a6a53c4841d7dc6bacf1ddaaaf87.nq.gz
│   ├── 62ee6e10fa6de047067add34b754f2f3155b4146.nq.gz
│   ├── 8a4dc07622c55a1f3228705242ae33ef88ad1244.nq.gz
│   ├── 8c763bf2156fd3dbdb3c762ed99aa22d7b3ead7c.nq.gz
│   ├── 90c4472751df3a9f2d57fb9b215cbb8326a6db59.nq.gz
│   ├── 90e0c1e0b3c888b977a53422ba5637deceef9dbe.nq.gz
│   ├── 91ec06e84d729881a66ec6873ea16bd015f2fdc3.nq.gz
│   ├── a045aaca30d1b38f1e7d56a96ffe7316d2af9c21.nq.gz
│   ├── a98430a895563e6fb1fd73893907f212bc60ba2a.nq.gz
│   ├── ab2411779ac067ac625512a270da48b976b46fce.nq.gz
│   ├── b0e3a4e936c0296d2ae0f86c2c2a277407adb48c.nq.gz
│   ├── b18ed61b888396414f62f469b9ae3a69cbb1428e.nq.gz
│   ├── bd40e5917518479406ec18377498f0d16eca1feb.nq.gz
│   ├── be8b14b2b010c1f1c2b8184ffc21f57c355eff5f.nq.gz
│   ├── c12ae9284452829a11790e41004f0a764062568d.nq.gz
│   ├── c1879b705c7d6853444bba1cb7af16ed26cae0ea.nq.gz
│   ├── c8bfa42edb5250b19098e02c142eab36c21b2726.nq.gz
│   ├── c8d0d24aec8da7edfec0dcde50871dd27240e031.nq.gz
│   ├── cbd32e15b61bc1af43dad11e7cb1995ab35c6be6.nq.gz
│   ├── cc93a75e69ac9ce651b77ab4372e3658ccee4fa7.nq.gz
│   ├── d63f2281e26eb0155e31fcf0ffb6125bd8deca1d.nq.gz
│   ├── d7eced48c974b125b3eaf7de4a23973120e458a4.nq.gz
│   ├── e10b21840cad1eca7770f3daaf495b78d435922f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e85cd9b94c2fc1bb807bb868ddd580fa1782dd71.nq.gz
│   ├── ead7bacaeb9a5f6c4f79c5b7772fbe53ed438b85.nq.gz
│   ├── f5f1da03f2f543a9895461c6a2eb5b3a18d2ab15.nq.gz
│   └── ff2c0415041e0bcd79106d1a3684144b495e7218.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b1be1a39703b8d3b693a0afd8a6ee61ff5078cb8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[databrickslabs/pylint-plugin](https://github.com/databrickslabs/pylint-plugin)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*

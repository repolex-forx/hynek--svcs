# Repolex Knowledge Graph of hynek/svcs

RDF knowledge graph data for [hynek/svcs](https://github.com/hynek/svcs), parsed by [repolex](https://repolex.ai).

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
rlex download hynek/svcs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9a034ff4cc228241c0a759f05cc4bcd9439311db
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9a034ff4cc228241c0a759f05cc4bcd9439311db
│           └── chunk-001.nq.gz
├── blob
│   ├── 00b2a2e3712b71631157d1839097ab08ca859428.nq.gz
│   ├── 02754b1fe0c7bbec911f959a663db4fdf03836d6.nq.gz
│   ├── 057262b1bf99fb4b228fa07524df1aebc58c0046.nq.gz
│   ├── 070188d5c5dcedc230743409f97fc989e1d0bdcd.nq.gz
│   ├── 12e9a167b2b59d5725c84db68382bf4b981c668d.nq.gz
│   ├── 1b46e568c81a3ed627e90ef65bb7a53cbd0c68a1.nq.gz
│   ├── 1ceece02c096a22f803d0d1d26af4ce6b187e4ca.nq.gz
│   ├── 21e80719ffc8cc210a0f31325ee751140df8e0ab.nq.gz
│   ├── 257c7bda36780f3955f7a9a879fea9511cf45f88.nq.gz
│   ├── 297d8930b4e8e5ff9978db9797154964f71bc53f.nq.gz
│   ├── 2b64447dc0c2917b140ffe488636760fdbb34e89.nq.gz
│   ├── 2da6a101c4d35db0fe648b3f52ce3ad49e0c22e1.nq.gz
│   ├── 2ed8b5c78da93f93b672de125d7226aa3f525a22.nq.gz
│   ├── 3260a0f7c697ee61205328ec7ebaf61e84f216ab.nq.gz
│   ├── 32e987ce4dd35b38a0718f5690119900fe53de44.nq.gz
│   ├── 33bb572e7cbd96171b1d1b40a587844af28cb09b.nq.gz
│   ├── 34b194ee3987d976ddcf75a343c8b85536ea1f48.nq.gz
│   ├── 36b1dab41633830f26d6fc0fd3e3dfc8d76f26e1.nq.gz
│   ├── 37958b762cd0ba0643877278e5f4fa16a6a709f3.nq.gz
│   ├── 38fa4fc36ac62b2f221e62176a1d058ad1b33c8b.nq.gz
│   ├── 3ae79bb20f384089816f2b67bc7425768831231f.nq.gz
│   ├── 3b975aa3ffdfeddbeb8f14d38d37276c8a54b080.nq.gz
│   ├── 3cc701bb0ef7ff88632ea143b7125f8a329ff6e7.nq.gz
│   ├── 45a3070b26c65f3c00ab975f8c788967e4814fb7.nq.gz
│   ├── 46042fc34c2823cef18ccb9ec769325cf624d17f.nq.gz
│   ├── 48f9025ba2af9da4e297e28efee4a3be6b532c8a.nq.gz
│   ├── 51df725c6310b12d5ea93ddc4f29e0b113276039.nq.gz
│   ├── 5421462802d0b71dbf2e1249ac91121f0b28fc61.nq.gz
│   ├── 59f722ee47de56b2eb6daebdebfa9ac3341c3698.nq.gz
│   ├── 5bf4e7100c5a4a4e89f72cf1d809e63f1e32b4ee.nq.gz
│   ├── 5ceb901716e6ae97ac70da17ebfd330f8774a31c.nq.gz
│   ├── 5f821bd4f990fe01cc5c7a3ac2f8381fbbd1747b.nq.gz
│   ├── 631812b19c65189140ba19b758faf4752e3b5ca4.nq.gz
│   ├── 681e827ae06ba11fb8c8941ef4737aa5c3ba8924.nq.gz
│   ├── 72083fee482321b1b3501a1c4edbfed3cae3d4e5.nq.gz
│   ├── 7abddc9f385484e97cceadf9be9a07b000e08bfe.nq.gz
│   ├── 7b87a5d31155f26fb4110dcb108d56bd333b5dd2.nq.gz
│   ├── 7c5100942aae489ca04d07d2c69a4d8f6f8470fe.nq.gz
│   ├── 812df520de0bc250f45edfed4d8d1ddf1472f025.nq.gz
│   ├── 850bf01cfd6b932a0d23a4c7feeb16fcfb9639bd.nq.gz
│   ├── 856adf6bb489f8c53825792d72588dd91ccf1012.nq.gz
│   ├── 85b90f1cd23c4da8c09c2ca4d8241a42161931f8.nq.gz
│   ├── 87fa1c79effe315c139e270fb00d0fc85552a1fd.nq.gz
│   ├── 8c51db113cc11ddd02be3e0718e62b597e28340b.nq.gz
│   ├── 920bc6416eee9eb0d56ef8b13e3e108720ce637f.nq.gz
│   ├── 93a848f9688291c7b2172cf99f133675225ad282.nq.gz
│   ├── 94337dc250f9d68d6f1b983439b764b25005eb90.nq.gz
│   ├── 957e65cf05da6eab6ea4af334cec509d491b62c7.nq.gz
│   ├── 95bfd4a847d454a6b4a816ffc382e77dad8f3961.nq.gz
│   ├── 9829be4a8306cbb55b81485fe27c10e8a06d4ec0.nq.gz
│   ├── 990c2bc0c99e729e08b26928288c70a49726ae23.nq.gz
│   ├── 9978c3b777457f6e159eb6ecb0be88fb3d837747.nq.gz
│   ├── 9d41dc28cb65de433929b3a99b3eccbd13fc9b07.nq.gz
│   ├── a5934c0c667958c6d7debed2c7555fa82d8e3f55.nq.gz
│   ├── a871d7f7c676d6c0a42ce6a9f148b70863c60b1c.nq.gz
│   ├── a8d084c0113a88ac7028a334621a498ee68ec070.nq.gz
│   ├── a9c523577bff012509dd4fff7b31aacf2da1cf02.nq.gz
│   ├── aecb03ad78fd90ba64936aabe18e4aee48a281c1.nq.gz
│   ├── b60fb2f3fc00a980c74b039c8ef2de7621f59f5d.nq.gz
│   ├── b8dbbf27fd9044e47f2ada2773f9f5a5e7fbe13e.nq.gz
│   ├── bd33bda91b34859a12faff34b5a47018e76ed1a3.nq.gz
│   ├── be00f79eecd1aa7e5619e275b3bbac57098aff44.nq.gz
│   ├── be2885ca49a31e59bdb6d2dab28ab9a1ca759ec0.nq.gz
│   ├── c0e66e28b9188025a332fa1733837dee111bbd14.nq.gz
│   ├── c2089e4783237591867be7fa633ff401c7ebdf37.nq.gz
│   ├── c8bfb8c19448f81266ac85c2b9735ee74214e7e3.nq.gz
│   ├── ca96e1e138985d36c3c0c35a7c2ba786010b9854.nq.gz
│   ├── cbb865d0c6c97b6c93b07144e560d51959364d2a.nq.gz
│   ├── cd46bd07565aa2cf3aab3580363284ba2fac0458.nq.gz
│   ├── cd8f13c955c804471b882c184e54f4c7e805cf73.nq.gz
│   ├── cfce4ef138488d32ea0b35097b4cfa7b42fb27a2.nq.gz
│   ├── d100f1b905bccec57aea06a3e626d613ca4210d5.nq.gz
│   ├── d11e4bfb991d03eb085116fab40825e4c55f3e63.nq.gz
│   ├── d36aba2671f471e6de8406efe7e6381d26cc05c9.nq.gz
│   ├── d4563f12ae9ed2e021fe7f5cadb335ec6732196c.nq.gz
│   ├── d50bfc4b1b48eccf76e72f740f5dff387cfbfdce.nq.gz
│   ├── d55fdfbbc12db4d6f0e14b5e72423598d136117d.nq.gz
│   ├── da6b2ce6fd62bf6c588c480602f906bf4a1fbddd.nq.gz
│   ├── dd943458b714c3cfa7e47fb9fdcc6b6419958bdd.nq.gz
│   ├── df7fb772734cc1b850a706a628551b42fec1392d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7c5d68f4759257537b0a06ae2ab17ed69cedabc.nq.gz
│   ├── eaa2e3f4ed4fad6a70c10f961fd25b47013a5b67.nq.gz
│   ├── ec8c33334fee0c7b5da22af531a3394e02f63023.nq.gz
│   ├── ee66078a9f52309c3dacb671535f5cc02dc2342b.nq.gz
│   ├── f23ef192818701856d11344e8de471096aedcca5.nq.gz
│   ├── f514cc396abc9b0494449ca1cad12126e8ae8e99.nq.gz
│   ├── f515a533ea5e651300badb7dacd9d0d8a3e2329d.nq.gz
│   ├── f5643bb17c24fb29fbf3dd9ae7f16e8ca028958d.nq.gz
│   └── f7f1af3c0f647be14ace46ab169b3758208fdf5c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9a034ff4cc228241c0a759f05cc4bcd9439311db.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 98 files
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

[hynek/svcs](https://github.com/hynek/svcs)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*

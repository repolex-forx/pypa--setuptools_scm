# Repolex Knowledge Graph of pypa/setuptools_scm

RDF knowledge graph data for [pypa/setuptools_scm](https://github.com/pypa/setuptools_scm), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/setuptools_scm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6146a260634666e5640c1a95f6b6ec138a1cc36a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6146a260634666e5640c1a95f6b6ec138a1cc36a
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a7b00c94e08b86c765d47689b6523148c46eec.nq.gz
│   ├── 01273c3c4aa63381a1bba487a36946da2b43d539.nq.gz
│   ├── 013b7b2a63c175681a4d8ea3c3f53f1f3b511d80.nq.gz
│   ├── 0253ecce79524c22f3291c916135597e02742698.nq.gz
│   ├── 02b98f7246a657eeb2f88e224b9f343a4014676e.nq.gz
│   ├── 03719ace5cea9e8ab345b142d65014b4f1c7a0fe.nq.gz
│   ├── 047ee6275129944f004b005c28912571e6f726e9.nq.gz
│   ├── 04a0d8cefd9dffd1cbdd79165cc0aea73b53d148.nq.gz
│   ├── 06afc6fdc41f7422f3018d4b3949b6ceb7f9b3d9.nq.gz
│   ├── 0713c115b71318f79cad4054a58f5e7045eb3a1a.nq.gz
│   ├── 086e996d1c29fdd4f216fde5ebb1c94e109dba93.nq.gz
│   ├── 0aa1d2a9ca4210b276c86870a0a6bb5aedadb5bf.nq.gz
│   ├── 0aa7c8e1dcf96e077ed1fa56a119b1dd26687790.nq.gz
│   ├── 0abd5196e448b188caae025d187f5229077122c0.nq.gz
│   ├── 0ba44192ac2a5a9d1d91de3828cf33eae40e5cd1.nq.gz
│   ├── 0c21fbf143d8731ba160a16739ec62a322dc0c2f.nq.gz
│   ├── 0c7de5e6845f3b64d9fbd812d47369b18042811f.nq.gz
│   ├── 0e98c9154a8ab74d89fe4be0bfaa54a638f78042.nq.gz
│   ├── 12fc415544d81f55003bfa2b17bd03dc6b6d94c5.nq.gz
│   ├── 14469692855cf69b94361b535b6bafd5f214a745.nq.gz
│   ├── 148dfff7880fcfa270695cea8051f7e3c5e72e7c.nq.gz
│   ├── 1494a2d1eaefaf6e41cad174ad6af78b8b261e40.nq.gz
│   ├── 14d86ad623010057a726185db3690c2d04126984.nq.gz
│   ├── 172171bd33148cd3cf28f7cb3a67e2698c0f2be4.nq.gz
│   ├── 1899ac3b16b831e9b5cbb30bba954ded02c5943b.nq.gz
│   ├── 19327af00dd48ea1911eab04b3bf93fa581f72a4.nq.gz
│   ├── 19a59567fbd8b6353a2ad3c7ed285e0b5fa4fbeb.nq.gz
│   ├── 1a11488231f581f615ddadc658aca5bbc1d6e8e2.nq.gz
│   ├── 1a7a2274e9f530bbcea8dd4970dc88c434dc3f99.nq.gz
│   ├── 1cc17ba78a4d67abbf8ffc021c5608b05ff82850.nq.gz
│   ├── 1cd093a3df565ce2a929102b98d95dd649b5fb7c.nq.gz
│   ├── 1d3338629a5bf73211d1da37bc96b22f58757e81.nq.gz
│   ├── 1ef6ba5c819e17223a9991f2bb03f60fca514f5f.nq.gz
│   ├── 1f93fbb4339333f83c5a896a1fc84aa7cd9c3404.nq.gz
│   ├── 1fdb05282b7d860a4646dee950fe0a00c616a8be.nq.gz
│   ├── 20ce91d31a1683614925a6a82ba6a763e3c2b982.nq.gz
│   ├── 21333c94a667f185302412a38f9a274d12931b23.nq.gz
│   ├── 21661e460d2fe939c31c64c484c7830e9f6430f4.nq.gz
│   ├── 2247fc35863aca7c88a7d504dabe9ea445bf931d.nq.gz
│   ├── 238deab28280fa2fcbe7275bc7346e82ac6ba4dd.nq.gz
│   ├── 245b9c73b345ce6987b0b594fa792c18ecd610c3.nq.gz
│   ├── 2486bcc16f3b93d69b407e1e448479724ccb7f4b.nq.gz
│   ├── 2503d23893f406ed77869726a48e979964adb93f.nq.gz
│   ├── 28987f0dadad904470e32648aad98c57767c6cfc.nq.gz
│   ├── 294e87989b4e2f16a4e52fedf6d8f8cdb7c94dba.nq.gz
│   ├── 2b0c486f55015bb97d9efd8a01dd026b2c86cd8f.nq.gz
│   ├── 2b181ff6f9c0133fe567ce9bc0d8fe13034f457d.nq.gz
│   ├── 2b39fe864cf499ad1b2117a26cfcd9e77fd54a47.nq.gz
│   ├── 2f2994bdcb58d3506f176ac6ba8e3fd6f7d9c70c.nq.gz
│   ├── 333272204298e652a80701eef2d578bb4f86da6e.nq.gz
│   ├── 37f92f1970a59f510ef09754044b87e44d247592.nq.gz
│   ├── 3e6adda560d1464999754221a2303f95105f1265.nq.gz
│   ├── 3ea521296674f7e26cda6e3430b3c9fde44519ea.nq.gz
│   ├── 3f56d42a0c635a4bdeabaccedb7b42c852fe4edb.nq.gz
│   ├── 3fdb4ad5996bc05819270aa98eea789723a74bda.nq.gz
│   ├── 4037ad258d979781810eee62fc210e6be1b3b7c5.nq.gz
│   ├── 41a46689999cf1d9af07699df22d44ca526ebc0a.nq.gz
│   ├── 41c7096204209919cc76c40888db34d4b3a5235d.nq.gz
│   ├── 430acc27a05b1887e9e00ee67cf47e6ed341e049.nq.gz
│   ├── 439fa674c68dd267f96a0d51f962f4266f2b4b13.nq.gz
│   ├── 43d1424d2174e3089e00b92a045590dcfe40b459.nq.gz
│   ├── 470bff98c392ae84fe9a592b4d8bb658383e5c48.nq.gz
│   ├── 4c1022148f210ddbd77cc3c20b5ce9b27bd4b7bc.nq.gz
│   ├── 4d36db1fd943d041d0e4d3d8b6454f1448799514.nq.gz
│   ├── 4e70b1843a413f100f6899c61a550f80dba62e52.nq.gz
│   ├── 4fc1cea601cc3e9f5a316e1f7eff235572d59e1a.nq.gz
│   ├── 505274b82fcd2b9cf382e1c11a6ea6f1c3c602e7.nq.gz
│   ├── 52240ef71313166dd72022e17bbe24a8b20f74ce.nq.gz
│   ├── 52ca496bdecca2252c78b4a65385bcec538fa09b.nq.gz
│   ├── 535cc2692bb720c9352d9328cd0f0d95029ed887.nq.gz
│   ├── 53a16b8ca607a99898028d7bf12e89c5832eab59.nq.gz
│   ├── 548c3c159fe16d5655c1c890f7710e2acfac0c3d.nq.gz
│   ├── 559e865f62ff4fa76042690c21d68ac9d8c154ee.nq.gz
│   ├── 55e9938c2d3cf4eff2426b84740f154aa4e63aa0.nq.gz
│   ├── 565d60fde2758e6f08ff8ae8d79d38788afddcdb.nq.gz
│   ├── 56781794484f6f73265f12d24695c2ffaece62d2.nq.gz
│   ├── 56e5b397fed64e5cf150148fbcb564cf75d18492.nq.gz
│   ├── 57864ed54e1cf6cbd0c5b013a23b38f2e1937d70.nq.gz
│   ├── 5945a1cc6034fc1c1064606a46a3a8865a993b26.nq.gz
│   ├── 5a6e9521448d29d839671ab54fb4d7e2681c86c5.nq.gz
│   ├── 5a817c7f73bda7fc1bf2c18734a69f8a03ef63c2.nq.gz
│   ├── 5b2032cb3569a8d1d3ec2eb7cbc2126a4ce62bad.nq.gz
│   ├── 5b48e3b8f55287d4d216e35cae477f42003bf61a.nq.gz
│   ├── 63489b5e67c64a82d08224996e173e871dbbad77.nq.gz
│   ├── 63a33209628d9a8d833fac9fd802bb25be342932.nq.gz
│   ├── 64937f66e154bb177bdb58a96714fa54a12d8a60.nq.gz
│   ├── 66e3cb078840682bf688845ae33a1d1ca6ba338d.nq.gz
│   ├── 683e569debfe5a671ee0f59a9d58e2ee30c6253b.nq.gz
│   ├── 68d50a9845e636c0a7a1973cd64d9f6216b468db.nq.gz
│   ├── 6ab9c20d352e283b1b93e2b29a7197434929dd11.nq.gz
│   ├── 6b2a40ce2fe5a7ec8d69dbb58b96ec6aadf093e9.nq.gz
│   ├── 6ece1ba7c151cf7e91dd9484e3312d99795d947a.nq.gz
│   ├── 72dd3f28afded506ddea9b019c9e2dabd00fcfe2.nq.gz
│   ├── 73b0282d6af4f20da2a92ca70eeede6d4843c32c.nq.gz
│   ├── 751fa88fa827feae90adf18d329883a8fc058796.nq.gz
│   ├── 781821fc00bbc659993706d1c0a9ee18019114f9.nq.gz
│   ├── 7843815cbd4d0c12ed70bf90c2d498ee459dc02a.nq.gz
│   ├── 78fe5d7dbdfca7406b623919ff494baaa22525aa.nq.gz
│   ├── 797edf8741eb2ed7ab5fe63ec5606629bf99016c.nq.gz
│   ├── 7af58bd23afeab1bd668d8b74f9bba5effd29552.nq.gz
│   ├── 7b515ede54a8851e19bb40fc006f99fd3bd16f0c.nq.gz
│   ├── 7c5100942aae489ca04d07d2c69a4d8f6f8470fe.nq.gz
│   ├── 7dff2d0efef4567ea00314c7dd6915cf7f013aa9.nq.gz
│   ├── 7e67fa76967127bab570ed9e6b3a6996eea71acc.nq.gz
│   ├── 7e6d0efb88a0a1d44175255c54a19016b42fc851.nq.gz
│   ├── 8586f64ca07d1e0af7af1a4076108462ace17579.nq.gz
│   ├── 85c8b4ba9d3ae323014328d6d364adeeb4da81a1.nq.gz
│   ├── 863a9cd120cded62e450243d2ea6db2ba050b93f.nq.gz
│   ├── 893a9ad48938951b2ebce25644ae1be7acd6d467.nq.gz
│   ├── 89de354795ec7a7cdab07c091029653d3618540d.nq.gz
│   ├── 8b4a96e02b4f03e53c3c11e97a9cc1a98e70ce6f.nq.gz
│   ├── 8b56c892cc55f2beb3b1e08d009ed2339875f4a1.nq.gz
│   ├── 8c8b188822b1907c45d3712b78316ad44a590354.nq.gz
│   ├── 8cf1420a3c0c07c77693a3d9e81743b79d188bcb.nq.gz
│   ├── 8e5d37fe24ec7898deae4b05a4f2caa6e6c14142.nq.gz
│   ├── 8e943f1cd863f31637e56f1af09569adfbb0cb66.nq.gz
│   ├── 92ee278a73c51f7edf24999a855541f89134603e.nq.gz
│   ├── 93b8b46f14e8f74ef8ccc5f163e9202e574818ef.nq.gz
│   ├── 9b9c72c6dfc7f0f726d4e5e2a0f1eed3fad915af.nq.gz
│   ├── 9d1e0987bfc323000b570d680343f00c53ddbc3d.nq.gz
│   ├── 9e4d507f19b66103225efec2af74425e3df998dd.nq.gz
│   ├── a0a846ed2929956d8dbe565f0ce75d9dde0fa53c.nq.gz
│   ├── a0ad8d1354d579237d4a375f9f8ef4bee8c958bc.nq.gz
│   ├── a287eb6f0ea56bf8a341912dc65e2d3b81c5be45.nq.gz
│   ├── a30582fe4c8ba2ab3ef9eaa5b89db91ad40a6d27.nq.gz
│   ├── a315b3bfd8eb496a51ca6c5f5fa97d21824cc3d8.nq.gz
│   ├── a3382ae9262c32454d44a4fcd2f2dab5a542bf68.nq.gz
│   ├── a9a455e47bd86dc5265a371d2dc639fa12497c19.nq.gz
│   ├── aae41a632fcf2ee5bf8af4f6209761fa5f72d4f7.nq.gz
│   ├── abc08d270fa2bfbacc523b658e2f9c2067087621.nq.gz
│   ├── ac0b95bcb416708b358ef1bc09d6ee40fdd9ca60.nq.gz
│   ├── ac779abfeaade7e70f6a3f51d589a62fd711c3e4.nq.gz
│   ├── ad3a4a006cfda235a352ae9dba5459eaf46bdb14.nq.gz
│   ├── b0471fd16c6a083225918cc06d3aef3849d10ad4.nq.gz
│   ├── b1d321edf0d270e8d9e2624a8321730d4d91e478.nq.gz
│   ├── b1ee29ab24dfdc763b44ef410a1834f1f7244879.nq.gz
│   ├── b2b89450fd55955b3c01d3e80214b4d27dae2358.nq.gz
│   ├── b33ac24ae80fdb5f748f815cb7c1b365464bba9b.nq.gz
│   ├── b4e1b4434573ec692d7c32ce9707842e0698b59e.nq.gz
│   ├── b544b5fb33928af9f3a578d8bef82e0430c8a949.nq.gz
│   ├── b5976c776c238409f2ef16cb363a7212e9b51f23.nq.gz
│   ├── b68ac159dac1860a282941a9c940c28b8e99459b.nq.gz
│   ├── b8695c3a017c4481d5ba54318a5d45fa1c487fb4.nq.gz
│   ├── b9f72557376229d61c5f3172416346cc8a3ce333.nq.gz
│   ├── bb8a28f13902b26a41b6674dbded3fdbf773f425.nq.gz
│   ├── bc8b6a12b9d5ab051435ff402029654760b3db95.nq.gz
│   ├── bce5ed5809c3646f18aae54ecc950e96b161f269.nq.gz
│   ├── befa2e50083758498a6310eb7b51ef40548b60af.nq.gz
│   ├── c01b7b15625b42008c80f2cda0d1f71d663b8d0a.nq.gz
│   ├── c0c71fb17c92ec1daefccfd67513183a62a1668f.nq.gz
│   ├── c199cfd64d4783f1e3afd0ae773510814c1332cf.nq.gz
│   ├── c4f1f99772322ab8f4095111cd8027836cfdfd66.nq.gz
│   ├── c63b0731989bc8d9a70c4c9e189271a353532906.nq.gz
│   ├── c6d218a0695fadb30ac1172ca926e7af900ac7c6.nq.gz
│   ├── ce66c1363b4e8ba890cd9ed4dcb39962ca3476ca.nq.gz
│   ├── ceb92c05215f593781db6aa2a835bf25b9097a47.nq.gz
│   ├── d0e5db6842e6e6628e408567b06f2e8ae163c588.nq.gz
│   ├── d422aa930b69dfc9174d61a0248146f3d6c9df45.nq.gz
│   ├── d5808385bf11ebbf9261437f5e85f8741c874434.nq.gz
│   ├── d5a0d90cbc1eb7a2249c7d1890e3c63819e9b73b.nq.gz
│   ├── d5ba8ff1572b93ba373043191582c96f07d0ee61.nq.gz
│   ├── d62bb4d4898c34dd6387c95abdb493c17bc4b678.nq.gz
│   ├── d6b70462d77fe2ea4e4c8c3f37944cbd6316c2cc.nq.gz
│   ├── d80a6dc0cdb9f635ec2e85ad7ff2ef34bc67c97d.nq.gz
│   ├── da222302e073a9f62ee2dc198b9cff5d71e3cba7.nq.gz
│   ├── e014a017e7ddca0c72c2c036332699604ecdbc45.nq.gz
│   ├── e0c3bb86f60e325a411f8f87fda2d23ab0155e47.nq.gz
│   ├── e1c6e103895c002b744dac54798af2dc93af9cc7.nq.gz
│   ├── e37d83ad428c157a1b68dafa8d96c8b32a3df3b6.nq.gz
│   ├── e52ce092c3b1f273c7e402fab5fa49d5d8d9f404.nq.gz
│   ├── e5c2b26d9160ac6fe1c616ac844eb2f1e567f750.nq.gz
│   ├── e5c5cb87253b350e4609acdaeb34ec91b01e9991.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e845ca76dda1770774c921ce30177f28b7758f76.nq.gz
│   ├── ea449520b15b87be48f5a60dbd4c5963ce71408c.nq.gz
│   ├── eaaf9943dd13f0ee691807629ee99d36f36a5093.nq.gz
│   ├── ed123ad2dadcc674ab9dffb38a374b8450a64bea.nq.gz
│   ├── efa3d2165633758b697e2a921a7f464cf88cac62.nq.gz
│   ├── f14eb273a9ba6a97d419a0bc4f7337766ec40c22.nq.gz
│   ├── f1abbce18c0a4bf936eea48faf9722e79c5341ef.nq.gz
│   ├── f32c5b55aba317f46a50badb5387096f1affae29.nq.gz
│   ├── f34e4d8a0a83a50a02d37fd05ad11cf26b880752.nq.gz
│   ├── f48fc13103ac9460fb7d7eb0640d038a3b8548b1.nq.gz
│   ├── f6995ccfa20f344ece4e932dd7fb8bb31a0578b2.nq.gz
│   ├── fa914e4202e2d6359c56d74ab018a120cc490d48.nq.gz
│   └── fb89435793bb12a6cb965e49c9fd0fa315208f40.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6146a260634666e5640c1a95f6b6ec138a1cc36a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 194 files
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

[pypa/setuptools_scm](https://github.com/pypa/setuptools_scm)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*

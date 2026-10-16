# Repolex Knowledge Graph of glue-viz/glue-plotly

RDF knowledge graph data for [glue-viz/glue-plotly](https://github.com/glue-viz/glue-plotly), parsed by [repolex](https://repolex.ai).

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
rlex download glue-viz/glue-plotly
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 127c20875b1b004a358c59519d63b3dafd66276e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 127c20875b1b004a358c59519d63b3dafd66276e
│           └── chunk-001.nq.gz
├── blob
│   ├── 01a925c42062318d3790ed2982b3a11a26543045.nq.gz
│   ├── 04b057457875b99a1fb0fad1b97fd69fb21fbc6f.nq.gz
│   ├── 0526b01f7ee387e4442079f253b83cb2d6e437e5.nq.gz
│   ├── 0561b6480e2d0451d8a42349c8d1a0a90bd931a8.nq.gz
│   ├── 05d0320ce01c50933f5825e5188ff9ef0ee8887e.nq.gz
│   ├── 0f166e41b4de143dda2737b80c7a6da8edd1c2ce.nq.gz
│   ├── 102de4a8561e654c5055066cfad9823f2bad4e2b.nq.gz
│   ├── 118afec9b9450b5d935e84de795321a6bc27d8bf.nq.gz
│   ├── 1450b210919ea27724d536be2ab63d62028566d4.nq.gz
│   ├── 1560982e125fc4ab2b2e5016dbfbb690cadbc4fa.nq.gz
│   ├── 15bd323a682eddfd3a682b90f978c20eccc1966b.nq.gz
│   ├── 172efd3a56c1d3bbcc99f86f34a73e7b6efbeae9.nq.gz
│   ├── 1765c3b401c3bc69c612ee23cef906681c966bbe.nq.gz
│   ├── 1a06c53cc35340de67062b6e61d9f4b712eb48d0.nq.gz
│   ├── 1c024e2e2f3e0bb89dfb4e5de3724faae0ca5519.nq.gz
│   ├── 1e2d9bd7c82f2953d1e933fbee8e4c7a76f1660e.nq.gz
│   ├── 1ecba0b1dfd293389276db536cbe0e3a9ea809f5.nq.gz
│   ├── 20708eb195eb80db8092b282b2648f95135d2be1.nq.gz
│   ├── 20eea7af43b6d5f4a1611f513c569e46e949fdb1.nq.gz
│   ├── 212d39c00683fe4882de62850859132f29888414.nq.gz
│   ├── 25648e4dc843a54d0de3ad00cedac1e7419e35b7.nq.gz
│   ├── 266b1738fe8da524f90fba5c8ed70f30f6992e3c.nq.gz
│   ├── 27225596bdc78726dbe909eca374939cfb40e72f.nq.gz
│   ├── 287022708056b2a67b7b2cf087455f3e1a39bcd4.nq.gz
│   ├── 28c6ee244662ac2132360171ae8fc1538280824f.nq.gz
│   ├── 2bdede53677c4505f08f5e6e6217412bab17848a.nq.gz
│   ├── 2da9c3b8d6aed99b336c1c1c2d806e7759abd596.nq.gz
│   ├── 30336464f8f695a2b4a9345e966440091b6271e5.nq.gz
│   ├── 331ec406656bc0e423f2bd57bb22c98ae6ad27bf.nq.gz
│   ├── 332e7cf6a3898a2f8700fc509b082a47fbdf8f66.nq.gz
│   ├── 36a2a4bcab8be422660b6a397483fc87114e5f6c.nq.gz
│   ├── 3d1f7826c51a700d17b8482e675ea5b75acc7b38.nq.gz
│   ├── 3fadb19095e0072ee355f9e0ae45d0327960a633.nq.gz
│   ├── 402fe2e1b96cafc6978bdc92378aa394da502cf4.nq.gz
│   ├── 419dd50845f86d596c1c3d4eda2869d2aed1e1d2.nq.gz
│   ├── 41ef39ec4a47a551935a0d8fc5459492a1af20ae.nq.gz
│   ├── 4464e3a8c348b4d2a88ed8548822be911bb0d8bd.nq.gz
│   ├── 46da50fc9d3d543707ce9a2b670c3c4905a0d0c2.nq.gz
│   ├── 488b62e89cfa195dfa93765b9e1b0086241cd876.nq.gz
│   ├── 53de030f409ac8cfa283266bb2dedbf5a6c1dc6d.nq.gz
│   ├── 574e4eeeaf22a32b77e7a302f41b2bccc8e562ff.nq.gz
│   ├── 5933f96aebc4bf6ab25c7c7a49844f3131d8bf67.nq.gz
│   ├── 59ae4605ff7d3931746ada1058588ddeda6e1679.nq.gz
│   ├── 5d90705f42e21fd3a18b93249b43e4e6877cff51.nq.gz
│   ├── 5e2016fd35441459536c7131e3363b4ee1a54137.nq.gz
│   ├── 5e47043497fadc2a9cbe1fc763a07d1dfcccc6ee.nq.gz
│   ├── 5e4e1c474cad1c9884ac200894551a9840653107.nq.gz
│   ├── 5fa72db9a1897bc565ba87e1afb0c1d62f9803a0.nq.gz
│   ├── 60d5dbe7feaacac9ebbac28aae3a314204cc2890.nq.gz
│   ├── 641480e1bc8b4e0a4a8c575e0d6b5e93038dd1ed.nq.gz
│   ├── 6617ec4ad818f215e14b850134c4924d16c63973.nq.gz
│   ├── 6711c9d243334a8d4dcd5d825306e0835ff3c3d1.nq.gz
│   ├── 68b772575a9e6e490b56e6363a9bf43c097ae236.nq.gz
│   ├── 69d583cc5fc6bea22b1dc09949f88da0c3a9ded8.nq.gz
│   ├── 6d317b2d13b4800ce400ef59a8a24e8350e22f1a.nq.gz
│   ├── 718160aa695eb2e692907b4fb8fa640f598cee67.nq.gz
│   ├── 73aee98276ebce950806b955855acaba9ba7f6c4.nq.gz
│   ├── 74fbb001c283dc0b458ef4ec8a69fbfb97c5bae6.nq.gz
│   ├── 7566ecac25fbb02fc11480410308dc1f4967e6fc.nq.gz
│   ├── 75cd8a3354d358c85560fcdffbe6e09c6db8744f.nq.gz
│   ├── 7671e2666811f708b04e20bc79194d481fc9e86d.nq.gz
│   ├── 789b5ee1b8c888b08ec472e67320a074fc6664ec.nq.gz
│   ├── 79269dd3477e2b5ad7dcfb98a68c95bfe3bff4b0.nq.gz
│   ├── 79de62cd6c1e5f1608a7bc6a1241186506ca2475.nq.gz
│   ├── 7ae491aa51a6eb7e5324404e3b969903ed92e736.nq.gz
│   ├── 7da14cf81de011460e06ce61711cbea32a613f1c.nq.gz
│   ├── 7da3b10f29df6464d334f4241022f94e0d8824da.nq.gz
│   ├── 7dbcb537e254938b56f6d16349c2f087dd1dd6d3.nq.gz
│   ├── 7fcbfaa4d73ca37cf1b40e29e5bf8df7fd3637ed.nq.gz
│   ├── 81bcf1c97808293b19ffd6e8149e48775d6a4a95.nq.gz
│   ├── 84b9236e29528071e6c770a59abc72b271f03934.nq.gz
│   ├── 86ce72642b4bfa48a96923b80802b8e73c5218aa.nq.gz
│   ├── 8d8ea2fb608d6087277b89d4aa3904a46c010765.nq.gz
│   ├── 9040a9a9b0645f7bb3a5d752650f846dbc6d1fb7.nq.gz
│   ├── 90dca609c63d746157ea7811d9bb05951a48725e.nq.gz
│   ├── 923f64431e9731140c7f17b433a84223b47771a7.nq.gz
│   ├── 96d50ae36cbcf3d6f8cd2e6e6daf83553f571a71.nq.gz
│   ├── 98fbb4963a790f631ce4c9785f5a989d159658f2.nq.gz
│   ├── 99068ccb9158a0e34b581264d762c2f9e78e2ce8.nq.gz
│   ├── 9a6c9b28b57c71083adfd88d9485e45d3fb90fff.nq.gz
│   ├── 9b41d60f8aa2760bea4deb5eff03ff35a318fb62.nq.gz
│   ├── 9e94a5be72d8297fbbafb885ee590b28f6caa2ff.nq.gz
│   ├── a03ddc552aacfb5fb97bdbd8adf1c1c1e6c343dd.nq.gz
│   ├── a1d9b1eb1cdd59e4d45cddc593720fb1d2cccaf6.nq.gz
│   ├── a3be285be394f6707807652c4927bbb59b7cde2a.nq.gz
│   ├── a63454de57047d72b9e35b8b573de488c102b38e.nq.gz
│   ├── a761be14148172ec5a9acaf5f4e3c804f8d32ba2.nq.gz
│   ├── a815ba7c9f8108fbeecac71eef4f392aa13dc437.nq.gz
│   ├── a91a2e913ae14bb7566acfe8426753fa39f3040e.nq.gz
│   ├── adc70f69fb8d6d90e0ff0b9aed05d92125719f13.nq.gz
│   ├── b1304be0853d773b25eacd47564c8d8b69fd136e.nq.gz
│   ├── b1f45a4cf0147b66f99e8b130eecc7f4527c176a.nq.gz
│   ├── b2890addb130df51b437dbefeb0ff6c5ef3ab697.nq.gz
│   ├── b63c1e473a378b2ddc71d890ec1503baa29e6878.nq.gz
│   ├── b976ba6f4085f0eb048a9790cd6f2a823bb1c9a5.nq.gz
│   ├── ba82682e6730ba9cafeddf7047f726a8e5a3db77.nq.gz
│   ├── bc18f59acc19413f18f9a92eabdcb942826ad2ec.nq.gz
│   ├── bed3abe26a6dc24685bfd170068f605bcc449f95.nq.gz
│   ├── c0d9c40c155a8dc24f8d6a794695a7f507d4ac20.nq.gz
│   ├── c2d53328f23b2a71d72e6dd4cddb3758a1941a69.nq.gz
│   ├── c83c6cc02cd918ec8e5dbc2a0f369bfdf5b19e91.nq.gz
│   ├── c867443441fbe560b5a042069747e5aed133e006.nq.gz
│   ├── cbf2752c6b0d78d25052963f3b7223349c33d7fe.nq.gz
│   ├── cd483867dbfdf80c162536f725113f5c3eda5c53.nq.gz
│   ├── cdaa88b687b14c76a6e1fd97910957c1afee4825.nq.gz
│   ├── ce36394b2254d3b3d7ee9abca30f75dafccef4e6.nq.gz
│   ├── d1854160004ec7cc485771cbeeaaf0b487a2f005.nq.gz
│   ├── d1d423ae616a60d3c70a521b12408e00f798b235.nq.gz
│   ├── d578459d75b872ca3b25306ed36528731ca2effb.nq.gz
│   ├── d894b40f4680af96d09ca3fb96b2db1553761bd5.nq.gz
│   ├── d9dd7ea143d453dd278220e7c2552f38a9f4512c.nq.gz
│   ├── dbc0558448310478e8f60b02dc04f7c4cb6c1232.nq.gz
│   ├── dd14774fda32eb307d4a51fd0866e2b290c16031.nq.gz
│   ├── dd6d64630561f125bc1056cdafe8094266251777.nq.gz
│   ├── dfb680d2535515c7e74a3fee243a2db6ce114ca2.nq.gz
│   ├── e5892d3e53a8eb65abe7de14e09beccf03061e62.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7f8c73edbc8f90c728b2ad60171634e368755e9.nq.gz
│   ├── e974afdc4041ddf7efc4a509c38f15ff887610a8.nq.gz
│   ├── e9ffe8f19e83090a8483d7f13f60985eb678e12d.nq.gz
│   ├── eb96f161e1746bacdd5c31a794fb1f8e09ff0b9b.nq.gz
│   ├── eddf91fc1d54ba08bc8945eb6b257adb44f46e74.nq.gz
│   ├── ef9c48ef771bd5d488690d9ead181e7a99627da1.nq.gz
│   ├── f1ef8ffdb59e3c495e14323955c7a626bf47466e.nq.gz
│   ├── f404643c39bcc96d43ed15052bc0f0bc084eb6c1.nq.gz
│   ├── f4cb1ae5f0febf380015d9e248214961549fd92f.nq.gz
│   ├── f703810aa26faadac36312de5912061775bd0244.nq.gz
│   ├── f837985008cfbb292b28049b167f7f67e4630cd7.nq.gz
│   └── fe349aeac1e5f1bb1d7803244d406c95f6bc45ab.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 127c20875b1b004a358c59519d63b3dafd66276e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 137 files
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

[glue-viz/glue-plotly](https://github.com/glue-viz/glue-plotly)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*

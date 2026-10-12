# Repolex Knowledge Graph of graphql-python/graphene

RDF knowledge graph data for [graphql-python/graphene](https://github.com/graphql-python/graphene), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/graphene
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 82903263080b3b7f22c2ad84319584d7a3b1a1f6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 82903263080b3b7f22c2ad84319584d7a3b1a1f6
│           └── chunk-001.nq.gz
├── blob
│   ├── 01e89bf30d5e0307ac0251f5498a6663889f4760.nq.gz
│   ├── 02e29a350e08eaa225844d1d7fb970220fdab417.nq.gz
│   ├── 04926e7aa5e085aa3c9c961b8f1b91aed855f4e9.nq.gz
│   ├── 05b7fd87e30413124b5cf8245acd8c14950c7121.nq.gz
│   ├── 0608b01668d848b3457c053f7936c30e40b80950.nq.gz
│   ├── 063f0cd957e14773ec526f04762b30bf10e84793.nq.gz
│   ├── 06ba848720dc0e99f2afa4511af461da77190b14.nq.gz
│   ├── 07d81ada6edc775dc4f8902cac745b0e88edf99d.nq.gz
│   ├── 088e62cab6e00daa548fcc6e34fd5ebf5d202ae6.nq.gz
│   ├── 08947707370424db19a5edc6c208475787f8c454.nq.gz
│   ├── 0d4ae7a6e5d4a6798794c6f798863834a48debf9.nq.gz
│   ├── 0d7bcf80c95f7e301ef9c7204c36abee93c61f33.nq.gz
│   ├── 0ed654c2ac3888866e88891bf54ef34ac8d1c373.nq.gz
│   ├── 149ac628d95c0c3ffa41d5325c8922385499fbc1.nq.gz
│   ├── 16ac24e8751a341cf06ac306ee6c382d4eff4e46.nq.gz
│   ├── 1813d9284008ae6cf23b1836531e8e65ed4533a9.nq.gz
│   ├── 1976448aa98452d081e2d4a0b498f9c1ca92cd42.nq.gz
│   ├── 1a3453e97ef0578b7728aa0923bc65bd8d958e89.nq.gz
│   ├── 1ba48bd1d224475d652210e7a28dfebd9e0d2950.nq.gz
│   ├── 1c007211fba2599554c3c62b9e9f0d33f775c6a7.nq.gz
│   ├── 1c0e2599afb615a00b63032afe7be0b2e4475cc9.nq.gz
│   ├── 232836d1f115bd66c670dfa507ee504de81f3f96.nq.gz
│   ├── 235ae535c46de542122b5ddcdfa59119dae7e29d.nq.gz
│   ├── 25642c343a4b5c030985a93c5f37b7285a7b5d81.nq.gz
│   ├── 257f48bef9cb460feb9566a46d129c04ed07a2f0.nq.gz
│   ├── 257f6b4db0a74670a763a2334c8e89f194d287d6.nq.gz
│   ├── 26c697eca1cf85b35ad8149151849ba43acaa7b9.nq.gz
│   ├── 285dbb20d50f131307b454760e31023745c3e631.nq.gz
│   ├── 294ad54e7ab7e0af8514f6d37e792fc9039b7ae0.nq.gz
│   ├── 29c1508c4b889edc26da2a8a7e2840f0067ccc57.nq.gz
│   ├── 2a214f0642e325a765f32194cdf72cea76d7856e.nq.gz
│   ├── 2a55245d2f735826503606909e722bcca029495e.nq.gz
│   ├── 2de21b3671948f073c0fda108ba5b29de24c12a3.nq.gz
│   ├── 2efde25fe1a8c01b1c5a0a7b1f2ae9128a13fd54.nq.gz
│   ├── 2f4a4b7386576598daf1c218e7e7208e3171f81f.nq.gz
│   ├── 2f70903cacb809d98eafa9505423516b024a0110.nq.gz
│   ├── 307d68771a1b7d284b37614eef69c8c5dad1796f.nq.gz
│   ├── 31bcc7f97b5e6e87389a673c0de271cb8d8de74b.nq.gz
│   ├── 31f515001bca524584ea9ae483ed156919fef9eb.nq.gz
│   ├── 322a3edad2beb1694b1e70a73d8676d07a9432db.nq.gz
│   ├── 338da9823a5c51bc4e5f0985279654db250fb774.nq.gz
│   ├── 38b74909ea6c13f378471739231a1080b5c15844.nq.gz
│   ├── 39374381996bfc665becda97026ba781a21fd060.nq.gz
│   ├── 3b5f7a3b9d2426958d47cc390e152353aec1b35f.nq.gz
│   ├── 3b842cf56fc6bfa373d2e57fcf75d4dae335fe81.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 3bb2b0fde72ef81e972467dbe4957c6a7087802c.nq.gz
│   ├── 3d086f3e99c72057c18e3a0d14cbd892b59b3675.nq.gz
│   ├── 3d10418e5343b4f0b0b03e466bd541292de43c3b.nq.gz
│   ├── 3dd4fc4fbaedd51862ab2263f32af8b637b1957f.nq.gz
│   ├── 3fbf139d1da26084769ca6855d7b39ec7a9985bb.nq.gz
│   ├── 3fe90ded7fbdf8bc1dfab23b093fc912cbd02f19.nq.gz
│   ├── 40bdbe9ccdbdde99d82b22f19acdd2d73d395c81.nq.gz
│   ├── 433f63c340817fc74476ef95ad84cb44468e5aeb.nq.gz
│   ├── 43f7d72681b67bbd4a2c311eaeda17c0bffdd886.nq.gz
│   ├── 4453e2a66679ea9c3b30fad83ea09d0d9697295f.nq.gz
│   ├── 480c5cd16c5a5b2f66492c58809bbc8fe1393c69.nq.gz
│   ├── 49a7d6073d8756217dede67ef331bb43d6e50a70.nq.gz
│   ├── 4a7ad3c7c59baee56da99d857fa88deb0be50324.nq.gz
│   ├── 4af8a413a9fa0a593c8ec0da4ce1942e9f907079.nq.gz
│   ├── 4d4e32a56e024b869164f1872217fd3fd837dfde.nq.gz
│   ├── 4d642d6f51e5f503318da238abf1d6970ccf1175.nq.gz
│   ├── 50c187585d7d95b6438ab1cd0da30809784d33c2.nq.gz
│   ├── 50e5ba68ecfb3ff00b79b16b22c52bece4dc1fa1.nq.gz
│   ├── 5443828133090d0a498fd173bfe6319ca10dfcdd.nq.gz
│   ├── 55665b6b8888efe0b71d31653cc6aa352e329355.nq.gz
│   ├── 557db2c136ebabaebdb525860862ec6196da1474.nq.gz
│   ├── 568b3971713b75ebe08cde0a0c7cb26e87f5765e.nq.gz
│   ├── 5691ac2263ee63ff0ad261df7488d2fd5ad6b068.nq.gz
│   ├── 59d72b24c3fade0e427c1382396bfff5996a689f.nq.gz
│   ├── 5b592a2cd863f885f04209e0e5bb8937ed841b2f.nq.gz
│   ├── 5f10a22e2eb55226fe1f8e513870e2096116df1c.nq.gz
│   ├── 61aa7d0023234304e70007ae4a7f719a1a3eb116.nq.gz
│   ├── 61c99ea455866783b46fb0861f4ae737551c0829.nq.gz
│   ├── 66ce9bd37161a7c28a7fd9de56fc13b0a5da57cf.nq.gz
│   ├── 69952f96d0728bd6c4fed1defef785f1ae12ddb9.nq.gz
│   ├── 69bb3380e37cbf6960e3bd28d858e23759883b7a.nq.gz
│   ├── 6c68b85c1449f9b9adabd38de64dabf76295015d.nq.gz
│   ├── 6ff02c901457174a4e1875aef886c7e534e94f9a.nq.gz
│   ├── 7138bf56c2e395baf42c8c630c6b4e4e31381d9c.nq.gz
│   ├── 72d2edb889ca347f01d3f1361a7faf93e8b4295c.nq.gz
│   ├── 72ff9713350c3ee2cddc7201876faa31a96c6f1c.nq.gz
│   ├── 738660632e427ef9f6186b891eb379329c95e8ec.nq.gz
│   ├── 73a8ac1bc545d5eea8a99666e988c3cf5042dbd2.nq.gz
│   ├── 762e342464e46252141a3317ef6fb8483af944e8.nq.gz
│   ├── 79a80b799e9fb9778faf969eef551c6ed1c83085.nq.gz
│   ├── 7beb975c2b8a3a65ea404a3889cc69f567a61ed5.nq.gz
│   ├── 80181a1bb779cc9ad026e2f3ed8eb118fc00b3f3.nq.gz
│   ├── 806d1be6643b5fb6637653d31142aced11196a3a.nq.gz
│   ├── 8082677a11aeda7a562834330d2c9ed3238a9c34.nq.gz
│   ├── 81860d9dcd5d83dd4178fec3f24a1e3420a4d15c.nq.gz
│   ├── 8369a75177afdfaa2feb7702bf4ec326a7a6cb8e.nq.gz
│   ├── 83a6afefc2334234086b5d638283ee032b17de4b.nq.gz
│   ├── 83cf49e2063c21ec2a7d013da37f735214db79da.nq.gz
│   ├── 8546bc85cd98b5cc4115b7f21ad8a271530c2ee9.nq.gz
│   ├── 86ed78a1c23e17a894ad0232b944e2f740574180.nq.gz
│   ├── 873531ae643ce2c28158257f5c84adc7ea33bff3.nq.gz
│   ├── 8753f299822347d5e7ea4dbb5eb6f3a2399ec2a0.nq.gz
│   ├── 88f3ff1da90ed83fbfee299a5360382458665097.nq.gz
│   ├── 898fac71b69c673e9734aecb79888106a1d8e678.nq.gz
│   ├── 8f799140993566da50625a85d70dc4a40f4503b4.nq.gz
│   ├── 9112718a59d3a5f9cc7de9efc3d460caa67bc423.nq.gz
│   ├── 92d0b1b04ad5cee72f3f115f2d6e2bd063452f0d.nq.gz
│   ├── 93ce31c54bce39d4a0ffe3d7dfdb9f1c2d48b481.nq.gz
│   ├── 95760a9a32d7e34b32824dd8d2951c6696c42691.nq.gz
│   ├── 95a70e7461998ff1fadd9ff0b7b7875fd2e940d2.nq.gz
│   ├── 96286992ec69d584cbe63230432dc35d877fc327.nq.gz
│   ├── 98e92bccb365bc87e128f3a77ccbe49c485b7b00.nq.gz
│   ├── 997efba0fcb59b596632f91007bd934482d16886.nq.gz
│   ├── 9b1001286d7e727b26f762adc36b92339753a8f4.nq.gz
│   ├── 9b80e68878f87743ed8fa4fec740e7d6d3ce7da1.nq.gz
│   ├── 9c8b89d13b2ec072a41cdb3755ee7468ff9915ee.nq.gz
│   ├── 9f92821d565f8720f71b7ccd63863b3d36c35f61.nq.gz
│   ├── a08374daa57eb3182f9134114521e9b4c4c4efff.nq.gz
│   ├── a127a9d2452fcb6134c96336e9504743d23fd947.nq.gz
│   ├── a23c7e7d71a63efd324998038163fadf39b374e7.nq.gz
│   ├── a4a6b37ed864f90ad1e1c65e145faee95b9251ca.nq.gz
│   ├── a6763978e963cbc9cd6e82a550e57e3154cdcd15.nq.gz
│   ├── a816fa201620d12c26f79010c1bb5f587a22fa66.nq.gz
│   ├── a82addc9a3bf0ddb1cd2005dfea1ba1e4f022502.nq.gz
│   ├── ac574bed5672a4ba3698870c1295c4adb12f5055.nq.gz
│   ├── ad5bd77a37f7d10dd6b635b199247c0e9b9b83fa.nq.gz
│   ├── ae228cf9a76c57c10b8b60a3c74fb529d733df80.nq.gz
│   ├── b27d3718e623da14d21836545f5705859b551bd6.nq.gz
│   ├── b55d5dabc2d61217e27b33e4b57d5d8f261cb40b.nq.gz
│   ├── b697c462a2df9f6adb52e2da7b24a65db569271a.nq.gz
│   ├── b964233e1ff1c9d9d96167e0cb02c5e0de519be5.nq.gz
│   ├── b9ac5333856ae86902bd7be42961da2c3f0c7d6c.nq.gz
│   ├── bbb37b7759c0d1805a096a39f93b9342e0d23d8e.nq.gz
│   ├── bc61cd4c60e53148a13ce4bcdb355b59602e1cd4.nq.gz
│   ├── bc992af5c8ce41fa568dfdbbb69b13a8530eb740.nq.gz
│   ├── bceede6ae791b1cacc4661a8a3e71d914ea8e9e1.nq.gz
│   ├── bd311e34a51b8331ac1902795f3d9a9790e2962f.nq.gz
│   ├── bdc312edadcee0d065449c6c94cd5dcacef08ab3.nq.gz
│   ├── bf61555de96f5c33467b0a7c7f71aa0900b8cb36.nq.gz
│   ├── c03c81ba0a4b15baa62ab7a9a286dec81cfba1ca.nq.gz
│   ├── c0d97a697b03b8c8a541635219aa149e41bbd078.nq.gz
│   ├── c37bc75a9f2113aa097a74f59166494bc6378ac3.nq.gz
│   ├── c42383e24a2cb973481eacc1571751f0c8e94443.nq.gz
│   ├── c4ee11d74f34d6c015fce168d0a8173ba600a76a.nq.gz
│   ├── c5521b6c25a7b487411e68c39537cb23fcb0ba2e.nq.gz
│   ├── c6099594c7289336445f7dc926ba9eb5c1abda76.nq.gz
│   ├── c75b9ee9ebf47a9677b28e8a57d59baac4bf0d9a.nq.gz
│   ├── cbdfd8c5057d08199c6ecbe62264b58db0b33800.nq.gz
│   ├── cc7d2da082b57b9b8a54e8940464423891d3ba20.nq.gz
│   ├── d031387b8033c930f185ddca4e066290fc0acb8b.nq.gz
│   ├── d1cce687f1b869154349b944bcd7d28de03c3e50.nq.gz
│   ├── d2685d288b1b08bcd046c95f3a38061133465c37.nq.gz
│   ├── d707c1c517f6c895c231d80c1bab0d7cf459fce7.nq.gz
│   ├── d7efe99634c1c5110e05aad56dd5b18194e03132.nq.gz
│   ├── d82beb33ad6d7e005351556748da55e4f2d206ab.nq.gz
│   ├── d8388f8deed6a5a5564245ffc007377075834ea7.nq.gz
│   ├── d9095d0ac2f35c7bed14f97b49a596bb78d55bc8.nq.gz
│   ├── d9283c4164e39c20d34a75946a326a3912621b2d.nq.gz
│   ├── db858b17b8e1d1edf753a72cfe9ef12e5f664b32.nq.gz
│   ├── dcadb6d8d39d4c0cb6d521990c4c8ea1fe48623e.nq.gz
│   ├── dece5e8b9de48a58e4525fce391430c81112d8af.nq.gz
│   ├── dee009c70cc18fa72b6ced01021354015b31d58e.nq.gz
│   ├── e079ab4ea702763692e44869be67ba73fb8d7750.nq.gz
│   ├── e0f286634fa19b08129ff9a81fe0d5f952884250.nq.gz
│   ├── e117754fe81602a0609b6d556fcc4f0d7d3dcfdf.nq.gz
│   ├── e23837d2764add931cceb40359f58d13aa98ef94.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6fce66c98ed2afcb4846a3219c27a6ac6e78e96.nq.gz
│   ├── e7ededb0b1f5011244fc20d92e97a002f6cec25f.nq.gz
│   ├── ea961b25d75958e7af2bc0b4359961aca25e1bb9.nq.gz
│   ├── ecf46fbaef4ff467eaa00f9304a6f00a1c9559a3.nq.gz
│   ├── ecfa9da7ea4edb3200a07086c61c39ac2b8d2c77.nq.gz
│   ├── f0401bfae232331c0f626e752c77255f1ba3b6e0.nq.gz
│   ├── f142d4a69b6f9731eefd781b849865005f8f2604.nq.gz
│   ├── f26259d363a8b5f1ec2ff9752b2f7ae29a40133b.nq.gz
│   ├── f97b59176df1a05bb3bd87a1b18bde9291cc23ac.nq.gz
│   ├── fa2a6ab3717e411f192edd52dcb5a4a82b7ac6bf.nq.gz
│   └── fa405179acec80a5a41301faa820440967765718.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 82903263080b3b7f22c2ad84319584d7a3b1a1f6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 182 files
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

[graphql-python/graphene](https://github.com/graphql-python/graphene)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*

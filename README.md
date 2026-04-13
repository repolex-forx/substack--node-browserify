# Repolex Knowledge Graph of substack/node-browserify

RDF knowledge graph data for [substack/node-browserify](https://github.com/substack/node-browserify), parsed by [repolex](https://repolex.ai).

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
lexq download substack/node-browserify
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d1d3fed4fea333f5d7a3b933e7ff12b045112322
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d1d3fed4fea333f5d7a3b933e7ff12b045112322.nq.gz
│   └── repolex
│       └── d1d3fed4fea333f5d7a3b933e7ff12b045112322
│           └── chunk-001.nq.gz
└── blob
    ├── 006521e560cb014d748c5e6355b7750962654c7e.nq.gz
    ├── 00aa54a1dfa4e67668cc1c095340e1b709d8ceae.nq.gz
    ├── 012cdeb7359cc941bab451153a9370ba0ca81d00.nq.gz
    ├── 0149b755c46a9a0e7daa939a1c81c9d7e9cd7b19.nq.gz
    ├── 020b86e329baad84eedfeda9db4724af7e1747d0.nq.gz
    ├── 0223dafc0d5543202927c34389dc6fe652398e76.nq.gz
    ├── 02b8f4323f855b7d8a0d2d4d39171998ab92c996.nq.gz
    ├── 02ff015e70b2509e3717e4ba02161055be594405.nq.gz
    ├── 039c587a8a27ec316b90be4d631e96e0fe91cff4.nq.gz
    ├── 03b374a1e59c882b8618138c78952b48f3b420a7.nq.gz
    ├── 03e6f690d3041ed66dc3924379056f172fd1827b.nq.gz
    ├── 047280d04ef25f918f416d23c462fe44575f1677.nq.gz
    ├── 0475609d406e466f497d0a4da0d61262e662a177.nq.gz
    ├── 04798b6ba258c8598e4e0a478aaa6bbec855851b.nq.gz
    ├── 05411d32826be1e7d136f8bd9b967ad686bbcef0.nq.gz
    ├── 05a0ac27264620667d3ef98829989fffdc4df1a3.nq.gz
    ├── 06881655dd38e0b75ab8b110bef2d53946002972.nq.gz
    ├── 076812a663649ac93b18ec2bd49962db51b2ddba.nq.gz
    ├── 07a8fbf2cac16392a65e16b3a650e51eef9c87be.nq.gz
    ├── 08955791812847010f9d80990758b9bd8e9469a2.nq.gz
    ├── 08a137dc7493e6f411aa579008a8ff0e99ad476d.nq.gz
    ├── 08a5b1dd692fc294ac098c962a4b1401585ab111.nq.gz
    ├── 0ad727779e5c5c906f421ff2aa2e303cfd731e0d.nq.gz
    ├── 0b26fef4a7ff2039a272de5d5ac677a115c5c7bf.nq.gz
    ├── 0b8636f5cfb14de80974b569b5ce82afb964d88d.nq.gz
    ├── 0ec72202801a2a7754ded543b8a5db076d35dc9d.nq.gz
    ├── 0efbc6d2df04e984105ff92c95c18eb00eac60e6.nq.gz
    ├── 0f904dc91068a490f0115aca8ef85cd6d43ea928.nq.gz
    ├── 100471ce8a5fce96abf472d66fcee5e2916430a9.nq.gz
    ├── 1066a868332f755f87041dc43128aece6798046f.nq.gz
    ├── 11431beb20ab1f33d8871f5f1992a40ba1c44788.nq.gz
    ├── 115317a61cfcd97b1263e6dc961646c1bb9502f7.nq.gz
    ├── 1178f93fbf93cb8a0322bb462ab025b39d80e70a.nq.gz
    ├── 11cfd825c175d9b825aa074eca0ec4c2df00f89c.nq.gz
    ├── 12bdd9fa8eb51e880141b9184e41c7f892876615.nq.gz
    ├── 13c441d79af5c19efb5b818433c44113025bef98.nq.gz
    ├── 13ee026e4f3b1253d27ef4480136bc5eb013cc93.nq.gz
    ├── 15fc71f14486b26a231beb55518b806d3a9fa12f.nq.gz
    ├── 164a5aaf7b2d320b13666243841142f989cb7303.nq.gz
    ├── 164cd233e1464864eef5580b316e0e3b2541a438.nq.gz
    ├── 16c105a71dfd89609b398de598e6d8b74f5f8abd.nq.gz
    ├── 176008c008f5c693917636f2f8b9a4337a2426c6.nq.gz
    ├── 176676407654f4da51364afb204cea209765f811.nq.gz
    ├── 178a8ac1bce4a28ab9a88f0480aafacf6c508f33.nq.gz
    ├── 18dea6747cf6275238e348fd00e44d898486b488.nq.gz
    ├── 1922194b8a8bb4a6d14d9e67b1a8433cb4b1c84e.nq.gz
    ├── 1a7537e65356faa79a86add4083bec55319f8c20.nq.gz
    ├── 1c251242a670dd250c6fecc3ac77343d62fbb72b.nq.gz
    ├── 1d7813582915fed02df09cc4ca323605a0935b01.nq.gz
    ├── 1dbea4211fdf3036f556c6b4058c9cc6d88e450e.nq.gz
    ├── 1dda5de34aad098b17957ef816ed1ca9d91a6b04.nq.gz
    ├── 1ebc261c71fe3b659d81c89e1aaa8ac9652b7f11.nq.gz
    ├── 202e5f6d72215c0df30b4543487b9ec736fe562e.nq.gz
    ├── 2047ac69932d4242dae235d4602e142b03b2c7e6.nq.gz
    ├── 207090c3a344b844b76e7875411d3e6c8cd9fc22.nq.gz
    ├── 208d369bf6c9e30587a7d20340ca7f3330c01042.nq.gz
    ├── 21d82d8e6a61faa15b3b51d439f5f45082c444af.nq.gz
    ├── 23a2ee25456b50049738f2a18c0613d98a8a2f60.nq.gz
    ├── 253f64051ee38c8b46be07f573ad3d4294434c2b.nq.gz
    ├── 29ad627e958ab32a15afa44f52c0ff5b9e4ed864.nq.gz
    ├── 2a569dd9c9bba6dced488571450e5a2abd048698.nq.gz
    ├── 2aa58b422f72b95dc45b776337e926cf1131fc68.nq.gz
    ├── 2b68515ecac021c83a954123b094495ae5746dd0.nq.gz
    ├── 2bd5e9ded0cf3f5df39b16f23338a21af25ae834.nq.gz
    ├── 2eca52644a2c0b17823873edd04a4bb899f141a8.nq.gz
    ├── 2f2bbfff8c2041167651c1a0ff74a67432bba2bb.nq.gz
    ├── 2f5beec16bdd3f5981a9025572a601402c4e65cc.nq.gz
    ├── 2fad98701761850eee4bdb05986e1c30a09b220a.nq.gz
    ├── 3037cd95e932edeed3924fb235d47dc1ad60516f.nq.gz
    ├── 3100f1d9b0a0d2ac1d0d18a55a727c339ee0fa99.nq.gz
    ├── 31d4c89ee5e05c192e0fa822dbcc187d614498a8.nq.gz
    ├── 327b5826b7d38ed5f83540e8b24663864846a815.nq.gz
    ├── 33063b271345045495a9a11233c03da7cac38bc9.nq.gz
    ├── 3390040963e20abe405c6b94435f92efe0028775.nq.gz
    ├── 33ac36ce57fb5d7c0f291057fd8fa67a502da30f.nq.gz
    ├── 353c90dbfaf9db51d4642390dbb11f02ffa3a0e6.nq.gz
    ├── 36199904875ae57e8596b593ce4bc1cb24f72e4e.nq.gz
    ├── 36ad48686e1c38b622dbf0c8a89719dcb9c0f402.nq.gz
    ├── 36ef338f4ebbb1249109799b882b49e3751700d9.nq.gz
    ├── 37b2b4053baf4d1d413cd48d8c2e11fc0094109b.nq.gz
    ├── 381bdc5f5baa9dd51826fc24c53869978158f7fd.nq.gz
    ├── 3829677377c7e150c7686e46286ba8af7cacfd7f.nq.gz
    ├── 3bbf3ca3337470084370d073131503c7194594a4.nq.gz
    ├── 3bdfe50d3c3ce8c7d0d191e6350080755783a0e4.nq.gz
    ├── 3d0142ce6328e03d25fc53692f875b9e5a3c4311.nq.gz
    ├── 3dce908988eb7361ab7642f6d27d3c7434f3dedd.nq.gz
    ├── 3e6a9e823be046d239e3a25e7ac18ed6eaaf22b7.nq.gz
    ├── 3e842e734ad68afd1bfbd1595c44620ac20b3a23.nq.gz
    ├── 3ec10cd5eacd2557dd6a1d7a18385bfd3a7beb1f.nq.gz
    ├── 3f73c326a210fb6677f00c02b99814b633177cc3.nq.gz
    ├── 3ff18b43841ce72f7c1a1200aaf7dc77291e83ea.nq.gz
    ├── 400038d6aec4d1e5fc255825bc6af1a84da65f54.nq.gz
    ├── 409ecf48a07657a4c49112000bb492152487ba3a.nq.gz
    ├── 4193b33427fbb033f0d8c94207469e05e8965fe9.nq.gz
    ├── 41a4973b3159017a74ae9d0cb4a9ca8a7c8a0940.nq.gz
    ├── 42684f036911a56ce3c686392b093bdba0ad5cd6.nq.gz
    ├── 428f3efc565539e412b33b7a06fc890dd1a8cea6.nq.gz
    ├── 43c97e719a5a824700932f72e6e7e6748ce45d01.nq.gz
    ├── 43f04ea5129ac0afde0cd51d7a9700a979124a12.nq.gz
    ├── 453ddb36872a69643347bbeaf207cf08ef0fddc9.nq.gz
    ├── 473f037def58ee829464b908ce13d46dd71795dd.nq.gz
    ├── 4753f09b7572a56ad14a21f372b8d00e88952cfe.nq.gz
    ├── 489c017f64a32a7dfa64ea4e76b958fa9ab952de.nq.gz
    ├── 4a25c93f293227f49537d80769742f30c51701ac.nq.gz
    ├── 4a324853b9ed6629c72e08a07455e08e2c755d47.nq.gz
    ├── 4a5851bb6599ed4f374a32c3a0aff226294a7f12.nq.gz
    ├── 4ac8093ca9572a65742eeec3fae8122bf310bb8c.nq.gz
    ├── 4bbffde1044258153b038e2ca9a53a2b36c6c133.nq.gz
    ├── 4c82b7ebe284ddd3beb49750c478050aafa45adf.nq.gz
    ├── 4c8398e898647744f13b17efc2d29a058657e691.nq.gz
    ├── 4cb70971f8ebc49c22e723f26b056f6d2b400dea.nq.gz
    ├── 4daf2bdd50d79e9839c47385676324ea0af8edd8.nq.gz
    ├── 4db9fff9d2d3672c86382925d0eca12a16070ce0.nq.gz
    ├── 5002ffcb18c9d4af5df81b448e3029101be45c10.nq.gz
    ├── 5103a2a157a08a84de08aa9a185d8cb6e142f8c0.nq.gz
    ├── 518d22aa96aaa11732d424b2bd86e91beaff98bc.nq.gz
    ├── 51b1e73275ac996886ebf751aedb1deead2d7042.nq.gz
    ├── 521eda4dc5d990c99102a3849917aa9662ee736a.nq.gz
    ├── 52b5cbb334dcf41a23117d6465113d1627192034.nq.gz
    ├── 54c7b9c1137d91e46869217c3b2c13e1360d93e6.nq.gz
    ├── 559e7f1fcad8f99092e8ec08f0b0c718ea362b77.nq.gz
    ├── 55d2cd1664f98f9ad88de1197cd5326cacae8be9.nq.gz
    ├── 56a8f741dc924dc8109d7693038cd1e5f50a0f4d.nq.gz
    ├── 5828b13ee21a732c5ad8e2be784389efb81c4c1a.nq.gz
    ├── 586e87fcd6c014032a6fa8fa16681216472807cd.nq.gz
    ├── 5965ac94904a7900f10f07e35489c2905eef312c.nq.gz
    ├── 59f71e2a19289c1dc0aef25c06a90784e0e86e14.nq.gz
    ├── 5a2e6bbb7ef1f8f323c7717afe7c2ef623c9febf.nq.gz
    ├── 5a4154b1d9a2564248030c57647b3ce6aea4673e.nq.gz
    ├── 5a4a25250128aed8a5f760c181ecf0aca84638e5.nq.gz
    ├── 5d0b2b1d70ca530dafcca09e2b80df3dc6ac2e49.nq.gz
    ├── 5dbca4475d3db1699af2687de272c9321c5bd148.nq.gz
    ├── 5f6937c38f3bcfeaab4593898b7126762bf3281f.nq.gz
    ├── 6036bec635704199de09bbe59c5bbd41fc3a9a0c.nq.gz
    ├── 60f9383f4a0bf653a87852af589124be9eb3a607.nq.gz
    ├── 61c0baabab0b6bd1bbd77c58d5013846795de37b.nq.gz
    ├── 63c1d8785963a29f920b6be9f1e2ab01109899ea.nq.gz
    ├── 654f021c371b0c17dcf71955055e34fb36da8ed0.nq.gz
    ├── 6687fa119792827f09c6c9fc330b72931810788e.nq.gz
    ├── 67eaa257bcc6ee212263f82f018d18ad99326714.nq.gz
    ├── 6887896a4640a8a2427267d6ac15cd44cc29fa5f.nq.gz
    ├── 68a6e2c69220c2e40c09a0b3a9eeb29d774fa149.nq.gz
    ├── 690aad34a46dc93c1dd9d876aa7201a2f317f62b.nq.gz
    ├── 69c72488f3a1c67bd6377c2d3a5f0db465094782.nq.gz
    ├── 69ce41bf90ceee544861f7e1eb3e72522d5ca4ce.nq.gz
    ├── 6a8dd8ebdfa2729713966edb0c28ace7d10ea6b2.nq.gz
    ├── 6ae19fb06e7c6da89d0e2b8cad2ac5d3cc5f06e7.nq.gz
    ├── 6bb03fbbac01d665349b3419e5446c1c5c562336.nq.gz
    ├── 6cfd3c259bd2cf161e8e34960990759403ede447.nq.gz
    ├── 6d007ec4dbc7665b1d50242df634df9b19c29b53.nq.gz
    ├── 6d0a1a8758d463dd9229cd79ae12dae94d49f91f.nq.gz
    ├── 6f037f8a9c689c7b5df689470d60c1f0b9e80427.nq.gz
    ├── 6f548ec964cb78a22308973263c6c90a9c34718a.nq.gz
    ├── 6f8cb02161944cd79a44706e8e9eda41cd507af7.nq.gz
    ├── 70c9e753b330dffc22637495006895730dc04b4d.nq.gz
    ├── 72461a5d3503459de2f74f89e6316754dda8588b.nq.gz
    ├── 729cac5a5488b04078a1e2936d76e13b85da048f.nq.gz
    ├── 74a8a7a470860fdffcdf2ea26e9fa4d00a7f7d6d.nq.gz
    ├── 753e6d8c0090b4923c5fa7330a8a3d2b8435e44e.nq.gz
    ├── 7651b1ab72ad83c377695b1ea9bcb08053487099.nq.gz
    ├── 7670bc09833bb6f6346641b2f209d1dbebc60b54.nq.gz
    ├── 767e9cb271a01bd0f92974c7d39c319defa905c8.nq.gz
    ├── 77a6c3afbdca45a375a6241e8cf69bfcc6391945.nq.gz
    ├── 77ada96bf9f2a18182b84fd53bc6e7272e97fb19.nq.gz
    ├── 78cca51e6fb5351570b7f37dc87dd47541bf98f9.nq.gz
    ├── 7a50fbcd5b863714f1096414ddf1ddfb9f91f461.nq.gz
    ├── 7a7b33aa1dc7083e9536ca09bc4b96fddf7b1f66.nq.gz
    ├── 7affe9accffc333db9e8f3a989888dbb7c8e3166.nq.gz
    ├── 7b37f2aa4a3f783f4467bc588f2891d8b346595d.nq.gz
    ├── 7cfdb1c0fadeca3a81ef169cf5f766def43f05fb.nq.gz
    ├── 7d0deaeb96497ddfdaeffea1467d822afc7861aa.nq.gz
    ├── 7d862baf680fd938b33fa9a1555ad3c2576230e2.nq.gz
    ├── 7dd85f1f3c8ac0e93b8c2b701bca89c9a9357872.nq.gz
    ├── 7fdc07fb34113d1fc1ad53b969b99c0eac35668d.nq.gz
    ├── 8026bcfb3d331b0cfd0078eca5c092ee3e1922aa.nq.gz
    ├── 8079379c132f89a666546e253deee867024fe24c.nq.gz
    ├── 83535046b44481af44a9c8d17e5490877c41300e.nq.gz
    ├── 837303206e1192768a771fb80fb6315b8ab5d191.nq.gz
    ├── 837e179b538ba5d50d6691b2e643f5b61678be6d.nq.gz
    ├── 83940ddc4b4435789da66b9495b97348fa0a94a6.nq.gz
    ├── 83ffa14ff142061d0766dd3c1e8ded591defb418.nq.gz
    ├── 8503c470f4484be382c71b0a72bbe6c562f73382.nq.gz
    ├── 8538725e486866c98cd0cdcd2f10f04b119604e2.nq.gz
    ├── 85dc112bf3093d886caa0fbaddd4b20b0a29ad17.nq.gz
    ├── 86c05b925ee7a7d4d77db106e21e0d14ee09f7dd.nq.gz
    ├── 871e0550091f856853ce7e4caac3a991762db094.nq.gz
    ├── 872cee5350417776ad3b5b246084dff9c5ac99e7.nq.gz
    ├── 882058e334627d8d61dcf1578edb1d3d145261af.nq.gz
    ├── 88e3f1d75e4dd582c6587e8e183e55488d5050f7.nq.gz
    ├── 88f875ca909e9878ddafd3904abe395c66220106.nq.gz
    ├── 89bb8a0366196fe7ad84a1e47c04f232fd2ea4b2.nq.gz
    ├── 8a7ccd883c09228b8b2013eb84249041857783c6.nq.gz
    ├── 8bb123b8dfb503b12b19c42c28a9169153cd01c5.nq.gz
    ├── 8c662a97f07c20176fc9cdf8de22a47b67c4472f.nq.gz
    ├── 8c71d799768a5d5cdada39662979b1b4343f6a6f.nq.gz
    ├── 8d76055bb6f254154cd4cf12a076a6af8ee1fa35.nq.gz
    └── 8da5557b675c2f079a1d80f732a7cdf38ff50803.nq.gz

8 directories, 200 files
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

[substack/node-browserify](https://github.com/substack/node-browserify)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*

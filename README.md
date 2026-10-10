# Repolex Knowledge Graph of shadcn-ui/lint

RDF knowledge graph data for [shadcn-ui/lint](https://github.com/shadcn-ui/lint), parsed by [repolex](https://repolex.ai).

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
rlex download shadcn-ui/lint
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ee9391038b5dc025f01777d8dbd0f72d5b885ab4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ee9391038b5dc025f01777d8dbd0f72d5b885ab4
│           └── chunk-001.nq.gz
└── blob
    ├── 00023910c5e5aeb3a80404cafdea0ef54a2d96a5.nq.gz
    ├── 01b148d1d96d49b323e0e432dfb8c5ecad3a7be1.nq.gz
    ├── 03ccf1d4ce8a089a74864d44a025441cd48e0461.nq.gz
    ├── 05d3b3461d75cb79b3c292049e75f7ef056f4f72.nq.gz
    ├── 05d6f7ac145420634db9b650040004909eea857e.nq.gz
    ├── 06994d8ad0ce1a060ca7ae021e53d1fa56865240.nq.gz
    ├── 06fd4639125384d7dc8455d1a8ca4ad70a82e7f6.nq.gz
    ├── 083b71c1d920c10cca63c535ffcf1923f446d7cc.nq.gz
    ├── 085d2e61f4327202403f50281ced33e6e3ab247c.nq.gz
    ├── 0a5d93c09cf582359fe81e525c13d7f32c74e861.nq.gz
    ├── 0af6fb16d6056c3306b84ad5e2932658ef6e958c.nq.gz
    ├── 0b7c0cbdcb6758ec8493ef8825ac1d1a6cb6dc4a.nq.gz
    ├── 0d10a3c58d7ff253fe7ce44cd5768b71054ab828.nq.gz
    ├── 0dbc5508098c6dccc6ac6df7f9253bb21a95b737.nq.gz
    ├── 0dd66e08ebb73d5a0f8a10dd1a88ac4209efc438.nq.gz
    ├── 0f2f6e7644414215a2fd0a613683a8b9589aaae2.nq.gz
    ├── 1090082f10e42ea38992aac1264da72f054c2b96.nq.gz
    ├── 1158ba280e63ff2ef2ab75b0e024aa06016b7ff6.nq.gz
    ├── 1177dce9bb6a3f887f14c96d2602a167e543f5c8.nq.gz
    ├── 11a93183e83f14c6161c5634c2407f5ce6d7b2c0.nq.gz
    ├── 11b1c0ec0c5faf13285c186a10cd3a60c1cd9d04.nq.gz
    ├── 12a4a050113693b68fd6f5fa43e19ad4e809b41b.nq.gz
    ├── 13781fbff33868111c9f510a5896e75f6a6ba3d9.nq.gz
    ├── 1387d1a39964c0ff5f779fc69af2930d366ad28b.nq.gz
    ├── 1595b9295f2e60eb1834a6a498db625abec5e006.nq.gz
    ├── 15fed0d0cffeaa19b4651e70354205e028e24db4.nq.gz
    ├── 171145301b3bf19bcd287dad4b71f415bb452497.nq.gz
    ├── 1788c7cb7ab20041d1d423e6355a434ad497ce8f.nq.gz
    ├── 18c02bc5d1e8bed2a7ef9256008d83a647e68793.nq.gz
    ├── 1920eec422bd5e2bc88f5c61b01e2570f345d812.nq.gz
    ├── 19a556da9fb07cd65bff94e6ad835b269e2785e0.nq.gz
    ├── 1cb862a44168d75320e63ec57f0da9b94f3eec2f.nq.gz
    ├── 1e107594b741822d18d1bc5f6efdda59989a5dc0.nq.gz
    ├── 1ed1444e87c03d6a9ef25e5d89840c97898851e0.nq.gz
    ├── 1ed795c00763fb458f561a24dc3218fbb45e2b89.nq.gz
    ├── 1f5746257f421ed57fdd1945c1a5c0e131bb9be0.nq.gz
    ├── 1f5d1954e0682dadb075b902df067fafeca895ba.nq.gz
    ├── 201648546d61efcf5c16ee752a4e460d2ebfc645.nq.gz
    ├── 2304c1a540e627d53c1d7848ccfcde021a0b0cb9.nq.gz
    ├── 24e1902575d6396508ed6e2f53bdd8e2c4ee794d.nq.gz
    ├── 250963f0ad9f7f109061d1d9b8873cef56bdf432.nq.gz
    ├── 25a041fb0eb75cc18ae9611a234f81638ed33803.nq.gz
    ├── 26561d636392ff646ad76bf42cf17396c1e4cf77.nq.gz
    ├── 2796908c16a1d2f744cbc823852baf4aafd6035f.nq.gz
    ├── 27e7f7778d090c25eee7faecb7eeec0a9d440edc.nq.gz
    ├── 27fc4ac7de9a891cd171c371b7c3ce81743ff95d.nq.gz
    ├── 29674033b9f6741c1c0e6f6463e9e821217ea65d.nq.gz
    ├── 2a23b1f7c68f34f3bf1ab7b42a7aa820b564563e.nq.gz
    ├── 2a659a68dd686d00e57e2e9b7c82ad44287e69ac.nq.gz
    ├── 2e48a2cb627d5eea9f25bd2f44e0ebdb94d10e6f.nq.gz
    ├── 2f6fe5ca4ce5af53fc5d9b75bb2e9a1c6cb4787d.nq.gz
    ├── 309d3660b5748ffbcd154344bd8e9dde20742c85.nq.gz
    ├── 311979d762ca5ead1289c114ba6f4d6dd28d4dcc.nq.gz
    ├── 3164fa96d57dff598246bb6d96e6aec7de20b5a3.nq.gz
    ├── 31c727144314a99269505fb4f3c026b05106d85d.nq.gz
    ├── 31fb8dc6a38ac26396649f61f2a4dd70049c36dc.nq.gz
    ├── 32c627bea8d52c72f9c2b7fdf71667b12504e7f2.nq.gz
    ├── 352fb2ef21a76220fdab0a34b6bedbc44febca16.nq.gz
    ├── 35842cc17f52c59451e7a0ee753a5d4463bfe901.nq.gz
    ├── 35d37abc1cc8941fe2033a137beeaeccca1a0071.nq.gz
    ├── 36447ee49466af1b8417fbb3b129ae683953f8a1.nq.gz
    ├── 367c857ee86fc13f3f8389a19efe5687d2c26355.nq.gz
    ├── 377fcde20d5d16a68cc8f392a9e0f8a8008bc660.nq.gz
    ├── 37f9ef4ddd1ca1e1e1bb6d981cf86eefaf3a060a.nq.gz
    ├── 3896955712cd16fd9034057229c444c3246f4d0f.nq.gz
    ├── 38a7206dde76ced3d0cfa82c10cb43c9c5514e4e.nq.gz
    ├── 38f570453f30dafed64e7a261d0bbaadbcebd7fd.nq.gz
    ├── 395ca07b85c3d5898c1ca22bc96f1256e7980c9c.nq.gz
    ├── 3aac1ce0752a16dc19333a49a482d1cde86cdf2b.nq.gz
    ├── 3bf43342f78c3a71bce1f9aebb8a1f2272ff1c25.nq.gz
    ├── 3cb9f49f517102a998bf6ed2bbf5d2feb2bb22c1.nq.gz
    ├── 3d3a1021f849e2f34fa97ed4abf178ebd73f799c.nq.gz
    ├── 3d8b0aaa6b665742f4494aea0c24a1a75f93a611.nq.gz
    ├── 3e563b8ce7a7cd956bb444d5e6fdd8ad0c444d36.nq.gz
    ├── 3f3a7970abdd7e7ec5ca363a7e957a313b85bff1.nq.gz
    ├── 3f46ea572e0f88bea4ec4b71591af808c666a476.nq.gz
    ├── 3fc57f71b3c5e7f441eff6e57d1ec3a97d0041b9.nq.gz
    ├── 40e5e358fe04508a22f4b348b123d48f0f172ce2.nq.gz
    ├── 41980277095599b87f1d47e04777844b8c9ac78d.nq.gz
    ├── 41b70d45cd7bdc50fa63d672d7976f58820b005a.nq.gz
    ├── 41f4d0ff016b84a2438f244529651011f8a6c97d.nq.gz
    ├── 42919c57e905c9031aa16dc512bd9625c66504b8.nq.gz
    ├── 42da2739a1845e27ee728b790c492109adfe9349.nq.gz
    ├── 438a4ee65e484c11290161255448b3a5250ea9a7.nq.gz
    ├── 45713812f92978e4c9eb9d9b7d7973ca3c7c431a.nq.gz
    ├── 475d49553946962f2464df8706c0b2ed90dbd91d.nq.gz
    ├── 47c26beced2ad2d4693c0f67da325157eb1df052.nq.gz
    ├── 4859fcb8a656d59f197a29ae0c056ddbb0da28c6.nq.gz
    ├── 4885795b9340c19257f7a9ab0d6260bc6ffb09a0.nq.gz
    ├── 48e907912c1d2876fe4ae0ac937ef90d278dfae7.nq.gz
    ├── 49cf6ed84387c9e7d2be4cfff336d27468a115e9.nq.gz
    ├── 4a41b468b83dbeced960d253c079ee12dbadbb2f.nq.gz
    ├── 4ae0eeba1eee4f18d9156b64ec32a3a190151bdc.nq.gz
    ├── 4c1f9d2a6a440defc794cbe7ef1d73da52efd549.nq.gz
    ├── 4caeda1aded93c9afb8acbd62e102be9f21bc848.nq.gz
    ├── 4cf1376290f91720511a5cca2d329aeba754b296.nq.gz
    ├── 4ea1f77201bcc9332845fb1551b1bbfb8f5487a4.nq.gz
    ├── 4fcf3f06584b58471752e330a942ea0f2345711a.nq.gz
    ├── 50c5d032919ab20c01f27c7986cb8ce449989cdf.nq.gz
    ├── 51fa48cbfa5002221b5a30e62ffb6f90c1350d2b.nq.gz
    ├── 54e456b61ba8d3c29a23ff3694ed5730d59b1abe.nq.gz
    ├── 552094b80aafe39a5da1f773018f6115ae00d0ef.nq.gz
    ├── 55413d42c07ef0cad057bdd80d20b754b61c9908.nq.gz
    ├── 59a1d37878836a81b6b10ede58e5871bbcbf51a1.nq.gz
    ├── 59e00c9a6206f5004cc194e8c836c91cfa90cf8c.nq.gz
    ├── 5a16d261df5edca2188154ede839075f0d5ecf9d.nq.gz
    ├── 5a51e53bc2caa25fff487d32830747f69d8b321e.nq.gz
    ├── 5addc5790b5dde1529b168c62937735fcaa02533.nq.gz
    ├── 5afe5ab16b7f9e487ca3159359efba057b9138a4.nq.gz
    ├── 5de0ce5f9cf604bb30caca52c465ed842e6d083c.nq.gz
    ├── 5e494befa2cc2a9721ce12c2162f3036e5ea89c6.nq.gz
    ├── 6175e2e20f7732c5bf0204ebbcdb5c196bdfa2cd.nq.gz
    ├── 61dfe5b1d3701b840ced2dc47c86acad20cf3b26.nq.gz
    ├── 623e08bc4d6de8dd9cfea957c0d22856aed2bba8.nq.gz
    ├── 62893d8dd4d35829110ebd0fba5f8879546be0ea.nq.gz
    ├── 62a2a870f9f1f3c450fe27494072673c1f923aa2.nq.gz
    ├── 6324fd96d2a79efd6931aa39f369e6325b3416e1.nq.gz
    ├── 634274611ba724ad907d2f42123e3f0ac46ccdac.nq.gz
    ├── 663a6a5b652597184a2c38d3b137fbfe614e4d9d.nq.gz
    ├── 6644896aeb417a8f9e0d9d27fb3b3c1996b4ecf7.nq.gz
    ├── 67deb9f10f5309eb3341b121ccc6b91c7a12f98b.nq.gz
    ├── 6abd948244c10f047c9a4e8230c1eab277de2fc6.nq.gz
    ├── 6b2668c847d5b8e6de44987d53a9538e44ff1c1f.nq.gz
    ├── 6b3acea3bff7def0962a8ea134b0ab5a9061829d.nq.gz
    ├── 6b9072f53e8040e7a1ceec4ab2d80077c361986f.nq.gz
    ├── 6cb03a2887595b7d0bc4f1f8aad0af4707778210.nq.gz
    ├── 6d2db145f81918c095debeeca475211d1ead97bd.nq.gz
    ├── 6eef12bebe46fc5597aa7bdeee411f96cc2f56e7.nq.gz
    ├── 6f9a9b4ef0607e7351b1cf5ca1400fd79d702cc4.nq.gz
    ├── 6feebc9e1136f6b6a20525df213f51595d87c48a.nq.gz
    ├── 70c1f5902e06fa816df86bd6f249dab4108840dd.nq.gz
    ├── 70cb45cd9b7413ab2aff4819fcecec2249d5e518.nq.gz
    ├── 7176f122950962ca4848de422438b0451ed203d4.nq.gz
    ├── 738ad1fba3c7f9f2ebe8c83aaaf540278059e4a8.nq.gz
    ├── 752accde8fcc97fb2b11807848764404b47b9e86.nq.gz
    ├── 754cde70cbacadeabc4900cdf2a327079ab01533.nq.gz
    ├── 78c3213193f520991245e332ad9ace849e24602e.nq.gz
    ├── 78dba946632ca828fa6a3448fd3baf59a078f0c5.nq.gz
    ├── 78f7927ccede5492616e1ffbb498c83d40a683de.nq.gz
    ├── 795624d932226ea177086994431c941a199348c6.nq.gz
    ├── 797650aedeca82bc99b8a6f2f5ae1d7bc1f14656.nq.gz
    ├── 798079ed62dba9c82690123d54bd52a07b1847b8.nq.gz
    ├── 7a3ada7a160bcb8d175b568b0061e262ad4e6bd5.nq.gz
    ├── 7a794a88be80f8a8d277cf851b124cd939ddf7b0.nq.gz
    ├── 7aab1d668514999fb7016684cf5e2210c5a427e8.nq.gz
    ├── 7aefca3a4c538512c6485677a51f428627401342.nq.gz
    ├── 7ba72f207b87809deb7cdf7ada6db2e76175da3e.nq.gz
    ├── 7c0c38a7055d0dc40bed083e903e10d45e25a056.nq.gz
    ├── 7c3fdb8496d6f4426b846bb1f252e1a20579ebfd.nq.gz
    ├── 7c5fc8252cfeeaf4c0770dbbc86f8fd7a7a75f3c.nq.gz
    ├── 7cdacaa062d2d0f8f074beafd96c2527054792bf.nq.gz
    ├── 7d3cc237f78c3cba8446f949dd3cdf6d9ed8b8b1.nq.gz
    ├── 7f00444c0de9f2d516b6cafe9d87f71fc61b6298.nq.gz
    ├── 80d326c933e7fb7665c94d77661a4301c28acb9b.nq.gz
    ├── 81673c5b85342aa61c1d7ce4e0549b80c144fb0b.nq.gz
    ├── 81813d43c34b9340364441b32934037dc495bdac.nq.gz
    ├── 81b6bf3dba9d3e082f54c9c82b355a6bccbe2264.nq.gz
    ├── 8248a4c9ffad4e63dbd62d1c12914a319b7d3394.nq.gz
    ├── 8292aab19c5e5b47033a8d57b6dbc40d2701a7a3.nq.gz
    ├── 8332fca6130b469039a7b99232cb82dd1be1f89f.nq.gz
    ├── 8505c86eb0abf06e98788bf61032959d0d62fdcd.nq.gz
    ├── 8548bcc28c512a16e07d20a69a874d3e54f9f043.nq.gz
    ├── 86eddb6e739aa0396dd3704d54f8483afb9d8d90.nq.gz
    ├── 87cf6cb7b60247a7667da86b047e36715fd6906d.nq.gz
    ├── 87d91febc4bc5016526e923844dca4fcb2dd1bb5.nq.gz
    ├── 880de623b3bae19367b82ddce817d2a8fe9c0fa5.nq.gz
    ├── 8871da30bb3c88e92178432b49e1e8bf00d385fa.nq.gz
    ├── 89ef6f999d7da84a48716391be8bb3d9a44c78a2.nq.gz
    ├── 8b4c50fc384ffbc4005a032cdbf0012964adf3f0.nq.gz
    ├── 8b6baef07841997109923bd518ddc7a8f10a982e.nq.gz
    ├── 8b8250705b8e98976e6326b45a165680d2ebb23f.nq.gz
    ├── 8c40410d73265bb5670fa5256388407d5c70677d.nq.gz
    ├── 8d66264743932c780018638cac3abb6e303c50d4.nq.gz
    ├── 8d76f988d55c945f1df5cc787a9c4839c302a9da.nq.gz
    ├── 8eacd2e92d4b1cc5327ffff596c91e19bccfdf11.nq.gz
    ├── 8f9a8b61b7a6ca7f808ac6cf288d7fe685741cce.nq.gz
    ├── 902b780a312005b116cd2b5d8572b7ee0d7b6e27.nq.gz
    ├── 9142d257f27a43ee668f59d0f5c55bf1f1ffa4ea.nq.gz
    ├── 91f6fecfda297c1d8dc2972423b6f5bf15efce08.nq.gz
    ├── 924b55f42e98721620a2206ca848eab030e6d887.nq.gz
    ├── 92d088e3b737eca9ad6b669dc484acc8628f4376.nq.gz
    ├── 9336badf0fd30e64014ad6f2705a8ae4bc8a4389.nq.gz
    ├── 9600d3444d77768980c5f26884c279fad03799ae.nq.gz
    ├── 963c2486cf2ae2b4ce6cf22248b3442a06c3a7f3.nq.gz
    ├── 96bcd37a9123dd2516dd134b62ab5d33ec1dd7ed.nq.gz
    ├── 9799ba6e64d1227f0d451ceb982ff728da5a0f49.nq.gz
    ├── 97b1fa21dbb62d22171e681dc858cb563d06512b.nq.gz
    ├── 98ffbc2ece2240322ee079bdb914ac1d8b4ddeb9.nq.gz
    ├── 9b757c4382802d0faa063568b4e14a32d374485e.nq.gz
    ├── 9c2e593e1d641cdb5441e968de371d5db9424d9a.nq.gz
    ├── 9cbf1e9c73ffed46eff58593ac5cd2d98b410016.nq.gz
    ├── 9da1fb7b2e603730b7e96f285dfad3c4a85e849f.nq.gz
    ├── 9ecc64de93260da287278d13245a98e116dd111c.nq.gz
    ├── 9ed2a670bea4bcecb6c12b2fcda9a02e2fcd0d1e.nq.gz
    ├── 9ee30d0ccc06c65f3958e4a8f471d54562d649f5.nq.gz
    ├── 9efe7d12ce29286bfebff5e56fbb534c9a60f335.nq.gz
    ├── a06193f2ac6a2114d638e6f1c53284f5a389099a.nq.gz
    └── a0c3fb3079e210c5ce4e3344dbfe3d61f1fed90a.nq.gz

7 directories, 200 files
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

[shadcn-ui/lint](https://github.com/shadcn-ui/lint)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*

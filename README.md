# Repolex Knowledge Graph of ansible-collections/aap-snapshot-collection

RDF knowledge graph data for [ansible-collections/aap-snapshot-collection](https://github.com/ansible-collections/aap-snapshot-collection), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/aap-snapshot-collection
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b9e211f686960e38e558a23ad2a00749d7dfe662
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b9e211f686960e38e558a23ad2a00749d7dfe662
│           └── chunk-001.nq.gz
└── blob
    ├── 00781fea3dbe07254bf8dcc7fec7c34050541b45.nq.gz
    ├── 01bda75747ba512626d39ae2e67d36d175d5fba8.nq.gz
    ├── 02e1e5c700dada197e8f85bae514417d045bcf58.nq.gz
    ├── 0383fa1b59252ccd15a5d163cc964228b8dbc183.nq.gz
    ├── 041ea4943bd7fc3e7f1758c0d723c26246e9efce.nq.gz
    ├── 046ae801d87642491dac96d046332a0bb39d2de2.nq.gz
    ├── 0549416f0c0a8b94a4592b72c522899324a9d4f0.nq.gz
    ├── 054d8352f20f27808c8c5a8f73667b9f86892881.nq.gz
    ├── 06ddec52071eb0f8b6ad7801a59be5ab42cd6d07.nq.gz
    ├── 06e7e64c650605af1d0025a43d84a942b53f250b.nq.gz
    ├── 0749416bdd4d960d135707913af982e041e6f9cc.nq.gz
    ├── 08f6b0cffc98a35e4f7338573bad49b8768c3705.nq.gz
    ├── 0900d4abb1cdea02283b6900da2addcfd1b1e392.nq.gz
    ├── 09d5769f8e186aaa6c8b322da1c4948481bfcbc4.nq.gz
    ├── 0ab50b62bea5c93a810baeb0f763009b2d4ff9b5.nq.gz
    ├── 0ac9bc9d5c2c15bb29036ebe9052b2992af0e890.nq.gz
    ├── 0b65c2974a9ac284eaebf8fe1c4c13219e9d11de.nq.gz
    ├── 0cb7094eface3194766db5be76b8c2e1b5af7fc6.nq.gz
    ├── 0de876636b1092061987eb2aecdc69bd52d00104.nq.gz
    ├── 0eff0b9754a948305539c7ed7eb62509d0f55b51.nq.gz
    ├── 0ff742c52aeeda4f5977e962e41dd07c894daab8.nq.gz
    ├── 11736779796f6dd2b19f0fe335737a1e405b5d66.nq.gz
    ├── 12bc3235201ec2246cae5097be46a512e234ff81.nq.gz
    ├── 13f4c23be728dcb707f45e57056dbca7913e94de.nq.gz
    ├── 16fbb9b8683213f1e223887d002937826d777fb7.nq.gz
    ├── 174a0984cff5c49b9f3391de59e6b77ec0b17fc1.nq.gz
    ├── 17e7daba96e99aadb59e85e0eab46d295e73a64e.nq.gz
    ├── 19f164ec605c0bbdf1e4c93b408d5d4e0a3fb3ec.nq.gz
    ├── 1b573f681a99ca41c61d8e425eec995ca4d91199.nq.gz
    ├── 1b74471133f962454993ac0221e03552409bdebb.nq.gz
    ├── 1bc7a6ea981787d6406f770dd09e4e36ba664804.nq.gz
    ├── 1c4ca14d6ed1454fd285e6c579035b0a66dcaa43.nq.gz
    ├── 1d885087bc653b3fc191ac650e412c9fb9c1e412.nq.gz
    ├── 1ffbda10411c1ed499db5e01e56028bdedf82a78.nq.gz
    ├── 21899bd92e5961aa6e7c79d1db55ec33543e7191.nq.gz
    ├── 22e9a826e5bd5be4e54a20bbccf1d1353c175c77.nq.gz
    ├── 236a8daae5385a065ada77b5bf1075e5901eff9d.nq.gz
    ├── 23b0c04a259305f51fc04b3109884da4a7a08923.nq.gz
    ├── 247e8552b9143fec2dd2bfb60ca264da059380cc.nq.gz
    ├── 261be91d7043a6bc62d88349a40bb66120ce3ccb.nq.gz
    ├── 26e0640b33ba423bb5f21c594c6c94378ead618a.nq.gz
    ├── 2b1b09d02d62969359d95855d4f9cf08946fd732.nq.gz
    ├── 2b24942e89b6406c145fb0ea4300929370d51e00.nq.gz
    ├── 2b7fcb0ffdd8fd7f08768655808c265f887a241e.nq.gz
    ├── 2df844cc228bd6e4135d7c97b60c43b7b1295742.nq.gz
    ├── 2ee82c09caa99cd686581d30228a27f986d34b06.nq.gz
    ├── 3070f0e7332df796a31437c8d9e94e0ebbba857e.nq.gz
    ├── 31f4575d248fcda9f244b9d81e8d3f5af70c7af3.nq.gz
    ├── 333b64f79f76a4f721654bde7fc0cc3937117b84.nq.gz
    ├── 34e6ff075b9028809f70b1209720591c9ad4ecbc.nq.gz
    ├── 35b63ee0096dbcd66354ed96eb669d1e1f87d134.nq.gz
    ├── 361cd5a557535db04092254cff7b3e17b12ff0e4.nq.gz
    ├── 37079700a1fdf442bc30c2a616f27a6b7224bee1.nq.gz
    ├── 39a291c0ff371c8b42ee9c40562c9860cea575b8.nq.gz
    ├── 39d31630c43a53448fbb636f5bc026f29ae32171.nq.gz
    ├── 3b0845c8ae7ea75085bc2044a502ef7e026ab70f.nq.gz
    ├── 3bd86ecba860cf29ca1bb78bdaf201b8adf1dfda.nq.gz
    ├── 3c3a2682ed541bd0fb036f00f0c37bbdeb1c8671.nq.gz
    ├── 3cbdedf4373e7a9f3305b6af6c8f674716d21fcc.nq.gz
    ├── 40405c35f9ff71983ffe214b124f0cf85464ae4f.nq.gz
    ├── 4166a580e6ec4971f5802e03d37c42a6961fc166.nq.gz
    ├── 41d48f65a0e0988e6c2c7ce7e91068e4f0efbca6.nq.gz
    ├── 42ae68db46abb70f7756fe401c7c4ddb9b9f5f07.nq.gz
    ├── 43f60a994e8cfc3e25cb16b4aecb7fe132bbd28c.nq.gz
    ├── 440a5c4622b2c6fc02e09e42a64eab8300b59dac.nq.gz
    ├── 46aaa5787d2aece04743bba31c5e0b755f9ca680.nq.gz
    ├── 47877b3bd0df3aea20839a22acd84839292d8d90.nq.gz
    ├── 482bfcc901a653dbbe892e2707ae8ada21aa88b4.nq.gz
    ├── 48befbde51eaa1c11b147db7d35e2c44f885728f.nq.gz
    ├── 48c7cec3a73aef086ff68868b4e5dbf28ab69021.nq.gz
    ├── 497ce518c3eb5f1cb5643b2e1f5934e115902cda.nq.gz
    ├── 4ab90b99c27292b08cad86f06ef9f62a21571ba2.nq.gz
    ├── 4b45e33786fd1092ec56a7eb063a65865f487dbb.nq.gz
    ├── 4b6f83b90bf8adc2d250da2b9206aa7b861c07a0.nq.gz
    ├── 4cf2a99405af3b109c51a4f023a5328215e363ca.nq.gz
    ├── 4e5a635db63c474032711740a3e9cb8053b092b0.nq.gz
    ├── 4eb33f40e185d4bff74cf2a413e0e11053331d83.nq.gz
    ├── 4ed9dc9cfa92e37cb24202119f7347dfa963a615.nq.gz
    ├── 52ed4ef95c16477674124914c9929dbeb47afbcc.nq.gz
    ├── 52f068514a6c8cd527b61151b15153c0bebc0daf.nq.gz
    ├── 5402e293931056cb391ac216b35a0cc7a0d77289.nq.gz
    ├── 54b6401debcc336147712bf86b397a3c89646f31.nq.gz
    ├── 5623a062567b344679765cd4bad3f5bee5a97417.nq.gz
    ├── 566d3f3f02a9e158eb610305870376ae8fae1317.nq.gz
    ├── 598e4608ea3d2d3db662bcaf58b3ddc9d89ec5be.nq.gz
    ├── 59dfa21663bef026bb9c9643889349a1aad59aad.nq.gz
    ├── 5c87734b101bd3c0ea7c056105ed7ef2d49b14b3.nq.gz
    ├── 5d1ea4b43a5eb081874c82f63cd8e2e7bcacb7d9.nq.gz
    ├── 5ee0d76bbd7e4cfbaa3939063fed64c0204f31a6.nq.gz
    ├── 604856c942e1714f22ec9d2e112fed177ae4d1d8.nq.gz
    ├── 60a8d3e6f1e2f0fe054492e115238bf3059d3457.nq.gz
    ├── 60aeb3bed4fd31493a1d3241ec37e44949ede21d.nq.gz
    ├── 6103065c6ec20f4f3426d75f8293c7cd3e6ed29c.nq.gz
    ├── 615930b577d0c6f9dc8565268ebaea6c074f6ac2.nq.gz
    ├── 628d1669a6bf9051a528f88041e8898b3d4054d3.nq.gz
    ├── 632f21ad970bd9dc3708776722a7f93fcb669a8f.nq.gz
    ├── 633fd62b1a1de7e33506bd070cbc680467fc495a.nq.gz
    ├── 656965d57a6496a35f6bde383698085034345409.nq.gz
    ├── 6638ed494392e52a30ceaa4c0221acbb066e6ac6.nq.gz
    ├── 676844bea327e6e4adb624bf5ff2cee90e4ae87e.nq.gz
    ├── 67a66d4cd7a8747869c3e4fd5157240a97413542.nq.gz
    ├── 67b679de81518b5f2828c5001941918c2a5a3e9e.nq.gz
    ├── 69a6162bcd42fc60fbeb60f6a02b19130c030d24.nq.gz
    ├── 6e95de353799d934df6f3084457924521a556548.nq.gz
    ├── 6f854a153bdc2b12ba1b7078e0cfbfa9c7645123.nq.gz
    ├── 7001f75ee315fe795ee71741326c5563fd1f8cb3.nq.gz
    ├── 70946be7d3675518acadc4ac1fe79902c8619a88.nq.gz
    ├── 70eb534b5002747b4d05ae53de1df5f64fe5a10f.nq.gz
    ├── 7217696dbb3daca428b4dfcfee80f734608c26ea.nq.gz
    ├── 72bf4204a19794fdb9bfe09c3d336dc5a97b51ea.nq.gz
    ├── 730215ef708ac31a9095274dc8b570b24b2cb19d.nq.gz
    ├── 7562d13f39d2ebea345d9793d23a36c0068e62c8.nq.gz
    ├── 75bbdcdcbae8512e40f00c7774a4a45a8a55a1af.nq.gz
    ├── 77ab57c17f640e714771956974a54939791f9d82.nq.gz
    ├── 7a505065874142c1b8d62bafc4077401236262bc.nq.gz
    ├── 7db0433360153d8c44f9df08919f6642cb9f9902.nq.gz
    ├── 7dbb6187064e7d26b3750d12bfb4fa32eb7db0f9.nq.gz
    ├── 7f50d95d00b921cf5c2630361ecdb7c4e722fcff.nq.gz
    ├── 805031b775e5ba94c9ff53a69c0c9ab8ef2bb453.nq.gz
    ├── 8201f992154a14a7fcd95a5937d5c40c610990c9.nq.gz
    ├── 8268e3486743f79d7f57fdf440bf2fe6b9475d1b.nq.gz
    ├── 82e301d7967cbb9dd8b94834b601ed6d7f564634.nq.gz
    ├── 841bc8d2f8646cdbe4e8c36d2131497541446cf5.nq.gz
    ├── 85f8f3cc020c2ae99ffb4a22505ef20f5fa75f54.nq.gz
    ├── 878b7b0afce5662a245ddbd73bc2ba59275b769d.nq.gz
    ├── 89cef0b4126d324b8d243a0bfff9f8ff63a8f09f.nq.gz
    ├── 8d7d08a62a7d56ab45dd5c255c28809ba6e9c9b9.nq.gz
    ├── 8e8af53e82c149b9154a53540891edb43e4a477b.nq.gz
    ├── 8ea47d6808df798b586be3d447ae6ec57e1096b6.nq.gz
    ├── 8f8954adbfe5426f24037cdbcfa46b18469b7643.nq.gz
    ├── 920ef2ec719cd044a41668fb7528558275b1d440.nq.gz
    ├── 9234935c0ee94db486c19120f11d7fd4bc5899c7.nq.gz
    ├── 941a3509a8069a1712f80a83f8d1c5698d920c6f.nq.gz
    ├── 94557649f7ac9ad36b669bda41e6ece630d494f5.nq.gz
    ├── 958543f5e30902e9f2f2a3499ff59ca797b66a31.nq.gz
    ├── 95b44878b5f6d55a0baa2469377112b2979b7570.nq.gz
    ├── 9706b39ca9d53ca6251e3212a4c778d2693cd2e5.nq.gz
    ├── 9ab1eafca648dfd8974cce38cc816ea1eb0c88d0.nq.gz
    ├── 9e1156fa62dd8198fa2ad2f8e35c21df184a35a2.nq.gz
    ├── 9e6f3ecca450f875504cdbbd655c324ab7d252b0.nq.gz
    ├── 9fa813426abd3dc3c6c52e38c036d787a65fe6c0.nq.gz
    ├── 9ff532a72c4b1461e6758d1bff47035b35ebcd24.nq.gz
    ├── a0d4abfd60ee47a6568c27931d8d8ef321c1fc2c.nq.gz
    ├── a253f28a6a232df5e78eee528f20d2b729b64f0c.nq.gz
    ├── a342806021af081abc4d9dd1fca6993203aae28d.nq.gz
    ├── a50112d9d0280a4cf91898a521ce89e6baec905c.nq.gz
    ├── a6fce590c88a7d73109d39c1b5ee75ee5e262644.nq.gz
    ├── a819b9eddf0a7ba8a9884925aee32cf27d5ffce4.nq.gz
    ├── a944813de3cf69409e1ec6bf930e105ae8832972.nq.gz
    ├── a997e25a8f2e0bea0dd21e0cb1fb23f3383ee0c3.nq.gz
    ├── a9ff68c433708e8977c108324ea0827d324fb502.nq.gz
    ├── aa9decd77623a3381e8838b3a385e873788c56fa.nq.gz
    ├── abaa82833ee2abb668bfb4890b3e89e49a5ec534.nq.gz
    ├── ae978af02c3b7add54a7ca8fe3b54146e653e0c2.nq.gz
    ├── b00a82e47b2f068bb038db947db87b6aa7c07ebc.nq.gz
    ├── b1a29fb895d66ca822d22e675d0abd08a360f351.nq.gz
    ├── b1fa18e4eb90b3820501da401dcd1a75c79124c3.nq.gz
    ├── b2b43b45b6a4b866ef73f3c1006715ee72db4025.nq.gz
    ├── b62adfe9a95822c912ae856f102a99099a84c750.nq.gz
    ├── b644e505ab7761f8942177fda536ca6e9b01080c.nq.gz
    ├── b652998ebbc74dddb7526e433b7172d56c4785c5.nq.gz
    ├── b7dc893feefe8b5718949906ba0e6e06b400218a.nq.gz
    ├── b9edf34de1357d332b3f427f11b6b33a257a4d1f.nq.gz
    ├── b9f6eb41112663c95739bfc6487d105ede103bb8.nq.gz
    ├── ba7410ffc3ecd38c863437a7436b5a21e30e005d.nq.gz
    ├── bc7123983ea75907cf5a3614f884eecc70cb1dfc.nq.gz
    ├── bc7997c83d26754faa44a9eca8c027f01675ceb5.nq.gz
    ├── bdcd5607f743130358e328432b98eeec751eb1ca.nq.gz
    ├── be41b707364e54dfdcb8406b2ffe35831a08238a.nq.gz
    ├── be82434e110794289450c0c6b1f06c60611fe071.nq.gz
    ├── bee7dda2770cfd445461dd39b21573c10274fac4.nq.gz
    ├── c036f72f6a800d3786d9f7ca5c804596241f159c.nq.gz
    ├── c26405f91f7bb6d953f6c2747c22edbd51193007.nq.gz
    ├── c2e8c644454f99efce73e9fa0782697ddc158cf7.nq.gz
    ├── c41550ac8c8b570d47c01d067bb222ccabc65fa8.nq.gz
    ├── c4a6a87aa537edc8f555964d493a9cfd7699abc2.nq.gz
    ├── c50b8c309a85086a84aebd8af9622e1425c7ced1.nq.gz
    ├── c5d161f6c124d46b50c6ce6b51372ad1b3db0918.nq.gz
    ├── c5edd50ca36020d114d1cd69a09b795b01f5bd79.nq.gz
    ├── c6e6a3d05ce8cfaa3a985bb7a2e09ad8be4ccbea.nq.gz
    ├── c74e0221cfc9013956975cf844168f5254779425.nq.gz
    ├── c75cf2689dc37bc50705e9bac4140fdfe7854d26.nq.gz
    ├── c764ee8e86b81a10ebcbc0abfdb59ade1e073c64.nq.gz
    ├── c7d0293ac2eff71ade5f4bae8d44206df66ef3a7.nq.gz
    ├── c8973a69fcd8e3221974b1c8577290148e3f3ed2.nq.gz
    ├── c945a5a4175ab5ca1499e0e4285cbd982fc2636d.nq.gz
    ├── c9f17c6485fa1a56d6c5851e76c88df8ed115249.nq.gz
    ├── cb2f535fd4f16dd1a4b827448fa66b6d5de82566.nq.gz
    ├── cdec8b25961ec15dbccb38433ee3e5941c7b7da7.nq.gz
    ├── ceea5d94fd6b98df233a9a6b8d3453bceddad46a.nq.gz
    ├── cf446242bde49fd1b3b6236ab8199fda7e033d7b.nq.gz
    ├── cf4d1eb6174ba7bf9e6d88cb35b6a40e28cc18aa.nq.gz
    ├── cf5324977e9163d6ff360724a674e5b42ea30002.nq.gz
    ├── d0a3ef28b8edd11cf488ad0b6ef2762d541431f4.nq.gz
    ├── d2fdb210a51fa3a8a075c1881a8d03a6768f9063.nq.gz
    ├── d38f44646abb458cfc11e89ba715472883dd1b7c.nq.gz
    ├── d4104f7abfede9f99aaa733782645de66e866f45.nq.gz
    └── d595438ce4e12100e9a91dfb5011574dd01669a8.nq.gz

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

[ansible-collections/aap-snapshot-collection](https://github.com/ansible-collections/aap-snapshot-collection)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*

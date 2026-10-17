# Repolex Knowledge Graph of facebookresearch/detectron2

RDF knowledge graph data for [facebookresearch/detectron2](https://github.com/facebookresearch/detectron2), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/detectron2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1e3e13bbf607b54f62205c4c33922521822fb298
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1e3e13bbf607b54f62205c4c33922521822fb298
│           └── chunk-001.nq.gz
└── blob
    ├── 000e9f8898dba53f54121a5325ba5165e45ddea2.nq.gz
    ├── 002c0a3ee4892be23dfbcd103028d99911a32461.nq.gz
    ├── 0053c9d7d41af0ee7262804838d8edcde10ed40d.nq.gz
    ├── 0174b7dd528efcaa0fe27d46f40a3866f03e7c41.nq.gz
    ├── 01c3373b64ee243198af682928939781a15f929a.nq.gz
    ├── 01dd6955f78e2700ffc10ed723ab1c95df0e5a18.nq.gz
    ├── 01e1eb7854a9662b9595a7ffa9b0e484faf34dff.nq.gz
    ├── 0249b493e7446eccfc9a483287308b8f064e15e9.nq.gz
    ├── 033918e0daec8c225306dafac3a5fe9923189e53.nq.gz
    ├── 03f4211003f42f601f0cfcf4a690f5da4a0a1f67.nq.gz
    ├── 03f73b3bb99275931a887ad9b2d8c0ac9f412bf3.nq.gz
    ├── 045f7f02f1b4eb0c0ef1733c3ac65e3aa70168de.nq.gz
    ├── 04ff988d073ef9169ee4ca2cbce0d6f030c15232.nq.gz
    ├── 055fadfd781adcdfd661795edbc621d5eca763fe.nq.gz
    ├── 057c8768186e8a818228aa2f028ba3007374c571.nq.gz
    ├── 084444bf0338d1bab2ee426ae226a0f8004dd0f5.nq.gz
    ├── 09f7dffdb36199350bba57bd3b4e9e8babb40594.nq.gz
    ├── 0a055a65454517876107c621ba53e4742fa5eb54.nq.gz
    ├── 0b40d5319c0838fdaa22bc6a10ef0d88bc6578ed.nq.gz
    ├── 0ba82423ad498bdd86274ada56a201134a590d94.nq.gz
    ├── 0c373368891bbdf02388800452b11800cc6dbcdf.nq.gz
    ├── 0e01f6fb31e9b00b1857b7de3b5074184d1f4a21.nq.gz
    ├── 0e8299ed78a425c91fc2e43fede0b26461d1c9ff.nq.gz
    ├── 0eb44cc3b23beeb1755ab8d12002d26f13434235.nq.gz
    ├── 0f35b3ab1de3b1b58e9d7f9763c73eb1236f67d2.nq.gz
    ├── 0f7ad8bfc173eac554f0b6ef7c684861e8014bbe.nq.gz
    ├── 0fc9e977ed3174e244414378dd85d48ea02e635e.nq.gz
    ├── 0fe96f57febdac5790ea4cec168fa4b97ac4807a.nq.gz
    ├── 101191818c511cf90c3c8f2cbc55aa49295697fa.nq.gz
    ├── 110acff5a54247abb7b344672038b71e24167f33.nq.gz
    ├── 133d8d38e5e9f5f44aca92c59f73309e166d7132.nq.gz
    ├── 1398d70491bbbd86127a69f348e210e71a937305.nq.gz
    ├── 13a808e587382216da6fe7ee957603f448172657.nq.gz
    ├── 141657cdab24a2f591eeef763aef29543c43108e.nq.gz
    ├── 14b754395bfbc581a181c7062acc47311103969d.nq.gz
    ├── 1533a434bc1374a9825aa4fed0fab8abb2e8c02f.nq.gz
    ├── 15475b1ac3bb7272a7ebc0061a55119ffd2591b9.nq.gz
    ├── 1579187a7004e716eb3a86dbbfebb092d7aca84b.nq.gz
    ├── 157e3844ef68779cda3579bee5d8c132826c9fba.nq.gz
    ├── 174ca978de21fa09fdf79eca62936ef497aaf2e8.nq.gz
    ├── 1786fad5c54841faf86b1fbef83d909e3bf2b1f9.nq.gz
    ├── 178da7968cc08c29ec61b823bba8b74e8d97e1d6.nq.gz
    ├── 18d5b0b9d73f2da263e7e026a82c62231a88d279.nq.gz
    ├── 18d6dacf4b62e609aa85735a87daa8d2506000d7.nq.gz
    ├── 18e5f0720c568db4ef0c97b59688b5e7866df606.nq.gz
    ├── 1922efca976eb809a7e9f135bb8b55ef92389b6d.nq.gz
    ├── 1935a302d2d0fa7f69553b3fd50b5a7082c6c0d1.nq.gz
    ├── 194724eb414db073bde87bf482e5c647fa23cde7.nq.gz
    ├── 1a3cd282c2d1ede5c60a7c2c84846cbeed7808f0.nq.gz
    ├── 1a7aaeb961581ed9492c4cfe5a69a1eb60495b3e.nq.gz
    ├── 1aad53bfef62fb584d5022585d567e346f671a55.nq.gz
    ├── 1b5a098d171e508fcb9dd8088ecc1799c3068efc.nq.gz
    ├── 1be53eb7d78b7af268cd03d58dea042864518fb0.nq.gz
    ├── 1c362e1f9e93f9b9b458532f5318518396404d9f.nq.gz
    ├── 1c752029b7fc64ec375a55182e5342c9eb48bb33.nq.gz
    ├── 1edf83a2466c1c2b6c2cb9bec1aafd64074e31cf.nq.gz
    ├── 1f78d775889b11e9e76743de5ddb8139198edf61.nq.gz
    ├── 1fb3e30f97dcc02b497e7c6de6bcc9e47ea94885.nq.gz
    ├── 2072bb856ec40b61c3826cead2fb7bb7c971a089.nq.gz
    ├── 221c99f228f2214d9111392053073154e0ae15c7.nq.gz
    ├── 222dfddffb1f9bedf87f4c345534045b29e2d8ee.nq.gz
    ├── 22ad239fe320b8f9501f783afb134b975276a628.nq.gz
    ├── 22d10db7fe28ad66819aeb8e991f129301095ea1.nq.gz
    ├── 23a9c67cefe3cfca790181c90b27f2471d8a7771.nq.gz
    ├── 245c88482a9e2405e5a912b5c560aed78a614a13.nq.gz
    ├── 24fe59bda44225324928542df3f2ef1745375dfd.nq.gz
    ├── 251a7e823e38931fb1b86b017417538af5350944.nq.gz
    ├── 2535a1b99c1406dbd71d0cb5132886800ee7aa48.nq.gz
    ├── 259f669b78bd05815cb8d3351fd6c5fc9a1b85a1.nq.gz
    ├── 268e8402aa45e31e8ad5422e8c836915b0dc8e1e.nq.gz
    ├── 2743603ad2b6cc3f99aa0600c715887f7550d1cd.nq.gz
    ├── 28881e488263c5693835063be9455f2fb1fdc849.nq.gz
    ├── 290248e0685bfa332101f0454ba03688652dfd91.nq.gz
    ├── 2a06a09c80865ab987773511b2acc71e232b26ac.nq.gz
    ├── 2a3db5c62e7a2da52ccf5bac980653c943d630fd.nq.gz
    ├── 2a7c376da5f9269197c44079f3e0f3b09cdc63fa.nq.gz
    ├── 2ca1ede262cf5c37a3a54778458c74aff1479411.nq.gz
    ├── 2dcb54cb1054c5d80ccc823af21f13b9ebbcf1a3.nq.gz
    ├── 2e292d43c6217647b186d55b704b312a160d2c89.nq.gz
    ├── 2fab6ae78e887c630ad94e71aa6e946115c61593.nq.gz
    ├── 30b4ed774368af89d654c9f01850d769e6cf9f52.nq.gz
    ├── 318afcc22c0af30481cfbe4e712665bf476d32d5.nq.gz
    ├── 31bf0cfcd5096ab87835db86a28671d474514c40.nq.gz
    ├── 31cc28ac887773dbc8aea2a663bacd5f7b63bb0c.nq.gz
    ├── 32d92e7786336da0ed9582793620c33a3853195e.nq.gz
    ├── 3393794507c6504bf6ac1bfae7a1c80a0d81725e.nq.gz
    ├── 33d1d4bd2d9ddf31d55c655c49d13a8b7ac7b376.nq.gz
    ├── 33fadeb87d1ef67ab2b55926b9a652ab4ac4a27d.nq.gz
    ├── 34016cea3ca9d7fb69ef4fe01d6b47ee8690a13b.nq.gz
    ├── 3427215746c9a146bd902f22ea9b26d121c36b27.nq.gz
    ├── 34eb12d00d94ff905b796e75e2c4c5845257c8e9.nq.gz
    ├── 350a2ebf81b13839c3a16545984c05c1aa68f5bf.nq.gz
    ├── 3510a381439fb43adf1eaaf6a046ffd95f49b891.nq.gz
    ├── 351746f0c14d5af3a6694c10a7cd60edfff8167f.nq.gz
    ├── 35380af01ab8bd53b870930d2b4d623295511090.nq.gz
    ├── 364e389078e78935da9e432bc04b5530d2d9963f.nq.gz
    ├── 366a965c4adfdbba2482593c0c81f3e6af50dfd2.nq.gz
    ├── 36ee909ab13fd4d032e57191a4bd92a7d3723679.nq.gz
    ├── 373e6bf00a39c040ff1da49d6dcd39a54a0b69a7.nq.gz
    ├── 37ba18b2af6abf6b2b20d32bdd064fa6592c0cad.nq.gz
    ├── 382048e533708dec3fabf89528564ebc2ad4c83f.nq.gz
    ├── 38da8958e0174d378555887d72a9956f4b3f8e58.nq.gz
    ├── 3a43087b7c1a2b4d2b249fad117724dbd0f14fdd.nq.gz
    ├── 3b5412d4a7aef1d6c3f7c1e34f94007de639b833.nq.gz
    ├── 3bb100f9bd5b4939e4646821c5a60d51c8ea65fd.nq.gz
    ├── 3bccb7837a2e4b905b4e3c7af465c3be3a44452d.nq.gz
    ├── 3bf383b8ed9b358b5313d433a9682c294dfb77e4.nq.gz
    ├── 3caed9df3caa50c0d3b606e4a56a1959c463b710.nq.gz
    ├── 3dbcd86b753ab93185f03ac1b6b3c918da553e7b.nq.gz
    ├── 3dd209f693bd0bfdd46a2c9e7e750dede3abc141.nq.gz
    ├── 3e675c45d62f7b363a298099cd520c417832d58c.nq.gz
    ├── 3e8db8e82343abd352482e3d740a6922a1e12ac5.nq.gz
    ├── 3f146009d04aad2fca08d970569a4d76d46c9bd2.nq.gz
    ├── 3f65b76cffebdc3ccb0d86c0e476c761713202b4.nq.gz
    ├── 402d432477507dc36f04c4a9777cb80fe06b2809.nq.gz
    ├── 404b0c8f467264d1adf61e8274e5f864e24018e8.nq.gz
    ├── 40844ddeb8d47ff58a6af49ab35bad84e14f5721.nq.gz
    ├── 40cf18131810307157a9a7d1f6d5922b00fd73d5.nq.gz
    ├── 41395182bf5c9dd8ab1241c4414068817298d554.nq.gz
    ├── 4269130ccd25fa4640f6e6836b5256241f2d50bc.nq.gz
    ├── 449caaffd8a9d5e13040cb64aca073703c579a5d.nq.gz
    ├── 44d1d41a9eeb280a6f36e3df403c2c9d6c88f6ec.nq.gz
    ├── 45c110c19508f23921b9033cdaf0aa8056f0c125.nq.gz
    ├── 46769a2569ffc6223a95990f8db5973757e7d23f.nq.gz
    ├── 469a3ba33bbe32ced5a6aee76f3d7eaa6003791c.nq.gz
    ├── 46f8536ad26f4d47a53a95bed62548d8aff5047e.nq.gz
    ├── 478f034a4b8e1b48a1ace5c0a4823ecdf15c8536.nq.gz
    ├── 48c136f1623261b079591065fec7c7fc38165076.nq.gz
    ├── 49660fb96a54f059e2e66bbcaec47732bea84501.nq.gz
    ├── 49a55b1bc87509e2bb24b902ae12c21d5aaeda81.nq.gz
    ├── 4a24ce3a9a108a8792e18c8aabfb7b712f0d3725.nq.gz
    ├── 4aa319fc7e614f6a7a8ece7a45c177211c03012d.nq.gz
    ├── 4b827d960cca69657e98bd89a9aa5623a847099d.nq.gz
    ├── 4b8732a43f6974ec60168652bf08e382ddc9c941.nq.gz
    ├── 4b92392f1c4457033ae4c87a521e339fe9e184ce.nq.gz
    ├── 4c3b2176a3480cfe05220fdf4be329e8687939e1.nq.gz
    ├── 4c3b767ff473bbab7225cc8a4a92608543d78246.nq.gz
    ├── 4ddc2c1c6c5cff3e70df9b6001fcf43aae1d732d.nq.gz
    ├── 4e1723b339fe964211d77e05cc0d4d6bd99afe0d.nq.gz
    ├── 4e425a6ec44c7c47a5a106bfdf5ce8062c2110c9.nq.gz
    ├── 4e546f2aa74b4586d97618d41c69432ed01e21e9.nq.gz
    ├── 4e648e632d55c70f160d49630378d202fbde4e45.nq.gz
    ├── 4e6c82ef3f75a73c7006f33d7c850a0d4781a58f.nq.gz
    ├── 4ea86a8d8e2cd3e51cbc7311b0d00710c07d01f6.nq.gz
    ├── 506651730ef2ec4c7832aee5d2eb629dc3554805.nq.gz
    ├── 50667a8a836b933666761cc09d4175e64098c8aa.nq.gz
    ├── 5117a7dad0f952af02580e5373a7be52b749ee86.nq.gz
    ├── 51327dd9379b011c2d6cdc8299515b6df8112f4e.nq.gz
    ├── 51721d6c7468f9d8320868a4d8fd7672fa410eb8.nq.gz
    ├── 52f78762bda23331c97afd523cf98a5c118b113e.nq.gz
    ├── 52fc0ec03c8b87ab2be1dda97bec1e8c93e6bb5c.nq.gz
    ├── 54082d3abf119bf2fdba7206124893f35b4b4ae1.nq.gz
    ├── 55076abd15beb50b1774f0b5fe399b22d7cc630f.nq.gz
    ├── 550bb6e5756d43da3d30c8cd9b602b3bd30a7e4a.nq.gz
    ├── 551753b15a999774482e6e632b342acaa26f1b52.nq.gz
    ├── 557bd6a7294c9770068d0908950a7a8f6e476ce4.nq.gz
    ├── 560143d77716315f5ebd541007332c0b52f4b3f1.nq.gz
    ├── 5629f7383adcafeaa1ebdae1f38f968437149652.nq.gz
    ├── 567f70b2a63f561e3760cb72da7ff3777a633a13.nq.gz
    ├── 582ddcc3490da38db0169369816bcf776fa75845.nq.gz
    ├── 598081cb542ce64dd1d100c0d3e12a59f57b8e0e.nq.gz
    ├── 59ae5c887abd8d4ad3cbddca7461c3ebd19ec424.nq.gz
    ├── 59bb8b22518877e633014ce18b569bce7fc667d7.nq.gz
    ├── 59d98c72cceca33831681b5392d8bbec53fe70ad.nq.gz
    ├── 5a0488adbfcf0c7eca08616f43ebf695acad4b7e.nq.gz
    ├── 5a0b034ae10b83cf0f3b9197b984cfbc548ba8f2.nq.gz
    ├── 5a47cc05e6e9dc882778c6b502d93cbcec88fb88.nq.gz
    ├── 5a58758f64aae6071fa688be4400622ce6036efa.nq.gz
    ├── 5a9a637e214cbd584773a9fb6031368b5d32417b.nq.gz
    ├── 5aa2d280c66dbccc9ff8c3ccf39ccfbfc1eaa430.nq.gz
    ├── 5abbad1ffe191480177e2173308cdc946159cf46.nq.gz
    ├── 5b3358a4061b143c78eba8e7bf81fe9f7ffac1aa.nq.gz
    ├── 5b3ce884d80d9cdc2e0da07194693dd1bf16dd61.nq.gz
    ├── 5b3d4272c6f8a3820c8d354bfb3c915ccdebfc4a.nq.gz
    ├── 5c5b48b1fc6100dd531f7b61467876e222e40bdd.nq.gz
    ├── 5cf29eacd57626c676ed4c960a3e97e552b6dbdf.nq.gz
    ├── 5d0370b0400d9268f13c905e4096a84ce42e9bfd.nq.gz
    ├── 5d5eee135a93149a0c4b2148a47cee02e8aed8eb.nq.gz
    ├── 5e5c501cd1da6cece55210efefc4ec712075ca8a.nq.gz
    ├── 5ebafb30d3d8c5dfd24d03beff6d16bc2c9439fc.nq.gz
    ├── 5f05da03514a4ee6aa37d6bc3e678873ead73c61.nq.gz
    ├── 5f18275274242d77531569b2ab6042fd929bcc32.nq.gz
    ├── 5f52b2be3c9650cfc3e16ffb8fa374d3fcbad371.nq.gz
    ├── 5f8a8ba038588bf8c014390f8b8feadfcdc40307.nq.gz
    ├── 611903d287c6ccd4195f391bfb134ac2a7b5ddec.nq.gz
    ├── 6204208198d813728cf6419e8eef4a733f20c18f.nq.gz
    ├── 63c7a1a31b31dd89b82011effee26471faccacf5.nq.gz
    ├── 63dd41aef658c9b51c7246880399405a029c5580.nq.gz
    ├── 6425968b99c0903657674e3da0cd31463771a89c.nq.gz
    ├── 6665ab4c4bd40cae9973417b5b8d4c0c1edd7fc7.nq.gz
    ├── 67b70cf4be8c19f5dc735b6f55a8690698f34b69.nq.gz
    ├── 67e875a41da652b2fcae6631b76d94584935ddb9.nq.gz
    ├── 67fc401d70fe5e7d7baec3530d435955d4a23f7c.nq.gz
    ├── 68bec5734456c9bbc813becd5da83bc2a0f90932.nq.gz
    ├── 68f86c9cf4d43db68b7733f3fcacff285057fdec.nq.gz
    ├── 6947399fc4bd356a5c0e8168334e490ab651ae27.nq.gz
    ├── 69ab22669e2176b6ec661fc982be7412abb5e0e8.nq.gz
    └── 69bfc4b9ef52ed26c61ec3d3feb5aa9bfa28da26.nq.gz

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

[facebookresearch/detectron2](https://github.com/facebookresearch/detectron2)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*

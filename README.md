# Repolex Knowledge Graph of modelcontextprotocol/rust-sdk

RDF knowledge graph data for [modelcontextprotocol/rust-sdk](https://github.com/modelcontextprotocol/rust-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/rust-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ae2f9c9b45a2c98d24ee345406e79f507c9f9282
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ae2f9c9b45a2c98d24ee345406e79f507c9f9282.nq.gz
│   └── repolex
│       └── ae2f9c9b45a2c98d24ee345406e79f507c9f9282
│           └── chunk-001.nq.gz
└── blob
    ├── 0178bab9508d68f3fd5f66c185410c1783568303.nq.gz
    ├── 027a2cc869f88e5bc4bafaa43b4e38e1ed910849.nq.gz
    ├── 03661219aaf56a1494e2af4e7f91df92dfcb7b1d.nq.gz
    ├── 039fdf2eb7ca00f2c995ab050ef264a903aa9998.nq.gz
    ├── 04f31610ff531a31953b3ea908da49a4eefd648a.nq.gz
    ├── 05702b405b39b7add7029e8318c21bd6d5f7c40f.nq.gz
    ├── 05efe211039e23081c263e6316dc85f1fe93d3df.nq.gz
    ├── 06666329e8ba9811e331d1426caf336f56f6eee1.nq.gz
    ├── 0940f29c287553c8b20c1ddd300f1163113178f1.nq.gz
    ├── 09bb58d2ce2b992e456d8d9261940af849dac07a.nq.gz
    ├── 09df6d2850193bb51d06dafe4006064e8081215f.nq.gz
    ├── 0a7121e4ac8c40aa96407c2ea1d09adb1be4fbb1.nq.gz
    ├── 0ca0182f941d4e4963a8a55ed715dd4c8f293cae.nq.gz
    ├── 0cf3c7a6f846599da39b4e6712f689148d708c2f.nq.gz
    ├── 0d0fec7292c6e662ab908522e6ee27a70511cf51.nq.gz
    ├── 0e8339c0a15c2b2ed32f267728fb4830e37efcdc.nq.gz
    ├── 0ebbeeff17334809d0f7d800849e0d1b9eb32d92.nq.gz
    ├── 10795862480a92f55e32710f2ffdd6084fee40e9.nq.gz
    ├── 11b2f0e5358a7881d4f19f82acdbf1d66fe7a342.nq.gz
    ├── 1233deb567b25c9ae5d6b2596468bba5e9ce6e10.nq.gz
    ├── 12a5d4000090f1abab4792d2e839c222c256f736.nq.gz
    ├── 12f271f4db168f0e60ea0204b62bc33334cf82cd.nq.gz
    ├── 134bb1efcfe68273a3cb07aeb018a66c359a78e2.nq.gz
    ├── 13deeeb60023a86328aa42d67be89c2e09b4c0b0.nq.gz
    ├── 14a8757bbd768b80f96e4258e6b4a52e5701fade.nq.gz
    ├── 15354a4974ae25867021b92f36274300aa95de18.nq.gz
    ├── 173a0a2608ec649ec26abcd13df1feafa245db72.nq.gz
    ├── 17b189a743aa4f07a2b825182f8fd871a5bf8dd9.nq.gz
    ├── 17d4e97314ba2f3954c4148ccea05c7c61af4915.nq.gz
    ├── 1819716abdab627a8cd895341472c6ef94787f86.nq.gz
    ├── 18ec242ba8add1ea2b52edddfa563c9e788505e2.nq.gz
    ├── 1bf3d52ac2251382b09434152413582b841cb8c0.nq.gz
    ├── 1c0cf6ad28d1c8e2199d6a8a86f9bfbbc026df78.nq.gz
    ├── 1c8ee6986d985c34ae7549a525c312670af0473b.nq.gz
    ├── 1e0e5e5f9e869b1cefa3bdd873be63f1fcc9ce1a.nq.gz
    ├── 1ee864549d0839e698d4f481d359e06f0fc97340.nq.gz
    ├── 21d06aefc8f5023e0fd0c92588de70f427151fc4.nq.gz
    ├── 221389ed13b924d042473f5a1700c86d1abdf033.nq.gz
    ├── 226c8d531c4bd075d1915fb83f62239e848dd6df.nq.gz
    ├── 2288665b1dbdad0d5410c176785a38b6c9fbd759.nq.gz
    ├── 23ab8d05331f63acecdb33013b692a04e89d0a2b.nq.gz
    ├── 27cb75c85a264761752bdc1d2cb7a27879172761.nq.gz
    ├── 290b05954aaa3edd5c2f3c4628816abe1eb2b8e8.nq.gz
    ├── 2b40a8bcf8fd413289466d2ee59cda97cbcfc22c.nq.gz
    ├── 2cc6872852dff37079e40404b65a33d77eda7949.nq.gz
    ├── 2e5be845c29379429440310fa15125a51e8ed6e4.nq.gz
    ├── 2eb00089091a4179771c074becb6b0ef860861d1.nq.gz
    ├── 2ee37aaf17e74b8c0e1c58738c9645d338b8bd26.nq.gz
    ├── 30aed176115b719645c5386b1de0188421206420.nq.gz
    ├── 311b74ec09011a63871993dbcc17c69064717482.nq.gz
    ├── 31a63c1b2c598bb3c1a2c9e29592d4163cc51e70.nq.gz
    ├── 324f08f0c17b1091c6a7d1a2bec9d5aa3c36f5e1.nq.gz
    ├── 32df83c7846e265bea901c137f596662f732da93.nq.gz
    ├── 34b17625fe75696626333ad7b2f49d576d5f7391.nq.gz
    ├── 3542231da4a4b52d09feb7726d883f75334ccefb.nq.gz
    ├── 362ffb4abab014edebc36134c1031ea354510cbf.nq.gz
    ├── 36bdd590a4d14cd51f5b03fb08c450a5d7f43c30.nq.gz
    ├── 37585ac760eb42491f09d194a0c94ab76ff5fdbc.nq.gz
    ├── 3811c09f46e1890daba5e2f88250b77fd5336157.nq.gz
    ├── 38f7b34f5e2759f59ac2ab3b91a4cb94423b27e7.nq.gz
    ├── 38fcb1fd0e4c0fc5a8aafa45c53c7707a1524a38.nq.gz
    ├── 39900068d24ed346bdcac78e79767ed6ea253334.nq.gz
    ├── 3b2904a812b6d16cf4271310bd68b4b1d6e07793.nq.gz
    ├── 3be6616ed0b0a91a6ccd7315e1a5ee54aeef0a2e.nq.gz
    ├── 3c82fd42bbeb3f454c8f67fb9d38f369de1bbe59.nq.gz
    ├── 3f87ccf0134e3cf243438b81714910f1dcf2859f.nq.gz
    ├── 4005b2fe047cb48cc415f8fcb5535409876d0b6f.nq.gz
    ├── 419a176f9fd2ee38c80a36b466cb83f593714429.nq.gz
    ├── 41f74c770992b1ac3387f5a1d91a04b48ca4bcb8.nq.gz
    ├── 420759219d9a19b1355c4b9f8f8c0604f504d63d.nq.gz
    ├── 45acc946ce4da63234b98790772b7885bf96aa9c.nq.gz
    ├── 46f5168eaebddfb95514b09d47d4aa5f3fccc9b5.nq.gz
    ├── 479fcfa093819d3160c5df7abadfc3cdd5d59cd5.nq.gz
    ├── 47b6caf5503e35bafad50121844c93899a551e35.nq.gz
    ├── 486fa3bdfa9644159d2f274e581e8f3bb1a6c30a.nq.gz
    ├── 491960651d83efb3560526512767f32189af1d98.nq.gz
    ├── 4a93985763241755401a10678395303de4e720ba.nq.gz
    ├── 4caecb897242e6c63124ca91c709319e85022f6f.nq.gz
    ├── 4d8dc70aa53b9bea6203db4f1a92eff61ffb165b.nq.gz
    ├── 4eb77350ba769bb7404c5ec45d8412e5034ddb33.nq.gz
    ├── 50292420096eb98f07f3945dc30325fe8b17a2af.nq.gz
    ├── 50479a2376996f7db4a36f0cee212e93a1403dd4.nq.gz
    ├── 509fb4287c60d131071094579bffde811f23f3a0.nq.gz
    ├── 50c9b85b8949de8b6eb4dd7a914a0a9b48d4c40d.nq.gz
    ├── 543abe537a2a9b6021095e648354bbaf98b79470.nq.gz
    ├── 546621e34b58ec128d79cb6be5936b3f23d236fc.nq.gz
    ├── 54de5fa119baaacc3e9dadfa9a8ca1d8bccff04b.nq.gz
    ├── 54e99e535672b0056468075f201c65d8e70ddd1f.nq.gz
    ├── 572406bfdde3e3cce38a8f5a356cc09cf0a90f88.nq.gz
    ├── 573fdd28c64165b91b34ba474e3d6d58d21dc62f.nq.gz
    ├── 5854f3f54f648d9e5118b56004df14ab3a9bb02e.nq.gz
    ├── 587f8e2e7c52552b3f1e19d92b9c4a1dd9334112.nq.gz
    ├── 58e83ff68c870511ffc62904dbe6ef13182b7f00.nq.gz
    ├── 5bbfedd64a7a8b6ef8abc601bc31c7921659a51a.nq.gz
    ├── 5c4b5c80e807b7e7a800f73fd0c0cab154152a3a.nq.gz
    ├── 5d4419e5cee025e07b4f2bbcb12e5030adc8ba73.nq.gz
    ├── 5d7cee5562e8898b54e0beffc3cee60cf5bdb7d8.nq.gz
    ├── 5d7f2808925df598c733a07cf79c6b78240e1e5e.nq.gz
    ├── 5dad6554a1cb39142f3aa57799c2048a1353560c.nq.gz
    ├── 5ebe8fa68eb7717447f1d2b619b13c59b504a3fe.nq.gz
    ├── 5ec9cbac9e6279ea9f841e7c6f1dd67081ec6f86.nq.gz
    ├── 5f9128a42ec5d4ace4a4b5e086c6487f7a5d3532.nq.gz
    ├── 5fa2cd191a00b3cd899c0b503174f9159f6e09f2.nq.gz
    ├── 6068f4e95b796f4c0a7247d0ee2dfd1270017348.nq.gz
    ├── 61240ede1ae827049fd6ba1558ca4992f9ba5f2f.nq.gz
    ├── 62088e48df65755e368728b71ab7db0d401c125e.nq.gz
    ├── 6286b53b38d274f7a2eedb89ee74e06192862e4d.nq.gz
    ├── 62daa7ae8dd834db3f433fc2bdf6c071cf988162.nq.gz
    ├── 6312180d40933455c4687470b8eac4ff784d8063.nq.gz
    ├── 64be3fc7342f4236489eaa9c6f24e21b6068c5d9.nq.gz
    ├── 65b31a1a3fa1ff42ffa577bf28549a5e4538debe.nq.gz
    ├── 66ee1ff993b3e98a051df2a46ca5ce968d8d3d1d.nq.gz
    ├── 6766034dbbd1438aaea6ae9de21cb11349916ae7.nq.gz
    ├── 688c9ad47027d4f71756ade830ae2ebdfa60d76a.nq.gz
    ├── 68a32ecf701d69df852e4279de2ed20e5803202c.nq.gz
    ├── 6abd96c96c5aaeb9e380e34d7f66bc7d4a2b222c.nq.gz
    ├── 6b2bd9d391d49b58c9af1f05af945cdd81409ded.nq.gz
    ├── 6b848cd2cdcc7fd6aa33876411d9e6dae7f07ddd.nq.gz
    ├── 6c2abbc8d4a2c7975abb06b9209dcc222985bac3.nq.gz
    ├── 6ce30eb998c08c93d83a40ef1d2cfe87199a3081.nq.gz
    ├── 6d957ecd9bdc72dcbdf46db0395316b538694b55.nq.gz
    ├── 6e19a0c3b58f6602557cfb113d27c689b274c8a9.nq.gz
    ├── 6eea344ab1a54eecb145ac17d6f9bd952cc11b64.nq.gz
    ├── 6efd6927f0a7c76de41107e373eef7e1473876fa.nq.gz
    ├── 6f9aac634fb4187ddbc6d62cc230cbfcb9dc338b.nq.gz
    ├── 6ffe963046a5caf64faddc52060fce55e1ef3f68.nq.gz
    ├── 703258b1685760593f2ba709f7de3404219db3b2.nq.gz
    ├── 70aa219dc1172ff38dbd5ad9f23e602eac4d9069.nq.gz
    ├── 70f102f437e8b6049f83ac35c1a31e2d31f6de24.nq.gz
    ├── 72428fe65d40be1acc4eb7fbc03f9d488905ed6b.nq.gz
    ├── 72a0832d5cd69278212827545a5c53bdc517b611.nq.gz
    ├── 735953007b9b0560edbdb43d50c1e3c391ca5858.nq.gz
    ├── 753e4e4d7e80d4b0518c67bbadf7ae606c1c010c.nq.gz
    ├── 76005a79700b577bebb081aab684407db06f0460.nq.gz
    ├── 760d9e18c5908c034f3f8df198ac851d297e2a96.nq.gz
    ├── 7615d5921a33e30eb2aa6af79945243092043b6c.nq.gz
    ├── 772844d864c954f989ef7607e6e6616258378a45.nq.gz
    ├── 7762c979c75b7eec7c3c3287530631f0a7f7852d.nq.gz
    ├── 776590fcb8a2ccd4e80db01f92ceeb579c867821.nq.gz
    ├── 787d63411beba26515b3129ee354a01ad89fd677.nq.gz
    ├── 79d1c58c1a4b39b4da9175e4ea184ce0d6dce8a6.nq.gz
    ├── 7a556e84746777d43934c7966f1c3b0d0bea2058.nq.gz
    ├── 7b24d6aba2cbc55c9fe33c2669155e966dcdd0f0.nq.gz
    ├── 7c529796375cd0320c7e9dccb8f3a70799b9929c.nq.gz
    ├── 7ce3b5f8e840a00e9f6a7690ed2d13d6b0573a13.nq.gz
    ├── 7db5b06b74f73ec1099b34eddbdefdd9e7ac1304.nq.gz
    ├── 7e6862131b91b76a52ef3256e568866c3106b8b3.nq.gz
    ├── 7f018d0dcede44e2a2eeb6f219ff8a088e7b681b.nq.gz
    ├── 7f81472ba8481cb009b805577154f15fad2c6177.nq.gz
    ├── 815033a42e2917add9fdc05a7febb127a2e11ab9.nq.gz
    ├── 819d8b8fb9b8b2e076c5478b3339f0cfa2028044.nq.gz
    ├── 82e293ed541696d5874c329b188d952809324875.nq.gz
    ├── 83d2c35b04039985086600bf261f8d6b4d8f2f0b.nq.gz
    ├── 864932aa39616a6b9a2e349d9602f7508c5714f0.nq.gz
    ├── 867d3e7fa82b941071a59038ca4111ae26077b59.nq.gz
    ├── 86894e73a5976f204f2527bcb7a09a9dcd3a0f55.nq.gz
    ├── 86bf3a35e9e7251d8f743060db9cb49a249eb271.nq.gz
    ├── 8795924d2cc979193b0d3bc1b0c9a76eaac69c75.nq.gz
    ├── 880fab5531aaf02f2928553c67579c054e5918b8.nq.gz
    ├── 8992f81619a090017d4207fa16a44c2322c348ab.nq.gz
    ├── 8ae04b62646c832f0b38b1c30cb71ee747641958.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8b656201c8b342dcaa6ebea110e70faf57d52429.nq.gz
    ├── 8cf00c02f5d4bafc4e26bf9c871396046bb06a25.nq.gz
    ├── 8d3e4a8a13d6f0da41d1be6842d1d9eed77c395e.nq.gz
    ├── 8d79fb119c591bb413039497d392e4295b3a7950.nq.gz
    ├── 8dac9a39137d4178c83a4c3549165aefd50dce29.nq.gz
    ├── 8df1b7cad598e51c9e52c367cbb93ba38a95b4bb.nq.gz
    ├── 8fa18df8c3be9cf3f73b8fcd43d87fabdb14adb3.nq.gz
    ├── 8fcf9b41bab3f49d1a48fd90c7dd7e449d700a0c.nq.gz
    ├── 8fdb94675ce3ed1165b5c8308800863b0ed2107e.nq.gz
    ├── 9046f6b3e8a36f8d077ab4087e6013c5bec01567.nq.gz
    ├── 9182dc51f2c8268d56757cf830d25ad3da7caf3c.nq.gz
    ├── 92c86643f7d1819c77a9edc3757ab1472386cb56.nq.gz
    ├── 9339ab866549605eaa7e5aaccf9aef3bf75db292.nq.gz
    ├── 9372b015273ef94d0f16824b5a4910d0a376d917.nq.gz
    ├── 953648c0e612df68db9b42682cc274c5bba7b332.nq.gz
    ├── 961d9775b02c395eb2a139c26d3d876c42585874.nq.gz
    ├── 97018a55a75756b828059f03d490ef5e3cb88cde.nq.gz
    ├── 979ce7e66bc989d50841e71bb1470808f772df5f.nq.gz
    ├── 98e4f398e73f06f50ceda0fe2cc61e2dfa1e5fa5.nq.gz
    ├── 99826131241ff07271da52cb61556b3f1770be47.nq.gz
    ├── 99b0508104f36b7a34ff46ee661b3b59208fadee.nq.gz
    ├── 9a9d2ab82e1d812acdc8bb9a29ab45001f4ce1ee.nq.gz
    ├── 9ab302b89bc365b07ea27cb71c085e733ec0bc22.nq.gz
    ├── 9c045319a606504848d258bc0ba594748e76712b.nq.gz
    ├── 9c27dce2ffd950880cc5acbd778792c679855a44.nq.gz
    ├── 9c8ce6ae9f1e3a6ea3a192f393864775506522bd.nq.gz
    ├── 9e4db7fd36aadb9466666c7b74017c9da7929510.nq.gz
    ├── 9f0b3d309ac2fd1198acd81241ff456fa11a4e66.nq.gz
    ├── 9f45572c7af027633c9ef64cee7ddb7d04a63264.nq.gz
    ├── a0a99f0f728b480caaf9f8cca4c7462dc9eb7912.nq.gz
    ├── a22933e35f61e5222ba119b2de1f1822d0b1a3e5.nq.gz
    ├── a5811429a32db9d183b3677313ebe7ad4c5c188b.nq.gz
    ├── a81297715bfcda7cf2969ad928797e60b113478e.nq.gz
    ├── a946f752e63bedccfa140a0d0f32397f470fef8d.nq.gz
    └── aa4ae63c739fe548a329e7af87097716813011e3.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[modelcontextprotocol/rust-sdk](https://github.com/modelcontextprotocol/rust-sdk)

---
*Parsed on 2026-10-04 by [repolex](https://repolex.ai)*

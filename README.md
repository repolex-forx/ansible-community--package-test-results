# Repolex Knowledge Graph of ansible-community/package-test-results

RDF knowledge graph data for [ansible-community/package-test-results](https://github.com/ansible-community/package-test-results), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/package-test-results
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ec3a08f494acbb4fa901bca30f001ce4d2ccf3af
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ec3a08f494acbb4fa901bca30f001ce4d2ccf3af
│           └── chunk-001.nq.gz
└── blob
    ├── 01e5f0efe5a39d198b910a6a4631d5349a51164f.nq.gz
    ├── 022069ec714d44e9c186fa555b62bb7867c54b9a.nq.gz
    ├── 02e4093a02ade56c22561a8f414c6d044b16b278.nq.gz
    ├── 05811e9d151bb559492bdbd9aab911a9178aae4f.nq.gz
    ├── 05aa96b3d76bee348ed2a9bad55f2731164d440c.nq.gz
    ├── 060ae9d58d16163226e03de97b6a78a92d4b40ba.nq.gz
    ├── 06a2cfc4926ad7b7b287e652b3e55d8291ec62a9.nq.gz
    ├── 072796ae69d9c5490964c5db8c569cec8245680d.nq.gz
    ├── 0728b21fc9cec858dddfb89dd0453758e2f9c272.nq.gz
    ├── 0733cd3ec733755997e836ad253957f30b13f1a4.nq.gz
    ├── 081a6a9d5c552d9fa21ff04f094685d0a70c91a4.nq.gz
    ├── 0827357fa53e8e71b1762bba70ec7abc35992ad3.nq.gz
    ├── 0895a5be97d4b95b8914e430041e5927835ecec0.nq.gz
    ├── 08c070f4ac8b18ef26ecdd9a61034e17e4577098.nq.gz
    ├── 0a63ed4752c67976c3e6cd435030091cf09c14ed.nq.gz
    ├── 0c88fbbafb532694d97916b6f8c64c0a6a930caf.nq.gz
    ├── 0e0907297bf02e6ae030cbb29c4a22d856ea6ed2.nq.gz
    ├── 0ede4c2ebe216856efbd11f1959078d37978c792.nq.gz
    ├── 10255d3ee4bb67dd20bb8ddbf4b5e69128c21e5d.nq.gz
    ├── 106271151645523db7cd9c9b6f73ec08a2c6f7aa.nq.gz
    ├── 120724dee908ae6919753e0fd7aa69e8baed93b7.nq.gz
    ├── 1277c240eea2acc989ab4d0ef82f03af87d3e24a.nq.gz
    ├── 12a1768e58262e00e1645390e02aef6ce9121641.nq.gz
    ├── 12b3e97958de2fc60f73bd3d934c33648a247e6f.nq.gz
    ├── 1469d442524b1b140079f2755bb293f0c6494682.nq.gz
    ├── 151a5d765c4585d135423c70a18d16b2f82e3835.nq.gz
    ├── 15d7c9bbbe1d184781911ef4f0ba5eb2135eb768.nq.gz
    ├── 16b635442ee0d8d757d0ebf9770830bfd1e1d9cc.nq.gz
    ├── 1725bcade3536c209791aee5fe8314dc01848663.nq.gz
    ├── 17a75b8f76b9a7ce682b0e1d5a8572c7a8970d51.nq.gz
    ├── 1825d98eaf46bc2a217b9a3c5929be0b53e6327b.nq.gz
    ├── 184165e8772a2fcf4731231ee3b52c9c5154ff28.nq.gz
    ├── 188637f2268002a3a1d85c329da278c6ccd2fd11.nq.gz
    ├── 18eddd8786cf41466d5b9171750300a0e5318d84.nq.gz
    ├── 190749a33115fe86c6ad100cd323ae869f5fd2df.nq.gz
    ├── 19f986d7611171c9b1f64efe6ace1edc8a42198a.nq.gz
    ├── 1a597c5716edaaaa6ab3337c60ab770cccb71998.nq.gz
    ├── 1b3787ee9fa5e0ffd8219521055352e82795e7bd.nq.gz
    ├── 1bbe2488394b60fbeeed712311659afa4278f78f.nq.gz
    ├── 1bd459a600b419b3f2ae6772a816f5fc4f0175a4.nq.gz
    ├── 1c8d948535a5b259046ed88a0600ef30980bb816.nq.gz
    ├── 1c9a813da2eaf210f3850877a5ccd7d646b4d09c.nq.gz
    ├── 1e44717c9b57eeaf5ca2ff9e8db9286b91e71e03.nq.gz
    ├── 1ecc179a0772831768b3304a0055973b230f374d.nq.gz
    ├── 1fa2f2f127cfd3f2196c8ebcb890dd3d0e9d8932.nq.gz
    ├── 20fe0be798f450d7d2298730a726fb5884aced3b.nq.gz
    ├── 218e30e6fff966307bc1669e13a38b3a651632a0.nq.gz
    ├── 22ffd582e85428464853fc78b610584edb616c8e.nq.gz
    ├── 24bb5ff08f423dc0a6554c7b43a7c8721f800053.nq.gz
    ├── 2881838dd2f2379d85c563cc0bdd1fa2acc7ca9d.nq.gz
    ├── 292ee83ec82bf91b8556ac4d6aa244e17d58c317.nq.gz
    ├── 2a4ad9b55601ec9ad1a123785f91c799636b7af9.nq.gz
    ├── 2ae0312b053cf5e9e60d143957844c154e0b5f76.nq.gz
    ├── 2b6c37f4efc80004b3c949ef3a7f00d73f7108ab.nq.gz
    ├── 2c6ed979a0c5e9ea98ec14a33809fdb1f59f9777.nq.gz
    ├── 2d0bf355568548d40c1b6367251de257a4ed873d.nq.gz
    ├── 2d24e7837923b6dbf30babbfbef6a500b55ac8e1.nq.gz
    ├── 2e051db928a05d36fec78ab9327411008422d867.nq.gz
    ├── 2e2f854302f901b3d8847163ef9a9c866c1c4929.nq.gz
    ├── 2e4ebe54672ad96e4b97dad0bc650b23eedc7ad6.nq.gz
    ├── 2f826aca742fba91bd785e8c6a08ea98d9e5f16d.nq.gz
    ├── 30012f97cde6d535c30a710546bfe8d06f7b1008.nq.gz
    ├── 31d5064043bbb96f933b069401670cc31d73327b.nq.gz
    ├── 32918d00d621f848dc176f9c90dd5fff9dacb6a2.nq.gz
    ├── 32d1b6c141ea8d4dad2576d0f851383f9bda4b54.nq.gz
    ├── 36107df78d19e3bbfc524cd6181420745feac22a.nq.gz
    ├── 36d59ce1dcc80262ac04caac0ac24c41bf42d219.nq.gz
    ├── 380130bf553c172bd1b17d757bcef2bd4d8f7ff3.nq.gz
    ├── 381839d58b2bb8454ac62f9702d97942049d6649.nq.gz
    ├── 388975f0e0b337cf67d7685ff1cb6dc9cb4a7f2c.nq.gz
    ├── 3a648f9d3491360da82316bf214bf676af7ea704.nq.gz
    ├── 3a6ca229b0422fe8f330ceea628334223cfa9fbe.nq.gz
    ├── 3ad6b2af18f9671c00dfef99fa9489bd7685d41b.nq.gz
    ├── 3b3dd0868c95876ac8c4d45126791a052b15096e.nq.gz
    ├── 3b68d907b5e6934a2babed597a7d6845259a47c5.nq.gz
    ├── 3b6d02280ecad6633a247fd42e695ffff2fbadfe.nq.gz
    ├── 3bb4620d5d60c5c3c0f1d02097dee22221541edc.nq.gz
    ├── 3c2c98ccf9d25d81e944ff59c2fc7cc833172b79.nq.gz
    ├── 3c33b52de4c74e7ed7e2f36b348daafe0ac0ab64.nq.gz
    ├── 3d07c941077db0a4e7d601bd8ee53f3ea50016e0.nq.gz
    ├── 3d2e3e64d981e168f9e37b6d0d08298b1c6f9421.nq.gz
    ├── 3e332f2578f4cf10b34aa357fc5db7d2e9de9deb.nq.gz
    ├── 3e459985551758be9f758a76d12b9dec7089e853.nq.gz
    ├── 3e57f9714162eb4fc5b5e80207dfd0cbe9b04b08.nq.gz
    ├── 3e6dc58870fcb495adfcf92f881f47400ee98a86.nq.gz
    ├── 3ee349a9e26bdca2d01ece90926863f9098a4257.nq.gz
    ├── 3f0716b3b0bdfefbdcb44471f30b098d736bbd1e.nq.gz
    ├── 3f3d8de358b3f9b5b854e77f74b15ce2cbb7f9c3.nq.gz
    ├── 3fc6f41aaecf53097808b615ed790f939e317e3b.nq.gz
    ├── 40eae8b2aa931733daa0cf2481b11e517674d06c.nq.gz
    ├── 4119198447418178ffeb8975d520999f915da668.nq.gz
    ├── 41ac63c452a7eccf73b10b8c425bcc988b3865b6.nq.gz
    ├── 4264fc58e39dd67ad7228bdf2ceb88e7e72d7f45.nq.gz
    ├── 43438237d807544e8ae077c78bf03ef29ac26ec1.nq.gz
    ├── 43bf1c6922de3df95642edfaf71ae390d7b01ade.nq.gz
    ├── 4483be3d5485c7cac482ce87ce1fe94b3d8ad525.nq.gz
    ├── 449fc6878f6484527c97e9a34ed6e7698cad448d.nq.gz
    ├── 46137e5ff6a765c308e43fb3ad60e48e709267d4.nq.gz
    ├── 472db0c9427576e4d4475715f93304523000e019.nq.gz
    ├── 4779ba0c1f4f66258ed72b1ca0ab94b8038f9603.nq.gz
    ├── 47a49fc052e376e5fe8f39006f2596e7a1a0f0e4.nq.gz
    ├── 496609776b9cc7283640a33080ceae52839a1c0f.nq.gz
    ├── 49ff235c0c8795d2d80ab78c503a11ea6bc485ba.nq.gz
    ├── 4c1ca594d5974ce04f705962a465d58af003d9cd.nq.gz
    ├── 4e3ff544cf11b6fecceea2d82eb8fd1fade6b9b5.nq.gz
    ├── 4e4af578c6549a4cfa81055aa643898514b52730.nq.gz
    ├── 4e4da7beb8ba34603df90d5580e4797f59c40fbe.nq.gz
    ├── 50e7f41410babd3df34f81147f64ea19e20c1ff5.nq.gz
    ├── 522baf2efbbaaaa7ae337f6361e684dbbad59e04.nq.gz
    ├── 53126d1b6431bd8d938dc1a64418dd3b632e33ef.nq.gz
    ├── 542dcd2b5b914bf947ef2b1b1c127134cb18268b.nq.gz
    ├── 542f8805d699424f44eaf2a2eff29574d91acd5d.nq.gz
    ├── 54cc787977e3210690655a7c79e0677de43a61af.nq.gz
    ├── 5519e3130bd3233159f7468a36c4c59d776e66ab.nq.gz
    ├── 55a1c91fa4be21b5102c7216592536b853f42306.nq.gz
    ├── 56332c95f612b6db6475c454d0814b97cd1482ba.nq.gz
    ├── 580e9a974b5e80d402ff577104e3e789c7640d7b.nq.gz
    ├── 583fdfe54a52560241ea9ae8c821542d03bff4b5.nq.gz
    ├── 58fc139c9c8547290e90080fdce7970f142f9a0b.nq.gz
    ├── 5a2d6c2fa754bf6f82e9a1d973fb176664ef2c9f.nq.gz
    ├── 5a34b5876a7f40c3c3668ef503d78e761c3a4c0d.nq.gz
    ├── 5b5ef42fe886a9e81b792302c0578342728bac7a.nq.gz
    ├── 5bf52d19461560cd33a6f52e5e0748d907623af3.nq.gz
    ├── 5c948c7116c63ab52cb9bb6f7da96940a34e2693.nq.gz
    ├── 5d48f7c576d3df77655dd08c65034db942d4284c.nq.gz
    ├── 5dcb450a0deaf1e5c67b75c947da86b2b89db2e6.nq.gz
    ├── 5e56be25993133289a798fbd3974e023b305a48a.nq.gz
    ├── 610f3c25de5a583ec648edb272170d36ae4bbcc7.nq.gz
    ├── 61967dbf5d58ffa2215c36a4317d6c4f43bb6eab.nq.gz
    ├── 638130cd424ee914bd257824b931b21ce506710d.nq.gz
    ├── 65cb8f83f21dad342e936dfc96b8e1a1ef30598d.nq.gz
    ├── 6672f5ac72a1caed40454abe1cfd06bec864aa43.nq.gz
    ├── 66cff027c74bc57623ca3c61b9db30ac893d2fa9.nq.gz
    ├── 66df287d082a13fcaa296c7c7f72f1404547ea70.nq.gz
    ├── 683f0cf9a2ee58b17981dfd4553b6b6cc23b1059.nq.gz
    ├── 684e2575b1fbba198b634bd74d88e8c7a864fcda.nq.gz
    ├── 68f68d82fce5bb0d8beeabed7083881503a0f8a4.nq.gz
    ├── 6934add696f3f3bde85e00447ede5b55859fe133.nq.gz
    ├── 69d46e2558713b09be3a1398670b5243b97568fe.nq.gz
    ├── 6a0ee0ec1c1faef879d326dab5172af682675ab4.nq.gz
    ├── 6b39f4fe1c04715e325296415c320df41aca0fa9.nq.gz
    ├── 6bc59614a1efb0814ab25fbcd765d55ceb49b28d.nq.gz
    ├── 6c0a5296b519cf8b7816e82f6ec94c9b313729e7.nq.gz
    ├── 6c2546c5774aa80543e9c54ec550dc26d4535c91.nq.gz
    ├── 6db987a96167ffe8cccc72547b7e4ba0889fd88e.nq.gz
    ├── 6e0e6dc286a9732de25fc71e6fb988156df4dc0a.nq.gz
    ├── 6e6451cd00597033cf989e661ed904d0d7a1f98f.nq.gz
    ├── 6f543b0abd1bb14ad9addd18fc6032c626f01195.nq.gz
    ├── 6f6b6e74a3ec47f9f02ad74154249c30035fa0cc.nq.gz
    ├── 7026c2f3c23c850b9f7fdd509249c0a2c74aff3f.nq.gz
    ├── 70b09513d7ec75594f5a68eb796085e5f113c6ba.nq.gz
    ├── 713277939b8f41650d1317e9705dbe3fb1d4a117.nq.gz
    ├── 71b82e75c7e5252838d69cd9112cf730859ea319.nq.gz
    ├── 71d115ef9ced5177f1b9bcbd8d9a3b15dcbf0987.nq.gz
    ├── 71e7c477d4b567a2ed4d544b52c9ab781ec2f8dd.nq.gz
    ├── 720cb19d099befb66a242c432bb0eb02a7f4a7b0.nq.gz
    ├── 7317242bc1e4cbb1f4d1889544c636b02b7102ff.nq.gz
    ├── 73904b170e1137963ce274b15c18d828f292aa9d.nq.gz
    ├── 74825d5f3b1fd56a15e6aed4b9878f490bf14f2c.nq.gz
    ├── 7493af8dcfa64fec35b9c40840c1bd9b609e6262.nq.gz
    ├── 74d90c620f471f81c268ab179e03b2deeb06762f.nq.gz
    ├── 7558faf25b8957b468380ede386e06f8271e38f7.nq.gz
    ├── 762d207948cf546134dbdf7a0d2e731943e6bc30.nq.gz
    ├── 765036df7aaf569b5446f73f079ebe5b55433d10.nq.gz
    ├── 7686820eddfa1474b16637979ae02fc620bda2f8.nq.gz
    ├── 76875994d7d6efea497ffe72998a3c2cffb14998.nq.gz
    ├── 779f88d7400ffb0fc85002c527e4e729d4d80385.nq.gz
    ├── 7966807fcbc1ae0f2b878f88b2661279c14c73f8.nq.gz
    ├── 7996b63043c43738b645a6e0d4e54516f828bd3f.nq.gz
    ├── 79bf55c518841474994c06aacab7790f25d8183b.nq.gz
    ├── 79c97e5ff85d57d99ddf58774b3c8930a9dc1281.nq.gz
    ├── 79fb8809f0db203ccdc2fe29a40872339b632b84.nq.gz
    ├── 7a742e55f341b8ca671ae1ad007fb58ae8550b3f.nq.gz
    ├── 7a936d26cb3efc4369dbc7c45bc1181d5dc00749.nq.gz
    ├── 7b716e502275507b5f93f8438e26e88ac5e56b44.nq.gz
    ├── 7c232de380fcf7b6fe7dbb0891bf5244cd4bad38.nq.gz
    ├── 7c9ead796961bf07b46ec1bb386bb53743bf40fa.nq.gz
    ├── 7e03f9c2b68e8e202e98107b4459fe288b4ed515.nq.gz
    ├── 80041df28f4c2341f4b6a01834c15cf9d20d1d00.nq.gz
    ├── 80e83fdeec2f776f7595bf662db1057b6e8fd9ee.nq.gz
    ├── 80f9e254b2d00fa80089f83cbfa5bb1ba6293e3b.nq.gz
    ├── 8126b4a1faa234ecb3689c1217795f00d5211c24.nq.gz
    ├── 813c07f3f3b1377830458f8c045d393319e8d564.nq.gz
    ├── 835f908d96c2f94a90e770375c30d1a601e5bd96.nq.gz
    ├── 8404d171f83b40caf0f225c9f0fd4f97f1361fd9.nq.gz
    ├── 8447981b90657c2e59aef56d9c3d313b7ee865ac.nq.gz
    ├── 84e991ea46900b626d6c25643c37283ef415ef86.nq.gz
    ├── 84feed144b330502a9061b3f566456ba150e75bd.nq.gz
    ├── 8585ee41331d2d2a75d7fa5e3fc5df3f46b42e50.nq.gz
    ├── 85f7ed31e362c73e01565c7a7984c4a9fa055271.nq.gz
    ├── 874d07feacadc58ccd34b4a363a01aa46b39a919.nq.gz
    ├── 88098a3e89eff9049aab8e01fcb33b760072bc13.nq.gz
    ├── 8839caa495db29bce08a185acf8e053fb161c080.nq.gz
    ├── 88cf54c21478cfc103f18ccde07c63664592a4a2.nq.gz
    ├── 88f8b19e1f910d8c95665a8dc71a77fa63a9f858.nq.gz
    ├── 8a73739ff927d87232713b3a977405e15a12a057.nq.gz
    ├── 8b2ffe705c25e52e223d7a00ea3132bf7cfdcc0d.nq.gz
    └── 8c5de9dd098148b74d06226e5107854e7021b65b.nq.gz

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

[ansible-community/package-test-results](https://github.com/ansible-community/package-test-results)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*

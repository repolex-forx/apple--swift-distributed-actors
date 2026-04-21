# Repolex Knowledge Graph of apple/swift-distributed-actors

RDF knowledge graph data for [apple/swift-distributed-actors](https://github.com/apple/swift-distributed-actors), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-distributed-actors
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d816a10b70a6d537b2aa666ff735888b7ba40ab4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d816a10b70a6d537b2aa666ff735888b7ba40ab4.nq.gz
│   └── repolex
│       └── d816a10b70a6d537b2aa666ff735888b7ba40ab4
│           └── chunk-001.nq.gz
└── blob
    ├── 015b79fb600299cf640f5d8a545a55012a87c73f.nq.gz
    ├── 017b79ca564c26e43462ce6ae054b51e2f3b8d8c.nq.gz
    ├── 0353e9bae58f2ceaaa332ff0852ddc28a8406535.nq.gz
    ├── 0389ccf345352f5ebdc69008ceea084fd7f41ed7.nq.gz
    ├── 041a8d551b86a9da1995e57aad6b308cd3990324.nq.gz
    ├── 04618e5a87700600355ff7f419dc6a105e05e34f.nq.gz
    ├── 04e0cff2bbe2cf5f1c8958f5d0d8a08615279a4f.nq.gz
    ├── 055e4b1db5a5e7c3af767946e20d5b170c4e9239.nq.gz
    ├── 059843691babdac6067dc1c49f291ff7eb543062.nq.gz
    ├── 0646ee58317a5626912a5111695da9b016cdcd7a.nq.gz
    ├── 068ae7dc9c48bf436c0bbb1b759da09e5a3362a1.nq.gz
    ├── 077c39a1ffe900e9584c43adda0d0643961d41dd.nq.gz
    ├── 090bc9cb635ef2581cf3b35e3988b2ba0957c6ce.nq.gz
    ├── 093fac5a6f349f0a947e40a0afbc67f8be7bfb2c.nq.gz
    ├── 09d543c952bd6e0c3116a77e1f0623a608106125.nq.gz
    ├── 0a16def13815de615140fee92fe3341f5286e0ab.nq.gz
    ├── 0a337ca3b07151a9427c927c6156d917d17edcc1.nq.gz
    ├── 0a96c3822515a31d767239ed9b9083a4cf5c7aa3.nq.gz
    ├── 0af6dd37fc885eeed6b214b417dc3323d31dfefd.nq.gz
    ├── 0b05cc40cddccbcdccc8f7a7ab62cbc99bb64fc1.nq.gz
    ├── 0b1bd469dcbe00963fda67f2334890a0b526301f.nq.gz
    ├── 0c18a72275630ceebeaef91e7ef8de88dce30215.nq.gz
    ├── 0c90bb4df41235057af456098b8677b9b9b7262c.nq.gz
    ├── 0d4fccb1a8b91356e6d0313498eeeb4f72c04bb6.nq.gz
    ├── 0e6807c01f61afdefede7544f029f9f65d30373b.nq.gz
    ├── 0f016fd38be3d446494a03ace085a08056749c09.nq.gz
    ├── 0f6201f8ffaec45f4ac314a828d8fee41c1aebd2.nq.gz
    ├── 105ae546ac9132f5ffba36c80c9424bff6a67e37.nq.gz
    ├── 107ae1e1e2047436ed2f14ba75933aa275dc06f4.nq.gz
    ├── 10937a3040d33e3889d52fb59422367893d9505b.nq.gz
    ├── 10dab3ae48e14e3d51246248949b38304c127263.nq.gz
    ├── 1154b314e470443283ede8154778ee3d301d5f08.nq.gz
    ├── 11d00ffc7f7b1d8ecefbb078993347c9ad7b6f96.nq.gz
    ├── 11f821083d53b9eb8f2ea3fa38357759713dcfca.nq.gz
    ├── 127dbe7dab77e40edd0d3af61e69b5531bf8a0ec.nq.gz
    ├── 12db930ec69be26367dc0e7501fb8e0166615338.nq.gz
    ├── 131746bc8b66146ead718222166e8503cff3706d.nq.gz
    ├── 13b62e719703fddd556f701ff506c10459052bc6.nq.gz
    ├── 144fd9bd83a8575eba95d4cc39311290d9059471.nq.gz
    ├── 147d2b42d56d08b9a7e45061f928e4edde545bf0.nq.gz
    ├── 1533e9f9406b237595d28a12b0937cd6fcaf3609.nq.gz
    ├── 15441c35c3d5036b7080615ebc54801a1329fb24.nq.gz
    ├── 166d6a5e00c2df72ede0e74ee564359f5d700813.nq.gz
    ├── 16f159a698dead3b6694c016ba3dd4ed06039d7f.nq.gz
    ├── 176af896e9924101e272776048d8d78a325a323c.nq.gz
    ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
    ├── 1a44ba9bc1a6e5d2e90235a28d7d2176356ff228.nq.gz
    ├── 1a9ebf0ee4fb7103b8f18b09c19752efc3703fb2.nq.gz
    ├── 1b54227f7c5f72f1e05417e6a2e195fe0db3915e.nq.gz
    ├── 1bfb91a05edf24af223daab1c258f174323a2c7f.nq.gz
    ├── 1c1862d4cfd6edaca76461207226ad3cc5f1dd5b.nq.gz
    ├── 1c51cdd61ac38a6f5667227dedad03b366fffb3f.nq.gz
    ├── 1e85f399893432327b074242715a03c551dc5071.nq.gz
    ├── 1f2ed1b740251248ba1941364e585ba659ff34ff.nq.gz
    ├── 1f692a3e8e85e5f41f9b807def6ac474494694a9.nq.gz
    ├── 1f7c58dcc61b69fb73e28c9688e94ec978d277f4.nq.gz
    ├── 1fbee93699f79e2458ac0cb70f0dfc0fc46b1a77.nq.gz
    ├── 217ed87ee86e1d088db3ebe5374cf7912615f362.nq.gz
    ├── 218ca7cb3e236727712a937ba64d8ffa13589a47.nq.gz
    ├── 22890904a8d723f7c02ee914baf5caceb36929ae.nq.gz
    ├── 22b7fdbb86fb7f313cfb6d51fd12f5fd8e9d84c2.nq.gz
    ├── 22ce34f98a889d81bdb4454b21c6882944dcbe1d.nq.gz
    ├── 233155e2d291c5104f580f0a3be2aa5fe26cf290.nq.gz
    ├── 239de5501d76edb97821c14e951a042b0951899f.nq.gz
    ├── 23a08245c8af35062e7a16383cb6770117270102.nq.gz
    ├── 23b7d6dcfbd8612361d031c886763d3186781864.nq.gz
    ├── 246176e89af85c872ddf676df4e0a8e78f3deb14.nq.gz
    ├── 2477145f4e6f8340abd16be5482fcd2baee8d388.nq.gz
    ├── 252e2376d6579f68d76646be6fcf9613a7d0e6ac.nq.gz
    ├── 264da41cafedb2768ad7d853c890f00a783d3c0a.nq.gz
    ├── 266a10ac05e6152c072ab82f350843a90003b849.nq.gz
    ├── 2714038edc9c42daf99d5a50c4c1af76515bbded.nq.gz
    ├── 27305c8655b8f9b93d8446fd27288c30d9600b15.nq.gz
    ├── 2748b93fc9da5a1b6048bbf1ba2d1d6650108724.nq.gz
    ├── 27a3b2be55e3fe532d256a8a49adc14ec8882d91.nq.gz
    ├── 282952ae626cffc49d0154f81470a5415e45ce9d.nq.gz
    ├── 285d368df717650819501ae810c6535b83f2ab05.nq.gz
    ├── 28671e705b0938e36255c2b0ebbed693956d5661.nq.gz
    ├── 288a9aebf2fc8e4b092ef9b2210017f01a39ac4c.nq.gz
    ├── 2902182dc42cb25d1cf9aaf99afb24bcf6050ce4.nq.gz
    ├── 2909199b33767fff6572ebea06c2d815c39ef41f.nq.gz
    ├── 29e0c2296d2910b5ed2419e47c374cfaa79ade01.nq.gz
    ├── 2a08f05b3f8ac6fd665a1082149ffd566649f4ea.nq.gz
    ├── 2c4ca1790f91af21e443e3ca60da2640da7de905.nq.gz
    ├── 2c785cb6dcf01846a7d06962c29427644afaf8a4.nq.gz
    ├── 2d181438e49a0504fc952e16a1d435dd3e508632.nq.gz
    ├── 2d1e01c6775e7676930829352f1090a66fb4d047.nq.gz
    ├── 2d432a0fd3421b7a753fd5816a8899682d2b8083.nq.gz
    ├── 2d70ed39fe8841e63822c8d95823a9a1c6e6b36d.nq.gz
    ├── 2d877918163581bb24257460d5f303c69eb67d25.nq.gz
    ├── 2dc4c0b97d960bba07b9e4f6718edec1682c5231.nq.gz
    ├── 2e5d857d9acf231aa2206a064cf4e092b1505fbf.nq.gz
    ├── 2fe337df5ab60e89152a76bb30d9d0e31dfc9d59.nq.gz
    ├── 301e78a111ab8a2e35ba9fe2b1abddcdb5a2907b.nq.gz
    ├── 304c27058f9d1a5419c4ff3411c19df8e467ce94.nq.gz
    ├── 3085bb4820fc74dee29e2b9bc9ed698f88139dd7.nq.gz
    ├── 30e41c2af9f2a257aa71dc15597dcb092e8220ae.nq.gz
    ├── 310b891d79739b3063c9e8cca4e09a32b28dc206.nq.gz
    ├── 310e32a6a02ee4f512476d71750690872bee2fa8.nq.gz
    ├── 316c1bb603a4692013c0fbba9b3d775ae796cc90.nq.gz
    ├── 31ee453886b740394da34235e040e243a17de55a.nq.gz
    ├── 327be46954c3c329677b905216f5d94debbb25b6.nq.gz
    ├── 330f3229d395413b59141781c723720bb5ce12ee.nq.gz
    ├── 333ecaaef886a1ea29ceae82b0eb7267650dcd74.nq.gz
    ├── 33753c8ba28e33e1017a56da8753368cb8f79faf.nq.gz
    ├── 34d37e665a6604a6e10d13e8f21fadca0812a062.nq.gz
    ├── 34e6288730589b47a45fa8d628d4001371bdf043.nq.gz
    ├── 35fc3eaf28b9a162138a24e0bbc738320c9f3178.nq.gz
    ├── 380e9b992671112249ba10e9ae2f3e244d60dd40.nq.gz
    ├── 38e7020309c24364cf6523cf00ba5c909e255e42.nq.gz
    ├── 39509652b73e4f98d8a5d438df99338052fe1e8d.nq.gz
    ├── 396ad07de60039b4cedb4c07b53e6b10d0b90c12.nq.gz
    ├── 3a28325228e5224c00f902c2e57c25a0d7db9830.nq.gz
    ├── 3a7d80b7ef384db083965c647f70b64f634d2364.nq.gz
    ├── 3a988f116fb2849e5ada454449f92634d6d7c715.nq.gz
    ├── 3b1a4a7d5f4c145d50d6ecaa9bb9cc65942fd2f6.nq.gz
    ├── 3b29812086f28a2b21884e57ead495ffd9434178.nq.gz
    ├── 3b332b21f781c51e2c52eb0374440b28f3c09513.nq.gz
    ├── 3b45f13c80ce7d3919a842e90b53444407fb7d38.nq.gz
    ├── 3b8decbc13a97dc9218abc5c3e2ff22627d865d6.nq.gz
    ├── 3d0b711a7de4a5ed9b66cac81c764017d4c33147.nq.gz
    ├── 3d5a8d7cf68df9bf7cd8b05828a3c777d04fa727.nq.gz
    ├── 3e07c806335faf41989818f49d1bfc357431a676.nq.gz
    ├── 3e8eaee00d7d91fea46a9e5b18f0a4870d06e9a2.nq.gz
    ├── 4055eb5827511f251bd6f76f275b29a457adfe6b.nq.gz
    ├── 40ec39f20d5341e51abd64107e51fe2e307ee82d.nq.gz
    ├── 410510b51ec6365eb54256da375310596953dc75.nq.gz
    ├── 41841b179c53675513b032419f17f5bfea952819.nq.gz
    ├── 42b8df591d788becf49d3822ff36e6370760c9ff.nq.gz
    ├── 42c3083e636898838340cd24841419133fbd41fb.nq.gz
    ├── 43c096d2a205c8f141abf1ff8c5fff2eacdfa80e.nq.gz
    ├── 4426da8725dd7d7d119108cda66c02a8287a53db.nq.gz
    ├── 451fe58300af7ac5a838756bf365360a4d70654b.nq.gz
    ├── 45aa5dcacfee67ea38968c4271333d32e7622ede.nq.gz
    ├── 46ee925915e68822338bba575f3d53c97258e33c.nq.gz
    ├── 472fe2eb699651c7adda93b451a1d4f0869fa8d9.nq.gz
    ├── 485a3e216e5ba77a2588d97bd46bbae28d6c2d5c.nq.gz
    ├── 48632a475f6479a05ed749a73c921eddd6f8a37a.nq.gz
    ├── 486aa0470d3fc4e8c151d50e3a8ac7d5cc7fdfd3.nq.gz
    ├── 48ac0d72ff2bc10232a37e687c5872920200e084.nq.gz
    ├── 4a192287b67529ad1d2e839ba8d8d0d5138662d0.nq.gz
    ├── 4be653e9c3d8ae4cdb89a9562d9c5bf74dab9573.nq.gz
    ├── 4c4b93e63f19d7775ed9d4da6246a831f4088ae7.nq.gz
    ├── 4d87b9b3464e9dab716bed691af1149e56cb37d7.nq.gz
    ├── 4e1392c04a0ded0427b5b839790adf4a2f0b03dc.nq.gz
    ├── 4fee1e0529c64ac58af5142677dde71830eceddc.nq.gz
    ├── 4ffba2e161be6c98f14a1f0df59007d7aa727bd0.nq.gz
    ├── 509d138620c4eaca05a979b44d258f0d2fd13456.nq.gz
    ├── 50d5f0c70c82b19811842ed9110c6b7314a5832e.nq.gz
    ├── 50eee88c0f897c5ccffea27650c5349ace66a6a9.nq.gz
    ├── 51ce2946c5f13a68fb63e47b476f04bd64833b15.nq.gz
    ├── 52413c688b21cf8e588b9b6931fc24f6e28aebee.nq.gz
    ├── 525815fc24f2e30f0d53170e43af3a7d386bb69a.nq.gz
    ├── 527db0f6eedb187ecb7bb6d5f1e43f559c88a2e3.nq.gz
    ├── 540c79052f9519ef38e5b82a8a6433668e3bbc9b.nq.gz
    ├── 5431cb1a36a81d9d6e560f56677c0ebbef72c138.nq.gz
    ├── 55435f81c031d61aba165ae42bc20cda896733d9.nq.gz
    ├── 55d10bc5c836a451af4e9d4f995203847da68157.nq.gz
    ├── 5606c3d6a541d9c5dd9d79ce490a5afcacc410ba.nq.gz
    ├── 569ffecf164899de0afe2a4719d32b85b096bf44.nq.gz
    ├── 56b46c28b3132bfd7f49166505123150d31423b5.nq.gz
    ├── 56c0800792f65aebd1003cd75b54021613391959.nq.gz
    ├── 57e6d5b2c684c22ceb46c261fdf07159429f8788.nq.gz
    ├── 5997efcbad598c4d7379aa3aaac93d61e5cf1f75.nq.gz
    ├── 5a17c4aa58ba02241f84d4206a29937c7f4a6417.nq.gz
    ├── 5a2f7c9825bd0cb720966524eb62ce0a63bcfaeb.nq.gz
    ├── 5a405b4b0707d54b680a4fe1e9b9d948c61cbfac.nq.gz
    ├── 5aef1a8f11ff23a12d96a85efd15e737be30146f.nq.gz
    ├── 5b5385c561de409de3dd577d924a1c35b93bc7e5.nq.gz
    ├── 5b840fac381e0782d8b4574264121a49456f7690.nq.gz
    ├── 5be557cf057010d5c87e31f63ddd10a46bdeb392.nq.gz
    ├── 5e4cefb72f578b6ad6e766a849b594dd49b62ac0.nq.gz
    ├── 5ea39bef043959932632e3820f6d14882ed7315c.nq.gz
    ├── 5eb6bdb8dd0db277c1585ca4f959c67adad98ba8.nq.gz
    ├── 5efc8518d90b5c95f1b2ebc6c7a77ebacc80f6f8.nq.gz
    ├── 61e2bbb2f04f97f4d556fcf4cd552e981a2158ed.nq.gz
    ├── 62fb718006e9ed81c1bae8c46b18729b47d7a5f3.nq.gz
    ├── 637e1355cfcde5cb531f6df6528a849f7b4cf1fa.nq.gz
    ├── 6504b8d867e5e2f479baad636872fc87a2b36862.nq.gz
    ├── 65d613e42e1a805f6bb7f365cc92d952ee57b830.nq.gz
    ├── 66599df17107b6ffe863a70bbdb67150c7973859.nq.gz
    ├── 66d85c04c2b0664c7ce17a38bed436438033ae35.nq.gz
    ├── 677fea22b4ec8854ce45df5bcb54827458d0fd56.nq.gz
    ├── 69d7cea40f422675dc7d9c225a63c527afa70b7c.nq.gz
    ├── 6aeb766c1452f1cd26a9516eb374c6db22049160.nq.gz
    ├── 6aff4fb76878ceecddbcd18526701dd35d485df0.nq.gz
    ├── 6b1ee51c9d89fccf7fae91c61cb63daf3c85784b.nq.gz
    ├── 6b29667ece93727265aecc6be639c879bee38744.nq.gz
    ├── 6bd8287a16c6ec0661d9186d39bca68e62b9bac4.nq.gz
    ├── 6cee837201593c0681294a515f0e81bbc40d0a39.nq.gz
    ├── 6d7b1132a4c079a62506c2e9706b15c3f8821945.nq.gz
    ├── 6e90f8f13227399e2a59f9d8463be0324cfb211e.nq.gz
    ├── 6f81b154a254a3f0396d7a0e82844a337a3cfad0.nq.gz
    ├── 703f601e02638b2d6c4fbb6d3a14f7738f8af15d.nq.gz
    ├── 707f2d8d569472febe5e1444e72278f8fff0da41.nq.gz
    ├── 70fcc9a002302e1d28d1142fef970a8f2791f8e0.nq.gz
    └── 70fe8ce9f2ad969a334c0de460c69be850813d52.nq.gz

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

[apple/swift-distributed-actors](https://github.com/apple/swift-distributed-actors)

---
*Parsed on 2026-04-21 by [repolex](https://repolex.ai)*

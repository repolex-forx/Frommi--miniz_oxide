# Repolex Knowledge Graph of Frommi/miniz_oxide

RDF knowledge graph data for [Frommi/miniz_oxide](https://github.com/Frommi/miniz_oxide), parsed by [repolex](https://repolex.ai).

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
lexq download Frommi/miniz_oxide
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 86d92e8d284b0acd451e7b6db6bdef41ae9c9db4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 86d92e8d284b0acd451e7b6db6bdef41ae9c9db4.nq.gz
│   └── repolex
│       └── 86d92e8d284b0acd451e7b6db6bdef41ae9c9db4
│           └── chunk-001.nq.gz
└── blob
    ├── 00d15c367103289687fca65c023782e7dd711839.nq.gz
    ├── 00e47849b88de15e7521394f5d535685c8517467.nq.gz
    ├── 0127990a24b93b7e24338487e7c7ba52be09d438.nq.gz
    ├── 012e2ed2da8bc6499692a93c78a3cfc06110d879.nq.gz
    ├── 01556d241b498cb311fce3fa6330e49522b5c9c7.nq.gz
    ├── 01741248e8552afe7abdbfd90c03239f115ad9d3.nq.gz
    ├── 01ca51d2ae910eba6d650355828ae7cd2df00ae1.nq.gz
    ├── 01d9b27cde090d43037b4450dd053e883f44dbc2.nq.gz
    ├── 01e9e398f6598e670d634084415e3b31f3a1cdb3.nq.gz
    ├── 021a1b6806fba56a9fe0a424def90430a4945aec.nq.gz
    ├── 025d71313f46d3f53b7d93d34fa698903e6f3b55.nq.gz
    ├── 0267a66779987d556697a63e21bdaf7f6ef6776d.nq.gz
    ├── 02d9b456eed96766afec2f54265a7d9a173254c6.nq.gz
    ├── 03b1c73605ccbbd3ec66cc45fe5f81eb48136413.nq.gz
    ├── 03c9042f874546512a1b74b350e0a3c8c4a4d60c.nq.gz
    ├── 04744afcf52e9597db42847ec39ea88dad90c01d.nq.gz
    ├── 04cbc24f4fd095f3ab30e5efea4b1f34ced09047.nq.gz
    ├── 052bb57864a0ed53524b2ab40f9596867cb06d00.nq.gz
    ├── 0705573996e2eb02b44871e554f59b93171f0db2.nq.gz
    ├── 07a2b51e6198914fe0e32f5947b87c31a6fab119.nq.gz
    ├── 0811e2815bc2732f6d838203e578ae07ea04bbf3.nq.gz
    ├── 0887989e6ddab3b40af3cadf95f26a91c8e88a0d.nq.gz
    ├── 08b9811c98f0d90dbacc006ddcd80c5945b9ea55.nq.gz
    ├── 08c5d37f4d24ac4b0603ca3391afe04930f17298.nq.gz
    ├── 08f1a84a234e78e6d7476f15016a9b6679eb0f61.nq.gz
    ├── 08fe6dcb911389f4febb2a09d7670dcb136465ca.nq.gz
    ├── 095d70030b8b7f2d0bcbf99fb337e73d4f90502d.nq.gz
    ├── 09a6b8ecb0d4188d656d606c5bfe363b0fedb164.nq.gz
    ├── 09b010fab35759a10ff2d0b907c87c3b66d965bf.nq.gz
    ├── 0a31ce9958b7124ebf867d6917c302053770d8bb.nq.gz
    ├── 0ae609abb882cdb70ef487b03cf388866f4c0cab.nq.gz
    ├── 0b3fda225bd2d5f1ad4ef03604818c55020d95d8.nq.gz
    ├── 0b4be7bb18397e22c91ad4a35d991d157c30dfc7.nq.gz
    ├── 0bcb2366a57b6de9616e5ef3d92a694f9b4ea8a7.nq.gz
    ├── 0bdadd3f77c5deafec66be7f65541dd06a4d1485.nq.gz
    ├── 0bdb9a8391bca96703f7925d41d96a63206bc102.nq.gz
    ├── 0cc8b3ab7956b8424309a4b99503903ca3dccfa4.nq.gz
    ├── 0d474d864a69354a2a3367a4409281bfe5789510.nq.gz
    ├── 0df74fbaa581f87ebec16b6070eb1814f133a0f2.nq.gz
    ├── 0e555f30999b7eb6d190664d26ad76481b167e5b.nq.gz
    ├── 0ead7f65208b408a45197368c2e67fdd39c97e41.nq.gz
    ├── 0edbdb877a916b39b7174a64939dd86d2b4d613c.nq.gz
    ├── 0f7a5a92efe954bd79b021b0c5fd7a1aca9cd8f7.nq.gz
    ├── 0ffc9a2010c725796ce8a1e027e62e789d66c438.nq.gz
    ├── 1033fa7403257f94e01ee7694ba1a4c98c61d928.nq.gz
    ├── 1096f46fdc5ca849000794d23f9a0be100bbf082.nq.gz
    ├── 10d00074e7f5ca0f76f927e841141ade0bef0eed.nq.gz
    ├── 11043098bff04b1aa27ddd76d515636838e436fa.nq.gz
    ├── 1179c4e4f404807595366500755342368f05cc19.nq.gz
    ├── 117d9e8a88fd092da319fbb983fc27569211e25b.nq.gz
    ├── 1194d5c88a3fd7e645b8359d9f2f478d00b168ac.nq.gz
    ├── 11bf15007dcfaac13bf952372c7dc87f318f0825.nq.gz
    ├── 125aed3924878505d131787bf5381718f857ab2b.nq.gz
    ├── 126d733302f2837cd96d983b5d43909652398344.nq.gz
    ├── 128f3261516c810d14ac2b7ce6d9d9e8771c6513.nq.gz
    ├── 12f5037e652291e33824dee6518ffcf482d38825.nq.gz
    ├── 1374508554d9bd19d12add926045ce6605063668.nq.gz
    ├── 1377f300b71adf32d4ed358c218c2e74123771f5.nq.gz
    ├── 147dea6e66839bff45e67a82f9a33bbc5eba85fb.nq.gz
    ├── 14a565bd3859fbc6f2866bd4c3ddf4e97423c0e7.nq.gz
    ├── 15294a501aa6e73201b85ff460b2fcf0adb11e48.nq.gz
    ├── 15a6532249a6539daecb385e751755d6e614fe1a.nq.gz
    ├── 15ea7bf336a8c7decb6e14ca44d9c9f4b37c3535.nq.gz
    ├── 17002b936c5db2ae35e857b79ce6eb14292eb828.nq.gz
    ├── 17424845e46ab500cf83eb22af3a778e6cbab714.nq.gz
    ├── 17820748e142a40301601188f3b68d00b84c5976.nq.gz
    ├── 1898fbd7f8a9bb0087adbdc2a2d1d420810f2b5c.nq.gz
    ├── 193d8a28b1481dbf83b4d90e784959311fdefab1.nq.gz
    ├── 197732aa6321a888f659cd6bd22552e7432a5a50.nq.gz
    ├── 19da690b7f7eade2c775d9d769569455dc16af9d.nq.gz
    ├── 1a2a97f1c0055cf7b0877949276f2f2cf548e720.nq.gz
    ├── 1ac46af6973df2daa9413a58ba648fea30e2659b.nq.gz
    ├── 1b69298275a9d4b022d0f1d3c52c1079e028d783.nq.gz
    ├── 1b83018cc862a2f15d06e858e83e139d2b8b05f2.nq.gz
    ├── 1bee69994d43104210f122835e140b5ca55ab733.nq.gz
    ├── 1c23c8ad2351294270679d7ad8f79e2300ad93c7.nq.gz
    ├── 1c88b56a6d23f4da9a4d63310cf3e3792220cc3e.nq.gz
    ├── 1c8a0e7976207fb9f03ed7e260950b62b8b9d396.nq.gz
    ├── 1d5354f631d192cfbcd2236e4270ed603775585c.nq.gz
    ├── 1d746403398e79956c1ad2d0b832b2782905bb2e.nq.gz
    ├── 1e16e082bbbcc4df953c1147149993acdec7ab66.nq.gz
    ├── 1e429c90a7f67b920fd8479ffc23ebf84e9c6b93.nq.gz
    ├── 1e436c87d5c8647540833c7a33a44d7dff95c1fd.nq.gz
    ├── 1f94b393c8e349aca3b88114d8ec20e11950424d.nq.gz
    ├── 20401d43319cc1fd896c5a3523f4ba53f6b58044.nq.gz
    ├── 20893cc28b7224183b11fb9d4cc3dd9b87893ded.nq.gz
    ├── 209bcaebf30100c8f84fdef5aebac2e72b98c9c3.nq.gz
    ├── 20a1a5117843dd2a3f896fe74f879f0a5aa5eb53.nq.gz
    ├── 20ad0f613418b6b268db8f16410b362a13263eb1.nq.gz
    ├── 210c8870b46f69859e615db0e2b66f422a7006f2.nq.gz
    ├── 220d567aaaea51fb4dbe372d30641419ff0ea302.nq.gz
    ├── 22781871bc4d3bd12bda714509235f5ea16a4915.nq.gz
    ├── 22f1adf12eddec16e81adcd93e0a9220e9f7b9e4.nq.gz
    ├── 22f473c9bfbb753ef16bd08b7691bde6f4b4a527.nq.gz
    ├── 232c2b65eafeae0cc614bbb189b3711df126aec2.nq.gz
    ├── 233796443aff7e5499ce5facc94c43af7cefafb7.nq.gz
    ├── 23534b584f68c0843e621c1a888edd6800364bda.nq.gz
    ├── 235a205f0a2f6e69a56de8eeb7dcd31e709e1b98.nq.gz
    ├── 23756964d66b2e582f98c6623b36258c23997462.nq.gz
    ├── 23a23d08a9981a4ecd2a6de078c81e47e7f33d11.nq.gz
    ├── 23aa5824af7557e3bbf58b9d95329f08f01f78f9.nq.gz
    ├── 247a0538360e0d9b77039abe8aeb3bce79782a11.nq.gz
    ├── 25ed40b6bc670b1b98ad4f977d5288a0d3c4ee77.nq.gz
    ├── 2620a0e2b552178038077231cf8c98574b2ec344.nq.gz
    ├── 26a8ad43e9d731f25d4e7a0bc922918888af7ef9.nq.gz
    ├── 275c5f6552824bf4e6fb10c98f07df88b27e49a6.nq.gz
    ├── 2832cfa8dace1d99d93dc4806a57dfa85de9edfa.nq.gz
    ├── 28cb0b54e5e90e6482b8b1dbfc0b64bab72d7af6.nq.gz
    ├── 2978b2552ff921603546ae279db1bbdb7b353583.nq.gz
    ├── 2b26f088ba172f085bfcc9c5ec194804348bac48.nq.gz
    ├── 2b3414ba60be4c82ec36c2472927012e954a5458.nq.gz
    ├── 2b71798a083beef1c1214e9276806670bdb50315.nq.gz
    ├── 2bbc547d9745ec8734b16b471a960c5e1fdac282.nq.gz
    ├── 2bd27028cc8ee9df053fd764bf7e36ecb271bae4.nq.gz
    ├── 2c518f3f496a921aa6a08f65eb06937768164c0a.nq.gz
    ├── 2c6042ed1967e923b89103d43fde5672e2d4321e.nq.gz
    ├── 2d4e298fbe49a2bc72aeea3a0276808b9b45c114.nq.gz
    ├── 2dbac7cbf535225aea6127eeefeaccfa986b8653.nq.gz
    ├── 2e1ed92fd2e90b677e35aa6d026c198053900b3c.nq.gz
    ├── 2e424161e3d7cc083382f938c165b7a5c7448e58.nq.gz
    ├── 2e80c50b123d65d9e33fab83da64e89c77c8c727.nq.gz
    ├── 2f1ab6f14c10228e76e514edb96bc919f2638403.nq.gz
    ├── 2f30b091a649ad2ac37d3bff5b2a7c075d832c61.nq.gz
    ├── 2f5420f764851125991e8f76cf15e24e04d2841a.nq.gz
    ├── 3001d292124df3c65876d81db2fb197cc89ee901.nq.gz
    ├── 30784e148c74c7de9ce6e6955677712938e8b9b7.nq.gz
    ├── 30dd1ba6acef77323b0ebd635de6a70c02e834bc.nq.gz
    ├── 312cdbc9a50591cf90248102a78e98816b6560ad.nq.gz
    ├── 31ba7297ff335ad215b2c61b4a3efe408db09f90.nq.gz
    ├── 327b0ef02cab744e3bc805d2f9c38e032a66aa04.nq.gz
    ├── 32ed2d0f2803c987ae02153a793984406313c3c7.nq.gz
    ├── 336f35e01393b871fc07a85e972f644e1bd7014c.nq.gz
    ├── 337874d48440df769beb2b428a41fa1bc5846868.nq.gz
    ├── 33791df7f044ffcd8d945b8481927d0c861e88a2.nq.gz
    ├── 35a4a6c40586fdd36f2001b65c0c8b1f27b4fde8.nq.gz
    ├── 35f7099be64e8e934c9398c0593ee7525dfe5a06.nq.gz
    ├── 360b0cbbf30850c8ea7047dd8f07d7258912b094.nq.gz
    ├── 364b4c19429231b67b851a02c93d9ff0245b7f36.nq.gz
    ├── 36e757ca9f679555ecaa91b9f3b604574e1c3d67.nq.gz
    ├── 37286935a7a8ee09e94c3fe794c5fe2f5eba29c0.nq.gz
    ├── 375a68380055dc657c60d118f9366b17f31b8fd5.nq.gz
    ├── 3787efaf624c39da9ae91b8a77519f567e0177f0.nq.gz
    ├── 37da2841451107b3def53d6f681176df8ee9562f.nq.gz
    ├── 37f0ebf045a43f4da95be68d46d6659c313a687d.nq.gz
    ├── 3801364817d9df28fa348112e98ca0d1f16eadba.nq.gz
    ├── 3863fed290d5bb4e3f046fc084cebf73e089563c.nq.gz
    ├── 38a6efc6690b11187489c7a376221fe76ee7055b.nq.gz
    ├── 38f398ff3c7da14fb95fc05945e9accd23ebc30e.nq.gz
    ├── 39534959c02f39ebe0e8705ebfaa8227be9160b7.nq.gz
    ├── 3956d0c84115e1827fcc04d746ffd827098e89c9.nq.gz
    ├── 3a3c07ca0da5e3582fb1bb915dbf772ac858467e.nq.gz
    ├── 3a427beb8b9ca10314fd43ffa81713f4ae68ec33.nq.gz
    ├── 3a515ad8f67484b820a864ee5d29d1303ebe023d.nq.gz
    ├── 3a521f3f2a6a48e2e124e7b4e093cb543cd99c65.nq.gz
    ├── 3a91ce22aa1e41da4bebe7c16b061f0cc0f3ef29.nq.gz
    ├── 3aace3415bf7a754057d956d27db9dfb144c02c5.nq.gz
    ├── 3ab26bc631cd0d2f4350f7ff5538256934db5f77.nq.gz
    ├── 3af9625cf971490c64a1b4d339d140bee37eb9d3.nq.gz
    ├── 3b5b3ede9bf87110305eb56ee25773bec7a07b3d.nq.gz
    ├── 3c6273ddc1ccf88c9277ed8cb68e2d1986e74c89.nq.gz
    ├── 3cc3b6f8c19b0f16be497aeaede0af3dc57be531.nq.gz
    ├── 3d2f55a1445ad8932c479fc2bae501e523f8807a.nq.gz
    ├── 3d9967e18a190a1a63444bb39a00f0f7ecb245c5.nq.gz
    ├── 3dd2bebf9aefa38f934d0b24421eff7a44f40a0a.nq.gz
    ├── 3e030474c34ec19c023e5caf0b806f8f1bbd2186.nq.gz
    ├── 3e529c81d3597237113a3c4a2e77da1e3b7429e3.nq.gz
    ├── 3eddbea745a7a45f76c46361914c16d2cba9eac2.nq.gz
    ├── 3eecaca9d8ca893c9ffe9e19f170f492c6d52f98.nq.gz
    ├── 3f589f0365b617825c3900c82fe394dd82e79094.nq.gz
    ├── 3f8fd73247f8bac45d83c1bc63ed0b33322a23b1.nq.gz
    ├── 3f95c29fc84370b85f51a9353c2fc1e4b2210267.nq.gz
    ├── 3fc0955715cc52a4d30facdd4199edcc14035d7a.nq.gz
    ├── 3ff729bb44262e8a7a087dd1a1a75b23644a303d.nq.gz
    ├── 405d2a447d3782f9f962fa5da3a4b4bfd81f7138.nq.gz
    ├── 406feba9c7ab76912620c06e3bc7d04a85b8efd3.nq.gz
    ├── 41b890839476f73200320c9ff02367ce0d66641f.nq.gz
    ├── 426fd9640dca2d6f2a58d7963cfaa64f1e3cd241.nq.gz
    ├── 42b76b283089fe22b2facad58a2db901a694541a.nq.gz
    ├── 42ebe519664fa5f66813627144586f8dda198ac5.nq.gz
    ├── 430af9db113552793fd9c7074e5154cb914527ba.nq.gz
    ├── 4418cf0a0f3bb76cdc9b378d08a14092b06a8e80.nq.gz
    ├── 4419eb0c2185e24b666a9e8b1a83a6a60862da27.nq.gz
    ├── 449f8e8214dfb8df83653c61298b133c67946339.nq.gz
    ├── 45b1fa508d64f659f8f81317afa3b9b0e0a80eef.nq.gz
    ├── 46821e0c86ea3ef063ee28dce6edd2e78cd8f718.nq.gz
    ├── 468e2cc95605d2e4b2fb4346ea382362f1db1b0a.nq.gz
    ├── 4693e6ace6bd500b518e20931673e36d2ecf085c.nq.gz
    ├── 469ed9179af3a6975a411313ad41513b366defb6.nq.gz
    ├── 47e6b262b8e5b6c6117d921b13704bd98c0955ad.nq.gz
    ├── 483b63bd64eaf3fcf784c2a5a7489ee8897c82cb.nq.gz
    ├── 48b6eca260ac3a927c134340691e898cefc7dea0.nq.gz
    ├── 495c3545ed0c000d64e40a4e74510be324ffc77b.nq.gz
    ├── 496d2e5e3389a67dee089fac8b3010e878fc1a1b.nq.gz
    ├── 49afacaf18c910bb1db5acdf0a8277195aa8d468.nq.gz
    ├── 49badfecf4425e28dcf8ab11cb1fae0d94b6bbc5.nq.gz
    ├── 4ae15a8cdfd32985cb8d8be7a94862c07a354e7e.nq.gz
    └── 4af82cf578a7bed1af88f4c970b1205cd9ac6be8.nq.gz

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

[Frommi/miniz_oxide](https://github.com/Frommi/miniz_oxide)

---
*Parsed on 2026-09-07 by [repolex](https://repolex.ai)*

# Repolex Knowledge Graph of astropy/astroquery

RDF knowledge graph data for [astropy/astroquery](https://github.com/astropy/astroquery), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/astroquery
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── efbcc3e940dcf182a4dc26266d5e0111b70947cc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── efbcc3e940dcf182a4dc26266d5e0111b70947cc
│           └── chunk-001.nq.gz
└── blob
    ├── 00de8e2e16bb445ca2b5fdb9fe68d810f52e6163.nq.gz
    ├── 00f99717527a9059a6f16a6cca0411a573eee1fa.nq.gz
    ├── 022d19c2e031f2d447b943d53111528ff7c603fd.nq.gz
    ├── 037bcfaaadf7f42189898f6d34abffd94b8d864a.nq.gz
    ├── 0485a7e3543cf2cb8a0d2466795feda56cd4271c.nq.gz
    ├── 057b08282c387175911c813463198b040eab5184.nq.gz
    ├── 06b591d99b87f569a4691b44b39ad4aeff9441dc.nq.gz
    ├── 06fe0ef27f28dc3e88e0900897afbf61b2268d49.nq.gz
    ├── 07b189ba0e93646f01fc886c9c3827df2329ca43.nq.gz
    ├── 07cc2e7d88ab0ff42df867af0044d382a72e9ff7.nq.gz
    ├── 07d33545b6ba1132df401bcfd6b5a25ca0359ae5.nq.gz
    ├── 083f8cb394330a5ce6f20865a898d6414d57ce55.nq.gz
    ├── 08c1894965730d3652d1970942ac08b6a8335843.nq.gz
    ├── 092e86ffb179fc57efab779f768b4a05f4b1002b.nq.gz
    ├── 09c98685bb05f943b052deae99e2a9a53f034c99.nq.gz
    ├── 0ac9c046cda99adf8875cb083a775f561eb11c6a.nq.gz
    ├── 0b630fe5a8c6083eb12415066f6cf75924a88d48.nq.gz
    ├── 0b753ff7aaea59b75c9bb20f63465913fc877ea8.nq.gz
    ├── 0c8a4ec996963bf243cce361abafe10af5025d9c.nq.gz
    ├── 0cb83db14bb5f597dff2eeb1dc3b91bdc480e032.nq.gz
    ├── 0ce50385a945fdef392e00820ffb56a244c7acfe.nq.gz
    ├── 0cf191a93253c2317eacb91faece88cc4017ddf7.nq.gz
    ├── 0eb5d45a8c438f394a1efe073545323951ed975e.nq.gz
    ├── 0ecbd73dd3f80780200f070ad58f7d5c8f5a89ea.nq.gz
    ├── 0ef6ffeef18f6d8048826c8eb9b1b49f7db2cf24.nq.gz
    ├── 0f1b2e01e11ef79016486d7e5ac1218dcc7b51b0.nq.gz
    ├── 0f87bef2b94714e7c7880d473f5d49acb3a0e8c5.nq.gz
    ├── 106da3e0724d92796ec0540020f50f51c0bbe8b0.nq.gz
    ├── 1197417d937fa59d56ddc26786113f6bac9639b2.nq.gz
    ├── 12355f48b51fa7ff8b1e5dda8d3890c7c508d3f2.nq.gz
    ├── 124ab8e7df729bf8215d0c7452ed54ef72e7051f.nq.gz
    ├── 1293a0c654d8f912aadab7add94d83d6cd84664b.nq.gz
    ├── 13824dd4fb87c4a02ef4bbb68f5aeb587caf33f5.nq.gz
    ├── 13e4037f4928fd970431a3a5c9f738c25e928329.nq.gz
    ├── 1556e84204f8322739d112e1d1308e5039ba73d1.nq.gz
    ├── 159bf389eb13ddf22f77d6a278db3b51da2902cd.nq.gz
    ├── 15a040e0085d0d121b0950209979b2d86dcf12ba.nq.gz
    ├── 15a71d419541d777f6fbf32be1bf7315f8832394.nq.gz
    ├── 15d8a1679f51847b07071d8087f0930ec7f98664.nq.gz
    ├── 168678d5eaf620591a0556bf1b58564fdcc56a48.nq.gz
    ├── 168b8efd97f97d7e3e16c5c17288a79e2f5de512.nq.gz
    ├── 1705da75f419994535f7c3574883e54e3bce9346.nq.gz
    ├── 185b979247f4c6e0730914ed20508f8a66fea377.nq.gz
    ├── 188bd4843700a235277eeafee4c08c12e345747d.nq.gz
    ├── 19079f8743d54dbe9691d2f36f8ecf5b0acdb0dd.nq.gz
    ├── 19692ea66a68f32a361226d9347e8eb136290b40.nq.gz
    ├── 19ac49e6c770a07e68037786baf36653df0e84f4.nq.gz
    ├── 1a79aeb3ac9908921e212ab1f34197278fb57450.nq.gz
    ├── 1c0fe44a242152ae0265cd8dc7b337d20af7412d.nq.gz
    ├── 1c25899ee9eb24424f2a98dc476ceb7366b01377.nq.gz
    ├── 1c36d364cb6b1d48c90f8a4b30e9ce5e7e0ddc2f.nq.gz
    ├── 1cf33395ef17241e384fc68dea5b938f2ca3f418.nq.gz
    ├── 1d25496e3f16e16a24e8afa0b1252f69961c929a.nq.gz
    ├── 1d86f55a56186c22c02ce3fc07df91621cfd22ad.nq.gz
    ├── 1d9aed171bff929a60bc7dda0107be43a27f1509.nq.gz
    ├── 1e8efc6d237684915a108ad6a3e0c7f27da2561a.nq.gz
    ├── 1effb7a86959d331c62bc893b1b83b890eb2c6b3.nq.gz
    ├── 1fa07cbb32d806df0c57cb789025b4ea7d4b4ffa.nq.gz
    ├── 1ffc386cec193a0c26b1a6e260d87bd5949a8319.nq.gz
    ├── 20317d7c8bae080aa44ea0bf1649698bdb2c1020.nq.gz
    ├── 21fdb7b3117fde945d7701fa4a8494a61f55a938.nq.gz
    ├── 226f14b079c4f105be7428a07ba9beb58e9b1f3a.nq.gz
    ├── 22d28df67cb3b05f12550f7cea844864b08b348e.nq.gz
    ├── 232c0e6968e1ad82c9824e4f4ce7ed43de24a12d.nq.gz
    ├── 23365a7af90408ac1a9b6ae3a46068e0e681d1da.nq.gz
    ├── 23376341cf3e773aa3591a80cb3fbc8e4afcb2ec.nq.gz
    ├── 23d2b92ef3f1a6f808ccdc234600d58b0cdc4989.nq.gz
    ├── 241515bc68e4e8fc7b6ad4ea058d789f7999d7d7.nq.gz
    ├── 243b1f3d52d7e105460fce2369c642560a2d9995.nq.gz
    ├── 24a3f9124fceba9e7e560ed1c0946c173a637d38.nq.gz
    ├── 25003098e882893e9c7f522a15f6d8fb8da0ccdb.nq.gz
    ├── 26d72bbe60de8ba3c966c7fc7c5451204a55fc87.nq.gz
    ├── 273d6f4855f2d54204f398f6c60ef5bd696f0579.nq.gz
    ├── 2831a6eb98a25bd595398cc80e540b340112d6ba.nq.gz
    ├── 2945a12937aa1ec2b1f24347cb3725fa308e9b10.nq.gz
    ├── 29afbffde6469b53886a085f6988c1517c140933.nq.gz
    ├── 29d4c7a9983e6e35b80d6d65496a16015cfe8227.nq.gz
    ├── 2adce3a5cec0d63bdf79b8cf5698522c9f1618c3.nq.gz
    ├── 2af874f2a519a28008b9c8d79b0fd1f0ec3f4908.nq.gz
    ├── 2b74042915ae2d60e04d97b504389d68c22a0298.nq.gz
    ├── 2bda39bc661de60f7d1e4f5562378fecd3963386.nq.gz
    ├── 2c1080fda6f5c73ca593d121e79c3e85b4bc7e96.nq.gz
    ├── 2c3874ef05530adfa9c9e93350150f24aaf20c9b.nq.gz
    ├── 2ca074b4f37ef70c91bece752ea515e4ebdaeb85.nq.gz
    ├── 2e3140603648a06baaf09df58d9e7fab07265725.nq.gz
    ├── 30df93f6c7e97417c247622462749fc63b88d744.nq.gz
    ├── 31f0534578c3ac05713d9b264ef0d5afcbc7eb3e.nq.gz
    ├── 33867ae0a4d167c15339cc67eb255a34525ed110.nq.gz
    ├── 347d54bfcc32f5ababa9fd85dcc55cabc4883e53.nq.gz
    ├── 34d452a32c0884a18800f3028962c66aef9bc020.nq.gz
    ├── 3520240704ddb49225a58eed9c87f68403c8d882.nq.gz
    ├── 35a666ff8cc6a9868cf32b38d8df9cd920217169.nq.gz
    ├── 3600400f749aed992b6db593a5118785158d26f9.nq.gz
    ├── 362b60e79a60b6d4e0002c2ca3b8629e58498c8d.nq.gz
    ├── 36b5c4f6325c14b6b3d22bb17f191e0ccbc645ea.nq.gz
    ├── 37d4428e5b2c0dd6a6593869ee89f2d3c155a5f5.nq.gz
    ├── 37fcd12fd5e241e76b3e79fef0cf3c216075c722.nq.gz
    ├── 3806d0c64034ec29e31c184c08831d76bc5c854c.nq.gz
    ├── 398cd0b8339a2d48898e5fccb800be355d26d159.nq.gz
    ├── 39daaa7196af72fc96de5377c202a0327cf48510.nq.gz
    ├── 39dbbb056468df4f0b96546ee9612496638fdf5a.nq.gz
    ├── 3a87ef8c6c1eb7e91f3488487c4cc3dede62bbdd.nq.gz
    ├── 3aacd9c3ccee42e0691bb7736b76678d8400918a.nq.gz
    ├── 3ae3d6a8e71c28cb41b908b6884af626233d11bf.nq.gz
    ├── 3aef6d245bc65e3554ad23abf3741a190627dd1f.nq.gz
    ├── 3afce2b5113a573c3fe3e84d2c1e71983e053783.nq.gz
    ├── 3b3cfd9f1b664ca23141ef5a7c217e37e3d62df0.nq.gz
    ├── 3b89832c852d0f8029a5f6ec68470ad01b0dfa37.nq.gz
    ├── 3bdd4b11ac3d35d214530bca14b61891987762a4.nq.gz
    ├── 3c0f7cfedd5bd79cce89d15a8c7db6483fadb1c3.nq.gz
    ├── 3c2b20fc39ff6cfba40f9d203befd337ef5338be.nq.gz
    ├── 3cc3191bea347374bef18d35e86d5aad94a46a4a.nq.gz
    ├── 3cda3999f13483129d52b70b57da75ba3a8b966c.nq.gz
    ├── 3db70a860058dad2e20cdba07b4d7b0dee6088e9.nq.gz
    ├── 3e6797d59e87ab4e2aa7a986b685acc7f58aebd4.nq.gz
    ├── 3f09172e8170705e746266ff40828f6eb5da8c76.nq.gz
    ├── 40a26e4ac97213cb29b7dd9e5e9d28215266244e.nq.gz
    ├── 4207be6e0cabdef2d2f0cef5cfc0db75af95c97a.nq.gz
    ├── 42966fc650132bf41a4f95ad160ead15b82cab9a.nq.gz
    ├── 42f2376e1ab272a5b67890bd0bfab196bd1b75b6.nq.gz
    ├── 431a2d2a9c702daf5dddaf611f43d6aae0ccf855.nq.gz
    ├── 43355e14ab1dda044b260d11e4cc78ca21774cda.nq.gz
    ├── 43c6d8b204deec5cff33c8d30a6321be191fc0e5.nq.gz
    ├── 44af5123ad543cca5bb030a7607a75c25087e803.nq.gz
    ├── 4507fd8bf4a09fd3e9fe96525463b74ab7e9ce2d.nq.gz
    ├── 45704369719a5f909a5530d8f49dcd3ce38ecf50.nq.gz
    ├── 464c4a2faf4ccbc06915533478a66a7e1f49d2e5.nq.gz
    ├── 46e49a7c68147e0d48935d3161418cea0ef38989.nq.gz
    ├── 47116125777fe256f96d3f62fbda4edd275372e8.nq.gz
    ├── 473480db9985916c750e9c00466db5054818afce.nq.gz
    ├── 478c550f678e40bc56851f7c3144cf7f91a88ec6.nq.gz
    ├── 47b4511e431d36b54cb1793a4e4f88d993a3a865.nq.gz
    ├── 47c17da275a518b0a564ee989d7da128706ceb0f.nq.gz
    ├── 47c61034399af5e0740c07716f760ec76cd3a5cf.nq.gz
    ├── 48509e41290a713c9cb67988c00c1309ef2dc496.nq.gz
    ├── 486f6a4931663dc4cd80378e1ca6e3b1fdbd9393.nq.gz
    ├── 48b82f1fd6fcb3d614b8defe13946feadfafd3d9.nq.gz
    ├── 48c6b7b9d2923e1bb3e4b0bed68a90e5c1b8ae8f.nq.gz
    ├── 49650fb6051e723b33c012ea36bac39306b1f451.nq.gz
    ├── 49ab7467a0336e65fc944ba46219ff9f47c63960.nq.gz
    ├── 4aa3be4891dfabacc43cac052aaee5517e3ef7bd.nq.gz
    ├── 4b272e4109b3777a059bfcdbb28e6e9b13ce0676.nq.gz
    ├── 4b93052cafbad9dff0cffd6b06052bf14a91e39c.nq.gz
    ├── 4bcdf897f823a899954ddc6d195e9110394f23b6.nq.gz
    ├── 4d0e9db2b86f7ae08bee88fb1fc9987d72db7302.nq.gz
    ├── 4d4e3aea8d5336c5cea3a6ca79c76a8ef347adab.nq.gz
    ├── 4dccb88b3c8ac56e960375c70ee7a1fca645b647.nq.gz
    ├── 4e0f2b0dfb3ffe85cc4639e4b0e86555de897ee5.nq.gz
    ├── 4e7e14f8607c3a053599e1aef2660faa5236e358.nq.gz
    ├── 4ea127ea16b297a3574609b95c6645caedf01432.nq.gz
    ├── 4ec94d7a08f45e29e6313f06960becf4e78899ea.nq.gz
    ├── 4f4cca86dd961a4aed406f9dab2aecce22f8386c.nq.gz
    ├── 5005553188997f2fee19c5732a9b2e9c3e0d9ab7.nq.gz
    ├── 510c6e1dce8ddfbe96d1ef4a32f5ee1155ac9163.nq.gz
    ├── 5114db47240c9449b19bf63337de8d64ef3bfc74.nq.gz
    ├── 5161a5298193191c6c7dc4cd83f640518fbb24d9.nq.gz
    ├── 5192e4207d6b25038db84e391ef7d4e30af494ce.nq.gz
    ├── 5203f9286e8ecf97e86d1657f4e1bfc8405ff71f.nq.gz
    ├── 5223572dcc19760d47f85e7618cd6a222c807b17.nq.gz
    ├── 524465deb3412c51a96b8a86d5840770e2b35259.nq.gz
    ├── 527c98a0e8bd1ca7e011b146986bb8f23bbc7b78.nq.gz
    ├── 52b48d53f0e899733709096d01978c8ba0a1d7db.nq.gz
    ├── 5387e72bb7c21bf435dd87e225b44e27964bdeec.nq.gz
    ├── 54174a1ad66055a59795132f83e6a46d8af62dd3.nq.gz
    ├── 545d8e05b61c75d23758efecad560f1fe2557d0f.nq.gz
    ├── 54c65560b5af41981ed4ffd4769caa69c898ce96.nq.gz
    ├── 556a7e906b85d5f77625ad279315cf452ed9aa1d.nq.gz
    ├── 55e86eb7025e119ac0736f34af330a656588a177.nq.gz
    ├── 57702bafbb980bab5aeb5a8765c553cef375e728.nq.gz
    ├── 5824fefaf81ee69bd043b4d27b4e17203ae1d05f.nq.gz
    ├── 58e377154d20ca32deddc7e544d56508c76163cb.nq.gz
    ├── 591ab2571d7879e81f80ea9854af4b4c3daee162.nq.gz
    ├── 5a0a8988e0bc78c17a55521fec12481120c04f1f.nq.gz
    ├── 5a3f9b204115be181d5430c8fb31c03964b28df9.nq.gz
    ├── 5c669c4a97a43c5dff43a0fdfcba8e65f8c3f588.nq.gz
    ├── 5e0a21f6d4a2f524e581327097a3a95a1d4e72f4.nq.gz
    ├── 5f251493ca1561789d07e172d22866cd8edaa3f4.nq.gz
    ├── 5fca5bb84dec35bbda16ba50e397d35d193dbf15.nq.gz
    ├── 6052b67670cc73b75344427771081b20b4ef31ff.nq.gz
    ├── 6159b0235ae868c48110c35947c8f211cd3ba908.nq.gz
    ├── 618d5bb219d19836cc4f271227fe051a61b599e3.nq.gz
    ├── 61d1d49c44acb2de679b1ce707bb17bd6ade5383.nq.gz
    ├── 6208c2e71d557e38069bff93414143b5af451dd9.nq.gz
    ├── 624fb7fd3a3b8f8a12b6af40757182d67d5750e0.nq.gz
    ├── 62c21722213a6f278a9ab0c6c2bed2abb22dbb2c.nq.gz
    ├── 62cc12d9a7bc2f60269a8f6750a708c98c207c26.nq.gz
    ├── 62d7da9e32c32bdbb9212c8e6f63284960c72819.nq.gz
    ├── 62d828cb1890d6dafc30688ffb9f731036508518.nq.gz
    ├── 639d7eb57e62f96376a331f00ddb51f7ada4ed76.nq.gz
    ├── 63b00afccc06cdc326c2529449cae8517f35b36b.nq.gz
    ├── 64181e4f4e2edf8d89022f3da94a4fa3d1bb7335.nq.gz
    ├── 64a74d0b5156ad39d36a1d2e1caba9c06cfd9e6a.nq.gz
    ├── 65b676be5c3ab86964ffd275ea58cf70795b66ed.nq.gz
    ├── 65dc8f2a453fe5029f087739503e2eb50582acc1.nq.gz
    ├── 668f60b9b4e2e53c4c281156aef4793edea2007c.nq.gz
    ├── 66dc09723cf7e40b62f99f68a415ff5c39c0f868.nq.gz
    ├── 66dcc0a37209abd5620a8a0a5b8d1afbecd9b04b.nq.gz
    └── 6727430f828449ae6f8870a154a13ef7eeb8a37a.nq.gz

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

[astropy/astroquery](https://github.com/astropy/astroquery)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*

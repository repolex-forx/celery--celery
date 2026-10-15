# Repolex Knowledge Graph of celery/celery

RDF knowledge graph data for [celery/celery](https://github.com/celery/celery), parsed by [repolex](https://repolex.ai).

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
rlex download celery/celery
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f5dbef350688eb7250cdf1e389db93ea9cc605fd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f5dbef350688eb7250cdf1e389db93ea9cc605fd
│           └── chunk-001.nq.gz
└── blob
    ├── 00831f7a77f7fc967459323fd64e5ffa81c63615.nq.gz
    ├── 02d69866a50daa66fbe6a036104237425e980d18.nq.gz
    ├── 052c091861e08692c4b390a26dc16687427c2253.nq.gz
    ├── 058261b54333053207f9d9121959cd2c6c7e1a1e.nq.gz
    ├── 0672a0ead97e8136a8ddc985ba42a89fcc22d269.nq.gz
    ├── 070ebc68a8c068dde0859639581a039cf8fdf3ab.nq.gz
    ├── 076f5f9a7e6cfe4e89c656884383c5bafbe3915f.nq.gz
    ├── 077537f7c4e58f4edb855c9b479a89690dcf5617.nq.gz
    ├── 083ccb026f7ef087acf4e84baaff7e0c99b6197a.nq.gz
    ├── 089b4e0eaf12bd96e69bf35a6a4b58df8dd1c8a3.nq.gz
    ├── 08bedfe89ccd0200dc282244d3af2e9abbf4425b.nq.gz
    ├── 08ee12027cac818d5be88bec9f7863377e97bd85.nq.gz
    ├── 090cdc3e42a8e7224456a38b08076d10a3c8e18f.nq.gz
    ├── 092450ea95e10e00eafb54beb5b05a4be18fa335.nq.gz
    ├── 0972b9f80cd128d8230121e0a108978b92b580c4.nq.gz
    ├── 09d3668724403ae24120d04d232312baa26b6a87.nq.gz
    ├── 0a38823b35eea164eebf546a4d39f01532597d4c.nq.gz
    ├── 0a4bfc0f19a97f36759d88c0c971a0a6f6ee98e5.nq.gz
    ├── 0ac7229a01acece87e1ddd00706b63202d8bf106.nq.gz
    ├── 0b136bde80dc18fa4c16f8213323dd7babf528ee.nq.gz
    ├── 0d0f937216625515de1f6e234bdd69398e6557a9.nq.gz
    ├── 0e0221cb7594c72c5ae9752b3e5a41259b1a6b6a.nq.gz
    ├── 0e1ba1fa2782a485f3719bee982bea317c7edd0e.nq.gz
    ├── 0e2e1a33070f274ba6a42e0331842a2edfd5066a.nq.gz
    ├── 0e8a0eb36f4ca2c939201c0d54b5d82a1ea34778.nq.gz
    ├── 0eb058fa6b23113418d4a3908789eb2623b0ae30.nq.gz
    ├── 0f4cb5051704f88f140f9da79287276ffe59098b.nq.gz
    ├── 1012f4be6aa6b6132390b3d0660e3e58650e1459.nq.gz
    ├── 1068439358c18b379087cd2c45a7ca003c6ad1f7.nq.gz
    ├── 107d96e019c310e7fed756fd90889e815e914ba6.nq.gz
    ├── 11d1f917f525f539dcf38992117623ff3b1cc095.nq.gz
    ├── 12520aeeb9f600af4af736e55b8eaf552677234b.nq.gz
    ├── 129801f708a472bcbe3ce1dabf30f5044952ab89.nq.gz
    ├── 13321b61d07b3f4d26c987a93e5f68950f2889de.nq.gz
    ├── 13cceda2c2d4c3223a10ae487087923e3c3134d4.nq.gz
    ├── 13daf51fa0318d9120c824107374875b1835ce74.nq.gz
    ├── 13e48bc0a27a3ad7158432fd6843135efaedd290.nq.gz
    ├── 13fdddef77457759e4efb109518120f27d91fb7b.nq.gz
    ├── 140566f181955dcb0541ea61c76d3e81e2226819.nq.gz
    ├── 14e7ae864b570eecba7d35bbbb86fa24ccf30f13.nq.gz
    ├── 15d7c508511dd2415509c88ee7b3ae51aca5b87a.nq.gz
    ├── 16281a1b55e8c0687156dc891a1cdeebbb02c71a.nq.gz
    ├── 163234f205142340eca1bc31f208a267a690e966.nq.gz
    ├── 174d31c4082ae4a25b222b248f42a7396a711c64.nq.gz
    ├── 178a4c713559d7229db2c1bd5745344bf51fd609.nq.gz
    ├── 17cca8f6470efa2d41b5fafd4843dd053ef56b1f.nq.gz
    ├── 1863681262efb2617b42726829ab0107940c1190.nq.gz
    ├── 188c8dd50a7bc2e718c1d1b06c8e8546da67803f.nq.gz
    ├── 19acb1367a7da6c0b890be36618b1bf922306758.nq.gz
    ├── 19ca97b0d46eff0f40dcdb3cf1262ef1529ae38e.nq.gz
    ├── 1a505ca54e5bc73e663fa9168d0c8b6bffbca2e1.nq.gz
    ├── 1b5feb51d4c8a61576a740bd12934a87bb38d2ac.nq.gz
    ├── 1b8f5a80ba2f605d2a01f1d442f9e7953f1edd85.nq.gz
    ├── 1bc4f67894e640b96cba1a249322a3e3d200d682.nq.gz
    ├── 1c0631f72bbcb976a702ee764d95c5eb87d57336.nq.gz
    ├── 1c836c6bc598cf63229a6410f323a6528344c6a6.nq.gz
    ├── 1ce9a751ea29d4efcb38b751d1b011692e28f92b.nq.gz
    ├── 1d76ce885644d9a824b70237f8524f352e304165.nq.gz
    ├── 1e2d70afa834e72f4d3e91ca1b4f4e411811371f.nq.gz
    ├── 1e8befe9afa350e7b77d25eaf4540fa9762113c4.nq.gz
    ├── 1edfb12fa486819572fa861e67f5b5a39f793980.nq.gz
    ├── 1f1af6017736021163ca156f6f63548b3072d075.nq.gz
    ├── 1f6507e46676732f166e76f206b50eb3fea18059.nq.gz
    ├── 1f7d09ead22464847d64bcb4398ef4241574a2c6.nq.gz
    ├── 1ff346b6a7d682f7bdfb5be3cd0f0cfdc64bfb68.nq.gz
    ├── 208d254b81c1f98f9b785f65f05296dcf4421b83.nq.gz
    ├── 21061a890da5e88e119dfb2b998c114ac9ccee2d.nq.gz
    ├── 213c15b8a193d06386ef389b314afb4c5b0e07d7.nq.gz
    ├── 215067f7507b7ac6f0464130a0a6872202dc4f09.nq.gz
    ├── 21fc59b1978122f9661ca66530b6f817aba2222b.nq.gz
    ├── 22c7eec6fe12905fdb214727ae0461f07ae54583.nq.gz
    ├── 22f5fc4cb025ecd326d40cabc3b9bfef6fb9f3ba.nq.gz
    ├── 23f43b160f8a747fa1053b918a7a40fa6d7f816b.nq.gz
    ├── 243efee377afcfde99fa90c3549ec012b0f24636.nq.gz
    ├── 24b4ac61b3b68fcc5cac5f5c7655887748eca2d5.nq.gz
    ├── 25163151930a25c27fd6d815a1b0cebe62a0c924.nq.gz
    ├── 25337d1afcb0e925d250b539d20156469c4df603.nq.gz
    ├── 25b60c9183362a3ab3463ea7ebaa7f2b11b6aa31.nq.gz
    ├── 27de377998dfe37b359f13feed94beff8eb32f51.nq.gz
    ├── 280a71446e86c1376e249c4cd37d419aa8789b15.nq.gz
    ├── 293369fbed8e7ee514390d6ede331459f61151b8.nq.gz
    ├── 2998e7bad621710ad8175e104e44baead0b87d3e.nq.gz
    ├── 2a6eb4f9552ee69a1ef3f35d731d9582b8d3db68.nq.gz
    ├── 2ac73ab8dcbf064a0b72f2f023b1bf4ff6aaf9d5.nq.gz
    ├── 2b8629d58bb128bdb97a643305006533e813224a.nq.gz
    ├── 2cd19905223c264ee589bc1d6723a856e4eb7dc5.nq.gz
    ├── 2f06ed20eddbedec53e644f240af7a1b9862ab8b.nq.gz
    ├── 301b4e1d8123e04f2effe661c6dac13c6102cba9.nq.gz
    ├── 3109e100b4da20477d7f72cd6f1c2931d9f5dda0.nq.gz
    ├── 319853dbfdacca715a46049ea685ae1763ad6f67.nq.gz
    ├── 31f6be2bb721baace8e5471050d470aea5cc9994.nq.gz
    ├── 324f88be1997592086409e13be27981731bce3ff.nq.gz
    ├── 3250970d25402dfdbe15b3694aedc2a4c775e557.nq.gz
    ├── 32d76f32052caf71ad422089de39cde9a31c80d7.nq.gz
    ├── 33e2e3d87c9711e57fd8efe1721a09b1eb014e30.nq.gz
    ├── 3489cce30c5bc3d772a68bd7986ffe3e8d524aed.nq.gz
    ├── 3490e52216ac0010d5a5bb652af02220dbfa9fbb.nq.gz
    ├── 349dcf8bebbc60d27028c7913a6c6485792e7b79.nq.gz
    ├── 34b4b5980909fd780bdba1319d90c92c22673e39.nq.gz
    ├── 34fc217dd0de11e5a7ba0cba2a25bc1fe439ef07.nq.gz
    ├── 3515dc84f9b841feb94f0bde119df749e97f2631.nq.gz
    ├── 351b29cdd7de8b7c7bd71bb510e738b010a246e0.nq.gz
    ├── 351faff9e15b90f29b91d7ba386fddfdc5edb4f9.nq.gz
    ├── 35786df2b43f377b5a3b15317fe5af042f0c00a5.nq.gz
    ├── 360c38693a8909c041e6fd59a438ee13f13afe9c.nq.gz
    ├── 36398acef5c9d6f44b46d37f296bae66d71fa777.nq.gz
    ├── 363f463062809c644d7da710c6921e14fb797a7a.nq.gz
    ├── 36c971752c47d4669b607aa7d5787e1b7e117dfa.nq.gz
    ├── 37ea0cb1d03749e1d99906e15c62eaf79978e1a3.nq.gz
    ├── 3a75eac28eedb1cc2d3a37da9beee6401979ac02.nq.gz
    ├── 3a7dbd4c786f9522b62354c6f4df29030a4509ef.nq.gz
    ├── 3a80fb07098de6f2a4644188cb628b384fa9a0d5.nq.gz
    ├── 3c1ef8cf68c8e29f32c2864046768375bb41a9d0.nq.gz
    ├── 3cc5fdbc5b43edc574401ccaeb86aa34014bda61.nq.gz
    ├── 3cfb1da8846ee427eb9fd5b10b9f6b62d266c649.nq.gz
    ├── 3da6b235f7e8bc6d6c0cfdfad9de88776e940899.nq.gz
    ├── 3dc3afe5338a0a0aab6fd9b488197b6d58cc61c1.nq.gz
    ├── 3e17ede25ad272fea6d9564396559c47f8473de4.nq.gz
    ├── 3ea6caf0c0f1b7b004578393420703dc87961ee2.nq.gz
    ├── 3ec1dcbadcdd1001fa0dce67a6cb1a4496921caa.nq.gz
    ├── 3f2b9033f67d6fbff4fffb0e58cc6824175cdebd.nq.gz
    ├── 3f6a87ab4e7976e8a7714626a9720a4341d77eba.nq.gz
    ├── 3f6e48889f05cd8f90a1c93e563f7497aa24899e.nq.gz
    ├── 3f96bc36cdc002c08f842e9952394d34bec67f82.nq.gz
    ├── 3fb1d77b77b0a0e7bfa8fd0152e2b8c09d7f7373.nq.gz
    ├── 4013c22b0da30fa62c60f6520138de27b6ad228d.nq.gz
    ├── 403c3df3e4e08e06e39be9351a3d63221f994d08.nq.gz
    ├── 40b24d047a680c94e945cb3e1c29488c5a721d25.nq.gz
    ├── 41276cc6333fca8ae3bae8aabb096f4ead23f98a.nq.gz
    ├── 41698f3ce0f7b02aad4f2def18c175a52991c766.nq.gz
    ├── 42a3aa9ec7f15f217f1cb1b8e1a13893c710c64e.nq.gz
    ├── 43c1dc5488f0379232027742a5e3df9627104b7e.nq.gz
    ├── 4426d65bf7a7fc0c291ad8a4ad7a51fb9097c19e.nq.gz
    ├── 44a12724b76a269b294d9b5918c61d5cafbe343c.nq.gz
    ├── 44f856b2ceded500e2331d571b8629bd76608026.nq.gz
    ├── 4702b0c9e8c44adc29cf5de0695f51b4d059cb19.nq.gz
    ├── 4714a945c6eed54165b302ff53b82d81957f194c.nq.gz
    ├── 47a31bc9d657ef5ba89d1889963b30ab32f1ebd5.nq.gz
    ├── 480f383eda282926393ca1ceee036629e306d1f4.nq.gz
    ├── 485b79265ee679e87d83ea110185957333f68dc1.nq.gz
    ├── 4a6cc5dc5ee16afe2490345f42e0e7ed86c3e1da.nq.gz
    ├── 4a7b254fc73dcb9612f70ea8ee11996abe5f3291.nq.gz
    ├── 4a946d930539bb6b6b31873b12047862f3375332.nq.gz
    ├── 4b5d28233f268de1e437879f041900fb893bb989.nq.gz
    ├── 4b8e202df8868c992798c51097afce6eba923945.nq.gz
    ├── 4cc1e8c5cef72e0df411d12ff8ce5edf22a9b533.nq.gz
    ├── 4e2eddb6e8e0b6af0c06e42ca6dd8be148f88730.nq.gz
    ├── 4e529b7009d8368a9f3b6708c997b843295ffb07.nq.gz
    ├── 4e5af7a3e039860fc42f28ac425d7955eb649654.nq.gz
    ├── 4ec79145527e4350f6665b12549bed8b1eccda42.nq.gz
    ├── 5051e5a0267a8785a33c4d4cd8b25023eeb88c2b.nq.gz
    ├── 50559fd0a56d37a3ebaf69be373d5c618dc38348.nq.gz
    ├── 5127bec25e60a873a5f6e5051969a5c69fabad04.nq.gz
    ├── 51a32191e78be13e2b7dd29113403c7262f55263.nq.gz
    ├── 51b32ffc0287acddc09853d82b709277945fff03.nq.gz
    ├── 52ab3d6e399481dfe5e90cb04e839070ca40af45.nq.gz
    ├── 52bbacf7dc2b247a0a9b97accfd9d0cd66ab38ca.nq.gz
    ├── 532b677fd84bbdc48269c35b9dce8cf6baadbf0a.nq.gz
    ├── 53667248fbf7473981514dab11014a5bb6844d27.nq.gz
    ├── 53ccaeee59d1fed6c6ffc09eb07546ebb248bd39.nq.gz
    ├── 55005a975c50f9036c00096ea7eb283259cb191c.nq.gz
    ├── 55be584b7784a9516a24b57d040e5fcc0725f343.nq.gz
    ├── 55c4e86c65c4136ace109252da8b4081be9dd162.nq.gz
    ├── 55c5ce97aa777091a2979d8723397e902950a92a.nq.gz
    ├── 5619c974d87d8223d0c166b27b1bc30749003bed.nq.gz
    ├── 572dbb4f07c371bef16f5b89201065d2db7182d7.nq.gz
    ├── 5738e09cbee8c9a90d0d6f1ac7f2a787f0d6de80.nq.gz
    ├── 59da2e9b14dc02d7d266b688d0560bc46bb909fd.nq.gz
    ├── 59f07e162c684348c25c9081a00cb60dd8b987f9.nq.gz
    ├── 5a000880b946effa5d74a91f708d6b9f558263c4.nq.gz
    ├── 5ade3d2946b75f075abf75f27cd37072b3cc3cd3.nq.gz
    ├── 5ae01d7b7c46e712c32e0ea33777078707b1266d.nq.gz
    ├── 5b303eb274b6a98f8951ce7aa008ae7506589672.nq.gz
    ├── 5b332588032966a87520a906bd89a7fca45dbb17.nq.gz
    ├── 5b44fbb671bc5ac1a32f910e068886252218d645.nq.gz
    ├── 5b6654edb049104c9e37aa9e9e1131600e0cc067.nq.gz
    ├── 5c746397cac2596cda666db95994b92efeb4d553.nq.gz
    ├── 5d3ed5fc56f060cfd513da5ff1c801d5466b7698.nq.gz
    ├── 5de9452a55cd8dbb3e2bb7d8eb7e33d5d3cb5b07.nq.gz
    ├── 5e4e85a21fbb6c87bd40134a7f0ed7133b19f314.nq.gz
    ├── 5e82fa02bb675e0e5d3a0a39985d65fa493b0124.nq.gz
    ├── 5ea1b875e7fd3a92dc3beb2f57a33a2f57d1632e.nq.gz
    ├── 5fcad1b9a8a4fc47c9d6bb3d27e8978358e02ddb.nq.gz
    ├── 6039873ff7478374d0580c00452ece7499328dc6.nq.gz
    ├── 60f00ef0ef347811e7b0c0921b7fda097acd9fcc.nq.gz
    ├── 615ee2eb4a4b6b6c97a6328853a2068003a5e556.nq.gz
    ├── 617a604fe024fb126408585017197b5ddbf79e14.nq.gz
    ├── 61b61769740bb53793df04639249eb4984e2427e.nq.gz
    ├── 62acf521d54d6537f1fc0e71ef8f4d146af64f5b.nq.gz
    ├── 62c73ee58ea5bcf6eb5a5942ebd748ec7459a37d.nq.gz
    ├── 6403afd0238fe5fa70f26c9092b212f8d5c54e94.nq.gz
    ├── 665f0a262944cd01631c2daf3ec225404477822f.nq.gz
    ├── 673dbf76c5d7a25ecf16315d6af8d702dffcf468.nq.gz
    ├── 67816322a17584c7b9d6cb9efaf09b9ce8d1393a.nq.gz
    ├── 67a7e16c62dda467bffbd38fe0380f67f92863d7.nq.gz
    ├── 6826d814374743346a7056ed71559eddf97845fd.nq.gz
    ├── 690e2acb4bd53b3d5d78dbf7026f8eced7522c68.nq.gz
    └── 6951b448d564121221707db753ee52a3dd46e539.nq.gz

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

[celery/celery](https://github.com/celery/celery)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*

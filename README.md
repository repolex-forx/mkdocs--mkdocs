# Repolex Knowledge Graph of mkdocs/mkdocs

RDF knowledge graph data for [mkdocs/mkdocs](https://github.com/mkdocs/mkdocs), parsed by [repolex](https://repolex.ai).

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
lexq download mkdocs/mkdocs
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bb7e8b62185b11d9f59bb7f50b13c15134f62f8a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── bb7e8b62185b11d9f59bb7f50b13c15134f62f8a.nq.gz
│   └── repolex
│       └── bb7e8b62185b11d9f59bb7f50b13c15134f62f8a
│           └── chunk-001.nq.gz
└── blob
    ├── 013dd2021de1a5afd414b8f87a273204170a9d5d.nq.gz
    ├── 022d60c5941bfeaaece100f1b3ebd95d28be3398.nq.gz
    ├── 04974c16e2e1bbb38885a8d5663894b15d55d9a9.nq.gz
    ├── 0ad1f982a34c520d9e0096bd2f3a756e712c6152.nq.gz
    ├── 0b3357f0f5bb7dd7133fa935b86befc8ef2c31de.nq.gz
    ├── 0c294f0f7f17deae0ae23146d6a9bb2bd9a33286.nq.gz
    ├── 0dfbe275f281813d55d4d940060713b98814bd05.nq.gz
    ├── 0e680e68573613d7151d9eff4953a1f96c142da7.nq.gz
    ├── 0f5f07d354ca2d215d1f7dd42bbf3768e9bacbe5.nq.gz
    ├── 0fb565c012d03063aba9dcea35cf8c9ba3041469.nq.gz
    ├── 11b7464f16173699e3ca1c4737ce3846b64a891a.nq.gz
    ├── 120cfa5e76059a17f1df56c785bd492ec287090c.nq.gz
    ├── 123e3bdf793801bbf04147d5498ac1e460695965.nq.gz
    ├── 14bb85da498b2f0c9267377be93bd007dd932348.nq.gz
    ├── 15bfba3adfc2511ec2d05b2da24603b24cc98a3c.nq.gz
    ├── 15e52dbb098d95d1eee12ec28bfc8af25d28b34a.nq.gz
    ├── 1650ede56c9b15ee8ce73e158333417606ab487c.nq.gz
    ├── 167fa6dd69e074b43de3aa48005d0b748b8e83e7.nq.gz
    ├── 16d74e520a067883e922d85d0922fc9529fcba0c.nq.gz
    ├── 1829fd5df9ecec9c1d55de265eab7efe180e6022.nq.gz
    ├── 183365e09a6fbb03776fd54169ab88f4082ca1ec.nq.gz
    ├── 18edeb8e1b41e5dbb3496437fcb9442c984979c2.nq.gz
    ├── 1b934a51d2ec50138a640d7684bbebf72bd8f5a2.nq.gz
    ├── 1be94abd872d028aefb3e80e819bb3fe6c0a12fb.nq.gz
    ├── 1ddff18be05926af3a457cb72f1812eb637a10ff.nq.gz
    ├── 1ffcfb58dc0bd2345ee00dfaed41fe5f28dc1e22.nq.gz
    ├── 21815fe6129953c8dbdee01130daf55730bceb50.nq.gz
    ├── 25a7f8738a9104e1ccd5830d03cda3b38b795b41.nq.gz
    ├── 25f99c4a583a29f526ed85d72e146d0fe1a66ed7.nq.gz
    ├── 26075f1ca24335ed4114a1ca32ab4e5220e7adc0.nq.gz
    ├── 279f4a8edd1975558e496df8ae5a6f14c411b1f0.nq.gz
    ├── 28b5c2d5d8e9119187166d25a07b510355f6ecf7.nq.gz
    ├── 2a39fdddccce8cb5708f085214a71a18a9ab3b04.nq.gz
    ├── 2de6d469b3353d0b21b5ed434c6c060d92086a79.nq.gz
    ├── 2e97c1dcb61eca57e778eedb2d88d472c06ec73a.nq.gz
    ├── 2e9b9627cb47e8e9b4790b7f3d21eef9c8c95ade.nq.gz
    ├── 2f83e1c6e0d7ae45a507b11a1fac64ed048eec70.nq.gz
    ├── 30be9905c5a9f62765c682bbe426958e79f575d3.nq.gz
    ├── 31d8abda464af5e9576ad476d346dbae1b9997cb.nq.gz
    ├── 32dfbb2445e9525bb6cdff0d3cba91f8726bb0b2.nq.gz
    ├── 3336e0f71051124a4efd0b003c43cac3e04d0d81.nq.gz
    ├── 3404f37e2e312757841abe20343588a7740768ca.nq.gz
    ├── 34f8ab1aae6c2f3035a9f4a10f3a8d8116ab8dc0.nq.gz
    ├── 35acda2fa1196aad98c2adf4378a7611dd713aa3.nq.gz
    ├── 36883d7ee277f97a99c30eb486fd64ad9bfae5db.nq.gz
    ├── 36fbda7d334c3ecea7fc1c378c84bd9b3e4d9be4.nq.gz
    ├── 38c3068d8fa77c19d5b34059f009466d8d636793.nq.gz
    ├── 39b92e68c6f7a1486ad473c0a13549b828ed037e.nq.gz
    ├── 3aa29e19199c3a21138bc7c125f0ded4c3f3443c.nq.gz
    ├── 3bf9843328a6359b6bd06e50010319c63da0d717.nq.gz
    ├── 3d3cc07ffdb6faded2a221241dec93513592bf57.nq.gz
    ├── 3d459f97844b2dfa4f5d51cb694c089952cc4bf3.nq.gz
    ├── 3fa69c6bff6bd117b428155ef53d759d8470cec4.nq.gz
    ├── 400014a4b06eee3d0c0d54402a47ab2601b2862b.nq.gz
    ├── 4138a1864d5b97225b8f396a80249d830b36135f.nq.gz
    ├── 44546d3c08e4c34a41a1217716921ce0c8dcdd46.nq.gz
    ├── 44eb411ef5cdcc3c52e1c347384e937210490197.nq.gz
    ├── 45f324841fc5044fa11f4ffca359ec76f168e94f.nq.gz
    ├── 46612d174ca465b4fe3e90b0a7aeadd960ecd761.nq.gz
    ├── 46745eecd3977ab67f65acb17a8ae2cf0794d497.nq.gz
    ├── 46cbc36070f333cc1342ac2317d30b4235d52e4a.nq.gz
    ├── 48f5890d964e4e66500e21b6ed2b099f98527ea2.nq.gz
    ├── 490b95d9cc2bf7bd00c4d6ac10861234b7874021.nq.gz
    ├── 499933f78e4f4ddaf2d11150f28d791436b08d97.nq.gz
    ├── 4c408b29d1f28e5c4a4cb72475315e17a8b1575e.nq.gz
    ├── 4cca01e3a3a5e482b48651656471cb07f7a08f05.nq.gz
    ├── 4d13fc60404b91e398a37200c4a77b645cfd9586.nq.gz
    ├── 4d5ce0a9303cebd6b5a4ead9c45a4943a7475599.nq.gz
    ├── 4e921e022fabb85a9b3beb8cf1069a0c3fa52a6e.nq.gz
    ├── 4fd81c15cd57e2fd1a985561826f4705d044e6ba.nq.gz
    ├── 508f53e5a787cb891e105e050b07717b2030fa7f.nq.gz
    ├── 50c3fa071e54b1e79023f2537980c545ca94ce62.nq.gz
    ├── 510ef6f6be000781c922c1358af1a14ec755c4d7.nq.gz
    ├── 52f5cb3c0cbdec67ea20293bd903aefe3603cd20.nq.gz
    ├── 533e634bc7ba9ce879835c63f361e332756c2f2a.nq.gz
    ├── 545e1efb0501c4ce6645c0ed1850180c44006a05.nq.gz
    ├── 555fecdbbde69b9e545fddb465b4647e14650b95.nq.gz
    ├── 55b43ff0fb546c61434cecca7123bfa02d09e53b.nq.gz
    ├── 57fcbe8d4d0d8eaa6ec98a78af3b4bbd87be2fa6.nq.gz
    ├── 596540f5d761c3dcd4ef2150b120dcbd4396145b.nq.gz
    ├── 59b1d2698f63f91ecae063176f9bec5260d18611.nq.gz
    ├── 5a9fe654670dd8fdfed17a76691a245293731bdd.nq.gz
    ├── 5b4bad814c01ca6523b410629665efd07f4b2474.nq.gz
    ├── 5efb1d4f96407d7019631b361b571ea454f6ce09.nq.gz
    ├── 6299d37f39ae890cdad15f7df5f215174b9c30e7.nq.gz
    ├── 676863b56358a457db9b09c52a62ef7b4cbf3214.nq.gz
    ├── 67b41aa6fee23948e998219554f3224692fc7f07.nq.gz
    ├── 684c3d639945c465f727d5c1ff7d1556d024b240.nq.gz
    ├── 68ebf3a8d89bdaf8dbeb4e57ac53f05bfe7951e8.nq.gz
    ├── 69992c1a0f073e695bf32bb89792b1f0d0081170.nq.gz
    ├── 6a7d93202b2746319cec63c8efedbdb0da1bfadc.nq.gz
    ├── 6bcd262533924c35cc9e30853f8928a836ef50cf.nq.gz
    ├── 6c338374a35b8d27d5426366bc6b253c5df9d0ce.nq.gz
    ├── 6cb60000181dbd348963953ac8ac54afb46c63d5.nq.gz
    ├── 6e03abf212cb6eb3b8cb122a8e6c32abb58b2891.nq.gz
    ├── 6fc4702b10d609b8d390fa8ede023145248c7448.nq.gz
    ├── 7059e23142aae3d8bad6067fc734a6cffec779c9.nq.gz
    ├── 70c535bd4a1b39fa9e1b10c5d2453625e8a673df.nq.gz
    ├── 70d44ba259f8bd6a6daa02a295810956b6fc518b.nq.gz
    ├── 7246e14865cecc94607d0b88654dd6466dd34c8d.nq.gz
    ├── 736c764b651004af97c7778de371de7380d349ae.nq.gz
    ├── 73ebff1d6e729695714cbd6f5111dd8226c9f3b2.nq.gz
    ├── 743a51bc173e7be931b7d9b6eaf7a824295d5205.nq.gz
    ├── 74b96bbb6d0e28944f3ad7d11884e598048446ca.nq.gz
    ├── 76114bc03362242c3325ecda6ce6d02bb737880f.nq.gz
    ├── 7652a394e30911a3d34fd7def64fa5b40406a39d.nq.gz
    ├── 770f24fe2235ddb8608a779df158404c350a52a9.nq.gz
    ├── 7b075415812745f8856fa867a51796723857efad.nq.gz
    ├── 7bb507395f28850a9b99d7f50c0deb356111960a.nq.gz
    ├── 7cd8480def010228bafa7e8942105e9e8ad09145.nq.gz
    ├── 7ce9515404207fc92fcbeba94a26fafa052c05c9.nq.gz
    ├── 7db41a5c50549e1cd986e3f548779791816a6768.nq.gz
    ├── 7dcbe47ce81bc11eea8a6d076e1a5bd7085f2947.nq.gz
    ├── 7f32146f00791676204b6efdaa3c26f896a19577.nq.gz
    ├── 8224cb9ae007ba352435dc319f5a62579552a6f0.nq.gz
    ├── 824d518eb4cbbd1fc837dcac2ccad718119d1ac9.nq.gz
    ├── 828dd2e67a872a1447d2947d4a0daff9de34ceb9.nq.gz
    ├── 8327b10782d35206deb902ffd0f2be9848991e78.nq.gz
    ├── 835d17ba3784fc5ae3de6e0a44004380312f8ca4.nq.gz
    ├── 838b4e2cfec1735771f6a237c7b28d6be5f62bfc.nq.gz
    ├── 855c845e538b65548118279537a04eab2ec6ef0d.nq.gz
    ├── 8628dbce9442638095bf6ae885651b7dec0c91ea.nq.gz
    ├── 86f94bd63dd4ae9446145b7b10e25dc7024bffd6.nq.gz
    ├── 87133caeb32eea234774319444c08bb8da6c9c32.nq.gz
    ├── 878c3ed5c196539c4e2da35b7787ab08e98b9cca.nq.gz
    ├── 8834b907f16a8689ef654ab9ac9f2f4264440b82.nq.gz
    ├── 889d80668eb807c118fed36f2d943adfc814ff78.nq.gz
    ├── 88ad05b9ff413055b4d4e89dd3eec1c193fa20c6.nq.gz
    ├── 896476a1812214c0d3527ff1764bd6729a80bc04.nq.gz
    ├── 8b53af114324857944b0bc359072178e2b8723e0.nq.gz
    ├── 8b54bdfa2693d20c1009f16946fb6ae9cd76e1ac.nq.gz
    ├── 8b861c879857beda3c03222a15635c1ba5056428.nq.gz
    ├── 8bdc19b21d4a4c56464500b1e88789af81f9af6b.nq.gz
    ├── 8c0ef430abaf07c6f7bd9d910b083f6bf943fd80.nq.gz
    ├── 8f8510e14c02e3419930341ab8f714f820fd0f2f.nq.gz
    ├── 91a9705ff0dea3aacfba1daaa584b99ca52d5a15.nq.gz
    ├── 92d0eb653ee75fc95273175cad1c098e00b042f8.nq.gz
    ├── 94171c45aa769a0cd28e296f1441972d31adcc01.nq.gz
    ├── 9485580611030bba371ec0de6eddbb888b682a80.nq.gz
    ├── 957ccad1727ac2d8c27505229fb0b85908e130a7.nq.gz
    ├── 95c35e6806c7b9da376a35d699f1e9c517c81da2.nq.gz
    ├── 96072a226cf05b3f5a02df67b01cb11c08300183.nq.gz
    ├── 96ca4f8154cd67ce0beaa2f5d2e2f098809a4ffd.nq.gz
    ├── 97008815811db86db6cd2779783f65b42570b0c2.nq.gz
    ├── 9780e912c738c593abcca1757d52293fdc4a15dc.nq.gz
    ├── 987c13822c7bd4934428b20096e9f12e768b8c16.nq.gz
    ├── 9a9848a4f24bc2db9b924c27cf7e5e3f501d0b72.nq.gz
    ├── 9e32b0c397bfd16d843f20b05b3981b46e05e9bd.nq.gz
    ├── 9eae03eb072ec0e5b342dbd0d05165e9af4fa7be.nq.gz
    ├── 9f76ebdd3d08d9c40baf620b41cd5151e5b60d8d.nq.gz
    ├── a59e4622c47cda10f35a72a4666538e5cd2349a6.nq.gz
    ├── a5e469d7c8d0d5e28fea196c244bc687fa3c9cd2.nq.gz
    ├── a992cac6ca2af2324660b005ac887cfc92ce3b3d.nq.gz
    ├── aa79a82c422d12ea90e7b614aae7c3a3769def14.nq.gz
    ├── aa9e8980f7a3225cf8cf116025d7f792676d3769.nq.gz
    ├── ab0631a1803c69462236d93ebb172e4451c0f06c.nq.gz
    ├── ab4eb192461e94604d0d441256939c3541043003.nq.gz
    ├── abdf7784a3f962f1bbb432141f285cdd8b332f81.nq.gz
    ├── aca0a167f39f894d2d120b07b6e99265882c049c.nq.gz
    ├── ad773009b9eb22c58b6abe95ff33f8b007408b72.nq.gz
    ├── ae1307ff5f4c48678621c240f8972d5a6e20b22c.nq.gz
    ├── aea3ba83fd21a72afe530d73d39b321a9b53a849.nq.gz
    ├── aff643fd59b010a3e771807725e73322a57a463c.nq.gz
    ├── b050f7c8812bd29ba55755781b95fcee5cafbc09.nq.gz
    ├── b05faf8ead077819f90df9cfb44be2c3fee99888.nq.gz
    ├── b09174020288469fe58fb5f34f71e8cbc946dc0e.nq.gz
    ├── b175aa8ece8b1881ed7a23ec6ee6db6ad6b7cd94.nq.gz
    ├── b19009a32947496021e3fb16aca8bd7c715e484e.nq.gz
    ├── b45f1079203e60443de699c20f742a5e97830239.nq.gz
    ├── b53d37e2f06caf02fb84a0b9f898c85b4d490ba6.nq.gz
    ├── b5456bb489f3a365f18d3c0e15945384a6aae64a.nq.gz
    ├── b6cabbacb67f4ac88248ef235c5d7a5361f7003b.nq.gz
    ├── b8cb0266fc49db33ca616c1a77ed4217b13f6fc0.nq.gz
    ├── ba0d105bc78cc5169b203624552054b17d7c40fa.nq.gz
    ├── bb195043cfc07fa52741c6144d7378b5ba8be4c5.nq.gz
    ├── bdd4fbded6c289a1ce5fc94a72332a8013063c58.nq.gz
    ├── be122def84c322aeef59c1e7af8734fac06a214d.nq.gz
    ├── be8f86c752b5c45c47ee924d28447b3e6052d6a1.nq.gz
    ├── bf93e0d2e92e9c532fbb080113f644058ead84e2.nq.gz
    ├── c3421adb55f9ba54f3cf151a6f703e176ce5d342.nq.gz
    ├── c4e3d804b57b625b16a36d767bfca6bbf63d414e.nq.gz
    ├── c52219ffeef26fb601da2071a682bd99304c10ea.nq.gz
    ├── c6a8daaab6ecebd93553b34c6f92afc030bed828.nq.gz
    ├── c6dff51f063cc732fdb5fe786a8966de85f4ebec.nq.gz
    ├── c7909a0e776861235a742412bb3a82d52da8c95e.nq.gz
    ├── c8d40969e767c659956de1600f66005c02a49ea9.nq.gz
    ├── c97182f51acbfa060a8a68cd7a073aa6d579bc17.nq.gz
    ├── c99b6575ec7fc8722d14f33b10ac94462c5de79c.nq.gz
    ├── cabc5220754067f9a437f135730c645f3fe6e7a3.nq.gz
    ├── cad49717493338af85f3765038504b72dd74dc2a.nq.gz
    ├── cebf2abb1727fa466d42534c185ec8ce9fd80816.nq.gz
    ├── d103ed6f75750ec48c064cf90aa0d4eb46645c14.nq.gz
    ├── d21b42ab587bb4d520979c1a7316606433708727.nq.gz
    ├── d21d1771e3992fdabd54ab4ed7f31b2595548ea1.nq.gz
    ├── d2dd3ca04eaeaf6c8bcac1aa04276d4ceacd2504.nq.gz
    ├── d654cc7f6f8e608298be4073cbabea4fa3b68cf1.nq.gz
    └── d7525f1699a95dedaa404173155daa36162965e7.nq.gz

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

[mkdocs/mkdocs](https://github.com/mkdocs/mkdocs)

---
*Parsed on 2026-09-15 by [repolex](https://repolex.ai)*

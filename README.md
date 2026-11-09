# Repolex Knowledge Graph of block/berd

RDF knowledge graph data for [block/berd](https://github.com/block/berd), parsed by [repolex](https://repolex.ai).

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
rlex download block/berd
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 81ca89585f68f4d85e7dccf3a4842e401acf18e4
│   │   │   └── chunk-001.nq.gz
│   │   └── a6b03407735bc2156a70c901d44a87f31e91c8e5
│   │       ├── chunk-001.nq.gz
│   │       ├── chunk-002.nq.gz
│   │       └── chunk-003.nq.gz
│   ├── lsp
│   │   └── 81ca89585f68f4d85e7dccf3a4842e401acf18e4.nq.gz
│   └── repolex
│       └── a6b03407735bc2156a70c901d44a87f31e91c8e5
│           └── chunk-001.nq.gz
└── blob
    ├── 0022c64b6a03bc03603c3913bf98bdfdee3e4ea8.nq.gz
    ├── 00e33821d58a07798c4b7a36be7833109445aaa3.nq.gz
    ├── 0101bb6791c4ce96eacaff1e69ee92b45a4efcc9.nq.gz
    ├── 011d62daf34b54399491a169d2728ba4df830ee4.nq.gz
    ├── 011ff2a91fbd677ad92bb1b47f5fec7beca7b88a.nq.gz
    ├── 0153ff830c94f8d07f85038d8c96fae389753fff.nq.gz
    ├── 015fb52f645949feaeac29e97fc72a3bd65f0493.nq.gz
    ├── 016d7e4778ae69a8be048541c2da0c1b4d685cae.nq.gz
    ├── 01c6a9d48ff90571f0055419ea711a66bef90e8b.nq.gz
    ├── 01d045dd7d07982e0920fb5d99c1cfe77dd61354.nq.gz
    ├── 01eb094736612800af3ba3214aa74c52fd05799f.nq.gz
    ├── 01f7851c5cb1618fa224be64a513e87062e25643.nq.gz
    ├── 02095cbeb6ab8865e69d4b99abc01b5358822a1c.nq.gz
    ├── 0282acbac6635f1492855bf8483481d2e96b2dae.nq.gz
    ├── 028b1bd683f82f73ec6f2ae004aa0ed156b1d1fc.nq.gz
    ├── 02d509ae1731765fd5126119a50c933da5c37268.nq.gz
    ├── 035360702e4c16f750fe5735461c23b984f58f30.nq.gz
    ├── 035aa6ec52edf5413e0ef60bed6b07421cb8b29b.nq.gz
    ├── 0360aa9c41aada96db9f31dd0100c98cccb4e19f.nq.gz
    ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
    ├── 03a008c31116e183244bbe8033cfb8c28fcb52a7.nq.gz
    ├── 03e64d5d8d2b6afbd85448ac9506699236730a70.nq.gz
    ├── 041d9e1763be572033c1c89afc3f6a7027b1ee71.nq.gz
    ├── 043fcc2ccaff31e7df02d612f44a6c79176fabb9.nq.gz
    ├── 04407e471e2c12d49bce306ca554493609b48600.nq.gz
    ├── 047c92f6e2212473dc436020afed689527076d44.nq.gz
    ├── 047ea7caeced1cb52691da9fb5f8e82e0341ce1d.nq.gz
    ├── 04848ddf821c3c670a319d0b4dde78c9ff14cc3f.nq.gz
    ├── 0489c6b774bf3c398c10e0b939d9ad3a0fc031ec.nq.gz
    ├── 048c057a840040ef7e9e3bbe6c61aebe02dee4be.nq.gz
    ├── 048c1d154415fa2f581f31183ba92518b0d78994.nq.gz
    ├── 0592db271ecbc5d7981e14365dc69cde66d2d24e.nq.gz
    ├── 05d86aed6e3593178bbf66c632ff0f4c5c22eb47.nq.gz
    ├── 05e633e0a6f3a523f99af9e2b7542ed089c75b79.nq.gz
    ├── 0600a9ca820e47559b43f9277fe27b63534e08db.nq.gz
    ├── 060e0f85403e18f0f869f8d89cdf46b3196ec32e.nq.gz
    ├── 0654a70e54cc0986451f2371b718fc8b2072710f.nq.gz
    ├── 0711651830b9bd48c57bde50a0c53b07469b9964.nq.gz
    ├── 071a19e836d18148189da75f56b8531d830ba18a.nq.gz
    ├── 07364c1b118c28bb5657d7256f3aaea886542e56.nq.gz
    ├── 074b3ece8cbeb1af12ef7a40af2aa52cc53be93c.nq.gz
    ├── 077170922349f5ce52b7882cb8b74568bf019e6a.nq.gz
    ├── 078d63e1f922d8be1d9e9f6d8185d21c2f144d22.nq.gz
    ├── 07a36d32df2ceb05b5f155aad1d5a840b3686236.nq.gz
    ├── 07a903c0e1f14cc1c32cc6eaacaca6c7e6f2fcec.nq.gz
    ├── 07fa89bf028ee212f94549e2657957b12643a00c.nq.gz
    ├── 07fe12109dc6964b6029af89c7bd185964ebca34.nq.gz
    ├── 08151dbc077e8d1436d8c7796f6032cfa35a509f.nq.gz
    ├── 084f7c55ca581d5f6530671178b1a8e4898d513e.nq.gz
    ├── 08616c343a079f746934215db3c596332d1ca948.nq.gz
    ├── 09081059885ecdb59ff0d57ff2586ac6dde5dd8b.nq.gz
    ├── 093415171df6aef1e67e76a0ce06be79b745a36b.nq.gz
    ├── 0939ff606d0bd353fa7db8437aba5731bfaff037.nq.gz
    ├── 09712afd531d99e260720fc96eb9c132ad0eaff7.nq.gz
    ├── 09c3856037ebc15d25fda88b97db9956c4fa9394.nq.gz
    ├── 0a0ba986abc33fa4d019017c3dac0e5b67bb14a3.nq.gz
    ├── 0a12dfb1abe182710232962b6654462700acd433.nq.gz
    ├── 0a2d944dac4685c9184b4d2320973569755770db.nq.gz
    ├── 0a43ab09b4cdfbaed9f93f26c1ac0e14e9dbc85d.nq.gz
    ├── 0ad7a4697d21d8b2cb5d4d2d4189bc2d9712089d.nq.gz
    ├── 0b22d41ef456e2d93b1d625c2664c960719a5db0.nq.gz
    ├── 0bb3418c61a643f649dcb2f799ca249388060723.nq.gz
    ├── 0c2f0f0e6c7139c23ca64fe404e86d21a936c066.nq.gz
    ├── 0c8bc816c85e94d1d30153762210e78ad91183c9.nq.gz
    ├── 0ca32f32ddbf8574365c3b8569bbdf9fe9e0b078.nq.gz
    ├── 0cdb6277302ff9076167815c294e5a69a7b73b73.nq.gz
    ├── 0cf8c759f927f40295c129b702a22f2b75b7e708.nq.gz
    ├── 0d08302a4a390c3d472f657e0699d60c18691915.nq.gz
    ├── 0d0be536686fafe4c88bc4e1613cc92ac0d5e0a0.nq.gz
    ├── 0d47d20938d3fe85f2c5531a2d0e5ee7afb63d2f.nq.gz
    ├── 0d51de82726fcac10bb300f3125293458974e3a5.nq.gz
    ├── 0d5f571b60d8a0a5d1aebd8b586af750a7213004.nq.gz
    ├── 0d6b5e066a8c87cfea59db52fe3546175895efdf.nq.gz
    ├── 0d79ad44d55b1a793591588b74f6e84064416467.nq.gz
    ├── 0d8974f79bfec5cb9705a32889f7799ca91e4b93.nq.gz
    ├── 0de8fa3b4ca9df53306b62f3f405e8b644b66403.nq.gz
    ├── 0deeeca640cc2c2aec2a3089e075896a38fb2490.nq.gz
    ├── 0e43ab1e873edc4b0914cf555a5afe9e7b95473e.nq.gz
    ├── 0e55189d2148426c412307bf0f5fec8bb5495b44.nq.gz
    ├── 0e780858d0a8e3183b8c9e23cb1a58c10de04ca3.nq.gz
    ├── 0e82555aa624a493a0a1b455af1c3ead0fe2e71b.nq.gz
    ├── 0e96fbac7916cd73498af8c8b87ca0e7a87ada6c.nq.gz
    ├── 0edf794b40418add7c8d363a3a1e4450f717ec53.nq.gz
    ├── 0f2bf8288eec0aa6813a38be6e50340c8fbe0a76.nq.gz
    ├── 0f597bf749114d031207180ff72c6a4c6032d570.nq.gz
    ├── 0f5e820a32541c0cd661a364a67fe0f5fafffc7f.nq.gz
    ├── 0f9e4838e26888618add2503bd563225cfa617fc.nq.gz
    ├── 0f9fe2d88d6b412aa70357298c719bb9beaa9c60.nq.gz
    ├── 0fa32ace7421230ebbeb4795de5fc651aac0461b.nq.gz
    ├── 0fe8f8b5a72f470dd832bae7d7ebf3fea6084eea.nq.gz
    ├── 0fea9a70e3f1a32ffcdb524cd41536f51307b4e4.nq.gz
    ├── 0ff5b4bc4c94a88c312c222b21c7d25651bd4251.nq.gz
    ├── 100058f1e5e74aee92d855a7753f87e969d1f0fd.nq.gz
    ├── 10c4c08d586a8f887fbcdbc16fad69d5f5d8f88d.nq.gz
    ├── 10f603cb9e29ef6ff133220692a51b638a1d9782.nq.gz
    ├── 1171235b90ffda57f28771659b7cab1c015cc529.nq.gz
    ├── 1189a8bff4871c9afe83306500c78bfc40fa0d45.nq.gz
    ├── 11b287faac5690e0fa0604ef7d7d4918daa26c0d.nq.gz
    ├── 12a1fc176ac96df7f16e1a1ab698df48c67d50da.nq.gz
    ├── 12cb8febc7cc34e69ab689cecffffdc31c44e3fa.nq.gz
    ├── 12edb6db471e79338601b46b202fc7cde4878469.nq.gz
    ├── 12f7aec8fbe23a35fd1b975bf690e35e53a18628.nq.gz
    ├── 130ffa7fac75fa199de799666aee8f513103ed5d.nq.gz
    ├── 131d8d18cdf289ba195bb2600c14cc94d4ccba5b.nq.gz
    ├── 13474c74e1c9d1687fb1278b647a6b9fe496f45a.nq.gz
    ├── 134b25c78b18db57da5f01ec49fa8492bc807299.nq.gz
    ├── 13bd1f55b23747e04b28c0e80c333d317ef705a6.nq.gz
    ├── 13bf49c57d52a9e2f1283a357b78f341eeecf6b9.nq.gz
    ├── 13c1f5ee2a309794d2ca2d2fa37553775c9aec14.nq.gz
    ├── 13c955f67509e6beaf553220535cf20362aabe6c.nq.gz
    ├── 13cdbce47324db1c785ba801a5a0c9ef8db5b4db.nq.gz
    ├── 13e37cce5b9aca871f6fa7acb529f465d73be099.nq.gz
    ├── 13ec89877ddbfb18fb2b09cf751c98f1a498d725.nq.gz
    ├── 13fa4c72381a3d99068de691e532d8dc951189d5.nq.gz
    ├── 1466d337fc371e18244f8063c6fb3be3d695af8e.nq.gz
    ├── 14bd5365d36509059f8d60af4f1df6199e6886cb.nq.gz
    ├── 14f02e4660fa9a2db35acda87c955da51664a493.nq.gz
    ├── 1520ed399a5dda1c119f64e3b8db58ff096a601f.nq.gz
    ├── 159d765d6d097150c965f514a88f770f83fcf2ea.nq.gz
    ├── 15b3f6778a46ab619099d9a964e842632acf9f0b.nq.gz
    ├── 15c594aadd2c97bddad96615882bde05a23f630d.nq.gz
    ├── 16244a3779b59c5ea883377c37cb2d1b82ff98f9.nq.gz
    ├── 1628046fdfa394eba4df2680c7e58bd2db6b87d9.nq.gz
    ├── 1636c3ecdb269f7f0e7e4055929497d312376dcc.nq.gz
    ├── 164a615109065ec65db358e61356bdbc6b9ad319.nq.gz
    ├── 16628d3b99f9644f69a15c65473121e139f095c2.nq.gz
    ├── 1668b0c6c8c14b0f4def8565852ef2c4a9cc7c53.nq.gz
    ├── 16ec00dfaaa7a1385b4a8ce3aa261600c3f4885a.nq.gz
    ├── 16fcc6b40a7adc46d38dcee84be3da1de953b1de.nq.gz
    ├── 1759cdf0d154f09db47a334a7227328dd875b4d7.nq.gz
    ├── 17c1f4c2eaef36f7b223b8e7532b9e7000aa29c2.nq.gz
    ├── 17d44fcea3a09191ac803e2a4c57491ad1009e07.nq.gz
    ├── 17d9dc44d42a126e7476939f5098ab9f2fd436e1.nq.gz
    ├── 17da584f6562472155b16595754e347d7ae46a4e.nq.gz
    ├── 17f5862de504f0696271ec7df6c1b3b694a294ed.nq.gz
    ├── 17ffa68b856728aa50f4973b15b60e2c4911065d.nq.gz
    ├── 182469268ecf250581bbf94e81892b9118f6f994.nq.gz
    ├── 185dea88d806f385b5a5961eab87dc3caa780a8e.nq.gz
    ├── 1886af955eb177a15923236adb1773531a65e416.nq.gz
    ├── 18e06982bdf6759f85e102d6d54b65b2e43b96ef.nq.gz
    ├── 1916a1386e4699f4540ed76c29805e81a3e827d2.nq.gz
    ├── 191c320f551388ba75fa91b374c4f044e30f64f7.nq.gz
    ├── 195c600fd80abd6090c7354d11da97c6ddda7d59.nq.gz
    ├── 198623543cc2454b9e4d8e4bb3dce349789029aa.nq.gz
    ├── 199581da5d6db62b5c22081b950f4c0f37f94a01.nq.gz
    ├── 19a14c8f1516c75856ca173b02cb435259afe9f6.nq.gz
    ├── 19cae2a778ca0ffeca16fdc8c021118321fcb8f4.nq.gz
    ├── 19f942cf03043e33daad65c5c568ccec5ee991df.nq.gz
    ├── 1a38b1e312d5db22c5511478e0904d83fa94dc2c.nq.gz
    ├── 1a3b9afd4c1375a4e290cca0b6269e6c557b16e7.nq.gz
    ├── 1a7186b1c9c2dd676da25cffba571dfe6710f892.nq.gz
    ├── 1a8e6dce99e54b073d533ce49b5b0834fb86a772.nq.gz
    ├── 1a9f053eb580eb0ce28ef3c6b20e7ad3d46e2096.nq.gz
    ├── 1ad46e013a2f07a18d1c5da77e0f728d86556b2e.nq.gz
    ├── 1b3eb04e1de58fecbac74bfa639c867db637013b.nq.gz
    ├── 1ba004e63bb8bb7fafb3f9d4fe978f69883835ae.nq.gz
    ├── 1ba6e14e70c1d85966ed9d6698ed29469cf53d44.nq.gz
    ├── 1baf59d5447c58a1e35d5f206e5e05aa393f89ec.nq.gz
    ├── 1bb45851c949614ee910fef14331909d598d0164.nq.gz
    ├── 1bb90d9dd1729a8c6f673aafbf4001952ac977bb.nq.gz
    ├── 1bde5969d19a6c03dea6eb533c5d48f36e725335.nq.gz
    ├── 1c01fafa812ecca3384139cb5eea74def9d14d5a.nq.gz
    ├── 1c19042aedba7fde0986d34e0a741550b6cb7a0f.nq.gz
    ├── 1ca0275a73e82abb4d22808884617519e61a3dea.nq.gz
    ├── 1cad24f51e295a1797ec66dcf7e9172a1836bd2b.nq.gz
    ├── 1ce15dd0f962e0ab3d4b295440cb0d955972a727.nq.gz
    ├── 1cf96bde123df94473cfb6eac6c13126d75db405.nq.gz
    ├── 1d1569c0f3eb1807d863ce223d0267162c62ee63.nq.gz
    ├── 1d23da0d270037fabd22493836d919cbfe35c5ab.nq.gz
    ├── 1d3e1ca600052968cd1ffcc99b7e5f9162f97328.nq.gz
    ├── 1d7009126715a1cdfb4fd4f7001c47b9894fa8d4.nq.gz
    ├── 1d74dd4617ff7b1cf0195ba09536ee6f6136c05f.nq.gz
    ├── 1d8bc0fa86718895273a3e4f47668149aeb00753.nq.gz
    ├── 1d95b1a5d1c827c8eb756550624d89920f0159b7.nq.gz
    ├── 1e0b25ade6455436458b26ee8f4e9ebf3eef3602.nq.gz
    ├── 1e4ecf7ae9c5d6b81235bef6ee133fde2dae12d1.nq.gz
    ├── 1e7e5e92d67dfca223aed073d98ed97ec31de320.nq.gz
    ├── 1e999153e8b6a5a4b11bcab28d9427d95591e39e.nq.gz
    ├── 1ed465cafb0512bb2418eb54f931a05868a4beac.nq.gz
    ├── 1f1c8f73e0dc14f9debd2bbbafdc7dbdcc7f3a1d.nq.gz
    ├── 1f2287d23ad5548d632a37b8ee0f63a86d23122a.nq.gz
    ├── 1f3e4fc4e7e2ea3e49891e35bf8ea7edcfa6bd76.nq.gz
    ├── 1f658ed17f70c756426ccbcc046e6cdb881c96a8.nq.gz
    ├── 1fea113f5dff449906c4fc2b67815121184d1e63.nq.gz
    ├── 1ffe3b220bc762ccc1f00d98bb69a4d9dd20da58.nq.gz
    ├── 2008e8b4959508ce8478c66b98ffa02c3bacde26.nq.gz
    ├── 2020d3301d2ee1c3de3e01b17d3efe622425adb7.nq.gz
    ├── 2047b3a30daea9ff85eab182d87d2f1e9dc11527.nq.gz
    ├── 20542b393168c28b298848b39b198099fb81f090.nq.gz
    ├── 2064ae88e04ac2e6f296f30e94e8476b5b5e0e5f.nq.gz
    ├── 20f23b9d6e9a9bb0f498c7bdf5191d80f148bdc3.nq.gz
    ├── 215228a202bbf6d9c155476ed1597becc7c87005.nq.gz
    ├── 21696b8093259f9ce6c16e60c75aa0a458547708.nq.gz
    └── 216b2491758132b8502026ca3b81128324068f1f.nq.gz

9 directories, 200 files
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

[block/berd](https://github.com/block/berd)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*

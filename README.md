# Repolex Knowledge Graph of willmcgugan/rich

RDF knowledge graph data for [willmcgugan/rich](https://github.com/willmcgugan/rich), parsed by [repolex](https://repolex.ai).

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
lexq download willmcgugan/rich
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
└── blob
    ├── 01033c248f8bd62ac42c74ad6046cf64dbfa9087.nq.gz
    ├── 01c6cafbe53f1fcb12f7b382b2b35e2fd2c69933.nq.gz
    ├── 02fdd0b0fb86634f4d297bc0bf01727cdbc3745d.nq.gz
    ├── 046323eca755593e5e187ae235e63888a1023f82.nq.gz
    ├── 04a30a53e20ca30fffc0b060df138e6d842b148d.nq.gz
    ├── 05c863a93dd968675df9b4df6b1e047ae315660d.nq.gz
    ├── 06de437202fa2615567bff20cddc369a073c3aa5.nq.gz
    ├── 076cb6669612f46d2a9d6ce2c64ee3b65a52cf23.nq.gz
    ├── 0790b1dadb847039d34a47344756ed3514f9e01b.nq.gz
    ├── 07c16425c0d4a859ae07db5b8c6c220d1dfe9c6d.nq.gz
    ├── 082d881741a10b0ce11d96970cda7042f4cec15e.nq.gz
    ├── 08beccc229cce8e01a8f0eb35cb131a6d3f095a5.nq.gz
    ├── 08c6eba328a805fadf7e74db17dff4023c5ca7c4.nq.gz
    ├── 0a815291e29df108b2411833de13b8a7a2711b28.nq.gz
    ├── 0b98b4d678e5a7bf9f0f42bc5006e1fea7dc2cf7.nq.gz
    ├── 0eb5487d1e6ffc2b27357801e4fc2f4fe43ff61c.nq.gz
    ├── 0ffc313acff8d8b5f2171f07f5b942448e290f73.nq.gz
    ├── 1144ebb49f70873a2cc2338b4434d392a3c8b855.nq.gz
    ├── 12198de48a554658879be22a376ea54fba67df4a.nq.gz
    ├── 13be0704fcee3e1510570f636ba45ebe09a7565b.nq.gz
    ├── 14bcd02481f899753747e03855abf1e33ec1fa09.nq.gz
    ├── 14fb919ff5120db8314ec12c3354b269913f9512.nq.gz
    ├── 15a3a939c9a07d540005647b104ab330d52a261a.nq.gz
    ├── 15fad3dac387a0425705c8e36d11437ca5c6a3b5.nq.gz
    ├── 164b18a1b1f743377b912ccee3f70d3aa12e3d29.nq.gz
    ├── 169b1cf53f91ba41739de405c41a16abd6a83bf9.nq.gz
    ├── 170f94b34d7a39230b6f5bed23de8e2e2083f33f.nq.gz
    ├── 17b5632f12370ee1ee4ef6d6eeb6836b03f2bb7e.nq.gz
    ├── 18467c6b16e063c016fc1c6cc30a429b79330394.nq.gz
    ├── 18b7c2c27659e9c7799e1fd31e41d92108dd7747.nq.gz
    ├── 194564e761ddae165b39ef6598877e2e3820af0a.nq.gz
    ├── 1a0ebccec411e4f2cb867661874b5097f57407b8.nq.gz
    ├── 1b3df42cd20dac49f0758167e67f9f80ff627b9e.nq.gz
    ├── 1d6300e76805c201fad879b18545af962a995b83.nq.gz
    ├── 1e40a254f781f8df6defc45fc4fec27aa213d65d.nq.gz
    ├── 1f02e9f47d5b18e2a71b4f2029ead7acb78f92a6.nq.gz
    ├── 1f2877bb2bd520253502b1c05bb811bb0d7ef64c.nq.gz
    ├── 2033d7b98115adb0d0f1db2e90ae8977440e2cfe.nq.gz
    ├── 20a321da1f08e0862da3af93dc768d6938f18c3a.nq.gz
    ├── 2121a786381f8bda36db578f26b6164dc3fff6b8.nq.gz
    ├── 2218d03b76919ed478f64d450967cb3a76bd2c9c.nq.gz
    ├── 228cb189dfcc1426a848fa3a57dc20358411b5ec.nq.gz
    ├── 233804adff338dcd7e01f1de13894b1bfa108d6d.nq.gz
    ├── 23c6124d623a38ff3b8c5fc2021fec4c1da54753.nq.gz
    ├── 24e44a220365afe83d85c92509af8da02a4260cf.nq.gz
    ├── 260cfbeacdc30355758a33efb385200aadf65b0c.nq.gz
    ├── 26ec6fffecb21e2c81b7cea3064480aa9d694b0d.nq.gz
    ├── 2966948fb0eaa60c41942c9a9147f9ee0f2f85cc.nq.gz
    ├── 2977495f299c8977d893018504ea498ef92a71c3.nq.gz
    ├── 2b0d250f7a0a5950699266c327b795a43da03717.nq.gz
    ├── 2b512ef82b7462061acf812cec32083b7cb2ecef.nq.gz
    ├── 2b557e5d327f0c7f557287f6de52459a85fe6e87.nq.gz
    ├── 2caad0bccc2a6993780aed3b6eeccbc3fede2b31.nq.gz
    ├── 2d0cc4f0f797a9457c92a3ebdd25efacca2b1c7a.nq.gz
    ├── 2d926775af03b85c2bef899e9a97d6ba173a5f75.nq.gz
    ├── 2db134d7515ad2cf5aab3aeab3f09e5c57a4428f.nq.gz
    ├── 2e6fef7f5a1bf5552dc63f7d5078b19a847419da.nq.gz
    ├── 2fd1f3d8e418f6dac1734ca0399938d5be304171.nq.gz
    ├── 310b994d3ad71fe30083d4ed1580d37c0c221235.nq.gz
    ├── 31840b78fffa39d8e028639f1a2cb546fd726422.nq.gz
    ├── 328bbd964db106c2f839d90de8828b8d4304a2fe.nq.gz
    ├── 334c31d9c8175588bd89d9b2f8094f38d058aeb9.nq.gz
    ├── 33850842ced327df5cc3f48ef152e199c70d39a2.nq.gz
    ├── 33e431399ffb363f801ad1255b8b2cdcdaafab63.nq.gz
    ├── 3421061cc117347265c179ec5cf57d4231d0e6d3.nq.gz
    ├── 34c2a11ead0164b58b23dfd6ee13b70a139ac274.nq.gz
    ├── 352dfdf3dbf8af25a02f4170e13654fa891f3281.nq.gz
    ├── 3571c872c6b13415ca0402aa2d163df25a39fb40.nq.gz
    ├── 35af5a0b0736c4330aeb0630415cd82ad8492b6e.nq.gz
    ├── 36286df379e28ea997bea3ee1fd62cadebebbba9.nq.gz
    ├── 3685e18e23675fc9786eb396747a0f3d603715b9.nq.gz
    ├── 374b4e85b8f4563e3bc6a7318d156c7052acba5b.nq.gz
    ├── 37b36f6ef0cb5662f5e186b45b7d638ac9f7284f.nq.gz
    ├── 37e86bfe2bedbc45fa2a7cef8b2364af7e71514a.nq.gz
    ├── 3891a8aa33f383289d649377d9df52fc7ac5e242.nq.gz
    ├── 394acd7678c5a03cadbfd38ea49f1581050a3880.nq.gz
    ├── 3a0ffbf3e516269e088f6bf6771342b5f6a25bfd.nq.gz
    ├── 3abaa33b4ef13f0ef7101898a0b1dff9eadbed2b.nq.gz
    ├── 3ac3fda23ea092fc5819ec9a003e2203a5ee108e.nq.gz
    ├── 3ae7fa68b48e22113199e4d73b84ebb6bdaf1a31.nq.gz
    ├── 3b3168d23f3f26a5b0194e5eab3b5b0b0c430177.nq.gz
    ├── 3b614dcf6bd2e627def4c56a464d0939902a00d7.nq.gz
    ├── 3b9882ad4c0c742672a2655e26053d6d6be8a9a6.nq.gz
    ├── 3ba219509d0e3db2fa4e824ecb8bdf27b2e367fb.nq.gz
    ├── 3bd05181a234355ea53e49c03b6da7f5b159b0b0.nq.gz
    ├── 3bf688860f236b4c4298e417a8eb2ef7a5c14e81.nq.gz
    ├── 3c4c086095dcb1bc4e416259f42961ef6e56394e.nq.gz
    ├── 3c748d33e45bfcdc690ceee490cbb50b516cd2b3.nq.gz
    ├── 3ca5355008c54d8ee8e0a0488402ddd0272cf639.nq.gz
    ├── 3d431ac5e9e3bc3bd0ebcaf750f8997990444c3f.nq.gz
    ├── 3d47f78fd7657ad4a176d8f1faaa1c0122a3ebfa.nq.gz
    ├── 3df1419796a98bbd4198215ef286517dbdabb27a.nq.gz
    ├── 3e8a1b9a2e80728fc79dcb302205d21c573ece93.nq.gz
    ├── 3f7440234ee7dde945aef0e8a42e8441f33fedc7.nq.gz
    ├── 3faa23fa93971fa468602264bd40ba3fff01cfe2.nq.gz
    ├── 3faec95e3a7e0547032e72c0e0f16368ce71078d.nq.gz
    ├── 3fcde8f562d189d6a2596cbe1b844ac0fc8d6c4d.nq.gz
    ├── 402404165a6c5c4e89c4757a1af1c7ce89064af8.nq.gz
    ├── 40562b07fc2f2ad7a364d27b3aaed650c1b250cc.nq.gz
    ├── 41581fda6e77791e2fe79847b71d974b3046abd4.nq.gz
    ├── 4173250165758b8e7c286a23bed7a170f35eddaf.nq.gz
    ├── 4195f707ec17816c7d36dd1b0f00bdea2f27cd73.nq.gz
    ├── 41a9bc6006fec0b03ec786ea20debae70421961f.nq.gz
    ├── 422f0237ae60ed5846821df8e44d74bff1f3d28e.nq.gz
    ├── 4290dbd73bc30d9476afa60a0b1dc704c97a0ced.nq.gz
    ├── 42db7c00202962561f5dfdb295b2cab54d4868c7.nq.gz
    ├── 43a929cc7b202064ad312e88b9168f3e275deb38.nq.gz
    ├── 442ea0679f284a24dedcf951a1ec3bea7362468f.nq.gz
    ├── 455e11dc026d3483f05ee8fe3c4f2b933806f746.nq.gz
    ├── 456510a89d32965c1d9f2bd5bf8a40ec94cadc2b.nq.gz
    ├── 45f0a37da327035177cf24ff3c1855fad109f6e7.nq.gz
    ├── 4602131b7622caa37fdc89a1968679bef81314c6.nq.gz
    ├── 460f4248b4db27b4082d9c80ee8ffbfa16d583ab.nq.gz
    ├── 46f8e4e5b4847a290757fbd62803a48af08f270d.nq.gz
    ├── 48768233035340b5300e067d7348e0d950744818.nq.gz
    ├── 49c74980ad33a4d4bca3531e17850b41e7ff5d8a.nq.gz
    ├── 49f344e146b77d36fb58f62e8c214c1d3d49497e.nq.gz
    ├── 4a592c867ac1c97dfbb5f5c040a1086bbb0cc03e.nq.gz
    ├── 4a945d1114cda8c954c47b3297b565e6717ecb7e.nq.gz
    ├── 4ab952520150aceaaa86324effc87f6fcb892290.nq.gz
    ├── 4ae80e0de0483fdd55160f41b556d76e27308955.nq.gz
    ├── 4c1e200c49237f8b924f0b9bd3266df2cf87896c.nq.gz
    ├── 4ce7635abd31da36f5c6818622d3278cfb2ed91a.nq.gz
    ├── 4d0ffea34f7a766b68f539aff89846eea1bdce1b.nq.gz
    ├── 4d7c2fc84bd2465a9305676c54996449bf93b034.nq.gz
    ├── 4f6d8b2d79406012c5f8bae9c289ed5bf4d179cc.nq.gz
    ├── 4febcee86ba3a659a6a4871795949ad48203183b.nq.gz
    ├── 50113d3724006b888a61bbb2a34d44836a848261.nq.gz
    ├── 50737088643ddd760a347a30b1682b6c68f20ede.nq.gz
    ├── 507eed1c07f5f4a929e63401ffe5527b9f920d27.nq.gz
    ├── 50b43da3b2a2bd9b61f11244ee627710ed29ef78.nq.gz
    ├── 50e4f05a549de78b1738eb0e6f37ca800daedc68.nq.gz
    ├── 5120ed598400e948131eba3a5d152680d1f2f2e1.nq.gz
    ├── 516ed8f24e6364dbe612f5956eb07d14f40a6e35.nq.gz
    ├── 52e77ef6da662c4dcb061e22d8d36931fb364e1b.nq.gz
    ├── 5315f76fe161aef46d36968dceb01f3940f4da8f.nq.gz
    ├── 53265a6919326c17eb9890d2a8513cc10b874c18.nq.gz
    ├── 53315dc7372278a8634378c1593713c853803ff0.nq.gz
    ├── 5364527bae341ba9ace30a7648e754548bca358f.nq.gz
    ├── 536a3de69c1a54d7be75f16c9fa07ce88bb57779.nq.gz
    ├── 5496d4681c7aff523f1a0fc5e89048e16611cbce.nq.gz
    ├── 54b052551369519329717a6fbae28c2d613d6a9e.nq.gz
    ├── 55b2e79a0b99455b34c15b982f2280cef5f7ede7.nq.gz
    ├── 562674f95ff0b703a23274ac3a3f85ccee62767c.nq.gz
    ├── 565e97157cdfc58789cf126b7d33fda4fa007870.nq.gz
    ├── 566c6859fa7a5b98c5d1fc90889e102a3c30b4c7.nq.gz
    ├── 5764b85c38ed1d9334595210a9a1b68fec922b03.nq.gz
    ├── 5912d41daa02a8cec7a455bd9fe82b1cd80f8c8f.nq.gz
    ├── 594bcd52d7fdc43a56e259c78209aa1da6dafeb3.nq.gz
    ├── 59ca4da6e95d00bb649986fa13cbb877a54506f7.nq.gz
    ├── 5a6dec17511351657b765bdd2ca4d7491474ccfb.nq.gz
    ├── 5adaa3dbed09a02d7207e1e1b6c3b93af3cd7904.nq.gz
    ├── 5bbb885dbecec1aa246f5b1a0ab597979dce7826.nq.gz
    ├── 5d69d8c4d542023707a347edf269246bfc308570.nq.gz
    ├── 5e3798e86862e06aaec2ee2cc3986849c8699f8e.nq.gz
    ├── 5f0bd51bf24f4eb000f2a0398dcaf4c01e79fa4d.nq.gz
    ├── 5fb16ba4460f83f8a61be8c864c998f3aff57eef.nq.gz
    ├── 5fe54e8590fcccfd8269a6a530537c8d1b8dc73a.nq.gz
    ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
    ├── 6286b565f8d104776767933680b53b421e3823fd.nq.gz
    ├── 62e4f8b906c1595252c2d254939acaa7ef9f5e3a.nq.gz
    ├── 62f1ba95dd3b2e1e77ca9ce238487e46d3c2bb30.nq.gz
    ├── 63b0168cbb21d7b6e5631a3c8b761cc07fa4b043.nq.gz
    ├── 63f90785d8a9d3338b226c32ea16ab093c09a0ca.nq.gz
    ├── 6413f8ed53bd62379d6cc406f1a3573faff60e58.nq.gz
    ├── 6468e5316928608228025551fc1eb802b7476f04.nq.gz
    ├── 64733343187ba28bc0780742509ce567b42ee1be.nq.gz
    ├── 649279b06ecbf98bfb22e2a7d9792edc7984a076.nq.gz
    ├── 664701fb4a7f3515d98d5265c5e4207860b4da58.nq.gz
    ├── 670988206de985adfc46daef2e924b48073161cd.nq.gz
    ├── 67207262ca7684fc9cfcca436faff4f40d5eb9f4.nq.gz
    ├── 676caf96153a595db91059b72bb6cc9ab5733685.nq.gz
    ├── 6941a2e4e7d40e610cfca8e4f6720e3d96b1cf02.nq.gz
    ├── 69551b25d68259585d312094e46cfc25b9126559.nq.gz
    ├── 6a247d793cff5e082e4bef8ec17e2486f9c777f8.nq.gz
    ├── 6a6b1bf9e9f4f4ff02bb37e49e95f5c1d21ad85a.nq.gz
    ├── 6b7c019baf67bb256c62565d70ff401f077f494c.nq.gz
    ├── 6bed4f767ba7b00e4bc5364b9f7a1ec7f545bdf8.nq.gz
    ├── 6bf2a1ebe9e3db447bca90587860a18f07682681.nq.gz
    ├── 6e27d5659f6b2555a534ce19fb3f5badd139ea82.nq.gz
    ├── 6e5a201f4a3406bba430965910bd836da6b3a26b.nq.gz
    ├── 6eb1904ac89e5ec0e85ef2b235940a04d6317a2f.nq.gz
    ├── 6fc96363a1fd6216aa261ad0f3b05c5ef847e664.nq.gz
    ├── 6fdd43cd3fa8de4c3422f968e4de54f613456675.nq.gz
    ├── 6ffa7ee9a6c92d16c9cc87e6204f62192c217fc2.nq.gz
    ├── 70005f85e5b2e9414307aa2cb11300238b93efc4.nq.gz
    ├── 71d5851d6e6311a64e09d274efb4b031eeeecc5e.nq.gz
    ├── 72863bd53c660d3638cb0d43734eb64039f003bd.nq.gz
    ├── 73566d9e6a5c21a130ea4aea14b6aa01bb0ee38d.nq.gz
    ├── 74eb72641e1b0554abbecddaeb9ade758ca01096.nq.gz
    ├── 7596c3a38524256226e13df57169d284e5d12236.nq.gz
    ├── 75c03d2aca35cecd201d96ab06b49e545a68892c.nq.gz
    ├── 76b41f4bb7808195caa44095e46ec57bbadf1ad0.nq.gz
    ├── 778b71bb6000e727420824ea82b7ec1b11e0786b.nq.gz
    ├── 785f19a464119419549f74df5026c0b1f89cb1af.nq.gz
    ├── 78c2e58a58a674e087757123b8110b110944bea0.nq.gz
    ├── 792d7ffb3d12bc11ffdff721770abf518693bd1a.nq.gz
    ├── 79594bf9a7a740dd1bb80f774f8410eb6ef3b703.nq.gz
    ├── 799c0d18cad812e3cfdfe8d5816fb82cc9d360c7.nq.gz
    └── 7ae1056733cedf1ed40507c3245fd11579ebc585.nq.gz

2 directories, 200 files
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

[willmcgugan/rich](https://github.com/willmcgugan/rich)

---
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*

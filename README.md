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
├── aggregate
│   ├── ast
│   │   ├── 063c653faa82c2e2a2497e71f45fe27ea159f01b.nq.gz
│   │   ├── 143fe06c477006b7d51c6a144047d77cbafde0b4.nq.gz
│   │   ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│   │   ├── 507f54995a2fb330440cb4fc9d7c6335350bd6a2.nq.gz
│   │   ├── 9b85add4b0be924da0753874f9ef35165e6fe665.nq.gz
│   │   ├── d4a60fef7ec607be08908ebde7be522e28a1e922.nq.gz
│   │   └── f1bde0a821781f6b7421fffd4df13a4afaaef47c.nq.gz
│   ├── lsp
│   │   ├── 063c653faa82c2e2a2497e71f45fe27ea159f01b.nq.gz
│   │   ├── 143fe06c477006b7d51c6a144047d77cbafde0b4.nq.gz
│   │   ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│   │   ├── 507f54995a2fb330440cb4fc9d7c6335350bd6a2.nq.gz
│   │   ├── 9b85add4b0be924da0753874f9ef35165e6fe665.nq.gz
│   │   ├── d4a60fef7ec607be08908ebde7be522e28a1e922.nq.gz
│   │   └── f1bde0a821781f6b7421fffd4df13a4afaaef47c.nq.gz
│   └── repolex
│       ├── 063c653faa82c2e2a2497e71f45fe27ea159f01b.nq.gz
│       ├── 143fe06c477006b7d51c6a144047d77cbafde0b4.nq.gz
│       ├── 1b437866469bd5a05e0a14141dc5c17acd30c858.nq.gz
│       ├── 507f54995a2fb330440cb4fc9d7c6335350bd6a2.nq.gz
│       ├── 9b85add4b0be924da0753874f9ef35165e6fe665.nq.gz
│       ├── d4a60fef7ec607be08908ebde7be522e28a1e922.nq.gz
│       └── f1bde0a821781f6b7421fffd4df13a4afaaef47c.nq.gz
└── blob
    ├── 00336c3e11762c13d7a58614c15032e0b82e5192.nq.gz
    ├── 007f82a4a06c883854c2f648c64c0c74112ed7b1.nq.gz
    ├── 009fda6a09bf14d21acb09fa4ebaf80dfb342c27.nq.gz
    ├── 00b21f48b362d45bce6d954238a9cc82d4953d62.nq.gz
    ├── 01033c248f8bd62ac42c74ad6046cf64dbfa9087.nq.gz
    ├── 01c6cafbe53f1fcb12f7b382b2b35e2fd2c69933.nq.gz
    ├── 02fdd0b0fb86634f4d297bc0bf01727cdbc3745d.nq.gz
    ├── 03202f2cd29e25d150b047d8211bc7af5f4e67f7.nq.gz
    ├── 0459369d190ff2377a8336429fb8cd7e1a08b3fe.nq.gz
    ├── 046323eca755593e5e187ae235e63888a1023f82.nq.gz
    ├── 04a30a53e20ca30fffc0b060df138e6d842b148d.nq.gz
    ├── 04fbd713296a1643410aa2f422806f85ca64d93a.nq.gz
    ├── 05c863a93dd968675df9b4df6b1e047ae315660d.nq.gz
    ├── 06ab11ef5e38e46079824158d4e29eb9d6806f22.nq.gz
    ├── 06de437202fa2615567bff20cddc369a073c3aa5.nq.gz
    ├── 06f813743edb0405a3810a24d7f5533d0dd0842f.nq.gz
    ├── 071957507bfc4cdd751dd2abc530f7a17aa97481.nq.gz
    ├── 076cb6669612f46d2a9d6ce2c64ee3b65a52cf23.nq.gz
    ├── 0790b1dadb847039d34a47344756ed3514f9e01b.nq.gz
    ├── 07c16425c0d4a859ae07db5b8c6c220d1dfe9c6d.nq.gz
    ├── 082d881741a10b0ce11d96970cda7042f4cec15e.nq.gz
    ├── 08beccc229cce8e01a8f0eb35cb131a6d3f095a5.nq.gz
    ├── 08c6eba328a805fadf7e74db17dff4023c5ca7c4.nq.gz
    ├── 0a085c785df4b5889a0c678e5679e982b6af7931.nq.gz
    ├── 0a687f441eca7fa4c7df6a0da11daf7f10d2023e.nq.gz
    ├── 0a7d22fa1115873536c654bdcd13e08f859135f5.nq.gz
    ├── 0a815291e29df108b2411833de13b8a7a2711b28.nq.gz
    ├── 0ae74bdde6a04295e9c0fbd17ef7edf5b5423d08.nq.gz
    ├── 0b46db1708291cc51eba57a3d43b356b85e43ce8.nq.gz
    ├── 0b7aaa575997b962a04d3c174cf03e51c0e6dbf0.nq.gz
    ├── 0b98b4d678e5a7bf9f0f42bc5006e1fea7dc2cf7.nq.gz
    ├── 0bcc67969542b0c6a4597365c40b45fbcb6fcaf6.nq.gz
    ├── 0c7598709e6c7b8e09f655e060bee14ff65856a9.nq.gz
    ├── 0c85af0406cf1fec285541bda7e07afa5af1d1cc.nq.gz
    ├── 0eb5487d1e6ffc2b27357801e4fc2f4fe43ff61c.nq.gz
    ├── 0ffc313acff8d8b5f2171f07f5b942448e290f73.nq.gz
    ├── 1067417f252b12a002146fe1c3e5191e54c953ee.nq.gz
    ├── 108e8b067cda6acfb2c718b30013673ae09cf119.nq.gz
    ├── 1144ebb49f70873a2cc2338b4434d392a3c8b855.nq.gz
    ├── 11c9ba1d3ffa30097042f1c07135e8f9db979a5e.nq.gz
    ├── 12198de48a554658879be22a376ea54fba67df4a.nq.gz
    ├── 13be0704fcee3e1510570f636ba45ebe09a7565b.nq.gz
    ├── 1477bd64f066992c07350edc2a3e84f8089c7b5e.nq.gz
    ├── 14bcd02481f899753747e03855abf1e33ec1fa09.nq.gz
    ├── 14fb53f275f80c0fb744c47b940ebd21b60b7fa2.nq.gz
    ├── 14fb919ff5120db8314ec12c3354b269913f9512.nq.gz
    ├── 15a3a939c9a07d540005647b104ab330d52a261a.nq.gz
    ├── 15fad3dac387a0425705c8e36d11437ca5c6a3b5.nq.gz
    ├── 164b18a1b1f743377b912ccee3f70d3aa12e3d29.nq.gz
    ├── 169b1cf53f91ba41739de405c41a16abd6a83bf9.nq.gz
    ├── 170f94b34d7a39230b6f5bed23de8e2e2083f33f.nq.gz
    ├── 17851d4a6b14a911d676f206642eae1bc921b4ce.nq.gz
    ├── 17b5632f12370ee1ee4ef6d6eeb6836b03f2bb7e.nq.gz
    ├── 18467c6b16e063c016fc1c6cc30a429b79330394.nq.gz
    ├── 184c219a9ee32e9d2f9b27054cb3d1fbda549c84.nq.gz
    ├── 18b7c2c27659e9c7799e1fd31e41d92108dd7747.nq.gz
    ├── 194564e761ddae165b39ef6598877e2e3820af0a.nq.gz
    ├── 1a0ebccec411e4f2cb867661874b5097f57407b8.nq.gz
    ├── 1af0d95c32152672dc4583296207907eb6534083.nq.gz
    ├── 1b3df42cd20dac49f0758167e67f9f80ff627b9e.nq.gz
    ├── 1cd0c7b93b94e7c537a86e6ed42feaf9dcbba98c.nq.gz
    ├── 1d1c6c1608a5b67046cb872f8a907903b590c691.nq.gz
    ├── 1d6300e76805c201fad879b18545af962a995b83.nq.gz
    ├── 1debad2c4bbdce765480227bc05e8ac9144946f9.nq.gz
    ├── 1e40a254f781f8df6defc45fc4fec27aa213d65d.nq.gz
    ├── 1eeb31d06c18047cc4e05b2c3f10cda08ab140dc.nq.gz
    ├── 1f02e9f47d5b18e2a71b4f2029ead7acb78f92a6.nq.gz
    ├── 1f2877bb2bd520253502b1c05bb811bb0d7ef64c.nq.gz
    ├── 1f517ad8ea8ecea938dfa253dece0d9e18945215.nq.gz
    ├── 1f682472395439a82e737cae8accf30c18188f72.nq.gz
    ├── 2033d7b98115adb0d0f1db2e90ae8977440e2cfe.nq.gz
    ├── 205b2458cd1b097a7c9dc59cb4b098b31e34de9a.nq.gz
    ├── 20a321da1f08e0862da3af93dc768d6938f18c3a.nq.gz
    ├── 2121a786381f8bda36db578f26b6164dc3fff6b8.nq.gz
    ├── 2218d03b76919ed478f64d450967cb3a76bd2c9c.nq.gz
    ├── 228cb189dfcc1426a848fa3a57dc20358411b5ec.nq.gz
    ├── 23075045958ac749743519cfa9af34591885c820.nq.gz
    ├── 233804adff338dcd7e01f1de13894b1bfa108d6d.nq.gz
    ├── 23c6124d623a38ff3b8c5fc2021fec4c1da54753.nq.gz
    ├── 244230d652762bfbcc5e106315c6d865dabb5891.nq.gz
    ├── 2455a404fcd3d6dedb92a2d3ab47a55f70ccd365.nq.gz
    ├── 24e44a220365afe83d85c92509af8da02a4260cf.nq.gz
    ├── 260cfbeacdc30355758a33efb385200aadf65b0c.nq.gz
    ├── 26ec6fffecb21e2c81b7cea3064480aa9d694b0d.nq.gz
    ├── 273b0dbc209d1867b3067d9d3180b7b5578112d3.nq.gz
    ├── 27a0f6ceac99f621450a944ad97e17edf6f9bb0f.nq.gz
    ├── 28ae54e89cbc94666cbfebe903a902d757dd4056.nq.gz
    ├── 2903a3cdd73048a80a1f34362886b8879e90ff01.nq.gz
    ├── 2951d6846f53686517cddfca71cd46c4b8d135aa.nq.gz
    ├── 2966948fb0eaa60c41942c9a9147f9ee0f2f85cc.nq.gz
    ├── 2977495f299c8977d893018504ea498ef92a71c3.nq.gz
    ├── 29a263e6614597808a182216b51868c11e00c412.nq.gz
    ├── 2b0d250f7a0a5950699266c327b795a43da03717.nq.gz
    ├── 2b512ef82b7462061acf812cec32083b7cb2ecef.nq.gz
    ├── 2b557e5d327f0c7f557287f6de52459a85fe6e87.nq.gz
    ├── 2c0967c2111f9541f4bb50f7dce38bb0605c353c.nq.gz
    ├── 2c33d233f3ad7e48a34578d63ce77ebcb75b584e.nq.gz
    ├── 2c7ac3dbd54fd12bd3c72f0c74ae5212c2b8aaec.nq.gz
    ├── 2c9ac094f650480cd30aeca596fec4eed0d7fc0a.nq.gz
    ├── 2caad0bccc2a6993780aed3b6eeccbc3fede2b31.nq.gz
    ├── 2d0cc4f0f797a9457c92a3ebdd25efacca2b1c7a.nq.gz
    ├── 2d926775af03b85c2bef899e9a97d6ba173a5f75.nq.gz
    ├── 2db134d7515ad2cf5aab3aeab3f09e5c57a4428f.nq.gz
    ├── 2e6fef7f5a1bf5552dc63f7d5078b19a847419da.nq.gz
    ├── 2fd1f3d8e418f6dac1734ca0399938d5be304171.nq.gz
    ├── 3079aa470d8290d6c75e99eef4aff75c8fde7a23.nq.gz
    ├── 310b994d3ad71fe30083d4ed1580d37c0c221235.nq.gz
    ├── 31840b78fffa39d8e028639f1a2cb546fd726422.nq.gz
    ├── 3185d0c6c6760557ae04f43df6d459ca9e497929.nq.gz
    ├── 31e50e926eee0f504cfb6e664762d7178abb9f0a.nq.gz
    ├── 328bbd964db106c2f839d90de8828b8d4304a2fe.nq.gz
    ├── 334c31d9c8175588bd89d9b2f8094f38d058aeb9.nq.gz
    ├── 33850842ced327df5cc3f48ef152e199c70d39a2.nq.gz
    ├── 33e431399ffb363f801ad1255b8b2cdcdaafab63.nq.gz
    ├── 33f884ee4bf85783a60b3ade2a06354a2dc2bece.nq.gz
    ├── 3421061cc117347265c179ec5cf57d4231d0e6d3.nq.gz
    ├── 34366bff99dbcb4287b280d09b4cbd568aae6df8.nq.gz
    ├── 34c2a11ead0164b58b23dfd6ee13b70a139ac274.nq.gz
    ├── 352dfdf3dbf8af25a02f4170e13654fa891f3281.nq.gz
    ├── 35468ca06a094ecc0278e9d8e40e0b65a6e92c20.nq.gz
    ├── 3571c872c6b13415ca0402aa2d163df25a39fb40.nq.gz
    ├── 35af5a0b0736c4330aeb0630415cd82ad8492b6e.nq.gz
    ├── 36286df379e28ea997bea3ee1fd62cadebebbba9.nq.gz
    ├── 363eeb34a95910cfaf3dc5e0ef08f169856fd753.nq.gz
    ├── 3685e18e23675fc9786eb396747a0f3d603715b9.nq.gz
    ├── 374b4e85b8f4563e3bc6a7318d156c7052acba5b.nq.gz
    ├── 37b36f6ef0cb5662f5e186b45b7d638ac9f7284f.nq.gz
    ├── 37b880d0d40e4181fa7bc1c3d7ad8225721a9563.nq.gz
    ├── 37e86bfe2bedbc45fa2a7cef8b2364af7e71514a.nq.gz
    ├── 37ed4b497edf1d230cc2ffe9e51bf94357592cdc.nq.gz
    ├── 3891a8aa33f383289d649377d9df52fc7ac5e242.nq.gz
    ├── 390100ec8113ee52064e03b5d4331f7269b90336.nq.gz
    ├── 394acd7678c5a03cadbfd38ea49f1581050a3880.nq.gz
    ├── 3962ddc74a52c3d885021830fd87af4701acc1e6.nq.gz
    ├── 39b475dc376f2a0900a3728ffa9c68932a892a57.nq.gz
    ├── 3a0ffbf3e516269e088f6bf6771342b5f6a25bfd.nq.gz
    ├── 3a2023154c3e450d06d75bcfb6d3583e189a99ed.nq.gz
    ├── 3abaa33b4ef13f0ef7101898a0b1dff9eadbed2b.nq.gz
    ├── 3ac3fda23ea092fc5819ec9a003e2203a5ee108e.nq.gz
    ├── 3ae7fa68b48e22113199e4d73b84ebb6bdaf1a31.nq.gz
    ├── 3b253458144aa8a853c2cadfc8dbbf2df019e2be.nq.gz
    ├── 3b3168d23f3f26a5b0194e5eab3b5b0b0c430177.nq.gz
    ├── 3b614dcf6bd2e627def4c56a464d0939902a00d7.nq.gz
    ├── 3b9882ad4c0c742672a2655e26053d6d6be8a9a6.nq.gz
    ├── 3ba219509d0e3db2fa4e824ecb8bdf27b2e367fb.nq.gz
    ├── 3bd05181a234355ea53e49c03b6da7f5b159b0b0.nq.gz
    ├── 3bf39fb7536357dea380f8d346459903703d2218.nq.gz
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
    ├── 40d3a04a82d1d05c153698e92b681186dc32dcb5.nq.gz
    ├── 40e054b908aa3390e5288fd34a14041d8b4c7dd0.nq.gz
    ├── 41581fda6e77791e2fe79847b71d974b3046abd4.nq.gz
    ├── 4173250165758b8e7c286a23bed7a170f35eddaf.nq.gz
    ├── 4195f707ec17816c7d36dd1b0f00bdea2f27cd73.nq.gz
    ├── 41a9bc6006fec0b03ec786ea20debae70421961f.nq.gz
    ├── 4203fe0404bc80990f8572ccb78778bd1dedd4fb.nq.gz
    ├── 422f0237ae60ed5846821df8e44d74bff1f3d28e.nq.gz
    ├── 424b81adbd881a4e85dbf43d31f3e116809ab077.nq.gz
    ├── 4290dbd73bc30d9476afa60a0b1dc704c97a0ced.nq.gz
    ├── 42db7c00202962561f5dfdb295b2cab54d4868c7.nq.gz
    ├── 43a929cc7b202064ad312e88b9168f3e275deb38.nq.gz
    ├── 43d9f108f3f156236c76205c93c33ef05b4c1db3.nq.gz
    ├── 43e4e870de8a742f663604325d17280a31f534db.nq.gz
    ├── 442ea0679f284a24dedcf951a1ec3bea7362468f.nq.gz
    ├── 455e11dc026d3483f05ee8fe3c4f2b933806f746.nq.gz
    ├── 456510a89d32965c1d9f2bd5bf8a40ec94cadc2b.nq.gz
    └── 45f0a37da327035177cf24ff3c1855fad109f6e7.nq.gz

6 directories, 200 files
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
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*

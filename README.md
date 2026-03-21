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
    ├── 01c6cafbe53f1fcb12f7b382b2b35e2fd2c69933.nq.gz
    ├── 02fdd0b0fb86634f4d297bc0bf01727cdbc3745d.nq.gz
    ├── 04a30a53e20ca30fffc0b060df138e6d842b148d.nq.gz
    ├── 05c863a93dd968675df9b4df6b1e047ae315660d.nq.gz
    ├── 06de437202fa2615567bff20cddc369a073c3aa5.nq.gz
    ├── 07c16425c0d4a859ae07db5b8c6c220d1dfe9c6d.nq.gz
    ├── 08beccc229cce8e01a8f0eb35cb131a6d3f095a5.nq.gz
    ├── 08c6eba328a805fadf7e74db17dff4023c5ca7c4.nq.gz
    ├── 0a815291e29df108b2411833de13b8a7a2711b28.nq.gz
    ├── 0ffc313acff8d8b5f2171f07f5b942448e290f73.nq.gz
    ├── 12198de48a554658879be22a376ea54fba67df4a.nq.gz
    ├── 13be0704fcee3e1510570f636ba45ebe09a7565b.nq.gz
    ├── 14bcd02481f899753747e03855abf1e33ec1fa09.nq.gz
    ├── 14fb919ff5120db8314ec12c3354b269913f9512.nq.gz
    ├── 15a3a939c9a07d540005647b104ab330d52a261a.nq.gz
    ├── 15fad3dac387a0425705c8e36d11437ca5c6a3b5.nq.gz
    ├── 164b18a1b1f743377b912ccee3f70d3aa12e3d29.nq.gz
    ├── 17b5632f12370ee1ee4ef6d6eeb6836b03f2bb7e.nq.gz
    ├── 18467c6b16e063c016fc1c6cc30a429b79330394.nq.gz
    ├── 194564e761ddae165b39ef6598877e2e3820af0a.nq.gz
    ├── 1a0ebccec411e4f2cb867661874b5097f57407b8.nq.gz
    ├── 1b3df42cd20dac49f0758167e67f9f80ff627b9e.nq.gz
    ├── 1f2877bb2bd520253502b1c05bb811bb0d7ef64c.nq.gz
    ├── 2033d7b98115adb0d0f1db2e90ae8977440e2cfe.nq.gz
    ├── 2121a786381f8bda36db578f26b6164dc3fff6b8.nq.gz
    ├── 2218d03b76919ed478f64d450967cb3a76bd2c9c.nq.gz
    ├── 228cb189dfcc1426a848fa3a57dc20358411b5ec.nq.gz
    ├── 23c6124d623a38ff3b8c5fc2021fec4c1da54753.nq.gz
    ├── 24e44a220365afe83d85c92509af8da02a4260cf.nq.gz
    ├── 260cfbeacdc30355758a33efb385200aadf65b0c.nq.gz
    ├── 26ec6fffecb21e2c81b7cea3064480aa9d694b0d.nq.gz
    ├── 2966948fb0eaa60c41942c9a9147f9ee0f2f85cc.nq.gz
    ├── 2b0d250f7a0a5950699266c327b795a43da03717.nq.gz
    ├── 2caad0bccc2a6993780aed3b6eeccbc3fede2b31.nq.gz
    ├── 2e6fef7f5a1bf5552dc63f7d5078b19a847419da.nq.gz
    ├── 2fd1f3d8e418f6dac1734ca0399938d5be304171.nq.gz
    ├── 310b994d3ad71fe30083d4ed1580d37c0c221235.nq.gz
    ├── 328bbd964db106c2f839d90de8828b8d4304a2fe.nq.gz
    ├── 334c31d9c8175588bd89d9b2f8094f38d058aeb9.nq.gz
    ├── 3421061cc117347265c179ec5cf57d4231d0e6d3.nq.gz
    ├── 34c2a11ead0164b58b23dfd6ee13b70a139ac274.nq.gz
    ├── 36286df379e28ea997bea3ee1fd62cadebebbba9.nq.gz
    ├── 37b36f6ef0cb5662f5e186b45b7d638ac9f7284f.nq.gz
    ├── 37e86bfe2bedbc45fa2a7cef8b2364af7e71514a.nq.gz
    ├── 3a0ffbf3e516269e088f6bf6771342b5f6a25bfd.nq.gz
    ├── 3abaa33b4ef13f0ef7101898a0b1dff9eadbed2b.nq.gz
    ├── 3ac3fda23ea092fc5819ec9a003e2203a5ee108e.nq.gz
    ├── 3ae7fa68b48e22113199e4d73b84ebb6bdaf1a31.nq.gz
    ├── 3b3168d23f3f26a5b0194e5eab3b5b0b0c430177.nq.gz
    ├── 3b9882ad4c0c742672a2655e26053d6d6be8a9a6.nq.gz
    ├── 3bd05181a234355ea53e49c03b6da7f5b159b0b0.nq.gz
    ├── 3bf688860f236b4c4298e417a8eb2ef7a5c14e81.nq.gz
    ├── 3c4c086095dcb1bc4e416259f42961ef6e56394e.nq.gz
    ├── 3c748d33e45bfcdc690ceee490cbb50b516cd2b3.nq.gz
    ├── 3ca5355008c54d8ee8e0a0488402ddd0272cf639.nq.gz
    ├── 3d431ac5e9e3bc3bd0ebcaf750f8997990444c3f.nq.gz
    ├── 3f7440234ee7dde945aef0e8a42e8441f33fedc7.nq.gz
    ├── 402404165a6c5c4e89c4757a1af1c7ce89064af8.nq.gz
    ├── 40562b07fc2f2ad7a364d27b3aaed650c1b250cc.nq.gz
    ├── 4173250165758b8e7c286a23bed7a170f35eddaf.nq.gz
    ├── 41a9bc6006fec0b03ec786ea20debae70421961f.nq.gz
    ├── 422f0237ae60ed5846821df8e44d74bff1f3d28e.nq.gz
    ├── 4290dbd73bc30d9476afa60a0b1dc704c97a0ced.nq.gz
    ├── 42db7c00202962561f5dfdb295b2cab54d4868c7.nq.gz
    ├── 43a929cc7b202064ad312e88b9168f3e275deb38.nq.gz
    ├── 442ea0679f284a24dedcf951a1ec3bea7362468f.nq.gz
    ├── 455e11dc026d3483f05ee8fe3c4f2b933806f746.nq.gz
    ├── 456510a89d32965c1d9f2bd5bf8a40ec94cadc2b.nq.gz
    ├── 4602131b7622caa37fdc89a1968679bef81314c6.nq.gz
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
    ├── 4d7c2fc84bd2465a9305676c54996449bf93b034.nq.gz
    ├── 4f6d8b2d79406012c5f8bae9c289ed5bf4d179cc.nq.gz
    ├── 4febcee86ba3a659a6a4871795949ad48203183b.nq.gz
    ├── 50113d3724006b888a61bbb2a34d44836a848261.nq.gz
    ├── 507eed1c07f5f4a929e63401ffe5527b9f920d27.nq.gz
    ├── 50b43da3b2a2bd9b61f11244ee627710ed29ef78.nq.gz
    ├── 5120ed598400e948131eba3a5d152680d1f2f2e1.nq.gz
    ├── 516ed8f24e6364dbe612f5956eb07d14f40a6e35.nq.gz
    ├── 52e77ef6da662c4dcb061e22d8d36931fb364e1b.nq.gz
    ├── 53265a6919326c17eb9890d2a8513cc10b874c18.nq.gz
    ├── 53315dc7372278a8634378c1593713c853803ff0.nq.gz
    ├── 5496d4681c7aff523f1a0fc5e89048e16611cbce.nq.gz
    ├── 54b052551369519329717a6fbae28c2d613d6a9e.nq.gz
    ├── 55b2e79a0b99455b34c15b982f2280cef5f7ede7.nq.gz
    ├── 562674f95ff0b703a23274ac3a3f85ccee62767c.nq.gz
    ├── 565e97157cdfc58789cf126b7d33fda4fa007870.nq.gz
    ├── 566c6859fa7a5b98c5d1fc90889e102a3c30b4c7.nq.gz
    ├── 5764b85c38ed1d9334595210a9a1b68fec922b03.nq.gz
    ├── 594bcd52d7fdc43a56e259c78209aa1da6dafeb3.nq.gz
    ├── 59ca4da6e95d00bb649986fa13cbb877a54506f7.nq.gz
    ├── 5adaa3dbed09a02d7207e1e1b6c3b93af3cd7904.nq.gz
    ├── 5bbb885dbecec1aa246f5b1a0ab597979dce7826.nq.gz
    ├── 5d69d8c4d542023707a347edf269246bfc308570.nq.gz
    ├── 5f0bd51bf24f4eb000f2a0398dcaf4c01e79fa4d.nq.gz
    ├── 5fb16ba4460f83f8a61be8c864c998f3aff57eef.nq.gz
    ├── 5fe54e8590fcccfd8269a6a530537c8d1b8dc73a.nq.gz
    ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
    ├── 6286b565f8d104776767933680b53b421e3823fd.nq.gz
    ├── 62e4f8b906c1595252c2d254939acaa7ef9f5e3a.nq.gz
    ├── 62f1ba95dd3b2e1e77ca9ce238487e46d3c2bb30.nq.gz
    ├── 63b0168cbb21d7b6e5631a3c8b761cc07fa4b043.nq.gz
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
    ├── 6bed4f767ba7b00e4bc5364b9f7a1ec7f545bdf8.nq.gz
    ├── 6bf2a1ebe9e3db447bca90587860a18f07682681.nq.gz
    ├── 6e27d5659f6b2555a534ce19fb3f5badd139ea82.nq.gz
    ├── 6e5a201f4a3406bba430965910bd836da6b3a26b.nq.gz
    ├── 6fc96363a1fd6216aa261ad0f3b05c5ef847e664.nq.gz
    ├── 6ffa7ee9a6c92d16c9cc87e6204f62192c217fc2.nq.gz
    ├── 70005f85e5b2e9414307aa2cb11300238b93efc4.nq.gz
    ├── 71d5851d6e6311a64e09d274efb4b031eeeecc5e.nq.gz
    ├── 74eb72641e1b0554abbecddaeb9ade758ca01096.nq.gz
    ├── 7596c3a38524256226e13df57169d284e5d12236.nq.gz
    ├── 75c03d2aca35cecd201d96ab06b49e545a68892c.nq.gz
    ├── 76b41f4bb7808195caa44095e46ec57bbadf1ad0.nq.gz
    ├── 778b71bb6000e727420824ea82b7ec1b11e0786b.nq.gz
    ├── 785f19a464119419549f74df5026c0b1f89cb1af.nq.gz
    ├── 78c2e58a58a674e087757123b8110b110944bea0.nq.gz
    ├── 799c0d18cad812e3cfdfe8d5816fb82cc9d360c7.nq.gz
    ├── 7ae1056733cedf1ed40507c3245fd11579ebc585.nq.gz
    ├── 7db5d2db7c06f2fe3aec32e387c68a1d9b1bea89.nq.gz
    ├── 7e7a3b33f8b9ccc163437b1b71c647fe15c335b5.nq.gz
    ├── 7f161d9c1a25c0094708c6f618fbcc553946df4c.nq.gz
    ├── 7f2b0a12ca5ebdada3a109c01b7560cad014af51.nq.gz
    ├── 7f5a11ffe698cbe2d94d1e7b3fa790cc11701479.nq.gz
    ├── 80098982edd7bad4dca7781bd648bb805c2a9f08.nq.gz
    ├── 8089bf0794e9b4696b04cd1e02a919f982ba8446.nq.gz
    ├── 80ad36e6356730d4a06ca8964a65fbdcefab831b.nq.gz
    ├── 823d345c8b9d0b2c1ca7375477a6a61fddd2b28f.nq.gz
    ├── 839298cfb68ce9b6e0f267ff95c052a466316a8f.nq.gz
    ├── 850f67a9108b06abb81c50472e25752199f8e628.nq.gz
    ├── 85410de5e6afaed7867544f70527a5e987d621bc.nq.gz
    ├── 87b0e18ea86200f895b9654a03b3e29722ce8f1e.nq.gz
    ├── 88d1679edbd2a581e23312540e72d2ccffa4a174.nq.gz
    ├── 898286cfabc3a2c77e86ba85b7cd540e9e31f078.nq.gz
    ├── 8d9e799c3d85fd122477a0faab67c61f59bd387e.nq.gz
    ├── 8ddd7cc9077d33f07d294ce4303b24cef7476dec.nq.gz
    ├── 8ebe5e8d3f34fca2c02f164739a7392d0ac88e33.nq.gz
    ├── 8fea58bb9db19f17c12472ef7951f34f7c774c23.nq.gz
    ├── 9048334ca9be0f8f3543ab277d861e44c3a03f2e.nq.gz
    ├── 90dcd77ec8a3c8b190f4a6726277f29be69b6ff9.nq.gz
    ├── 9178953514ad3bec46b3a8bd02a44e605efae925.nq.gz
    ├── 9261d6f9c49fb0b4a646c0a5969f25fa4833bb25.nq.gz
    ├── 927aba2116415d32e63c11921908fb29fafd04ac.nq.gz
    ├── 927c8597c79fffbb24a1ce257f7d1604a056a2e8.nq.gz
    ├── 928b4d9d2b3cda29144a7cd2e7fb32bc92d0508a.nq.gz
    ├── 937ef7353b873385a35bfd601e384fae940068b6.nq.gz
    ├── 9685a6f5ace357f234565adf1a3b65713fd147d2.nq.gz
    ├── 96962b08fc03a7226ab0beb5efe893056669ad4a.nq.gz
    ├── 973b9e85e977de998b9161002bf4b524570e5d51.nq.gz
    ├── 9773c330149be4beda4f402ba295e9f813a6e7f8.nq.gz
    ├── 97c209e1ea7baba3e0fda92e7b7b9549938e0d8c.nq.gz
    ├── 99277192b318158908bb19995580e3c020eb6d7f.nq.gz
    ├── 997e1a7e5042e657ac49e682b2e76d3db2dcbe46.nq.gz
    ├── 998f2903f1493ba42cd42a3a194fe1f6e0b0faff.nq.gz
    ├── 99a6922cb4cda208ba56a4b71dc3babd71d7a3c6.nq.gz
    ├── 99be518a493e10dd9212c46af8a94f158b5f370e.nq.gz
    ├── 99d566314440018e99bc62a771664e639314435c.nq.gz
    ├── 9a1d7d10b58c1ce5bd60d8225069805075c1d138.nq.gz
    ├── 9a41cc3964e6e7d71c149cc4a8a29d71c952c652.nq.gz
    ├── 9daf847cfb4246d3416387986b4bbf23f7a51c2d.nq.gz
    ├── 9ddc06fccce16e1495cdce3742cd515f640d44fa.nq.gz
    ├── 9f167b9a693036285b2d30f301794a2b229265bc.nq.gz
    ├── 9f8a22a48d70440ae25958166b6de9072e302f04.nq.gz
    ├── 9fa173a53c2543a742e62416fc903a928d66cf20.nq.gz
    ├── a2435c542a66d83ab5d77c0ae76e240f3a53de83.nq.gz
    ├── a2ced2e27b133e9c25c900cc10a447b4092a6603.nq.gz
    ├── a433067d5ad6c51887419ecc1849c507017ff215.nq.gz
    ├── a5ca1c0c7f75ef1089d487767bbc54cdfb012a97.nq.gz
    ├── a61f830ddb141e8ce5bc7dbf888b1175a2fe8b36.nq.gz
    ├── a667d0d693147aac743c064e7ce2dbbbc1d67b0d.nq.gz
    ├── a69f211bf8f53417ee6072237ff1d79f1f924864.nq.gz
    ├── a72dcbf9d5fc0f8dc4cd4a7836e2419b6f6c369b.nq.gz
    ├── a7caafcde4929edc4531b7ed3bc680d37488147e.nq.gz
    ├── ac4704ec508e78380644fb62253142f27a516e4e.nq.gz
    ├── b01621502b6a4de9523a5f724d7dd83e017c83b4.nq.gz
    ├── b01d2743868459efc7c1a095621e0dce3fc360a2.nq.gz
    ├── b0e4c8d9411b49c80627d74980b0b23e5100d9c3.nq.gz
    ├── b19a15c10e3c3b3e205d98137d6400c7dfa6226b.nq.gz
    ├── b236e0bb110039663016ce48a312b21e18a9cd98.nq.gz
    ├── b23803d5019e082a19d7347cd0f2472042f916c1.nq.gz
    └── b29bd6988b415ee3f3c7286b237259caeb4434e0.nq.gz

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

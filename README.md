# Repolex Knowledge Graph of NousResearch/agent-governance-toolkit

RDF knowledge graph data for [NousResearch/agent-governance-toolkit](https://github.com/NousResearch/agent-governance-toolkit), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/agent-governance-toolkit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d93e32c526ef1a7282cfb3508665e8293cf05800
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d93e32c526ef1a7282cfb3508665e8293cf05800
│           └── chunk-001.nq.gz
└── blob
    ├── 0161f4870cfa676f0fb45d9b454d9bb64e9430e4.nq.gz
    ├── 02067c381f5a50051a3bf4fcfbb53390787f3b2f.nq.gz
    ├── 0257309922b52d6a3e379788ffa392c85f777d1e.nq.gz
    ├── 02ac71fdf374df389a0867bf04cf7f37f854cb3b.nq.gz
    ├── 03004f9a1181c515325e37bc6676ad867950a805.nq.gz
    ├── 0324164ec8169ba8670e27d923442e7a62bfd255.nq.gz
    ├── 03405531717d476b8bb71904019541564850e030.nq.gz
    ├── 03bb4758caf1cf58fe281be71b9d3b141f612da7.nq.gz
    ├── 03bff0fbf959ea62463d33bd301ba0b2d223757a.nq.gz
    ├── 03f55dfff71e9f0f3feac51c2196f3bd1755d552.nq.gz
    ├── 0428bf80460e5687a73c0d0f851a512a997b95a3.nq.gz
    ├── 0494ab7c75f0b09ffa0b514959d5bae8d101aa9a.nq.gz
    ├── 0527669fdf372f35ab327e9bfdcdb8d762517acc.nq.gz
    ├── 0607bdc9038f2261d6d1f8a3427c89b754a08c8b.nq.gz
    ├── 0617e73efee50eadf04e7285952df38fa798c486.nq.gz
    ├── 0678f49f195536f5e3f1abfccb65c80d3bd5a44c.nq.gz
    ├── 06bbdba2a20cb67019a4068f8694e89a4719fac6.nq.gz
    ├── 06dd42d1af123291d31efaca72c480786ba3d81f.nq.gz
    ├── 06dd57d67fb88aa18733609afaaa19826550d25c.nq.gz
    ├── 06f10ace7226c5e58ece88fad2690d16c8698f1d.nq.gz
    ├── 070bf9807abe0ae01332fd5b38bd21c5232f7141.nq.gz
    ├── 0711d5c20143ebad11ad318f049db8bd0bba9e08.nq.gz
    ├── 077f10a076f7aac16b52df0e76a2e3549feb44f3.nq.gz
    ├── 0855bb0f3b91a4e5216b83636a0358fc2098cd20.nq.gz
    ├── 08c151529a9f8d87d328967b668de8552ec14b62.nq.gz
    ├── 08dff0ab19d214ff29f08b99d3d8996f8d3e4cf2.nq.gz
    ├── 094f168acc7873ec47efed4036ac4f8c15dd04c3.nq.gz
    ├── 0993b2bc54a39f82c39e5c97e2b441b892a75b44.nq.gz
    ├── 0a334a594fae73c9fa3c5b70583c8f7156ad003d.nq.gz
    ├── 0a3be242248968dfe4adce7d68973ba060014d6c.nq.gz
    ├── 0a4072f4dd44973a818fa72543eb3f9c924f31ab.nq.gz
    ├── 0b3653c48fe0235d8c248d8a38c6279738aeee65.nq.gz
    ├── 0bb0645211afd8164d9d0c8864647b0a88c733ae.nq.gz
    ├── 0bb8a7d112fc1d502982b7db0c2373f7c7f29e33.nq.gz
    ├── 0cf713034216215548b0cc12c197d7045f28c5da.nq.gz
    ├── 0d971673264419b79ccc98b75e2f360c6f89273a.nq.gz
    ├── 0d9c6d6fd70c68ae92a1ead213ba9863cf72cac9.nq.gz
    ├── 0e41625c5891c494fa7752c762fc48d4456e1e7e.nq.gz
    ├── 0f1901a06e25f454253be555bc431d686bdeb4d9.nq.gz
    ├── 0f1a90f3f3567d2b0a2637100c65bda4b0db4ff8.nq.gz
    ├── 0f5a990f8d62e8c78174392dd68edc7130b80d12.nq.gz
    ├── 0f7b84fe20b50a5809571a73b1b7b09b0d364be3.nq.gz
    ├── 100d6d84ee076a627deb70c0abd5b82213c83aa6.nq.gz
    ├── 1047cd52418bb6aac56e8a56cc32d9534428e7a0.nq.gz
    ├── 11044115117102842658c945d9c79126c8d9af35.nq.gz
    ├── 132ce02af690517dea4ec0a221cf93b14ff16ff2.nq.gz
    ├── 144f007d03ccfb8a73b1759b7f4e54ff8e6a28c8.nq.gz
    ├── 14ad01dabdbe65926ad506482f32b5d045ea88c0.nq.gz
    ├── 1558bbce4c4275f00c3d7005e51bc50d8adf2b0a.nq.gz
    ├── 15b8c00e17857110cd05f3e3199b08b9472540db.nq.gz
    ├── 16281a66dcfa3b6d6bed69d3e64fcbe7051357fb.nq.gz
    ├── 178473c71c266033a71e5d9d41bf470ff234366f.nq.gz
    ├── 1859ff8091fe0900076f2a695c70bc9f1e87438f.nq.gz
    ├── 18be4515b00331845dc3c6d808325b80af9a0ed0.nq.gz
    ├── 19674f8ea44e26e2c3669e68d2129d2c689a9df7.nq.gz
    ├── 1a47f2dfd3c6ff2619e89f8237445767e2551132.nq.gz
    ├── 1a5ee2885569fb94333e0076906905847237869f.nq.gz
    ├── 1a9c74eb7bf603febceb2134709739aa5c9d54a4.nq.gz
    ├── 1b55c22e264710f6892e3e0da625d5edaed86298.nq.gz
    ├── 1c4a732a852de66684e083b86a669c6170550c5a.nq.gz
    ├── 1ccc87edb1b05ba0509c8c75632046b665bd32ce.nq.gz
    ├── 1cfa85f57e4877a6115c831ea21aa32c78c59988.nq.gz
    ├── 1d6af92dd55ea58a4e1f515cd57174367b98461e.nq.gz
    ├── 1d716f8ed7d049851f31b78e0288520d0d58e67a.nq.gz
    ├── 1e388f0d7e793d481336ef18bb47b733cd6e62b8.nq.gz
    ├── 1e54677be0c0a02f41ea9f9b44ee8ef3c6585cba.nq.gz
    ├── 1f94dc09a8d53b7fa617ec5bb38f8f63215dfdce.nq.gz
    ├── 2132fdcaefad2034971b8475eb8b69076f5290c8.nq.gz
    ├── 21531c2a2c8b8ad07464f9f93c4251792ea18179.nq.gz
    ├── 2169a070dd18f7c1194fb35f990da4d3604b42f4.nq.gz
    ├── 219d7876b92b173cd92bf970fbf24e5ca9211c8e.nq.gz
    ├── 21cbe9a370d6e62a7b8fc91bc0697aab8b02fd29.nq.gz
    ├── 21e3d9e34432c2d87e17ee5a4fd2718eeeed5188.nq.gz
    ├── 2226a150fe67c8a1984f048d53049b8da07f23b8.nq.gz
    ├── 2243db5e28abf0248dcdd5a8821da89f36e3bd18.nq.gz
    ├── 22607c449e5289caea6fc00481c9ee22b20866e1.nq.gz
    ├── 22a0f08ef58142ddf281775657766b1ddc9d2d2e.nq.gz
    ├── 22aed37e650bbf933b6983cda9c2c5db65dcdd04.nq.gz
    ├── 22d3f2ee140fe67d546fa6616a916f1bd9c78048.nq.gz
    ├── 230b0aae8292537570735b18deb70b13ede142e8.nq.gz
    ├── 23a38c8523b8106b75996da501c8dd712e843248.nq.gz
    ├── 241752d0721a63b43380eb7aec7398d0f11d54df.nq.gz
    ├── 260035a2d0dc847cff37b2ea059fe20c69f8e670.nq.gz
    ├── 264af7cab71c3823818a1e59bea12ab68ee7d491.nq.gz
    ├── 26b0f2371f447351dc0d42d0560a3368d0cd4641.nq.gz
    ├── 279b803107ac92f6c5b98c4d3c2fad406f5c15bd.nq.gz
    ├── 28512a02ce9a462633696f654684928f3623dec4.nq.gz
    ├── 28e0cb851ba562f4d7eb32157ef8902551ddbbbf.nq.gz
    ├── 29d6c2f2a81719eeb9d58d15db511a16563b9531.nq.gz
    ├── 2aa206f458087ca93cf064a9a49a8d808f4050d0.nq.gz
    ├── 2aad26f2dbfd2ca1e6422e850f13ebf7470b0d73.nq.gz
    ├── 2ac53628f48b2b8295ae0f7a19291f877f401755.nq.gz
    ├── 2af6efe07934d0482f2cdaab7d147ccfc55d3605.nq.gz
    ├── 2b37965332f72483079fe0d4bfca32d2352881c6.nq.gz
    ├── 2b97be0a935bac26eac0da66ddbb852948e480e3.nq.gz
    ├── 2ca5518ac6cafa7d22cc23af8e24ea5d8f5f69fd.nq.gz
    ├── 2db96be04472c2dc1d7371fd65ebd1751b961bd1.nq.gz
    ├── 2e0bdd6270aaaf46cf017035c31b941bdda7c854.nq.gz
    ├── 2e4cbedd4d4add455a503eff4879d1ba9b683f20.nq.gz
    ├── 2e95a013b6c8850099b369b575091e1037734615.nq.gz
    ├── 2f39f353bff9d093e9249bdda412289ed926d2d9.nq.gz
    ├── 2f3e81b3bbe4eed738b0588735758cac4eb16650.nq.gz
    ├── 311f669dddc64b7665071ef1d7edd0e4f827aa81.nq.gz
    ├── 31483da587c37318d6eddbdd98b35261967d3580.nq.gz
    ├── 330b93a728e914f5e35d4f5aacd9893fc66bab6a.nq.gz
    ├── 337847855c3b59403bdbd32f538822bf7bc25fd1.nq.gz
    ├── 33c733c1092316bea175785d6af8a5392ff7e825.nq.gz
    ├── 33dd781f4d811d6030441e4a0753f94440a2f24d.nq.gz
    ├── 346db690d8538636160cad41c0d54758f13f2b7a.nq.gz
    ├── 34856fd32964ac1a8969902c5e72c10863becbe4.nq.gz
    ├── 35169abcf42a71e4f6abf18706aab14e9b7ab099.nq.gz
    ├── 358388454a5f8376093ccb0b222e9f6c4ce12487.nq.gz
    ├── 35c687b4c8eb6ebf11bce481e0978a8c6938471e.nq.gz
    ├── 35ce87a5822b043bf0b6c631e66b6dfbf975a1a4.nq.gz
    ├── 35fcd0ff9b04b78d02cd979e542a390f213f5db7.nq.gz
    ├── 365858dfc7ae340efed56640d5afc775317c3615.nq.gz
    ├── 3784c83e3f4aa46a5fae24e431b3b4c9bd0c9688.nq.gz
    ├── 37c62cc87b0f3087478291f627d9c30d25d4d214.nq.gz
    ├── 37f86481ef50947873c066609d703e5809a784d5.nq.gz
    ├── 37fcd76661d92e8613d96e6512c11aa140c57fbc.nq.gz
    ├── 382b4392ac46f54a06d6be38104fe825ea78d8fa.nq.gz
    ├── 38bb674b398f8db73f6bfb5f97177cdabac93c48.nq.gz
    ├── 3984ea02e67245b279fee3a99a35c42b082fd750.nq.gz
    ├── 3991d5b45ac327af2f36cc967bedd8153f5f346c.nq.gz
    ├── 3a709664b9bd852e745426674d5f2a7a820f745c.nq.gz
    ├── 3a85901c7529cc5dbef776497ea08fcf32433dab.nq.gz
    ├── 3ad23587e739ec975139327fbdd9db36f5068097.nq.gz
    ├── 3aeccd9ec7868e641067a5d38d5ec1a929c8d90d.nq.gz
    ├── 3aecde93d82a93dc3ba6d5a1c3efd7d707561ed9.nq.gz
    ├── 3b26c71c82cc9762b44059eb7f60bf722c32f310.nq.gz
    ├── 3ba2848f017e240be4cbeb4ddb4ae7aa764d2705.nq.gz
    ├── 3c508e0b0cdf423938baecc0458cf518962793d2.nq.gz
    ├── 3c5b0141057bc7b9b0424c77355909007dc0d647.nq.gz
    ├── 3cecfeeab314a035af14cd6c40219b8cadfb12f3.nq.gz
    ├── 3df0b84e2ba0294d97b8d3a870526469e5290ea9.nq.gz
    ├── 3e4fd4200108732fb7288db506b7fc8a42c03675.nq.gz
    ├── 3ebf230c9d215e1149e809297b0be254fc348827.nq.gz
    ├── 3f916ba613978a790d62d176083351bc8c840609.nq.gz
    ├── 4028cbb637921eee4491370da7cbdb6976112a02.nq.gz
    ├── 406e333b0cbe5cc243b36b41c748e0a2dfd67cb9.nq.gz
    ├── 40d1193dde3c7065dd36c0b6c3c2d7e99cbeb083.nq.gz
    ├── 40f399ae9392f1c895c8364c76767fd385d29eae.nq.gz
    ├── 41ce47e895336228be8d9b776b159a507171df08.nq.gz
    ├── 4430c63370742648b1b246ef30a61450349aa489.nq.gz
    ├── 4437307711d674beaa6f5586c421e5efc4ad4f75.nq.gz
    ├── 456cb5bad5a6aed89596702daba8eddfac33d89f.nq.gz
    ├── 458f069e623ebbd7e8727ce65a5404ab84aea153.nq.gz
    ├── 46762642f2adbf6297f716dfbbe8e1ce24aa3440.nq.gz
    ├── 468d735d4e5418fdc30496ad372d805921955559.nq.gz
    ├── 47de78e01a698f7be30ad7d992782feaedbe8b3b.nq.gz
    ├── 4831f45ce270e186249995315dd95abdfb518345.nq.gz
    ├── 48cce5e118ee6912eea36c32ac7a4ab26f8fdb0a.nq.gz
    ├── 48ee24813aafdd3b6ce68b59aebb34346c281d92.nq.gz
    ├── 4b165087c42a89f118fde7b27688bd9497ba2a98.nq.gz
    ├── 4b5e5f6dd727621b3467200644a65c07966bfef8.nq.gz
    ├── 4bd85936b65a411d52432b4594f95a281a4a13d7.nq.gz
    ├── 4c4b07979ee842fbc5e02586b21e0a127f41df52.nq.gz
    ├── 4de6112c96093f2149e2e938438111e42e22ace1.nq.gz
    ├── 4e5a7b3f4fb157a64d9278fec5761c33e0087992.nq.gz
    ├── 4edc08d7a505c2bb62f4996828bbed8aabd044b1.nq.gz
    ├── 4ee45e20caa52642aa1b0a3c5fb53778cad675e3.nq.gz
    ├── 50085cc0aaac6fed6966bd68f76f1ce158d38d5d.nq.gz
    ├── 500d4203978e23c69ff0999810d2d83f2fcc1ebc.nq.gz
    ├── 5032d5c72bd294c8803b4ea174671464e55470c6.nq.gz
    ├── 50692ca5d2c57674238ff4f48129eb1c37ee3617.nq.gz
    ├── 5089c69217d1b58416f9ec7bc3e0c1fc7e0cdfdd.nq.gz
    ├── 516fb4604c738ab5a83972b3f74ebae3bee32b4b.nq.gz
    ├── 52529d737b4c6d97cc63b8f5d23af0d02c62102a.nq.gz
    ├── 52c2b59748f6c4018713d687248be289a4628c12.nq.gz
    ├── 52d3b7dbb0d0ebf86c9ae6b45babc66ec2bc7eb9.nq.gz
    ├── 534fb5b7ffd49bfdcf81aadc48a854736ba7bec3.nq.gz
    ├── 53677855ec194d01278cfcf75a2453eea6ef56da.nq.gz
    ├── 53bd118926007fb7d043c685932ee7fb8712d615.nq.gz
    ├── 53cf75c6191eba9cc7571bfad269f58c0fe1bc57.nq.gz
    ├── 54ed3ab7ac44018b0275bf74354a46548ea8455d.nq.gz
    ├── 54edcbf5fc2697e26d7d8dede1b83f6525273d0c.nq.gz
    ├── 560595f184a427838c60c3e00bfee95ec02b232d.nq.gz
    ├── 562582fa2c4082c3dd2ec074125d469d19b11b7d.nq.gz
    ├── 56806deeee3bcc0bb22432e2dd5dd5fd808e59b7.nq.gz
    ├── 56a89122c50e5408cc02a510f49aa398aeb504d9.nq.gz
    ├── 5768b9e77e646b40ab9014d0d206b1880f7a6b52.nq.gz
    ├── 576c10de4cf0f87944af029b11f92c025ba08038.nq.gz
    ├── 57cbb0adc51da4175705ec6daba771e6e12d894b.nq.gz
    ├── 57d3d05d74cf211a35c050afc4b8d6058e0d813f.nq.gz
    ├── 57fba6b4f4e56fa22bbacf5443b5548200e44b5a.nq.gz
    ├── 58420e2b7296c2190f08b2ae2791fe2fb071f407.nq.gz
    ├── 587b09b5b14dc45416a51dd744ff8990dcacf63a.nq.gz
    ├── 58bcb5cd5edf9626856edf6b9dd995b4229e3dad.nq.gz
    ├── 58e741b55159cfcf07b8044a878b41582e0eae95.nq.gz
    ├── 5aab187036429fe7705691657302ed96d0970092.nq.gz
    ├── 5b877f28442af344f1e3c46d22570e09722a2869.nq.gz
    ├── 5baf47cc3d755e4de38299829e0d1e0c9baafb48.nq.gz
    ├── 5ce845f8a1a8179ecbf8fde2d6c438344ae6d66d.nq.gz
    ├── 5e0fcaa92755cd2c8d9dfb68b7ce56822d7e1cf3.nq.gz
    ├── 5e4878ef00fb1047523b806d327f12d2af9b61b3.nq.gz
    ├── 606b59e650920e41fccfc972da2cb98a41e18a89.nq.gz
    ├── 612ce46497654d3e4a81ca90755ff3a13420cfe0.nq.gz
    └── 61457ebb7e27368e2bf617299001727cc22c655e.nq.gz

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

[NousResearch/agent-governance-toolkit](https://github.com/NousResearch/agent-governance-toolkit)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*

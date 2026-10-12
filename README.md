# Repolex Knowledge Graph of django-ckeditor/django-ckeditor

RDF knowledge graph data for [django-ckeditor/django-ckeditor](https://github.com/django-ckeditor/django-ckeditor), parsed by [repolex](https://repolex.ai).

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
rlex download django-ckeditor/django-ckeditor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1a9c5a78ecbcc31d39271bd2bebf4a7912d3d5af
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1a9c5a78ecbcc31d39271bd2bebf4a7912d3d5af
│           └── chunk-001.nq.gz
└── blob
    ├── 00a35d43be092fe4bd252b3833687310b664dfb8.nq.gz
    ├── 0141ecd78eadd50db12e0c2c57faeb466e9a958d.nq.gz
    ├── 030790722d2d529bf37257d8fc5ad93793a21fd7.nq.gz
    ├── 038ca055178cc6840eeaf57b66fa0fba048abbde.nq.gz
    ├── 03b4ed3d63a9d6dc0ddac105a1145765bd218ed1.nq.gz
    ├── 04769877aa6d074e476f9560638d06cb158aaf1b.nq.gz
    ├── 06ab51aa48d86dd9d1baeaa6480e1804e0618454.nq.gz
    ├── 0721066b536d4f88784f441ba26c05a2478c774b.nq.gz
    ├── 078e38380aa4a6eb3247c2c68793c838ea919a14.nq.gz
    ├── 07a042172ec17d559d2bdb773b80076309c1ef1f.nq.gz
    ├── 07ebe956a08c56d0cfe48c317ea0e5c54ba4520a.nq.gz
    ├── 07ecb180f329609e065775d6fdc8ddcb5fa11090.nq.gz
    ├── 08142466cf769d60028e968e029e489b5bee42be.nq.gz
    ├── 0838fb8f982867a85a2c89c3fae286604e1bf65d.nq.gz
    ├── 0899886b5bc4e9a70cd44e9be33e90995697562c.nq.gz
    ├── 08c2cc24c84380be292242042554853ffc77ef8c.nq.gz
    ├── 092bf8f3ba6fbbfc61316f5a5d9f164ee218ceb7.nq.gz
    ├── 0959eb88cc3419d19bd82d9a857227060105ab94.nq.gz
    ├── 09d7a4ce2393f2d7a843d3b6f76e870eb3f630e6.nq.gz
    ├── 0a19d69d6192d720781fe3041f7d36bf16ea8f7a.nq.gz
    ├── 0b28d3d0f8210e0d5854a29bab06b0cb42bebf05.nq.gz
    ├── 0b50398886a824901c7ec2a9d45dfd22e4cc4bb4.nq.gz
    ├── 0b7abcec8aec3fc61ed2038fb90bc74b8bde31e8.nq.gz
    ├── 0b89722e315b05c5ad05f4c4dd4ef005b1029f78.nq.gz
    ├── 0bc6caa7a6abca57d3f1e1376fbd5067d5cd66d0.nq.gz
    ├── 0d03118a8cf33ebc75b24666fce6ca88821c5627.nq.gz
    ├── 0de19ff47ddf3993c854596621e84e8120dcc72a.nq.gz
    ├── 0e126f12230b0a0fcc0e9e5c93147eba0c8d15c8.nq.gz
    ├── 0e40959229497fc77627d91c76e2e24b13e09ecc.nq.gz
    ├── 0e420cba4af510c616dbfcad2b48acddc94da29f.nq.gz
    ├── 0eea82963f9d355086833219a5a798cca6d8465b.nq.gz
    ├── 0ef8b53898d8d49a56ed7356b85d81e2821dfdd0.nq.gz
    ├── 0faff6f5d63e42698b8e44a5640e206baa64bbb7.nq.gz
    ├── 117a2d4a4715551e735a14ac0a79d40c9affab8a.nq.gz
    ├── 11d84d4f0230cbaedc95b6e841ae4f6899c58587.nq.gz
    ├── 1266a7fdec5235ffcd93a0691779d19a88f470fb.nq.gz
    ├── 1322b2386de0348705ddd3eca99d1401def5c521.nq.gz
    ├── 132906c9075c236bcfa44acb459590cb0a32e4d9.nq.gz
    ├── 13d414a59bf37fded758be2d9d7c4216cce10dc5.nq.gz
    ├── 15d9b94a0541f912243a7fa5b245ff88ba6295d3.nq.gz
    ├── 16175cc1f893fb0bca30f16de228eab1bd8377a1.nq.gz
    ├── 17115180097dc450709d55a8267731b2711226fb.nq.gz
    ├── 1715619396694040aadefd4634dbfdfb08052ece.nq.gz
    ├── 182ea18bc45740903e7ff57ad115e11f6f06f2df.nq.gz
    ├── 186c3e916512175f0d6ab12d8eacfe9f320314db.nq.gz
    ├── 1877884379f1e37fe75e1e3924ce241725da1d3f.nq.gz
    ├── 18857fb7b54bb2abe5f4ef411fbb1c91b8d37650.nq.gz
    ├── 196c68dcc6d21c3da7886ca265669a6d76713043.nq.gz
    ├── 1aad4ac257a0398c34a86673321e2f45df3735b9.nq.gz
    ├── 1acfd0a81995ad10c8d4ab92d161fce3c8978703.nq.gz
    ├── 1bc04376c4fb5d74a163eb4ff8c00a07dff2e69f.nq.gz
    ├── 1c31c6056ee947822f64fe002042295469157ca8.nq.gz
    ├── 1d2d57674b9330704297a3c0beb679f2c4243326.nq.gz
    ├── 1dc6be152dd75fd77412f6f6d53c71a31a051b3b.nq.gz
    ├── 1f454578feed431ce35511bae7577ef888f62d77.nq.gz
    ├── 20b1be7b66a8b18c1ab1406fc57eabd3c000d331.nq.gz
    ├── 20eafc478cda18af2f22ef43800d0b7c5b9c90b7.nq.gz
    ├── 20f417a3ddab1393e09de3271571c986aaec4783.nq.gz
    ├── 20f5ae64ddbf1a8309e9d4524cd9a2d5b93e4f1d.nq.gz
    ├── 20f7e68dbdb9a634d7bea87cf318d8d88f44a91a.nq.gz
    ├── 21e3292e71aabc017076724637c34c8e211aa3d2.nq.gz
    ├── 2241ec6018481949e26e194e2242b9c3be19e348.nq.gz
    ├── 225dbf16283281bd44ccd36f8190068420f98681.nq.gz
    ├── 2278e8b400651223e3021ba10feaa8401f6c7a84.nq.gz
    ├── 22a9740ac428fabff434104bdb6bead928a0aa97.nq.gz
    ├── 23148f8e0793569f6c0bca2302edb8a938e01e87.nq.gz
    ├── 2323f5e9f864a127c5e8136ac999ccf2a489580b.nq.gz
    ├── 2325dcd1e5565a11d202020c779e7248d8a6f9cb.nq.gz
    ├── 234a5ce5cb3a985d6cb86a609a305a500a75f8d5.nq.gz
    ├── 2456ba750993eef8f9c9dc2e6035039ba0544d51.nq.gz
    ├── 24f0b98c017fb90198be33a01e5da26cef70e8ef.nq.gz
    ├── 2509224a58213b13e46db79bc2a5fd6a2f4c05a2.nq.gz
    ├── 25ad0f4a31906d0d7f13f55e2ed4e174aa365a48.nq.gz
    ├── 26335f6879fc87ae5fa8567dc351667e0ea80136.nq.gz
    ├── 26587e0347557c3b97ed9ecb3c2dcc2ceeb6fd73.nq.gz
    ├── 27043cb4d6accab906f34a2cd6053eedfde32d61.nq.gz
    ├── 275fa69603adeaa600892715f4f4e9d2e5a63387.nq.gz
    ├── 2840094d413b9c07d6b1255355c124bf9069b7dd.nq.gz
    ├── 287f0265ed759ba8333758b48a54559731abd719.nq.gz
    ├── 289d5dc35473ae9b20105888514056d097030896.nq.gz
    ├── 289ebfe9eb5c910ee45c505af561d8f783f6445e.nq.gz
    ├── 2929c6ccc2ba3694f67c853bc02ef6994d893724.nq.gz
    ├── 2a355a38f5e021da19f4f115e7c7504dd132421f.nq.gz
    ├── 2a622f225282d078af8c00a01e54e4cc5bf0767c.nq.gz
    ├── 2b8d1ab0a73977563b1e94d60482da33accae640.nq.gz
    ├── 2befc7f77a393818a71e6f50057dbe6bc1b90baa.nq.gz
    ├── 2c5ed3f3953029169d8a9ae3f99fb025d5d42671.nq.gz
    ├── 2c7ed973651d8ef8a1f5baee59dcc088f1c3a13f.nq.gz
    ├── 2ca000c7cee9444d7c97f48e06f96b5ae3a419e5.nq.gz
    ├── 2d0d8f584f9d2b2570a7a349c2151cf5f43a4200.nq.gz
    ├── 2d21633380adce8068766ac0dbf92ee988358036.nq.gz
    ├── 2d79369f7022506b24af27a619f58a8528e2cd36.nq.gz
    ├── 2e2d37ae9b84d4342e419c175f22d45d096e33f0.nq.gz
    ├── 2fec89c7e0d0a8538ab04d01e4659017f25b1831.nq.gz
    ├── 3072fe815e563bbe10bc2084b3ff03a8b6475c95.nq.gz
    ├── 3177355fe8a5e46fce327ebba5b1484af2584de9.nq.gz
    ├── 319bc08b255ca414e56a2c7a907da4cd13b6a0f0.nq.gz
    ├── 31ac46b5ea4a5ad3083b42d63c5a46a8b756b44e.nq.gz
    ├── 3209b92f7605ebee361f25ed3934b485c87d8929.nq.gz
    ├── 33cc89189ad6d7fb6731851839f9f608dbfecfe1.nq.gz
    ├── 33e87aba05e12922808b0cf2d856c88d33a9a51e.nq.gz
    ├── 33e8d43b2b4f45ed58c35b30364d531ab852bef8.nq.gz
    ├── 342729040362c26ea1a2ae1fff8784285d639696.nq.gz
    ├── 34a569140549da33cd2b9814c466f2bbd0265b20.nq.gz
    ├── 34cd4f9ea97a9e41415795bc2bc800c18934762f.nq.gz
    ├── 34f57912a5293e8dd5f6bd304dda72e439883d71.nq.gz
    ├── 36b04f23fc32e1b3e4cfe428ca35c3610653ef1b.nq.gz
    ├── 36cfff55a5feb4c8f3f4be535761ce50cd8b37ad.nq.gz
    ├── 371d4c4aa0609675dbf7f71cf6e822addce31be4.nq.gz
    ├── 37752d4e0faf65793e9465a713bd13c5b0edc6f5.nq.gz
    ├── 379804d5d8db9d05ca26cdd0ac2f3847c0d280c0.nq.gz
    ├── 3813903dbf9fa7b1fb5bd11d9534c06667d9056f.nq.gz
    ├── 3817844e2a3e372794ba365bc90504a8dfd7b8a7.nq.gz
    ├── 389f685a9280ed01a75a4333d4b3954fb096c2a4.nq.gz
    ├── 3908a6ae1ee7c13976b80bd93e26f10de1771c32.nq.gz
    ├── 3920c3626901bfcd8f841faa2aa7fffa4e187b70.nq.gz
    ├── 39850a4fd6fda096d2d45b577b9dad9cb2365c0b.nq.gz
    ├── 3ab4b74847aa2a2bb8f2845cbb49676b251af68e.nq.gz
    ├── 3b910cc2e2d4287ffecff85b31f4f3c801eacab1.nq.gz
    ├── 3ba389a6ee059fb60fda7a2fe36ed6e86c0c3a02.nq.gz
    ├── 3c2971b90907d31f3bcf76bdf29a9df39fb5af7c.nq.gz
    ├── 3dab755d15530c1b0407fe5df3952f66a1af62de.nq.gz
    ├── 3de3dadb95be18e3c88362dd7789760ed33c5d07.nq.gz
    ├── 3ea07243d4a5e8fa7b6706e013717282761210d6.nq.gz
    ├── 3ea92cd2eb946c67bce2302899f5aae11e1d35d9.nq.gz
    ├── 3f0999c5e62e807f7a790dda6a40fe132d4b5095.nq.gz
    ├── 4064597fb8e2a16441017a6780e617fcb606e553.nq.gz
    ├── 41841613847c3ea66f98e358dd0ef28a20152f1b.nq.gz
    ├── 41ebe9b1d7f33e89a80457a29e7c4924ef370c94.nq.gz
    ├── 421b42c886b749c2257752d60d1429331c6fadbd.nq.gz
    ├── 4231f20b8b6ffe8eacbafc5690738109d41f94ff.nq.gz
    ├── 424d13a05f23b5ea31493339d316ea73a3184e43.nq.gz
    ├── 428c5a6a8840bd9fabd512c7e1f4c34c8841f992.nq.gz
    ├── 42df5f411136270482f7af50e8553832e36b7769.nq.gz
    ├── 432c9bb4203bd175b2b25cdc67afee494d3e40ce.nq.gz
    ├── 43f3824d45b2d59eb11b90c7838cc3ac68b6f1d0.nq.gz
    ├── 452d1b947ceec75dc22be5cf018f8bb4a074d115.nq.gz
    ├── 462cde56c37da29943abb3d6286c6f17595b70df.nq.gz
    ├── 470ae6ee8d250e97c344ec7eec52254ddf6f62f3.nq.gz
    ├── 471dac0459a5e256d96bb6cd67bbed47e6fddbd0.nq.gz
    ├── 473a9f8d64395493a987e74bbe91f5af218e3369.nq.gz
    ├── 47d692d92e1e9f5f1ad05d1e74b2a3438ac8eb7b.nq.gz
    ├── 481af36c1f58bdc131e771746481ec996ce75b55.nq.gz
    ├── 48233daddb8e5d9383f791bf9138a3f7a0b27c8d.nq.gz
    ├── 4832c1f6ffd022ac1eb8f2131d8fd7742906f7aa.nq.gz
    ├── 48a8d2d77cc41dcb1608cf896b22622153389f17.nq.gz
    ├── 4948767f179c26e6d1f2b529736b5acf127732f6.nq.gz
    ├── 49e6192c28cd087a78c0fecd6edf7aabe458f677.nq.gz
    ├── 4bd4ac9fb9bff81bce743377fa36e0ca89a9785c.nq.gz
    ├── 4dfbb8bb1d581f8f13d52f3b8624e7bff575163b.nq.gz
    ├── 4e83249d341f907b6031ad0627f474c54b7576c7.nq.gz
    ├── 4f25550236effe9d11cd221ec6d33e545ca9ea87.nq.gz
    ├── 4fcb7c67846ecd26fa812dde386c2998fd856216.nq.gz
    ├── 5026d6cf8422bfec78e009891a73d791da02513f.nq.gz
    ├── 51292d39a8aa826f278927b4f78d9c1c5a1c3918.nq.gz
    ├── 514a6784be3170fbafdea43ceaf245e4934af68a.nq.gz
    ├── 519dd13f95ab45ca5a10f9d59caf6faf770c411c.nq.gz
    ├── 51d2d4dbe5961da7bf5cd72f11bc5b75fa63d04a.nq.gz
    ├── 52494e3413f181a4a8133232788a801ae1b92948.nq.gz
    ├── 524e0a2a8f2afbebe172320e8b00e4b8fb6a4833.nq.gz
    ├── 52de968cdbe84c22b621b254f7227c13253a4a9f.nq.gz
    ├── 540805bbf1e927ab71e0d51506ea10b0c644afe4.nq.gz
    ├── 5487327b7142df7b7b8457bec85ed028e62a9414.nq.gz
    ├── 548ac86467428dc9c9a67f5e90acc9b79727b6a9.nq.gz
    ├── 548f368bd1d222f8c2e2bac7e59ede6830544e4b.nq.gz
    ├── 54ceb58508657d6699a755c9b5d115e47bc708d7.nq.gz
    ├── 55b5b5f949a60c8fabc63867fd7827fe33d0ab71.nq.gz
    ├── 55efd00d18a93f6a553289ca81b725cc2d92679b.nq.gz
    ├── 56143cef78ea439ead30fc80fd257d5536c0375e.nq.gz
    ├── 56bbfd7f45fb2d44b47a57f0d7b780ef154517ff.nq.gz
    ├── 57271e59dcd4e73700eb3ee3f1617b13872021dc.nq.gz
    ├── 58a9f4c1328de5c5c9d05e61878e9860cd8a6399.nq.gz
    ├── 58f9dd6c7b15e421a49d8e380384a4ab8be9fd23.nq.gz
    ├── 5a782694d317b1ed23bfa5e8df5ea729bfde3ed5.nq.gz
    ├── 5a85bf593393240f68d32a8ff3f71e60a9f804ca.nq.gz
    ├── 5ab518c1aa127e09499fa048f8db6975dbf227a0.nq.gz
    ├── 5abdae127953d052a36ca481023730baf8e10461.nq.gz
    ├── 5b0a48a77287407e4cc64222c8f5dcd290a5ff65.nq.gz
    ├── 5b7a7681bfa4b30d880cd2431a1411d626f010e3.nq.gz
    ├── 5c8bee300d7fa70e68e5219a92da9f1bd3933f43.nq.gz
    ├── 5c9b429da4c92a2f52ae275b6720ae6775a145a4.nq.gz
    ├── 5cc49b68f1543d322f1cfd7e1db0b788ae5247c5.nq.gz
    ├── 5d307e0f03e1fe75d9fc4e57c1b4a079904a047c.nq.gz
    ├── 5e63785e42152e16329c5156f444b06f411f1c00.nq.gz
    ├── 5ef9b3dd5a9e24abad0326a0f26eb67a25303b5d.nq.gz
    ├── 5f282702bb03ef11d7184d19c80927b47f919764.nq.gz
    ├── 61014944e52670bbc95202b687b5f0425240e4dd.nq.gz
    ├── 61583f006396c81910adac409ef60d752f2e23be.nq.gz
    ├── 624acfc43bce81b07f1cb8416d5a18ce1e2f079b.nq.gz
    ├── 628325234f9a01f6dc444154bcc3c1a5c5228daf.nq.gz
    ├── 636814d98183bfffcdf1882583bfb3364a3bd659.nq.gz
    ├── 638b063cf8eb95cbda662dc7505b6b2bb349daed.nq.gz
    ├── 63a582024687b942afac422016a0ac37e3e9d827.nq.gz
    ├── 646292800df74199040d5e78bbfeb51a7eb9a81c.nq.gz
    ├── 65307e3d846877f5915ce0b8c3c246eb68aba4f4.nq.gz
    ├── 659a07060e8d8ce48d04d552c6d55eda01d4d75b.nq.gz
    ├── 65b630628711378fe4bb1b52bb01c622f28c87f8.nq.gz
    └── 65c47d611b9948526377d83452f99082bca7648b.nq.gz

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

[django-ckeditor/django-ckeditor](https://github.com/django-ckeditor/django-ckeditor)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*

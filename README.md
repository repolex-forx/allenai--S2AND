# Repolex Knowledge Graph of allenai/S2AND

RDF knowledge graph data for [allenai/S2AND](https://github.com/allenai/S2AND), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/S2AND
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fe0081df6647d9e4a66092693f272cbb946cae0d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fe0081df6647d9e4a66092693f272cbb946cae0d
│           └── chunk-001.nq.gz
└── blob
    ├── 01c0ff48999e09d1ad5dcba7da592f18dde8f2b2.nq.gz
    ├── 01f267c4f8205d92801f4099bac8d8c109c8f6dd.nq.gz
    ├── 03537fcbc954eb785146f5548cada6c53141cd0d.nq.gz
    ├── 03696550d14672af01ad0700315bcc35d33c3627.nq.gz
    ├── 043dc5562de643e558bb5ebdf2efff4a85319183.nq.gz
    ├── 063427a4996016c8ed025a25afc14d39df12cce5.nq.gz
    ├── 0705c974798a994326e16898f29923a949eb28a2.nq.gz
    ├── 0712ad95bfb2a13e2c2f1290ccb5aa59ebb6563b.nq.gz
    ├── 073a610cdaf1ea06a2546e7dab1fc4dff6261fd8.nq.gz
    ├── 086629c937c659bd44e54d0c7f16591557bf7afc.nq.gz
    ├── 08a27e7cd5850a6388b17dd7c48b68052a0644e5.nq.gz
    ├── 0a682b2d79d3ff7e329ddd76ef40dd3455c0bde6.nq.gz
    ├── 0b239a4a0601fd7dead3aaeb12060bc4c0ab7b9d.nq.gz
    ├── 0ba4fc0869f5dc2e8ca7bbfd07ae6474af85cb34.nq.gz
    ├── 0bbe19c68cdd864532b774e3e8992ad4788c7661.nq.gz
    ├── 0be37cda55805b7ec61fdc0b882d325891fd23b7.nq.gz
    ├── 0c66ec253a5c4faeab88103f3086dbaa0d8c5664.nq.gz
    ├── 0de51e607a01dd3e712682f75828842372900323.nq.gz
    ├── 0e1b98323de094e168f50bec6df25642c5da6319.nq.gz
    ├── 0e6a6a0f85c3fd8f90fca2eaee744a9379a3bb5f.nq.gz
    ├── 1282316faacbfd78d2e3e4d641d7d1e95b34eeb7.nq.gz
    ├── 1333d6b62146de49af78bb8d220ae950eaaa1cae.nq.gz
    ├── 13f665876e72da552fb633a5b8708be3ae95fc55.nq.gz
    ├── 13fd0f11f4cec5ce924d909ae41a31f4057c03c9.nq.gz
    ├── 14328a4fb7e69d5c156caca39c3ca3b4dbf765e3.nq.gz
    ├── 1505c0b5f0f1bdc8228354148844fec011c31ec7.nq.gz
    ├── 1657097bca4d3fb76a20fcececec0bbcc119b3d1.nq.gz
    ├── 1770441a78695f209e946a75051f24024cc44b3d.nq.gz
    ├── 17d6f9db8fa911e33009621176ed747c1bd6aab5.nq.gz
    ├── 19e29d43a68a0637522cb6ca046ae679525d649b.nq.gz
    ├── 1af1912306b7a2d0db1add504b9dc74aac5eecc7.nq.gz
    ├── 1af2a0f4c7383f2f6fd6ec7d9406111074de57a5.nq.gz
    ├── 1b28106c6f12c9a5119d22dd060b02aa68a35d68.nq.gz
    ├── 1c3a61253018db05498c0fef2b9bf4bdc51eec99.nq.gz
    ├── 1cc725ae8b8a1df44246a9b3470c5c79c36272ac.nq.gz
    ├── 1e1081f098b53198ca7db39d9118c064ccbea936.nq.gz
    ├── 1e6832b6506c9e5a9ed6215b2be4b5f1e98fcc4b.nq.gz
    ├── 213c7477e9e72bd3bff7cf3a646c544dd76f908c.nq.gz
    ├── 219085483798f3a494a44147ffa9f28ee74b0f0f.nq.gz
    ├── 2193b37c87f1e7a88ed46a656c8a33e1439f2c69.nq.gz
    ├── 2364f73d8bd47c0104094595ee67ab8f7418ffaf.nq.gz
    ├── 237c6499c287c878bde4bfca79fb8f20563cbeb0.nq.gz
    ├── 26a41b09db04e68bdbe11f33405c38f4e681f79b.nq.gz
    ├── 29966ed8d640be405de8f9b9bca36df0173268d3.nq.gz
    ├── 2a389a834ac1db02d6ee4ed380031a958d201837.nq.gz
    ├── 2a584d854d3fa141d7704202dc7046e6575fd2d8.nq.gz
    ├── 2ab9ac34a7f51c385941c7825c00ca02ee8fd6cd.nq.gz
    ├── 2c9703f8892627eeaa195e3abee3b11f5656f767.nq.gz
    ├── 2d51200004b19d12873976fdbaf8a327ad73e249.nq.gz
    ├── 2d52994014beb30f8ab54c9498ac0467d236be4c.nq.gz
    ├── 2d7c31631f55b78b8e74fc5ca91fb9a8500f8760.nq.gz
    ├── 315507bfa1ae22c0db41d487bddb793bf5b9eb7c.nq.gz
    ├── 31c992ada84735fc430a25767417a7d087c9882d.nq.gz
    ├── 33f2a2bf3409e9616b947639c50d5ed48c918e85.nq.gz
    ├── 34888037a3937b7c99bbbff8faf96e4cb51781e7.nq.gz
    ├── 3624e56ad108c222398241bd94ea0623ef0f3a2e.nq.gz
    ├── 36d88c6828d053bdfd7ed45d2dce42571a4d57b5.nq.gz
    ├── 3722b7f4c9ea0ce0720e7ff784c45c63ec819532.nq.gz
    ├── 37c54c0119b95175d04150273c7d994b1680b0fe.nq.gz
    ├── 38d8d8fdc637128fb108c7706e1241d9898971b7.nq.gz
    ├── 38deb8b2495d831122f80f4d44a5bdbbe30961ab.nq.gz
    ├── 3aa77590f2166e92634db19df96ab3dc732a8ced.nq.gz
    ├── 3b0c21acc3a085eeeb700b42509ba7ae1b437193.nq.gz
    ├── 3b15009501a8ef4c5ccc80b4c4b8fdcbfaba8a57.nq.gz
    ├── 3b71a250fc7c614bef4e7d0c5c642f361bd23c7f.nq.gz
    ├── 3cd3d3362e364ac049f958ca9786a1a6bc81d8eb.nq.gz
    ├── 3d179c9f693c231fd7e919ddd539cdf746b0209a.nq.gz
    ├── 3d421d890a5bec2157495dae436c2a04aef38f35.nq.gz
    ├── 3ede7905de04b491b4a1356bce2f8ed460fa86bc.nq.gz
    ├── 3f1635ec8db5804336987cef845d29ff78991013.nq.gz
    ├── 3f3f24f9d3c3918ff12cd6e4823d620482aacfda.nq.gz
    ├── 41008de81fcba3a38b0c8624f5d5203bdc24f84d.nq.gz
    ├── 41c791672d247dbb69c2c7512ace6e96fdf3b493.nq.gz
    ├── 4227be4db9c0cc4810e4c3a2a9bd3635d0cde2fa.nq.gz
    ├── 422a73d3737fc609d97bc4f4fafa6a224bac1c61.nq.gz
    ├── 431641bb5f36381c3cab365ec0be39bdcc4f8c07.nq.gz
    ├── 4322477b930a8dd48a22988ed14dcba83cae1c54.nq.gz
    ├── 43cacaf486c18212bcbbcd9b5d107beb2958b3e0.nq.gz
    ├── 43d1b2c5b8711dac69ac2c4e03db6b9d929d83f7.nq.gz
    ├── 441997b48456ef9fc2525f5c74af4d97e87bf77e.nq.gz
    ├── 441a0542ce715854ffe2be53d50ba7d49829caf0.nq.gz
    ├── 46eebb06e0118b13e9545ce234834194360b94da.nq.gz
    ├── 46fbe48240e76cb11cf350acd4d64a568599fc39.nq.gz
    ├── 47f7a2d967d5b52b4c2f162404afba264a91d944.nq.gz
    ├── 48a97246e2cd8424abeb3b7b592777b3f0414b47.nq.gz
    ├── 4993a644e37691d40b9ac1776e8f89279c566dc4.nq.gz
    ├── 4abc58391521f7992fe235a8b710ae13f8fceed7.nq.gz
    ├── 4b56ec3f5f58ddbbcb00fb1b6f68eec18c8bb0eb.nq.gz
    ├── 4b6aff6995dc469c7aa8177b821a6b8fde50f059.nq.gz
    ├── 4bd0a654b797502d053977b9d6bfc1d206866e54.nq.gz
    ├── 4cf7df2057579b0430d72a030b2ce6db0cf25e03.nq.gz
    ├── 4dace48b7b3f30c3118d6690182c9416616c9173.nq.gz
    ├── 4df85fd892a048c3d94ea682439e402617b69a94.nq.gz
    ├── 4e2b522bc4caceeec4ab799f98d21e47f192c14e.nq.gz
    ├── 4e2c3dc3412379b10b930c0bed871c103e57153a.nq.gz
    ├── 4e7501fbe357d22de1f9d4a9eede8ef8f4202e66.nq.gz
    ├── 4f6c0b3825f96e9b0478088f09a39369bec68795.nq.gz
    ├── 519399f442c295903ba359e4b47b6353a35353d9.nq.gz
    ├── 52d8ff7004720fc7c11069f39a0e18f88673b512.nq.gz
    ├── 53c8b6787820ea62bffc8954bb10ed9486ee8644.nq.gz
    ├── 53fb3c711153cf57472a8a60ec0e06aaad67cbb0.nq.gz
    ├── 540c751887046898e6c5a8b1da4bd83e6bd0565d.nq.gz
    ├── 54470168aa9e7e1004d430bb2a9f313a3c26c954.nq.gz
    ├── 55f4ce789d20f1a689d6078baebbfc8f747c0ca3.nq.gz
    ├── 57d4a6a033e3a3403c3ceef9087af7d209c489e6.nq.gz
    ├── 5817637f7f556a89dd4ed2fd7a0065bb2128048a.nq.gz
    ├── 5874b763f0a468cc7ea58265104186c08cd1c8e1.nq.gz
    ├── 58bdcf3d8c7ead2f2ccd4beae83191588b9632ed.nq.gz
    ├── 5ab10f38161482faffd9b074e1ebbf13866af88f.nq.gz
    ├── 5abdefb0a69b898945f31ef61bc29fee75ae9d85.nq.gz
    ├── 5abf8ed93f76109d8270e5d2e10f295745a21c61.nq.gz
    ├── 5ba4e18a296d2bfacb2d918b089389f76c2a0c33.nq.gz
    ├── 5c105bfbe91ebec08b57047275eb3b3cc6741267.nq.gz
    ├── 5cfc687f27a8961d06cb616fccd48b7c9a012be3.nq.gz
    ├── 5dae9c43f06c5039c8d0d26b1e11e37295cefd24.nq.gz
    ├── 5e0cf07aefbb0045583030544ef154c3e5ef424b.nq.gz
    ├── 5e64a9e187e08d409cd0a4935b5db2b1a3c2511d.nq.gz
    ├── 5ee09ae89b521a5ada6acfc0990913b0196300e5.nq.gz
    ├── 5eec7240b071e47597e7312b9920b305ff430f13.nq.gz
    ├── 5f26dc455231b6a363ef5a92ff94e5d00f0b42bb.nq.gz
    ├── 60e7c870d4c96d0a29ae6b1fc68d8899c8fb7dfb.nq.gz
    ├── 614a0fb921ba61a4bcc80ad4232b6a6a02798a3b.nq.gz
    ├── 61c41c3bf3228c6b665299af3ccd4d733957a3a0.nq.gz
    ├── 631791e065e7f17f635b5ac4811b2367dbe209ae.nq.gz
    ├── 6503fb8bd96174105e81efa4039795bd599a8ff0.nq.gz
    ├── 65706f810c54e1acca15610d99110e085263326c.nq.gz
    ├── 665c81c1ff3717fd367cb43dad46450ab6c95bb3.nq.gz
    ├── 66f4d7cc258eb1d4b9dc17f4b0e97dd0a2197523.nq.gz
    ├── 67aeddeaee111340b60910a860d9df1dfc5d9228.nq.gz
    ├── 6808a1a233ce72eef8be7403796f5ae26e974e5b.nq.gz
    ├── 69596438eddc3563874d6bc2111c1264e7b8254b.nq.gz
    ├── 69ac2e3017028c8be8fcbd06d4528855c12b93a1.nq.gz
    ├── 69adcd5c679010e3180b836494614c54b0b6eeee.nq.gz
    ├── 69f293381408d3e6418049aae595a7d5aff9ba34.nq.gz
    ├── 6a082e6218a92d70abac1a1b11796e9082ff209d.nq.gz
    ├── 6a108976139f54e0d3b3f4372d50c43bbec03e6d.nq.gz
    ├── 6a8872d11d968a96005fe3f57b171f3e6b91d4cc.nq.gz
    ├── 6a9133522b1d3fbe3e2a640322243e82cfce0985.nq.gz
    ├── 6abfe34d4a23141f66ec9a85da68cf5c3af82a5d.nq.gz
    ├── 6bd0fff923fa220314a67fe3ce7cc8b76701c3cd.nq.gz
    ├── 6cc28b6ab8b194d142aa6f20bedea798430ad784.nq.gz
    ├── 6d5f53a9f5ec160eb7e2ad9cc635377eedd9cd8b.nq.gz
    ├── 72218e5cc0c44dbe675ec429b2cb2823ceed8e5b.nq.gz
    ├── 726f909891ab62484cd9f93df2baa57e2e94c7a4.nq.gz
    ├── 73a5ba6d350118287bc5f095897353c24a3f80db.nq.gz
    ├── 73d9af800e569c9131d7a9ce51116a9d9d7e3dcc.nq.gz
    ├── 743968cd4d1d353868f5dd216450143bc9af9e48.nq.gz
    ├── 743ec4c6a4266fe19f2bb0cc92d076d9fb04aea6.nq.gz
    ├── 75f3c684fa7ee758304983abfef1f47a9af8d8b9.nq.gz
    ├── 75fc46025932ffa75c6b66dab193dc026103d90e.nq.gz
    ├── 76b71268941699bbbc498fde79badbae51b530aa.nq.gz
    ├── 76fad87140cb325ddff28a5bb130bbf9482cce0e.nq.gz
    ├── 77303dcc4183d13efb63681b346beffed2ee7597.nq.gz
    ├── 784e2b962fdde5f79d7f3f7c9cd417be0bb3ac8e.nq.gz
    ├── 78b66c180e286a5e54608f156e327d5b260de1df.nq.gz
    ├── 7a129a272354e3e911e124e2c0540d7b7eed7dc4.nq.gz
    ├── 7c0efec4110884c790c4aaf35ecdf54b724ec5e4.nq.gz
    ├── 7d8c01b1d2c14926c31b874d2bc32265d78112f0.nq.gz
    ├── 7dcaa48f2f5c3039dcf7922d078cc7d4b012c683.nq.gz
    ├── 7e05a6275fd69ca15340bccce0a6950186dad547.nq.gz
    ├── 7e0af438d7235a653f8cef5c2448f8f428b0d2a1.nq.gz
    ├── 81a24731cc386b0c01eb777cc09361d58ca29e9a.nq.gz
    ├── 83d1fc1bbfec979dab8d679d5f463ebedf7a8b22.nq.gz
    ├── 85f7a018400ae611947d9af4b2ef5ad211c1f414.nq.gz
    ├── 862a519ecbf88df9b524401929ff29004d237376.nq.gz
    ├── 8639833042f5a51c3937179ec333afccc0cb00a1.nq.gz
    ├── 87db9c403ae8d42a67bbbc262dff1d963f001cab.nq.gz
    ├── 882d1189e428e9507a1c11afc8b0ee9c656f72f9.nq.gz
    ├── 8950bbc6a2416b28ce3b758eb7ebe398d1ab534b.nq.gz
    ├── 8999f25ca5d8638eba608f34a3f14310cc0aaa99.nq.gz
    ├── 89c787926e85e10e69e1b524d59522a0ff09bcbf.nq.gz
    ├── 8aaded32d95d3a15093fdf3e77fa31004c6ffacf.nq.gz
    ├── 8c9ae61fd0b0b5141d9658a279902a0c54fc9bc2.nq.gz
    ├── 8d4e49480d1071f3c666ec13051e8b1793d8aadd.nq.gz
    ├── 8dec9c37ed7b8447d3a3ab7e994d8d382902fd60.nq.gz
    ├── 8dfbb094aaab4f738914d1455ca88bb4adf0b277.nq.gz
    ├── 8ecc73a3064fb7e01df39d905f570055c938bffb.nq.gz
    ├── 9099720b8f7eecbe25836f68eb22a86cac91d951.nq.gz
    ├── 91344d7df77f4d82a88ada287494594510dde8c2.nq.gz
    ├── 915fd80634ee155d7e98739b0a831e4abd77114d.nq.gz
    ├── 9161f4005dd7a49bf82f41889ea26f21b7ff4251.nq.gz
    ├── 9234094670a6bec46af5289e0220edd709795a47.nq.gz
    ├── 9281a4f1bcccd7c347b9c452d4618b45268c9a32.nq.gz
    ├── 928b18c1a104eedea30e43ad633e9c3860340d5e.nq.gz
    ├── 938f1ac17c779bf03f0be0034303add6b7b6909c.nq.gz
    ├── 93c2ed67c3c3b8b1f49bca5a567ad32cbbe55c33.nq.gz
    ├── 95b1ba1c2c7189d117fc5b36d7d5f994841acf2d.nq.gz
    ├── 96727d5eff82eab83f0302e7260a65e2d7d0e431.nq.gz
    ├── 969eb252497ceec1593a4b037de294d89fa0996e.nq.gz
    ├── 971d27ea1280156f3c0395beaac24a48f9d419ff.nq.gz
    ├── 979975b0be8831640d1164a1889f771f2619a344.nq.gz
    ├── 9883178a3d59de165e685fa5d450f02a4a8f1b88.nq.gz
    ├── 998cb542308c0ca852263abfbf695f7399b07b46.nq.gz
    ├── 9ac982c9630cc1fec23ec420ac2399a09396573e.nq.gz
    ├── 9b0577e39cb68f46def347273adb4602b7bf8612.nq.gz
    ├── 9b172b95b56c246f40da5d8c4229d5f4ccf8c208.nq.gz
    ├── 9b5146744b3a9f5a54557db385321a56d0573e4f.nq.gz
    └── 9b9466f97eea0c8d1e74654da5b0b59e157ab36f.nq.gz

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

[allenai/S2AND](https://github.com/allenai/S2AND)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*

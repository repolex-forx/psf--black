# Repolex Knowledge Graph of psf/black

RDF knowledge graph data for [psf/black](https://github.com/psf/black), parsed by [repolex](https://repolex.ai).

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
lexq download psf/black
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c6755bb741b6481d6b3d3bb563c83fa060db96c9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── c6755bb741b6481d6b3d3bb563c83fa060db96c9.nq.gz
│   └── repolex
│       └── c6755bb741b6481d6b3d3bb563c83fa060db96c9
│           └── chunk-001.nq.gz
└── blob
    ├── 005f20933ca6ae6bedf66f0c976876d69d0c073c.nq.gz
    ├── 01165f9c032a912a28bd3dfa9157f6d15c7d2e6d.nq.gz
    ├── 0189d4e642dd11abf00a53f47af75be4becffc4c.nq.gz
    ├── 020c4cea967ac387920c23c238b80e96d4902bee.nq.gz
    ├── 028832d772ab20059c945054874def4e7c786d9a.nq.gz
    ├── 0391d17a843f774d9f3c20323d550e2b4a183578.nq.gz
    ├── 06096c589f1791f9389f07b6ecef0f6b88299580.nq.gz
    ├── 065bf4328d7e68f9e3ab959479c249f653bf1b88.nq.gz
    ├── 06899029469cdb94189fcff66fa03fdefa622040.nq.gz
    ├── 073150c5f08a34dd60486a09d81a4d915acbc206.nq.gz
    ├── 0798d3f3b2971d2d8bf36589e773d2d8fc6273b4.nq.gz
    ├── 0856302624569c16cffacaf5baca022ad3919fca.nq.gz
    ├── 08dba3ffdf9b3eacc1c4410452bd631f06085384.nq.gz
    ├── 0a0d2e9967c7f34b9e929036c9887d2d370e67e6.nq.gz
    ├── 0a779fcee00f470b69eec84c52ee1f7073fb9eb1.nq.gz
    ├── 0aaa2d8e6702621d2dbd698a85012f7bf8a79c1b.nq.gz
    ├── 0acce4bed2b1aa8c6918dae35df6ae7a78e680c5.nq.gz
    ├── 0af0c29bbe9b35e8296b636babae52217d1d0059.nq.gz
    ├── 0b3e63c92f75e1a675bd63f4a73d5eee7cfd9e61.nq.gz
    ├── 0b754cdc0f0a2b1a2991c14c52d9595c4b7fc6a0.nq.gz
    ├── 0d21755db58e5b797c7d44a0b67bfe9d92964e2c.nq.gz
    ├── 0d28f9931081ba153cf34d2b8fd7da57fda802dd.nq.gz
    ├── 0d34650e0980fabfd2ed63cf52df37ce818219d9.nq.gz
    ├── 0d4ade348d6876d07b39c6956cb9c3a7d4646375.nq.gz
    ├── 0ed0e989123c37d597693d3521eebf840fc29e98.nq.gz
    ├── 0f8dfc6249857f6978df916f3a8111deb15168b6.nq.gz
    ├── 10662d8dc38a863ae838407f2326d059c9bc3ca6.nq.gz
    ├── 107bc2c506f7f53ecce60674ca01d5b401d97d18.nq.gz
    ├── 11c7fe1e3aa79b6d319b6bfede780b3fbc85704b.nq.gz
    ├── 1221139b6d818109d1d0c2ab3ff3ba1187cda6a0.nq.gz
    ├── 123342f575c961e1e2aa581cfc7dca1373025159.nq.gz
    ├── 124292d6d5481337e18b2cb5c34341f90b61c757.nq.gz
    ├── 12c820def390a61ad21df6f88de70af3daa1d7bf.nq.gz
    ├── 12e49180e415f8ea07e81fbc8d99e7eb16ce3e4a.nq.gz
    ├── 132c95bfe2a944733147f0cd0e16fdff67c6e8fa.nq.gz
    ├── 133c230a3a806c8cfb1bd86eb76ca3389dc1aec5.nq.gz
    ├── 13e517816d65fd63401228b0832c47dac07e854b.nq.gz
    ├── 150f68c80f52952b9c2bf25a4348084aee22b2d1.nq.gz
    ├── 158038bf960607aa048e6cde702c8a4ce6c0bb62.nq.gz
    ├── 16047255562fb880c963e4a9c6317048d1e62820.nq.gz
    ├── 165117cdcb495be4470d8cbe41bb4c584432380c.nq.gz
    ├── 16645a18baa25b65deb728300c91e44ae92a5c55.nq.gz
    ├── 16a55e4e03ea023be08860b1ffdc4e10a0f22ac1.nq.gz
    ├── 16ebea379bc85705f52b8149ceda64bf3aede657.nq.gz
    ├── 177f866be0a57476d2ad64f8166c2c00c82aec05.nq.gz
    ├── 1798b3955c667ca48fb2c27776a1485b978f9961.nq.gz
    ├── 18758da476b872302847e4c360d4cc1c8d85a4f7.nq.gz
    ├── 18e6321ec2bb22293dd27fe06a2ac746a635df7e.nq.gz
    ├── 1977396685c9214bd841879059dce7e61145c678.nq.gz
    ├── 19b810b530acb20f7cf790f2b902f717ef1d8c03.nq.gz
    ├── 1a0dd747d8ecc3e422cf47a150943b60ad24d692.nq.gz
    ├── 1aef8f16b5a8ef3c3f654e20a61863232cb21f7a.nq.gz
    ├── 1bb8bf6d7fd4c8d09aea89b47de20fb8bbb61626.nq.gz
    ├── 1bd4d5615be9f1764ffbcac0a23d4a4b41891d14.nq.gz
    ├── 1c5d58f16f23800574fa242d936cdf50f581338e.nq.gz
    ├── 1c86a49b6865610cd0b685076c66d195c107dc10.nq.gz
    ├── 1c8cdbb31adff2004e6fb189ef12decb1372140f.nq.gz
    ├── 1d5836fc0311b875cf0c8a468ad7213a72ab7e8d.nq.gz
    ├── 1ec7acdd7d69c41ba1dcd0405cd048d7c071c198.nq.gz
    ├── 1ef34af4f119977191ab61056bb1b6f037ec247c.nq.gz
    ├── 1f2d53437cb56201d84cc6fd78c9265fdcaa4eed.nq.gz
    ├── 217fc2b5bb29ecc0951fbd7fe751820a3a6bfa19.nq.gz
    ├── 21b0e1a1f5b89ac9ea6dbbb200aaae12988f0155.nq.gz
    ├── 22b5b94c0a46a78e9cc96c7444d902a05e16df71.nq.gz
    ├── 231cc84ccfad8a0a3f3416b0a0b523dd15969e97.nq.gz
    ├── 2326e95293af871e08d3643b29985b656df7fa8d.nq.gz
    ├── 257cc5642cb1a054f08cc83f2d943e56fd3ebe99.nq.gz
    ├── 25aa18b91afafcf2e4a70be9cfacf799d85da714.nq.gz
    ├── 261c5e9f0a07491cfe38bcbeec439602cfd7b05c.nq.gz
    ├── 28497e731bc0502161c5dac1c704acafeff5000e.nq.gz
    ├── 2987e7bb646d5d283f6fd130593dda8e2bfc8e51.nq.gz
    ├── 2992da88d9073144719d7abc7acbf811d25e0813.nq.gz
    ├── 2a194759a821ecb1b8529dc71cd5d6363a2e69d9.nq.gz
    ├── 2ac9d1fc77812840e05277dd7101794bb2712c2e.nq.gz
    ├── 2b0e1e8581c0c5e70be577ec0ed1af70734c1efb.nq.gz
    ├── 2c6c915f539071dd4e9e90fc93d056c9685706c9.nq.gz
    ├── 2d126a945e4a20d3a6715daf89935339eda9a9d8.nq.gz
    ├── 2dc02c8c50c870b083ea0bc0304f0f235fb2740f.nq.gz
    ├── 2e5ca2ede8c9ec1bd63ccc8813e9ad3ed30cd7a9.nq.gz
    ├── 2eaaeb479f8c7334e75468642c01fa25c5d92f9c.nq.gz
    ├── 2ec0728af821d2962905cf63c30e7d64946e0693.nq.gz
    ├── 2ed82d5588500f3fc8afb747a23faf369ee5a821.nq.gz
    ├── 2ee6ea2b6e99b5d168227f9803386e92f64f6c9d.nq.gz
    ├── 2f937cf54efdfbdd817444ed3b1b27e6728c05c0.nq.gz
    ├── 3030ee96d0ec0183e79ce665b581389b54701468.nq.gz
    ├── 3040de06fde3033ba333bca7934e8314c516a148.nq.gz
    ├── 30e6eb788b341cee7dd9ee711843bcd64ffd9aa4.nq.gz
    ├── 31c44b9fa90e897d8a208e8601c67e87262461d3.nq.gz
    ├── 322c5b7a51b07e74257a989d6668044f54988bce.nq.gz
    ├── 32a170a97d06a7770a808a67536460ca8e59e31c.nq.gz
    ├── 33135d08f1ad53bd87b857034e110d528b5f4d00.nq.gz
    ├── 33af6ab907f6375ccee7a157be4c1cef94b67023.nq.gz
    ├── 342259075247e9909c853e084909e0b6682c9b47.nq.gz
    ├── 3440696c3039191b1c4f74ad0c111b62b7882f8d.nq.gz
    ├── 3558b181b58fa576f6c92a0d0424480f35762e68.nq.gz
    ├── 374469977e441283f7e72a15bacb47f0bc12302b.nq.gz
    ├── 3775ab8ea7292ec06507fe288844b0e30dcc6d0a.nq.gz
    ├── 38b04158ddb70070110e5047aab88bb9009ea003.nq.gz
    ├── 38e9c2a9f47b99acbe8e710ddae9eb675a94797c.nq.gz
    ├── 3908e457a9ec11818b60c8a246f481d550841763.nq.gz
    ├── 39205ba9f7aae25cafd20b132920bcb676420a57.nq.gz
    ├── 3b48e318adeb90ca375cc302ef561a5c2c145137.nq.gz
    ├── 3ba70a63c40ed023dd7a91bd795e3e0a7d6df964.nq.gz
    ├── 3c460d9bd7993beaf44a85a52cb6e996285eb490.nq.gz
    ├── 3c7b6bb6c91d7de29e268d052acdc28a758454af.nq.gz
    ├── 3d0058dd554f13a664cdf58e2984168c7d744d8a.nq.gz
    ├── 3d1c91b77bf3c1d513588a3009603bb652b0ec2a.nq.gz
    ├── 3d2406a3c7829006948a75c5a1c3d391128fabdc.nq.gz
    ├── 40ca11e9330ab26bb1c7abf208ad688daf8d535a.nq.gz
    ├── 40caf30a9831ded54ce91b8d0d4932d07a9c517a.nq.gz
    ├── 43e94630047944826d41c1e29675713a5ea0bf27.nq.gz
    ├── 44a3c9a2946fe65762dc41f5697f3a48a99f6ff5.nq.gz
    ├── 450262d3cd1920989c907e313fc5480f4a92aeec.nq.gz
    ├── 4573ac5b3ac1477ab9f1893075b70e7f9bc053e2.nq.gz
    ├── 459e404ea4f347d3256027336de4e7db4c0aa5da.nq.gz
    ├── 45de882d02c079e9b8e84e424e25c9530a7e8f9f.nq.gz
    ├── 463be7e52d44ea3e68b28e213e7e459c391ca7c3.nq.gz
    ├── 4646e919735113de6a632e74e196882b6fb2e049.nq.gz
    ├── 468509723a66eea025b21fae315de6da31a38aba.nq.gz
    ├── 469b76f3284698f61441f5bab62b4fcb76225154.nq.gz
    ├── 47049501183d391e3419c279929a10bfa543f4d8.nq.gz
    ├── 4739fc5478ee6f85ecb3bf34a7e0de111f6b1d8a.nq.gz
    ├── 483fbe8c57d868c236373b9711d76e552379ec33.nq.gz
    ├── 4a0c76682fdccf45c323324b783f73eefc21bf09.nq.gz
    ├── 4b2ccc9e3a53eb0504a3c7e91f7bf48ad832266b.nq.gz
    ├── 4b4d45f0bffb5966e63225efb87a220bad9f8e0d.nq.gz
    ├── 4c03e432383c174127c803dea8076488a09a8daf.nq.gz
    ├── 4c134a9eea32d6563e8a7a7cc166e69dbb4dfb48.nq.gz
    ├── 4c9b70336e748ecc7c0384338ee7606b6496c95f.nq.gz
    ├── 4ca707965ad17ee268cabe1b353a35f5b19b2418.nq.gz
    ├── 4d7af3d077f26a2e352bf4ea6069534acffd92c4.nq.gz
    ├── 4e3761f3028a0324352ade4385f9053387304147.nq.gz
    ├── 4e3b024ed3c04c7f56dc8a2f2278c612bdb1ce2c.nq.gz
    ├── 4e3f91fd8b175e594381ebc2e14e4edc81d61184.nq.gz
    ├── 4ec6b8a01535a17d092a4ac0d255c43d8ec524d2.nq.gz
    ├── 4efce755c242c22e3792b242e7044841dd8e6e24.nq.gz
    ├── 4f82869312d52c1dc9db485fa9a97a995a422d80.nq.gz
    ├── 4fae7530eb98ab918766980229dc88320c83a8e0.nq.gz
    ├── 517535701f76a0e8efc93f3eccb000ad96a02d22.nq.gz
    ├── 560c9e27be28c11ec87853628fdf3cc239d06689.nq.gz
    ├── 5660b0f6a14de5ce40db50c133fdd8000a1181ad.nq.gz
    ├── 56972812896ace89487bb9a7f0d3cafc12c285f9.nq.gz
    ├── 56d99b8caf5c16b6f53f86e41f6014f5cf20d2ab.nq.gz
    ├── 5709b92b197b815931beb2f58154980b9b5da3ca.nq.gz
    ├── 573ae9c98e437ba0997c8d202f6839db12e1d8d8.nq.gz
    ├── 5751154f7f08e8a12d29b75f8ab8a3b2452d6c71.nq.gz
    ├── 58f28673022c0f7a47c7028a5eddc570cf26e2a9.nq.gz
    ├── 5aebbf46a83f1a371fd32edb971fcfb43047ae07.nq.gz
    ├── 5b09c6646062998e81b428b891e5cf83f0ee2226.nq.gz
    ├── 5bb36c26318cbd0b9992b55fd73da3485cf500c7.nq.gz
    ├── 5bcdb94196613581fdfa478054c74b25c14d2367.nq.gz
    ├── 5c9b47cf9803e44de6639b9f92ef58251a39345a.nq.gz
    ├── 5d280e4bb6431cc603b59a72cf8e0467ed9fb345.nq.gz
    ├── 5db12c9adf134e220e9da00d12afde1131a57805.nq.gz
    ├── 5e5ff52816857cb75a0c9f383536327c23eaf059.nq.gz
    ├── 60560309376351e79d53d505dd3f89b1745eae7b.nq.gz
    ├── 60f02861e4a885727ea188696b1b35b8f737a9d3.nq.gz
    ├── 61799b335113e7b1c94d7f476bf482c699c2452c.nq.gz
    ├── 619119279577a0a11bcb6c7384a4b006882ef33b.nq.gz
    ├── 61d8ae8d8eed669f9dd71270f93b63667850807f.nq.gz
    ├── 6226858a157b4dba40a478c42e890dd2a9a53dcd.nq.gz
    ├── 6335cf733964f4a23083282451f1ab2a119d3148.nq.gz
    ├── 63cf3999c2eb2e41df9a53e62535fa2ff080671e.nq.gz
    ├── 640ac4ddec97b8c5316ca33d52393aaa42d910f0.nq.gz
    ├── 6622e8afb7d3ffafd98a445564bc377134d5689d.nq.gz
    ├── 667f550b353aa571ef6bdc3fbabe8ef0168558a7.nq.gz
    ├── 66c347d99df7d62370a501cafd14312b94b8af68.nq.gz
    ├── 67623d2279be1bf7291e109c85b8972000de822b.nq.gz
    ├── 684316652116fb4acb4419dba1f23cb47812bc94.nq.gz
    ├── 687e13675524dacd768975914c755ca22fb9b45f.nq.gz
    ├── 6937df52f09868ca76a777c82b4885a0c7434c67.nq.gz
    ├── 6c398827115b755716fac0e8c1af8d29290de361.nq.gz
    ├── 6d60bdbb34d185dd63a79b1fcf579b8183ee78dc.nq.gz
    ├── 6d991c74f8f0ea81e8da274048e87102c3feb121.nq.gz
    ├── 6df81dd798ef97c721c0239195ac1f9ad864b0ae.nq.gz
    ├── 6dfb5445efec0308e323688bbf687562fd43a83d.nq.gz
    ├── 6e166888e21926ac6a7aea4801ff0b097ca7a213.nq.gz
    ├── 6ec088ac79b79a6f135ee53dcd575ac1e608e0c6.nq.gz
    ├── 6ec8bb454088d5707c7db4b61e223655c1f695db.nq.gz
    ├── 6f86988f0fbebecff4de2afa0a5b91f6bbd2d446.nq.gz
    ├── 6fa2000f0dedc93db0837093443e98376ac78025.nq.gz
    ├── 6fea860adf6aab2a3b5ec6ae61d954a07fe7c77d.nq.gz
    ├── 703e3c8fbdeb26ba74b80c5c0267c6913a467f34.nq.gz
    ├── 7135cfd187cd4c9fc4ad2cf0b731c153c512bcf8.nq.gz
    ├── 715641b1871b553344142ad5bbb7479ad55e549c.nq.gz
    ├── 719c2b5574564fd62f194b03973c03a4c2af30a5.nq.gz
    ├── 7212740fc42d7fbdf55419fdc571547471de0257.nq.gz
    ├── 72969b7b68a235b9b4e72193daf66a7a70e038a3.nq.gz
    ├── 733fcbebac05f7f049df9cecaa5a32d1df020f35.nq.gz
    ├── 734e2a3c752b6721c87b8cee10128b04bfce4cba.nq.gz
    ├── 735c6aa6d7adbc0dcf60414e7c15b0c2b27f0404.nq.gz
    ├── 73fbe44d42c2687bd97e4458463579cfa25658da.nq.gz
    ├── 745bc9e8b02545cfdb58f6d5259cc71857768f22.nq.gz
    ├── 74d43cd7eafba24b6c24b2b37bf03193c285571c.nq.gz
    ├── 75113771ae0a2de9f8c17c5f7512db45f49c4409.nq.gz
    ├── 75b8db4817538a82b3b807e9dd33650524572fef.nq.gz
    └── 76b18ffecb3c340dc1d2b6c3a341e92a7bab9cbf.nq.gz

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

[psf/black](https://github.com/psf/black)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*

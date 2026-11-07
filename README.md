# Repolex Knowledge Graph of huggingface/atif-scan

RDF knowledge graph data for [huggingface/atif-scan](https://github.com/huggingface/atif-scan), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/atif-scan
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 400cb9d7572bfd8baf11bd1669930fa015836fa0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 400cb9d7572bfd8baf11bd1669930fa015836fa0
│           └── chunk-001.nq.gz
└── blob
    ├── 002c237df895386a23ef29b9358a85595feefe4e.nq.gz
    ├── 00ef8ab16649644d613fd0939b066799aae16933.nq.gz
    ├── 01eb84be2a67058a14fb5fa79f60d627d90ef594.nq.gz
    ├── 02135c5697e36f2553a8b92b578c15866830a229.nq.gz
    ├── 021aa5c766f0ecf8eb88ea7d92dc158aac0722cf.nq.gz
    ├── 0231b7bf15ffc72b2c1dc80ef62b22ea8f3ef72c.nq.gz
    ├── 02c8bf0d8c35443868b5a58469bf71b635e43c44.nq.gz
    ├── 038c56dc412b256767086a8b620c4540f129020a.nq.gz
    ├── 04d600fe6a99d3fb3b01d60a878a9e635f7a5236.nq.gz
    ├── 0552d8377bfb71cabe23fc720bc9eaeaf0062984.nq.gz
    ├── 05dac43cd4f687171ed2abb4cb5027b88cf78f77.nq.gz
    ├── 06fef0c901e054ae7a8e3437e28d1cb9c6c8bf4f.nq.gz
    ├── 07b43bcfd5e33488749f7308d1dc4da26385519c.nq.gz
    ├── 07dbb23da2611bbdf8b473fc5d8be9ec3907a21d.nq.gz
    ├── 07e90dc966e761f39562c9411c1a2d423be8f0ac.nq.gz
    ├── 0800e1a3da23d13b6d4d21c55bf8fbdaf6a9e41c.nq.gz
    ├── 094503b202c96028c53b5a99a6cc5ce26cc63554.nq.gz
    ├── 0a6fa348de1b79a8f8f833c38d07e10eae5f78b0.nq.gz
    ├── 0b1759ab0c9b963ae687907a201f45e3cc3bca8f.nq.gz
    ├── 0b39b2cd81a65c0950e857b20423ca87cdfe93c8.nq.gz
    ├── 0b46e0695ea5b68b3bca5a9a077dd32f964de373.nq.gz
    ├── 0c3675ce23291af8f658676f75f77ef5fa64d7b0.nq.gz
    ├── 0c9c4be444146838a8f7d56f62b01f5956a68657.nq.gz
    ├── 0cb53499f561d76b73bc82955da6f6159604c32f.nq.gz
    ├── 0d74052d154398904dad9c672be2239aa3e0ed4e.nq.gz
    ├── 0eb2460768a58faf2cad14285775744c771b288f.nq.gz
    ├── 0f258f0eb221f25570e193c9b92837c09407c593.nq.gz
    ├── 0f63a0c893e09d295080f5386971cf68226201b1.nq.gz
    ├── 0faa7bc52b0c0b8719e9c467c80796df950392b5.nq.gz
    ├── 0fe98c9b26f65b4daf468e71975554a06ac8a9e1.nq.gz
    ├── 10224cd4412c8d91919594b005ca81f496022a2a.nq.gz
    ├── 107bde8b11573e6937be50a710147aac029cf0cd.nq.gz
    ├── 114d24204946cb95c90b22ae758bce5d30cd22c5.nq.gz
    ├── 12928c56e2c9020fa547e2f75e78d9954b3372e5.nq.gz
    ├── 12a822c6a36f3b40933e8ed1f104a0083b4d1bf4.nq.gz
    ├── 131c80e893a4a4c9b67866e8605045708e2b55a8.nq.gz
    ├── 1322f8607ab757c684f97c74b8d0a44e35ac279f.nq.gz
    ├── 134446badf46755940a8b6d6f8e916bad1a159bb.nq.gz
    ├── 146d8c4630b84d78fc78d3053ffc7aed48abe3d8.nq.gz
    ├── 14dfb9b9fe2df80d6b17f5cea28d5ec1bd361136.nq.gz
    ├── 15deddb788562f6959b810567ca04d2a304669fc.nq.gz
    ├── 15ff22afaefb1cff230bd4dfa9da8810a5e77138.nq.gz
    ├── 172fc7b1dddff7a849988d3bd2bac74ea3676fa7.nq.gz
    ├── 17599cba1ad1f05f28c41be446b38f685b5d0294.nq.gz
    ├── 180daa63127669dd3d63ed7e06f0f71f4133c249.nq.gz
    ├── 193301bac89078a4372c304141f86964b08a4992.nq.gz
    ├── 197f145bc32fc5b72e161f4c246946a98e1abeaf.nq.gz
    ├── 1b547f8d2ca8f4f3f81491eb428785c5efd0711b.nq.gz
    ├── 1c14e543f5789ff68ddbe0c666935dd35e50f0b5.nq.gz
    ├── 1c1c2f1034bcee307da4ed3ff6b6da441a0feb72.nq.gz
    ├── 1d4c8cf593ad66d05a0e6a7a790bce2951e05a43.nq.gz
    ├── 1e46c79559175523462b718397200d081a1d88ad.nq.gz
    ├── 1f8e9559c36b397c57ba6c2eca6c744c5000f7d0.nq.gz
    ├── 21458bac3f743b0d7e7a6fec4604380750a99081.nq.gz
    ├── 22b4de8a2e927be27f0ea1fe7f4ebe36aba333cf.nq.gz
    ├── 22b6c7f69c05831fd146b97e0ab4580fce816cee.nq.gz
    ├── 233fd4aa0bd507a2a2eedf5fdf37403b52c35cc1.nq.gz
    ├── 23720a3b6f77e69c962d250a9f65f07af1814d34.nq.gz
    ├── 25e0d6e39a721c3ba76ab1df387bf9bd24fbe86b.nq.gz
    ├── 26406a8d3017400e65a4b2a109c103c50e4d5b08.nq.gz
    ├── 267eadc6836a7d3a004b178213c4fc565a67d06d.nq.gz
    ├── 28609061fc8fbd8f31a84694048abc250613ac9a.nq.gz
    ├── 2927e94eddde8ef0ba1cad1f0bbbad31eb762de4.nq.gz
    ├── 29c520ab2fe8be33e766b4e8dd86d9d2987f97ab.nq.gz
    ├── 2adfb9beee8ca31bd1f4696379fb524feace5dc1.nq.gz
    ├── 2b5195c2df7d585e81730afe9e9b8ecbcf9a9733.nq.gz
    ├── 2bbeb26bfdb11c16c40c248c71d8e9ccb72e6f40.nq.gz
    ├── 2c1c7c52456a80d5a897c612ad8591caa6a79999.nq.gz
    ├── 2c221987719ee692599714b66b0a21405e870f45.nq.gz
    ├── 2cde38dda0b7a2cae779370ecb5f0eef51f736d2.nq.gz
    ├── 2dd37f3e0153b96aa1c9223e1aa50e6ef61f026a.nq.gz
    ├── 2fd9694fe6b975d040b5261775339dca4b4571f1.nq.gz
    ├── 31a5dc5ff7688314a221d50f0da4e4be6df6abe0.nq.gz
    ├── 3239190608b480f21640f1fa50b11fa50d71e312.nq.gz
    ├── 32de2ff4c0868b20aac122dc44bcb636c2d8d43a.nq.gz
    ├── 33aa1d33c7ff6756854187ed00129611430e4b81.nq.gz
    ├── 35d2370a3e0c366a98cea8ef9508a52504aab5d3.nq.gz
    ├── 36f854ae4a538bdb750d67b907e9b5efd6998691.nq.gz
    ├── 3830fa01a6313fc0264641b57884fb7b41059b24.nq.gz
    ├── 38516c399d82f1fd8fcf673269707ad3bfc26e74.nq.gz
    ├── 38bcc8ad141e05073c90c28971957bdba925d7c3.nq.gz
    ├── 38eeb6d7650d841ec1b465e32aa8655fb3d3869f.nq.gz
    ├── 3a968bded06a7262a2994c62d394cbcb9108005c.nq.gz
    ├── 3afc8d86dd8bc335fc54f23c696580984da30432.nq.gz
    ├── 3cabc8dfbe8a12c31223f5a50bc6beae9dc141e8.nq.gz
    ├── 3cb908e29544b8036ac0957999c9af9a5a773b3e.nq.gz
    ├── 3d7414256d4f707fb985267263b72372b9576726.nq.gz
    ├── 3e6573a56b727cf09b6e9d05485c49cff3b6e4a7.nq.gz
    ├── 3e85129ee1860126451ffbdcd318cdb2ce0dffe9.nq.gz
    ├── 3e95b719050df0be96da5d3a8bc40c769328777b.nq.gz
    ├── 3f01746257ca78487d48dfdcb66de41389b8f2be.nq.gz
    ├── 3fc0ceb3cf5810aed9beaac1a8ada3fbe3374e38.nq.gz
    ├── 4056b4b2e6e7dbf98823c20efa2031e67dbcb979.nq.gz
    ├── 40817b51e075eb462bebef7c3aca04486820dd76.nq.gz
    ├── 41bbaa8e247f6f7d6108edc70b09c4254d85b906.nq.gz
    ├── 41fca2a83e7d176351a41972e5b47e9d9e40727a.nq.gz
    ├── 4246dc76924633afa8f4385b73e144f1590c4f98.nq.gz
    ├── 42a963667a0aa3b35090c45e7e0882f07fbbd6e4.nq.gz
    ├── 42bb8e04379cfbb13601e205756098713463a596.nq.gz
    ├── 42ccba2418075d3a77d08f9da2439973d2b30f98.nq.gz
    ├── 42df5d253928664753e37b14b5b34b11f910854c.nq.gz
    ├── 445d64c3e99cd0320f06a1ca3a5b9837d6048f9d.nq.gz
    ├── 44aa015f27b8fe932f57fb3188dd553a26a16022.nq.gz
    ├── 44f419c9f5b1a1d983a3d6aad958a6d7caa9140b.nq.gz
    ├── 4593d7111c219b04a15cfef278ba60f0ee050c8d.nq.gz
    ├── 468c7c0d4aa7ed6e2cca9e906b2160663c0dc5d3.nq.gz
    ├── 46a99e8ab80c0eb80a4e7f0ba092bc20a770f949.nq.gz
    ├── 48128d6958ccfe221bec992f7c13e4b8dc6fa688.nq.gz
    ├── 486af4e4f689f2912b64576ee696a4e552eb0147.nq.gz
    ├── 49940b0123466c310479f9a171fb092234d6b44b.nq.gz
    ├── 49a8998d76dc4341faee73db388b73e24de6e0cd.nq.gz
    ├── 4b1e17c313af4f8248a8145839ca891a384d0ca6.nq.gz
    ├── 4b4298839467118f16fc7c9f1719f32b573327b2.nq.gz
    ├── 4bd6faf15e3e8d3f290b40c3784f83710e22628d.nq.gz
    ├── 4bd8f5d3b8cd8956a03a2e004cad504b58d5dcd3.nq.gz
    ├── 4cda1ba5efaf6c95a1d0ff0f2c00d80da1dfcf64.nq.gz
    ├── 4d01ff876fed6a691136c0f36ce0be4c14ccc0e0.nq.gz
    ├── 4d25521fd2ae0c1aa4b900d32b3bbc4040d4425c.nq.gz
    ├── 4d664b1d18d7f11b5aeec6b3e3a72cf4265dd6e8.nq.gz
    ├── 4fed318146414894f3359467d0ad479f1a4e2cc8.nq.gz
    ├── 505bbb9f6505768cd3bd3141aa3a63a1282b4951.nq.gz
    ├── 50cbd06273f71066e828195db4a2b8ed260281a1.nq.gz
    ├── 50d94e8be984a6fda7fe9c1940a67d362b5c1829.nq.gz
    ├── 50f99b39fd45ed9589d6f68415ea704835092189.nq.gz
    ├── 50faf343ca55756fc6a105ce8fb12ba9fcd5e103.nq.gz
    ├── 5119e802ea317b10189f43124676e0db052efb21.nq.gz
    ├── 51479f764e41193b84be0ffc0d9d38fce4078b60.nq.gz
    ├── 518778983df432146eddf9297f40b86bf5e1c5e0.nq.gz
    ├── 52255ab143269c1c4bda6ac3a876351e023f76a6.nq.gz
    ├── 524655ead1a189e388c483f35358c2c50fde04ee.nq.gz
    ├── 5286c5eb6deb7b11c9181012f8f64b3cb8729b89.nq.gz
    ├── 52899da4f3dbe6423ebd4b6fd2a3c6c5efb5763c.nq.gz
    ├── 5325b1450c34542b816a474c0ec7ca990f0f6812.nq.gz
    ├── 534f42000da3ad3a943d0cdc7975685f13bc2dfa.nq.gz
    ├── 535e2beb555cc578ee232525fdb8f11e8baedc31.nq.gz
    ├── 537812899283b9085bfb82c613a6f0e0f57b76dd.nq.gz
    ├── 541a3fb77d2536e0c51f46dbe5c0ed904e591df1.nq.gz
    ├── 548e979dc7792457e4adb1a2951b263e01aee2e5.nq.gz
    ├── 550d8fa230498ae0e6a0d4a6fd2a82926b03e0f2.nq.gz
    ├── 55af1dfa7799a86063113aba8d3b6dbf0002d3c0.nq.gz
    ├── 55ee323820b00d6d83b0a1656246c294382080dd.nq.gz
    ├── 56b4a22b44c4904fb4372a8adbaee93a3243d081.nq.gz
    ├── 57528ca96aaa44e739149397eb130b87364528e4.nq.gz
    ├── 57bd83252507e00409eea2cdcd45f0283427a826.nq.gz
    ├── 57d5b86b34fdc4d8aaec38ddd038184819a04a55.nq.gz
    ├── 57e56e290c85cc371d1ddb4c9458f330a9096e0d.nq.gz
    ├── 58852a234fdf4625eb3b3d148e8dcc8344c65084.nq.gz
    ├── 58caceaa8cbe26b1bb7ba483228c41ae99271752.nq.gz
    ├── 593e1463ed91120981c46c72281637416becad85.nq.gz
    ├── 59b62fa4ac2f8aa0e2cffb2d0ebc29edd4860d7d.nq.gz
    ├── 5a4449777bad6423e6dcebac1d8d1bd8dd785102.nq.gz
    ├── 5ae5b275f0d4ee784c9d73208a3890b2abd197f2.nq.gz
    ├── 5b17a975d2b37f9a2180a12c65520bb506d0533b.nq.gz
    ├── 5dcaa7e9bcddc5c604bd61751447998fddf7a09f.nq.gz
    ├── 5df1e5d4304048a5840e41b38196cb569571518e.nq.gz
    ├── 5e456ace495a19857b782807fe28b4a517dbc4c4.nq.gz
    ├── 5f038819a1d3db640f05646e691369e33cbe4f8b.nq.gz
    ├── 5f10d345b0bc3ea05a98320b5966b7675a8e4225.nq.gz
    ├── 5f6e552499b215c15a87edc7d898db349586fe27.nq.gz
    ├── 602d6ba8fda8524b0e2eda31c781559728c15270.nq.gz
    ├── 605567288160ff2c46e6d4654e9b9eae4fb5999e.nq.gz
    ├── 60c4b973a14e5980c53e23a7b68587d934bf5945.nq.gz
    ├── 617994824bc1420e17457aaf36a5d4903a2e6572.nq.gz
    ├── 61a2e2f2f6a1c00a2d41993d1c06a2421108eea3.nq.gz
    ├── 625ec9ed6f84a7fd30b628442c52fe8d7ff55473.nq.gz
    ├── 638986baac209e207c7957d453b14524469fa178.nq.gz
    ├── 644af298b73520f9ea86f8230063a60f286ab874.nq.gz
    ├── 64a5c756389d7f46b12796a7b1f7d3a3adcce5a1.nq.gz
    ├── 64de467c6d3b64c6404f3902faf0bb88fcaf20f1.nq.gz
    ├── 6565dca8ef6b2e1829f487b5fbf46578040002de.nq.gz
    ├── 66104eacd36d2a3aad930677452ede558c2546d9.nq.gz
    ├── 662e644164dbd6310038866719a65c0cf706e922.nq.gz
    ├── 664466dfd5384d80f91706b4eb8c6833c3a22e31.nq.gz
    ├── 66bb2bff6d4a446108e8c91ff47bf260668a145b.nq.gz
    ├── 66c3c3dcd0d5d37596930b8ae39dd307f3f891c8.nq.gz
    ├── 68ef7ed77f2b59b7d84a5bbcccac1f540ffdc759.nq.gz
    ├── 68f5273a69441a624acea298f15d120d7df81b13.nq.gz
    ├── 697ff9bee1c9b1b39f6a39b1fe9c9980548043cc.nq.gz
    ├── 69861d57ad6c36bb021a5906254e1331034ec470.nq.gz
    ├── 6992fd1d6e368eb3fdef56a1cc3b705d52790619.nq.gz
    ├── 69c2e8cfcff8ce40cb075aa962793205bfa456b3.nq.gz
    ├── 6a7b7a8981d2b350dbc8c9211c1716e616c8e5ab.nq.gz
    ├── 6b1154c97b916943e965133fb7e42e869d538dac.nq.gz
    ├── 6c304ca16e161013b8066040de13b0a15f9d63ee.nq.gz
    ├── 6ce846535f6f76457878a639326d93eeb39c5fb6.nq.gz
    ├── 6d1bb41f7fde9a299c2b116ffc503cce823a4f92.nq.gz
    ├── 6d746963c07134a76d9afac48cc3f47dbeb623e6.nq.gz
    ├── 6e56102f4c2b04ee7a21e3bbaf3fc996b0140b38.nq.gz
    ├── 6e82bab7d2469539f66506237552125e11d04f06.nq.gz
    ├── 6eb9bb32437787a0d4c104c978a6913320a52db5.nq.gz
    ├── 6f7839f80423c43971bdbe7cdd08bb896a150a68.nq.gz
    ├── 6f8500e31a95ab30578fac98fc25fff130e57784.nq.gz
    ├── 6feb36f52083ee6e8eb3cc7267321265898226ea.nq.gz
    ├── 71b958d485fb8b8155bb1171f72da119911a224c.nq.gz
    ├── 721e0de57fc36a137c3638a46b1c3819b59ad1e7.nq.gz
    ├── 7457a0c54ef6b4a1484881899ff1c348e4a56b2a.nq.gz
    ├── 7480d4bc18d2544c513a7bb68674a42422b4b978.nq.gz
    └── 74903a00c6cc6e9cefe373e280db1db0493a680b.nq.gz

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

[huggingface/atif-scan](https://github.com/huggingface/atif-scan)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*

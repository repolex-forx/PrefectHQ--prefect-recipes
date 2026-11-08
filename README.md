# Repolex Knowledge Graph of PrefectHQ/prefect-recipes

RDF knowledge graph data for [PrefectHQ/prefect-recipes](https://github.com/PrefectHQ/prefect-recipes), parsed by [repolex](https://repolex.ai).

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
rlex download PrefectHQ/prefect-recipes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ebc974b22430f8fceda609dd0d17663ab2008c01
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ebc974b22430f8fceda609dd0d17663ab2008c01
│           └── chunk-001.nq.gz
└── blob
    ├── 016a004fe529365f247e9cd78e1c4ef42f42ff30.nq.gz
    ├── 01bc9eb3f743ef59ffa84c43f845afd3a999916c.nq.gz
    ├── 0452c6c4d20670ebac44ed19644cea3fa7e9b1e0.nq.gz
    ├── 04a9eeffec71e85a1a8580ee1fd2d76e59b66ac6.nq.gz
    ├── 0544c42b17d5ed6a0fa0f84a56d7a9ca3bc85ff7.nq.gz
    ├── 060772439dc129b0d59ea2897d95a2f3aa07bb33.nq.gz
    ├── 08915f13c7cdaab4db750aeb4e9a43d514d3bca9.nq.gz
    ├── 0b1183d29bab189701cf5d169f2a761333683626.nq.gz
    ├── 0c3eb9a4a889b5f50a4b7e2529a66f24b9895a08.nq.gz
    ├── 0d26ac85fa11fad4fa402c8e51c76f0aa913bf69.nq.gz
    ├── 0dbcadc7965dbe01686033d94b203377eab45dd3.nq.gz
    ├── 0dceed629bc8a2213c93be57f1bcf762d5c40563.nq.gz
    ├── 0e8a0eb36f4ca2c939201c0d54b5d82a1ea34778.nq.gz
    ├── 102bedcec17d1b1c6990c3eebfdc25ef8d6f6010.nq.gz
    ├── 111b33b53f76c10f026365929df49ffe42847a10.nq.gz
    ├── 1287a4124d88fcf759913b89666ee9dc1c776488.nq.gz
    ├── 12d17e5af5efacd58e71aab903d5051e205f315e.nq.gz
    ├── 1301a026e13a644d066b4474f01f189ddd7233e2.nq.gz
    ├── 14d446b7adc57ed87c80e8226d203453016dde49.nq.gz
    ├── 15f0f12df21df8caaf502c3560ee66eeff32f582.nq.gz
    ├── 170dd702d5a5f991576ff696cd23aaab382dc2c7.nq.gz
    ├── 19fa025b0ef935f46714d929a7465044fbe54066.nq.gz
    ├── 1bec2cbb8b4475df448540c80d4237afd7ff487f.nq.gz
    ├── 1c2a02132ba6f58000c62a32efb3fd546bec957a.nq.gz
    ├── 1c500e01fcc12cc185466f4ce574f7725caa9666.nq.gz
    ├── 1f620b1d6d8d74e39f0cf8541e2e7d04a8a0b51d.nq.gz
    ├── 20a7c3305eb6c8d8466d47f1960db3e2541d1bce.nq.gz
    ├── 219898b2acfc2514fa248847d1c253bfd8ef0fe5.nq.gz
    ├── 2346058160c1b3145b462d8d05242ae513735c12.nq.gz
    ├── 2380cdc1226fef3ffa49f6087f58bb2454dcaa7d.nq.gz
    ├── 23e2de1d9146f5b9c77362c1a54b668d5970bbcc.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26e97be1672bce5a5d098c94563be2acf9da2b3e.nq.gz
    ├── 275a90899d35e8df5e74c458326049ac27c82e25.nq.gz
    ├── 280d9d9e3fcb7f73b7d8166426c45907498e6761.nq.gz
    ├── 2894fd17c67b029d17ea7ef17272ed31b4a2b730.nq.gz
    ├── 292ffe582397c752953cdd32e77d0e92a69260a2.nq.gz
    ├── 293ae8f8e9f7ed2b6781289546f9686b2d163539.nq.gz
    ├── 294284458765e44f9fcca381d4e81fd7d9d3ec22.nq.gz
    ├── 2ab8c33c8d2a4d899f30abb781109faa989e616a.nq.gz
    ├── 2c22e04ea98ed797543f08fbe4fafd7dca4ce488.nq.gz
    ├── 2f1298b55127cb41cc59238bafe44b6923944759.nq.gz
    ├── 30d51f097ae838d6ba1fdcbfec1fbc9744174ae2.nq.gz
    ├── 31370a5387f5e5a475e1f806c425f822646dfa0f.nq.gz
    ├── 327b62380e565268abec9075057dc7504074315c.nq.gz
    ├── 32e01d429d454e0b18e80b28437d29797893ce3f.nq.gz
    ├── 32e25b1d9cf78751fbe14c42efa5151605581223.nq.gz
    ├── 351b228b8001b0dee2662c3e65038ef78a036e41.nq.gz
    ├── 361426fbbcd8f9fac70da6339f4c55fe55f6cec9.nq.gz
    ├── 364fa6bc28dabb6d8aec931687691aa450f39428.nq.gz
    ├── 36bb74bb43604bf23e6c792211b0a23792700472.nq.gz
    ├── 36d896a582fec0287ddaf07790cb97823b2a0d28.nq.gz
    ├── 373cdc75fa19652f36970f55301256493001f5de.nq.gz
    ├── 381349cfda2bd5625c505b6e3f3a6586da07345d.nq.gz
    ├── 384741d51d7eefa8faf96368fb280459e0171c85.nq.gz
    ├── 38bdd8acd24b3d0971099c0a5835c568dfe26297.nq.gz
    ├── 39b0de1979d46b3025fa2142d26bed8f2c6b1d8d.nq.gz
    ├── 3b23de190b99b7aa29ca8d8438bf2d318f259dbb.nq.gz
    ├── 3b25e98b63e9a224b66c8242ff916bdf613d14d1.nq.gz
    ├── 3db0f1d2cb5c5a584867fb458da40845770359ee.nq.gz
    ├── 3e73a3699ae6f8338f37b61910bdfdb0753367e0.nq.gz
    ├── 3e8d360c0b0098d6a5209b5255737821d6b4b263.nq.gz
    ├── 3f2b1f9a734d8b25639e2a256d7b01412d975bf7.nq.gz
    ├── 3ffe30dc28c484c4b6bf869c86e14c3edd16a06f.nq.gz
    ├── 4032b16538e510839ed2c7e229e789b903dd5cd7.nq.gz
    ├── 40361637f264598dd3c7e8441b21c5b4cd0083b6.nq.gz
    ├── 41259511ba753cf52c09e471ca8ec05f4eb260c2.nq.gz
    ├── 426d9e3f6293a3263340d6de9c9057f700db407a.nq.gz
    ├── 42e8ea620e75b90baf85e25e75e53ee751f46563.nq.gz
    ├── 44a6d643401a4228a323471beaf83285dd814a68.nq.gz
    ├── 44c4c9390116b7403aeab040e4753c6b4d2d15d6.nq.gz
    ├── 45d8a776f72f053dda9e29a73d0ef9bb35e5b0ed.nq.gz
    ├── 46ab5f1b5c0ed5932df51207a4b8e1724ca2a47e.nq.gz
    ├── 470584a28dd84666df716d17853200ab8a05f3e7.nq.gz
    ├── 48361b37f593fb4675cae1adfd956a7df39e779c.nq.gz
    ├── 4a15212c5cc5fc713e83984d8164c514849a9445.nq.gz
    ├── 4c67c4c67e5a5ca8cf0b76dbc8c166df04fea6f3.nq.gz
    ├── 4ed38547b526804821d6f6b19ed36353375788b6.nq.gz
    ├── 4f0952f567d0f8759dd8e1acef64ed935c96b859.nq.gz
    ├── 4f68cbe590e8921c64452c503f71698b9ef8a4c4.nq.gz
    ├── 50ca61396fa83406b0467ec53ed9a20d1e05a652.nq.gz
    ├── 510a8aabbcd722e970c36433a08ed4d92de62cca.nq.gz
    ├── 521a3862e634208173a4b2d1d3bc975672108ce0.nq.gz
    ├── 52509c8d3dc7227e7618806fbbfc1e914fa2f6f0.nq.gz
    ├── 555fe18276578c613e2d9dd5fdfe46c6d25d20f5.nq.gz
    ├── 57309525f41c6159694b61476a3aee8349298117.nq.gz
    ├── 575687949c9427ca00fd36e986a38f0f376c017d.nq.gz
    ├── 5765600ecc34dfdf31c98ebd1ff57b3e44efbc01.nq.gz
    ├── 57ff8d3027f83cdc38038455723e8e27450c67f2.nq.gz
    ├── 589e538145a8282ca35da81da8449a5e83261949.nq.gz
    ├── 58ebbf0d1ce23f61376efa4f9b994b68e808c4e3.nq.gz
    ├── 5a3d0d878bee35c4be98f8026c27dfdf1cf5c1a4.nq.gz
    ├── 5a9357770a9ef7412396737c03429992bbc381f3.nq.gz
    ├── 5ad9dfc8d423e57744623bce331392c08ea01ae0.nq.gz
    ├── 5b1d63565616f7623c1f8598425b3a2bd7741bdc.nq.gz
    ├── 5d0ddd2e1fea838430947b3b510b348a1a2b9667.nq.gz
    ├── 5dd463af1101324cdb85b00dba9b997283290d78.nq.gz
    ├── 5e17bf50e02dbb50fcdb56f5044010a2ba8e9e97.nq.gz
    ├── 5f212719cebc509d987f4643ef2a2860fd2895f4.nq.gz
    ├── 6081d10ac70297f0df3ac4923d54265b3179cc9c.nq.gz
    ├── 615cb43d9d4ab50b62d2c540575be171c52c7eff.nq.gz
    ├── 6197a435d8b9878b16195f2defae70d66a8853bd.nq.gz
    ├── 6267ef3bc5fd768bc2adce15787f2b089262f090.nq.gz
    ├── 6276e085728492045a0ef2d2c89d1ae1881cb9d1.nq.gz
    ├── 63f6f74fd9e716aec5957f46b796bb8a1a7a138b.nq.gz
    ├── 65244565512ceb796ebffa48d80c0443b6c97e97.nq.gz
    ├── 679142d145a8ff331363d313c090a8a1f8557830.nq.gz
    ├── 67b7fa15fd60135f3670f09ae8a8ba844ce70af9.nq.gz
    ├── 685b5b39d36808fc5266b4391f40ef219eb84368.nq.gz
    ├── 69b6661961becd8c13826bbf2c63df3a66e2700f.nq.gz
    ├── 6a656a7254fbfc4b96c10f77b53f686b2cef91a2.nq.gz
    ├── 6c151e058c008a4b43bbff9ab4e96120bd4627f1.nq.gz
    ├── 6cde0283217d13247a26b13d2d098f718de22757.nq.gz
    ├── 6d2f8ecffefc6ae1207591c01a12cc565e594b74.nq.gz
    ├── 6e7f4703a6466e4d06f48862b0bf3b46aef174c9.nq.gz
    ├── 6f1a47db51e77926274d2f8a4fc337e9a7aaadfd.nq.gz
    ├── 6f5205428073b21707b45efcb79058962b51b335.nq.gz
    ├── 6f8853990d270fd9aa0eea1b4c87b83903cc83c6.nq.gz
    ├── 700cf7f4f657b7c42c679699d0005f97cec52f4b.nq.gz
    ├── 70c9eda76d6836becaa3fc2f04618ba58e1201d5.nq.gz
    ├── 70d326f2d990bb1be32085ee99435cd419aa0f67.nq.gz
    ├── 7170de2b240a2923eecb243bf9cafef73b857117.nq.gz
    ├── 71e58d333f8ca8354f168fe5135d529ce20fc606.nq.gz
    ├── 7358e9a182c8fb2f6f35ad81514f8a14355f4d39.nq.gz
    ├── 74d35d9ee6391facc8cfd0e724642de1b656d328.nq.gz
    ├── 74d76557ace5e1043c139e5e7b7d63c2ba38c4f7.nq.gz
    ├── 7501a5af9bf7792bd2d00e66c65d3a6f507f32ad.nq.gz
    ├── 75559c81340e79bfbd2e68f2369bd6a06aa0c7b8.nq.gz
    ├── 757d0bd19c250c5a90d6051458c536faaead94d8.nq.gz
    ├── 75913c54a5451bea1c8e7bc74f070bac9beb0a13.nq.gz
    ├── 76a92d30c7e1166b8babfa9a805b99714b8623ce.nq.gz
    ├── 7836b7aec7fa6ecc330c900c253048dfc943e733.nq.gz
    ├── 789e4b38a0a9f7de95977cb63160b062619b5294.nq.gz
    ├── 78ebbd68f7f79bff92da06e4f3a903fe188d4d68.nq.gz
    ├── 7a198b514bf24dfcf72923cb48838f4e6dd0ab05.nq.gz
    ├── 7b19083d980bdeeb3e839d2a506dc3fceb80efcd.nq.gz
    ├── 7bb5879f441731b8b236d9b730355d952c5582a6.nq.gz
    ├── 7bf606afa994df8ca6aa3700843a256f4f6c24be.nq.gz
    ├── 7cd80a44861bad83c56778f29f52e41a5d7dde6d.nq.gz
    ├── 7ce7d44d725af3b55ff2b964495219fcdddd1ce5.nq.gz
    ├── 7dab502fbfdbbca1213c16046a4a83727ad95719.nq.gz
    ├── 7e0aff5ab8097a11b93d12a0d204419224f52a5d.nq.gz
    ├── 815b11943320239fb78d5eb5a557e20c7c401909.nq.gz
    ├── 815f7b1880ce2bd79c1589f8ffc125d0507db8ea.nq.gz
    ├── 81693fa131b9cdd44be964352a5e721b1b594ec9.nq.gz
    ├── 83270213af8b8b6916dc14c532f9c03169feb283.nq.gz
    ├── 851aebde444172edb95d39446ccc4fe9a866f0aa.nq.gz
    ├── 852a93d16e12d12653d0dd5c0c2d2ae4ff4cab01.nq.gz
    ├── 879e791e5a53aedcbc9dc1f583031b98cac762e2.nq.gz
    ├── 87db3a7c435ada1522215448561219e2cc7d0622.nq.gz
    ├── 88025a8e95be8cce84ddb15cc8bf500efdb19389.nq.gz
    ├── 881a08631db577d86ff6881417c5bacb49489100.nq.gz
    ├── 88a18c94419bfa7bebbbbb7b2516dcda3a02f2cd.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8c46863d684a49fe8efd7c0a65251555369d570f.nq.gz
    ├── 8d884bc9e4d54b624b5fc7e25b0be3159913a7ce.nq.gz
    ├── 8df9e1a5c66a144313e86d477eb3de14d9e3a609.nq.gz
    ├── 8e6a3e254a56dc684ef16517ed07e2aea99d24e7.nq.gz
    ├── 8ef1ff1483884127f971027bbef2ce822c57c988.nq.gz
    ├── 8f3c89802a410390db08a8c9e956d9360502cc82.nq.gz
    ├── 8f50cb0c56396b75f4f66115cb367852c5ceb93c.nq.gz
    ├── 908c1a068b4e1d1897065edca46199f5bf533ec0.nq.gz
    ├── 90d8d72790408b025f868dbc6f733dc4524d38cb.nq.gz
    ├── 92040723abad3a7d76d3afc997e082335781a490.nq.gz
    ├── 95e0f2fcbbfb7509365d0b4d748834da8c0611b7.nq.gz
    ├── 960e80e164cfb65f13245a6914e76af7e91b33a4.nq.gz
    ├── 97073c7cfb6bec43ba8503567efc06268f0caa5b.nq.gz
    ├── 9a38de26fdbad5a7d2ef39d341364c25bbf4eaa3.nq.gz
    ├── 9b356c6492920c08e24bfeb72a6d4419ee26b386.nq.gz
    ├── 9b4aa83543e4bd5ab7cd213ed7cda854101a012b.nq.gz
    ├── 9bf37dfd8a064dfa41431e24cb84503eb02ff3d7.nq.gz
    ├── 9d15c8cb9d559c3f3ec4cf20df81f7a49c39611e.nq.gz
    ├── 9dbc374b7c5d5e64530f62a2c9663194b9d2b311.nq.gz
    ├── 9ebf157aba1dd6db4ac49f3635fd05ba4d4369a2.nq.gz
    ├── 9f9e6fd24b9eca1d15ab3cc482a42845932b1f2f.nq.gz
    ├── 9fe927272aadf8de39170dc5750c89e760819ec8.nq.gz
    ├── a216dd68f9aeae58dc04e14dcbba18373298d3a8.nq.gz
    ├── a2de87272757e1c2be6bb481f1ba606a352736aa.nq.gz
    ├── a3d437569e00171da3f374eb720e81469897a480.nq.gz
    ├── a4042cd6c7718d5642c077653d8cdfb94865d015.nq.gz
    ├── a4bdeb4d059aa8c9ff58a27088fce921f1b059d8.nq.gz
    ├── a4c0f29389333c663a5f9b1de5ea9e0af83d7abe.nq.gz
    ├── a4edef3012e0d6ba3f161858189ebf400573291f.nq.gz
    ├── a5885cf1ba846c41f0baca8694a9acce75a6ac88.nq.gz
    ├── a654dcb9474a783aa8cb0aee566e87d9ad185421.nq.gz
    ├── a7a6a0954e3f32de03079120f9b32fda36ac509a.nq.gz
    ├── a808cc21f7cc7805abb2bf30dbfc330c201f93e7.nq.gz
    ├── a8afa6aa3f0c6c8c1d2eac8ca4ca3543f3f6897b.nq.gz
    ├── a8b4b4100398f3cd8ec37cf9b091dc145ad45544.nq.gz
    ├── a8d8b281fe103f638cb874171325dd8c02513806.nq.gz
    ├── a8dd70d6721bfbc620b0fbdd0f7ec31e6d8e6438.nq.gz
    ├── a9c81770f0c9d4af9aab78c280b39b31965a1646.nq.gz
    ├── aa45faa0950b1f56c8f7b22e29e0036b73eb9abd.nq.gz
    ├── aa57e40ae82e7bfb198589065d3b3e46cda646cd.nq.gz
    ├── ad2da99a64843cfce1c70decbcc6123bfa9cbe8a.nq.gz
    ├── ad632859b39e7f691576652d0b93ad5ae65848cb.nq.gz
    ├── ad6668bcc57d3c90769e076ffc7c8cb996bcb1b2.nq.gz
    └── adee0ed1401653eb34858a3880efab98b0ff2c44.nq.gz

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

[PrefectHQ/prefect-recipes](https://github.com/PrefectHQ/prefect-recipes)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*

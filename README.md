# Repolex Knowledge Graph of ansible-collections/community.routeros

RDF knowledge graph data for [ansible-collections/community.routeros](https://github.com/ansible-collections/community.routeros), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.routeros
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 82fd0bbe8ae336290800d8d8a133c92927ae825d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 82fd0bbe8ae336290800d8d8a133c92927ae825d
│           └── chunk-001.nq.gz
├── blob
│   ├── 012065c8539f2bd3e61eecc74acf5a046956de40.nq.gz
│   ├── 06153f091ecc1eb5dec5ba00b3d5fc779560a0d2.nq.gz
│   ├── 062ac5aae2d35f0c212076ff3a67af7ff1f1c27e.nq.gz
│   ├── 06d515e491e7d0e17e7e04114859cf72ea85d4a6.nq.gz
│   ├── 0c68c843fd4613e7f9eda16c2269116fd0794dce.nq.gz
│   ├── 0ddec5bb60d838e90863b42966af4d77787f8f89.nq.gz
│   ├── 0ea34bc0dee4bbad01cffdf8485381e34ef69506.nq.gz
│   ├── 0f49fefe305a67de5c600ca5a83d11a395815e50.nq.gz
│   ├── 0fac95a8ab53c33605c950f1fb8c903bec129177.nq.gz
│   ├── 107fe125698754beed8efddf473a003bdc2a80d7.nq.gz
│   ├── 151f5c1f79bae9eed39649882ebd95caafc6b906.nq.gz
│   ├── 1ae4f5bcfd0833380cf37bfe790f9bd75781e780.nq.gz
│   ├── 1c7f5da453d89046d0ca527bcb5912512e489036.nq.gz
│   ├── 1d6cf8554ada641c9a963a6f986822bf4be2da9d.nq.gz
│   ├── 263c959095b098e251f09333fb851e4f68cefd9d.nq.gz
│   ├── 2a4e7d4338a6cd0de09e4c7c7f4df4fe638b51da.nq.gz
│   ├── 2e18ddcad262cf0779a243f361003cd0fd607e40.nq.gz
│   ├── 38590f2e4ec486212f404e5f1405e69f7ec27db8.nq.gz
│   ├── 3985d558101bc5def3c3b8ed57a5bf99628b9992.nq.gz
│   ├── 39b7120e9d5b865b7c4993efd88ce1c9b366971c.nq.gz
│   ├── 3b2f9ed6bc2ca64f4a0a83fabdea98babd4029be.nq.gz
│   ├── 3d2c2b13434a0e661b2a6a8ac52fe1cd0bd6d17d.nq.gz
│   ├── 3e54b736861307f3b6bb4037487638484c53cc54.nq.gz
│   ├── 3f806211e540ffdb490c3ebddfa617e1ac412501.nq.gz
│   ├── 3fc74ce2f3c7a922a7ff4abf53ad6244de425506.nq.gz
│   ├── 44234de7ca85f95241cf7492ffaa59b362fe6db7.nq.gz
│   ├── 44d67c671979290fc4264ce6280fe94f04441367.nq.gz
│   ├── 470d2b266e25ccd2ff3e879b9eb19f5f5864a2b6.nq.gz
│   ├── 477a15eba476a8978aeeafeed8939b49420e4234.nq.gz
│   ├── 4786da6c9dd32b6fb11ea23a5e283fee4b828c8f.nq.gz
│   ├── 479f2fc6f44ddcf5a07cb7ca5f065c14a596285d.nq.gz
│   ├── 4b70989712e2453dd747d4568e9e6574e8ad15be.nq.gz
│   ├── 4be7f4d8f7bb59dca4381ff55f3fea45e295dc64.nq.gz
│   ├── 50c92fb673d25cf1055004cac03dc4cfd5befc5b.nq.gz
│   ├── 545acac84ef9fc8fef3f7faea6fcb7d6a9d43c11.nq.gz
│   ├── 559c301534db0666d75a14dded17de1ccb7cf7d2.nq.gz
│   ├── 5611277081c144f6c3bb5051bff6a408389d1d05.nq.gz
│   ├── 56c8cfbcab8e5a2fcf85921a2bb5ad9cde5ecee7.nq.gz
│   ├── 5b0b411ca8ea796fa7231288da324f57d9596f38.nq.gz
│   ├── 5ee7812edbb236187b2434d8d01342f71c10b922.nq.gz
│   ├── 609159123b881588f13e41ac35bc47f946e77596.nq.gz
│   ├── 63135a1a1bd20093f9efe0dc8491ace15ef78b67.nq.gz
│   ├── 63bc3beba59e1e09dae49c3eaaf704b18986adc3.nq.gz
│   ├── 65e5bca47b91276a4607b198bb6fb52f8374bcaa.nq.gz
│   ├── 6810e04e32878215c32b2039277d4b1809f4de4a.nq.gz
│   ├── 6b1155a69a7a6a772ef21bc785ba99ac659400f7.nq.gz
│   ├── 6c2e558efd1f91463a1591a78805a78a48ee9eec.nq.gz
│   ├── 6d29d507cceb56328c43a54412cb13251be418be.nq.gz
│   ├── 71d12fce7618023441ab129e69f21d57efae4f6f.nq.gz
│   ├── 728531beef0690ae462387f1a8fb019f7683025e.nq.gz
│   ├── 737b39847337207d114f990719256dc8474e0d2e.nq.gz
│   ├── 78910caac29da485c41997da121f291149b57261.nq.gz
│   ├── 79353f791fa2c1b56e8cd9ec6a4af804ccdc7161.nq.gz
│   ├── 7b019f94da45b7895e89bfd96fbc0d285c8c41d3.nq.gz
│   ├── 7b7c5b1aaaf0424ff6799738d75d219eeba3ad57.nq.gz
│   ├── 7ba9300954e0a11c533269fe7c6aa0cfb90ece2f.nq.gz
│   ├── 7c71952c78e59f69fd88752f7dcf53d385aa2b0c.nq.gz
│   ├── 7e24c0f905b967f7faac72238d593a6b40dbb36c.nq.gz
│   ├── 8a3956169cc230481f7aa63254ce92911c8df14c.nq.gz
│   ├── 8c560e2a41c992447f429ccb26d6d6b542fffe1d.nq.gz
│   ├── 8cf0be62e573c0e63683dc5ed60d3f2d120791c7.nq.gz
│   ├── 906dfb750244c79449be666aff7043a87cd6fcc4.nq.gz
│   ├── 918f378e6c0040c312c2dd3749a4909430dff191.nq.gz
│   ├── 9623a78f4b5804bc9447906a4090c5dda7a8cda5.nq.gz
│   ├── 96404663356b3e66792bf6c4edbe1f2fa1b2c7c0.nq.gz
│   ├── 9733153ea65f9a16ea944538feed01cdd3ef8af2.nq.gz
│   ├── 9a0382549d53525f1a5c18974e294068e6e1084c.nq.gz
│   ├── 9ccddb292fd06ed028fe7a696561b3594d7e4e17.nq.gz
│   ├── 9df17fc00e82a1b3f69f31ed38b47dfc816d6a41.nq.gz
│   ├── a069e5e1198ac2f8c182b56eb6afe95a5595b9c2.nq.gz
│   ├── a36140cc1813718c65efe89ac608dc97b1584b29.nq.gz
│   ├── a6707e291cd008e31aaa116fd8e4a8e7f9411bd7.nq.gz
│   ├── aa3aa2e82b1a64ade8fb1ed7eac76840e697b7f3.nq.gz
│   ├── aae1259ac33f9c7b3502d257efdc9162185d2919.nq.gz
│   ├── ac1f65b550fd13b42022a57bff565b263215710b.nq.gz
│   ├── ac7ebac8af95dbb36c9bbee8cbf20c9d14ad197a.nq.gz
│   ├── b1c04538219966ecce061396f20ce55a121ba8e0.nq.gz
│   ├── b34de108934c5f1022119e56799b12a5ad7351be.nq.gz
│   ├── b4da246cdfddb8679e11cc40188f39854b7be5aa.nq.gz
│   ├── b8e68bff440f437d32ef7445cdbb288295bf4e71.nq.gz
│   ├── c18e9ea573c4dd1a44d2c2b12707a6f9dab3e53c.nq.gz
│   ├── c2bd09c75a072dbc41cc336ba48c6b0f4b56611c.nq.gz
│   ├── c8bf5ed41e93543386b3d42a00dfd68cdc06236f.nq.gz
│   ├── cb4ba884741dbb90d5626ec8141af54313a1a1f9.nq.gz
│   ├── cbcd2371cc7e5fdb7ec5273119d330282d53a3c5.nq.gz
│   ├── cc3028c3efd285007dd30475dde8e6a17488daa9.nq.gz
│   ├── d1ac491409950ff629bdeb80b814a5b1ce13e577.nq.gz
│   ├── d3c2c3c0954eed957b1f15c0fcab805e67605e38.nq.gz
│   ├── d4fd2bcd24b6086d2f76f6291fa47566c0cfd158.nq.gz
│   ├── d683b252cd0ffc24f5c491f89e2c6e3f2c3bca6e.nq.gz
│   ├── d7dc3ff3eedc93a56a42f378d049b080461441d0.nq.gz
│   ├── dc2f4a9a48a8b71fee65d9c12ae047f2cf969a91.nq.gz
│   ├── ddba818182d2a835cc929e084d0052744e3ce88c.nq.gz
│   ├── de8947d74e8be1ce7f67166e509629b0ff7e9850.nq.gz
│   ├── e416cb5184cdb30b32ae0a7a7bf48b3820e3733c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── edff8c7685d5f4817c24b0ac7a99e0826bd2cf18.nq.gz
│   ├── f25d739faa915825aefbb99a6ca47b8a3b3f386d.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f64fa6d00ecdca6f192ad0e8fef6d46debbc67f9.nq.gz
│   ├── f71b322d2aabd560774185ebb7c3fec99c47ef3e.nq.gz
│   ├── ff151d3a8ce2752c9c48f3654d3b3130efa08fc2.nq.gz
│   └── ff95bb8217b6b64162a2911f958f8c367bebec4c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 82fd0bbe8ae336290800d8d8a133c92927ae825d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 111 files
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

[ansible-collections/community.routeros](https://github.com/ansible-collections/community.routeros)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*

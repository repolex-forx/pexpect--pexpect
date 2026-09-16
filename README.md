# Repolex Knowledge Graph of pexpect/pexpect

RDF knowledge graph data for [pexpect/pexpect](https://github.com/pexpect/pexpect), parsed by [repolex](https://repolex.ai).

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
lexq download pexpect/pexpect
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── aa989594e1e413f45c18b26ded1783f7d5990fe5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── aa989594e1e413f45c18b26ded1783f7d5990fe5.nq.gz
│   └── repolex
│       └── aa989594e1e413f45c18b26ded1783f7d5990fe5
│           └── chunk-001.nq.gz
├── blob
│   ├── 01d89a0923329b18be46e9677cd9cff31b6de182.nq.gz
│   ├── 05027a0e22dacc83b1e1d48245dc829750073dea.nq.gz
│   ├── 06b6ce6ed2faed30487edba47fa6e2702a25c460.nq.gz
│   ├── 0813d349ee9a4dd73178ff0088848f5b5ebdfb62.nq.gz
│   ├── 08dbd5e8692fa812821a1204c0a5675c5fd4c8df.nq.gz
│   ├── 0a7d5f89ca86b60594450b3f6cb764b8110ed8ff.nq.gz
│   ├── 0d34b0390419ec859daf024767958ceb0e766249.nq.gz
│   ├── 11fb55cdcf6ead63cee7f41034163f161b809530.nq.gz
│   ├── 1288397acbb3cd2c7e5641b0cdc729fdfe7d4cca.nq.gz
│   ├── 140bdfeeda6992acf01dae8bf2d058ac84fc8647.nq.gz
│   ├── 15d0c40b2597673d88ff0b38a65af87e7e7917da.nq.gz
│   ├── 1964b12002ae23135c088d833bf20fd46fd75e61.nq.gz
│   ├── 1b4d717218af52bc600ccecb1f782309dc90f48a.nq.gz
│   ├── 1cd2e90e7ab0c54430801b53d84ef9bb8d749485.nq.gz
│   ├── 1e4dba687df79bbd17ebb809a63da86680657a0a.nq.gz
│   ├── 22cd4785f715dc1e3d3d344578ef29921e7c4995.nq.gz
│   ├── 261720c16069e89411b1511eeba53f1068c3c913.nq.gz
│   ├── 273220aced46b579f3d38c1c453ed2048a5531ab.nq.gz
│   ├── 2af04bbf8df189fdae6be941a8789ad052ad7dc3.nq.gz
│   ├── 2e32241b7b71c3f28c040f9910b766f2a6becdde.nq.gz
│   ├── 32c72ba17124861c59dfb577f26b4ade2b3b1540.nq.gz
│   ├── 3425fd2110e370ff711aef440fa7090a8d1febe3.nq.gz
│   ├── 35d4816d38c0dedb1563e4c0fd4c8fab04147c2b.nq.gz
│   ├── 377563228118e74bf2644cb959bab83becf1c7db.nq.gz
│   ├── 3b2b6ec35817a1ebfcf76d481be4d98b10022b31.nq.gz
│   ├── 3bea1f9cba96e0701ec64fb3a273e377b6d66d93.nq.gz
│   ├── 3c8055357df996da096f02cfcb0b672cd78a74a5.nq.gz
│   ├── 3ddf2cdb228676b175d0053cab249d07f3634e7c.nq.gz
│   ├── 3f9d954660c3969aafe6ec34812ae1fed3a57ca0.nq.gz
│   ├── 448f1470824c22b0ff80ad6ad0faadc6d20a529e.nq.gz
│   ├── 44c15e1da952b12e74511e2924e6289f9abd8efe.nq.gz
│   ├── 44c58c52e3c806073c82f7c9afe90abfca12f6b5.nq.gz
│   ├── 454246ef24a735da0327dd6cbba28edd912565d3.nq.gz
│   ├── 46b392ea08aaf53577b27c0552776ecc86d72510.nq.gz
│   ├── 50937a30fc4fb930ce32715e09936cf04a4d669c.nq.gz
│   ├── 5695ab7f7b4811dffdddadf6e2310a9879f8817c.nq.gz
│   ├── 57d8667eb91e551426103bd3f25d3bd0678d7036.nq.gz
│   ├── 587b8adde7969d54a76e7d55126f31364bfaa090.nq.gz
│   ├── 59cb1ef13d5041ddf24398891db9fa41c2ad63d2.nq.gz
│   ├── 5be733c710f9b48aeb91b6d9c101c64d19166cda.nq.gz
│   ├── 5c81f92cad6edf1918e7241ae9ee6d49b7013fc7.nq.gz
│   ├── 5ecc1c21be01cdd120c9f0e2b0a838efdfae1db4.nq.gz
│   ├── 602b458af16bd1ce5bf3a3cd4a94d971c60c870d.nq.gz
│   ├── 6168148065fca7d9392c31abbf18639f7938d913.nq.gz
│   ├── 64cae1561ea9119ba47d6b17dccf2b194e4831bd.nq.gz
│   ├── 6538677075ac1a655d33e454ad4f83c0fddbef08.nq.gz
│   ├── 65f965b505d0365027bad23f679087c7d7fde0d7.nq.gz
│   ├── 6839a2f705338aba8464a402527e0f416a1837e9.nq.gz
│   ├── 68c5fc26d662d23dfe2fefdcfbb270d54dabc519.nq.gz
│   ├── 6f7e36af62d21968a6d4a9299414217f706301a3.nq.gz
│   ├── 6fc78cef17f34727536e85736285105f663b39ea.nq.gz
│   ├── 7205d801a676b0a87ba9b3c53867ac66f317bac2.nq.gz
│   ├── 726a99988b251801084b50d053445406075594e5.nq.gz
│   ├── 742f59e4069e7f171801ba4a01373aa938f13df5.nq.gz
│   ├── 747c8120c38f22e029534e6e9e2b5eab70fca327.nq.gz
│   ├── 754db5afcb8260c5539b1e0ede3990b8ddbc3e29.nq.gz
│   ├── 79bbcefffc52a68f35579db252fcd012d6073789.nq.gz
│   ├── 79f95c4e54273c3ca4e00623fd55cce516040392.nq.gz
│   ├── 7e2d9e2e2b863b963ee36a926febdf2ba9b2cffa.nq.gz
│   ├── 802f9e8d738d6579d5eb963f23caec3d194f6e91.nq.gz
│   ├── 810236bdad60121858c58b4a4ddc99702c7b7f0d.nq.gz
│   ├── 81ece1b6da1c9effe768717844ebc791ce7b86a5.nq.gz
│   ├── 823cc6335a9213e7ebc5ea3e95e703c7b9d502ff.nq.gz
│   ├── 83bb7f21274f12db0501732e7915ca8addf5236e.nq.gz
│   ├── 853f099b4c5ae0ccb8be7859ded2584d9c1381c5.nq.gz
│   ├── 85d35b98ab9741dc8cd41f6e9b962efb242606f5.nq.gz
│   ├── 85dc78d7729c6a77d13904ad7dee7972efd408bb.nq.gz
│   ├── 86254ee720ecda4e15e7656dc0c0e0febd61d291.nq.gz
│   ├── 86381faf0dd353761c72130af34c04d2ae8df22e.nq.gz
│   ├── 86b8dffa1c1bb502ce0e5c24e40278584d85e772.nq.gz
│   ├── 86bcc17fab5b6a9043b0c4009d14c2aa0e2f38a8.nq.gz
│   ├── 8e28ca7cd7de46ede116b2b9d354e50669f05de2.nq.gz
│   ├── 8e47ed0ead73860ba709aab9ab428bf90fa45dfb.nq.gz
│   ├── 8fbcebfdd76107803efef12e1c749a94a56ac530.nq.gz
│   ├── 8ff6cfe29da5c1637e9ce91d810b44fa4e902d96.nq.gz
│   ├── 902710576beb144788719a3ee88febcd8e4a21e4.nq.gz
│   ├── 9362ec6cbcf998460c6a3e71a0f52e4df2c007dd.nq.gz
│   ├── 9598aa765eb4b9d0d69cc47e954f5042f9a9993c.nq.gz
│   ├── 9598fd7ca6bc9fba0e82e0b2f72a7e987f6fc0ea.nq.gz
│   ├── 962b9fdb67609c9cab1a7e61a081c8dfcfbdcc91.nq.gz
│   ├── 9cf38247a3da17e656c107188971ff37e6c876bc.nq.gz
│   ├── 9e275bc4273aef10aa99266fe7e07a896782a6d8.nq.gz
│   ├── a08416a7369111aa9593322d9ebc310399001c3b.nq.gz
│   ├── a1519abac1d0f8fdba3b16a8f8da2da7cefc9d88.nq.gz
│   ├── a15fd94697851b19baff4aeb8ae40d4f5c833051.nq.gz
│   ├── a1c1343a7dea5bdd93c5ca448c7f11a4f53ecf61.nq.gz
│   ├── a362e521d31c2f42bfa45b7a8b8df8f0bd9fa09d.nq.gz
│   ├── a49c6633482c98f3c853d9e07cfd5dd93663d663.nq.gz
│   ├── a839e9502f9a7e27d91612e99b108c5ca875e8d5.nq.gz
│   ├── aaac442dbaf1af52a2eeef07fbd7110c3a1d59dd.nq.gz
│   ├── abf8071ec152e68d4d30265360b185e24c1a6231.nq.gz
│   ├── ac337160d7e78980c925c52a765cbd9872db98f9.nq.gz
│   ├── adb9c01360f84016180b1ab10356226e8434d9aa.nq.gz
│   ├── b2a82dcdc6c56e87cfdc66b7601de2c0fbd889ea.nq.gz
│   ├── b2c914eb6e81f701792f8a2fe0917b1132f1fe98.nq.gz
│   ├── b34094e149dca24f021bf267cdd1a515d55fc2eb.nq.gz
│   ├── b41755a9635c805290fc3a2f1cbd0dc24810161d.nq.gz
│   ├── b801b00a921f27f25953dd0529e6b35ed874e6c8.nq.gz
│   ├── ba2b5d4da33cf911eb482c4e43dc9f7193735004.nq.gz
│   ├── be48f6adf757ca5a68296cbdf3c16e85a4e84b93.nq.gz
│   ├── bf44a948db88f8af9b31e89452f3d1becbfb35e1.nq.gz
│   ├── c030d3a493d592b7fb97a46cf9308439aeaa709d.nq.gz
│   ├── c0633eb80e066a2c10a7f9502ac45c2b0e5c5f8e.nq.gz
│   ├── c16e055102d4596664b4b1424c5b83955e411894.nq.gz
│   ├── c1ec4d0b3265f523ad8398506f63c23068289c63.nq.gz
│   ├── c74ea7a08b121b78f89afe889970fc748fd3a580.nq.gz
│   ├── c8b94961de66136d0c9245937fbbfaa29488d7b2.nq.gz
│   ├── cb11ac225891f090f9c4fb312d0707210d0a1b55.nq.gz
│   ├── cb360f02614304b306714b309cbc9b0a0f2ff770.nq.gz
│   ├── cbd664ffec73c261ae58dcd0afe1eec2bcbd0d30.nq.gz
│   ├── cd930cfd62e6f1153c6005b349677d5f973b84ef.nq.gz
│   ├── ced8a68526394e405d5826f7425f3c26a6162b60.nq.gz
│   ├── d3409db9d73d55d5b59fa15816be1021af1439bc.nq.gz
│   ├── d40cbae206fa1d67ac410f7dc712a0f6b40a5e53.nq.gz
│   ├── d45bc8a3bd404672a4e9add4c34f73ced7be857d.nq.gz
│   ├── d50f94cd620668aca3e51e30272168995c3153d9.nq.gz
│   ├── d681ad7f553f7d2b6276fa8cc6772a09db19021f.nq.gz
│   ├── d75d1a5b626e4c6c12b17655e089a1ecc72fc70e.nq.gz
│   ├── d7619118e08886eedb19a3dedf772dabd475d124.nq.gz
│   ├── dcd3aa017da3d86c3d8b7847f67a191426303513.nq.gz
│   ├── ddafa5d638c402f798a418542d8c73f9d2c296c1.nq.gz
│   ├── e15205925cfa9ced199145607a5771efce4ce4bd.nq.gz
│   ├── e1b19a895101c2269af8e7bac70afa7b0559d0f0.nq.gz
│   ├── e2defff3988c355ed4bdde709ee474ce763deeaf.nq.gz
│   ├── e38563d39cbde5e3509df6399835971aad7ef404.nq.gz
│   ├── e3e62009e43061292e925d497898245d6a5713df.nq.gz
│   ├── e6bdf07d614a462a34cc6114e6ab40afa3562b72.nq.gz
│   ├── e6e471cf092a443ba1c2ad2859b29525d7fe9d99.nq.gz
│   ├── e79441626b359dda0fc2a2bc4aad96c31c7cc52e.nq.gz
│   ├── e82d950714127afd54936e6fcd33c4a6849b3d9f.nq.gz
│   ├── e8d98ddb2e59980078a3b45358828b588c9156c2.nq.gz
│   ├── ecaaa4bea26a8710101892ce8d75595b2b247d1d.nq.gz
│   ├── eeaf6c00cf7fa139bf6c0ba219a13bd6509b8335.nq.gz
│   ├── f10956ab1c9629fda50ebd7832c544bdefb2da8c.nq.gz
│   ├── f2230e5a4a594d8752a7f462f171bb823a6dacee.nq.gz
│   ├── f2bef23bd68243c4ba3c06e3e415154e0e7e4d96.nq.gz
│   ├── f3559f72e31473ebf07b015996cdb470aaee0b17.nq.gz
│   ├── f50e3ed772636ea7749162ecaa9803d64f949f67.nq.gz
│   ├── f717d82ecf5183dae516e756dfbcb6f492d9702a.nq.gz
│   ├── f768d2234aeab282278f2e8e43e7212e27d36f8c.nq.gz
│   ├── f774519609005dface41fd15021c7f237f091341.nq.gz
│   ├── f8a7c242539701063b3d202e1749ae20a8fb97a7.nq.gz
│   └── f8e3fc3989ba6d2074683c9267c2b6c13ad3795b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── aa989594e1e413f45c18b26ded1783f7d5990fe5.nq.gz
├── filetree
│   └── aa989594e1e413f45c18b26ded1783f7d5990fe5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 153 files
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

[pexpect/pexpect](https://github.com/pexpect/pexpect)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*

# Repolex Knowledge Graph of ratatui/ratatui

RDF knowledge graph data for [ratatui/ratatui](https://github.com/ratatui/ratatui), parsed by [repolex](https://repolex.ai).

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
lexq download ratatui/ratatui
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e7831aedd40d9ce2fa9f37a6f2b8f00c05f2859e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e7831aedd40d9ce2fa9f37a6f2b8f00c05f2859e.nq.gz
│   └── repolex
│       └── e7831aedd40d9ce2fa9f37a6f2b8f00c05f2859e
│           └── chunk-001.nq.gz
└── blob
    ├── 004ede93bbb8acffd9c92f9101270e5b3c6fcef1.nq.gz
    ├── 0126a6f4d08071eb931e7c2838fa2b950a3e1088.nq.gz
    ├── 01ea3ea983cc3ff93bd70e3b95134780b8339ab6.nq.gz
    ├── 0219e40a8e7e8c87fbb0738fabb31de3c4845cf7.nq.gz
    ├── 023103d4d5de95bc80b94cca4ea15ad3de1e4d3e.nq.gz
    ├── 03991ed775a0cb2bb94460bae300176e24cded06.nq.gz
    ├── 0440b7fa4645def385cce8b5c3caf02566d889e0.nq.gz
    ├── 0505eb609c7d5e8c1b31fed822df540d86d5928a.nq.gz
    ├── 051a7a12589dde91384236ae6e0ea9cd96920b19.nq.gz
    ├── 0531346e36023b7a951cb2453eaa93652688714b.nq.gz
    ├── 05b87f11beb174b28068e59c68f0aa76e70ace9f.nq.gz
    ├── 06b859d2ac081e16cf1ad2c7a0eca8a47f7b7656.nq.gz
    ├── 093066dba60558203e09e7f6d2b86624b4d94e63.nq.gz
    ├── 09598990a09b97392743f610fb6acc07160fb8ca.nq.gz
    ├── 09a72cde8e913ef438fa535cbc79a97feebf123e.nq.gz
    ├── 0a85fa4a0b329c84037e2a3bf11c101c277ce9ee.nq.gz
    ├── 0c5bf4591cbb5bd149dc0bc5116dc15fad5bde07.nq.gz
    ├── 0c6ccab9a7502791c231c68b9fc231c62d409260.nq.gz
    ├── 0ebec7b3a41929dc4e9830f75a2ee41675bf1cc5.nq.gz
    ├── 1003d5615c1a27ed3d2af3d779cf9838dad10ce8.nq.gz
    ├── 11ae5182712c539e742eeda0a32a9885c7b568a7.nq.gz
    ├── 12f435b9d45cbb868ec7c13069d01e2c6846e6d3.nq.gz
    ├── 1416460f25b6a2f50a5e39fb10adef9a99066ef2.nq.gz
    ├── 168de824c3a3bddc9666539378ec1bcaef1cb974.nq.gz
    ├── 1764d6934760dc32c574ec293bfb5fa98972d812.nq.gz
    ├── 187d2fcaee601c74454544ccb0e983011221a43c.nq.gz
    ├── 19a101bb7a2dc12e315799a2fdbf57efe78249b3.nq.gz
    ├── 1a5f0652fe217cdd2731e59b446ffc9e9e0e1db4.nq.gz
    ├── 1b4a5ddf93d7240ed4d748d5abfb9557b1f1422d.nq.gz
    ├── 1bd27b441a2dc96fcc7e5a3a594343cecceb3a72.nq.gz
    ├── 1bf50bde131bbda851c6c7cf7da09907ecbefca5.nq.gz
    ├── 1cadb6cf551e6124ede2159f1e801d4a8b026ba8.nq.gz
    ├── 1ce3d32adf5e51632ef7c29fcf6432da6a764233.nq.gz
    ├── 1ec29817467f1982ae7e00f406580eb75f5031f7.nq.gz
    ├── 203af02085f047b3a4e37e969570d5e30f500666.nq.gz
    ├── 2080179cf7c2d3fd67af550fbfdf6263acf2cc09.nq.gz
    ├── 2118c57818615e235abe35a63201679f367cf572.nq.gz
    ├── 2289154d73a152687bf7a4bad4b7a3d09c8d4788.nq.gz
    ├── 22dcda8a52e51799a32c2c42f1fefbc245c8719a.nq.gz
    ├── 2330f58c320c57b9b59c3838df6023d0a0d95228.nq.gz
    ├── 2369529e9d0b47f56cb645ffcd3ba5441c2f7dfd.nq.gz
    ├── 24430092a0324971a2839594400ead03550b6989.nq.gz
    ├── 25082eef76ea96eb9e70896f2bb748efefcfed13.nq.gz
    ├── 2623437697e29c5b492b21526ab895e551f8eb88.nq.gz
    ├── 26b0a56070123bd598cff6f56f9598f8be8446e1.nq.gz
    ├── 28122c26eaf2f0cff8c9b4213f1e348a26661a82.nq.gz
    ├── 28f9fa9bce848756b0b7cd0bfe9de8d29a83413a.nq.gz
    ├── 290a0640f3dfdd381113d59c635229e880e5851a.nq.gz
    ├── 2927242ae7283aaa8bf86b9824030b9211f687c3.nq.gz
    ├── 292fe499e3b25d42211661ba9c7fafe6120186ca.nq.gz
    ├── 2ae95aba11445ead145a0de45b79051cd549672f.nq.gz
    ├── 2cead89c3bfe43a4a40a1ad136fb2dd7a1c00042.nq.gz
    ├── 2d4b0b436034ba889b618622b7745937eb5a31a8.nq.gz
    ├── 2f27747807644cee9b21002806549d40e4bac6f4.nq.gz
    ├── 2fac413a372985980483e71a160adc32c01912f3.nq.gz
    ├── 2fe68d0efe264fbfd293bc0d31e5783bc14d4342.nq.gz
    ├── 2fe9c950bf32aba7fac629efd1592465e5a1e709.nq.gz
    ├── 3003a6d584a604bf2db733fdb7138b7d8e4e4e30.nq.gz
    ├── 32049da1ed3139b731c1c2f6a22ac85be7b3ff66.nq.gz
    ├── 325f02b4902a5502e72e64020119aa659df7cbf3.nq.gz
    ├── 33ca3f2f49156b7a4a6de2dada1cf20521e921c4.nq.gz
    ├── 34887f03539f11a65c0a62ba43007eb609713bb8.nq.gz
    ├── 34c86d7b0eb34ee4d04b59b96905d8d2a7e0be0a.nq.gz
    ├── 35049cbcb13c204648d1f7897162492f05123199.nq.gz
    ├── 352f0c47327650015503b3e6cfb272e36ac8acce.nq.gz
    ├── 35d066b11b36380bb45a711d26c01e09c50e2e27.nq.gz
    ├── 3651545a34fbce9364c370a5d82c78a5492d67f1.nq.gz
    ├── 37df07f5014772db944e9576b7f548fe7df27a39.nq.gz
    ├── 3973fbab103a779383bbd15417d0565171e18b0c.nq.gz
    ├── 3a3a2903ea329929bbefc5ce238a18fe101de07d.nq.gz
    ├── 3bbd8324300114bdd5d7937e4572a1b22b4bb1be.nq.gz
    ├── 3cb970997ec463c10b31725028bf90e655caa19e.nq.gz
    ├── 3eb8bc19df3767e5f76c89d0b759e9971be43993.nq.gz
    ├── 4009594fb653250feeb8987819fcf10bed1c1068.nq.gz
    ├── 40be8fb8a7518c45ad5f651dcdb113e2628b4c1c.nq.gz
    ├── 4186758af26657267b223b5b0728156dd9c02851.nq.gz
    ├── 42986cd68ccc321d2907967cbc4a866e84a2d1bb.nq.gz
    ├── 4370512383a272746aa56a5f91c39cc52c9e3345.nq.gz
    ├── 4412e76b8294e2efb9d94efe48a756e27a4be745.nq.gz
    ├── 45bb43dcaeb2c9f07fe0f0a92be6ace2d840347c.nq.gz
    ├── 460d915cfb20478ab2010ab2e5c6321f44dd18c6.nq.gz
    ├── 478cb54170eec371a2bbeb838775957d66dc7b78.nq.gz
    ├── 4916dc190b2779def6bdc35f5897b57d44ade446.nq.gz
    ├── 4bc500a41fce37ee0180ea75e0ed489104803cc6.nq.gz
    ├── 4bcc178413afaa0b870377d80be2c4993d466711.nq.gz
    ├── 4ce1afdb45f7a0b07d83acf3c8776ce1fc06e2c3.nq.gz
    ├── 4d46c93c684a0c33bd3ff4edb82383a1e5b9d963.nq.gz
    ├── 4f437cf8b2ebc931b2c08829461e4a47156aaffb.nq.gz
    ├── 4fb9af3000c73c4b3ba0076d825a07980fe7857e.nq.gz
    ├── 5168908af3479e916233bcd32ddf62c98200ca45.nq.gz
    ├── 5422cfd997a4609ac7df93e4ce27203fcd99a0b4.nq.gz
    ├── 553544ed9a8218e1c92e4bcf0bec7ec93d998c3d.nq.gz
    ├── 55ce632ae2d6d8860ca221a9239c6e581a2cc5ac.nq.gz
    ├── 56c63e6a8afca0a31a2d29719a418f8498dd327c.nq.gz
    ├── 57b0d3f7124abb0dc015abd386693cbe97724f2f.nq.gz
    ├── 57bc0e174e6d7f456e519375d46141208bf218f6.nq.gz
    ├── 58a2064857e23124cb63b6e96b6c41380c156f75.nq.gz
    ├── 5989c082a4331bbda9d2c655b0f540cb3ad48646.nq.gz
    ├── 5a76105313daf531dc75abf8b145530d23efbc95.nq.gz
    ├── 5accbbb20a2a29ca7a103a25adcb67ffc9d9b906.nq.gz
    ├── 5c42c8953d320c6329f5c6e2f567c880332448d4.nq.gz
    ├── 5c7a3c5c0071f677dca77d0075270ddbe0366cdd.nq.gz
    ├── 5ccd33f3eb72915512f3817b556137ede2850905.nq.gz
    ├── 5f18e959f6a0ef331c2c7c0a93078340b9cd1e46.nq.gz
    ├── 61aeb1b0e8088a07c66480bc25cd87bf877eea5f.nq.gz
    ├── 6246ce59ba36eef37fca4bb307c9229d007f8c61.nq.gz
    ├── 624a31783e6ec37a602d21623df17c02547731df.nq.gz
    ├── 6285772987b5ed5fe2c2dc63d70c818487b02ad3.nq.gz
    ├── 62a9bfd2939682f0858dfb4691f72d1a4a4f191b.nq.gz
    ├── 62bd64094bd79d43b11ebab9941be8c55136a13d.nq.gz
    ├── 63506b1bd2010a0ffc05b2e84ee95eb88f6bb79c.nq.gz
    ├── 6491eaf41339cffe7ea320a82cc9dc78646e8852.nq.gz
    ├── 652e62d5effa4715155e585b68f82a015884e705.nq.gz
    ├── 6539457cea403c04974be2abf560e4417202c762.nq.gz
    ├── 6679bd1a8011e2419e8d2b44e77577b2a7ee143c.nq.gz
    ├── 670287ee90b0f631879f56f06cb275e6ac4685df.nq.gz
    ├── 699669f1ad20640e7e1ce7e6bf7d1cf7bc8d031a.nq.gz
    ├── 69dfcf87872ba345fc3cdcd8dd2c100b23f9e344.nq.gz
    ├── 6b3bb40d02301f69beda2004f4504b705963974e.nq.gz
    ├── 6b9dc1ed94e727a97b4c338eca94e780a33c97c1.nq.gz
    ├── 6da8f106ca88ca6d6dd7de20c8e7b4a8e9f33f74.nq.gz
    ├── 6ddbea1d7c015a9e5f7274fc9bffa61e18d4a4bd.nq.gz
    ├── 6fa19cda131be1d806c4115d049038058641bec6.nq.gz
    ├── 719c7bd702e4579559909dd043581f396222fc6d.nq.gz
    ├── 72a88c4b342750dab469386e2d5a0a1e8398d401.nq.gz
    ├── 73448d950931a2fe9df8cd398e09d73e6158a977.nq.gz
    ├── 743538869879722b8c4a3fd1fca581c802dd356a.nq.gz
    ├── 74555ef1fc10e1135d0b24706cfec9c774d87364.nq.gz
    ├── 7557a4bec2274cb4b226ead7be030c29614c934b.nq.gz
    ├── 7622a162c8634e52e2e57de36affdf9aeb1cf8d5.nq.gz
    ├── 776e83daf7a0d9069864fd10dfce4227edde9bbc.nq.gz
    ├── 77fc4695f228f1c41a7dc62fefa7dfe40957cc02.nq.gz
    ├── 78cfde3aee911a8aaa399d888d57e31a93d5500b.nq.gz
    ├── 7a3032afbf699af2d9bcba7d8a09b898bc788606.nq.gz
    ├── 7b49c11a34962fa3986cbdb5b3060e24531475da.nq.gz
    ├── 7b95452bdf0244824b3ce06e32d421b93d14f0ce.nq.gz
    ├── 7ba20f5b4cca4302ae3e196f4320f21e7c62f01b.nq.gz
    ├── 7bc27f89e673d069ef47590129362763e245ddf0.nq.gz
    ├── 7c3da818c03ed20e0e7b84b964e2cb98ab9fae80.nq.gz
    ├── 7c6be5559aee3c2ab6ca69360689178d6523cb27.nq.gz
    ├── 7c7b118270f316cd2cfbe33ba07aacec0352b49e.nq.gz
    ├── 7c9a60cc0df207939f2f5a997ca2e28e4b000c05.nq.gz
    ├── 7cebfb9f0d46a846e968d859fb0ddfe7813aeb87.nq.gz
    ├── 7d75dc911d9084c59334732e7a3b5495a014c99b.nq.gz
    ├── 7e77c7feab7b86b4a1b2a59af0bf4d69c75c1777.nq.gz
    ├── 7e96da1317ee6db70439057a790b0c09b86bd2b4.nq.gz
    ├── 7e97fcb4f9c908bc3866896bf6156563e23e54ba.nq.gz
    ├── 7f5509750a6d38c55b8480c6d61a9b58424d393c.nq.gz
    ├── 80177ea802063a0795ab80e17dfa29c4b7d21d83.nq.gz
    ├── 819d088ceb63ee5f13c83975600a57466334fc70.nq.gz
    ├── 83006e909e402b224d43e74fee02b1e80099d9fc.nq.gz
    ├── 830fea15a6a83c6cfe6fa1dac906854791cb33af.nq.gz
    ├── 8332b665c95452671896269e6022aca31d34d138.nq.gz
    ├── 83b717f744c6b40ee7caf6969af1ec75363457a4.nq.gz
    ├── 845e8396dbcb56fd473f12a70a104eb28aae2a60.nq.gz
    ├── 849e8e8e3b49a4dc77d74524ddac429f99b29f64.nq.gz
    ├── 84a80c4b2a2b2b957abcd2ce0b6f2b29403c6f59.nq.gz
    ├── 875fe9bc14b50e1ed2080462a0e4d044e8a9de63.nq.gz
    ├── 89dacd2310aa8ddd37cb9cd001b1bd216cc66d5c.nq.gz
    ├── 8a56a8dbe61aa0cd322c1e01d565335c69e2b1b6.nq.gz
    ├── 8b7aea90ee758337d424e1a9633ee94d69b7f4d3.nq.gz
    ├── 8c62c411bfd5360e232108a069d9ee3486a00865.nq.gz
    ├── 8ca2121675c6690ebaaedb3ef5966e701f757c07.nq.gz
    ├── 8f307954ee343e13df91a5f44fc80f61253e6ea2.nq.gz
    ├── 8f480611f98d21eb009081d8537d6e62aca9ddf9.nq.gz
    ├── 9097a243efec1d3c666c1bea3e3b3ebd006f2f56.nq.gz
    ├── 90f3c559879448b1dff352f38ad04de3f78cda45.nq.gz
    ├── 92094b732f580ccd552718cb4d1ee5db8dea7735.nq.gz
    ├── 926a4390e9bd47582a3968703122f0e681a1f7c8.nq.gz
    ├── 92fd0eb1277548a5d482966ea336a90a5177a450.nq.gz
    ├── 939e29c678ddec8c9b241e4d5b4050a6630626c5.nq.gz
    ├── 940780645455114dc2f901bc12b6886bae7025bd.nq.gz
    ├── 94f4ca5ef14c646e4b223e01c800041780219362.nq.gz
    ├── 9747fb6d2d730f7e8bee1779136db006c37e03e0.nq.gz
    ├── 9869f73a1a0cbadd4e3f792cbb6fee912edc412b.nq.gz
    ├── 99516e14b10a27c489e7f5d070f23b3b36a5ce6e.nq.gz
    ├── 995c638ce5b996711084154f720ce791135db1b3.nq.gz
    ├── 9a5e7b15b1d29d78925d70aa0067e8325cbad5b5.nq.gz
    ├── 9ae9c81fbc3f955321b098e4fef06a4c4736e2d2.nq.gz
    ├── 9b72f836d52e57cfbca07e43a47e80b932f0ed16.nq.gz
    ├── 9bcee7e2da3f7b8b131b47aec0c69b02584e8271.nq.gz
    ├── 9e60c9e249636bbe1d8bc58a0b9a7e3c5f5b698c.nq.gz
    ├── 9e814620ea1f47d0fa4b34ad266d27ee454d4d1f.nq.gz
    ├── 9f1aa58ba56456b7d056adb075edbf61d6e0bd54.nq.gz
    ├── 9f9032ba77c0b311a827c025d5a434bf0377346d.nq.gz
    ├── a0f915012a3e51ec15cda8968ba6166835c8d258.nq.gz
    ├── a1667bfb5db1f2d757723559bc8b35b30d8fbd83.nq.gz
    ├── a1eb27b806b88e7b87f1ee270591ad2b62dad011.nq.gz
    ├── a2ce35ea7a94c2b4e57bc8fde5a9555dabf4c66c.nq.gz
    ├── a447e5aa112438a7251532afcf013fc69f79b588.nq.gz
    ├── a467551ef34fb8d95a06058f32b9aea1a9135311.nq.gz
    ├── a55e2ed8219daa2011911a0985680f90baa8fb6d.nq.gz
    ├── a569b0faa36ce366608a1b81c11e154c98c489a8.nq.gz
    ├── a62f26221157dbcca6998329b74fe545f909aa04.nq.gz
    ├── a6c1347d9bfbd465610c7a5ba436320e8741357a.nq.gz
    ├── aa7df8e76007dbf7bba04d581765d92af57f4cf9.nq.gz
    └── abeac52bab0d33cd4dcbdfb8d3a11f3b32878f63.nq.gz

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

[ratatui/ratatui](https://github.com/ratatui/ratatui)

---
*Parsed on 2026-04-23 by [repolex](https://repolex.ai)*

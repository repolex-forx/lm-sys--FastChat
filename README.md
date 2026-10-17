# Repolex Knowledge Graph of lm-sys/FastChat

RDF knowledge graph data for [lm-sys/FastChat](https://github.com/lm-sys/FastChat), parsed by [repolex](https://repolex.ai).

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
rlex download lm-sys/FastChat
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 587d5cfa1609a43d192cedb8441cac3c17db105d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 587d5cfa1609a43d192cedb8441cac3c17db105d
│           └── chunk-001.nq.gz
└── blob
    ├── 0002ff6543f4e2bdc859d441dd49a9beabef8328.nq.gz
    ├── 01263dcc71535e275c7509af96d10eac3b79926b.nq.gz
    ├── 04477a0959c97d7d11160400ee3d4cc3c1129681.nq.gz
    ├── 06f8b2acf2bd64ff525f3065c393c19a5b3441df.nq.gz
    ├── 07f4b16a66f112fb485e2c327dda812e5d33723a.nq.gz
    ├── 089b500ffc1f0bc6bfe8b023cdb147753a20068e.nq.gz
    ├── 0984513c96931b6d48dfd17f3020fe5cebc3f911.nq.gz
    ├── 0ae63ea76cb4aae9f22f622db84857958965cd07.nq.gz
    ├── 0af680bb5f1cabcf77b9a67bd9d542b53550f89f.nq.gz
    ├── 0b49bea4cd5c9afd723318daaa5c10dcb309b776.nq.gz
    ├── 0cd78b71e95a3034bf3440aee3557a38426d0244.nq.gz
    ├── 0e0698e4c5fce8fdb287b224e88c16edf471557c.nq.gz
    ├── 0eb2badd59140d72ff995ad4419fde2a2a697955.nq.gz
    ├── 1107756dbf9baccfe1fc5b0bdbdc9796f6f61807.nq.gz
    ├── 1114151a9b077fd538e39721c8fc85e9a06d7a91.nq.gz
    ├── 113e0c7a36511518307a5c299defc1d6dbb7fc50.nq.gz
    ├── 113e497a48062bc68039357e97194fdc8d5853d9.nq.gz
    ├── 16cf5d2b65649a99ce70c6cd13553daafbeec71d.nq.gz
    ├── 18bef5f1962384d80f174aa22a7b6dcc867fe7c0.nq.gz
    ├── 1b940bf5a5bdb02ca093fac88d883e3a45da4322.nq.gz
    ├── 1ccc8a1623569d8612858cfaada2704875e46a49.nq.gz
    ├── 1d1a011396c5298aed26f887418e54fd79a1ace4.nq.gz
    ├── 1f27be85c09e2394bd821cc1ce236f46c429d4bc.nq.gz
    ├── 203a44901c10c5526f198c8e9dbb4e32d15ed7aa.nq.gz
    ├── 21642d94810ea4fd81d53cd03e158fdac2cece80.nq.gz
    ├── 21abc92cb9e64482d4c3375e6321bd00641ac4f9.nq.gz
    ├── 223642384936578e66cf127936251dda6a51d595.nq.gz
    ├── 25b3e13f847cb38f22bba2cf277b55cef6c10726.nq.gz
    ├── 25ea24ffe07fab0953bfe7b6a3b24769fb55053c.nq.gz
    ├── 261c57ad5219f1cb6fbc6f415eba439e1f9fa7da.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 270f981ccf62eb822d823ed299d864f6533fad17.nq.gz
    ├── 29767dce6ae41b72ecabfed477531684a4241d55.nq.gz
    ├── 2bf582ac615e421cf06e79e65b11e8a724d20ac1.nq.gz
    ├── 2cbac8bc5f9f5ccbee833ac9cc22cf23c068e51e.nq.gz
    ├── 2dc99449dca6551f8eb6c51dfe86eca28ea6a6be.nq.gz
    ├── 2e967e3efbfc07f1c93fc19bb4604dfa86e09f06.nq.gz
    ├── 2e9b607709e79e5bc29a4ecf08d3236795a4eded.nq.gz
    ├── 2eed9649e12c791647919e504ae970e820cc83d6.nq.gz
    ├── 2f089c418556fc68e3a791c62727fd945c8b9be9.nq.gz
    ├── 2f4ad7b0b134d1699ff8ba0d95d8039ec3c1f204.nq.gz
    ├── 2f7b39adbea524b4ec2f93cf65f42f09f1a5a08a.nq.gz
    ├── 2fe322990f1e9d7a14cb45afbc16e5574604a766.nq.gz
    ├── 306edab21a79658d22eb75f1da3eba1f830e4ae7.nq.gz
    ├── 3400d63b2d55876446d7654cea097103fd644d1c.nq.gz
    ├── 3691158561fce7cea656e7610c50198463efdd99.nq.gz
    ├── 3796a6e2a7cb53dc6921674fc4c488246e0b93c7.nq.gz
    ├── 382c888a0305296d7307ce061d527e1c5e01aca3.nq.gz
    ├── 393827bb47ebfad2d38d04d58aadc71f7ad7d407.nq.gz
    ├── 3b6da455fc7bf8af1ce473f80440bff280c9366e.nq.gz
    ├── 3c1a8793d00ae2cd40da085e09448428f9ef5cff.nq.gz
    ├── 3ccde1ca57546acf5d1131cae14a499f1228a02c.nq.gz
    ├── 3d1c1e61cf0287b57512b0c6eb3f2dda9572b964.nq.gz
    ├── 3d58e56bf3a749fe13480ea0eb7f7d2d412accc7.nq.gz
    ├── 3e7879bb5e499b080a9e50c5f5db570d7378f0dc.nq.gz
    ├── 4078d1e0dc7498885f55448edaac41258e68980c.nq.gz
    ├── 40ae32219a243d3ba2bf8eafe9bbab997ffb33bd.nq.gz
    ├── 410ce8a828c38b8ecca98aa40469d9e8b93b3580.nq.gz
    ├── 413dd3b30500c788abb19e5742447237ba2b1738.nq.gz
    ├── 413fa8bced590cdb476e67a6523c3967cb844acd.nq.gz
    ├── 41d0fbdb59b4c7dc8385bef87a1bf0c8ea6e7401.nq.gz
    ├── 42d928403090d501fb9bdfa608b77bc7d9e15c31.nq.gz
    ├── 44166fb08852364439db93b2fdcbba03d7331c2a.nq.gz
    ├── 462e38187b8cb425a607d559a2e973353fa8b92c.nq.gz
    ├── 464e2c22f7a021a0f9a584d232338a9a17c40066.nq.gz
    ├── 46588ba8426aa99deab3ab1cb03e3b6774ede3a6.nq.gz
    ├── 47aecc1113fabfc76fa005cd34d2a0451efa294e.nq.gz
    ├── 480ba8f1a2cb067d69df174ee7d00e5072ee5164.nq.gz
    ├── 4a46103ec291bb36ff0a2d496b5f4ae9e8806d40.nq.gz
    ├── 4ade15504251620b4034ac1cb13f38c645949bda.nq.gz
    ├── 4ae098374064ad074c824a7aee8204dc0dd84262.nq.gz
    ├── 4bdd18694f55fb2e29aed357dd2637e0477966e3.nq.gz
    ├── 4c439731f6aee43bd29e1a65576c5ae04ff59cfa.nq.gz
    ├── 4ec7524cbcdf308766fddc52df31e203316ad75f.nq.gz
    ├── 4fc41918bebddec7324b00702cd58ce3fad5cb7b.nq.gz
    ├── 50174a85e654768d7e98825586b4a79b457bf71a.nq.gz
    ├── 52eb874ac63799eaa33dd61acf9d8f19ddf768ef.nq.gz
    ├── 52eddf6c82687a544ae27a7ffad6d6f0458dcb29.nq.gz
    ├── 53b1bfe7c49b7c25ca87ef180d80cc22b08c6448.nq.gz
    ├── 54890b1ca4977f4243cca46cb7c78114a3b2e5d6.nq.gz
    ├── 549d49811848d83da27eb117d63b2e9e60e59c3f.nq.gz
    ├── 563e2a5598233788a4a165eb41371fd7ab729f62.nq.gz
    ├── 57ac73c59f4a5c30f6c7a429debab12b9e7a1d7f.nq.gz
    ├── 58bedf8f07b976ca4b2b6866f49eae2483dd521d.nq.gz
    ├── 5a4b5765d23549371d92c32b73d951ca58533844.nq.gz
    ├── 5a88209bfcb58cb2131ce94d6eba03c899e74a0a.nq.gz
    ├── 5b53dae6b9b22d883f03e707771482947d56ee02.nq.gz
    ├── 5bae9fbad221c57eba8f2cf5b7eb2779a6f040a8.nq.gz
    ├── 5da803656f4be6cef89559583cd36d692e1a582e.nq.gz
    ├── 5e5fc81b3453a25905896cba31f9ce9dd0f0690e.nq.gz
    ├── 5e6266fe0449b59529825c7e8982cccf7d871e0e.nq.gz
    ├── 5ea94fadaeb243269d125a41b71a69ef15ce16fa.nq.gz
    ├── 60b8960b57e30c28ef92652b17db7e52756f8aac.nq.gz
    ├── 61ab4b0991d304a2a3c34a9191d4c98b2fae3e6e.nq.gz
    ├── 625c69c44c6161ae2945a0285d62d9365895cb37.nq.gz
    ├── 63ba7cd06238ab7d06440717c3484ecd2e0821b2.nq.gz
    ├── 64cfadbc1dd209f225c67ab228e641429957a2b1.nq.gz
    ├── 6510b8ab70acc61e2bf23ff826a7f6f4ad53b71a.nq.gz
    ├── 683a78556dd6062e395d23effa3faa77a422cf58.nq.gz
    ├── 688c2f4fa33ec50b5daab43b62e984b2aced1c68.nq.gz
    ├── 6d12d7c652bc02bb7b5c9f65bce0e1644f739c1b.nq.gz
    ├── 6d155aab7c6cb32ca5fdb10d5661f1b298908f93.nq.gz
    ├── 6d568703a4a5a18298ac51d92394e5142040c6c5.nq.gz
    ├── 6dda5b5e62674b6f0c04cb5b732c53311b3b7839.nq.gz
    ├── 6ed8e6c8cc4a39904927532beab24874b7762a17.nq.gz
    ├── 6f3c09a14a044f7c085e149b5c6b81202c7d3b6a.nq.gz
    ├── 712efdf83bdedf81ad5be166d93ca0cf0991f561.nq.gz
    ├── 7329cfe0c5771c4b71d37e3c6b1a31aa95e79c66.nq.gz
    ├── 7404839b98db34ded6a5fd9c8749fef27766b8a8.nq.gz
    ├── 78f7f51b1b18b7a10f3fab937f1475067d3e5ecf.nq.gz
    ├── 798b698641772e7ec997a7f026e660a1c6282a13.nq.gz
    ├── 7a7dd5d6b3456c4919a623bf0f1c00c539cb99f4.nq.gz
    ├── 7c653acf38e1839665febd9209b72365a49f024a.nq.gz
    ├── 7d3205bb8b89af9a9cdc61defbf6ef2be8cc58b2.nq.gz
    ├── 7f984b852ee7d0f7a6b966e4ae1b870d39d85989.nq.gz
    ├── 7fbb5625093430b7edb493d5385542d4a8ccc6f1.nq.gz
    ├── 8022fbc93e9f2d4240eb67ff95061928cee81bbd.nq.gz
    ├── 8198108e08b23c0dcd805bcf30769ea6e4e6fa5f.nq.gz
    ├── 864033fae31be8b04dec1df4eb855cae621ed96c.nq.gz
    ├── 866df9e3d4d2432f715dd93710aec5f146231a67.nq.gz
    ├── 879b240b626d9bb87f739cfe749822a17777efab.nq.gz
    ├── 87b87312f972d9d5848d58cc769a19bc4234d650.nq.gz
    ├── 8941c6ecb69afd6a9dad01b371ee018a5be0581d.nq.gz
    ├── 89ca02ece6befd647ee3bb790565e0d96f7e1227.nq.gz
    ├── 8b66387a3129cbb117178fe515491df553dd52df.nq.gz
    ├── 8d1a45ac50934c25ee8d616e270a8805103fbaf2.nq.gz
    ├── 8e8198e3861856b1f5f7020052db64b2dae29396.nq.gz
    ├── 8e94cf2756203f207e82cc7f31ff544ecdcc80f0.nq.gz
    ├── 8ed943e8be506b2a0da66bd1cddf39d2dcbdb5fb.nq.gz
    ├── 8f122caeb6023625437cd1d307025e4f343ee593.nq.gz
    ├── 8f9c626244337e9e52f404c46a84eeb0b8806cdc.nq.gz
    ├── 916aaeae0f1ed2786ae0d1c53a720365abc23a1c.nq.gz
    ├── 9546311f542af7a0824cacb0d9427f62a1a586e2.nq.gz
    ├── 95e2b704f0b65584c5be15ce14b40bc150bd6009.nq.gz
    ├── 97abaaa0df053c93c3adb655f1b5c41af0aab00d.nq.gz
    ├── 9b2aff22e84a43e583bc8e8e23d97df690eacb28.nq.gz
    ├── 9ce4913aae3ef2080470161724a4f7127abb11f0.nq.gz
    ├── 9eadd7cd57510ecbbd23798d55b079c69aac1a12.nq.gz
    ├── 9ecb47c29fbb21f6e57d9de1cba70002a886d152.nq.gz
    ├── a1c70b29545782f778ef349bf567a2e28b938428.nq.gz
    ├── a2bcff42ed9fab14fb3ed6934282b615cc7e5133.nq.gz
    ├── a680a419bd9d11d0db85afbc21c0063a2ae36df7.nq.gz
    ├── a6a843d3734e0a0127a9c54ad862f3992c10ac33.nq.gz
    ├── a6ffee96bf4f9ea39f49e9a309cab92a651fdfb9.nq.gz
    ├── a7084207309907dcb8fa37eccf55fd2a6b62ca48.nq.gz
    ├── a7e85f848eadbf2e492e0298f5a3609e50f12e59.nq.gz
    ├── aa1af38e46e3e47dc22ba2e06bab690835822664.nq.gz
    ├── aa57117b9106730b0731df10dbfb0a2b1bbe381b.nq.gz
    ├── ac38ef3dd513c4346a1b8fc05a97ceda749030b6.nq.gz
    ├── ac84dc626cb555d162db127df37b7a557ef4b1d2.nq.gz
    ├── acb8cea12c67e750698c98182fa1ae7573ad62e7.nq.gz
    ├── ad52e7b2b6e234ed33a51d516e9d682addd1e0eb.nq.gz
    ├── af6ffb6954f9bc1ba60f05b88ba7a5c916494b05.nq.gz
    ├── b08b030d45bc7faff2a8c85e5923f701a94d4cc4.nq.gz
    ├── b0da77ef2e3707caf1d5df00067f8d44f80c81b3.nq.gz
    ├── b1519652e6d90479d60054008d8d7e371b16356e.nq.gz
    ├── b271a826a19927c3ab8ead8231308bfd4b65aa25.nq.gz
    ├── b3afaf171bc38b232b68609585244c9e76489da7.nq.gz
    ├── b3d812220e0559c731c7e5efdf341ef164116782.nq.gz
    ├── b461a68b2bfeeaf1a660103b491edf7f0b255a21.nq.gz
    ├── b64aa8181726c26c9b3da355e17a6afb163f7796.nq.gz
    ├── b6b19b486149c6d03859ff4750b07819a950f4b6.nq.gz
    ├── b80703388b2a47bf372a09bbed81d7bede2bd412.nq.gz
    ├── b88ca8c50772421fca91f33ff77ef75f4d23ad4d.nq.gz
    ├── b9c07fcf6e00b4c50629b4aac1e1ccc31974a644.nq.gz
    ├── ba1c06d48aa1125113f7a864ec26d5c9368a91f5.nq.gz
    ├── ba6fd5e37a4524dda3c7ae7a05313fefbe030a86.nq.gz
    ├── ba9acf5b1c3977c5b14529299c80d161028049e3.nq.gz
    ├── bab53bcc7faa75d90392ab7d8dc35d6cdbec67bd.nq.gz
    ├── bb50a5ef0aa1d5454ce6bcc566abf15df7a1df71.nq.gz
    ├── bc1588c0ffa89758bd94dcd345838b8f15d88655.nq.gz
    ├── bc456f107b41fcadae6e51ebd1c370bdd00d8500.nq.gz
    ├── bdbc14584bfd1ec90e8478b4e55f07e8ec89a967.nq.gz
    ├── bdd86f36925639c20bad5ba316c1b373db21e7a2.nq.gz
    ├── c0b2301500455965d46641c8d80ef2d7e54224e2.nq.gz
    ├── c1fe51c91bd553f8fbe0c25e9c88fe1abc3542e7.nq.gz
    ├── c971add65283be43ea849cf3475ec450317aa649.nq.gz
    ├── c9fc72bfbbe24795e378113214b1a57c7de2b4c0.nq.gz
    ├── cb45a8bb6addf8a8506c847060e23dc65ae27995.nq.gz
    ├── cc26c3ce1c1036f0e4b84a2bfe553d3a0fccf0a5.nq.gz
    ├── ceaaa12d9f5c80e118b4a9b10a03f75a9ebe17ae.nq.gz
    ├── d139ed7f22b4eafe16702b67cf528a908061c768.nq.gz
    ├── d2640d6013b08c05a3ae3a1b887f13d3a4b1f39c.nq.gz
    ├── d30caad41581244459996a31d814040cd0adb550.nq.gz
    ├── d3531928f3f1c8d7d60a556b52d73d7cb95c4284.nq.gz
    ├── d4d4d484e50b7bc94e96b3c5dbf66ed0eb8fc7dd.nq.gz
    ├── d692b378766dc98793905d6c54d11e42bcc23e8c.nq.gz
    ├── d7a8f6e5f5ac69b518019d12c8fc8068fd0a7232.nq.gz
    ├── dadba8a558822542f093d2185a5df39577e3321f.nq.gz
    ├── dc8af8efa20bd29fb31cdd0a0bc039b30f4bf26e.nq.gz
    ├── dd4883991c570d5c870a9be03c3d5275c63900cf.nq.gz
    ├── df79f87e114662266a23bda9e6803271c7fdfa7a.nq.gz
    ├── df9227106be0bdc70946e6efc90b9cbd6fa7bf9b.nq.gz
    ├── df96cf8d2985026bf41779f76f1376bfe92b3040.nq.gz
    ├── e3461a935fe2f16ef2a6377b0424134ea0948043.nq.gz
    ├── e368e92a1dcf260ecb5b175b77e85c6971809a3c.nq.gz
    ├── e37aadcea65df7ca605369b88c068aa57c8f35f2.nq.gz
    └── e5c5f353de1b14a64150faa703165f52878d309d.nq.gz

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

[lm-sys/FastChat](https://github.com/lm-sys/FastChat)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*

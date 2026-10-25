# zat-voice-models

Voice recognition models for the **zat-voice** FiveM resource (used by zat-pets). One zip per language.

## Install

1. Download the zip of the language you use from the **Releases** page (for example `fr.zip`).
2. Unzip it into `resources/[dev]/zat-voice/web/build/voice/`. You end up with `web/build/voice/fr/model.tar.gz`.
3. Set `Config.Language = 'fr'` in zat-pets (`shared/config.lua`) and restart `zat-voice` and `zat-pets`.

Keep only the language you use in `web/build/voice/`: every file under `web/build` is downloaded by every player.

## Models

| Code | Language | Vosk model | Licence | Size | SHA-256 of model.tar.gz |
|------|----------|------------|---------|------|-------------------------|
| `en` | English (US) | `vosk-model-small-en-us-0.15` | Apache 2.0 | 39 MB | `f0b24bb92a48ca575b6a96500d6b543f0f079c573dfe85bbe16001fc0404e1d8` |
| `fr` | French | `vosk-model-small-fr-0.22` | Apache 2.0 | 40 MB | `a02efdcf7726a982d22803a0728d02402ee26f5ff334296d0e103d51d2029e10` |
| `es` | Spanish | `vosk-model-small-es-0.42` | Apache 2.0 | 38 MB | `051d5ca32ef4485c167fd7f442f981e7eaf0389dc1d12e963e18089258948f8f` |
| `de` | German | `vosk-model-small-de-0.15` | Apache 2.0 | 44 MB | `d76f67be4941c234a59ffb067890a1f3d882ef3c7f0456f688e1d0338ed7962e` |
| `pt` | Portuguese | `vosk-model-small-pt-0.3` | Apache 2.0 | 31 MB | `7687fa4ad8771a6039edebfef33941edf272a73eb207ab5e55f3cce9c7ca6989` |
| `it` | Italian | `vosk-model-small-it-0.22` | Apache 2.0 | 47 MB | `2d6e229945fb72c6db7a09cb778f8a978e226a9efb79d1aefc8443d738950c6f` |
| `ru` | Russian | `vosk-model-small-ru-0.22` | Apache 2.0 | 44 MB | `7047085a2e6bc2d0ce6d42f34a6857ef556f995b68c0d5a247a2a33d4061ca7f` |
| `tr` | Turkish | `vosk-model-small-tr-0.3` | see the Vosk models page | 35 MB | `f9963aae9919844e68ae3611e1dd10c2286cabee85f6226ae79cd798859b7a0e` |
| `pl` | Polish | `vosk-model-small-pl-0.22` | Apache 2.0 | 50 MB | `de68c051a6c4ec1c071bea4a6fc8cb6685ac40fc3a45d35b463a84dba57741ac` |
| `nl` | Dutch | `vosk-model-small-nl-0.22` | Apache 2.0 | 39 MB | `dbadff00e7692b87e379d7544d5fd53269a2db0c10944bcc8cf0d0543eccf7b3` |
| `uk` | Ukrainian | `vosk-model-small-uk-v3-nano` | Apache 2.0 | 74 MB | `b00b52df1bc1a867a5296ba620009d47d1947e10c1c95e58ff2f6e367743433f` |
| `cs` | Czech | `vosk-model-small-cs-0.4-rhasspy` | MIT | 44 MB | `e95285654e0bc3e3a56f4ab2e381f70fcf1eced3ffe059c96fb4bbcd21ea3452` |
| `sv` | Swedish | `vosk-model-small-sv-rhasspy-0.15` | MIT | 289 MB | `582c5e55e17d31d33201e2b7aff35fa97cea50869fb275575a364c9f93525cda` |
| `zh` | Chinese | `vosk-model-small-cn-0.22` | Apache 2.0 | 42 MB | `d819d38a3e79ed6a72127490c32e9d62c7d31c273c16d8a81d722db0462daac1` |
| `ja` | Japanese | `vosk-model-small-ja-0.22` | Apache 2.0 | 47 MB | `feba05d297c3bc0df0e3e159d4edd87a0dfa4c134beb89f2f07dfb437d33281c` |
| `ko` | Korean | `vosk-model-small-ko-0.22` | Apache 2.0 | 83 MB | `ef29e5582ff9e3d9833be2f0a5c1897c759dcefa2bfacad45d48d70ba0a7eefc` |
| `ar` | Arabic (Tunisian dialect) | `vosk-model-small-ar-tn-0.1-linto` | Apache 2.0 | 158 MB | `060251736a3fbc71eff8568deff24fef0fd70f581dc3287b8ed889eaff58ace1` |

The models are the Vosk small models from https://alphacephei.com/vosk/models, repacked as `.tar.gz` for the browser
recognizer. Check each model's licence on that page. Romanian, Hungarian and Danish have no small Vosk model (the texts
of zat-pets still work in those languages, without voice). The Arabic model is a Tunisian-dialect model. The Swedish model
is 289 MB.

## Checksums of the release zips (SHA-256)

| File | Size | SHA-256 |
|------|------|---------|
| `en.zip` | 39 MB | `c1bd6245d12cf04c43bf6ae272940c2ab56bedd8c3d5db641e9169a0d9d6ea0c` |
| `fr.zip` | 40 MB | `ad11e9bd5590382b476beb4b112898498f13be78b8a2265320500a7ae6415b46` |
| `es.zip` | 38 MB | `1a8012a23654501b28320a7ba96986fc2ac51a462d08f0f84b845af4d6beec69` |
| `de.zip` | 44 MB | `f99501b027f7be7eac558eca1ec3df4b86b0e9f571124e48341327bbe398e367` |
| `pt.zip` | 31 MB | `1098c5d520712eccb4bc2eb1e0391fdd2d38be46a6c5a5226cd0fc4205f9afd1` |
| `it.zip` | 47 MB | `fc3e9c0e672ca5912c2efb4f1d617dd0cfedee4fce97a0583920289f857485e5` |
| `ru.zip` | 44 MB | `0c021205888a0d5d5f31b7e899c80e1c31b000baa0dff9a9c101e6c0c32b7f99` |
| `tr.zip` | 35 MB | `29c130fc23d66c2a9cdfc0700321b5ca48dec6f1722da6dbd63e3f82cda35a1d` |
| `pl.zip` | 50 MB | `a1197d71411ea580a284bf6e39ecbdef9e558e3a5c1e3495e2c9c909405014ef` |
| `nl.zip` | 39 MB | `f69ba7cbbc2692ee3aa96cbe76b06a84761aec091377fbf04f87673844726db0` |
| `uk.zip` | 74 MB | `82ae9ed21be58cb4fe17ef5a9c2ed0e012fb6b2d1a97e5c7706e061976367e1b` |
| `cs.zip` | 44 MB | `ca4cd198d968e06745c000681f6b42262a23da2d6ce76537d4511bec47109cc2` |
| `sv.zip` | 289 MB | `57dbb528a0436ffc73ddf9d8fdff8cbe4348abd4967186cc33f3fafe34cd40ab` |
| `zh.zip` | 42 MB | `efbe920cc70807273770f322bebaddf36e1e33bbe26913338f196426d65d5957` |
| `ja.zip` | 47 MB | `8a6a68cfd80575e1ab9ce6765d2eb0eefe61f494a781ca8d7935c9ca1c471b0a` |
| `ko.zip` | 83 MB | `854c7f7ffe9ad300720c401be63fddd39f7dedfe1be23117709fff75b3c00b00` |
| `ar.zip` | 158 MB | `507a9384ca750e422e12c3d4a9dd9e1034258b21a763ad959af46ce733e68e73` |

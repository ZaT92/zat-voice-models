# zat-voice-models

Voice recognition models for the **zat-voice** FiveM resource (used by zat-pets). One zip per language.

> [!CAUTION]
> ## KEEP ONLY ONE LANGUAGE in `web/build/voice/`
> **Every file under `web/build` is downloaded by every player who joins your server.** Each model is 31-289 MB, so leaving several languages there makes everyone download all of them. Put only the language you use in that folder, and delete the others.

## Install

1. Download the zip of the language you use from the **Releases** page (for example `fr.zip`).
2. Unzip it into `resources/[dev]/zat-voice/web/build/voice/`. You end up with `web/build/voice/fr/model.tar.gz`.
3. Set `Config.Language = 'fr'` in zat-pets (`shared/config.lua`) and restart `zat-voice` and `zat-pets`.


## Models

| Code | Language | Vosk model | Licence | Size |
|------|----------|------------|---------|------|
| `en` | English (US) | `vosk-model-small-en-us-0.15` | Apache 2.0 | 39 MB |
| `fr` | French | `vosk-model-small-fr-0.22` | Apache 2.0 | 40 MB |
| `es` | Spanish | `vosk-model-small-es-0.42` | Apache 2.0 | 38 MB |
| `de` | German | `vosk-model-small-de-0.15` | Apache 2.0 | 44 MB |
| `pt` | Portuguese | `vosk-model-small-pt-0.3` | Apache 2.0 | 31 MB |
| `it` | Italian | `vosk-model-small-it-0.22` | Apache 2.0 | 47 MB |
| `ru` | Russian | `vosk-model-small-ru-0.22` | Apache 2.0 | 44 MB |
| `tr` | Turkish | `vosk-model-small-tr-0.3` | see the Vosk models page | 35 MB |
| `pl` | Polish | `vosk-model-small-pl-0.22` | Apache 2.0 | 50 MB |
| `nl` | Dutch | `vosk-model-small-nl-0.22` | Apache 2.0 | 39 MB |
| `uk` | Ukrainian | `vosk-model-small-uk-v3-nano` | Apache 2.0 | 74 MB |
| `cs` | Czech | `vosk-model-small-cs-0.4-rhasspy` | MIT | 44 MB |
| `sv` | Swedish | `vosk-model-small-sv-rhasspy-0.15` | MIT | 289 MB |
| `zh` | Chinese | `vosk-model-small-cn-0.22` | Apache 2.0 | 42 MB |
| `ja` | Japanese | `vosk-model-small-ja-0.22` | Apache 2.0 | 47 MB |
| `ko` | Korean | `vosk-model-small-ko-0.22` | Apache 2.0 | 83 MB |
| `ar` | Arabic (Tunisian dialect) | `vosk-model-small-ar-tn-0.1-linto` | Apache 2.0 | 158 MB |

The models are the Vosk small models from https://alphacephei.com/vosk/models, repacked as `.tar.gz` for the browser
recognizer. Check each model's licence on that page. Romanian, Hungarian and Danish have no small Vosk model (the texts
of zat-pets still work in those languages, without voice). The Arabic model is a Tunisian-dialect model. The Swedish model
is 289 MB.

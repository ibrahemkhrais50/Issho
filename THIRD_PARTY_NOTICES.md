# Third-party notices

Issho © 2026 Ibrahem Khrais. All rights reserved (see `LICENSE`).
Issho uses the following open-source work. Each keeps its own license; the full texts are at the links.

| Work | Used for | License |
|---|---|---|
| [PDF.js](https://github.com/mozilla/pdf.js), Mozilla | Showing PDF pages | [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) |
| [Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M), hexgrad | English smart voice (model) | [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) |
| [kokoro-js](https://github.com/hexgrad/kokoro), hexgrad | English smart voice (runtime code) | [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) |
| [misaki](https://github.com/hexgrad/misaki) 0.7.4, hexgrad | English pronunciation word lists (`data/en-us.json`, `data/en-gb.json`) | [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) |
| [HeadTTS](https://github.com/met4citizen/HeadTTS), Mika Suominen | Letter-to-sound rules for unknown English words | [MIT](https://opensource.org/license/mit) |
| [onnxruntime-web](https://github.com/microsoft/onnxruntime) 1.20.1, Microsoft | Running the voice models in the browser | [MIT](https://opensource.org/license/mit) |
| [Supertonic 3](https://github.com/supertone-inc/supertonic), Supertone | Arabic smart voice (model) | Model: [OpenRAIL-M](https://huggingface.co/Supertone/supertonic) (use restrictions apply); code: MIT |
| [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx), k2-fsa | int8 build of the Supertonic model | [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) |
| [JSZip](https://stuk.github.io/jszip/) | Reading EPUB files | [MIT](https://opensource.org/license/mit) (dual MIT/GPLv3; used under MIT) |
| [pdf-lib](https://pdf-lib.js.org) and [@pdf-lib/fontkit](https://github.com/Hopding/fontkit) | EPUB → PDF | [MIT](https://opensource.org/license/mit) |
| [Literata](https://github.com/googlefonts/literata), [Amiri](https://github.com/aliftype/amiri), [IBM Plex Sans Arabic](https://github.com/IBM/plex) | Fonts | [SIL Open Font License 1.1](https://openfontlicense.org) |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper), SYSTRAN | Only in the Colab notebook (installed there, not part of the app) | [MIT](https://opensource.org/license/mit) |
| [Whisper large-v3-turbo](https://huggingface.co/openai/whisper-large-v3-turbo), OpenAI | Only in the Colab notebook (downloaded there) | [MIT](https://opensource.org/license/mit) |

Issho opens EPUB files made by [Storyteller](https://gitlab.com/storyteller-platform/storyteller) (MIT); no Storyteller
code is part of Issho. Translations come from [MyMemory](https://mymemory.translated.net) (or, when the user turns it on,
Google Cloud Translation with their own key), under their own terms. English definitions come from
[Wiktionary](https://en.wiktionary.org) through the [Free Dictionary API](https://dictionaryapi.dev), under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/); the app credits it under each definition.

The same list, with the privacy policy and the terms of use, is inside the app: Settings → Privacy / Terms of use /
Licenses (`#/privacy`, `#/terms`, `#/licenses`).

The Supertonic model's OpenRAIL-M license forbids some uses of the model (for example, impersonating people or
producing deceptive content). Anyone using Issho's Arabic voice agrees to those use restrictions.

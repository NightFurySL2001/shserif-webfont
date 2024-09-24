This repo is used to host Source Han Serif for web font usage in [SHS-CID project](https://nightfurysl2001.github.io/shs-cid). This repo will be served through `jsdelivr`.

Use the root `index.css` to get all OTFs for all languages, or the individual language CSS files in the folder for one locale. The fonts includes all weights and locales that can be changed through `locl`. The font name to be used in CSS and their file location are listed below. Note that the `font-family` does not match upstream naming scheme.

| Language/Locale                     | HTML `lang` tag | `font-family`         | CSS file                      |
|-------------------------------------|-----------------|-----------------------|-------------------------------|
| Japanese                            | `ja`            | `Source Han Serif`    | `Japanese/J.css`              |
| Korean                              | `ko`            | `Source Han Serif K`  | `Korean/K.css`                |
| Simplified Chinese                  | `zh-CN`         | `Source Han Serif CN` | `SimplifiedChinese/CN.css`    |
| Traditional Chinese (Taiwan Edu)    | `zh-TW`         | `Source Han Serif TW` | `TraditionalChinese/TW.css`   |
| Traditional Chinese (Hong Kong Ref) | `zh-HK`         | `Source Han Serif HK` | `TraditionalChineseHK/HK.css` |
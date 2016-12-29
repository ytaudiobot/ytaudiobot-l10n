<a href="//ytaudiobot.ml"><img src="logo.png" width="100%"/></a>
#### Help translate [@YTAudioBot](//telegram.me/ytaudiobot) — a YouTube audio downloader for Telegram Messenger
_Stay tuned for news and updates on our [Telegram Channel](//telegram.me/ytaudio)_

---

YTAudioBot is currently available in the following languages:

Language | Contributors | Translated
:-- | :-- | :--
:us: **English** ([en_US](messages/en_US.json)) | [Dan](//github.com/delivrance) | -
:it: **Italiano** ([it_IT](messages/it_IT.json)) | [Dan](//github.com/delivrance) | -
:es: **Español** ([es_ES](messages/es_ES.json)) | [Gerardo](//github.com/balboag) | 100%
:brazil: **Português** ([pt_BR](messages/pt_BR.json)) | [Rafael](//github.com/rafaelsturmer) | [**95.1%**](https://github.com/ytaudiobot/ytaudiobot-l10n/issues/53)
:israel: **עברית** ([he_IL](messages/he_IL.json)) | [PhantomGitHub](//github.com/PhantomGitHub) | 100%
:de: **Deutsch** ([de_DE](messages/de_DE.json)) | [Julian](//github.com/jwsp1), Alex | 100%
:finland: **Suomi** ([fi_FI](messages/fi_FI.json)) | [Elias](//github.com/theel0ja) | 100%
:greece: **Ελληνικά** ([el_GR](messages/el_GR.json)) | [stamsarger](//github.com/stamsarger) | 100%
:romania: **Română** ([ro_RO](messages/ro_RO.json)) | [NicuG](//telegram.me/nicug) | [**95.1%**](https://github.com/ytaudiobot/ytaudiobot-l10n/issues/53)
:uzbekistan: **O'zbek** ([Lt_uz_UZ](messages/Lt_uz_UZ.json)) | [HusanboyBayern](//telegram.me/HusanboyBayern) | [**97.1%**](https://github.com/ytaudiobot/ytaudiobot-l10n/issues/53)
:indonesia: **Bahasa Indonesia** ([id_ID](messages/id_ID.json)) | [Aldian Hudaya](//telegram.me/oichidan) | 100%
:tr: **Türkçe** ([tr_TR](messages/tr_TR.json)) | [EypCnn](//github.com/EypCnn), [Ilker Binzet](//github.com/binzet) | 100%
**(WIP)** :cn: **简体中文** ([zh_CN](messages/zh_CN.json)) | [Kris](//telegram.me/littlekris) | 100%
**(WIP)** :taiwan: **繁體中文** ([zh_TW](messages/zh_TW.json)) | [Kris](//telegram.me/littlekris) | 100%
**(WIP)** :saudi_arabia: **العربية** ([ar_SA](messages/ar_SA.json)) | [Mohammad Fahad](//twitter.com/mohmd1429) | 100%

> Add yourself here once you submit your translations

All translations, except English (en_US) and Italiano (it_IT), are made by volunteers who decided to help.
More translations and improved translations in any language are gratefully accepted!

You don't need to know how to program to create or improve translations.
All you need is a text editor, knowledge of the English language and of course knowledge of your own language.

## Localization guidelines
- Source/fallback is in English (en_US), updated simultaneously with Italian (it_IT).
- Locale files are stored under `messages` in JSON format: `{"key": "value"}`.
- You only need to modify the `value` of the strings; do not translate the `key`.
- Keep symbols like `*bold*`, `_italic_`, `` `code` ``, `\\n`, `\\\"` unaltered.
- Do not translate format fields such as `{EMOJI}` and `{keyword}`.
- Do not add or omit any text, also try to keep the same string length.
- Some strings are actually a `["list ", "of ", "strings"]`. This is a cosmetic need to make .json files tidy.
- Split lines every `\\n`, but be aware that some long lines have a white space at the end` `.

## How to improve or create a new localization
The process is slightly different depending upon whether you are improving an existing localization or creating a new one.

### Improving an existing localization
* [Look](messages) for the language file you want to review and compare it with [English (en_US)](messages/en_US.json).
* Edit the translated strings you want to improve or translate the missing ones (`null`) by following the [localization guidelines](#localization-guidelines).
* Send a pull request with your changes.

### Creating a new localization
To avoid different people working on the same language at the same time, first check whether your language is not already taken by someone else. So, if it's not listed under [Open Issues](//github.com/ytaudiobot/ytaudiobot-l10n/issues):

- Open a [New Issue](//github.com/ytaudiobot/ytaudiobot-l10n/issues/new) to let other people know you are working on a new translation. 
    - Put language name and code in the title, e.g. `Deutsch (de_DE)`.

Then, you can start.

* Copy `en_US.json` and rename the file to your [language code](LANGUAGES.md), e.g. `de_DE.json`.
* Edit the file to change the English strings to your language strings by following the [localization guidelines](#localization-guidelines). 
* Send a pull request with your changes.

If you don't know exactly how to translate a specific string you can set the entire value to `null`, e.g. `"send_feedback": null`.
This way, it will be replaced with the corresponding string in English (en_US) as a fallback until the translated string is available.

---

I tried to do my best in writing both the English (en_US) translation source and this page to allow a broader access to contributors, but since it's not my native language there might be some imperfections.
If you happen to find something to improve (without completely change the meaning), feel free to make changes.

## Contacts
- Telegram: [@haskell](//telegram.me/haskell).
- E-Mail: [admin@ytaudiobot.ml](mailto:admin@ytaudiobot.ml).
- YTAudioBot: :gear: **Settings >** :speech_balloon: **Feedback >** :memo: **Send feedback**.

# GetAnyMessageILBot-Translations

[GetAnyMessageILBot](https://t.me/GetAnyMessageILBot) is currently available in the following languages:

### Language:

**English** by [me](https://github.com/moshe-coh)

**Hebrew** by [me](https://github.com/moshe-coh)

> Add yourself here once you submit your translations

All translations, except English (en) and Hebrew (he) are made by volunteers who decided to help.
More translations and improved translations in any language are gratefully accepted!

You don't need to know how to program to create or improve translations.
All you need is a text editor, knowledge of the English language and of course knowledge of your own language.

## Localization guidelines
- Source/fallback is in English (en), updated simultaneously with Hebrew (he).
- Locale files are stored under `locales` in JSON format: `{"key": "value"}`.
- You only need to modify the `value` of the strings; do not translate the `key`.
- Keep symbols like `**bold**`, `__italic__`, `` `code` ``, `\n`, `[` , `]` unaltered.
- Do not translate format fields such as `{}`.
- Do not add or omit any text, also try to keep the same string length.

## How to improve or create a new localization
The process is slightly different depending upon whether you are improving an existing localization or creating a new one.

### Improving an existing localization
* [Look](locales) for the language file you want to review and compare it with [English (en)](locales/en.json).
* Edit the translated strings you want to improve or translate the missing ones (`null`) by following the [localization guidelines](#localization-guidelines).
* Send a pull request with your changes.

### Creating a new localization
To avoid different people working on the same language at the same time, first check whether your language is not already taken by someone else. So, if it's not listed under [Open Issues](//github.com/MehdiMJ1/Instagram-Downloader-Translation/issues):

- Open a [New Issue](https://github.com/moshe-coh/GetAnyMessageILBot-Translations/issues/new) to let other people know you are working on a new translation. 
    - Put language name and code in the title, e.g. `Deutsch (de_DE)`.

Then, you can start.

* Copy `en_US.json` and rename the file to your language code, e.g. `de.json`.
* Edit the file to change the English strings to your language strings by following the [localization guidelines](#localization-guidelines). 
* Don't forget to add your name and the percent of translation's accuracy to contributers table in README.md.
* Send a pull request with your changes.

If you don't know exactly how to translate a specific string you can set the entire value to `null`, e.g. `"ConfirmRevoke": null`.
This way, it will be replaced with the corresponding string in English (en_US) as a fallback until the translated string is available.

---

If you happen to find something to improve (without completely change the meaning), feel free to make changes.

## Contacts
- Telegram: [@JewsAdmin](https://t.me/JewsAdmin).
- Telegram Group: [Support Group](https://t.me/JewsSupport).

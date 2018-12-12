# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

## Contribute on your own Machine

Currently this project uses Node.js to support prettier & all-contributors. I intend to migrate these to CI entirely, but until then you can follow these steps:

```shell
# clone/fork
# install
yarn

### or
npm install
```

## Adding an new Item

- Try to fit your item into an existing section. Create an Issue to start as discussion about any new sections.
- Add a new item to the bottom of the list in a section.
- If a duplicate item exists, discuss why the new item should replace it.
- Check your spelling & grammar.
- The item must follow this format:
  ```
  - :legend emoji: [item name](https link) - Description beginning with capital, ending in period.
  ```

### Valid Sources

Roughly speaking, a source is considered valid if - it could be used by a development team or beginner today on a new Firebase project and not lead them astray.

An item is NOT valid if:

- it is an archived GitHub (or other) repository
- it is an outed project that is no longer actively maintained AND it's the type of project that requires maintenance. Eg: [minimist](https://github.com/substack/minimist) is an unmaintained project but it would still qualify as it doesn't particularly require maintenance.

An item can still be VALID if:

- it is a heavily used project/article (npm downloads being one metric)
- it is a heavily referenced project/article

## Languages

We should aim to support all languages that the Firebase docs support. At the time of writing this is:

- KO: 한국어
- ZH-CN: 简体中文
- JA: 日本語
- PT-BR: Português Brasileiro
- ES-419: Español (América Latina)
- EN: English
- ID: Bahasa Indonesia

### Adding an item to the English README

If you are adding an item that is not english, please translate the item name and description to english, but include the [language code](https://www.w3schools.com/tags/ref_language_codes.asp) between the emoji and item name.

### Non-English versions

If you wish to see this list in another language, please create a PR with translations for items where you can.

- Create a README suffixed with your [language code](https://www.w3schools.com/tags/ref_language_codes.asp) in a folder with your language code. Eg: `ko/README_KO.md` for Korean.
- Add your [language code](https://www.w3schools.com/tags/ref_language_codes.asp) to the list at the top of the english readme (README.md). The langs supported by Firebase are already there but commented out.

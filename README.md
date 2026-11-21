# mixture-of-vietnam
My personal VS Code themes, each is named based on a city in Vietnam.

## Themes

### Hai Duong

Two near-monochrome syntax schemes, each in a paper light and a warm dark. Gold is used for one role per scheme. Comments are the only italic.

| Theme | Gold marks | Notes |
| --- | --- | --- |
| Hai Duong Gilt Light / Dark | Keywords and headings | Names stay in ink, strings fade to grey, types and numbers are deep bronze. |
| Hai Duong Rubric Light / Dark | Function names | Keywords step back to grey, strings and numbers are deep bronze, types stay in ink. |
| Hai Duong Vellum Gilt Light / Dark | Keywords and headings | The Gilt mapping on a softer ground. Light sits on greige with warm charcoal ink (about 8:1 for text). Dark sits on soft umber, not near-black. |

The terminal uses six muted ANSI colors, set at the same lightness as the ink and gold.

Font used in the design: [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono).

## Install

1. Open the Extensions view in VS Code and search for **Mixture of Vietnam**.
2. Run **Preferences: Color Theme** and pick a Hai Duong theme.

## Build locally

```bash
npx @vscode/vsce package
code --install-extension mixture-of-vietnam-0.2.0.vsix
```

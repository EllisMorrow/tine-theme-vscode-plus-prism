# Adaptation notes

Based on Microsoft VS Code built-in Light+ and Dark+ themes at fixed revision 4bda7217fc83e8e838b1edd9ebaf21bb9b498c7e; both are in the official repository under MIT. Tine role mappings are independent adaptations.

## Sources

- darkPlus: https://github.com/microsoft/vscode/blob/4bda7217fc83e8e838b1edd9ebaf21bb9b498c7e/extensions/theme-defaults/themes/dark_plus.json
- lightPlus: https://github.com/microsoft/vscode/blob/4bda7217fc83e8e838b1edd9ebaf21bb9b498c7e/extensions/theme-defaults/themes/light_plus.json
- darkBase: https://github.com/microsoft/vscode/blob/4bda7217fc83e8e838b1edd9ebaf21bb9b498c7e/extensions/theme-defaults/themes/dark_vs.json
- lightBase: https://github.com/microsoft/vscode/blob/4bda7217fc83e8e838b1edd9ebaf21bb9b498c7e/extensions/theme-defaults/themes/light_vs.json
- license: https://github.com/microsoft/vscode/blob/4bda7217fc83e8e838b1edd9ebaf21bb9b498c7e/LICENSE.txt

## Mapping decisions

- Paired the upstream built-in Light+ and Dark+ variants; each inherits its respective light_vs or dark_vs editor surface and foreground.
- Tine surfaces, links, tags, selection and marks map selected roles from the upstream UI and token palette; colors not exposed by the 21-token API are not represented.
- Mapping is a semantic adaptation for Tine and does not reproduce VS Code syntax highlighting or full UI.

## Local validation

See the [local check summary](local-check.md) for the exact tested combinations and current manifest digest. User screenshots and full Tine interaction acceptance are pending.

Release 0.1.1 retains the tested 0.1.0 color tokens and adds publication metadata and pinned screenshots.

See the [local check summary](local-check.md) for the exact tested combinations and manifest digest.

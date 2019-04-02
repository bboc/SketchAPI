---
title: Customize Run Script editor
section: plugins
chapter: Guides
permalink: /plugins/customize-editor

order: 109
---

Use your preferred font in the _Run Script…_ editor panel.

### Use custom font

Set the `scriptEditorFont` peference to the name of the custom font, e.g. SF Mono Light.

```shell
defaults write com.bohemiancoding.sketch3 scriptEditorFont "SF Mono Light"
```

Adjust the font size setting the `scriptEditorFontSize` preference, default: 12.

```shell
defaults write com.bohemiancoding.sketch3 scriptEditorFontSize 14
```

### Reset font

To revert any changes, remove your user preferences for font and font size.

```shell
defaults delete com.bohemiancoding.sketch3 scriptEditorFont
defaults delete com.bohemiancoding.sketch3 scriptEditorFontSize
```
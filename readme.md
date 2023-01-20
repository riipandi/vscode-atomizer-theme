# Atomizer

This is fork of [Atomize VSCode Theme](https://marketplace.visualstudio.com/items?itemName=emroussel.atomize-atom-one-dark-theme). A detailed and accurate Atom One Dark theme.

**Note that if you want the same syntax highlighting as Atom One Dark, you will need to turn off semantic highlighting in your VS Code settings:**

```json
"editor.semanticHighlighting.enabled": false
```

## Contribution

I have mostly used this theme with JavaScript and other web technologies.

If you'd like me to add support for other languages, or notice a bug/discrepancy with Atom's One Dark theme, feel free to open an issue or pull request on this repo.

## Motivation

I've always loved the UI and UX of Atom, but prefer the speed and reliability of VS Code. After looking for a while, I couldn't find any VS Code theme that accurately replicated Atom One Dark's interface and syntax highlighting, so I made this one.

## Next steps

Here are some settings I use to make VS Code more minimalistic, so that I can focus on what's important. It also makes the experience more similar to Atom.

```json
{
    "breadcrumbs.enabled": false,
    "editor.cursorBlinking": "blink",
    "editor.folding": false,
    "editor.hideCursorInOverviewRuler": true,
    "editor.minimap.enabled": false,
    "editor.occurrencesHighlight": false,
    "editor.renderIndentGuides": false,
    "editor.roundedSelection": false,
    "editor.selectionHighlight": false,
    "editor.scrollBeyondLastLine": false,
    "explorer.decorations.colors": false,
    "explorer.openEditors.visible": 0,
    "window.zoomLevel": 0,
    "workbench.activityBar.visible": false,
    "workbench.editor.showIcons": false,
    "workbench.startupEditor": "none",
    "workbench.tree.renderIndentGuides": "none"
}
```

## Credits

Thanks to Emmanuel Roussel for creating [Atomize VSCode Theme](https://marketplace.visualstudio.com/items?itemName=emroussel.atomize-atom-one-dark-theme).
This theme is heavily inspired from Atom's [One Dark Syntax theme](https://github.com/atom/one-dark-syntax).

## License

This project is open-sourced software licensed under the [MIT license](./LICENSE).

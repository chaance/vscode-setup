# VS Code Setup

## Extensions

### HTML Tools 

* ~~**[Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)**~~
  * **NOTE:** I no longer use this extension as the functionality is built in to VS Code these days. Instead, I use these settings to support auto-closing tags in HTML and JSX/TSX:
```json
{
  "html.autoClosingTags": true,
  "javascript.autoClosingTags": true,
  "typescript.autoClosingTags": true
}
```
* **[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)** – Automatically rename paired HTML/XML tag
  * **NOTE:** While this feature was added to VS Code for HTML via the `editor.linkedEditing` setting, it is not yet supported for JSX/TSX. [Tracking this issue](https://github.com/microsoft/vscode/issues/85707) and I plan on dropping this extension once it's finally supported natively!

### CSS Tools 

* ~~**[Intellisense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)** – Could really use a snappier name, but you get the picture.~~
  * **NOTE:** While handy, I no longer use this extension because it's just a bit too harsh on the CPU.
* **[Sass](https://marketplace.visualstudio.com/items?itemName=robinbentley.sass-indented)** – All the code completion and snippets you'll need.
* **[SCSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-scss)** – Ignore what I said before, this is nice to have as well.

### JavaScript/TypeScript Tools

* ~~**[Babel JavaScript](https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel)** – All the good syntax support for modern JS, plus Flow and GraphQL.~~
  * **NOTE:** I no longer use this extension because VS Code does a good job with modern JS + JSX these days. I never use Flow, and I don't write GraphQL enough to need the syntax highlighting!
* **[CSS-in-JS](https://marketplace.visualstudio.com/items?itemName=paulmolluzzo.convert-css-in-js)** – Auto-complete CSS-in-JS. Also let's you quickly toggle between standard CSS and JS object-syntax, a huge time saver!
* **[Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)** – Makes adding JSDoc blocks a little quicker. Kind of buggy with some things, but useful enough that I keep it around.
* **[Import To Require Syntax](https://marketplace.visualstudio.com/items?itemName=tlevesque.import-to-require)** – Quickly convert ES module imports/exports to `require` syntax. The opposite of [Require To Import Syntax](https://marketplace.visualstudio.com/items?itemName=Bruce.rona&ssr=false#review-details).
* **[Jest Snapshot Language Support](https://marketplace.visualstudio.com/items?itemName=tlent.jest-snapshot-language-support)** – Makes reading those snapshots a bit easier!
* **[MDX](https://marketplace.visualstudio.com/items?itemName=silvenon.mdx)** – Language support/highlighting for MDX.
* **[npm intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)** – Autocomplete NPM modules in `import`/`require` statements.
* **[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)** – No brainer!
* **[Require To Import Syntax](https://marketplace.visualstudio.com/items?itemName=Bruce.rona&ssr=false#review-details)** – Quickly convert CommonJS imports/exports to ES module syntax. The opposite of [Import To Require Syntax](https://marketplace.visualstudio.com/items?itemName=tlevesque.import-to-require).
* **[TypeScript Importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)** – Autocomplete and auto-import types from `node_modules` or elsewhere from your project.
* **[vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components#review-details)** – Syntax highlighting and formatting for Styled Components (though it works with Emotion and other libs that use the same `styled` API).

### PHP Tools

**NOTE:** I don't write PHP very much these days. I may consider knocking some of these off the list at some point, but in the rare event I need to jump into some PHP these lil' tools are still great to have.

* **[PHP Debug](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-debug)**
* **[PHP DocBlocker](https://marketplace.visualstudio.com/items?itemName=neilbrayfield.php-docblocker)**
* **[PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)** – There are a few other intellisense extensions out there, but this is the strongest contender in my experience.

### Git Tools 

* **[Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)** – Useful for quickly looking at Git history, comparing branches, etc.
* **[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)** – Loads of goodies here if you prefer to visualize Git history, step through commits, a lots more. One of my favorite extensions on the list.
* **[gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)** – Language support for `.gitignore` files + generation from templates based on the project type.

### Markdown Tools 

* **[Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)** – Lots of features to simplify writing markdown. Click the link if you're curious because they keep adding more!
* **[Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced#review-details)** – Real-time preview your markdown in a side panel while you write. I'm using it while I write this very document OMG.
* **[Markdown Table Formatter](https://marketplace.visualstudio.com/items?itemName=fcrespo82.markdown-table-formatter)**

### Linting and Formatting Tools

* **[EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)** – Infer formatting settings as you type from your `.editorconfig`. I generally let Prettier handle formatting, but it's nice to see some formatting as you type, especially if I'm writing code for a demo or workshop.
* **[EditorConfig Generator](https://marketplace.visualstudio.com/items?itemName=nepaul.editorconfiggenerator)** – Exactly what it sounds like.
* **[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)** – Linter for JavaScript and TypeScript.
* **[Stylelint](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint)** – Linter for CSS.

### General Productivity Tools

* **[advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)** – Shortcut to create new files by path.
* **[change-case](https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case)** – Because sometimes ya gotta do `whatUpHomie` instead of `what_up_homie`.
* **[File Utils](https://marketplace.visualstudio.com/items?itemName=sleistner.vscode-fileutils)** – Shortcuts to quickly rename/duplicate/whatever the current working file.
* **[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)** – Autocomplete for your filenames.
* **[Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)** – Quickly access and switch between projects. Never leave home without it.
* **[TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)**
* **[Toggle Quotes](https://marketplace.visualstudio.com/items?itemName=BriteSnow.vscode-toggle-quotes)** – Quickly switch between double quotes, single quotes, backticks, whatevs.
* **[Wrap Selection](https://marketplace.visualstudio.com/items?itemName=konstantin.wrapSelection)** – Quickly throw a group of items into brackets, quotes, whatevs.

### More addons that tickle my fancy

* **[Apache Conf](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-apache)** – Remember `.htaccess` files? Sometimes I still have to look at them, and this makes them a bit easier to digest.
* **[Atom Keymap](https://marketplace.visualstudio.com/items?itemName=ms-vscode.atom-keybindings)** – Because old habits die hard.
* **[DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)** – Syntax support for your `.env` files.
* **[Gist](https://marketplace.visualstudio.com/items?itemName=kenhowardpdx.vscode-gist)** – Access your GitHub Gists in your editor + quickly publish new ones.
* **[JSON5 syntax](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-json5)**
* **[Quill Icons](https://marketplace.visualstudio.com/items?itemName=cdonohue.quill-icons)** – Dress up your file explorer icons.
* **[Rewrap](https://marketplace.visualstudio.com/items?itemName=stkb.rewrap)** – Reformats comments to a set line length. Prettier for your comments!
* **[Subtle Match Brackets](https://marketplace.visualstudio.com/items?itemName=rafamel.subtle-brackets)** – I dislike how VS Code boxes your matched brackets. This gives you a bit more control over it.
* **[TOML Language Support](https://marketplace.visualstudio.com/items?itemName=be5invis.toml)**
* **[VimL](https://marketplace.visualstudio.com/items?itemName=XadillaX.viml)** – Syntax highlighting for your Vim config/script files.
* **[XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)** – XML formatting.

## My Settings

```json5
{
  "atomKeymap.promptV3Features": true,
  "breadcrumbs.enabled": true,
  "css.validate": false,
  "editor.cursorBlinking": "phase",
  "editor.detectIndentation": false,
  "editor.fontFamily": "'JetBrains Mono', 'Inconsolata for Powerline', monospace",
  "editor.fontSize": 13,
  "editor.fontWeight": "400",
  "editor.hideCursorInOverviewRuler": true,
  "editor.lineHeight": 28,
  "editor.matchBrackets": "never",
  "editor.minimap.enabled": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.occurrencesHighlight": false,
  "editor.renderIndentGuides": false,
  "editor.renderLineHighlight": "gutter",
  "editor.rulers": [],
  "editor.snippetSuggestions": "inline",
  "editor.suggestSelection": "first",
  "editor.tokenColorCustomizations": 3,
  "editor.wordSeparators": "`~!@#%^&*()-=+[{]}\\|;:'\",.<>/?",
  "editor.wordWrap": "on",
  "editor.wrappingIndent": "same",
  "emmet.excludeLanguages": [],
  "emmet.includeLanguages": {
    "markdown": "html",
    "javascript": "javascriptreact",
    "typescript": "typescriptreact",
    "vue-html": "html"
  },
  "emmet.triggerExpansionOnTab": true,
  "eslint.workingDirectories": [{ "mode": "auto" }],
  "explorer.confirmDragAndDrop": false,
  "explorer.openEditors.visible": 0,
  "files.trimTrailingWhitespace": true,
  "files.watcherExclude": {
    "**/.git/**": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/.DS_Store": true,
    "**/bower_components/**": true,
    "**/jspm_packages/**": true,
    "**/node_modules/**": true
  },
  "gitlens.currentLine.scrollable": false,
  "gitlens.currentLine.enabled": false,
  "intelephense.files.maxSize": 3200000,
  "intelephense.files.exclude": [
    "**/.git/**",
    "**/.svn/**",
    "**/.hg/**",
    "**/CVS/**",
    "**/.DS_Store/**",
    "**/node_modules/**",
    "**/bower_components/**",
    "**/vendor/**/{Tests,tests}/**",
    "**/.history/**"
  ],
  "html.autoClosingTags": true,
  "javascript.autoClosingTags": true,
  "typescript.autoClosingTags": true,
  "javascript.suggestionActions.enabled": false,
  "less.validate": false,
  "markdown-table-formatter.markdownGrammarScopes": [
    "markdown",
    "mdx",
    "javascript"
  ],
  "phpcs.enable": false,
  "phpcs.ignorePatterns": [
    "**/dist/**",
    "**/vendor/**",
    "acf-json/**",
    "wp-admin/**",
    "wp-content/themes/twentyeleven/**",
    "wp-content/themes/twentyfifteen/**",
    "wp-content/themes/twentyfourteen/**",
    "wp-content/themes/twentynineteen/**",
    "wp-content/themes/twentyseventeen/**",
    "wp-content/themes/twentysixteen/**",
    "wp-content/themes/twentyten/**",
    "wp-content/themes/twentythirteen/**",
    "wp-content/themes/twentytwelve/**",
    "wp-content/themes/twentytwenty/**",
    "wp-includes/**"
  ],
  "phpcs.standard": "PSR2",
  "rewrap.wrappingColumn": 80,
  "scss.validate": false,
  "stylelint.validate": [
    // https://github.com/stylelint/vscode-stylelint
    "css",
    "html",
    "less",
    "markdown",
    "postcss",
    "sass",
    "scss",
    "source.css.styled",
    "styled-css",
    "sugarss",
    "svelte",
    "vue",
    "vue-html",
    "vue-postcss",
    "xml",
    "xsl"
  ],
  "subtleBrackets.disableNative": false,
  "task.slowProviderWarning": ["npm"],
  "terminal.external.osxExec": "iTerm.app",
  "terminal.integrated.fontFamily": "'IBM Plex Mono', 'Operator Mono', 'Inconsolata for Powerline', monospace",
  "terminal.integrated.fontSize": 13,
  "terminal.integrated.fontWeight": "400",
  "terminal.integrated.fontWeightBold": "400",
  "terminal.integrated.lineHeight": 1.25,
  "todohighlight.exclude": [
    "**/vendor/**",
    "**/node_modules/**",
    "**/dist/**",
    "**/bower_components/**",
    "**/build/**",
    "**/.vscode/**",
    "**/.github/**",
    "**/_output/**",
    "**/*.min.*",
    "**/*.map"
  ],
  "typescript.format.enable": false,
  "typescript.tsdk": "node_modules/typescript/lib",
  "typescript.validate.enable": true,
  "window.openFoldersInNewWindow": "default",
  "workbench.activityBar.visible": true,
  "workbench.editor.showIcons": false,
  "workbench.statusBar.visible": true,
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "files.trimTrailingWhitespace": false
  },
  "[php]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[python]": {
    "editor.rulers": [79],
    "rewrap.wrappingColumn": 79
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[mdx]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.iconTheme": "quill-icons",
  "[dart]": {
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.rulers": [80],
    "editor.selectionHighlight": false,
    "editor.suggest.snippetsPreventQuickSuggestions": false,
    "editor.suggestSelection": "first",
    "editor.tabCompletion": "onlySnippets",
    "editor.wordBasedSuggestions": false
  },
  "workbench.colorTheme": "City Lights",
  "extensions.ignoreRecommendations": true,
  "explorer.confirmDelete": false,
  "workbench.startupEditor": "newUntitledFile",
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "typescript.updateImportsOnFileMove.enabled": "never",
  "editor.accessibilitySupport": "off",
  "window.zoomLevel": 1,
  "security.workspace.trust.untrustedFiles": "open",
  "shellformat.useEditorConfig": true,
  "todohighlight.isEnable": false
}
```

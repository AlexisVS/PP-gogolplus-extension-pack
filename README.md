# README


### Description

Voici mon pack d'extension coontent plein d'extension pour le web developpement

Ce truc en dessous c'est mon fichier ``settings.json``.

Il permet d'enregistrer toute les options. PS: Meme les options qui a dans le menu settings 

```JSON
 {
  "workbench.colorTheme": "One Dark Pro",
  "workbench.colorCustomizations": { // pour changer les couleurs
    "tab.activeBackground": "#12141C",
    "activityBar.background": "#12141C",
    "sideBar.background": "#12141C",
    "editor.background": "#12141C",
    "statusBar.background": "#12141C",
    "editorGroupHeader.tabsBackground": "#12141C",
    "sideBarSectionHeader.background": "#12141C",
    "terminal.background": "#12141C",
    "titleBar.activeBackground": "#12141C",
    "sideBar.border": "#4e567a",
    "tab.unfocusedActiveBackground": "#12141C",
    "tab.inactiveBackground": "#12141C",
    "editorGroup.border": "#4e567a"
  },
  "editor.fontFamily": "Fira Code, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.formatOnSave": true,
  "files.autoSave": "afterDelay",
  "workbench.iconTheme": "material-icon-theme",
  "browser-preview.startUrl": "http://127.0.0.1:5500", //a changer en fonction de la techno utilisé
  "sync.autoUpload": true,
  "sync.gist": "535d907e6ec4e635298a590766df4f86", // pour settings sync pour que tes donner soit synchroniser je pense que maintenant c'est natif dans VSCODE
  "editor.linkedEditing": true,
  // Defining custom colors instead of default "Rainbow" for dark backgrounds.
  // (Sorry: Changing them needs an editor restart for now!)
  
  // *** C'est mon dégrader de gris
  "indentRainbow.colors": [
    "rgba(103,113,133,0)",
    "rgba(103,113,133,0.05)",
    "rgba(103,113,133,0.1)",
    "rgba(103,113,133,0.15)",
    "rgba(103,113,133,0.2)",
    "rgba(103,113,133,0.25)",
    "rgba(103,113,133,0.3)",
    "rgba(103,113,133,0.35)",
    "rgba(103,113,133,0.4)",
    "rgba(103,113,133,0.45)",
    "rgba(103,113,133,0.5)",
    "rgba(103,113,133,0.55)",
    "rgba(103,113,133,0.6)",
    "rgba(103,113,133,0.65)",
    "rgba(103,113,133,0.7)",
    "rgba(103,113,133,0.75)",
    "rgba(103,113,133,0.8)",
    "rgba(103,113,133,0.85)",
    "rgba(103,113,133,0.9)",
    "rgba(103,113,133,0.95)",
    "rgba(103,113,133,1)"
  ],
  "indentRainbow.excludedLanguages": [
    "css",
    "js"
  ],
  "vsicons.dontShowNewVersionMessage": true,
  // The indent color if the number of spaces is not a multiple of "tabSize".
  "indentRainbow.errorColor": "#DB918A",
  // The indent color when there is a mix between spaces and tabs.
  // To be disabled this coloring set this to an empty string.
  "indentRainbow.tabmixColor": "#DBA78A",
  "liveServer.settings.donotShowInfoMsg": true,
  "php.validate.executablePath": "C:\\laragon\\bin\\php\\php-7.4.20-Win32-vc15-x64\\php.exe", // executable php.exe
  "editor.minimap.renderCharacters": false,
  "editor.minimap.maxColumn": 75,
  "liveServer.settings.ChromeDebuggingAttachment": true,
  "browser-preview.chromeExecutable": "C:\\Program Files\\Google\\Chrome\\Application\\chrome.exe",
  "liveServer.settings.donotVerifyTags": true,
  "editor.snippetSuggestions": "top",
  "explorer.confirmDragAndDrop": false,
  "liveSassCompile.settings.formats": [
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "/public/css/" // choisit ou tu veut sauvegarder ton fichier
    }
  ],
  "liveSassCompile.settings.excludeList": [
    "**/node_modules/**",
    ".vscode/**"
  ],
  "emmet.excludeLanguages": [
    "markdown"
  ],
  "emmet.includeLanguages": {
    "php": "html",
    "postcss": "css",
    "javascript": "javascriptreact",
    "blade": "html",
    "vue-html": "html",
    "vue": "html"
  },
  "emmet.showExpandedAbbreviation": "always",
  "html-css-class-completion.enableEmmetSupport": true,
  "emmet.syntaxProfiles": {
    "php": "html"
  },
  "emmet.triggerExpansionOnTab": true,
  "workbench.preferredDarkColorTheme": "One Dark Pro",
  "intelephense.environment.documentRoot": "./public",
  "autoprefixer.options": {},
  "[scss]": {
    "editor.defaultFormatter": "michelemelluso.code-beautifier"
  },
  "[xml]": {
    "editor.defaultFormatter": "fabianlauer.vs-code-xml-format"
  },
  "tailwindCSS.emmetCompletions": true,
  "files.exclude": {
    "**/.git": false,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true
  },
  "explorer.confirmDelete": false,
  "[sass]": {
    "editor.defaultFormatter": "syler.sass-indented"
  },
  "editor.quickSuggestions": {
    "other": true,
    "comments": false,
    "strings": true
  },
  "editor.suggestOnTriggerCharacters": true,
  "editor.suggest.localityBonus": false,
  "colorize.languages": [
    "javascript",
    "html",
    "HTML",
    "SCSS",
    "SASS",
    "scss",
    "sass"
  ],
  "colorize.colorized_variables": [
    "LESS",
    "SASS",
  ],
  "editor.quickSuggestionsDelay": 100,
  "tailwindCSS.colorDecorators": true,
  "html-css-class-completion.HTMLLanguages": [
    "html",
    "vue",
    "razor",
    "blade",
    "handlebars",
    "twig",
    "django-html",
    "php",
    "markdown",
    "erb",
    "ejs",
    "svelte"
  ],
  "html-css-class-completion.JavaScriptLanguages": [
    "javascript",
    "javascriptreact",
    "typescriptreact"
  ],
  "html-css-class-completion.enableScssFindUsage": true,
  "workbench.tree.indent": 14,
  "sync.autoDownload": true,
  "discord.detailsEditing": "Editing {file_name} on repo : {git_repo_name}",
  "material-icon-theme.folders.color": "#F7BF0E",
  "oneDarkPro.vivid": true,
  "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
  "workbench.editorAssociations": {
    "*.ipynb": "jupyter-notebook"
  },
  "glassit.alpha": 255,
  "quokka.automaticRestart": true,
  "quokka.colors": {
    "covered": "#62b455",
    "errorPath": "#ffa0a0",
    "errorSource": "#fe536a",
    "notCovered": "#cccccc",
    "partiallyCovered": "#d2a032"
  },
  "gitlens.defaultDateFormat": null,
  "git.autofetch": true,
  "gitlens.advanced.messages": {
    "suppressCreatePullRequestPrompt": true
  },
  "terminal.integrated.tabs.enabled": true,
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "phpserver.browser": "firefox",
  "phpserver.phpPath": "C:\\php-8.0.7\\php.exe",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "[blade]": {
    "editor.autoClosingBrackets": "always",
    "editor.defaultFormatter": "shufo.vscode-blade-formatter"
  },
  "editor.tabSize": 2,
  "tabnine.experimentalAutoImports": true,
  "editor.suggest.showStatusBar": true,
  "editor.suggest.filterGraceful": false,
  "editor.suggest.previewMode": "prefix",
  "editor.wordBasedSuggestionsMode": "allDocuments",
  "bladeFormatter.format.indentSize": 2, // par defaut les blade sont a 4 mais c'est degueu
  "editor.bracketPairColorization.enabled": true,
  // tous le truc en dessous c'est pour rajouter des petite information dans le code ps: les trucs qui resemble a des vignettes
  "javascript.inlayHints.parameterNames.enabled": "all",
  "typescript.inlayHints.parameterNames.enabled": "all",
  // "javascript.inlayHints.variableTypes.enabled": true,
  // "typescript.inlayHints.variableTypes.enabled": true,
  // "javascript.inlayHints.propertyDeclarationTypes.enabled": true,
  // "typescript.inlayHints.propertyDeclarationTypes.enabled": true,
  // "javascript.inlayHints.parameterTypes.enabled": true,
  // "typescript.inlayHints.parameterTypes.enabled": true,
  // "javascript.inlayHints.functionLikeReturnTypes.enabled": true,
  // "typescript.inlayHints.functionLikeReturnTypes.enabled": true,
  "tailwindCSS.includeLanguages": {
    "plaintext": "blade.php",
    "blade": "html"
  },
  "css.validate": false,
  "less.validate": false,
  "scss.validate": false,
 }
```
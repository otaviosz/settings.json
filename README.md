Todas minhas configurações do vscode.

// Requirements:
// 1. Must install APC extension (drcika.apc-extension)
// 2. Change the font family or install JetBrainsMono Nerd Font (https://www.nerdfonts.com/font-downloads)
// 3. Change the color theme or install Catppuccin Mocha (Catppuccin.catppuccin-vsc)
//   3.1. If you changed the color theme, also change the color of the window controls to match the theme (Line 101 of this gist)
// 4. Change the icon theme or install Symbols (miguelsolorio.symbols)
// 5. Change/add your specific settings whatever you like
// ⚠ Made for Windows so idk how its gonna look on Mac
{
  // General
  "json.schemaDownload.enable": true,
  "breadcrumbs.enabled": false,
  "update.mode": "manual",
  "update.showReleaseNotes": false,
  "window.titleBarStyle": "native",
  "window.customTitleBarVisibility": "never",
  "window.commandCenter": false,
  "window.menuBarVisibility": "hidden",
  "window.restoreWindows": "all",
  "files.associations": {
    ".env.*": "dotenv"
  },

  // Workbench
  "workbench.startupEditor": "newUntitledFile",
  "workbench.list.smoothScrolling": true,
  "workbench.iconTheme": "symbols",
  "workbench.colorTheme": "Min Dark",
  "workbench.editor.labelFormat": "short",
  "workbench.editor.empty.hint": "hidden",
  "workbench.editor.editorActionsLocation": "default",
  "workbench.statusBar.visible": false,
  "workbench.layoutControl.enabled": false,

  // Editor
  "editor.fontSize": 14,
  "editor.lineHeight": 1.8,
  "editor.rulers": [80, 120],
  "editor.tabSize": 2,
  "editor.suggestSelection": "recentlyUsed",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.smoothScrolling": true,
  "editor.parameterHints.enabled": true,
  "editor.fontFamily": "JetBrainsMono Nerd Font",
  "window.zoomLevel": 1,
  "editor.fontLigatures": true,
  "editor.acceptSuggestionOnCommitCharacter": true,
  "editor.accessibilitySupport": "off",
  "editor.semanticHighlighting.enabled": true,
  "editor.inlineSuggest.enabled": true,
  "editor.hideCursorInOverviewRuler": false,
  "editor.minimap.enabled": false,
  "editor.scrollbar.vertical": "auto",
  "editor.renderLineHighlight": "all",
  "editor.quickSuggestions": {
    "strings": "on"
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },

  // Explorer
  "explorer.compactFolders": false,
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.sortOrder": "foldersNestsFiles",
  "explorer.fileNesting.enabled": true,
  "explorer.fileNesting.patterns": {
    "package.json": ".eslint*, .prettier*, tsconfig*, vite*, pnpm-lock*, bun.lockb, nest*, .yarn*, yarn.lock",
    "tailwind.config.js": "tailwind.config*, postcss.config*",
    "next.config.js": "next*",
    ".env.local": ".env*",
    ".env": ".env*"
  },

  // Terminal
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
  "terminal.external.windowsExec": "wt",
  "terminal.integrated.defaultProfile.windows": "Git Bash",

  // Security
  "security.workspace.trust.banner": "never",
  "security.workspace.trust.startupPrompt": "never",
  "security.workspace.trust.untrustedFiles": "open",
  "security.workspace.trust.enabled": false,

  // Extensions settings
  "apc.activityBar": {
    "position": "bottom",
    "hideSettings": true,
    "size": 48,
    "itemMargin": 8,
    "itemSize": 32
  },
  "apc.electron": {
    "titleBarStyle": "hidden",
    "titleBarOverlay": {
      "color": "rgba(0,0,0,0)",
      // Color of the window controls matching my theme
      "symbolColor": "#cba6f7",
      "height": 42,
      "opacity": 0
    },
    "frame": false
  },
  "apc.header": {
    "height": 36
  },
  "apc.listRow": {
    "height": 24
  },
  "apc.stylesheet": {
    // Draggable area
    "body::after": "content:'';position:absolute;top:0;left:0;width:100%;height:10px;z-index:9999;-webkit-app-region: drag;",
    ".sidebar>.title>.title-label": "opacity: 0;flex: 0!important;padding: 0!important;",
    ".sidebar>.title": "padding: 0px 8px!important",
    ".nosidebar .inline-tabs-placeholder": "width: 75px",
    ".tabs-and-actions-container": "max-width: calc(100% - 115px);",
    ".pane-header": "padding: 0 8px",
    ".pane-body": "padding: 0px",
    ".split-view-view:first-child .pane-header": "display: none !important;",
    ".monaco-list-row": "border-radius: 0px;",
    ".monaco-workbench .monaco-list:not(.element-focused):focus:before": "display: none;",
    ".window-appicon": "display: none;"
  },
  "symbols.hidesExplorerArrows": false,
  "autoimport.showNotifications": false,
  "prettier.trailingComma": "all",
  "github.copilot.enable": {
    "*": true,
    "plaintext": false,
    "markdown": true,
    "scminput": false
  },
  "git.suggestSmartCommit": false,

  // Language specific settings
  "javascript.suggest.autoImports": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.suggest.autoImports": true,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}

{
// =========================
// Workbench / UI
// =========================
"workbench.colorTheme": "Theme Darker",
"workbench.iconTheme": "material-icon-theme",
"workbench.editor.editorActionsLocation": "titleBar",
"workbench.editor.empty.hint": "hidden",

// =========================
// Editor (General)
// =========================
"editor.fontFamily": "'Cascadia Code', 'monospace', monospace",
"editor.fontSize": 16,
"editor.fontLigatures": true,
"editor.tabSize": 2,

"editor.cursorBlinking": "expand",
"editor.cursorSmoothCaretAnimation": "on",
"editor.overtypeCursorStyle": "line",

"editor.linkedEditing": true,
"editor.guides.bracketPairs": true,

// =========================
// Formatter / Prettier
// =========================
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.formatOnSave": true,
"editor.formatOnPaste": true,

"prettier.semi": false,
"prettier.singleQuote": true,
"prettier.trailingComma": "none",
"prettier.tabWidth": 2,
"prettier.printWidth": 80,
"prettier.arrowParens": "avoid",

// =========================
// Terminal Integrado
// =========================
"terminal.integrated.fontSize": 16,
"terminal.integrated.env.windows": {},

// =========================
// Git
// =========================
"git.autofetch": true,
"git.confirmSync": false,
"git.openRepositoryInParentFolders": "always",

// =========================
// JavaScript / TypeScript
// =========================
"javascript.updateImportsOnFileMove.enabled": "always",
"typescript.updateImportsOnFileMove.enabled": "always",

// =========================
// Python
// =========================
"python.defaultInterpreterPath": "/bin/python",
"python.analysis.autoImportCompletions": true,

// =========================
// Extensiones / Extras
// =========================
"github.copilot.advanced": {
"authProvider": "github"
},
"github-enterprise.uri": "https://keincarrillo.ghe.com",

"codeium.enableCodeLens": false,
"codeium.enableConfig": {
"\*": true,
"http": true
},

"liveServer.settings.donotShowInfoMsg": true,
"console-ninja.featureSet": "Community",

// =========================
// Language-specific
// =========================
"[java]": {
// "editor.defaultFormatter": "redhat.java",
"editor.formatOnSave": true
},
"[svg]": {
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.formatOnSave": true
}
}

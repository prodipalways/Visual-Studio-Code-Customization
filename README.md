# Visual Studio Code Customization

## 📝 Why?

I've been a loyal user of Visual Studio Code since 2018, and it has become my preferred code editor. Its speed and flexibility make it a reliable choice for me, regardless of the operating system I'm using. Over the years, I've created numerous projects using this code editor, and I've made various customizations to tailor it to my preferences.

I've tweaked its appearance, added and modified features, installed extensions, and even created a personalized theme because I haven't found a theme that's absolutely perfect for me. Each time I set up a new work environment, I find myself manually configuring these settings. To streamline this process, I've uploaded all my settings here, so I can quickly apply them. Feel free to use any of them for your convenience.

## 🛠 VS Code Settings
<pre>{
  <span class="pl-s"><span class="pl-pds">"</span>editor.fontSize<span class="pl-pds">"</span></span>: 20,
  <span class="pl-s"><span class="pl-pds">"</span>editor.tabSize<span class="pl-pds">"</span></span>: 2,
  <span class="pl-s"><span class="pl-pds">"</span>editor.wordWrap<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>on<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>editor.cursorSmoothCaretAnimation<span class="pl-pds">"</span></span>: true,
  <span class="pl-s"><span class="pl-pds">"</span>editor.cursorBlinking<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>expand<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>editor.formatOnSave<span class="pl-pds">"</span></span>: true,
  <span class="pl-s"><span class="pl-pds">"</span>editor.formatOnPaste<span class="pl-pds">"</span></span>: true,
  <span class="pl-s"><span class="pl-pds">"</span>editor.formatOnType<span class="pl-pds">"</span></span>: true,
  <span class="pl-s"><span class="pl-pds">"</span>workbench.colorCustomizations<span class="pl-pds">"</span></span>: {
    <span class="pl-s"><span class="pl-pds">"</span>editorGroupHeader.tabsBackground<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#2c2c54<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>activityBar.background<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#2c2c54<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>sideBar.background<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#141422<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>minimap.background<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#141422<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>tab.activeBackground<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#706fd3<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>tab.inactiveBackground<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#191846<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>terminal.border<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#2c2c54<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>terminal.background<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#2c2c54<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>statusBar.background<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#474787<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>scrollbarSlider.background<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#474787<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>scrollbarSlider.hoverBackground<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#706fd3<span class="pl-pds">"</span></span>
  },
  <span class="pl-s"><span class="pl-pds">"</span>editor.tokenColorCustomizations<span class="pl-pds">"</span></span>: {
    <span class="pl-s"><span class="pl-pds">"</span>comments<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#95afc0<span class="pl-pds">"</span></span>
  },
  <span class="pl-s"><span class="pl-pds">"</span>editor.linkedEditing<span class="pl-pds">"</span></span>: true,
  <span class="pl-s"><span class="pl-pds">"</span>editor.bracketPairColorization.enabled<span class="pl-pds">"</span></span>: true,
  <span class="pl-s"><span class="pl-pds">"</span>editor.guides.bracketPairs<span class="pl-pds">"</span></span>: true,
  <span class="pl-s"><span class="pl-pds">"</span>editor.guides.bracketPairsHorizontal<span class="pl-pds">"</span></span>: true,
  <span class="pl-s"><span class="pl-pds">"</span>editor.hover.enabled<span class="pl-pds">"</span></span>: false,
  <span class="pl-s"><span class="pl-pds">"</span>window.zoomLevel<span class="pl-pds">"</span></span>: 1,
  // Live Server 
  <span class="pl-s"><span class="pl-pds">"</span>liveServer.settings.CustomBrowser<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>chrome:PrivateMode<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>liveServer.settings.donotShowInfoMsg<span class="pl-pds">"</span></span>: true,
  <span class="pl-s"><span class="pl-pds">"</span>liveServer.settings.donotVerifyTags<span class="pl-pds">"</span></span>: true,
  // Live SASS Compiler
  <span class="pl-s"><span class="pl-pds">"</span>liveSassCompile.settings.formats<span class="pl-pds">"</span></span>: [
    {
      <span class="pl-s"><span class="pl-pds">"</span>format<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>compressed<span class="pl-pds">"</span></span>,
      <span class="pl-s"><span class="pl-pds">"</span>extensionName<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>.min.css<span class="pl-pds">"</span></span>,
      <span class="pl-s"><span class="pl-pds">"</span>savePath<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>/css<span class="pl-pds">"</span></span>
    }
  ],
  <span class="pl-s"><span class="pl-pds">"</span>liveSassCompile.settings.generateMap<span class="pl-pds">"</span></span>: false,
  // VS Code Theme Customization
  <span class="pl-s"><span class="pl-pds">"</span>workbench.iconTheme<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>material-icon-theme<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>workbench.colorTheme<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Andromeda<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>workbench.editor.enablePreview<span class="pl-pds">"</span></span>: false,
  <span class="pl-s"><span class="pl-pds">"</span>terminal.integrated.defaultProfile.windows<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Git Bash<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>terminal.integrated.fontSize<span class="pl-pds">"</span></span>: 20,
  <span class="pl-s"><span class="pl-pds">"</span>diffEditor.wordWrap<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>on<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>security.workspace.trust.untrustedFiles<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>open<span class="pl-pds">"</span></span>,
  // <span class="pl-s"><span class="pl-pds">"</span>files.autoSave<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>afterDelay<span class="pl-pds">"</span></span>,
  // <span class="pl-s"><span class="pl-pds">"</span>files.autoSaveDelay<span class="pl-pds">"</span></span>: 10,
  
  // Prettier Config
  <span class="pl-s"><span class="pl-pds">"</span>prettier.proseWrap<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>always<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>prettier.singleQuote<span class="pl-pds">"</span></span>: true,
  <span class="pl-s"><span class="pl-pds">"</span>prettier.arrowParens<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>avoid<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>editor.defaultFormatter<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>esbenp.prettier-vscode<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>[html]<span class="pl-pds">"</span></span>: {
    <span class="pl-s"><span class="pl-pds">"</span>editor.defaultFormatter<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>vscode.html-language-features<span class="pl-pds">"</span></span>
  },
  // Screencast Mode
  <span class="pl-s"><span class="pl-pds">"</span>screencastMode.onlyKeyboardShortcuts<span class="pl-pds">"</span></span>: true,
  <span class="pl-s"><span class="pl-pds">"</span>screencastMode.mouseIndicatorColor<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>#f1c40f<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>screencastMode.verticalOffset<span class="pl-pds">"</span></span>: 0,

  // Enable Emmet support <span class="pl-k">for</span> JSX
   <span class="pl-s"><span class="pl-pds">"</span>emmet.includeLanguages<span class="pl-pds">"</span></span>: {
      <span class="pl-s"><span class="pl-pds">"</span>javascript<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>javascriptreact<span class="pl-pds">"</span></span>
   }
}
</pre>
## ⚙️ VS Code Extension

- Auto Close Tag (Jun Han)
- Auto Import - ES6, TS, JSX, TSX (Sergey Korenuk)
- Auto Rename Tag (Jun Han)
- Debugger for Chrome
- ESLint (Microsoft)
- indent-rainbow (oderwat)
- HTML CSS Support (ecmel)
- JavaScript (ES6) code snippets (charalampos karypidis)
- Live Server (Ritwick Dey)
- Live Sass Compiler (Glenn Marks)
- Material Icon Theme (Philipp Kief)
- npm Intellisense (Christian Kohler)
- Path Intellisense (Christian Kohler)
- Postman (Postman)
- Prettier - Code formatted (Prettier)
- Reactjs code snippets (charalampos karypidis)
- Simple React Snippets (Burke Holland)
- Snipped (Jefferson Licet)
- Stylelint (Stylelint)
- WordPress Snippets (wpprotools.io)
- VSCode React Refactor (planbcoding)
- Tailwind CSS IntelliSense (Tailwind Labs)

## 🎨 VS Code Themes

- Andromeda 👈
- Dracula Official
- Night Owl
- Shades of Purple
- SynthWave '84
- Ayu (Theme)

## 🔑 VS Code Keyboard Shortcuts

<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr>
<th align="left">Keyboard Shortcuts</th>
<th align="left">Windows / Linux</th>
<th align="left">Mac</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">HTML boilerplate</td>
<td align="left">! + TAB</td>
<td align="left">! + TAB</td>
</tr>
<tr>
<td align="left">Open the palette to search for a file</td>
<td align="left">Ctrl + P</td>
<td align="left">cmd + P</td>
</tr>
<tr>
<td align="left">Add cursors to all matching selections</td>
<td align="left">Ctrl + Shift + L</td>
<td align="left">cmd + Shift + L</td>
</tr>
<tr>
<td align="left">Undo</td>
<td align="left">Ctrl + U</td>
<td align="left">cmd + U</td>
</tr>
<tr>
<td align="left">Select Current Line</td>
<td align="left">Ctrl + L</td>
<td align="left">cmd + L</td>
</tr>
<tr>
<td align="left">Zen Mode</td>
<td align="left">Ctrl + K Z</td>
<td align="left">cmd + K Z</td>
</tr>
<tr>
<td align="left">Toggle Sidebar</td>
<td align="left">Ctrl + B</td>
<td align="left">cmd + B</td>
</tr>
<tr>
<td align="left">Search Global Files</td>
<td align="left">Ctrl + Shift + F</td>
<td align="left">Ctrl + Shift + F</td>
</tr>
<tr>
<td align="left">Search on file</td>
<td align="left">Ctrl + F</td>
<td align="left">cmd + F</td>
</tr>
<tr>
<td align="left">Find and Replace</td>
<td align="left">Ctrl + H</td>
<td align="left">cmd + H</td>
</tr>
<tr>
<td align="left">Delete the previous Word</td>
<td align="left">Ctrl + Backspace</td>
<td align="left">cmd + Backspace</td>
</tr>
<tr>
<td align="left">Move line up/Down</td>
<td align="left">Alt + up/down arrow</td>
<td align="left">option + up/down arrow</td>
</tr>
<tr>
<td align="left">Add multiple cursors</td>
<td align="left">Ctrl + Alt +up/down arrow</td>
<td align="left">cmd + option + up/down arrow</td>
</tr>
<tr>
<td align="left">Comment Line</td>
<td align="left">Ctrl + /</td>
<td align="left">cmd + /</td>
</tr>
<tr>
<td align="left">Comment Line</td>
<td align="left">Ctrl + K + Ctrl + C</td>
<td align="left">cmd + K + cmd + C</td>
</tr>
<tr>
<td align="left">Split View</td>
<td align="left">Ctrl + \</td>
<td align="left">cmd + \</td>
</tr>
<tr>
<td align="left">Switch Between views</td>
<td align="left">Ctrl +1, Ctrl + 2 ..</td>
<td align="left">cmd + 1, cmd + 2</td>
</tr>
<tr>
<td align="left">Duplicate Line</td>
<td align="left">Alt + Shift + up/down</td>
<td align="left">option + Shift + up/down</td>
</tr>
<tr>
<td align="left">Navigate to a specific line</td>
<td align="left">Ctrl + g</td>
<td align="left">cmd + G</td>
</tr>
<tr>
<td align="left">Open Terminal</td>
<td align="left">Ctrl + `</td>
<td align="left">cmd + `</td>
</tr>
<tr>
<td align="left">To Show suggestion</td>
<td align="left">Ctrl + Space</td>
<td align="left">cmd + space</td>
</tr>
<tr>
<td align="left">To Close a TAB</td>
<td align="left">Ctrl + W</td>
<td align="left">cmd + W</td>
</tr>
<tr>
<td align="left">To Close all TAB</td>
<td align="left">Ctrl + Shift + W</td>
<td align="left">cmd + Shift + W</td>
</tr>
</tbody>
</table></markdown-accessiblity-table>

## ✒ Font Info

<ul dir="auto">
<li><a href="https://fonts.google.com/specimen/Fira+Code" rel="nofollow">Fira Code</a></li>
<li><a href="https://www.typography.com/fonts/operator/styles" rel="nofollow">Operator Mono</a></li>
</ul>

## 🧑‍💻 Contributors

<ul dir="auto">
<li><a href="https://github.com/prodipalways/">@Prodip Ray</a></li>
</ul>

## 🥰 Follow me
<ul dir="auto">
  <li><a href="https://youtube.com/rkprodip/" rel="nofollow">@YouTube</a></li>
<li><a href="https://github.com/prodipalways/">@Github</a></li>
<li><a href="https://facebook.com/prodipalways/" rel="nofollow">@Facebook</a></li>
<li><a href="https://twitter.com/prodipalways/" rel="nofollow">@Twitter</a></li>
<li><a href="https://instagram.com/prodipalways/" rel="nofollow">@Instagram</a></li>
</ul>

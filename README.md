[![GitHub Theme][vscode-github-theme-version]][github-vscode-theme-release]

# GitHub VS Code Theme for iTerm

<img src="https://github.gallerycdn.vsassets.io/extensions/github/github-vscode-theme/6.3.5/1680003819182/Microsoft.VisualStudio.Services.Icons.Default" width="64px" align="right" style="top: 1px; visibility: visible;" />

[GitHub Visual Studio Code Theme][vscode-github-theme-marketplace] for [iTerm](https://iterm2.com) (Dark, Dimmed, Light and High Contrast)

<p style="font-size:8pt">
  <img src="images/GitHubThemeiTerm.png">
  <code>ll</code> is an alias<span id="a1"><a href="#f1"><sup>1</sup></a></span> for <a href="https://github.com/ogham/exa"><code>ogham/exa</code></a> cli tool.
</p>

Download iTerm profiles and open them.

- [GitHub Dark Default.itermcolors](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/GitHub%20Dark%20Default.itermcolors)
- [GitHub Dark Dimmed.itermcolors](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/GitHub%20Dark%20Dimmed.itermcolors)
- [GitHub Dark High Contrast.itermcolors](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/GitHub%20Dark%20High%20Contrast.itermcolors)
- [GitHub Light Default.itermcolors](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/GitHub%20Light%20Default.itermcolors)
- [GitHub Light High Contrast.itermcolors](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/GitHub%20Light%20High%20Contrast.itermcolors)

|GitHub Dark Default|GitHub Dark Dimmed|GitHub Dark Hight Contrast|
|:---:|:---:|:---:|
|![GitHub Dark Default](images/GitHub_Dark_Default-iTerm.png)|![GitHub Dark Dimmed](images/GitHub_Dark_Dimmed-iTerm.png)|![GitHub Dark Hight Contrast](images/GitHub_Dark_High_Contrast-iTerm.png)|

|GitHub Light Default|GitHub Light High Contrast|
|:---:|:---:|
|![GitHub Light Default](images/GitHub_Light_Default-iTerm.png)|![GitHub Light High Contrast](images/GitHub_Light_High_Contrast-iTerm.png)|

### iTerm legacy themes

- [GitHub Dark.itermcolors](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/legacy/GitHub%20Dark.itermcolors)
- [GitHub Light.itermcolors](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/legacy/GitHub%20Light.itermcolors)

|GitHub Dark|GitHub Light|
|:---:|:---:|
|![GitHub Dark](images/GitHub_Dark-iTerm.png)|![GitHub Light](images/GitHub_Light-iTerm.png)|

They will be automatically added to your _Color Presets..._ inside _Profiles > Colors_ in iTerm Preferences pane.

![iTerm Profiles Colors Pane](images/iTermProfilesColorsPane.png)

## GitHub VSCode Theme for Apple Terminal

You can also download these profiles for Apple Terminal app:

- [GitHub Dark Default.terminal](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/terminal/GitHub%20Dark%20Default.terminal)
- [GitHub Dark Dimmed.terminal](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/terminal/GitHub%20Dark%20Dimmed.terminal)
- [GitHub Dark High Contrast.terminal](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/terminal/GitHub%20Dark%20High%20Contrast.terminal)
- [GitHub Light Default.terminal](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/terminal/GitHub%20Light%20Default.terminal)
- [GitHub Light High Contrast.terminal](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/terminal/GitHub%20Light%20High%20Contrast.terminal)

### Terminal.app legacy themes

- [GitHub Dark.terminal](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/terminal/legacy/GitHub%20Dark.terminal)
- [GitHub Light.terminal](https://raw.githubusercontent.com/cdalvaro/github-vscode-theme-iterm/HEAD/terminal/legacy/GitHub%20Light.terminal)

[vscode-github-theme-marketplace]: https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme
[vscode-github-theme-version]: https://img.shields.io/badge/GitHub%20Theme-v6.3.5-007ACC?style=flat-square&logo=visual-studio-code&logoColor=007ACC
[github-vscode-theme-release]: https://github.com/primer/github-vscode-theme/releases/tag/v6.3.5

## About my shell setup

I use [Z shell](https://zsh.sourceforge.io) in combination with [_ohmyzsh_](https://ohmyz.sh) framework.

My prompt theme is [starship](https://starship.rs), which is available for any shell. And the font I'm currently using is [MonoLisa](https://www.monolisa.dev).

Some of the _ohmyzsh_ plugins I use are:

- [ohmyzsh/colored-man-pages](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/colored-man-pages)
- [ohmyzsh/git](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git)
- [wfxr/forgit](https://github.com/wfxr/forgit)

Apart of those, I use other plugins such as:

- [zsh-users/zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
- [zsh-users/zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)

And some interesting utils I use are:

- [`ogham/exa`](https://the.exa.website), which is a modern replacement for `ls`. In my case for `ll`<a href="#f1"><sup>1</sup></a>.
- [`junegunn/fzf`](https://github.com/junegunn/fzf)
- [`BurntSushi/ripgrep`](https://github.com/BurntSushi/ripgrep)
- [`neovim/neovim`](https://github.com/neovim/neovim)

See <a href="https://github.com/cdalvaro/dotfiles">cdalvaro/dotfiles</a> for more details.

---

1. <span id="f1"></span> `alias ll='exa --long --header --group --git --modified --color-scale'` [↩️](#a1)

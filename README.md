# gh-contribs

Render your contribution graph to the terminal.

<img width="745" alt="gif main preview" src="https://raw.githubusercontent.com/MintArchit/gh-contribs/refs/heads/assets/gif/gh-contribs_main-preview_v0.23.9.gif">

connects directly via github api / no third party service is used

<div align="center">

[![Stargazers][shield_stars]][url_git-remote-stars]
[![Contributors][shield_contributors]][url_git-remote-contributors]
[![Forks][shield_forks]][url_git-remote-forks]
[![Issues][shield_issues]][url_git-remote-issues]
[![License][shield_license]][url_git-remote-license]

</div>

## Contents

## ✨ Features

- [X] other user arg (NEW)
- [X] Color schemes (NEW)
- [X] Orientation Portrait/Landscape
- [X] Diffrent Character Glyphs
- [X] Day labels
- [X] Specify weeks
- [X] Automatic Resizing
- [X] Improved help
- [X] More control over ouput with gap arguments
- [X] Doubling █ -> ██

<details>
 <summary><h4>Todo</h4></summary>

- [ ] Configuration file
- [ ] advanced animations
- [ ] User defined characters(styles)
- [ ] optimize performance
- [ ] include update notifier
- [ ] add version arg
- [ ] isolated per-repo graph
- [ ] Show legend, month, and contribution count—separate flags for each

</details>

## 📦 Installation

### install

``` bash
gh extension install mintarchit/gh-contribs
```

<details>
<summary><h3>Manage Installation</h3></summary>

#### list installed extensions

``` bash
gh extension list
```

#### upgrade

``` bash
gh extensions upgrade gh-contribs
```

#### uninstall

``` bash
gh extension remove gh-contribs
```

</details>

## ⚡️ Usage

``` bash
gh contribs
```

### display help with a list of all possible arguments

``` bash
gh contribs --help
```

``` text
Usage: gh contribs [-h] [-s <scheme>] [-g <glyph>] [-u <user>] [-w <weeks>] [-x] [-y] [-d] [-l] [-p] [-D] [-W]

Arguments:

  -h | --help                 Displays this help.
  -s | --scheme <name>        Color Scheme
  -g | --glyph <char>         Change Character
  -u | --user <user>          Show graph for other users
  -w | --weeks <weeks>        Set range of weeks to be displayed
  -x | --xgap                 Remove Gap between each Column
  -y | --ygap                 Put a Gap between each Row
  -d | --double               Enable Doubling Glyph
  -l | --labels               Enable Labels
  -p | --portrait             Set Output Orientation
  -D | --Debug                Enable additional debug output
  -W | --Warning              Disable warning output

glyphs:
square dot fisheye diamond plus block

Schemes:
gh_contrast vibrant blackAwhite dracula north gold sunset mint
```

## Color Schemes [--scheme \<name\>]

``` text
Schemes:
gh_contrast vibrant blackAwhite dracula north gold sunset mint
```

<img width="745" alt="gif scheme preview " src="https://raw.githubusercontent.com/MintArchit/gh-contribs/refs/heads/assets/gif/gh-contribs_scheme-preview_v0.1.0.gif">

## Character Glyphs [--glyph \<glyph\>]

``` text
Chars:
square dot fisheye diamond plus block
```

<img width="745" alt="gif char preview " src="https://raw.githubusercontent.com/MintArchit/gh-contribs/refs/heads/assets/gif/gh-contribs_char-preview_v0.3.6.gif">

## Limitations

Resizing Terminal font-size can temporarily mess up the display of old graph outputs

## Contributing

All contributions are greatly appreciated!

If you have a suggestion that would make gh-contribs better,
please fork the repo and create a pull request or open an issue.

See file [CONTRIBUTION.md][url_git-remote-contributing]

## Credits

gh-contribs is currently maintained by [MintArchit](https://github.com/MintArchit)

Forked from [Mizlav](https://github.com/mislav)/[gh-contrib](https://github.com/mislav/gh-contrib)

See file [CONTRIBUTORS](https://github.com/MintArchit/gh-contribs/CONTRIBUTORS)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- [url_git-remote]: https://github.com/MintArchit/gh-contribs
[url_git-remote-releases]: https://github.com/MintArchit/gh-contribs/releases -->
[url_git-remote-issues]: https://github.com/MintArchit/gh-contribs/issues
[url_git-remote-contributors]: https://github.com/MintArchit/gh-contribs/graphs/contributors
[url_git-remote-forks]: https://github.com/MintArchit/gh-contribs/network/members
[url_git-remote-stars]: https://github.com/MintArchit/gh-contribs/stargazers
[url_git-remote-contributing]: docs/CONTRIBUTING.md
<!-- [url_git-remote-coc]: https://github.com/MintArchit/gh-contribs?tab=coc-ov-file
[url_git-remote-security-policy]: https://github.com/MintArchit/gh-contribs?tab=security-ov-file#readme -->
[url_git-remote-license]: https://github.com/MintArchit/gh-contribs/LICENSE.txt

<!-- shields links-->
[shield_contributors]: https://img.shields.io/github/contributors/MintArchit/gh-contribs.svg?style=for-the-badge
[shield_forks]: https://img.shields.io/github/forks/MintArchit/gh-contribs.svg?style=for-the-badge&color=purple
[shield_issues]: https://img.shields.io/github/issues/MintArchit/gh-contribs.svg?style=for-the-badge
[shield_stars]: https://img.shields.io/github/stars/MintArchit/gh-contribs.svg?style=for-the-badge
[shield_license]: https://img.shields.io/github/license/MintArchit/gh-contribs.svg?style=for-the-badge&color=black

<!-- image links-->
<!-- [main-preview]: images/screenshot.png -->

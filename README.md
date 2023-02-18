# gh-contribs

Render your contribution graph to the terminal.

<img width="745" alt="Screenshot Gif" src="https://github.com/mintarchit/gh-contribs/blob/91bcf0d/gif/gh-contribs_main-preview_v0.23.9.gif">


connects directly via github api / no third party service is used

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
 
#### install

```
$ gh extension install mintarchit/gh-contribs
```

<details>
	<summary><h4>Manage Installation</h4></summary>

#### list installed extensions

```
$ gh extension list
```

#### upgrade

```
$ gh extensions upgrade gh-contribs
```

#### uninstall

```
$ gh extension remove gh-contribs
```
</details>

## ⚡️ Usage

```
$ gh contribs
```

#### display help with a list of all possible arguments

```
gh contribs --help
```
```
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

```
Schemes:
gh_contrast vibrant blackAwhite dracula north gold sunset mint
```

<img width="745" alt="Screenshot scheme gif preview " src="https://github.com/mintarchit/gh-contribs/blob/ba576fc/gif/gh-contribs_scheme-preview_v0.1.0.gif">

## Character Glyphs [--glyph \<glyph\>]

```
Chars:
square dot fisheye diamond plus block
```
<img width="745" alt="Screenshot char gif preview " src="https://github.com/mintarchit/gh-contribs/blob/d075d1a/gif/gh-contribs_char-preview_v0.3.6.gif">

## Limitations

Resizing Terminal font-size can temporarily mess up the display of old graph outputs

## Contributing

All contributions are greatly appreciated!

If you have a suggestion that would make gh-contribs better, 
please fork the repo and create a pull request or open an issue.

See file [CONTRIBUTION.md](https://github.com/MintArchit/gh-contribs/CONTRIBUTION.md)

## Credits

gh-contribs is currently maintained by [MintArchit](https://github.com/MintArchit)

Forked from [Mizlav](https://github.com/mislav)/[gh-contrib](https://github.com/mislav/gh-contrib)

See file [CONTRIBUTORS](https://github.com/MintArchit/gh-contribs/CONTRIBUTORS)

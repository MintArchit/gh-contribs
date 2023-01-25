# gh-contribs

Render your contribution graph to the terminal.

<img width="745" alt="Screenshot" src="https://user-images.githubusercontent.com/887/153284410-74925ad9-0e5a-441c-b4cb-5cbeced0630d.png">

connects directly via github api / no third party service is used

## Contents

## ✨ Features 

- [X] Default Style Contrast
- [X] Specify weeks
- [X] Automated Sizing (WIP)
- [X] Improved help
- [X] More control over ouput with gap arguments
- [X] Day labels (NEW)

<details>
	<summary>#### todo</summary>
	
	- [ ] Orientation Portrait/Landscape 
	- [ ] Configuration file
	- [ ] Color schemes
	- [ ] User defined characters(styles)
</details>

## 📦 Installation
 
### install

```
$ gh extension install mintarchit/gh-contribs
```

<details>
<summary>### manage Installation</summary>

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
$ gh contribs -h		#or gh contribs --help
```

## Styles

- contrast (default)
- block
- square
- dot
- shade
- fisheye
- diamond
- plus

## Limitations

Resizing Terminal font-size can temporarily mess up the display of old graph outputs

## Contributing

All contributions are greatly appreciated!

If you have a suggestion that would make gh-contribs better, 
please fork the repo and create a pull request or open an issue.

## Credits

gh-contribs is maintained by [MintArchit](https://github.com/MintArchit) &

Forked from [Mizlav](https://github.com/mislav)/[gh-contrib](https://github.com/mislav/gh-contrib)

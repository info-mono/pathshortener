<h1 align="center"><code>pathshortener</code></h1>
<p align="center">Path shortener</p>
<p align="center"><a href="https://github.com/NNBnh/pathshortener/blob/main/LICENSE"><img src="https://img.shields.io/github/license/NNBnh/pathshortener?labelColor=073551&color=4EAA25&style=for-the-badge" alt="License: GPL-3.0"></a> <img src="https://img.shields.io/badge/development-completed-%234EAA25.svg?labelColor=073551&style=for-the-badge&logoColor=FFFFFF" alt="Development completed"></p>
<p align="center"><a href="https://github.com/NNBnh/pathshortener/watchers"><img src="https://img.shields.io/github/watchers/NNBnh/pathshortener?labelColor=073551&color=4EAA25&style=flat-square"></a> <a href="https://github.com/NNBnh/pathshortener/stargazers"><img src="https://img.shields.io/github/stars/NNBnh/pathshortener?labelColor=073551&color=4EAA25&style=flat-square"></a> <a href="https://github.com/NNBnh/pathshortener/network/members"><img src="https://img.shields.io/github/forks/NNBnh/pathshortener?labelColor=073551&color=4EAA25&style=flat-square"></a> <a href="https://github.com/NNBnh/pathshortener/issues"><img src="https://img.shields.io/github/issues/NNBnh/pathshortener?labelColor=073551&color=4EAA25&style=flat-square"></a></p>

## 💡 About
`pathshortener` is a path shortener written in [`portable sh`](https://github.com/dylanaraps/pure-sh-bible) inspired by [Fish's `prompt_pwd` command](https://fishshell.com/docs/current/cmds/prompt_pwd.html) and [Starship's Directory module](https://starship.rs/config/#directory).

## 🚀 Setup
### 🧾 Dependencies
- `sh` to process

### 📥 Installation
#### 🔧 Manually
- Option 1: using `curl`

```sh
curl https://raw.githubusercontent.com/NNBnh/pathshortener/main/bin/pathshortener > ~/.local/bin/pathshortener
chmod +x ~/.local/bin/pathshortener
```

- Option 2: using `git`

```sh
git clone https://github.com/NNBnh/pathshortener.git ~/.local/share/pathshortener
ln -s ~/.local/share/pathshortener/bin/pathshortener ~/.local/bin/pathshortener
```

#### 📦 Package manager
For [`bpkg`](https://github.com/bpkg/bpkg) user:

```sh
bpkg install NNBnh/pathshortener
```

For [Basher](https://github.com/bpkg/bpkg) user:

```sh
basher install NNBnh/pathshortener
```

> *If you can and want to port pathshortener to other package managers, feel free to do so.*

## ⌨️ Usage
Run 'pathshortener' in the terminal:

```sh
pathshortener PATHS
```

## 💌 Credits
Special thanks to:
- [**Fish**](https://fishshell.com/docs/current/cmds/fish_status_to_signal.html) by [it's contributors](https://github.com/fish-shell/fish-shell/graphs/contributors)

<br><br><br><br>

---

> <h1 align="center">Made with ❤️ by <a href="https://github.com/NNBnh"><i>NNB</i></a></h1>
>
> <p align="center"><a href="https://www.buymeacoffee.com/nnbnh"><img src="https://img.shields.io/badge/buy_me_a_coffee%20-%23F7CA88.svg?logo=buy-me-a-coffee&logoColor=333333&style=for-the-badge" alt="Buy Me a Coffee"></p>

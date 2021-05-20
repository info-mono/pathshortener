<h1 align="center"><code>…/P/A/T/H/shortener</code></h1>
<p align="center">File system's path shortener</p>
<p align="center"><a href="https://github.com/info-mono/pathshortener/blob/main/LICENSE"><img src="https://img.shields.io/github/license/info-mono/pathshortener?labelColor=383838&color=585858&style=for-the-badge" alt="License: GPL-3.0"></a> <img src="https://img.shields.io/badge/development-completed-%23585858.svg?labelColor=383838&style=for-the-badge&logoColor=FFFFFF" alt="Development completed"></p>
<p align="center"><a href="https://github.com/info-mono/pathshortener/watchers"><img src="https://img.shields.io/github/watchers/info-mono/pathshortener?labelColor=383838&color=585858&style=flat-square"></a> <a href="https://github.com/info-mono/pathshortener/stargazers"><img src="https://img.shields.io/github/stars/info-mono/pathshortener?labelColor=383838&color=585858&style=flat-square"></a> <a href="https://github.com/info-mono/pathshortener/network/members"><img src="https://img.shields.io/github/forks/info-mono/pathshortener?labelColor=383838&color=585858&style=flat-square"></a> <a href="https://github.com/info-mono/pathshortener/issues"><img src="https://img.shields.io/github/issues/info-mono/pathshortener?labelColor=383838&color=585858&style=flat-square"></a></p>

## 💡 About
`pathshortener` is a file system's path shortener written in [`portable sh`](https://github.com/dylanaraps/pure-sh-bible) inspired by [Fish's `prompt_pwd` command](https://fishshell.com/docs/current/cmds/prompt_pwd.html) and [Starship's Directory module](https://starship.rs/config/#directory).

## 🚀 Setup
### 🧾 Dependencies
- `sh` to process

### 📥 Installation
#### 🔧 Manually
- Option 1: using `curl`

```sh
curl https://raw.githubusercontent.com/info-mono/pathshortener/main/bin/pathshortener > ~/.local/bin/pathshortener
chmod +x ~/.local/bin/pathshortener
```

- Option 2: using `git`

```sh
git clone https://github.com/info-mono/pathshortener.git ~/.local/share/pathshortener
ln -s ~/.local/share/pathshortener/bin/pathshortener ~/.local/bin/pathshortener
```

#### 📦 Package manager
For [`bpkg`](https://github.com/bpkg/bpkg) user:

```sh
bpkg install info-mono/pathshortener
```

For [Basher](https://github.com/bpkg/bpkg) user:

```sh
basher install info-mono/pathshortener
```

> *If you can and want to port Pathshortener to other package managers, feel free to do so.*

## ⌨️ Usage
Run 'pathshortener' in the terminal:

```sh
pathshortener PATHS
```

## ⚙️ Configuration
Pathshortener is configured through environment variables: `export PATHSHORTENER_<SETTING>="<value>"`

|Value                            |Valid      |Default|Description                                                                                           |
|---------------------------------|-----------|-------|------------------------------------------------------------------------------------------------------|
|`PATHSHORTENER_TRUNCATION_LENGTH`|`<integer>`|`3`    |The number of parent folders that the current directory should be truncated to (set to `0` to disable)|
|`PATHSHORTENER_SHORT_LENGTH`     |`<integer>`|`0`    |The number of characters to display in truncated paths                                                |
|`PATHSHORTENER_TRUNCATION_SYMBOL`|`<string>` |`…/`   |The symbol to prefix to truncated paths                                                               |
|`PATHSHORTENER_HOME_SYMBOL`      |`<string>` |`~`    |The symbol indicating home directory                                                                  |

## 💌 Credits
Special thanks to:
- [**Fish**](https://fishshell.com/docs/current/cmds/fish_status_to_signal.html) by [it's contributors](https://github.com/fish-shell/fish-shell/graphs/contributors)
- [**Starship**](https://starship.rs/) by [it's contributors](https://github.com/starship/starship/graphs/contributors)

<br><br><br><br>

---

> <h1 align="center">Made with ❤️ by <a href="https://github.com/info-mono"><code>@info-mono</code></a></h1>
>
> <p align="center"><a href="https://www.buymeacoffee.com/nnbnh"><img src="https://img.shields.io/badge/buy_me_a_coffee%20-%23F7CA88.svg?logo=buy-me-a-coffee&logoColor=333333&style=for-the-badge" alt="Buy Me a Coffee"></p>

<h3 align="center">
	<img src="https://github.com/everviolet/.github/raw/main/assets/logo-circle.png" width="100" alt="Logo"/><br/>
	Evergarden for <a href="https://github.com/tmux/tmux">Tmux</a>
</h3>

<p align="center">
	<a href="https://github.com/everviolet/tmux/stargazers"><img src="https://img.shields.io/github/stars/everviolet/tmux?style=for-the-badge&colorA=313B40&colorB=DBBC7F"></a>
	<a href="https://github.com/everviolet/tmux/issues"><img src="https://img.shields.io/github/issues/everviolet/tmux?style=for-the-badge&colorA=313B40&colorB=E69875"></a>
	<a href="https://github.com/everviolet/tmux/contributors"><img src="https://img.shields.io/github/contributors/everviolet/tmux?style=for-the-badge&colorA=313B40&colorB=97C9C3"></a>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/everviolet/tmux/main/assets/previews/preview.webp"/>
</p>

### Previews

<details>
<summary>Winter</summary>
<img src="https://raw.githubusercontent.com/everviolet/tmux/main/assets/previews/winter.webp"/>
</details>
<details>
<summary>Fall</summary>
<img src="https://raw.githubusercontent.com/everviolet/tmux/main/assets/previews/fall.webp"/>
</details>
<details>
<summary>Spring</summary>
<img src="https://raw.githubusercontent.com/everviolet/tmux/main/assets/previews/spring.webp"/>
</details>

### Usage

2. copy the `themes/` directory to tmux plugins `~/.tmux/plugins/evergarden-tmux`
3. add `run ~/.tmux/plugins/evergarden-tmux/evergarden.sh` to your `.tmux.conf`

The default theme is `fall`. If you want to change the theme to `winter` or `spring` you need to explicitly set the `@evergarden_style` before running `evergarden.sh`.
```tmux
# .tmux.conf

set -gq @evergarden_style "winter"

run ~/.tmux/plugins/evergarden-tmux/evergarden.sh
```

### Thanks to <3

- [qapquiz](https://github.com/qapquiz)
- [comfysage](https://github.com/comfysage)

<hr>

<p align="center">
	<a href="https://github.com/comfysage/evergarden/blob/mega/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=LICENSE&message=GPL3&colorA=313B40&colorB=9BB5CF"/></a>
</p>

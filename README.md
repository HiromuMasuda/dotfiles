# dotfiles

## initial settings

```
ln -sf ~/dotfiles/vimrc ~/.vimrc
ln -sf ~/dotfiles/zshrc ~/.zshrc
ln -sf ~/dotfiles/tmux.conf ~/.tmux.conf
ln -sf ~/dotfiles/gitconfig ~/.gitconfig
```

## .vimrc
### dein
- [Shougo/dein.vim - ReadMe](https://github.com/Shougo/dein.vim)
- [Shougo/dein.vim - Command](https://github.com/Shougo/dein.vim/blob/master/doc/dein.txt)

```
:call dein#install()
:call dein#update()
```

### NERDTree

| コマンド| 説明 |
|:-----------|:------------|
|o(enter)|ファイルを開く|
|go|ファイルを開き、カーソルはツリーに保持する|
|t|タブで開く|
|T|タブで開き、移動はしない|
|i|水平分割して開く|
|gi|水平分割して開き、移動はしない|
|s|垂直分割して開く|
|gs|垂直分割して開き、移動はしない|
|o(enter)|フォルダを開く|
|O|再帰的にディレクトリをすべて開く|
|x|親ディレクトリを閉じる|
|X|再帰的にすべての子ディレクトリを閉じる|
|P|ルートディレクトリへ移動|
|p|親ディレクトリへ移動|
|K|一番上へ移動|
|J|一番下へ移動|
|C|ツリーのルートを選択したディレクトリに変更|
|u|ツリーのルートを上の階層にする|
|U|変更前のツリーの状態を保持して、ツリーのルートを上の階層にする|
|r|選択したディレクトリをリフレッシュする|
|R|ツリーのルートをリフレッシュする|
|m|メニューを表示する|
|I|隠しファイルの表示、非表示|
|F|ファイルの表示・非表示|

### Ag
|コマンド|内容
:-----:|--------------
e |                  開くと同時に終了
o |                  開く
go|                  プレビュー
t |                  タブで開く
T |                  タブで開く(silently)
h |                  水平分割で開く
H |                  水平分割で開く(silently)
v |                  垂直分割で開く
gv|                  垂直分割で開く(silently)
q |                  終了


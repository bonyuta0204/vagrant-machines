# Windows向け環境構築

## 入るもの
デフォルトで
- Ubuntu LTS 18.04のインストール
- dockerのインストール
- gitなど各種ツールのインストール
- vim, neovim, fishなどの各種設定ツール
が入ります。

個人的にカスタマイズしている部分があるので、
`site.yml`の`roles`の中から、いらないものは適当にコメントアウトして使って下さい

## リポジトリのセットアップ
```
git submodule update --init
```


## 仮想マシンの設定
### 1. 必要なソフトウェアのインストール
VagrantとVirtualboxのインストールを行う

### 2. 仮想マシンの立ち上げ
マシンを作成するディレクトリに移動し、`vagrant up` で仮想マシンを立ち上げる

#### ex.)
```
cd ubuntu-bionic-beaver/
vagrant up
```

## 仮想マシンへの接続
```
vagrant ssh
```

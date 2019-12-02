# Windows向け環境構築

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
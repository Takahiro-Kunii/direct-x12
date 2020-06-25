# direct-x12
DirectX 12の使い方

## プログラミング ガイド
公式を読むのが正当だと思う。

### 公式Direct3D 12 プログラミング ガイド
https://docs.microsoft.com/ja-jp/windows/win32/direct3d12/directx-12-programming-guide

## Toolkitについて
Direct X Tool kitはDirect Xを使う上で便利な機能をまとめたもの。
DirectXTexにも含まれるので、こちらを加えるのが簡単。

### DirectXTex
https://github.com/microsoft/DirectXTK12

Wikiに最新Nugetが紹介されていたので、git cloneではなくNugetのインストールを使った。パス設定等が省略できる。

### Direct X Tool kit
単独はこちら
https://github.com/microsoft/DirectXTex

## ヘッダー D3dx12.h について
DirectXを使う上で役立つヘルパーをまとめたヘッダーファイルは以下の公式のサンプルに含まれている。
なぜこのような提供の仕方をするかは不明だが、公式のセットアップページでも、この公式のサンプル：DirectX-Graphics-Samples\Libraries\D3DX12から取り出せと書かれている。

### 公式のサンプル
https://github.com/microsoft/DirectX-Graphics-Samples

### 公式のセットアップページ
https://docs.microsoft.com/ja-jp/windows/win32/direct3d12/directx-12-programming-environment-set-up

公式のサンプルをGitHubから丸ごとクローンして、以下のパスをプロジェクトプロパティに追加インクルード参照パスとして設定した。

```
{クローン先}DirectX-Graphics-Samples\Libraries\D3DX12
```

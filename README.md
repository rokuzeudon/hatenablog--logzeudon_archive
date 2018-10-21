[@rokuzeudon](https://github.com/rokuzeudon)の個人ブログ用テーマです。
株式会社はてな様のデザインテーマ[Hatena-Blog-Theme-Boilerplate](https://github.com/hatena/Hatena-Blog-Theme-Boilerplate)をベースにしています。

# 条件

- [Node.js](https://nodejs.org/)

# インストール

```
$ git clone git@github.com:rokuzeudon/blog.rokuzeudon.com.git
$ cd blog.rokuzeudon.com
$ npm install
```

# 始め方

`$ npm start`

## 任意

テーマ検証に使う[はてなブログ](https://blog.hatena.ne.jp/)を用意し、
`デザイン設定 > カスタマイズ > デザインCSS` に下記を保存します。

```
/* Responsive: yes */
@import url("http://localhost:3000/style.css");
```

npm実行中、出力した`style.css`が検証用ブログに反映されるようになります。

# 構造

```
blog.rokuzeudon.com/
┣┳ scss/
┃┗┳ lib/
┃ ┗ about.scss
┃ ┗ style.scss
┗┳ build/
 ┃ about.css
 ┗ style.css
```

aboutページのためだけの記述が多かったので、ファイルを分けて出力し、aboutページ内にインラインで保存するようにしている。

# ライセンス

Released under the CC BY 2.1 JP License.  
[クリエイティブ・コモンズ　リーガル・コード](https://creativecommons.org/licenses/by/2.1/jp/legalcode)

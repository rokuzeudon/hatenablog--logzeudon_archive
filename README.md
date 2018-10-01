# Requirements

- [Node.js](https://nodejs.org/)

# Installation

```
$ git clone git@github.com:rokuzeudon/blog.rokuzeudon.com.git
$ cd blog.rokuzeudon.com
$ npm install
```

# Usage

`$ npm start`

## Optional

テーマ検証に使う[はてなブログ](https://blog.hatena.ne.jp/)を用意し、
`デザイン設定 > カスタマイズ > デザインCSS` に下記を保存します。

```
/* Responsive: yes */
@import url("http://localhost:3000/style.css");
```

npm実行中、出力した`style.css`が検証用ブログに反映されるようになります。

# Structure

```
blog.rokuzeudon.com/
┣┳ scss/
┃┗┳ lib/
┃ ┗ style.scss
┗┳ build/
 ┗ style.css
```

# License

Released under the CC BY 2.1 JP License.  
[クリエイティブ・コモンズ　リーガル・コード](https://creativecommons.org/licenses/by/2.1/jp/legalcode)

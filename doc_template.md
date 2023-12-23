---
marp: true
theme: test
---
<!-- 
marp使い方参考サイト
https://qiita.com/tomo_makes/items/aafae4021986553ae1d8
https://qiita.com/aikige/items/be0bcfea8768e1cf02b8
 -->

<!-- 
backgroundColor: #e0e0e0
_class: title
 -->

# タイトルページ

日付 / 所属 / 作者名

----

<!-- 
header: スライドテンプレ
footer: 2023/12 ICDC アルゴ部 1課 中西
-->

# アジェンダ
1. hoge
    1. hoge
    1. hoge
1. hoge
    1. hoge
    1. hoge

----

<!-- paginate: true -->
<!-- class: slides -->

# 本文１

本文はここから書いていく

----

# 本文２

体裁は気にせず、文書の内容に注力できるようにしよう

----

# 見た目のこだわり

## 文字の見た目
- 真っ白とか真っ黒はセンスがないので使わない。ちょっとグレーに寄せる

## 図の見た目
- 余白は多めにとって見やすい図を心がける
- ごちゃごちゃと詰め込まない

----

# MarpのカスタムテーマをVSCodeに読み込ませる
## VSCode側で設定を変更する必要があります。

- VSCodeの設定で、下図の項目を探して「項目の追加」をクリック
- 自作したテーマの設定を記述したCSSファイルのパスを指定する
    - フォルダ区切りは"`\\`"なので注意

![height:150](figure/marp%E3%81%AE%E3%82%AB%E3%82%B9%E3%82%BF%E3%83%A0%E3%83%86%E3%83%BC%E3%83%9E%E3%81%AECSS%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E6%8C%87%E5%AE%9A.png)

> メニューバーの「ファイル」→「ユーザー設定」→「設定」を開いて「markdown marp themes」で検索すれば見つかる。

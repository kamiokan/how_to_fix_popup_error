# how_to_fix_popup_error
====

chromeバージョン76で急にポップアップブロックエラーが発生した時の対処

## Description

&lt;a href="javascript:void(window.open('https://yahoo.co.jp', '', 'width=500,height=650') target="_blank"&gt;ポップアップで開く&lt;/a&gt;

という書き方で別ウィンドウで別ページを開く処理を行っていた。

が、chromeバージョン76になってから「ポップアップブロック」の対象に。

WEBアプリ内で遷移先のURL部分を「/」始まりにしていると、Chromeのポップアップ許可でも対応できない。

target="_blank" を消したら、うまくいった。

## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author

nobuhiro kamioka


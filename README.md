作成上の注意（中鉢 2012-09-02）
- texliveパッケージを利用（Ubuntuはaptで, Winはインストーラで導入）
- 漢字コードはEUCを使用．プリアンプルに設定．
- jbiblatexを用いるので，.emacs.d/init.elにその旨を設定
   -> http://oku.edu.mie-u.ac.jp/~okumura/texwiki/?YaTeX#j78164d5
- 従来提供されていたipsjunsrt.bstがないのでjunsrt.bstで代用
- ipsjのクラスファイルでcopyrightがwarningになるので修正
- bibtexが生成する\newblockがないので追加
- dummy.texを使用
- bibliographyはサブモジュールにした．

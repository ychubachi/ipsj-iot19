作成上の注意（中鉢 2012-09-02）
- texliveパッケージを利用（Ubuntuのaptは古い）
- 漢字コードはUTF-8を使用．プリアンプルに設定．
- dummy.texを使用
- bibtexが生成する\newblockがないので追加
- pbibtexなどの設定を.emacs.d/init.elに行う
   -> http://oku.edu.mie-u.ac.jp/~okumura/texwiki/?YaTeX#j78164d5
- 従来提供されていたipsjunsrt.bstがないのでjunsrt.bstで代用
- ipsjのクラスファイルでcopyrightがwarningになるので修正
- bibliographyはサブモジュールにした．cloneしたら，git submodule init後，git submodule updateする．


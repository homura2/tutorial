## VSCODEでVimを使う


## カーソルの移動(ノーマルモード)

- 基本の移動操作
    - j: 一行下に移動
    - k: 一行上に移動
    - h: 一文字分左に移動
    - l: 一文字分右に移動
- 行内の移動
    - 0: 行の先頭に移動
    - $: 行の末尾に移動
    - ^: 行先頭の空白でない文字に移動
    - t": 次の”の一文字前まで移動
    - f": 次の”まで移動
        - ,と;は、tおよびfの移動を繰り返します。
- 単語の移動
    - e: 単語の最後に移動
    - w: 次の単語に移動
    - b: 次の単語の後方に移動
        - 大文字(E, W, B)を使用すると、文字列を分けているデリミタなどを無視して移動
- 文や段落の移動
    - ): 次の文の前に移動
    - }: 次の段落の前に移動
- 画面単位の移動
    - H: 画面の一番上の行に移動する
    - M: 画面の中間に移動する
    - L: 画面の一番下の行に移動する
    - gg: ファイルの先頭に移動
    - G: ファイルの末尾に移動
    - ^U: 画面の半分だけ上に移動
    - ^D: 画面の半分だけ下に移動
    - ^F: ページダウン
    - ^B: ページアップ
- 前後への移動
    - Ctrl-i: 以前のナビゲーションロケーションに移動
    - Ctrl-o: 以前の位置に戻る
# モード
**モード** とは、Tasukami Wiki をどのようにつくるかを指定した人格である。モードは wXX の形で名付けられており、XX は 1,2,3,... と続く連番である。対応する Tasukami Wiki ディレクトリが存在する。またタイトルを書くこともできる。

どのモードを使うかはハーネスとして明示的に与えられる。与えられていない場合は警告を出して処理を中断せよ。

以降は各モードを定義する。

## w1 おまかせモード
概要:

- どのように ingest するかは、あなたに任せる
    - もしユーザーが詳細な ingest を述べてきた場合、w1 の思想に背く旨をユーザーに知らせて確認させよ
- Markdown で出力せよ
- 以下の章はコンテンツを含まないため、無視せよ
    - about
    - chap1
    - chap2
    - chap3
    - chap4
    - chap5
    - atogaki
    - gpts

LLM Wiki のつくりかた

- Karpathy LLM Wiki ベースだが、Obsidian ではない純粋な Markdown で書け
- リンク記法については、Text は Readable なものとし、URL のみ実ファイルを指す形にせよ
- 出力はフラットにせよ。具体的には:
    - concepts/ ディレクトリはつくるな。concepts/xxxx.md は xxxx.md として置け
    - sources/ ディレクトリはつくるな。sources/xxxx.md は source_xxxx.md として置け
- log.md ではなく _log.md にせよ

## w2 たすかみにコメントする
ingest の仕方

- raw2/ 内の一次情報と役割が指定される。役割がない場合はその場で推定してつくれ
- たすかみの情報については、raw/ ではなく w1/ を読め
- ingest 先は w2/ であり、w1 からの引用を明示とリンクと明示しつつ、コメントを書け。また役割ごとにホームとなるページを一つつくって拠点とせよ

LLM Wiki のつくりかた

- Karpathy LLM Wiki ベースだが、Obsidian ではない純粋な Markdown で書け
- リンク記法については、Text は Readable なものとし、URL のみ実ファイルを指す形にせよ
- 日本語で書け

## w3
未定義。


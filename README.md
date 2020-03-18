# 動態マクロ経済学（大阪府立大学・2020年度前期）

## 基本情報

- 毎週金曜日5限（C5棟・情報教育教室 Cスパン）
- 対象受講者：大阪府立大学 3,4回生（主に，現シスの学類生）
- 受講定員：45名
- 講義担当者： 佐藤 健治 <https://www.kenjisato.jp>


## トピック

[準備中]

- Ch01
  - 


## 講義資料

この GitHub レポジトリに講義資料を掲載する予定です。資料中で利用しているデータの生データ（官公庁が公開しているもの），前処理に用いたコードも合わせて掲載する予定です（R or Python）。ただし，容易にダウンロードできるデータセットはリンクのみ掲載します。

**お断り**  

すべて資料をウェブ公開できるかどうかは分かりません。


### ファイル構成

受講生は主に 

- Lecture Notes
- Jupyter

の2つのフォルダを参照してください。

#### Lecture Notes

講義資料の PDF ファイルを置いています。LyX ファイルは PDF を作成するために使ったファイルです。通常，.lyx がついたファイルを開く必要はありません。


#### Jupyter

このフォルダの中に

- 講義資料に挿入されているコード
- 講義資料の図を作成するために使ったコード
- 講義の付属資料としての練習問題（追加予定）

が含まれています。.ipynb で終わるファイルを表示すると GitHub 上で内容を閲覧できます。


**Colaboratory**

[Colaboratory](https://colab.research.google.com/) を使うと手元に Python/Anaconda 環境がなくてもコードを試すことができます。次の手順でノートブックを開いてください。

1. [Colaboratory](https://colab.research.google.com/) にアクセス
1. ファイル → ノートブックを開く
1. GitHub タブをクリック
1. 検索欄に「 kenjisato/MaD 」を入力する
1. 一覧から開きたいノートブックを選ぶ


#### その他

他のフォルダの役割は次の通りです。


    .
    ├── Bibliography       参考文献リスト
    ├── Jupyter            講義資料・スライドに埋め込むコード
    ├── Lecture\ Notes     LyX ファイル, PDF ファイル
    │   ├── Data           使用データ Raw Data を元に変換・加工されたファイル
    │   ├── Figure         コードから生成された図
    │   ├── Images         手書き（keynote, draw.io）の図
    │   ├── Knitr          コード埋め込みのための設定ファイル
    │   ├── Python         Jupyter から変換された Python コード
    │   └── Styles         LaTeX のスタイルファイル
    ├── R                  データラングリングのための R コード
    └── Raw\ Data          元データ
        └── SNA
      
      
### 修正について

この講義ノートは個人的かつ未編集な資料集です。修正すべき内容も多分に含まれていると思います。どうしても放ってはおけないとお考えの方は，[Issue](https://github.com/kenjisato/MaD/issues) でお知らせいただけますと幸いです。

コードや文章の修正にご協力いただける方は Fork から Pull Request をお願いします。その際，誠にご面倒ではありますが，Pull Requestのメッセージに，以下の2文を挿入していただくようにお願いします。

- この貢献に対する著作権の全部を佐藤健治に譲渡する。
- この貢献について、佐藤健治及び佐藤健治が指定する第三者に対して著作者人格権を行使しない。





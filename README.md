# Pythonと入門計量経済学

神戸大学経済学部・[春山ゼミ](https://haruyama-kobeu.github.io)で使う資料集

### 目的
* 初歩的な`Python`の使い方を学ぶ。
* 計量分析のための`Python`の使い方を学ぶ。

（注意）

* 授業の目的は`Python`の使い方を学ぶことであり，計量経済学については各自復習すること。
* このレポの`.ipynb`ファイルは，コードが書けるようにコード・セルは空白になっている。授業中にコードを書くことができるように授業前にダウンロードし，Jupyter Notebookを起動しファイルを読み込んで準備すること。
* コード・セルを実行した結果は「[Pythonで学ぶ入門計量経済学](https://py4etrics.github.io)」で確認することがきる。

### 教科書
[Pythonで学ぶ入門計量経済学](https://py4etrics.github.io) &nbsp; ← ← ← ← ←  &nbsp;:snake:+:chart_with_upwards_trend:

### 内容
* Part I: `Python`について
  1. [ツールの設定](https://haruyama-kobeu.github.io/book_etrics/docs/0_Preparations.html)
  1. [Pythonの基本](https://haruyama-kobeu.github.io/book_etrics/docs/1_Python_Basics.html)
  1. [NumPy](https://haruyama-kobeu.github.io/book_etrics/docs/2_NumPy.html)
  1. [Pandas](https://haruyama-kobeu.github.io/book_etrics/docs/3_Pandas.html)
  1. [Matplotlib](https://haruyama-kobeu.github.io/book_etrics/docs/4_Matplotlib.html)
  1. [SciPy.stats](https://haruyama-kobeu.github.io/book_etrics/docs/5_SciPy_stats.html)
  1. [Python使用上のTipsと注意点](https://haruyama-kobeu.github.io/book_etrics/docs/6_things_to_note.html)
* Part II: `Python`を使った計量経済分析
  1. [統計学の簡単な復習](https://haruyama-kobeu.github.io/book_etrics/docs/7_Review_of_Statistics.html)
  1. [単回帰分析](https://haruyama-kobeu.github.io/book_etrics/docs/8_Simple_Regression.html)
  1. [重回帰分析](https://haruyama-kobeu.github.io/book_etrics/docs/9_Multiple_Regression.html)
  1. [残差分析](https://haruyama-kobeu.github.io/book_etrics/docs/10_Residuals.html)
  1. [推論（検定）](https://haruyama-kobeu.github.io/book_etrics/docs/11_Inference.html)
  1. [大標本特性](https://haruyama-kobeu.github.io/book_etrics/docs/12_Asymptotics.html)
  1. [質的変数と回帰分析](https://haruyama-kobeu.github.io/book_etrics/docs/13_Dummies.html)
  1. [不均一分散](https://haruyama-kobeu.github.io/book_etrics/docs/14_Heteroskedasticity.html)
  1. [プーリング・データとパネル・データ](https://haruyama-kobeu.github.io/book_etrics/docs/15_Pooling.html)
  1. [linearmodels](https://haruyama-kobeu.github.io/book_etrics/docs/16_linearmodels.html)
  1. [パネル・データ分析](https://haruyama-kobeu.github.io/book_etrics/docs/17_Panel.html)
  1. [GM仮定４が満たされない場合](https://haruyama-kobeu.github.io/book_etrics/docs/18_Zero_Conditional_Mean.html)
  1. [操作変数法と２段階OLS](https://haruyama-kobeu.github.io/book_etrics/docs/19_IV2SLS.html)
  1. [離散選択モデル](https://haruyama-kobeu.github.io/book_etrics/docs/20_LogitProbit.html)
  1. [制限従属変数モデル](https://haruyama-kobeu.github.io/book_etrics/docs/21_TruncregTobitHeckit.html)
* Part III: 番外編
  1. [Gapminderのデータを使って](https://haruyama-kobeu.github.io/book_etrics/docs/Gapminder.html)
      * [Gapminderのサイト](https://www.gapminder.org)
  1. [記述統計とグラフ](https://haruyama-kobeu.github.io/book_etrics/docs/Descriptive_stats_vs_Graphs.html)

### 参考書
* `Python`の参考書
  * [春山ゼミのサイト](https://haruyama-kobeu.github.io/#Python)に無料のものも含めていくつか挙げているが，個人的には[Python for Data Analysis](https://op.lib.kobe-u.ac.jp/opac/opac_search/?lang=0&amode=2&cmode=0&smode=0&kywd=Python+for+Data+Analysis)が分かりやすい。
  * 日本の「東西横綱大学」が出している参考書もオススメ:
    * 東京大学：
        * [Pythonプログラミング入門 (html版)](https://utokyo-ipp.github.io)
        * [Pythonプログラミング入門 (pdf版)](https://utokyo-ipp.github.io/IPP_textbook.pdf)
    * 京都大学：
        * [プログラミング演習 Python 2019](https://repository.kulib.kyoto-u.ac.jp/dspace/bitstream/2433/245698/1/Version2020_02_13_01.pdf)
        * [プログラミング演習 Python 2019( コラム編 )](https://repository.kulib.kyoto-u.ac.jp/dspace/bitstream/2433/245698/2/Version2020_02_13_02.pdf)
* 計量経済学の参考書
  * [Introductory Econometrics: A Modern Approach, by J.M. Wooldridge](https://op.lib.kobe-u.ac.jp/opac/opac_search/?lang=0&amode=2&cmode=0&smode=0&kywd=Introductory+Econometrics%3A+A+Modern+Approach) (古い版でもOK)
  * 授業ではこの本で扱われているデータを使う。
  * 他の本でも良いが，著者によって仮定が少し違ってくるので注意すること。

### `Python`について
* `Python`のインストールには[Anaconda](https://www.anaconda.com/distribution/)を使う。
  * 授業ではJupyter Notebook（Anacondaに含まれている）を使用する。
* `pip`を使ってインストールする必要があるパッケージ
  * [linearmodels](https://pypi.org/project/linearmodels/)
  * [wooldridge](https://pypi.org/project/wooldridge/)
  * [lmdiag](https://pypi.org/project/lmdiag/)
  * [see](https://pypi.org/project/see/)
  * 使い方：`pip install バッケージ名`

### `Github`について
* 授業では[Github](https://github.com)を使用する。
  * [git](https://git-scm.com)
  * [参考リンク１](https://happygitwithr.com/install-git.html)
  * [参考リンク２](https://employment.en-japan.com/engineerhub/entry/2017/01/31/110000)
  * [参考リンク３](https://qiita.com/nnahito/items/565f8755e70c51532459)
* 毎回ゼミ終了後に作成・修正したJupyter NotebookをGitHubにuploadすること。

### `Terminal`について
* 使い方についての日英対訳
  * 英語：[The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
  * 日本語：[The Art of Command Line](https://github.com/jlevy/the-art-of-command-line/blob/master/README-ja.md)
* `Finder`からカレント・デイレクトリを指定して`Terminal`を開くアプリ
  * [cd to...](https://github.com/jbtule/cdto)
* `Shell`のコマンドを説明してくれるサイト（英語）
  * [ExplainShell.com](https://explainshell.com)

### [DataCamp](https://www.datacamp.com)について
* このサービスを使い宿題をだします。
* Subscription Feeを支払う必要はありません。
* この[リンク](https://haruyama-kobeu.github.io/#DataCamp)を参考にして自習に役立ててください。

### オープン・データ
* [IMF Data](https://data.imf.org/?sk=388dfa60-1d26-4ade-b505-a05a558d9a42)
* [地域経済分析システム](https://resas.go.jp/)
* [data.gov](https://www.data.gov)
* [DBpedia](https://wiki.dbpedia.org)
* [figshare](https://figshare.com)

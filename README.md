# Pythonと入門計量経済学

神戸大学経済学部・[春山ゼミ](https://haruyama-kobeu.github.io)で使う資料集

### 目的
* 初歩的な`Python`の使い方を学ぶ。
* 計量分析のための`Python`の使い方を学ぶ。

（注意）
授業の目的は`Python`の使い方を学ぶことであり，計量経済学については各自復習すること。

### 内容
* Part I: `Python`について
  1. [ツールの設定](https://nbviewer.jupyter.org/github/Haruyama-KobeU/Py4Basics/blob/master/0_Preparations.ipynb)
  1. [Pythonの基本](https://nbviewer.jupyter.org/github/Haruyama-KobeU/Py4Basics/blob/master/1_Python_Basics.ipynb)
  1. [NumPy](https://nbviewer.jupyter.org/github/Haruyama-KobeU/Py4Basics/blob/master/2_NumPy.ipynb)
  1. [pandas](https://nbviewer.jupyter.org/github/Haruyama-KobeU/Py4Basics/blob/master/3_Pandas.ipynb)
  1. [matplotlib](https://nbviewer.jupyter.org/github/Haruyama-KobeU/Py4Basics/blob/master/4_Matplotlib.ipynb)
  1. [scipy.stats](https://nbviewer.jupyter.org/github/Haruyama-KobeU/Py4Basics/blob/master/5_SciPy_stats.ipynb)
  1. [Python使用上の注意点](https://github.com/Haruyama-KobeU/Py4Basics/blob/master/6_things_to_note.ipynb)
* Part II: `Python`を使った計量経済分析 (Access for students in class only)
  1. [統計学の簡単な復習](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/7_Review_of_Statistics.ipynb)
  1. [単回帰分析](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/8_Simple_Regression.ipynb)
  1. [重回帰分析](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/9_Multiple_Regression.ipynb)
  1. [残差分析](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/10_Residuals.ipynb)
  1. [推論（検定）](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/11_Inference.ipynb)
  1. [漸近的特性（大標本）](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/12_Asymptotics.ipynb)
  1. [ダミー変数](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/13_Dummies.ipynb)
  1. [不均一分散](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/14_Heteroskedasticity.ipynb)
  1. [プーリング・データとパネル・データ](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/15_Pooling.ipynb)
  1. [linearmodels](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/16_linearmodels.ipynb)
  1. [パネル・データ分析](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/17_Panel.ipynb)
  1. [GM仮定４が満たされない場合](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/18_Zero_Conditional_Mean.ipynb)
  1. [操作変数法と２段階OLS](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/19_IV2SLS.ipynb)
  1. [離散選択モデル](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/20_LogitProbit.ipynb)
  1. [制限従属変数モデル](https://github.com/Haruyama-KobeU/Py4Etrics/blob/master/21_TobitHeckit.ipynb)
* Part III: 番外編
  1. [Gapminderのデータを使って](https://nbviewer.jupyter.org/github/Haruyama-KobeU/Py4Basics/blob/master/Gapminder.ipynb)
      * [Gapminderのサイト](https://www.gapminder.org)
  1. [記述統計とグラフ](https://nbviewer.jupyter.org/github/Haruyama-KobeU/Py4Basics/blob/master/Descriptive_stats_vs_Graphs.ipynb)

### 参考書
* `Python`の参考書
  * [春山ゼミのサイト](https://haruyama-kobeu.github.io/#Python)に無料のものも含めていくつか挙げているが，個人的には[Python for Data Analysis](https://op.lib.kobe-u.ac.jp/opac/opac_search/?lang=0&amode=2&cmode=0&smode=0&kywd=Python+for+Data+Analysis)が分かりやすい。
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
  * 使い方：`pip install --user バッケージ名`

### `Github`について
* 授業では[Github](https://github.com)を使用する。
  * [git](https://git-scm.com)
  * [参考リンク１](https://happygitwithr.com/install-git.html)
  * [参考リンク２](https://employment.en-japan.com/engineerhub/entry/2017/01/31/110000)
  * [参考リンク３](https://qiita.com/nnahito/items/565f8755e70c51532459)
* 毎回ゼミ終了後に作成・修正したJupyter Notebookをgithubにuploadすること。

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

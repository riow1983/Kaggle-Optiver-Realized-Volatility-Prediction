# Kaggle-Optiver-Realized-Volatility-Prediction
![](https://github.com/riow1983/Kaggle-Optiver-Realized-Volatility-Prediction/blob/master/png/20210901(3).png?raw=true)<br>
https://www.kaggle.com/c/optiver-realized-volatility-prediction<br>
どんなコンペ?:<br>
開催期間:<br>
[結果]()<br>  
<br>
<br>
<br>
***
## 実験管理テーブル
|commitSHA|comment|Local CV|Public LB|
|----|----|----|----|
<br>

## Late Submissions
|commitSHA|comment|Local CV|Private LB|Public LB|
|----|----|----|----|----|
<br>


## My Assets
[notebook命名規則]  
- kagglenb001-hoge.ipynb: Kaggle platform上で新規作成されたKaggle notebook (kernel).
- nb001-hoge.ipynb: kagglenb001-hoge.ipynbをlocalにpullしlocalで変更を加えるもの. 番号はkagglenb001-hoge.ipynbと共通.
- localnb001-hoge.ipynb: localで新規作成されたnotebook. 
- l2knb001-hoge.ipynb: localnb001-hoge.ipynbをKaggle platformにpushしたもの. 番号はlocalnb001-hoge.ipynbと共通.

#### Code
作成したnotebook等の説明  
|name|url|input|output|status|comment|
|----|----|----|----|----|----|
<br>





***
## 参考資料
#### Snipets
```Python
# Check if A is a subset of B
# A: Set
# B: Set
A.issubset(B)
```
<br>


#### Papers
|name|url|status|comment|
|----|----|----|----|
|Deep Smoothing of the Implied Volatility Surface|[URL](https://arxiv.org/abs/1906.05065)|解読中|-|
|Pricing options and computing implied volatilities using neural networks|[URL](https://arxiv.org/pdf/1901.08943.pdf)|解読中|-|
|Incorporating Prior Financial Domain Knowledge into Neural Networks for Implied Volatility Surface Prediction|[URL](https://arxiv.org/pdf/1904.12834.pdf)|解読中|社内発表か|
|Gated Neural Networks for Option Pricing: Rationality by Design|[URL](https://arxiv.org/pdf/1609.07472.pdf)|解読中|-|
|Gaussian Process Volatility Model|[URL](https://arxiv.org/pdf/1402.3085.pdf)|解読中|-|
|Financial Time Series Volatility Analysis Using Gaussian Process State-Space Models|[URL](https://www.ee.ryerson.ca/~xzhang/publications/globalsip2015-gpsv.pdf)|解読中|-|
|An Overview of Gaussian process Regression for Volatility Forecasting|[URL](https://www.oxford-man.ox.ac.uk/wp-content/uploads/2020/06/An-Overview-of-Gaussian-process-Regression-for.pdf)|解読中|-|
|A Bayesian take on option pricing with Gaussian processes|[URL](https://www.robots.ox.ac.uk/~mt/pdfFiles/GPLV.pdf)|解読中|-|
|HTML: Hierarchical Transformer-based Multi-task Learning for Volatility Prediction|[URL](https://www.researchgate.net/publication/340385140_HTML_Hierarchical_Transformer-based_Multi-task_Learning_for_Volatility_Prediction)|解読中|-|
|金融危機時における株式市場の期待変動：インプライド・モーメントとジャンプ拡散過程を用いた分析|[URL](https://www.imes.boj.or.jp/research/papers/japanese/kk29-3-3.pdf)|解読中|-|
|初期分布探索付き自己組織化状態空間モデルによる金融時系列解析の最前線：t分布付き確率的ボラティリティ変動モデルへの応用|[URL](https://www.fsa.go.jp/frtc/nenpou/2006a/05.pdf)|解読中|-|
|時系列データにおけるボラティリティ推定についてVolatility Estimation in Time Series Data|[URL](https://ipsj.ixsq.nii.ac.jp/ej/?action=repository_action_common_download&item_id=184473&item_no=1&attribute_id=1&file_no=1)|解読中|-|
|t過程ボラティリティ変動モデル|[URL](https://sigfin.org/?plugin=attach&refer=025-13&openfile=13_SIG-FIN-25.pdf)|解読中|-|
|Forecasting Volatility in Financial Markets: A Review|[URL](https://faculty.washington.edu/ezivot/econ589/PoonGrangerJELsurvey.pdf)|解読中|-|
|Modeling and Forecasting Implied Volatility – an Econometric Analysis of the VIX Index|[URL](https://core.ac.uk/download/pdf/14912922.pdf)|解読中|-|
|A practical guide to volatility forecasting through calm and storm|[URL](https://www.sas.upenn.edu/~fdiebold/papers/misc/Brownlees.pdf)|解読中|-|
|Forecasting the Volatility of Financial Markets: ARCHIGARCH Models and the AUTOREG Procedure|[URL](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.453.5809&rep=rep1&type=pdf)|解読中|SAS社によるSAS procedureの適用例|
|A GARCH Model with Artificial Neural Networks|[URL](https://www.mdpi.com/2078-2489/11/10/489/pdf)|解読中|-|
|A machine learning approach to volatility forecasting|[URL](https://econ.au.dk/fileadmin/site_files/filer_oekonomi/Working_Papers/CREATES/2021/rp21_03.pdf)|解読中|-|
<br>


#### Blogs / Qiita / etc.
|name|url|status|comment|
|----|----|----|----|
|Implied Volatility (IV)|[URL](https://www.investopedia.com/terms/i/iv.asp)|参考|IVの説明|
|ボラティリティには2種類ある、その変動に注目したシンプルな投資戦略と実践例|[URL](https://moneyzine.jp/article/detail/215873)|参考|取引されているオプションの価格から計算される「インプライド・ボラティリティ（Implied Volatility）」に関連した日本語記事|
|Unsupervised learning for anomaly detection in stock options pricing|[URL](https://towardsdatascience.com/unsupervised-learning-for-anomaly-detection-in-stock-options-pricing-e599728958c7)|参考|volatility smileなどが出てきて本コンペと近い問題設定かとも思うがドメイン知識が無いため難解|
|How To Model Volatility Smile In Python|[URL](https://blog.quantinsti.com/volatility-smile-origin-implications/)|参考|PythonによるVolatility Smileの実装方法|
<br>


#### Documentation / Tutorials / StackOverflow / etc.
|name|url|status|comment|
|----|----|----|----|
|Regular expression usage in glob.glob?|[URL](https://stackoverflow.com/questions/13031989/regular-expression-usage-in-glob-glob)|Done|regexによるglob.glob結果の選別方法|
<br>


#### GitHub
|name|url|status|comment|
|----|----|----|----|
<br>


#### Kaggle Notebooks
|name|url|status|comment|
|----|----|----|----|
<br>


#### Kaggle Datasets
|name|url|status|comment|
|----|----|----|----|
<br>

#### Kaggle Discussion
|name|url|status|comment|
|----|----|----|----|
|Forecasting volatility with the ARCH and GARCH models|[URL](https://www.kaggle.com/c/optiver-realized-volatility-prediction/discussion/250998)|読了|ARCH系とその他モデルに関する先行論文など|
<br>



***
## Diary

#### 2021-08-01  
コンペ参加. [tutorial notebook](https://www.kaggle.com/jiashenliu/introduction-to-financial-concepts-and-data?scriptVersionId=67183666#Competition-data)を読んだ.
<br>
<br>
<br>

#### 2021-08-02
`kagglenb001-eda`でデータを見始めた.<br>
<br>
<br>
<br>








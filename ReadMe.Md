# 統計的因果推論関連文献集
統計的因果推論を学んでいくための書籍・論文についてまとめました。  
まずは超入門書 -> 入門書 -> 概説書の順で読み進めて理解を深めたうえで、各種テーマごとの論文に当たっていけると理解が深まると思います。

## 書籍
### 超入門書でまずは考え方を知る
|Id|Name|
|-|-|
|1|[伊藤公一朗 (2017)『データ分析の力 因果関係に迫る思考法』光文社](https://www.amazon.co.jp/%E3%83%87%E3%83%BC%E3%82%BF%E5%88%86%E6%9E%90%E3%81%AE%E5%8A%9B-%E5%9B%A0%E6%9E%9C%E9%96%A2%E4%BF%82%E3%81%AB%E8%BF%AB%E3%82%8B%E6%80%9D%E8%80%83%E6%B3%95-%E5%85%89%E6%96%87%E7%A4%BE%E6%96%B0%E6%9B%B8-%E4%BC%8A%E8%97%A4-%E5%85%AC%E4%B8%80%E6%9C%97/dp/4334039863)|  
|2|[中室牧子・津川祐介 (2017)『「原因と結果」の経済学』ダイヤモンド社](https://www.amazon.co.jp/%E3%80%8C%E5%8E%9F%E5%9B%A0%E3%81%A8%E7%B5%90%E6%9E%9C%E3%80%8D%E3%81%AE%E7%B5%8C%E6%B8%88%E5%AD%A6%E2%80%95%E2%80%95%E2%80%95%E3%83%87%E3%83%BC%E3%82%BF%E3%81%8B%E3%82%89%E7%9C%9F%E5%AE%9F%E3%82%92%E8%A6%8B%E6%8A%9C%E3%81%8F%E6%80%9D%E8%80%83%E6%B3%95-%E4%B8%AD%E5%AE%A4%E7%89%A7%E5%AD%90/dp/447803947X/ref=sr_1_1?adgrpid=51990675783&dchild=1&gclid=Cj0KCQjw3qzzBRDnARIsAECmryqTr9vQnRc_fjirZdUwYq9Fm_z5uvn9clFMCe0jU7M2JPP2KWVIuwwaAndhEALw_wcB&hvadid=338543383096&hvdev=c&hvlocphy=1009279&hvnetw=g&hvqmt=e&hvrand=3083489441769443559&hvtargid=aud-758806828496%3Akwd-333359952402&hydadcr=21805_10989639&jp-ad-ap=0&keywords=%E5%8E%9F%E5%9B%A0%E3%81%A8%E7%B5%90%E6%9E%9C%E3%81%AE%E7%B5%8C%E6%B8%88%E5%AD%A6&qid=1584105367&sr=8-1)|  
|3|[安井翔太 (2020)『効果検証入門 正しい比較のための因果推論/計量経済学の基礎』技術評論社](https://www.amazon.co.jp/%E5%8A%B9%E6%9E%9C%E6%A4%9C%E8%A8%BC%E5%85%A5%E9%96%80%E3%80%9C%E6%AD%A3%E3%81%97%E3%81%84%E6%AF%94%E8%BC%83%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AE%E5%9B%A0%E6%9E%9C%E6%8E%A8%E8%AB%96-%E8%A8%88%E9%87%8F%E7%B5%8C%E6%B8%88%E5%AD%A6%E3%81%AE%E5%9F%BA%E7%A4%8E-%E5%AE%89%E4%BA%95-%E7%BF%94%E5%A4%AA/dp/4297111179/ref=sr_1_1?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&crid=1OBV7VII6R9AD&dchild=1&keywords=%E5%8A%B9%E6%9E%9C%E6%A4%9C%E8%A8%BC&qid=1584105393&sprefix=%E3%81%93%E3%81%86%E3%81%8B%E3%81%91%E3%82%93%E3%81%97%E3%82%87%E3%81%86%2Caps%2C268&sr=8-1)|
   
### 入門書でよりしっかりと学ぶ
|Id|Name|
|-|-|
|1|[岩波データサイエンス刊行委員会編 (2016)『岩波データサイエンスVol.3 [特集]因果推論――実世界のデータから因果を読む』岩波書店](https://www.amazon.co.jp/%E5%B2%A9%E6%B3%A2%E3%83%87%E3%83%BC%E3%82%BF%E3%82%B5%E3%82%A4%E3%82%A8%E3%83%B3%E3%82%B9-Vol-3-%E5%B2%A9%E6%B3%A2%E3%83%87%E3%83%BC%E3%82%BF%E3%82%B5%E3%82%A4%E3%82%A8%E3%83%B3%E3%82%B9%E5%88%8A%E8%A1%8C%E5%A7%94%E5%93%A1%E4%BC%9A/dp/4000298534/ref=sr_1_1?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&crid=2LHKKGKBCT854&dchild=1&keywords=%E5%B2%A9%E6%B3%A2%E3%83%87%E3%83%BC%E3%82%BF%E3%82%B5%E3%82%A4%E3%82%A8%E3%83%B3%E3%82%B9&qid=1584105518&sprefix=%E5%B2%A9%E6%B3%A2%E3%83%87%E3%83%BC%E3%82%BF%2Caps%2C246&sr=8-1)|  
|2|[J. Pearl 他, 落合浩訳 (2019)『入門 統計的因果推論』朝倉書店](https://www.amazon.co.jp/%E5%85%A5%E9%96%80-%E7%B5%B1%E8%A8%88%E7%9A%84%E5%9B%A0%E6%9E%9C%E6%8E%A8%E8%AB%96-Judea-Pearl/dp/4254122411/ref=sr_1_6?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&dchild=1&keywords=%E7%B5%B1%E8%A8%88%E7%9A%84%E5%9B%A0%E6%9E%9C%E6%8E%A8%E8%AB%96&qid=1584105567&sr=8-6)|  
|3|[ヨシュア・アングリスト、ヨーン・ビスケ著 大森義明・小原美紀・田中隆一・野口晴子訳 (2013)『「ほとんど無害」な計量経済学 応用経済学のための実証分析ガイド』NTT出版](https://www.amazon.co.jp/%E3%80%8C%E3%81%BB%E3%81%A8%E3%82%93%E3%81%A9%E7%84%A1%E5%AE%B3%E3%80%8D%E3%81%AA%E8%A8%88%E9%87%8F%E7%B5%8C%E6%B8%88%E5%AD%A6%E2%80%95%E5%BF%9C%E7%94%A8%E7%B5%8C%E6%B8%88%E5%AD%A6%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AE%E5%AE%9F%E8%A8%BC%E5%88%86%E6%9E%90%E3%82%AC%E3%82%A4%E3%83%89-%E3%83%A8%E3%82%B7%E3%83%A5%E3%82%A2%E3%83%BB%E3%82%A2%E3%83%B3%E3%82%B0%E3%83%AA%E3%82%B9%E3%83%88/dp/4757122519/ref=sr_1_1?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&dchild=1&keywords=%E3%81%BB%E3%81%A8%E3%82%93%E3%81%A9%E7%84%A1%E5%AE%B3&qid=1584105598&sr=8-1)|  
   
### 概説書でより本格的に勉強していく
|Id|Name|
|-|-|
|1|[星野崇宏 (2009)『調査観察データの統計化学――因果推論・選択バイアス・データ融合』岩波書店](https://www.amazon.co.jp/%E8%AA%BF%E6%9F%BB%E8%A6%B3%E5%AF%9F%E3%83%87%E3%83%BC%E3%82%BF%E3%81%AE%E7%B5%B1%E8%A8%88%E7%A7%91%E5%AD%A6%E2%80%95%E5%9B%A0%E6%9E%9C%E6%8E%A8%E8%AB%96%E3%83%BB%E9%81%B8%E6%8A%9E%E3%83%90%E3%82%A4%E3%82%A2%E3%82%B9%E3%83%BB%E3%83%87%E3%83%BC%E3%82%BF%E8%9E%8D%E5%90%88-%E3%82%B7%E3%83%AA%E3%83%BC%E3%82%BA%E7%A2%BA%E7%8E%87%E3%81%A8%E6%83%85%E5%A0%B1%E3%81%AE%E7%A7%91%E5%AD%A6-%E6%98%9F%E9%87%8E-%E5%B4%87%E5%AE%8F/dp/4000069721/ref=sr_1_fkmr0_1?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&dchild=1&keywords=%E8%AA%BF%E6%9F%BB%E8%A6%B3%E5%AF%9F%E3%83%87%E3%83%BC%E3%82%BF%E3%81%AE%E7%B5%B1%E8%A8%88%E5%8C%96%E5%AD%A6&qid=1584105930&sr=8-1-fkmr0)|
|2|[G. Imbens and D. Rubin (2015), _Causal Inference for Statistics, Social, and Biomedical Science_, Cambridge University Press](https://www.amazon.co.jp/Causal-Inference-Statistics-Biomedical-Sciences/dp/0521885884/ref=sr_1_1?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&dchild=1&keywords=Causal+Inference+for+Statistics%2C+Social%2C+and+Biomedical+Science&qid=1584105905&sr=8-1)|
|3|[J. Angrist and J. Pischke (2014), _Mastering Metrics: The Path from Cause to Effect_, Princeton University Press](https://www.amazon.co.jp/Mastering-Metrics-Path-Cause-Effect/dp/0691152845/ref=sr_1_1?adgrpid=53628805136&dchild=1&gclid=Cj0KCQjw3qzzBRDnARIsAECmryrfWNhwiBLmYRFhmvM1TtaJhderozo80ozaJKWP65dJZevYdIuxjlEaAt74EALw_wcB&hvadid=338564794964&hvdev=c&hvlocphy=1009279&hvnetw=g&hvqmt=e&hvrand=13677210793030631759&hvtargid=aud-758806828496%3Akwd-299833799494&hydadcr=11339_10884778&jp-ad-ap=0&keywords=mastering+metrics&qid=1584105956&sr=8-1)|
|4|[M. Hernan and J. Robins (2020), _Causal Inference: What If_, Boca Raton: Chapman  Hall/CRC](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)|

## 論文
### 傾向スコアとそれを用いた因果推論の基礎
|Id|Name|
|-|-|
|1|[R. Deheija and S. Wahba (1999), "Causal Effects in Nonexperimental Studies: Reevaluating the Evaluation of Training Programs", _Journal of the American Statistical Association_, 94(448), 1053-1062](https://www.uh.edu/~adkugler/Dehejia&Wahba_JASA.pdf)|
|2|[P. Rosenbaum and D. Rubin (1983), "The Central Role of the Propensity Score in Observational Studies for Causal Effects", _Biometrika_, Vol. 70, 41-55](https://academic.oup.com/biomet/article/70/1/41/240879)|
|3|[E. Stuart (2010), "Matching Methods for Causal Inference: A Review and a Look Forward", _Statistical Science_, Vol. 25, 1-21](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2943670/)|


### 傾向スコアから一般化傾向スコアへ
|Id|Name|
|-|-|
|1|[K. Hirano and G. Imbens (2004), "The Propensity Score with Continuous Treatments", in Gelman and Meng eds. _Applied Bayesian Modeling and Causal Inference from Missing Data Perspectives_, Wiley](http://www.math.mcgill.ca/dstephens/SISCR2017/Articles/HIrano-Imbens-2004.pdf)|
|2|[K. Imai and D van Dyk (2004), "Causal Inference with General Treatment Regimes: Generalizing the Propensity Score", _Journal of the American Statistical Association_, Vol. 99, 854-866](https://imai.fas.harvard.edu/research/files/pscore.pdf)|
|3|[G. Imbens (2000), "The Role of the Propensity Score in Estimating Dose-Response Functions", _Biometrika_, Vol. 87, 706-710](https://pdfs.semanticscholar.org/b9d2/3c91c9054433a4b5d31553f55cf6ae7880b1.pdf)|

### 傾向スコアマッチング/ウェイティングをより深く理解する
|Id|Name|
|-|-|
|1|[A. Abadie and G. Imbens (2011), "Bias-Corrected Matching Estimators for Average Treatment Effects", _Journal of Business & Economic Statistics_, Vol. 29(1), 1-11](https://economics.mit.edu/files/11861)|
|2|[B. Lee, J. Lessler and E. Stuart (2011), "Weight Trimming and Propensity Score Weighting", _PLoS ONE_, 6(3): e18174](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3069059/)|
|3|[G. King and R. Nielsen (2018), "Why Propensity Scores should not be Used for Matching", _Political Analysis_, 27(4), 1-20](https://gking.harvard.edu/publications/why-propensity-scores-should-not-be-used-formatching)|


### 様々なマッチング/ウェイティング手法
|Id|Name|
|-|-|
|1|[K. Imai and M. Ratkovic (2014), “Covariate Balancing Propensity Score”, _Journal of the Royal Statistical Society: Series B (Statistical Methodology)_, Vol. 76, 243-263](https://imai.fas.harvard.edu/research/files/CBPS.pdf)|
|2|[A. Naimi (2017), "An Introduction to g methods", _International Journal of Epidemiology_, Vol. 46(2), 756-762](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6074945/)|
|3|[M. Schuler and S. Rose (2016), "Targeted Maximum Likelihood Estimation for Causal Inference in Observational Studies", _American Journal of Epidemiology_, Vol.185(1), 65-73](https://academic.oup.com/aje/article/185/1/65/2662306)|

### 感度分析
|Id|Name|
|-|-|
|1|[S. Athey and G. Imbens (2015), "A Measure of Robustness to Misspecification", _American Economic Review_, Vol. 105(5), 476-480](https://pdfs.semanticscholar.org/701f/8f1aa9c93ac478b8e1cbcef0e94b2a0d3821.pdf)|
|2|[M. Blackwell (2014), "A Selection Bias Approach to Sensitivity Analysis for Causal Effects", _Political Analysis_, Vol. 22(2), 169-182](https://pdfs.semanticscholar.org/350b/5d60c84ac5194600b49051b6fc69e6c081ad.pdf)|
|3|[T. VanderWeele (2017), "Sensitivity Analysis in Observational Research: Introducing the E-Value", _Annals of Internal Medicine_, Vol. 167(4), 268-274](https://dash.harvard.edu/bitstream/handle/1/36874927/EValue_FinalSubmission.pdf?sequence=1&isAllowed=y)|

### 機械学習と因果推論の融合
|Id|Name|
|-|-|
|1|[S. Athey and G. Imbens (2016), "Recursive Partitioning for Heterogeneous Causal Effects", _Proceedings of the National Academy of Sciences of the United States of America_, Vol. 113, 7353-7360](https://www.pnas.org/content/pnas/113/27/7353.full.pdf)|
|2|[S. Athey, J. Tibshirani and S. Wager (2018), "Generalized Random Forests", _Annals of Statistics_, Vol. 47(2), 1148-1178](https://arxiv.org/abs/1610.01271)|
|3|[S. Athey and S. Wager (2018), "Estimation and Inference of Heterogeneous Treatment Effects Using Random Forests", _Journal of the American Statistical Association_, Vol. 113, 1228-1242](https://www.tandfonline.com/doi/pdf/10.1080/01621459.2017.1319839?needAccess=true)|
|4|[A. Nicholas and L. McBride (2019), "Propensity Scores and Causal Inference Using Machine Learning Methods", Stata Conference, 13](http://lindenmcbride.com/uploads/3/6/2/2/36225639/psw_ml.pdf)|
|5|[M. Oprescu, V. Syrgkanis and Z. Wu (2019), "Orthogonal Random Forest for Causal Inference", _Proceedings of the 36th International Conference on Machine Learning_,Papers 1806.03467, arXiv.org](https://arxiv.org/pdf/1806.03467.pdf)|
|6|[R. Pirracchio, M. Petersen and M. van der Laan (2015), "Improving Propensity Score Estimators' Robustness to Model Misspecification Using Super Learner", _American Journal of Epidemiology_, Vol. 181(2), 108-119](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4351345/)|

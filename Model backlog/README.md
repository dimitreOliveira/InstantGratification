## Model backlog (list of the developed model and it's score)
- **Cross validation** is the result using **K-Fold** cross validation.
- The competition metric is **AUC**.
- **Pb Leaderboard** is the Public Leaderboard score.
- **Pv Leaderboard** is the Private Leaderboard score.

---

## Models

|Model|Cross validation|Pb Leaderboard|Pv Leaderboard|
|-----|----------------|--------------|--------------|
|Instant Gratification - Deep Learning|0.61|0.81091|0.81113|
|Instant Gratification - Experimentation|0.73|0.80581|0.80392|
|Ensembling and evaluating Magic models|1.00|0.96495|0.96575|
|[1] - Deep Learning - 5 Fold|0.93|0.83250|0.83218|
|[2] - Deep Learning - 10 Fold|0.95|0.83494|0.83412|
|[3] - Deep Learning - Stdv scaler|0.91|0.73818|0.73585|
|[4] - Deep Learning - Magic count|0.89|0.80903|0.80826|
|[5] - Deep Learning - Correlated only|0.70|0.66789|0.66999|
|[6] - Deep Learning - Magic features|0.83|0.82651|0.82657|
|[7] - Deep Learning - Batch 256|0.86|0.80573|0.80515|
|[8] - Deep Learning - AUC monitor|0.98|0.84260|0.84267|
|[9] - Deep Learning - AUC monitor - Delta 0.001|0.98|0.84273|0.84228|
|[11] - SVC - Magic dataset|1.00|0.92895|0.93101|
|[12] - NuSVC - Magic dataset|1.00|0.94679|0.94758|
|[13] - RF - Magic dataset|1.00|0.84948|0.84917|
|[14] - KNN - Magic dataset|0.97|0.92350|0.92374|
|[15] - GaussianProcess - Magic dataset|1.00|0.50000|0.50000|
|[16] - MLP - Magic dataset|1.00|0.93048|0.93095|
|[17] - AdaBoost - Magic dataset|0.98|0.76527|0.76279|
|[18] - QuadDiscriAnalysis - Magic dataset|0.99|0.96587|0.96657|
|[19] - QuadDiscriAnalysis - Magic dataset -25 Fold|0.99|0.96583|0.96650|
|[20] - NuSVC - Magic dataset - 25 Fold|1.00|0.94640|0.94717|
|[21] - Top 5 models - Magic dataset.ipynb|1.00|0.96364|0.96456|
|[22] - KNN k=10 - Magic dataset|0.96|0.92706|0.92759|
|[23] - Top 5 models - Magic dataset - 25 fold|1.00|0.96343|0.96438|
|[24] - Top 5 models - Magic dataset - 5 fold|1.00|0.96407|0.96492|
|[25] - Top 5 models - Magic dataset - Stdv Scaler|1.00|0.96462|0.96528|
|[26] - Top 5 models - Magic dataset - MinMax Scaler|0.98|0.95127|0.95227|
|[27] - Magic dataset - PCA Stdv scaler|1.00|0.96651|0.96735|
|[28] - Magic dataset - PCA MinMax scaler|0.98|0.93683|0.93759|
|[29] - 512 QDA - VarThreshold tunning|1.00|0.96587|0.96657|
|[30] - 512 QDA - Scaller tunning|0.99977|0.96466|0.96542|
|[31] - 512 QDA - PCA tunning|0.99418|0.96543|0.96621|
|[32] - 512 QDA - Tunning 5 Fold|0.99241|0.96495|0.96573|
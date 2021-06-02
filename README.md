# 2021平安保险数字挑战赛-rank14

1.比赛链接：https://www.heywhale.com/home/competition/607d279965852e0017ab9575
2.该比赛属于风控类比赛且限制使用在线平台算力，所以主要考虑用lgbm和catboost来做模型，且同样特征lgbm线下比cbt高一个千（两者importances强特不同）
3.在特征构造完后，考虑用cat_depth8,cat_depth9,lgbm_depth9,lgbm_depth10四个模型stacking融合，但提升效果不明显，与lgbm单模相差在万分位

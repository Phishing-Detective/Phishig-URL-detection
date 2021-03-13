# Phishing-URL-detection

1. 데이터 merge, Train & Test set split -> train.csv, test.csv

2. 실험
- 실험 1. Only URL
- 실험 2. URL + URL feature(5개까지)
  - Length, Depth, '-',  shorten service (+http://https 동시에 존재하는지)
- 실험 3. URL + URL feature(10개까지)
  - 기존 5개 + [DNS Record in WHOIS DB, web traffic rank < 100000, Age of Domain, Redireciton count > 2, IP addr in URL]

3. 모델
- Random Forest, Decision Tree, XGBoost(+LightGBM)
- CNN, LSTM, Transformer, BERT



- 연수 : RF, CNN, BERT
- 수빈 : DT, LSTM, XGBoost

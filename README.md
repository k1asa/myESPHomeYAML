# myESPHomeYAML
esphomeとHA連携でいろんなデバイスを作ってみる。
HomeAssistant上のEsphome Dashboardをいじっていたけれど
AIにたよって編集してたら、コンパイルしたら「違うそうじゃない」などで
YAML構成を二手三手試しては戻す状況が多く、バージョン管理したくてGitHubリポジトリ化を開始。


## 2432S028_entrance.yaml
いわゆるCheap Yellor Display。
天気表示して、玄関に設置したくて作成
タッチして週間天気を表示。
もう一方をタッチして時間天気もいいかも。
### page2
<img width="320" height="240" alt="esp_sample" src="https://github.com/user-attachments/assets/99c4982e-70f5-450c-8c9d-3998353b476e" />

### page3
<img width="320" height="240" alt="esp_weekly" src="https://github.com/user-attachments/assets/aff45f86-e821-41d4-bb11-06153caabc30" />


## 2432S028_entrance.yaml
上記の天気表示をWICにも設置したくて作成
基本的に上記の玄関設置のyamlを引用している。
設置位置の関係からデバイスを180度回転させて設置しているので設定値を上書き。

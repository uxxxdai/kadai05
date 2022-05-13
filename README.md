# 課題5 -JS4 - APIアプリ-

## ①課題内容（どんな作品か）
- 日本にある世界遺産を地図上に表示させ、訪問済みの世界遺産にチェックをつけると制覇率（全体の何パーセントに訪問したか）がわかり、制覇に向けた進捗管理ができるアプリ作りました。
- Bing Maps APIを使用しています。
- 世界遺産だけでなく、エクセルでアップロードした場所リスト（お店リストとかでも良い）を地図表示/リスト表示させられるようにし、自分が達成したい場所の制覇に向けた進捗管理をできるようにしたかったものの、エクセルアップロードが自身の思う形でデータを取得できず、いまだ奮闘中です。（そのため、今回表示の世界遺産データはコードの中にべた張りしています。）

## ②工夫した点・こだわった点
- Bing Maps APIを色々試してみるべく、Pushpinを画像に変えてみたり、Pinにテキストを入れたり、Infoboxを表示させたりしてみたりしました。
- ループを使って一つずつを表示させていますが、InfoboxをPushpinと紐づけるのに苦労しました。
- エクセルアップロードしたときに手直しが少なくなるように設計しており、リストの数が多くなってもデータを取得できるようにしています。

## ③質問・疑問（あれば）
- エクセル、CSVファイル、Google スプレッドシートなど色々とネット上にある情報は確認し、実装を試みましたがデータ取得はできたものの、自身の思っているオブジェクトの形に変換できず、このあと質問として挙げる予定です。

## ④その他（感想、シェアしたいことなんでも）
- 解決すれば授業までにエクセルアップロード機能とLocalStorageの保存機能を実装したいと思います。

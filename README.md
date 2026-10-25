# Hiroshi Ando
### Java・PHPを学び、仕組みが見えるWebアプリをつくる。

Java・PHP・生成AIを中心に学習しながら、身近な疑問や制作上の課題を、小さなWebツールにしています。初級ITエンジニアへの転職を目指しています。

**[個人制作ポートフォリオ「Code & Sound」を見る ↗](https://hiroshi-ando-creative-lab.machinehead7777777.chatgpt.site)**

ポートフォリオでは、楽曲 **「Sytytä haava tuleen」** をBGMとして試聴できます。画面右下の **▶** で再生・一時停止、**♫** で音量調整ができます。自動再生はせず、初期音量は20%、繰り返し再生に対応しています。

## 学習していること

- **Java**：Java Silver 11取得。Java Goldに向けて学習中
- **Web開発**：PHP、JavaScript、Spring Boot
- **生成AI**：OllamaやRAGを使ったシステムの仕組みと設計

## 制作物

### PHPの参照バグを理解する「ビル比較教材」

毎年2倍になる3棟のビルを題材に、`foreach`の参照が残ると何が起こるかを可視化した教材です。

- 正常な処理とバグのある処理を年ごとに比較
- 問題のコードと、`unset()`を使う修正版を確認
- PHPで計算した結果を、JavaScriptでアニメーション表示

[ビル比較教材を試す](https://hiroshi-ando-creative-lab.machinehead7777777.chatgpt.site/#works)

### Javaの落とし穴を比較する「Java Bug Lab」

問題コードと修正版を並べ、値や実行順序を操作して確かめる4つの教材です。Javaの仕組みを説明するJavaScriptシミュレーターとして制作しています。

| 題材 | 操作・比較できること |
| --- | --- |
| HashMapのキー変更 | 登録後のキー変更による検索失敗と、不変キーでの再登録 |
| スレッド競合 | count++の実行順序と、AtomicIntegerによる加算 |
| ArrayListのループ中削除 | 前方向・拡張forと、逆方向・Iterator.removeの比較 |
| Integer比較 | 127・128やキャッシュ設定による==の違いと、値の比較 |

[Java Bug Labを試す](https://hiroshi-ando-creative-lab.machinehead7777777.chatgpt.site/java-lab.html)

各教材に模型の前提とJava公式APIへのリンクを記載しています。コード例はJava 17以降を想定しています。

### 音楽PVの構成を考える「PV Sequence」

画像の順序と表示秒数を編集し、ffmpeg用の連結リストとコマンドを書き出すツールです。

- シーンの追加・削除・並べ替え
- 合計時間と時間配分の表示
- 動画生成に使うファイルとコマンドの出力

[PV Sequenceを使う](https://hiroshi-ando-creative-lab.machinehead7777777.chatgpt.site/#works)

## 生成AIとの取り組み方

制作では、コードの提案・実装・検証に生成AIを活用しています。

AIの支援で制作した部分と、自分で理解・説明できる部分を区別し、小さなコードや実際の動作を通して理解を深めていくことを大切にしています。

## 音楽・映像制作

Sunoを活用した音楽制作にも取り組み、2026年9月時点で120曲以上を制作しています。

プログレッシブロックや組曲を中心に、物語・歌詞・曲の構成を考え、映像へつなげる表現を探っています。PV制作で感じた課題は、Webツールづくりの題材にもなっています。

[音楽と世界観の制作ノート](https://hiroshi-ando-creative-lab.machinehead7777777.chatgpt.site/#sound)

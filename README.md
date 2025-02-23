# 深層学習用 JVS声優統計コーパス準拠 骨伝導音声
## 内容物：
- 気導音声100発話（90音を学習用データ、10音を評価用データ）
- 骨伝導音声100発話（90音を学習用データ、10音を評価用データ）
## 音声ファイルの詳細：
- 男性話者1名による読み上げ音声
- サンプリング周波数 22050 Hz
- エンコード         16 bit Signed-Integer PCM
- チャンネル         1 （モノラル）
## 注意点：
発話内容はJVSの台本を使用していますが、ファイル番号の振り分けは、
EMIME bilingual corpusを参考にしています。
## ダウンロード方法：
配置したいディレクトリに移動し、クローンするだけ（研究室のマシンでできます）
```

cd your/directory

```
```

git clone https://github.com/Lemontea014/bone2air_cps

```
## 録音環境
- 無響室
## 使用機材について
| 使用機材  | 品番・備考 |
| ------------- | ------------- |
| オーディオインターフェース  | Rubix22  |
| 骨伝導イヤーマイク  | EM20N-T3.5P  |
| コンデンサマイクロホン  | Earthworks M50  |
| モニターヘッドホン  | ATH-M50x  |
| 編集ソフトウェア  | audacity3.7.1  |

## reference
- [JVS corpus: free Japanese multi-speaker voice corpus](https://www.google.com/url?q=https%3A%2F%2Farxiv.org%2Fabs%2F1908.06248&sa=D&sntz=1&usg=AOvVaw2j6j5_3wH7e6tdC9PCMQ8z)
- [つくよみちゃんコーパス│声優統計コーパス（JVSコーパス準拠）](https://tyc.rei-yumesaki.net/material/corpus/)
- [EMIME Bilingual Database](http://www.emime.org/participate/emime-bilingual-database.html)

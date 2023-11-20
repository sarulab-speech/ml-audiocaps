# Multi-lingual AudioCaps: generating multi-lingual captions for audios in the wild

The [AudioCaps](https://github.com/cdjkim/audiocaps) contains a dataset of audio and English captions. We extended this to multi linguality; the parallel sentences that is mapped to unique sounds.

[AudioCaps](https://github.com/cdjkim/audiocaps) は，音イベントと英語のキャプションから成るデータセットです．我々はこのデータを多言語に拡張し，１つの音を表す複数言語のデータセットを作成しました．

## Supported language / 対応言語
 - English (en)
 - Japanese (ja) ... Both manual and automatic translation.

## Audio data / 環境音データ
Formatted as 256kbps MP3, 1ch, 48kHz. Since some videos of data source were deleted, the number of audio files does not match that of text captions.
 - [training set](https://ss-takashi.sakura.ne.jp/corpus/audiocaps/train.zip)
 - [validation set](https://ss-takashi.sakura.ne.jp/corpus/audiocaps/val.zip)
 - [test set](https://ss-takashi.sakura.ne.jp/corpus/audiocaps/test.zip)

## Example / 文例

| AudioCapID    | Language  | Caption |
| ---           | ---       | ---     |
| 53262         | en        | A motorbike revs and a dark barks |
| 53262             | ja (manual) | オートバイの回転音、犬が吠える声 | 
| 53262         | ja (auto)     | モーターバイクがエンジンを回し、獣のように暗闇がほえる。|

## Contributors / 貢献者
 - Shinnosuke Takamichi (The University of Tokyo, Japan) / 高道 慎之介 (東京大学)
 - Ai Morimatsu (The University of Tokyo, Japan) / 森松 亜依 (東京大学)
 - Aya Watanabe (The University of Tokyo, Japan) / 渡邊 亞椰 (東京大学)

## Paper / 論文
(TBA)

## Acknowledgement / 謝辞
This work is supported by the following supports.
- JSPS KAKENHI 22H03639
- JST FOREST JP23KJ0828
- JST Moonshot JPMJPS2011
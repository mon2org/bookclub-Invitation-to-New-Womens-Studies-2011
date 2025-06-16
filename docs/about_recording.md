# 録音について

この読書会では意見交換、議論の時間帯に会話を録音します。

どういう話をしたのか記録するためです。

録音したデータから文字起こしを行います。文字起こしは[whisper.cpp](https://github.com/ggml-org/whisper.cpp)を用います。

音声データは32kbpsのmp3に変換します。

文字起こししたテキストデータと音声データは、暗号化した上で、当リポジトリ配下に置きます。

## 取り扱いについて

- パスワードは参加者への個別連絡 or 読書会中に告知します。参加者以外へのパスワードの提供は行いません。
- パスワードは毎回、違うものを生成します。
  - IPAの[日常における情報セキュリティ対策](https://www.ipa.go.jp/security/anshin/measures/everyday.html)では英数字記号込み最低10字以上としていますが、本読書会ではコピペを前提に英数字(大文字/小文字)で最低64文字を設定します。
- 必要に応じて、発言内容の修正・削除依頼を受け付けます。

## 使用するソフトウェア

- 録音: [QuickTime Player](https://support.apple.com/ja-jp/guide/quicktime-player/welcome/mac)
- 音声データの変換: [ffmpeg](https://github.com/FFmpeg/FFmpeg)
- 文字起こし: [whisper.cpp](https://github.com/ggml-org/whisper.cpp)
- 暗号化: [アタッシェケース](https://hibara.org/software/attachecase/)

## 注意事項

- 録音・文字起こしに同意できない場合は、事前に主催者までご連絡ください。
- 要望や改善案があれば、[要望Issue](https://github.com/mon2org/bookclub-Invitation-to-New-Womens-Studies-2011/issues/new?template=request.yml)からご連絡ください。

[README](./README.md)
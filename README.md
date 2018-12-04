# ご注意

このリポジトリーは [katze_7514](http://twitter.com/katze_7514) さんの [katze7514/UEDirectInputPadPlugin](https://github.com/katze7514/UEDirectInputPadPlugin) を [Usagi Ito]() が [usagi/](https://github.com/usagi/UEDirectInputPadPlugin) へ Fork してちょこっといじったりしている何かです。

- Fork 元の状態の README は [README.original.md](README.original.md) を参照して下さい。

# このプラグインを使う動機

UE4 には 4.15 以降は標準で Windows RawInput Plugin が入りましたが、

- 軸の入力値が unorm でそのまま Input のマッピングへ入力されてしまうので XInput と同じマッパーにできず XInput とは別に RawInput 用のマッピングを用意する必要がある。（あるいは Product ID, Vendor ID からデバイスごとに値域のマッパーを定義するか…）
- ボタンのイベントが安定しない。（連打しても数秒に1度しか Pressed が来ないとか…）

など、既に UEDirectInputPadPlugin でちょろっとマッピングして便利に XInput / DirectInput の両対応をしているプロジェクト、あるいはその経験があるといまひとつ現時点の Windows RawInput Plugin に変更する気が起こらないのです。

基本的には Fork 元で完成している良プラグインですが、 Fork 版では Usagi Ito が大昔の DirectInput プログラミングの経験と記憶から若干ちょいちょい修正するかもしれません。

# License

- Fork 元のライセンスは MIT です。
- Fork 後の Usagi Ito による変更も MIT です。

# Author

## Original

Twitter : [katze_7514](http://twitter.com/katze_7514)  
blog    : [GameProgrammer's Night](http://katze.hatenablog.jp/)

## This Fork

- Usagi Ito
    - GitHub: [usagi](https://github.com/usagi/)
    - Twitter: [USAGI_WRP](https://twitter.com/USAGI_WRP)
    - Facebook: [usagi.wrp](https://www.facebook.com/usagi.wrp)
    - Blog(tech): [C++ ときどき ごはん、わりとてぃーぶれいく☆](https://usagi.hatenablog.jp/)

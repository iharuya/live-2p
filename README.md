# Live 2p

## about
カメラ使って空間にお絵描きできるやつ

カメラで手をパースして指とかの情報から編集モードとかを決定してアクションを適当なFPSでやる。

## usage
- `python VirtualPainter.py`
- 一つの指で選択or描画
- 二つ以上（パーとか両手を出すとか）は何もしない
- 反対の手は消しゴム

### issue
- ディレクトリ変更につきvenv関係のハードコードされたパス設定を、限定的に手動で修復したけど、もっといいsuitがあるだろう
..
- VirtualPainterでカメラAPIあたりで詰まるけど３回やればまあ成功するという不完全性
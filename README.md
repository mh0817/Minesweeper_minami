# Minesweeper_minami
Minesweeper作るよ

一応進捗

C# MVVMで開発予定

外観はWiondowにDataGridを付けて、それぞれの行にButtonを取り付け、マインスイーパの外観を作成。

DataGridそれぞれの行と、ViewModels内で管理している爆弾管理用配列Bomb_manage[]の中身の値（爆弾無し=0、爆弾あり = 0以外）をバインド予定。
また、周囲の爆弾数を管理するための配列Surround_Bomb_Number[]も作成予定。

ボタンが押されるとBomb_manage[]の値を元に爆弾判定を行い、その行にSurround_Bomb_Number[]内の値を表示。
周囲に爆弾がない場合は再帰的にどんどん周囲のボタンを押していく。


構想はこんな感じ。

DataGrudでボタンおいていくことを思いつかなかったので時間くいました

後、今週仕事忙しいので間に合わんかも

1.
・科目名
・前期金額
・当期金額
のデータを持ち、
・全てのデータを1行で出力
・科目名、(当期金額 - 前期金額)を1行で出力
の機能を持つクラスを作成してください。

例:
  科目名: 現金及び預金
  前期金額: 4,564,255
  当期金額: 5,160,507
  出力1 → 現金及び預金 4,564,255 5,160,507
  出力2 → 現金及び預金 596,252


2.
・区分名
・1で作成したクラスのインスタンスの配列
のデータを持ち、
・区分名、前期金額の合計、当期金額の合計を1行で出力
・区分名、(当期金額の合計 - 前期金額の合計)を1行で出力
の機能を持つクラスを作成してください。

例:
  区分名: 流動資産
  (1)
    科目名: 現金及び預金
    前期金額: 4,564,255
    当期金額: 5,160,507
  (2)
    科目名: 受け取り手形及び売掛金
    前期金額: 2,013,110
    当期金額: 2,525,653
  出力1 → 流動資産 6,577,365 7,686,160
  出力2 → 流動資産 1,108,795


3.
2のクラスが2のインスタンスの配列も受け取ることが出来るように全体を再設計してください。

例:
  区分名: 資産の部
  (1)
    区分名: 流動資産
    前期金額: 7,277,553
    当期金額: 8,398,467
  (2)
    区分名: 固定資産
    前期金額: 1,536,737
    当期金額: 2,016,762
  出力1 → 資産の部 8,814,290 10,415,229
  出力2 → 資産の部 1,600,939
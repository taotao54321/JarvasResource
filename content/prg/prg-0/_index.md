+++
title = "PRG 0"
+++

論理アドレス `$8000-$BFFF` にマップされる PRG バンク。

## メモリマップ

| アドレス | 内容 |
| -- | -- |
| | {% todo() %}TODO{% end %} |
| `$B000-$B0EF` | マップメタデータテーブル (マップIDをインデックスとする) |
| | {% todo() %}TODO{% end %} |
| `$B12C-$B13A` | マップブロックデータテーブル |
| `$B13B-$B149` | マップメタチップデータテーブル |
| `$B14A-$B15D` | {% todo() %}TODO{% end %}: スクロールマージンテーブル? |
| | {% todo() %}TODO{% end %} |
| `$B600` | 現在のマップに応じた CHR バンク切り替えを行うルーチン |
| `$B713` | 主人公のレベルアップ判定/処理ルーチン (レベル依存の値の再計算も行う) |
| `$B7B8` | 主人公の能力 (最大HP/力/耐久) を現在のレベルに応じて再計算するルーチン  |
| `$B93C` | 主人公の習得魔法マスクを現在のレベルに応じて再計算するルーチン |
| `$B96B-$BFFF` | (未使用) |
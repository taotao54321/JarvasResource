+++
title = "PRG-ROM"
+++

本作は[マッパー 80](https://www.nesdev.org/wiki/INES_Mapper_080) である。
このマッパーは機能的には 0x2000 バイト単位での PRG バンク切り替えが可能だが、本作では実質的に 0x4000 バイト単位で PRG バンクを切り替えている。よって、ここでも PRG バンクは 0x4000 バイト単位で扱う。

CPU メモリマップは以下の通り:

| 論理アドレス  | 内容                                       |
| --            | --                                         |
| `$8000-$BFFF` | 可変バンク領域                             |
| `$C000-$FFFF` | 固定バンク領域 (常に PRG 7 がマップされる) |

各 PRG バンクの概要は以下の通り (詳細はリンク先を参照):

| バンク | 論理アドレス | 内容 |
| -- | -- | -- |
| [PRG 0](@/prg/prg-0/_index.md) | `$8000-$BFFF` | |
| [PRG 1](@/prg/prg-1/_index.md) | `$8000-$BFFF` | |
| [PRG 2](@/prg/prg-2/_index.md) | `$8000-$BFFF` | |
| [PRG 3](@/prg/prg-3/_index.md) | `$8000-$BFFF` | |
| [PRG 4](@/prg/prg-4/_index.md) | `$8000-$BFFF` | |
| [PRG 5](@/prg/prg-5/_index.md) | `$8000-$BFFF` | |
| [PRG 6](@/prg/prg-6/_index.md) | `$8000-$BFFF` | |
| [PRG 7](@/prg/prg-7/_index.md) | `$C000-$FFFF` | 汎用的なコード/データ |

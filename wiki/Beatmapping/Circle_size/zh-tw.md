---
no_native_review: true
tags:
  - CS
  - key count
---

# 圓圈大小

*關於圓圈大小的規定，請見[審核標準](/wiki/Ranking_Criteria)*

**圓圈大小** (***CS***)是影響[打擊物件](/wiki/Hit_object)大小的[圖譜](/wiki/Beatmap)難度設定。數值可介於 0 到 10 之間，但在[圖譜編輯器](/wiki/Beatmap_Editor)中只能在 2 到 7 間調整。若要繞過此限制，必須手動修改圖譜的 [.osu檔案](/wiki/osu!_File_Formats/Osu_(file_format))。

## osu!

在 osu! 中，圓圈大小將改變打擊圈圈和滑條的大小。數值越大，物件越小。轉盤不會被影響。以下是計算公式：

`r = 54.4 - 4.48 * CS`<!-- multiplied by 1.00041 in the end to account for some bug in old replays -->

`r` 為半徑，以osu!pixel為單位。`CS` 為圓圈大小的值。

## osu!taiko

在 osu!taiko 中，圓圈大小沒有作用。

## osu!catch

在 osu!catch 中， 圓圈大小將改變玩家和水果的大小。

## osu!mania

在 osu!mania 中， 圓圈大小指按鍵數量。

## Mod 效果

有兩個 mod 會改變圓圈大小：

- [Easy](/wiki/Game_modifier/Easy): CS 值減半。
- [Hard Rock](/wiki/Game_modifier/Hard_Rock): 將CS值乘上 1.3，仍不會超過 10。

<!--TODO: Insert links -->

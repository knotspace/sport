# 更新履歴

## 2026-11-13
- 卓球トップページの大会・選手・ランキング情報が404になっていた参照先を修正。/`sport/tabletennis/` から `../world-data.json` 相当の正しい公開パス `/sport/world-data.json` を読むように変更しました。
- 公式データJSONの構造確認を実施。未掲載情報を推測で補う処理は追加していません。

## 2026-11-13（公式大会日程更新）
- ITTF公式2026 Events Calendarを再確認し、Gaborone・Nevsehirの開催状態を更新、PattayaのITTF World Para Championshipsを追加。大会12件を日付・開催地・状態で整理。世界ランキングの個別データは独立確認できていないため推測で追加していません。

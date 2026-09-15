# noupark-media

脳パーク(`@nou_park_jp`)の Threads / Instagram 投稿用メディアの置き場。GitHub Pages で配信し、Threads / Instagram の API がここの URL から取りに来る。

- 中身は `BrainScore/tools/meta-poster/convert.py` の出力だけ(手で置かない・答えは入れない)
- `match/` マッチ棒クイズ(JPEG 1440×810)/ `spot/` 間違い探し(JPEG 1440×960)/ `aha/` アハ体験(MP4・無音 AAC 付き)
- `ig/<axis>/` Instagram 用のリール(MP4 1080×1920・見出し・問い・残り時間のバー入り)= `BrainScore/tools/meta-poster/reel.py` の出力
- 仕様 = BrainScore `docs/specs/meta-poster-spec.md` MP-4 / MP-5 / MP-12

# Tincture Capture Patterns

## 概要
- Tinctureの種類毎にフォルダを作成
- Tinctureの各状態ごとに分類

## ファイル構成
sap_of_the_seasons/
|-- idle/       # Tinctureが使用可能状態
|-- active/     # Tinctureがアクティブ状態
|-- cooldown/   # Tinctureがクールダウン状態

## ファイル命名規則
- {tincture_type}_{State}_{cooldown_progress_bar}
- 例: sap_of_the_seasons_active.png     # Sap of the Sesaons アクティブ状態、クールダウンはなし
- 例: sap_of_the_seasons_cooldown_p050.png  # Sap of the Seasons 非アクティブ状態、クールダウン50％経過
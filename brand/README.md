# 株式会社上田 ブランドロゴ

2026年10月採用。漢字「上」を縦線・土台・赤い横線の3つの部品に分解したマークと、英字「UEDA」・社名「株式会社上田」の組み合わせ。

## 色

| 用途 | 色 | HEX |
|---|---|---|
| メイン（文字・マーク） | 黒 | `#111111` |
| 差し色（赤い横線のみ） | 赤 | `#D7261E` |
| 反転時のメイン | 白 | `#FFFFFF` |

- 赤は横線1か所だけに使う。文字やマーク全体を赤にしない。
- 印刷・刺繍・看板の発注時は、画面の色ではなく印刷所の色見本（DIC・PANTONE等の色番号）で実物を確認して指定する。

## フォント

- 英字・社名は Noto Sans CJK JP（Black / Bold）を図形化済み。データ利用時にフォントのインストールは不要。
- Noto Sans CJK は SIL Open Font License で、商用利用可。

## ファイル

| 場所 | 内容 | 使う場面 |
|---|---|---|
| `brand/print/ueda-logo-horizontal-color.*` | 2段組ロゴ（マーク＋UEDA＋株式会社上田） | 名刺・書類・看板・車両（白い背景） |
| `brand/print/ueda-logo-horizontal-white.*` | 同・白抜き | 作業着・黒い看板（濃い背景） |
| `brand/print/ueda-mark-color.*` / `-white.*` | マーク単体 | SNSアイコン・名刺の裏・ステッカー |
| `images/brand/logo-header-color.*` | 1行ロゴ（マーク｜UEDA｜株式会社上田） | ホームページのヘッダー（白い背景） |
| `images/brand/logo-header-white.*` | 同・白抜き | ホームページのフッター・暗いヘッダー |
| `/favicon.svg`・`/favicon.ico` | ファビコン（16px用に形を調整済み） | ブラウザのタブ・検索結果 |
| `/apple-touch-icon.png`・`/icon-*.png`・`/site.webmanifest` | ホーム画面アイコン | iPhone・Android |
| `brand/mockups/` | 名刺・作業着・車両・サイトへの当てはめ確認画像 | 社内確認・業者への説明 |

- `.svg` は拡大しても劣化しない。印刷所・刺繍業者・看板業者にはSVGを渡す。
- `.png` は背景透過。Word・PowerPoint・SNSに貼る用。

## 使い方のルール

- ロゴの周りには、マークの赤い横線の高さ以上の余白を空ける。
- 縦横比を変えない・傾けない・影や枠を付けない。
- 背景が明るい時は color、暗い時は white を使う。
- 16px程度の極小サイズでは、通常のマークではなく `favicon.svg` の形を使う（隙間が潰れないよう調整済み）。
- 商標登録を検討する場合は、事前に特許庁 J-PlatPat で類似の図形商標を確認する。

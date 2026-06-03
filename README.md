# 小林聖心女子学院小学校 SQ対話型入試 プレテスト 広報用

2026年8月1日（土）開催の出願者限定イベント「SQ対話型入試 プレテスト」の広報用リポジトリ。

LPは「出願誘導」と「プレテスト申込」の2つのCTAを並列で提示し、未出願者を出願に促す導線を持つ設計。

## イベント概要

- 開催日: 2026年8月1日（土）9:30〜12:00
- 申込期間: 2026年6月22日（月）〜7月31日（金）
- 対象: 本校への出願者（希望者のみ）
- 会場: 小林聖心女子学院小学校
- 主催: 本校入試広報

## URL

- LP本体: https://oby-kouhou.github.io/oby-2026-0801-pretest/
- 申込中継ページ: https://oby-kouhou.github.io/oby-2026-0801-pretest/go/?s=（ソース名）
- 申込先（外部）: https://mirai-compass.net/usr/obyshjge/event/evtIndex.jsf

## 計測

- GA4計測ID: G-WG4L0SGNJJ
- 申込クリックイベント: `click_apply`（go/中継ページで発火）
- LP内CTAクリックイベント: `cta_click`（LP本体で発火）
- イベント識別: `event_name_jp: pretest_0801`

## LP内CTAのトラッキング値（data-cta-location）

| 値 | 何のCTAか |
|----|----------|
| output | 出願誘導CTA（本校公式サイト 入試募集要項へ） |
| pretest | プレテスト申込CTA（go/中継ページ経由） |
| sticky | 下部固定のスティッキーCTA |

## go/?s= のソース別パラメータ

| s= の値 | 意味 |
|---------|------|
| lp | LP内のCTAから |
| email | メール配信から |
| line | 公式LINE配信から |
| ig | Instagram投稿・広告から |
| direct | パラメータなしアクセス |
| test | テストアクセス（除外） |

## LP本体のUTMパラメータ（流入媒体識別）

| utm_source | utm_medium | utm_campaign | 配信媒体 |
|------------|-----------|-------------|---------|
| flyer-pretest | print | pretest_0801 | 本校作成ちらし（QRコード） |
| line | messaging | pretest_0801 | 公式LINE |
| email | email | pretest_0801 | メール |
| instagram | social | pretest_0801 | Instagram通常投稿 |

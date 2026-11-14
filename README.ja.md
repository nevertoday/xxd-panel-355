<div align="center">

# XXD Panel 355｜俯瞰の押し文字

**主体を真上から見た地面の粒にし、短い一語を溝の大字として横に押します。**

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 355 · 01 · ラクダ"><br><sub>01 · ラクダ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 355 · 02 · 砂浜のカヤック"><br><sub>02 · 砂浜のカヤック</sub></td>
  </tr>
</table>

<p align="center"><sub>上が元の写真、下がこのスタイルで描き直したものです。</sub></p>

## これは何か

Claude Code や Codex などの AI エージェント向け Skill です。写真を 1 枚渡すと、Panel 355 の原文プロンプトに沿って PNG の完成作品を描きます。

- **どんな絵になるか：** 上半分には元の写真を残し、主体の正体、構造、姿勢、質感と自然光はそのまま、色だけをわずかに整え、頭上に空を残し、看板や印刷文字は上だけに留めます。下半分は真上からの俯瞰で、写真の中で最も広い材質の平らで清潔な地面が続き、地平線も他の景物もなく、短い一語が中央よりやや下を横切り、両側に余白を残して端に触れません。画は材質そのものを押し凹めた溝で、縁は柔らかく盛り上がり、低い斜光が片側を照らしてもう片側は浅い影に落ち、最後の画は長い軌跡になって雫形の大きな輪を一回りします。主体は真上からでも姿勢の分かる数個の大きな形に収め、軌跡の上に粒のように完結して立ち、見えるのは自分の色の二、三か所と自分より長い影だけで、頭上に少し空き、上下は広い空き地で、場面の写真は最も代表的な一つだけを残し、地面はその一色、溝は一段暗く影が最も暗く、文字は角の丸い幾何学的なサンセリフの一語、ラテン文字は小文字、末尾に大きな一点、色は地面より一段暗く、中国語は簡体字で、見える細部から引いた隠喩として物の名前は呼びません。
- **キーワード：** 真上からの俯瞰 · 地平線のない単一の地面 · 押し凹めた溝の大字 · 雫形の長い軌跡 · 粒のような主体と長い影 · 角の丸いサンセリフの一語
- **作れるもの：** 上下比較（上に写真、下にデザイン）、左右比較、デザインのみ、またはスマホ／タブレット／PC／ウォッチの壁紙セット。複数選択でき、比率やピクセル数も自由です。
- **これは違う：** フィルターでもテンプレートでもありません。毎回あなたの写真から描き直し、写真 1 枚ごとに独立したタスクです。

## 3 ステップで始める

**1. インストール。** Claude Code、Codex など Skills 対応のエージェントで使えます：

```bash
npx skills add https://github.com/nevertoday/xxd-panel-355 --skill xxd-panel-355
```

インストール後、エージェントのセッションを開き直してください。このリポジトリを `git clone` して `~/.claude/skills/xxd-panel-355` または `~/.codex/skills/xxd-panel-355` にリンクしても使えます。

**2. エージェントが画像を生成できるか確認。** この Skill 自体は画像モデルを持たず、エージェントの画像生成（GPT Image 2 推奨）を使います。

- Codex は内蔵の画像生成が有効ならそのまま使えます。
- Claude Code など内蔵の画像生成がないエージェントは、OpenAI 互換の画像 API が必要です。5 分ほどで設定できます：[画像生成の設定](#画像生成の設定)。

わからなければそのまま試してください。生成できない場合は、作業を始める前に Skill が止まって知らせます。

**3. 写真を送って、ひとこと：**

> xxd-panel-355 でこの写真を 3:4 の上下比較ポスターにして、日本語のタイトルを付けて。

指示がそろっていればすぐ生成し、足りない点（レイアウト、比率、文字）は 1〜2 問ほど質問します。完成した PNG は `~/Desktop/xxd/xxd-panel-355/` の新しいフォルダに保存されます。

## 向いている写真

**向いている**

- 地面の材質が広く見える写真：砂浜の人、雪の中の犬、乾いた草地の端の自転車
- 輪郭と姿勢がはっきりした単体：一人の人、一羽の鳥、一軒の建物、一台の車
- 構図が弱い、背景が散らかっている、主体が小さい写真（俯瞰にして周囲を省きます）

**あまり向いていない**

- 通り全体、人混み、風景全体を残したい写真（置くのは一つだけです）
- 目線や斜めからの風景、表面に印刷した文字、主体を大きく描くことを求める場合
- 色数を増やしたい、またはタイトルに物の名前をそのまま呼びたい場合

## サンプル

下の画像はすべて、この Skill が写真 1 枚から作った完成作品です。上下比較と左右比較では別の写真を使っています。

### 上下比較：上が写真、下がデザイン

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 355 · 01 · ラクダ"><br><sub>01 · ラクダ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 355 · 02 · 砂浜のカヤック"><br><sub>02 · 砂浜のカヤック</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-03.png" alt="XXD Panel 355 · 03 · 砂浜のヨガ"><br><sub>03 · 砂浜のヨガ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-04.png" alt="XXD Panel 355 · 04 · 雪の茶色い馬"><br><sub>04 · 雪の茶色い馬</sub></td>
  </tr>
</table>

<details>
<summary>さらに 15 枚を見る</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-05.png" alt="XXD Panel 355 · 05 · 雪のキツネ"><br><sub>05 · 雪のキツネ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-06.png" alt="XXD Panel 355 · 06 · 赤い服の歩行者"><br><sub>06 · 赤い服の歩行者</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-07.png" alt="XXD Panel 355 · 07 · サーカスのテント"><br><sub>07 · サーカスのテント</sub></td>
    <td width="50%"><img src="./assets/examples/sample-08.png" alt="XXD Panel 355 · 08 · 草原の赤い自転車"><br><sub>08 · 草原の赤い自転車</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-09.png" alt="XXD Panel 355 · 09 · 草原の白いガチョウ"><br><sub>09 · 草原の白いガチョウ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-10.png" alt="XXD Panel 355 · 10 · 草原に横たわる人"><br><sub>10 · 草原に横たわる人</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-11.png" alt="XXD Panel 355 · 11 · 塩湖の歩行者"><br><sub>11 · 塩湖の歩行者</sub></td>
    <td width="50%"><img src="./assets/examples/sample-12.png" alt="XXD Panel 355 · 12 · 家族のピクニック"><br><sub>12 · 家族のピクニック</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-13.png" alt="XXD Panel 355 · 13 · 畑の干し草ロール"><br><sub>13 · 畑の干し草ロール</sub></td>
    <td width="50%"><img src="./assets/examples/sample-14.png" alt="XXD Panel 355 · 14 · 氷上のアザラシ"><br><sub>14 · 氷上のアザラシ</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-15.png" alt="XXD Panel 355 · 15 · 野原のカボチャ"><br><sub>15 · 野原のカボチャ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-16.png" alt="XXD Panel 355 · 16 · 草原のゾウ"><br><sub>16 · 草原のゾウ</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-17.png" alt="XXD Panel 355 · 17 · 草地のヒツジ"><br><sub>17 · 草地のヒツジ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-18.png" alt="XXD Panel 355 · 18 · 野原の白い椅子"><br><sub>18 · 野原の白い椅子</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-19.png" alt="XXD Panel 355 · 19 · 庭の手押し車"><br><sub>19 · 庭の手押し車</sub></td>
  </tr>
</table>

</details>

### 左右比較：左が写真、右がデザイン

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-20.png" alt="XXD Panel 355 · 20 · サーファー"><br><sub>20 · サーファー</sub></td>
    <td width="50%"><img src="./assets/examples/sample-21.png" alt="XXD Panel 355 · 21 · 黄色い服で立つ人"><br><sub>21 · 黄色い服で立つ人</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-22.png" alt="XXD Panel 355 · 22 · 庭を掃く人"><br><sub>22 · 庭を掃く人</sub></td>
    <td width="50%"><img src="./assets/examples/sample-23.png" alt="XXD Panel 355 · 23 · 風船を持つ人"><br><sub>23 · 風船を持つ人</sub></td>
  </tr>
</table>

<details>
<summary>さらに 13 枚を見る</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-24.png" alt="XXD Panel 355 · 24 · 砂地のフラミンゴ"><br><sub>24 · 砂地のフラミンゴ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-25.png" alt="XXD Panel 355 · 25 · 全身のキリン"><br><sub>25 · 全身のキリン</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-26.png" alt="XXD Panel 355 · 26 · 雪のペンギン"><br><sub>26 · 雪のペンギン</sub></td>
    <td width="50%"><img src="./assets/examples/sample-27.png" alt="XXD Panel 355 · 27 · 庭の雄鶏"><br><sub>27 · 庭の雄鶏</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-28.png" alt="XXD Panel 355 · 28 · 座る茶トラ"><br><sub>28 · 座る茶トラ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-29.png" alt="XXD Panel 355 · 29 · ひまわり畑"><br><sub>29 · ひまわり畑</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-30.png" alt="XXD Panel 355 · 30 · サボテン一本"><br><sub>30 · サボテン一本</sub></td>
    <td width="50%"><img src="./assets/examples/sample-31.png" alt="XXD Panel 355 · 31 · 竹林の切り株"><br><sub>31 · 竹林の切り株</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-32.png" alt="XXD Panel 355 · 32 · 梨一つ"><br><sub>32 · 梨一つ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-33.png" alt="XXD Panel 355 · 33 · 銅のティーポット"><br><sub>33 · 銅のティーポット</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-34.png" alt="XXD Panel 355 · 34 · 柱上の巣箱"><br><sub>34 · 柱上の巣箱</sub></td>
    <td width="50%"><img src="./assets/examples/sample-35.png" alt="XXD Panel 355 · 35 · 庭に水をやる人"><br><sub>35 · 庭に水をやる人</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-36.png" alt="XXD Panel 355 · 36 · カラー一輪"><br><sub>36 · カラー一輪</sub></td>
  </tr>
</table>

</details>

## こう言えば OK

パラメータを覚える必要はありません。そのまま伝えてください：

| やりたいこと | こう言う |
|---|---|
| 上下比較 | 3:4 の上下比較にして |
| 左右比較 | 16:9 の左右比較で、左に写真 |
| デザインのみ | 写真なしでデザインだけ、9:16 縦長 |
| 壁紙セット | スマホ、タブレット、PC、ウォッチの壁紙を統一感のあるセットで |
| 複数の比率 | 同じ写真で 1:1、3:4、16:9 を 1 枚ずつ |
| 自分の文字 | タイトルは「風の通り道」、一字も変えないで |
| 文字なし | 文字は一切入れないで |
| 文字の言語 | 文字は英語で |
| フォルダごと | このフォルダの写真を全部上下比較にして |
| 前回と同じ | 前回の設定で |

コマンドラインが好みなら、パラメータは上と一対一で対応します：

```text
/xxd-panel-355 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale ja-JP
/xxd-panel-355 photo.jpg --mode design-only --size 9:16 --text none
/xxd-panel-355 ./photos --mode left-right --size 16:9 --text prompt --locale en-US
```

すべてのパラメータは[パラメータ一覧](#パラメータ一覧)にあります。

## よくある質問

**元の写真は必ず入りますか？** いいえ。「デザインだけ」や壁紙なら、画面全体がデザインになります。

**文字は誰が書くのですか？** 既定では画像モデルが写真を見て書き、あなたは言語だけを選びます。自分の文字を指定すれば一字も変えずに使い、文字なしにもできます。事実に見える情報（地名、日付、数字）は、あなたが渡したものか写真に写っているものだけを使い、作りません。

**気に入らなかったら？** 「もう 1 枚」と言ってください。前の結果を直すのではなく元の写真から描き直すので、毎回違う結果になります。

**まとめて処理すると混ざりませんか？** 混ざりません。写真ごとに個別に生成し、ほかの写真の色、文字、構図を借りません。設定は一括で 1 回だけ聞きます。

**写真はどこに送られますか？** エージェントが使う画像モデルにだけ送られます。Skill はほかへアップロードせず、接続先やキーも表示しません。

**ほかの Panel との関係は？** XXD Panel は番号ごとに 1 つのスタイルで、互いに独立しています。好きなものだけ入れてかまいません。写真に合うスタイルを AI に選ばせたい、複数を比べたいときは、カタログ [xxd-panel-all](https://github.com/nevertoday/xxd-panel-all) を使ってください。

## 原文プロンプト

このスタイルは小小東が書いた[原文プロンプト](references/original-prompt/zh-CN.md)（中国語）だけで決まります。Skill はあなたが選んだレイアウト、サイズ、文字の設定を末尾に足すだけで、要約・翻訳・書き換えはしません。

参考訳（読むためのもので、画像生成には使いません）：[English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

## 画像生成の設定

`gpt-image-2`（または互換モデル）を提供する OpenAI 互換 API とその API キーが必要です。次の手順は別の設定ファイルを作るので、Codex 本体の設定には影響しません：

```bash
mkdir -p ~/.xxd-imagegen
cat > ~/.xxd-imagegen/config.toml <<'EOF'
model_provider = "image"

[model_providers.image]
base_url = "https://api.openai.com/v1"   # または互換エンドポイント
env_key = "XXD_IMAGE_API_KEY"
EOF

# ~/.zshrc か ~/.bashrc に書き、エージェントからも読めるようにする
echo 'export XXD_IMAGEGEN_CODEX_DIR=~/.xxd-imagegen' >> ~/.zshrc
echo 'export XXD_IMAGE_API_KEY=あなたのキー' >> ~/.zshrc
```

ターミナルとエージェントを開き直してから、この Skill のフォルダで一度確認します：

```bash
python3 scripts/configured_imagegen.py probe
```

`"ok":true` なら成功です。結果は使えるかどうかだけで、接続先やキーは表示されません。Codex がすでに互換 API で画像を生成できるなら、この手順は不要です。

## パラメータ一覧

| パラメータ | 値 |
|---|---|
| `--mode` | `top-bottom` 上下比較 · `left-right` 左右比較 · `design-only` デザインのみ · `wallpaper-pack` 4 端末の壁紙；複数選択可 |
| `--size` | `auto` おすすめ · `source` 写真に合わせる · `1:1` `3:4` `4:3` `4:5` `5:4` `2:3` `3:2` `9:16` `16:9` `21:9` `5:7` `7:5` · ピクセル指定（例 `2160x3840`）；複数選択可 |
| `--text` | `prompt` 写真から書く · `exact` あなたの文字（`--copy "…"` と併用） · `none` 文字なし |
| `--locale` | 文字の言語。例：`zh-CN` `en-US` `ja-JP` `ko-KR` `ar` |
| `--wallpaper` | `linked` 統一感のあるセット · `independent` 4 枚それぞれ独立 |
| `--wallpaper-size` | 端末ごとのピクセル。例：`phone=1440x3200,desktop=3840x2160` |
| `--out` | 出力先のルートを変更（既定は `~/Desktop/xxd/xxd-panel-355/`） |
| `--prefs` | `last` 前回どおり · `edit` 前回から変更 · `new` 選び直す · `off` 今回は記録しない · `clear` 記録を消す |

- 値がそろっていれば質問せず、足りないものだけを聞きます。`photo.jpg` の代わりにフォルダを渡すと一括処理になります。
- 組み合わせは 1 枚ずつ生成します。2 モード × 3 サイズ = 6 枚で、どれも切り抜きではなくキャンバスごとに構図を組み直します。
- 比較画像は正確に 50:50 です。通常はモデルがデザイン側だけを描き、スクリプトが元の写真をそのまま隣に並べるので、境目は中央で写真も変わりません。
- ファイル名は `source-001-street-top-bottom-3x4-1152x1536.png` のような形式で、すべて 1 つのタスクフォルダに平置きされます。
- 記録するのはレイアウト、サイズ、文字の方式と言語だけで、写真、文字、キーは残しません。

<!-- xxd-readme-ads:start -->
## XXD について

XXD は Xiaoxiaodong のブランド名略称です。本プロジェクトの作成・管理：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。

## Xiaoxiaodong マルチプラットフォーム会員 · 年額 CNY 699

> **広告表示：** 以下のQRコード、会員および有料サービスのリンクはXXDの広告情報です。スキャンや購入は任意であり、本プロジェクトの利用には影響しません。

年額会員ひとつで、**Knowledge Planet＋XXD会員プロンプトライブラリ＋すべてのGeneral Skills会員**の3つを利用できます。別々に購入する必要はありません。

<!-- xxd-panel-command-system:start -->

### Skills の連携方法

| 区分 | 含まれるもの | 役割 |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | 利用可能な番号付きSkillsを検出し、画像・テーマ・用途から推薦し、複数スタイルや一括タスクを整理します。 |
| **Soldier** | `xxd-panel-NNN` | 各番号が固有の原文プロンプトと美学に従い、Generalから割り当てられた具体的な作業を完成させます。 |

<!-- xxd-panel-command-system:end -->

### 会員の内容

1. **WeChatでの一対一AI学習・プロジェクト相談**
   下のQRコードからXiaoxiaodongのWeChatを追加し、AI学習、ツール、実際のプロジェクトについて一対一で相談できます。代表的な質問は会員向けコンテンツに整理されます。
2. **継続更新する会員プロンプトライブラリ**
   [XXD会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)には現在約3.2万件のプロンプトがあり、10万件超を目標に継続して拡充します。
3. **すべてのGeneral Skillsと利用サポート**
   ひとつの会員で全General Skillsを利用でき、使い方に困ったときは案内やQ&Aを受けられます。
4. **必要性の高い要望を優先**
   会員から寄せられた頻度と必要性の高いプロンプトやSkillsは、優先して検討・開発します。

### 開設方法

- [会員サイトから自分で開設](https://vip.xiaoxiaodong.ai/)できます。
- または下のQRコードからXiaoxiaodongのWeChatを追加し、一対一で開設サポートを受けられます。

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="Xiaoxiaodongへの連絡" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## ライセンス

**非商用は無料、商用には個別の許可が必要です。** 本プロジェクト（Skill、オリジナルプロンプト、スクリプト、ドキュメント）は [PolyForm Noncommercial 1.0.0](LICENSE) で提供しています。ソースは公開していますが、OSI の定義するオープンソースではありません。

- **無料：** 個人の学習や趣味の制作。自分の写真から画像を作り、手元に残したり個人アカウントで共有したりすること（広告、案件投稿、商品紹介を除く）。LICENSE を添えた非商用の改変と再配布。
- **個人の商用には許可が必要：** 依頼を受けた有償制作、広告や商品紹介のコンテンツ、少量のグッズ販売、有料講座やコミュニティでの利用。通常は相談に応じ、作者の書面での確認を基準とします。
- **組織での利用は契約が必須：** 企業、スタジオ、MCN、ブランドなどによる商用利用すべて。社内利用や、アプリ・ウェブサイト・SaaS・API への組み込みも含みます。
- **許可しないもの：** Skill、プロンプト、サンプルの転売、改名、再パッケージしての公開。
- Xiaoxiaodong の会員には商用ライセンスは含まれません。サンプルの元写真の権利は各撮影者にあり、効果の紹介のためだけに掲載しています。

申請は Xiaoxiaodong の WeChat を追加し、「商用ライセンス」とお書きください。詳しい条件と QR コードは [商用ライセンスについて](COMMERCIAL.md)（中国語・英語）にあります。

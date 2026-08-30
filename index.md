---
layout: default
title: Copilot Experience Lab
description: 自分の仕事で試す、Microsoft 365 Copilot 体験ラボ

# 扉（カード）はここに書いた groups の順に、
# contents/<dir>/ 配下の実ファイルから自動生成されます。
# コンテンツを追加・リネームしても index.md の修正は不要です。
#
# 各コンテンツ .md の front matter で、見え方を調整できます（すべて任意）:
#   title:    カードの見出し（未指定ならファイル名から生成）
#   subtitle: 見出し下の一文
#   minutes:  所要分数（例: 10 → 「約 10 分」）
#   duration: 自由記述の所要（minutes より優先）
#   key:      true にすると ★ が付きます
groups:
  - dir: "00-setup"
    cls: "g0"
    label: "Setup"
    lead: "はじめる前に　環境と進め方をそろえる"
  - dir: "01-copilot-chat"
    cls: "g1"
    label: "Copilot Chat"
    lead: "まず驚く　自分のデータで対話する"
  - dir: "02-microsoft365-copilot"
    cls: "g2"
    label: "Microsoft 365 Copilot"
    lead: "仕事の文脈をまたいで使う"
  - dir: "03-outlook-teams"
    cls: "g3"
    label: "Outlook / Teams"
    lead: "毎日の面倒を減らす　メールと会議"
  - dir: "04-excel"
    cls: "g4"
    label: "Excel"
    lead: "数字から示唆を取り出す"
  - dir: "05-word"
    cls: "g5"
    label: "Word"
    lead: "文書をゼロから書かない"
  - dir: "06-researcher-analyst"
    cls: "g6"
    label: "Researcher / Analyst"
    lead: "調べる・分析するを任せる"
  - dir: "07-agent-builder"
    cls: "g7"
    label: "Agent Builder"
    lead: "自分専用のエージェントを作る"
  - dir: "08-powerpoint"
    cls: "g8"
    label: "PowerPoint"
    lead: "伝わる資料に仕上げる"
  - dir: "09-personas"
    cls: "g9"
    label: "Personas"
    lead: "役割別の使いどころ"
---

<!-- GitHub Pages（Jekyll）用のトップページです。
     扉のリンクは site.pages / site.static_files から自動生成しているため、
     ファイル名を index.md に書き写す必要はありません。
     リポジトリ上（github.com）で直接見る場合は README.md の一覧をご利用ください。 -->

<style>
.cel-hero{padding:2rem 1.6rem;margin:0 0 1.6rem;border-radius:14px;color:#fff;
  background:linear-gradient(135deg,#0f3d6e 0%,#1668b8 55%,#2aa3a3 100%);}
.cel-hero h1{margin:0 0 .4rem;font-size:1.9rem;line-height:1.3;color:#fff;border:0;}
.cel-hero p{margin:.3rem 0 0;opacity:.94;line-height:1.7;}
.cel-hero .cel-tag{display:inline-block;margin-top:.9rem;padding:.25rem .7rem;border-radius:999px;
  background:rgba(255,255,255,.18);font-size:.8rem;}

.cel-legend{display:flex;flex-wrap:wrap;gap:.5rem;margin:0 0 1.6rem;padding:0;list-style:none;}
.cel-legend li{display:flex;align-items:center;gap:.45rem;padding:.35rem .7rem;border-radius:999px;
  background:#f2f4f7;font-size:.82rem;color:#333;}
.cel-legend a{color:#333;text-decoration:none;}
.cel-legend a:hover{text-decoration:underline;}
.cel-legend i{width:.7rem;height:.7rem;border-radius:50%;display:inline-block;background:var(--c);}

.cel-sec{margin:0 0 2.2rem;scroll-margin-top:1rem;}
.cel-sec h2{display:flex;align-items:center;gap:.55rem;margin:0 0 .15rem;font-size:1.15rem;
  padding-bottom:.35rem;border-bottom:2px solid var(--c);}
.cel-sec h2 i{width:.7rem;height:.7rem;border-radius:50%;display:inline-block;background:var(--c);}
.cel-sec h2 em{margin-left:auto;font-style:normal;font-size:.72rem;font-weight:400;color:#61697a;}
.cel-lead{margin:.45rem 0 .9rem;font-size:.85rem;color:#61697a;line-height:1.6;}

.cel-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(158px,1fr));gap:.8rem;margin:0;}
.cel-door{display:block;position:relative;padding:.9rem .9rem 1rem;border-radius:12px;text-decoration:none;
  border:1px solid #e3e6ea;background:#fff;color:#1b1b1b;overflow:hidden;
  transition:transform .15s ease,box-shadow .15s ease,border-color .15s ease;}
.cel-door:before{content:"";position:absolute;inset:0 auto 0 0;width:5px;background:var(--c);}
.cel-door:hover{transform:translateY(-3px);box-shadow:0 8px 18px rgba(16,32,60,.14);
  border-color:var(--c);text-decoration:none;}
.cel-num{display:flex;align-items:baseline;gap:.35rem;font-weight:700;color:var(--c);letter-spacing:.02em;}
.cel-num b{font-size:1.6rem;line-height:1;}
.cel-num span{font-size:.72rem;opacity:.75;}
.cel-title{display:block;margin:.5rem 0 .3rem;font-size:.86rem;line-height:1.45;font-weight:600;color:#1b1b1b;}
.cel-subtitle{display:block;margin:0 0 .5rem;font-size:.73rem;line-height:1.45;color:#3f4757;}
.cel-meta{font-size:.72rem;color:#61697a;}
.cel-door.is-key:after{content:"★";position:absolute;top:.6rem;right:.7rem;font-size:.8rem;color:var(--c);}
.cel-empty{font-size:.8rem;color:#8a91a0;padding:.6rem 0;}

.cel-start{border:1px solid #e3e6ea;border-radius:12px;padding:1rem 1.2rem;background:#fafbfc;}
.cel-start ol{margin:.4rem 0 0;padding-left:1.2rem;}
.cel-start li{margin:.25rem 0;line-height:1.7;}

.g0{--c:#475569;} .g1{--c:#c2410c;} .g2{--c:#1668b8;} .g3{--c:#0f766e;} .g4{--c:#15803d;}
.g5{--c:#1d4ed8;} .g6{--c:#6d28d9;} .g7{--c:#b91c1c;} .g8{--c:#b45309;} .g9{--c:#9d174d;}

@media (max-width:480px){.cel-grid{grid-template-columns:repeat(auto-fill,minmax(136px,1fr));gap:.6rem;}}
</style>

<div class="cel-hero">
  <h1>Copilot Experience Lab</h1>
  <p>1 つずつ、扉を開けるように試す体験ラボ。<br>
  使うのはサンプルデータではなく、<strong>あなた自身のメール・会議・チャット・ファイル</strong>です。</p>
  <p class="cel-tag">所要 5〜20 分 / 1 コンテンツ &nbsp;·&nbsp; Microsoft 365 Copilot</p>
</div>

## 今日の扉を開ける

順番どおりでなくて構いません。**開けたい扉から開けてください**。
★ の付いた扉は、期間中に何度も繰り返す価値のある体験です。

<ul class="cel-legend">
{%- for g in page.groups -%}
  {%- assign dirkey = "contents/" | append: g.dir | append: "/" -%}
  {%- assign gp = site.pages | where_exp: "p", "p.path contains dirkey" -%}
  {%- assign gp = gp | where_exp: "p", "p.name != 'index.md' and p.name != 'README.md'" -%}
  {%- assign gs = site.static_files | where_exp: "f", "f.path contains dirkey" -%}
  {%- assign gs = gs | where_exp: "f", "f.extname == '.md'" -%}
  {%- assign gs = gs | where_exp: "f", "f.name != 'index.md' and f.name != 'README.md'" -%}
  {%- assign gc = gp.size | plus: gs.size -%}
  {%- if gc > 0 -%}
  <li class="{{ g.cls }}"><i></i><a href="#{{ g.dir }}">{{ g.label }}</a>（{{ gc }}）</li>
  {%- endif -%}
{%- endfor -%}
</ul>

{% for g in page.groups %}
  {%- assign dirkey = "contents/" | append: g.dir | append: "/" -%}

  {%- comment -%} 実ファイルを収集（front matter 付きは site.pages、素の .md は site.static_files） {%- endcomment -%}
  {%- assign gp = site.pages | where_exp: "p", "p.path contains dirkey" -%}
  {%- assign gp = gp | where_exp: "p", "p.name != 'index.md' and p.name != 'README.md'" -%}
  {%- assign gs = site.static_files | where_exp: "f", "f.path contains dirkey" -%}
  {%- assign gs = gs | where_exp: "f", "f.extname == '.md'" -%}
  {%- assign gs = gs | where_exp: "f", "f.name != 'index.md' and f.name != 'README.md'" -%}
  {%- assign items = gp | concat: gs -%}

  {%- comment -%} ファイル名末尾の連番（例 _CHAT-05）で昇順に並べ替え {%- endcomment -%}
  {%- assign ordered = "" | split: "," -%}
  {%- assign seen = "" -%}
  {%- for n in (0..59) -%}
    {%- assign pad = n | prepend: "0" | slice: -2, 2 -%}
    {%- for p in items -%}
      {%- assign stem = p.name | split: "." | first -%}
      {%- assign code = stem | split: "_" | last -%}
      {%- assign num = code | split: "-" | last -%}
      {%- if num == pad -%}
        {%- assign ordered = ordered | push: p -%}
        {%- assign seen = seen | append: "|" | append: p.name | append: "|" -%}
      {%- endif -%}
    {%- endfor -%}
  {%- endfor -%}
  {%- for p in items -%}
    {%- assign mark = p.name | prepend: "|" | append: "|" -%}
    {%- unless seen contains mark -%}{%- assign ordered = ordered | push: p -%}{%- endunless -%}
  {%- endfor -%}

  {%- if ordered.size > 0 -%}
<section class="cel-sec {{ g.cls }}" id="{{ g.dir }}">
  <h2><i></i>{{ g.label }}<em>{{ g.dir }}／{{ ordered.size }} 件</em></h2>
  <p class="cel-lead">{{ g.lead }}</p>
  <div class="cel-grid">
  {%- for p in ordered -%}
    {%- assign stem = p.name | split: "." | first -%}
    {%- assign parts = stem | split: "_" -%}
    {%- assign code = parts | last -%}
    {%- assign cparts = code | split: "-" -%}
    {%- if parts.size > 1 and cparts.size > 1 -%}
      {%- assign badge = cparts | last -%}
      {%- assign kind = cparts | first -%}
      {%- assign fallback = parts | first -%}
    {%- else -%}
      {%- assign badge = forloop.index | prepend: "0" | slice: -2, 2 -%}
      {%- assign kind = "DOOR" -%}
      {%- assign fallback = stem -%}
    {%- endif -%}
    <a class="cel-door {{ g.cls }}{% if p.key %} is-key{% endif %}" href="{{ p.url | default: p.path | relative_url }}">
      <span class="cel-num"><b>{{ badge }}</b><span>{{ kind }}</span></span>
      <span class="cel-title">{{ p.title | default: fallback }}</span>
      {%- if p.subtitle %}<span class="cel-subtitle">{{ p.subtitle }}</span>{%- endif %}
      <span class="cel-meta">
      {%- if p.duration -%}{{ p.duration }}
      {%- elsif p.minutes -%}約 {{ p.minutes }} 分
      {%- else -%}体験コンテンツ{%- endif -%}
      </span>
    </a>
  {%- endfor -%}
  </div>
</section>
  {%- endif -%}
{% endfor %}

---

## はじめての方へ

<div class="cel-start" markdown="1">

1. Copilot Chat を開き、**Work** が選択されていることを確認する
2. 今日の扉を開き、**TRY — 手順**のプロンプトをそのまま貼り付ける
3. 出てきた答えを鵜呑みにせず、**根拠リンクを 1 つ開いて確認する**
4. 最後の **REFLECT — 振り返り**に、その日のうちに答える

</div>

各ページは「目的 / 所要 / 入力 / 成果」→ シナリオ → TRY（手順とプロンプト）→ REFLECT → NEXT の順に並んでいます。
うまくいかなかった依頼にも価値があります。**どう指示を変えれば直るか**まで書き残してください。

---

## プログラム（連続体験）

単発で試すだけでなく、期間を決めて続ける進め方も用意しています。

<div class="cel-grid">
{%- assign progs = site.pages | where_exp: "p", "p.path contains 'programs/'" -%}
{%- assign progs = progs | where_exp: "p", "p.name == 'README.md' or p.name == 'index.md'" -%}
{%- for p in progs -%}
  {%- assign segs = p.path | split: "/" -%}
  {%- assign slug = segs[1] -%}
  {%- if segs.size > 2 -%}
  <a class="cel-door g2" href="{{ p.url | relative_url }}">
    <span class="cel-num"><b>▶</b><span>PROGRAM</span></span>
    <span class="cel-title">{{ p.title | default: slug }}</span>
    <span class="cel-meta">{{ p.description | default: slug }}</span>
  </a>
  {%- endif -%}
{%- endfor -%}
</div>

---

## 続けるコツ

- **新しい扉は週 3 回**くらいで十分です。残りの日は、気に入ったプロンプトを繰り返し使ってください。
- 効いたプロンプトは保存して、毎営業日使えるようにします。
- 週に 1 回、チームのチャネルに「今週いちばん良かった 1 件」を投稿します。
- 時間短縮は**自分で計測**します。Copilot に見積もらせないでください。

---

## 実施にあたって

- 自分の実データを使います。共有・公開する成果物に機密情報が含まれていないか、必ず確認してください。
- 利用できる機能は、ライセンスとテナント設定によって異なります。
- Excel の体験は、ファイルを OneDrive に保存し AutoSave を有効にする必要があります。
- エージェントの作成・共有は、管理者設定・テナント構成・ライセンスによって可否が異なります。事前に管理者へ確認してください。
- ハンズオンが難しい回は、ファシリテーターのデモを見ながら進めてください。

---

<p class="cel-meta">運営・ファシリテーター向けの進行ルールと測定項目は <a href="{{ '/README.html' | relative_url }}">プログラム概要</a> にまとめています。</p>

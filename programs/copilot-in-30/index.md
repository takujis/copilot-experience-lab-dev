---
layout: default
title: Copilot in 30
description: 30 日間で「自分の仕事」に Copilot を溶かし込む体験カレンダー
---

<!-- 置き場所：programs/copilot-in-30/index.md
     各扉のリンク先は ../../contents/ 配下の .html です。
     GitHub Pages は jekyll-optional-front-matter を既定で有効にしているため、
     front matter を持たない .md も .html として出力されます。
     リポジトリ上（github.com）で直接見る場合は、同じフォルダの README.md をご利用ください。 -->

<style>
.c30-hero{padding:2rem 1.6rem;margin:0 0 1.8rem;border-radius:14px;color:#fff;
  background:linear-gradient(135deg,#0f3d6e 0%,#1668b8 55%,#2aa3a3 100%);}
.c30-hero h1{margin:0 0 .4rem;font-size:1.9rem;line-height:1.3;color:#fff;border:0;}
.c30-hero p{margin:.3rem 0 0;opacity:.94;line-height:1.7;}
.c30-hero .c30-tag{display:inline-block;margin-top:.9rem;padding:.25rem .7rem;border-radius:999px;
  background:rgba(255,255,255,.18);font-size:.8rem;}

.c30-legend{display:flex;flex-wrap:wrap;gap:.5rem;margin:0 0 1.4rem;padding:0;list-style:none;}
.c30-legend li{display:flex;align-items:center;gap:.45rem;padding:.35rem .7rem;border-radius:999px;
  background:#f2f4f7;font-size:.82rem;color:#333;}
.c30-legend li a{color:#333;text-decoration:none;}
.c30-legend li a:hover{text-decoration:underline;}
.c30-legend i{width:.7rem;height:.7rem;border-radius:50%;display:inline-block;}

.c30-sec{margin:0 0 2rem;scroll-margin-top:1rem;}
.c30-sec h3{display:flex;align-items:center;gap:.55rem;margin:0 0 .2rem;font-size:1.05rem;
  padding-bottom:.35rem;border-bottom:2px solid var(--c);}
.c30-sec h3 i{width:.7rem;height:.7rem;border-radius:50%;display:inline-block;background:var(--c);}
.c30-secnote{margin:.5rem 0 .9rem;font-size:.82rem;color:#61697a;line-height:1.7;}

.c30-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(150px,1fr));gap:.8rem;margin:0 0 2rem;}
.c30-door{display:block;position:relative;padding:.9rem .9rem 1rem;border-radius:12px;text-decoration:none;
  border:1px solid #e3e6ea;background:#fff;color:#1b1b1b;overflow:hidden;
  transition:transform .15s ease,box-shadow .15s ease,border-color .15s ease;}
.c30-door:before{content:"";position:absolute;top:0;bottom:0;left:0;width:5px;background:var(--c);}
.c30-door:hover{transform:translateY(-3px);box-shadow:0 8px 18px rgba(16,32,60,.14);
  border-color:var(--c);text-decoration:none;}
.c30-num{display:flex;align-items:baseline;gap:.35rem;font-weight:700;color:var(--c);letter-spacing:.02em;}
.c30-num b{font-size:1.6rem;line-height:1;}
.c30-num span{font-size:.72rem;opacity:.75;}
.c30-title{display:block;margin:.5rem 0 .35rem;font-size:.86rem;line-height:1.45;font-weight:600;color:#1b1b1b;}
.c30-subtitle{display:block;margin:0 0 .55rem;font-size:.73rem;line-height:1.45;color:#3f4757;}
.c30-meta{font-size:.72rem;color:#61697a;}
.c30-door.is-key:after{content:"\2605";position:absolute;top:.6rem;right:.7rem;font-size:.8rem;color:var(--c);}

.w0{--c:#475569;}
.w1{--c:#c2410c;}
.w2{--c:#1668b8;}
.w3{--c:#0f766e;}
.w4{--c:#b45309;}
.w5{--c:#6d28d9;}
.wx{--c:#8a91a0;}

.c30-start{border:1px solid #e3e6ea;border-radius:12px;padding:1rem 1.2rem;background:#fafbfc;}
.c30-start ol{margin:.4rem 0 0;padding-left:1.2rem;}
.c30-start li{margin:.25rem 0;line-height:1.7;}

.c30-stop{border:1px solid #f0d8a8;border-left:5px solid #b45309;border-radius:12px;
  padding:1rem 1.2rem;background:#fffaf0;margin:0 0 2rem;}
.c30-stop p{margin:.3rem 0;line-height:1.7;}

@media (max-width:480px){.c30-grid{grid-template-columns:repeat(auto-fill,minmax(132px,1fr));gap:.6rem;}}
</style>

<div class="c30-hero">
  <h1>Copilot in 30</h1>
  <p>1 つずつ、扉を開けるように試す 30 日間。<br>
  使うのはサンプルデータではなく、<strong>あなた自身のメール・会議・チャット・ファイル</strong>です。</p>
  <p class="c30-tag">所要 5〜20 分 / 回 &nbsp;·&nbsp; Day 0 〜 Day 21 &nbsp;·&nbsp; Microsoft 365 Copilot</p>
</div>

## 今日の扉を開ける

進む順番は Week 0 からがおすすめです。★ の付いた扉が、その週の**今週の体験**です。
★ のない扉はオプションなので、実データを使いにくいときや、関心に合わせて選んでください。

<ul class="c30-legend">
  <li class="w0"><i style="background:var(--c)"></i><a href="#week0">Week 0 ｜ Day 0</a></li>
  <li class="w1"><i style="background:var(--c)"></i><a href="#week1">Week 1 ｜ Day 1-5</a></li>
  <li class="w2"><i style="background:var(--c)"></i><a href="#week2">Week 2 ｜ Day 6-10</a></li>
  <li class="w3"><i style="background:var(--c)"></i><a href="#week3">Week 3 ｜ Day 11-15</a></li>
  <li class="w4"><i style="background:var(--c)"></i><a href="#day15">Day 15 前後 ｜ 立ち止まる</a></li>
  <li class="w5"><i style="background:var(--c)"></i><a href="#week4">Week 4 ｜ Day 16-20</a></li>
  <li class="wx"><i style="background:var(--c)"></i><a href="#more">さらに試す</a></li>
</ul>

<section class="c30-sec w0" id="week0">
  <h3><i></i>Week 0 ｜ Day 0：はじめる前に</h3>
  <p class="c30-secnote">ライセンス割り当て後、キックオフ前。正しい職場アカウントで入れることを確認し、Copilot が Microsoft 365 の信頼基盤の上にあることを共有します。</p>
</section>
<div class="c30-grid w0">
  <a class="c30-door w0 is-key" href="../../contents/00-setup/%E3%82%B5%E3%82%A4%E3%83%B3%E3%82%A4%E3%83%B3%E7%A2%BA%E8%AA%8D%E3%81%A8%E5%AE%89%E5%85%A8%E3%81%AAAI%E5%88%A9%E7%94%A8%E3%81%AE%E5%9C%9F%E5%8F%B0%E3%81%A5%E3%81%8F%E3%82%8A_SETUP-01.html">
    <span class="c30-num"><b>01</b><span>DOOR</span></span>
    <span class="c30-title">サインイン確認と安全なAI利用の土台づくり</span>
    <span class="c30-subtitle">SETUP</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w0 is-key" href="../../contents/01-copilot-chat/%E8%87%AA%E5%88%86%E3%81%AE%E3%83%AF%E3%83%BC%E3%82%AF%E3%83%9A%E3%83%AB%E3%82%BD%E3%83%8A%E3%82%921%E6%9E%9A%E3%81%AE%E3%82%B9%E3%82%B1%E3%83%83%E3%83%81%E3%81%AB%E3%81%99%E3%82%8B_CHAT-IMG-01.html">
    <span class="c30-num"><b>02</b><span>DOOR</span></span>
    <span class="c30-title">自分のワークペルソナを1枚のスケッチにする</span>
    <span class="c30-subtitle">アイスブレイクにも使える</span>
    <span class="c30-meta">約 10 分</span>
  </a>
</div>

<section class="c30-sec w1" id="week1">
  <h3><i></i>Week 1 ｜ Day 1-5：受信トレイを制する</h3>
  <p class="c30-secnote">メールと Teams を横断して、自分が抱えている未対応事項を洗い出します。「Copilot が自分の仕事を把握している」という最初の実感を得る週です。</p>
</section>
<div class="c30-grid w1">
  <a class="c30-door w1 is-key" href="../../contents/03-outlook-teams/%E3%83%A1%E3%83%BC%E3%83%AB%E3%81%A8%E3%83%81%E3%83%A3%E3%83%83%E3%83%88%E3%81%8B%E3%82%89%E6%9C%AA%E5%AF%BE%E5%BF%9C%E3%81%AE%E3%83%95%E3%82%A9%E3%83%AD%E3%83%BC%E3%82%A2%E3%83%83%E3%83%97%E3%82%92%E6%B4%97%E3%81%84%E5%87%BA%E3%81%99_CATCH-01.html">
    <span class="c30-num"><b>03</b><span>DOOR</span></span>
    <span class="c30-title">メールとチャットから未対応のフォローアップを洗い出す</span>
    <span class="c30-subtitle">今週の体験</span>
    <span class="c30-meta">約 15 分</span>
  </a>
  <a class="c30-door w1" href="../../contents/01-copilot-chat/%E9%A1%A7%E5%AE%A2%E3%82%AF%E3%83%AC%E3%83%BC%E3%83%A0%E3%82%92%E8%AB%96%E7%82%B9%E6%95%B4%E7%90%86%E3%81%97%E8%BF%94%E4%BF%A1%E6%A1%88%E3%81%BE%E3%81%A7%E4%BD%9C%E3%82%8B_CHAT-03.html">
    <span class="c30-num"><b>04</b><span>DOOR</span></span>
    <span class="c30-title">顧客クレームを論点整理し返信案まで作る</span>
    <span class="c30-subtitle">オプション：サンプルデータで実施</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w1" href="../../contents/01-copilot-chat/%E3%83%91%E3%83%BC%E3%83%88%E3%83%8A%E3%83%BC%E6%8F%90%E6%A1%88%E6%9B%B8%E3%82%92%E8%A6%81%E7%B4%84%E3%81%97%E7%A2%BA%E8%AA%8D%E3%81%99%E3%81%B9%E3%81%8D%E8%B3%AA%E5%95%8F%E3%82%92%E6%B4%97%E3%81%84%E5%87%BA%E3%81%99_CHAT-04.html">
    <span class="c30-num"><b>05</b><span>DOOR</span></span>
    <span class="c30-title">パートナー提案書を要約し確認すべき質問を洗い出す</span>
    <span class="c30-subtitle">オプション：サンプルデータで実施</span>
    <span class="c30-meta">約 10 分</span>
  </a>
</div>

<section class="c30-sec w2" id="week2">
  <h3><i></i>Week 2 ｜ Day 6-10：会議から成果を取り出す</h3>
  <p class="c30-secnote">要約から、そのまま送れる連絡文を作るまでを一気通貫で体験します。この週に短時間のチェックインを設け、利用頻度とブロッカーを確認します。</p>
</section>
<div class="c30-grid w2">
  <a class="c30-door w2 is-key" href="../../contents/03-outlook-teams/%E4%BC%9A%E8%AD%B0%E3%82%92%E8%A6%81%E7%B4%84%E3%81%97%E3%83%95%E3%82%A9%E3%83%AD%E3%83%BC%E3%82%A2%E3%83%83%E3%83%97%E9%80%A3%E7%B5%A1%E6%96%87%E3%82%92%E4%BD%9C%E3%82%8B_MTG-01.html">
    <span class="c30-num"><b>06</b><span>DOOR</span></span>
    <span class="c30-title">会議を要約しフォローアップ連絡文を作る</span>
    <span class="c30-subtitle">今週の体験</span>
    <span class="c30-meta">約 10 分</span>
  </a>
</div>

<section class="c30-sec w3" id="week3">
  <h3><i></i>Week 3 ｜ Day 11-15：つくる時間を短くする</h3>
  <p class="c30-secnote">一般的な回答と、自社ファイルを根拠にした回答の差を体感します。ここまでで、メール・会議・文書・データ・資料をひととおり試した状態になります。</p>
</section>
<div class="c30-grid w3">
  <a class="c30-door w3 is-key" href="../../contents/02-microsoft365-copilot/%E8%87%AA%E7%A4%BE%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%82%92%E6%A0%B9%E6%8B%A0%E3%81%AB%E7%AB%B6%E5%90%88%E5%88%86%E6%9E%90%E3%82%92%E8%87%AA%E7%A4%BE%E8%A6%96%E7%82%B9%E3%81%B8%E5%BC%95%E3%81%8D%E4%B8%8A%E3%81%92%E3%82%8B_CHAT-05.html">
    <span class="c30-num"><b>07</b><span>DOOR</span></span>
    <span class="c30-title">自社ファイルを根拠に競合分析を自社視点へ引き上げる</span>
    <span class="c30-subtitle">今週の体験</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w3" href="../../contents/05-word/%E7%9F%AD%E3%81%84%E3%83%96%E3%83%AA%E3%83%BC%E3%83%95%E3%82%9210%E7%AB%A0%E3%81%AE%E3%83%AD%E3%83%BC%E3%83%B3%E3%83%81%E6%96%87%E6%9B%B8%E3%81%AB%E5%B1%95%E9%96%8B%E3%81%99%E3%82%8B_WRD-01.html">
    <span class="c30-num"><b>08</b><span>DOOR</span></span>
    <span class="c30-title">短いブリーフを10章のローンチ文書に展開する</span>
    <span class="c30-subtitle">オプション：Word</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w3" href="../../contents/04-excel/%E5%A3%B2%E4%B8%8A%E3%83%87%E3%83%BC%E3%82%BF%E3%81%8B%E3%82%89%E5%9C%B0%E5%9F%9F%E5%88%A5%E3%81%AE%E5%BC%B1%E7%82%B9%E3%81%A8%E4%BE%A1%E6%A0%BC%E6%96%BD%E7%AD%96%E3%82%92%E5%B0%8E%E3%81%8F_XLS-01.html">
    <span class="c30-num"><b>09</b><span>DOOR</span></span>
    <span class="c30-title">売上データから地域別の弱点と価格施策を導く</span>
    <span class="c30-subtitle">オプション：Excel</span>
    <span class="c30-meta">約 15 分</span>
  </a>
  <a class="c30-door w3" href="../../contents/01-copilot-chat/%E3%82%AD%E3%83%A3%E3%83%B3%E3%83%9A%E3%83%BC%E3%83%B3%E3%83%96%E3%83%AA%E3%83%BC%E3%83%95%E3%81%A8%E5%BD%B9%E5%93%A1%E5%90%91%E3%81%91%E3%83%97%E3%83%AC%E3%82%BC%E3%83%B3%E9%AA%A8%E5%AD%90%E3%82%92%E4%BD%9C%E3%82%8B_CHAT-02.html">
    <span class="c30-num"><b>10</b><span>DOOR</span></span>
    <span class="c30-title">キャンペーンブリーフと役員向けプレゼン骨子を作る</span>
    <span class="c30-subtitle">オプション：Copilot Chat</span>
    <span class="c30-meta">約 15 分</span>
  </a>
  <a class="c30-door w3" href="../../contents/01-copilot-chat/%E7%AB%B6%E5%90%883%E7%A4%BE%E3%81%AE%E3%83%A1%E3%83%A2%E3%82%92%E6%AF%94%E8%BC%83%E8%A1%A8%E3%81%A8%E7%A4%BA%E5%94%86%E3%81%AB%E5%A4%89%E3%81%88%E3%82%8B_CHAT-01.html">
    <span class="c30-num"><b>11</b><span>DOOR</span></span>
    <span class="c30-title">競合3社のメモを比較表と示唆に変える</span>
    <span class="c30-subtitle">オプション：Copilot Chat</span>
    <span class="c30-meta">約 10 分</span>
  </a>
</div>

<section class="c30-sec w4" id="day15">
  <h3><i></i>Day 15 前後 ｜ 立ち止まる：自分の定番を 1 つ決める</h3>
  <p class="c30-secnote">このプログラムの山場です。新しい使い方を増やすのではなく、毎週・毎月すでに繰り返している作業を 1 つに絞り、残りの期間は必ず Copilot から始めます。</p>
</section>
<div class="c30-grid w4">
  <a class="c30-door w4 is-key" href="../../contents/07-agent-builder/%E7%B9%B0%E3%82%8A%E8%BF%94%E3%81%97%E6%A5%AD%E5%8B%99%E3%82%92%E6%B4%97%E3%81%84%E5%87%BA%E3%81%97%E3%81%A61%E4%BB%B6%E3%81%AB%E7%B5%9E%E3%82%8B_AGT-00.html">
    <span class="c30-num"><b>12</b><span>DOOR</span></span>
    <span class="c30-title">繰り返し業務を洗い出して1件に絞る</span>
    <span class="c30-subtitle">「私の定番」を決める</span>
    <span class="c30-meta">約 15 分</span>
  </a>
</div>

<div class="c30-stop" markdown="1">

**「私の定番」を書き出す**

```text
私の定番
　作業名：
　発生頻度：（毎週 / 毎月 / 案件ごと）
　これまでの所要時間：
　最初に使うプロンプト：
```

向いているのは、毎週または毎月必ず発生し、毎回ゼロから書き始めていて、要約・下書き・整理から始まる作業です。判断や交渉が本体の作業は向きません。

</div>

<section class="c30-sec w5" id="week4">
  <h3><i></i>Week 4 ｜ Day 16-20：決めた仕事を仕組みにする</h3>
  <p class="c30-secnote">Day 15 で決めた「自分の定番」を、目的・指示・参照する情報・スターター プロンプトに整理してエージェント化します。まず参考例で作り方を確認してください。</p>
</section>
<div class="c30-grid w5">
  <a class="c30-door w5 is-key" href="../../contents/07-agent-builder/%E9%A1%A7%E5%AE%A2%E3%83%95%E3%82%A9%E3%83%AD%E3%83%BC%E3%82%A2%E3%83%83%E3%83%97%E7%94%A8%E3%82%A8%E3%83%BC%E3%82%B8%E3%82%A7%E3%83%B3%E3%83%88%E3%82%92%E4%BD%9C%E3%82%8B_AGT-03.html">
    <span class="c30-num"><b>13</b><span>DOOR</span></span>
    <span class="c30-title">顧客フォローアップ用エージェントを作る</span>
    <span class="c30-subtitle">Agent Builder の参考例</span>
    <span class="c30-meta">約 20 分</span>
  </a>
  <a class="c30-door w5 is-key" href="../../contents/07-agent-builder/%E6%8F%90%E6%A1%88%E6%9B%B8%E4%BD%9C%E6%88%90%E3%82%A8%E3%83%BC%E3%82%B8%E3%82%A7%E3%83%B3%E3%83%88%E3%82%92%E4%BD%9C%E3%82%8B_AGT-04.html">
    <span class="c30-num"><b>14</b><span>DOOR</span></span>
    <span class="c30-title">提案書作成エージェントを作る</span>
    <span class="c30-subtitle">Agent Builder の参考例</span>
    <span class="c30-meta">約 15 分</span>
  </a>
  <a class="c30-door w5" href="../../contents/06-researcher-analyst/Researcher%E3%81%AB%E5%B8%82%E5%A0%B4%E8%AA%BF%E6%9F%BB%E3%83%96%E3%83%AA%E3%83%BC%E3%83%95%E3%82%92%E5%A7%94%E4%BB%BB%E3%81%99%E3%82%8B_AGT-01.html">
    <span class="c30-num"><b>15</b><span>DOOR</span></span>
    <span class="c30-title">Researcherに市場調査ブリーフを委任する</span>
    <span class="c30-subtitle">オプション：Researcher</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w5" href="../../contents/06-researcher-analyst/Analyst%E3%81%AB%E3%83%AA%E3%82%B9%E3%82%AF%E3%81%AE%E9%AB%98%E3%81%84SKU%E7%89%B9%E5%AE%9A%E3%82%92%E5%A7%94%E4%BB%BB%E3%81%99%E3%82%8B_AGT-02.html">
    <span class="c30-num"><b>16</b><span>DOOR</span></span>
    <span class="c30-title">Analystにリスクの高いSKU特定を委任する</span>
    <span class="c30-subtitle">オプション：Analyst</span>
    <span class="c30-meta">約 10 分</span>
  </a>
</div>

<section class="c30-sec w5" id="day21">
  <h3><i></i>Day 21 ｜ 成果を振り返り、次の一歩を決める</h3>
  <p class="c30-secnote">Day 15 で決めた作業を<strong>何回 Copilot で行ったか</strong>、<strong>かかる時間がどう変わったか</strong>を具体的な数字で整理します。各体験の証跡をまとめ、次に置き換えたい作業を 1 つ決めてください。</p>
</section>

---

## さらに試す

<p class="c30-secnote" id="more">プログラムの必修ではありませんが、同じ体験ラボに収録されている回です。定番が決まった後の練習や、参加者の関心に合わせた追加の回として使えます。</p>

<div class="c30-grid wx">
  <a class="c30-door wx" href="../../contents/01-copilot-chat/Copilot%E3%81%AF%E3%82%82%E3%81%86%E3%81%82%E3%81%AA%E3%81%9F%E3%81%AE%E4%BB%95%E4%BA%8B%E3%82%92%E7%9F%A5%E3%81%A3%E3%81%A6%E3%81%84%E3%82%8B_CHAT-05.html">
    <span class="c30-num"><b>17</b><span>DOOR</span></span>
    <span class="c30-title">Copilotはもうあなたの仕事を知っている</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/01-copilot-chat/%E5%BF%99%E3%81%97%E3%81%84%E6%9C%9D%E3%82%923%E5%88%86%E3%81%A7%E6%95%B4%E7%90%86%E3%81%99%E3%82%8B_CHAT-06.html">
    <span class="c30-num"><b>18</b><span>DOOR</span></span>
    <span class="c30-title">忙しい朝を3分で整理する</span>
    <span class="c30-meta">約 5 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/01-copilot-chat/%E4%BC%9A%E8%AD%B0%E5%89%8D%E3%81%AE_%E4%BD%95%E3%82%92%E8%A9%B1%E3%81%9B%E3%81%B0%E3%82%88%E3%81%84%E3%81%8B_%E3%82%92%E4%BD%9C%E3%82%8B_CHAT-08.html">
    <span class="c30-num"><b>19</b><span>DOOR</span></span>
    <span class="c30-title">会議前の「何を話せばよいか」を作る</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/01-copilot-chat/Week%201%E3%81%AE%E9%A9%9A%E3%81%8D%E3%82%92%E8%A8%80%E8%AA%9E%E5%8C%96%E3%81%99%E3%82%8B_CHAT-09.html">
    <span class="c30-num"><b>20</b><span>DOOR</span></span>
    <span class="c30-title">Week 1の驚きを言語化する</span>
    <span class="c30-meta">約 10 分 ＋ 共有 5 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/01-copilot-chat/%E6%9C%AA%E5%87%A6%E7%90%86%E3%83%A1%E3%83%BC%E3%83%AB%E3%82%92%E3%81%BE%E3%81%A8%E3%82%81%E3%81%A6%E6%95%B4%E7%90%86%E3%81%99%E3%82%8B_CHAT-10.html">
    <span class="c30-num"><b>21</b><span>DOOR</span></span>
    <span class="c30-title">未処理メールをまとめて整理する</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/01-copilot-chat/%E3%81%93%E3%81%AE%E7%94%BB%E9%9D%A2%E3%81%AF%E4%BD%95%E3%81%8B%E3%82%92%E6%92%AE%E3%81%A3%E3%81%A6%E8%81%9E%E3%81%8F_CHAT-11.html">
    <span class="c30-num"><b>22</b><span>DOOR</span></span>
    <span class="c30-title">この画面は何かを撮って聞く</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/01-copilot-chat/%E6%9C%9D%E3%81%BE%E3%81%9F%E3%81%AF%E5%A4%95%E6%96%B9%E3%81%AE%E3%83%97%E3%83%AD%E3%83%B3%E3%83%97%E3%83%88%E3%82%92%E5%AE%9A%E5%9E%8B%E5%8C%96%E3%81%99%E3%82%8B_CHAT-12.html">
    <span class="c30-num"><b>23</b><span>DOOR</span></span>
    <span class="c30-title">朝または夕方のプロンプトを定型化する</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/01-copilot-chat/1%E6%97%A5%E3%81%AE%E7%B5%82%E3%82%8F%E3%82%8A%E3%82%92Copilot%E3%81%A7%E7%B7%A0%E3%82%81%E3%82%8B_CHAT-13.html">
    <span class="c30-num"><b>24</b><span>DOOR</span></span>
    <span class="c30-title">1日の終わりをCopilotで締める</span>
    <span class="c30-meta">約 5 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/01-copilot-chat/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E7%8A%B6%E6%B3%81%E3%82%92%E6%A8%AA%E6%96%AD%E7%9A%84%E3%81%AB%E6%8A%8A%E6%8F%A1%E3%81%99%E3%82%8B_CHAT-14.html">
    <span class="c30-num"><b>25</b><span>DOOR</span></span>
    <span class="c30-title">プロジェクトの状況を横断的に把握する</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/01-copilot-chat/Copilot%E8%87%AA%E5%88%86%E3%81%AE%E4%BD%BF%E3%81%84%E6%96%B9%E3%81%8B%E3%82%89%E3%83%A6%E3%83%BC%E3%82%B9%E3%82%B1%E3%83%BC%E3%82%B9%E3%82%92%E4%BD%9C%E3%82%8B_CHAT-15.html">
    <span class="c30-num"><b>26</b><span>DOOR</span></span>
    <span class="c30-title">Copilot自分の使い方からユースケースを作る</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/01-copilot-chat/%E8%87%AA%E5%88%86%E5%B0%82%E7%94%A8%E3%81%AE%E3%80%8C%E9%89%84%E6%9D%BF%E3%83%97%E3%83%AD%E3%83%B3%E3%83%97%E3%83%88%E3%80%8D%E3%82%92%E4%BD%9C%E3%82%8B_CHAT-16.html">
    <span class="c30-num"><b>27</b><span>DOOR</span></span>
    <span class="c30-title">自分専用の「鉄板プロンプト」を作る</span>
    <span class="c30-meta">約 20 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/01-copilot-chat/%E8%87%AA%E7%A4%BE%E3%81%AE%E3%83%9B%E3%83%BC%E3%83%A0%E3%83%9A%E3%83%BC%E3%82%B8%E3%81%8B%E3%82%89%E4%BC%81%E6%A5%AD%E7%B4%B9%E4%BB%8B%E3%82%A4%E3%83%B3%E3%83%95%E3%82%A9%E3%82%B0%E3%83%A9%E3%83%95%E3%82%A3%E3%83%83%E3%82%AF%E3%82%92%E4%BD%9C%E3%82%8B_CHAT-IMG-02.html">
    <span class="c30-num"><b>28</b><span>DOOR</span></span>
    <span class="c30-title">自社のホームページから企業紹介インフォグラフィックを作る</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/02-microsoft365-copilot/%E8%A4%87%E6%95%B0%E8%B3%87%E6%96%99%E3%82%92%E6%AF%94%E8%BC%83%E3%81%99%E3%82%8B_CHAT-15.html">
    <span class="c30-num"><b>29</b><span>DOOR</span></span>
    <span class="c30-title">複数資料を比較する</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/02-microsoft365-copilot/%E6%97%A2%E5%AD%98%E8%B3%87%E6%96%99%E3%82%92%E8%A6%81%E7%B4%84%E3%81%99%E3%82%8B_CHAT-17.html">
    <span class="c30-num"><b>30</b><span>DOOR</span></span>
    <span class="c30-title">既存資料を要約する</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/03-outlook-teams/%E9%95%B7%E3%81%84%E3%83%A1%E3%83%BC%E3%83%AB%E3%82%B9%E3%83%AC%E3%83%83%E3%83%89%E3%81%8B%E3%82%89%E7%B5%90%E8%AB%96%E3%81%A0%E3%81%91%E3%82%92%E5%BE%97%E3%82%8B_CHAT-07.html">
    <span class="c30-num"><b>31</b><span>DOOR</span></span>
    <span class="c30-title">長いメールスレッドから結論だけを得る</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/03-outlook-teams/%E3%83%A1%E3%83%BC%E3%83%AB%E8%BF%94%E4%BF%A1%E3%82%923%E3%83%91%E3%82%BF%E3%83%BC%E3%83%B3%E4%BD%9C%E3%82%8B_MAL-01.html">
    <span class="c30-num"><b>32</b><span>DOOR</span></span>
    <span class="c30-title">メール返信を3パターン作る</span>
    <span class="c30-meta">約 5 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/03-outlook-teams/%E4%BC%9A%E8%AD%B0%E5%BE%8C%E3%81%AE%E3%82%A2%E3%82%AF%E3%82%B7%E3%83%A7%E3%83%B3%E3%82%92%E8%87%AA%E5%88%86%E7%94%A8%E3%81%AB%E5%86%8D%E6%95%B4%E7%90%86%E3%81%99%E3%82%8B_MTG-02.html">
    <span class="c30-num"><b>33</b><span>DOOR</span></span>
    <span class="c30-title">会議後のアクションを自分用に再整理する</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/03-outlook-teams/%E4%BC%9A%E8%AD%B0%E5%89%8D%E3%81%8B%E3%82%89%E4%BC%9A%E8%AD%B0%E5%BE%8C%E3%81%BE%E3%81%A7%E3%82%92%E4%B8%80%E9%80%A3%E3%81%A7%E4%BD%BF%E3%81%86_MTG-03.html">
    <span class="c30-num"><b>34</b><span>DOOR</span></span>
    <span class="c30-title">会議前から会議後までを一連で使う</span>
    <span class="c30-meta">会議前 10 分 ＋ 会議後 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/05-word/%E9%95%B7%E3%81%84%E6%96%87%E6%9B%B8%E3%82%92%E3%83%AC%E3%83%93%E3%83%A5%E3%83%BC%E3%81%97%E3%81%A6%E3%82%82%E3%82%89%E3%81%86_WRD-02.html">
    <span class="c30-num"><b>35</b><span>DOOR</span></span>
    <span class="c30-title">長い文書をレビューしてもらう</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/07-agent-builder/%E8%BB%BD%E9%87%8FAgent%20Builder%E4%BD%93%E9%A8%93_AGT-01.html">
    <span class="c30-num"><b>36</b><span>DOOR</span></span>
    <span class="c30-title">軽量Agent Builder体験</span>
    <span class="c30-meta">約 25 分</span>
  </a>
  <a class="c30-door wx" href="../../contents/07-agent-builder/%E3%83%9B%E3%83%AF%E3%82%A4%E3%83%88%E3%83%9C%E3%83%BC%E3%83%89%E5%86%99%E7%9C%9F%E3%81%8B%E3%82%89%E8%AD%B0%E4%BA%8B%E9%8C%B2%E3%81%A8%E3%82%B9%E3%83%A9%E3%82%A4%E3%83%89%E3%82%92%E4%BD%9C%E3%82%8B%E3%82%A8%E3%83%BC%E3%82%B8%E3%82%A7%E3%83%B3%E3%83%88_AGT-02.html">
    <span class="c30-num"><b>37</b><span>DOOR</span></span>
    <span class="c30-title">ホワイトボード写真から議事録とスライドを作るエージェント</span>
    <span class="c30-meta">約 30 分</span>
  </a>
</div>

---

## はじめての方へ

<div class="c30-start" markdown="1">

1. Copilot Chat を開き、**Work** が選択されていることを確認する
2. 今日の扉を開き、**TRY — 手順**のプロンプトをそのまま貼り付ける
3. 出てきた答えを鵜呑みにせず、**根拠リンクを 1 つ開いて確認する**
4. 最後の **REFLECT — 振り返り**に、その日のうちに答える

</div>

各ページは「目的 / 所要 / 利用 / 入力 / 成果」→ シナリオ → TRY（手順とプロンプト）→ REFLECT → NEXT の順に並んでいます。
うまくいかなかった依頼にも価値があります。**どう指示を変えれば直るか**まで書き残してください。

---

## 全体の流れ

| 期間 | 参加者の到達点 |
|---|---|
| Week 1〜3 | できることを**広く知る** |
| **Day 15 前後** | **立ち止まり、自分の定番を 1 つ決める** |
| Week 4 | 決めた仕事を**仕組みにして繰り返し活用する** |
| Day 21 | 成果を言葉にする |

参加者が Copilot の価値を実感するには、さまざまな機能を試すだけでなく、**ひとつの作業で繰り返し使うこと**が重要です。
Week 1〜3 で選択肢を広げ、Day 15 で定番にする作業を 1 つ決め、Week 4 で定着させる流れを支援します。

---

## 続けるコツ

- **新しい扉は週 3 回**くらいで十分です。残りの日は、気に入ったプロンプトを繰り返し使ってください。
- 効いたプロンプトは保存して、毎営業日使えるようにします。
- 週に 1 回、チームのチャネルに「今週いちばん良かった 1 件」を投稿します。
- 時間短縮は**自分で計測**します。Copilot に見積もらせないでください。

---

## 実施にあたって

- 自分の実データを使います。共有・公開する成果物に機密情報が含まれていないか、必ず確認してください。
- 実業務のデータを扱えない場合に備えてサンプルデータを使った体験も用意していますが、**基本的には実業務のデータを使ってください**。
- 利用できる機能は、ライセンスとテナント設定によって異なります。
- Excel の体験は、ファイルを OneDrive に保存し AutoSave を有効にする必要があります。
- Agent Builder の体験は、管理者設定・テナント構成・ライセンスによって可否が異なります。事前に管理者へ確認してください。
- ハンズオンが難しい回は、ファシリテーターのデモを見ながら進めてください。

---

<p class="c30-meta">運営・ファシリテーター向けの進行ルールと測定項目は <a href="./README.html">プログラム概要</a> にまとめています。</p>

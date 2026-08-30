---
layout: default
title: Copilot in 30
description: 30 日間で「自分の仕事」に Copilot を溶かし込む体験カレンダー
---

<!-- GitHub Pages（Jekyll）用のトップページです。
     各扉のリンク先は ./contents/copilot-chat/ 配下の .html です。Jekyll が .md を .html として出力するためです。
     Jekyll を使わず .md のまま配信する場合は、href の拡張子を .html → .md に置換してください。
     リポジトリ上（github.com）で直接見る場合は README.md の一覧をご利用ください。 -->

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
.c30-legend i{width:.7rem;height:.7rem;border-radius:50%;display:inline-block;}

.c30-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(150px,1fr));gap:.8rem;margin:0 0 2rem;}
.c30-door{display:block;position:relative;padding:.9rem .9rem 1rem;border-radius:12px;text-decoration:none;
  border:1px solid #e3e6ea;background:#fff;color:#1b1b1b;overflow:hidden;
  transition:transform .15s ease,box-shadow .15s ease,border-color .15s ease;}
.c30-door:before{content:"";position:absolute;inset:0 auto 0 0;width:5px;background:var(--c);}
.c30-door:hover{transform:translateY(-3px);box-shadow:0 8px 18px rgba(16,32,60,.14);
  border-color:var(--c);text-decoration:none;}
.c30-num{display:flex;align-items:baseline;gap:.35rem;font-weight:700;color:var(--c);letter-spacing:.02em;}
.c30-num b{font-size:1.6rem;line-height:1;}
.c30-num span{font-size:.72rem;opacity:.75;}
.c30-title{display:block;margin:.5rem 0 .35rem;font-size:.86rem;line-height:1.45;font-weight:600;color:#1b1b1b;}
.c30-subtitle{display:block;margin: 0rem 0 .55rem;font-size:.75rem;line-height:1.45;font-weight:600;color:#1b1b1b;}     
.c30-meta{font-size:.72rem;color:#61697a;}
.c30-door.is-key:after{content:"★";position:absolute;top:.6rem;right:.7rem;font-size:.8rem;color:var(--c);}

.w1{--c:#c2410c;}
.w2{--c:#1668b8;}
.w3{--c:#0f766e;}
.w4{--c:#6d28d9;}
.w5{--c:#b91c1c;}

.c30-start{border:1px solid #e3e6ea;border-radius:12px;padding:1rem 1.2rem;background:#fafbfc;}
.c30-start ol{margin:.4rem 0 0;padding-left:1.2rem;}
.c30-start li{margin:.25rem 0;line-height:1.7;}

@media (max-width:480px){.c30-grid{grid-template-columns:repeat(auto-fill,minmax(132px,1fr));gap:.6rem;}}
</style>

<div class="c30-hero">
  <h1>Copilot in 30</h1>
  <p>1 日ひとつ、扉を開けるように試す 30 日間。<br>
  使うのはサンプルデータではなく、<strong>あなた自身のメール・会議・チャット・ファイル</strong>です。</p>
  <p class="c30-tag">所要 5〜20 分 / 日 &nbsp;·&nbsp; Microsoft 365 Copilot</p>
</div>

## 今日の扉を開ける

進む順番は Day 1 からがおすすめですが、**開けたい扉から開けても構いません**。
★ の付いた扉は、期間中に何度も繰り返す価値のある体験です。

<ul class="c30-legend">
  <li class="w1"><i style="background:var(--c)"></i>Week 1：まず驚く（Day 1–5）</li>
  <li class="w2"><i style="background:var(--c)"></i>Week 2：毎日の面倒を減らす（Day 6–12）</li>
  <li class="w3"><i style="background:var(--c)"></i>Week 3：成果物を作る（Day 13–19）</li>
  <li class="w4"><i style="background:var(--c)"></i>Week 4：仕事をつなげる（Day 20–25）</li>
  <li class="w5"><i style="background:var(--c)"></i>Final Week：自分専用化と価値証明（Day 26–30）</li>
</ul>

<div class="c30-grid">
  <a class="c30-door w1" href="./contents/copilot-chat/Copilot%E3%81%AB%E8%87%AA%E5%88%86%E3%81%AE%E7%8F%BE%E5%9C%A8%E5%9C%B0%E3%82%92%E8%81%9E%E3%81%8F_DAY-01.html">
    <span class="c30-num"><b>01</b><span>DOOR</span></span>
    <span class="c30-title">Copilotに自分の現在地を聞く </span>
　　<span class="c30-subtitle">「いま抱えている仕事、5件」— 一言も説明していないのに</span>   
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w1 is-key" href="./contents/copilot-chat/%E5%BF%99%E3%81%97%E3%81%84%E6%9C%9D%E3%82%923%E5%88%86%E3%81%A7%E6%95%B4%E7%90%86%E3%81%99%E3%82%8B_DAY-02.html">
    <span class="c30-num"><b>02</b><span>DOOR</span></span>
    <span class="c30-title">忙しい朝を3分で整理する</span>
    <span class="c30-meta">約 5 分</span>
  </a>
  <a class="c30-door w1" href="./contents/copilot-chat/%E9%95%B7%E3%81%84%E3%83%A1%E3%83%BC%E3%83%AB%E3%82%B9%E3%83%AC%E3%83%83%E3%83%89%E3%81%8B%E3%82%89%E7%B5%90%E8%AB%96%E3%81%A0%E3%81%91%E3%82%92%E5%BE%97%E3%82%8B_DAY-03.html">
    <span class="c30-num"><b>03</b><span>DOOR</span></span>
    <span class="c30-title">長いメールスレッドから結論だけを得る</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w1 is-key" href="./contents/copilot-chat/%E4%BC%9A%E8%AD%B0%E5%89%8D%E3%81%AE%E3%80%8C%E4%BD%95%E3%82%92%E8%A9%B1%E3%81%9B%E3%81%B0%E3%82%88%E3%81%84%E3%81%8B%E3%80%8D%E3%82%92%E4%BD%9C%E3%82%8B_DAY-04.html">
    <span class="c30-num"><b>04</b><span>DOOR</span></span>
    <span class="c30-title">会議前の「何を話せばよいか」を作る</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w1" href="./contents/copilot-chat/Week%201%E3%81%AE%E9%A9%9A%E3%81%8D%E3%82%92%E8%A8%80%E8%AA%9E%E5%8C%96%E3%81%99%E3%82%8B_DAY-05.html">
    <span class="c30-num"><b>05</b><span>DOOR</span></span>
    <span class="c30-title">Week 1の驚きを言語化する</span>
    <span class="c30-meta">約 10 分 ＋ 共有 5 分</span>
  </a>
  <a class="c30-door w2" href="./contents/copilot-chat/この画面は何かを撮って聞く_SHOT-02.html">
    <span class="c30-num"><b>06</b><span>DOOR</span></span>
    <span class="c30-title">この画面は何なの？を撮って聞く</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w2" href="./contents/copilot-chat/%E6%96%87%E7%AB%A0%E3%82%92%E3%80%8C%E7%9B%B8%E6%89%8B%E3%81%AB%E4%BC%9D%E3%82%8F%E3%82%8B%E5%BD%A2%E3%80%8D%E3%81%B8%E5%A4%89%E6%8F%9B%E3%81%99%E3%82%8B_DAY-07.html">
    <span class="c30-num"><b>07</b><span>DOOR</span></span>
    <span class="c30-title">文章を「相手に伝わる形」へ変換する</span>
    <span class="c30-meta">約 5 分</span>
  </a>
  <a class="c30-door w2" href="./contents/copilot-chat/%E3%83%A1%E3%83%BC%E3%83%AB%E8%BF%94%E4%BF%A1%E3%82%923%E3%83%91%E3%82%BF%E3%83%BC%E3%83%B3%E4%BD%9C%E3%82%8B_DAY-08.html">
    <span class="c30-num"><b>08</b><span>DAY</span></span>
    <span class="c30-title">メール返信を3パターン作る</span>
    <span class="c30-meta">約 5 分</span>
  </a>
  <a class="c30-door w2 is-key" href="./contents/copilot-chat/%E4%BC%9A%E8%AD%B0%E5%BE%8C%E3%81%AE%E3%82%A2%E3%82%AF%E3%82%B7%E3%83%A7%E3%83%B3%E3%82%92%E8%87%AA%E5%88%86%E7%94%A8%E3%81%AB%E5%86%8D%E6%95%B4%E7%90%86%E3%81%99%E3%82%8B_DAY-09.html">
    <span class="c30-num"><b>09</b><span>DAY</span></span>
    <span class="c30-title">会議後のアクションを自分用に再整理する</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w2" href="./contents/copilot-chat/%E8%A6%8B%E8%90%BD%E3%81%A8%E3%81%97%E3%81%A6%E3%81%84%E3%82%8B%E4%BE%9D%E9%A0%BC%E3%82%92%E6%8E%A2%E3%81%99_DAY-10.html">
    <span class="c30-num"><b>10</b><span>DAY</span></span>
    <span class="c30-title">見落としている依頼を探す</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w2" href="./contents/copilot-chat/1%E6%97%A5%E3%81%AE%E7%B5%82%E3%82%8F%E3%82%8A%E3%82%92Copilot%E3%81%A7%E7%B7%A0%E3%82%81%E3%82%8B_DAY-11.html">
    <span class="c30-num"><b>11</b><span>DAY</span></span>
    <span class="c30-title">1日の終わりをCopilotで締める</span>
    <span class="c30-meta">約 5 分</span>
  </a>
  <a class="c30-door w2" href="./contents/copilot-chat/%E6%9C%9D%E3%81%BE%E3%81%9F%E3%81%AF%E5%A4%95%E6%96%B9%E3%81%AE%E3%83%97%E3%83%AD%E3%83%B3%E3%83%97%E3%83%88%E3%82%92%E5%AE%9A%E5%9E%8B%E5%8C%96%E3%81%99%E3%82%8B_DAY-12.html">
    <span class="c30-num"><b>12</b><span>DAY</span></span>
    <span class="c30-title">朝または夕方のプロンプトを定型化する</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w3" href="./contents/copilot-chat/%E6%97%A2%E5%AD%98%E8%B3%87%E6%96%99%E3%82%92%E8%A6%81%E7%B4%84%E3%81%99%E3%82%8B_DAY-13.html">
    <span class="c30-num"><b>13</b><span>DAY</span></span>
    <span class="c30-title">既存資料を要約する</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w3" href="./contents/copilot-chat/%E8%A4%87%E6%95%B0%E8%B3%87%E6%96%99%E3%82%92%E6%AF%94%E8%BC%83%E3%81%99%E3%82%8B_DAY-14.html">
    <span class="c30-num"><b>14</b><span>DAY</span></span>
    <span class="c30-title">複数資料を比較する</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w3" href="./contents/copilot-chat/%E7%AE%87%E6%9D%A1%E6%9B%B8%E3%81%8D%E3%81%8B%E3%82%89%E6%96%87%E6%9B%B8%E3%81%AE%E5%88%9D%E7%A8%BF%E3%82%92%E4%BD%9C%E3%82%8B_DAY-15.html">
    <span class="c30-num"><b>15</b><span>DAY</span></span>
    <span class="c30-title">箇条書きから文書の初稿を作る</span>
    <span class="c30-meta">約 15 分</span>
  </a>
  <a class="c30-door w3" href="./contents/copilot-chat/%E9%95%B7%E3%81%84%E6%96%87%E6%9B%B8%E3%82%92%E3%83%AC%E3%83%93%E3%83%A5%E3%83%BC%E3%81%97%E3%81%A6%E3%82%82%E3%82%89%E3%81%86_DAY-16.html">
    <span class="c30-num"><b>16</b><span>DAY</span></span>
    <span class="c30-title">長い文書をレビューしてもらう</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w3" href="./contents/copilot-chat/Word%E3%81%8B%E3%82%89%E3%83%97%E3%83%AC%E3%82%BC%E3%83%B3%E3%83%86%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%81%AE%E6%A7%8B%E6%88%90%E3%82%92%E4%BD%9C%E3%82%8B_DAY-17.html">
    <span class="c30-num"><b>17</b><span>DAY</span></span>
    <span class="c30-title">Wordからプレゼンテーションの構成を作る</span>
    <span class="c30-meta">約 15 分</span>
  </a>
  <a class="c30-door w3 is-key" href="./contents/copilot-chat/%E8%87%AA%E7%A4%BE%E7%B4%B9%E4%BB%8B%E3%82%92%E8%A6%96%E8%A6%9A%E5%8C%96%E3%81%99%E3%82%8B_DAY-18.html">
    <span class="c30-num"><b>18</b><span>DAY</span></span>
    <span class="c30-title">自社紹介を視覚化する</span>
    <span class="c30-meta">約 15 分</span>
  </a>
  <a class="c30-door w3" href="./contents/copilot-chat/Excel%E3%83%87%E3%83%BC%E3%82%BF%E3%81%8B%E3%82%89%E7%A4%BA%E5%94%86%E3%82%92%E5%BE%97%E3%82%8B_DAY-19.html">
    <span class="c30-num"><b>19</b><span>DAY</span></span>
    <span class="c30-title">Excelデータから示唆を得る</span>
    <span class="c30-meta">約 15 分</span>
  </a>
  <a class="c30-door w4" href="./contents/copilot-chat/%E4%BC%9A%E8%AD%B0%E5%89%8D%E3%81%8B%E3%82%89%E4%BC%9A%E8%AD%B0%E5%BE%8C%E3%81%BE%E3%81%A7%E3%82%92%E4%B8%80%E9%80%A3%E3%81%A7%E4%BD%BF%E3%81%86_DAY-20.html">
    <span class="c30-num"><b>20</b><span>DAY</span></span>
    <span class="c30-title">会議前から会議後までを一連で使う</span>
    <span class="c30-meta">会議前 10 分 ＋ 会議後 10 分</span>
  </a>
  <a class="c30-door w4" href="./contents/copilot-chat/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E7%8A%B6%E6%B3%81%E3%82%92%E6%A8%AA%E6%96%AD%E7%9A%84%E3%81%AB%E6%8A%8A%E6%8F%A1%E3%81%99%E3%82%8B_DAY-21.html">
    <span class="c30-num"><b>21</b><span>DAY</span></span>
    <span class="c30-title">プロジェクトの状況を横断的に把握する</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w4" href="./contents/copilot-chat/%E3%80%8C%E6%9C%80%E6%96%B0%E7%8A%B6%E6%B3%81%E3%82%92%E6%95%99%E3%81%88%E3%81%A6%E3%80%8D%E3%82%92%E8%87%AA%E5%88%86%E3%81%AE%E6%A1%88%E4%BB%B6%E3%81%A7%E4%BD%BF%E3%81%86_DAY-22.html">
    <span class="c30-num"><b>22</b><span>DAY</span></span>
    <span class="c30-title">「最新状況を教えて」を自分の案件で使う</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w4" href="./contents/copilot-chat/%E5%BD%B9%E5%89%B2%E5%88%A5%E3%81%AE%E3%83%A6%E3%83%BC%E3%82%B9%E3%82%B1%E3%83%BC%E3%82%B9%E3%82%92%E4%BD%9C%E3%82%8B_DAY-23.html">
    <span class="c30-num"><b>23</b><span>DAY</span></span>
    <span class="c30-title">役割別のユースケースを作る</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w4 is-key" href="./contents/copilot-chat/%E8%87%AA%E5%88%86%E5%B0%82%E7%94%A8%E3%81%AE%E3%80%8C%E9%89%84%E6%9D%BF%E3%83%97%E3%83%AD%E3%83%B3%E3%83%97%E3%83%88%E3%80%8D%E3%82%92%E4%BD%9C%E3%82%8B_DAY-24.html">
    <span class="c30-num"><b>24</b><span>DAY</span></span>
    <span class="c30-title">自分専用の「鉄板プロンプト」を作る</span>
    <span class="c30-meta">約 15 分</span>
  </a>
  <a class="c30-door w4" href="./contents/copilot-chat/%E3%83%81%E3%83%BC%E3%83%A0%E3%81%A7%E3%83%97%E3%83%AD%E3%83%B3%E3%83%97%E3%83%88%E3%82%92%E4%BA%A4%E6%8F%9B%E3%81%99%E3%82%8B_DAY-25.html">
    <span class="c30-num"><b>25</b><span>DAY</span></span>
    <span class="c30-title">チームでプロンプトを交換する</span>
    <span class="c30-meta">約 15 分 ＋ 共有 10 分</span>
  </a>
  <a class="c30-door w5" href="./contents/copilot-chat/%E7%B9%B0%E3%82%8A%E8%BF%94%E3%81%97%E6%A5%AD%E5%8B%99%E3%82%921%E3%81%A4%E9%81%B8%E3%81%B6_DAY-26.html">
    <span class="c30-num"><b>26</b><span>DAY</span></span>
    <span class="c30-title">繰り返し業務を1つ選ぶ</span>
    <span class="c30-meta">約 10 分</span>
  </a>
  <a class="c30-door w5" href="./contents/copilot-chat/%E8%BB%BD%E9%87%8FAgent%20Builder%E4%BD%93%E9%A8%93_DAY-27.html">
    <span class="c30-num"><b>27</b><span>DAY</span></span>
    <span class="c30-title">軽量Agent Builder体験</span>
    <span class="c30-meta">約 20 分</span>
  </a>
  <a class="c30-door w5" href="./contents/copilot-chat/ホワイトボード写真から議事録とスライドを作るエージェント_AGENT-01.html">
    <span class="c30-num"><b>28</b><span>DAY</span></span>
    <span class="c30-title">ホワイトボード写真から議事録を作るエージェント</span>
    <span class="c30-meta">約 15 分</span>
  </a>
  <a class="c30-door w5" href="./contents/copilot-chat/%E8%87%AA%E5%88%86%E3%81%AE30%E6%97%A5%E9%96%93%E3%81%AE%E4%BE%A1%E5%80%A4%E3%82%92%E3%81%BE%E3%81%A8%E3%82%81%E3%82%8B_DAY-29.html">
    <span class="c30-num"><b>29</b><span>DAY</span></span>
    <span class="c30-title">自分の30日間の価値をまとめる</span>
    <span class="c30-meta">約 15 分</span>
  </a>
  <a class="c30-door w5 is-key" href="./contents/copilot-chat/%E3%80%8C%E6%98%8E%E6%97%A5%E3%81%8B%E3%82%89Copilot%E3%81%8C%E3%81%AA%E3%81%8F%E3%81%AA%E3%81%A3%E3%81%9F%E3%82%89%E3%80%8D%E3%82%92%E8%80%83%E3%81%88%E3%82%8B_DAY-30.html">
    <span class="c30-num"><b>30</b><span>DAY</span></span>
    <span class="c30-title">「明日からCopilotがなくなったら」を考える</span>
    <span class="c30-meta">約 20 分</span>
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

各ページは「目的 / 所要 / 入力 / 成果」→ シナリオ → TRY（手順とプロンプト）→ REFLECT → NEXT の順に並んでいます。
うまくいかなかった依頼にも価値があります。**どう指示を変えれば直るか**まで書き残してください。

---

## 5 週間の流れ

| 期間 | テーマ | このころの実感 |
|---|---|---|
| Day 1–5 | まず驚く | 「こんなことまで分かるの？」 |
| Day 6–12 | 毎日の面倒を減らす | 「これ、毎日使える」 |
| Day 13–19 | 成果物を作る | 「ゼロから作らなくてよい」 |
| Day 20–25 | 仕事をつなげる | 「仕事の進め方そのものが変わる」 |
| Day 26–30 | 自分専用化と価値証明 | 「なくなると困る」 |

30 日間の目的は、30 個の機能を覚えることではありません。
「自分の朝」「自分の会議」「自分のメール」「自分の成果物」「自分の鉄板プロンプト」を持ち、
最終日に**元の仕事の仕方へ戻るコスト**を自分の言葉で説明できる状態になることです。

---

## 続けるコツ

- **新しい扉は週 3 回**くらいで十分です。残りの日は、気に入ったプロンプトを繰り返し使ってください。
- 効いたプロンプトは保存して、毎営業日使えるようにします（[朝または夕方のプロンプトを定型化する｜DAY-12](./contents/copilot-chat/%E6%9C%9D%E3%81%BE%E3%81%9F%E3%81%AF%E5%A4%95%E6%96%B9%E3%81%AE%E3%83%97%E3%83%AD%E3%83%B3%E3%83%97%E3%83%88%E3%82%92%E5%AE%9A%E5%9E%8B%E5%8C%96%E3%81%99%E3%82%8B_DAY-12.html)）。
- 週に 1 回、チームのチャネルに「今週いちばん良かった 1 件」を投稿します。
- 時間短縮は**自分で計測**します。Copilot に見積もらせないでください（[Copilotなしで行っていた方法と比較する｜DAY-28](./contents/copilot-chat/Copilot%E3%81%AA%E3%81%97%E3%81%A7%E8%A1%8C%E3%81%A3%E3%81%A6%E3%81%84%E3%81%9F%E6%96%B9%E6%B3%95%E3%81%A8%E6%AF%94%E8%BC%83%E3%81%99%E3%82%8B_DAY-28.html)）。

---

## 実施にあたって

- 自分の実データを使います。共有・公開する成果物に機密情報が含まれていないか、必ず確認してください。
- 利用できる機能は、ライセンスとテナント設定によって異なります。
- Excel の体験（[Excelデータから示唆を得る｜DAY-19](./contents/copilot-chat/Excel%E3%83%87%E3%83%BC%E3%82%BF%E3%81%8B%E3%82%89%E7%A4%BA%E5%94%86%E3%82%92%E5%BE%97%E3%82%8B_DAY-19.html)）は、ファイルを OneDrive に保存し AutoSave を有効にする必要があります。
- エージェントの作成・共有（[軽量Agent Builder体験｜DAY-27](./contents/copilot-chat/%E8%BB%BD%E9%87%8FAgent%20Builder%E4%BD%93%E9%A8%93_DAY-27.html)）は、管理者設定・テナント構成・ライセンスによって可否が異なります。事前に管理者へ確認してください。
- ハンズオンが難しい回は、ファシリテーターのデモを見ながら進めてください。

---

<p class="c30-meta">運営・ファシリテーター向けの進行ルールと測定項目は <a href="README.html">プログラム概要</a> にまとめています。</p>

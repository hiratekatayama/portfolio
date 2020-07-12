---
layout: default
---

<header class="bloghead">
    <nav class="bloghead-nav">
        {% for nav in site.nav %}
	<a class="text-link" href="{{ nav.href }}">{{ nav.name }}<span> &nbsp;/&nbsp; </span></a> {% endfor %}
    </nav>
</header>

## About Me {#aboutme}
筑波大学大学院理工情報生命学術院システム情報学研究群理工情報学位プログラム
<a class="text-link" href="http://kde.cs.tsukuba.ac.jp">北川・天笠データ工学研究室</a> 所属

平方 俊行 (Toshiyuki Hirakata)

Email: hirakata [at] kde.cs.tsukuba.ac.jp

<ul class="social">
  {% if site.github %}
  <a type="button" href="http://github.com/{{ site.github }}">
    <i class="fa fa-github"></i>
  </a>
  {% endif %}
</ul>

## Research Interest {#research}
データ工学，データベースシステム，データマイニングに関する分野に興味・関心があります．
現在，ソーシャルネットワークを管理するグラフデータベースへの問合せ処理高速化に関する研究をしております．
* keyword
  * GDB
  * RDF
  * index

## Publications {#publications}
* 平方 俊行，楠 和馬，波多野賢治. "クエリログの部分的利用を考慮したグラフの集約演算高速化" 第12回データ工学と情報マネジメントに関するフォーラム. DEIM Forum 2020 C3-4. p.1-5
* 八島 裕史，平方 俊行，草野 彰吾，笹田 大翔. "統計的因果推論を用いた地方の課題解決の提案". SAS Forum Japan 2019

## Competition・Hackathon {#competitionhackathon} 
データ分析に関するコンペにいくつか参加しています．
* "富山県における就職の魅力度向上と定住化促進計画". 第2回和歌山県データ利活用コンペティション
* "クリック率向上を目指したクエリ内の略語展開による検索補助法". WebDB Forum DBSJ Data Challenge 2018

## Awards {#awards}
* "リクルートテクノロジーズ賞". WebDB Forum DBSJ Data Challenge 2018
* "SAS賞". 第2回和歌山県データ利活用コンペティション

## Personal Interest {#personal}
グラフデータベースやRDBMSへの問合せ処理高速化に関心があります．

## Experience {#experience}
* 2019-03~06 SAS Institute Japan
* 2020-05~ SMS 株式会社

## Education {#education}
* 2016-04 同志社大学文化情報学部入学
* 2018-04 同志社大学 波多野研究室配属 <a class="text-link" href="https://www.cis.doshisha.ac.jp/course/foundationaldata/student/
">同志社大学データ科学基盤コース 平方さんと文化情報学部 ～学生インタビュー～</a>
* 2020-04 筑波大学大学院理工情報生命学術院システム情報学研究群理工情報学位プログラム入学 北川・天笠データ工学研究室配属

## Hobby {#hobby}
* キャンプ
* サイクリング
* テニス

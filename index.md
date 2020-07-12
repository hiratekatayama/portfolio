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
<a class="text-link" href="http://kde.cs.tsukuba.ac.jp">北川・天笠データ工学研究室</a>

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

グラフデータベースへの問合せ処理高速化に関する研究をしております．
* keyword
  * GDB
  * RDF

## Publications {#publications}
* クエリログの部分的利用を考慮したグラフの集約演算高速化 第12回データ工学と情報マネジメントに関するフォーラム. DEIM Forum 2020 C3-4. p.1-5

## Awards {#awards}
* WebDB Forum DBSJ Data Challenge リクルートテクノロジーズ賞
* 第2回和歌山県データ利活用コンペティション SAS賞

## Personal Interest {#personal}
グラフデータベースやRDBMSへの問合せ処理高速化に関心があります．

## Experience {#experience}
* SAS Institute Japan
* SMS 株式会社

## Education {#education}
* 2016-04 同志社大学文化情報学部入学
* 2018-04 同志社大学 波多野研究室配属
* 2020-04 筑波大学大学院理工情報生命学術院システム情報学研究群理工情報学位プログラム入学 北川・天笠データ工学研究室配属

## Hobby {#hobby}
* キャンプ
* サイクリング
* テニス

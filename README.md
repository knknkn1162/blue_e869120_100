# これは何？

[競プロ・AtCoder上達のガイドライン【中級編】](https://qiita.com/e869120/items/eb50fdaece12be418faa#2-3-%E5%88%86%E9%87%8E%E5%88%A5%E5%88%9D%E4%B8%AD%E7%B4%9A%E8%80%85%E3%81%8C%E8%A7%A3%E3%81%8F%E3%81%B9%E3%81%8D%E9%81%8E%E5%8E%BB%E5%95%8F%E7%B2%BE%E9%81%B8-100-%E5%95%8F)のC言語による全問解答および解説。

# 全問題一覧

|todo|idx|問題名|難易度(1~5)|comment by @E869120 |方針/解答例|
|---|---|---|---|---|---|
||1|[組み合わせの数](https://onlinejudge.u-aizu.ac.jp/problems/ITP1_7_B)|1|基本問題|[全探索](https://onlinejudge.u-aizu.ac.jp/solutions/problem/ITP1_7_B/review/4281105/knknkn1162/C)|
||2|[AtCoder Beginner Contest 106 B - 105](https://atcoder.jp/contests/abc106/tasks/abc106_b)|1|-|[全探索](https://atcoder.jp/contests/abc106/submissions/11035473) or [手計算](https://atcoder.jp/contests/abc106/submissions/10375434)|
||3|[AtCoder Beginner Contest 122 B - ATCoder](https://atcoder.jp/contests/abc122/tasks/abc122_b)|1|-|[全探索, skip](https://atcoder.jp/contests/abc122/submissions/11035941)|
||4|[パ研杯2019 C - カラオケ](https://atcoder.jp/contests/pakencamp-2019-day3/tasks/pakencamp_2019_day3_c)|2|全探索の免許皆伝|[全探索](https://atcoder.jp/contests/pakencamp-2019-day3/submissions/11036549)|
||5|[AtCoder Beginner Contest 095 C - Half and Half](https://atcoder.jp/contests/abc095/tasks/arc096_a)|2|-|[考察](https://atcoder.jp/contests/abc095/submissions/10376238)|
||6|[三井住友信託銀行プログラミングコンテスト 2019 D - Lucky PIN](https://atcoder.jp/contests/sumitrust2019/tasks/sumitb2019_d)|2|-|[全探索(要工夫), skip](https://atcoder.jp/contests/sumitrust2019/submissions/10583223)|
||7|[JOI 2007 本選 3 - 最古の遺跡](https://atcoder.jp/contests/joi2007ho/tasks/joi2007ho_c)|2|面白い|[全探索(要工夫),二次元](https://atcoder.jp/contests/joi2007ho/submissions/10660106)|
||8|[Square869120Contest #6 B - AtCoder Markets](https://atcoder.jp/contests/s8pc-6/tasks/s8pc_6_b)|4|工夫|[全探索(要工夫),中央値](https://atcoder.jp/contests/s8pc-6/submissions/10662359)|
||9|[JOI 2008 予選 4 - 星座探し](https://atcoder.jp/contests/joi2008yo/tasks/joi2008yo_d)|3|-|[全探索(要工夫),二次元](https://atcoder.jp/contests/joi2008yo/submissions/10665323)|
||10|[ALDS_5_A - 総当たり](https://onlinejudge.u-aizu.ac.jp/problems/ALDS1_5_A)|1|基本問題|[bit全探索](https://onlinejudge.u-aizu.ac.jp/solutions/problem/ALDS1_5_A/review/4244976/knknkn1162/C)|
||11|[AtCoder Beginner Contest 128 C - Switches](https://atcoder.jp/contests/abc128/tasks/abc128_c)|3|-|[bit全探索,ややこしい](https://atcoder.jp/contests/abc128/submissions/10586194)|
||12|[AtCoder Beginner Contest 002 D - 派閥](https://atcoder.jp/contests/abc002/tasks/abc002_4)|2|-|[bit全探索](https://atcoder.jp/contests/abc002/submissions/10667180)|
||13|[JOI 2008 予選 5 - おせんべい](https://atcoder.jp/contests/joi2008yo/tasks/joi2008yo_e)|2|茶色コーダーにはやや難|[縦に関してbit全探索](https://atcoder.jp/contests/joi2008yo/submissions/10734695)|
||14|[Square869120Contest #4 B - Buildings are Colorful!](https://atcoder.jp/contests/s8pc-4/tasks/s8pc_4_b)|4|難問|[建物数に関してbit全探索](https://atcoder.jp/contests/s8pc-4/submissions/10738108)|
||15|[AtCoder Beginner Contest 145 C - Average Length](https://atcoder.jp/contests/abc145/tasks/abc145_c)|2|-|[順列全探索](https://atcoder.jp/contests/abc145/submissions/10605659)|
||16|[AtCoder Beginner Contest 150 C - Count Order](https://atcoder.jp/contests/abc150/tasks/abc150_c)|2|-|[順列全探索](https://atcoder.jp/contests/abc150/submissions/10632625)|
||17|[ALDS_13_A - 8 クイーン問題](https://onlinejudge.u-aizu.ac.jp/problems/ALDS1_13_A)|3|面白い|[順列全探索](https://onlinejudge.u-aizu.ac.jp/solutions/problem/ALDS1_13_A/review/4254080/knknkn1162/C)|
||18|[ALDS_4_B - 二分探索](https://onlinejudge.u-aizu.ac.jp/problems/ALDS1_4_B)|1|基本問題, mapでも解ける|[二分探索](https://onlinejudge.u-aizu.ac.jp/solutions/problem/ALDS1_4_B/review/4261818/knknkn1162/C) or [hash(map)](https://onlinejudge.u-aizu.ac.jp/solutions/problem/ALDS1_4_B/review/4333032/knknkn1162/C) or [sort -> 線形探索](https://onlinejudge.u-aizu.ac.jp/solutions/problem/ALDS1_4_B/review/4333136/knknkn1162/C)|
||19|[JOI 2009 本選 2 - ピザ](https://atcoder.jp/contests/joi2009ho/tasks/joi2009ho_b)|2|-|[二分探索](https://atcoder.jp/contests/joi2009ho/submissions/10814537)|
||20|[AtCoder Beginner Contest 077 C - Snuke Festival](https://atcoder.jp/contests/abc077/tasks/arc084_a)|3|面白い|[二分探索(lower/upper bound)、中部を軸に](https://atcoder.jp/contests/abc077/submissions/10816319) or [二分探索,累積和](https://atcoder.jp/contests/abc077/submissions/10815991)|
||21|[AtCoder Beginner Contest 023 D - 射撃王](https://atcoder.jp/contests/abc023/tasks/abc023_d)|5|教育的に良い|[解決め打ちで二分検索(lower bound)](https://atcoder.jp/contests/abc023/submissions/11029093)|
||22|[AtCoder Regular Contest 054 B - ムーアの法則](https://atcoder.jp/contests/arc054/tasks/arc054_b)|3|微分して二分法|[二分法](https://atcoder.jp/contests/arc054/submissions/10824878) or [手計算](https://atcoder.jp/contests/arc054/submissions/10823956)|
||23|[JOI 2008 本選 3 - ダーツ](https://atcoder.jp/contests/joi2008ho/tasks/joi2008ho_c)|4|チャレンジ問題|[解決め打ちで二分検索(upper bound), 2つの和に帰着](https://atcoder.jp/contests/joi2008ho/submissions/10906780)|
||24|[ALDS_11_B - 深さ優先探索](https://onlinejudge.u-aizu.ac.jp/problems/ALDS1_11_B)|1|基本問題|[DFS](https://onlinejudge.u-aizu.ac.jp/solutions/problem/ALDS1_11_B/review/4265393/knknkn1162/C)|
||25|[AOJ 1160 - 島はいくつある？](https://onlinejudge.u-aizu.ac.jp/problems/1160)|2|深さ優先探索|[複数回DFS](https://onlinejudge.u-aizu.ac.jp/solutions/problem/1160/review/4265477/knknkn1162/C)|
||26|[AtCoder Beginner Contest 138 D - Ki](https://atcoder.jp/contests/abc138/tasks/abc138_d)|5|深さ優先探索|[DFS, 累積和](https://atcoder.jp/contests/abc138/submissions/10946685) or [BFS, 累積和](https://atcoder.jp/contests/abc138/submissions/10985972)|
||27|[JOI 2009 予選 4 - 薄氷渡り](https://atcoder.jp/contests/joi2009yo/tasks/joi2009yo_d)|4|再帰関数を使って|[盤面では再帰のDFS](https://atcoder.jp/contests/joi2009yo/submissions/10990508)|
||28|[ALDS_11_C - 幅優先探索](https://onlinejudge.u-aizu.ac.jp/problems/ALDS1_11_C)|1|基本問題|[BFS](https://onlinejudge.u-aizu.ac.jp/solutions/problem/ALDS1_11_C/review/4275470/knknkn1162/C)|
||29|[AtCoder Beginner Contest 007 C - 幅優先探索](https://atcoder.jp/contests/abc007/tasks/abc007_3)|2|幅優先探索で|[BFS](https://onlinejudge.u-aizu.ac.jp/solutions/problem/ALDS1_11_C/review/4275470/knknkn1162/C)|
||30|[JOI 2011 予選 5 - チーズ](https://atcoder.jp/contests/joi2011yo/tasks/joi2011yo_e)|3|-|[複数回BFS](https://atcoder.jp/contests/joi2011yo/submissions/11007341)|
||31|[JOI 2012 予選 5 - イルミネーション](https://atcoder.jp/contests/joi2012yo/tasks/joi2012yo_e)|4|実装が少し重い|[BFS, 配列の添字に注意](https://atcoder.jp/contests/joi2012yo/submissions/11017433)|
||32|[AOJ 1166 - 迷図と命ず](https://onlinejudge.u-aizu.ac.jp/problems/1166)|4|実装が少し重い|[BFS](https://onlinejudge.u-aizu.ac.jp/solutions/problem/1166/review/4279325/knknkn1162/C)|
||33|[AtCoder Beginner Contest 088 D - Grid Repainting](https://atcoder.jp/contests/abc088/tasks/abc088_d)|3|幅優先探索の免許皆伝|[BFS](https://atcoder.jp/contests/abc088/submissions/11023795)|
||34|[ALDS_10_A - フィボナッチ数](https://onlinejudge.u-aizu.ac.jp/problems/ALDS1_10_A)|1|超基本|[DP(漸化式)](https://onlinejudge.u-aizu.ac.jp/solutions/problem/ALDS1_10_A/review/4281332/knknkn1162/C)|
||35|[DPL_1_B - 0,1ナップザック問題](https://onlinejudge.u-aizu.ac.jp/problems/DPL_1_B)|2|基本問題|[DP](https://onlinejudge.u-aizu.ac.jp/solutions/problem/DPL_1_B/review/4281552/knknkn1162/C)|
||36|[DPL_1_C - ナップザック問題](https://onlinejudge.u-aizu.ac.jp/problems/DPL_1_C)|2|基本問題|[1次元DP](https://onlinejudge.u-aizu.ac.jp/solutions/problem/DPL_1_C/review/4281702/knknkn1162/C)|
||37|[DPL_1_A - コイン問題](https://onlinejudge.u-aizu.ac.jp/problems/DPL_1_A)|2|基本問題|[DP, 「必ず1を含む」を利用](https://onlinejudge.u-aizu.ac.jp/solutions/problem/DPL_1_A/review/4281782/knknkn1162/C)|
||38|[ALDS_10_C - 最長共通部分列](https://onlinejudge.u-aizu.ac.jp/problems/ALDS1_10_C)|3|基本問題|[DP](https://onlinejudge.u-aizu.ac.jp/solutions/problem/ALDS1_10_C/review/4281838/knknkn1162/C)|
||39|[JOI 2011 予選 4 - 1 年生](https://atcoder.jp/contests/joi2011yo/tasks/joi2011yo_d)|3|-|[DP](https://atcoder.jp/contests/joi2011yo/submissions/11044913)|
||40|[JOI 2012 予選 4 - パスタ](https://atcoder.jp/contests/joi2012yo/tasks/joi2012yo_d)|5|-|[DP, 三項間漸化式](https://atcoder.jp/contests/joi2012yo/submissions/11063373)|
||41|[JOI 2013 予選 4 - 暑い日々](https://atcoder.jp/contests/joi2013yo/tasks/joi2013yo_d)|4|-|[DP](https://atcoder.jp/contests/joi2013yo/submissions/11071917)|
||42|[JOI 2015 予選 4 - シルクロード](https://atcoder.jp/contests/joi2015yo/tasks/joi2015yo_d)|4|-|[DP, 添字に注意](https://atcoder.jp/contests/joi2015yo/submissions/11072738)|
||43|[パ研杯2019 D - パ研軍旗](https://atcoder.jp/contests/pakencamp-2019-day3/tasks/pakencamp_2019_day3_d)|4|-|[DP](https://atcoder.jp/contests/pakencamp-2019-day3/submissions/11073514)|
||44|[AOJ 1167 - ポロック予想](https://onlinejudge.u-aizu.ac.jp/problems/1167)|3|-|[DP](https://onlinejudge.u-aizu.ac.jp/solutions/problem/1167/review/4285611/knknkn1162/C)|
||45|[AOJ 2199 - 差分パルス符号変調](https://onlinejudge.u-aizu.ac.jp/problems/2199)|4|-|[DP](https://onlinejudge.u-aizu.ac.jp/solutions/problem/2199/review/4290020/knknkn1162/C)|
||46|[ALDS_10_B - 連鎖行列積](https://onlinejudge.u-aizu.ac.jp/problems/ALDS1_10_B)|3|基本問題|[区間DP](https://onlinejudge.u-aizu.ac.jp/solutions/problem/ALDS1_10_B/review/4290616/knknkn1162/C)|
||47|[JOI 2015 本選 2 - ケーキの切り分け 2](https://atcoder.jp/contests/joi2015ho/tasks/joi2015ho_b)|4|O(N^2)の区間DP|[区間DP](https://atcoder.jp/contests/joi2015ho/submissions/11199863)|
||48|[AOJ 1611 ダルマ落とし](https://onlinejudge.u-aizu.ac.jp/problems/1611)|5|O(N^3)の区間DP|[下からi個までのダルマについて都度区間DP](https://onlinejudge.u-aizu.ac.jp/solutions/problem/1611/review/4296429/knknkn1162/C)|
||49|[DPL_2_A - 巡回セールスマン問題](https://onlinejudge.u-aizu.ac.jp/problems/DPL_2_A)|3|基本問題|[bit DP](https://onlinejudge.u-aizu.ac.jp/solutions/problem/DPL_2_A/review/4300234/knknkn1162/C)|
||50|[Square869120Contest #1 G - Revenge of Traveling Salesman Problem](https://atcoder.jp/contests/s8pc-1/tasks/s8pc_1_g)|4|巡回セールスマン問題の類題|[bit DP](https://atcoder.jp/contests/s8pc-1/submissions/11258019)|
||51|[JOI 2014 予選 4 - 部活のスケジュール表](https://atcoder.jp/contests/joi2014yo/tasks/joi2014yo_d)|3|一応bitDPとして|[bitDP](https://atcoder.jp/contests/joi2014yo/submissions/11260609)|
||52|[JOI 2017 予選 4 - ぬいぐるみの整理](https://atcoder.jp/contests/joi2017yo/tasks/joi2017yo_d)|5|少し難しい|[bitDP, 累積和](https://atcoder.jp/contests/joi2017yo/submissions/11263795)|
||53|[DPL_1_D - 最長増加部分列](https://onlinejudge.u-aizu.ac.jp/problems/DPL_1_D)|3|-|[stack, 線形探索](https://onlinejudge.u-aizu.ac.jp/solutions/problem/DPL_1_D/review/4332973/knknkn1162/C) or [stack, 二分探索](https://onlinejudge.u-aizu.ac.jp/solutions/problem/DPL_1_D/review/4302517/knknkn1162/C)|
||54|[AtCoder Beginner Contest 006 D - トランプ挿入ソート](https://atcoder.jp/contests/abc006/tasks/abc006_4)|3|-|[53とほぼ同様にstack](https://atcoder.jp/contests/abc006/submissions/11331581)|
||55|[AtCoder Beginner Contest 134 E - Sequence Decomposing](https://atcoder.jp/contests/abc134/tasks/abc134_e)|5|チャレンジ問題|[groupの要素数をメンバにしたstack](https://atcoder.jp/contests/abc134/submissions/11333378)|
||56|[GRL_1_A - 単一始点最短経路](https://onlinejudge.u-aizu.ac.jp/problems/GRL_1_A)|3|-|[ダイクストラ+min heap](https://onlinejudge.u-aizu.ac.jp/solutions/problem/GRL_1_A/review/4324769/knknkn1162/C), [ベルマンフォード法](https://onlinejudge.u-aizu.ac.jp/solutions/problem/GRL_1_A/review/4324769/knknkn1162/C)|
||57|[JOI 2008 予選 6 - 船旅](https://atcoder.jp/contests/joi2008yo/tasks/joi2008yo_f)|3|ワーシャルフロイド法でも(ダイクストラでも)|[ダイクストラ + min heap](https://atcoder.jp/contests/joi2008yo/submissions/11579403) or [ワーシャルフロイド法](https://atcoder.jp/contests/joi2008yo/submissions/11604956) or [ベルマンフォード法](https://atcoder.jp/contests/joi2008yo/submissions/11591911)|
||58|[JOI 2016 予選 5 - ゾンビ島](https://atcoder.jp/contests/joi2016yo/tasks/joi2016yo_e)|4|幅優先探索も使う。実装重め|[BFS, ダイクストラ, min heap](https://atcoder.jp/contests/joi2016yo/submissions/11613275)|
||59|[JOI 2014 予選 5 - タクシー](https://atcoder.jp/contests/joi2014yo/tasks/joi2014yo_e)|5|-|[BFS, ダイクストラ, min heap](https://atcoder.jp/contests/joi2014yo/submissions/11632287)|
||60|[GRL_1_C - 全点対間最短経路](https://onlinejudge.u-aizu.ac.jp/problems/GRL_1_C)|3|基本問題|[ワーシャルフロイド法,重みの上限がシビア](https://onlinejudge.u-aizu.ac.jp/solutions/problem/GRL_1_C/review/4331113/knknkn1162/C)|
||61|[AtCoder Beginner Contest 012 D - バスと避けられない運命](https://atcoder.jp/contests/abc012/tasks/abc012_4)|2|-|[ワーシャルフロイド法](https://atcoder.jp/contests/abc012/submissions/11640675)|
||62|[AtCoder Beginner Contest 079 D - Wall](https://atcoder.jp/contests/abc079/tasks/abc079_d)|3|-|[2次元をgraphに見立ててワーシャルフロイド法, map](https://atcoder.jp/contests/abc079/submissions/11641009)|
||63|[AtCoder Beginner Contest 074 D - Restoring Road Network](https://atcoder.jp/contests/abc074/tasks/arc083_b)|5|数学的考察が必要で難しいがおすすめ|[ワーシャルフロイド2回](https://atcoder.jp/contests/abc074/submissions/11645387)|
||64|[GRL_2_A - 最小全域木](https://onlinejudge.u-aizu.ac.jp/problems/GRL_2_A)||基本問題|[クラスカル法](https://onlinejudge.u-aizu.ac.jp/solutions/problem/GRL_2_A/review/4333233/knknkn1162/C)|
||65|[JOI 2010 春合宿 - Finals(Day 3)](https://atcoder.jp/contests/joisc2010/tasks/joisc2010_finals), [問題](https://www.ioi-jp.org/camp/2010/2010-sp-tasks/2010-sp-day3_22.pdf)|4|JOI 春合宿の問題だが、比較的簡単|[クラスカル法 + 一般のKの時の考察](https://atcoder.jp/contests/joisc2010/submissions/11659915)|
||66|[AOJ 1127 - Building a Space Station](https://onlinejudge.u-aizu.ac.jp/problems/1127)|3|-|[クラスカル法](https://onlinejudge.u-aizu.ac.jp/solutions/problem/1127/review/4333742/knknkn1162/C)|
||67|[AtCoder Beginner Contest 065 D - Built?](https://atcoder.jp/contests/abc065/tasks/arc076_b)|4|やや難しい。素朴な最小全域木ではO(N^2)で解けないが..|[ソート -> クラスカル法](https://atcoder.jp/contests/abc065/submissions/11662019)|
||68|[NTL_1_A - 素因数分解](https://onlinejudge.u-aizu.ac.jp/problems/NTL_1_A)|1~2|基本問題|[単純なloopによる解法](https://onlinejudge.u-aizu.ac.jp/solutions/problem/NTL_1_A/review/4334191/knknkn1162/C) or [エラトステネスのふるい](https://onlinejudge.u-aizu.ac.jp/solutions/problem/NTL_1_A/review/4334411/knknkn1162/C)|
||69|[AtCoder Beginner Contest 084 D - 2017-like Number](https://atcoder.jp/contests/abc084/tasks/abc084_d)|3|-|[エラトステネスのふるい + 累積和](https://atcoder.jp/contests/abc084/submissions/11665020)|
||70|[NTL_1_B - べき乗](https://onlinejudge.u-aizu.ac.jp/problems/NTL_1_B)||-|[bit演算](https://onlinejudge.u-aizu.ac.jp/solutions/problem/NTL_1_B/review/4334457/knknkn1162/C)|
||71|[Square869120Contest #1 E - 散歩](https://atcoder.jp/contests/s8pc-1/tasks/s8pc_1_e)|4|-|[bit演算, いもす法](https://atcoder.jp/contests/s8pc-1/submissions/11667270)|
||72|[AtCoder Beginner Contest 034 C - 経路](https://atcoder.jp/contests/abc034/tasks/abc034_c)|3|基本問題|[二項係数の計算、逆元](https://atcoder.jp/contests/abc034/submissions/11684318)|
||73|[Atcoder Beginner Contest 145 D - Knight](https://atcoder.jp/contests/abc145/tasks/abc145_d)|3|-|[考察、二項係数の計算、逆元](https://atcoder.jp/contests/abc145/submissions/11685019)|
||74|[AtCoder Beginner Contest 021 D - 多重ループ](https://atcoder.jp/contests/abc021/tasks/abc021_d)|3|-|[考察、重複組合せ, 逆元](https://atcoder.jp/contests/abc021/submissions/11687036)|
|o|75|[AtCoder Beginner Contest 149 F - Surrounded Nodes](https://atcoder.jp/contests/abc149/tasks/abc149_f)|5|チャレンジ問題|[]()|
||76|[全国統一プログラミング王決定戦本戦 A - Abundant Resources](https://atcoder.jp/contests/nikkei2019-final/tasks/nikkei2019_final_a)|1|基本|[累積和](https://atcoder.jp/contests/nikkei2019-final/submissions/11334284)|
||77|[JOI 2010 本選 1 - 旅人](https://atcoder.jp/contests/joi2010ho/tasks/joi2010ho_a)|2|-|[累積和, 添字に注意](https://atcoder.jp/contests/joi2010ho/submissions/11338148)|
||78|[JOI 2011 本選 1 - 惑星探査](https://atcoder.jp/contests/joi2011ho/tasks/joi2011ho1)|3|二次元累積和|[二次元累積和](https://atcoder.jp/contests/joi2011ho/submissions/11340451)|
||79|[AtCoder Beginner Contest 106 D - AtCoder Express 2](https://atcoder.jp/contests/abc106/tasks/abc106_d)|3|-|[二次元累積和](https://atcoder.jp/contests/abc106/submissions/11348226) or [区間DP](https://atcoder.jp/contests/abc106/submissions/11346781)|
||80|[GigaCode 2019 D - 家の建設](https://atcoder.jp/contests/gigacode-2019/tasks/gigacode_2019_d)|3|-|[二次元累積和](https://atcoder.jp/contests/gigacode-2019/submissions/11350327)|
||81|[AtCoder Beginner Contest 014 C - AtColor](https://atcoder.jp/contests/abc014/tasks/abc014_3)|3|基本問題|[いもす法](https://atcoder.jp/contests/abc014/submissions/11362928)|
||82|[AOJ 2013 - 大崎](https://onlinejudge.u-aizu.ac.jp/problems/2013)|3|-|[いもす法](https://onlinejudge.u-aizu.ac.jp/solutions/problem/2013/review/4306854/knknkn1162/C)|
||83|[JOI 2015 本選 1 - 鉄道運賃](https://atcoder.jp/contests/joi2015ho/tasks/joi2015ho_a)|3|-|[いもす法、添字に注意](https://atcoder.jp/contests/joi2015ho/submissions/11370150)|
||84|[JOI 2012 本選 4 - 釘](https://atcoder.jp/contests/joi2012ho/tasks/joi2012ho4)|5|チャレンジ問題|[いもす法, 3階差分](https://atcoder.jp/contests/joi2012ho/submissions/11421264)|
||85|[DSL_1_A - 互いに素な集合](https://onlinejudge.u-aizu.ac.jp/problems/DSL_1_A)|2|基本問題|[Union Find](https://onlinejudge.u-aizu.ac.jp/solutions/problem/DSL_1_A/review/4315753/knknkn1162/C)|
||86|[AtCoder Beginner Contest 075 C - Bridge](https://atcoder.jp/contests/abc075/tasks/abc075_c)|3|深さ優先探索でもUnion Findでも解ける|[複数回Union Find](https://atcoder.jp/contests/abc075/submissions/11444607)|
||87|[AtCoder Beginner Contest 120 D - Decayed Bridge](https://atcoder.jp/contests/abc120/tasks/abc120_d)|4|少し難しい|[Union-Find, 累積和](https://atcoder.jp/contests/abc120/submissions/11458940)|
||88|[JOI 2008 本選 1 - 碁石ならべ](https://atcoder.jp/contests/joi2008ho/tasks/joi2008ho_a)|3|-|[stack](https://atcoder.jp/contests/joi2008ho/submissions/11465819)|
||89|[JOI 2013 本選 1 - 電飾](https://atcoder.jp/contests/joi2013ho/tasks/joi2013ho1)|3|-|[stack](https://atcoder.jp/contests/joi2013ho/submissions/11466663)|
||90|[Square869120Contest #5 B - Emblem](https://atcoder.jp/contests/s8pc-5/tasks/s8pc_5_b)|2|-|[sqrtを使用](https://atcoder.jp/contests/s8pc-5/submissions/11467649)|
||91|[AtCoder Beginner Contest 144 D - Water Bottle](https://atcoder.jp/contests/abc144/tasks/abc144_d)|2|-|[atanを使用](https://atcoder.jp/contests/abc144/submissions/11475040)|
||92|[AOJ 1193 - 連鎖消滅パズル](https://onlinejudge.u-aizu.ac.jp/problems/1193)|3|-|[落ちゲー、解くだけ](https://onlinejudge.u-aizu.ac.jp/solutions/problem/1193/review/4320693/knknkn1162/C)|
||93|[Square869120Contest #3 B - 石落としゲーム](https://atcoder.jp/contests/s8pc-3/tasks/s8pc_3_b)|3|-|[(WIDTH)×(HEIGHT-1)個シュミレート](https://atcoder.jp/contests/s8pc-3/submissions/11477560)|
||94|[AOJ 1149 - ケーキカット](https://onlinejudge.u-aizu.ac.jp/problems/1149)|4|-|[連結リスト](https://onlinejudge.u-aizu.ac.jp/solutions/problem/1149/review/4321489/knknkn1162/C)|
||95|[AtCoder Beginner Contest 149 B - Greedy Takahashi](https://atcoder.jp/contests/abc149/tasks/abc149_b)|1|200-300 点問題の数学的問題の典型|[簡単な考察](https://atcoder.jp/contests/abc149/submissions/11486960)|
||96|[AtCoder Beginner Contest 139 D - ModSum](https://atcoder.jp/contests/abc139/tasks/abc139_d)|2|考察一個|[法則性をみつけるだけ](https://atcoder.jp/contests/abc139/submissions/11487225)|
||97|[AtCoder Beginner Contest 150 D - Semi Common Multiple](https://atcoder.jp/contests/abc150/submissions/11522990)|3|-|[最小公倍数](https://atcoder.jp/contests/abc150/submissions/11522990)|
||98|[三井住友信託銀行プログラミングコンテスト2019 予選 E - Colorful Hats 2](https://atcoder.jp/contests/sumitrust2019/tasks/sumitb2019_e)|3|-|[数学的な考察, 配列](https://atcoder.jp/contests/sumitrust2019/submissions/11699547)|
||99|[DDCC2020 予選 D - Digit Sum Replace](https://atcoder.jp/contests/ddcc2020-qual/tasks/ddcc2020_qual_d)|4|考察一個|[考察(数字の遷移方法は2パターンのうちどれか)](https://atcoder.jp/contests/ddcc2020-qual/submissions/11700593)|
||100|[Tenka1 Programmer Beginner Contest D - Crossing](https://atcoder.jp/contests/tenka1-2018-beginner/tasks/tenka1_2018_d)|4|やや難|[部分集合の要素数を決めて構成, n=1も考慮](https://atcoder.jp/contests/tenka1-2018-beginner/submissions/11702203)|

# 解説

(not yet)

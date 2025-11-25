
このページは、以下のポスター発表の補遺です。

**Title:** 勝ちきれなかった選挙前野党連合は何をもたらすか ―権威主義体制下の市民の政治態度に対する影響― 

**Author:** 門屋寿

**Date:** 2025-11-26

## 分析対象となった国波一覧
<iframe src="woi_countryround.html" width="100%" height="600px"></iframe>

## 野党連合の操作化
- 統一連合(coalition_full)
  - 以下のいずれかを満たす連合があり(Samet 2024, p.3)、その連合にすべての主要野党が参加していれば1
  1. 正式な連合として一緒に選挙運動を実施
  2. 選挙のために単一の政党を結成
  3. 大統領選第1ラウンドの前に単一の候補の支持を表明
  4. 候補者が対立しないよう調整

- 部分連合(coalition_partial)
  - 先ほどのSametのルールに当てはまる連合があるが、その他に連合不参加の野党(得票率5%以上)が存在するときに1


## 結果変数の質問項目
- 野党信頼(trust_opp)
  - Question: How much do you trust each of the following, or haven’t you heard enough about them to say: Opposition Political Parties?
- 選挙(electleader)
  - Question: Which of the following statements is closest to your view? Choose Statement 1 or Statement 2.
    - Statement 1: We should choose our leaders in this country through regular, open and honest elections.
    - Statement 2: Since elections sometimes produce bad results, we should adopt other methods for choosing this country’s leaders.
- 民主主義満足(swd)
  - Question: Overall, how satisfied are you with the way democracy works in [ENTER COUNTRY]? Are you: 


## 統制変数
- 個人レベル
  - 与党支持ダミー[ruling]、野党支持ダミー[opposition]、与党信頼度[trust_rul]、年齢[age]、女性ダミー[female]、教育水準[education]、田舎居住ダミー[rural]、ラジオ利用頻度[radio]
- 国レベル
  - 選挙前年の選挙公正性指標[v2x_frefair_l]、大統領選挙ダミー[pres]、選挙前年の一人当たりGDP(対数)[lgdppc_sl]、選挙前年の人口(対数)[lpopulation_sl]、選挙前年のGDP成長率[growth_sl]、ラウンド(波)[round]


## モデルに投入した変数の記述統計
<iframe src="stats.html" width="100%" height="600px"></iframe>

## 頑健性の確認

## References
Samet, Oren. 2024. “Supplementary Appendix for ‘When You Come at the King: Opposition Coalitions and Nearly Stunning Elections.’” https://onlinelibrary.wiley.com/action/downloadSupplement?doi=10.1111%2Fajps.12920&file=ajps12920-sup-0001-Appendix.pdf.





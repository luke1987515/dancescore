# dancescore
Use EtherCalc make a Free and open-source online judging software.(The Skating System)

# 開發目的
參與國標舞的比賽，計分人員需要手動收單，手動計分，手動公布成績，造成計分緩慢、計分錯誤、公佈欄壅擠的狀況。

為了解決上述問題，上網搜尋類似的工具。
1. DanceScore [網址](https://dancescorelive.com/dancescore.php "DanceScore Project")
2. Scrutelle  [網址](http://www.scrutelle.info/ "Scrutelle V9")
3. Aspire     [網址](https://aspiresystem-tld.com/ "Aspire System")

已知這些軟體，都不是開放原始碼，無法依使用環境的需要調整。  
既然沒有可以輪子可以用，就自己造一個輪子。 ^____^

最終目標：讓之後參與國標舞比賽的計分人員，可以減輕他們的壓力，節省計分團隊的軟體授權開支。

# 概念發想
對我來說計分人員的手動計分，就像在 Excel 表格上的進行計算。  
我找到 EtherCalc 一個線上的試算表工具，希望透過這個自由且開源的表格，  
在上面開發計分系統。

*計分規則(The Skating System)(Rule1-11)[PDF](https://www.worlddancesport.org/Document/99473179446/The_Skating_System.pdf "The_Skating_System")

# 開發方向
- 階段一：
  - 最小可行系統：
    - 輸入：裁判(5)、選手(12)、圈選半數選手/每一個裁判 (CSV 格式檔案)，
    - 計算：Rule 1；
    - 輸出：裁判圈選紀錄、入圍選手。(CSV 格式檔案)；

# ~使用者介面的開發~
~腳色：主辦(賽程)、裁判、選手~
 


政大資科職碩 110971018 李昂縣

作業說明:

以下列演算法解決 8-puzzle

Iterative-Deepening Search
Uniform-Cost Search
Greedy Best-First Search
A* search
Recursive Best-First Search

共含四個檔案，說明如下:
8puzzle.py : 主要作業內容，包含PUZZLE邏輯及五種演算法
16puzzle.py : 加分題，包含PUZZLE邏輯及五種演算法
README.txt : 作業說明
trigger.ipynb : 操作範例


下列為演算法簡寫 

ids => Iterative-Deepening Search
usc => Uniform-Cost Search
gbf => Greedy Best-First Search
ast => A* search
rbf => Recursive Best-First Search

下列為範例 (輸入格式 : 演算法 數字序列)
%run 8puzzle.py ids 0,8,7,6,5,4,3,1,2
%run 16puzzle.py ast 7,14,11,5,6,2,8,10,3,0,12,15,9,4,13,1
# RAKE_improve
Improvement of RAKE Algorithm （Rapid Automatic keyword extraction）

在原有RAKE算法上进行了改进，将核心公式
- **wordScore = wordDegree(w) / wordFrequency(w)**

修改成为 wordmeanScore， 即取了phrase的平均值。

另外其他具体改进见rake_improve.py。

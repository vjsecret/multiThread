# 
pra_multiThread4.py:多工進行兩筆資料的運算，每筆資料皆多工進行cond2的運算，將運算完的結果存下來，希望存成2job.txt與3job.txt。 =>result:只有3job.txt一個擋案 =>solve:改用thread可以return值試看看，如果不行，那就每次只能對同一個任務進行多工運算，無法多工任務進行多工運算

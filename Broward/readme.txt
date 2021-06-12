For all the datasets, the last column is label column. All the datasets are binary-classified, which means labels are 0 or 1.

For Adult dataset:

gender index: 9, majority gender: Female(0)
race index: 8, majority race: White(0)
categorical features:[1, 3, 5, 6, 7, 8, 9, 13]

http://archive.ics.uci.edu/ml/datasets/



For Broward dataset:

gender index: 1, majority gender: Female(1)
race index: 0, majority race: Black(1)
categorical features:[1, 3, 5, 6, 7, 8, 9, 13]

https://farid.berkeley.edu/downloads/publications/scienceadvances17/



For Hospital dataset:

gender index: 1, majority gender: female(1)
race index: 2, majority race: Black(1)
categorical features:[1, 2, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15]		

https://www.dshs.texas.gov/thcic/hospitals/UserManual1Q2014.pdf

Hospital 的列的说明如下：
0：Age,
1: Gender,
2: Race,
3: "LENGTH_OF_STAY",
4: "ADMITTING_DIAGNOSIS"（诊断代码，已经map成了数字）
5-16: 口头诊断代码，已经map成了数字
17：临床诊断代码，也是map成了数字，0是心脏类疾病，1是呼吸类疾病
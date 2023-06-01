Втора Лабораториска вежба по Софтверско инженерство

Марија Тасеска 213087

2.Control Flow Graph:

![CONTROL FLOW GRAPH](https://github.com/marijataseska/SI_2023_lab2_213087/assets/108740625/2dd7abb8-2f46-4819-b162-64a0d738a696)


3.Цикломатската комплексност на овој код е 11.
Бидејќи има 10 предикатни јазли и според формулата P+1, каде P е бројот на предикатни јазли=10, добиваме 11.

4.Тест случаи според Every Branch методата:
имаме 3 тест случаи според оваа метода и тоа:

Every branch 	Username==null Password==null Email==null	Username==student Password==student123 Email==student@gmail.com	Username==student Password==student123 Email==null	Username==student Password==null Email==null	
1-2	1	1	1	1	TRUE
1-3	1	1	1	1	TRUE
2-25	0	0	0	1	TRUE
3-4	1	1	1	1	TRUE
3-5	0	1	0	0	TRUE
4-5	1	1	1	1	TRUE
5-6	1	0	0	0	TRUE
6-7	0	0	0	1	TRUE
7-8.1	0	1	0	0	TRUE
8.1-8.2	0	0	0	1	TRUE
8.2-9	0	0	0	1	TRUE
8.2-14,15,16	0	1	1	1	TRUE
8.3-8.2	0	1	1	1	TRUE
9-10	1	0	1	0	TRUE
10-11	0	0	0	1	TRUE
10-12	1	1	0	0	TRUE
11-12	0	1	0	1	TRUE
12-13	0	0	1	0	TRUE
12-8.3	0	0	1	0	TRUE
14,15,16-17	1	1	1	1	TRUE
17-18	1	1	1	1	TRUE
17-19	1	0	0	0	TRUE
19-20	0	1	0	0	TRUE
20-21.1	1	0	1	1	TRUE
21.1-21.2	1	1	0	0	TRUE
21.2-22	1	1	1	1	TRUE
21.2-24	0	0	1	0	TRUE
22-23	0	0	0	1	TRUE
22-21.3	0	0	1	0	TRUE
21.3-21.2	0	0	1	0	TRUE
23-25	0	1	0	1	TRUE
24-25	0	1	1	1	TRUE
![image](https://github.com/marijataseska/SI_2023_lab2_213087/assets/108740625/8b895165-120f-415b-852f-de354903b3b7)





5.Multiple Condition критериумот за условот if (user==null || user.getPassword()==null || user.getEmail()==null) има 4 тест случаи, според табелата за точно и неточно:

Т V Т V T= Т
Т V ]T V ]T = T
]T V T V T = T
]T V ]T V T= T


 | FirstName     | LastName      | City   
| ------------- | ------------- | --------    
| `John`        | Test1         | `NewYork`   
| `Bob`         | Test2         | `Toronto`   
 
 
 | 1 | insert | [0, 1, 2, 3, 4, 5, 6, 0] | 26 |
 
| ------------- | ------------- | --------  | ------------- | ------------- | --------  
 | 1 | insert | [0, 1, 2, 3, 4, 5, 6, 0] | 26 |
 | 2 | 2opt   | [0, 1, 3, 4, 5, 2, 6, 0] | 23 |
 3 2opt   [0, 1, 3, 4, 5, 2, 6, 0] 23 <br/>
 4 2opt   [0, 1, 3, 4, 5, 2, 6, 0] 23 <br/>
 5 insert [0, 1, 3, 4, 5, 2, 6, 0] 23 <br/>
 6 2opt   [0, 1, 3, 4, 5, 2, 6, 0] 23 <br/>
 7 2opt   [0, 1, 3, 4, 5, 2, 6, 0] 23 <br/>
 8 swap   [0, 1, 3, 4, 5, 2, 6, 0] 23 <br/>
 9 insert [0, 6, 3, 4, 5, 2, 1, 0] 23 <br/>
10 2opt   [0, 6, 3, 4, 5, 2, 1, 0] 23 <br/>
11 insert [0, 6, 3, 4, 5, 2, 1, 0] 23 <br/>
12 swap   [0, 6, 3, 4, 5, 2, 1, 0] 23 <br/>
13 swap   [0, 6, 3, 4, 5, 2, 1, 0] 23 <br/>
14 2opt   [0, 6, 3, 4, 5, 2, 1, 0] 23 <br/>
15 insert [0, 6, 3, 4, 5, 2, 1, 0] 23
16 2opt   [0, 6, 3, 4, 5, 2, 1, 0] 23
17 2opt   [0, 6, 3, 4, 5, 2, 1, 0] 23
18 insert [0, 6, 3, 4, 5, 2, 1, 0] 23
19 insert [0, 3, 4, 5, 2, 6, 1, 0] 16
20 insert [0, 3, 4, 5, 2, 6, 1, 0] 16
21 2opt   [0, 3, 4, 5, 2, 6, 1, 0] 16
22 insert [0, 3, 4, 5, 2, 6, 1, 0] 16
23 swap   [0, 3, 4, 5, 2, 6, 1, 0] 16
24 2opt   [0, 3, 4, 5, 2, 6, 1, 0] 16
25 2opt   [0, 3, 4, 5, 2, 6, 1, 0] 16
26 insert [0, 3, 4, 5, 2, 6, 1, 0] 16
27 swap   [0, 3, 4, 5, 2, 6, 1, 0] 16
28 insert [0, 3, 4, 5, 2, 6, 1, 0] 16
29 swap   [0, 3, 4, 5, 2, 6, 1, 0] 16
30 swap   [0, 3, 4, 5, 2, 6, 1, 0] 16
31 insert [0, 3, 4, 5, 2, 6, 1, 0] 16
32 swap   [0, 3, 4, 5, 2, 6, 1, 0] 16
33 swap   [0, 3, 4, 5, 2, 6, 1, 0] 16
34 insert [0, 3, 4, 5, 2, 6, 1, 0] 16
35 2opt   [0, 3, 4, 5, 2, 6, 1, 0] 16
36 2opt   [0, 3, 4, 5, 2, 6, 1, 0] 16
37 2opt   [0, 3, 4, 5, 2, 6, 1, 0] 16
38 swap   [0, 3, 4, 5, 2, 6, 1, 0] 16
39 2opt   [0, 3, 4, 5, 2, 6, 1, 0] 16
40 2opt   [0, 3, 4, 5, 2, 6, 1, 0] 16
41 swap   [0, 3, 4, 5, 2, 6, 1, 0] 16
42 2opt   [0, 3, 4, 5, 2, 6, 1, 0] 16
43 insert [0, 3, 4, 5, 2, 6, 1, 0] 16
44 2opt   [0, 3, 4, 5, 2, 6, 1, 0] 16
45 swap   [0, 3, 4, 5, 2, 6, 1, 0] 16
46 insert [0, 4, 3, 5, 2, 6, 1, 0] 15
47 insert [0, 4, 3, 5, 2, 6, 1, 0] 15
48 insert [0, 4, 3, 5, 2, 6, 1, 0] 15
49 insert [0, 4, 3, 5, 2, 6, 1, 0] 15
50 2opt   [0, 4, 3, 5, 2, 6, 1, 0] 15
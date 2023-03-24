# HOMEWORK CHALLENGE

![image](https://github.com/AbdelrahmanShahrour/Unihance-DS/blob/main/Stats/HW/image/1.png) 

![image](https://github.com/AbdelrahmanShahrour/Unihance-DS/blob/main/Stats/HW/image/2.png) 

![image](https://github.com/AbdelrahmanShahrour/Unihance-DS/blob/main/Stats/HW/image/3.png) 

![image](https://github.com/AbdelrahmanShahrour/Unihance-DS/blob/main/Stats/HW/image/4.png) 

![image](https://github.com/AbdelrahmanShahrour/Unihance-DS/blob/main/Stats/HW/image/5.png) 

## Solution steps

1. data

![image](https://github.com/AbdelrahmanShahrour/Unihance-DS/blob/main/Stats/HW/image/1.1.png) 

2. generate random data using this equation
### for men: `=ROUND(NORM.INV(RAND(), 175.5, 7.4),0)`
### for women: `=ROUND(NORM.INV(RAND(), 161.8, 6.9),0)`

![image](https://github.com/AbdelrahmanShahrour/Unihance-DS/blob/main/Stats/HW/image/1.2.png) 

3. Calculating the lowest value, the highest value, and the highest 2.2%

Top 2.2%: `=LARGE(E2:E1001,ROUNDUP(0.022*COUNT(E2:E1001),0))`

![image](https://github.com/AbdelrahmanShahrour/Unihance-DS/blob/main/Stats/HW/image/1.3.png) 

4. `Freq` and `Bins`

#### freq: `=COUNTIFS(F2:F1001, G2)`
#### Bins: `MEN(F2:F1001)-5`, and them `Value+1`
![image](https://github.com/AbdelrahmanShahrour/Unihance-DS/blob/main/Stats/HW/image/1.4.png) 

5. Finally, create the graph

![image](https://github.com/AbdelrahmanShahrour/Unihance-DS/blob/main/Stats/HW/image/1.5.png) 

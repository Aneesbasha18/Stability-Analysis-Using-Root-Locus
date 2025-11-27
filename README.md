# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software
## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.
## Theory:
![IMG-20251127-WA0051](https://github.com/user-attachments/assets/52fe8354-d9bb-42cf-a8e8-b18a982ca929)
![IMG-20251127-WA0048](https://github.com/user-attachments/assets/3da2f169-ed88-4be1-8c2c-891d59878a95)
![IMG-20251127-WA0050](https://github.com/user-attachments/assets/6842d77e-55fd-4355-ba7f-ab06cc2d7044)
![IMG-20251127-WA0051](https://github.com/user-attachments/assets/a0cf3075-e211-4c93-91c5-4522ae05914c)
## Program: 
num=[1] <br>
den=[1 15 50 0] <br>
sys=tf(num,den) <br>
rlocus(sys)<br>
[k poles]=rlocfind(sys)<br>

## Output:
<img width="699" height="626" alt="image" src="https://github.com/user-attachments/assets/d83123ef-0d26-4999-8b1e-9b107ca02711" />


## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 744.551

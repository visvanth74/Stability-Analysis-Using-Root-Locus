# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
Open MATLAB software
Open a new script file.
Type the program.
Save and Execute the program.
Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
From the value of K, analyse the stability.

## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
num = [1]; <br>
den = [1 15 50 0]; <br>
sys = tf(num, den); <br>
rlocus(sys); <br>
[k, poles] = rlocfind(sys); <br>


## Output:
<img width="849" height="777" alt="image" src="https://github.com/user-attachments/assets/6adca219-04f1-4014-ad32-85e5973c05b1" />

## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 744.551 .

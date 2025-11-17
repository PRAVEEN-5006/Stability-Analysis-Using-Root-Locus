# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![WhatsApp Image 2025-11-17 at 20 49 08_58030a70](https://github.com/user-attachments/assets/87b8ef70-4619-4f42-a4a9-15b7b73a34c2)
![WhatsApp Image 2025-11-17 at 20 49 08_e87a5cae](https://github.com/user-attachments/assets/bdd90cc2-9176-4792-b84e-f4ddd72a0f22)
![WhatsApp Image 2025-11-17 at 20 49 09_eda0ecb8](https://github.com/user-attachments/assets/fd617deb-aa51-4b1a-bc8f-47d828f735c9)




## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 

```
num=[1];
den=[1 15 50 0];
sys=tf(num,den);
rlocus(sys);
[k,poles]=rlocfind(sys)
```

## Output:

<img width="689" height="621" alt="image" src="https://github.com/user-attachments/assets/972c3aae-aef5-4eb6-854e-85d2d7472016" />
<img width="1064" height="328" alt="image" src="https://github.com/user-attachments/assets/412359d8-0c2b-4a7c-b74c-34dac16ae9a7" />



## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 744.5551

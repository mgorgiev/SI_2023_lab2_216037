# SI_2023_lab2_216037!

Михаил Ѓорѓиев 216037

2.
![CFG (1)](https://github.com/mgorgiev/SI_2023_lab2_216037/assets/120776054/5f9099e1-5825-44b6-911d-81aad83516af)

3.
Cyclomatic complexity = 28-19+2 = 11
Cyclomatic complexity = P+1 = 10 + 1 = 11
Cyclomatic complexity = R (Regions) = 11

4.
C0 + ACEMOPQSPV 
ABV (user==null || user.getPassword()==null || user.getEmail()==null) ( , , )
ACDEFGHIJKFMOPQR ( ,passvord!,johndoe@gmail.com,(kade sto postoi veke ist email i user so ist username))
ACEFGIKFMNV (johndoe,pasvord,johndoe@gmail.com, (nema drugi so ist email i username,pasvordot pomal od 8 ili user e ist so pass)
ACEMOPQSPV(johndoe,pasword,johndoegmail,(emailot nema @ ili .)

5.
if (user==null || user.getPassword()==null || user.getEmail()==null) 
TXX | ( ,X,X) | A-B
FTX | (johndoe, ,X) | A-B
FFT | (johndoe,password, ) | A-B
FFF | (johndoe,password,johndoe@gmail.com ) | A-C

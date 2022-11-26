import string 
flag =[104, 290, 356, 313, 262, 337, 354, 229, 146, 297, 118, 373, 221, 359, 338, 321, 288, 79, 214, 277, 131, 190, 377, ]

Libr = "ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789_"

picoCTF=""
for i in flag:
    modulus=pow(i,-1,41)
    picoCTF+=Libr[modulus -1]


print("picoCTF{%s}" % "".join(picoCTF))

# proycompGr5
print('Estudiante 2: Anthony Tacuri')
print('CI: 1721731998')
ced2='1721731998'
cont=0
res=0
while cont<5:
    res=res+int(ced2[cont])+int(ced2[9-cont])
    cont=cont+1

print('La suma de los digitos es:',res)
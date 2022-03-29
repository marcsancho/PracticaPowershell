# Practica Powershell
## Script 1
El siguiente script es el primero.
<br>
![image](https://user-images.githubusercontent.com/91566044/160675616-d086adb3-6331-4f18-bbec-45ad3d8db4d7.png)
<br>

El inicio nos indica el libro al que pertenece el script, su autor, el capitulo y la forma en que se guarda.
Siguiendo en las siguientes lineas vemos como crea una variable "number" y le va asignando diferentes valores:
<br>
![image](https://user-images.githubusercontent.com/91566044/160676262-2424b912-1596-45ae-84d0-d440600600e2.png)

Estos valores se van sacando por pantalla con un Write-Host, como vemos:
<br>
![image](https://user-images.githubusercontent.com/91566044/160676325-f3ac7959-4a0d-4351-a9d7-5ef528609341.png)

Va repitiendo la secuencia durante todo el script.

## Script 2

![image](https://user-images.githubusercontent.com/91566044/160677324-260abd1c-d3e2-4c6b-a8e3-0e1796fbe3d2.png)
<br>
El inicio del script vuelve a ser una synopsis donde nos indica las mismas cosas que el script anterior.
<br>
![image](https://user-images.githubusercontent.com/91566044/160677460-991ae548-892a-44fe-9495-6d2cd31f2579.png)
<br>
La continuacion del script es un loop de "for" donde contador ira en aumento, mientras el mismo sea menor que el valor de $repeat.
<br>
![image](https://user-images.githubusercontent.com/91566044/160677818-81867858-4f6b-47e7-a32f-2e7c11b4c005.png)
<br>
Mientras esto sea asi escribira "hello"
<br>
![image](https://user-images.githubusercontent.com/91566044/160677919-980b7cf8-9a58-4b15-a802-7fa580ecddab.png)
<br>
Sigue con un loop de tipo while que realiza la misma funcion.
<br>
![image](https://user-images.githubusercontent.com/91566044/160678066-9379102b-ae69-494c-8cd0-2963dfe5a8af.png)
<br>
El siguiente loop es un do while con la misma utilidad.
<br>
![image](https://user-images.githubusercontent.com/91566044/160678195-9d40453f-deca-4f9e-8548-34e779ab49aa.png)
<br>
Sigue con un loop for each, donde lee un string la cual contiene "PowerShell for Beginners" caracter a caracter y lo va imprimiendo.
<br>
![image](https://user-images.githubusercontent.com/91566044/160678452-02de3c58-0c43-48db-a510-0b3d18cd3904.png)
<br>
Y el ultimo comando es un loop ForEach-Object donde lee otra string igual y la va escribiendo caracter a caracter
<br>
![image](https://user-images.githubusercontent.com/91566044/160678790-dcba1af6-9019-4e2c-959e-3165444035d7.png)
<br>
## Script 3

![image](https://user-images.githubusercontent.com/91566044/160679316-ad79e93c-9db3-46fb-a341-dc166705ac84.png)
<br>
![image](https://user-images.githubusercontent.com/91566044/160679387-a844f802-2019-4c3b-8d99-37151044efa9.png)
<br>
![image](https://user-images.githubusercontent.com/91566044/160679437-95459021-e364-4665-9848-35bb36a30ca3.png)
<br>
El script inicia con otra synopsis
<br>
![image](https://user-images.githubusercontent.com/91566044/160679730-c22f184c-a058-42e4-bef9-35205bf4672c.png)
<br>
Lo siguiente nos pone dos condiciones, las cuales si se cumplen se ejecuta el codigo que esta entre {}
<br>
![image](https://user-images.githubusercontent.com/91566044/160680005-c1d8250b-8f41-40ad-bd11-69cb3692a917.png)
<br>
Lo siguiente que hace es mostrarnos como funcionan las condiciones pero con variables numericas.
<br>
![image](https://user-images.githubusercontent.com/91566044/160680208-9018b964-5200-469d-a962-9548336d024e.png)
<br>
Sigue con el mismo ejemplo pero en este caso, las variables son Strings.
<br>
![image](https://user-images.githubusercontent.com/91566044/160680505-65b0072c-4c45-4df0-bcb2-8aced2e8ee75.png)
<br>
En este caso, pide un imput al usuario mediante el prompt, donde usara ese imput para aplicar funciones como el elseif o el else.
<br>
![image](https://user-images.githubusercontent.com/91566044/160680861-77d9e898-b6ac-45fe-b5b5-9a959574e76c.png)
<br>
Lo siguiente que nos muestra este script son los operadores de comparación, donde nos muestra el -eq = Iguales, -ne = No son iguales, -gt = Mayor que, -ge = Mayor o igual que, -lt = Menor que, -le = Menor o igual que.
<br>
![image](https://user-images.githubusercontent.com/91566044/160681221-5449300f-57a6-4592-9a25-91a9a2be071c.png)
<br>
Continua el script mostrandonos como funciona el -like, -notlike, -match, -not match, -contains, -notcontains, -in, -notin, -is, -isnot  el cual funciona comparando dos variables, o caracteres, ya sea 1 o mas de estos, también explica el uso del "asterisco" el cual sirve para indicar que puede haber mas caracteres en su lugar.
<br>
![image](https://user-images.githubusercontent.com/91566044/160682140-06438236-2f19-46e9-bd66-8af015d00668.png)
<br>
La parte final del script esplica como funciona un switch, y realiza uno spara dejarnoslo de ejemplo.
<br>
![image](https://user-images.githubusercontent.com/91566044/160682371-981c541d-4daa-477c-a965-7107ddc16336.png)
<br>

# TAREA  #6

## PARTICIPANTE
1. Juan Felipe Martinez .........

## Ejercicio #1

```javascript
var nombre = prompt("Ingrese su nombre");
console.log("Ahora estas en la matrix" + " " +nombre);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/1.png)

## Ejercicio #2

```javascript
var decimal = prompt("Ingrese un numero decimal");
var entero = prompt ("Ingrese un numero entero");
var suma = parseFloat(decimal) + parseInt(entero);
console.log("El resultado de la suma es:"+" "+suma);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/2.png)

## Ejercicio 3

```javascript
var numero_Uno = prompt("Ingrese un numero");
var numero_Dos = prompt("Ingrese otro numero");
var suma = parseInt(numero_Uno) + parseInt(numero_Dos);
var numero_tres = prompt("Ingrese el numero par multiplicar la suma");
var producto = (suma * numero_tres);
console.log("Multiplicacion de la suma por el ultimo numero"+" "+producto);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/3.png)

## Ejercicio 4

```javascript
var kilometros = prompt("Ingrese el numero de kilometros recorridos");
var litros_combustible = prompt("Ingrese el numero de litros de combustibleque consumio durante el recorrido");
var division = (kilometros/litros_combustible);
console.log("El consumo por kilometro es de:" + " "+division);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/4.png)

## Ejercicio 5

```javascript
var farenheit = prompt("Ingrese la temperatura en Farenheit");
var celsius = ((5/9)*(farenheit-32));
console.log("La conversion en Celsios es de: "+celsius);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/5.png)

## Ejercicio 6

```javascript
var numero_1no = prompt("Ingrese el primer numero");
var numero_2os = prompt("Ingrese el segundo numero");
var numero_3res = prompt("Ingrese el tercer numero");
var promedio = ((parseFloat(numero_1no)+parseFloat(numero_2os)+parseFloat(numero_3res))/3);
console.log("El promedio de los tres es de: "+promedio);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/6.png)

## Ejercicio 7

```javascript
var numero = prompt("Ingrese el numero");
var calculo = (numero*0.15);
var descuento = (numero - calculo);
console.log("Descontando el 15% queda en: "+descuento); 
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/7.png)

## Ejercicio 8

```javascript
var palabra1 = prompt("Ingrese la primera palabra");
var palabra2 = prompt("Ingrese la segunda palbara");
console.log(palabra1+" "+palabra2);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/8.png)

## Ejercicio 9

```javascript
var texto = prompt("Ingrese el texto que desee");
var arraytext = texto.split("");
console.log("El primer caracter del texto es: "+arraytext[0]);
var numero = prompt("Ingrese un numero positivo menor a la cantidad de caracteres del texto");
console.log("El caracter que corresponde a el numero digitado es: "+arraytext[numero]);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/9.png)

## Ejercicio 10

```javascript
var numero_Shows = prompt("Ingrese el numero de shows musicales vistos en el ultimo año");
var condicion = (numero_Shows < 3);
console.log(condicion);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/10.png)

## Ejercicio 11

```javascript
var numero_Fecha = prompt("Ingrese el numero con el formato DDMMAAAA");
var numarr = numero_Fecha.split("");
console.log(numarr[0]+numarr[1]+"/"+numarr[2]+numarr[3]+"/"+numarr[4]+numarr[5]+numarr[6]+numarr[7]);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/11.png)

## Ejercicio 12

```javascript
var numero = prompt("Ingrese un numero para saber si es par o impar");
var operacion = (numero % 2);
var condicion = (operacion == 0);
console.log("¿Es numero par? " + condicion);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/12.png)

## Ejercicio 13

```javascript
var edad = prompt("Ingrese su edad");
var cantidad_Articulos = prompt("Ingrese el numero de articulos comprados");
var condicion= (cantidad_Articulos >= 1 && edad <= 18);
console.log(condicion);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/13.png)

## Ejercicio 14

```javascript
var texto = prompt("Ingrese el texto que desee");
var arraytext = texto.split("");
var operacion = (arraytext.length % 2);
var condicion = (operacion == 0);
console.log(condicion);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/14.png)

## Ejercicio 15

```javascript
var palabra1 = prompt("Ingrese una palabra");
var arraytext1 = texto.split("");
var palabra2 = prompt("Ingrese otra palabra");
var arraytext2 = texto.split("");
var condicion = (arraytext1.length < arraytext2);
console.log(condicion);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/15.png)

## Ejercicio 16

```javascript
var nombre1 = prompt("Ingrese un nombre");
var arraytext1 = texto.split("");
var nombre2 = prompt("Ingrese otro nombre");
var arraytext2 = texto.split("");
var condicion = (arraytext1[0] == arraytext2[0] && arraytext1[arraytext1.length] == arraytext2[arraytext2-length]);
console.log(condicion);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/16.png)

## Ejercicio 17

```javascript
var numero = prompt("Ingrese un numero");
var condicion = (numero < 0) ? (numero*-1) : (numero*1);
console.log("El valor absoluto es: "+ condicion);
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/17.png)

## Ejercicio 18

```javascript
var numero1 = prompt("Ingrese un numero");
var numero2 = prompt("Ingrese otro numero");
var condicion = (numero1 > numero2) ? console.log(numero2 + " Es mayor") : console.log(numero1 + " Es mayor");
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/18.png)

## Ejercicio 19

```javascript
var letra = prompt("Ingrese una Letra");
var arrayletra = letra.split("");
var condicion = (letra.length > 1) ? console.log("No es posible identificar la letra") : (arrayletra[0] == "a","e","i","o","u") ? console.log("Es vocal") : console.log("No es vocal");
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/19.png)

## Ejercicio 20

```javascript
var numero1 = prompt("Ingrese el primer numero");
var numero2 = prompt("Ingrese el segundo numero");
var numero3 = prompt("Ingrese el tercer numero");
var condicion = ((numero1 < numero2) ? ((numero1 < numero3) ? console.log(numero1):console.log(numero3)) : ((numero2 < numero3) ? console.log(numero2) : console.log(numero3))); 
```
![li](https://github.com/FelipeeMartinez/READMEt6/blob/master/Imagenes/20.png)


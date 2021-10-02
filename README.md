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


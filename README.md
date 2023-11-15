# ayudantia1511
## Añadir elementos a un arreglo con condiciones
Realice un programa en C++ permite al usuario añadir números a un arreglo de longitud 5. Solo se aceptan números que sean positivos e impares. Si el usuario introduce un número que no cumple con estas condiciones, el programa solicitará de nuevo una entrada válida indefinidamente. Una vez que el arreglo esté completo, el programa muestra los números almacenados en el arreglo. Para la validación crea una función llamada ```validador``` que reciba el número y retorne true o false según sea el caso, si el número es inválido debe mostrar el mensaje ```Número inválido```   
## Conversor de Temperaturas en C++

Programa en C++ que permite la conversión de temperaturas entre Celsius, Fahrenheit y Kelvin. El usuario puede seleccionar entre varias opciones para realizar las conversiones de temperatura deseadas.

### Funcionalidades

1. **Conversión de Celsius a Fahrenheit**
   - Función: `celsiusToFahrenheit(float celsius)`
   - Fórmula: Fahrenheit = (Celsius * 9/5) + 32

2. **Conversión de Fahrenheit a Celsius**
   - Función: `fahrenheitToCelsius(float fahrenheit)`
   - Fórmula: Celsius = (Fahrenheit - 32) * 5/9

3. **Conversión de Celsius a Kelvin**
   - Función: `celsiusToKelvin(float celsius)`
   - Fórmula: Kelvin = Celsius + 273.15

4. **Conversión de Kelvin a Celsius**
   - Función: `kelvinToCelsius(float kelvin)`
   - Fórmula: Celsius = Kelvin - 273.15

5. **Terminación del Programa**

### Validaciones

- El programa valida que la opción seleccionada por el usuario sea válida.
- En caso de una opción no válida, se notifica al usuario y se le solicita volver a elegir.

## Crea un programa en C++ que simule un cajero automático. El programa debe permitir al usuario realizar las siguientes operaciones:

1. Consultar saldo disponible.
2. Depositar dinero en la cuenta.
3. Retirar dinero de la cuenta (asegurándose de que el saldo sea suficiente para cubrir el retiro).
4. Salir del programa.
   
El programa debe mantener un registro del saldo actual y realizar las operaciones según la elección del usuario, mostrando mensajes correspondientes para cada operación realizada.

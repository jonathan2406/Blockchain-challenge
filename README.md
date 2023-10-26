# Reto a realizar sobre BlockChain  

El reto que deben realizar consiste en completar el código con sus debidos métodos y clases
Teniendo en cuenta lo explicado en clase sobre Blockchain.

# PASOS:

 1. Crear la clase bloque con los siguientes atributos:
- Indice: Número entero que representa el indice del bloque. 
- Datos: Una cadena que representa los datos almacenados en el bloque.
- Tiempo: Valor de tiempo en el que se creo el bloque.
- HashAnterior: Cadena que representa el hash anterior, del bloque, es decir un puntero.
- Hash: Una cadena que representa el hash del bloque actual
- Siguiente: Un atributo que almacena una referencia al siguiente bloque en la cadena.

2. Implementar la generación de Hash:
- En la clase bloque implementar el método 'calcular_hash()' la cual utiliza
    una función para encriptar y desencriptar cadenas.

3. Crear la clase CadenaBlockchain:
- Implementa una clase 'CadenaBlockchain' que tendrá un puntero al primer bloque ('bloque_genesis') como atributo.
- *Explicación:* La cadena de bloques se gestiona como una lista enlazada, donde el primer bloque sirve como punto de partida.

4. Métodos para agregar bloques:
- Implementa el método 'agregar_bloque()' en la clase 'CadenaBlockchain' que tome como argumento 'datos'. Este método
  deberá crear un nuevo bloque, calcular su Hash, y agregarlo al final de la cadena.

5. Método para mostrar la cadena:
- Implementa el método 'mostrar_cadena()' en la clase 'CadenaBlockchain' que imprima todos los bloques de la cadena.
  Este método recorrer la cadena e imprimir los datos de cada bloque.

6. Método para Verificar la Integridad de la Cadena:

- Implementa el método 'verificar_integridad()' en la clase 'CadenaBlockchain' que verifique si la cadena de bloques es válida y no ha sido alterada. Este método deberá recorrer la cadena y verificar que el hash calculado de cada bloque coincida con el hash_anterior del siguiente bloque.

7. Que funcione el código.



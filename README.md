# Práctica: Sincronización de Hilos en Java

## Descripción
Esta práctica implementa y analiza diferentes mecanismos de concurrencia y sincronización en Java, utilizando cuatro hilos que realizan incrementos sobre una variable compartida.

---

## Ejercicios

1. **Suma sin sincronización (SumaSinSincronizacion.java)**
 Propósito:o:** Demostrar el surgimiento de una condición de carrera al no utilizar mecanismos de control.

2. **Exclusión mutua con Lock (SumaLock.java)Propósito:ósito:** Proteger la sección crítica utilizando ReentrantLock para garantizar un acceso exclusivo y un resultado correcto.

3. **Spin Lock con tryLock (SumaSpinLock.java)**
   * **Propósito:** Implementar una espera activa (spin lock) mediante tryLock() para sondear la disponibilidad del candado.

4. **Sincronización con semáforo (SumaSemaforo.java)**
   * **Propósito:** Controlar el acceso a la sección crítica utilizando un Semaphore binarioSincronización por barrera (SumaBarrera.java)era (SumaBarrera.java)**
   * **Propósito:** Coordinar a los hilos mediante una CyclicBarrier para detenerlos hasta que todos concluyan su fase de trabajo.

---

## Compilación y Ejecución

Para compilar y ejecutar cualquiera de los ejercicios, utiliza los siguientes comandos en tu terminal (sustituyendo el nombre de la clase según corresponda):

`bash
javac NombreDeLaClase.java
java NombreDeLaClase
 

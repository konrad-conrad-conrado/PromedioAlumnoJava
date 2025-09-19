# PromedioAlumnoJava

Este proyecto en Java implementa una clase **Alumno** que permite calcular el promedio de cinco calificaciones y asignar una calificación final en letra, de acuerdo con una tabla de rangos.  

El programa forma parte de una tarea de programación orientada a objetos, y fue desarrollado en **IntelliJ IDEA**.

---

## 🚀 Descripción de la práctica

La clase `Alumno` contiene:
- **Atributos**:  
  - `String nombre` → nombre del estudiante.  
  - `double[] calificaciones` → arreglo con 5 calificaciones numéricas.  
- **Métodos**:  
  1. `calcularPromedio(double[] calificaciones)` → calcula y devuelve el promedio.  
  2. `obtenerCalificacion(double promedio)` → devuelve la calificación en letra según el rango:  
     - 0 – 50 → F  
     - 51 – 60 → E  
     - 61 – 70 → D  
     - 71 – 80 → C  
     - 81 – 90 → B  
     - 91 – 100 → A  
  3. `imprimirResultados(...)` → imprime nombre, calificaciones, promedio y calificación final.  

---

## 🖥️ Instrucciones de uso

### En IntelliJ IDEA
1. Abre IntelliJ IDEA.  
2. Crea un nuevo **Proyecto Java**.  
3. Copia el archivo `Alumno.java` dentro de la carpeta `src`.  
4. Asegúrate de tener configurado el SDK de Java (versión 11 o superior).  
5. Ejecuta la clase desde IntelliJ (`Run → Run 'Alumno.main()'`).

### En terminal
Si quieres compilar y ejecutar desde la terminal (macOS/Linux):

```bash
cd src
javac Alumno.java
java Alumno


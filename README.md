# Calculadora Básica en Java Swing (NetBeans)

¡Bienvenido a **Calculadora Básica**! Esta es una aplicación de escritorio interactiva construida en **Java** utilizando la biblioteca gráfica **Swing** (JFrame). El proyecto fue diseñado utilizando el entorno de desarrollo integrado **Apache NetBeans**, aprovechando su potente diseñador de interfaces gráficas.

---

## 🎨 Características Visuales y de Diseño
El diseño de la interfaz destaca por su estilo limpio y llamativo:
- **Panel de Fondo Elegante**: Un fondo de color azul rey intenso (`#000099`) que le da personalidad y un contraste moderno a los controles.
- **Pantalla de Texto Clara**: Un área de visualización (`JTextField`) de color gris (`#999999`) que resalta los números ingresados y los resultados de las operaciones.
- **Botones Interactivos**: Botones numéricos (`0-9`) y de operaciones ordenados en cuadrícula de fácil acceso.

---

## ⚙️ Funciones Soportadas
La calculadora realiza las operaciones aritméticas básicas de forma directa y sencilla:
- **Operaciones Principales**: 
  - ➕ Suma (`+`)
  - ➖ Resta (`-`)
  - ✖️ Multiplicación (`*`)
  - ➗ División (`/`)
- **Control de Pantalla**:
  - Botón **`c`** (Clear): Limpia por completo la pantalla y reinicia el estado de las variables para comenzar un nuevo cálculo.
  - Botón **`=`** (Igual): Procesa la operación seleccionada utilizando los dos operandos ingresados y muestra el resultado final.

---

## 📂 Estructura de Archivos del Proyecto
Dentro de la carpeta `src/`, encontrarás los dos archivos esenciales del componente:
- **`CalculadoraBasic.java`**: Contiene todo el código fuente de Java, incluyendo el manejo de eventos (ActionListeners), la inicialización de los componentes y la lógica matemática detrás de cada botón.
- **`CalculadoraBasic.form`**: Archivo de metadatos XML utilizado por NetBeans GUI Builder para guardar las posiciones, colores y propiedades visuales de la interfaz gráfica.

---

## 🚀 Cómo abrir y ejecutar el proyecto en Apache NetBeans

Para correr esta calculadora en tu computadora local usando **NetBeans**, sigue estos sencillos pasos:

1. **Abre NetBeans**: Abre tu entorno de desarrollo Apache NetBeans (versión 12 o superior recomendada).
2. **Carga el Proyecto**:
   - Ve al menú superior y selecciona **File** > **Open Project...** (o usa el atajo `Ctrl + Shift + O`).
   - Navega hasta el directorio del proyecto:
     `C:\Users\angee\OneDrive\Documents\NetBeansProjects\Calculadora`
   - Haz clic en el botón **Open Project**.
3. **Ejecuta la Aplicación**:
   - En la barra lateral izquierda (panel *Projects*), despliega el proyecto **Calculadora** y entra a `Source Packages` > `<default package>`.
   - Haz clic derecho sobre **`CalculadoraBasic.java`** y selecciona **Run File** (o presiona `Shift + F6`).
   - ¡Listo! Se abrirá la ventana interactiva de la calculadora en tu pantalla.

---

## 🛠️ Tecnologías Utilizadas
- **Lenguaje**: Java SE (Standard Edition)
- **Biblioteca GUI**: Java Swing & AWT
- **IDE**: Apache NetBeans

# Credit Card Management 💳

![Diagrama de Clases](https://github.com/Juan-Matias/gestionTarjetaDeCredito/blob/163564606d40ec5e58dc882fe8089278fa87ff96/diagramaDeClases.png)


Simulación simple de una tarjeta de crédito desarrollada en Java.  
Permite realizar compras siempre que haya saldo disponible, y mantiene un historial de transacciones.

## 🚀 Características

- Definición de un **límite de crédito**
- Gestión del **saldo restante**
- Registro de cada **compra realizada**
- Validación de compras según el **saldo disponible**

## 🛠️ Tecnologías usadas

- Java 17 o superior
- IntelliJ IDEA (opcional)
- Consola / Terminal

## 📁 Estructura del proyecto

```
src/
├── Compra.java               // Clase que representa una compra individual
├── TarjetaDeCredito.java     // Clase principal que maneja el saldo y el historial
├── Main.java                 // Punto de entrada para pruebas
```

## ▶️ Cómo ejecutar

Desde la terminal:

```bash
cd src
javac Compra.java TarjetaDeCredito.java Main.java
java Main
```

O desde un entorno como **IntelliJ IDEA**, creá una configuración de ejecución y ejecutá `Main`.

## 📸 Ejemplo de salida

```
Compra 1 aprobada.
Compra 2 rechazada (saldo insuficiente).
Saldo restante: $750.0
```

## 📌 Autor

**Matías**  
Proyecto de práctica en Java como ejercicio de lógica y POO.

---

¡Gracias por visitar este proyecto!  
Podés dejar una ⭐ si te sirvió o te gustó el código.

💶 Gestor de Caja: Cambio Óptimo en Efectivo
Este proyecto simula una caja registradora que gestiona transacciones en efectivo. Permite introducir el precio de un artículo y el importe pagado (con desglose en billetes y monedas), y devuelve el cambio de forma óptima, utilizando la menor cantidad de unidades posible y actualizando el estado de la caja tras cada operación.

🧾 Descripción
La caja inicia con un importe de 234,27 €, distribuido de la siguiente manera:

Billetes:

500€: 0

200€: 0

100€: 0

50€: 1

20€: 4

10€: 8

5€: 2

Monedas:

2€: 5

1€: 4

0.50€: 0

0.20€: 0

0.10€: 1

0.05€: 2

0.02€: 3

0.01€: 1

Los datos están cargados en un array de objetos que representa el estado de la caja.

⚙️ Funcionamiento
Entrada del usuario:

Precio del producto.

Cantidad entregada por el cliente desglosada por billetes y monedas.

Cálculo:

Se determina si el pago es justo, si falta dinero o si se debe devolver cambio.

En caso de devolver cambio, se utiliza un algoritmo de cambio óptimo, priorizando las unidades de mayor valor disponibles.

Salida del sistema:

Mensaje indicando el resultado: "Pago justo", "Falta dinero" o "Cambio entregado".

Desglose detallado del cambio entregado.

Estado actualizado de la caja después de la operación.

💡 Ejemplo de uso
Entrada:
Precio del producto: 18.73 €

Dinero entregado:

Billetes de 20€: 1

Salida:
Cambio a devolver: 1.27 €

Desglose del cambio:

1 moneda de 1€

1 moneda de 0.20€

1 moneda de 0.05€

1 moneda de 0.02€

Estado actualizado de la caja mostrado al finalizar la operación.

🧑‍💻 Lenguaje
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript Logo" width="30"/>
JavaScript
# FoodApp

Este repositorio contiene dos aplicaciones web en HTML para planificar menús y generar recetas.

## `RECETAS.html`

Generador de recetas interactivo que permite crear platos a partir de una base de ingredientes. Incluye:

- Barra lateral con buscador de ingredientes.
- Zona de arrastre para ir añadiendo ingredientes a la receta.
- Tabla que calcula de forma automática los macros (proteínas, hidratos, grasa y calorías) según la cantidad indicada.
- Posibilidad de crear múltiples recetas, renombrarlas y exportarlas a CSV.

El código se apoya únicamente en JavaScript del lado del cliente y almacena las recetas en memoria mientras la página está abierta.

## `MENÚ2.html`

Planificador semanal que combina recetas y usuarios con requerimientos nutricionales:

- Panel lateral con usuarios y banco de tarjetas de recetas.
- Los usuarios se definen con peso, altura, edad, sexo y nivel de actividad para calcular sus necesidades calóricas.
- Las recetas se pueden arrastrar sobre la cuadrícula de comidas (desayuno, comida, snack y cena) para cada día de la semana.
- El resumen inferior muestra barras con las calorías y macronutrientes de cada día, adaptados a las necesidades de los usuarios.

Ambos archivos funcionan de forma local y no requieren dependencias externas.

# Analisis-de-embudo-y-retencion
El objetivo de este proyecto fue mapear el embudo de conversión completo, identificando los principales puntos de fuga y evaluando la retención de usuarios por cohortes.
# Herramientas
SQL, Pensamiento critico, Analisis, visualización y limpieza de datos.

# Preguntas clave
- ¿En qué etapa del proceso perdemos más usuarios?
- ¿Cómo mejorar su retención a lo largo del tiempo?

# Metodología
- Exploración: esquema y datos base.
- Construcción del embudo de conversión
- Calculos: tasas y caidas
- Analisis: retención y cohortes
- Simulación: mejoras
- Informe ejecutivo
  
# Conclusiones
- La mayor caida porcentual se presenta entre los pasos select_item y add_to_cart
- Optimizar la etapa entre select_item y add_to_cart, ya que representa el mayor punto de fuga del embudo

# Recomendaciones

- La optimización entre etapas se podria lograr mejorando la experiencia de navegación, la claridad del precio, los costos de envío, entre otros.
- Tambien es posible implementar estrategias de activación temprana, como beneficios por primera compra.
- La mayoría de los usuarios abandona rápidamente en los primeros días si no encuentra valor o enganche. Lograr una retención temprana (entre las 2 primeras etapas) es clave para mejorar la consistencia de los clientes por ende una resolucion final en compra.

# Diccionario de datos
TABLAS:
- mercadolibre_funnel: registra eventos de usuarios durante el proceso de compra.
- mercadolibre_retention: mide actividad recurrente por usuario y periodo.

COLUMNAS DE INTERES:
- first_visit
- select_item
- add_to_cart
- begin_checkout
- add_shipping_info
- add_payment_info
- purchase

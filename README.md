# Proyecto plataforma Zuber

## Descripción
 Este proyecto está orientado a identificar patrones de movilidad, comprender las preferencias de los usuarios y evaluar el impacto de factores externos como el meteorológico y el competitivo en los trayectos del transporte urbano en la ciudad de Chicago.

## Conclusiones
1. La empresa Flash Cab ejerce una posición de dominio absoluto en el sector de transportes tradicionales, acumulando la mayor cuota de mercado en volumen bruto de viajes durante los días de medición masiva.
2. El resto del mercado tradicional se encuentra altamente atomizado en decenas de pequeñas compañías con participaciones marginales. Esta fragmentación facilita la entrada de Zuber, permitiendo capturar clientes mediante una propuesta de valor diferenciada, basada en la inmediatez tecnológica, transparencia de precios y un ecosistema digital moderno.
3. El distrito financiero Loop y zonas colindantes como River North y Streeterville constituyen los principales centros de origen y destino de la ciudad. Concentran la mayor densidad de viajes diarios debido a la intensa actividad corporativa, comercial y turística.
4. El Aeropuerto Internacional O'Hare se posiciona firmemente en el Top 5 de destinos de la ciudad. Aunque representa trayectos de larga distancia, su volumen constante de pasajeros lo convierte en una ruta de alta rentabilidad por unidad de tiempo para la flota de conductores.
5. Se demostró con un 95% de confianza que las condiciones climáticas adversas (lluvia y tormentas) cambian significativamente la duración promedio de los viajes que conectan el centro (Loop) con el aeropuerto (O'Hare) los días.
6. El mal clima incrementa de manera sistemática los tiempos de traslado, un fenómeno impulsado por una velocidad de conducción preventiva y la congestión vial reactiva en las arterias principales de Chicago.
7. Para maximizar la rentabilidad, optimizar la experiencia del usuario y asegurar un lanzamiento exitoso frente a los competidores tradicionales, se recomienda implementar tres políticas operativas inmediatas:
	* Posicionamiento geográfico inteligente: Concentrar y retener la disponibilidad de la flota en el corredor de alta demanda (Loop - River North - Streeterville) durante los horarios pico laborales para minimizar de forma agresiva los tiempos de espera del usuario (ETA).
	* Algoritmo de tarifas dinámicas por clima: Integrar las alertas meteorológicas horarias de forma automatizada en el backend de la aplicación. Cuando se detecten condiciones clasificadas como Bad (lluvia o tormenta), el sistema debe ajustar predictivamente el costo del viaje y los tiempos estimados de llegada, compensando de manera justa el gasto de combustible del conductor atrapado en el tráfico y protegiendo el margen del negocio.
	* Campañas especiales de tarifa plana al Aeropuerto: Diseñar cupones o tarifas fijas atractivas para las rutas hacia O'Hare durante los fines de semana. Esto permitirá a Zuber competir de frente contra el gigante Flash Cab en el segmento de usuarios de alta fidelidad (viajeros frecuentes y turistas), garantizando previsibilidad de costos para el cliente.

## Tecnologías utilizadas
* Python (Pandas, Matplotlib, Seaborn, NumPy, Spipy.stats, Beautifulsoup4, Requests)
* Jupyter Notebook

## Ver el análisis completo
👉 [Haz clic aquí para ver el código y los gráficos interactivos](proyecto_plataforma_zuber.ipynb)


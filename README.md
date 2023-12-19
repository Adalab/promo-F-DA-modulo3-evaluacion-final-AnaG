# Descripción del Proyecto
Este proyecto se enfoca en analizar un conjunto de datos que contiene información sobre reservas de vuelos y datos demográficos de clientes. El objetivo es explorar y visualizar diferentes aspectos de los datos, así como evaluar si existe una diferencia significativa en el número de vuelos reservados según el nivel educativo de los clientes.

# Fases del Proyecto
- Fase 1: Exploración y Limpieza
    Exploración Inicial
    Identificación de problemas potenciales como valores nulos, atípicos o datos faltantes en las columnas relevantes.
    Uso de funciones de Pandas para obtener información estructural, presencia de valores nulos y estadísticas básicas de las columnas involucradas.
    Unión eficiente de los dos conjuntos de datos.
    Limpieza de Datos
    Tratamiento de valores nulos en columnas clave para garantizar datos completos.
    Verificación de consistencia y corrección de datos para su presentación coherente.
    Ajustes o conversiones necesarias en columnas (cambio de tipos de datos) para garantizar la adecuación de los datos para el análisis estadístico.
- Fase 2: Visualización
    Preguntas a Responder Visualmente
    Distribución de la cantidad de vuelos reservados por mes durante el año.
    Existencia de una relación entre la distancia de los vuelos y los puntos acumulados por los clientes.
    Distribución de clientes por provincia o estado.
    Comparación del salario promedio entre los diferentes niveles educativos de los clientes.
    Proporción de clientes con diferentes tipos de tarjetas de fidelidad.
    Distribución de clientes según su estado civil y género.
- Fase 3: Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo
    Objetivo
    Evaluar si existen diferencias significativas en el número de vuelos reservados según el nivel educativo de los clientes.
    Pasos a Seguir
    Preparación de Datos: Filtrar el conjunto de datos para incluir únicamente las columnas 'Flights Booked' y 'Education'.
    Análisis Descriptivo: Agrupar los datos por nivel educativo y calcular estadísticas descriptivas básicas del número de vuelos reservados para cada grupo.
    Prueba Estadística: Realizar una prueba de A/B testing para determinar si existe una diferencia significativa en el número de vuelos reservados entre los diferentes niveles educativos.
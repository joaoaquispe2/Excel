# :sparkle: Análisis de Datos con Excel :sparkle:

### Análisis de datos

El análisis de datos es el proceso de recopilar, organizar, limpiar e interpretar información para obtener conclusiones que apoyen la toma de decisiones. Su objetivo es convertir datos sin procesar en información útil. En Excel, el análisis de datos permite identificar tendencias, comparar resultados, detectar problemas y realizar proyecciones mediante tablas, gráficos, fórmulas y tablas dinámicas.

### KPI (Key Performance Indicator)

Un KPI (Indicador Clave de Desempeño) es una métrica utilizada para medir qué tan bien se está cumpliendo un objetivo específico. Un buen KPI debe ser claro, medible, relevante y estar alineado con los objetivos del negocio. Se utiliza para monitorear el rendimiento y facilitar la toma de decisiones.

**Ejemplos de KPI:**

| Área | KPI | Ejemplo |
| --- | --- | --- |
| Ventas | Ventas mensuales | S/ 80,000 |
| Marketing | Tasa de conversión | 4.8% |
| Recursos Humanos | Rotación de personal | 6% |
| Atención al cliente | Tiempo de respuesta | 12 minutos |
| Finanzas | Margen de utilidad | 22% |

### Tipos de tablas y estructuras de datos

Una buena estructura de datos facilita el análisis, reduce errores y mejora el rendimiento de herramientas como tablas dinámicas, Power Query o Power BI.

#### 1. Tabla simple

Contiene filas y columnas con encabezados únicos. Cada fila representa un registro y cada columna un atributo.

| ID | Cliente | Producto | Venta |
| --- | --- | --- | --- |
| 1 | Ana | Laptop | 3500 |

Es la estructura más utilizada para almacenar información.

#### 2. Tabla de Excel

Es una tabla creada con **Insertar > Tabla**. Permite aplicar filtros automáticos, formatos, referencias estructuradas y expansión automática al agregar nuevos registros.

Es la estructura recomendada para trabajar en Excel.

#### 3. Base de datos tabular

Organiza la información siguiendo el principio de 

- `una fila = un registro`
- `una columna = un atributo`

| ID | Fecha | Ciudad | Vendedor | Total |
| --- | --- | --- | --- | --- |

Este formato es compatible con la mayoría de herramientas de análisis de datos.

### Limpieza básica de datos

La limpieza de datos consiste en preparar la información antes de analizarla para garantizar que sea correcta, consistente y completa. Las tareas más comunes incluyen eliminar duplicados, corregir errores de escritura, completar valores faltantes, unificar formatos de fecha y números, eliminar espacios innecesarios y validar que los datos sean coherentes. Una base de datos limpia produce análisis más precisos y evita conclusiones incorrectas.

| Tipo de limpieza | Descripción |
| --- | --- |
| Eliminar duplicados | Identificar y eliminar registros repetidos para evitar resultados incorrectos. |
| Corregir errores de escritura | Unificar nombres, categorías o valores escritos de forma diferente (ej. "Lima" y "lima"). |
| Completar datos faltantes | Llenar o gestionar celdas vacías cuando sea posible o eliminar registros incompletos si es necesario. |
| Estandarizar formatos | Unificar formatos de fechas, monedas, porcentajes, números y texto. |
| Eliminar espacios innecesarios | Quitar espacios al inicio, final o entre palabras que afectan búsquedas y comparaciones. |
| Validar tipos de datos | Verificar que cada columna contenga el tipo de dato correcto (texto, número, fecha, etc.). |
| Corregir inconsistencias | Asegurar que los datos sigan un mismo criterio, como nombres de productos, ciudades o categorías. |
| Detectar valores atípicos | Identificar datos anormalmente altos o bajos que puedan corresponder a errores de captura. |

### Errores comunes al estructurar información

| Error | Problema que genera | Buena práctica |
| --- | --- | --- |
| Combinar celdas | Dificulta filtros, fórmulas y tablas dinámicas | Mantener cada dato en una celda independiente. |
| Dejar filas o columnas vacías | Interrumpe el rango de datos | Mantener la tabla continua, sin espacios. |
| Encabezados duplicados o poco claros | Confunde el análisis y las fórmulas | Usar nombres únicos y descriptivos. |
| Mezclar diferentes tipos de datos en una columna | Genera errores al ordenar o calcular | Cada columna debe contener un solo tipo de dato. |
| Usar colores como información | Los colores no pueden analizarse fácilmente | Registrar el estado en una columna específica (por ejemplo: "Pendiente", "Completado"). |
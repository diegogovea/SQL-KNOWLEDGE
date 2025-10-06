# 🗄️ SQL vs NoSQL Databases

Una guía concisa para entender las diferencias clave entre **bases de datos relacionales (SQL)** y **no relacionales (NoSQL)**.

---

## 📘 SQL Databases (Relacionales)

**Características principales:**
- Basadas en un modelo estructurado de **tablas, filas y columnas**.  
- Requieren un **esquema predefinido**.  
- Cumplen con las propiedades **ACID**:  
  - **A**tomicity  
  - **C**onsistency  
  - **I**solation  
  - **D**urability  
- Utilizan **SQL (Structured Query Language)** para consultar y manipular datos.  
- Escalan **verticalmente** (aumentando la capacidad de un solo servidor).  

**Usos comunes:**
- Aplicaciones que requieren **alta consistencia de datos**, **relaciones complejas** o **transacciones financieras**.  
  > Ejemplos: sistemas bancarios, e-commerce, ERP, CRM.

---

## 📗 NoSQL Databases (No Relacionales)

**Características principales:**
- Usan distintos modelos de datos:
  - **Documentos** (MongoDB)
  - **Clave-Valor** (Redis)
  - **Columnas** (Cassandra)
  - **Grafos** (Neo4j)
- Son **sin esquema fijo** o **flexibles en su estructura**.  
- Priorizan las propiedades **BASE**:
  - **B**asically Available  
  - **S**oft state  
  - **E**ventually consistent  
- Escalan **horizontalmente** (añadiendo más servidores).  
- Utilizan diferentes métodos o lenguajes de consulta según el modelo.  

**Usos comunes:**
- Aplicaciones que requieren **alta escalabilidad**, **flexibilidad** o manejo de **datos no estructurados**.  
  > Ejemplos: redes sociales, análisis de big data, IoT, streaming.

---

## ⚖️ Diferencias Clave

| Característica     | SQL                          | NoSQL                         |
|--------------------|------------------------------|-------------------------------|
| **Estructura**     | Tablas y relaciones fijas     | Modelos flexibles             |
| **Esquema**        | Predefinido (rígido)          | Dinámico o ausente            |
| **Consistencia**   | Fuerte (ACID)                 | Eventual (BASE)               |
| **Escalabilidad**  | Vertical                      | Horizontal                    |
| **Consultas**      | SQL estándar                  | Propias del motor de datos    |
| **Uso ideal**      | Transacciones complejas       | Grandes volúmenes y flexibilidad |

---

## 🎯 Elección del Tipo de Base de Datos

- **Elige SQL si:**
  - Tu aplicación requiere **integridad de datos**.
  - Existen **relaciones complejas** entre entidades.
  - Manejas **transacciones críticas** (ej. banca, inventarios).

- **Elige NoSQL si:**
  - Necesitas **escalar rápidamente** con grandes volúmenes de datos.
  - Trabajas con **datos no estructurados o semiestructurados**.
  - Requieres **alta disponibilidad y rendimiento**.

---

## 🔀 Enfoque Híbrido

En muchos proyectos modernos, **combinar SQL y NoSQL** resulta la mejor opción.  
Ejemplo:  
- **SQL** para datos transaccionales.  
- **NoSQL** para almacenamiento de logs, analítica o datos en tiempo real.

---

## 🧩 Conclusión

| SQL                            | NoSQL                            |
|--------------------------------|----------------------------------|
| Estructurado y consistente      | Flexible y escalable             |
| Ideal para integridad y lógica  | Ideal para velocidad y volumen   |

> La mejor elección depende del **tipo de aplicación**, **necesidades de consistencia**, y **escalabilidad** del sistema.

# MongoDB-UNAD

---

## 🧩 Objetivo del Proyecto

Implementar una base de datos NoSQL utilizando **MongoDB**, realizando:

✔ Diseño del modelo documental  
✔ Creación de la base de datos y la colección  
✔ Inserción de 100 documentos a partir de un archivo CSV  
✔ Ejecución de consultas básicas (CRUD)  
✔ Consultas con filtros y operadores  
✔ Consultas de agregación para análisis estadístico  
✔ Documentación y análisis de resultados  

---

## 🛠️ Tecnologías Utilizadas

- **MongoDB Community Server**
- **MongoDB Compass**
- **CSV (datos de prueba)**
- **Git y GitHub**

---

## 🗄️ Base de Datos

**Nombre de la base de datos:** `UNAD`  
**Colección principal:** `Leads`

La colección contiene información de leads comerciales con los siguientes campos:

- nombre  
- email  
- telefono  
- pais  
- fuente  
- presupuesto_estimado  
- intereses  
- estado  
- campaña  
- fecha_creacion  

---

## 🔽 Importación del CSV en MongoDB Compass

1. Abrir MongoDB Compass  
2. Crear la base de datos **UNAD**  
3. Crear la colección **Leads**  
4. Clic en **Import Data**  
5. Seleccionar el archivo `100_leads_random_names.csv`  
6. Tipo de archivo: **CSV**  
7. Importar  

*Nota: algunos campos de fecha pueden quedar como string; pueden convertirse con `$toDate` si es necesario.*

---

## 📌 Consultas Incluidas

El repositorio contiene consultas de:

### 🔹 CRUD básico
- Inserción
- Selección
- Actualización
- Eliminación

### 🔹 Filtros y operadores
- `$gt`, `$lt`, `$gte`, `$lte`
- `$in`, `$nin`
- `$ne`
- Combinación de condiciones

### 🔹 Agregaciones
- `$group`
- `$sum`
- `$avg`
- `$max`, `$min`
- `$unwind`
- `$sort`
- `$substr`

---

## 📊 Análisis Generado

Incluye estadísticas como:

- Leads por país  
- Presupuesto promedio  
- Intereses más comunes  
- Lead por campaña  
- Fecha de creación indicada en los registros  

---

## ▶️ Comandos para clonar el repositorio

```bash
git clone https://github.com/tuusuario/tu-repositorio.git
cd tu-repositorio

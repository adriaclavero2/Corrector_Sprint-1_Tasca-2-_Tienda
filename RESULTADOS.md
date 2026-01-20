# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 32 correctas de 41 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.35 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 22: Error
- **Descripción**: 1253 (42000): COLLATION 'utf8_spanish_ci' is not valid for CHARACTER SET 'utf8mb4'


## ✅ Query 23: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 24: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 25: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio | fabricante
+nombre | precio | fabricant
 GeForce GTX 1080 Xtreme | 755.00 | Crucial
```

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 26: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 27: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 28: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio | fabricante
+nombre | precio | fabricant
 Disco duro SATA3 1TB | 86.99 | Seagate
 Monitor 24 LED Full HD | 202.00 | Asus
 Monitor 27 LED Full HD | 245.99 | Asus
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 29: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio | fabricante
+nombre | precio | fabricant
 Disco duro SATA3 1TB | 86.99 | Seagate
 Monitor 24 LED Full HD | 202.00 | Asus
 Monitor 27 LED Full HD | 245.99 | Asus
```

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

🚨 **Problemas detectados:**
⚠️ Considerar `EXISTS` en lugar de `IN` para eficiencia.

---

## ❌ Query 30: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT
    producto.nombre,
    producto.precio,
    fabricante.nombre
FROM prod' at line 3


## ❌ Query 31: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | precio | fabricante
+nombre | precio | nombre
 Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
 Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 32: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio | fabricante
+nombre | precio | nombre
 GeForce GTX 1080 Xtreme | 755.00 | Crucial
 Portátil Yoga 520 | 559.00 | Lenovo
 Portátil Ideapd 320 | 444.00 | Lenovo
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 33: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 34: Incorrecto
```diff
--- 
+++ 
@@ -1,14 +1,12 @@
 fabricante | producto
+Seagate | Disco duro SATA3 1TB
+Crucial | Memoria RAM DDR4 8GB
+Samsung | Disco SSD 1 TB
+Gigabyte | GeForce GTX 1050Ti
+Crucial | GeForce GTX 1080 Xtreme
+Asus | Monitor 24 LED Full HD
 Asus | Monitor 27 LED Full HD
-Asus | Monitor 24 LED Full HD
+Lenovo | Portátil Yoga 520
 Lenovo | Portátil Ideapd 320
-Lenovo | Portátil Yoga 520
+Hewlett-Packard | Impresora HP Deskjet 3720
 Hewlett-Packard | Impresora HP Laserjet Pro M26nw
-Hewlett-Packard | Impresora HP Deskjet 3720
-Samsung | Disco SSD 1 TB
-Seagate | Disco duro SATA3 1TB
-Crucial | GeForce GTX 1080 Xtreme
-Crucial | Memoria RAM DDR4 8GB
-Gigabyte | GeForce GTX 1050Ti
-Huawei | NULL
-Xiaomi | NULL
```

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 35: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,8 @@
 fabricante
-Huawei
-Xiaomi
+Asus
+Lenovo
+Hewlett-Packard
+Samsung
+Seagate
+Crucial
+Gigabyte
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 36: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 37: Correcto

⏱ Tiempo: 0.40 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 38: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 39: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 40: Correcto

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 41: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

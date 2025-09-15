# 📥 Guía de Importación de Excel

## 📋 Formato Requerido

Tu archivo Excel debe tener **exactamente estas 4 hojas** con estos nombres:

### 🔹 Hoja 1: "Aportes"
| ID | Nombre | Monto Comprometido | Monto Entregado | Fecha | Forma de Pago | Observaciones | Saldo |
|----|--------|-------------------|-----------------|-------|---------------|---------------|-------|
| 1  | Juan Pérez | 50000 | 25000 | 2025-01-15 | transferencia | Pago parcial | 25000 |
| 2  | María García | 75000 | 75000 | 2025-01-20 | efectivo | Pago completo | 0 |

### 🔹 Hoja 2: "Gastos"
| ID | Categoría | Proveedor | Costo Estimado | Costo Real | Diferencia | Fecha Pago | Pagado Por | Observaciones |
|----|-----------|-----------|----------------|------------|------------|------------|------------|---------------|
| 1  | banquete | Restaurante ABC | 200000 | 180000 | 20000 | 2025-02-01 | Juan | Descuento aplicado |
| 2  | musica | DJ Party | 50000 | 55000 | -5000 | 2025-02-05 | María | Equipo adicional |

### 🔹 Hoja 3: "Tareas"
| ID | Tarea | Categoría | Responsable | Fecha Límite | Prioridad | Estado | Observaciones |
|----|-------|-----------|-------------|--------------|-----------|--------|---------------|
| 1  | Confirmar salón | planificacion | Carlos | 2025-01-30 | alta | completada | Ya confirmado |
| 2  | Comprar decoración | decoracion | Ana | 2025-02-10 | media | pendiente | Buscar presupuestos |

### 🔹 Hoja 4: "Invitados"
| ID | Nombre | Relación | Teléfono | Email | Estado | Acompañantes | Necesidades Especiales | Observaciones |
|----|--------|----------|----------|-------|--------|--------------|----------------------|---------------|
| 1  | Pedro López | familia | 88888888 | pedro@email.com | confirmado | 2 | Sin gluten | Traerá esposa e hijo |
| 2  | Laura Sánchez | amigos | 77777777 | laura@email.com | pendiente | 0 | Vegetariana | Confirmar esta semana |

## ⚠️ Notas Importantes

### ✅ **Lo que SÍ funciona:**
- Archivos .xlsx y .xls
- Nombres de hojas exactos: "Aportes", "Gastos", "Tareas", "Invitados"
- Encabezados en la primera fila (se ignoran al importar)
- Celdas vacías (se llenan automáticamente)

### ❌ **Lo que NO funciona:**
- Nombres de hojas diferentes
- Archivos corruptos
- Formatos que no sean Excel
- Caracteres especiales en los datos

## 🔄 **Proceso de Importación**

1. **Prepara tu archivo Excel** con el formato correcto
2. **Haz clic en "Cargar Excel a la Nube"**
3. **Selecciona tu archivo** (.xlsx o .xls)
4. **Espera el procesamiento** (puede tardar unos segundos)
5. **¡Listo!** Los datos se cargan directamente a Firebase

## 📊 **Datos Existentes**

⚠️ **IMPORTANTE**: Los datos importados se **AGREGAN** a los existentes, no los reemplazan.

Si quieres reemplazar todos los datos:
1. Elimina manualmente los datos existentes
2. Luego importa el nuevo archivo

## 🚀 **Ventajas de Importar a la Nube**

- ✅ **Sincronización inmediata** en todos los dispositivos
- ✅ **Respaldo automático** en Firebase
- ✅ **Acceso universal** desde cualquier navegador
- ✅ **Colaboración en tiempo real** con la familia

## 📱 **Después de Importar**

Los datos estarán disponibles inmediatamente en:
- Tu aplicación web actual
- Cualquier otro dispositivo que acceda a la app
- Todos los familiares que tengan acceso

¡Es como tener una base de datos profesional para tu fiesta! 🎉

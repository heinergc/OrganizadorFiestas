# 🎉 Organizador de Fiesta - 50 Aniversario

Una aplicación web completa para organizar fiestas de aniversario, desarrollada con HTML, CSS, JavaScript y SQLite (usando sql.js).

## ✨ Características

### 📱 **Totalmente Responsive**
- Funciona perfectamente en escritorio, tablets y móviles
- Diseño adaptativo que se ajusta a cualquier tamaño de pantalla
- Interfaz optimizada para pantallas táctiles

### 🗂️ **5 Módulos Principales**

1. **💰 Aportes de la Familia**
   - Registro de familiares y sus compromisos económicos
   - Control de montos comprometidos vs entregados
   - Cálculo automático de saldos pendientes
   - Diferentes formas de pago

2. **💸 Gastos de la Fiesta**
   - Categorización por tipo de gasto (banquete, música, decoración, etc.)
   - Comparación entre costos estimados y reales
   - Control de proveedores y fechas de pago
   - Cálculo automático de diferencias

3. **📝 Tareas**
   - Organización de tareas por categoría
   - Asignación de responsables
   - Control de prioridades (alta, media, baja)
   - Estados: pendiente, en progreso, completada
   - Filtros por estado

4. **👥 Invitados**
   - Lista completa de invitados
   - Control de confirmaciones
   - Gestión de acompañantes
   - Necesidades especiales (alergias, dietas)
   - Estadísticas en tiempo real

5. **📊 Resumen General**
   - Dashboard con estadísticas financieras
   - Balance general de la fiesta
   - Gráficos y análisis de datos

### 💾 **Gestión de Datos**

- **Almacenamiento Local**: Los datos se guardan en el navegador usando SQLite
- **Exportar Excel**: Descarga un archivo Excel con todos los datos organizados por pestañas
- **Importar Excel**: Sube un archivo Excel para cargar datos masivamente
- **Exportar/Importar Base de Datos**: Respaldo completo en formato SQLite
- **Limpieza de Datos**: Elimina registros vacíos o limpia toda la base de datos

## 🚀 Cómo Usar

### Instalación
1. Clona este repositorio o descarga los archivos
2. Abre `index.html` en cualquier navegador web moderno
3. ¡Listo! No necesita instalación adicional

### Uso desde GitHub Pages
1. Sube los archivos a un repositorio de GitHub
2. Activa GitHub Pages en la configuración del repositorio
3. Accede desde cualquier dispositivo con internet

### Primer Uso
1. La aplicación creará automáticamente la base de datos SQLite
2. Comienza agregando familiares en la pestaña "Aportes"
3. Registra los gastos estimados en "Gastos"
4. Organiza las tareas en "Tareas"
5. Gestiona la lista de invitados en "Invitados"
6. Revisa el progreso en "Resumen General"

### Importar Datos desde Excel
1. Haz clic en "📈 Importar Excel"
2. Selecciona un archivo Excel (.xlsx o .xls)
3. El archivo debe tener las siguientes hojas:
   - **"Aportes de la Familia"** con columnas: ID, Nombre del Integrante, Monto Comprometido, Monto Entregado, Fecha de Aporte, Forma de Pago, Observaciones, Saldo Pendiente
   - **"Gastos de la Fiesta"** con columnas: ID, Categoría, Proveedor, Costo Estimado, Costo Real, Diferencia, Fecha de Pago, Pagado Por, Observaciones
   - **"Tareas"** con columnas: ID, Tarea, Categoría, Responsable, Fecha Límite, Prioridad, Estado, Observaciones
   - **"Invitados"** con columnas: ID, Nombre Completo, Relación, Teléfono, Email, Estado, Acompañantes, Necesidades Especiales, Observaciones

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Diseño responsive con gradientes y animaciones
- **JavaScript ES6+**: Lógica de la aplicación
- **SQLite (sql.js)**: Base de datos en el navegador
- **SheetJS (xlsx)**: Manejo de archivos Excel
- **CDN**: Bibliotecas externas cargadas desde CDN

## 📱 Compatibilidad

- ✅ Chrome (versión 60+)
- ✅ Firefox (versión 60+)
- ✅ Safari (versión 12+)
- ✅ Edge (versión 79+)
- ✅ Móviles Android/iOS

## 🔒 Privacidad y Seguridad

- **Datos Locales**: Toda la información se almacena localmente en tu navegador
- **Sin Servidor**: No se envían datos a servidores externos
- **Offline**: Funciona sin conexión a internet después de la carga inicial
- **Respaldos**: Puedes exportar y respaldar tus datos cuando quieras

## 🎨 Personalización

El diseño utiliza gradientes y colores que puedes personalizar editando las variables CSS:

```css
/* Colores principales */
--color-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
--color-secondary: linear-gradient(135deg, #ffd89b 0%, #19547b 100%);
--color-accent: linear-gradient(135deg, #19547b 0%, #ffd89b 100%);
```

## 📝 Notas Importantes

1. **Respaldos**: Haz respaldos regulares usando "Exportar Base de Datos"
2. **Navegador**: Los datos se almacenan por navegador, cambiar de navegador requiere importar los datos
3. **Actualizaciones**: Antes de actualizar, exporta tus datos como respaldo
4. **Excel**: Para importar Excel, usa el mismo formato que genera la exportación

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras bugs o tienes ideas para mejorar:

1. Fork el repositorio
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Puedes usarlo libremente para eventos personales o comerciales.

## 🎊 ¡Disfruta Organizando tu Fiesta!

Esta aplicación está diseñada para hacer que la organización de tu fiesta de aniversario sea lo más sencilla y eficiente posible. ¡Que tengas un evento inolvidable! 🥳

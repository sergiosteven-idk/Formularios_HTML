# 🎨 Tipos de Inputs HTML

Guía completa de todos los tipos de `<input>` en HTML5 para formularios web.

## 📋 Tipos Principales

### **Texto y Contraseñas**
- `text`: Campo de texto normal
- `password`: Oculta caracteres
- `email`: Valida formato de correo
- `search`: Para búsquedas

### **Fechas y Tiempo**
- `date`: Selector de fecha
- `time`: Selector de hora
- `month`: Selecciona mes/año
- `week`: Selecciona semana

### **Selección**
- `checkbox`: Casillas múltiples
- `radio`: Opción única
- `color`: Selector de color
- `file`: Subir archivos

### **Botones**
- `submit`: Enviar formulario
- `reset`: Limpiar campos
- `button`: Botón genérico

### **Especiales**
- `range`: Barra deslizante
- `number`: Solo números
- `url`: Valida URLs web
- `hidden`: Campo invisible

## 💡 Ejemplo Básico
```html
<form>
  <label>Nombre:
    <input type="text" required>
  </label>
  
  <label>Contraseña:
    <input type="password" minlength="8">
  </label>
  
  <input type="submit" value="Enviar">
</form>
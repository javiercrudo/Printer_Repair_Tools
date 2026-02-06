# 📘 Manual de Usuario - Printer Repair Tool Pro
## Optimización y Reparación de Sistemas de Impresión

---

## 📋 Introducción
**Printer Repair Tool** es una herramienta profesional diseñada para diagnosticar y solucionar los problemas más comunes en impresoras locales y de red. Desde documentos atascados hasta conflictos de controladores (drivers) y errores de conexión USB.

---

## 🚀 Inicio Rápido: Reparación Automática (Recomendado)
Si su impresora no imprime, está "en pausa" o los documentos se quedan en espera, utilice la función estrella:

1. Presione el botón verde **⭐ REPARACIÓN AUTOMÁTICA (F5)**.
2. El programa realizará automáticamente tres pasos cruciales:
   - Detener el servicio de cola de impresión.
   - Eliminar documentos corruptos atascados.
   - Reiniciar el servicio para dejarlo operativo.
3. **Atajo de teclado:** Puede presionar la tecla **F5** en cualquier momento para iniciar este proceso.

---

## 🔧 Operaciones Básicas
Para un control manual detallado, dispone de tres funciones básicas:

1. **Detener Spooler:** Apaga el motor de impresión de Windows. Útil si el sistema está bloqueado.
2. **Limpiar Archivos Temporales:** Borra la memoria caché de las impresoras (identifica archivos .SPL y .SHD que traban la salida).
3. **Iniciar Spooler:** Vuelve a encender el sistema de impresión.

---

## 📊 Diagnóstico y Red
Si la impresora está encendida pero el equipo no la detecta:

*   **Escáner de Impresora de Red:** Busca automáticamente las impresoras IP configuradas en su PC y verifica si responden (hace un "ping"). Si aparece en **ROJO**, el problema es de conexión física o red.
*   **Carpeta Impresoras:** Acceso directo al Panel de Control de Windows.
*   **Ping Manual:** Permite probar una dirección IP específica.
*   **Administrador de Dispositivos:** Abre la ventana técnica de Windows para revisar controladores.
*   **Exportar Reporte:** Genera un archivo `.txt` detallado con todo lo realizado. **Es fundamental enviarlo a soporte técnico si el problema persiste.**

---

## ✨ Funciones Avanzadas (Mantenimiento Pro)
Estas funciones solo están disponibles en la versión **PROFESSIONAL**:

### 🧹 Limpieza Profunda de Drivers
Elimina controladores antiguos u "huérfanos" que ya no se usan. Esto previene conflictos de software y hace que el sistema de impresión responda más rápido.

### 🔌 Resetear Puertos USB
Si su impresora está conectada por cable pero aparece como "Desconectada", esta función limpia la caché de los puertos USB, obligando a Windows a reconocer la impresora de nuevo.
> **Nota:** Se recomienda desconectar y volver a conectar el cable USB después de usar esta función.

### 🚫 Forzar Cierre y Reiniciar
Úselo en casos extremos donde el botón normal de "Detener Spooler" no responda. Cierra el proceso de forma agresiva para destrabar el sistema.

### 🔄 Reiniciar Explorer
Refresca la barra de tareas y las ventanas de Windows. Útil si la cola de impresión no se actualiza visualmente.

---

## 🔐 Licencia y Estado
En la parte superior verá su estado actual:
*   **Verde:** Licencia vigente (más de 15 días).
*   **Naranja:** Próxima a vencer (7 a 15 días).
*   **Rojo:** Vencimiento inminente (menos de 7 días).

**Soporte Técnico:** Haga clic sobre el nombre del cliente para abrir un chat directo de WhatsApp con el soporte técnico.

---

## 🆘 Preguntas Frecuentes

**¿Por qué el programa pide permisos de administrador al abrir?**
Es necesario porque el programa interactúa con servicios críticos de Windows para poder reparar la impresión.

**¿El programa borra mis drivers instalados?**
No. La "Limpieza de Drivers" solo borra paquetes de controladores que NO están en uso y que son redundantes. Sus impresoras actuales instaladas seguirán funcionando.

**¿Qué hago si después de la Reparación Automática sigue sin imprimir?**
1. Verifique que la impresora tenga papel y tinta.
2. Use el "Escáner de Red" para ver si hay conexión.
3. Si es USB, use "Resetear Puertos USB".
4. Exportar el reporte y enviarlo a soporte.

---
*© 2026 - Printer Repair Tool - Soporte Técnico Especializado*

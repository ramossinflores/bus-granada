# 🚌 Bus Granada

> Horarios en tiempo real de las líneas **L-225** y **L-226** entre Granada y los pueblos del Poniente.  
> Instalable como app en el móvil — sin tiendas, sin cuentas, sin anuncios.

## ¿Qué es esto?

Una PWA (Progressive Web App) con los horarios completos de autobús, pensada para consultarse de un vistazo desde el móvil. Funciona sin conexión a internet una vez cargada.

**Líneas incluidas:**
- `L-225` Granada ↔ Pinos Puente
- `L-226` Granada ↔ Zujaira (vía Pinos Puente y Casanueva)

## Funcionalidades

- ⏱ **Próximo autobús** — muestra la salida más cercana y la cuenta atrás en minutos
- 🕐 **Horarios L–V, Sábado y Domingo** — cambia automáticamente según el día
- 🔵🟢 **Filtros por línea y dirección** — ida y vuelta, por separado o juntas
- 📴 **Funciona sin internet** — los datos están embebidos en el archivo
- 📱 **Instalable en el móvil** — se abre como una app nativa, sin barra del navegador


## Instalación en el móvil

**Android (Chrome)**
1. Abre la web en Chrome
2. Menú `⋮` → *Añadir a pantalla de inicio*

**iPhone (Safari)**
1. Abre la web en Safari
2. Botón compartir `↑` → *Añadir a pantalla de inicio*



## Uso en local

Si quieres modificarla y probarla en tu ordenador:

```bash
# Con Python (cualquier versión moderna)
python -m http.server 8080

# Luego abre en el navegador:
# http://localhost:8080
```


## Estructura

```
index.html   ← toda la app en un único archivo
README.md    ← esto
```

No hay dependencias, ni build, ni node_modules. Solo HTML, CSS y JavaScript puro 😁


## Datos y precisión

Los horarios están extraídos de los cuadros oficiales de la concesionaria. Pueden cambiar con la temporada o en festivos — comprueba siempre el horario oficial si el viaje es importante.


*Hecho con cariño para no perder el bus 🚌  ...    🏃🏃🏼*

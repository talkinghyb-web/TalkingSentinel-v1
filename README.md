# TALKING SENTINEL v1
### by Talking Studio Hyb · Lenux Studio · Talking Scripts

---

## Nuestro Servidor de Discord — Talking Studio Hyb

[![Discord](https://img.shields.io/badge/Unirse%20al%20servidor-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/invite/Su7WVJu8R)

Unete a **Talking Studio Hyb**, la comunidad oficial de Talking Sentinel.  
Ahi encontraras soporte directo, actualizaciones antes que nadie, anuncios de nuevas versiones y contacto con los creadores. Si usas el script, el servidor es el mejor sitio para estar.

> discord.com/invite/Su7WVJu8R

---

## Webs

| Nombre | Enlace |
|---|---|
| Talking Sentinel (web oficial) | https://talking-sentinel.base44.app |
| Discord — Talking Studio Hyb | https://discord.com/invite/Su7WVJu8R |

---

## Que es Talking Sentinel

**Talking Sentinel v1** es una suite de seguridad completa para Roblox desarrollada por Talking Studio Hyb y Lenux Studio. No es una sola herramienta, son cuatro sistemas en uno: ofuscador de scripts, detector de trampas en tiempo real, generador de anticheat para servidor y analizador de anticheats existentes. Todo dentro de una sola interfaz flotante que se abre encima del juego.

Compatible con cualquier executor, con Roblox Studio y con PC, movil y tablet. Detecta tu plataforma e idioma automaticamente al arrancar.

---

## Secciones principales

### `[~/OBF]` Ofuscador de Scripts

Pega tu codigo, elige los metodos que quieras y genera una version protegida. Puedes seleccionar uno, varios o todos los metodos a la vez.

**Metodos disponibles:**

| Metodo | Descripcion |
|---|---|
| Renombrar Variables | Reemplaza todos los nombres por cadenas aleatorias |
| Cifrar Strings | Convierte textos a secuencias de escape numericas |
| Flujo de Control | Ofusca estructuras if / while / for |
| Ofuscar Numeros | Representa numeros como operaciones aritmeticas |
| Eliminar Comentarios | Borra todos los comentarios del codigo |
| Comprimir Espacios | Elimina espacios e indentacion innecesaria |
| Ofuscar Constantes | Mueve constantes a tabla de lookup encriptada |
| **TKG v2** `NUEVO` `NUESTRO` | Codificacion casi-binaria con clave XOR aleatoria. El metodo mas potente de la suite |

> Al generar aparece un aviso: guarda siempre tu script original por si algun dia lo necesitas.

---

### `[~/CHT]` Detector de Cheats

Escanea a todos los jugadores durante **60 segundos**. Compara velocidades de movimiento, tiempo en el aire y saltos entre todos los presentes. Si tres jugadores se mueven normal y uno no, el sistema lo detecta, lo marca y genera un reporte automatico.

**Que detecta:**
- Speed hack (velocidad de caminar anormal)
- Fly hack (tiempo en el aire prolongado sin saltar)
- Jump hack (JumpPower modificado)
- Noclip (colision desactivada)
- Rastros de executor en el entorno local

Durante el escaneo muestra una barra de progreso y tips rotativos sobre como funcionan las detecciones.

**Al terminar** puedes expandir cada jugador para ver su informe completo con hora, nombre, estado y trampas detectadas. Lo puedes copiar en Espanol o Ingles.

---

### `[~/AC+]` Obtener Anticheat

Genera el script de anticheat listo para colocar en `ServerScriptService`. Lo copias, lo pegas en tu juego y funciona desde el servidor.

**Lo que incluye el anticheat:**

- Deteccion de speed hack por WalkSpeed directo
- Deteccion de speed hack relativo comparando con todos los jugadores
- Deteccion de fly hack por FloorMaterial Air prolongado y velocidad vertical
- Deteccion de jump power modificado
- Sistema de violaciones acumuladas: no kickea al primer frame
- Anti-lag: no penaliza items del juego que dan velocidad de forma legitima
- Kick automatico con mensaje personalizado al jugador
- Ban temporal con historial en memoria durante la sesion
- **Whitelist** de jugadores de confianza directamente en el script
- Logs detallados en Output del servidor con hora, jugador y tipo de trampa

> La whitelist esta comentada dentro del script copiado. Busca `-- WHITELIST` y agrega los UserIds de tus admins.

---

### `[~/ACZ]` Analizador de Anticheats

Escanea el entorno local del juego donde estas en **7 capas** para detectar si hay anticheats activos. No toca el servidor, todo es analisis en cliente. Al terminar te dice cuantos anticheats encontro y cuantas capas estan activas.

**Las 7 capas:**

| Capa | Que analiza |
|---|---|
| 1 | BindableEvents y BindableFunctions con nombres de anticheat |
| 2 | Scripts y ModuleScripts con nombres de seguridad |
| 3 | RemoteEvents de reporte, kick o ban |
| 4 | Valores de configuracion como MaxSpeed, MaxJump o Whitelist |
| 5 | Carpetas y configuraciones de sistemas de proteccion |
| 6 | Hooks en propiedades del Humanoid controladas externamente |
| 7 | Interceptores en FireServer y metodos de RemoteEvent modificados |

---

### `[~/SET]` Ajustes

- Cambiar entre tema **oscuro** y **claro**
- Cambiar idioma: **Espanol** o **Ingles**
- Copyright completo con creditos
- Boton para destruir el script y cerrar todo

---

## Compatibilidad

- PC, movil y tablet. La interfaz se adapta al tamano de pantalla automaticamente
- Compatible con Synapse X, KRNL, Fluxus y cualquier executor que soporte LocalScript
- Compatible con Roblox Studio
- Idiomas detectados automaticamente: Espanol, Ingles, Portugues, Frances, Aleman
- Interfaz flotante movible y minimizable con barra inferior semitransparente
- Pantalla de carga animada con barra de progreso, sistema de capas y tres puntos animados

---

## Creadores

| Nombre | Rol |
|---|---|
| **Lenux Play** | Desarrollo Principal y UI |
| **Lenux Studio** | Arquitectura del Sistema |
| **Talking Scripts** | Sistemas de Deteccion |
| **Talking Hyb** | Motor de Ofuscacion TKG v2 |

---

## Copyright

Copyright (c) 2024 Talking Scripts & Lenux Studio. Todos los derechos reservados.

Queda prohibida la copia, redistribucion o modificacion de este script sin el consentimiento expreso de los autores. El nombre Talking Sentinel, el motor TKG v2 y todos los sistemas de deteccion son propiedad de sus creadores.

---

*Proxima actualizacion: v1.1...*

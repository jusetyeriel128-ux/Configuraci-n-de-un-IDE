###REPORTE DE CONFIGURACION DEL IDE VISUAL STUDIO CORE

**Alumno:** Jimenez Lagunas Juset Yeriel

**Grupo:** 2DSM-G3

**Fecha:** 19/01/2026

**Unidad:** 1°


## 1. IDE seleccionado
- IDE: Visual Studio Code
- Versión: 1.108.0
- Sistema operativo: Windows 11 Pro, Versión 23H2
  



## 2. Justificación
- Criterio 1: Es gratuito y de código abierto, accesible para cualquier estudiante sin costo adicional y con soporte comunitario constante
- Criterio 2: Multiplataforma, compatible con Windows, Linux y macOS para trabajar en diferentes equipos sin problemas de compatibilidad
- Criterio 3: Cuenta con amplias extensiones que permiten adaptarlo a lenguajes de programación de la materia como Python, C++ y JavaScript



## 3. Requisitos previos
- Requisito 1: Conexión a internet estable para descargar el instalador y extensiones necesarias
- Requisito 2: Al menos 200 MB de espacio libre en disco duro (se recomiendan 500 MB para herramientas adicionales)
- Permisos: Acceso con privilegios de administrador para realizar la instalación del software y configurar rutas del sistema



## 4. Instalación (paso a paso)
1. Acceder a la página oficial de descarga: https://code.visualstudio.com/Download
   
2. Seleccionar la opción de descarga para Windows x64 (User Installer) y guardar el archivo instalador en la carpeta "Documentos"
   
3. Ejecutar el archivo instalador, aceptar el acuerdo de licencia y seleccionar la ruta de instalación predeterminada: `C:\Users\Juset Yeri\AppData\Local\Programs\Microsoft VS Code`
   
4. Marcar opciones adicionales: "Agregar VS Code al PATH", "Registrar como editor de archivos admitidos" y "Crear acceso directo en el menú Inicio"
   
5. Iniciar la instalación y esperar a su finalización, luego marcar la opción para lanzar VS Code


## 4.1 Verificación
- ¿Cómo comprobé que funciona? Al iniciar Visual Studio Code, la interfaz principal se carga correctamente, se puede acceder a todas las secciones del menú y se puede crear/abrir archivos de código sin errores



## 5. Configuración inicial
### 5.1 Ajustes básicos
- Tamaño de fuente: 14 píxeles (configurado en la sección "Editor: Font Size")
- Auto guardado: Desactivado ("off" - configurado en la sección "Files: Auto Save")
- Tema de color: Tema oscuro "Dark+" predeterminado (seleccionado en la sección "Workbench: Color Theme")
- Idioma del IDE: Inglés (opción disponible para cambiar a español con el paquete de idioma correspondiente)



### 5.2 Extensiones / plugins
| Extensión/Plugin | Función | Por qué |
|------------------|---------|---------|
| Python           | Resaltado de sintaxis, depuración paso a paso, autocompletado de código y verificación de errores | Necesaria para desarrollar en Python, lenguaje principal utilizado en la materia de programación estructurada |
| Code Runner      | Ejecutar código de múltiples lenguajes directamente desde el editor con un solo clic en el icono de ejecución | Facilita probar fragmentos de código de forma rápida sin necesidad de abrir la terminal externamente |
| Spanish Language Pack | Traduce toda la interfaz de VS Code (menús, opciones, mensajes) al español | Mejora la comprensión y manejo del entorno para estudiantes de habla hispana, reduciendo barreras de lenguaje |



### 5.3 Herramientas adicionales (si aplica)
- Compilador/intérprete: Python 3.11.4 (instalado en la ruta `C:\Python311`, con variables de entorno configuradas)
- Prueba: Se verificó el funcionamiento del intérprete ejecutando el comando `python --version` en la terminal integrada de VS Code, obteniendo la versión correcta



## 6. Prueba final (mini-ejercicio)
```python
# Programa de prueba para verificar el entorno configurado completamente
# Actividad 3 - Verificación final del IDE Visual Studio Code

print("=" * 70)
print("                    PRUEBA FINAL DE ENTORNO DE DESARROLLO                    ")
print("=" * 70)
print("¡Hola, mundo!")
print("Visual Studio Code está funcionando correctamente")
print("Intérprete de Python 3.11.4 activado exitosamente")
print("=" * 70)
```
## 7. Conclusiones
Visual Studio Code se ha demostrado como una herramienta altamente adecuada para estudiantes de programación, ya que combina accesibilidad gratuita, funcionalidad completa y compatibilidad multiplataforma. 

El proceso de instalación resultó ser sencillo y bien estructurado, con opciones que se adaptan a diferentes necesidades y sistemas operativos. La configuración inicial, incluyendo ajustes básicos de visualización y la instalación de extensiones específicas como Python, Code Runner y Spanish Language Pack, optimiza significativamente el flujo de trabajo al trabajar con lenguajes de programación de la materia.

Un entorno de desarrollo integrado bien configurado no solo reduce el tiempo dedicado a tareas auxiliares, sino que también minimiza errores al concentrar todas las herramientas necesarias (editor, depurador, intérprete) en un solo espacio organizado. Además, su compatibilidad con Git y plataformas como GitHub facilita el control de versiones y la correcta entrega de proyectos académicos.



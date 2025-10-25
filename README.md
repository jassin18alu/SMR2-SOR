# SMR2-SOR


# Práctica de Sistemas Operativos

**Autor:** [Jashanpreet Singh]  
*Fecha:* 25 de octubre de 2025  
[Enlace al repositorio de GitHub](https://github.com/tu-usuario/tu-repo) (reemplaza con tu enlace real)

## Sintaxis y Formato Básico de Markdown

Según el manual de GitHub: [Sintaxis básica de escritura y formato](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

Aquí demuestro formatos simples y sofisticados:

- **Negrita**: Usa **doble asterisco** para resaltar texto importante.
- *Cursiva*: Usa *un asterisco* para enfatizar.
- Listas no ordenadas:
  - Elemento 1
  - Elemento 2
- Listas ordenadas:
  1. Paso uno
  2. Paso dos
- Código inline: Usa `comando` para resaltar comandos como `wsl --install`.
- Bloque de código:


echo "Hola mundo"



- Citas:
> "Crear formatos sofisticados para tu prosa y código en GitHub con sintaxis simple." - Manual de GitHub.
- Enlaces: [Manual de Diagramas](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams).
- Tablas (formato sofisticado):
| Tarea | Descripción |
|-------|-------------|
| Modo Dios | Acceso rápido a configuraciones. |
| BalenaEtcher | Crear USB booteable. |

GitHub soporta diagramas con Mermaid para conveying information through charts and graphs.

## Explicación y Pasos de Cada Tarea

A continuación, detallo cada tarea con explicación, pasos, comandos/códigos y un diagrama Mermaid que representa los pasos (creado en [mermaid.live](https://mermaid.live/)). Usé flowcharts para visualizar el flujo de pasos.

### Tarea 1: Hardware – Win10 (Modo Dios)

**Explicación:** El "Modo Dios" (God Mode) es una carpeta especial en Windows 10 que da acceso a más de 200 herramientas y configuraciones del sistema en un solo lugar. No requiere descarga, solo crear una carpeta con un nombre específico.

**Pasos para Iniciarlo (Crear la Carpeta):**
1. Haz clic derecho en el escritorio.
2. Selecciona "Nuevo" > "Carpeta".
3. Renombra la carpeta con el siguiente código: `GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}`.
4. Presiona Enter. El icono cambiará a un panel de control.

**Código/Comando:** El "código" es el nombre de la carpeta: `GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}`.

**Diagrama Mermaid de Pasos para Iniciarlo:**




```mermaid
flowchart TD
  A[Haz clic derecho en escritorio] --> B[Selecciona Nuevo > Carpeta]
  B --> C["Renombra a GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}"]
  C --> D[Presiona Enter]
  D --> E[Icono cambia, carpeta lista]








```mermaid
flowchart TD
  A[Haz clic derecho en escritorio] --> B[Selecciona Nuevo > Carpeta]
  B --> C[Renombra a GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}]
  C --> D[Presiona Enter]
  D --> E[Icono cambia, carpeta lista]







flowchart TD
    A[Abre la carpeta GodMode] --> B[Navega categorías ej. Administración]
    B --> C[Selecciona herramienta ej. Admin de Dispositivos]
    C --> D[Usa la herramienta]
    D --> E[Vuelve a carpeta para más opciones]








flowchart TD
    A[Descarga e instala Etcher] --> B[Descarga ISO ej. Linux Mint]
    B --> C[Inserta USB]
    C --> D[Abre Etcher y selecciona ISO]
    D --> E[Selecciona USB]
    E --> F[Haz clic en Flash]










flowchart TD
    A[Abre PowerShell como admin] --> B[Ejecuta wsl --install]
    B --> C[Reinicia PC]
    C --> D[Configura usuario en terminal Linux]






flowchart TD
    A[Verifica WSL instalado] --> B[Descarga instalador .exe]
    B --> C[Ejecuta instalador]
    C --> D[Abre Docker y verifica con docker --version]





flowchart TD
    A[Descarga instalador desde sitio] --> B[Ejecuta .exe como admin]
    B --> C[Sigue wizard]
    C --> D[Reinicia desde acceso directo]




flowchart TD
    A[Descarga instalador desde sitio] --> B[Ejecuta .exe como admin]
    B --> C[Sigue wizard]
    C --> D[Reinicia desde acceso directo]







graph TD
    Start[Inicio: Configura Windows] --> T1[Tarea 1: Activa Modo Dios]
    T1 --> T2[Tarea 2: Instala BalenaEtcher y crea USB]
    T2 --> T3[Tarea 3: Instala WSL]
    T3 --> T4[Tarea 4: Instala Docker Desktop]
    T4 --> T5[Tarea 5: Instala LliuWin]
    T5 --> End[Fin: Entornos listos]




``` mermaid

# Simulador Enigma Educativo

Simulador interactivo de la máquina **Enigma I** militar alemana (3 rotores + reflector + clavijero), pensado para el aula de Tecnología. Es un único archivo HTML autónomo: **funciona sin conexión** con solo abrirlo en el navegador, sin librerías externas ni instalación.

## 🔗 Demo en vivo

Una vez activado GitHub Pages:

> https://susanaoubina.github.io/enigma/simulador-enigma-educativo.html

## ✨ Características

- **Cableado histórico real** de los rotores I–V, la rueda de entrada (ETW) y los reflectores B y C.
- **Teclado y lámparas** con la distribución alemana QWERTZ, usables con ratón o teclado físico.
- **Clavijero (Steckerbrett)** con hasta 10 cables, dibujados sobre las clavijas.
- **Rotores animados** con el mecanismo real, incluido el **doble paso** (double-stepping).
- **Visualización del recorrido eléctrico** paso a paso, mostrando la letra en cada etapa, con control de velocidad.
- **Elección de 3 rotores entre 5** (60 órdenes posibles) sin repetición, Ringstellung y Grundstellung configurables.
- **Clave del día (Tagesschlüssel)** y **clave del mensaje (Spruchschlüssel)** separadas, como en la realidad.
- **Cifrado y descifrado recíproco** (gracias al reflector) y procesado de mensajes completos.
- **Conversor de números y signos** al formato Enigma (números deletreados, X como separador, transliteración de acentos y Ä/Ö/Ü/ß).
- **Tutorial interactivo** de rol: el alumno cifra y descifra un mensaje real siguiendo el procedimiento histórico del indicador doble, y descubre el fallo que permitió romper Enigma.
- Botón de **reinicio total** y panel didáctico con la explicación de cada parte.

## 📂 Contenido del repositorio

| Archivo | Descripción |
|---------|-------------|
| `simulador-enigma-educativo.html` | El simulador completo (abrir en el navegador). |
| `Ficha_Enigma_alumno.pdf` | Ficha imprimible del alumno con la actividad guiada y la hoja de soluciones para el profesorado. |
| `README.md` | Este archivo. |

## 🎓 Cómo usarlo en clase

1. Abre el simulador (enlace de la demo o el archivo `.html`).
2. Configura una **clave del día** (rotores, anillos, reflector y cables) o pulsa «Generar clave del día».
3. Elige una **clave del mensaje** de 3 letras (posición inicial de los rotores).
4. Escribe el mensaje y ciframos; para descifrar, aplica la misma clave y procesa el texto cifrado.

Para una comprobación rápida: con rotores I-II-III, reflector B, anillos AAA y posición AAA, al teclear `AAAAA` debe salir `BDZGO`.

La **ficha en PDF** propone una misión completa (cifrar y descifrar un mensaje real) y trae la solución para el docente.

## 👩‍🏫 Créditos

Creado por **Susana Oubiña Falcón** y Claude Opus 4.8 · Material educativo para el aula de Tecnología o la materia de IA para la Sociedad

## 📝 Nota técnica

Todo el código (HTML + CSS + JavaScript) está en un solo archivo, comentado en español para poder revisarlo o modificarlo con el alumnado. No requiere conexión a internet y funciona en Chrome, Firefox y Edge.

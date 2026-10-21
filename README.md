# 🌼 Concurso de Altares de Muertos «La Magia de Recordar»
### Grupo Bacis — Capital Humano (R.H. Unidad)

Plataforma web oficial e interactiva para el registro de equipos, asignación de premiaciones y galería fotográfica de ofrendas para el **Tradicional Concurso de Altares de Muertos** de Grupo Bacis.

---

## 🌟 Características Principales

1. **Efecto de Entrada Cinematográfico ("Altar Minero"):**
   - Ilustración interactiva en SVG de un altar tradicional de 3 niveles enmarcado en el socavón minero de Grupo Bacis.
   - Veladoras con flamas animadas, casco minero con haz de luz, copal, pico y pala cruzados y lluvia de pétalos de flor de cempasúchil sobre canvas HTML5.
   - Botón para reproducir la intro en cualquier momento (ideal para proyectores en la ceremonia del 31 de octubre).

2. **Podio y Premiación Oficial:**
   - 🥇 **1er Lugar:** $3,000 MXN
   - 🥈 **2do Lugar:** $2,000 MXN
   - 🥉 **3er Lugar:** $1,500 MXN
   - Asignación dinámica de ganadores con lluvia de cempasúchil y actualización en tiempo real del podio.

3. **Registro Oficial de Equipos:**
   - Mismos campos oficiales de Capital Humano:
     - 01. Fecha de inscripción
     - 02. Nombre del líder
     - 03. Departamento participante
     - 04. Nombre del equipo / Altar
     - Folio RH autogenerado (`RH-ALTAR-XX`)
     - Solicitud de materiales (Sí / No) con enlaces directos a Recursos Humanos
   - Subida múltiple de fotografías de altares con compresión automática en cliente.

4. **Persistencia de Datos (Triple Capa):**
   - **IndexedDB:** Guarda decenas de fotos en alta resolución localmente sin límite de tamaño.
   - **LocalStorage:** Respaldo rápido en el navegador.
   - **datos_equipos.json:** Permite exportar e importar datos para sincronizarlos con GitHub Pages y compartirlos con toda la empresa.

5. **Recursos Oficiales Integrados:**
   - Descarga directa del **Formato Oficial en PDF Editable** (`Formato_Inscripcion_Concurso_Altares_Muertos_Grupo_Bacis.pdf`).
   - Visor modal del **Cartel Oficial de la Convocatoria** (`cartel_oficial.png`).
   - Logotipo oficial de **Grupo Bacis** (`logo_bacis.png`).

---

## 🚀 Publicación en GitHub Pages

Para publicar este proyecto y que cualquier persona pueda consultarlo desde su celular o computadora:

### Opción A: Desde GitHub Desktop (Recomendada)
1. Abre **GitHub Desktop**.
2. Ve al menú `File` > `Add Local Repository...`.
3. Selecciona esta carpeta:
   `C:\Users\jesus.martinez\OneDrive - Grupo Minero Bacis\Escritorio\Recursos Humanos\Circulares\concurso-altares-bacis`
4. Haz clic en **Publish repository** (puedes dejarlo como público o de tu cuenta `kitus1000`).
5. En GitHub (web), entra al repositorio, ve a **Settings** > **Pages** y en **Branch** elige `main` (o `master`) y guarda.
6. ¡Listo! Tu enlace será:
   `https://kitus1000.github.io/concurso-altares-bacis/`

### Opción B: Por línea de comandos
```bash
git add .
git commit -m "Publicación oficial: Concurso de Altares de Muertos Grupo Bacis"
git branch -M main
git remote add origin https://github.com/kitus1000/concurso-altares-bacis.git
git push -u origin main
```

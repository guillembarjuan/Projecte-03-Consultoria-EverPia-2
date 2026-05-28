# P03 – Rèplica web

## 📌 Descripció del producte

Aquest producte consisteix en la **replicació en local** d’una web corporativa real feta amb WordPress: `davidperalvarez.com`. L’encàrrec prové d’un client exigent d’EverPia, que vol analitzar l’estructura, l’arquitectura de continguts i les bones pràctiques de desenvolupament d’aquest lloc professional.

L’objectiu no és només copiar l’estètica, sinó entendre com està construïda la web: menús, jerarquia de pàgines, estils, tipografies, colors i experiència d’usuari (UX). Aquesta activitat s’emmarca dins l’escenari **“Sobreviure en una empresa IT”**, on es valora la capacitat d’adaptació a webs complexes i ben dissenyades.

---

## 🎯 Objectius específics

- Instal·lar un nou lloc WordPress a l’entorn local **WP Local** amb el nom `replica_guillem` (seguint el patró establert).
- Analitzar la web original (`davidperalvarez.com`) per identificar-ne l’estructura, el mapa del lloc (sitemap XML), les pàgines, menús i submenús.
- Replicar totes les pàgines principals que apareixen al sitemap, incloent:
  - Inici
  - Sobre mí
  - Academia básica
  - Mantenimiento para academias online
  - Consultoría para academias online
  - Proyectos que he realizado
  - Descarga
  - Contactar
  - Política de privacitat, cookies i condicions d’ús.
- Reproduir els continguts (text, imatges, vídeos, seccions) amb el màxim de fidelitat possible, utilitzant text copiat de l’original o *Lorem Ipsum* quan no sigui possible, però mantenint títols, seccions i estructura visual.
- Configurar el lloc replicat perquè tingui:
  - Pàgina d’inici estàtica.
  - Menú principal amb submenús (igual que l’original).
  - Enllaços permanents amigables.
  - Tema visual que s’assembli al màxim a l’original (provant diferents temes fins a trobar-ne un d’adequat).
  - Paràmetres generals (idioma, zona horària, nom del lloc).

---

## 🛠️ Eines utilitzades

- **WP Local** – per crear l’entorn de proves WordPress local.
- **WordPress** – CMS per a la replicació.
- **Kadence Blocks** – plugin recomanat per ampliar els blocs de Gutenberg i facilitar la creació de pàgines complexes.
- **WP Theme Detector** (wpthemedetector.com) – per esbrinar quin tema utilitza la web original.
- **Image Color Picker** (imagecolorpicker.com) – per identificar el color exacte de la paleta original.
- **MyFonts** – per identificar les fonts utilitzades.
- **Sitemap XML** (`/page-sitemap.xml`) – per obtenir totes les URL de la web original.

---

## 🔧 Passos realitzats

1. **Creació del nou lloc a WP Local** amb el nom `replica_guillem`.
2. **Exploració de la web original** per entendre l’estructura i disseny.
3. **Identificació del tema i plugins** mitjançant les eines online.
4. **Instal·lació d’un tema similar** i configuració bàsica.
5. **Instal·lació de Kadence Blocks** per disposar de blocs avançats.
6. **Creació de totes les pàgines** del sitemap, copiant o adaptant continguts.
7. **Configuració de la pàgina d’inici estàtica** (Configuració → Lectura).
8. **Creació del menú principal** amb els ítems i submenús igual que l’original (Apariència → Menús).
9. **Ajust de colors, tipografies i estils** mitjançant el personalitzador del tema.
10. **Verificació de la navegació** i enllaços relatius/absoluts.
11. **Documentació del procés** al repositori GitHub.

---

## 📁 Contingut del producte

- Carpeta `producte03/` dins del repositori `Projecte-03-Consultoria-EverPia-2`.
- Aquest fitxer `README.md` amb la descripció detallada.
- Captures de pantalla de la rèplica comparada amb l’original (dins `img/`).
- (Opcional) Exportació de la web replicada en format `.zip` o referència a WP Local.

---

## 💡 Aprenentatges clau

- **Anàlisi de webs professionals:** capacitat de desmuntar una web real per entendre’n l’estructura, el disseny i el funcionament.
- **Replicació manual amb WordPress:** habilitat per recrear continguts, menús i estils sense eines automàtiques d’importació.
- **Ús de plugins de blocs:** Kadence Blocks permet maquetacions més flexibles i properes al disseny original.
- **Eines externes:** detectar temes, colors i fonts és una competència molt útil per a futurs projectes de manteniment o redisseny web.
- **Atenció al detall:** la fidelitat visual i l’experiència d’usuari (UX) són clau per satisfer les exigències d’un client professional.

---

## 👤 Autor

**Guillem Barjuan Alonso** – CFGM SMX  
Projecte 03 – Consultoria EverPia 2  
Data de realització: segon trimestre del curs 2025-2026

---

*Aquest producte demostra la capacitat d’analitzar i replicar una web real, una habilitat fonamental per a qualsevol tècnic de sistemes que hagi de mantenir o modificar llocs existents per a clients.*

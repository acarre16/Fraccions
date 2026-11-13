# 🍕 El Taller de les Fraccions — 5è de Primària
### Fitxa Educativa Interactiva de Matemàtiques

![Nivell Educatiu](https://img.shields.io/badge/Nivell-5%C3%A8%20de%20Prim%C3%A0ria-orange?style=for-the-badge)
![Àrea](https://img.shields.io/badge/%C3%80rea-Matem%C3%A0tiques-blue?style=for-the-badge)
![Idioma](https://img.shields.io/badge/Idioma-Catal%C3%A0-red?style=for-the-badge)
![Tecnologia](https://img.shields.io/badge/HTML5%20%7C%20Tailwind%20CSS%20%7C%20JS-Vanilla-green?style=for-the-badge)

**El Taller de les Fraccions** és una aplicació web educativa i interactiva dissenyada per a l'alumnat de **5è d'Educació Primària** (Cicle Superior). Amb un disseny visual clar, manipulatiu i gamificat, permet comprendre el concepte de fracció, practicar la seva representació gràfica, comparar-les i resoldre operacions tant amb igual com amb diferent denominador.

---

## ✨ Estructura i Continguts de la Fitxa

L'aplicació s'organitza en **7 pestanyes progressives** amb un marcador global de **29 punts**, barra de progrés i generació aleatòria de nous exercicis:

### 1. 🔬 Explora i comprèn (Laboratori Visual)
* Controls interactius per modificar el **numerador** i el **denominador** (de 1 a 12).
* Representació gràfica simultània en **model circular** (pizza/pastís) i **model rectangular** (rajola de xocolata).
* **Lectura normativa en català** en temps real i classificació automàtica (*fracció pròpia, igual a la unitat, impròpia o aparent*).
* Panell desplegable amb exemples visuals de **fraccions equivalents** (`1/2 = 2/4 = 4/8`, `1/3 = 2/6 = 3/9`, `2/3 = 4/6 = 6/9`).

### 2. 🎨 Pinta i identifica (5 exercicis)
* **Exercicis de pintar:** L'alumne/a fa clic directament sobre les porcions d'un cercle o d'una barra per representar la fracció demanada.
* **Exercicis d'identificar:** Observació d'una figura ja pintada per escriure'n el numerador i el denominador corresponents.

### 3. ⚖️ Compara i ordena (6 exercicis)
* **5 parelles de comparació:** Triar el signe correcte (`<`, `=`, `>`) entre fraccions amb igual denominador, igual numerador o equivalents, amb un botó desplegable **«Veure dibuix»** com a pista visual.
* **1 repte d'ordenació:** Ordenar 4 fraccions de menor a major fent clic en l'ordre adequat.

### 4. 🧮 Igual denominador i quantitat (8 exercicis)
* **Part A — Fracció d'una quantitat (4 exercicis):** Càlcul guiat amb agrupacions visuals de fitxes de colors per entendre la divisió pel denominador i la multiplicació pel numerador.
* **Part B — Sumes i restes d'igual denominador (4 exercicis):** Pràctica de càlcul directe amb retroacció explicativa.

### 5. 🚀 Operacions amb diferent denominador (Explicació + 6 exercicis)
* **Explicació visual pas a pas:**
  * **Sumar amb diferent denominador (`+`):** Cerca del denominador comú, conversió a fraccions equivalents i suma de numeradors amb barres subdividides (`1/2 + 1/3 = 3/6 + 2/6 = 5/6`).
  * **Restar amb diferent denominador (`−`):** Procediment equivalent il·lustrat visualment (`3/4 − 1/2 = 3/4 − 2/4 = 1/4`).
  * **Multiplicar fraccions (`×`):** Multiplicació directa en línia recta (numerador × numerador i denominador × denominador) representada mitjançant un **model d'àrea en quadrícula** (`1/2 × 2/3 = 2/6`).
* **Calculadora Visual Pas a Pas:** Eina interactiva per escollir dues fraccions i l'operació (`+`, `−` o `×`) i visualitzar-ne tot el desenvolupament gràfic i numèric.
* **Pràctica guiada (6 exercicis):** 2 sumes i 2 restes amb caselles per completar les fraccions equivalents intermèdies i 2 multiplicacions, amb pistes desplegables.

### 6. 🧩 Problemes de la vida quotidiana (4 problemes)
* Situacions contextualitzades amb suport visual i explicació detallada de la resolució en validar cada resposta.

### 7. 🏆 Resum i Diploma Final
* Informe detallat d'encerts per blocs i valoració pedagògica personalitzada.
* Camp editable per introduir el nom de l'alumne/a i estils optimitzats (`@media print`) per **imprimir o desar el diploma en PDF**.

---

## 🚀 Instal·lació i Ús

El projecte està contingut en un **únic arxiu HTML autocontingut** (`fitxa_fraccions_5e.html`), sense necessitat d'instal·lar cap dependència ni servidor.

1. **Clona o descarrega el repositori:**
   ```bash
   git clone https://github.com/el-teu-usuari/taller-fraccions-5e.git
   ```
2. **Obre l'activitat:**
   Fes doble clic sobre `fitxa_fraccions_5e.html` per obrir-lo a qualsevol navegador web modern (Chrome, Firefox, Safari, Edge).
3. **Publicació a GitHub Pages (Opcional):**
   Pots allotjar la fitxa en línia gratuïtament activant **GitHub Pages** a `Settings > Pages` seleccionant la branca principal (`main`).

---

## 🛠️ Tecnologies Utilitzades

* **HTML5 Semàntic** i gràfics vectorials **SVG** generats dinàmicament per als models circulars.
* **Tailwind CSS** (via CDN) per a una interfície *responsive* adaptada a ordinadors, tauletes i pissarres digitals d'aula.
* **JavaScript (ES6+)** pur per a la generació aleatòria d'exercicis, càlcul de mínim comú múltiple, validació pas a pas i seguiment del progrés.
* **Google Fonts** (`Fredoka` i `Nunito`) per a una tipografia amigable, clara i llegible a Primària.

---

## 📄 Llicència

Aquest recurs es comparteix com a **Material Educatiu Obert** per a ús escolar, docent i familiar.
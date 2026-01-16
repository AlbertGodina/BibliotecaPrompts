# 📚 Biblioteca de Prompts

Una aplicació web senzilla per gestionar i organitzar els teus prompts per a IAG i VibeCoding.

## ✨ Característiques

- ✅ **CRUD Complet**: Afegir, editar i eliminar prompts
- 🔍 **Cerca avançada**: Cerca per títol, descripció o contingut
- 🏷️ **Sistema d'etiquetes**: Organitza i filtra per categories
- 📋 **Copiar ràpid**: Botó per copiar prompts al portapapers
- 💾 **Exportar/Importar**: Fes còpies de seguretat en format JSON
- 📱 **Responsive**: Funciona perfectament en mòbil i escriptori
- 🎨 **Interfície moderna**: Disseny atractiu i fàcil d'usar

## 🚀 Com desplegar a GitHub Pages

### Pas 1: Crear el repositori

1. Ves a [GitHub](https://github.com) i inicia sessió
2. Clica "New repository" (botó verd)
3. Posa un nom al repositori (ex: `biblioteca-prompts`)
4. Marca'l com a **Public** o **Private** (com prefereixis)
5. Clica "Create repository"

### Pas 2: Pujar els fitxers

1. A la pàgina del nou repositori, clica "uploading an existing file"
2. Arrossega el fitxer `index.html` a la zona indicada
3. Escriu un missatge de commit (ex: "Primera versió de la biblioteca")
4. Clica "Commit changes"

### Pas 3: Activar GitHub Pages

1. Al teu repositori, ves a **Settings** (configuració)
2. Al menú lateral esquerre, clica **Pages**
3. A "Source", selecciona **Deploy from a branch**
4. A "Branch", selecciona **main** i la carpeta **/ (root)**
5. Clica **Save**

### Pas 4: Accedir a l'aplicació

Després d'uns minuts, la teva aplicació estarà disponible a:
```
https://EL-TEU-USUARI.github.io/biblioteca-prompts/
```

(Substitueix `EL-TEU-USUARI` pel teu nom d'usuari de GitHub)

## 📖 Com utilitzar l'aplicació

### Afegir un nou prompt

1. Clica el botó **"➕ Afegir Prompt"**
2. Omple els camps:
   - **Títol**: Nom descriptiu del prompt
   - **Descripció**: Breu explicació del què fa
   - **Text del Prompt**: El prompt complet
   - **Etiquetes**: Categories separades per comes (ex: `matemàtiques, ESO, quiz`)
3. Clica **"Crear"**

### Cercar i filtrar

- Utilitza la barra de cerca per trobar prompts per text
- Clica les etiquetes per filtrar per categoria
- Combina cerca i filtres per resultats més precisos

### Editar o eliminar

- Cada targeta de prompt té botons per **Editar** o **Eliminar**
- Confirma l'eliminació abans que es faci efectiva

### Copiar un prompt

- Clica el botó **"📋 Copiar"** de qualsevol prompt
- El text es copiarà automàticament al portapapers

### Exportar i importar

- **Exportar**: Descarrega tots els teus prompts en format JSON (còpia de seguretat)
- **Importar**: Carrega prompts des d'un fitxer JSON exportat prèviament

## 💾 Emmagatzematge

Les dades es guarden localment al teu navegador utilitzant `localStorage`. Això significa:

- ✅ No necessites compte ni backend
- ✅ Les dades són privades i només accessibles des del teu navegador
- ⚠️ Si canvies de navegador o esborres les dades del navegador, perdràs els prompts
- 💡 **Solució**: Utilitza la funció d'exportar regularment per fer còpies de seguretat

## 🔧 Personalització

Si vols personalitzar l'aplicació (colors, estils, funcionalitats):

1. Descarrega el fitxer `index.html`
2. Obre'l amb un editor de text
3. Modifica el CSS (dins de `<style>`) o el JavaScript (dins de `<script>`)
4. Puja el fitxer modificat al repositori

## 📝 Exemples d'ús

### Exemple 1: Prompt per a activitat educativa
- **Títol**: Quiz interactiu de ciències
- **Descripció**: Crea un quiz amb preguntes de diversos nivells
- **Etiquetes**: `ciències, ESO, quiz, interactiu`

### Exemple 2: Prompt per a VibeCoding
- **Títol**: Joc de memòria personalitzable
- **Descripció**: Aplicació de memòria amb diferents temes
- **Etiquetes**: `joc, primària, memòria, vibecoding`

## 🆘 Ajuda i suport

Si tens problemes:

1. Assegura't que el fitxer `index.html` està a l'arrel del repositori
2. Comprova que GitHub Pages està activat a la configuració
3. Espera uns minuts després d'activar GitHub Pages
4. Prova obrir l'aplicació en mode incògnit per evitar problemes de cache

## 📄 Llicència

Aquest projecte és de lliure ús per a finalitats personals i educatives.

---

Creat amb ❤️ per a docents que utilitzen IAG i VibeCoding

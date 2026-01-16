# 📚 Biblioteca de Prompts

Una aplicació web senzilla per gestionar i organitzar prompts per a IAG i VibeCoding.

## ✨ Característiques

- ✅ **CRUD Complet**: Afegir, editar i eliminar prompts
- 🔍 **Cerca avançada**: Cerca per títol, descripció o contingut
- 🏷️ **Sistema d'etiquetes**: Organitza i filtra per categories
- 📋 **Copiar ràpid**: Botó per copiar prompts al portapapers
- 💾 **Exportar/Importar**: Fes còpies de seguretat en format JSON
- 📱 **Responsive**: Funciona perfectament en mòbil i escriptori
- 🎨 **Interfície moderna**: Disseny atractiu i fàcil d'usar


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

## 📄 Llicència

Aquest projecte és de lliure ús per a finalitats personals i educatives.

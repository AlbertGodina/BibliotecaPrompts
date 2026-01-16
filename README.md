# 📚 Biblioteca de Prompts

Una aplicació web senzilla per gestionar i organitzar els teus prompts per a IAG i VibeCoding.

## ✨ Característiques

- ✅ **CRUD Complet**: Afegir, editar i eliminar prompts
- 🔍 **Cerca avançada**: Cerca per títol, descripció o contingut
- 🏷️ **Sistema d'etiquetes**: Organitza i filtra per categories
- 📋 **Copiar ràpid**: Botó per copiar prompts al portapapers
- 💾 **Exportar/Importar**: Fes còpies de seguretat en format JSON
- 🔄 **Sincronització GitHub**: Puja i baixa els prompts del repositori
- 📱 **Responsive**: Funciona perfectament en mòbil i escriptori
- 🎨 **Interfície moderna**: Disseny atractiu i fàcil d'usar
- 💻 **Treball offline**: Funciona amb localStorage, sincronitza quan vulguis

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

### Sincronitzar amb GitHub

1. **Configurar GitHub**:
   - Clica el botó **"⚙️ Configurar GitHub"**
   - Omple els camps:
     - Nom d'usuari de GitHub
     - Nom del repositori (el mateix on tens l'aplicació)
     - Token d'accés personal (veure instruccions a continuació)
   - La configuració es guarda al localStorage

2. **Crear Token d'Accés Personal**:
   - Ves a GitHub → Settings → Developer settings
   - Personal access tokens → Tokens (classic)
   - Generate new token (classic)
   - Marca només el permís **`repo`**
   - Copia el token i enganxa'l a l'aplicació

3. **Pujar i baixar prompts**:
   - **⬆️ Pujar a GitHub**: Guarda els prompts del navegador al repositori
   - **⬇️ Baixar de GitHub**: Carrega els prompts del repositori al navegador
   - Els prompts es guarden a `prompts.json` a l'arrel del repositori

4. **Flux de treball recomanat**:
   - Treballa normalment amb l'aplicació (localStorage)
   - Quan acabis la sessió, puja els prompts a GitHub
   - Des d'un altre dispositiu, baixa els prompts de GitHub
   - Així tens sempre els prompts sincronitzats!

## 💾 Emmagatzematge

L'aplicació utilitza un **sistema híbrid** d'emmagatzematge:

### localStorage (Treball local)
- Les dades es guarden localment al teu navegador
- ✅ Treball ràpid i offline
- ✅ No necessites connexió a internet
- ⚠️ Les dades només estan disponibles en aquest navegador

### GitHub (Sincronització)
- Els prompts es poden sincronitzar amb el repositori
- ✅ Còpia de seguretat automàtica
- ✅ Accés des de diferents dispositius
- ✅ Control de versions (historial de canvis)
- 💡 Fitxer `prompts.json` a l'arrel del repositori

### Recomanacions
- Treballa normalment amb localStorage per rapidesa
- Puja els prompts a GitHub al final de cada sessió
- Des d'altres dispositius, baixa els prompts abans de començar
- Fes exportacions manuals (JSON) periòdicament com a còpia extra

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

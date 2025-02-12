# LEA (Language Enhanced Anki Template)

<center><img src="https://raw.githubusercontent.com/nath444/lea/f6e640eda26d4017ce92258b98990a64aa004696/lea%20logo.svg" width="50%"></center>

A modern, feature-rich Anki template designed for language learning, with special support for Chinese and English.

## Fonctionnalités 

### Universal Features [U]
- 🌙 Dark mode support
- 🔄 Interactive example toggles (show/hide translations)
- 🎯 Word type badges (Adjective, Verb, Noun, etc.)
- 🌍 Country and region flags support
- 🔊 Text-to-Speech for words and examples
- 📝 Grammar categories
- 💾 Local storage for user preferences

### Chinese-Specific Features [ZH]
- 🀄 Pinyin display for words and examples
- 📚 Chinese radicals support
- 🈺 Character decomposition
- 🗣️ Automatic pinyin generation

## Insertion des champs

Tous les paquets comportent des intitulés de champs suivant ce format :

<table>
   <thead>
      <tr>
         <th>Nom de champ</th>
         <th>Description</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td><b>mot_src</b></td>
         <td>Mots dans la langue d'origine</td>
      </tr>
      <tr>
         <td><b>mot_trad</b></td>
         <td>Mots dans la langue cible</td>
      </tr>
      <tr>
         <td><b>image</b></td>
         <td>URL de l'image associée au mot (facultatif)</td>
      </tr>
      <tr>
         <td><b>exemple_src</b></td>
         <td>Exemple d'utilisation du mot dans la langue d'origine (facultatif)</td>
      </tr>
      <tr>
         <td><b>exemple_trad</b></td>
         <td>Exemple d'utilisation du mot dans la langue cible (facultatif [selon les cas]*)</td>
      </tr>
      <tr>
         <td><b>grammaire</b></td>
         <td>Catégories grammaticales du mot dans la langue d'origine (facultatif [selon les cas]*)</td>
      </tr>
      <tr>
         <td><b>source</b></td>
         <td>Contexte dans lequel le mot a été vu pour la première fois (facultatif)</td>
      </tr>
   </tbody>
</table>

### 1. **Mots dans la langue source**

Le titre doit être écrit dans la langue source et doit suivre les règles de formatage suivantes :
- [si autres définitions] séparation obligatoire avec des « ; » (sans espace après)

2. **Mots dans la langue cible**

Veillez respecter les règles de formatage suivantes :
- [facultatif] codes pays ISO 3166-2 des pays, collés si plusieurs (ex : FR, VEES, etc.)
- [facultatif] code région (ex : 001, 002, etc.)
- [facultatif] détails entre crochets qui seront affichés en bas de la définition
- [si autres définitions] séparation obligatoire avec des « ; » (sans espace après)

Exemple : (sciences) physique ;ES étrenner [faire usage d’une chose pour la première fois]

<center><img src="https://i.postimg.cc/hGMrnn7N/definitions.png" height="80"></center>
<center><i><p style="color:grey">— Affichage de l'exemple.</p></i></center>

3. **URL de l'image associée au mot (facultatif)**

Si vous avez choisi d'inclure une image associée au mot, veillez à respecter les règles suivantes :
- Vérifier que l'URL est valide et pointe vers une image au format compatible avec votre plateforme.

4. **Exemple de l'utilisation du mot dans la langue source (facultatif)**

Si vous avez choisi d'inclure un exemple d'utilisation du mot dans la langue source, veillez à respecter les règles de grammaire et de syntaxe de la langue en question.

Vous devez également respecter les règles de formatage suivantes :
- [ZH] phrase en caractères chinois

5. **Exemple de l'utilisation du mot dans la langue cible (facultatif)**

6. **Catégories grammaticales du mot dans la langue source (facultatif)**

Si vous avez choisi d'inclure les catégories grammaticales du mot dans la langue source, veuillez à respecter les règles suivantes :
- Séparer les différentes catégories grammaticales avec des « ; »

7. **Source (facultatif)** :

Veuillez à respecter les règles suivantes :
- URL de la source en texte plein

### Language Tags
Use these tags at the beginning of your cards:
- `[ZH]` - Chinese cards
- `[EN]` - English cards

### Region Codes
Add region codes before words to display regional flags:
- `001` - North America
- `002` - South America
- `003` - Europe
- `004` - Africa
- `005` - Asia

## Classification des parties du discours

Pour utiliser la classification des parties du discours inclue de base avec LEA, vous devez renseignez votre carte dans un sous-paquet du nom des classes grammaticales ci-dessous (les abréviations et couleurs suivantes seront utilisées) :

<table>
	<thead>
		<tr>
			<th>Classe grammaticale</th>
			<th>Abréviation</th>
			<th>Parties du discours incluses</th>
			<th>Catégorisation complète obligatoire</th>
			<th>Couleur HTML</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Adjectifs</td>
			<td>ADJ.</td>
			<td>Mots qui modifient ou précisent les noms.</td>
			<td>-</td>
			<td><span style='color:#037bff'>037bff</span></td>
		</tr>
		<tr>
			<td>Adverbes</td>
			<td>ADV.</td>
			<td>Mots qui modifient ou précisent les verbes et les adjectifs.</td>
			<td>-</td>
			<td><span style='color:#fec009'>fec009</span></td>
		</tr>
		<tr>
			<td>Divers</td>
			<td>DIV.</td>
			<td>Mots qui servent à relier des mots ou des phrases entre eux, mots qui indiquent la possession, mots qui expriment une émotion ou un sentiment, et toutes les autres parties du discours qui ne peuvent être regroupées ailleurs.</td>
			<td>Oui*</td>
			<td><span style='color:#6c757d'>6c757d</span></td>
		</tr>
		<tr>
			<td>Expressions</td>
			<td>EXP.</td>
			<td>Locutions verbales qui ne peuvent être traduites mot à mot.</td>
			<td>-</td>
			<td><span style='color:#14a3b9'>14a3b9</span></td>
		</tr>
		<tr>
			<td>Noms</td>
			<td>NOM</td>
			<td>Mots qui désignent des personnes, des choses, des qualités, etc.</td>
			<td>-</td>
			<td><span style='color:#28a644'>28a644</span></td>
		</tr>
		<tr>
			<td>Verbes</td>
			<td>VERBE</td>
			<td>Mots qui expriment l'action ou l'état.</td>
			<td>-</td>
			<td><span style='color:#dc3444'>dc3444</span></td>
		</tr>
	</tbody>
</table>

## Détails

## Dependencies
- Bootstrap 5.3.3
- Bootstrap Icons
- CNChar (for Chinese character handling)
- PapaParse
- Flag Icons CSS

## Installation
1. Copy the template files to your Anki collection
2. Create a new note type using these templates
3. Import the required CSS and JavaScript files

## Customization
- Edit `style.css` for visual customization
- Modify `front.php` and `back.php` for template changes
- Adjust JavaScript functions for behavior modifications

## Browser Compatibility
- Works with modern browsers supporting ES6
- Requires localStorage for saving preferences
- Needs internet connection for CDN resources

## Version
Current Version: 3.5 (Beta) - 2025
